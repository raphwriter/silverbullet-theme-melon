```space-style
/* ------------------------------------------------------------------------- */
/* # Main Editor Area  */
/* ------------------------------------------------------------------------- */
html[data-theme="light"] #sb-main {
  background-color: #fcfcfd;
  /* candidates: #647479, #f3f6f7, #fcfcfd */
}


/* Move Editor to Left */
#sb-main .cm-editor .cm-content {  
  /*width: 100%;*/
  margin-left: 1em;
  margin-right: auto;
  min-height: unset;
}


/* Change Colors, Add Shadow */
html[data-theme="light"] #sb-main .cm-editor .cm-content {  /* Add Box Shadow to Editor */
  background-color: var(--editor-main-background-color);
  box-shadow: var(--editor-main-box-shadow);
  padding-block: 0;
  /*border-inline: 1px solid #d7d7d7;*/
}


#sb-main #sb-editor .cm-scroller .cm-content .sb-code,
#sb-main .cm-editor .cm-line.sb-line-fenced-code {
  padding-inline: 0.4em;
  padding-block: 0.4em;
}

#sb-main .cm-editor .cm-line.sb-line-fenced-code + .sb-line-fenced-code {
  padding-block: 0;
}


/* ## Blockquotes */
#sb-main .cm-editor .sb-blockquote-outside,
#sb-main .cm-editor .sb-line-blockquote.cm-line {
  border-width: 2px;
  text-indent: unset;
  padding: 3px 0;
  margin-top: 1em;
  padding-left: 10px;
}
/* Remove Top Margin From Adjacent Blockquote Lines */
#sb-main .cm-editor .sb-blockquote-outside + .sb-blockquote-outside,
#sb-main .cm-editor .sb-line-blockquote.cm-line + .sb-line-blockquote.cm-line {
  margin-top: 0;
}


```
