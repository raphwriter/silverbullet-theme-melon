```space-style
/* ------------------------------------------------------------------------- */
/* # Forms */
/* ------------------------------------------------------------------------- */
/* ## Buttons */
#sb-editor .sb-button, .sb-button-primary,
#sb-editor div.cm-content div.sb-markdown-top-widget div.content button {
  box-shadow: none;
  border-radius: var(--melon-border-radius-button);
  padding: 0.4em 0.7em;
  font-size: .95em;
  font-family: var(--editor-font);
  border: 1px solid var(--button-border-color);
}
#sb-editor .sb-button.sb-button-primary, .sb-button-primary.sb-button-primary,
#sb-editor div.cm-content div.sb-markdown-top-widget div.content button {
  --color: var(--primary-button-color);
  --background-color: var(--primary-button-background-color);
  --hover-background-color: var(--primary-button-hover-background-color);
  --border-color: var(--primary-button-border-color);
  font-weight: 400;
}
#sb-main .cm-editor .sb-command-button {
  padding: 0.2em 0.4em;
}

#sb-editor div.cm-content div.sb-markdown-top-widget div.content button {
  padding: 0.2em;
}

#sb-main .cm-editor .sb-command-button::after {
  content: " ‣";
}

#sb-main #sb-editor .cm-editor .cm-panels .cm-search.cm-panel button.cm-button {
  color: var(--melon-button-color);
}
```
