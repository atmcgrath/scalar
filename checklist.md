# WAVE errors

Resolving errors flagged by WAVE tool (Chrome extension).

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

## Color contrast

- #a6a6a6 on white background: too light
- #9d9d9d on dark gray background: too dark

### Custom CSS to fix contrast issues

```{css}
/*on dark background - make lighter */
/*author attribution in site header */
.author_text {color: #DDDDDF;}
/*media file text*/
.attribution{color: #C0C1C4;}

/*on white bg - make darker*/
/*top-left path link*/
.path-breadcrumb, .path-breadcrumb a {color:#444444;}
/*media details on page */
.mediainfo div {color:#444444 !important;}
.media_tab.select {background-color:#444444 !important; color:white !important;}

/*blue buttons - text lighter, bg darker*/
a.btn-primary {background-color: #02547E; color: white;}
path-breadcrumb {
    color: #000000 !important;
}
```
