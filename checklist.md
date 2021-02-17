# WAVE errors

Resolving errors flagged by WAVE tool (Chrome extension).

## Color contrast
- #a6a6a6 on white background: too light
- #9d9d9d on dark gray background: too dark

## Alt text
- [x] Images missing alt text: scalar logo and white overlay (1x1white_trans.png)
  9/9/20 - added alt attributes
- [x] Linked image missing alt text: fullscreen button
  9/9/20 - added alt attribute

## Forms
- [x] Missing form label - top menu search uses placeholder to label instead of proper label: added 'title' attribute
- [x] Empty button - added 'value' attribute

### Hidden errors
- 227 Empty link - all ARIA hidden
- 2 Broken ARIA references - all hidden
- 6 Broken ARIA menu - also hidden
