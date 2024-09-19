```space-style

/* ------------------------------------------------------------------------- */
/* # Font Definitions */
/* ------------------------------------------------------------------------- */
/* ## Fira Mono Regular */
@font-face { 
  font-family: 'Fira Mono'; 
  font-style: normal; 
  font-weight: 400;
  src: url('Library/Personal/Themes/Fonts/FiraMono/FiraMono-Regular.woff') format('woff');
}

/* ## Fira Sans Light */
@font-face {
  font-family: 'Fira Sans'; 
  font-style: normal; 
  font-weight: 300; 
  src: url('Library/Personal/Themes/Fonts/FiraSans/FiraSans-Light.woff') format('woff');
}

/* ## Fira Sans Regular */
@font-face {
  font-family: 'Fira Sans';
  font-style: normal;
  font-weight: 400;
  src: url('Library/Personal/Themes/Fonts/FiraSans/FiraSans-Regular.woff') format('woff');
}

/* ## Fira Code Regular */
@font-face {
  font-family: 'Fira Code'; 
  font-style: normal; 
  font-weight: 300; 
  src: url('Library/Personal/Themes/Fonts/FiraCode/FiraCode-Regular.woff') format('woff');
}

/* ## Fira Code Bold */
@font-face {
  font-family: 'Fira Code'; 
  font-style: normal; 
  font-weight: 600; 
  src: url('Library/Personal/Themes/Fonts/FiraCode/FiraCode-Bold.woff') format('woff');
}

/* ## Roboto Slab Light */
@font-face {
  font-family: 'Roboto Slab';
  font-style: normal;
  font-weight: 200;
  src: url('Library/Personal/Themes/Fonts/roboto-slab-v11-latin-200.woff') format('woff');
}

/* ## Roboto Slab Regular */
@font-face {
  font-family: 'Roboto Slab';
  font-style: normal;
  font-weight: 300;
  src: url('Library/Personal/Themes/Fonts/RobotoSlab/roboto-slab-v11-latin-300.woff') format('woff');
}

/* ## Roboto Slab Medium */
@font-face {
  font-family: 'Roboto Slab';
  font-style: normal;
  font-weight: 400;
  src: url('Library/Personal/Themes/Fonts/RobotoSlab/roboto-slab-v11-latin-regular.woff') format('woff');

}

/* ## Roboto Slab Bold */
@font-face {
  font-family: 'Roboto Slab';
  font-style: normal;
  font-weight: 600;
  src: url('Library/Personal/Themes/Fonts/RobotoSlab/roboto-slab-v11-latin-600.woff') format('woff');
}

html {
  --melon-ui-font: "Roboto Slab", "Noto Sans", "Segoe UI", "Helvetica Neue", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji", Arial, sans-serif;
  
  --melon-editor-font: 'Fira Sans', 'Open Sans', 'Source Sans Pro', 'Liberation Sans', Arial, Sans-serif;
  
  --melon-code-font: 'Fira Code', 'Source Code Pro', Courier, Monospace;
}

/* # Set Font Variables */
html {
  --ui-font: var(--melon-ui-font);
  --editor-font: var(--melon-editor-font);
  --code-font: var(--melon-code-font);
}
```
