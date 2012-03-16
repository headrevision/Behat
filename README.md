Formatters that distinguish between an error and a failure in terms of xUnit's notion
=====================================================================================

See https://github.com/Behat/Behat/issues/111

* A failed step is the equivalent of an error in xUnit.
* A false step is the equivalent of a failure in xUnit (colored magenta by the formatters).
* Actually a false step is a failed step too, it is just a fine-grained interpretation of a failed step (complementarily there can be non-false steps among failed steps).

ProgressWithFalseStepsFormatter
-------------------------------

https://github.com/headrevision/Behat/blob/falsesteps/src/Behat/CommonFormatters/ProgressWithFalseStepsFormatter.php

![ProgressWithFalseStepsFormatter](https://raw.github.com/headrevision/Behat/falsesteps/progress_with_false_steps_formatter.png "ProgressWithFalseStepsFormatter")

PrettyWithFalseStepsFormatter
-----------------------------

https://github.com/headrevision/Behat/blob/falsesteps/src/Behat/CommonFormatters/PrettyWithFalseStepsFormatter.php

![PrettyWithFalseStepsFormatter](https://raw.github.com/headrevision/Behat/falsesteps/pretty_with_false_steps_formatter.png "PrettyWithFalseStepsFormatter")

HtmlWithFalseStepsFormatter
---------------------------

https://github.com/headrevision/Behat/blob/falsesteps/src/Behat/CommonFormatters/HtmlWithFalseStepsFormatter.php

![HtmlWithFalseStepsFormatter](https://raw.github.com/headrevision/Behat/falsesteps/html_with_false_steps_formatter.png "HtmlWithFalseStepsFormatter")

Copyright
---------

See LICENSE for details.
