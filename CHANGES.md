# CHANGELOG

## 1.2.8

- Updated to work with Bootstrap 4. Bootstrap 3 is still the default mode.
- Allow to establish the placement of the popover through an option.
- Make the css classes added to the bar and verdicts customizable.
- Bugfix in the progress bar percentage calculation for a score of zero.

## 1.2.7

- Bugfix: escape special characters in username for regex.

## 1.2.6

- More sensible default score for sequences rule.
- Publish plugin in npm.

## 1.2.5

- Bugfix when using zxcvbn and form inputs with empty values.
- New option to specify a list of banned words for zxcvbn.

## 1.2.4

- Standardise name on pwstrength-foundation
- Fixed zxcvbn demo
- Now on bower

## 1.2.3

- First release to support Zurb Foundation, forked from ablanco/jquery.pwstrength.bootstrap v 1.2.2
- The lack of a built in orange warning state for progress bars is posing a problem, we might have to add it
- Basic support for progress bar, though text in progress bar requires extra styling
- Verdicts outputted to Foundation .postfix, if existing
- Errors outputted to Foundation Error states
- Popover not currently supported
