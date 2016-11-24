# Babel + Inline HTMLBars Highlighting

Adds syntax highlighting for inline htmlbars to the [language-babel](https://github.com/gandm/language-babel) package.


Notes:
Thank you [language-babel](https://github.com/gandm/language-babel) and [language-ember-htmlbars](https://github.com/jmurphyau/language-ember-htmlbars) for the regex patterns.

This atom package combines the two to allow for syntax highlighting of inline Ember template declarations.


### TODO:
- [] Check if JSX has html patterns for use
- [x] Move htmlbars core to separate file
- [] Add real `increaseIndentPattern` && `decreaseIndentPattern` regexes in settings
- [x] Create a specific parsing rule for inline hbs instead of using quasi-js
- [x] Migrate html and htmlbars patterns to repo
