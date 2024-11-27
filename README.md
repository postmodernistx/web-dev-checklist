# Web Development checklist
Example of a personal checklist.

## General
- [ ] Avoid Swenglish

## HTML
### Conventions
- [ ] Capital letters in CSS
- [ ] Unified naming convention/same standard across document

### Images
- [ ] Proper alt text on images, [see Harvard website](https://accessibility.huit.harvard.edu/describe-content-images) for examples
- [ ] Width and height attributes
- [ ] Lazy loading (or eager): `<img loading="lazy">`

### Accessibility
- [ ] Aria labels on buttons with no text
- [ ] Tabbing works
- [ ] Proper `lang` attributte on `<html>` tag
- [ ] Go through [this checklist](https://www.a11yproject.com/checklist/)
- [ ] Go through [inclusive design checklist from Heydon Pickering](https://github.com/Heydon/inclusive-design-checklist)

### Validation
- [ ] Check [W3C HTML Validator](https://validator.w3.org/#validate_by_input)
- [ ] Check [CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) (Note! Generated CSS code, not Sass)
- [ ] Check [HTML5 Outliner](https://gsnedders.html5.org/outliner/)
- [ ] Chrome Lighthouse
- [ ] Firefox accessibility

## CSS
- [ ] [Unified naming for classes](https://en.wikipedia.org/wiki/Naming_convention_(programming)#Examples_of_multiple-word_identifier_formats)
- [ ] Always using `min-height` instead of `height`
- [ ] Font size is set in `rem` or `em`

### JavaScript
- [ ] Turn off JavaScript and see how the page is rendered: [Chrome](https://developer.chrome.com/docs/devtools/javascript/disable) | [Firefox](https://support.mozilla.org/en-US/kb/javascript-settings-for-interactive-web-pages#w_for-advanced-users)


And so forth…
