```space-style
/* ------------------------------------------------------------------------- */  
/* # Widgets & Front Matter */
/* ------------------------------------------------------------------------- */

#sb-main .sb-panel:first-child {
  /*border-right: none;*/
  border-right: 1px dashed var(--panel-border-color);
  /*padding-right: 0.2em;*/
}

/* ## Widgets Top */
#sb-main .cm-editor .sb-markdown-top-widget {
  background-color: var(--editor-top-widget-background-color);
  border: none;
  border-bottom: 1px dashed var(--panel-border-color);
  border-radius: 0;
  font-size: 0.9em;
  /*margin-bottom: 1.3em;*/
  margin-inline: -20px;
  padding: 1em;
  min-height: unset;
}    

#sb-main .cm-editor .sb-markdown-top-widget h1 {
  padding: .1em;
}

/* ## Widgets Bottom */
#sb-root #sb-main #sb-editor .cm-editor .cm-content .sb-markdown-bottom-widget {
  background-color: var(--editor-top-widget-background-color);
  border: none;
  border-top: 1px dashed var(--panel-border-color);
  border-radius: 0;
  font-size: 0.9em;
  margin-inline: -20px;
  padding: 1em;
}

#sb-root #sb-main #sb-editor .cm-editor .cm-content .sb-markdown-bottom-widget h1 {
  background: none;
}

#sb-main .cm-editor .sb-markdown-bottom-widget:has(*),
#sb-editor div.cm-content div.sb-fenced-code-iframe.sb-line-fenced-code {
  font-family: var(--editor-font);
}

```
