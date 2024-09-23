```space-style
/* ------------------------------------------------------------------------- */
/* # Main Editor Area  */
/* ------------------------------------------------------------------------- */

html[data-theme="light"] #sb-main {
  background-color: #fcfcfd; /*TODO - assign variable + dark theme */
}

/* Move Editor to Left */
#sb-main .cm-editor .cm-content {  
  /*width: 100%;*/
  margin-left: 1em;
  margin-right: auto;
  min-height: unset;
}

/* Change Colors, Add Shadow */
/* TODO same for dark theme */
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

/* ## Text Selections */
#sb-main #sb-editor .cm-editor .cm-scroller .cm-content ::selection {
  background-color: var(--selection-background-color) !important;
}

#sb-top .main .inner .wrapper .sb-mini-editor .cm-editor .cm-scroller .cm-line::selection {
  background-color: var(--melon-top-selection-color); /* Selection in Top Bar (aka page name) */
}

```
