---
pageDecoration: 
  prefix: "🔝"
---
```space-style

/* ------------------------------------------------------------------------- */
/* # Top Bar */
/* ------------------------------------------------------------------------- */
#sb-top {
  border-bottom: none;
  align-items: center;
  background-color: var(--melon-color);
}


#sb-top .main .inner {  /* Move Top Bar to the Left */
  margin-left: 20px;
  margin-right: auto;
}

#sb-top .main .inner .wrapper {  
  margin-left: 0;
  padding: 0;
}

#sb-top .main #sb-current-page .cm-scroller {
  font-weight: bold;
  font-size: 0.7em;
}

#sb-top.sb-sync-error {
  background: var(--background-error);
}
  

#sb-top {  /* Make Top Bar Responsive */
  height: unset;
}
#sb-top span#sb-current-page {  /* Make Top Bar Responsive */
  width: fit-content;
  align-content: center;
  align-self: center;
  min-width: fit-content;
}
#sb-top div.wrapper {  /* Make Top Bar Responsive */
  flex-flow: wrap;
  display: inline-flex;
}

/* Save States */
#sb-root #sb-top .main .inner .wrapper #sb-current-page.sb-unsaved .cm-line::after {
  content: ""; 
  background-color: var(--melon-unsaved-color);
  border-radius: 50%; 
  margin-left: 0.5em;
  border: 2px solid var(--melon-unsaved-border-color);
  width: 8px;
  display: inline-block ;
  vertical-align: center;
  height: 8px;
}

/* Page Prefix */
#sb-root #sb-top .sb-page-prefix {
  margin-inline-end: 0.3em;
}
```

```disbl
/* Page Prefix */
#sb-root #sb-top .sb-page-prefix {
  align-items: center;
  align-self: center;
  aspect-ratio: 1;
  background-color: white;
  border-radius: 50%;
  font-size: 0.7em;
  height: 1.6em;
  justify-content: center;
  margin-inline-end: .5em;
  padding: 0.3em;
  width: 1.6em;
}
```
