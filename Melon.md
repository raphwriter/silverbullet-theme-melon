---
tags: theme
aliases: 
  - "theme"
  - "melon"
  - "melon-theme-sb"
pageDecoration: 
  prefix: 🍉
---
```space-style

/* ------------------------------------------------------------------------- */
/* HTML & VARS */
/* ------------------------------------------------------------------------- */

html {
  --editor-width: 960px;
}

html[data-theme="light"] {
  --root-color: #212122;

  /* Custom Variables */
  --selection-background-color: #3cad9e54;
  --shadow-main: 1px 1px 4px 1px #aaa;
  
  --editor-main-background-color: #fcfcfc;
  --editor-main-box-shadow: 1px 1px 4px 1px #ddd;
  --editor-secondary-box-shadow: 2px 3px 4px -1px #aaa;
  --editor-top-widget-background-color: #eae8d754;
  --melon-color: #3cad9e;
  --melon-color-text: #256a61;
  --melon-color-text-negative: #ebebeb;
  --melon-unsaved-color: #d6222e;
  --melon-unsaved-border-color: white;
  --melon-secondary-background-color: #647479;
  --melon-secondary-background-border-color: #e8e8e8;
  --melon-secondary-color: #d2d2d2;
  --melon-top-selection-color: #187166f5;
  --melon-media-image-box-shadow: 1px 2px 4px -1px #ccd;
  --melon-media-image-border-color: var(--melon-secondary-background-border-color);
  --melon-border-radius-button: 3px;
  
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
  
  --modal-selected-option-background-color: #eef4f4;
  --modal-selected-option-color: var(--melon-color);
  --modal-description-color: var(--melon-color);
  --modal-hint-color: #eee;
  --modal-hint-background-color: #333;

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

html[data-theme="dark"] {
  --root-color: #dedede;
  --selection-background-color: #383d3ff5;

  --editor-main-background-color: #2a2b2b;
  --editor-main-box-shadow: 1px 1px 4px 1px #ddd;
  --editor-secondary-box-shadow: 2px 3px 4px -1px #aaa;
  --editor-top-widget-background-color: #eae8d754;
  
  --melon-color: #3e6f68;
  --melon-color-text: #090e0e;
  --melon-color-text-negative: #ebebeb;
  --melon-unsaved-color: #d6222e;
  --melon-unsaved-border-color: white;
  --melon-secondary-background-color: #383d3f;
  --melon-secondary-background-border-color: #181a1a;
  --melon-secondary-color: #d2d2d2;
  --melon-top-selection-color: #383d3ff5;

  --action-button-background-color: transparent;
  --action-button-color: var(--melon-color-text-negative);
  --action-button-hover-color: var(--melon-color-text);
  --action-button-active-color: var(--melon-color-text);

  --button-color: #333;
  --button-background-color: #efefef;
  --button-hover-background-color: #ccc;
  --button-border-color: #d2d2d2;
  --primary-button-color: var(--melon-color-text-negative);
  --primary-button-background-color: var(--melon-color);
  --primary-button-hover-background-color: var(--melon-color-text);
  --primary-button-border-color: var(--melon-color-text);
  --editor-command-button-color: var(--melon-color-text);
  --editor-command-button-background-color: var(--melon-color);
  --editor-command-button-border-color: var(--melon-color-text);
}

```


```css
/* parking space */
--background-error: repeating-linear-gradient(
      45deg, #e6e370, #e6e370 100px, #686868 100px, #686868 200px
    );
/* ## Animation */
@keyframes fade {
  0%,100% { opacity: 0 }
  50% { opacity: 1 }
}
```
