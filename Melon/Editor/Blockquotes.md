```space-style
/* ## Blockquotes */
#sb-main .cm-editor .sb-blockquote-outside,
#sb-main .cm-editor .sb-line-blockquote.cm-line {
  border-width: 2px;
  font-style: italic;
  margin-top: 1em;
  padding: 3px 0;
  padding-left: 10px;
  text-indent: -3px; /* not quite ideal, value may depend on font choice */
}
/* Remove Top Margin From Adjacent Blockquote Lines */
#sb-main .cm-editor .sb-blockquote-outside + .sb-blockquote-outside,
#sb-main .cm-editor .sb-line-blockquote.cm-line + .sb-line-blockquote.cm-line {
  margin-top: 0;
}

```
