```space-style

/* Put Treeview on Top on Mobile/Small Screens */
@media screen and (max-width: 960px) {
  div.sb-panel {
    min-height: 300px;
    border-bottom: 1px dashed var(--bhs-border-color);
  }
  div#sb-main {
    flex-direction: column;
  }
  div#sb-main .cm-editor .cm-content {
    margin-left: 0;
  }
}

html .treeview-root {
  --treeview-node-border-width: 2px;
  --treeview-node-border-radius: 2px;

  --treeview-page-color: #666363 !important;
  --treeview-page-background-color: var(--editor-main-background-color);
  --treeview-page-border-color: var(--treeview-page-background-color);

  --treeview-current-page-background-color: var(--top-background-color);
  --treeview-current-page-border-color: var(--top-background-color);
  --treeview-current-page-color: var(--top-color);
  
  --treeview-folder-color: #8c8c8c !important;
  --treeview-folder-background-color: var(--treeview-page-background-color);
  --treeview-folder-border-color: var(--treeview-page-background-color);
}

.treeview-root {
  /* SortableTree variables */
  --st-label-height: 1.3em;
  --st-subnodes-padding-left: 1em;
  --st-collapse-icon-height: 1.8em;
  --st-collapse-icon-width: 1.1em;
  --st-collapse-icon-size: 0.8em;
  background-color: var(--editor-main-background-color);
}
.treeview-header {
  padding: 0;
}

.treeview-actions {
  background-color: var(--melon-secondary-background-color); /*was: #666363*/
  border: none;
  border-radius: 0;
  border-bottom: 1px solid var(--melon-secondary-background-border-color);
  margin-bottom: 0.5em;
}

html[data-theme="light"] .treeview-actions button {
  color: var(--melon-secondary-color);
}

html[data-theme="light"] sortable-tree-node {
  color: var(--subtle-color);
}

.tree__label {
  padding: 1px;
  margin: 1px;
}

.tree__label > span {
  font-size: 1em;
}

.tree__label > span[data-current-page="true"] {
  font-weight: bold;
  border: none;
  background: none;
  color: var(--melon-color);
}

/* differentiate folders (= empty notes with children) */
.tree__label span[data-node-type="folder"] {
  /*border-bottom: 1px dashed #ccc;*/
}

```


