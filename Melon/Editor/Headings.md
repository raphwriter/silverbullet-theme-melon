# Heading
```space-style
/* ## Headings  */
#sb-main .cm-editor .cm-line.sb-line-h1, 
#sb-main .cm-editor .sb-markdown-top-widget :is(h1,h2,h3,h4,h5,h6),
#sb-main .cm-editor .cm-line:is(.sb-line-h1, .sb-line-h2, .sb-line-h3, .sb-line-h4, .sb-line-h5, .sb-line-h6) {
  font-weight: unset;
  font-family: var(--ui-font);
  padding-block: 1em 0.3em;
}

#sb-main .cm-editor .cm-content div.cm-line.sb-line-h1:nth-of-type(1),
#sb-main .cm-editor .cm-content div.cm-line:is(.sb-line-h1, .sb-line-h2, .sb-line-h3, .sb-line-h4, .sb-line-h5, .sb-line-h6):nth-of-type(1),
#sb-main .cm-editor .cm-content > div.cm-line.sb-line-h1:first-of-type {
  padding-top: 0;
  margin-top: 0;
}

/* no text indent when cursor in heading */
#sb-editor div.cm-scroller div.cm-content div.sb-header-inside.cm-line {
  text-indent: 0;
}

/* Apply (somewhat) modular scale to headings (https://alistapart.com/article/more-meaningful-typography/) */
#sb-main .cm-editor .sb-line-h1, #sb-main .cm-editor h1 {font-size: 2.25em;}
#sb-main .cm-editor .sb-line-h2, #sb-main .cm-editor h2 {font-size: 1.75em;}
#sb-main .cm-editor .sb-line-h3, #sb-main .cm-editor h3 {font-size: 1.3em;}
#sb-main .cm-editor .sb-line-h4, #sb-main .cm-editor h4 {font-size: 1em;}
#sb-main .cm-editor .sb-line-h5, #sb-main .cm-editor h5 {font-size: 0.8em;}
#sb-main .cm-editor .sb-line-h6, #sb-main .cm-editor h6 {font-size: 0.75em;}

/* no whitespace between sibling headings */
#sb-root #sb-main #sb-editor .cm-scroller .cm-content .sb-line-h1 + .sb-line-h2,
#sb-root #sb-main #sb-editor .cm-scroller .cm-content .sb-line-h2 + .sb-line-h3,
#sb-root #sb-main #sb-editor .cm-scroller .cm-content .sb-line-h3 + .sb-line-h4,
#sb-root #sb-main #sb-editor .cm-scroller .cm-content .sb-line-h4 + .sb-line-h5,
#sb-root #sb-main #sb-editor .cm-scroller .cm-content .sb-line-h5 + .sb-line-h6 {
  padding-top: 0;
}
```


```

```
