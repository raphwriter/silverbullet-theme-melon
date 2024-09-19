```space-style
/* ------------------------------------------------------------------------- */
/* # Overlays */
/* ------------------------------------------------------------------------- */
/* ## Modals (Rename Dialog, Confirm Delete Dialog, ...) */
#sb-root .sb-modal-box {
  border-radius: 0;
  box-shadow: var(--editor-secondary-box-shadow);
  font-family: var(--editor-font);
}
#sb-root .sb-modal-box .sb-header label {
  color: var(--melon-color);
}
#sb-root .sb-modal-box .sb-header .sb-mini-editor .cm-editor .cm-content .cm-line {
  font-family: var(--editor-font);
}
#sb-root .sb-modal-box .sb-help-text {
  font-size: .9em;
}
.sb-highlight {
  padding: 1px 2px;
}


/* ## Text Selection */
#sb-main #sb-editor .cm-editor .cm-scroller .cm-content ::selection {
  background-color: var(--selection-background-color) !important;
}
#sb-top .main .inner .wrapper .sb-mini-editor .cm-editor .cm-scroller .cm-line::selection {
  background-color: var(--melon-top-selection-color);  /*Selection in Top Bar*/
}

/* ## Notifications */
#sb-top .main .inner .wrapper .sb-notifications {
  top: 50px;
}
#sb-top .main .inner .wrapper .sb-notifications > div {
  opacity: 1;
  /*animation: fade cubic-bezier(.95, 0, .15, 1) 2s;*/
  background-color: var(--melon-color);
  border: 1px dashed var(--melon-color-text);
  border-radius: 3px;
  margin-bottom: 3px;
  margin-top: 0.5em;
  padding: 0.6em;
  color: var(--melon-color-text-negative);
}

/* ## Search & Replace */
#sb-main #sb-editor .cm-search.cm-panel {
  padding-top: .3em;
  box-shadow: 0px 0px 8px -2px #313131 inset;
  font-size: 1.2em;
  font-family: var(--editor-font);
}

#sb-main #sb-editor .cm-search.cm-panel label {
  font-size: .85em;
  color: var(--melon-secondary-color);
}

#sb-main #sb-editor .cm-search.cm-panel .cm-button {
  color: #333;
}

```