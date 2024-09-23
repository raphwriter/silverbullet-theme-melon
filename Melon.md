---
tags: theme
aliases: 
  - "theme"
  - "melon"
  - "melon-theme-sb"
pageDecoration: 
  prefix: "🍉 "
---
# General
```space-style

/* ------------------------------------------------------------------------- */
/* HTML & VARS */
/* ------------------------------------------------------------------------- */

html {
  --editor-width: 960px;
}
```

# Light Theme
```space-style
html[data-theme="light"] {
  --root-color: #212122;

  /* Custom Variables */
  --selection-background-color: #3cad9e54;
  --shadow-main: 1px 1px 4px 1px #aaa;
  --editor-main-background-color: #fcfcfc;
  --editor-main-box-shadow: 1px 1px 4px 1px #ddd;
  --editor-secondary-box-shadow: 2px 3px 4px -1px #aaa;
  --editor-top-widget-background-color: #eae8d754;
  --melon-border-radius-button: 3px;
  --melon-color: #3cad9e;
  --melon-color-text: #256a61;
  --melon-color-text-negative: #ebebeb;
  --melon-media-image-box-shadow: 1px 2px 4px -1px #ccd;
  --melon-media-image-border-color: var(--melon-secondary-background-border-color);
  --melon-placeholder-color: var(--root-color);
  --melon-secondary-background-color: #647479;
  --melon-secondary-background-border-color: #e8e8e8;
  --melon-secondary-color: #d2d2d2;
  --melon-top-selection-color: #187166f5;
  --melon-unsaved-color: #d6222e;
  --melon-unsaved-border-color: white;
  
  
  /* SilverBullet Variables Overrides */
  --action-button-background-color: transparent;
  --action-button-color: var(--melon-color-text-negative);
  --action-button-hover-color: #f0b11d;
  --action-button-active-color: #f0b11d;

  --button-color: #333;
  --button-background-color: #efefef;
  --button-hover-background-color: #ccc;
  --button-border-color: #d2d2d2;
  
  --primary-button-color: white;
  --primary-button-background-color: var(--melon-color);
  --primary-button-hover-background-color: var(--melon-color-text);
  --primary-button-border-color: var(--melon-color-text);
  
  --editor-command-button-color: #333;
  --editor-command-button-background-color: var(--melon-secondary-color);
  --editor-command-button-border-color: var(--melon-secondary-background-border-color);
  --editor-command-button-hover-background-color: var(--editor-main-background-color);
  
  --editor-code-atom-color: #003e51;
  --editor-code-background-color: hsl(120 1% 95% / 1);
  --editor-code-number-color: #0198a8;
  --editor-code-string-color: #ce0676;
  --editor-code-typename-color: #095e6c;
  --editor-code-variable-color: var(--melon-color-text);
  --editor-directive-color: #333;
  --editor-directive-background-color: #3c73ad2e;
  --editor-frontmatter-background-color: #f0eab4;
  --editor-frontmatter-border-color: #c6ba4f;
  
  --editor-hashtag-color: var(--melon-color-text-negative);
  --editor-hashtag-background-color: var(--melon-color);
  --editor-hashtag-border-color: var(--melon-color);
  --editor-highlight-background-color: #d6222e24;
  --editor-link-color: #35290d;
  --editor-meta-color: #b30e63;
  --editor-naked-url-color: var(--melon-color-text);
  --editor-panels-bottom-color: var(--melon-secondary-color);
  --editor-panels-bottom-background-color: var(--melon-secondary-background-color);
  --editor-panels-bottom-border-color: var(--melon-secondary-background-border-color);
  --editor-table-head-background-color: #647479;
  --editor-table-head-color: #d2d2d2;
  --editor-wiki-link-page-color: var(--editor-link-color);
  --editor-wiki-link-page-background-color: #ffb50670;

  --link-color: #d90033;
  --link-missing-color: #d90033;

  --modal-header-label-color: var(--melon-color);
  --modal-selected-option-background-color: #eef4f4;
  --modal-selected-option-color: var(--melon-color);
  --modal-description-color: var(--melon-color);
  --modal-hint-color: #eee;
  --modal-hint-background-color: #333;
  --modal-help-background-color:; /*TODO*/

  --panel-border-color: #d1d1d1;
  
  --top-background-color: #c4c5c5;
  --top-color: #eee;
  --top-saved-color: #ebebeb;
  --top-unsaved-color: var(--top-saved-color);
  --top-loading-color: #6dbd8c;
  --top-border-color: #f0b11d;
  --top-sync-error-color: black;
  --top-sync-error-background-color: yellow;

  --ui-accent-color: #464cfc;
}
```

# Dark Theme
```space-style
html[data-theme="dark"] {
  /* Custom Variables */
  --editor-top-widget-background-color: var(--editor-code-background-color);
  --editor-main-background-color: #2a2b2b;
  --editor-main-box-shadow: 1px 1px 4px 1px #ddd;
  --editor-secondary-box-shadow: 2px 3px 5px 1px #111;
  
  --melon-button-color: var(--root-color);
  --melon-color: #3e6f68;
  --melon-color-text: #090e0e;
  --melon-color-text-negative: #ebebeb;
  --melon-placeholder-color: var(--root-color);
  --melon-unsaved-color: #d6222e;
  --melon-unsaved-border-color: white;
  --melon-secondary-background-color: #383d3f;
  --melon-secondary-background-border-color: #181a1a;
  --melon-secondary-color: #d2d2d2;
  --melon-top-selection-color: #383d3ff5;

  
  /* SilverBullet Variables Overrides */
  --root-color: #dedede;
  --root-background-color: #1c1d20;
  --selection-background-color: #383d3ff5;

  --action-button-background-color: transparent;
  --action-button-color: var(--melon-color-text-negative);
  --action-button-hover-color: var(--melon-color-text);
  --action-button-active-color: var(--melon-color-text);

  --button-background-color: #efefef;
  --button-border-color: #d2d2d2;
  --button-color: #333;
  --button-hover-background-color: #ccc;

  --editor-code-atom-color: #ce6c91;
  --editor-code-info-color: #eee;
  --editor-code-number-color: #b485d9;
  --editor-code-string-color: #c094e1;
  --editor-code-typename-color: #13bb5a;
  --editor-code-variable-color: #7bc7e8;
  
  --editor-command-button-color: var(--melon-color-text);
  --editor-command-button-background-color: var(--melon-color);
  --editor-command-button-border-color: var(--melon-color-text);

  --editor-frontmatter-background-color: rgba(51, 50, 51, 0.5);
  --editor-frontmatter-border-color: #7e405a;
  --editor-frontmatter-marker-color: #576462;
  --editor-hashtag-background-color: var(--melon-color);
  --editor-highlight-background-color: #72735f4f;
  --editor-link-color: #66bdaf; /*#a4c2bd;*/
  --editor-meta-color: #5f99cc;
  
  --editor-wiki-link-page-background-color: none;
  --editor-wiki-link-page-color: var(--editor-link-color);
  --editor-wiki-link-page-missing-color: #aa7373;

  --link-color: var(--editor-link-color);
  --link-missing-color: var(--editor-wiki-link-page-missing-color);
  
  --modal-background-color: #644c60;
  --modal-border-color: #644c60;
  --modal-color: #dbe4e2;
  --modal-header-label-color: #8ec2ba;
  --modal-help-background-color: #3336;
  
  --primary-button-color: var(--melon-color-text-negative);
  --primary-button-background-color: var(--melon-color);
  --primary-button-hover-background-color: var(--melon-color-text);
  --primary-button-border-color: var(--melon-color-text);
  
  --text-field-background-color: #373737;
  
  --top-saved-color: #ececec;
}

```
#asd
[[asdfasdf]]
[[01 Journal/2024/08/2024-08-08]]