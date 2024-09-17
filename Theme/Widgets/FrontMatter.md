```space-style
/* ## Front Matter */
#sb-root #sb-main #sb-editor .cm-editor .cm-scroller .cm-content.cm-lineWrapping .sb-frontmatter.cm-line {
  padding: 0 1em; 
  border-left: 3px solid var(--editor-frontmatter-border-color);
  margin-left: -21px;
}
/* add margin after frontmatter for paragraphs */
.sb-frontmatter.cm-line + .cm-line:not(.sb-frontmatter) {
  /*margin-top: 1em;*/
}
```

do not add margin to headings, it messes with sb cursor behaviour #til #silverbullet