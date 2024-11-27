# Web Development checklist
Example of a personal checklist.

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

And so forth…
