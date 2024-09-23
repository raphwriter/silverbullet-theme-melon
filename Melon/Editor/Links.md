```space-style
/* ## Links */
#sb-main .cm-editor .sb-markdown-top-widget a.wiki-link,
#sb-main .cm-editor .sb-markdown-top-widget .sb-wiki-link-page-missing,
#sb-main #sb-editor .cm-editor .cm-scroller .cm-content a.sb-wiki-link-page-missing,
#sb-main #sb-editor .cm-editor .cm-scroller .cm-content a.sb-wiki-link-page,
#sb-main #sb-editor .cm-editor .cm-scroller .cm-content .sb-markdown-bottom-widget div.content #span.p a.wiki-link,
#sb-main .cm-editor .sb-markdown-widget a.wiki-link
{
  background: none;
  border-bottom: 1px solid var(--link-color);
  border-radius: 0;
  text-decoration: none;
  color: var(--link-color);
  padding-inline: 0.1em;
}

/* Broken Links and Links to Missing Pages */
#sb-main .cm-editor .sb-markdown-top-widget .sb-wiki-link-page-missing,
#sb-main #sb-editor .cm-editor .cm-scroller .cm-content a.sb-wiki-link-page-missing {
  border-bottom: 1px dashed var(--link-color);
}
a.sb-wiki-link-page-missing, .sb-wiki-link-page-missing > .sb-wiki-link-page {
  background: none;
}

/* External URLs */
#sb-main .cm-editor .sb-naked-url::after {
  content: "↗"
}


/* ## Hashtags */
#sb-main .cm-editor .sb-hashtag, 
#sb-main .cm-editor .hashtag {
  border-radius: 4px;
  border: none;
  padding: 3px 5px;
  margin: 0 1px 0 0;
  font-size: 0.9em;
}

```
