<!DOCTYPE html>
<html>
<head><meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>EDA Analysis of Car Data</title><script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>




<style type="text/css">
    pre { line-height: 125%; }
td.linenos .normal { color: inherit; background-color: transparent; padding-left: 5px; padding-right: 5px; }
span.linenos { color: inherit; background-color: transparent; padding-left: 5px; padding-right: 5px; }
td.linenos .special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
span.linenos.special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
.highlight .hll { background-color: var(--jp-cell-editor-active-background) }
.highlight { background: var(--jp-cell-editor-background); color: var(--jp-mirror-editor-variable-color) }
.highlight .c { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment */
.highlight .err { color: var(--jp-mirror-editor-error-color) } /* Error */
.highlight .k { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword */
.highlight .o { color: var(--jp-mirror-editor-operator-color); font-weight: bold } /* Operator */
.highlight .p { color: var(--jp-mirror-editor-punctuation-color) } /* Punctuation */
.highlight .ch { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Multiline */
.highlight .cp { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Preproc */
.highlight .cpf { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Single */
.highlight .cs { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Special */
.highlight .kc { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Pseudo */
.highlight .kr { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Type */
.highlight .m { color: var(--jp-mirror-editor-number-color) } /* Literal.Number */
.highlight .s { color: var(--jp-mirror-editor-string-color) } /* Literal.String */
.highlight .ow { color: var(--jp-mirror-editor-operator-color); font-weight: bold } /* Operator.Word */
.highlight .w { color: var(--jp-mirror-editor-variable-color) } /* Text.Whitespace */
.highlight .mb { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Bin */
.highlight .mf { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Float */
.highlight .mh { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Hex */
.highlight .mi { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Integer */
.highlight .mo { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Oct */
.highlight .sa { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Affix */
.highlight .sb { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Backtick */
.highlight .sc { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Char */
.highlight .dl { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Delimiter */
.highlight .sd { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Doc */
.highlight .s2 { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Double */
.highlight .se { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Escape */
.highlight .sh { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Heredoc */
.highlight .si { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Interpol */
.highlight .sx { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Other */
.highlight .sr { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Regex */
.highlight .s1 { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Single */
.highlight .ss { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Symbol */
.highlight .il { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Integer.Long */
  </style>



<style type="text/css">
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*
 * Mozilla scrollbar styling
 */

/* use standard opaque scrollbars for most nodes */
[data-jp-theme-scrollbars='true'] {
  scrollbar-color: rgb(var(--jp-scrollbar-thumb-color))
    var(--jp-scrollbar-background-color);
}

/* for code nodes, use a transparent style of scrollbar. These selectors
 * will match lower in the tree, and so will override the above */
[data-jp-theme-scrollbars='true'] .CodeMirror-hscrollbar,
[data-jp-theme-scrollbars='true'] .CodeMirror-vscrollbar {
  scrollbar-color: rgba(var(--jp-scrollbar-thumb-color), 0.5) transparent;
}

/*
 * Webkit scrollbar styling
 */

/* use standard opaque scrollbars for most nodes */

[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar,
[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar-corner {
  background: var(--jp-scrollbar-background-color);
}

[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar-thumb {
  background: rgb(var(--jp-scrollbar-thumb-color));
  border: var(--jp-scrollbar-thumb-margin) solid transparent;
  background-clip: content-box;
  border-radius: var(--jp-scrollbar-thumb-radius);
}

[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar-track:horizontal {
  border-left: var(--jp-scrollbar-endpad) solid
    var(--jp-scrollbar-background-color);
  border-right: var(--jp-scrollbar-endpad) solid
    var(--jp-scrollbar-background-color);
}

[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar-track:vertical {
  border-top: var(--jp-scrollbar-endpad) solid
    var(--jp-scrollbar-background-color);
  border-bottom: var(--jp-scrollbar-endpad) solid
    var(--jp-scrollbar-background-color);
}

/* for code nodes, use a transparent style of scrollbar */

[data-jp-theme-scrollbars='true'] .CodeMirror-hscrollbar::-webkit-scrollbar,
[data-jp-theme-scrollbars='true'] .CodeMirror-vscrollbar::-webkit-scrollbar,
[data-jp-theme-scrollbars='true']
  .CodeMirror-hscrollbar::-webkit-scrollbar-corner,
[data-jp-theme-scrollbars='true']
  .CodeMirror-vscrollbar::-webkit-scrollbar-corner {
  background-color: transparent;
}

[data-jp-theme-scrollbars='true']
  .CodeMirror-hscrollbar::-webkit-scrollbar-thumb,
[data-jp-theme-scrollbars='true']
  .CodeMirror-vscrollbar::-webkit-scrollbar-thumb {
  background: rgba(var(--jp-scrollbar-thumb-color), 0.5);
  border: var(--jp-scrollbar-thumb-margin) solid transparent;
  background-clip: content-box;
  border-radius: var(--jp-scrollbar-thumb-radius);
}

[data-jp-theme-scrollbars='true']
  .CodeMirror-hscrollbar::-webkit-scrollbar-track:horizontal {
  border-left: var(--jp-scrollbar-endpad) solid transparent;
  border-right: var(--jp-scrollbar-endpad) solid transparent;
}

[data-jp-theme-scrollbars='true']
  .CodeMirror-vscrollbar::-webkit-scrollbar-track:vertical {
  border-top: var(--jp-scrollbar-endpad) solid transparent;
  border-bottom: var(--jp-scrollbar-endpad) solid transparent;
}

/*
 * Phosphor
 */

.lm-ScrollBar[data-orientation='horizontal'] {
  min-height: 16px;
  max-height: 16px;
  min-width: 45px;
  border-top: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='vertical'] {
  min-width: 16px;
  max-width: 16px;
  min-height: 45px;
  border-left: 1px solid #a0a0a0;
}

.lm-ScrollBar-button {
  background-color: #f0f0f0;
  background-position: center center;
  min-height: 15px;
  max-height: 15px;
  min-width: 15px;
  max-width: 15px;
}

.lm-ScrollBar-button:hover {
  background-color: #dadada;
}

.lm-ScrollBar-button.lm-mod-active {
  background-color: #cdcdcd;
}

.lm-ScrollBar-track {
  background: #f0f0f0;
}

.lm-ScrollBar-thumb {
  background: #cdcdcd;
}

.lm-ScrollBar-thumb:hover {
  background: #bababa;
}

.lm-ScrollBar-thumb.lm-mod-active {
  background: #a0a0a0;
}

.lm-ScrollBar[data-orientation='horizontal'] .lm-ScrollBar-thumb {
  height: 100%;
  min-width: 15px;
  border-left: 1px solid #a0a0a0;
  border-right: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='vertical'] .lm-ScrollBar-thumb {
  width: 100%;
  min-height: 15px;
  border-top: 1px solid #a0a0a0;
  border-bottom: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='horizontal']
  .lm-ScrollBar-button[data-action='decrement'] {
  background-image: var(--jp-icon-caret-left);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='horizontal']
  .lm-ScrollBar-button[data-action='increment'] {
  background-image: var(--jp-icon-caret-right);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='vertical']
  .lm-ScrollBar-button[data-action='decrement'] {
  background-image: var(--jp-icon-caret-up);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='vertical']
  .lm-ScrollBar-button[data-action='increment'] {
  background-image: var(--jp-icon-caret-down);
  background-size: 17px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-Widget, /* </DEPRECATED> */
.lm-Widget {
  box-sizing: border-box;
  position: relative;
  overflow: hidden;
  cursor: default;
}


/* <DEPRECATED> */ .p-Widget.p-mod-hidden, /* </DEPRECATED> */
.lm-Widget.lm-mod-hidden {
  display: none !important;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-CommandPalette, /* </DEPRECATED> */
.lm-CommandPalette {
  display: flex;
  flex-direction: column;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */ .p-CommandPalette-search, /* </DEPRECATED> */
.lm-CommandPalette-search {
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-CommandPalette-content, /* </DEPRECATED> */
.lm-CommandPalette-content {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  min-height: 0;
  overflow: auto;
  list-style-type: none;
}


/* <DEPRECATED> */ .p-CommandPalette-header, /* </DEPRECATED> */
.lm-CommandPalette-header {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}


/* <DEPRECATED> */ .p-CommandPalette-item, /* </DEPRECATED> */
.lm-CommandPalette-item {
  display: flex;
  flex-direction: row;
}


/* <DEPRECATED> */ .p-CommandPalette-itemIcon, /* </DEPRECATED> */
.lm-CommandPalette-itemIcon {
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-CommandPalette-itemContent, /* </DEPRECATED> */
.lm-CommandPalette-itemContent {
  flex: 1 1 auto;
  overflow: hidden;
}


/* <DEPRECATED> */ .p-CommandPalette-itemShortcut, /* </DEPRECATED> */
.lm-CommandPalette-itemShortcut {
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-CommandPalette-itemLabel, /* </DEPRECATED> */
.lm-CommandPalette-itemLabel {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-DockPanel, /* </DEPRECATED> */
.lm-DockPanel {
  z-index: 0;
}


/* <DEPRECATED> */ .p-DockPanel-widget, /* </DEPRECATED> */
.lm-DockPanel-widget {
  z-index: 0;
}


/* <DEPRECATED> */ .p-DockPanel-tabBar, /* </DEPRECATED> */
.lm-DockPanel-tabBar {
  z-index: 1;
}


/* <DEPRECATED> */ .p-DockPanel-handle, /* </DEPRECATED> */
.lm-DockPanel-handle {
  z-index: 2;
}


/* <DEPRECATED> */ .p-DockPanel-handle.p-mod-hidden, /* </DEPRECATED> */
.lm-DockPanel-handle.lm-mod-hidden {
  display: none !important;
}


/* <DEPRECATED> */ .p-DockPanel-handle:after, /* </DEPRECATED> */
.lm-DockPanel-handle:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  content: '';
}


/* <DEPRECATED> */
.p-DockPanel-handle[data-orientation='horizontal'],
/* </DEPRECATED> */
.lm-DockPanel-handle[data-orientation='horizontal'] {
  cursor: ew-resize;
}


/* <DEPRECATED> */
.p-DockPanel-handle[data-orientation='vertical'],
/* </DEPRECATED> */
.lm-DockPanel-handle[data-orientation='vertical'] {
  cursor: ns-resize;
}


/* <DEPRECATED> */
.p-DockPanel-handle[data-orientation='horizontal']:after,
/* </DEPRECATED> */
.lm-DockPanel-handle[data-orientation='horizontal']:after {
  left: 50%;
  min-width: 8px;
  transform: translateX(-50%);
}


/* <DEPRECATED> */
.p-DockPanel-handle[data-orientation='vertical']:after,
/* </DEPRECATED> */
.lm-DockPanel-handle[data-orientation='vertical']:after {
  top: 50%;
  min-height: 8px;
  transform: translateY(-50%);
}


/* <DEPRECATED> */ .p-DockPanel-overlay, /* </DEPRECATED> */
.lm-DockPanel-overlay {
  z-index: 3;
  box-sizing: border-box;
  pointer-events: none;
}


/* <DEPRECATED> */ .p-DockPanel-overlay.p-mod-hidden, /* </DEPRECATED> */
.lm-DockPanel-overlay.lm-mod-hidden {
  display: none !important;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-Menu, /* </DEPRECATED> */
.lm-Menu {
  z-index: 10000;
  position: absolute;
  white-space: nowrap;
  overflow-x: hidden;
  overflow-y: auto;
  outline: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */ .p-Menu-content, /* </DEPRECATED> */
.lm-Menu-content {
  margin: 0;
  padding: 0;
  display: table;
  list-style-type: none;
}


/* <DEPRECATED> */ .p-Menu-item, /* </DEPRECATED> */
.lm-Menu-item {
  display: table-row;
}


/* <DEPRECATED> */
.p-Menu-item.p-mod-hidden,
.p-Menu-item.p-mod-collapsed,
/* </DEPRECATED> */
.lm-Menu-item.lm-mod-hidden,
.lm-Menu-item.lm-mod-collapsed {
  display: none !important;
}


/* <DEPRECATED> */
.p-Menu-itemIcon,
.p-Menu-itemSubmenuIcon,
/* </DEPRECATED> */
.lm-Menu-itemIcon,
.lm-Menu-itemSubmenuIcon {
  display: table-cell;
  text-align: center;
}


/* <DEPRECATED> */ .p-Menu-itemLabel, /* </DEPRECATED> */
.lm-Menu-itemLabel {
  display: table-cell;
  text-align: left;
}


/* <DEPRECATED> */ .p-Menu-itemShortcut, /* </DEPRECATED> */
.lm-Menu-itemShortcut {
  display: table-cell;
  text-align: right;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-MenuBar, /* </DEPRECATED> */
.lm-MenuBar {
  outline: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */ .p-MenuBar-content, /* </DEPRECATED> */
.lm-MenuBar-content {
  margin: 0;
  padding: 0;
  display: flex;
  flex-direction: row;
  list-style-type: none;
}


/* <DEPRECATED> */ .p--MenuBar-item, /* </DEPRECATED> */
.lm-MenuBar-item {
  box-sizing: border-box;
}


/* <DEPRECATED> */
.p-MenuBar-itemIcon,
.p-MenuBar-itemLabel,
/* </DEPRECATED> */
.lm-MenuBar-itemIcon,
.lm-MenuBar-itemLabel {
  display: inline-block;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-ScrollBar, /* </DEPRECATED> */
.lm-ScrollBar {
  display: flex;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */
.p-ScrollBar[data-orientation='horizontal'],
/* </DEPRECATED> */
.lm-ScrollBar[data-orientation='horizontal'] {
  flex-direction: row;
}


/* <DEPRECATED> */
.p-ScrollBar[data-orientation='vertical'],
/* </DEPRECATED> */
.lm-ScrollBar[data-orientation='vertical'] {
  flex-direction: column;
}


/* <DEPRECATED> */ .p-ScrollBar-button, /* </DEPRECATED> */
.lm-ScrollBar-button {
  box-sizing: border-box;
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-ScrollBar-track, /* </DEPRECATED> */
.lm-ScrollBar-track {
  box-sizing: border-box;
  position: relative;
  overflow: hidden;
  flex: 1 1 auto;
}


/* <DEPRECATED> */ .p-ScrollBar-thumb, /* </DEPRECATED> */
.lm-ScrollBar-thumb {
  box-sizing: border-box;
  position: absolute;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-SplitPanel-child, /* </DEPRECATED> */
.lm-SplitPanel-child {
  z-index: 0;
}


/* <DEPRECATED> */ .p-SplitPanel-handle, /* </DEPRECATED> */
.lm-SplitPanel-handle {
  z-index: 1;
}


/* <DEPRECATED> */ .p-SplitPanel-handle.p-mod-hidden, /* </DEPRECATED> */
.lm-SplitPanel-handle.lm-mod-hidden {
  display: none !important;
}


/* <DEPRECATED> */ .p-SplitPanel-handle:after, /* </DEPRECATED> */
.lm-SplitPanel-handle:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  content: '';
}


/* <DEPRECATED> */
.p-SplitPanel[data-orientation='horizontal'] > .p-SplitPanel-handle,
/* </DEPRECATED> */
.lm-SplitPanel[data-orientation='horizontal'] > .lm-SplitPanel-handle {
  cursor: ew-resize;
}


/* <DEPRECATED> */
.p-SplitPanel[data-orientation='vertical'] > .p-SplitPanel-handle,
/* </DEPRECATED> */
.lm-SplitPanel[data-orientation='vertical'] > .lm-SplitPanel-handle {
  cursor: ns-resize;
}


/* <DEPRECATED> */
.p-SplitPanel[data-orientation='horizontal'] > .p-SplitPanel-handle:after,
/* </DEPRECATED> */
.lm-SplitPanel[data-orientation='horizontal'] > .lm-SplitPanel-handle:after {
  left: 50%;
  min-width: 8px;
  transform: translateX(-50%);
}


/* <DEPRECATED> */
.p-SplitPanel[data-orientation='vertical'] > .p-SplitPanel-handle:after,
/* </DEPRECATED> */
.lm-SplitPanel[data-orientation='vertical'] > .lm-SplitPanel-handle:after {
  top: 50%;
  min-height: 8px;
  transform: translateY(-50%);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-TabBar, /* </DEPRECATED> */
.lm-TabBar {
  display: flex;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */ .p-TabBar[data-orientation='horizontal'], /* </DEPRECATED> */
.lm-TabBar[data-orientation='horizontal'] {
  flex-direction: row;
}


/* <DEPRECATED> */ .p-TabBar[data-orientation='vertical'], /* </DEPRECATED> */
.lm-TabBar[data-orientation='vertical'] {
  flex-direction: column;
}


/* <DEPRECATED> */ .p-TabBar-content, /* </DEPRECATED> */
.lm-TabBar-content {
  margin: 0;
  padding: 0;
  display: flex;
  flex: 1 1 auto;
  list-style-type: none;
}


/* <DEPRECATED> */
.p-TabBar[data-orientation='horizontal'] > .p-TabBar-content,
/* </DEPRECATED> */
.lm-TabBar[data-orientation='horizontal'] > .lm-TabBar-content {
  flex-direction: row;
}


/* <DEPRECATED> */
.p-TabBar[data-orientation='vertical'] > .p-TabBar-content,
/* </DEPRECATED> */
.lm-TabBar[data-orientation='vertical'] > .lm-TabBar-content {
  flex-direction: column;
}


/* <DEPRECATED> */ .p-TabBar-tab, /* </DEPRECATED> */
.lm-TabBar-tab {
  display: flex;
  flex-direction: row;
  box-sizing: border-box;
  overflow: hidden;
}


/* <DEPRECATED> */
.p-TabBar-tabIcon,
.p-TabBar-tabCloseIcon,
/* </DEPRECATED> */
.lm-TabBar-tabIcon,
.lm-TabBar-tabCloseIcon {
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-TabBar-tabLabel, /* </DEPRECATED> */
.lm-TabBar-tabLabel {
  flex: 1 1 auto;
  overflow: hidden;
  white-space: nowrap;
}


/* <DEPRECATED> */ .p-TabBar-tab.p-mod-hidden, /* </DEPRECATED> */
.lm-TabBar-tab.lm-mod-hidden {
  display: none !important;
}


/* <DEPRECATED> */ .p-TabBar.p-mod-dragging .p-TabBar-tab, /* </DEPRECATED> */
.lm-TabBar.lm-mod-dragging .lm-TabBar-tab {
  position: relative;
}


/* <DEPRECATED> */
.p-TabBar.p-mod-dragging[data-orientation='horizontal'] .p-TabBar-tab,
/* </DEPRECATED> */
.lm-TabBar.lm-mod-dragging[data-orientation='horizontal'] .lm-TabBar-tab {
  left: 0;
  transition: left 150ms ease;
}


/* <DEPRECATED> */
.p-TabBar.p-mod-dragging[data-orientation='vertical'] .p-TabBar-tab,
/* </DEPRECATED> */
.lm-TabBar.lm-mod-dragging[data-orientation='vertical'] .lm-TabBar-tab {
  top: 0;
  transition: top 150ms ease;
}


/* <DEPRECATED> */
.p-TabBar.p-mod-dragging .p-TabBar-tab.p-mod-dragging
/* </DEPRECATED> */
.lm-TabBar.lm-mod-dragging .lm-TabBar-tab.lm-mod-dragging {
  transition: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-TabPanel-tabBar, /* </DEPRECATED> */
.lm-TabPanel-tabBar {
  z-index: 1;
}


/* <DEPRECATED> */ .p-TabPanel-stackedPanel, /* </DEPRECATED> */
.lm-TabPanel-stackedPanel {
  z-index: 0;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

@charset "UTF-8";
/*!

Copyright 2015-present Palantir Technologies, Inc. All rights reserved.
Licensed under the Apache License, Version 2.0.

*/
html{
  -webkit-box-sizing:border-box;
          box-sizing:border-box; }

*,
*::before,
*::after{
  -webkit-box-sizing:inherit;
          box-sizing:inherit; }

body{
  text-transform:none;
  line-height:1.28581;
  letter-spacing:0;
  font-size:14px;
  font-weight:400;
  color:#182026;
  font-family:-apple-system, "BlinkMacSystemFont", "Segoe UI", "Roboto", "Oxygen", "Ubuntu", "Cantarell", "Open Sans", "Helvetica Neue", "Icons16", sans-serif; }

p{
  margin-top:0;
  margin-bottom:10px; }

small{
  font-size:12px; }

strong{
  font-weight:600; }

::-moz-selection{
  background:rgba(125, 188, 255, 0.6); }

::selection{
  background:rgba(125, 188, 255, 0.6); }
.bp3-heading{
  color:#182026;
  font-weight:600;
  margin:0 0 10px;
  padding:0; }
  .bp3-dark .bp3-heading{
    color:#f5f8fa; }

h1.bp3-heading, .bp3-running-text h1{
  line-height:40px;
  font-size:36px; }

h2.bp3-heading, .bp3-running-text h2{
  line-height:32px;
  font-size:28px; }

h3.bp3-heading, .bp3-running-text h3{
  line-height:25px;
  font-size:22px; }

h4.bp3-heading, .bp3-running-text h4{
  line-height:21px;
  font-size:18px; }

h5.bp3-heading, .bp3-running-text h5{
  line-height:19px;
  font-size:16px; }

h6.bp3-heading, .bp3-running-text h6{
  line-height:16px;
  font-size:14px; }
.bp3-ui-text{
  text-transform:none;
  line-height:1.28581;
  letter-spacing:0;
  font-size:14px;
  font-weight:400; }

.bp3-monospace-text{
  text-transform:none;
  font-family:monospace; }

.bp3-text-muted{
  color:#5c7080; }
  .bp3-dark .bp3-text-muted{
    color:#a7b6c2; }

.bp3-text-disabled{
  color:rgba(92, 112, 128, 0.6); }
  .bp3-dark .bp3-text-disabled{
    color:rgba(167, 182, 194, 0.6); }

.bp3-text-overflow-ellipsis{
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal; }
.bp3-running-text{
  line-height:1.5;
  font-size:14px; }
  .bp3-running-text h1{
    color:#182026;
    font-weight:600;
    margin-top:40px;
    margin-bottom:20px; }
    .bp3-dark .bp3-running-text h1{
      color:#f5f8fa; }
  .bp3-running-text h2{
    color:#182026;
    font-weight:600;
    margin-top:40px;
    margin-bottom:20px; }
    .bp3-dark .bp3-running-text h2{
      color:#f5f8fa; }
  .bp3-running-text h3{
    color:#182026;
    font-weight:600;
    margin-top:40px;
    margin-bottom:20px; }
    .bp3-dark .bp3-running-text h3{
      color:#f5f8fa; }
  .bp3-running-text h4{
    color:#182026;
    font-weight:600;
    margin-top:40px;
    margin-bottom:20px; }
    .bp3-dark .bp3-running-text h4{
      color:#f5f8fa; }
  .bp3-running-text h5{
    color:#182026;
    font-weight:600;
    margin-top:40px;
    margin-bottom:20px; }
    .bp3-dark .bp3-running-text h5{
      color:#f5f8fa; }
  .bp3-running-text h6{
    color:#182026;
    font-weight:600;
    margin-top:40px;
    margin-bottom:20px; }
    .bp3-dark .bp3-running-text h6{
      color:#f5f8fa; }
  .bp3-running-text hr{
    margin:20px 0;
    border:none;
    border-bottom:1px solid rgba(16, 22, 26, 0.15); }
    .bp3-dark .bp3-running-text hr{
      border-color:rgba(255, 255, 255, 0.15); }
  .bp3-running-text p{
    margin:0 0 10px;
    padding:0; }

.bp3-text-large{
  font-size:16px; }

.bp3-text-small{
  font-size:12px; }
a{
  text-decoration:none;
  color:#106ba3; }
  a:hover{
    cursor:pointer;
    text-decoration:underline;
    color:#106ba3; }
  a .bp3-icon, a .bp3-icon-standard, a .bp3-icon-large{
    color:inherit; }
  a code,
  .bp3-dark a code{
    color:inherit; }
  .bp3-dark a,
  .bp3-dark a:hover{
    color:#48aff0; }
    .bp3-dark a .bp3-icon, .bp3-dark a .bp3-icon-standard, .bp3-dark a .bp3-icon-large,
    .bp3-dark a:hover .bp3-icon,
    .bp3-dark a:hover .bp3-icon-standard,
    .bp3-dark a:hover .bp3-icon-large{
      color:inherit; }
.bp3-running-text code, .bp3-code{
  text-transform:none;
  font-family:monospace;
  border-radius:3px;
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2);
  background:rgba(255, 255, 255, 0.7);
  padding:2px 5px;
  color:#5c7080;
  font-size:smaller; }
  .bp3-dark .bp3-running-text code, .bp3-running-text .bp3-dark code, .bp3-dark .bp3-code{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
    background:rgba(16, 22, 26, 0.3);
    color:#a7b6c2; }
  .bp3-running-text a > code, a > .bp3-code{
    color:#137cbd; }
    .bp3-dark .bp3-running-text a > code, .bp3-running-text .bp3-dark a > code, .bp3-dark a > .bp3-code{
      color:inherit; }

.bp3-running-text pre, .bp3-code-block{
  text-transform:none;
  font-family:monospace;
  display:block;
  margin:10px 0;
  border-radius:3px;
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
  background:rgba(255, 255, 255, 0.7);
  padding:13px 15px 12px;
  line-height:1.4;
  color:#182026;
  font-size:13px;
  word-break:break-all;
  word-wrap:break-word; }
  .bp3-dark .bp3-running-text pre, .bp3-running-text .bp3-dark pre, .bp3-dark .bp3-code-block{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
    background:rgba(16, 22, 26, 0.3);
    color:#f5f8fa; }
  .bp3-running-text pre > code, .bp3-code-block > code{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:none;
    padding:0;
    color:inherit;
    font-size:inherit; }

.bp3-running-text kbd, .bp3-key{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
  background:#ffffff;
  min-width:24px;
  height:24px;
  padding:3px 6px;
  vertical-align:middle;
  line-height:24px;
  color:#5c7080;
  font-family:inherit;
  font-size:12px; }
  .bp3-running-text kbd .bp3-icon, .bp3-key .bp3-icon, .bp3-running-text kbd .bp3-icon-standard, .bp3-key .bp3-icon-standard, .bp3-running-text kbd .bp3-icon-large, .bp3-key .bp3-icon-large{
    margin-right:5px; }
  .bp3-dark .bp3-running-text kbd, .bp3-running-text .bp3-dark kbd, .bp3-dark .bp3-key{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
    background:#394b59;
    color:#a7b6c2; }
.bp3-running-text blockquote, .bp3-blockquote{
  margin:0 0 10px;
  border-left:solid 4px rgba(167, 182, 194, 0.5);
  padding:0 20px; }
  .bp3-dark .bp3-running-text blockquote, .bp3-running-text .bp3-dark blockquote, .bp3-dark .bp3-blockquote{
    border-color:rgba(115, 134, 148, 0.5); }
.bp3-running-text ul,
.bp3-running-text ol, .bp3-list{
  margin:10px 0;
  padding-left:30px; }
  .bp3-running-text ul li:not(:last-child), .bp3-running-text ol li:not(:last-child), .bp3-list li:not(:last-child){
    margin-bottom:5px; }
  .bp3-running-text ul ol, .bp3-running-text ol ol, .bp3-list ol,
  .bp3-running-text ul ul,
  .bp3-running-text ol ul,
  .bp3-list ul{
    margin-top:5px; }

.bp3-list-unstyled{
  margin:0;
  padding:0;
  list-style:none; }
  .bp3-list-unstyled li{
    padding:0; }
.bp3-rtl{
  text-align:right; }

.bp3-dark{
  color:#f5f8fa; }

:focus{
  outline:rgba(19, 124, 189, 0.6) auto 2px;
  outline-offset:2px;
  -moz-outline-radius:6px; }

.bp3-focus-disabled :focus{
  outline:none !important; }
  .bp3-focus-disabled :focus ~ .bp3-control-indicator{
    outline:none !important; }

.bp3-alert{
  max-width:400px;
  padding:20px; }

.bp3-alert-body{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex; }
  .bp3-alert-body .bp3-icon{
    margin-top:0;
    margin-right:20px;
    font-size:40px; }

.bp3-alert-footer{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:reverse;
      -ms-flex-direction:row-reverse;
          flex-direction:row-reverse;
  margin-top:10px; }
  .bp3-alert-footer .bp3-button{
    margin-left:10px; }
.bp3-breadcrumbs{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -ms-flex-wrap:wrap;
      flex-wrap:wrap;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  margin:0;
  cursor:default;
  height:30px;
  padding:0;
  list-style:none; }
  .bp3-breadcrumbs > li{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-align:center;
        -ms-flex-align:center;
            align-items:center; }
    .bp3-breadcrumbs > li::after{
      display:block;
      margin:0 5px;
      background:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill-rule='evenodd' clip-rule='evenodd' d='M10.71 7.29l-4-4a1.003 1.003 0 0 0-1.42 1.42L8.59 8 5.3 11.29c-.19.18-.3.43-.3.71a1.003 1.003 0 0 0 1.71.71l4-4c.18-.18.29-.43.29-.71 0-.28-.11-.53-.29-.71z' fill='%235C7080'/%3e%3c/svg%3e");
      width:16px;
      height:16px;
      content:""; }
    .bp3-breadcrumbs > li:last-of-type::after{
      display:none; }

.bp3-breadcrumb,
.bp3-breadcrumb-current,
.bp3-breadcrumbs-collapsed{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  font-size:16px; }

.bp3-breadcrumb,
.bp3-breadcrumbs-collapsed{
  color:#5c7080; }

.bp3-breadcrumb:hover{
  text-decoration:none; }

.bp3-breadcrumb.bp3-disabled{
  cursor:not-allowed;
  color:rgba(92, 112, 128, 0.6); }

.bp3-breadcrumb .bp3-icon{
  margin-right:5px; }

.bp3-breadcrumb-current{
  color:inherit;
  font-weight:600; }
  .bp3-breadcrumb-current .bp3-input{
    vertical-align:baseline;
    font-size:inherit;
    font-weight:inherit; }

.bp3-breadcrumbs-collapsed{
  margin-right:2px;
  border:none;
  border-radius:3px;
  background:#ced9e0;
  cursor:pointer;
  padding:1px 5px;
  vertical-align:text-bottom; }
  .bp3-breadcrumbs-collapsed::before{
    display:block;
    background:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cg fill='%235C7080'%3e%3ccircle cx='2' cy='8.03' r='2'/%3e%3ccircle cx='14' cy='8.03' r='2'/%3e%3ccircle cx='8' cy='8.03' r='2'/%3e%3c/g%3e%3c/svg%3e") center no-repeat;
    width:16px;
    height:16px;
    content:""; }
  .bp3-breadcrumbs-collapsed:hover{
    background:#bfccd6;
    text-decoration:none;
    color:#182026; }

.bp3-dark .bp3-breadcrumb,
.bp3-dark .bp3-breadcrumbs-collapsed{
  color:#a7b6c2; }

.bp3-dark .bp3-breadcrumbs > li::after{
  color:#a7b6c2; }

.bp3-dark .bp3-breadcrumb.bp3-disabled{
  color:rgba(167, 182, 194, 0.6); }

.bp3-dark .bp3-breadcrumb-current{
  color:#f5f8fa; }

.bp3-dark .bp3-breadcrumbs-collapsed{
  background:rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-breadcrumbs-collapsed:hover{
    background:rgba(16, 22, 26, 0.6);
    color:#f5f8fa; }
.bp3-button{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  border:none;
  border-radius:3px;
  cursor:pointer;
  padding:5px 10px;
  vertical-align:middle;
  text-align:left;
  font-size:14px;
  min-width:30px;
  min-height:30px; }
  .bp3-button > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-button > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-button::before,
  .bp3-button > *{
    margin-right:7px; }
  .bp3-button:empty::before,
  .bp3-button > :last-child{
    margin-right:0; }
  .bp3-button:empty{
    padding:0 !important; }
  .bp3-button:disabled, .bp3-button.bp3-disabled{
    cursor:not-allowed; }
  .bp3-button.bp3-fill{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    width:100%; }
  .bp3-button.bp3-align-right,
  .bp3-align-right .bp3-button{
    text-align:right; }
  .bp3-button.bp3-align-left,
  .bp3-align-left .bp3-button{
    text-align:left; }
  .bp3-button:not([class*="bp3-intent-"]){
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    background-color:#f5f8fa;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
    color:#182026; }
    .bp3-button:not([class*="bp3-intent-"]):hover{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
      background-clip:padding-box;
      background-color:#ebf1f5; }
    .bp3-button:not([class*="bp3-intent-"]):active, .bp3-button:not([class*="bp3-intent-"]).bp3-active{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#d8e1e8;
      background-image:none; }
    .bp3-button:not([class*="bp3-intent-"]):disabled, .bp3-button:not([class*="bp3-intent-"]).bp3-disabled{
      outline:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      background-color:rgba(206, 217, 224, 0.5);
      background-image:none;
      cursor:not-allowed;
      color:rgba(92, 112, 128, 0.6); }
      .bp3-button:not([class*="bp3-intent-"]):disabled.bp3-active, .bp3-button:not([class*="bp3-intent-"]):disabled.bp3-active:hover, .bp3-button:not([class*="bp3-intent-"]).bp3-disabled.bp3-active, .bp3-button:not([class*="bp3-intent-"]).bp3-disabled.bp3-active:hover{
        background:rgba(206, 217, 224, 0.7); }
  .bp3-button.bp3-intent-primary{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    background-color:#137cbd;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    color:#ffffff; }
    .bp3-button.bp3-intent-primary:hover, .bp3-button.bp3-intent-primary:active, .bp3-button.bp3-intent-primary.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-primary:hover{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
      background-color:#106ba3; }
    .bp3-button.bp3-intent-primary:active, .bp3-button.bp3-intent-primary.bp3-active{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#0e5a8a;
      background-image:none; }
    .bp3-button.bp3-intent-primary:disabled, .bp3-button.bp3-intent-primary.bp3-disabled{
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      background-color:rgba(19, 124, 189, 0.5);
      background-image:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button.bp3-intent-success{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    background-color:#0f9960;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    color:#ffffff; }
    .bp3-button.bp3-intent-success:hover, .bp3-button.bp3-intent-success:active, .bp3-button.bp3-intent-success.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-success:hover{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
      background-color:#0d8050; }
    .bp3-button.bp3-intent-success:active, .bp3-button.bp3-intent-success.bp3-active{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#0a6640;
      background-image:none; }
    .bp3-button.bp3-intent-success:disabled, .bp3-button.bp3-intent-success.bp3-disabled{
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      background-color:rgba(15, 153, 96, 0.5);
      background-image:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button.bp3-intent-warning{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    background-color:#d9822b;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    color:#ffffff; }
    .bp3-button.bp3-intent-warning:hover, .bp3-button.bp3-intent-warning:active, .bp3-button.bp3-intent-warning.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-warning:hover{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
      background-color:#bf7326; }
    .bp3-button.bp3-intent-warning:active, .bp3-button.bp3-intent-warning.bp3-active{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#a66321;
      background-image:none; }
    .bp3-button.bp3-intent-warning:disabled, .bp3-button.bp3-intent-warning.bp3-disabled{
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      background-color:rgba(217, 130, 43, 0.5);
      background-image:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button.bp3-intent-danger{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    background-color:#db3737;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    color:#ffffff; }
    .bp3-button.bp3-intent-danger:hover, .bp3-button.bp3-intent-danger:active, .bp3-button.bp3-intent-danger.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-danger:hover{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
      background-color:#c23030; }
    .bp3-button.bp3-intent-danger:active, .bp3-button.bp3-intent-danger.bp3-active{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#a82a2a;
      background-image:none; }
    .bp3-button.bp3-intent-danger:disabled, .bp3-button.bp3-intent-danger.bp3-disabled{
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      background-color:rgba(219, 55, 55, 0.5);
      background-image:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button[class*="bp3-intent-"] .bp3-button-spinner .bp3-spinner-head{
    stroke:#ffffff; }
  .bp3-button.bp3-large,
  .bp3-large .bp3-button{
    min-width:40px;
    min-height:40px;
    padding:5px 15px;
    font-size:16px; }
    .bp3-button.bp3-large::before,
    .bp3-button.bp3-large > *,
    .bp3-large .bp3-button::before,
    .bp3-large .bp3-button > *{
      margin-right:10px; }
    .bp3-button.bp3-large:empty::before,
    .bp3-button.bp3-large > :last-child,
    .bp3-large .bp3-button:empty::before,
    .bp3-large .bp3-button > :last-child{
      margin-right:0; }
  .bp3-button.bp3-small,
  .bp3-small .bp3-button{
    min-width:24px;
    min-height:24px;
    padding:0 7px; }
  .bp3-button.bp3-loading{
    position:relative; }
    .bp3-button.bp3-loading[class*="bp3-icon-"]::before{
      visibility:hidden; }
    .bp3-button.bp3-loading .bp3-button-spinner{
      position:absolute;
      margin:0; }
    .bp3-button.bp3-loading > :not(.bp3-button-spinner){
      visibility:hidden; }
  .bp3-button[class*="bp3-icon-"]::before{
    line-height:1;
    font-family:"Icons16", sans-serif;
    font-size:16px;
    font-weight:400;
    font-style:normal;
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased;
    color:#5c7080; }
  .bp3-button .bp3-icon, .bp3-button .bp3-icon-standard, .bp3-button .bp3-icon-large{
    color:#5c7080; }
    .bp3-button .bp3-icon.bp3-align-right, .bp3-button .bp3-icon-standard.bp3-align-right, .bp3-button .bp3-icon-large.bp3-align-right{
      margin-left:7px; }
  .bp3-button .bp3-icon:first-child:last-child,
  .bp3-button .bp3-spinner + .bp3-icon:last-child{
    margin:0 -7px; }
  .bp3-dark .bp3-button:not([class*="bp3-intent-"]){
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    background-color:#394b59;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
    color:#f5f8fa; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):hover, .bp3-dark .bp3-button:not([class*="bp3-intent-"]):active, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-active{
      color:#f5f8fa; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):hover{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
      background-color:#30404d; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):active, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-active{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#202b33;
      background-image:none; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):disabled, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none;
      background-color:rgba(57, 75, 89, 0.5);
      background-image:none;
      color:rgba(167, 182, 194, 0.6); }
      .bp3-dark .bp3-button:not([class*="bp3-intent-"]):disabled.bp3-active, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-disabled.bp3-active{
        background:rgba(57, 75, 89, 0.7); }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]) .bp3-button-spinner .bp3-spinner-head{
      background:rgba(16, 22, 26, 0.5);
      stroke:#8a9ba8; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"])[class*="bp3-icon-"]::before{
      color:#a7b6c2; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]) .bp3-icon, .bp3-dark .bp3-button:not([class*="bp3-intent-"]) .bp3-icon-standard, .bp3-dark .bp3-button:not([class*="bp3-intent-"]) .bp3-icon-large{
      color:#a7b6c2; }
  .bp3-dark .bp3-button[class*="bp3-intent-"]{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-button[class*="bp3-intent-"]:hover{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-button[class*="bp3-intent-"]:active, .bp3-dark .bp3-button[class*="bp3-intent-"].bp3-active{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-dark .bp3-button[class*="bp3-intent-"]:disabled, .bp3-dark .bp3-button[class*="bp3-intent-"].bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none;
      background-image:none;
      color:rgba(255, 255, 255, 0.3); }
    .bp3-dark .bp3-button[class*="bp3-intent-"] .bp3-button-spinner .bp3-spinner-head{
      stroke:#8a9ba8; }
  .bp3-button:disabled::before,
  .bp3-button:disabled .bp3-icon, .bp3-button:disabled .bp3-icon-standard, .bp3-button:disabled .bp3-icon-large, .bp3-button.bp3-disabled::before,
  .bp3-button.bp3-disabled .bp3-icon, .bp3-button.bp3-disabled .bp3-icon-standard, .bp3-button.bp3-disabled .bp3-icon-large, .bp3-button[class*="bp3-intent-"]::before,
  .bp3-button[class*="bp3-intent-"] .bp3-icon, .bp3-button[class*="bp3-intent-"] .bp3-icon-standard, .bp3-button[class*="bp3-intent-"] .bp3-icon-large{
    color:inherit !important; }
  .bp3-button.bp3-minimal{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:none; }
    .bp3-button.bp3-minimal:hover{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(167, 182, 194, 0.3);
      text-decoration:none;
      color:#182026; }
    .bp3-button.bp3-minimal:active, .bp3-button.bp3-minimal.bp3-active{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(115, 134, 148, 0.3);
      color:#182026; }
    .bp3-button.bp3-minimal:disabled, .bp3-button.bp3-minimal:disabled:hover, .bp3-button.bp3-minimal.bp3-disabled, .bp3-button.bp3-minimal.bp3-disabled:hover{
      background:none;
      cursor:not-allowed;
      color:rgba(92, 112, 128, 0.6); }
      .bp3-button.bp3-minimal:disabled.bp3-active, .bp3-button.bp3-minimal:disabled:hover.bp3-active, .bp3-button.bp3-minimal.bp3-disabled.bp3-active, .bp3-button.bp3-minimal.bp3-disabled:hover.bp3-active{
        background:rgba(115, 134, 148, 0.3); }
    .bp3-dark .bp3-button.bp3-minimal{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:none;
      color:inherit; }
      .bp3-dark .bp3-button.bp3-minimal:hover, .bp3-dark .bp3-button.bp3-minimal:active, .bp3-dark .bp3-button.bp3-minimal.bp3-active{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none; }
      .bp3-dark .bp3-button.bp3-minimal:hover{
        background:rgba(138, 155, 168, 0.15); }
      .bp3-dark .bp3-button.bp3-minimal:active, .bp3-dark .bp3-button.bp3-minimal.bp3-active{
        background:rgba(138, 155, 168, 0.3);
        color:#f5f8fa; }
      .bp3-dark .bp3-button.bp3-minimal:disabled, .bp3-dark .bp3-button.bp3-minimal:disabled:hover, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled:hover{
        background:none;
        cursor:not-allowed;
        color:rgba(167, 182, 194, 0.6); }
        .bp3-dark .bp3-button.bp3-minimal:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal:disabled:hover.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled:hover.bp3-active{
          background:rgba(138, 155, 168, 0.3); }
    .bp3-button.bp3-minimal.bp3-intent-primary{
      color:#106ba3; }
      .bp3-button.bp3-minimal.bp3-intent-primary:hover, .bp3-button.bp3-minimal.bp3-intent-primary:active, .bp3-button.bp3-minimal.bp3-intent-primary.bp3-active{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none;
        color:#106ba3; }
      .bp3-button.bp3-minimal.bp3-intent-primary:hover{
        background:rgba(19, 124, 189, 0.15);
        color:#106ba3; }
      .bp3-button.bp3-minimal.bp3-intent-primary:active, .bp3-button.bp3-minimal.bp3-intent-primary.bp3-active{
        background:rgba(19, 124, 189, 0.3);
        color:#106ba3; }
      .bp3-button.bp3-minimal.bp3-intent-primary:disabled, .bp3-button.bp3-minimal.bp3-intent-primary.bp3-disabled{
        background:none;
        color:rgba(16, 107, 163, 0.5); }
        .bp3-button.bp3-minimal.bp3-intent-primary:disabled.bp3-active, .bp3-button.bp3-minimal.bp3-intent-primary.bp3-disabled.bp3-active{
          background:rgba(19, 124, 189, 0.3); }
      .bp3-button.bp3-minimal.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head{
        stroke:#106ba3; }
      .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary{
        color:#48aff0; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary:hover{
          background:rgba(19, 124, 189, 0.2);
          color:#48aff0; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary:active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary.bp3-active{
          background:rgba(19, 124, 189, 0.3);
          color:#48aff0; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary:disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary.bp3-disabled{
          background:none;
          color:rgba(72, 175, 240, 0.5); }
          .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary.bp3-disabled.bp3-active{
            background:rgba(19, 124, 189, 0.3); }
    .bp3-button.bp3-minimal.bp3-intent-success{
      color:#0d8050; }
      .bp3-button.bp3-minimal.bp3-intent-success:hover, .bp3-button.bp3-minimal.bp3-intent-success:active, .bp3-button.bp3-minimal.bp3-intent-success.bp3-active{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none;
        color:#0d8050; }
      .bp3-button.bp3-minimal.bp3-intent-success:hover{
        background:rgba(15, 153, 96, 0.15);
        color:#0d8050; }
      .bp3-button.bp3-minimal.bp3-intent-success:active, .bp3-button.bp3-minimal.bp3-intent-success.bp3-active{
        background:rgba(15, 153, 96, 0.3);
        color:#0d8050; }
      .bp3-button.bp3-minimal.bp3-intent-success:disabled, .bp3-button.bp3-minimal.bp3-intent-success.bp3-disabled{
        background:none;
        color:rgba(13, 128, 80, 0.5); }
        .bp3-button.bp3-minimal.bp3-intent-success:disabled.bp3-active, .bp3-button.bp3-minimal.bp3-intent-success.bp3-disabled.bp3-active{
          background:rgba(15, 153, 96, 0.3); }
      .bp3-button.bp3-minimal.bp3-intent-success .bp3-button-spinner .bp3-spinner-head{
        stroke:#0d8050; }
      .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success{
        color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success:hover{
          background:rgba(15, 153, 96, 0.2);
          color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success:active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success.bp3-active{
          background:rgba(15, 153, 96, 0.3);
          color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success:disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success.bp3-disabled{
          background:none;
          color:rgba(61, 204, 145, 0.5); }
          .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success.bp3-disabled.bp3-active{
            background:rgba(15, 153, 96, 0.3); }
    .bp3-button.bp3-minimal.bp3-intent-warning{
      color:#bf7326; }
      .bp3-button.bp3-minimal.bp3-intent-warning:hover, .bp3-button.bp3-minimal.bp3-intent-warning:active, .bp3-button.bp3-minimal.bp3-intent-warning.bp3-active{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none;
        color:#bf7326; }
      .bp3-button.bp3-minimal.bp3-intent-warning:hover{
        background:rgba(217, 130, 43, 0.15);
        color:#bf7326; }
      .bp3-button.bp3-minimal.bp3-intent-warning:active, .bp3-button.bp3-minimal.bp3-intent-warning.bp3-active{
        background:rgba(217, 130, 43, 0.3);
        color:#bf7326; }
      .bp3-button.bp3-minimal.bp3-intent-warning:disabled, .bp3-button.bp3-minimal.bp3-intent-warning.bp3-disabled{
        background:none;
        color:rgba(191, 115, 38, 0.5); }
        .bp3-button.bp3-minimal.bp3-intent-warning:disabled.bp3-active, .bp3-button.bp3-minimal.bp3-intent-warning.bp3-disabled.bp3-active{
          background:rgba(217, 130, 43, 0.3); }
      .bp3-button.bp3-minimal.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head{
        stroke:#bf7326; }
      .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning{
        color:#ffb366; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning:hover{
          background:rgba(217, 130, 43, 0.2);
          color:#ffb366; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning:active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning.bp3-active{
          background:rgba(217, 130, 43, 0.3);
          color:#ffb366; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning:disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning.bp3-disabled{
          background:none;
          color:rgba(255, 179, 102, 0.5); }
          .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning.bp3-disabled.bp3-active{
            background:rgba(217, 130, 43, 0.3); }
    .bp3-button.bp3-minimal.bp3-intent-danger{
      color:#c23030; }
      .bp3-button.bp3-minimal.bp3-intent-danger:hover, .bp3-button.bp3-minimal.bp3-intent-danger:active, .bp3-button.bp3-minimal.bp3-intent-danger.bp3-active{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none;
        color:#c23030; }
      .bp3-button.bp3-minimal.bp3-intent-danger:hover{
        background:rgba(219, 55, 55, 0.15);
        color:#c23030; }
      .bp3-button.bp3-minimal.bp3-intent-danger:active, .bp3-button.bp3-minimal.bp3-intent-danger.bp3-active{
        background:rgba(219, 55, 55, 0.3);
        color:#c23030; }
      .bp3-button.bp3-minimal.bp3-intent-danger:disabled, .bp3-button.bp3-minimal.bp3-intent-danger.bp3-disabled{
        background:none;
        color:rgba(194, 48, 48, 0.5); }
        .bp3-button.bp3-minimal.bp3-intent-danger:disabled.bp3-active, .bp3-button.bp3-minimal.bp3-intent-danger.bp3-disabled.bp3-active{
          background:rgba(219, 55, 55, 0.3); }
      .bp3-button.bp3-minimal.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head{
        stroke:#c23030; }
      .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger{
        color:#ff7373; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger:hover{
          background:rgba(219, 55, 55, 0.2);
          color:#ff7373; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger:active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger.bp3-active{
          background:rgba(219, 55, 55, 0.3);
          color:#ff7373; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger:disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger.bp3-disabled{
          background:none;
          color:rgba(255, 115, 115, 0.5); }
          .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger.bp3-disabled.bp3-active{
            background:rgba(219, 55, 55, 0.3); }

a.bp3-button{
  text-align:center;
  text-decoration:none;
  -webkit-transition:none;
  transition:none; }
  a.bp3-button, a.bp3-button:hover, a.bp3-button:active{
    color:#182026; }
  a.bp3-button.bp3-disabled{
    color:rgba(92, 112, 128, 0.6); }

.bp3-button-text{
  -webkit-box-flex:0;
      -ms-flex:0 1 auto;
          flex:0 1 auto; }

.bp3-button.bp3-align-left .bp3-button-text, .bp3-button.bp3-align-right .bp3-button-text,
.bp3-button-group.bp3-align-left .bp3-button-text,
.bp3-button-group.bp3-align-right .bp3-button-text{
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto; }
.bp3-button-group{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex; }
  .bp3-button-group .bp3-button{
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    position:relative;
    z-index:4; }
    .bp3-button-group .bp3-button:focus{
      z-index:5; }
    .bp3-button-group .bp3-button:hover{
      z-index:6; }
    .bp3-button-group .bp3-button:active, .bp3-button-group .bp3-button.bp3-active{
      z-index:7; }
    .bp3-button-group .bp3-button:disabled, .bp3-button-group .bp3-button.bp3-disabled{
      z-index:3; }
    .bp3-button-group .bp3-button[class*="bp3-intent-"]{
      z-index:9; }
      .bp3-button-group .bp3-button[class*="bp3-intent-"]:focus{
        z-index:10; }
      .bp3-button-group .bp3-button[class*="bp3-intent-"]:hover{
        z-index:11; }
      .bp3-button-group .bp3-button[class*="bp3-intent-"]:active, .bp3-button-group .bp3-button[class*="bp3-intent-"].bp3-active{
        z-index:12; }
      .bp3-button-group .bp3-button[class*="bp3-intent-"]:disabled, .bp3-button-group .bp3-button[class*="bp3-intent-"].bp3-disabled{
        z-index:8; }
  .bp3-button-group:not(.bp3-minimal) > .bp3-popover-wrapper:not(:first-child) .bp3-button,
  .bp3-button-group:not(.bp3-minimal) > .bp3-button:not(:first-child){
    border-top-left-radius:0;
    border-bottom-left-radius:0; }
  .bp3-button-group:not(.bp3-minimal) > .bp3-popover-wrapper:not(:last-child) .bp3-button,
  .bp3-button-group:not(.bp3-minimal) > .bp3-button:not(:last-child){
    margin-right:-1px;
    border-top-right-radius:0;
    border-bottom-right-radius:0; }
  .bp3-button-group.bp3-minimal .bp3-button{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:none; }
    .bp3-button-group.bp3-minimal .bp3-button:hover{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(167, 182, 194, 0.3);
      text-decoration:none;
      color:#182026; }
    .bp3-button-group.bp3-minimal .bp3-button:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-active{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(115, 134, 148, 0.3);
      color:#182026; }
    .bp3-button-group.bp3-minimal .bp3-button:disabled, .bp3-button-group.bp3-minimal .bp3-button:disabled:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover{
      background:none;
      cursor:not-allowed;
      color:rgba(92, 112, 128, 0.6); }
      .bp3-button-group.bp3-minimal .bp3-button:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button:disabled:hover.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover.bp3-active{
        background:rgba(115, 134, 148, 0.3); }
    .bp3-dark .bp3-button-group.bp3-minimal .bp3-button{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:none;
      color:inherit; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:hover, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-active{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:hover{
        background:rgba(138, 155, 168, 0.15); }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-active{
        background:rgba(138, 155, 168, 0.3);
        color:#f5f8fa; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled:hover, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover{
        background:none;
        cursor:not-allowed;
        color:rgba(167, 182, 194, 0.6); }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled:hover.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover.bp3-active{
          background:rgba(138, 155, 168, 0.3); }
    .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary{
      color:#106ba3; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-active{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none;
        color:#106ba3; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:hover{
        background:rgba(19, 124, 189, 0.15);
        color:#106ba3; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-active{
        background:rgba(19, 124, 189, 0.3);
        color:#106ba3; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-disabled{
        background:none;
        color:rgba(16, 107, 163, 0.5); }
        .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-disabled.bp3-active{
          background:rgba(19, 124, 189, 0.3); }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head{
        stroke:#106ba3; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary{
        color:#48aff0; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:hover{
          background:rgba(19, 124, 189, 0.2);
          color:#48aff0; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-active{
          background:rgba(19, 124, 189, 0.3);
          color:#48aff0; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-disabled{
          background:none;
          color:rgba(72, 175, 240, 0.5); }
          .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-disabled.bp3-active{
            background:rgba(19, 124, 189, 0.3); }
    .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success{
      color:#0d8050; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-active{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none;
        color:#0d8050; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:hover{
        background:rgba(15, 153, 96, 0.15);
        color:#0d8050; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-active{
        background:rgba(15, 153, 96, 0.3);
        color:#0d8050; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-disabled{
        background:none;
        color:rgba(13, 128, 80, 0.5); }
        .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-disabled.bp3-active{
          background:rgba(15, 153, 96, 0.3); }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success .bp3-button-spinner .bp3-spinner-head{
        stroke:#0d8050; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success{
        color:#3dcc91; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:hover{
          background:rgba(15, 153, 96, 0.2);
          color:#3dcc91; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-active{
          background:rgba(15, 153, 96, 0.3);
          color:#3dcc91; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-disabled{
          background:none;
          color:rgba(61, 204, 145, 0.5); }
          .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-disabled.bp3-active{
            background:rgba(15, 153, 96, 0.3); }
    .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning{
      color:#bf7326; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-active{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none;
        color:#bf7326; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:hover{
        background:rgba(217, 130, 43, 0.15);
        color:#bf7326; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-active{
        background:rgba(217, 130, 43, 0.3);
        color:#bf7326; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-disabled{
        background:none;
        color:rgba(191, 115, 38, 0.5); }
        .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-disabled.bp3-active{
          background:rgba(217, 130, 43, 0.3); }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head{
        stroke:#bf7326; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning{
        color:#ffb366; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:hover{
          background:rgba(217, 130, 43, 0.2);
          color:#ffb366; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-active{
          background:rgba(217, 130, 43, 0.3);
          color:#ffb366; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-disabled{
          background:none;
          color:rgba(255, 179, 102, 0.5); }
          .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-disabled.bp3-active{
            background:rgba(217, 130, 43, 0.3); }
    .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger{
      color:#c23030; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-active{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none;
        color:#c23030; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:hover{
        background:rgba(219, 55, 55, 0.15);
        color:#c23030; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-active{
        background:rgba(219, 55, 55, 0.3);
        color:#c23030; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-disabled{
        background:none;
        color:rgba(194, 48, 48, 0.5); }
        .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-disabled.bp3-active{
          background:rgba(219, 55, 55, 0.3); }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head{
        stroke:#c23030; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger{
        color:#ff7373; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:hover{
          background:rgba(219, 55, 55, 0.2);
          color:#ff7373; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-active{
          background:rgba(219, 55, 55, 0.3);
          color:#ff7373; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-disabled{
          background:none;
          color:rgba(255, 115, 115, 0.5); }
          .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-disabled.bp3-active{
            background:rgba(219, 55, 55, 0.3); }
  .bp3-button-group .bp3-popover-wrapper,
  .bp3-button-group .bp3-popover-target{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto; }
  .bp3-button-group.bp3-fill{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    width:100%; }
  .bp3-button-group .bp3-button.bp3-fill,
  .bp3-button-group.bp3-fill .bp3-button:not(.bp3-fixed){
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto; }
  .bp3-button-group.bp3-vertical{
    -webkit-box-orient:vertical;
    -webkit-box-direction:normal;
        -ms-flex-direction:column;
            flex-direction:column;
    -webkit-box-align:stretch;
        -ms-flex-align:stretch;
            align-items:stretch;
    vertical-align:top; }
    .bp3-button-group.bp3-vertical.bp3-fill{
      width:unset;
      height:100%; }
    .bp3-button-group.bp3-vertical .bp3-button{
      margin-right:0 !important;
      width:100%; }
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-popover-wrapper:first-child .bp3-button,
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-button:first-child{
      border-radius:3px 3px 0 0; }
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-popover-wrapper:last-child .bp3-button,
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-button:last-child{
      border-radius:0 0 3px 3px; }
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-popover-wrapper:not(:last-child) .bp3-button,
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-button:not(:last-child){
      margin-bottom:-1px; }
  .bp3-button-group.bp3-align-left .bp3-button{
    text-align:left; }
  .bp3-dark .bp3-button-group:not(.bp3-minimal) > .bp3-popover-wrapper:not(:last-child) .bp3-button,
  .bp3-dark .bp3-button-group:not(.bp3-minimal) > .bp3-button:not(:last-child){
    margin-right:1px; }
  .bp3-dark .bp3-button-group.bp3-vertical > .bp3-popover-wrapper:not(:last-child) .bp3-button,
  .bp3-dark .bp3-button-group.bp3-vertical > .bp3-button:not(:last-child){
    margin-bottom:1px; }
.bp3-callout{
  line-height:1.5;
  font-size:14px;
  position:relative;
  border-radius:3px;
  background-color:rgba(138, 155, 168, 0.15);
  width:100%;
  padding:10px 12px 9px; }
  .bp3-callout[class*="bp3-icon-"]{
    padding-left:40px; }
    .bp3-callout[class*="bp3-icon-"]::before{
      line-height:1;
      font-family:"Icons20", sans-serif;
      font-size:20px;
      font-weight:400;
      font-style:normal;
      -moz-osx-font-smoothing:grayscale;
      -webkit-font-smoothing:antialiased;
      position:absolute;
      top:10px;
      left:10px;
      color:#5c7080; }
  .bp3-callout.bp3-callout-icon{
    padding-left:40px; }
    .bp3-callout.bp3-callout-icon > .bp3-icon:first-child{
      position:absolute;
      top:10px;
      left:10px;
      color:#5c7080; }
  .bp3-callout .bp3-heading{
    margin-top:0;
    margin-bottom:5px;
    line-height:20px; }
    .bp3-callout .bp3-heading:last-child{
      margin-bottom:0; }
  .bp3-dark .bp3-callout{
    background-color:rgba(138, 155, 168, 0.2); }
    .bp3-dark .bp3-callout[class*="bp3-icon-"]::before{
      color:#a7b6c2; }
  .bp3-callout.bp3-intent-primary{
    background-color:rgba(19, 124, 189, 0.15); }
    .bp3-callout.bp3-intent-primary[class*="bp3-icon-"]::before,
    .bp3-callout.bp3-intent-primary > .bp3-icon:first-child,
    .bp3-callout.bp3-intent-primary .bp3-heading{
      color:#106ba3; }
    .bp3-dark .bp3-callout.bp3-intent-primary{
      background-color:rgba(19, 124, 189, 0.25); }
      .bp3-dark .bp3-callout.bp3-intent-primary[class*="bp3-icon-"]::before,
      .bp3-dark .bp3-callout.bp3-intent-primary > .bp3-icon:first-child,
      .bp3-dark .bp3-callout.bp3-intent-primary .bp3-heading{
        color:#48aff0; }
  .bp3-callout.bp3-intent-success{
    background-color:rgba(15, 153, 96, 0.15); }
    .bp3-callout.bp3-intent-success[class*="bp3-icon-"]::before,
    .bp3-callout.bp3-intent-success > .bp3-icon:first-child,
    .bp3-callout.bp3-intent-success .bp3-heading{
      color:#0d8050; }
    .bp3-dark .bp3-callout.bp3-intent-success{
      background-color:rgba(15, 153, 96, 0.25); }
      .bp3-dark .bp3-callout.bp3-intent-success[class*="bp3-icon-"]::before,
      .bp3-dark .bp3-callout.bp3-intent-success > .bp3-icon:first-child,
      .bp3-dark .bp3-callout.bp3-intent-success .bp3-heading{
        color:#3dcc91; }
  .bp3-callout.bp3-intent-warning{
    background-color:rgba(217, 130, 43, 0.15); }
    .bp3-callout.bp3-intent-warning[class*="bp3-icon-"]::before,
    .bp3-callout.bp3-intent-warning > .bp3-icon:first-child,
    .bp3-callout.bp3-intent-warning .bp3-heading{
      color:#bf7326; }
    .bp3-dark .bp3-callout.bp3-intent-warning{
      background-color:rgba(217, 130, 43, 0.25); }
      .bp3-dark .bp3-callout.bp3-intent-warning[class*="bp3-icon-"]::before,
      .bp3-dark .bp3-callout.bp3-intent-warning > .bp3-icon:first-child,
      .bp3-dark .bp3-callout.bp3-intent-warning .bp3-heading{
        color:#ffb366; }
  .bp3-callout.bp3-intent-danger{
    background-color:rgba(219, 55, 55, 0.15); }
    .bp3-callout.bp3-intent-danger[class*="bp3-icon-"]::before,
    .bp3-callout.bp3-intent-danger > .bp3-icon:first-child,
    .bp3-callout.bp3-intent-danger .bp3-heading{
      color:#c23030; }
    .bp3-dark .bp3-callout.bp3-intent-danger{
      background-color:rgba(219, 55, 55, 0.25); }
      .bp3-dark .bp3-callout.bp3-intent-danger[class*="bp3-icon-"]::before,
      .bp3-dark .bp3-callout.bp3-intent-danger > .bp3-icon:first-child,
      .bp3-dark .bp3-callout.bp3-intent-danger .bp3-heading{
        color:#ff7373; }
  .bp3-running-text .bp3-callout{
    margin:20px 0; }
.bp3-card{
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
  background-color:#ffffff;
  padding:20px;
  -webkit-transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-card.bp3-dark,
  .bp3-dark .bp3-card{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
    background-color:#30404d; }

.bp3-elevation-0{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0); }
  .bp3-elevation-0.bp3-dark,
  .bp3-dark .bp3-elevation-0{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0); }

.bp3-elevation-1{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-elevation-1.bp3-dark,
  .bp3-dark .bp3-elevation-1{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4); }

.bp3-elevation-2{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 1px 1px rgba(16, 22, 26, 0.2), 0 2px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 1px 1px rgba(16, 22, 26, 0.2), 0 2px 6px rgba(16, 22, 26, 0.2); }
  .bp3-elevation-2.bp3-dark,
  .bp3-dark .bp3-elevation-2{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.4), 0 2px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.4), 0 2px 6px rgba(16, 22, 26, 0.4); }

.bp3-elevation-3{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2); }
  .bp3-elevation-3.bp3-dark,
  .bp3-dark .bp3-elevation-3{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }

.bp3-elevation-4{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2); }
  .bp3-elevation-4.bp3-dark,
  .bp3-dark .bp3-elevation-4{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4); }

.bp3-card.bp3-interactive:hover{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  cursor:pointer; }
  .bp3-card.bp3-interactive:hover.bp3-dark,
  .bp3-dark .bp3-card.bp3-interactive:hover{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }

.bp3-card.bp3-interactive:active{
  opacity:0.9;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
  -webkit-transition-duration:0;
          transition-duration:0; }
  .bp3-card.bp3-interactive:active.bp3-dark,
  .bp3-dark .bp3-card.bp3-interactive:active{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4); }

.bp3-collapse{
  height:0;
  overflow-y:hidden;
  -webkit-transition:height 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:height 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-collapse .bp3-collapse-body{
    -webkit-transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-collapse .bp3-collapse-body[aria-hidden="true"]{
      display:none; }

.bp3-context-menu .bp3-popover-target{
  display:block; }

.bp3-context-menu-popover-target{
  position:fixed; }

.bp3-divider{
  margin:5px;
  border-right:1px solid rgba(16, 22, 26, 0.15);
  border-bottom:1px solid rgba(16, 22, 26, 0.15); }
  .bp3-dark .bp3-divider{
    border-color:rgba(16, 22, 26, 0.4); }
.bp3-dialog-container{
  opacity:1;
  -webkit-transform:scale(1);
          transform:scale(1);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  width:100%;
  min-height:100%;
  pointer-events:none;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-dialog-container.bp3-overlay-enter > .bp3-dialog, .bp3-dialog-container.bp3-overlay-appear > .bp3-dialog{
    opacity:0;
    -webkit-transform:scale(0.5);
            transform:scale(0.5); }
  .bp3-dialog-container.bp3-overlay-enter-active > .bp3-dialog, .bp3-dialog-container.bp3-overlay-appear-active > .bp3-dialog{
    opacity:1;
    -webkit-transform:scale(1);
            transform:scale(1);
    -webkit-transition-property:opacity, -webkit-transform;
    transition-property:opacity, -webkit-transform;
    transition-property:opacity, transform;
    transition-property:opacity, transform, -webkit-transform;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-dialog-container.bp3-overlay-exit > .bp3-dialog{
    opacity:1;
    -webkit-transform:scale(1);
            transform:scale(1); }
  .bp3-dialog-container.bp3-overlay-exit-active > .bp3-dialog{
    opacity:0;
    -webkit-transform:scale(0.5);
            transform:scale(0.5);
    -webkit-transition-property:opacity, -webkit-transform;
    transition-property:opacity, -webkit-transform;
    transition-property:opacity, transform;
    transition-property:opacity, transform, -webkit-transform;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
    -webkit-transition-delay:0;
            transition-delay:0; }

.bp3-dialog{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin:30px 0;
  border-radius:6px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
  background:#ebf1f5;
  width:500px;
  padding-bottom:20px;
  pointer-events:all;
  -webkit-user-select:text;
     -moz-user-select:text;
      -ms-user-select:text;
          user-select:text; }
  .bp3-dialog:focus{
    outline:0; }
  .bp3-dialog.bp3-dark,
  .bp3-dark .bp3-dialog{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
    background:#293742;
    color:#f5f8fa; }

.bp3-dialog-header{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  border-radius:6px 6px 0 0;
  -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
          box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
  background:#ffffff;
  min-height:40px;
  padding-right:5px;
  padding-left:20px; }
  .bp3-dialog-header .bp3-icon-large,
  .bp3-dialog-header .bp3-icon{
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    margin-right:10px;
    color:#5c7080; }
  .bp3-dialog-header .bp3-heading{
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    margin:0;
    line-height:inherit; }
    .bp3-dialog-header .bp3-heading:last-child{
      margin-right:20px; }
  .bp3-dark .bp3-dialog-header{
    -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.4);
            box-shadow:0 1px 0 rgba(16, 22, 26, 0.4);
    background:#30404d; }
    .bp3-dark .bp3-dialog-header .bp3-icon-large,
    .bp3-dark .bp3-dialog-header .bp3-icon{
      color:#a7b6c2; }

.bp3-dialog-body{
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto;
  margin:20px;
  line-height:18px; }

.bp3-dialog-footer{
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  margin:0 20px; }

.bp3-dialog-footer-actions{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-pack:end;
      -ms-flex-pack:end;
          justify-content:flex-end; }
  .bp3-dialog-footer-actions .bp3-button{
    margin-left:10px; }
.bp3-drawer{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin:0;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
  background:#ffffff;
  padding:0; }
  .bp3-drawer:focus{
    outline:0; }
  .bp3-drawer.bp3-position-top{
    top:0;
    right:0;
    left:0;
    height:50%; }
    .bp3-drawer.bp3-position-top.bp3-overlay-enter, .bp3-drawer.bp3-position-top.bp3-overlay-appear{
      -webkit-transform:translateY(-100%);
              transform:translateY(-100%); }
    .bp3-drawer.bp3-position-top.bp3-overlay-enter-active, .bp3-drawer.bp3-position-top.bp3-overlay-appear-active{
      -webkit-transform:translateY(0);
              transform:translateY(0);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
    .bp3-drawer.bp3-position-top.bp3-overlay-exit{
      -webkit-transform:translateY(0);
              transform:translateY(0); }
    .bp3-drawer.bp3-position-top.bp3-overlay-exit-active{
      -webkit-transform:translateY(-100%);
              transform:translateY(-100%);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
  .bp3-drawer.bp3-position-bottom{
    right:0;
    bottom:0;
    left:0;
    height:50%; }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-enter, .bp3-drawer.bp3-position-bottom.bp3-overlay-appear{
      -webkit-transform:translateY(100%);
              transform:translateY(100%); }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-enter-active, .bp3-drawer.bp3-position-bottom.bp3-overlay-appear-active{
      -webkit-transform:translateY(0);
              transform:translateY(0);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-exit{
      -webkit-transform:translateY(0);
              transform:translateY(0); }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-exit-active{
      -webkit-transform:translateY(100%);
              transform:translateY(100%);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
  .bp3-drawer.bp3-position-left{
    top:0;
    bottom:0;
    left:0;
    width:50%; }
    .bp3-drawer.bp3-position-left.bp3-overlay-enter, .bp3-drawer.bp3-position-left.bp3-overlay-appear{
      -webkit-transform:translateX(-100%);
              transform:translateX(-100%); }
    .bp3-drawer.bp3-position-left.bp3-overlay-enter-active, .bp3-drawer.bp3-position-left.bp3-overlay-appear-active{
      -webkit-transform:translateX(0);
              transform:translateX(0);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
    .bp3-drawer.bp3-position-left.bp3-overlay-exit{
      -webkit-transform:translateX(0);
              transform:translateX(0); }
    .bp3-drawer.bp3-position-left.bp3-overlay-exit-active{
      -webkit-transform:translateX(-100%);
              transform:translateX(-100%);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
  .bp3-drawer.bp3-position-right{
    top:0;
    right:0;
    bottom:0;
    width:50%; }
    .bp3-drawer.bp3-position-right.bp3-overlay-enter, .bp3-drawer.bp3-position-right.bp3-overlay-appear{
      -webkit-transform:translateX(100%);
              transform:translateX(100%); }
    .bp3-drawer.bp3-position-right.bp3-overlay-enter-active, .bp3-drawer.bp3-position-right.bp3-overlay-appear-active{
      -webkit-transform:translateX(0);
              transform:translateX(0);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
    .bp3-drawer.bp3-position-right.bp3-overlay-exit{
      -webkit-transform:translateX(0);
              transform:translateX(0); }
    .bp3-drawer.bp3-position-right.bp3-overlay-exit-active{
      -webkit-transform:translateX(100%);
              transform:translateX(100%);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
  .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
  .bp3-position-right):not(.bp3-vertical){
    top:0;
    right:0;
    bottom:0;
    width:50%; }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-enter, .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-appear{
      -webkit-transform:translateX(100%);
              transform:translateX(100%); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-enter-active, .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-appear-active{
      -webkit-transform:translateX(0);
              transform:translateX(0);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-exit{
      -webkit-transform:translateX(0);
              transform:translateX(0); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-exit-active{
      -webkit-transform:translateX(100%);
              transform:translateX(100%);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
  .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
  .bp3-position-right).bp3-vertical{
    right:0;
    bottom:0;
    left:0;
    height:50%; }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-enter, .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-appear{
      -webkit-transform:translateY(100%);
              transform:translateY(100%); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-enter-active, .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-appear-active{
      -webkit-transform:translateY(0);
              transform:translateY(0);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-exit{
      -webkit-transform:translateY(0);
              transform:translateY(0); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-exit-active{
      -webkit-transform:translateY(100%);
              transform:translateY(100%);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
  .bp3-drawer.bp3-dark,
  .bp3-dark .bp3-drawer{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
    background:#30404d;
    color:#f5f8fa; }

.bp3-drawer-header{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  position:relative;
  border-radius:0;
  -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
          box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
  min-height:40px;
  padding:5px;
  padding-left:20px; }
  .bp3-drawer-header .bp3-icon-large,
  .bp3-drawer-header .bp3-icon{
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    margin-right:10px;
    color:#5c7080; }
  .bp3-drawer-header .bp3-heading{
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    margin:0;
    line-height:inherit; }
    .bp3-drawer-header .bp3-heading:last-child{
      margin-right:20px; }
  .bp3-dark .bp3-drawer-header{
    -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.4);
            box-shadow:0 1px 0 rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-drawer-header .bp3-icon-large,
    .bp3-dark .bp3-drawer-header .bp3-icon{
      color:#a7b6c2; }

.bp3-drawer-body{
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto;
  overflow:auto;
  line-height:18px; }

.bp3-drawer-footer{
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  position:relative;
  -webkit-box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
          box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
  padding:10px 20px; }
  .bp3-dark .bp3-drawer-footer{
    -webkit-box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.4); }
.bp3-editable-text{
  display:inline-block;
  position:relative;
  cursor:text;
  max-width:100%;
  vertical-align:top;
  white-space:nowrap; }
  .bp3-editable-text::before{
    position:absolute;
    top:-3px;
    right:-3px;
    bottom:-3px;
    left:-3px;
    border-radius:3px;
    content:"";
    -webkit-transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-editable-text:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15); }
  .bp3-editable-text.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
    background-color:#ffffff; }
  .bp3-editable-text.bp3-disabled::before{
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-editable-text.bp3-intent-primary .bp3-editable-text-input,
  .bp3-editable-text.bp3-intent-primary .bp3-editable-text-content{
    color:#137cbd; }
  .bp3-editable-text.bp3-intent-primary:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(19, 124, 189, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(19, 124, 189, 0.4); }
  .bp3-editable-text.bp3-intent-primary.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-editable-text.bp3-intent-success .bp3-editable-text-input,
  .bp3-editable-text.bp3-intent-success .bp3-editable-text-content{
    color:#0f9960; }
  .bp3-editable-text.bp3-intent-success:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px rgba(15, 153, 96, 0.4);
            box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px rgba(15, 153, 96, 0.4); }
  .bp3-editable-text.bp3-intent-success.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-editable-text.bp3-intent-warning .bp3-editable-text-input,
  .bp3-editable-text.bp3-intent-warning .bp3-editable-text-content{
    color:#d9822b; }
  .bp3-editable-text.bp3-intent-warning:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px rgba(217, 130, 43, 0.4);
            box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px rgba(217, 130, 43, 0.4); }
  .bp3-editable-text.bp3-intent-warning.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-editable-text.bp3-intent-danger .bp3-editable-text-input,
  .bp3-editable-text.bp3-intent-danger .bp3-editable-text-content{
    color:#db3737; }
  .bp3-editable-text.bp3-intent-danger:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px rgba(219, 55, 55, 0.4);
            box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px rgba(219, 55, 55, 0.4); }
  .bp3-editable-text.bp3-intent-danger.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-editable-text:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(255, 255, 255, 0.15);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(255, 255, 255, 0.15); }
  .bp3-dark .bp3-editable-text.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    background-color:rgba(16, 22, 26, 0.3); }
  .bp3-dark .bp3-editable-text.bp3-disabled::before{
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-dark .bp3-editable-text.bp3-intent-primary .bp3-editable-text-content{
    color:#48aff0; }
  .bp3-dark .bp3-editable-text.bp3-intent-primary:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(72, 175, 240, 0), 0 0 0 0 rgba(72, 175, 240, 0), inset 0 0 0 1px rgba(72, 175, 240, 0.4);
            box-shadow:0 0 0 0 rgba(72, 175, 240, 0), 0 0 0 0 rgba(72, 175, 240, 0), inset 0 0 0 1px rgba(72, 175, 240, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-primary.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #48aff0, 0 0 0 3px rgba(72, 175, 240, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #48aff0, 0 0 0 3px rgba(72, 175, 240, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-success .bp3-editable-text-content{
    color:#3dcc91; }
  .bp3-dark .bp3-editable-text.bp3-intent-success:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(61, 204, 145, 0), 0 0 0 0 rgba(61, 204, 145, 0), inset 0 0 0 1px rgba(61, 204, 145, 0.4);
            box-shadow:0 0 0 0 rgba(61, 204, 145, 0), 0 0 0 0 rgba(61, 204, 145, 0), inset 0 0 0 1px rgba(61, 204, 145, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-success.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #3dcc91, 0 0 0 3px rgba(61, 204, 145, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #3dcc91, 0 0 0 3px rgba(61, 204, 145, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-warning .bp3-editable-text-content{
    color:#ffb366; }
  .bp3-dark .bp3-editable-text.bp3-intent-warning:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(255, 179, 102, 0), 0 0 0 0 rgba(255, 179, 102, 0), inset 0 0 0 1px rgba(255, 179, 102, 0.4);
            box-shadow:0 0 0 0 rgba(255, 179, 102, 0), 0 0 0 0 rgba(255, 179, 102, 0), inset 0 0 0 1px rgba(255, 179, 102, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-warning.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #ffb366, 0 0 0 3px rgba(255, 179, 102, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #ffb366, 0 0 0 3px rgba(255, 179, 102, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-danger .bp3-editable-text-content{
    color:#ff7373; }
  .bp3-dark .bp3-editable-text.bp3-intent-danger:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(255, 115, 115, 0), 0 0 0 0 rgba(255, 115, 115, 0), inset 0 0 0 1px rgba(255, 115, 115, 0.4);
            box-shadow:0 0 0 0 rgba(255, 115, 115, 0), 0 0 0 0 rgba(255, 115, 115, 0), inset 0 0 0 1px rgba(255, 115, 115, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-danger.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #ff7373, 0 0 0 3px rgba(255, 115, 115, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #ff7373, 0 0 0 3px rgba(255, 115, 115, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }

.bp3-editable-text-input,
.bp3-editable-text-content{
  display:inherit;
  position:relative;
  min-width:inherit;
  max-width:inherit;
  vertical-align:top;
  text-transform:inherit;
  letter-spacing:inherit;
  color:inherit;
  font:inherit;
  resize:none; }

.bp3-editable-text-input{
  border:none;
  -webkit-box-shadow:none;
          box-shadow:none;
  background:none;
  width:100%;
  padding:0;
  white-space:pre-wrap; }
  .bp3-editable-text-input::-webkit-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-editable-text-input::-moz-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-editable-text-input:-ms-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-editable-text-input::-ms-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-editable-text-input::placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-editable-text-input:focus{
    outline:none; }
  .bp3-editable-text-input::-ms-clear{
    display:none; }

.bp3-editable-text-content{
  overflow:hidden;
  padding-right:2px;
  text-overflow:ellipsis;
  white-space:pre; }
  .bp3-editable-text-editing > .bp3-editable-text-content{
    position:absolute;
    left:0;
    visibility:hidden; }
  .bp3-editable-text-placeholder > .bp3-editable-text-content{
    color:rgba(92, 112, 128, 0.6); }
    .bp3-dark .bp3-editable-text-placeholder > .bp3-editable-text-content{
      color:rgba(167, 182, 194, 0.6); }

.bp3-editable-text.bp3-multiline{
  display:block; }
  .bp3-editable-text.bp3-multiline .bp3-editable-text-content{
    overflow:auto;
    white-space:pre-wrap;
    word-wrap:break-word; }
.bp3-control-group{
  -webkit-transform:translateZ(0);
          transform:translateZ(0);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:stretch;
      -ms-flex-align:stretch;
          align-items:stretch; }
  .bp3-control-group > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-control-group > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-control-group .bp3-button,
  .bp3-control-group .bp3-html-select,
  .bp3-control-group .bp3-input,
  .bp3-control-group .bp3-select{
    position:relative; }
  .bp3-control-group .bp3-input{
    z-index:2;
    border-radius:inherit; }
    .bp3-control-group .bp3-input:focus{
      z-index:14;
      border-radius:3px; }
    .bp3-control-group .bp3-input[class*="bp3-intent"]{
      z-index:13; }
      .bp3-control-group .bp3-input[class*="bp3-intent"]:focus{
        z-index:15; }
    .bp3-control-group .bp3-input[readonly], .bp3-control-group .bp3-input:disabled, .bp3-control-group .bp3-input.bp3-disabled{
      z-index:1; }
  .bp3-control-group .bp3-input-group[class*="bp3-intent"] .bp3-input{
    z-index:13; }
    .bp3-control-group .bp3-input-group[class*="bp3-intent"] .bp3-input:focus{
      z-index:15; }
  .bp3-control-group .bp3-button,
  .bp3-control-group .bp3-html-select select,
  .bp3-control-group .bp3-select select{
    -webkit-transform:translateZ(0);
            transform:translateZ(0);
    z-index:4;
    border-radius:inherit; }
    .bp3-control-group .bp3-button:focus,
    .bp3-control-group .bp3-html-select select:focus,
    .bp3-control-group .bp3-select select:focus{
      z-index:5; }
    .bp3-control-group .bp3-button:hover,
    .bp3-control-group .bp3-html-select select:hover,
    .bp3-control-group .bp3-select select:hover{
      z-index:6; }
    .bp3-control-group .bp3-button:active,
    .bp3-control-group .bp3-html-select select:active,
    .bp3-control-group .bp3-select select:active{
      z-index:7; }
    .bp3-control-group .bp3-button[readonly], .bp3-control-group .bp3-button:disabled, .bp3-control-group .bp3-button.bp3-disabled,
    .bp3-control-group .bp3-html-select select[readonly],
    .bp3-control-group .bp3-html-select select:disabled,
    .bp3-control-group .bp3-html-select select.bp3-disabled,
    .bp3-control-group .bp3-select select[readonly],
    .bp3-control-group .bp3-select select:disabled,
    .bp3-control-group .bp3-select select.bp3-disabled{
      z-index:3; }
    .bp3-control-group .bp3-button[class*="bp3-intent"],
    .bp3-control-group .bp3-html-select select[class*="bp3-intent"],
    .bp3-control-group .bp3-select select[class*="bp3-intent"]{
      z-index:9; }
      .bp3-control-group .bp3-button[class*="bp3-intent"]:focus,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"]:focus,
      .bp3-control-group .bp3-select select[class*="bp3-intent"]:focus{
        z-index:10; }
      .bp3-control-group .bp3-button[class*="bp3-intent"]:hover,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"]:hover,
      .bp3-control-group .bp3-select select[class*="bp3-intent"]:hover{
        z-index:11; }
      .bp3-control-group .bp3-button[class*="bp3-intent"]:active,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"]:active,
      .bp3-control-group .bp3-select select[class*="bp3-intent"]:active{
        z-index:12; }
      .bp3-control-group .bp3-button[class*="bp3-intent"][readonly], .bp3-control-group .bp3-button[class*="bp3-intent"]:disabled, .bp3-control-group .bp3-button[class*="bp3-intent"].bp3-disabled,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"][readonly],
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"]:disabled,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"].bp3-disabled,
      .bp3-control-group .bp3-select select[class*="bp3-intent"][readonly],
      .bp3-control-group .bp3-select select[class*="bp3-intent"]:disabled,
      .bp3-control-group .bp3-select select[class*="bp3-intent"].bp3-disabled{
        z-index:8; }
  .bp3-control-group .bp3-input-group > .bp3-icon,
  .bp3-control-group .bp3-input-group > .bp3-button,
  .bp3-control-group .bp3-input-group > .bp3-input-action{
    z-index:16; }
  .bp3-control-group .bp3-select::after,
  .bp3-control-group .bp3-html-select::after,
  .bp3-control-group .bp3-select > .bp3-icon,
  .bp3-control-group .bp3-html-select > .bp3-icon{
    z-index:17; }
  .bp3-control-group:not(.bp3-vertical) > *{
    margin-right:-1px; }
  .bp3-dark .bp3-control-group:not(.bp3-vertical) > *{
    margin-right:0; }
  .bp3-dark .bp3-control-group:not(.bp3-vertical) > .bp3-button + .bp3-button{
    margin-left:1px; }
  .bp3-control-group .bp3-popover-wrapper,
  .bp3-control-group .bp3-popover-target{
    border-radius:inherit; }
  .bp3-control-group > :first-child{
    border-radius:3px 0 0 3px; }
  .bp3-control-group > :last-child{
    margin-right:0;
    border-radius:0 3px 3px 0; }
  .bp3-control-group > :only-child{
    margin-right:0;
    border-radius:3px; }
  .bp3-control-group .bp3-input-group .bp3-button{
    border-radius:3px; }
  .bp3-control-group > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto; }
  .bp3-control-group.bp3-fill > *:not(.bp3-fixed){
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto; }
  .bp3-control-group.bp3-vertical{
    -webkit-box-orient:vertical;
    -webkit-box-direction:normal;
        -ms-flex-direction:column;
            flex-direction:column; }
    .bp3-control-group.bp3-vertical > *{
      margin-top:-1px; }
    .bp3-control-group.bp3-vertical > :first-child{
      margin-top:0;
      border-radius:3px 3px 0 0; }
    .bp3-control-group.bp3-vertical > :last-child{
      border-radius:0 0 3px 3px; }
.bp3-control{
  display:block;
  position:relative;
  margin-bottom:10px;
  cursor:pointer;
  text-transform:none; }
  .bp3-control input:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    background-color:#137cbd;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    color:#ffffff; }
  .bp3-control:hover input:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    background-color:#106ba3; }
  .bp3-control input:not(:disabled):active:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background:#0e5a8a; }
  .bp3-control input:disabled:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(19, 124, 189, 0.5); }
  .bp3-dark .bp3-control input:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control:hover input:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    background-color:#106ba3; }
  .bp3-dark .bp3-control input:not(:disabled):active:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background-color:#0e5a8a; }
  .bp3-dark .bp3-control input:disabled:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(14, 90, 138, 0.5); }
  .bp3-control:not(.bp3-align-right){
    padding-left:26px; }
    .bp3-control:not(.bp3-align-right) .bp3-control-indicator{
      margin-left:-26px; }
  .bp3-control.bp3-align-right{
    padding-right:26px; }
    .bp3-control.bp3-align-right .bp3-control-indicator{
      margin-right:-26px; }
  .bp3-control.bp3-disabled{
    cursor:not-allowed;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-control.bp3-inline{
    display:inline-block;
    margin-right:20px; }
  .bp3-control input{
    position:absolute;
    top:0;
    left:0;
    opacity:0;
    z-index:-1; }
  .bp3-control .bp3-control-indicator{
    display:inline-block;
    position:relative;
    margin-top:-3px;
    margin-right:10px;
    border:none;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    background-clip:padding-box;
    background-color:#f5f8fa;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
    cursor:pointer;
    width:1em;
    height:1em;
    vertical-align:middle;
    font-size:16px;
    -webkit-user-select:none;
       -moz-user-select:none;
        -ms-user-select:none;
            user-select:none; }
    .bp3-control .bp3-control-indicator::before{
      display:block;
      width:1em;
      height:1em;
      content:""; }
  .bp3-control:hover .bp3-control-indicator{
    background-color:#ebf1f5; }
  .bp3-control input:not(:disabled):active ~ .bp3-control-indicator{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background:#d8e1e8; }
  .bp3-control input:disabled ~ .bp3-control-indicator{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(206, 217, 224, 0.5);
    cursor:not-allowed; }
  .bp3-control input:focus ~ .bp3-control-indicator{
    outline:rgba(19, 124, 189, 0.6) auto 2px;
    outline-offset:2px;
    -moz-outline-radius:6px; }
  .bp3-control.bp3-align-right .bp3-control-indicator{
    float:right;
    margin-top:1px;
    margin-left:10px; }
  .bp3-control.bp3-large{
    font-size:16px; }
    .bp3-control.bp3-large:not(.bp3-align-right){
      padding-left:30px; }
      .bp3-control.bp3-large:not(.bp3-align-right) .bp3-control-indicator{
        margin-left:-30px; }
    .bp3-control.bp3-large.bp3-align-right{
      padding-right:30px; }
      .bp3-control.bp3-large.bp3-align-right .bp3-control-indicator{
        margin-right:-30px; }
    .bp3-control.bp3-large .bp3-control-indicator{
      font-size:20px; }
    .bp3-control.bp3-large.bp3-align-right .bp3-control-indicator{
      margin-top:0; }
  .bp3-control.bp3-checkbox input:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    background-color:#137cbd;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    color:#ffffff; }
  .bp3-control.bp3-checkbox:hover input:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    background-color:#106ba3; }
  .bp3-control.bp3-checkbox input:not(:disabled):active:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background:#0e5a8a; }
  .bp3-control.bp3-checkbox input:disabled:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(19, 124, 189, 0.5); }
  .bp3-dark .bp3-control.bp3-checkbox input:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-checkbox:hover input:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    background-color:#106ba3; }
  .bp3-dark .bp3-control.bp3-checkbox input:not(:disabled):active:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background-color:#0e5a8a; }
  .bp3-dark .bp3-control.bp3-checkbox input:disabled:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(14, 90, 138, 0.5); }
  .bp3-control.bp3-checkbox .bp3-control-indicator{
    border-radius:3px; }
  .bp3-control.bp3-checkbox input:checked ~ .bp3-control-indicator::before{
    background-image:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill-rule='evenodd' clip-rule='evenodd' d='M12 5c-.28 0-.53.11-.71.29L7 9.59l-2.29-2.3a1.003 1.003 0 0 0-1.42 1.42l3 3c.18.18.43.29.71.29s.53-.11.71-.29l5-5A1.003 1.003 0 0 0 12 5z' fill='white'/%3e%3c/svg%3e"); }
  .bp3-control.bp3-checkbox input:indeterminate ~ .bp3-control-indicator::before{
    background-image:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill-rule='evenodd' clip-rule='evenodd' d='M11 7H5c-.55 0-1 .45-1 1s.45 1 1 1h6c.55 0 1-.45 1-1s-.45-1-1-1z' fill='white'/%3e%3c/svg%3e"); }
  .bp3-control.bp3-radio .bp3-control-indicator{
    border-radius:50%; }
  .bp3-control.bp3-radio input:checked ~ .bp3-control-indicator::before{
    background-image:radial-gradient(#ffffff, #ffffff 28%, transparent 32%); }
  .bp3-control.bp3-radio input:checked:disabled ~ .bp3-control-indicator::before{
    opacity:0.5; }
  .bp3-control.bp3-radio input:focus ~ .bp3-control-indicator{
    -moz-outline-radius:16px; }
  .bp3-control.bp3-switch input ~ .bp3-control-indicator{
    background:rgba(167, 182, 194, 0.5); }
  .bp3-control.bp3-switch:hover input ~ .bp3-control-indicator{
    background:rgba(115, 134, 148, 0.5); }
  .bp3-control.bp3-switch input:not(:disabled):active ~ .bp3-control-indicator{
    background:rgba(92, 112, 128, 0.5); }
  .bp3-control.bp3-switch input:disabled ~ .bp3-control-indicator{
    background:rgba(206, 217, 224, 0.5); }
    .bp3-control.bp3-switch input:disabled ~ .bp3-control-indicator::before{
      background:rgba(255, 255, 255, 0.8); }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator{
    background:#137cbd; }
  .bp3-control.bp3-switch:hover input:checked ~ .bp3-control-indicator{
    background:#106ba3; }
  .bp3-control.bp3-switch input:checked:not(:disabled):active ~ .bp3-control-indicator{
    background:#0e5a8a; }
  .bp3-control.bp3-switch input:checked:disabled ~ .bp3-control-indicator{
    background:rgba(19, 124, 189, 0.5); }
    .bp3-control.bp3-switch input:checked:disabled ~ .bp3-control-indicator::before{
      background:rgba(255, 255, 255, 0.8); }
  .bp3-control.bp3-switch:not(.bp3-align-right){
    padding-left:38px; }
    .bp3-control.bp3-switch:not(.bp3-align-right) .bp3-control-indicator{
      margin-left:-38px; }
  .bp3-control.bp3-switch.bp3-align-right{
    padding-right:38px; }
    .bp3-control.bp3-switch.bp3-align-right .bp3-control-indicator{
      margin-right:-38px; }
  .bp3-control.bp3-switch .bp3-control-indicator{
    border:none;
    border-radius:1.75em;
    -webkit-box-shadow:none !important;
            box-shadow:none !important;
    width:auto;
    min-width:1.75em;
    -webkit-transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-control.bp3-switch .bp3-control-indicator::before{
      position:absolute;
      left:0;
      margin:2px;
      border-radius:50%;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
      background:#ffffff;
      width:calc(1em - 4px);
      height:calc(1em - 4px);
      -webkit-transition:left 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
      transition:left 100ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator::before{
    left:calc(100% - 1em); }
  .bp3-control.bp3-switch.bp3-large:not(.bp3-align-right){
    padding-left:45px; }
    .bp3-control.bp3-switch.bp3-large:not(.bp3-align-right) .bp3-control-indicator{
      margin-left:-45px; }
  .bp3-control.bp3-switch.bp3-large.bp3-align-right{
    padding-right:45px; }
    .bp3-control.bp3-switch.bp3-large.bp3-align-right .bp3-control-indicator{
      margin-right:-45px; }
  .bp3-dark .bp3-control.bp3-switch input ~ .bp3-control-indicator{
    background:rgba(16, 22, 26, 0.5); }
  .bp3-dark .bp3-control.bp3-switch:hover input ~ .bp3-control-indicator{
    background:rgba(16, 22, 26, 0.7); }
  .bp3-dark .bp3-control.bp3-switch input:not(:disabled):active ~ .bp3-control-indicator{
    background:rgba(16, 22, 26, 0.9); }
  .bp3-dark .bp3-control.bp3-switch input:disabled ~ .bp3-control-indicator{
    background:rgba(57, 75, 89, 0.5); }
    .bp3-dark .bp3-control.bp3-switch input:disabled ~ .bp3-control-indicator::before{
      background:rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator{
    background:#137cbd; }
  .bp3-dark .bp3-control.bp3-switch:hover input:checked ~ .bp3-control-indicator{
    background:#106ba3; }
  .bp3-dark .bp3-control.bp3-switch input:checked:not(:disabled):active ~ .bp3-control-indicator{
    background:#0e5a8a; }
  .bp3-dark .bp3-control.bp3-switch input:checked:disabled ~ .bp3-control-indicator{
    background:rgba(14, 90, 138, 0.5); }
    .bp3-dark .bp3-control.bp3-switch input:checked:disabled ~ .bp3-control-indicator::before{
      background:rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-switch .bp3-control-indicator::before{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    background:#394b59; }
  .bp3-dark .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator::before{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-control.bp3-switch .bp3-switch-inner-text{
    text-align:center;
    font-size:0.7em; }
  .bp3-control.bp3-switch .bp3-control-indicator-child:first-child{
    visibility:hidden;
    margin-right:1.2em;
    margin-left:0.5em;
    line-height:0; }
  .bp3-control.bp3-switch .bp3-control-indicator-child:last-child{
    visibility:visible;
    margin-right:0.5em;
    margin-left:1.2em;
    line-height:1em; }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator .bp3-control-indicator-child:first-child{
    visibility:visible;
    line-height:1em; }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator .bp3-control-indicator-child:last-child{
    visibility:hidden;
    line-height:0; }
  .bp3-dark .bp3-control{
    color:#f5f8fa; }
    .bp3-dark .bp3-control.bp3-disabled{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-control .bp3-control-indicator{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
      background-color:#394b59;
      background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
      background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0)); }
    .bp3-dark .bp3-control:hover .bp3-control-indicator{
      background-color:#30404d; }
    .bp3-dark .bp3-control input:not(:disabled):active ~ .bp3-control-indicator{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background:#202b33; }
    .bp3-dark .bp3-control input:disabled ~ .bp3-control-indicator{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(57, 75, 89, 0.5);
      cursor:not-allowed; }
    .bp3-dark .bp3-control.bp3-checkbox input:disabled:checked ~ .bp3-control-indicator, .bp3-dark .bp3-control.bp3-checkbox input:disabled:indeterminate ~ .bp3-control-indicator{
      color:rgba(167, 182, 194, 0.6); }
.bp3-file-input{
  display:inline-block;
  position:relative;
  cursor:pointer;
  height:30px; }
  .bp3-file-input input{
    opacity:0;
    margin:0;
    min-width:200px; }
    .bp3-file-input input:disabled + .bp3-file-upload-input,
    .bp3-file-input input.bp3-disabled + .bp3-file-upload-input{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(206, 217, 224, 0.5);
      cursor:not-allowed;
      color:rgba(92, 112, 128, 0.6);
      resize:none; }
      .bp3-file-input input:disabled + .bp3-file-upload-input::after,
      .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after{
        outline:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        background-color:rgba(206, 217, 224, 0.5);
        background-image:none;
        cursor:not-allowed;
        color:rgba(92, 112, 128, 0.6); }
        .bp3-file-input input:disabled + .bp3-file-upload-input::after.bp3-active, .bp3-file-input input:disabled + .bp3-file-upload-input::after.bp3-active:hover,
        .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after.bp3-active,
        .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after.bp3-active:hover{
          background:rgba(206, 217, 224, 0.7); }
      .bp3-dark .bp3-file-input input:disabled + .bp3-file-upload-input, .bp3-dark
      .bp3-file-input input.bp3-disabled + .bp3-file-upload-input{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:rgba(57, 75, 89, 0.5);
        color:rgba(167, 182, 194, 0.6); }
        .bp3-dark .bp3-file-input input:disabled + .bp3-file-upload-input::after, .bp3-dark
        .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after{
          -webkit-box-shadow:none;
                  box-shadow:none;
          background-color:rgba(57, 75, 89, 0.5);
          background-image:none;
          color:rgba(167, 182, 194, 0.6); }
          .bp3-dark .bp3-file-input input:disabled + .bp3-file-upload-input::after.bp3-active, .bp3-dark
          .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after.bp3-active{
            background:rgba(57, 75, 89, 0.7); }
  .bp3-file-input.bp3-file-input-has-selection .bp3-file-upload-input{
    color:#182026; }
  .bp3-dark .bp3-file-input.bp3-file-input-has-selection .bp3-file-upload-input{
    color:#f5f8fa; }
  .bp3-file-input.bp3-fill{
    width:100%; }
  .bp3-file-input.bp3-large,
  .bp3-large .bp3-file-input{
    height:40px; }
  .bp3-file-input .bp3-file-upload-input-custom-text::after{
    content:attr(bp3-button-text); }

.bp3-file-upload-input{
  outline:none;
  border:none;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
  background:#ffffff;
  height:30px;
  padding:0 10px;
  vertical-align:middle;
  line-height:30px;
  color:#182026;
  font-size:14px;
  font-weight:400;
  -webkit-transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  -webkit-appearance:none;
     -moz-appearance:none;
          appearance:none;
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal;
  position:absolute;
  top:0;
  right:0;
  left:0;
  padding-right:80px;
  color:rgba(92, 112, 128, 0.6);
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-file-upload-input::-webkit-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-file-upload-input::-moz-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-file-upload-input:-ms-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-file-upload-input::-ms-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-file-upload-input::placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-file-upload-input:focus, .bp3-file-upload-input.bp3-active{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-file-upload-input[type="search"], .bp3-file-upload-input.bp3-round{
    border-radius:30px;
    -webkit-box-sizing:border-box;
            box-sizing:border-box;
    padding-left:10px; }
  .bp3-file-upload-input[readonly]{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15); }
  .bp3-file-upload-input:disabled, .bp3-file-upload-input.bp3-disabled{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(206, 217, 224, 0.5);
    cursor:not-allowed;
    color:rgba(92, 112, 128, 0.6);
    resize:none; }
  .bp3-file-upload-input::after{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    background-color:#f5f8fa;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
    color:#182026;
    min-width:24px;
    min-height:24px;
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    position:absolute;
    top:0;
    right:0;
    margin:3px;
    border-radius:3px;
    width:70px;
    text-align:center;
    line-height:24px;
    content:"Browse"; }
    .bp3-file-upload-input::after:hover{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
      background-clip:padding-box;
      background-color:#ebf1f5; }
    .bp3-file-upload-input::after:active, .bp3-file-upload-input::after.bp3-active{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#d8e1e8;
      background-image:none; }
    .bp3-file-upload-input::after:disabled, .bp3-file-upload-input::after.bp3-disabled{
      outline:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      background-color:rgba(206, 217, 224, 0.5);
      background-image:none;
      cursor:not-allowed;
      color:rgba(92, 112, 128, 0.6); }
      .bp3-file-upload-input::after:disabled.bp3-active, .bp3-file-upload-input::after:disabled.bp3-active:hover, .bp3-file-upload-input::after.bp3-disabled.bp3-active, .bp3-file-upload-input::after.bp3-disabled.bp3-active:hover{
        background:rgba(206, 217, 224, 0.7); }
  .bp3-file-upload-input:hover::after{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    background-clip:padding-box;
    background-color:#ebf1f5; }
  .bp3-file-upload-input:active::after{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background-color:#d8e1e8;
    background-image:none; }
  .bp3-large .bp3-file-upload-input{
    height:40px;
    line-height:40px;
    font-size:16px;
    padding-right:95px; }
    .bp3-large .bp3-file-upload-input[type="search"], .bp3-large .bp3-file-upload-input.bp3-round{
      padding:0 15px; }
    .bp3-large .bp3-file-upload-input::after{
      min-width:30px;
      min-height:30px;
      margin:5px;
      width:85px;
      line-height:30px; }
  .bp3-dark .bp3-file-upload-input{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    background:rgba(16, 22, 26, 0.3);
    color:#f5f8fa;
    color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::-webkit-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::-moz-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input:-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-file-upload-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-file-upload-input:disabled, .bp3-dark .bp3-file-upload-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(57, 75, 89, 0.5);
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::after{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
      background-color:#394b59;
      background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
      background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
      color:#f5f8fa; }
      .bp3-dark .bp3-file-upload-input::after:hover, .bp3-dark .bp3-file-upload-input::after:active, .bp3-dark .bp3-file-upload-input::after.bp3-active{
        color:#f5f8fa; }
      .bp3-dark .bp3-file-upload-input::after:hover{
        -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
        background-color:#30404d; }
      .bp3-dark .bp3-file-upload-input::after:active, .bp3-dark .bp3-file-upload-input::after.bp3-active{
        -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
                box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
        background-color:#202b33;
        background-image:none; }
      .bp3-dark .bp3-file-upload-input::after:disabled, .bp3-dark .bp3-file-upload-input::after.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none;
        background-color:rgba(57, 75, 89, 0.5);
        background-image:none;
        color:rgba(167, 182, 194, 0.6); }
        .bp3-dark .bp3-file-upload-input::after:disabled.bp3-active, .bp3-dark .bp3-file-upload-input::after.bp3-disabled.bp3-active{
          background:rgba(57, 75, 89, 0.7); }
      .bp3-dark .bp3-file-upload-input::after .bp3-button-spinner .bp3-spinner-head{
        background:rgba(16, 22, 26, 0.5);
        stroke:#8a9ba8; }
    .bp3-dark .bp3-file-upload-input:hover::after{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
      background-color:#30404d; }
    .bp3-dark .bp3-file-upload-input:active::after{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#202b33;
      background-image:none; }

.bp3-file-upload-input::after{
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
.bp3-form-group{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin:0 0 15px; }
  .bp3-form-group label.bp3-label{
    margin-bottom:5px; }
  .bp3-form-group .bp3-control{
    margin-top:7px; }
  .bp3-form-group .bp3-form-helper-text{
    margin-top:5px;
    color:#5c7080;
    font-size:12px; }
  .bp3-form-group.bp3-intent-primary .bp3-form-helper-text{
    color:#106ba3; }
  .bp3-form-group.bp3-intent-success .bp3-form-helper-text{
    color:#0d8050; }
  .bp3-form-group.bp3-intent-warning .bp3-form-helper-text{
    color:#bf7326; }
  .bp3-form-group.bp3-intent-danger .bp3-form-helper-text{
    color:#c23030; }
  .bp3-form-group.bp3-inline{
    -webkit-box-orient:horizontal;
    -webkit-box-direction:normal;
        -ms-flex-direction:row;
            flex-direction:row;
    -webkit-box-align:start;
        -ms-flex-align:start;
            align-items:flex-start; }
    .bp3-form-group.bp3-inline.bp3-large label.bp3-label{
      margin:0 10px 0 0;
      line-height:40px; }
    .bp3-form-group.bp3-inline label.bp3-label{
      margin:0 10px 0 0;
      line-height:30px; }
  .bp3-form-group.bp3-disabled .bp3-label,
  .bp3-form-group.bp3-disabled .bp3-text-muted,
  .bp3-form-group.bp3-disabled .bp3-form-helper-text{
    color:rgba(92, 112, 128, 0.6) !important; }
  .bp3-dark .bp3-form-group.bp3-intent-primary .bp3-form-helper-text{
    color:#48aff0; }
  .bp3-dark .bp3-form-group.bp3-intent-success .bp3-form-helper-text{
    color:#3dcc91; }
  .bp3-dark .bp3-form-group.bp3-intent-warning .bp3-form-helper-text{
    color:#ffb366; }
  .bp3-dark .bp3-form-group.bp3-intent-danger .bp3-form-helper-text{
    color:#ff7373; }
  .bp3-dark .bp3-form-group .bp3-form-helper-text{
    color:#a7b6c2; }
  .bp3-dark .bp3-form-group.bp3-disabled .bp3-label,
  .bp3-dark .bp3-form-group.bp3-disabled .bp3-text-muted,
  .bp3-dark .bp3-form-group.bp3-disabled .bp3-form-helper-text{
    color:rgba(167, 182, 194, 0.6) !important; }
.bp3-input-group{
  display:block;
  position:relative; }
  .bp3-input-group .bp3-input{
    position:relative;
    width:100%; }
    .bp3-input-group .bp3-input:not(:first-child){
      padding-left:30px; }
    .bp3-input-group .bp3-input:not(:last-child){
      padding-right:30px; }
  .bp3-input-group .bp3-input-action,
  .bp3-input-group > .bp3-button,
  .bp3-input-group > .bp3-icon{
    position:absolute;
    top:0; }
    .bp3-input-group .bp3-input-action:first-child,
    .bp3-input-group > .bp3-button:first-child,
    .bp3-input-group > .bp3-icon:first-child{
      left:0; }
    .bp3-input-group .bp3-input-action:last-child,
    .bp3-input-group > .bp3-button:last-child,
    .bp3-input-group > .bp3-icon:last-child{
      right:0; }
  .bp3-input-group .bp3-button{
    min-width:24px;
    min-height:24px;
    margin:3px;
    padding:0 7px; }
    .bp3-input-group .bp3-button:empty{
      padding:0; }
  .bp3-input-group > .bp3-icon{
    z-index:1;
    color:#5c7080; }
    .bp3-input-group > .bp3-icon:empty{
      line-height:1;
      font-family:"Icons16", sans-serif;
      font-size:16px;
      font-weight:400;
      font-style:normal;
      -moz-osx-font-smoothing:grayscale;
      -webkit-font-smoothing:antialiased; }
  .bp3-input-group > .bp3-icon,
  .bp3-input-group .bp3-input-action > .bp3-spinner{
    margin:7px; }
  .bp3-input-group .bp3-tag{
    margin:5px; }
  .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus),
  .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus){
    color:#5c7080; }
    .bp3-dark .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus), .bp3-dark
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus){
      color:#a7b6c2; }
    .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon, .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon-standard, .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon-large,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon-standard,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon-large{
      color:#5c7080; }
  .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:disabled,
  .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:disabled{
    color:rgba(92, 112, 128, 0.6) !important; }
    .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:disabled .bp3-icon, .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:disabled .bp3-icon-standard, .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:disabled .bp3-icon-large,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:disabled .bp3-icon,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:disabled .bp3-icon-standard,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:disabled .bp3-icon-large{
      color:rgba(92, 112, 128, 0.6) !important; }
  .bp3-input-group.bp3-disabled{
    cursor:not-allowed; }
    .bp3-input-group.bp3-disabled .bp3-icon{
      color:rgba(92, 112, 128, 0.6); }
  .bp3-input-group.bp3-large .bp3-button{
    min-width:30px;
    min-height:30px;
    margin:5px; }
  .bp3-input-group.bp3-large > .bp3-icon,
  .bp3-input-group.bp3-large .bp3-input-action > .bp3-spinner{
    margin:12px; }
  .bp3-input-group.bp3-large .bp3-input{
    height:40px;
    line-height:40px;
    font-size:16px; }
    .bp3-input-group.bp3-large .bp3-input[type="search"], .bp3-input-group.bp3-large .bp3-input.bp3-round{
      padding:0 15px; }
    .bp3-input-group.bp3-large .bp3-input:not(:first-child){
      padding-left:40px; }
    .bp3-input-group.bp3-large .bp3-input:not(:last-child){
      padding-right:40px; }
  .bp3-input-group.bp3-small .bp3-button{
    min-width:20px;
    min-height:20px;
    margin:2px; }
  .bp3-input-group.bp3-small .bp3-tag{
    min-width:20px;
    min-height:20px;
    margin:2px; }
  .bp3-input-group.bp3-small > .bp3-icon,
  .bp3-input-group.bp3-small .bp3-input-action > .bp3-spinner{
    margin:4px; }
  .bp3-input-group.bp3-small .bp3-input{
    height:24px;
    padding-right:8px;
    padding-left:8px;
    line-height:24px;
    font-size:12px; }
    .bp3-input-group.bp3-small .bp3-input[type="search"], .bp3-input-group.bp3-small .bp3-input.bp3-round{
      padding:0 12px; }
    .bp3-input-group.bp3-small .bp3-input:not(:first-child){
      padding-left:24px; }
    .bp3-input-group.bp3-small .bp3-input:not(:last-child){
      padding-right:24px; }
  .bp3-input-group.bp3-fill{
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    width:100%; }
  .bp3-input-group.bp3-round .bp3-button,
  .bp3-input-group.bp3-round .bp3-input,
  .bp3-input-group.bp3-round .bp3-tag{
    border-radius:30px; }
  .bp3-dark .bp3-input-group .bp3-icon{
    color:#a7b6c2; }
  .bp3-dark .bp3-input-group.bp3-disabled .bp3-icon{
    color:rgba(167, 182, 194, 0.6); }
  .bp3-input-group.bp3-intent-primary .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-primary .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-primary .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #137cbd;
              box-shadow:inset 0 0 0 1px #137cbd; }
    .bp3-input-group.bp3-intent-primary .bp3-input:disabled, .bp3-input-group.bp3-intent-primary .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-input-group.bp3-intent-primary > .bp3-icon{
    color:#106ba3; }
    .bp3-dark .bp3-input-group.bp3-intent-primary > .bp3-icon{
      color:#48aff0; }
  .bp3-input-group.bp3-intent-success .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-success .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-success .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #0f9960;
              box-shadow:inset 0 0 0 1px #0f9960; }
    .bp3-input-group.bp3-intent-success .bp3-input:disabled, .bp3-input-group.bp3-intent-success .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-input-group.bp3-intent-success > .bp3-icon{
    color:#0d8050; }
    .bp3-dark .bp3-input-group.bp3-intent-success > .bp3-icon{
      color:#3dcc91; }
  .bp3-input-group.bp3-intent-warning .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-warning .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-warning .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #d9822b;
              box-shadow:inset 0 0 0 1px #d9822b; }
    .bp3-input-group.bp3-intent-warning .bp3-input:disabled, .bp3-input-group.bp3-intent-warning .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-input-group.bp3-intent-warning > .bp3-icon{
    color:#bf7326; }
    .bp3-dark .bp3-input-group.bp3-intent-warning > .bp3-icon{
      color:#ffb366; }
  .bp3-input-group.bp3-intent-danger .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-danger .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-danger .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #db3737;
              box-shadow:inset 0 0 0 1px #db3737; }
    .bp3-input-group.bp3-intent-danger .bp3-input:disabled, .bp3-input-group.bp3-intent-danger .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-input-group.bp3-intent-danger > .bp3-icon{
    color:#c23030; }
    .bp3-dark .bp3-input-group.bp3-intent-danger > .bp3-icon{
      color:#ff7373; }
.bp3-input{
  outline:none;
  border:none;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
  background:#ffffff;
  height:30px;
  padding:0 10px;
  vertical-align:middle;
  line-height:30px;
  color:#182026;
  font-size:14px;
  font-weight:400;
  -webkit-transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  -webkit-appearance:none;
     -moz-appearance:none;
          appearance:none; }
  .bp3-input::-webkit-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input::-moz-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input:-ms-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input::-ms-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input::placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input:focus, .bp3-input.bp3-active{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-input[type="search"], .bp3-input.bp3-round{
    border-radius:30px;
    -webkit-box-sizing:border-box;
            box-sizing:border-box;
    padding-left:10px; }
  .bp3-input[readonly]{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15); }
  .bp3-input:disabled, .bp3-input.bp3-disabled{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(206, 217, 224, 0.5);
    cursor:not-allowed;
    color:rgba(92, 112, 128, 0.6);
    resize:none; }
  .bp3-input.bp3-large{
    height:40px;
    line-height:40px;
    font-size:16px; }
    .bp3-input.bp3-large[type="search"], .bp3-input.bp3-large.bp3-round{
      padding:0 15px; }
  .bp3-input.bp3-small{
    height:24px;
    padding-right:8px;
    padding-left:8px;
    line-height:24px;
    font-size:12px; }
    .bp3-input.bp3-small[type="search"], .bp3-input.bp3-small.bp3-round{
      padding:0 12px; }
  .bp3-input.bp3-fill{
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    width:100%; }
  .bp3-dark .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    background:rgba(16, 22, 26, 0.3);
    color:#f5f8fa; }
    .bp3-dark .bp3-input::-webkit-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input::-moz-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input:-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input::-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input::placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-input:disabled, .bp3-dark .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(57, 75, 89, 0.5);
      color:rgba(167, 182, 194, 0.6); }
  .bp3-input.bp3-intent-primary{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-primary:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-primary[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #137cbd;
              box-shadow:inset 0 0 0 1px #137cbd; }
    .bp3-input.bp3-intent-primary:disabled, .bp3-input.bp3-intent-primary.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-input.bp3-intent-primary{
      -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-primary:focus{
        -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-primary[readonly]{
        -webkit-box-shadow:inset 0 0 0 1px #137cbd;
                box-shadow:inset 0 0 0 1px #137cbd; }
      .bp3-dark .bp3-input.bp3-intent-primary:disabled, .bp3-dark .bp3-input.bp3-intent-primary.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none; }
  .bp3-input.bp3-intent-success{
    -webkit-box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-success:focus{
      -webkit-box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-success[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #0f9960;
              box-shadow:inset 0 0 0 1px #0f9960; }
    .bp3-input.bp3-intent-success:disabled, .bp3-input.bp3-intent-success.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-input.bp3-intent-success{
      -webkit-box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-success:focus{
        -webkit-box-shadow:0 0 0 1px #0f9960, 0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px #0f9960, 0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-success[readonly]{
        -webkit-box-shadow:inset 0 0 0 1px #0f9960;
                box-shadow:inset 0 0 0 1px #0f9960; }
      .bp3-dark .bp3-input.bp3-intent-success:disabled, .bp3-dark .bp3-input.bp3-intent-success.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none; }
  .bp3-input.bp3-intent-warning{
    -webkit-box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-warning:focus{
      -webkit-box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-warning[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #d9822b;
              box-shadow:inset 0 0 0 1px #d9822b; }
    .bp3-input.bp3-intent-warning:disabled, .bp3-input.bp3-intent-warning.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-input.bp3-intent-warning{
      -webkit-box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-warning:focus{
        -webkit-box-shadow:0 0 0 1px #d9822b, 0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px #d9822b, 0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-warning[readonly]{
        -webkit-box-shadow:inset 0 0 0 1px #d9822b;
                box-shadow:inset 0 0 0 1px #d9822b; }
      .bp3-dark .bp3-input.bp3-intent-warning:disabled, .bp3-dark .bp3-input.bp3-intent-warning.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none; }
  .bp3-input.bp3-intent-danger{
    -webkit-box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-danger:focus{
      -webkit-box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-danger[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #db3737;
              box-shadow:inset 0 0 0 1px #db3737; }
    .bp3-input.bp3-intent-danger:disabled, .bp3-input.bp3-intent-danger.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-input.bp3-intent-danger{
      -webkit-box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-danger:focus{
        -webkit-box-shadow:0 0 0 1px #db3737, 0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px #db3737, 0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-danger[readonly]{
        -webkit-box-shadow:inset 0 0 0 1px #db3737;
                box-shadow:inset 0 0 0 1px #db3737; }
      .bp3-dark .bp3-input.bp3-intent-danger:disabled, .bp3-dark .bp3-input.bp3-intent-danger.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none; }
  .bp3-input::-ms-clear{
    display:none; }
textarea.bp3-input{
  max-width:100%;
  padding:10px; }
  textarea.bp3-input, textarea.bp3-input.bp3-large, textarea.bp3-input.bp3-small{
    height:auto;
    line-height:inherit; }
  textarea.bp3-input.bp3-small{
    padding:8px; }
  .bp3-dark textarea.bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    background:rgba(16, 22, 26, 0.3);
    color:#f5f8fa; }
    .bp3-dark textarea.bp3-input::-webkit-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input::-moz-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input:-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input::-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input::placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark textarea.bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark textarea.bp3-input:disabled, .bp3-dark textarea.bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(57, 75, 89, 0.5);
      color:rgba(167, 182, 194, 0.6); }
label.bp3-label{
  display:block;
  margin-top:0;
  margin-bottom:15px; }
  label.bp3-label .bp3-html-select,
  label.bp3-label .bp3-input,
  label.bp3-label .bp3-select,
  label.bp3-label .bp3-slider,
  label.bp3-label .bp3-popover-wrapper{
    display:block;
    margin-top:5px;
    text-transform:none; }
  label.bp3-label .bp3-button-group{
    margin-top:5px; }
  label.bp3-label .bp3-select select,
  label.bp3-label .bp3-html-select select{
    width:100%;
    vertical-align:top;
    font-weight:400; }
  label.bp3-label.bp3-disabled,
  label.bp3-label.bp3-disabled .bp3-text-muted{
    color:rgba(92, 112, 128, 0.6); }
  label.bp3-label.bp3-inline{
    line-height:30px; }
    label.bp3-label.bp3-inline .bp3-html-select,
    label.bp3-label.bp3-inline .bp3-input,
    label.bp3-label.bp3-inline .bp3-input-group,
    label.bp3-label.bp3-inline .bp3-select,
    label.bp3-label.bp3-inline .bp3-popover-wrapper{
      display:inline-block;
      margin:0 0 0 5px;
      vertical-align:top; }
    label.bp3-label.bp3-inline .bp3-button-group{
      margin:0 0 0 5px; }
    label.bp3-label.bp3-inline .bp3-input-group .bp3-input{
      margin-left:0; }
    label.bp3-label.bp3-inline.bp3-large{
      line-height:40px; }
  label.bp3-label:not(.bp3-inline) .bp3-popover-target{
    display:block; }
  .bp3-dark label.bp3-label{
    color:#f5f8fa; }
    .bp3-dark label.bp3-label.bp3-disabled,
    .bp3-dark label.bp3-label.bp3-disabled .bp3-text-muted{
      color:rgba(167, 182, 194, 0.6); }
.bp3-numeric-input .bp3-button-group.bp3-vertical > .bp3-button{
  -webkit-box-flex:1;
      -ms-flex:1 1 14px;
          flex:1 1 14px;
  width:30px;
  min-height:0;
  padding:0; }
  .bp3-numeric-input .bp3-button-group.bp3-vertical > .bp3-button:first-child{
    border-radius:0 3px 0 0; }
  .bp3-numeric-input .bp3-button-group.bp3-vertical > .bp3-button:last-child{
    border-radius:0 0 3px 0; }

.bp3-numeric-input .bp3-button-group.bp3-vertical:first-child > .bp3-button:first-child{
  border-radius:3px 0 0 0; }

.bp3-numeric-input .bp3-button-group.bp3-vertical:first-child > .bp3-button:last-child{
  border-radius:0 0 0 3px; }

.bp3-numeric-input.bp3-large .bp3-button-group.bp3-vertical > .bp3-button{
  width:40px; }

form{
  display:block; }
.bp3-html-select select,
.bp3-select select{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  border:none;
  border-radius:3px;
  cursor:pointer;
  padding:5px 10px;
  vertical-align:middle;
  text-align:left;
  font-size:14px;
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
  background-color:#f5f8fa;
  background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
  background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
  color:#182026;
  border-radius:3px;
  width:100%;
  height:30px;
  padding:0 25px 0 10px;
  -moz-appearance:none;
  -webkit-appearance:none; }
  .bp3-html-select select > *, .bp3-select select > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-html-select select > .bp3-fill, .bp3-select select > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-html-select select::before,
  .bp3-select select::before, .bp3-html-select select > *, .bp3-select select > *{
    margin-right:7px; }
  .bp3-html-select select:empty::before,
  .bp3-select select:empty::before,
  .bp3-html-select select > :last-child,
  .bp3-select select > :last-child{
    margin-right:0; }
  .bp3-html-select select:hover,
  .bp3-select select:hover{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    background-clip:padding-box;
    background-color:#ebf1f5; }
  .bp3-html-select select:active,
  .bp3-select select:active, .bp3-html-select select.bp3-active,
  .bp3-select select.bp3-active{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background-color:#d8e1e8;
    background-image:none; }
  .bp3-html-select select:disabled,
  .bp3-select select:disabled, .bp3-html-select select.bp3-disabled,
  .bp3-select select.bp3-disabled{
    outline:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    background-color:rgba(206, 217, 224, 0.5);
    background-image:none;
    cursor:not-allowed;
    color:rgba(92, 112, 128, 0.6); }
    .bp3-html-select select:disabled.bp3-active,
    .bp3-select select:disabled.bp3-active, .bp3-html-select select:disabled.bp3-active:hover,
    .bp3-select select:disabled.bp3-active:hover, .bp3-html-select select.bp3-disabled.bp3-active,
    .bp3-select select.bp3-disabled.bp3-active, .bp3-html-select select.bp3-disabled.bp3-active:hover,
    .bp3-select select.bp3-disabled.bp3-active:hover{
      background:rgba(206, 217, 224, 0.7); }

.bp3-html-select.bp3-minimal select,
.bp3-select.bp3-minimal select{
  -webkit-box-shadow:none;
          box-shadow:none;
  background:none; }
  .bp3-html-select.bp3-minimal select:hover,
  .bp3-select.bp3-minimal select:hover{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(167, 182, 194, 0.3);
    text-decoration:none;
    color:#182026; }
  .bp3-html-select.bp3-minimal select:active,
  .bp3-select.bp3-minimal select:active, .bp3-html-select.bp3-minimal select.bp3-active,
  .bp3-select.bp3-minimal select.bp3-active{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(115, 134, 148, 0.3);
    color:#182026; }
  .bp3-html-select.bp3-minimal select:disabled,
  .bp3-select.bp3-minimal select:disabled, .bp3-html-select.bp3-minimal select:disabled:hover,
  .bp3-select.bp3-minimal select:disabled:hover, .bp3-html-select.bp3-minimal select.bp3-disabled,
  .bp3-select.bp3-minimal select.bp3-disabled, .bp3-html-select.bp3-minimal select.bp3-disabled:hover,
  .bp3-select.bp3-minimal select.bp3-disabled:hover{
    background:none;
    cursor:not-allowed;
    color:rgba(92, 112, 128, 0.6); }
    .bp3-html-select.bp3-minimal select:disabled.bp3-active,
    .bp3-select.bp3-minimal select:disabled.bp3-active, .bp3-html-select.bp3-minimal select:disabled:hover.bp3-active,
    .bp3-select.bp3-minimal select:disabled:hover.bp3-active, .bp3-html-select.bp3-minimal select.bp3-disabled.bp3-active,
    .bp3-select.bp3-minimal select.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-disabled:hover.bp3-active,
    .bp3-select.bp3-minimal select.bp3-disabled:hover.bp3-active{
      background:rgba(115, 134, 148, 0.3); }
  .bp3-dark .bp3-html-select.bp3-minimal select, .bp3-html-select.bp3-minimal .bp3-dark select,
  .bp3-dark .bp3-select.bp3-minimal select, .bp3-select.bp3-minimal .bp3-dark select{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:none;
    color:inherit; }
    .bp3-dark .bp3-html-select.bp3-minimal select:hover, .bp3-html-select.bp3-minimal .bp3-dark select:hover,
    .bp3-dark .bp3-select.bp3-minimal select:hover, .bp3-select.bp3-minimal .bp3-dark select:hover, .bp3-dark .bp3-html-select.bp3-minimal select:active, .bp3-html-select.bp3-minimal .bp3-dark select:active,
    .bp3-dark .bp3-select.bp3-minimal select:active, .bp3-select.bp3-minimal .bp3-dark select:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-active,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-active{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:none; }
    .bp3-dark .bp3-html-select.bp3-minimal select:hover, .bp3-html-select.bp3-minimal .bp3-dark select:hover,
    .bp3-dark .bp3-select.bp3-minimal select:hover, .bp3-select.bp3-minimal .bp3-dark select:hover{
      background:rgba(138, 155, 168, 0.15); }
    .bp3-dark .bp3-html-select.bp3-minimal select:active, .bp3-html-select.bp3-minimal .bp3-dark select:active,
    .bp3-dark .bp3-select.bp3-minimal select:active, .bp3-select.bp3-minimal .bp3-dark select:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-active,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-active{
      background:rgba(138, 155, 168, 0.3);
      color:#f5f8fa; }
    .bp3-dark .bp3-html-select.bp3-minimal select:disabled, .bp3-html-select.bp3-minimal .bp3-dark select:disabled,
    .bp3-dark .bp3-select.bp3-minimal select:disabled, .bp3-select.bp3-minimal .bp3-dark select:disabled, .bp3-dark .bp3-html-select.bp3-minimal select:disabled:hover, .bp3-html-select.bp3-minimal .bp3-dark select:disabled:hover,
    .bp3-dark .bp3-select.bp3-minimal select:disabled:hover, .bp3-select.bp3-minimal .bp3-dark select:disabled:hover, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-disabled,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-disabled:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-disabled:hover,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-disabled:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-disabled:hover{
      background:none;
      cursor:not-allowed;
      color:rgba(167, 182, 194, 0.6); }
      .bp3-dark .bp3-html-select.bp3-minimal select:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select:disabled.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select:disabled:hover.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select:disabled:hover.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select:disabled:hover.bp3-active, .bp3-select.bp3-minimal .bp3-dark select:disabled:hover.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-disabled.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-disabled:hover.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-disabled:hover.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-disabled:hover.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-disabled:hover.bp3-active{
        background:rgba(138, 155, 168, 0.3); }
  .bp3-html-select.bp3-minimal select.bp3-intent-primary,
  .bp3-select.bp3-minimal select.bp3-intent-primary{
    color:#106ba3; }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary:hover,
    .bp3-select.bp3-minimal select.bp3-intent-primary:hover, .bp3-html-select.bp3-minimal select.bp3-intent-primary:active,
    .bp3-select.bp3-minimal select.bp3-intent-primary:active, .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-active{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:none;
      color:#106ba3; }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary:hover,
    .bp3-select.bp3-minimal select.bp3-intent-primary:hover{
      background:rgba(19, 124, 189, 0.15);
      color:#106ba3; }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary:active,
    .bp3-select.bp3-minimal select.bp3-intent-primary:active, .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-active{
      background:rgba(19, 124, 189, 0.3);
      color:#106ba3; }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary:disabled,
    .bp3-select.bp3-minimal select.bp3-intent-primary:disabled, .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-disabled,
    .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-disabled{
      background:none;
      color:rgba(16, 107, 163, 0.5); }
      .bp3-html-select.bp3-minimal select.bp3-intent-primary:disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-primary:disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-disabled.bp3-active{
        background:rgba(19, 124, 189, 0.3); }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head, .bp3-select.bp3-minimal select.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head{
      stroke:#106ba3; }
    .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary{
      color:#48aff0; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary:hover,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary:hover{
        background:rgba(19, 124, 189, 0.2);
        color:#48aff0; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary:active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary:active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary:active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-active{
        background:rgba(19, 124, 189, 0.3);
        color:#48aff0; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary:disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary:disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary:disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary:disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-disabled{
        background:none;
        color:rgba(72, 175, 240, 0.5); }
        .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary:disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-disabled.bp3-active{
          background:rgba(19, 124, 189, 0.3); }
  .bp3-html-select.bp3-minimal select.bp3-intent-success,
  .bp3-select.bp3-minimal select.bp3-intent-success{
    color:#0d8050; }
    .bp3-html-select.bp3-minimal select.bp3-intent-success:hover,
    .bp3-select.bp3-minimal select.bp3-intent-success:hover, .bp3-html-select.bp3-minimal select.bp3-intent-success:active,
    .bp3-select.bp3-minimal select.bp3-intent-success:active, .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-success.bp3-active{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:none;
      color:#0d8050; }
    .bp3-html-select.bp3-minimal select.bp3-intent-success:hover,
    .bp3-select.bp3-minimal select.bp3-intent-success:hover{
      background:rgba(15, 153, 96, 0.15);
      color:#0d8050; }
    .bp3-html-select.bp3-minimal select.bp3-intent-success:active,
    .bp3-select.bp3-minimal select.bp3-intent-success:active, .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-success.bp3-active{
      background:rgba(15, 153, 96, 0.3);
      color:#0d8050; }
    .bp3-html-select.bp3-minimal select.bp3-intent-success:disabled,
    .bp3-select.bp3-minimal select.bp3-intent-success:disabled, .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-disabled,
    .bp3-select.bp3-minimal select.bp3-intent-success.bp3-disabled{
      background:none;
      color:rgba(13, 128, 80, 0.5); }
      .bp3-html-select.bp3-minimal select.bp3-intent-success:disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-success:disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-success.bp3-disabled.bp3-active{
        background:rgba(15, 153, 96, 0.3); }
    .bp3-html-select.bp3-minimal select.bp3-intent-success .bp3-button-spinner .bp3-spinner-head, .bp3-select.bp3-minimal select.bp3-intent-success .bp3-button-spinner .bp3-spinner-head{
      stroke:#0d8050; }
    .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success{
      color:#3dcc91; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success:hover,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success:hover{
        background:rgba(15, 153, 96, 0.2);
        color:#3dcc91; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success:active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success:active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success:active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-active{
        background:rgba(15, 153, 96, 0.3);
        color:#3dcc91; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success:disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success:disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success:disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success:disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-disabled{
        background:none;
        color:rgba(61, 204, 145, 0.5); }
        .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success:disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-disabled.bp3-active{
          background:rgba(15, 153, 96, 0.3); }
  .bp3-html-select.bp3-minimal select.bp3-intent-warning,
  .bp3-select.bp3-minimal select.bp3-intent-warning{
    color:#bf7326; }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning:hover,
    .bp3-select.bp3-minimal select.bp3-intent-warning:hover, .bp3-html-select.bp3-minimal select.bp3-intent-warning:active,
    .bp3-select.bp3-minimal select.bp3-intent-warning:active, .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-active{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:none;
      color:#bf7326; }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning:hover,
    .bp3-select.bp3-minimal select.bp3-intent-warning:hover{
      background:rgba(217, 130, 43, 0.15);
      color:#bf7326; }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning:active,
    .bp3-select.bp3-minimal select.bp3-intent-warning:active, .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-active{
      background:rgba(217, 130, 43, 0.3);
      color:#bf7326; }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning:disabled,
    .bp3-select.bp3-minimal select.bp3-intent-warning:disabled, .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-disabled,
    .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-disabled{
      background:none;
      color:rgba(191, 115, 38, 0.5); }
      .bp3-html-select.bp3-minimal select.bp3-intent-warning:disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-warning:disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-disabled.bp3-active{
        background:rgba(217, 130, 43, 0.3); }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head, .bp3-select.bp3-minimal select.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head{
      stroke:#bf7326; }
    .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning{
      color:#ffb366; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning:hover,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning:hover{
        background:rgba(217, 130, 43, 0.2);
        color:#ffb366; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning:active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning:active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning:active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-active{
        background:rgba(217, 130, 43, 0.3);
        color:#ffb366; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning:disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning:disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning:disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning:disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-disabled{
        background:none;
        color:rgba(255, 179, 102, 0.5); }
        .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning:disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-disabled.bp3-active{
          background:rgba(217, 130, 43, 0.3); }
  .bp3-html-select.bp3-minimal select.bp3-intent-danger,
  .bp3-select.bp3-minimal select.bp3-intent-danger{
    color:#c23030; }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger:hover,
    .bp3-select.bp3-minimal select.bp3-intent-danger:hover, .bp3-html-select.bp3-minimal select.bp3-intent-danger:active,
    .bp3-select.bp3-minimal select.bp3-intent-danger:active, .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-active{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:none;
      color:#c23030; }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger:hover,
    .bp3-select.bp3-minimal select.bp3-intent-danger:hover{
      background:rgba(219, 55, 55, 0.15);
      color:#c23030; }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger:active,
    .bp3-select.bp3-minimal select.bp3-intent-danger:active, .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-active{
      background:rgba(219, 55, 55, 0.3);
      color:#c23030; }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger:disabled,
    .bp3-select.bp3-minimal select.bp3-intent-danger:disabled, .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-disabled,
    .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-disabled{
      background:none;
      color:rgba(194, 48, 48, 0.5); }
      .bp3-html-select.bp3-minimal select.bp3-intent-danger:disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-danger:disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-disabled.bp3-active{
        background:rgba(219, 55, 55, 0.3); }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head, .bp3-select.bp3-minimal select.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head{
      stroke:#c23030; }
    .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger{
      color:#ff7373; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger:hover,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger:hover{
        background:rgba(219, 55, 55, 0.2);
        color:#ff7373; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger:active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger:active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger:active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-active{
        background:rgba(219, 55, 55, 0.3);
        color:#ff7373; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger:disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger:disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger:disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger:disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-disabled{
        background:none;
        color:rgba(255, 115, 115, 0.5); }
        .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger:disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-disabled.bp3-active{
          background:rgba(219, 55, 55, 0.3); }

.bp3-html-select.bp3-large select,
.bp3-select.bp3-large select{
  height:40px;
  padding-right:35px;
  font-size:16px; }

.bp3-dark .bp3-html-select select, .bp3-dark .bp3-select select{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
  background-color:#394b59;
  background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
  background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
  color:#f5f8fa; }
  .bp3-dark .bp3-html-select select:hover, .bp3-dark .bp3-select select:hover, .bp3-dark .bp3-html-select select:active, .bp3-dark .bp3-select select:active, .bp3-dark .bp3-html-select select.bp3-active, .bp3-dark .bp3-select select.bp3-active{
    color:#f5f8fa; }
  .bp3-dark .bp3-html-select select:hover, .bp3-dark .bp3-select select:hover{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    background-color:#30404d; }
  .bp3-dark .bp3-html-select select:active, .bp3-dark .bp3-select select:active, .bp3-dark .bp3-html-select select.bp3-active, .bp3-dark .bp3-select select.bp3-active{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background-color:#202b33;
    background-image:none; }
  .bp3-dark .bp3-html-select select:disabled, .bp3-dark .bp3-select select:disabled, .bp3-dark .bp3-html-select select.bp3-disabled, .bp3-dark .bp3-select select.bp3-disabled{
    -webkit-box-shadow:none;
            box-shadow:none;
    background-color:rgba(57, 75, 89, 0.5);
    background-image:none;
    color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-html-select select:disabled.bp3-active, .bp3-dark .bp3-select select:disabled.bp3-active, .bp3-dark .bp3-html-select select.bp3-disabled.bp3-active, .bp3-dark .bp3-select select.bp3-disabled.bp3-active{
      background:rgba(57, 75, 89, 0.7); }
  .bp3-dark .bp3-html-select select .bp3-button-spinner .bp3-spinner-head, .bp3-dark .bp3-select select .bp3-button-spinner .bp3-spinner-head{
    background:rgba(16, 22, 26, 0.5);
    stroke:#8a9ba8; }

.bp3-html-select select:disabled,
.bp3-select select:disabled{
  -webkit-box-shadow:none;
          box-shadow:none;
  background-color:rgba(206, 217, 224, 0.5);
  cursor:not-allowed;
  color:rgba(92, 112, 128, 0.6); }

.bp3-html-select .bp3-icon,
.bp3-select .bp3-icon, .bp3-select::after{
  position:absolute;
  top:7px;
  right:7px;
  color:#5c7080;
  pointer-events:none; }
  .bp3-html-select .bp3-disabled.bp3-icon,
  .bp3-select .bp3-disabled.bp3-icon, .bp3-disabled.bp3-select::after{
    color:rgba(92, 112, 128, 0.6); }
.bp3-html-select,
.bp3-select{
  display:inline-block;
  position:relative;
  vertical-align:middle;
  letter-spacing:normal; }
  .bp3-html-select select::-ms-expand,
  .bp3-select select::-ms-expand{
    display:none; }
  .bp3-html-select .bp3-icon,
  .bp3-select .bp3-icon{
    color:#5c7080; }
    .bp3-html-select .bp3-icon:hover,
    .bp3-select .bp3-icon:hover{
      color:#182026; }
    .bp3-dark .bp3-html-select .bp3-icon, .bp3-dark
    .bp3-select .bp3-icon{
      color:#a7b6c2; }
      .bp3-dark .bp3-html-select .bp3-icon:hover, .bp3-dark
      .bp3-select .bp3-icon:hover{
        color:#f5f8fa; }
  .bp3-html-select.bp3-large::after,
  .bp3-html-select.bp3-large .bp3-icon,
  .bp3-select.bp3-large::after,
  .bp3-select.bp3-large .bp3-icon{
    top:12px;
    right:12px; }
  .bp3-html-select.bp3-fill,
  .bp3-html-select.bp3-fill select,
  .bp3-select.bp3-fill,
  .bp3-select.bp3-fill select{
    width:100%; }
  .bp3-dark .bp3-html-select option, .bp3-dark
  .bp3-select option{
    background-color:#30404d;
    color:#f5f8fa; }
  .bp3-dark .bp3-html-select::after, .bp3-dark
  .bp3-select::after{
    color:#a7b6c2; }

.bp3-select::after{
  line-height:1;
  font-family:"Icons16", sans-serif;
  font-size:16px;
  font-weight:400;
  font-style:normal;
  -moz-osx-font-smoothing:grayscale;
  -webkit-font-smoothing:antialiased;
  content:""; }
.bp3-running-text table, table.bp3-html-table{
  border-spacing:0;
  font-size:14px; }
  .bp3-running-text table th, table.bp3-html-table th,
  .bp3-running-text table td,
  table.bp3-html-table td{
    padding:11px;
    vertical-align:top;
    text-align:left; }
  .bp3-running-text table th, table.bp3-html-table th{
    color:#182026;
    font-weight:600; }
  
  .bp3-running-text table td,
  table.bp3-html-table td{
    color:#182026; }
  .bp3-running-text table tbody tr:first-child th, table.bp3-html-table tbody tr:first-child th,
  .bp3-running-text table tbody tr:first-child td,
  table.bp3-html-table tbody tr:first-child td{
    -webkit-box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15); }
  .bp3-dark .bp3-running-text table th, .bp3-running-text .bp3-dark table th, .bp3-dark table.bp3-html-table th{
    color:#f5f8fa; }
  .bp3-dark .bp3-running-text table td, .bp3-running-text .bp3-dark table td, .bp3-dark table.bp3-html-table td{
    color:#f5f8fa; }
  .bp3-dark .bp3-running-text table tbody tr:first-child th, .bp3-running-text .bp3-dark table tbody tr:first-child th, .bp3-dark table.bp3-html-table tbody tr:first-child th,
  .bp3-dark .bp3-running-text table tbody tr:first-child td,
  .bp3-running-text .bp3-dark table tbody tr:first-child td,
  .bp3-dark table.bp3-html-table tbody tr:first-child td{
    -webkit-box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15);
            box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15); }

table.bp3-html-table.bp3-html-table-condensed th,
table.bp3-html-table.bp3-html-table-condensed td, table.bp3-html-table.bp3-small th,
table.bp3-html-table.bp3-small td{
  padding-top:6px;
  padding-bottom:6px; }

table.bp3-html-table.bp3-html-table-striped tbody tr:nth-child(odd) td{
  background:rgba(191, 204, 214, 0.15); }

table.bp3-html-table.bp3-html-table-bordered th:not(:first-child){
  -webkit-box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15);
          box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15); }

table.bp3-html-table.bp3-html-table-bordered tbody tr td{
  -webkit-box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15);
          box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15); }
  table.bp3-html-table.bp3-html-table-bordered tbody tr td:not(:first-child){
    -webkit-box-shadow:inset 1px 1px 0 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 1px 1px 0 0 rgba(16, 22, 26, 0.15); }

table.bp3-html-table.bp3-html-table-bordered.bp3-html-table-striped tbody tr:not(:first-child) td{
  -webkit-box-shadow:none;
          box-shadow:none; }
  table.bp3-html-table.bp3-html-table-bordered.bp3-html-table-striped tbody tr:not(:first-child) td:not(:first-child){
    -webkit-box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15); }

table.bp3-html-table.bp3-interactive tbody tr:hover td{
  background-color:rgba(191, 204, 214, 0.3);
  cursor:pointer; }

table.bp3-html-table.bp3-interactive tbody tr:active td{
  background-color:rgba(191, 204, 214, 0.4); }

.bp3-dark table.bp3-html-table.bp3-html-table-striped tbody tr:nth-child(odd) td{
  background:rgba(92, 112, 128, 0.15); }

.bp3-dark table.bp3-html-table.bp3-html-table-bordered th:not(:first-child){
  -webkit-box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15);
          box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15); }

.bp3-dark table.bp3-html-table.bp3-html-table-bordered tbody tr td{
  -webkit-box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15);
          box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15); }
  .bp3-dark table.bp3-html-table.bp3-html-table-bordered tbody tr td:not(:first-child){
    -webkit-box-shadow:inset 1px 1px 0 0 rgba(255, 255, 255, 0.15);
            box-shadow:inset 1px 1px 0 0 rgba(255, 255, 255, 0.15); }

.bp3-dark table.bp3-html-table.bp3-html-table-bordered.bp3-html-table-striped tbody tr:not(:first-child) td{
  -webkit-box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15);
          box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15); }
  .bp3-dark table.bp3-html-table.bp3-html-table-bordered.bp3-html-table-striped tbody tr:not(:first-child) td:first-child{
    -webkit-box-shadow:none;
            box-shadow:none; }

.bp3-dark table.bp3-html-table.bp3-interactive tbody tr:hover td{
  background-color:rgba(92, 112, 128, 0.3);
  cursor:pointer; }

.bp3-dark table.bp3-html-table.bp3-interactive tbody tr:active td{
  background-color:rgba(92, 112, 128, 0.4); }

.bp3-key-combo{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center; }
  .bp3-key-combo > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-key-combo > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-key-combo::before,
  .bp3-key-combo > *{
    margin-right:5px; }
  .bp3-key-combo:empty::before,
  .bp3-key-combo > :last-child{
    margin-right:0; }

.bp3-hotkey-dialog{
  top:40px;
  padding-bottom:0; }
  .bp3-hotkey-dialog .bp3-dialog-body{
    margin:0;
    padding:0; }
  .bp3-hotkey-dialog .bp3-hotkey-label{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1; }

.bp3-hotkey-column{
  margin:auto;
  max-height:80vh;
  overflow-y:auto;
  padding:30px; }
  .bp3-hotkey-column .bp3-heading{
    margin-bottom:20px; }
    .bp3-hotkey-column .bp3-heading:not(:first-child){
      margin-top:40px; }

.bp3-hotkey{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  -webkit-box-pack:justify;
      -ms-flex-pack:justify;
          justify-content:space-between;
  margin-right:0;
  margin-left:0; }
  .bp3-hotkey:not(:last-child){
    margin-bottom:10px; }
.bp3-icon{
  display:inline-block;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  vertical-align:text-bottom; }
  .bp3-icon:not(:empty)::before{
    content:"" !important;
    content:unset !important; }
  .bp3-icon > svg{
    display:block; }
    .bp3-icon > svg:not([fill]){
      fill:currentColor; }

.bp3-icon.bp3-intent-primary, .bp3-icon-standard.bp3-intent-primary, .bp3-icon-large.bp3-intent-primary{
  color:#106ba3; }
  .bp3-dark .bp3-icon.bp3-intent-primary, .bp3-dark .bp3-icon-standard.bp3-intent-primary, .bp3-dark .bp3-icon-large.bp3-intent-primary{
    color:#48aff0; }

.bp3-icon.bp3-intent-success, .bp3-icon-standard.bp3-intent-success, .bp3-icon-large.bp3-intent-success{
  color:#0d8050; }
  .bp3-dark .bp3-icon.bp3-intent-success, .bp3-dark .bp3-icon-standard.bp3-intent-success, .bp3-dark .bp3-icon-large.bp3-intent-success{
    color:#3dcc91; }

.bp3-icon.bp3-intent-warning, .bp3-icon-standard.bp3-intent-warning, .bp3-icon-large.bp3-intent-warning{
  color:#bf7326; }
  .bp3-dark .bp3-icon.bp3-intent-warning, .bp3-dark .bp3-icon-standard.bp3-intent-warning, .bp3-dark .bp3-icon-large.bp3-intent-warning{
    color:#ffb366; }

.bp3-icon.bp3-intent-danger, .bp3-icon-standard.bp3-intent-danger, .bp3-icon-large.bp3-intent-danger{
  color:#c23030; }
  .bp3-dark .bp3-icon.bp3-intent-danger, .bp3-dark .bp3-icon-standard.bp3-intent-danger, .bp3-dark .bp3-icon-large.bp3-intent-danger{
    color:#ff7373; }

span.bp3-icon-standard{
  line-height:1;
  font-family:"Icons16", sans-serif;
  font-size:16px;
  font-weight:400;
  font-style:normal;
  -moz-osx-font-smoothing:grayscale;
  -webkit-font-smoothing:antialiased;
  display:inline-block; }

span.bp3-icon-large{
  line-height:1;
  font-family:"Icons20", sans-serif;
  font-size:20px;
  font-weight:400;
  font-style:normal;
  -moz-osx-font-smoothing:grayscale;
  -webkit-font-smoothing:antialiased;
  display:inline-block; }

span.bp3-icon:empty{
  line-height:1;
  font-family:"Icons20";
  font-size:inherit;
  font-weight:400;
  font-style:normal; }
  span.bp3-icon:empty::before{
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased; }

.bp3-icon-add::before{
  content:""; }

.bp3-icon-add-column-left::before{
  content:""; }

.bp3-icon-add-column-right::before{
  content:""; }

.bp3-icon-add-row-bottom::before{
  content:""; }

.bp3-icon-add-row-top::before{
  content:""; }

.bp3-icon-add-to-artifact::before{
  content:""; }

.bp3-icon-add-to-folder::before{
  content:""; }

.bp3-icon-airplane::before{
  content:""; }

.bp3-icon-align-center::before{
  content:""; }

.bp3-icon-align-justify::before{
  content:""; }

.bp3-icon-align-left::before{
  content:""; }

.bp3-icon-align-right::before{
  content:""; }

.bp3-icon-alignment-bottom::before{
  content:""; }

.bp3-icon-alignment-horizontal-center::before{
  content:""; }

.bp3-icon-alignment-left::before{
  content:""; }

.bp3-icon-alignment-right::before{
  content:""; }

.bp3-icon-alignment-top::before{
  content:""; }

.bp3-icon-alignment-vertical-center::before{
  content:""; }

.bp3-icon-annotation::before{
  content:""; }

.bp3-icon-application::before{
  content:""; }

.bp3-icon-applications::before{
  content:""; }

.bp3-icon-archive::before{
  content:""; }

.bp3-icon-arrow-bottom-left::before{
  content:"↙"; }

.bp3-icon-arrow-bottom-right::before{
  content:"↘"; }

.bp3-icon-arrow-down::before{
  content:"↓"; }

.bp3-icon-arrow-left::before{
  content:"←"; }

.bp3-icon-arrow-right::before{
  content:"→"; }

.bp3-icon-arrow-top-left::before{
  content:"↖"; }

.bp3-icon-arrow-top-right::before{
  content:"↗"; }

.bp3-icon-arrow-up::before{
  content:"↑"; }

.bp3-icon-arrows-horizontal::before{
  content:"↔"; }

.bp3-icon-arrows-vertical::before{
  content:"↕"; }

.bp3-icon-asterisk::before{
  content:"*"; }

.bp3-icon-automatic-updates::before{
  content:""; }

.bp3-icon-badge::before{
  content:""; }

.bp3-icon-ban-circle::before{
  content:""; }

.bp3-icon-bank-account::before{
  content:""; }

.bp3-icon-barcode::before{
  content:""; }

.bp3-icon-blank::before{
  content:""; }

.bp3-icon-blocked-person::before{
  content:""; }

.bp3-icon-bold::before{
  content:""; }

.bp3-icon-book::before{
  content:""; }

.bp3-icon-bookmark::before{
  content:""; }

.bp3-icon-box::before{
  content:""; }

.bp3-icon-briefcase::before{
  content:""; }

.bp3-icon-bring-data::before{
  content:""; }

.bp3-icon-build::before{
  content:""; }

.bp3-icon-calculator::before{
  content:""; }

.bp3-icon-calendar::before{
  content:""; }

.bp3-icon-camera::before{
  content:""; }

.bp3-icon-caret-down::before{
  content:"⌄"; }

.bp3-icon-caret-left::before{
  content:"〈"; }

.bp3-icon-caret-right::before{
  content:"〉"; }

.bp3-icon-caret-up::before{
  content:"⌃"; }

.bp3-icon-cell-tower::before{
  content:""; }

.bp3-icon-changes::before{
  content:""; }

.bp3-icon-chart::before{
  content:""; }

.bp3-icon-chat::before{
  content:""; }

.bp3-icon-chevron-backward::before{
  content:""; }

.bp3-icon-chevron-down::before{
  content:""; }

.bp3-icon-chevron-forward::before{
  content:""; }

.bp3-icon-chevron-left::before{
  content:""; }

.bp3-icon-chevron-right::before{
  content:""; }

.bp3-icon-chevron-up::before{
  content:""; }

.bp3-icon-circle::before{
  content:""; }

.bp3-icon-circle-arrow-down::before{
  content:""; }

.bp3-icon-circle-arrow-left::before{
  content:""; }

.bp3-icon-circle-arrow-right::before{
  content:""; }

.bp3-icon-circle-arrow-up::before{
  content:""; }

.bp3-icon-citation::before{
  content:""; }

.bp3-icon-clean::before{
  content:""; }

.bp3-icon-clipboard::before{
  content:""; }

.bp3-icon-cloud::before{
  content:"☁"; }

.bp3-icon-cloud-download::before{
  content:""; }

.bp3-icon-cloud-upload::before{
  content:""; }

.bp3-icon-code::before{
  content:""; }

.bp3-icon-code-block::before{
  content:""; }

.bp3-icon-cog::before{
  content:""; }

.bp3-icon-collapse-all::before{
  content:""; }

.bp3-icon-column-layout::before{
  content:""; }

.bp3-icon-comment::before{
  content:""; }

.bp3-icon-comparison::before{
  content:""; }

.bp3-icon-compass::before{
  content:""; }

.bp3-icon-compressed::before{
  content:""; }

.bp3-icon-confirm::before{
  content:""; }

.bp3-icon-console::before{
  content:""; }

.bp3-icon-contrast::before{
  content:""; }

.bp3-icon-control::before{
  content:""; }

.bp3-icon-credit-card::before{
  content:""; }

.bp3-icon-cross::before{
  content:"✗"; }

.bp3-icon-crown::before{
  content:""; }

.bp3-icon-cube::before{
  content:""; }

.bp3-icon-cube-add::before{
  content:""; }

.bp3-icon-cube-remove::before{
  content:""; }

.bp3-icon-curved-range-chart::before{
  content:""; }

.bp3-icon-cut::before{
  content:""; }

.bp3-icon-dashboard::before{
  content:""; }

.bp3-icon-data-lineage::before{
  content:""; }

.bp3-icon-database::before{
  content:""; }

.bp3-icon-delete::before{
  content:""; }

.bp3-icon-delta::before{
  content:"Δ"; }

.bp3-icon-derive-column::before{
  content:""; }

.bp3-icon-desktop::before{
  content:""; }

.bp3-icon-diagram-tree::before{
  content:""; }

.bp3-icon-direction-left::before{
  content:""; }

.bp3-icon-direction-right::before{
  content:""; }

.bp3-icon-disable::before{
  content:""; }

.bp3-icon-document::before{
  content:""; }

.bp3-icon-document-open::before{
  content:""; }

.bp3-icon-document-share::before{
  content:""; }

.bp3-icon-dollar::before{
  content:"$"; }

.bp3-icon-dot::before{
  content:"•"; }

.bp3-icon-double-caret-horizontal::before{
  content:""; }

.bp3-icon-double-caret-vertical::before{
  content:""; }

.bp3-icon-double-chevron-down::before{
  content:""; }

.bp3-icon-double-chevron-left::before{
  content:""; }

.bp3-icon-double-chevron-right::before{
  content:""; }

.bp3-icon-double-chevron-up::before{
  content:""; }

.bp3-icon-doughnut-chart::before{
  content:""; }

.bp3-icon-download::before{
  content:""; }

.bp3-icon-drag-handle-horizontal::before{
  content:""; }

.bp3-icon-drag-handle-vertical::before{
  content:""; }

.bp3-icon-draw::before{
  content:""; }

.bp3-icon-drive-time::before{
  content:""; }

.bp3-icon-duplicate::before{
  content:""; }

.bp3-icon-edit::before{
  content:"✎"; }

.bp3-icon-eject::before{
  content:"⏏"; }

.bp3-icon-endorsed::before{
  content:""; }

.bp3-icon-envelope::before{
  content:"✉"; }

.bp3-icon-equals::before{
  content:""; }

.bp3-icon-eraser::before{
  content:""; }

.bp3-icon-error::before{
  content:""; }

.bp3-icon-euro::before{
  content:"€"; }

.bp3-icon-exchange::before{
  content:""; }

.bp3-icon-exclude-row::before{
  content:""; }

.bp3-icon-expand-all::before{
  content:""; }

.bp3-icon-export::before{
  content:""; }

.bp3-icon-eye-off::before{
  content:""; }

.bp3-icon-eye-on::before{
  content:""; }

.bp3-icon-eye-open::before{
  content:""; }

.bp3-icon-fast-backward::before{
  content:""; }

.bp3-icon-fast-forward::before{
  content:""; }

.bp3-icon-feed::before{
  content:""; }

.bp3-icon-feed-subscribed::before{
  content:""; }

.bp3-icon-film::before{
  content:""; }

.bp3-icon-filter::before{
  content:""; }

.bp3-icon-filter-keep::before{
  content:""; }

.bp3-icon-filter-list::before{
  content:""; }

.bp3-icon-filter-open::before{
  content:""; }

.bp3-icon-filter-remove::before{
  content:""; }

.bp3-icon-flag::before{
  content:"⚑"; }

.bp3-icon-flame::before{
  content:""; }

.bp3-icon-flash::before{
  content:""; }

.bp3-icon-floppy-disk::before{
  content:""; }

.bp3-icon-flow-branch::before{
  content:""; }

.bp3-icon-flow-end::before{
  content:""; }

.bp3-icon-flow-linear::before{
  content:""; }

.bp3-icon-flow-review::before{
  content:""; }

.bp3-icon-flow-review-branch::before{
  content:""; }

.bp3-icon-flows::before{
  content:""; }

.bp3-icon-folder-close::before{
  content:""; }

.bp3-icon-folder-new::before{
  content:""; }

.bp3-icon-folder-open::before{
  content:""; }

.bp3-icon-folder-shared::before{
  content:""; }

.bp3-icon-folder-shared-open::before{
  content:""; }

.bp3-icon-follower::before{
  content:""; }

.bp3-icon-following::before{
  content:""; }

.bp3-icon-font::before{
  content:""; }

.bp3-icon-fork::before{
  content:""; }

.bp3-icon-form::before{
  content:""; }

.bp3-icon-full-circle::before{
  content:""; }

.bp3-icon-full-stacked-chart::before{
  content:""; }

.bp3-icon-fullscreen::before{
  content:""; }

.bp3-icon-function::before{
  content:""; }

.bp3-icon-gantt-chart::before{
  content:""; }

.bp3-icon-geolocation::before{
  content:""; }

.bp3-icon-geosearch::before{
  content:""; }

.bp3-icon-git-branch::before{
  content:""; }

.bp3-icon-git-commit::before{
  content:""; }

.bp3-icon-git-merge::before{
  content:""; }

.bp3-icon-git-new-branch::before{
  content:""; }

.bp3-icon-git-pull::before{
  content:""; }

.bp3-icon-git-push::before{
  content:""; }

.bp3-icon-git-repo::before{
  content:""; }

.bp3-icon-glass::before{
  content:""; }

.bp3-icon-globe::before{
  content:""; }

.bp3-icon-globe-network::before{
  content:""; }

.bp3-icon-graph::before{
  content:""; }

.bp3-icon-graph-remove::before{
  content:""; }

.bp3-icon-greater-than::before{
  content:""; }

.bp3-icon-greater-than-or-equal-to::before{
  content:""; }

.bp3-icon-grid::before{
  content:""; }

.bp3-icon-grid-view::before{
  content:""; }

.bp3-icon-group-objects::before{
  content:""; }

.bp3-icon-grouped-bar-chart::before{
  content:""; }

.bp3-icon-hand::before{
  content:""; }

.bp3-icon-hand-down::before{
  content:""; }

.bp3-icon-hand-left::before{
  content:""; }

.bp3-icon-hand-right::before{
  content:""; }

.bp3-icon-hand-up::before{
  content:""; }

.bp3-icon-header::before{
  content:""; }

.bp3-icon-header-one::before{
  content:""; }

.bp3-icon-header-two::before{
  content:""; }

.bp3-icon-headset::before{
  content:""; }

.bp3-icon-heart::before{
  content:"♥"; }

.bp3-icon-heart-broken::before{
  content:""; }

.bp3-icon-heat-grid::before{
  content:""; }

.bp3-icon-heatmap::before{
  content:""; }

.bp3-icon-help::before{
  content:"?"; }

.bp3-icon-helper-management::before{
  content:""; }

.bp3-icon-highlight::before{
  content:""; }

.bp3-icon-history::before{
  content:""; }

.bp3-icon-home::before{
  content:"⌂"; }

.bp3-icon-horizontal-bar-chart::before{
  content:""; }

.bp3-icon-horizontal-bar-chart-asc::before{
  content:""; }

.bp3-icon-horizontal-bar-chart-desc::before{
  content:""; }

.bp3-icon-horizontal-distribution::before{
  content:""; }

.bp3-icon-id-number::before{
  content:""; }

.bp3-icon-image-rotate-left::before{
  content:""; }

.bp3-icon-image-rotate-right::before{
  content:""; }

.bp3-icon-import::before{
  content:""; }

.bp3-icon-inbox::before{
  content:""; }

.bp3-icon-inbox-filtered::before{
  content:""; }

.bp3-icon-inbox-geo::before{
  content:""; }

.bp3-icon-inbox-search::before{
  content:""; }

.bp3-icon-inbox-update::before{
  content:""; }

.bp3-icon-info-sign::before{
  content:"ℹ"; }

.bp3-icon-inheritance::before{
  content:""; }

.bp3-icon-inner-join::before{
  content:""; }

.bp3-icon-insert::before{
  content:""; }

.bp3-icon-intersection::before{
  content:""; }

.bp3-icon-ip-address::before{
  content:""; }

.bp3-icon-issue::before{
  content:""; }

.bp3-icon-issue-closed::before{
  content:""; }

.bp3-icon-issue-new::before{
  content:""; }

.bp3-icon-italic::before{
  content:""; }

.bp3-icon-join-table::before{
  content:""; }

.bp3-icon-key::before{
  content:""; }

.bp3-icon-key-backspace::before{
  content:""; }

.bp3-icon-key-command::before{
  content:""; }

.bp3-icon-key-control::before{
  content:""; }

.bp3-icon-key-delete::before{
  content:""; }

.bp3-icon-key-enter::before{
  content:""; }

.bp3-icon-key-escape::before{
  content:""; }

.bp3-icon-key-option::before{
  content:""; }

.bp3-icon-key-shift::before{
  content:""; }

.bp3-icon-key-tab::before{
  content:""; }

.bp3-icon-known-vehicle::before{
  content:""; }

.bp3-icon-label::before{
  content:""; }

.bp3-icon-layer::before{
  content:""; }

.bp3-icon-layers::before{
  content:""; }

.bp3-icon-layout::before{
  content:""; }

.bp3-icon-layout-auto::before{
  content:""; }

.bp3-icon-layout-balloon::before{
  content:""; }

.bp3-icon-layout-circle::before{
  content:""; }

.bp3-icon-layout-grid::before{
  content:""; }

.bp3-icon-layout-group-by::before{
  content:""; }

.bp3-icon-layout-hierarchy::before{
  content:""; }

.bp3-icon-layout-linear::before{
  content:""; }

.bp3-icon-layout-skew-grid::before{
  content:""; }

.bp3-icon-layout-sorted-clusters::before{
  content:""; }

.bp3-icon-learning::before{
  content:""; }

.bp3-icon-left-join::before{
  content:""; }

.bp3-icon-less-than::before{
  content:""; }

.bp3-icon-less-than-or-equal-to::before{
  content:""; }

.bp3-icon-lifesaver::before{
  content:""; }

.bp3-icon-lightbulb::before{
  content:""; }

.bp3-icon-link::before{
  content:""; }

.bp3-icon-list::before{
  content:"☰"; }

.bp3-icon-list-columns::before{
  content:""; }

.bp3-icon-list-detail-view::before{
  content:""; }

.bp3-icon-locate::before{
  content:""; }

.bp3-icon-lock::before{
  content:""; }

.bp3-icon-log-in::before{
  content:""; }

.bp3-icon-log-out::before{
  content:""; }

.bp3-icon-manual::before{
  content:""; }

.bp3-icon-manually-entered-data::before{
  content:""; }

.bp3-icon-map::before{
  content:""; }

.bp3-icon-map-create::before{
  content:""; }

.bp3-icon-map-marker::before{
  content:""; }

.bp3-icon-maximize::before{
  content:""; }

.bp3-icon-media::before{
  content:""; }

.bp3-icon-menu::before{
  content:""; }

.bp3-icon-menu-closed::before{
  content:""; }

.bp3-icon-menu-open::before{
  content:""; }

.bp3-icon-merge-columns::before{
  content:""; }

.bp3-icon-merge-links::before{
  content:""; }

.bp3-icon-minimize::before{
  content:""; }

.bp3-icon-minus::before{
  content:"−"; }

.bp3-icon-mobile-phone::before{
  content:""; }

.bp3-icon-mobile-video::before{
  content:""; }

.bp3-icon-moon::before{
  content:""; }

.bp3-icon-more::before{
  content:""; }

.bp3-icon-mountain::before{
  content:""; }

.bp3-icon-move::before{
  content:""; }

.bp3-icon-mugshot::before{
  content:""; }

.bp3-icon-multi-select::before{
  content:""; }

.bp3-icon-music::before{
  content:""; }

.bp3-icon-new-drawing::before{
  content:""; }

.bp3-icon-new-grid-item::before{
  content:""; }

.bp3-icon-new-layer::before{
  content:""; }

.bp3-icon-new-layers::before{
  content:""; }

.bp3-icon-new-link::before{
  content:""; }

.bp3-icon-new-object::before{
  content:""; }

.bp3-icon-new-person::before{
  content:""; }

.bp3-icon-new-prescription::before{
  content:""; }

.bp3-icon-new-text-box::before{
  content:""; }

.bp3-icon-ninja::before{
  content:""; }

.bp3-icon-not-equal-to::before{
  content:""; }

.bp3-icon-notifications::before{
  content:""; }

.bp3-icon-notifications-updated::before{
  content:""; }

.bp3-icon-numbered-list::before{
  content:""; }

.bp3-icon-numerical::before{
  content:""; }

.bp3-icon-office::before{
  content:""; }

.bp3-icon-offline::before{
  content:""; }

.bp3-icon-oil-field::before{
  content:""; }

.bp3-icon-one-column::before{
  content:""; }

.bp3-icon-outdated::before{
  content:""; }

.bp3-icon-page-layout::before{
  content:""; }

.bp3-icon-panel-stats::before{
  content:""; }

.bp3-icon-panel-table::before{
  content:""; }

.bp3-icon-paperclip::before{
  content:""; }

.bp3-icon-paragraph::before{
  content:""; }

.bp3-icon-path::before{
  content:""; }

.bp3-icon-path-search::before{
  content:""; }

.bp3-icon-pause::before{
  content:""; }

.bp3-icon-people::before{
  content:""; }

.bp3-icon-percentage::before{
  content:""; }

.bp3-icon-person::before{
  content:""; }

.bp3-icon-phone::before{
  content:"☎"; }

.bp3-icon-pie-chart::before{
  content:""; }

.bp3-icon-pin::before{
  content:""; }

.bp3-icon-pivot::before{
  content:""; }

.bp3-icon-pivot-table::before{
  content:""; }

.bp3-icon-play::before{
  content:""; }

.bp3-icon-plus::before{
  content:"+"; }

.bp3-icon-polygon-filter::before{
  content:""; }

.bp3-icon-power::before{
  content:""; }

.bp3-icon-predictive-analysis::before{
  content:""; }

.bp3-icon-prescription::before{
  content:""; }

.bp3-icon-presentation::before{
  content:""; }

.bp3-icon-print::before{
  content:"⎙"; }

.bp3-icon-projects::before{
  content:""; }

.bp3-icon-properties::before{
  content:""; }

.bp3-icon-property::before{
  content:""; }

.bp3-icon-publish-function::before{
  content:""; }

.bp3-icon-pulse::before{
  content:""; }

.bp3-icon-random::before{
  content:""; }

.bp3-icon-record::before{
  content:""; }

.bp3-icon-redo::before{
  content:""; }

.bp3-icon-refresh::before{
  content:""; }

.bp3-icon-regression-chart::before{
  content:""; }

.bp3-icon-remove::before{
  content:""; }

.bp3-icon-remove-column::before{
  content:""; }

.bp3-icon-remove-column-left::before{
  content:""; }

.bp3-icon-remove-column-right::before{
  content:""; }

.bp3-icon-remove-row-bottom::before{
  content:""; }

.bp3-icon-remove-row-top::before{
  content:""; }

.bp3-icon-repeat::before{
  content:""; }

.bp3-icon-reset::before{
  content:""; }

.bp3-icon-resolve::before{
  content:""; }

.bp3-icon-rig::before{
  content:""; }

.bp3-icon-right-join::before{
  content:""; }

.bp3-icon-ring::before{
  content:""; }

.bp3-icon-rotate-document::before{
  content:""; }

.bp3-icon-rotate-page::before{
  content:""; }

.bp3-icon-satellite::before{
  content:""; }

.bp3-icon-saved::before{
  content:""; }

.bp3-icon-scatter-plot::before{
  content:""; }

.bp3-icon-search::before{
  content:""; }

.bp3-icon-search-around::before{
  content:""; }

.bp3-icon-search-template::before{
  content:""; }

.bp3-icon-search-text::before{
  content:""; }

.bp3-icon-segmented-control::before{
  content:""; }

.bp3-icon-select::before{
  content:""; }

.bp3-icon-selection::before{
  content:"⦿"; }

.bp3-icon-send-to::before{
  content:""; }

.bp3-icon-send-to-graph::before{
  content:""; }

.bp3-icon-send-to-map::before{
  content:""; }

.bp3-icon-series-add::before{
  content:""; }

.bp3-icon-series-configuration::before{
  content:""; }

.bp3-icon-series-derived::before{
  content:""; }

.bp3-icon-series-filtered::before{
  content:""; }

.bp3-icon-series-search::before{
  content:""; }

.bp3-icon-settings::before{
  content:""; }

.bp3-icon-share::before{
  content:""; }

.bp3-icon-shield::before{
  content:""; }

.bp3-icon-shop::before{
  content:""; }

.bp3-icon-shopping-cart::before{
  content:""; }

.bp3-icon-signal-search::before{
  content:""; }

.bp3-icon-sim-card::before{
  content:""; }

.bp3-icon-slash::before{
  content:""; }

.bp3-icon-small-cross::before{
  content:""; }

.bp3-icon-small-minus::before{
  content:""; }

.bp3-icon-small-plus::before{
  content:""; }

.bp3-icon-small-tick::before{
  content:""; }

.bp3-icon-snowflake::before{
  content:""; }

.bp3-icon-social-media::before{
  content:""; }

.bp3-icon-sort::before{
  content:""; }

.bp3-icon-sort-alphabetical::before{
  content:""; }

.bp3-icon-sort-alphabetical-desc::before{
  content:""; }

.bp3-icon-sort-asc::before{
  content:""; }

.bp3-icon-sort-desc::before{
  content:""; }

.bp3-icon-sort-numerical::before{
  content:""; }

.bp3-icon-sort-numerical-desc::before{
  content:""; }

.bp3-icon-split-columns::before{
  content:""; }

.bp3-icon-square::before{
  content:""; }

.bp3-icon-stacked-chart::before{
  content:""; }

.bp3-icon-star::before{
  content:"★"; }

.bp3-icon-star-empty::before{
  content:"☆"; }

.bp3-icon-step-backward::before{
  content:""; }

.bp3-icon-step-chart::before{
  content:""; }

.bp3-icon-step-forward::before{
  content:""; }

.bp3-icon-stop::before{
  content:""; }

.bp3-icon-stopwatch::before{
  content:""; }

.bp3-icon-strikethrough::before{
  content:""; }

.bp3-icon-style::before{
  content:""; }

.bp3-icon-swap-horizontal::before{
  content:""; }

.bp3-icon-swap-vertical::before{
  content:""; }

.bp3-icon-symbol-circle::before{
  content:""; }

.bp3-icon-symbol-cross::before{
  content:""; }

.bp3-icon-symbol-diamond::before{
  content:""; }

.bp3-icon-symbol-square::before{
  content:""; }

.bp3-icon-symbol-triangle-down::before{
  content:""; }

.bp3-icon-symbol-triangle-up::before{
  content:""; }

.bp3-icon-tag::before{
  content:""; }

.bp3-icon-take-action::before{
  content:""; }

.bp3-icon-taxi::before{
  content:""; }

.bp3-icon-text-highlight::before{
  content:""; }

.bp3-icon-th::before{
  content:""; }

.bp3-icon-th-derived::before{
  content:""; }

.bp3-icon-th-disconnect::before{
  content:""; }

.bp3-icon-th-filtered::before{
  content:""; }

.bp3-icon-th-list::before{
  content:""; }

.bp3-icon-thumbs-down::before{
  content:""; }

.bp3-icon-thumbs-up::before{
  content:""; }

.bp3-icon-tick::before{
  content:"✓"; }

.bp3-icon-tick-circle::before{
  content:""; }

.bp3-icon-time::before{
  content:"⏲"; }

.bp3-icon-timeline-area-chart::before{
  content:""; }

.bp3-icon-timeline-bar-chart::before{
  content:""; }

.bp3-icon-timeline-events::before{
  content:""; }

.bp3-icon-timeline-line-chart::before{
  content:""; }

.bp3-icon-tint::before{
  content:""; }

.bp3-icon-torch::before{
  content:""; }

.bp3-icon-tractor::before{
  content:""; }

.bp3-icon-train::before{
  content:""; }

.bp3-icon-translate::before{
  content:""; }

.bp3-icon-trash::before{
  content:""; }

.bp3-icon-tree::before{
  content:""; }

.bp3-icon-trending-down::before{
  content:""; }

.bp3-icon-trending-up::before{
  content:""; }

.bp3-icon-truck::before{
  content:""; }

.bp3-icon-two-columns::before{
  content:""; }

.bp3-icon-unarchive::before{
  content:""; }

.bp3-icon-underline::before{
  content:"⎁"; }

.bp3-icon-undo::before{
  content:"⎌"; }

.bp3-icon-ungroup-objects::before{
  content:""; }

.bp3-icon-unknown-vehicle::before{
  content:""; }

.bp3-icon-unlock::before{
  content:""; }

.bp3-icon-unpin::before{
  content:""; }

.bp3-icon-unresolve::before{
  content:""; }

.bp3-icon-updated::before{
  content:""; }

.bp3-icon-upload::before{
  content:""; }

.bp3-icon-user::before{
  content:""; }

.bp3-icon-variable::before{
  content:""; }

.bp3-icon-vertical-bar-chart-asc::before{
  content:""; }

.bp3-icon-vertical-bar-chart-desc::before{
  content:""; }

.bp3-icon-vertical-distribution::before{
  content:""; }

.bp3-icon-video::before{
  content:""; }

.bp3-icon-volume-down::before{
  content:""; }

.bp3-icon-volume-off::before{
  content:""; }

.bp3-icon-volume-up::before{
  content:""; }

.bp3-icon-walk::before{
  content:""; }

.bp3-icon-warning-sign::before{
  content:""; }

.bp3-icon-waterfall-chart::before{
  content:""; }

.bp3-icon-widget::before{
  content:""; }

.bp3-icon-widget-button::before{
  content:""; }

.bp3-icon-widget-footer::before{
  content:""; }

.bp3-icon-widget-header::before{
  content:""; }

.bp3-icon-wrench::before{
  content:""; }

.bp3-icon-zoom-in::before{
  content:""; }

.bp3-icon-zoom-out::before{
  content:""; }

.bp3-icon-zoom-to-fit::before{
  content:""; }
.bp3-submenu > .bp3-popover-wrapper{
  display:block; }

.bp3-submenu .bp3-popover-target{
  display:block; }

.bp3-submenu.bp3-popover{
  -webkit-box-shadow:none;
          box-shadow:none;
  padding:0 5px; }
  .bp3-submenu.bp3-popover > .bp3-popover-content{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-submenu.bp3-popover, .bp3-submenu.bp3-popover.bp3-dark{
    -webkit-box-shadow:none;
            box-shadow:none; }
    .bp3-dark .bp3-submenu.bp3-popover > .bp3-popover-content, .bp3-submenu.bp3-popover.bp3-dark > .bp3-popover-content{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }
.bp3-menu{
  margin:0;
  border-radius:3px;
  background:#ffffff;
  min-width:180px;
  padding:5px;
  list-style:none;
  text-align:left;
  color:#182026; }

.bp3-menu-divider{
  display:block;
  margin:5px;
  border-top:1px solid rgba(16, 22, 26, 0.15); }
  .bp3-dark .bp3-menu-divider{
    border-top-color:rgba(255, 255, 255, 0.15); }

.bp3-menu-item{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:start;
      -ms-flex-align:start;
          align-items:flex-start;
  border-radius:2px;
  padding:5px 7px;
  text-decoration:none;
  line-height:20px;
  color:inherit;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-menu-item > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-menu-item > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-menu-item::before,
  .bp3-menu-item > *{
    margin-right:7px; }
  .bp3-menu-item:empty::before,
  .bp3-menu-item > :last-child{
    margin-right:0; }
  .bp3-menu-item > .bp3-fill{
    word-break:break-word; }
  .bp3-menu-item:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-menu-item{
    background-color:rgba(167, 182, 194, 0.3);
    cursor:pointer;
    text-decoration:none; }
  .bp3-menu-item.bp3-disabled{
    background-color:inherit;
    cursor:not-allowed;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-dark .bp3-menu-item{
    color:inherit; }
    .bp3-dark .bp3-menu-item:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-menu-item{
      background-color:rgba(138, 155, 168, 0.15);
      color:inherit; }
    .bp3-dark .bp3-menu-item.bp3-disabled{
      background-color:inherit;
      color:rgba(167, 182, 194, 0.6); }
  .bp3-menu-item.bp3-intent-primary{
    color:#106ba3; }
    .bp3-menu-item.bp3-intent-primary .bp3-icon{
      color:inherit; }
    .bp3-menu-item.bp3-intent-primary::before, .bp3-menu-item.bp3-intent-primary::after,
    .bp3-menu-item.bp3-intent-primary .bp3-menu-item-label{
      color:#106ba3; }
    .bp3-menu-item.bp3-intent-primary:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-menu-item.bp3-intent-primary.bp3-active{
      background-color:#137cbd; }
    .bp3-menu-item.bp3-intent-primary:active{
      background-color:#106ba3; }
    .bp3-menu-item.bp3-intent-primary:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-menu-item.bp3-intent-primary:hover::before, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::before, .bp3-menu-item.bp3-intent-primary:hover::after, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::after,
    .bp3-menu-item.bp3-intent-primary:hover .bp3-menu-item-label,
    .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item .bp3-menu-item-label, .bp3-menu-item.bp3-intent-primary:active, .bp3-menu-item.bp3-intent-primary:active::before, .bp3-menu-item.bp3-intent-primary:active::after,
    .bp3-menu-item.bp3-intent-primary:active .bp3-menu-item-label, .bp3-menu-item.bp3-intent-primary.bp3-active, .bp3-menu-item.bp3-intent-primary.bp3-active::before, .bp3-menu-item.bp3-intent-primary.bp3-active::after,
    .bp3-menu-item.bp3-intent-primary.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-menu-item.bp3-intent-success{
    color:#0d8050; }
    .bp3-menu-item.bp3-intent-success .bp3-icon{
      color:inherit; }
    .bp3-menu-item.bp3-intent-success::before, .bp3-menu-item.bp3-intent-success::after,
    .bp3-menu-item.bp3-intent-success .bp3-menu-item-label{
      color:#0d8050; }
    .bp3-menu-item.bp3-intent-success:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-menu-item.bp3-intent-success.bp3-active{
      background-color:#0f9960; }
    .bp3-menu-item.bp3-intent-success:active{
      background-color:#0d8050; }
    .bp3-menu-item.bp3-intent-success:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-menu-item.bp3-intent-success:hover::before, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::before, .bp3-menu-item.bp3-intent-success:hover::after, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::after,
    .bp3-menu-item.bp3-intent-success:hover .bp3-menu-item-label,
    .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item .bp3-menu-item-label, .bp3-menu-item.bp3-intent-success:active, .bp3-menu-item.bp3-intent-success:active::before, .bp3-menu-item.bp3-intent-success:active::after,
    .bp3-menu-item.bp3-intent-success:active .bp3-menu-item-label, .bp3-menu-item.bp3-intent-success.bp3-active, .bp3-menu-item.bp3-intent-success.bp3-active::before, .bp3-menu-item.bp3-intent-success.bp3-active::after,
    .bp3-menu-item.bp3-intent-success.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-menu-item.bp3-intent-warning{
    color:#bf7326; }
    .bp3-menu-item.bp3-intent-warning .bp3-icon{
      color:inherit; }
    .bp3-menu-item.bp3-intent-warning::before, .bp3-menu-item.bp3-intent-warning::after,
    .bp3-menu-item.bp3-intent-warning .bp3-menu-item-label{
      color:#bf7326; }
    .bp3-menu-item.bp3-intent-warning:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-menu-item.bp3-intent-warning.bp3-active{
      background-color:#d9822b; }
    .bp3-menu-item.bp3-intent-warning:active{
      background-color:#bf7326; }
    .bp3-menu-item.bp3-intent-warning:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-menu-item.bp3-intent-warning:hover::before, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::before, .bp3-menu-item.bp3-intent-warning:hover::after, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::after,
    .bp3-menu-item.bp3-intent-warning:hover .bp3-menu-item-label,
    .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item .bp3-menu-item-label, .bp3-menu-item.bp3-intent-warning:active, .bp3-menu-item.bp3-intent-warning:active::before, .bp3-menu-item.bp3-intent-warning:active::after,
    .bp3-menu-item.bp3-intent-warning:active .bp3-menu-item-label, .bp3-menu-item.bp3-intent-warning.bp3-active, .bp3-menu-item.bp3-intent-warning.bp3-active::before, .bp3-menu-item.bp3-intent-warning.bp3-active::after,
    .bp3-menu-item.bp3-intent-warning.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-menu-item.bp3-intent-danger{
    color:#c23030; }
    .bp3-menu-item.bp3-intent-danger .bp3-icon{
      color:inherit; }
    .bp3-menu-item.bp3-intent-danger::before, .bp3-menu-item.bp3-intent-danger::after,
    .bp3-menu-item.bp3-intent-danger .bp3-menu-item-label{
      color:#c23030; }
    .bp3-menu-item.bp3-intent-danger:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-menu-item.bp3-intent-danger.bp3-active{
      background-color:#db3737; }
    .bp3-menu-item.bp3-intent-danger:active{
      background-color:#c23030; }
    .bp3-menu-item.bp3-intent-danger:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-menu-item.bp3-intent-danger:hover::before, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::before, .bp3-menu-item.bp3-intent-danger:hover::after, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::after,
    .bp3-menu-item.bp3-intent-danger:hover .bp3-menu-item-label,
    .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item .bp3-menu-item-label, .bp3-menu-item.bp3-intent-danger:active, .bp3-menu-item.bp3-intent-danger:active::before, .bp3-menu-item.bp3-intent-danger:active::after,
    .bp3-menu-item.bp3-intent-danger:active .bp3-menu-item-label, .bp3-menu-item.bp3-intent-danger.bp3-active, .bp3-menu-item.bp3-intent-danger.bp3-active::before, .bp3-menu-item.bp3-intent-danger.bp3-active::after,
    .bp3-menu-item.bp3-intent-danger.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-menu-item::before{
    line-height:1;
    font-family:"Icons16", sans-serif;
    font-size:16px;
    font-weight:400;
    font-style:normal;
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased;
    margin-right:7px; }
  .bp3-menu-item::before,
  .bp3-menu-item > .bp3-icon{
    margin-top:2px;
    color:#5c7080; }
  .bp3-menu-item .bp3-menu-item-label{
    color:#5c7080; }
  .bp3-menu-item:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-menu-item{
    color:inherit; }
  .bp3-menu-item.bp3-active, .bp3-menu-item:active{
    background-color:rgba(115, 134, 148, 0.3); }
  .bp3-menu-item.bp3-disabled{
    outline:none !important;
    background-color:inherit !important;
    cursor:not-allowed !important;
    color:rgba(92, 112, 128, 0.6) !important; }
    .bp3-menu-item.bp3-disabled::before,
    .bp3-menu-item.bp3-disabled > .bp3-icon,
    .bp3-menu-item.bp3-disabled .bp3-menu-item-label{
      color:rgba(92, 112, 128, 0.6) !important; }
  .bp3-large .bp3-menu-item{
    padding:9px 7px;
    line-height:22px;
    font-size:16px; }
    .bp3-large .bp3-menu-item .bp3-icon{
      margin-top:3px; }
    .bp3-large .bp3-menu-item::before{
      line-height:1;
      font-family:"Icons20", sans-serif;
      font-size:20px;
      font-weight:400;
      font-style:normal;
      -moz-osx-font-smoothing:grayscale;
      -webkit-font-smoothing:antialiased;
      margin-top:1px;
      margin-right:10px; }

button.bp3-menu-item{
  border:none;
  background:none;
  width:100%;
  text-align:left; }
.bp3-menu-header{
  display:block;
  margin:5px;
  border-top:1px solid rgba(16, 22, 26, 0.15);
  cursor:default;
  padding-left:2px; }
  .bp3-dark .bp3-menu-header{
    border-top-color:rgba(255, 255, 255, 0.15); }
  .bp3-menu-header:first-of-type{
    border-top:none; }
  .bp3-menu-header > h6{
    color:#182026;
    font-weight:600;
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    margin:0;
    padding:10px 7px 0 1px;
    line-height:17px; }
    .bp3-dark .bp3-menu-header > h6{
      color:#f5f8fa; }
  .bp3-menu-header:first-of-type > h6{
    padding-top:0; }
  .bp3-large .bp3-menu-header > h6{
    padding-top:15px;
    padding-bottom:5px;
    font-size:18px; }
  .bp3-large .bp3-menu-header:first-of-type > h6{
    padding-top:0; }

.bp3-dark .bp3-menu{
  background:#30404d;
  color:#f5f8fa; }

.bp3-dark .bp3-menu-item.bp3-intent-primary{
  color:#48aff0; }
  .bp3-dark .bp3-menu-item.bp3-intent-primary .bp3-icon{
    color:inherit; }
  .bp3-dark .bp3-menu-item.bp3-intent-primary::before, .bp3-dark .bp3-menu-item.bp3-intent-primary::after,
  .bp3-dark .bp3-menu-item.bp3-intent-primary .bp3-menu-item-label{
    color:#48aff0; }
  .bp3-dark .bp3-menu-item.bp3-intent-primary:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active{
    background-color:#137cbd; }
  .bp3-dark .bp3-menu-item.bp3-intent-primary:active{
    background-color:#106ba3; }
  .bp3-dark .bp3-menu-item.bp3-intent-primary:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-primary:hover::before, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::before, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::before, .bp3-dark .bp3-menu-item.bp3-intent-primary:hover::after, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::after, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::after,
  .bp3-dark .bp3-menu-item.bp3-intent-primary:hover .bp3-menu-item-label,
  .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item .bp3-menu-item-label,
  .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-primary:active, .bp3-dark .bp3-menu-item.bp3-intent-primary:active::before, .bp3-dark .bp3-menu-item.bp3-intent-primary:active::after,
  .bp3-dark .bp3-menu-item.bp3-intent-primary:active .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active, .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active::before, .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active::after,
  .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active .bp3-menu-item-label{
    color:#ffffff; }

.bp3-dark .bp3-menu-item.bp3-intent-success{
  color:#3dcc91; }
  .bp3-dark .bp3-menu-item.bp3-intent-success .bp3-icon{
    color:inherit; }
  .bp3-dark .bp3-menu-item.bp3-intent-success::before, .bp3-dark .bp3-menu-item.bp3-intent-success::after,
  .bp3-dark .bp3-menu-item.bp3-intent-success .bp3-menu-item-label{
    color:#3dcc91; }
  .bp3-dark .bp3-menu-item.bp3-intent-success:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active{
    background-color:#0f9960; }
  .bp3-dark .bp3-menu-item.bp3-intent-success:active{
    background-color:#0d8050; }
  .bp3-dark .bp3-menu-item.bp3-intent-success:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-success:hover::before, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::before, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::before, .bp3-dark .bp3-menu-item.bp3-intent-success:hover::after, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::after, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::after,
  .bp3-dark .bp3-menu-item.bp3-intent-success:hover .bp3-menu-item-label,
  .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item .bp3-menu-item-label,
  .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-success:active, .bp3-dark .bp3-menu-item.bp3-intent-success:active::before, .bp3-dark .bp3-menu-item.bp3-intent-success:active::after,
  .bp3-dark .bp3-menu-item.bp3-intent-success:active .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active, .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active::before, .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active::after,
  .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active .bp3-menu-item-label{
    color:#ffffff; }

.bp3-dark .bp3-menu-item.bp3-intent-warning{
  color:#ffb366; }
  .bp3-dark .bp3-menu-item.bp3-intent-warning .bp3-icon{
    color:inherit; }
  .bp3-dark .bp3-menu-item.bp3-intent-warning::before, .bp3-dark .bp3-menu-item.bp3-intent-warning::after,
  .bp3-dark .bp3-menu-item.bp3-intent-warning .bp3-menu-item-label{
    color:#ffb366; }
  .bp3-dark .bp3-menu-item.bp3-intent-warning:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active{
    background-color:#d9822b; }
  .bp3-dark .bp3-menu-item.bp3-intent-warning:active{
    background-color:#bf7326; }
  .bp3-dark .bp3-menu-item.bp3-intent-warning:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-warning:hover::before, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::before, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::before, .bp3-dark .bp3-menu-item.bp3-intent-warning:hover::after, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::after, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::after,
  .bp3-dark .bp3-menu-item.bp3-intent-warning:hover .bp3-menu-item-label,
  .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item .bp3-menu-item-label,
  .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-warning:active, .bp3-dark .bp3-menu-item.bp3-intent-warning:active::before, .bp3-dark .bp3-menu-item.bp3-intent-warning:active::after,
  .bp3-dark .bp3-menu-item.bp3-intent-warning:active .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active, .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active::before, .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active::after,
  .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active .bp3-menu-item-label{
    color:#ffffff; }

.bp3-dark .bp3-menu-item.bp3-intent-danger{
  color:#ff7373; }
  .bp3-dark .bp3-menu-item.bp3-intent-danger .bp3-icon{
    color:inherit; }
  .bp3-dark .bp3-menu-item.bp3-intent-danger::before, .bp3-dark .bp3-menu-item.bp3-intent-danger::after,
  .bp3-dark .bp3-menu-item.bp3-intent-danger .bp3-menu-item-label{
    color:#ff7373; }
  .bp3-dark .bp3-menu-item.bp3-intent-danger:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active{
    background-color:#db3737; }
  .bp3-dark .bp3-menu-item.bp3-intent-danger:active{
    background-color:#c23030; }
  .bp3-dark .bp3-menu-item.bp3-intent-danger:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-danger:hover::before, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::before, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::before, .bp3-dark .bp3-menu-item.bp3-intent-danger:hover::after, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::after, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::after,
  .bp3-dark .bp3-menu-item.bp3-intent-danger:hover .bp3-menu-item-label,
  .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item .bp3-menu-item-label,
  .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-danger:active, .bp3-dark .bp3-menu-item.bp3-intent-danger:active::before, .bp3-dark .bp3-menu-item.bp3-intent-danger:active::after,
  .bp3-dark .bp3-menu-item.bp3-intent-danger:active .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active, .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active::before, .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active::after,
  .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active .bp3-menu-item-label{
    color:#ffffff; }

.bp3-dark .bp3-menu-item::before,
.bp3-dark .bp3-menu-item > .bp3-icon{
  color:#a7b6c2; }

.bp3-dark .bp3-menu-item .bp3-menu-item-label{
  color:#a7b6c2; }

.bp3-dark .bp3-menu-item.bp3-active, .bp3-dark .bp3-menu-item:active{
  background-color:rgba(138, 155, 168, 0.3); }

.bp3-dark .bp3-menu-item.bp3-disabled{
  color:rgba(167, 182, 194, 0.6) !important; }
  .bp3-dark .bp3-menu-item.bp3-disabled::before,
  .bp3-dark .bp3-menu-item.bp3-disabled > .bp3-icon,
  .bp3-dark .bp3-menu-item.bp3-disabled .bp3-menu-item-label{
    color:rgba(167, 182, 194, 0.6) !important; }

.bp3-dark .bp3-menu-divider,
.bp3-dark .bp3-menu-header{
  border-color:rgba(255, 255, 255, 0.15); }

.bp3-dark .bp3-menu-header > h6{
  color:#f5f8fa; }

.bp3-label .bp3-menu{
  margin-top:5px; }
.bp3-navbar{
  position:relative;
  z-index:10;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
  background-color:#ffffff;
  width:100%;
  height:50px;
  padding:0 15px; }
  .bp3-navbar.bp3-dark,
  .bp3-dark .bp3-navbar{
    background-color:#394b59; }
  .bp3-navbar.bp3-dark{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-navbar{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-navbar.bp3-fixed-top{
    position:fixed;
    top:0;
    right:0;
    left:0; }

.bp3-navbar-heading{
  margin-right:15px;
  font-size:16px; }

.bp3-navbar-group{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  height:50px; }
  .bp3-navbar-group.bp3-align-left{
    float:left; }
  .bp3-navbar-group.bp3-align-right{
    float:right; }

.bp3-navbar-divider{
  margin:0 10px;
  border-left:1px solid rgba(16, 22, 26, 0.15);
  height:20px; }
  .bp3-dark .bp3-navbar-divider{
    border-left-color:rgba(255, 255, 255, 0.15); }
.bp3-non-ideal-state{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  width:100%;
  height:100%;
  text-align:center; }
  .bp3-non-ideal-state > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-non-ideal-state > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-non-ideal-state::before,
  .bp3-non-ideal-state > *{
    margin-bottom:20px; }
  .bp3-non-ideal-state:empty::before,
  .bp3-non-ideal-state > :last-child{
    margin-bottom:0; }
  .bp3-non-ideal-state > *{
    max-width:400px; }

.bp3-non-ideal-state-visual{
  color:rgba(92, 112, 128, 0.6);
  font-size:60px; }
  .bp3-dark .bp3-non-ideal-state-visual{
    color:rgba(167, 182, 194, 0.6); }

.bp3-overflow-list{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -ms-flex-wrap:nowrap;
      flex-wrap:nowrap;
  min-width:0; }

.bp3-overflow-list-spacer{
  -ms-flex-negative:1;
      flex-shrink:1;
  width:1px; }

body.bp3-overlay-open{
  overflow:hidden; }

.bp3-overlay{
  position:static;
  top:0;
  right:0;
  bottom:0;
  left:0;
  z-index:20; }
  .bp3-overlay:not(.bp3-overlay-open){
    pointer-events:none; }
  .bp3-overlay.bp3-overlay-container{
    position:fixed;
    overflow:hidden; }
    .bp3-overlay.bp3-overlay-container.bp3-overlay-inline{
      position:absolute; }
  .bp3-overlay.bp3-overlay-scroll-container{
    position:fixed;
    overflow:auto; }
    .bp3-overlay.bp3-overlay-scroll-container.bp3-overlay-inline{
      position:absolute; }
  .bp3-overlay.bp3-overlay-inline{
    display:inline;
    overflow:visible; }

.bp3-overlay-content{
  position:fixed;
  z-index:20; }
  .bp3-overlay-inline .bp3-overlay-content,
  .bp3-overlay-scroll-container .bp3-overlay-content{
    position:absolute; }

.bp3-overlay-backdrop{
  position:fixed;
  top:0;
  right:0;
  bottom:0;
  left:0;
  opacity:1;
  z-index:20;
  background-color:rgba(16, 22, 26, 0.7);
  overflow:auto;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-overlay-backdrop.bp3-overlay-enter, .bp3-overlay-backdrop.bp3-overlay-appear{
    opacity:0; }
  .bp3-overlay-backdrop.bp3-overlay-enter-active, .bp3-overlay-backdrop.bp3-overlay-appear-active{
    opacity:1;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-overlay-backdrop.bp3-overlay-exit{
    opacity:1; }
  .bp3-overlay-backdrop.bp3-overlay-exit-active{
    opacity:0;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-overlay-backdrop:focus{
    outline:none; }
  .bp3-overlay-inline .bp3-overlay-backdrop{
    position:absolute; }
.bp3-panel-stack{
  position:relative;
  overflow:hidden; }

.bp3-panel-stack-header{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -ms-flex-negative:0;
      flex-shrink:0;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  z-index:1;
  -webkit-box-shadow:0 1px rgba(16, 22, 26, 0.15);
          box-shadow:0 1px rgba(16, 22, 26, 0.15);
  height:30px; }
  .bp3-dark .bp3-panel-stack-header{
    -webkit-box-shadow:0 1px rgba(255, 255, 255, 0.15);
            box-shadow:0 1px rgba(255, 255, 255, 0.15); }
  .bp3-panel-stack-header > span{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-flex:1;
        -ms-flex:1;
            flex:1;
    -webkit-box-align:stretch;
        -ms-flex-align:stretch;
            align-items:stretch; }
  .bp3-panel-stack-header .bp3-heading{
    margin:0 5px; }

.bp3-button.bp3-panel-stack-header-back{
  margin-left:5px;
  padding-left:0;
  white-space:nowrap; }
  .bp3-button.bp3-panel-stack-header-back .bp3-icon{
    margin:0 2px; }

.bp3-panel-stack-view{
  position:absolute;
  top:0;
  right:0;
  bottom:0;
  left:0;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin-right:-1px;
  border-right:1px solid rgba(16, 22, 26, 0.15);
  background-color:#ffffff;
  overflow-y:auto; }
  .bp3-dark .bp3-panel-stack-view{
    background-color:#30404d; }

.bp3-panel-stack-push .bp3-panel-stack-enter, .bp3-panel-stack-push .bp3-panel-stack-appear{
  -webkit-transform:translateX(100%);
          transform:translateX(100%);
  opacity:0; }

.bp3-panel-stack-push .bp3-panel-stack-enter-active, .bp3-panel-stack-push .bp3-panel-stack-appear-active{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease;
  -webkit-transition-delay:0;
          transition-delay:0; }

.bp3-panel-stack-push .bp3-panel-stack-exit{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1; }

.bp3-panel-stack-push .bp3-panel-stack-exit-active{
  -webkit-transform:translateX(-50%);
          transform:translateX(-50%);
  opacity:0;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease;
  -webkit-transition-delay:0;
          transition-delay:0; }

.bp3-panel-stack-pop .bp3-panel-stack-enter, .bp3-panel-stack-pop .bp3-panel-stack-appear{
  -webkit-transform:translateX(-50%);
          transform:translateX(-50%);
  opacity:0; }

.bp3-panel-stack-pop .bp3-panel-stack-enter-active, .bp3-panel-stack-pop .bp3-panel-stack-appear-active{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease;
  -webkit-transition-delay:0;
          transition-delay:0; }

.bp3-panel-stack-pop .bp3-panel-stack-exit{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1; }

.bp3-panel-stack-pop .bp3-panel-stack-exit-active{
  -webkit-transform:translateX(100%);
          transform:translateX(100%);
  opacity:0;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease;
  -webkit-transition-delay:0;
          transition-delay:0; }
.bp3-popover{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  -webkit-transform:scale(1);
          transform:scale(1);
  display:inline-block;
  z-index:20;
  border-radius:3px; }
  .bp3-popover .bp3-popover-arrow{
    position:absolute;
    width:30px;
    height:30px; }
    .bp3-popover .bp3-popover-arrow::before{
      margin:5px;
      width:20px;
      height:20px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-popover{
    margin-top:-17px;
    margin-bottom:17px; }
    .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-popover > .bp3-popover-arrow{
      bottom:-11px; }
      .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-popover > .bp3-popover-arrow svg{
        -webkit-transform:rotate(-90deg);
                transform:rotate(-90deg); }
  .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-popover{
    margin-left:17px; }
    .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-popover > .bp3-popover-arrow{
      left:-11px; }
      .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-popover > .bp3-popover-arrow svg{
        -webkit-transform:rotate(0);
                transform:rotate(0); }
  .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-popover{
    margin-top:17px; }
    .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-popover > .bp3-popover-arrow{
      top:-11px; }
      .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-popover > .bp3-popover-arrow svg{
        -webkit-transform:rotate(90deg);
                transform:rotate(90deg); }
  .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-popover{
    margin-right:17px;
    margin-left:-17px; }
    .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-popover > .bp3-popover-arrow{
      right:-11px; }
      .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-popover > .bp3-popover-arrow svg{
        -webkit-transform:rotate(180deg);
                transform:rotate(180deg); }
  .bp3-tether-element-attached-middle > .bp3-popover > .bp3-popover-arrow{
    top:50%;
    -webkit-transform:translateY(-50%);
            transform:translateY(-50%); }
  .bp3-tether-element-attached-center > .bp3-popover > .bp3-popover-arrow{
    right:50%;
    -webkit-transform:translateX(50%);
            transform:translateX(50%); }
  .bp3-tether-element-attached-top.bp3-tether-target-attached-top > .bp3-popover > .bp3-popover-arrow{
    top:-0.3934px; }
  .bp3-tether-element-attached-right.bp3-tether-target-attached-right > .bp3-popover > .bp3-popover-arrow{
    right:-0.3934px; }
  .bp3-tether-element-attached-left.bp3-tether-target-attached-left > .bp3-popover > .bp3-popover-arrow{
    left:-0.3934px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-bottom > .bp3-popover > .bp3-popover-arrow{
    bottom:-0.3934px; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-left > .bp3-popover{
    -webkit-transform-origin:top left;
            transform-origin:top left; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-center > .bp3-popover{
    -webkit-transform-origin:top center;
            transform-origin:top center; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-right > .bp3-popover{
    -webkit-transform-origin:top right;
            transform-origin:top right; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-left > .bp3-popover{
    -webkit-transform-origin:center left;
            transform-origin:center left; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-center > .bp3-popover{
    -webkit-transform-origin:center center;
            transform-origin:center center; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-right > .bp3-popover{
    -webkit-transform-origin:center right;
            transform-origin:center right; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-left > .bp3-popover{
    -webkit-transform-origin:bottom left;
            transform-origin:bottom left; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-center > .bp3-popover{
    -webkit-transform-origin:bottom center;
            transform-origin:bottom center; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-right > .bp3-popover{
    -webkit-transform-origin:bottom right;
            transform-origin:bottom right; }
  .bp3-popover .bp3-popover-content{
    background:#ffffff;
    color:inherit; }
  .bp3-popover .bp3-popover-arrow::before{
    -webkit-box-shadow:1px 1px 6px rgba(16, 22, 26, 0.2);
            box-shadow:1px 1px 6px rgba(16, 22, 26, 0.2); }
  .bp3-popover .bp3-popover-arrow-border{
    fill:#10161a;
    fill-opacity:0.1; }
  .bp3-popover .bp3-popover-arrow-fill{
    fill:#ffffff; }
  .bp3-popover-enter > .bp3-popover, .bp3-popover-appear > .bp3-popover{
    -webkit-transform:scale(0.3);
            transform:scale(0.3); }
  .bp3-popover-enter-active > .bp3-popover, .bp3-popover-appear-active > .bp3-popover{
    -webkit-transform:scale(1);
            transform:scale(1);
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-popover-exit > .bp3-popover{
    -webkit-transform:scale(1);
            transform:scale(1); }
  .bp3-popover-exit-active > .bp3-popover{
    -webkit-transform:scale(0.3);
            transform:scale(0.3);
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-popover .bp3-popover-content{
    position:relative;
    border-radius:3px; }
  .bp3-popover.bp3-popover-content-sizing .bp3-popover-content{
    max-width:350px;
    padding:20px; }
  .bp3-popover-target + .bp3-overlay .bp3-popover.bp3-popover-content-sizing{
    width:350px; }
  .bp3-popover.bp3-minimal{
    margin:0 !important; }
    .bp3-popover.bp3-minimal .bp3-popover-arrow{
      display:none; }
    .bp3-popover.bp3-minimal.bp3-popover{
      -webkit-transform:scale(1);
              transform:scale(1); }
      .bp3-popover-enter > .bp3-popover.bp3-minimal.bp3-popover, .bp3-popover-appear > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1); }
      .bp3-popover-enter-active > .bp3-popover.bp3-minimal.bp3-popover, .bp3-popover-appear-active > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1);
        -webkit-transition-property:-webkit-transform;
        transition-property:-webkit-transform;
        transition-property:transform;
        transition-property:transform, -webkit-transform;
        -webkit-transition-duration:100ms;
                transition-duration:100ms;
        -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
                transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
        -webkit-transition-delay:0;
                transition-delay:0; }
      .bp3-popover-exit > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1); }
      .bp3-popover-exit-active > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1);
        -webkit-transition-property:-webkit-transform;
        transition-property:-webkit-transform;
        transition-property:transform;
        transition-property:transform, -webkit-transform;
        -webkit-transition-duration:100ms;
                transition-duration:100ms;
        -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
                transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
        -webkit-transition-delay:0;
                transition-delay:0; }
  .bp3-popover.bp3-dark,
  .bp3-dark .bp3-popover{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }
    .bp3-popover.bp3-dark .bp3-popover-content,
    .bp3-dark .bp3-popover .bp3-popover-content{
      background:#30404d;
      color:inherit; }
    .bp3-popover.bp3-dark .bp3-popover-arrow::before,
    .bp3-dark .bp3-popover .bp3-popover-arrow::before{
      -webkit-box-shadow:1px 1px 6px rgba(16, 22, 26, 0.4);
              box-shadow:1px 1px 6px rgba(16, 22, 26, 0.4); }
    .bp3-popover.bp3-dark .bp3-popover-arrow-border,
    .bp3-dark .bp3-popover .bp3-popover-arrow-border{
      fill:#10161a;
      fill-opacity:0.2; }
    .bp3-popover.bp3-dark .bp3-popover-arrow-fill,
    .bp3-dark .bp3-popover .bp3-popover-arrow-fill{
      fill:#30404d; }

.bp3-popover-arrow::before{
  display:block;
  position:absolute;
  -webkit-transform:rotate(45deg);
          transform:rotate(45deg);
  border-radius:2px;
  content:""; }

.bp3-tether-pinned .bp3-popover-arrow{
  display:none; }

.bp3-popover-backdrop{
  background:rgba(255, 255, 255, 0); }

.bp3-transition-container{
  opacity:1;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  z-index:20; }
  .bp3-transition-container.bp3-popover-enter, .bp3-transition-container.bp3-popover-appear{
    opacity:0; }
  .bp3-transition-container.bp3-popover-enter-active, .bp3-transition-container.bp3-popover-appear-active{
    opacity:1;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-transition-container.bp3-popover-exit{
    opacity:1; }
  .bp3-transition-container.bp3-popover-exit-active{
    opacity:0;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-transition-container:focus{
    outline:none; }
  .bp3-transition-container.bp3-popover-leave .bp3-popover-content{
    pointer-events:none; }
  .bp3-transition-container[data-x-out-of-boundaries]{
    display:none; }

span.bp3-popover-target{
  display:inline-block; }

.bp3-popover-wrapper.bp3-fill{
  width:100%; }

.bp3-portal{
  position:absolute;
  top:0;
  right:0;
  left:0; }
@-webkit-keyframes linear-progress-bar-stripes{
  from{
    background-position:0 0; }
  to{
    background-position:30px 0; } }
@keyframes linear-progress-bar-stripes{
  from{
    background-position:0 0; }
  to{
    background-position:30px 0; } }

.bp3-progress-bar{
  display:block;
  position:relative;
  border-radius:40px;
  background:rgba(92, 112, 128, 0.2);
  width:100%;
  height:8px;
  overflow:hidden; }
  .bp3-progress-bar .bp3-progress-meter{
    position:absolute;
    border-radius:40px;
    background:linear-gradient(-45deg, rgba(255, 255, 255, 0.2) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.2) 50%, rgba(255, 255, 255, 0.2) 75%, transparent 75%);
    background-color:rgba(92, 112, 128, 0.8);
    background-size:30px 30px;
    width:100%;
    height:100%;
    -webkit-transition:width 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:width 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-progress-bar:not(.bp3-no-animation):not(.bp3-no-stripes) .bp3-progress-meter{
    animation:linear-progress-bar-stripes 300ms linear infinite reverse; }
  .bp3-progress-bar.bp3-no-stripes .bp3-progress-meter{
    background-image:none; }

.bp3-dark .bp3-progress-bar{
  background:rgba(16, 22, 26, 0.5); }
  .bp3-dark .bp3-progress-bar .bp3-progress-meter{
    background-color:#8a9ba8; }

.bp3-progress-bar.bp3-intent-primary .bp3-progress-meter{
  background-color:#137cbd; }

.bp3-progress-bar.bp3-intent-success .bp3-progress-meter{
  background-color:#0f9960; }

.bp3-progress-bar.bp3-intent-warning .bp3-progress-meter{
  background-color:#d9822b; }

.bp3-progress-bar.bp3-intent-danger .bp3-progress-meter{
  background-color:#db3737; }
@-webkit-keyframes skeleton-glow{
  from{
    border-color:rgba(206, 217, 224, 0.2);
    background:rgba(206, 217, 224, 0.2); }
  to{
    border-color:rgba(92, 112, 128, 0.2);
    background:rgba(92, 112, 128, 0.2); } }
@keyframes skeleton-glow{
  from{
    border-color:rgba(206, 217, 224, 0.2);
    background:rgba(206, 217, 224, 0.2); }
  to{
    border-color:rgba(92, 112, 128, 0.2);
    background:rgba(92, 112, 128, 0.2); } }
.bp3-skeleton{
  border-color:rgba(206, 217, 224, 0.2) !important;
  border-radius:2px;
  -webkit-box-shadow:none !important;
          box-shadow:none !important;
  background:rgba(206, 217, 224, 0.2);
  background-clip:padding-box !important;
  cursor:default;
  color:transparent !important;
  -webkit-animation:1000ms linear infinite alternate skeleton-glow;
          animation:1000ms linear infinite alternate skeleton-glow;
  pointer-events:none;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-skeleton::before, .bp3-skeleton::after,
  .bp3-skeleton *{
    visibility:hidden !important; }
.bp3-slider{
  width:100%;
  min-width:150px;
  height:40px;
  position:relative;
  outline:none;
  cursor:default;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-slider:hover{
    cursor:pointer; }
  .bp3-slider:active{
    cursor:-webkit-grabbing;
    cursor:grabbing; }
  .bp3-slider.bp3-disabled{
    opacity:0.5;
    cursor:not-allowed; }
  .bp3-slider.bp3-slider-unlabeled{
    height:16px; }

.bp3-slider-track,
.bp3-slider-progress{
  top:5px;
  right:0;
  left:0;
  height:6px;
  position:absolute; }

.bp3-slider-track{
  border-radius:3px;
  overflow:hidden; }

.bp3-slider-progress{
  background:rgba(92, 112, 128, 0.2); }
  .bp3-dark .bp3-slider-progress{
    background:rgba(16, 22, 26, 0.5); }
  .bp3-slider-progress.bp3-intent-primary{
    background-color:#137cbd; }
  .bp3-slider-progress.bp3-intent-success{
    background-color:#0f9960; }
  .bp3-slider-progress.bp3-intent-warning{
    background-color:#d9822b; }
  .bp3-slider-progress.bp3-intent-danger{
    background-color:#db3737; }

.bp3-slider-handle{
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
  background-color:#f5f8fa;
  background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
  background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
  color:#182026;
  position:absolute;
  top:0;
  left:0;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
  cursor:pointer;
  width:16px;
  height:16px; }
  .bp3-slider-handle:hover{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    background-clip:padding-box;
    background-color:#ebf1f5; }
  .bp3-slider-handle:active, .bp3-slider-handle.bp3-active{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background-color:#d8e1e8;
    background-image:none; }
  .bp3-slider-handle:disabled, .bp3-slider-handle.bp3-disabled{
    outline:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    background-color:rgba(206, 217, 224, 0.5);
    background-image:none;
    cursor:not-allowed;
    color:rgba(92, 112, 128, 0.6); }
    .bp3-slider-handle:disabled.bp3-active, .bp3-slider-handle:disabled.bp3-active:hover, .bp3-slider-handle.bp3-disabled.bp3-active, .bp3-slider-handle.bp3-disabled.bp3-active:hover{
      background:rgba(206, 217, 224, 0.7); }
  .bp3-slider-handle:focus{
    z-index:1; }
  .bp3-slider-handle:hover{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    background-clip:padding-box;
    background-color:#ebf1f5;
    z-index:2;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
    cursor:-webkit-grab;
    cursor:grab; }
  .bp3-slider-handle.bp3-active{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background-color:#d8e1e8;
    background-image:none;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 1px rgba(16, 22, 26, 0.1);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 1px rgba(16, 22, 26, 0.1);
    cursor:-webkit-grabbing;
    cursor:grabbing; }
  .bp3-disabled .bp3-slider-handle{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:#bfccd6;
    pointer-events:none; }
  .bp3-dark .bp3-slider-handle{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    background-color:#394b59;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
    color:#f5f8fa; }
    .bp3-dark .bp3-slider-handle:hover, .bp3-dark .bp3-slider-handle:active, .bp3-dark .bp3-slider-handle.bp3-active{
      color:#f5f8fa; }
    .bp3-dark .bp3-slider-handle:hover{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
      background-color:#30404d; }
    .bp3-dark .bp3-slider-handle:active, .bp3-dark .bp3-slider-handle.bp3-active{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#202b33;
      background-image:none; }
    .bp3-dark .bp3-slider-handle:disabled, .bp3-dark .bp3-slider-handle.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none;
      background-color:rgba(57, 75, 89, 0.5);
      background-image:none;
      color:rgba(167, 182, 194, 0.6); }
      .bp3-dark .bp3-slider-handle:disabled.bp3-active, .bp3-dark .bp3-slider-handle.bp3-disabled.bp3-active{
        background:rgba(57, 75, 89, 0.7); }
    .bp3-dark .bp3-slider-handle .bp3-button-spinner .bp3-spinner-head{
      background:rgba(16, 22, 26, 0.5);
      stroke:#8a9ba8; }
    .bp3-dark .bp3-slider-handle, .bp3-dark .bp3-slider-handle:hover{
      background-color:#394b59; }
    .bp3-dark .bp3-slider-handle.bp3-active{
      background-color:#293742; }
  .bp3-dark .bp3-disabled .bp3-slider-handle{
    border-color:#5c7080;
    -webkit-box-shadow:none;
            box-shadow:none;
    background:#5c7080; }
  .bp3-slider-handle .bp3-slider-label{
    margin-left:8px;
    border-radius:3px;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
    background:#394b59;
    color:#f5f8fa; }
    .bp3-dark .bp3-slider-handle .bp3-slider-label{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
      background:#e1e8ed;
      color:#394b59; }
    .bp3-disabled .bp3-slider-handle .bp3-slider-label{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-slider-handle.bp3-start, .bp3-slider-handle.bp3-end{
    width:8px; }
  .bp3-slider-handle.bp3-start{
    border-top-right-radius:0;
    border-bottom-right-radius:0; }
  .bp3-slider-handle.bp3-end{
    margin-left:8px;
    border-top-left-radius:0;
    border-bottom-left-radius:0; }
    .bp3-slider-handle.bp3-end .bp3-slider-label{
      margin-left:0; }

.bp3-slider-label{
  -webkit-transform:translate(-50%, 20px);
          transform:translate(-50%, 20px);
  display:inline-block;
  position:absolute;
  padding:2px 5px;
  vertical-align:top;
  line-height:1;
  font-size:12px; }

.bp3-slider.bp3-vertical{
  width:40px;
  min-width:40px;
  height:150px; }
  .bp3-slider.bp3-vertical .bp3-slider-track,
  .bp3-slider.bp3-vertical .bp3-slider-progress{
    top:0;
    bottom:0;
    left:5px;
    width:6px;
    height:auto; }
  .bp3-slider.bp3-vertical .bp3-slider-progress{
    top:auto; }
  .bp3-slider.bp3-vertical .bp3-slider-label{
    -webkit-transform:translate(20px, 50%);
            transform:translate(20px, 50%); }
  .bp3-slider.bp3-vertical .bp3-slider-handle{
    top:auto; }
    .bp3-slider.bp3-vertical .bp3-slider-handle .bp3-slider-label{
      margin-top:-8px;
      margin-left:0; }
    .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-end, .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-start{
      margin-left:0;
      width:16px;
      height:8px; }
    .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-start{
      border-top-left-radius:0;
      border-bottom-right-radius:3px; }
      .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-start .bp3-slider-label{
        -webkit-transform:translate(20px);
                transform:translate(20px); }
    .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-end{
      margin-bottom:8px;
      border-top-left-radius:3px;
      border-bottom-left-radius:0;
      border-bottom-right-radius:0; }

@-webkit-keyframes pt-spinner-animation{
  from{
    -webkit-transform:rotate(0deg);
            transform:rotate(0deg); }
  to{
    -webkit-transform:rotate(360deg);
            transform:rotate(360deg); } }

@keyframes pt-spinner-animation{
  from{
    -webkit-transform:rotate(0deg);
            transform:rotate(0deg); }
  to{
    -webkit-transform:rotate(360deg);
            transform:rotate(360deg); } }

.bp3-spinner{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  overflow:visible;
  vertical-align:middle; }
  .bp3-spinner svg{
    display:block; }
  .bp3-spinner path{
    fill-opacity:0; }
  .bp3-spinner .bp3-spinner-head{
    -webkit-transform-origin:center;
            transform-origin:center;
    -webkit-transition:stroke-dashoffset 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:stroke-dashoffset 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    stroke:rgba(92, 112, 128, 0.8);
    stroke-linecap:round; }
  .bp3-spinner .bp3-spinner-track{
    stroke:rgba(92, 112, 128, 0.2); }

.bp3-spinner-animation{
  -webkit-animation:pt-spinner-animation 500ms linear infinite;
          animation:pt-spinner-animation 500ms linear infinite; }
  .bp3-no-spin > .bp3-spinner-animation{
    -webkit-animation:none;
            animation:none; }

.bp3-dark .bp3-spinner .bp3-spinner-head{
  stroke:#8a9ba8; }

.bp3-dark .bp3-spinner .bp3-spinner-track{
  stroke:rgba(16, 22, 26, 0.5); }

.bp3-spinner.bp3-intent-primary .bp3-spinner-head{
  stroke:#137cbd; }

.bp3-spinner.bp3-intent-success .bp3-spinner-head{
  stroke:#0f9960; }

.bp3-spinner.bp3-intent-warning .bp3-spinner-head{
  stroke:#d9822b; }

.bp3-spinner.bp3-intent-danger .bp3-spinner-head{
  stroke:#db3737; }
.bp3-tabs.bp3-vertical{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex; }
  .bp3-tabs.bp3-vertical > .bp3-tab-list{
    -webkit-box-orient:vertical;
    -webkit-box-direction:normal;
        -ms-flex-direction:column;
            flex-direction:column;
    -webkit-box-align:start;
        -ms-flex-align:start;
            align-items:flex-start; }
    .bp3-tabs.bp3-vertical > .bp3-tab-list .bp3-tab{
      border-radius:3px;
      width:100%;
      padding:0 10px; }
      .bp3-tabs.bp3-vertical > .bp3-tab-list .bp3-tab[aria-selected="true"]{
        -webkit-box-shadow:none;
                box-shadow:none;
        background-color:rgba(19, 124, 189, 0.2); }
    .bp3-tabs.bp3-vertical > .bp3-tab-list .bp3-tab-indicator-wrapper .bp3-tab-indicator{
      top:0;
      right:0;
      bottom:0;
      left:0;
      border-radius:3px;
      background-color:rgba(19, 124, 189, 0.2);
      height:auto; }
  .bp3-tabs.bp3-vertical > .bp3-tab-panel{
    margin-top:0;
    padding-left:20px; }

.bp3-tab-list{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  -webkit-box-align:end;
      -ms-flex-align:end;
          align-items:flex-end;
  position:relative;
  margin:0;
  border:none;
  padding:0;
  list-style:none; }
  .bp3-tab-list > *:not(:last-child){
    margin-right:20px; }

.bp3-tab{
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  position:relative;
  cursor:pointer;
  max-width:100%;
  vertical-align:top;
  line-height:30px;
  color:#182026;
  font-size:14px; }
  .bp3-tab a{
    display:block;
    text-decoration:none;
    color:inherit; }
  .bp3-tab-indicator-wrapper ~ .bp3-tab{
    -webkit-box-shadow:none !important;
            box-shadow:none !important;
    background-color:transparent !important; }
  .bp3-tab[aria-disabled="true"]{
    cursor:not-allowed;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-tab[aria-selected="true"]{
    border-radius:0;
    -webkit-box-shadow:inset 0 -3px 0 #106ba3;
            box-shadow:inset 0 -3px 0 #106ba3; }
  .bp3-tab[aria-selected="true"], .bp3-tab:not([aria-disabled="true"]):hover{
    color:#106ba3; }
  .bp3-tab:focus{
    -moz-outline-radius:0; }
  .bp3-large > .bp3-tab{
    line-height:40px;
    font-size:16px; }

.bp3-tab-panel{
  margin-top:20px; }
  .bp3-tab-panel[aria-hidden="true"]{
    display:none; }

.bp3-tab-indicator-wrapper{
  position:absolute;
  top:0;
  left:0;
  -webkit-transform:translateX(0), translateY(0);
          transform:translateX(0), translateY(0);
  -webkit-transition:height, width, -webkit-transform;
  transition:height, width, -webkit-transform;
  transition:height, transform, width;
  transition:height, transform, width, -webkit-transform;
  -webkit-transition-duration:200ms;
          transition-duration:200ms;
  -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
          transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
  pointer-events:none; }
  .bp3-tab-indicator-wrapper .bp3-tab-indicator{
    position:absolute;
    right:0;
    bottom:0;
    left:0;
    background-color:#106ba3;
    height:3px; }
  .bp3-tab-indicator-wrapper.bp3-no-animation{
    -webkit-transition:none;
    transition:none; }

.bp3-dark .bp3-tab{
  color:#f5f8fa; }
  .bp3-dark .bp3-tab[aria-disabled="true"]{
    color:rgba(167, 182, 194, 0.6); }
  .bp3-dark .bp3-tab[aria-selected="true"]{
    -webkit-box-shadow:inset 0 -3px 0 #48aff0;
            box-shadow:inset 0 -3px 0 #48aff0; }
  .bp3-dark .bp3-tab[aria-selected="true"], .bp3-dark .bp3-tab:not([aria-disabled="true"]):hover{
    color:#48aff0; }

.bp3-dark .bp3-tab-indicator{
  background-color:#48aff0; }

.bp3-flex-expander{
  -webkit-box-flex:1;
      -ms-flex:1 1;
          flex:1 1; }
.bp3-tag{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  position:relative;
  border:none;
  border-radius:3px;
  -webkit-box-shadow:none;
          box-shadow:none;
  background-color:#5c7080;
  min-width:20px;
  max-width:100%;
  min-height:20px;
  padding:2px 6px;
  line-height:16px;
  color:#f5f8fa;
  font-size:12px; }
  .bp3-tag.bp3-interactive{
    cursor:pointer; }
    .bp3-tag.bp3-interactive:hover{
      background-color:rgba(92, 112, 128, 0.85); }
    .bp3-tag.bp3-interactive.bp3-active, .bp3-tag.bp3-interactive:active{
      background-color:rgba(92, 112, 128, 0.7); }
  .bp3-tag > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-tag > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-tag::before,
  .bp3-tag > *{
    margin-right:4px; }
  .bp3-tag:empty::before,
  .bp3-tag > :last-child{
    margin-right:0; }
  .bp3-tag:focus{
    outline:rgba(19, 124, 189, 0.6) auto 2px;
    outline-offset:0;
    -moz-outline-radius:6px; }
  .bp3-tag.bp3-round{
    border-radius:30px;
    padding-right:8px;
    padding-left:8px; }
  .bp3-dark .bp3-tag{
    background-color:#bfccd6;
    color:#182026; }
    .bp3-dark .bp3-tag.bp3-interactive{
      cursor:pointer; }
      .bp3-dark .bp3-tag.bp3-interactive:hover{
        background-color:rgba(191, 204, 214, 0.85); }
      .bp3-dark .bp3-tag.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-interactive:active{
        background-color:rgba(191, 204, 214, 0.7); }
    .bp3-dark .bp3-tag > .bp3-icon, .bp3-dark .bp3-tag .bp3-icon-standard, .bp3-dark .bp3-tag .bp3-icon-large{
      fill:currentColor; }
  .bp3-tag > .bp3-icon, .bp3-tag .bp3-icon-standard, .bp3-tag .bp3-icon-large{
    fill:#ffffff; }
  .bp3-tag.bp3-large,
  .bp3-large .bp3-tag{
    min-width:30px;
    min-height:30px;
    padding:0 10px;
    line-height:20px;
    font-size:14px; }
    .bp3-tag.bp3-large::before,
    .bp3-tag.bp3-large > *,
    .bp3-large .bp3-tag::before,
    .bp3-large .bp3-tag > *{
      margin-right:7px; }
    .bp3-tag.bp3-large:empty::before,
    .bp3-tag.bp3-large > :last-child,
    .bp3-large .bp3-tag:empty::before,
    .bp3-large .bp3-tag > :last-child{
      margin-right:0; }
    .bp3-tag.bp3-large.bp3-round,
    .bp3-large .bp3-tag.bp3-round{
      padding-right:12px;
      padding-left:12px; }
  .bp3-tag.bp3-intent-primary{
    background:#137cbd;
    color:#ffffff; }
    .bp3-tag.bp3-intent-primary.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-intent-primary.bp3-interactive:hover{
        background-color:rgba(19, 124, 189, 0.85); }
      .bp3-tag.bp3-intent-primary.bp3-interactive.bp3-active, .bp3-tag.bp3-intent-primary.bp3-interactive:active{
        background-color:rgba(19, 124, 189, 0.7); }
  .bp3-tag.bp3-intent-success{
    background:#0f9960;
    color:#ffffff; }
    .bp3-tag.bp3-intent-success.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-intent-success.bp3-interactive:hover{
        background-color:rgba(15, 153, 96, 0.85); }
      .bp3-tag.bp3-intent-success.bp3-interactive.bp3-active, .bp3-tag.bp3-intent-success.bp3-interactive:active{
        background-color:rgba(15, 153, 96, 0.7); }
  .bp3-tag.bp3-intent-warning{
    background:#d9822b;
    color:#ffffff; }
    .bp3-tag.bp3-intent-warning.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-intent-warning.bp3-interactive:hover{
        background-color:rgba(217, 130, 43, 0.85); }
      .bp3-tag.bp3-intent-warning.bp3-interactive.bp3-active, .bp3-tag.bp3-intent-warning.bp3-interactive:active{
        background-color:rgba(217, 130, 43, 0.7); }
  .bp3-tag.bp3-intent-danger{
    background:#db3737;
    color:#ffffff; }
    .bp3-tag.bp3-intent-danger.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-intent-danger.bp3-interactive:hover{
        background-color:rgba(219, 55, 55, 0.85); }
      .bp3-tag.bp3-intent-danger.bp3-interactive.bp3-active, .bp3-tag.bp3-intent-danger.bp3-interactive:active{
        background-color:rgba(219, 55, 55, 0.7); }
  .bp3-tag.bp3-fill{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    width:100%; }
  .bp3-tag.bp3-minimal > .bp3-icon, .bp3-tag.bp3-minimal .bp3-icon-standard, .bp3-tag.bp3-minimal .bp3-icon-large{
    fill:#5c7080; }
  .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]){
    background-color:rgba(138, 155, 168, 0.2);
    color:#182026; }
    .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive:hover{
        background-color:rgba(92, 112, 128, 0.3); }
      .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive.bp3-active, .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive:active{
        background-color:rgba(92, 112, 128, 0.4); }
    .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]){
      color:#f5f8fa; }
      .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive:hover{
          background-color:rgba(191, 204, 214, 0.3); }
        .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive:active{
          background-color:rgba(191, 204, 214, 0.4); }
      .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]) > .bp3-icon, .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]) .bp3-icon-standard, .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]) .bp3-icon-large{
        fill:#a7b6c2; }
  .bp3-tag.bp3-minimal.bp3-intent-primary{
    background-color:rgba(19, 124, 189, 0.15);
    color:#106ba3; }
    .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive:hover{
        background-color:rgba(19, 124, 189, 0.25); }
      .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive.bp3-active, .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive:active{
        background-color:rgba(19, 124, 189, 0.35); }
    .bp3-tag.bp3-minimal.bp3-intent-primary > .bp3-icon, .bp3-tag.bp3-minimal.bp3-intent-primary .bp3-icon-standard, .bp3-tag.bp3-minimal.bp3-intent-primary .bp3-icon-large{
      fill:#137cbd; }
    .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary{
      background-color:rgba(19, 124, 189, 0.25);
      color:#48aff0; }
      .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive:hover{
          background-color:rgba(19, 124, 189, 0.35); }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive:active{
          background-color:rgba(19, 124, 189, 0.45); }
  .bp3-tag.bp3-minimal.bp3-intent-success{
    background-color:rgba(15, 153, 96, 0.15);
    color:#0d8050; }
    .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive:hover{
        background-color:rgba(15, 153, 96, 0.25); }
      .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive.bp3-active, .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive:active{
        background-color:rgba(15, 153, 96, 0.35); }
    .bp3-tag.bp3-minimal.bp3-intent-success > .bp3-icon, .bp3-tag.bp3-minimal.bp3-intent-success .bp3-icon-standard, .bp3-tag.bp3-minimal.bp3-intent-success .bp3-icon-large{
      fill:#0f9960; }
    .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success{
      background-color:rgba(15, 153, 96, 0.25);
      color:#3dcc91; }
      .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive:hover{
          background-color:rgba(15, 153, 96, 0.35); }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive:active{
          background-color:rgba(15, 153, 96, 0.45); }
  .bp3-tag.bp3-minimal.bp3-intent-warning{
    background-color:rgba(217, 130, 43, 0.15);
    color:#bf7326; }
    .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive:hover{
        background-color:rgba(217, 130, 43, 0.25); }
      .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive.bp3-active, .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive:active{
        background-color:rgba(217, 130, 43, 0.35); }
    .bp3-tag.bp3-minimal.bp3-intent-warning > .bp3-icon, .bp3-tag.bp3-minimal.bp3-intent-warning .bp3-icon-standard, .bp3-tag.bp3-minimal.bp3-intent-warning .bp3-icon-large{
      fill:#d9822b; }
    .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning{
      background-color:rgba(217, 130, 43, 0.25);
      color:#ffb366; }
      .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive:hover{
          background-color:rgba(217, 130, 43, 0.35); }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive:active{
          background-color:rgba(217, 130, 43, 0.45); }
  .bp3-tag.bp3-minimal.bp3-intent-danger{
    background-color:rgba(219, 55, 55, 0.15);
    color:#c23030; }
    .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive:hover{
        background-color:rgba(219, 55, 55, 0.25); }
      .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive.bp3-active, .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive:active{
        background-color:rgba(219, 55, 55, 0.35); }
    .bp3-tag.bp3-minimal.bp3-intent-danger > .bp3-icon, .bp3-tag.bp3-minimal.bp3-intent-danger .bp3-icon-standard, .bp3-tag.bp3-minimal.bp3-intent-danger .bp3-icon-large{
      fill:#db3737; }
    .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger{
      background-color:rgba(219, 55, 55, 0.25);
      color:#ff7373; }
      .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive:hover{
          background-color:rgba(219, 55, 55, 0.35); }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive:active{
          background-color:rgba(219, 55, 55, 0.45); }

.bp3-tag-remove{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  opacity:0.5;
  margin-top:-2px;
  margin-right:-6px !important;
  margin-bottom:-2px;
  border:none;
  background:none;
  cursor:pointer;
  padding:2px;
  padding-left:0;
  color:inherit; }
  .bp3-tag-remove:hover{
    opacity:0.8;
    background:none;
    text-decoration:none; }
  .bp3-tag-remove:active{
    opacity:1; }
  .bp3-tag-remove:empty::before{
    line-height:1;
    font-family:"Icons16", sans-serif;
    font-size:16px;
    font-weight:400;
    font-style:normal;
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased;
    content:""; }
  .bp3-large .bp3-tag-remove{
    margin-right:-10px !important;
    padding:5px;
    padding-left:0; }
    .bp3-large .bp3-tag-remove:empty::before{
      line-height:1;
      font-family:"Icons20", sans-serif;
      font-size:20px;
      font-weight:400;
      font-style:normal; }
.bp3-tag-input{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:start;
      -ms-flex-align:start;
          align-items:flex-start;
  cursor:text;
  height:auto;
  min-height:30px;
  padding-right:0;
  padding-left:5px;
  line-height:inherit; }
  .bp3-tag-input > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-tag-input > .bp3-tag-input-values{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-tag-input .bp3-tag-input-icon{
    margin-top:7px;
    margin-right:7px;
    margin-left:2px;
    color:#5c7080; }
  .bp3-tag-input .bp3-tag-input-values{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-orient:horizontal;
    -webkit-box-direction:normal;
        -ms-flex-direction:row;
            flex-direction:row;
    -ms-flex-wrap:wrap;
        flex-wrap:wrap;
    -webkit-box-align:center;
        -ms-flex-align:center;
            align-items:center;
    -ms-flex-item-align:stretch;
        align-self:stretch;
    margin-top:5px;
    margin-right:7px;
    min-width:0; }
    .bp3-tag-input .bp3-tag-input-values > *{
      -webkit-box-flex:0;
          -ms-flex-positive:0;
              flex-grow:0;
      -ms-flex-negative:0;
          flex-shrink:0; }
    .bp3-tag-input .bp3-tag-input-values > .bp3-fill{
      -webkit-box-flex:1;
          -ms-flex-positive:1;
              flex-grow:1;
      -ms-flex-negative:1;
          flex-shrink:1; }
    .bp3-tag-input .bp3-tag-input-values::before,
    .bp3-tag-input .bp3-tag-input-values > *{
      margin-right:5px; }
    .bp3-tag-input .bp3-tag-input-values:empty::before,
    .bp3-tag-input .bp3-tag-input-values > :last-child{
      margin-right:0; }
    .bp3-tag-input .bp3-tag-input-values:first-child .bp3-input-ghost:first-child{
      padding-left:5px; }
    .bp3-tag-input .bp3-tag-input-values > *{
      margin-bottom:5px; }
  .bp3-tag-input .bp3-tag{
    overflow-wrap:break-word; }
    .bp3-tag-input .bp3-tag.bp3-active{
      outline:rgba(19, 124, 189, 0.6) auto 2px;
      outline-offset:0;
      -moz-outline-radius:6px; }
  .bp3-tag-input .bp3-input-ghost{
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    width:80px;
    line-height:20px; }
    .bp3-tag-input .bp3-input-ghost:disabled, .bp3-tag-input .bp3-input-ghost.bp3-disabled{
      cursor:not-allowed; }
  .bp3-tag-input .bp3-button,
  .bp3-tag-input .bp3-spinner{
    margin:3px;
    margin-left:0; }
  .bp3-tag-input .bp3-button{
    min-width:24px;
    min-height:24px;
    padding:0 7px; }
  .bp3-tag-input.bp3-large{
    height:auto;
    min-height:40px; }
    .bp3-tag-input.bp3-large::before,
    .bp3-tag-input.bp3-large > *{
      margin-right:10px; }
    .bp3-tag-input.bp3-large:empty::before,
    .bp3-tag-input.bp3-large > :last-child{
      margin-right:0; }
    .bp3-tag-input.bp3-large .bp3-tag-input-icon{
      margin-top:10px;
      margin-left:5px; }
    .bp3-tag-input.bp3-large .bp3-input-ghost{
      line-height:30px; }
    .bp3-tag-input.bp3-large .bp3-button{
      min-width:30px;
      min-height:30px;
      padding:5px 10px;
      margin:5px;
      margin-left:0; }
    .bp3-tag-input.bp3-large .bp3-spinner{
      margin:8px;
      margin-left:0; }
  .bp3-tag-input.bp3-active{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
    background-color:#ffffff; }
    .bp3-tag-input.bp3-active.bp3-intent-primary{
      -webkit-box-shadow:0 0 0 1px #106ba3, 0 0 0 3px rgba(16, 107, 163, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #106ba3, 0 0 0 3px rgba(16, 107, 163, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-tag-input.bp3-active.bp3-intent-success{
      -webkit-box-shadow:0 0 0 1px #0d8050, 0 0 0 3px rgba(13, 128, 80, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #0d8050, 0 0 0 3px rgba(13, 128, 80, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-tag-input.bp3-active.bp3-intent-warning{
      -webkit-box-shadow:0 0 0 1px #bf7326, 0 0 0 3px rgba(191, 115, 38, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #bf7326, 0 0 0 3px rgba(191, 115, 38, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-tag-input.bp3-active.bp3-intent-danger{
      -webkit-box-shadow:0 0 0 1px #c23030, 0 0 0 3px rgba(194, 48, 48, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #c23030, 0 0 0 3px rgba(194, 48, 48, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-tag-input .bp3-tag-input-icon, .bp3-tag-input.bp3-dark .bp3-tag-input-icon{
    color:#a7b6c2; }
  .bp3-dark .bp3-tag-input .bp3-input-ghost, .bp3-tag-input.bp3-dark .bp3-input-ghost{
    color:#f5f8fa; }
    .bp3-dark .bp3-tag-input .bp3-input-ghost::-webkit-input-placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost::-webkit-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-tag-input .bp3-input-ghost::-moz-placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost::-moz-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-tag-input .bp3-input-ghost:-ms-input-placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost:-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-tag-input .bp3-input-ghost::-ms-input-placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost::-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-tag-input .bp3-input-ghost::placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost::placeholder{
      color:rgba(167, 182, 194, 0.6); }
  .bp3-dark .bp3-tag-input.bp3-active, .bp3-tag-input.bp3-dark.bp3-active{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    background-color:rgba(16, 22, 26, 0.3); }
    .bp3-dark .bp3-tag-input.bp3-active.bp3-intent-primary, .bp3-tag-input.bp3-dark.bp3-active.bp3-intent-primary{
      -webkit-box-shadow:0 0 0 1px #106ba3, 0 0 0 3px rgba(16, 107, 163, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #106ba3, 0 0 0 3px rgba(16, 107, 163, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-tag-input.bp3-active.bp3-intent-success, .bp3-tag-input.bp3-dark.bp3-active.bp3-intent-success{
      -webkit-box-shadow:0 0 0 1px #0d8050, 0 0 0 3px rgba(13, 128, 80, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #0d8050, 0 0 0 3px rgba(13, 128, 80, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-tag-input.bp3-active.bp3-intent-warning, .bp3-tag-input.bp3-dark.bp3-active.bp3-intent-warning{
      -webkit-box-shadow:0 0 0 1px #bf7326, 0 0 0 3px rgba(191, 115, 38, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #bf7326, 0 0 0 3px rgba(191, 115, 38, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-tag-input.bp3-active.bp3-intent-danger, .bp3-tag-input.bp3-dark.bp3-active.bp3-intent-danger{
      -webkit-box-shadow:0 0 0 1px #c23030, 0 0 0 3px rgba(194, 48, 48, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #c23030, 0 0 0 3px rgba(194, 48, 48, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }

.bp3-input-ghost{
  border:none;
  -webkit-box-shadow:none;
          box-shadow:none;
  background:none;
  padding:0; }
  .bp3-input-ghost::-webkit-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input-ghost::-moz-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input-ghost:-ms-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input-ghost::-ms-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input-ghost::placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input-ghost:focus{
    outline:none !important; }
.bp3-toast{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-align:start;
      -ms-flex-align:start;
          align-items:flex-start;
  position:relative !important;
  margin:20px 0 0;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  background-color:#ffffff;
  min-width:300px;
  max-width:500px;
  pointer-events:all; }
  .bp3-toast.bp3-toast-enter, .bp3-toast.bp3-toast-appear{
    -webkit-transform:translateY(-40px);
            transform:translateY(-40px); }
  .bp3-toast.bp3-toast-enter-active, .bp3-toast.bp3-toast-appear-active{
    -webkit-transform:translateY(0);
            transform:translateY(0);
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-toast.bp3-toast-enter ~ .bp3-toast, .bp3-toast.bp3-toast-appear ~ .bp3-toast{
    -webkit-transform:translateY(-40px);
            transform:translateY(-40px); }
  .bp3-toast.bp3-toast-enter-active ~ .bp3-toast, .bp3-toast.bp3-toast-appear-active ~ .bp3-toast{
    -webkit-transform:translateY(0);
            transform:translateY(0);
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-toast.bp3-toast-exit{
    opacity:1;
    -webkit-filter:blur(0);
            filter:blur(0); }
  .bp3-toast.bp3-toast-exit-active{
    opacity:0;
    -webkit-filter:blur(10px);
            filter:blur(10px);
    -webkit-transition-property:opacity, -webkit-filter;
    transition-property:opacity, -webkit-filter;
    transition-property:opacity, filter;
    transition-property:opacity, filter, -webkit-filter;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-toast.bp3-toast-exit ~ .bp3-toast{
    -webkit-transform:translateY(0);
            transform:translateY(0); }
  .bp3-toast.bp3-toast-exit-active ~ .bp3-toast{
    -webkit-transform:translateY(-40px);
            transform:translateY(-40px);
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:50ms;
            transition-delay:50ms; }
  .bp3-toast .bp3-button-group{
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    padding:5px;
    padding-left:0; }
  .bp3-toast > .bp3-icon{
    margin:12px;
    margin-right:0;
    color:#5c7080; }
  .bp3-toast.bp3-dark,
  .bp3-dark .bp3-toast{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
    background-color:#394b59; }
    .bp3-toast.bp3-dark > .bp3-icon,
    .bp3-dark .bp3-toast > .bp3-icon{
      color:#a7b6c2; }
  .bp3-toast[class*="bp3-intent-"] a{
    color:rgba(255, 255, 255, 0.7); }
    .bp3-toast[class*="bp3-intent-"] a:hover{
      color:#ffffff; }
  .bp3-toast[class*="bp3-intent-"] > .bp3-icon{
    color:#ffffff; }
  .bp3-toast[class*="bp3-intent-"] .bp3-button, .bp3-toast[class*="bp3-intent-"] .bp3-button::before,
  .bp3-toast[class*="bp3-intent-"] .bp3-button .bp3-icon, .bp3-toast[class*="bp3-intent-"] .bp3-button:active{
    color:rgba(255, 255, 255, 0.7) !important; }
  .bp3-toast[class*="bp3-intent-"] .bp3-button:focus{
    outline-color:rgba(255, 255, 255, 0.5); }
  .bp3-toast[class*="bp3-intent-"] .bp3-button:hover{
    background-color:rgba(255, 255, 255, 0.15) !important;
    color:#ffffff !important; }
  .bp3-toast[class*="bp3-intent-"] .bp3-button:active{
    background-color:rgba(255, 255, 255, 0.3) !important;
    color:#ffffff !important; }
  .bp3-toast[class*="bp3-intent-"] .bp3-button::after{
    background:rgba(255, 255, 255, 0.3) !important; }
  .bp3-toast.bp3-intent-primary{
    background-color:#137cbd;
    color:#ffffff; }
  .bp3-toast.bp3-intent-success{
    background-color:#0f9960;
    color:#ffffff; }
  .bp3-toast.bp3-intent-warning{
    background-color:#d9822b;
    color:#ffffff; }
  .bp3-toast.bp3-intent-danger{
    background-color:#db3737;
    color:#ffffff; }

.bp3-toast-message{
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto;
  padding:11px;
  word-break:break-word; }

.bp3-toast-container{
  display:-webkit-box !important;
  display:-ms-flexbox !important;
  display:flex !important;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  position:fixed;
  right:0;
  left:0;
  z-index:40;
  overflow:hidden;
  padding:0 20px 20px;
  pointer-events:none; }
  .bp3-toast-container.bp3-toast-container-top{
    top:0;
    bottom:auto; }
  .bp3-toast-container.bp3-toast-container-bottom{
    -webkit-box-orient:vertical;
    -webkit-box-direction:reverse;
        -ms-flex-direction:column-reverse;
            flex-direction:column-reverse;
    top:auto;
    bottom:0; }
  .bp3-toast-container.bp3-toast-container-left{
    -webkit-box-align:start;
        -ms-flex-align:start;
            align-items:flex-start; }
  .bp3-toast-container.bp3-toast-container-right{
    -webkit-box-align:end;
        -ms-flex-align:end;
            align-items:flex-end; }

.bp3-toast-container-bottom .bp3-toast.bp3-toast-enter:not(.bp3-toast-enter-active),
.bp3-toast-container-bottom .bp3-toast.bp3-toast-enter:not(.bp3-toast-enter-active) ~ .bp3-toast, .bp3-toast-container-bottom .bp3-toast.bp3-toast-appear:not(.bp3-toast-appear-active),
.bp3-toast-container-bottom .bp3-toast.bp3-toast-appear:not(.bp3-toast-appear-active) ~ .bp3-toast,
.bp3-toast-container-bottom .bp3-toast.bp3-toast-leave-active ~ .bp3-toast{
  -webkit-transform:translateY(60px);
          transform:translateY(60px); }
.bp3-tooltip{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  -webkit-transform:scale(1);
          transform:scale(1); }
  .bp3-tooltip .bp3-popover-arrow{
    position:absolute;
    width:22px;
    height:22px; }
    .bp3-tooltip .bp3-popover-arrow::before{
      margin:4px;
      width:14px;
      height:14px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-tooltip{
    margin-top:-11px;
    margin-bottom:11px; }
    .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-tooltip > .bp3-popover-arrow{
      bottom:-8px; }
      .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-tooltip > .bp3-popover-arrow svg{
        -webkit-transform:rotate(-90deg);
                transform:rotate(-90deg); }
  .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-tooltip{
    margin-left:11px; }
    .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-tooltip > .bp3-popover-arrow{
      left:-8px; }
      .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-tooltip > .bp3-popover-arrow svg{
        -webkit-transform:rotate(0);
                transform:rotate(0); }
  .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-tooltip{
    margin-top:11px; }
    .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-tooltip > .bp3-popover-arrow{
      top:-8px; }
      .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-tooltip > .bp3-popover-arrow svg{
        -webkit-transform:rotate(90deg);
                transform:rotate(90deg); }
  .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-tooltip{
    margin-right:11px;
    margin-left:-11px; }
    .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-tooltip > .bp3-popover-arrow{
      right:-8px; }
      .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-tooltip > .bp3-popover-arrow svg{
        -webkit-transform:rotate(180deg);
                transform:rotate(180deg); }
  .bp3-tether-element-attached-middle > .bp3-tooltip > .bp3-popover-arrow{
    top:50%;
    -webkit-transform:translateY(-50%);
            transform:translateY(-50%); }
  .bp3-tether-element-attached-center > .bp3-tooltip > .bp3-popover-arrow{
    right:50%;
    -webkit-transform:translateX(50%);
            transform:translateX(50%); }
  .bp3-tether-element-attached-top.bp3-tether-target-attached-top > .bp3-tooltip > .bp3-popover-arrow{
    top:-0.22183px; }
  .bp3-tether-element-attached-right.bp3-tether-target-attached-right > .bp3-tooltip > .bp3-popover-arrow{
    right:-0.22183px; }
  .bp3-tether-element-attached-left.bp3-tether-target-attached-left > .bp3-tooltip > .bp3-popover-arrow{
    left:-0.22183px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-bottom > .bp3-tooltip > .bp3-popover-arrow{
    bottom:-0.22183px; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-left > .bp3-tooltip{
    -webkit-transform-origin:top left;
            transform-origin:top left; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-center > .bp3-tooltip{
    -webkit-transform-origin:top center;
            transform-origin:top center; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-right > .bp3-tooltip{
    -webkit-transform-origin:top right;
            transform-origin:top right; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-left > .bp3-tooltip{
    -webkit-transform-origin:center left;
            transform-origin:center left; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-center > .bp3-tooltip{
    -webkit-transform-origin:center center;
            transform-origin:center center; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-right > .bp3-tooltip{
    -webkit-transform-origin:center right;
            transform-origin:center right; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-left > .bp3-tooltip{
    -webkit-transform-origin:bottom left;
            transform-origin:bottom left; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-center > .bp3-tooltip{
    -webkit-transform-origin:bottom center;
            transform-origin:bottom center; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-right > .bp3-tooltip{
    -webkit-transform-origin:bottom right;
            transform-origin:bottom right; }
  .bp3-tooltip .bp3-popover-content{
    background:#394b59;
    color:#f5f8fa; }
  .bp3-tooltip .bp3-popover-arrow::before{
    -webkit-box-shadow:1px 1px 6px rgba(16, 22, 26, 0.2);
            box-shadow:1px 1px 6px rgba(16, 22, 26, 0.2); }
  .bp3-tooltip .bp3-popover-arrow-border{
    fill:#10161a;
    fill-opacity:0.1; }
  .bp3-tooltip .bp3-popover-arrow-fill{
    fill:#394b59; }
  .bp3-popover-enter > .bp3-tooltip, .bp3-popover-appear > .bp3-tooltip{
    -webkit-transform:scale(0.8);
            transform:scale(0.8); }
  .bp3-popover-enter-active > .bp3-tooltip, .bp3-popover-appear-active > .bp3-tooltip{
    -webkit-transform:scale(1);
            transform:scale(1);
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-popover-exit > .bp3-tooltip{
    -webkit-transform:scale(1);
            transform:scale(1); }
  .bp3-popover-exit-active > .bp3-tooltip{
    -webkit-transform:scale(0.8);
            transform:scale(0.8);
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-tooltip .bp3-popover-content{
    padding:10px 12px; }
  .bp3-tooltip.bp3-dark,
  .bp3-dark .bp3-tooltip{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }
    .bp3-tooltip.bp3-dark .bp3-popover-content,
    .bp3-dark .bp3-tooltip .bp3-popover-content{
      background:#e1e8ed;
      color:#394b59; }
    .bp3-tooltip.bp3-dark .bp3-popover-arrow::before,
    .bp3-dark .bp3-tooltip .bp3-popover-arrow::before{
      -webkit-box-shadow:1px 1px 6px rgba(16, 22, 26, 0.4);
              box-shadow:1px 1px 6px rgba(16, 22, 26, 0.4); }
    .bp3-tooltip.bp3-dark .bp3-popover-arrow-border,
    .bp3-dark .bp3-tooltip .bp3-popover-arrow-border{
      fill:#10161a;
      fill-opacity:0.2; }
    .bp3-tooltip.bp3-dark .bp3-popover-arrow-fill,
    .bp3-dark .bp3-tooltip .bp3-popover-arrow-fill{
      fill:#e1e8ed; }
  .bp3-tooltip.bp3-intent-primary .bp3-popover-content{
    background:#137cbd;
    color:#ffffff; }
  .bp3-tooltip.bp3-intent-primary .bp3-popover-arrow-fill{
    fill:#137cbd; }
  .bp3-tooltip.bp3-intent-success .bp3-popover-content{
    background:#0f9960;
    color:#ffffff; }
  .bp3-tooltip.bp3-intent-success .bp3-popover-arrow-fill{
    fill:#0f9960; }
  .bp3-tooltip.bp3-intent-warning .bp3-popover-content{
    background:#d9822b;
    color:#ffffff; }
  .bp3-tooltip.bp3-intent-warning .bp3-popover-arrow-fill{
    fill:#d9822b; }
  .bp3-tooltip.bp3-intent-danger .bp3-popover-content{
    background:#db3737;
    color:#ffffff; }
  .bp3-tooltip.bp3-intent-danger .bp3-popover-arrow-fill{
    fill:#db3737; }

.bp3-tooltip-indicator{
  border-bottom:dotted 1px;
  cursor:help; }
.bp3-tree .bp3-icon, .bp3-tree .bp3-icon-standard, .bp3-tree .bp3-icon-large{
  color:#5c7080; }
  .bp3-tree .bp3-icon.bp3-intent-primary, .bp3-tree .bp3-icon-standard.bp3-intent-primary, .bp3-tree .bp3-icon-large.bp3-intent-primary{
    color:#137cbd; }
  .bp3-tree .bp3-icon.bp3-intent-success, .bp3-tree .bp3-icon-standard.bp3-intent-success, .bp3-tree .bp3-icon-large.bp3-intent-success{
    color:#0f9960; }
  .bp3-tree .bp3-icon.bp3-intent-warning, .bp3-tree .bp3-icon-standard.bp3-intent-warning, .bp3-tree .bp3-icon-large.bp3-intent-warning{
    color:#d9822b; }
  .bp3-tree .bp3-icon.bp3-intent-danger, .bp3-tree .bp3-icon-standard.bp3-intent-danger, .bp3-tree .bp3-icon-large.bp3-intent-danger{
    color:#db3737; }

.bp3-tree-node-list{
  margin:0;
  padding-left:0;
  list-style:none; }

.bp3-tree-root{
  position:relative;
  background-color:transparent;
  cursor:default;
  padding-left:0; }

.bp3-tree-node-content-0{
  padding-left:0px; }

.bp3-tree-node-content-1{
  padding-left:23px; }

.bp3-tree-node-content-2{
  padding-left:46px; }

.bp3-tree-node-content-3{
  padding-left:69px; }

.bp3-tree-node-content-4{
  padding-left:92px; }

.bp3-tree-node-content-5{
  padding-left:115px; }

.bp3-tree-node-content-6{
  padding-left:138px; }

.bp3-tree-node-content-7{
  padding-left:161px; }

.bp3-tree-node-content-8{
  padding-left:184px; }

.bp3-tree-node-content-9{
  padding-left:207px; }

.bp3-tree-node-content-10{
  padding-left:230px; }

.bp3-tree-node-content-11{
  padding-left:253px; }

.bp3-tree-node-content-12{
  padding-left:276px; }

.bp3-tree-node-content-13{
  padding-left:299px; }

.bp3-tree-node-content-14{
  padding-left:322px; }

.bp3-tree-node-content-15{
  padding-left:345px; }

.bp3-tree-node-content-16{
  padding-left:368px; }

.bp3-tree-node-content-17{
  padding-left:391px; }

.bp3-tree-node-content-18{
  padding-left:414px; }

.bp3-tree-node-content-19{
  padding-left:437px; }

.bp3-tree-node-content-20{
  padding-left:460px; }

.bp3-tree-node-content{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  width:100%;
  height:30px;
  padding-right:5px; }
  .bp3-tree-node-content:hover{
    background-color:rgba(191, 204, 214, 0.4); }

.bp3-tree-node-caret,
.bp3-tree-node-caret-none{
  min-width:30px; }

.bp3-tree-node-caret{
  color:#5c7080;
  -webkit-transform:rotate(0deg);
          transform:rotate(0deg);
  cursor:pointer;
  padding:7px;
  -webkit-transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-tree-node-caret:hover{
    color:#182026; }
  .bp3-dark .bp3-tree-node-caret{
    color:#a7b6c2; }
    .bp3-dark .bp3-tree-node-caret:hover{
      color:#f5f8fa; }
  .bp3-tree-node-caret.bp3-tree-node-caret-open{
    -webkit-transform:rotate(90deg);
            transform:rotate(90deg); }
  .bp3-tree-node-caret.bp3-icon-standard::before{
    content:""; }

.bp3-tree-node-icon{
  position:relative;
  margin-right:7px; }

.bp3-tree-node-label{
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal;
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto;
  position:relative;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-tree-node-label span{
    display:inline; }

.bp3-tree-node-secondary-label{
  padding:0 5px;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-tree-node-secondary-label .bp3-popover-wrapper,
  .bp3-tree-node-secondary-label .bp3-popover-target{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-align:center;
        -ms-flex-align:center;
            align-items:center; }

.bp3-tree-node.bp3-disabled .bp3-tree-node-content{
  background-color:inherit;
  cursor:not-allowed;
  color:rgba(92, 112, 128, 0.6); }

.bp3-tree-node.bp3-disabled .bp3-tree-node-caret,
.bp3-tree-node.bp3-disabled .bp3-tree-node-icon{
  cursor:not-allowed;
  color:rgba(92, 112, 128, 0.6); }

.bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content{
  background-color:#137cbd; }
  .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content,
  .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-icon, .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-icon-standard, .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-icon-large{
    color:#ffffff; }
  .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-tree-node-caret::before{
    color:rgba(255, 255, 255, 0.7); }
  .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-tree-node-caret:hover::before{
    color:#ffffff; }

.bp3-dark .bp3-tree-node-content:hover{
  background-color:rgba(92, 112, 128, 0.3); }

.bp3-dark .bp3-tree .bp3-icon, .bp3-dark .bp3-tree .bp3-icon-standard, .bp3-dark .bp3-tree .bp3-icon-large{
  color:#a7b6c2; }
  .bp3-dark .bp3-tree .bp3-icon.bp3-intent-primary, .bp3-dark .bp3-tree .bp3-icon-standard.bp3-intent-primary, .bp3-dark .bp3-tree .bp3-icon-large.bp3-intent-primary{
    color:#137cbd; }
  .bp3-dark .bp3-tree .bp3-icon.bp3-intent-success, .bp3-dark .bp3-tree .bp3-icon-standard.bp3-intent-success, .bp3-dark .bp3-tree .bp3-icon-large.bp3-intent-success{
    color:#0f9960; }
  .bp3-dark .bp3-tree .bp3-icon.bp3-intent-warning, .bp3-dark .bp3-tree .bp3-icon-standard.bp3-intent-warning, .bp3-dark .bp3-tree .bp3-icon-large.bp3-intent-warning{
    color:#d9822b; }
  .bp3-dark .bp3-tree .bp3-icon.bp3-intent-danger, .bp3-dark .bp3-tree .bp3-icon-standard.bp3-intent-danger, .bp3-dark .bp3-tree .bp3-icon-large.bp3-intent-danger{
    color:#db3737; }

.bp3-dark .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content{
  background-color:#137cbd; }
/*!

Copyright 2017-present Palantir Technologies, Inc. All rights reserved.
Licensed under the Apache License, Version 2.0.

*/
.bp3-omnibar{
  -webkit-filter:blur(0);
          filter:blur(0);
  opacity:1;
  top:20vh;
  left:calc(50% - 250px);
  z-index:21;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
  background-color:#ffffff;
  width:500px; }
  .bp3-omnibar.bp3-overlay-enter, .bp3-omnibar.bp3-overlay-appear{
    -webkit-filter:blur(20px);
            filter:blur(20px);
    opacity:0.2; }
  .bp3-omnibar.bp3-overlay-enter-active, .bp3-omnibar.bp3-overlay-appear-active{
    -webkit-filter:blur(0);
            filter:blur(0);
    opacity:1;
    -webkit-transition-property:opacity, -webkit-filter;
    transition-property:opacity, -webkit-filter;
    transition-property:filter, opacity;
    transition-property:filter, opacity, -webkit-filter;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-omnibar.bp3-overlay-exit{
    -webkit-filter:blur(0);
            filter:blur(0);
    opacity:1; }
  .bp3-omnibar.bp3-overlay-exit-active{
    -webkit-filter:blur(20px);
            filter:blur(20px);
    opacity:0.2;
    -webkit-transition-property:opacity, -webkit-filter;
    transition-property:opacity, -webkit-filter;
    transition-property:filter, opacity;
    transition-property:filter, opacity, -webkit-filter;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-omnibar .bp3-input{
    border-radius:0;
    background-color:transparent; }
    .bp3-omnibar .bp3-input, .bp3-omnibar .bp3-input:focus{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-omnibar .bp3-menu{
    border-radius:0;
    -webkit-box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
    background-color:transparent;
    max-height:calc(60vh - 40px);
    overflow:auto; }
    .bp3-omnibar .bp3-menu:empty{
      display:none; }
  .bp3-dark .bp3-omnibar, .bp3-omnibar.bp3-dark{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
    background-color:#30404d; }

.bp3-omnibar-overlay .bp3-overlay-backdrop{
  background-color:rgba(16, 22, 26, 0.2); }

.bp3-select-popover .bp3-popover-content{
  padding:5px; }

.bp3-select-popover .bp3-input-group{
  margin-bottom:0; }

.bp3-select-popover .bp3-menu{
  max-width:400px;
  max-height:300px;
  overflow:auto;
  padding:0; }
  .bp3-select-popover .bp3-menu:not(:first-child){
    padding-top:5px; }

.bp3-multi-select{
  min-width:150px; }

.bp3-multi-select-popover .bp3-menu{
  max-width:400px;
  max-height:300px;
  overflow:auto; }

.bp3-select-popover .bp3-popover-content{
  padding:5px; }

.bp3-select-popover .bp3-input-group{
  margin-bottom:0; }

.bp3-select-popover .bp3-menu{
  max-width:400px;
  max-height:300px;
  overflow:auto;
  padding:0; }
  .bp3-select-popover .bp3-menu:not(:first-child){
    padding-top:5px; }
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensureUiComponents() in @jupyterlab/buildutils */

/**
 * (DEPRECATED) Support for consuming icons as CSS background images
 */

/* Icons urls */

:root {
  --jp-icon-add: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE5IDEzaC02djZoLTJ2LTZINXYtMmg2VjVoMnY2aDZ2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-bug: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwIDhoLTIuODFjLS40NS0uNzgtMS4wNy0xLjQ1LTEuODItMS45NkwxNyA0LjQxIDE1LjU5IDNsLTIuMTcgMi4xN0MxMi45NiA1LjA2IDEyLjQ5IDUgMTIgNWMtLjQ5IDAtLjk2LjA2LTEuNDEuMTdMOC40MSAzIDcgNC40MWwxLjYyIDEuNjNDNy44OCA2LjU1IDcuMjYgNy4yMiA2LjgxIDhINHYyaDIuMDljLS4wNS4zMy0uMDkuNjYtLjA5IDF2MUg0djJoMnYxYzAgLjM0LjA0LjY3LjA5IDFINHYyaDIuODFjMS4wNCAxLjc5IDIuOTcgMyA1LjE5IDNzNC4xNS0xLjIxIDUuMTktM0gyMHYtMmgtMi4wOWMuMDUtLjMzLjA5LS42Ni4wOS0xdi0xaDJ2LTJoLTJ2LTFjMC0uMzQtLjA0LS42Ny0uMDktMUgyMFY4em0tNiA4aC00di0yaDR2MnptMC00aC00di0yaDR2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-build: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE0LjkgMTcuNDVDMTYuMjUgMTcuNDUgMTcuMzUgMTYuMzUgMTcuMzUgMTVDMTcuMzUgMTMuNjUgMTYuMjUgMTIuNTUgMTQuOSAxMi41NUMxMy41NCAxMi41NSAxMi40NSAxMy42NSAxMi40NSAxNUMxMi40NSAxNi4zNSAxMy41NCAxNy40NSAxNC45IDE3LjQ1Wk0yMC4xIDE1LjY4TDIxLjU4IDE2Ljg0QzIxLjcxIDE2Ljk1IDIxLjc1IDE3LjEzIDIxLjY2IDE3LjI5TDIwLjI2IDE5LjcxQzIwLjE3IDE5Ljg2IDIwIDE5LjkyIDE5LjgzIDE5Ljg2TDE4LjA5IDE5LjE2QzE3LjczIDE5LjQ0IDE3LjMzIDE5LjY3IDE2LjkxIDE5Ljg1TDE2LjY0IDIxLjdDMTYuNjIgMjEuODcgMTYuNDcgMjIgMTYuMyAyMkgxMy41QzEzLjMyIDIyIDEzLjE4IDIxLjg3IDEzLjE1IDIxLjdMMTIuODkgMTkuODVDMTIuNDYgMTkuNjcgMTIuMDcgMTkuNDQgMTEuNzEgMTkuMTZMOS45NjAwMiAxOS44NkM5LjgxMDAyIDE5LjkyIDkuNjIwMDIgMTkuODYgOS41NDAwMiAxOS43MUw4LjE0MDAyIDE3LjI5QzguMDUwMDIgMTcuMTMgOC4wOTAwMiAxNi45NSA4LjIyMDAyIDE2Ljg0TDkuNzAwMDIgMTUuNjhMOS42NTAwMSAxNUw5LjcwMDAyIDE0LjMxTDguMjIwMDIgMTMuMTZDOC4wOTAwMiAxMy4wNSA4LjA1MDAyIDEyLjg2IDguMTQwMDIgMTIuNzFMOS41NDAwMiAxMC4yOUM5LjYyMDAyIDEwLjEzIDkuODEwMDIgMTAuMDcgOS45NjAwMiAxMC4xM0wxMS43MSAxMC44NEMxMi4wNyAxMC41NiAxMi40NiAxMC4zMiAxMi44OSAxMC4xNUwxMy4xNSA4LjI4OTk4QzEzLjE4IDguMTI5OTggMTMuMzIgNy45OTk5OCAxMy41IDcuOTk5OThIMTYuM0MxNi40NyA3Ljk5OTk4IDE2LjYyIDguMTI5OTggMTYuNjQgOC4yODk5OEwxNi45MSAxMC4xNUMxNy4zMyAxMC4zMiAxNy43MyAxMC41NiAxOC4wOSAxMC44NEwxOS44MyAxMC4xM0MyMCAxMC4wNyAyMC4xNyAxMC4xMyAyMC4yNiAxMC4yOUwyMS42NiAxMi43MUMyMS43NSAxMi44NiAyMS43MSAxMy4wNSAyMS41OCAxMy4xNkwyMC4xIDE0LjMxTDIwLjE1IDE1TDIwLjEgMTUuNjhaIi8+CiAgICA8cGF0aCBkPSJNNy4zMjk2NiA3LjQ0NDU0QzguMDgzMSA3LjAwOTU0IDguMzM5MzIgNi4wNTMzMiA3LjkwNDMyIDUuMjk5ODhDNy40NjkzMiA0LjU0NjQzIDYuNTA4MSA0LjI4MTU2IDUuNzU0NjYgNC43MTY1NkM1LjM5MTc2IDQuOTI2MDggNS4xMjY5NSA1LjI3MTE4IDUuMDE4NDkgNS42NzU5NEM0LjkxMDA0IDYuMDgwNzEgNC45NjY4MiA2LjUxMTk4IDUuMTc2MzQgNi44NzQ4OEM1LjYxMTM0IDcuNjI4MzIgNi41NzYyMiA3Ljg3OTU0IDcuMzI5NjYgNy40NDQ1NFpNOS42NTcxOCA0Ljc5NTkzTDEwLjg2NzIgNC45NTE3OUMxMC45NjI4IDQuOTc3NDEgMTEuMDQwMiA1LjA3MTMzIDExLjAzODIgNS4xODc5M0wxMS4wMzg4IDYuOTg4OTNDMTEuMDQ1NSA3LjEwMDU0IDEwLjk2MTYgNy4xOTUxOCAxMC44NTUgNy4yMTA1NEw5LjY2MDAxIDcuMzgwODNMOS4yMzkxNSA4LjEzMTg4TDkuNjY5NjEgOS4yNTc0NUM5LjcwNzI5IDkuMzYyNzEgOS42NjkzNCA5LjQ3Njk5IDkuNTc0MDggOS41MzE5OUw4LjAxNTIzIDEwLjQzMkM3LjkxMTMxIDEwLjQ5MiA3Ljc5MzM3IDEwLjQ2NzcgNy43MjEwNSAxMC4zODI0TDYuOTg3NDggOS40MzE4OEw2LjEwOTMxIDkuNDMwODNMNS4zNDcwNCAxMC4zOTA1QzUuMjg5MDkgMTAuNDcwMiA1LjE3MzgzIDEwLjQ5MDUgNS4wNzE4NyAxMC40MzM5TDMuNTEyNDUgOS41MzI5M0MzLjQxMDQ5IDkuNDc2MzMgMy4zNzY0NyA5LjM1NzQxIDMuNDEwNzUgOS4yNTY3OUwzLjg2MzQ3IDguMTQwOTNMMy42MTc0OSA3Ljc3NDg4TDMuNDIzNDcgNy4zNzg4M0wyLjIzMDc1IDcuMjEyOTdDMi4xMjY0NyA3LjE5MjM1IDIuMDQwNDkgNy4xMDM0MiAyLjA0MjQ1IDYuOTg2ODJMMi4wNDE4NyA1LjE4NTgyQzIuMDQzODMgNS4wNjkyMiAyLjExOTA5IDQuOTc5NTggMi4yMTcwNCA0Ljk2OTIyTDMuNDIwNjUgNC43OTM5M0wzLjg2NzQ5IDQuMDI3ODhMMy40MTEwNSAyLjkxNzMxQzMuMzczMzcgMi44MTIwNCAzLjQxMTMxIDIuNjk3NzYgMy41MTUyMyAyLjYzNzc2TDUuMDc0MDggMS43Mzc3NkM1LjE2OTM0IDEuNjgyNzYgNS4yODcyOSAxLjcwNzA0IDUuMzU5NjEgMS43OTIzMUw2LjExOTE1IDIuNzI3ODhMNi45ODAwMSAyLjczODkzTDcuNzI0OTYgMS43ODkyMkM3Ljc5MTU2IDEuNzA0NTggNy45MTU0OCAxLjY3OTIyIDguMDA4NzkgMS43NDA4Mkw5LjU2ODIxIDIuNjQxODJDOS42NzAxNyAyLjY5ODQyIDkuNzEyODUgMi44MTIzNCA5LjY4NzIzIDIuOTA3OTdMOS4yMTcxOCA0LjAzMzgzTDkuNDYzMTYgNC4zOTk4OEw5LjY1NzE4IDQuNzk1OTNaIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down-empty-thin: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iOS45LDEzLjYgMy42LDcuNCA0LjQsNi42IDkuOSwxMi4yIDE1LjQsNi43IDE2LjEsNy40ICIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down-empty: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik01LjIsNS45TDksOS43bDMuOC0zLjhsMS4yLDEuMmwtNC45LDVsLTQuOS01TDUuMiw1Ljl6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik01LjIsNy41TDksMTEuMmwzLjgtMy44SDUuMnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-caret-left: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwYXRoIGQ9Ik0xMC44LDEyLjhMNy4xLDlsMy44LTMuOGwwLDcuNkgxMC44eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-caret-right: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik03LjIsNS4yTDEwLjksOWwtMy44LDMuOFY1LjJINy4yeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-caret-up-empty-thin: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iMTUuNCwxMy4zIDkuOSw3LjcgNC40LDEzLjIgMy42LDEyLjUgOS45LDYuMyAxNi4xLDEyLjYgIi8+Cgk8L2c+Cjwvc3ZnPgo=);
  --jp-icon-caret-up: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwYXRoIGQ9Ik01LjIsMTAuNUw5LDYuOGwzLjgsMy44SDUuMnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-case-sensitive: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0MTQxNDEiPgogICAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiAgPC9nPgogIDxnIGNsYXNzPSJqcC1pY29uLWFjY2VudDIiIGZpbGw9IiNGRkYiPgogICAgPHBhdGggZD0iTTcuNiw4aDAuOWwzLjUsOGgtMS4xTDEwLDE0SDZsLTAuOSwySDRMNy42LDh6IE04LDkuMUw2LjQsMTNoMy4yTDgsOS4xeiIvPgogICAgPHBhdGggZD0iTTE2LjYsOS44Yy0wLjIsMC4xLTAuNCwwLjEtMC43LDAuMWMtMC4yLDAtMC40LTAuMS0wLjYtMC4yYy0wLjEtMC4xLTAuMi0wLjQtMC4yLTAuNyBjLTAuMywwLjMtMC42LDAuNS0wLjksMC43Yy0wLjMsMC4xLTAuNywwLjItMS4xLDAuMmMtMC4zLDAtMC41LDAtMC43LTAuMWMtMC4yLTAuMS0wLjQtMC4yLTAuNi0wLjNjLTAuMi0wLjEtMC4zLTAuMy0wLjQtMC41IGMtMC4xLTAuMi0wLjEtMC40LTAuMS0wLjdjMC0wLjMsMC4xLTAuNiwwLjItMC44YzAuMS0wLjIsMC4zLTAuNCwwLjQtMC41QzEyLDcsMTIuMiw2LjksMTIuNSw2LjhjMC4yLTAuMSwwLjUtMC4xLDAuNy0wLjIgYzAuMy0wLjEsMC41LTAuMSwwLjctMC4xYzAuMiwwLDAuNC0wLjEsMC42LTAuMWMwLjIsMCwwLjMtMC4xLDAuNC0wLjJjMC4xLTAuMSwwLjItMC4yLDAuMi0wLjRjMC0xLTEuMS0xLTEuMy0xIGMtMC40LDAtMS40LDAtMS40LDEuMmgtMC45YzAtMC40LDAuMS0wLjcsMC4yLTFjMC4xLTAuMiwwLjMtMC40LDAuNS0wLjZjMC4yLTAuMiwwLjUtMC4zLDAuOC0wLjNDMTMuMyw0LDEzLjYsNCwxMy45LDQgYzAuMywwLDAuNSwwLDAuOCwwLjFjMC4zLDAsMC41LDAuMSwwLjcsMC4yYzAuMiwwLjEsMC40LDAuMywwLjUsMC41QzE2LDUsMTYsNS4yLDE2LDUuNnYyLjljMCwwLjIsMCwwLjQsMCwwLjUgYzAsMC4xLDAuMSwwLjIsMC4zLDAuMmMwLjEsMCwwLjIsMCwwLjMsMFY5Ljh6IE0xNS4yLDYuOWMtMS4yLDAuNi0zLjEsMC4yLTMuMSwxLjRjMCwxLjQsMy4xLDEsMy4xLTAuNVY2Ljl6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-check: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTkgMTYuMTdMNC44MyAxMmwtMS40MiAxLjQxTDkgMTkgMjEgN2wtMS40MS0xLjQxeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-circle-empty: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyIDJDNi40NyAyIDIgNi40NyAyIDEyczQuNDcgMTAgMTAgMTAgMTAtNC40NyAxMC0xMFMxNy41MyAyIDEyIDJ6bTAgMThjLTQuNDEgMC04LTMuNTktOC04czMuNTktOCA4LTggOCAzLjU5IDggOC0zLjU5IDgtOCA4eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-circle: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPGNpcmNsZSBjeD0iOSIgY3k9IjkiIHI9IjgiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-clear: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8bWFzayBpZD0iZG9udXRIb2xlIj4KICAgIDxyZWN0IHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgZmlsbD0id2hpdGUiIC8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSI4IiBmaWxsPSJibGFjayIvPgogIDwvbWFzaz4KCiAgPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxyZWN0IGhlaWdodD0iMTgiIHdpZHRoPSIyIiB4PSIxMSIgeT0iMyIgdHJhbnNmb3JtPSJyb3RhdGUoMzE1LCAxMiwgMTIpIi8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIxMCIgbWFzaz0idXJsKCNkb251dEhvbGUpIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-close: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1ub25lIGpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIGpwLWljb24zLWhvdmVyIiBmaWxsPSJub25lIj4KICAgIDxjaXJjbGUgY3g9IjEyIiBjeT0iMTIiIHI9IjExIi8+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIGpwLWljb24tYWNjZW50Mi1ob3ZlciIgZmlsbD0iIzYxNjE2MSI+CiAgICA8cGF0aCBkPSJNMTkgNi40MUwxNy41OSA1IDEyIDEwLjU5IDYuNDEgNSA1IDYuNDEgMTAuNTkgMTIgNSAxNy41OSA2LjQxIDE5IDEyIDEzLjQxIDE3LjU5IDE5IDE5IDE3LjU5IDEzLjQxIDEyeiIvPgogIDwvZz4KCiAgPGcgY2xhc3M9ImpwLWljb24tbm9uZSBqcC1pY29uLWJ1c3kiIGZpbGw9Im5vbmUiPgogICAgPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNyIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-console: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwMCAyMDAiPgogIDxnIGNsYXNzPSJqcC1pY29uLWJyYW5kMSBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiMwMjg4RDEiPgogICAgPHBhdGggZD0iTTIwIDE5LjhoMTYwdjE1OS45SDIweiIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNmZmYiPgogICAgPHBhdGggZD0iTTEwNSAxMjcuM2g0MHYxMi44aC00MHpNNTEuMSA3N0w3NCA5OS45bC0yMy4zIDIzLjMgMTAuNSAxMC41IDIzLjMtMjMuM0w5NSA5OS45IDg0LjUgODkuNCA2MS42IDY2LjV6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-copy: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTExLjksMUgzLjJDMi40LDEsMS43LDEuNywxLjcsMi41djEwLjJoMS41VjIuNWg4LjdWMXogTTE0LjEsMy45aC04Yy0wLjgsMC0xLjUsMC43LTEuNSwxLjV2MTAuMmMwLDAuOCwwLjcsMS41LDEuNSwxLjVoOCBjMC44LDAsMS41LTAuNywxLjUtMS41VjUuNEMxNS41LDQuNiwxNC45LDMuOSwxNC4xLDMuOXogTTE0LjEsMTUuNWgtOFY1LjRoOFYxNS41eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-cut: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTkuNjQgNy42NGMuMjMtLjUuMzYtMS4wNS4zNi0xLjY0IDAtMi4yMS0xLjc5LTQtNC00UzIgMy43OSAyIDZzMS43OSA0IDQgNGMuNTkgMCAxLjE0LS4xMyAxLjY0LS4zNkwxMCAxMmwtMi4zNiAyLjM2QzcuMTQgMTQuMTMgNi41OSAxNCA2IDE0Yy0yLjIxIDAtNCAxLjc5LTQgNHMxLjc5IDQgNCA0IDQtMS43OSA0LTRjMC0uNTktLjEzLTEuMTQtLjM2LTEuNjRMMTIgMTRsNyA3aDN2LTFMOS42NCA3LjY0ek02IDhjLTEuMSAwLTItLjg5LTItMnMuOS0yIDItMiAyIC44OSAyIDItLjkgMi0yIDJ6bTAgMTJjLTEuMSAwLTItLjg5LTItMnMuOS0yIDItMiAyIC44OSAyIDItLjkgMi0yIDJ6bTYtNy41Yy0uMjggMC0uNS0uMjItLjUtLjVzLjIyLS41LjUtLjUuNS4yMi41LjUtLjIyLjUtLjUuNXpNMTkgM2wtNiA2IDIgMiA3LTdWM3oiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-download: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE5IDloLTRWM0g5djZINWw3IDcgNy03ek01IDE4djJoMTR2LTJINXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-edit: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTMgMTcuMjVWMjFoMy43NUwxNy44MSA5Ljk0bC0zLjc1LTMuNzVMMyAxNy4yNXpNMjAuNzEgNy4wNGMuMzktLjM5LjM5LTEuMDIgMC0xLjQxbC0yLjM0LTIuMzRjLS4zOS0uMzktMS4wMi0uMzktMS40MSAwbC0xLjgzIDEuODMgMy43NSAzLjc1IDEuODMtMS44M3oiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-ellipses: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPGNpcmNsZSBjeD0iNSIgY3k9IjEyIiByPSIyIi8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIyIi8+CiAgICA8Y2lyY2xlIGN4PSIxOSIgY3k9IjEyIiByPSIyIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-extension: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwLjUgMTFIMTlWN2MwLTEuMS0uOS0yLTItMmgtNFYzLjVDMTMgMi4xMiAxMS44OCAxIDEwLjUgMVM4IDIuMTIgOCAzLjVWNUg0Yy0xLjEgMC0xLjk5LjktMS45OSAydjMuOEgzLjVjMS40OSAwIDIuNyAxLjIxIDIuNyAyLjdzLTEuMjEgMi43LTIuNyAyLjdIMlYyMGMwIDEuMS45IDIgMiAyaDMuOHYtMS41YzAtMS40OSAxLjIxLTIuNyAyLjctMi43IDEuNDkgMCAyLjcgMS4yMSAyLjcgMi43VjIySDE3YzEuMSAwIDItLjkgMi0ydi00aDEuNWMxLjM4IDAgMi41LTEuMTIgMi41LTIuNVMyMS44OCAxMSAyMC41IDExeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-fast-forward: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTQgMThsOC41LTZMNCA2djEyem05LTEydjEybDguNS02TDEzIDZ6Ii8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-file-upload: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTkgMTZoNnYtNmg0bC03LTctNyA3aDR6bS00IDJoMTR2Mkg1eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-file: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkuMyA4LjJsLTUuNS01LjVjLS4zLS4zLS43LS41LTEuMi0uNUgzLjljLS44LjEtMS42LjktMS42IDEuOHYxNC4xYzAgLjkuNyAxLjYgMS42IDEuNmgxNC4yYy45IDAgMS42LS43IDEuNi0xLjZWOS40Yy4xLS41LS4xLS45LS40LTEuMnptLTUuOC0zLjNsMy40IDMuNmgtMy40VjQuOXptMy45IDEyLjdINC43Yy0uMSAwLS4yIDAtLjItLjJWNC43YzAtLjIuMS0uMy4yLS4zaDcuMnY0LjRzMCAuOC4zIDEuMWMuMy4zIDEuMS4zIDEuMS4zaDQuM3Y3LjJzLS4xLjItLjIuMnoiLz4KPC9zdmc+Cg==);
  --jp-icon-filter-list: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEwIDE4aDR2LTJoLTR2MnpNMyA2djJoMThWNkgzem0zIDdoMTJ2LTJINnYyeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-folder: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTAgNEg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMThjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY4YzAtMS4xLS45LTItMi0yaC04bC0yLTJ6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-html5: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUxMiA1MTIiPgogIDxwYXRoIGNsYXNzPSJqcC1pY29uMCBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiMwMDAiIGQ9Ik0xMDguNCAwaDIzdjIyLjhoMjEuMlYwaDIzdjY5aC0yM1Y0NmgtMjF2MjNoLTIzLjJNMjA2IDIzaC0yMC4zVjBoNjMuN3YyM0gyMjl2NDZoLTIzbTUzLjUtNjloMjQuMWwxNC44IDI0LjNMMzEzLjIgMGgyNC4xdjY5aC0yM1YzNC44bC0xNi4xIDI0LjgtMTYuMS0yNC44VjY5aC0yMi42bTg5LjItNjloMjN2NDYuMmgzMi42VjY5aC01NS42Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI2U0NGQyNiIgZD0iTTEwNy42IDQ3MWwtMzMtMzcwLjRoMzYyLjhsLTMzIDM3MC4yTDI1NS43IDUxMiIvPgogIDxwYXRoIGNsYXNzPSJqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNmMTY1MjkiIGQ9Ik0yNTYgNDgwLjVWMTMxaDE0OC4zTDM3NiA0NDciLz4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNlYmViZWIiIGQ9Ik0xNDIgMTc2LjNoMTE0djQ1LjRoLTY0LjJsNC4yIDQ2LjVoNjB2NDUuM0gxNTQuNG0yIDIyLjhIMjAybDMuMiAzNi4zIDUwLjggMTMuNnY0Ny40bC05My4yLTI2Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIiBmaWxsPSIjZmZmIiBkPSJNMzY5LjYgMTc2LjNIMjU1Ljh2NDUuNGgxMDkuNm0tNC4xIDQ2LjVIMjU1Ljh2NDUuNGg1NmwtNS4zIDU5LTUwLjcgMTMuNnY0Ny4ybDkzLTI1LjgiLz4KPC9zdmc+Cg==);
  --jp-icon-image: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1icmFuZDQganAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNGRkYiIGQ9Ik0yLjIgMi4yaDE3LjV2MTcuNUgyLjJ6Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzNGNTFCNSIgZD0iTTIuMiAyLjJ2MTcuNWgxNy41bC4xLTE3LjVIMi4yem0xMi4xIDIuMmMxLjIgMCAyLjIgMSAyLjIgMi4ycy0xIDIuMi0yLjIgMi4yLTIuMi0xLTIuMi0yLjIgMS0yLjIgMi4yLTIuMnpNNC40IDE3LjZsMy4zLTguOCAzLjMgNi42IDIuMi0zLjIgNC40IDUuNEg0LjR6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-inspector: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMjAgNEg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMThjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY2YzAtMS4xLS45LTItMi0yem0tNSAxNEg0di00aDExdjR6bTAtNUg0VjloMTF2NHptNSA1aC00VjloNHY5eiIvPgo8L3N2Zz4K);
  --jp-icon-json: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMSBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNGOUE4MjUiPgogICAgPHBhdGggZD0iTTIwLjIgMTEuOGMtMS42IDAtMS43LjUtMS43IDEgMCAuNC4xLjkuMSAxLjMuMS41LjEuOS4xIDEuMyAwIDEuNy0xLjQgMi4zLTMuNSAyLjNoLS45di0xLjloLjVjMS4xIDAgMS40IDAgMS40LS44IDAtLjMgMC0uNi0uMS0xIDAtLjQtLjEtLjgtLjEtMS4yIDAtMS4zIDAtMS44IDEuMy0yLTEuMy0uMi0xLjMtLjctMS4zLTIgMC0uNC4xLS44LjEtMS4yLjEtLjQuMS0uNy4xLTEgMC0uOC0uNC0uNy0xLjQtLjhoLS41VjQuMWguOWMyLjIgMCAzLjUuNyAzLjUgMi4zIDAgLjQtLjEuOS0uMSAxLjMtLjEuNS0uMS45LS4xIDEuMyAwIC41LjIgMSAxLjcgMXYxLjh6TTEuOCAxMC4xYzEuNiAwIDEuNy0uNSAxLjctMSAwLS40LS4xLS45LS4xLTEuMy0uMS0uNS0uMS0uOS0uMS0xLjMgMC0xLjYgMS40LTIuMyAzLjUtMi4zaC45djEuOWgtLjVjLTEgMC0xLjQgMC0xLjQuOCAwIC4zIDAgLjYuMSAxIDAgLjIuMS42LjEgMSAwIDEuMyAwIDEuOC0xLjMgMkM2IDExLjIgNiAxMS43IDYgMTNjMCAuNC0uMS44LS4xIDEuMi0uMS4zLS4xLjctLjEgMSAwIC44LjMuOCAxLjQuOGguNXYxLjloLS45Yy0yLjEgMC0zLjUtLjYtMy41LTIuMyAwLS40LjEtLjkuMS0xLjMuMS0uNS4xLS45LjEtMS4zIDAtLjUtLjItMS0xLjctMXYtMS45eiIvPgogICAgPGNpcmNsZSBjeD0iMTEiIGN5PSIxMy44IiByPSIyLjEiLz4KICAgIDxjaXJjbGUgY3g9IjExIiBjeT0iOC4yIiByPSIyLjEiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-jupyter-favicon: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTUyIiBoZWlnaHQ9IjE2NSIgdmlld0JveD0iMCAwIDE1MiAxNjUiIHZlcnNpb249IjEuMSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCIgZmlsbD0iI0YzNzcyNiI+CiAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjA3ODk0NywgMTEwLjU4MjkyNykiIGQ9Ik03NS45NDIyODQyLDI5LjU4MDQ1NjEgQzQzLjMwMjM5NDcsMjkuNTgwNDU2MSAxNC43OTY3ODMyLDE3LjY1MzQ2MzQgMCwwIEM1LjUxMDgzMjExLDE1Ljg0MDY4MjkgMTUuNzgxNTM4OSwyOS41NjY3NzMyIDI5LjM5MDQ5NDcsMzkuMjc4NDE3MSBDNDIuOTk5Nyw0OC45ODk4NTM3IDU5LjI3MzcsNTQuMjA2NzgwNSA3NS45NjA1Nzg5LDU0LjIwNjc4MDUgQzkyLjY0NzQ1NzksNTQuMjA2NzgwNSAxMDguOTIxNDU4LDQ4Ljk4OTg1MzcgMTIyLjUzMDY2MywzOS4yNzg0MTcxIEMxMzYuMTM5NDUzLDI5LjU2Njc3MzIgMTQ2LjQxMDI4NCwxNS44NDA2ODI5IDE1MS45MjExNTgsMCBDMTM3LjA4Nzg2OCwxNy42NTM0NjM0IDEwOC41ODI1ODksMjkuNTgwNDU2MSA3NS45NDIyODQyLDI5LjU4MDQ1NjEgTDc1Ljk0MjI4NDIsMjkuNTgwNDU2MSBaIiAvPgogICAgPHBhdGggdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC4wMzczNjgsIDAuNzA0ODc4KSIgZD0iTTc1Ljk3ODQ1NzksMjQuNjI2NDA3MyBDMTA4LjYxODc2MywyNC42MjY0MDczIDEzNy4xMjQ0NTgsMzYuNTUzNDQxNSAxNTEuOTIxMTU4LDU0LjIwNjc4MDUgQzE0Ni40MTAyODQsMzguMzY2MjIyIDEzNi4xMzk0NTMsMjQuNjQwMTMxNyAxMjIuNTMwNjYzLDE0LjkyODQ4NzggQzEwOC45MjE0NTgsNS4yMTY4NDM5IDkyLjY0NzQ1NzksMCA3NS45NjA1Nzg5LDAgQzU5LjI3MzcsMCA0Mi45OTk3LDUuMjE2ODQzOSAyOS4zOTA0OTQ3LDE0LjkyODQ4NzggQzE1Ljc4MTUzODksMjQuNjQwMTMxNyA1LjUxMDgzMjExLDM4LjM2NjIyMiAwLDU0LjIwNjc4MDUgQzE0LjgzMzA4MTYsMzYuNTg5OTI5MyA0My4zMzg1Njg0LDI0LjYyNjQwNzMgNzUuOTc4NDU3OSwyNC42MjY0MDczIEw3NS45Nzg0NTc5LDI0LjYyNjQwNzMgWiIgLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-jupyter: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMzkiIGhlaWdodD0iNTEiIHZpZXdCb3g9IjAgMCAzOSA1MSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtMTYzOCAtMjI4MSkiPgogICAgPGcgY2xhc3M9ImpwLWljb24td2FybjAiIGZpbGw9IiNGMzc3MjYiPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM5Ljc0IDIzMTEuOTgpIiBkPSJNIDE4LjI2NDYgNy4xMzQxMUMgMTAuNDE0NSA3LjEzNDExIDMuNTU4NzIgNC4yNTc2IDAgMEMgMS4zMjUzOSAzLjgyMDQgMy43OTU1NiA3LjEzMDgxIDcuMDY4NiA5LjQ3MzAzQyAxMC4zNDE3IDExLjgxNTIgMTQuMjU1NyAxMy4wNzM0IDE4LjI2OSAxMy4wNzM0QyAyMi4yODIzIDEzLjA3MzQgMjYuMTk2MyAxMS44MTUyIDI5LjQ2OTQgOS40NzMwM0MgMzIuNzQyNCA3LjEzMDgxIDM1LjIxMjYgMy44MjA0IDM2LjUzOCAwQyAzMi45NzA1IDQuMjU3NiAyNi4xMTQ4IDcuMTM0MTEgMTguMjY0NiA3LjEzNDExWiIvPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM5LjczIDIyODUuNDgpIiBkPSJNIDE4LjI3MzMgNS45MzkzMUMgMjYuMTIzNSA1LjkzOTMxIDMyLjk3OTMgOC44MTU4MyAzNi41MzggMTMuMDczNEMgMzUuMjEyNiA5LjI1MzAzIDMyLjc0MjQgNS45NDI2MiAyOS40Njk0IDMuNjAwNEMgMjYuMTk2MyAxLjI1ODE4IDIyLjI4MjMgMCAxOC4yNjkgMEMgMTQuMjU1NyAwIDEwLjM0MTcgMS4yNTgxOCA3LjA2ODYgMy42MDA0QyAzLjc5NTU2IDUuOTQyNjIgMS4zMjUzOSA5LjI1MzAzIDAgMTMuMDczNEMgMy41Njc0NSA4LjgyNDYzIDEwLjQyMzIgNS45MzkzMSAxOC4yNzMzIDUuOTM5MzFaIi8+CiAgICA8L2c+CiAgICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjY5LjMgMjI4MS4zMSkiIGQ9Ik0gNS44OTM1MyAyLjg0NEMgNS45MTg4OSAzLjQzMTY1IDUuNzcwODUgNC4wMTM2NyA1LjQ2ODE1IDQuNTE2NDVDIDUuMTY1NDUgNS4wMTkyMiA0LjcyMTY4IDUuNDIwMTUgNC4xOTI5OSA1LjY2ODUxQyAzLjY2NDMgNS45MTY4OCAzLjA3NDQ0IDYuMDAxNTEgMi40OTgwNSA1LjkxMTcxQyAxLjkyMTY2IDUuODIxOSAxLjM4NDYzIDUuNTYxNyAwLjk1NDg5OCA1LjE2NDAxQyAwLjUyNTE3IDQuNzY2MzMgMC4yMjIwNTYgNC4yNDkwMyAwLjA4MzkwMzcgMy42Nzc1N0MgLTAuMDU0MjQ4MyAzLjEwNjExIC0wLjAyMTIzIDIuNTA2MTcgMC4xNzg3ODEgMS45NTM2NEMgMC4zNzg3OTMgMS40MDExIDAuNzM2ODA5IDAuOTIwODE3IDEuMjA3NTQgMC41NzM1MzhDIDEuNjc4MjYgMC4yMjYyNTkgMi4yNDA1NSAwLjAyNzU5MTkgMi44MjMyNiAwLjAwMjY3MjI5QyAzLjYwMzg5IC0wLjAzMDcxMTUgNC4zNjU3MyAwLjI0OTc4OSA0Ljk0MTQyIDAuNzgyNTUxQyA1LjUxNzExIDEuMzE1MzEgNS44NTk1NiAyLjA1Njc2IDUuODkzNTMgMi44NDRaIi8+CiAgICAgIDxwYXRoIHRyYW5zZm9ybT0idHJhbnNsYXRlKDE2MzkuOCAyMzIzLjgxKSIgZD0iTSA3LjQyNzg5IDMuNTgzMzhDIDcuNDYwMDggNC4zMjQzIDcuMjczNTUgNS4wNTgxOSA2Ljg5MTkzIDUuNjkyMTNDIDYuNTEwMzEgNi4zMjYwNyA1Ljk1MDc1IDYuODMxNTYgNS4yODQxMSA3LjE0NDZDIDQuNjE3NDcgNy40NTc2MyAzLjg3MzcxIDcuNTY0MTQgMy4xNDcwMiA3LjQ1MDYzQyAyLjQyMDMyIDcuMzM3MTIgMS43NDMzNiA3LjAwODcgMS4yMDE4NCA2LjUwNjk1QyAwLjY2MDMyOCA2LjAwNTIgMC4yNzg2MSA1LjM1MjY4IDAuMTA1MDE3IDQuNjMyMDJDIC0wLjA2ODU3NTcgMy45MTEzNSAtMC4wMjYyMzYxIDMuMTU0OTQgMC4yMjY2NzUgMi40NTg1NkMgMC40Nzk1ODcgMS43NjIxNyAwLjkzMTY5NyAxLjE1NzEzIDEuNTI1NzYgMC43MjAwMzNDIDIuMTE5ODMgMC4yODI5MzUgMi44MjkxNCAwLjAzMzQzOTUgMy41NjM4OSAwLjAwMzEzMzQ0QyA0LjU0NjY3IC0wLjAzNzQwMzMgNS41MDUyOSAwLjMxNjcwNiA2LjIyOTYxIDAuOTg3ODM1QyA2Ljk1MzkzIDEuNjU4OTYgNy4zODQ4NCAyLjU5MjM1IDcuNDI3ODkgMy41ODMzOEwgNy40Mjc4OSAzLjU4MzM4WiIvPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM4LjM2IDIyODYuMDYpIiBkPSJNIDIuMjc0NzEgNC4zOTYyOUMgMS44NDM2MyA0LjQxNTA4IDEuNDE2NzEgNC4zMDQ0NSAxLjA0Nzk5IDQuMDc4NDNDIDAuNjc5MjY4IDMuODUyNCAwLjM4NTMyOCAzLjUyMTE0IDAuMjAzMzcxIDMuMTI2NTZDIDAuMDIxNDEzNiAyLjczMTk4IC0wLjA0MDM3OTggMi4yOTE4MyAwLjAyNTgxMTYgMS44NjE4MUMgMC4wOTIwMDMxIDEuNDMxOCAwLjI4MzIwNCAxLjAzMTI2IDAuNTc1MjEzIDAuNzEwODgzQyAwLjg2NzIyMiAwLjM5MDUxIDEuMjQ2OTEgMC4xNjQ3MDggMS42NjYyMiAwLjA2MjA1OTJDIDIuMDg1NTMgLTAuMDQwNTg5NyAyLjUyNTYxIC0wLjAxNTQ3MTQgMi45MzA3NiAwLjEzNDIzNUMgMy4zMzU5MSAwLjI4Mzk0MSAzLjY4NzkyIDAuNTUxNTA1IDMuOTQyMjIgMC45MDMwNkMgNC4xOTY1MiAxLjI1NDYyIDQuMzQxNjkgMS42NzQzNiA0LjM1OTM1IDIuMTA5MTZDIDQuMzgyOTkgMi42OTEwNyA0LjE3Njc4IDMuMjU4NjkgMy43ODU5NyAzLjY4NzQ2QyAzLjM5NTE2IDQuMTE2MjQgMi44NTE2NiA0LjM3MTE2IDIuMjc0NzEgNC4zOTYyOUwgMi4yNzQ3MSA0LjM5NjI5WiIvPgogICAgPC9nPgogIDwvZz4+Cjwvc3ZnPgo=);
  --jp-icon-jupyterlab-wordmark: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMDAiIHZpZXdCb3g9IjAgMCAxODYwLjggNDc1Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0RTRFNEUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDQ4MC4xMzY0MDEsIDY0LjI3MTQ5MykiPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC4wMDAwMDAsIDU4Ljg3NTU2NikiPgogICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjA4NzYwMywgMC4xNDAyOTQpIj4KICAgICAgICA8cGF0aCBkPSJNLTQyNi45LDE2OS44YzAsNDguNy0zLjcsNjQuNy0xMy42LDc2LjRjLTEwLjgsMTAtMjUsMTUuNS0zOS43LDE1LjVsMy43LDI5IGMyMi44LDAuMyw0NC44LTcuOSw2MS45LTIzLjFjMTcuOC0xOC41LDI0LTQ0LjEsMjQtODMuM1YwSC00Mjd2MTcwLjFMLTQyNi45LDE2OS44TC00MjYuOSwxNjkuOHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMTU1LjA0NTI5NiwgNTYuODM3MTA0KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEuNTYyNDUzLCAxLjc5OTg0MikiPgogICAgICAgIDxwYXRoIGQ9Ik0tMzEyLDE0OGMwLDIxLDAsMzkuNSwxLjcsNTUuNGgtMzEuOGwtMi4xLTMzLjNoLTAuOGMtNi43LDExLjYtMTYuNCwyMS4zLTI4LDI3LjkgYy0xMS42LDYuNi0yNC44LDEwLTM4LjIsOS44Yy0zMS40LDAtNjktMTcuNy02OS04OVYwaDM2LjR2MTEyLjdjMCwzOC43LDExLjYsNjQuNyw0NC42LDY0LjdjMTAuMy0wLjIsMjAuNC0zLjUsMjguOS05LjQgYzguNS01LjksMTUuMS0xNC4zLDE4LjktMjMuOWMyLjItNi4xLDMuMy0xMi41LDMuMy0xOC45VjAuMmgzNi40VjE0OEgtMzEyTC0zMTIsMTQ4eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgzOTAuMDEzMzIyLCA1My40Nzk2MzgpIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMS43MDY0NTgsIDAuMjMxNDI1KSI+CiAgICAgICAgPHBhdGggZD0iTS00NzguNiw3MS40YzAtMjYtMC44LTQ3LTEuNy02Ni43aDMyLjdsMS43LDM0LjhoMC44YzcuMS0xMi41LDE3LjUtMjIuOCwzMC4xLTI5LjcgYzEyLjUtNywyNi43LTEwLjMsNDEtOS44YzQ4LjMsMCw4NC43LDQxLjcsODQuNywxMDMuM2MwLDczLjEtNDMuNywxMDkuMi05MSwxMDkuMmMtMTIuMSwwLjUtMjQuMi0yLjItMzUtNy44IGMtMTAuOC01LjYtMTkuOS0xMy45LTI2LjYtMjQuMmgtMC44VjI5MWgtMzZ2LTIyMEwtNDc4LjYsNzEuNEwtNDc4LjYsNzEuNHogTS00NDIuNiwxMjUuNmMwLjEsNS4xLDAuNiwxMC4xLDEuNywxNS4xIGMzLDEyLjMsOS45LDIzLjMsMTkuOCwzMS4xYzkuOSw3LjgsMjIuMSwxMi4xLDM0LjcsMTIuMWMzOC41LDAsNjAuNy0zMS45LDYwLjctNzguNWMwLTQwLjctMjEuMS03NS42LTU5LjUtNzUuNiBjLTEyLjksMC40LTI1LjMsNS4xLTM1LjMsMTMuNGMtOS45LDguMy0xNi45LDE5LjctMTkuNiwzMi40Yy0xLjUsNC45LTIuMywxMC0yLjUsMTUuMVYxMjUuNkwtNDQyLjYsMTI1LjZMLTQ0Mi42LDEyNS42eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSg2MDYuNzQwNzI2LCA1Ni44MzcxMDQpIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC43NTEyMjYsIDEuOTg5Mjk5KSI+CiAgICAgICAgPHBhdGggZD0iTS00NDAuOCwwbDQzLjcsMTIwLjFjNC41LDEzLjQsOS41LDI5LjQsMTIuOCw0MS43aDAuOGMzLjctMTIuMiw3LjktMjcuNywxMi44LTQyLjQgbDM5LjctMTE5LjJoMzguNUwtMzQ2LjksMTQ1Yy0yNiw2OS43LTQzLjcsMTA1LjQtNjguNiwxMjcuMmMtMTIuNSwxMS43LTI3LjksMjAtNDQuNiwyMy45bC05LjEtMzEuMSBjMTEuNy0zLjksMjIuNS0xMC4xLDMxLjgtMTguMWMxMy4yLTExLjEsMjMuNy0yNS4yLDMwLjYtNDEuMmMxLjUtMi44LDIuNS01LjcsMi45LTguOGMtMC4zLTMuMy0xLjItNi42LTIuNS05LjdMLTQ4MC4yLDAuMSBoMzkuN0wtNDQwLjgsMEwtNDQwLjgsMHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoODIyLjc0ODEwNCwgMC4wMDAwMDApIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMS40NjQwNTAsIDAuMzc4OTE0KSI+CiAgICAgICAgPHBhdGggZD0iTS00MTMuNywwdjU4LjNoNTJ2MjguMmgtNTJWMTk2YzAsMjUsNywzOS41LDI3LjMsMzkuNWM3LjEsMC4xLDE0LjItMC43LDIxLjEtMi41IGwxLjcsMjcuN2MtMTAuMywzLjctMjEuMyw1LjQtMzIuMiw1Yy03LjMsMC40LTE0LjYtMC43LTIxLjMtMy40Yy02LjgtMi43LTEyLjktNi44LTE3LjktMTIuMWMtMTAuMy0xMC45LTE0LjEtMjktMTQuMS01Mi45IFY4Ni41aC0zMVY1OC4zaDMxVjkuNkwtNDEzLjcsMEwtNDEzLjcsMHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOTc0LjQzMzI4NiwgNTMuNDc5NjM4KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDAuOTkwMDM0LCAwLjYxMDMzOSkiPgogICAgICAgIDxwYXRoIGQ9Ik0tNDQ1LjgsMTEzYzAuOCw1MCwzMi4yLDcwLjYsNjguNiw3MC42YzE5LDAuNiwzNy45LTMsNTUuMy0xMC41bDYuMiwyNi40IGMtMjAuOSw4LjktNDMuNSwxMy4xLTY2LjIsMTIuNmMtNjEuNSwwLTk4LjMtNDEuMi05OC4zLTEwMi41Qy00ODAuMiw0OC4yLTQ0NC43LDAtMzg2LjUsMGM2NS4yLDAsODIuNyw1OC4zLDgyLjcsOTUuNyBjLTAuMSw1LjgtMC41LDExLjUtMS4yLDE3LjJoLTE0MC42SC00NDUuOEwtNDQ1LjgsMTEzeiBNLTMzOS4yLDg2LjZjMC40LTIzLjUtOS41LTYwLjEtNTAuNC02MC4xIGMtMzYuOCwwLTUyLjgsMzQuNC01NS43LDYwLjFILTMzOS4yTC0zMzkuMiw4Ni42TC0zMzkuMiw4Ni42eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxMjAxLjk2MTA1OCwgNTMuNDc5NjM4KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEuMTc5NjQwLCAwLjcwNTA2OCkiPgogICAgICAgIDxwYXRoIGQ9Ik0tNDc4LjYsNjhjMC0yMy45LTAuNC00NC41LTEuNy02My40aDMxLjhsMS4yLDM5LjloMS43YzkuMS0yNy4zLDMxLTQ0LjUsNTUuMy00NC41IGMzLjUtMC4xLDcsMC40LDEwLjMsMS4ydjM0LjhjLTQuMS0wLjktOC4yLTEuMy0xMi40LTEuMmMtMjUuNiwwLTQzLjcsMTkuNy00OC43LDQ3LjRjLTEsNS43LTEuNiwxMS41LTEuNywxNy4ydjEwOC4zaC0zNlY2OCBMLTQ3OC42LDY4eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCIgZmlsbD0iI0YzNzcyNiI+CiAgICA8cGF0aCBkPSJNMTM1Mi4zLDMyNi4yaDM3VjI4aC0zN1YzMjYuMnogTTE2MDQuOCwzMjYuMmMtMi41LTEzLjktMy40LTMxLjEtMy40LTQ4Ljd2LTc2IGMwLTQwLjctMTUuMS04My4xLTc3LjMtODMuMWMtMjUuNiwwLTUwLDcuMS02Ni44LDE4LjFsOC40LDI0LjRjMTQuMy05LjIsMzQtMTUuMSw1My0xNS4xYzQxLjYsMCw0Ni4yLDMwLjIsNDYuMiw0N3Y0LjIgYy03OC42LTAuNC0xMjIuMywyNi41LTEyMi4zLDc1LjZjMCwyOS40LDIxLDU4LjQsNjIuMiw1OC40YzI5LDAsNTAuOS0xNC4zLDYyLjItMzAuMmgxLjNsMi45LDI1LjZIMTYwNC44eiBNMTU2NS43LDI1Ny43IGMwLDMuOC0wLjgsOC0yLjEsMTEuOGMtNS45LDE3LjItMjIuNywzNC00OS4yLDM0Yy0xOC45LDAtMzQuOS0xMS4zLTM0LjktMzUuM2MwLTM5LjUsNDUuOC00Ni42LDg2LjItNDUuOFYyNTcuN3ogTTE2OTguNSwzMjYuMiBsMS43LTMzLjZoMS4zYzE1LjEsMjYuOSwzOC43LDM4LjIsNjguMSwzOC4yYzQ1LjQsMCw5MS4yLTM2LjEsOTEuMi0xMDguOGMwLjQtNjEuNy0zNS4zLTEwMy43LTg1LjctMTAzLjcgYy0zMi44LDAtNTYuMywxNC43LTY5LjMsMzcuNGgtMC44VjI4aC0zNi42djI0NS43YzAsMTguMS0wLjgsMzguNi0xLjcsNTIuNUgxNjk4LjV6IE0xNzA0LjgsMjA4LjJjMC01LjksMS4zLTEwLjksMi4xLTE1LjEgYzcuNi0yOC4xLDMxLjEtNDUuNCw1Ni4zLTQ1LjRjMzkuNSwwLDYwLjUsMzQuOSw2MC41LDc1LjZjMCw0Ni42LTIzLjEsNzguMS02MS44LDc4LjFjLTI2LjksMC00OC4zLTE3LjYtNTUuNS00My4zIGMtMC44LTQuMi0xLjctOC44LTEuNy0xMy40VjIwOC4yeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-kernel: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgZmlsbD0iIzYxNjE2MSIgZD0iTTE1IDlIOXY2aDZWOXptLTIgNGgtMnYtMmgydjJ6bTgtMlY5aC0yVjdjMC0xLjEtLjktMi0yLTJoLTJWM2gtMnYyaC0yVjNIOXYySDdjLTEuMSAwLTIgLjktMiAydjJIM3YyaDJ2MkgzdjJoMnYyYzAgMS4xLjkgMiAyIDJoMnYyaDJ2LTJoMnYyaDJ2LTJoMmMxLjEgMCAyLS45IDItMnYtMmgydi0yaC0ydi0yaDJ6bS00IDZIN1Y3aDEwdjEweiIvPgo8L3N2Zz4K);
  --jp-icon-keyboard: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMjAgNUg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMTdjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY3YzAtMS4xLS45LTItMi0yem0tOSAzaDJ2MmgtMlY4em0wIDNoMnYyaC0ydi0yek04IDhoMnYySDhWOHptMCAzaDJ2Mkg4di0yem0tMSAySDV2LTJoMnYyem0wLTNINVY4aDJ2MnptOSA3SDh2LTJoOHYyem0wLTRoLTJ2LTJoMnYyem0wLTNoLTJWOGgydjJ6bTMgM2gtMnYtMmgydjJ6bTAtM2gtMlY4aDJ2MnoiLz4KPC9zdmc+Cg==);
  --jp-icon-launcher: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkgMTlINVY1aDdWM0g1YTIgMiAwIDAwLTIgMnYxNGEyIDIgMCAwMDIgMmgxNGMxLjEgMCAyLS45IDItMnYtN2gtMnY3ek0xNCAzdjJoMy41OWwtOS44MyA5LjgzIDEuNDEgMS40MUwxOSA2LjQxVjEwaDJWM2gtN3oiLz4KPC9zdmc+Cg==);
  --jp-icon-line-form: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGZpbGw9IndoaXRlIiBkPSJNNS44OCA0LjEyTDEzLjc2IDEybC03Ljg4IDcuODhMOCAyMmwxMC0xMEw4IDJ6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-link: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTMuOSAxMmMwLTEuNzEgMS4zOS0zLjEgMy4xLTMuMWg0VjdIN2MtMi43NiAwLTUgMi4yNC01IDVzMi4yNCA1IDUgNWg0di0xLjlIN2MtMS43MSAwLTMuMS0xLjM5LTMuMS0zLjF6TTggMTNoOHYtMkg4djJ6bTktNmgtNHYxLjloNGMxLjcxIDAgMy4xIDEuMzkgMy4xIDMuMXMtMS4zOSAzLjEtMy4xIDMuMWgtNFYxN2g0YzIuNzYgMCA1LTIuMjQgNS01cy0yLjI0LTUtNS01eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-list: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiIGQ9Ik0xOSA1djE0SDVWNWgxNG0xLjEtMkgzLjljLS41IDAtLjkuNC0uOS45djE2LjJjMCAuNC40LjkuOS45aDE2LjJjLjQgMCAuOS0uNS45LS45VjMuOWMwLS41LS41LS45LS45LS45ek0xMSA3aDZ2MmgtNlY3em0wIDRoNnYyaC02di0yem0wIDRoNnYyaC02ek03IDdoMnYySDd6bTAgNGgydjJIN3ptMCA0aDJ2Mkg3eiIvPgo8L3N2Zz4=);
  --jp-icon-listings-info: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iaXNvLTg4NTktMSI/Pg0KPHN2ZyB2ZXJzaW9uPSIxLjEiIGlkPSJDYXBhXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSIwIDAgNTAuOTc4IDUwLjk3OCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAwIDAgNTAuOTc4IDUwLjk3ODsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPGc+DQoJPGc+DQoJCTxnPg0KCQkJPHBhdGggc3R5bGU9ImZpbGw6IzAxMDAwMjsiIGQ9Ik00My41Miw3LjQ1OEMzOC43MTEsMi42NDgsMzIuMzA3LDAsMjUuNDg5LDBDMTguNjcsMCwxMi4yNjYsMi42NDgsNy40NTgsNy40NTgNCgkJCQljLTkuOTQzLDkuOTQxLTkuOTQzLDI2LjExOSwwLDM2LjA2MmM0LjgwOSw0LjgwOSwxMS4yMTIsNy40NTYsMTguMDMxLDcuNDU4YzAsMCwwLjAwMSwwLDAuMDAyLDANCgkJCQljNi44MTYsMCwxMy4yMjEtMi42NDgsMTguMDI5LTcuNDU4YzQuODA5LTQuODA5LDcuNDU3LTExLjIxMiw3LjQ1Ny0xOC4wM0M1MC45NzcsMTguNjcsNDguMzI4LDEyLjI2Niw0My41Miw3LjQ1OHoNCgkJCQkgTTQyLjEwNiw0Mi4xMDVjLTQuNDMyLDQuNDMxLTEwLjMzMiw2Ljg3Mi0xNi42MTUsNi44NzJoLTAuMDAyYy02LjI4NS0wLjAwMS0xMi4xODctMi40NDEtMTYuNjE3LTYuODcyDQoJCQkJYy05LjE2Mi05LjE2My05LjE2Mi0yNC4wNzEsMC0zMy4yMzNDMTMuMzAzLDQuNDQsMTkuMjA0LDIsMjUuNDg5LDJjNi4yODQsMCwxMi4xODYsMi40NCwxNi42MTcsNi44NzINCgkJCQljNC40MzEsNC40MzEsNi44NzEsMTAuMzMyLDYuODcxLDE2LjYxN0M0OC45NzcsMzEuNzcyLDQ2LjUzNiwzNy42NzUsNDIuMTA2LDQyLjEwNXoiLz4NCgkJPC9nPg0KCQk8Zz4NCgkJCTxwYXRoIHN0eWxlPSJmaWxsOiMwMTAwMDI7IiBkPSJNMjMuNTc4LDMyLjIxOGMtMC4wMjMtMS43MzQsMC4xNDMtMy4wNTksMC40OTYtMy45NzJjMC4zNTMtMC45MTMsMS4xMS0xLjk5NywyLjI3Mi0zLjI1Mw0KCQkJCWMwLjQ2OC0wLjUzNiwwLjkyMy0xLjA2MiwxLjM2Ny0xLjU3NWMwLjYyNi0wLjc1MywxLjEwNC0xLjQ3OCwxLjQzNi0yLjE3NWMwLjMzMS0wLjcwNywwLjQ5NS0xLjU0MSwwLjQ5NS0yLjUNCgkJCQljMC0xLjA5Ni0wLjI2LTIuMDg4LTAuNzc5LTIuOTc5Yy0wLjU2NS0wLjg3OS0xLjUwMS0xLjMzNi0yLjgwNi0xLjM2OWMtMS44MDIsMC4wNTctMi45ODUsMC42NjctMy41NSwxLjgzMg0KCQkJCWMtMC4zMDEsMC41MzUtMC41MDMsMS4xNDEtMC42MDcsMS44MTRjLTAuMTM5LDAuNzA3LTAuMjA3LDEuNDMyLTAuMjA3LDIuMTc0aC0yLjkzN2MtMC4wOTEtMi4yMDgsMC40MDctNC4xMTQsMS40OTMtNS43MTkNCgkJCQljMS4wNjItMS42NCwyLjg1NS0yLjQ4MSw1LjM3OC0yLjUyN2MyLjE2LDAuMDIzLDMuODc0LDAuNjA4LDUuMTQxLDEuNzU4YzEuMjc4LDEuMTYsMS45MjksMi43NjQsMS45NSw0LjgxMQ0KCQkJCWMwLDEuMTQyLTAuMTM3LDIuMTExLTAuNDEsMi45MTFjLTAuMzA5LDAuODQ1LTAuNzMxLDEuNTkzLTEuMjY4LDIuMjQzYy0wLjQ5MiwwLjY1LTEuMDY4LDEuMzE4LTEuNzMsMi4wMDINCgkJCQljLTAuNjUsMC42OTctMS4zMTMsMS40NzktMS45ODcsMi4zNDZjLTAuMjM5LDAuMzc3LTAuNDI5LDAuNzc3LTAuNTY1LDEuMTk5Yy0wLjE2LDAuOTU5LTAuMjE3LDEuOTUxLTAuMTcxLDIuOTc5DQoJCQkJQzI2LjU4OSwzMi4yMTgsMjMuNTc4LDMyLjIxOCwyMy41NzgsMzIuMjE4eiBNMjMuNTc4LDM4LjIydi0zLjQ4NGgzLjA3NnYzLjQ4NEgyMy41Nzh6Ii8+DQoJCTwvZz4NCgk8L2c+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8L3N2Zz4NCg==);
  --jp-icon-markdown: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjN0IxRkEyIiBkPSJNNSAxNC45aDEybC02LjEgNnptOS40LTYuOGMwLTEuMy0uMS0yLjktLjEtNC41LS40IDEuNC0uOSAyLjktMS4zIDQuM2wtMS4zIDQuM2gtMkw4LjUgNy45Yy0uNC0xLjMtLjctMi45LTEtNC4zLS4xIDEuNi0uMSAzLjItLjIgNC42TDcgMTIuNEg0LjhsLjctMTFoMy4zTDEwIDVjLjQgMS4yLjcgMi43IDEgMy45LjMtMS4yLjctMi42IDEtMy45bDEuMi0zLjdoMy4zbC42IDExaC0yLjRsLS4zLTQuMnoiLz4KPC9zdmc+Cg==);
  --jp-icon-new-folder: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwIDZoLThsLTItMkg0Yy0xLjExIDAtMS45OS44OS0xLjk5IDJMMiAxOGMwIDEuMTEuODkgMiAyIDJoMTZjMS4xMSAwIDItLjg5IDItMlY4YzAtMS4xMS0uODktMi0yLTJ6bS0xIDhoLTN2M2gtMnYtM2gtM3YtMmgzVjloMnYzaDN2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-not-trusted: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI1IDI1Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDMgMykiIGQ9Ik0xLjg2MDk0IDExLjQ0MDlDMC44MjY0NDggOC43NzAyNyAwLjg2Mzc3OSA2LjA1NzY0IDEuMjQ5MDcgNC4xOTkzMkMyLjQ4MjA2IDMuOTMzNDcgNC4wODA2OCAzLjQwMzQ3IDUuNjAxMDIgMi44NDQ5QzcuMjM1NDkgMi4yNDQ0IDguODU2NjYgMS41ODE1IDkuOTg3NiAxLjA5NTM5QzExLjA1OTcgMS41ODM0MSAxMi42MDk0IDIuMjQ0NCAxNC4yMTggMi44NDMzOUMxNS43NTAzIDMuNDEzOTQgMTcuMzk5NSAzLjk1MjU4IDE4Ljc1MzkgNC4yMTM4NUMxOS4xMzY0IDYuMDcxNzcgMTkuMTcwOSA4Ljc3NzIyIDE4LjEzOSAxMS40NDA5QzE3LjAzMDMgMTQuMzAzMiAxNC42NjY4IDE3LjE4NDQgOS45OTk5OSAxOC45MzU0QzUuMzMzMTkgMTcuMTg0NCAyLjk2OTY4IDE0LjMwMzIgMS44NjA5NCAxMS40NDA5WiIvPgogICAgPHBhdGggY2xhc3M9ImpwLWljb24yIiBzdHJva2U9IiMzMzMzMzMiIHN0cm9rZS13aWR0aD0iMiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOS4zMTU5MiA5LjMyMDMxKSIgZD0iTTcuMzY4NDIgMEwwIDcuMzY0NzkiLz4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDkuMzE1OTIgMTYuNjgzNikgc2NhbGUoMSAtMSkiIGQ9Ik03LjM2ODQyIDBMMCA3LjM2NDc5Ii8+Cjwvc3ZnPgo=);
  --jp-icon-notebook: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNFRjZDMDAiPgogICAgPHBhdGggZD0iTTE4LjcgMy4zdjE1LjRIMy4zVjMuM2gxNS40bTEuNS0xLjVIMS44djE4LjNoMTguM2wuMS0xOC4zeiIvPgogICAgPHBhdGggZD0iTTE2LjUgMTYuNWwtNS40LTQuMy01LjYgNC4zdi0xMWgxMXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-palette: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE4IDEzVjIwSDRWNkg5LjAyQzkuMDcgNS4yOSA5LjI0IDQuNjIgOS41IDRINEMyLjkgNCAyIDQuOSAyIDZWMjBDMiAyMS4xIDIuOSAyMiA0IDIySDE4QzE5LjEgMjIgMjAgMjEuMSAyMCAyMFYxNUwxOCAxM1pNMTkuMyA4Ljg5QzE5Ljc0IDguMTkgMjAgNy4zOCAyMCA2LjVDMjAgNC4wMSAxNy45OSAyIDE1LjUgMkMxMy4wMSAyIDExIDQuMDEgMTEgNi41QzExIDguOTkgMTMuMDEgMTEgMTUuNDkgMTFDMTYuMzcgMTEgMTcuMTkgMTAuNzQgMTcuODggMTAuM0wyMSAxMy40MkwyMi40MiAxMkwxOS4zIDguODlaTTE1LjUgOUMxNC4xMiA5IDEzIDcuODggMTMgNi41QzEzIDUuMTIgMTQuMTIgNCAxNS41IDRDMTYuODggNCAxOCA1LjEyIDE4IDYuNUMxOCA3Ljg4IDE2Ljg4IDkgMTUuNSA5WiIvPgogICAgPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBjbGlwLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik00IDZIOS4wMTg5NEM5LjAwNjM5IDYuMTY1MDIgOSA2LjMzMTc2IDkgNi41QzkgOC44MTU3NyAxMC4yMTEgMTAuODQ4NyAxMi4wMzQzIDEySDlWMTRIMTZWMTIuOTgxMUMxNi41NzAzIDEyLjkzNzcgMTcuMTIgMTIuODIwNyAxNy42Mzk2IDEyLjYzOTZMMTggMTNWMjBINFY2Wk04IDhINlYxMEg4VjhaTTYgMTJIOFYxNEg2VjEyWk04IDE2SDZWMThIOFYxNlpNOSAxNkgxNlYxOEg5VjE2WiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-paste: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTE5IDJoLTQuMThDMTQuNC44NCAxMy4zIDAgMTIgMGMtMS4zIDAtMi40Ljg0LTIuODIgMkg1Yy0xLjEgMC0yIC45LTIgMnYxNmMwIDEuMS45IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0yVjRjMC0xLjEtLjktMi0yLTJ6bS03IDBjLjU1IDAgMSAuNDUgMSAxcy0uNDUgMS0xIDEtMS0uNDUtMS0xIC40NS0xIDEtMXptNyAxOEg1VjRoMnYzaDEwVjRoMnYxNnoiLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-python: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1icmFuZDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMEQ0N0ExIj4KICAgIDxwYXRoIGQ9Ik0xMS4xIDYuOVY1LjhINi45YzAtLjUgMC0xLjMuMi0xLjYuNC0uNy44LTEuMSAxLjctMS40IDEuNy0uMyAyLjUtLjMgMy45LS4xIDEgLjEgMS45LjkgMS45IDEuOXY0LjJjMCAuNS0uOSAxLjYtMiAxLjZIOC44Yy0xLjUgMC0yLjQgMS40LTIuNCAyLjh2Mi4ySDQuN0MzLjUgMTUuMSAzIDE0IDMgMTMuMVY5Yy0uMS0xIC42LTIgMS44LTIgMS41LS4xIDYuMy0uMSA2LjMtLjF6Ii8+CiAgICA8cGF0aCBkPSJNMTAuOSAxNS4xdjEuMWg0LjJjMCAuNSAwIDEuMy0uMiAxLjYtLjQuNy0uOCAxLjEtMS43IDEuNC0xLjcuMy0yLjUuMy0zLjkuMS0xLS4xLTEuOS0uOS0xLjktMS45di00LjJjMC0uNS45LTEuNiAyLTEuNmgzLjhjMS41IDAgMi40LTEuNCAyLjQtMi44VjYuNmgxLjdDMTguNSA2LjkgMTkgOCAxOSA4LjlWMTNjMCAxLS43IDIuMS0xLjkgMi4xaC02LjJ6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-r-kernel: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMjE5NkYzIiBkPSJNNC40IDIuNWMxLjItLjEgMi45LS4zIDQuOS0uMyAyLjUgMCA0LjEuNCA1LjIgMS4zIDEgLjcgMS41IDEuOSAxLjUgMy41IDAgMi0xLjQgMy41LTIuOSA0LjEgMS4yLjQgMS43IDEuNiAyLjIgMyAuNiAxLjkgMSAzLjkgMS4zIDQuNmgtMy44Yy0uMy0uNC0uOC0xLjctMS4yLTMuN3MtMS4yLTIuNi0yLjYtMi42aC0uOXY2LjRINC40VjIuNXptMy43IDYuOWgxLjRjMS45IDAgMi45LS45IDIuOS0yLjNzLTEtMi4zLTIuOC0yLjNjLS43IDAtMS4zIDAtMS42LjJ2NC41aC4xdi0uMXoiLz4KPC9zdmc+Cg==);
  --jp-icon-react: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMTUwIDE1MCA1NDEuOSAyOTUuMyI+CiAgPGcgY2xhc3M9ImpwLWljb24tYnJhbmQyIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzYxREFGQiI+CiAgICA8cGF0aCBkPSJNNjY2LjMgMjk2LjVjMC0zMi41LTQwLjctNjMuMy0xMDMuMS04Mi40IDE0LjQtNjMuNiA4LTExNC4yLTIwLjItMTMwLjQtNi41LTMuOC0xNC4xLTUuNi0yMi40LTUuNnYyMi4zYzQuNiAwIDguMy45IDExLjQgMi42IDEzLjYgNy44IDE5LjUgMzcuNSAxNC45IDc1LjctMS4xIDkuNC0yLjkgMTkuMy01LjEgMjkuNC0xOS42LTQuOC00MS04LjUtNjMuNS0xMC45LTEzLjUtMTguNS0yNy41LTM1LjMtNDEuNi01MCAzMi42LTMwLjMgNjMuMi00Ni45IDg0LTQ2LjlWNzhjLTI3LjUgMC02My41IDE5LjYtOTkuOSA1My42LTM2LjQtMzMuOC03Mi40LTUzLjItOTkuOS01My4ydjIyLjNjMjAuNyAwIDUxLjQgMTYuNSA4NCA0Ni42LTE0IDE0LjctMjggMzEuNC00MS4zIDQ5LjktMjIuNiAyLjQtNDQgNi4xLTYzLjYgMTEtMi4zLTEwLTQtMTkuNy01LjItMjktNC43LTM4LjIgMS4xLTY3LjkgMTQuNi03NS44IDMtMS44IDYuOS0yLjYgMTEuNS0yLjZWNzguNWMtOC40IDAtMTYgMS44LTIyLjYgNS42LTI4LjEgMTYuMi0zNC40IDY2LjctMTkuOSAxMzAuMS02Mi4yIDE5LjItMTAyLjcgNDkuOS0xMDIuNyA4Mi4zIDAgMzIuNSA0MC43IDYzLjMgMTAzLjEgODIuNC0xNC40IDYzLjYtOCAxMTQuMiAyMC4yIDEzMC40IDYuNSAzLjggMTQuMSA1LjYgMjIuNSA1LjYgMjcuNSAwIDYzLjUtMTkuNiA5OS45LTUzLjYgMzYuNCAzMy44IDcyLjQgNTMuMiA5OS45IDUzLjIgOC40IDAgMTYtMS44IDIyLjYtNS42IDI4LjEtMTYuMiAzNC40LTY2LjcgMTkuOS0xMzAuMSA2Mi0xOS4xIDEwMi41LTQ5LjkgMTAyLjUtODIuM3ptLTEzMC4yLTY2LjdjLTMuNyAxMi45LTguMyAyNi4yLTEzLjUgMzkuNS00LjEtOC04LjQtMTYtMTMuMS0yNC00LjYtOC05LjUtMTUuOC0xNC40LTIzLjQgMTQuMiAyLjEgMjcuOSA0LjcgNDEgNy45em0tNDUuOCAxMDYuNWMtNy44IDEzLjUtMTUuOCAyNi4zLTI0LjEgMzguMi0xNC45IDEuMy0zMCAyLTQ1LjIgMi0xNS4xIDAtMzAuMi0uNy00NS0xLjktOC4zLTExLjktMTYuNC0yNC42LTI0LjItMzgtNy42LTEzLjEtMTQuNS0yNi40LTIwLjgtMzkuOCA2LjItMTMuNCAxMy4yLTI2LjggMjAuNy0zOS45IDcuOC0xMy41IDE1LjgtMjYuMyAyNC4xLTM4LjIgMTQuOS0xLjMgMzAtMiA0NS4yLTIgMTUuMSAwIDMwLjIuNyA0NSAxLjkgOC4zIDExLjkgMTYuNCAyNC42IDI0LjIgMzggNy42IDEzLjEgMTQuNSAyNi40IDIwLjggMzkuOC02LjMgMTMuNC0xMy4yIDI2LjgtMjAuNyAzOS45em0zMi4zLTEzYzUuNCAxMy40IDEwIDI2LjggMTMuOCAzOS44LTEzLjEgMy4yLTI2LjkgNS45LTQxLjIgOCA0LjktNy43IDkuOC0xNS42IDE0LjQtMjMuNyA0LjYtOCA4LjktMTYuMSAxMy0yNC4xek00MjEuMiA0MzBjLTkuMy05LjYtMTguNi0yMC4zLTI3LjgtMzIgOSAuNCAxOC4yLjcgMjcuNS43IDkuNCAwIDE4LjctLjIgMjcuOC0uNy05IDExLjctMTguMyAyMi40LTI3LjUgMzJ6bS03NC40LTU4LjljLTE0LjItMi4xLTI3LjktNC43LTQxLTcuOSAzLjctMTIuOSA4LjMtMjYuMiAxMy41LTM5LjUgNC4xIDggOC40IDE2IDEzLjEgMjQgNC43IDggOS41IDE1LjggMTQuNCAyMy40ek00MjAuNyAxNjNjOS4zIDkuNiAxOC42IDIwLjMgMjcuOCAzMi05LS40LTE4LjItLjctMjcuNS0uNy05LjQgMC0xOC43LjItMjcuOC43IDktMTEuNyAxOC4zLTIyLjQgMjcuNS0zMnptLTc0IDU4LjljLTQuOSA3LjctOS44IDE1LjYtMTQuNCAyMy43LTQuNiA4LTguOSAxNi0xMyAyNC01LjQtMTMuNC0xMC0yNi44LTEzLjgtMzkuOCAxMy4xLTMuMSAyNi45LTUuOCA0MS4yLTcuOXptLTkwLjUgMTI1LjJjLTM1LjQtMTUuMS01OC4zLTM0LjktNTguMy01MC42IDAtMTUuNyAyMi45LTM1LjYgNTguMy01MC42IDguNi0zLjcgMTgtNyAyNy43LTEwLjEgNS43IDE5LjYgMTMuMiA0MCAyMi41IDYwLjktOS4yIDIwLjgtMTYuNiA0MS4xLTIyLjIgNjAuNi05LjktMy4xLTE5LjMtNi41LTI4LTEwLjJ6TTMxMCA0OTBjLTEzLjYtNy44LTE5LjUtMzcuNS0xNC45LTc1LjcgMS4xLTkuNCAyLjktMTkuMyA1LjEtMjkuNCAxOS42IDQuOCA0MSA4LjUgNjMuNSAxMC45IDEzLjUgMTguNSAyNy41IDM1LjMgNDEuNiA1MC0zMi42IDMwLjMtNjMuMiA0Ni45LTg0IDQ2LjktNC41LS4xLTguMy0xLTExLjMtMi43em0yMzcuMi03Ni4yYzQuNyAzOC4yLTEuMSA2Ny45LTE0LjYgNzUuOC0zIDEuOC02LjkgMi42LTExLjUgMi42LTIwLjcgMC01MS40LTE2LjUtODQtNDYuNiAxNC0xNC43IDI4LTMxLjQgNDEuMy00OS45IDIyLjYtMi40IDQ0LTYuMSA2My42LTExIDIuMyAxMC4xIDQuMSAxOS44IDUuMiAyOS4xem0zOC41LTY2LjdjLTguNiAzLjctMTggNy0yNy43IDEwLjEtNS43LTE5LjYtMTMuMi00MC0yMi41LTYwLjkgOS4yLTIwLjggMTYuNi00MS4xIDIyLjItNjAuNiA5LjkgMy4xIDE5LjMgNi41IDI4LjEgMTAuMiAzNS40IDE1LjEgNTguMyAzNC45IDU4LjMgNTAuNi0uMSAxNS43LTIzIDM1LjYtNTguNCA1MC42ek0zMjAuOCA3OC40eiIvPgogICAgPGNpcmNsZSBjeD0iNDIwLjkiIGN5PSIyOTYuNSIgcj0iNDUuNyIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-refresh: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTkgMTMuNWMtMi40OSAwLTQuNS0yLjAxLTQuNS00LjVTNi41MSA0LjUgOSA0LjVjMS4yNCAwIDIuMzYuNTIgMy4xNyAxLjMzTDEwIDhoNVYzbC0xLjc2IDEuNzZDMTIuMTUgMy42OCAxMC42NiAzIDkgMyA1LjY5IDMgMy4wMSA1LjY5IDMuMDEgOVM1LjY5IDE1IDkgMTVjMi45NyAwIDUuNDMtMi4xNiA1LjktNWgtMS41MmMtLjQ2IDItMi4yNCAzLjUtNC4zOCAzLjV6Ii8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-regex: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0MTQxNDEiPgogICAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbi1hY2NlbnQyIiBmaWxsPSIjRkZGIj4KICAgIDxjaXJjbGUgY2xhc3M9InN0MiIgY3g9IjUuNSIgY3k9IjE0LjUiIHI9IjEuNSIvPgogICAgPHJlY3QgeD0iMTIiIHk9IjQiIGNsYXNzPSJzdDIiIHdpZHRoPSIxIiBoZWlnaHQ9IjgiLz4KICAgIDxyZWN0IHg9IjguNSIgeT0iNy41IiB0cmFuc2Zvcm09Im1hdHJpeCgwLjg2NiAtMC41IDAuNSAwLjg2NiAtMi4zMjU1IDcuMzIxOSkiIGNsYXNzPSJzdDIiIHdpZHRoPSI4IiBoZWlnaHQ9IjEiLz4KICAgIDxyZWN0IHg9IjEyIiB5PSI0IiB0cmFuc2Zvcm09Im1hdHJpeCgwLjUgLTAuODY2IDAuODY2IDAuNSAtMC42Nzc5IDE0LjgyNTIpIiBjbGFzcz0ic3QyIiB3aWR0aD0iMSIgaGVpZ2h0PSI4Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-run: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTggNXYxNGwxMS03eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-running: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUxMiA1MTIiPgogIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICA8cGF0aCBkPSJNMjU2IDhDMTE5IDggOCAxMTkgOCAyNTZzMTExIDI0OCAyNDggMjQ4IDI0OC0xMTEgMjQ4LTI0OFMzOTMgOCAyNTYgOHptOTYgMzI4YzAgOC44LTcuMiAxNi0xNiAxNkgxNzZjLTguOCAwLTE2LTcuMi0xNi0xNlYxNzZjMC04LjggNy4yLTE2IDE2LTE2aDE2MGM4LjggMCAxNiA3LjIgMTYgMTZ2MTYweiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-save: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTE3IDNINWMtMS4xMSAwLTIgLjktMiAydjE0YzAgMS4xLjg5IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0yVjdsLTQtNHptLTUgMTZjLTEuNjYgMC0zLTEuMzQtMy0zczEuMzQtMyAzLTMgMyAxLjM0IDMgMy0xLjM0IDMtMyAzem0zLTEwSDVWNWgxMHY0eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-search: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyLjEsMTAuOWgtMC43bC0wLjItMC4yYzAuOC0wLjksMS4zLTIuMiwxLjMtMy41YzAtMy0yLjQtNS40LTUuNC01LjRTMS44LDQuMiwxLjgsNy4xczIuNCw1LjQsNS40LDUuNCBjMS4zLDAsMi41LTAuNSwzLjUtMS4zbDAuMiwwLjJ2MC43bDQuMSw0LjFsMS4yLTEuMkwxMi4xLDEwLjl6IE03LjEsMTAuOWMtMi4xLDAtMy43LTEuNy0zLjctMy43czEuNy0zLjcsMy43LTMuN3MzLjcsMS43LDMuNywzLjcgUzkuMiwxMC45LDcuMSwxMC45eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-settings: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkuNDMgMTIuOThjLjA0LS4zMi4wNy0uNjQuMDctLjk4cy0uMDMtLjY2LS4wNy0uOThsMi4xMS0xLjY1Yy4xOS0uMTUuMjQtLjQyLjEyLS42NGwtMi0zLjQ2Yy0uMTItLjIyLS4zOS0uMy0uNjEtLjIybC0yLjQ5IDFjLS41Mi0uNC0xLjA4LS43My0xLjY5LS45OGwtLjM4LTIuNjVBLjQ4OC40ODggMCAwMDE0IDJoLTRjLS4yNSAwLS40Ni4xOC0uNDkuNDJsLS4zOCAyLjY1Yy0uNjEuMjUtMS4xNy41OS0xLjY5Ljk4bC0yLjQ5LTFjLS4yMy0uMDktLjQ5IDAtLjYxLjIybC0yIDMuNDZjLS4xMy4yMi0uMDcuNDkuMTIuNjRsMi4xMSAxLjY1Yy0uMDQuMzItLjA3LjY1LS4wNy45OHMuMDMuNjYuMDcuOThsLTIuMTEgMS42NWMtLjE5LjE1LS4yNC40Mi0uMTIuNjRsMiAzLjQ2Yy4xMi4yMi4zOS4zLjYxLjIybDIuNDktMWMuNTIuNCAxLjA4LjczIDEuNjkuOThsLjM4IDIuNjVjLjAzLjI0LjI0LjQyLjQ5LjQyaDRjLjI1IDAgLjQ2LS4xOC40OS0uNDJsLjM4LTIuNjVjLjYxLS4yNSAxLjE3LS41OSAxLjY5LS45OGwyLjQ5IDFjLjIzLjA5LjQ5IDAgLjYxLS4yMmwyLTMuNDZjLjEyLS4yMi4wNy0uNDktLjEyLS42NGwtMi4xMS0xLjY1ek0xMiAxNS41Yy0xLjkzIDAtMy41LTEuNTctMy41LTMuNXMxLjU3LTMuNSAzLjUtMy41IDMuNSAxLjU3IDMuNSAzLjUtMS41NyAzLjUtMy41IDMuNXoiLz4KPC9zdmc+Cg==);
  --jp-icon-spreadsheet: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDEganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNENBRjUwIiBkPSJNMi4yIDIuMnYxNy42aDE3LjZWMi4ySDIuMnptMTUuNCA3LjdoLTUuNVY0LjRoNS41djUuNXpNOS45IDQuNHY1LjVINC40VjQuNGg1LjV6bS01LjUgNy43aDUuNXY1LjVINC40di01LjV6bTcuNyA1LjV2LTUuNWg1LjV2NS41aC01LjV6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-stop: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik02IDZoMTJ2MTJINnoiLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-tab: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIxIDNIM2MtMS4xIDAtMiAuOS0yIDJ2MTRjMCAxLjEuOSAyIDIgMmgxOGMxLjEgMCAyLS45IDItMlY1YzAtMS4xLS45LTItMi0yem0wIDE2SDNWNWgxMHY0aDh2MTB6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-terminal: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0IiA+CiAgICA8cmVjdCBjbGFzcz0ianAtaWNvbjIganAtaWNvbi1zZWxlY3RhYmxlIiB3aWR0aD0iMjAiIGhlaWdodD0iMjAiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDIgMikiIGZpbGw9IiMzMzMzMzMiLz4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uLWFjY2VudDIganAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGQ9Ik01LjA1NjY0IDguNzYxNzJDNS4wNTY2NCA4LjU5NzY2IDUuMDMxMjUgOC40NTMxMiA0Ljk4MDQ3IDguMzI4MTJDNC45MzM1OSA4LjE5OTIyIDQuODU1NDcgOC4wODIwMyA0Ljc0NjA5IDcuOTc2NTZDNC42NDA2MiA3Ljg3MTA5IDQuNSA3Ljc3NTM5IDQuMzI0MjIgNy42ODk0NUM0LjE1MjM0IDcuNTk5NjEgMy45NDMzNiA3LjUxMTcyIDMuNjk3MjcgNy40MjU3OEMzLjMwMjczIDcuMjg1MTYgMi45NDMzNiA3LjEzNjcyIDIuNjE5MTQgNi45ODA0N0MyLjI5NDkyIDYuODI0MjIgMi4wMTc1OCA2LjY0MjU4IDEuNzg3MTEgNi40MzU1NUMxLjU2MDU1IDYuMjI4NTIgMS4zODQ3NyA1Ljk4ODI4IDEuMjU5NzcgNS43MTQ4NEMxLjEzNDc3IDUuNDM3NSAxLjA3MjI3IDUuMTA5MzggMS4wNzIyNyA0LjczMDQ3QzEuMDcyMjcgNC4zOTg0NCAxLjEyODkxIDQuMDk1NyAxLjI0MjE5IDMuODIyMjdDMS4zNTU0NyAzLjU0NDkyIDEuNTE1NjIgMy4zMDQ2OSAxLjcyMjY2IDMuMTAxNTZDMS45Mjk2OSAyLjg5ODQ0IDIuMTc5NjkgMi43MzQzNyAyLjQ3MjY2IDIuNjA5MzhDMi43NjU2MiAyLjQ4NDM4IDMuMDkxOCAyLjQwNDMgMy40NTExNyAyLjM2OTE0VjEuMTA5MzhINC4zODg2N1YyLjM4MDg2QzQuNzQwMjMgMi40Mjc3MyA1LjA1NjY0IDIuNTIzNDQgNS4zMzc4OSAyLjY2Nzk3QzUuNjE5MTQgMi44MTI1IDUuODU3NDIgMy4wMDE5NSA2LjA1MjczIDMuMjM2MzNDNi4yNTE5NSAzLjQ2NjggNi40MDQzIDMuNzQwMjMgNi41MDk3NyA0LjA1NjY0QzYuNjE5MTQgNC4zNjkxNCA2LjY3MzgzIDQuNzIwNyA2LjY3MzgzIDUuMTExMzNINS4wNDQ5MkM1LjA0NDkyIDQuNjM4NjcgNC45Mzc1IDQuMjgxMjUgNC43MjI2NiA0LjAzOTA2QzQuNTA3ODEgMy43OTI5NyA0LjIxNjggMy42Njk5MiAzLjg0OTYxIDMuNjY5OTJDMy42NTAzOSAzLjY2OTkyIDMuNDc2NTYgMy42OTcyNyAzLjMyODEyIDMuNzUxOTVDMy4xODM1OSAzLjgwMjczIDMuMDY0NDUgMy44NzY5NSAyLjk3MDcgMy45NzQ2MUMyLjg3Njk1IDQuMDY4MzYgMi44MDY2NCA0LjE3OTY5IDIuNzU5NzcgNC4zMDg1OUMyLjcxNjggNC40Mzc1IDIuNjk1MzEgNC41NzgxMiAyLjY5NTMxIDQuNzMwNDdDMi42OTUzMSA0Ljg4MjgxIDIuNzE2OCA1LjAxOTUzIDIuNzU5NzcgNS4xNDA2MkMyLjgwNjY0IDUuMjU3ODEgMi44ODI4MSA1LjM2NzE5IDIuOTg4MjggNS40Njg3NUMzLjA5NzY2IDUuNTcwMzEgMy4yNDAyMyA1LjY2Nzk3IDMuNDE2MDIgNS43NjE3MkMzLjU5MTggNS44NTE1NiAzLjgxMDU1IDUuOTQzMzYgNC4wNzIyNyA2LjAzNzExQzQuNDY2OCA2LjE4NTU1IDQuODI0MjIgNi4zMzk4NCA1LjE0NDUzIDYuNUM1LjQ2NDg0IDYuNjU2MjUgNS43MzgyOCA2LjgzOTg0IDUuOTY0ODQgNy4wNTA3OEM2LjE5NTMxIDcuMjU3ODEgNi4zNzEwOSA3LjUgNi40OTIxOSA3Ljc3NzM0QzYuNjE3MTkgOC4wNTA3OCA2LjY3OTY5IDguMzc1IDYuNjc5NjkgOC43NUM2LjY3OTY5IDkuMDkzNzUgNi42MjMwNSA5LjQwNDMgNi41MDk3NyA5LjY4MTY0QzYuMzk2NDggOS45NTUwOCA2LjIzNDM4IDEwLjE5MTQgNi4wMjM0NCAxMC4zOTA2QzUuODEyNSAxMC41ODk4IDUuNTU4NTkgMTAuNzUgNS4yNjE3MiAxMC44NzExQzQuOTY0ODQgMTAuOTg4MyA0LjYzMjgxIDExLjA2NDUgNC4yNjU2MiAxMS4wOTk2VjEyLjI0OEgzLjMzMzk4VjExLjA5OTZDMy4wMDE5NSAxMS4wNjg0IDIuNjc5NjkgMTAuOTk2MSAyLjM2NzE5IDEwLjg4MjhDMi4wNTQ2OSAxMC43NjU2IDEuNzc3MzQgMTAuNTk3NyAxLjUzNTE2IDEwLjM3ODlDMS4yOTY4OCAxMC4xNjAyIDEuMTA1NDcgOS44ODQ3NyAwLjk2MDkzOCA5LjU1MjczQzAuODE2NDA2IDkuMjE2OCAwLjc0NDE0MSA4LjgxNDQ1IDAuNzQ0MTQxIDguMzQ1N0gyLjM3ODkxQzIuMzc4OTEgOC42MjY5NSAyLjQxOTkyIDguODYzMjggMi41MDE5NSA5LjA1NDY5QzIuNTgzOTggOS4yNDIxOSAyLjY4OTQ1IDkuMzkyNTggMi44MTgzNiA5LjUwNTg2QzIuOTUxMTcgOS42MTUyMyAzLjEwMTU2IDkuNjkzMzYgMy4yNjk1MyA5Ljc0MDIzQzMuNDM3NSA5Ljc4NzExIDMuNjA5MzggOS44MTA1NSAzLjc4NTE2IDkuODEwNTVDNC4yMDMxMiA5LjgxMDU1IDQuNTE5NTMgOS43MTI4OSA0LjczNDM4IDkuNTE3NThDNC45NDkyMiA5LjMyMjI3IDUuMDU2NjQgOS4wNzAzMSA1LjA1NjY0IDguNzYxNzJaTTEzLjQxOCAxMi4yNzE1SDguMDc0MjJWMTFIMTMuNDE4VjEyLjI3MTVaIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgzLjk1MjY0IDYpIiBmaWxsPSJ3aGl0ZSIvPgo8L3N2Zz4K);
  --jp-icon-text-editor: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTUgMTVIM3YyaDEydi0yem0wLThIM3YyaDEyVjd6TTMgMTNoMTh2LTJIM3Yyem0wIDhoMTh2LTJIM3Yyek0zIDN2MmgxOFYzSDN6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-trusted: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI1Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDIgMykiIGQ9Ik0xLjg2MDk0IDExLjQ0MDlDMC44MjY0NDggOC43NzAyNyAwLjg2Mzc3OSA2LjA1NzY0IDEuMjQ5MDcgNC4xOTkzMkMyLjQ4MjA2IDMuOTMzNDcgNC4wODA2OCAzLjQwMzQ3IDUuNjAxMDIgMi44NDQ5QzcuMjM1NDkgMi4yNDQ0IDguODU2NjYgMS41ODE1IDkuOTg3NiAxLjA5NTM5QzExLjA1OTcgMS41ODM0MSAxMi42MDk0IDIuMjQ0NCAxNC4yMTggMi44NDMzOUMxNS43NTAzIDMuNDEzOTQgMTcuMzk5NSAzLjk1MjU4IDE4Ljc1MzkgNC4yMTM4NUMxOS4xMzY0IDYuMDcxNzcgMTkuMTcwOSA4Ljc3NzIyIDE4LjEzOSAxMS40NDA5QzE3LjAzMDMgMTQuMzAzMiAxNC42NjY4IDE3LjE4NDQgOS45OTk5OSAxOC45MzU0QzUuMzMzMiAxNy4xODQ0IDIuOTY5NjggMTQuMzAzMiAxLjg2MDk0IDExLjQ0MDlaIi8+CiAgICA8cGF0aCBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiMzMzMzMzMiIHN0cm9rZT0iIzMzMzMzMyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOCA5Ljg2NzE5KSIgZD0iTTIuODYwMTUgNC44NjUzNUwwLjcyNjU0OSAyLjk5OTU5TDAgMy42MzA0NUwyLjg2MDE1IDYuMTMxNTdMOCAwLjYzMDg3Mkw3LjI3ODU3IDBMMi44NjAxNSA0Ljg2NTM1WiIvPgo8L3N2Zz4K);
  --jp-icon-undo: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyLjUgOGMtMi42NSAwLTUuMDUuOTktNi45IDIuNkwyIDd2OWg5bC0zLjYyLTMuNjJjMS4zOS0xLjE2IDMuMTYtMS44OCA1LjEyLTEuODggMy41NCAwIDYuNTUgMi4zMSA3LjYgNS41bDIuMzctLjc4QzIxLjA4IDExLjAzIDE3LjE1IDggMTIuNSA4eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-vega: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbjEganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMjEyMTIxIj4KICAgIDxwYXRoIGQ9Ik0xMC42IDUuNGwyLjItMy4ySDIuMnY3LjNsNC02LjZ6Ii8+CiAgICA8cGF0aCBkPSJNMTUuOCAyLjJsLTQuNCA2LjZMNyA2LjNsLTQuOCA4djUuNWgxNy42VjIuMmgtNHptLTcgMTUuNEg1LjV2LTQuNGgzLjN2NC40em00LjQgMEg5LjhWOS44aDMuNHY3Ljh6bTQuNCAwaC0zLjRWNi41aDMuNHYxMS4xeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-yaml: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1jb250cmFzdDIganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjRDgxQjYwIj4KICAgIDxwYXRoIGQ9Ik03LjIgMTguNnYtNS40TDMgNS42aDMuM2wxLjQgMy4xYy4zLjkuNiAxLjYgMSAyLjUuMy0uOC42LTEuNiAxLTIuNWwxLjQtMy4xaDMuNGwtNC40IDcuNnY1LjVsLTIuOS0uMXoiLz4KICAgIDxjaXJjbGUgY2xhc3M9InN0MCIgY3g9IjE3LjYiIGN5PSIxNi41IiByPSIyLjEiLz4KICAgIDxjaXJjbGUgY2xhc3M9InN0MCIgY3g9IjE3LjYiIGN5PSIxMSIgcj0iMi4xIi8+CiAgPC9nPgo8L3N2Zz4K);
}

/* Icon CSS class declarations */

.jp-AddIcon {
  background-image: var(--jp-icon-add);
}
.jp-BugIcon {
  background-image: var(--jp-icon-bug);
}
.jp-BuildIcon {
  background-image: var(--jp-icon-build);
}
.jp-CaretDownEmptyIcon {
  background-image: var(--jp-icon-caret-down-empty);
}
.jp-CaretDownEmptyThinIcon {
  background-image: var(--jp-icon-caret-down-empty-thin);
}
.jp-CaretDownIcon {
  background-image: var(--jp-icon-caret-down);
}
.jp-CaretLeftIcon {
  background-image: var(--jp-icon-caret-left);
}
.jp-CaretRightIcon {
  background-image: var(--jp-icon-caret-right);
}
.jp-CaretUpEmptyThinIcon {
  background-image: var(--jp-icon-caret-up-empty-thin);
}
.jp-CaretUpIcon {
  background-image: var(--jp-icon-caret-up);
}
.jp-CaseSensitiveIcon {
  background-image: var(--jp-icon-case-sensitive);
}
.jp-CheckIcon {
  background-image: var(--jp-icon-check);
}
.jp-CircleEmptyIcon {
  background-image: var(--jp-icon-circle-empty);
}
.jp-CircleIcon {
  background-image: var(--jp-icon-circle);
}
.jp-ClearIcon {
  background-image: var(--jp-icon-clear);
}
.jp-CloseIcon {
  background-image: var(--jp-icon-close);
}
.jp-ConsoleIcon {
  background-image: var(--jp-icon-console);
}
.jp-CopyIcon {
  background-image: var(--jp-icon-copy);
}
.jp-CutIcon {
  background-image: var(--jp-icon-cut);
}
.jp-DownloadIcon {
  background-image: var(--jp-icon-download);
}
.jp-EditIcon {
  background-image: var(--jp-icon-edit);
}
.jp-EllipsesIcon {
  background-image: var(--jp-icon-ellipses);
}
.jp-ExtensionIcon {
  background-image: var(--jp-icon-extension);
}
.jp-FastForwardIcon {
  background-image: var(--jp-icon-fast-forward);
}
.jp-FileIcon {
  background-image: var(--jp-icon-file);
}
.jp-FileUploadIcon {
  background-image: var(--jp-icon-file-upload);
}
.jp-FilterListIcon {
  background-image: var(--jp-icon-filter-list);
}
.jp-FolderIcon {
  background-image: var(--jp-icon-folder);
}
.jp-Html5Icon {
  background-image: var(--jp-icon-html5);
}
.jp-ImageIcon {
  background-image: var(--jp-icon-image);
}
.jp-InspectorIcon {
  background-image: var(--jp-icon-inspector);
}
.jp-JsonIcon {
  background-image: var(--jp-icon-json);
}
.jp-JupyterFaviconIcon {
  background-image: var(--jp-icon-jupyter-favicon);
}
.jp-JupyterIcon {
  background-image: var(--jp-icon-jupyter);
}
.jp-JupyterlabWordmarkIcon {
  background-image: var(--jp-icon-jupyterlab-wordmark);
}
.jp-KernelIcon {
  background-image: var(--jp-icon-kernel);
}
.jp-KeyboardIcon {
  background-image: var(--jp-icon-keyboard);
}
.jp-LauncherIcon {
  background-image: var(--jp-icon-launcher);
}
.jp-LineFormIcon {
  background-image: var(--jp-icon-line-form);
}
.jp-LinkIcon {
  background-image: var(--jp-icon-link);
}
.jp-ListIcon {
  background-image: var(--jp-icon-list);
}
.jp-ListingsInfoIcon {
  background-image: var(--jp-icon-listings-info);
}
.jp-MarkdownIcon {
  background-image: var(--jp-icon-markdown);
}
.jp-NewFolderIcon {
  background-image: var(--jp-icon-new-folder);
}
.jp-NotTrustedIcon {
  background-image: var(--jp-icon-not-trusted);
}
.jp-NotebookIcon {
  background-image: var(--jp-icon-notebook);
}
.jp-PaletteIcon {
  background-image: var(--jp-icon-palette);
}
.jp-PasteIcon {
  background-image: var(--jp-icon-paste);
}
.jp-PythonIcon {
  background-image: var(--jp-icon-python);
}
.jp-RKernelIcon {
  background-image: var(--jp-icon-r-kernel);
}
.jp-ReactIcon {
  background-image: var(--jp-icon-react);
}
.jp-RefreshIcon {
  background-image: var(--jp-icon-refresh);
}
.jp-RegexIcon {
  background-image: var(--jp-icon-regex);
}
.jp-RunIcon {
  background-image: var(--jp-icon-run);
}
.jp-RunningIcon {
  background-image: var(--jp-icon-running);
}
.jp-SaveIcon {
  background-image: var(--jp-icon-save);
}
.jp-SearchIcon {
  background-image: var(--jp-icon-search);
}
.jp-SettingsIcon {
  background-image: var(--jp-icon-settings);
}
.jp-SpreadsheetIcon {
  background-image: var(--jp-icon-spreadsheet);
}
.jp-StopIcon {
  background-image: var(--jp-icon-stop);
}
.jp-TabIcon {
  background-image: var(--jp-icon-tab);
}
.jp-TerminalIcon {
  background-image: var(--jp-icon-terminal);
}
.jp-TextEditorIcon {
  background-image: var(--jp-icon-text-editor);
}
.jp-TrustedIcon {
  background-image: var(--jp-icon-trusted);
}
.jp-UndoIcon {
  background-image: var(--jp-icon-undo);
}
.jp-VegaIcon {
  background-image: var(--jp-icon-vega);
}
.jp-YamlIcon {
  background-image: var(--jp-icon-yaml);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * (DEPRECATED) Support for consuming icons as CSS background images
 */

:root {
  --jp-icon-search-white: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyLjEsMTAuOWgtMC43bC0wLjItMC4yYzAuOC0wLjksMS4zLTIuMiwxLjMtMy41YzAtMy0yLjQtNS40LTUuNC01LjRTMS44LDQuMiwxLjgsNy4xczIuNCw1LjQsNS40LDUuNCBjMS4zLDAsMi41LTAuNSwzLjUtMS4zbDAuMiwwLjJ2MC43bDQuMSw0LjFsMS4yLTEuMkwxMi4xLDEwLjl6IE03LjEsMTAuOWMtMi4xLDAtMy43LTEuNy0zLjctMy43czEuNy0zLjcsMy43LTMuN3MzLjcsMS43LDMuNywzLjcgUzkuMiwxMC45LDcuMSwxMC45eiIvPgogIDwvZz4KPC9zdmc+Cg==);
}

.jp-Icon,
.jp-MaterialIcon {
  background-position: center;
  background-repeat: no-repeat;
  background-size: 16px;
  min-width: 16px;
  min-height: 16px;
}

.jp-Icon-cover {
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

/**
 * (DEPRECATED) Support for specific CSS icon sizes
 */

.jp-Icon-16 {
  background-size: 16px;
  min-width: 16px;
  min-height: 16px;
}

.jp-Icon-18 {
  background-size: 18px;
  min-width: 18px;
  min-height: 18px;
}

.jp-Icon-20 {
  background-size: 20px;
  min-width: 20px;
  min-height: 20px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * Support for icons as inline SVG HTMLElements
 */

/* recolor the primary elements of an icon */
.jp-icon0[fill] {
  fill: var(--jp-inverse-layout-color0);
}
.jp-icon1[fill] {
  fill: var(--jp-inverse-layout-color1);
}
.jp-icon2[fill] {
  fill: var(--jp-inverse-layout-color2);
}
.jp-icon3[fill] {
  fill: var(--jp-inverse-layout-color3);
}
.jp-icon4[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon0[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}
.jp-icon1[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}
.jp-icon2[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}
.jp-icon3[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}
.jp-icon4[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}
/* recolor the accent elements of an icon */
.jp-icon-accent0[fill] {
  fill: var(--jp-layout-color0);
}
.jp-icon-accent1[fill] {
  fill: var(--jp-layout-color1);
}
.jp-icon-accent2[fill] {
  fill: var(--jp-layout-color2);
}
.jp-icon-accent3[fill] {
  fill: var(--jp-layout-color3);
}
.jp-icon-accent4[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-accent0[stroke] {
  stroke: var(--jp-layout-color0);
}
.jp-icon-accent1[stroke] {
  stroke: var(--jp-layout-color1);
}
.jp-icon-accent2[stroke] {
  stroke: var(--jp-layout-color2);
}
.jp-icon-accent3[stroke] {
  stroke: var(--jp-layout-color3);
}
.jp-icon-accent4[stroke] {
  stroke: var(--jp-layout-color4);
}
/* set the color of an icon to transparent */
.jp-icon-none[fill] {
  fill: none;
}

.jp-icon-none[stroke] {
  stroke: none;
}
/* brand icon colors. Same for light and dark */
.jp-icon-brand0[fill] {
  fill: var(--jp-brand-color0);
}
.jp-icon-brand1[fill] {
  fill: var(--jp-brand-color1);
}
.jp-icon-brand2[fill] {
  fill: var(--jp-brand-color2);
}
.jp-icon-brand3[fill] {
  fill: var(--jp-brand-color3);
}
.jp-icon-brand4[fill] {
  fill: var(--jp-brand-color4);
}

.jp-icon-brand0[stroke] {
  stroke: var(--jp-brand-color0);
}
.jp-icon-brand1[stroke] {
  stroke: var(--jp-brand-color1);
}
.jp-icon-brand2[stroke] {
  stroke: var(--jp-brand-color2);
}
.jp-icon-brand3[stroke] {
  stroke: var(--jp-brand-color3);
}
.jp-icon-brand4[stroke] {
  stroke: var(--jp-brand-color4);
}
/* warn icon colors. Same for light and dark */
.jp-icon-warn0[fill] {
  fill: var(--jp-warn-color0);
}
.jp-icon-warn1[fill] {
  fill: var(--jp-warn-color1);
}
.jp-icon-warn2[fill] {
  fill: var(--jp-warn-color2);
}
.jp-icon-warn3[fill] {
  fill: var(--jp-warn-color3);
}

.jp-icon-warn0[stroke] {
  stroke: var(--jp-warn-color0);
}
.jp-icon-warn1[stroke] {
  stroke: var(--jp-warn-color1);
}
.jp-icon-warn2[stroke] {
  stroke: var(--jp-warn-color2);
}
.jp-icon-warn3[stroke] {
  stroke: var(--jp-warn-color3);
}
/* icon colors that contrast well with each other and most backgrounds */
.jp-icon-contrast0[fill] {
  fill: var(--jp-icon-contrast-color0);
}
.jp-icon-contrast1[fill] {
  fill: var(--jp-icon-contrast-color1);
}
.jp-icon-contrast2[fill] {
  fill: var(--jp-icon-contrast-color2);
}
.jp-icon-contrast3[fill] {
  fill: var(--jp-icon-contrast-color3);
}

.jp-icon-contrast0[stroke] {
  stroke: var(--jp-icon-contrast-color0);
}
.jp-icon-contrast1[stroke] {
  stroke: var(--jp-icon-contrast-color1);
}
.jp-icon-contrast2[stroke] {
  stroke: var(--jp-icon-contrast-color2);
}
.jp-icon-contrast3[stroke] {
  stroke: var(--jp-icon-contrast-color3);
}

/* CSS for icons in selected items in the settings editor */
#setting-editor .jp-PluginList .jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}
#setting-editor
  .jp-PluginList
  .jp-mod-selected
  .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}

/* CSS for icons in selected filebrowser listing items */
.jp-DirListing-item.jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}
.jp-DirListing-item.jp-mod-selected .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}

/* CSS for icons in selected tabs in the sidebar tab manager */
#tab-manager .lm-TabBar-tab.jp-mod-active .jp-icon-selectable[fill] {
  fill: #fff;
}

#tab-manager .lm-TabBar-tab.jp-mod-active .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}
#tab-manager
  .lm-TabBar-tab.jp-mod-active
  .jp-icon-hover
  :hover
  .jp-icon-selectable[fill] {
  fill: var(--jp-brand-color1);
}

#tab-manager
  .lm-TabBar-tab.jp-mod-active
  .jp-icon-hover
  :hover
  .jp-icon-selectable-inverse[fill] {
  fill: #fff;
}

/**
 * TODO: come up with non css-hack solution for showing the busy icon on top
 *  of the close icon
 * CSS for complex behavior of close icon of tabs in the sidebar tab manager
 */
#tab-manager
  .lm-TabBar-tab.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon3[fill] {
  fill: none;
}
#tab-manager
  .lm-TabBar-tab.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon-busy[fill] {
  fill: var(--jp-inverse-layout-color3);
}

#tab-manager
  .lm-TabBar-tab.jp-mod-dirty.jp-mod-active
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon-busy[fill] {
  fill: #fff;
}

/**
* TODO: come up with non css-hack solution for showing the busy icon on top
*  of the close icon
* CSS for complex behavior of close icon of tabs in the main area tabbar
*/
.lm-DockPanel-tabBar
  .lm-TabBar-tab.lm-mod-closable.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon3[fill] {
  fill: none;
}
.lm-DockPanel-tabBar
  .lm-TabBar-tab.lm-mod-closable.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon-busy[fill] {
  fill: var(--jp-inverse-layout-color3);
}

/* CSS for icons in status bar */
#jp-main-statusbar .jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}

#jp-main-statusbar .jp-mod-selected .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}
/* special handling for splash icon CSS. While the theme CSS reloads during
   splash, the splash icon can loose theming. To prevent that, we set a
   default for its color variable */
:root {
  --jp-warn-color0: var(--md-orange-700);
}

/* not sure what to do with this one, used in filebrowser listing */
.jp-DragIcon {
  margin-right: 4px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * Support for alt colors for icons as inline SVG HTMLElements
 */

/* alt recolor the primary elements of an icon */
.jp-icon-alt .jp-icon0[fill] {
  fill: var(--jp-layout-color0);
}
.jp-icon-alt .jp-icon1[fill] {
  fill: var(--jp-layout-color1);
}
.jp-icon-alt .jp-icon2[fill] {
  fill: var(--jp-layout-color2);
}
.jp-icon-alt .jp-icon3[fill] {
  fill: var(--jp-layout-color3);
}
.jp-icon-alt .jp-icon4[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-alt .jp-icon0[stroke] {
  stroke: var(--jp-layout-color0);
}
.jp-icon-alt .jp-icon1[stroke] {
  stroke: var(--jp-layout-color1);
}
.jp-icon-alt .jp-icon2[stroke] {
  stroke: var(--jp-layout-color2);
}
.jp-icon-alt .jp-icon3[stroke] {
  stroke: var(--jp-layout-color3);
}
.jp-icon-alt .jp-icon4[stroke] {
  stroke: var(--jp-layout-color4);
}

/* alt recolor the accent elements of an icon */
.jp-icon-alt .jp-icon-accent0[fill] {
  fill: var(--jp-inverse-layout-color0);
}
.jp-icon-alt .jp-icon-accent1[fill] {
  fill: var(--jp-inverse-layout-color1);
}
.jp-icon-alt .jp-icon-accent2[fill] {
  fill: var(--jp-inverse-layout-color2);
}
.jp-icon-alt .jp-icon-accent3[fill] {
  fill: var(--jp-inverse-layout-color3);
}
.jp-icon-alt .jp-icon-accent4[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-alt .jp-icon-accent0[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}
.jp-icon-alt .jp-icon-accent1[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}
.jp-icon-alt .jp-icon-accent2[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}
.jp-icon-alt .jp-icon-accent3[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}
.jp-icon-alt .jp-icon-accent4[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-icon-hoverShow:not(:hover) svg {
  display: none !important;
}

/**
 * Support for hover colors for icons as inline SVG HTMLElements
 */

/**
 * regular colors
 */

/* recolor the primary elements of an icon */
.jp-icon-hover :hover .jp-icon0-hover[fill] {
  fill: var(--jp-inverse-layout-color0);
}
.jp-icon-hover :hover .jp-icon1-hover[fill] {
  fill: var(--jp-inverse-layout-color1);
}
.jp-icon-hover :hover .jp-icon2-hover[fill] {
  fill: var(--jp-inverse-layout-color2);
}
.jp-icon-hover :hover .jp-icon3-hover[fill] {
  fill: var(--jp-inverse-layout-color3);
}
.jp-icon-hover :hover .jp-icon4-hover[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-hover :hover .jp-icon0-hover[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}
.jp-icon-hover :hover .jp-icon1-hover[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}
.jp-icon-hover :hover .jp-icon2-hover[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}
.jp-icon-hover :hover .jp-icon3-hover[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}
.jp-icon-hover :hover .jp-icon4-hover[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/* recolor the accent elements of an icon */
.jp-icon-hover :hover .jp-icon-accent0-hover[fill] {
  fill: var(--jp-layout-color0);
}
.jp-icon-hover :hover .jp-icon-accent1-hover[fill] {
  fill: var(--jp-layout-color1);
}
.jp-icon-hover :hover .jp-icon-accent2-hover[fill] {
  fill: var(--jp-layout-color2);
}
.jp-icon-hover :hover .jp-icon-accent3-hover[fill] {
  fill: var(--jp-layout-color3);
}
.jp-icon-hover :hover .jp-icon-accent4-hover[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-hover :hover .jp-icon-accent0-hover[stroke] {
  stroke: var(--jp-layout-color0);
}
.jp-icon-hover :hover .jp-icon-accent1-hover[stroke] {
  stroke: var(--jp-layout-color1);
}
.jp-icon-hover :hover .jp-icon-accent2-hover[stroke] {
  stroke: var(--jp-layout-color2);
}
.jp-icon-hover :hover .jp-icon-accent3-hover[stroke] {
  stroke: var(--jp-layout-color3);
}
.jp-icon-hover :hover .jp-icon-accent4-hover[stroke] {
  stroke: var(--jp-layout-color4);
}

/* set the color of an icon to transparent */
.jp-icon-hover :hover .jp-icon-none-hover[fill] {
  fill: none;
}

.jp-icon-hover :hover .jp-icon-none-hover[stroke] {
  stroke: none;
}

/**
 * inverse colors
 */

/* inverse recolor the primary elements of an icon */
.jp-icon-hover.jp-icon-alt :hover .jp-icon0-hover[fill] {
  fill: var(--jp-layout-color0);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon1-hover[fill] {
  fill: var(--jp-layout-color1);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon2-hover[fill] {
  fill: var(--jp-layout-color2);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon3-hover[fill] {
  fill: var(--jp-layout-color3);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon4-hover[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon0-hover[stroke] {
  stroke: var(--jp-layout-color0);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon1-hover[stroke] {
  stroke: var(--jp-layout-color1);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon2-hover[stroke] {
  stroke: var(--jp-layout-color2);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon3-hover[stroke] {
  stroke: var(--jp-layout-color3);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon4-hover[stroke] {
  stroke: var(--jp-layout-color4);
}

/* inverse recolor the accent elements of an icon */
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent0-hover[fill] {
  fill: var(--jp-inverse-layout-color0);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent1-hover[fill] {
  fill: var(--jp-inverse-layout-color1);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent2-hover[fill] {
  fill: var(--jp-inverse-layout-color2);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent3-hover[fill] {
  fill: var(--jp-inverse-layout-color3);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent4-hover[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent0-hover[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent1-hover[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent2-hover[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent3-hover[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent4-hover[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* Sibling imports */

/* Override Blueprint's _reset.scss styles */
html {
  box-sizing: unset;
}

*,
*::before,
*::after {
  box-sizing: unset;
}

body {
  color: unset;
  font-family: var(--jp-ui-font-family);
}

p {
  margin-top: unset;
  margin-bottom: unset;
}

small {
  font-size: unset;
}

strong {
  font-weight: unset;
}

/* Override Blueprint's _typography.scss styles */
a {
  text-decoration: unset;
  color: unset;
}
a:hover {
  text-decoration: unset;
  color: unset;
}

/* Override Blueprint's _accessibility.scss styles */
:focus {
  outline: unset;
  outline-offset: unset;
  -moz-outline-radius: unset;
}

/* Styles for ui-components */
.jp-Button {
  border-radius: var(--jp-border-radius);
  padding: 0px 12px;
  font-size: var(--jp-ui-font-size1);
}

/* Use our own theme for hover styles */
button.jp-Button.bp3-button.bp3-minimal:hover {
  background-color: var(--jp-layout-color2);
}
.jp-Button.minimal {
  color: unset !important;
}

.jp-Button.jp-ToolbarButtonComponent {
  text-transform: none;
}

.jp-InputGroup input {
  box-sizing: border-box;
  border-radius: 0;
  background-color: transparent;
  color: var(--jp-ui-font-color0);
  box-shadow: inset 0 0 0 var(--jp-border-width) var(--jp-input-border-color);
}

.jp-InputGroup input:focus {
  box-shadow: inset 0 0 0 var(--jp-border-width)
      var(--jp-input-active-box-shadow-color),
    inset 0 0 0 3px var(--jp-input-active-box-shadow-color);
}

.jp-InputGroup input::placeholder,
input::placeholder {
  color: var(--jp-ui-font-color3);
}

.jp-BPIcon {
  display: inline-block;
  vertical-align: middle;
  margin: auto;
}

/* Stop blueprint futzing with our icon fills */
.bp3-icon.jp-BPIcon > svg:not([fill]) {
  fill: var(--jp-inverse-layout-color3);
}

.jp-InputGroupAction {
  padding: 6px;
}

.jp-HTMLSelect.jp-DefaultStyle select {
  background-color: initial;
  border: none;
  border-radius: 0;
  box-shadow: none;
  color: var(--jp-ui-font-color0);
  display: block;
  font-size: var(--jp-ui-font-size1);
  height: 24px;
  line-height: 14px;
  padding: 0 25px 0 10px;
  text-align: left;
  -moz-appearance: none;
  -webkit-appearance: none;
}

/* Use our own theme for hover and option styles */
.jp-HTMLSelect.jp-DefaultStyle select:hover,
.jp-HTMLSelect.jp-DefaultStyle select > option {
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color0);
}
select {
  box-sizing: border-box;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Collapse {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  border-top: 1px solid var(--jp-border-color2);
  border-bottom: 1px solid var(--jp-border-color2);
}

.jp-Collapse-header {
  padding: 1px 12px;
  color: var(--jp-ui-font-color1);
  background-color: var(--jp-layout-color1);
  font-size: var(--jp-ui-font-size2);
}

.jp-Collapse-header:hover {
  background-color: var(--jp-layout-color2);
}

.jp-Collapse-contents {
  padding: 0px 12px 0px 12px;
  background-color: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  overflow: auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-commandpalette-search-height: 28px;
}

/*-----------------------------------------------------------------------------
| Overall styles
|----------------------------------------------------------------------------*/

.lm-CommandPalette {
  padding-bottom: 0px;
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);
  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
}

/*-----------------------------------------------------------------------------
| Search
|----------------------------------------------------------------------------*/

.lm-CommandPalette-search {
  padding: 4px;
  background-color: var(--jp-layout-color1);
  z-index: 2;
}

.lm-CommandPalette-wrapper {
  overflow: overlay;
  padding: 0px 9px;
  background-color: var(--jp-input-active-background);
  height: 30px;
  box-shadow: inset 0 0 0 var(--jp-border-width) var(--jp-input-border-color);
}

.lm-CommandPalette.lm-mod-focused .lm-CommandPalette-wrapper {
  box-shadow: inset 0 0 0 1px var(--jp-input-active-box-shadow-color),
    inset 0 0 0 3px var(--jp-input-active-box-shadow-color);
}

.lm-CommandPalette-wrapper::after {
  content: ' ';
  color: white;
  background-color: var(--jp-brand-color1);
  position: absolute;
  top: 4px;
  right: 4px;
  height: 30px;
  width: 10px;
  padding: 0px 10px;
  background-image: var(--jp-icon-search-white);
  background-size: 20px;
  background-repeat: no-repeat;
  background-position: center;
}

.lm-CommandPalette-input {
  background: transparent;
  width: calc(100% - 18px);
  float: left;
  border: none;
  outline: none;
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  line-height: var(--jp-private-commandpalette-search-height);
}

.lm-CommandPalette-input::-webkit-input-placeholder,
.lm-CommandPalette-input::-moz-placeholder,
.lm-CommandPalette-input:-ms-input-placeholder {
  color: var(--jp-ui-font-color3);
  font-size: var(--jp-ui-font-size1);
}

/*-----------------------------------------------------------------------------
| Results
|----------------------------------------------------------------------------*/

.lm-CommandPalette-header:first-child {
  margin-top: 0px;
}

.lm-CommandPalette-header {
  border-bottom: solid var(--jp-border-width) var(--jp-border-color2);
  color: var(--jp-ui-font-color1);
  cursor: pointer;
  display: flex;
  font-size: var(--jp-ui-font-size0);
  font-weight: 600;
  letter-spacing: 1px;
  margin-top: 8px;
  padding: 8px 0 8px 12px;
  text-transform: uppercase;
}

.lm-CommandPalette-header.lm-mod-active {
  background: var(--jp-layout-color2);
}

.lm-CommandPalette-header > mark {
  background-color: transparent;
  font-weight: bold;
  color: var(--jp-ui-font-color1);
}

.lm-CommandPalette-item {
  padding: 4px 12px 4px 4px;
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  font-weight: 400;
  display: flex;
}

.lm-CommandPalette-item.lm-mod-disabled {
  color: var(--jp-ui-font-color3);
}

.lm-CommandPalette-item.lm-mod-active {
  background: var(--jp-layout-color3);
}

.lm-CommandPalette-item.lm-mod-active:hover:not(.lm-mod-disabled) {
  background: var(--jp-layout-color4);
}

.lm-CommandPalette-item:hover:not(.lm-mod-active):not(.lm-mod-disabled) {
  background: var(--jp-layout-color2);
}

.lm-CommandPalette-itemContent {
  overflow: hidden;
}

.lm-CommandPalette-itemLabel > mark {
  color: var(--jp-ui-font-color0);
  background-color: transparent;
  font-weight: bold;
}

.lm-CommandPalette-item.lm-mod-disabled mark {
  color: var(--jp-ui-font-color3);
}

.lm-CommandPalette-item .lm-CommandPalette-itemIcon {
  margin: 0 4px 0 0;
  position: relative;
  width: 16px;
  top: 2px;
  flex: 0 0 auto;
}

.lm-CommandPalette-item.lm-mod-disabled .lm-CommandPalette-itemIcon {
  opacity: 0.4;
}

.lm-CommandPalette-item .lm-CommandPalette-itemShortcut {
  flex: 0 0 auto;
}

.lm-CommandPalette-itemCaption {
  display: none;
}

.lm-CommandPalette-content {
  background-color: var(--jp-layout-color1);
}

.lm-CommandPalette-content:empty:after {
  content: 'No results';
  margin: auto;
  margin-top: 20px;
  width: 100px;
  display: block;
  font-size: var(--jp-ui-font-size2);
  font-family: var(--jp-ui-font-family);
  font-weight: lighter;
}

.lm-CommandPalette-emptyMessage {
  text-align: center;
  margin-top: 24px;
  line-height: 1.32;
  padding: 0px 8px;
  color: var(--jp-content-font-color3);
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Dialog {
  position: absolute;
  z-index: 10000;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  top: 0px;
  left: 0px;
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
  background: var(--jp-dialog-background);
}

.jp-Dialog-content {
  display: flex;
  flex-direction: column;
  margin-left: auto;
  margin-right: auto;
  background: var(--jp-layout-color1);
  padding: 24px;
  padding-bottom: 12px;
  min-width: 300px;
  min-height: 150px;
  max-width: 1000px;
  max-height: 500px;
  box-sizing: border-box;
  box-shadow: var(--jp-elevation-z20);
  word-wrap: break-word;
  border-radius: var(--jp-border-radius);
  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color1);
}

.jp-Dialog-button {
  overflow: visible;
}

button.jp-Dialog-button:focus {
  outline: 1px solid var(--jp-brand-color1);
  outline-offset: 4px;
  -moz-outline-radius: 0px;
}

button.jp-Dialog-button:focus::-moz-focus-inner {
  border: 0;
}

.jp-Dialog-header {
  flex: 0 0 auto;
  padding-bottom: 12px;
  font-size: var(--jp-ui-font-size3);
  font-weight: 400;
  color: var(--jp-ui-font-color0);
}

.jp-Dialog-body {
  display: flex;
  flex-direction: column;
  flex: 1 1 auto;
  font-size: var(--jp-ui-font-size1);
  background: var(--jp-layout-color1);
  overflow: auto;
}

.jp-Dialog-footer {
  display: flex;
  flex-direction: row;
  justify-content: flex-end;
  flex: 0 0 auto;
  margin-left: -12px;
  margin-right: -12px;
  padding: 12px;
}

.jp-Dialog-title {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.jp-Dialog-body > .jp-select-wrapper {
  width: 100%;
}

.jp-Dialog-body > button {
  padding: 0px 16px;
}

.jp-Dialog-body > label {
  line-height: 1.4;
  color: var(--jp-ui-font-color0);
}

.jp-Dialog-button.jp-mod-styled:not(:last-child) {
  margin-right: 12px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-HoverBox {
  position: fixed;
}

.jp-HoverBox.jp-mod-outofview {
  display: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-IFrame {
  width: 100%;
  height: 100%;
}

.jp-IFrame > iframe {
  border: none;
}

/*
When drag events occur, `p-mod-override-cursor` is added to the body.
Because iframes steal all cursor events, the following two rules are necessary
to suppress pointer events while resize drags are occurring. There may be a
better solution to this problem.
*/
body.lm-mod-override-cursor .jp-IFrame {
  position: relative;
}

body.lm-mod-override-cursor .jp-IFrame:before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-MainAreaWidget > :focus {
  outline: none;
}

/**
 * google-material-color v1.2.6
 * https://github.com/danlevan/google-material-color
 */
:root {
  --md-red-50: #ffebee;
  --md-red-100: #ffcdd2;
  --md-red-200: #ef9a9a;
  --md-red-300: #e57373;
  --md-red-400: #ef5350;
  --md-red-500: #f44336;
  --md-red-600: #e53935;
  --md-red-700: #d32f2f;
  --md-red-800: #c62828;
  --md-red-900: #b71c1c;
  --md-red-A100: #ff8a80;
  --md-red-A200: #ff5252;
  --md-red-A400: #ff1744;
  --md-red-A700: #d50000;

  --md-pink-50: #fce4ec;
  --md-pink-100: #f8bbd0;
  --md-pink-200: #f48fb1;
  --md-pink-300: #f06292;
  --md-pink-400: #ec407a;
  --md-pink-500: #e91e63;
  --md-pink-600: #d81b60;
  --md-pink-700: #c2185b;
  --md-pink-800: #ad1457;
  --md-pink-900: #880e4f;
  --md-pink-A100: #ff80ab;
  --md-pink-A200: #ff4081;
  --md-pink-A400: #f50057;
  --md-pink-A700: #c51162;

  --md-purple-50: #f3e5f5;
  --md-purple-100: #e1bee7;
  --md-purple-200: #ce93d8;
  --md-purple-300: #ba68c8;
  --md-purple-400: #ab47bc;
  --md-purple-500: #9c27b0;
  --md-purple-600: #8e24aa;
  --md-purple-700: #7b1fa2;
  --md-purple-800: #6a1b9a;
  --md-purple-900: #4a148c;
  --md-purple-A100: #ea80fc;
  --md-purple-A200: #e040fb;
  --md-purple-A400: #d500f9;
  --md-purple-A700: #aa00ff;

  --md-deep-purple-50: #ede7f6;
  --md-deep-purple-100: #d1c4e9;
  --md-deep-purple-200: #b39ddb;
  --md-deep-purple-300: #9575cd;
  --md-deep-purple-400: #7e57c2;
  --md-deep-purple-500: #673ab7;
  --md-deep-purple-600: #5e35b1;
  --md-deep-purple-700: #512da8;
  --md-deep-purple-800: #4527a0;
  --md-deep-purple-900: #311b92;
  --md-deep-purple-A100: #b388ff;
  --md-deep-purple-A200: #7c4dff;
  --md-deep-purple-A400: #651fff;
  --md-deep-purple-A700: #6200ea;

  --md-indigo-50: #e8eaf6;
  --md-indigo-100: #c5cae9;
  --md-indigo-200: #9fa8da;
  --md-indigo-300: #7986cb;
  --md-indigo-400: #5c6bc0;
  --md-indigo-500: #3f51b5;
  --md-indigo-600: #3949ab;
  --md-indigo-700: #303f9f;
  --md-indigo-800: #283593;
  --md-indigo-900: #1a237e;
  --md-indigo-A100: #8c9eff;
  --md-indigo-A200: #536dfe;
  --md-indigo-A400: #3d5afe;
  --md-indigo-A700: #304ffe;

  --md-blue-50: #e3f2fd;
  --md-blue-100: #bbdefb;
  --md-blue-200: #90caf9;
  --md-blue-300: #64b5f6;
  --md-blue-400: #42a5f5;
  --md-blue-500: #2196f3;
  --md-blue-600: #1e88e5;
  --md-blue-700: #1976d2;
  --md-blue-800: #1565c0;
  --md-blue-900: #0d47a1;
  --md-blue-A100: #82b1ff;
  --md-blue-A200: #448aff;
  --md-blue-A400: #2979ff;
  --md-blue-A700: #2962ff;

  --md-light-blue-50: #e1f5fe;
  --md-light-blue-100: #b3e5fc;
  --md-light-blue-200: #81d4fa;
  --md-light-blue-300: #4fc3f7;
  --md-light-blue-400: #29b6f6;
  --md-light-blue-500: #03a9f4;
  --md-light-blue-600: #039be5;
  --md-light-blue-700: #0288d1;
  --md-light-blue-800: #0277bd;
  --md-light-blue-900: #01579b;
  --md-light-blue-A100: #80d8ff;
  --md-light-blue-A200: #40c4ff;
  --md-light-blue-A400: #00b0ff;
  --md-light-blue-A700: #0091ea;

  --md-cyan-50: #e0f7fa;
  --md-cyan-100: #b2ebf2;
  --md-cyan-200: #80deea;
  --md-cyan-300: #4dd0e1;
  --md-cyan-400: #26c6da;
  --md-cyan-500: #00bcd4;
  --md-cyan-600: #00acc1;
  --md-cyan-700: #0097a7;
  --md-cyan-800: #00838f;
  --md-cyan-900: #006064;
  --md-cyan-A100: #84ffff;
  --md-cyan-A200: #18ffff;
  --md-cyan-A400: #00e5ff;
  --md-cyan-A700: #00b8d4;

  --md-teal-50: #e0f2f1;
  --md-teal-100: #b2dfdb;
  --md-teal-200: #80cbc4;
  --md-teal-300: #4db6ac;
  --md-teal-400: #26a69a;
  --md-teal-500: #009688;
  --md-teal-600: #00897b;
  --md-teal-700: #00796b;
  --md-teal-800: #00695c;
  --md-teal-900: #004d40;
  --md-teal-A100: #a7ffeb;
  --md-teal-A200: #64ffda;
  --md-teal-A400: #1de9b6;
  --md-teal-A700: #00bfa5;

  --md-green-50: #e8f5e9;
  --md-green-100: #c8e6c9;
  --md-green-200: #a5d6a7;
  --md-green-300: #81c784;
  --md-green-400: #66bb6a;
  --md-green-500: #4caf50;
  --md-green-600: #43a047;
  --md-green-700: #388e3c;
  --md-green-800: #2e7d32;
  --md-green-900: #1b5e20;
  --md-green-A100: #b9f6ca;
  --md-green-A200: #69f0ae;
  --md-green-A400: #00e676;
  --md-green-A700: #00c853;

  --md-light-green-50: #f1f8e9;
  --md-light-green-100: #dcedc8;
  --md-light-green-200: #c5e1a5;
  --md-light-green-300: #aed581;
  --md-light-green-400: #9ccc65;
  --md-light-green-500: #8bc34a;
  --md-light-green-600: #7cb342;
  --md-light-green-700: #689f38;
  --md-light-green-800: #558b2f;
  --md-light-green-900: #33691e;
  --md-light-green-A100: #ccff90;
  --md-light-green-A200: #b2ff59;
  --md-light-green-A400: #76ff03;
  --md-light-green-A700: #64dd17;

  --md-lime-50: #f9fbe7;
  --md-lime-100: #f0f4c3;
  --md-lime-200: #e6ee9c;
  --md-lime-300: #dce775;
  --md-lime-400: #d4e157;
  --md-lime-500: #cddc39;
  --md-lime-600: #c0ca33;
  --md-lime-700: #afb42b;
  --md-lime-800: #9e9d24;
  --md-lime-900: #827717;
  --md-lime-A100: #f4ff81;
  --md-lime-A200: #eeff41;
  --md-lime-A400: #c6ff00;
  --md-lime-A700: #aeea00;

  --md-yellow-50: #fffde7;
  --md-yellow-100: #fff9c4;
  --md-yellow-200: #fff59d;
  --md-yellow-300: #fff176;
  --md-yellow-400: #ffee58;
  --md-yellow-500: #ffeb3b;
  --md-yellow-600: #fdd835;
  --md-yellow-700: #fbc02d;
  --md-yellow-800: #f9a825;
  --md-yellow-900: #f57f17;
  --md-yellow-A100: #ffff8d;
  --md-yellow-A200: #ffff00;
  --md-yellow-A400: #ffea00;
  --md-yellow-A700: #ffd600;

  --md-amber-50: #fff8e1;
  --md-amber-100: #ffecb3;
  --md-amber-200: #ffe082;
  --md-amber-300: #ffd54f;
  --md-amber-400: #ffca28;
  --md-amber-500: #ffc107;
  --md-amber-600: #ffb300;
  --md-amber-700: #ffa000;
  --md-amber-800: #ff8f00;
  --md-amber-900: #ff6f00;
  --md-amber-A100: #ffe57f;
  --md-amber-A200: #ffd740;
  --md-amber-A400: #ffc400;
  --md-amber-A700: #ffab00;

  --md-orange-50: #fff3e0;
  --md-orange-100: #ffe0b2;
  --md-orange-200: #ffcc80;
  --md-orange-300: #ffb74d;
  --md-orange-400: #ffa726;
  --md-orange-500: #ff9800;
  --md-orange-600: #fb8c00;
  --md-orange-700: #f57c00;
  --md-orange-800: #ef6c00;
  --md-orange-900: #e65100;
  --md-orange-A100: #ffd180;
  --md-orange-A200: #ffab40;
  --md-orange-A400: #ff9100;
  --md-orange-A700: #ff6d00;

  --md-deep-orange-50: #fbe9e7;
  --md-deep-orange-100: #ffccbc;
  --md-deep-orange-200: #ffab91;
  --md-deep-orange-300: #ff8a65;
  --md-deep-orange-400: #ff7043;
  --md-deep-orange-500: #ff5722;
  --md-deep-orange-600: #f4511e;
  --md-deep-orange-700: #e64a19;
  --md-deep-orange-800: #d84315;
  --md-deep-orange-900: #bf360c;
  --md-deep-orange-A100: #ff9e80;
  --md-deep-orange-A200: #ff6e40;
  --md-deep-orange-A400: #ff3d00;
  --md-deep-orange-A700: #dd2c00;

  --md-brown-50: #efebe9;
  --md-brown-100: #d7ccc8;
  --md-brown-200: #bcaaa4;
  --md-brown-300: #a1887f;
  --md-brown-400: #8d6e63;
  --md-brown-500: #795548;
  --md-brown-600: #6d4c41;
  --md-brown-700: #5d4037;
  --md-brown-800: #4e342e;
  --md-brown-900: #3e2723;

  --md-grey-50: #fafafa;
  --md-grey-100: #f5f5f5;
  --md-grey-200: #eeeeee;
  --md-grey-300: #e0e0e0;
  --md-grey-400: #bdbdbd;
  --md-grey-500: #9e9e9e;
  --md-grey-600: #757575;
  --md-grey-700: #616161;
  --md-grey-800: #424242;
  --md-grey-900: #212121;

  --md-blue-grey-50: #eceff1;
  --md-blue-grey-100: #cfd8dc;
  --md-blue-grey-200: #b0bec5;
  --md-blue-grey-300: #90a4ae;
  --md-blue-grey-400: #78909c;
  --md-blue-grey-500: #607d8b;
  --md-blue-grey-600: #546e7a;
  --md-blue-grey-700: #455a64;
  --md-blue-grey-800: #37474f;
  --md-blue-grey-900: #263238;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Spinner {
  position: absolute;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 10;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background: var(--jp-layout-color0);
  outline: none;
}

.jp-SpinnerContent {
  font-size: 10px;
  margin: 50px auto;
  text-indent: -9999em;
  width: 3em;
  height: 3em;
  border-radius: 50%;
  background: var(--jp-brand-color3);
  background: linear-gradient(
    to right,
    #f37626 10%,
    rgba(255, 255, 255, 0) 42%
  );
  position: relative;
  animation: load3 1s infinite linear, fadeIn 1s;
}

.jp-SpinnerContent:before {
  width: 50%;
  height: 50%;
  background: #f37626;
  border-radius: 100% 0 0 0;
  position: absolute;
  top: 0;
  left: 0;
  content: '';
}

.jp-SpinnerContent:after {
  background: var(--jp-layout-color0);
  width: 75%;
  height: 75%;
  border-radius: 50%;
  content: '';
  margin: auto;
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
}

@keyframes fadeIn {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

@keyframes load3 {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

button.jp-mod-styled {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  border: none;
  box-sizing: border-box;
  text-align: center;
  line-height: 32px;
  height: 32px;
  padding: 0px 12px;
  letter-spacing: 0.8px;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

input.jp-mod-styled {
  background: var(--jp-input-background);
  height: 28px;
  box-sizing: border-box;
  border: var(--jp-border-width) solid var(--jp-border-color1);
  padding-left: 7px;
  padding-right: 7px;
  font-size: var(--jp-ui-font-size2);
  color: var(--jp-ui-font-color0);
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

input.jp-mod-styled:focus {
  border: var(--jp-border-width) solid var(--md-blue-500);
  box-shadow: inset 0 0 4px var(--md-blue-300);
}

.jp-select-wrapper {
  display: flex;
  position: relative;
  flex-direction: column;
  padding: 1px;
  background-color: var(--jp-layout-color1);
  height: 28px;
  box-sizing: border-box;
  margin-bottom: 12px;
}

.jp-select-wrapper.jp-mod-focused select.jp-mod-styled {
  border: var(--jp-border-width) solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
  background-color: var(--jp-input-active-background);
}

select.jp-mod-styled:hover {
  background-color: var(--jp-layout-color1);
  cursor: pointer;
  color: var(--jp-ui-font-color0);
  background-color: var(--jp-input-hover-background);
  box-shadow: inset 0 0px 1px rgba(0, 0, 0, 0.5);
}

select.jp-mod-styled {
  flex: 1 1 auto;
  height: 32px;
  width: 100%;
  font-size: var(--jp-ui-font-size2);
  background: var(--jp-input-background);
  color: var(--jp-ui-font-color0);
  padding: 0 25px 0 8px;
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  border-radius: 0px;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

:root {
  --jp-private-toolbar-height: calc(
    28px + var(--jp-border-width)
  ); /* leave 28px for content */
}

.jp-Toolbar {
  color: var(--jp-ui-font-color1);
  flex: 0 0 auto;
  display: flex;
  flex-direction: row;
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  box-shadow: var(--jp-toolbar-box-shadow);
  background: var(--jp-toolbar-background);
  min-height: var(--jp-toolbar-micro-height);
  padding: 2px;
  z-index: 1;
}

/* Toolbar items */

.jp-Toolbar > .jp-Toolbar-item.jp-Toolbar-spacer {
  flex-grow: 1;
  flex-shrink: 1;
}

.jp-Toolbar-item.jp-Toolbar-kernelStatus {
  display: inline-block;
  width: 32px;
  background-repeat: no-repeat;
  background-position: center;
  background-size: 16px;
}

.jp-Toolbar > .jp-Toolbar-item {
  flex: 0 0 auto;
  display: flex;
  padding-left: 1px;
  padding-right: 1px;
  font-size: var(--jp-ui-font-size1);
  line-height: var(--jp-private-toolbar-height);
  height: 100%;
}

/* Toolbar buttons */

/* This is the div we use to wrap the react component into a Widget */
div.jp-ToolbarButton {
  color: transparent;
  border: none;
  box-sizing: border-box;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  padding: 0px;
  margin: 0px;
}

button.jp-ToolbarButtonComponent {
  background: var(--jp-layout-color1);
  border: none;
  box-sizing: border-box;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  padding: 0px 6px;
  margin: 0px;
  height: 24px;
  border-radius: var(--jp-border-radius);
  display: flex;
  align-items: center;
  text-align: center;
  font-size: 14px;
  min-width: unset;
  min-height: unset;
}

button.jp-ToolbarButtonComponent:disabled {
  opacity: 0.4;
}

button.jp-ToolbarButtonComponent span {
  padding: 0px;
  flex: 0 0 auto;
}

button.jp-ToolbarButtonComponent .jp-ToolbarButtonComponent-label {
  font-size: var(--jp-ui-font-size1);
  line-height: 100%;
  padding-left: 2px;
  color: var(--jp-ui-font-color1);
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ body.p-mod-override-cursor *, /* </DEPRECATED> */
body.lm-mod-override-cursor * {
  cursor: inherit !important;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-JSONEditor {
  display: flex;
  flex-direction: column;
  width: 100%;
}

.jp-JSONEditor-host {
  flex: 1 1 auto;
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  border-radius: 0px;
  background: var(--jp-layout-color0);
  min-height: 50px;
  padding: 1px;
}

.jp-JSONEditor.jp-mod-error .jp-JSONEditor-host {
  border-color: red;
  outline-color: red;
}

.jp-JSONEditor-header {
  display: flex;
  flex: 1 0 auto;
  padding: 0 0 0 12px;
}

.jp-JSONEditor-header label {
  flex: 0 0 auto;
}

.jp-JSONEditor-commitButton {
  height: 16px;
  width: 16px;
  background-size: 18px;
  background-repeat: no-repeat;
  background-position: center;
}

.jp-JSONEditor-host.jp-mod-focused {
  background-color: var(--jp-input-active-background);
  border: 1px solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
}

.jp-Editor.jp-mod-dropTarget {
  border: var(--jp-border-width) solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* BASICS */

.CodeMirror {
  /* Set height, width, borders, and global font properties here */
  font-family: monospace;
  height: 300px;
  color: black;
  direction: ltr;
}

/* PADDING */

.CodeMirror-lines {
  padding: 4px 0; /* Vertical padding around content */
}
.CodeMirror pre.CodeMirror-line,
.CodeMirror pre.CodeMirror-line-like {
  padding: 0 4px; /* Horizontal padding of content */
}

.CodeMirror-scrollbar-filler, .CodeMirror-gutter-filler {
  background-color: white; /* The little square between H and V scrollbars */
}

/* GUTTER */

.CodeMirror-gutters {
  border-right: 1px solid #ddd;
  background-color: #f7f7f7;
  white-space: nowrap;
}
.CodeMirror-linenumbers {}
.CodeMirror-linenumber {
  padding: 0 3px 0 5px;
  min-width: 20px;
  text-align: right;
  color: #999;
  white-space: nowrap;
}

.CodeMirror-guttermarker { color: black; }
.CodeMirror-guttermarker-subtle { color: #999; }

/* CURSOR */

.CodeMirror-cursor {
  border-left: 1px solid black;
  border-right: none;
  width: 0;
}
/* Shown when moving in bi-directional text */
.CodeMirror div.CodeMirror-secondarycursor {
  border-left: 1px solid silver;
}
.cm-fat-cursor .CodeMirror-cursor {
  width: auto;
  border: 0 !important;
  background: #7e7;
}
.cm-fat-cursor div.CodeMirror-cursors {
  z-index: 1;
}
.cm-fat-cursor-mark {
  background-color: rgba(20, 255, 20, 0.5);
  -webkit-animation: blink 1.06s steps(1) infinite;
  -moz-animation: blink 1.06s steps(1) infinite;
  animation: blink 1.06s steps(1) infinite;
}
.cm-animate-fat-cursor {
  width: auto;
  border: 0;
  -webkit-animation: blink 1.06s steps(1) infinite;
  -moz-animation: blink 1.06s steps(1) infinite;
  animation: blink 1.06s steps(1) infinite;
  background-color: #7e7;
}
@-moz-keyframes blink {
  0% {}
  50% { background-color: transparent; }
  100% {}
}
@-webkit-keyframes blink {
  0% {}
  50% { background-color: transparent; }
  100% {}
}
@keyframes blink {
  0% {}
  50% { background-color: transparent; }
  100% {}
}

/* Can style cursor different in overwrite (non-insert) mode */
.CodeMirror-overwrite .CodeMirror-cursor {}

.cm-tab { display: inline-block; text-decoration: inherit; }

.CodeMirror-rulers {
  position: absolute;
  left: 0; right: 0; top: -50px; bottom: 0;
  overflow: hidden;
}
.CodeMirror-ruler {
  border-left: 1px solid #ccc;
  top: 0; bottom: 0;
  position: absolute;
}

/* DEFAULT THEME */

.cm-s-default .cm-header {color: blue;}
.cm-s-default .cm-quote {color: #090;}
.cm-negative {color: #d44;}
.cm-positive {color: #292;}
.cm-header, .cm-strong {font-weight: bold;}
.cm-em {font-style: italic;}
.cm-link {text-decoration: underline;}
.cm-strikethrough {text-decoration: line-through;}

.cm-s-default .cm-keyword {color: #708;}
.cm-s-default .cm-atom {color: #219;}
.cm-s-default .cm-number {color: #164;}
.cm-s-default .cm-def {color: #00f;}
.cm-s-default .cm-variable,
.cm-s-default .cm-punctuation,
.cm-s-default .cm-property,
.cm-s-default .cm-operator {}
.cm-s-default .cm-variable-2 {color: #05a;}
.cm-s-default .cm-variable-3, .cm-s-default .cm-type {color: #085;}
.cm-s-default .cm-comment {color: #a50;}
.cm-s-default .cm-string {color: #a11;}
.cm-s-default .cm-string-2 {color: #f50;}
.cm-s-default .cm-meta {color: #555;}
.cm-s-default .cm-qualifier {color: #555;}
.cm-s-default .cm-builtin {color: #30a;}
.cm-s-default .cm-bracket {color: #997;}
.cm-s-default .cm-tag {color: #170;}
.cm-s-default .cm-attribute {color: #00c;}
.cm-s-default .cm-hr {color: #999;}
.cm-s-default .cm-link {color: #00c;}

.cm-s-default .cm-error {color: #f00;}
.cm-invalidchar {color: #f00;}

.CodeMirror-composing { border-bottom: 2px solid; }

/* Default styles for common addons */

div.CodeMirror span.CodeMirror-matchingbracket {color: #0b0;}
div.CodeMirror span.CodeMirror-nonmatchingbracket {color: #a22;}
.CodeMirror-matchingtag { background: rgba(255, 150, 0, .3); }
.CodeMirror-activeline-background {background: #e8f2ff;}

/* STOP */

/* The rest of this file contains styles related to the mechanics of
   the editor. You probably shouldn't touch them. */

.CodeMirror {
  position: relative;
  overflow: hidden;
  background: white;
}

.CodeMirror-scroll {
  overflow: scroll !important; /* Things will break if this is overridden */
  /* 30px is the magic margin used to hide the element's real scrollbars */
  /* See overflow: hidden in .CodeMirror */
  margin-bottom: -30px; margin-right: -30px;
  padding-bottom: 30px;
  height: 100%;
  outline: none; /* Prevent dragging from highlighting the element */
  position: relative;
}
.CodeMirror-sizer {
  position: relative;
  border-right: 30px solid transparent;
}

/* The fake, visible scrollbars. Used to force redraw during scrolling
   before actual scrolling happens, thus preventing shaking and
   flickering artifacts. */
.CodeMirror-vscrollbar, .CodeMirror-hscrollbar, .CodeMirror-scrollbar-filler, .CodeMirror-gutter-filler {
  position: absolute;
  z-index: 6;
  display: none;
}
.CodeMirror-vscrollbar {
  right: 0; top: 0;
  overflow-x: hidden;
  overflow-y: scroll;
}
.CodeMirror-hscrollbar {
  bottom: 0; left: 0;
  overflow-y: hidden;
  overflow-x: scroll;
}
.CodeMirror-scrollbar-filler {
  right: 0; bottom: 0;
}
.CodeMirror-gutter-filler {
  left: 0; bottom: 0;
}

.CodeMirror-gutters {
  position: absolute; left: 0; top: 0;
  min-height: 100%;
  z-index: 3;
}
.CodeMirror-gutter {
  white-space: normal;
  height: 100%;
  display: inline-block;
  vertical-align: top;
  margin-bottom: -30px;
}
.CodeMirror-gutter-wrapper {
  position: absolute;
  z-index: 4;
  background: none !important;
  border: none !important;
}
.CodeMirror-gutter-background {
  position: absolute;
  top: 0; bottom: 0;
  z-index: 4;
}
.CodeMirror-gutter-elt {
  position: absolute;
  cursor: default;
  z-index: 4;
}
.CodeMirror-gutter-wrapper ::selection { background-color: transparent }
.CodeMirror-gutter-wrapper ::-moz-selection { background-color: transparent }

.CodeMirror-lines {
  cursor: text;
  min-height: 1px; /* prevents collapsing before first draw */
}
.CodeMirror pre.CodeMirror-line,
.CodeMirror pre.CodeMirror-line-like {
  /* Reset some styles that the rest of the page might have set */
  -moz-border-radius: 0; -webkit-border-radius: 0; border-radius: 0;
  border-width: 0;
  background: transparent;
  font-family: inherit;
  font-size: inherit;
  margin: 0;
  white-space: pre;
  word-wrap: normal;
  line-height: inherit;
  color: inherit;
  z-index: 2;
  position: relative;
  overflow: visible;
  -webkit-tap-highlight-color: transparent;
  -webkit-font-variant-ligatures: contextual;
  font-variant-ligatures: contextual;
}
.CodeMirror-wrap pre.CodeMirror-line,
.CodeMirror-wrap pre.CodeMirror-line-like {
  word-wrap: break-word;
  white-space: pre-wrap;
  word-break: normal;
}

.CodeMirror-linebackground {
  position: absolute;
  left: 0; right: 0; top: 0; bottom: 0;
  z-index: 0;
}

.CodeMirror-linewidget {
  position: relative;
  z-index: 2;
  padding: 0.1px; /* Force widget margins to stay inside of the container */
}

.CodeMirror-widget {}

.CodeMirror-rtl pre { direction: rtl; }

.CodeMirror-code {
  outline: none;
}

/* Force content-box sizing for the elements where we expect it */
.CodeMirror-scroll,
.CodeMirror-sizer,
.CodeMirror-gutter,
.CodeMirror-gutters,
.CodeMirror-linenumber {
  -moz-box-sizing: content-box;
  box-sizing: content-box;
}

.CodeMirror-measure {
  position: absolute;
  width: 100%;
  height: 0;
  overflow: hidden;
  visibility: hidden;
}

.CodeMirror-cursor {
  position: absolute;
  pointer-events: none;
}
.CodeMirror-measure pre { position: static; }

div.CodeMirror-cursors {
  visibility: hidden;
  position: relative;
  z-index: 3;
}
div.CodeMirror-dragcursors {
  visibility: visible;
}

.CodeMirror-focused div.CodeMirror-cursors {
  visibility: visible;
}

.CodeMirror-selected { background: #d9d9d9; }
.CodeMirror-focused .CodeMirror-selected { background: #d7d4f0; }
.CodeMirror-crosshair { cursor: crosshair; }
.CodeMirror-line::selection, .CodeMirror-line > span::selection, .CodeMirror-line > span > span::selection { background: #d7d4f0; }
.CodeMirror-line::-moz-selection, .CodeMirror-line > span::-moz-selection, .CodeMirror-line > span > span::-moz-selection { background: #d7d4f0; }

.cm-searching {
  background-color: #ffa;
  background-color: rgba(255, 255, 0, .4);
}

/* Used to force a border model for a node */
.cm-force-border { padding-right: .1px; }

@media print {
  /* Hide the cursor when printing */
  .CodeMirror div.CodeMirror-cursors {
    visibility: hidden;
  }
}

/* See issue #2901 */
.cm-tab-wrap-hack:after { content: ''; }

/* Help users use markselection to safely style text background */
span.CodeMirror-selectedtext { background: none; }

.CodeMirror-dialog {
  position: absolute;
  left: 0; right: 0;
  background: inherit;
  z-index: 15;
  padding: .1em .8em;
  overflow: hidden;
  color: inherit;
}

.CodeMirror-dialog-top {
  border-bottom: 1px solid #eee;
  top: 0;
}

.CodeMirror-dialog-bottom {
  border-top: 1px solid #eee;
  bottom: 0;
}

.CodeMirror-dialog input {
  border: none;
  outline: none;
  background: transparent;
  width: 20em;
  color: inherit;
  font-family: monospace;
}

.CodeMirror-dialog button {
  font-size: 70%;
}

.CodeMirror-foldmarker {
  color: blue;
  text-shadow: #b9f 1px 1px 2px, #b9f -1px -1px 2px, #b9f 1px -1px 2px, #b9f -1px 1px 2px;
  font-family: arial;
  line-height: .3;
  cursor: pointer;
}
.CodeMirror-foldgutter {
  width: .7em;
}
.CodeMirror-foldgutter-open,
.CodeMirror-foldgutter-folded {
  cursor: pointer;
}
.CodeMirror-foldgutter-open:after {
  content: "\25BE";
}
.CodeMirror-foldgutter-folded:after {
  content: "\25B8";
}

/*
  Name:       material
  Author:     Mattia Astorino (http://github.com/equinusocio)
  Website:    https://material-theme.site/
*/

.cm-s-material.CodeMirror {
  background-color: #263238;
  color: #EEFFFF;
}

.cm-s-material .CodeMirror-gutters {
  background: #263238;
  color: #546E7A;
  border: none;
}

.cm-s-material .CodeMirror-guttermarker,
.cm-s-material .CodeMirror-guttermarker-subtle,
.cm-s-material .CodeMirror-linenumber {
  color: #546E7A;
}

.cm-s-material .CodeMirror-cursor {
  border-left: 1px solid #FFCC00;
}

.cm-s-material div.CodeMirror-selected {
  background: rgba(128, 203, 196, 0.2);
}

.cm-s-material.CodeMirror-focused div.CodeMirror-selected {
  background: rgba(128, 203, 196, 0.2);
}

.cm-s-material .CodeMirror-line::selection,
.cm-s-material .CodeMirror-line>span::selection,
.cm-s-material .CodeMirror-line>span>span::selection {
  background: rgba(128, 203, 196, 0.2);
}

.cm-s-material .CodeMirror-line::-moz-selection,
.cm-s-material .CodeMirror-line>span::-moz-selection,
.cm-s-material .CodeMirror-line>span>span::-moz-selection {
  background: rgba(128, 203, 196, 0.2);
}

.cm-s-material .CodeMirror-activeline-background {
  background: rgba(0, 0, 0, 0.5);
}

.cm-s-material .cm-keyword {
  color: #C792EA;
}

.cm-s-material .cm-operator {
  color: #89DDFF;
}

.cm-s-material .cm-variable-2 {
  color: #EEFFFF;
}

.cm-s-material .cm-variable-3,
.cm-s-material .cm-type {
  color: #f07178;
}

.cm-s-material .cm-builtin {
  color: #FFCB6B;
}

.cm-s-material .cm-atom {
  color: #F78C6C;
}

.cm-s-material .cm-number {
  color: #FF5370;
}

.cm-s-material .cm-def {
  color: #82AAFF;
}

.cm-s-material .cm-string {
  color: #C3E88D;
}

.cm-s-material .cm-string-2 {
  color: #f07178;
}

.cm-s-material .cm-comment {
  color: #546E7A;
}

.cm-s-material .cm-variable {
  color: #f07178;
}

.cm-s-material .cm-tag {
  color: #FF5370;
}

.cm-s-material .cm-meta {
  color: #FFCB6B;
}

.cm-s-material .cm-attribute {
  color: #C792EA;
}

.cm-s-material .cm-property {
  color: #C792EA;
}

.cm-s-material .cm-qualifier {
  color: #DECB6B;
}

.cm-s-material .cm-variable-3,
.cm-s-material .cm-type {
  color: #DECB6B;
}


.cm-s-material .cm-error {
  color: rgba(255, 255, 255, 1.0);
  background-color: #FF5370;
}

.cm-s-material .CodeMirror-matchingbracket {
  text-decoration: underline;
  color: white !important;
}
/**
 * "
 *  Using Zenburn color palette from the Emacs Zenburn Theme
 *  https://github.com/bbatsov/zenburn-emacs/blob/master/zenburn-theme.el
 *
 *  Also using parts of https://github.com/xavi/coderay-lighttable-theme
 * "
 * From: https://github.com/wisenomad/zenburn-lighttable-theme/blob/master/zenburn.css
 */

.cm-s-zenburn .CodeMirror-gutters { background: #3f3f3f !important; }
.cm-s-zenburn .CodeMirror-foldgutter-open, .CodeMirror-foldgutter-folded { color: #999; }
.cm-s-zenburn .CodeMirror-cursor { border-left: 1px solid white; }
.cm-s-zenburn { background-color: #3f3f3f; color: #dcdccc; }
.cm-s-zenburn span.cm-builtin { color: #dcdccc; font-weight: bold; }
.cm-s-zenburn span.cm-comment { color: #7f9f7f; }
.cm-s-zenburn span.cm-keyword { color: #f0dfaf; font-weight: bold; }
.cm-s-zenburn span.cm-atom { color: #bfebbf; }
.cm-s-zenburn span.cm-def { color: #dcdccc; }
.cm-s-zenburn span.cm-variable { color: #dfaf8f; }
.cm-s-zenburn span.cm-variable-2 { color: #dcdccc; }
.cm-s-zenburn span.cm-string { color: #cc9393; }
.cm-s-zenburn span.cm-string-2 { color: #cc9393; }
.cm-s-zenburn span.cm-number { color: #dcdccc; }
.cm-s-zenburn span.cm-tag { color: #93e0e3; }
.cm-s-zenburn span.cm-property { color: #dfaf8f; }
.cm-s-zenburn span.cm-attribute { color: #dfaf8f; }
.cm-s-zenburn span.cm-qualifier { color: #7cb8bb; }
.cm-s-zenburn span.cm-meta { color: #f0dfaf; }
.cm-s-zenburn span.cm-header { color: #f0efd0; }
.cm-s-zenburn span.cm-operator { color: #f0efd0; }
.cm-s-zenburn span.CodeMirror-matchingbracket { box-sizing: border-box; background: transparent; border-bottom: 1px solid; }
.cm-s-zenburn span.CodeMirror-nonmatchingbracket { border-bottom: 1px solid; background: none; }
.cm-s-zenburn .CodeMirror-activeline { background: #000000; }
.cm-s-zenburn .CodeMirror-activeline-background { background: #000000; }
.cm-s-zenburn div.CodeMirror-selected { background: #545454; }
.cm-s-zenburn .CodeMirror-focused div.CodeMirror-selected { background: #4f4f4f; }

.cm-s-abcdef.CodeMirror { background: #0f0f0f; color: #defdef; }
.cm-s-abcdef div.CodeMirror-selected { background: #515151; }
.cm-s-abcdef .CodeMirror-line::selection, .cm-s-abcdef .CodeMirror-line > span::selection, .cm-s-abcdef .CodeMirror-line > span > span::selection { background: rgba(56, 56, 56, 0.99); }
.cm-s-abcdef .CodeMirror-line::-moz-selection, .cm-s-abcdef .CodeMirror-line > span::-moz-selection, .cm-s-abcdef .CodeMirror-line > span > span::-moz-selection { background: rgba(56, 56, 56, 0.99); }
.cm-s-abcdef .CodeMirror-gutters { background: #555; border-right: 2px solid #314151; }
.cm-s-abcdef .CodeMirror-guttermarker { color: #222; }
.cm-s-abcdef .CodeMirror-guttermarker-subtle { color: azure; }
.cm-s-abcdef .CodeMirror-linenumber { color: #FFFFFF; }
.cm-s-abcdef .CodeMirror-cursor { border-left: 1px solid #00FF00; }

.cm-s-abcdef span.cm-keyword { color: darkgoldenrod; font-weight: bold; }
.cm-s-abcdef span.cm-atom { color: #77F; }
.cm-s-abcdef span.cm-number { color: violet; }
.cm-s-abcdef span.cm-def { color: #fffabc; }
.cm-s-abcdef span.cm-variable { color: #abcdef; }
.cm-s-abcdef span.cm-variable-2 { color: #cacbcc; }
.cm-s-abcdef span.cm-variable-3, .cm-s-abcdef span.cm-type { color: #def; }
.cm-s-abcdef span.cm-property { color: #fedcba; }
.cm-s-abcdef span.cm-operator { color: #ff0; }
.cm-s-abcdef span.cm-comment { color: #7a7b7c; font-style: italic;}
.cm-s-abcdef span.cm-string { color: #2b4; }
.cm-s-abcdef span.cm-meta { color: #C9F; }
.cm-s-abcdef span.cm-qualifier { color: #FFF700; }
.cm-s-abcdef span.cm-builtin { color: #30aabc; }
.cm-s-abcdef span.cm-bracket { color: #8a8a8a; }
.cm-s-abcdef span.cm-tag { color: #FFDD44; }
.cm-s-abcdef span.cm-attribute { color: #DDFF00; }
.cm-s-abcdef span.cm-error { color: #FF0000; }
.cm-s-abcdef span.cm-header { color: aquamarine; font-weight: bold; }
.cm-s-abcdef span.cm-link { color: blueviolet; }

.cm-s-abcdef .CodeMirror-activeline-background { background: #314151; }

/*

    Name:       Base16 Default Light
    Author:     Chris Kempson (http://chriskempson.com)

    CodeMirror template by Jan T. Sott (https://github.com/idleberg/base16-codemirror)
    Original Base16 color scheme by Chris Kempson (https://github.com/chriskempson/base16)

*/

.cm-s-base16-light.CodeMirror { background: #f5f5f5; color: #202020; }
.cm-s-base16-light div.CodeMirror-selected { background: #e0e0e0; }
.cm-s-base16-light .CodeMirror-line::selection, .cm-s-base16-light .CodeMirror-line > span::selection, .cm-s-base16-light .CodeMirror-line > span > span::selection { background: #e0e0e0; }
.cm-s-base16-light .CodeMirror-line::-moz-selection, .cm-s-base16-light .CodeMirror-line > span::-moz-selection, .cm-s-base16-light .CodeMirror-line > span > span::-moz-selection { background: #e0e0e0; }
.cm-s-base16-light .CodeMirror-gutters { background: #f5f5f5; border-right: 0px; }
.cm-s-base16-light .CodeMirror-guttermarker { color: #ac4142; }
.cm-s-base16-light .CodeMirror-guttermarker-subtle { color: #b0b0b0; }
.cm-s-base16-light .CodeMirror-linenumber { color: #b0b0b0; }
.cm-s-base16-light .CodeMirror-cursor { border-left: 1px solid #505050; }

.cm-s-base16-light span.cm-comment { color: #8f5536; }
.cm-s-base16-light span.cm-atom { color: #aa759f; }
.cm-s-base16-light span.cm-number { color: #aa759f; }

.cm-s-base16-light span.cm-property, .cm-s-base16-light span.cm-attribute { color: #90a959; }
.cm-s-base16-light span.cm-keyword { color: #ac4142; }
.cm-s-base16-light span.cm-string { color: #f4bf75; }

.cm-s-base16-light span.cm-variable { color: #90a959; }
.cm-s-base16-light span.cm-variable-2 { color: #6a9fb5; }
.cm-s-base16-light span.cm-def { color: #d28445; }
.cm-s-base16-light span.cm-bracket { color: #202020; }
.cm-s-base16-light span.cm-tag { color: #ac4142; }
.cm-s-base16-light span.cm-link { color: #aa759f; }
.cm-s-base16-light span.cm-error { background: #ac4142; color: #505050; }

.cm-s-base16-light .CodeMirror-activeline-background { background: #DDDCDC; }
.cm-s-base16-light .CodeMirror-matchingbracket { color: #f5f5f5 !important; background-color: #6A9FB5 !important}

/*

    Name:       Base16 Default Dark
    Author:     Chris Kempson (http://chriskempson.com)

    CodeMirror template by Jan T. Sott (https://github.com/idleberg/base16-codemirror)
    Original Base16 color scheme by Chris Kempson (https://github.com/chriskempson/base16)

*/

.cm-s-base16-dark.CodeMirror { background: #151515; color: #e0e0e0; }
.cm-s-base16-dark div.CodeMirror-selected { background: #303030; }
.cm-s-base16-dark .CodeMirror-line::selection, .cm-s-base16-dark .CodeMirror-line > span::selection, .cm-s-base16-dark .CodeMirror-line > span > span::selection { background: rgba(48, 48, 48, .99); }
.cm-s-base16-dark .CodeMirror-line::-moz-selection, .cm-s-base16-dark .CodeMirror-line > span::-moz-selection, .cm-s-base16-dark .CodeMirror-line > span > span::-moz-selection { background: rgba(48, 48, 48, .99); }
.cm-s-base16-dark .CodeMirror-gutters { background: #151515; border-right: 0px; }
.cm-s-base16-dark .CodeMirror-guttermarker { color: #ac4142; }
.cm-s-base16-dark .CodeMirror-guttermarker-subtle { color: #505050; }
.cm-s-base16-dark .CodeMirror-linenumber { color: #505050; }
.cm-s-base16-dark .CodeMirror-cursor { border-left: 1px solid #b0b0b0; }

.cm-s-base16-dark span.cm-comment { color: #8f5536; }
.cm-s-base16-dark span.cm-atom { color: #aa759f; }
.cm-s-base16-dark span.cm-number { color: #aa759f; }

.cm-s-base16-dark span.cm-property, .cm-s-base16-dark span.cm-attribute { color: #90a959; }
.cm-s-base16-dark span.cm-keyword { color: #ac4142; }
.cm-s-base16-dark span.cm-string { color: #f4bf75; }

.cm-s-base16-dark span.cm-variable { color: #90a959; }
.cm-s-base16-dark span.cm-variable-2 { color: #6a9fb5; }
.cm-s-base16-dark span.cm-def { color: #d28445; }
.cm-s-base16-dark span.cm-bracket { color: #e0e0e0; }
.cm-s-base16-dark span.cm-tag { color: #ac4142; }
.cm-s-base16-dark span.cm-link { color: #aa759f; }
.cm-s-base16-dark span.cm-error { background: #ac4142; color: #b0b0b0; }

.cm-s-base16-dark .CodeMirror-activeline-background { background: #202020; }
.cm-s-base16-dark .CodeMirror-matchingbracket { text-decoration: underline; color: white !important; }

/*

    Name:       dracula
    Author:     Michael Kaminsky (http://github.com/mkaminsky11)

    Original dracula color scheme by Zeno Rocha (https://github.com/zenorocha/dracula-theme)

*/


.cm-s-dracula.CodeMirror, .cm-s-dracula .CodeMirror-gutters {
  background-color: #282a36 !important;
  color: #f8f8f2 !important;
  border: none;
}
.cm-s-dracula .CodeMirror-gutters { color: #282a36; }
.cm-s-dracula .CodeMirror-cursor { border-left: solid thin #f8f8f0; }
.cm-s-dracula .CodeMirror-linenumber { color: #6D8A88; }
.cm-s-dracula .CodeMirror-selected { background: rgba(255, 255, 255, 0.10); }
.cm-s-dracula .CodeMirror-line::selection, .cm-s-dracula .CodeMirror-line > span::selection, .cm-s-dracula .CodeMirror-line > span > span::selection { background: rgba(255, 255, 255, 0.10); }
.cm-s-dracula .CodeMirror-line::-moz-selection, .cm-s-dracula .CodeMirror-line > span::-moz-selection, .cm-s-dracula .CodeMirror-line > span > span::-moz-selection { background: rgba(255, 255, 255, 0.10); }
.cm-s-dracula span.cm-comment { color: #6272a4; }
.cm-s-dracula span.cm-string, .cm-s-dracula span.cm-string-2 { color: #f1fa8c; }
.cm-s-dracula span.cm-number { color: #bd93f9; }
.cm-s-dracula span.cm-variable { color: #50fa7b; }
.cm-s-dracula span.cm-variable-2 { color: white; }
.cm-s-dracula span.cm-def { color: #50fa7b; }
.cm-s-dracula span.cm-operator { color: #ff79c6; }
.cm-s-dracula span.cm-keyword { color: #ff79c6; }
.cm-s-dracula span.cm-atom { color: #bd93f9; }
.cm-s-dracula span.cm-meta { color: #f8f8f2; }
.cm-s-dracula span.cm-tag { color: #ff79c6; }
.cm-s-dracula span.cm-attribute { color: #50fa7b; }
.cm-s-dracula span.cm-qualifier { color: #50fa7b; }
.cm-s-dracula span.cm-property { color: #66d9ef; }
.cm-s-dracula span.cm-builtin { color: #50fa7b; }
.cm-s-dracula span.cm-variable-3, .cm-s-dracula span.cm-type { color: #ffb86c; }

.cm-s-dracula .CodeMirror-activeline-background { background: rgba(255,255,255,0.1); }
.cm-s-dracula .CodeMirror-matchingbracket { text-decoration: underline; color: white !important; }

/*

    Name:       Hopscotch
    Author:     Jan T. Sott

    CodeMirror template by Jan T. Sott (https://github.com/idleberg/base16-codemirror)
    Original Base16 color scheme by Chris Kempson (https://github.com/chriskempson/base16)

*/

.cm-s-hopscotch.CodeMirror {background: #322931; color: #d5d3d5;}
.cm-s-hopscotch div.CodeMirror-selected {background: #433b42 !important;}
.cm-s-hopscotch .CodeMirror-gutters {background: #322931; border-right: 0px;}
.cm-s-hopscotch .CodeMirror-linenumber {color: #797379;}
.cm-s-hopscotch .CodeMirror-cursor {border-left: 1px solid #989498 !important;}

.cm-s-hopscotch span.cm-comment {color: #b33508;}
.cm-s-hopscotch span.cm-atom {color: #c85e7c;}
.cm-s-hopscotch span.cm-number {color: #c85e7c;}

.cm-s-hopscotch span.cm-property, .cm-s-hopscotch span.cm-attribute {color: #8fc13e;}
.cm-s-hopscotch span.cm-keyword {color: #dd464c;}
.cm-s-hopscotch span.cm-string {color: #fdcc59;}

.cm-s-hopscotch span.cm-variable {color: #8fc13e;}
.cm-s-hopscotch span.cm-variable-2 {color: #1290bf;}
.cm-s-hopscotch span.cm-def {color: #fd8b19;}
.cm-s-hopscotch span.cm-error {background: #dd464c; color: #989498;}
.cm-s-hopscotch span.cm-bracket {color: #d5d3d5;}
.cm-s-hopscotch span.cm-tag {color: #dd464c;}
.cm-s-hopscotch span.cm-link {color: #c85e7c;}

.cm-s-hopscotch .CodeMirror-matchingbracket { text-decoration: underline; color: white !important;}
.cm-s-hopscotch .CodeMirror-activeline-background { background: #302020; }

/****************************************************************/
/*   Based on mbonaci's Brackets mbo theme                      */
/*   https://github.com/mbonaci/global/blob/master/Mbo.tmTheme  */
/*   Create your own: http://tmtheme-editor.herokuapp.com       */
/****************************************************************/

.cm-s-mbo.CodeMirror { background: #2c2c2c; color: #ffffec; }
.cm-s-mbo div.CodeMirror-selected { background: #716C62; }
.cm-s-mbo .CodeMirror-line::selection, .cm-s-mbo .CodeMirror-line > span::selection, .cm-s-mbo .CodeMirror-line > span > span::selection { background: rgba(113, 108, 98, .99); }
.cm-s-mbo .CodeMirror-line::-moz-selection, .cm-s-mbo .CodeMirror-line > span::-moz-selection, .cm-s-mbo .CodeMirror-line > span > span::-moz-selection { background: rgba(113, 108, 98, .99); }
.cm-s-mbo .CodeMirror-gutters { background: #4e4e4e; border-right: 0px; }
.cm-s-mbo .CodeMirror-guttermarker { color: white; }
.cm-s-mbo .CodeMirror-guttermarker-subtle { color: grey; }
.cm-s-mbo .CodeMirror-linenumber { color: #dadada; }
.cm-s-mbo .CodeMirror-cursor { border-left: 1px solid #ffffec; }

.cm-s-mbo span.cm-comment { color: #95958a; }
.cm-s-mbo span.cm-atom { color: #00a8c6; }
.cm-s-mbo span.cm-number { color: #00a8c6; }

.cm-s-mbo span.cm-property, .cm-s-mbo span.cm-attribute { color: #9ddfe9; }
.cm-s-mbo span.cm-keyword { color: #ffb928; }
.cm-s-mbo span.cm-string { color: #ffcf6c; }
.cm-s-mbo span.cm-string.cm-property { color: #ffffec; }

.cm-s-mbo span.cm-variable { color: #ffffec; }
.cm-s-mbo span.cm-variable-2 { color: #00a8c6; }
.cm-s-mbo span.cm-def { color: #ffffec; }
.cm-s-mbo span.cm-bracket { color: #fffffc; font-weight: bold; }
.cm-s-mbo span.cm-tag { color: #9ddfe9; }
.cm-s-mbo span.cm-link { color: #f54b07; }
.cm-s-mbo span.cm-error { border-bottom: #636363; color: #ffffec; }
.cm-s-mbo span.cm-qualifier { color: #ffffec; }

.cm-s-mbo .CodeMirror-activeline-background { background: #494b41; }
.cm-s-mbo .CodeMirror-matchingbracket { color: #ffb928 !important; }
.cm-s-mbo .CodeMirror-matchingtag { background: rgba(255, 255, 255, .37); }

/*
  MDN-LIKE Theme - Mozilla
  Ported to CodeMirror by Peter Kroon <plakroon@gmail.com>
  Report bugs/issues here: https://github.com/codemirror/CodeMirror/issues
  GitHub: @peterkroon

  The mdn-like theme is inspired on the displayed code examples at: https://developer.mozilla.org/en-US/docs/Web/CSS/animation

*/
.cm-s-mdn-like.CodeMirror { color: #999; background-color: #fff; }
.cm-s-mdn-like div.CodeMirror-selected { background: #cfc; }
.cm-s-mdn-like .CodeMirror-line::selection, .cm-s-mdn-like .CodeMirror-line > span::selection, .cm-s-mdn-like .CodeMirror-line > span > span::selection { background: #cfc; }
.cm-s-mdn-like .CodeMirror-line::-moz-selection, .cm-s-mdn-like .CodeMirror-line > span::-moz-selection, .cm-s-mdn-like .CodeMirror-line > span > span::-moz-selection { background: #cfc; }

.cm-s-mdn-like .CodeMirror-gutters { background: #f8f8f8; border-left: 6px solid rgba(0,83,159,0.65); color: #333; }
.cm-s-mdn-like .CodeMirror-linenumber { color: #aaa; padding-left: 8px; }
.cm-s-mdn-like .CodeMirror-cursor { border-left: 2px solid #222; }

.cm-s-mdn-like .cm-keyword { color: #6262FF; }
.cm-s-mdn-like .cm-atom { color: #F90; }
.cm-s-mdn-like .cm-number { color:  #ca7841; }
.cm-s-mdn-like .cm-def { color: #8DA6CE; }
.cm-s-mdn-like span.cm-variable-2, .cm-s-mdn-like span.cm-tag { color: #690; }
.cm-s-mdn-like span.cm-variable-3, .cm-s-mdn-like span.cm-def, .cm-s-mdn-like span.cm-type { color: #07a; }

.cm-s-mdn-like .cm-variable { color: #07a; }
.cm-s-mdn-like .cm-property { color: #905; }
.cm-s-mdn-like .cm-qualifier { color: #690; }

.cm-s-mdn-like .cm-operator { color: #cda869; }
.cm-s-mdn-like .cm-comment { color:#777; font-weight:normal; }
.cm-s-mdn-like .cm-string { color:#07a; font-style:italic; }
.cm-s-mdn-like .cm-string-2 { color:#bd6b18; } /*?*/
.cm-s-mdn-like .cm-meta { color: #000; } /*?*/
.cm-s-mdn-like .cm-builtin { color: #9B7536; } /*?*/
.cm-s-mdn-like .cm-tag { color: #997643; }
.cm-s-mdn-like .cm-attribute { color: #d6bb6d; } /*?*/
.cm-s-mdn-like .cm-header { color: #FF6400; }
.cm-s-mdn-like .cm-hr { color: #AEAEAE; }
.cm-s-mdn-like .cm-link { color:#ad9361; font-style:italic; text-decoration:none; }
.cm-s-mdn-like .cm-error { border-bottom: 1px solid red; }

div.cm-s-mdn-like .CodeMirror-activeline-background { background: #efefff; }
div.cm-s-mdn-like span.CodeMirror-matchingbracket { outline:1px solid grey; color: inherit; }

.cm-s-mdn-like.CodeMirror { background-image: url(data:image/png;base64,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); }

/*

    Name:       seti
    Author:     Michael Kaminsky (http://github.com/mkaminsky11)

    Original seti color scheme by Jesse Weed (https://github.com/jesseweed/seti-syntax)

*/


.cm-s-seti.CodeMirror {
  background-color: #151718 !important;
  color: #CFD2D1 !important;
  border: none;
}
.cm-s-seti .CodeMirror-gutters {
  color: #404b53;
  background-color: #0E1112;
  border: none;
}
.cm-s-seti .CodeMirror-cursor { border-left: solid thin #f8f8f0; }
.cm-s-seti .CodeMirror-linenumber { color: #6D8A88; }
.cm-s-seti.CodeMirror-focused div.CodeMirror-selected { background: rgba(255, 255, 255, 0.10); }
.cm-s-seti .CodeMirror-line::selection, .cm-s-seti .CodeMirror-line > span::selection, .cm-s-seti .CodeMirror-line > span > span::selection { background: rgba(255, 255, 255, 0.10); }
.cm-s-seti .CodeMirror-line::-moz-selection, .cm-s-seti .CodeMirror-line > span::-moz-selection, .cm-s-seti .CodeMirror-line > span > span::-moz-selection { background: rgba(255, 255, 255, 0.10); }
.cm-s-seti span.cm-comment { color: #41535b; }
.cm-s-seti span.cm-string, .cm-s-seti span.cm-string-2 { color: #55b5db; }
.cm-s-seti span.cm-number { color: #cd3f45; }
.cm-s-seti span.cm-variable { color: #55b5db; }
.cm-s-seti span.cm-variable-2 { color: #a074c4; }
.cm-s-seti span.cm-def { color: #55b5db; }
.cm-s-seti span.cm-keyword { color: #ff79c6; }
.cm-s-seti span.cm-operator { color: #9fca56; }
.cm-s-seti span.cm-keyword { color: #e6cd69; }
.cm-s-seti span.cm-atom { color: #cd3f45; }
.cm-s-seti span.cm-meta { color: #55b5db; }
.cm-s-seti span.cm-tag { color: #55b5db; }
.cm-s-seti span.cm-attribute { color: #9fca56; }
.cm-s-seti span.cm-qualifier { color: #9fca56; }
.cm-s-seti span.cm-property { color: #a074c4; }
.cm-s-seti span.cm-variable-3, .cm-s-seti span.cm-type { color: #9fca56; }
.cm-s-seti span.cm-builtin { color: #9fca56; }
.cm-s-seti .CodeMirror-activeline-background { background: #101213; }
.cm-s-seti .CodeMirror-matchingbracket { text-decoration: underline; color: white !important; }

/*
Solarized theme for code-mirror
http://ethanschoonover.com/solarized
*/

/*
Solarized color palette
http://ethanschoonover.com/solarized/img/solarized-palette.png
*/

.solarized.base03 { color: #002b36; }
.solarized.base02 { color: #073642; }
.solarized.base01 { color: #586e75; }
.solarized.base00 { color: #657b83; }
.solarized.base0 { color: #839496; }
.solarized.base1 { color: #93a1a1; }
.solarized.base2 { color: #eee8d5; }
.solarized.base3  { color: #fdf6e3; }
.solarized.solar-yellow  { color: #b58900; }
.solarized.solar-orange  { color: #cb4b16; }
.solarized.solar-red { color: #dc322f; }
.solarized.solar-magenta { color: #d33682; }
.solarized.solar-violet  { color: #6c71c4; }
.solarized.solar-blue { color: #268bd2; }
.solarized.solar-cyan { color: #2aa198; }
.solarized.solar-green { color: #859900; }

/* Color scheme for code-mirror */

.cm-s-solarized {
  line-height: 1.45em;
  color-profile: sRGB;
  rendering-intent: auto;
}
.cm-s-solarized.cm-s-dark {
  color: #839496;
  background-color: #002b36;
  text-shadow: #002b36 0 1px;
}
.cm-s-solarized.cm-s-light {
  background-color: #fdf6e3;
  color: #657b83;
  text-shadow: #eee8d5 0 1px;
}

.cm-s-solarized .CodeMirror-widget {
  text-shadow: none;
}

.cm-s-solarized .cm-header { color: #586e75; }
.cm-s-solarized .cm-quote { color: #93a1a1; }

.cm-s-solarized .cm-keyword { color: #cb4b16; }
.cm-s-solarized .cm-atom { color: #d33682; }
.cm-s-solarized .cm-number { color: #d33682; }
.cm-s-solarized .cm-def { color: #2aa198; }

.cm-s-solarized .cm-variable { color: #839496; }
.cm-s-solarized .cm-variable-2 { color: #b58900; }
.cm-s-solarized .cm-variable-3, .cm-s-solarized .cm-type { color: #6c71c4; }

.cm-s-solarized .cm-property { color: #2aa198; }
.cm-s-solarized .cm-operator { color: #6c71c4; }

.cm-s-solarized .cm-comment { color: #586e75; font-style:italic; }

.cm-s-solarized .cm-string { color: #859900; }
.cm-s-solarized .cm-string-2 { color: #b58900; }

.cm-s-solarized .cm-meta { color: #859900; }
.cm-s-solarized .cm-qualifier { color: #b58900; }
.cm-s-solarized .cm-builtin { color: #d33682; }
.cm-s-solarized .cm-bracket { color: #cb4b16; }
.cm-s-solarized .CodeMirror-matchingbracket { color: #859900; }
.cm-s-solarized .CodeMirror-nonmatchingbracket { color: #dc322f; }
.cm-s-solarized .cm-tag { color: #93a1a1; }
.cm-s-solarized .cm-attribute { color: #2aa198; }
.cm-s-solarized .cm-hr {
  color: transparent;
  border-top: 1px solid #586e75;
  display: block;
}
.cm-s-solarized .cm-link { color: #93a1a1; cursor: pointer; }
.cm-s-solarized .cm-special { color: #6c71c4; }
.cm-s-solarized .cm-em {
  color: #999;
  text-decoration: underline;
  text-decoration-style: dotted;
}
.cm-s-solarized .cm-error,
.cm-s-solarized .cm-invalidchar {
  color: #586e75;
  border-bottom: 1px dotted #dc322f;
}

.cm-s-solarized.cm-s-dark div.CodeMirror-selected { background: #073642; }
.cm-s-solarized.cm-s-dark.CodeMirror ::selection { background: rgba(7, 54, 66, 0.99); }
.cm-s-solarized.cm-s-dark .CodeMirror-line::-moz-selection, .cm-s-dark .CodeMirror-line > span::-moz-selection, .cm-s-dark .CodeMirror-line > span > span::-moz-selection { background: rgba(7, 54, 66, 0.99); }

.cm-s-solarized.cm-s-light div.CodeMirror-selected { background: #eee8d5; }
.cm-s-solarized.cm-s-light .CodeMirror-line::selection, .cm-s-light .CodeMirror-line > span::selection, .cm-s-light .CodeMirror-line > span > span::selection { background: #eee8d5; }
.cm-s-solarized.cm-s-light .CodeMirror-line::-moz-selection, .cm-s-ligh .CodeMirror-line > span::-moz-selection, .cm-s-ligh .CodeMirror-line > span > span::-moz-selection { background: #eee8d5; }

/* Editor styling */



/* Little shadow on the view-port of the buffer view */
.cm-s-solarized.CodeMirror {
  -moz-box-shadow: inset 7px 0 12px -6px #000;
  -webkit-box-shadow: inset 7px 0 12px -6px #000;
  box-shadow: inset 7px 0 12px -6px #000;
}

/* Remove gutter border */
.cm-s-solarized .CodeMirror-gutters {
  border-right: 0;
}

/* Gutter colors and line number styling based of color scheme (dark / light) */

/* Dark */
.cm-s-solarized.cm-s-dark .CodeMirror-gutters {
  background-color: #073642;
}

.cm-s-solarized.cm-s-dark .CodeMirror-linenumber {
  color: #586e75;
  text-shadow: #021014 0 -1px;
}

/* Light */
.cm-s-solarized.cm-s-light .CodeMirror-gutters {
  background-color: #eee8d5;
}

.cm-s-solarized.cm-s-light .CodeMirror-linenumber {
  color: #839496;
}

/* Common */
.cm-s-solarized .CodeMirror-linenumber {
  padding: 0 5px;
}
.cm-s-solarized .CodeMirror-guttermarker-subtle { color: #586e75; }
.cm-s-solarized.cm-s-dark .CodeMirror-guttermarker { color: #ddd; }
.cm-s-solarized.cm-s-light .CodeMirror-guttermarker { color: #cb4b16; }

.cm-s-solarized .CodeMirror-gutter .CodeMirror-gutter-text {
  color: #586e75;
}

/* Cursor */
.cm-s-solarized .CodeMirror-cursor { border-left: 1px solid #819090; }

/* Fat cursor */
.cm-s-solarized.cm-s-light.cm-fat-cursor .CodeMirror-cursor { background: #77ee77; }
.cm-s-solarized.cm-s-light .cm-animate-fat-cursor { background-color: #77ee77; }
.cm-s-solarized.cm-s-dark.cm-fat-cursor .CodeMirror-cursor { background: #586e75; }
.cm-s-solarized.cm-s-dark .cm-animate-fat-cursor { background-color: #586e75; }

/* Active line */
.cm-s-solarized.cm-s-dark .CodeMirror-activeline-background {
  background: rgba(255, 255, 255, 0.06);
}
.cm-s-solarized.cm-s-light .CodeMirror-activeline-background {
  background: rgba(0, 0, 0, 0.06);
}

.cm-s-the-matrix.CodeMirror { background: #000000; color: #00FF00; }
.cm-s-the-matrix div.CodeMirror-selected { background: #2D2D2D; }
.cm-s-the-matrix .CodeMirror-line::selection, .cm-s-the-matrix .CodeMirror-line > span::selection, .cm-s-the-matrix .CodeMirror-line > span > span::selection { background: rgba(45, 45, 45, 0.99); }
.cm-s-the-matrix .CodeMirror-line::-moz-selection, .cm-s-the-matrix .CodeMirror-line > span::-moz-selection, .cm-s-the-matrix .CodeMirror-line > span > span::-moz-selection { background: rgba(45, 45, 45, 0.99); }
.cm-s-the-matrix .CodeMirror-gutters { background: #060; border-right: 2px solid #00FF00; }
.cm-s-the-matrix .CodeMirror-guttermarker { color: #0f0; }
.cm-s-the-matrix .CodeMirror-guttermarker-subtle { color: white; }
.cm-s-the-matrix .CodeMirror-linenumber { color: #FFFFFF; }
.cm-s-the-matrix .CodeMirror-cursor { border-left: 1px solid #00FF00; }

.cm-s-the-matrix span.cm-keyword { color: #008803; font-weight: bold; }
.cm-s-the-matrix span.cm-atom { color: #3FF; }
.cm-s-the-matrix span.cm-number { color: #FFB94F; }
.cm-s-the-matrix span.cm-def { color: #99C; }
.cm-s-the-matrix span.cm-variable { color: #F6C; }
.cm-s-the-matrix span.cm-variable-2 { color: #C6F; }
.cm-s-the-matrix span.cm-variable-3, .cm-s-the-matrix span.cm-type { color: #96F; }
.cm-s-the-matrix span.cm-property { color: #62FFA0; }
.cm-s-the-matrix span.cm-operator { color: #999; }
.cm-s-the-matrix span.cm-comment { color: #CCCCCC; }
.cm-s-the-matrix span.cm-string { color: #39C; }
.cm-s-the-matrix span.cm-meta { color: #C9F; }
.cm-s-the-matrix span.cm-qualifier { color: #FFF700; }
.cm-s-the-matrix span.cm-builtin { color: #30a; }
.cm-s-the-matrix span.cm-bracket { color: #cc7; }
.cm-s-the-matrix span.cm-tag { color: #FFBD40; }
.cm-s-the-matrix span.cm-attribute { color: #FFF700; }
.cm-s-the-matrix span.cm-error { color: #FF0000; }

.cm-s-the-matrix .CodeMirror-activeline-background { background: #040; }

/*
Copyright (C) 2011 by MarkLogic Corporation
Author: Mike Brevoort <mike@brevoort.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
*/
.cm-s-xq-light span.cm-keyword { line-height: 1em; font-weight: bold; color: #5A5CAD; }
.cm-s-xq-light span.cm-atom { color: #6C8CD5; }
.cm-s-xq-light span.cm-number { color: #164; }
.cm-s-xq-light span.cm-def { text-decoration:underline; }
.cm-s-xq-light span.cm-variable { color: black; }
.cm-s-xq-light span.cm-variable-2 { color:black; }
.cm-s-xq-light span.cm-variable-3, .cm-s-xq-light span.cm-type { color: black; }
.cm-s-xq-light span.cm-property {}
.cm-s-xq-light span.cm-operator {}
.cm-s-xq-light span.cm-comment { color: #0080FF; font-style: italic; }
.cm-s-xq-light span.cm-string { color: red; }
.cm-s-xq-light span.cm-meta { color: yellow; }
.cm-s-xq-light span.cm-qualifier { color: grey; }
.cm-s-xq-light span.cm-builtin { color: #7EA656; }
.cm-s-xq-light span.cm-bracket { color: #cc7; }
.cm-s-xq-light span.cm-tag { color: #3F7F7F; }
.cm-s-xq-light span.cm-attribute { color: #7F007F; }
.cm-s-xq-light span.cm-error { color: #f00; }

.cm-s-xq-light .CodeMirror-activeline-background { background: #e8f2ff; }
.cm-s-xq-light .CodeMirror-matchingbracket { outline:1px solid grey;color:black !important;background:yellow; }

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.CodeMirror {
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  font-family: var(--jp-code-font-family);
  border: 0;
  border-radius: 0;
  height: auto;
  /* Changed to auto to autogrow */
}

.CodeMirror pre {
  padding: 0 var(--jp-code-padding);
}

.jp-CodeMirrorEditor[data-type='inline'] .CodeMirror-dialog {
  background-color: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
}

/* This causes https://github.com/jupyter/jupyterlab/issues/522 */
/* May not cause it not because we changed it! */
.CodeMirror-lines {
  padding: var(--jp-code-padding) 0;
}

.CodeMirror-linenumber {
  padding: 0 8px;
}

.jp-CodeMirrorEditor-static {
  margin: var(--jp-code-padding);
}

.jp-CodeMirrorEditor,
.jp-CodeMirrorEditor-static {
  cursor: text;
}

.jp-CodeMirrorEditor[data-type='inline'] .CodeMirror-cursor {
  border-left: var(--jp-code-cursor-width0) solid var(--jp-editor-cursor-color);
}

/* When zoomed out 67% and 33% on a screen of 1440 width x 900 height */
@media screen and (min-width: 2138px) and (max-width: 4319px) {
  .jp-CodeMirrorEditor[data-type='inline'] .CodeMirror-cursor {
    border-left: var(--jp-code-cursor-width1) solid
      var(--jp-editor-cursor-color);
  }
}

/* When zoomed out less than 33% */
@media screen and (min-width: 4320px) {
  .jp-CodeMirrorEditor[data-type='inline'] .CodeMirror-cursor {
    border-left: var(--jp-code-cursor-width2) solid
      var(--jp-editor-cursor-color);
  }
}

.CodeMirror.jp-mod-readOnly .CodeMirror-cursor {
  display: none;
}

.CodeMirror-gutters {
  border-right: 1px solid var(--jp-border-color2);
  background-color: var(--jp-layout-color0);
}

.jp-CollaboratorCursor {
  border-left: 5px solid transparent;
  border-right: 5px solid transparent;
  border-top: none;
  border-bottom: 3px solid;
  background-clip: content-box;
  margin-left: -5px;
  margin-right: -5px;
}

.CodeMirror-selectedtext.cm-searching {
  background-color: var(--jp-search-selected-match-background-color) !important;
  color: var(--jp-search-selected-match-color) !important;
}

.cm-searching {
  background-color: var(
    --jp-search-unselected-match-background-color
  ) !important;
  color: var(--jp-search-unselected-match-color) !important;
}

.CodeMirror-focused .CodeMirror-selected {
  background-color: var(--jp-editor-selected-focused-background);
}

.CodeMirror-selected {
  background-color: var(--jp-editor-selected-background);
}

.jp-CollaboratorCursor-hover {
  position: absolute;
  z-index: 1;
  transform: translateX(-50%);
  color: white;
  border-radius: 3px;
  padding-left: 4px;
  padding-right: 4px;
  padding-top: 1px;
  padding-bottom: 1px;
  text-align: center;
  font-size: var(--jp-ui-font-size1);
  white-space: nowrap;
}

.jp-CodeMirror-ruler {
  border-left: 1px dashed var(--jp-border-color2);
}

/**
 * Here is our jupyter theme for CodeMirror syntax highlighting
 * This is used in our marked.js syntax highlighting and CodeMirror itself
 * The string "jupyter" is set in ../codemirror/widget.DEFAULT_CODEMIRROR_THEME
 * This came from the classic notebook, which came form highlight.js/GitHub
 */

/**
 * CodeMirror themes are handling the background/color in this way. This works
 * fine for CodeMirror editors outside the notebook, but the notebook styles
 * these things differently.
 */
.CodeMirror.cm-s-jupyter {
  background: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
}

/* In the notebook, we want this styling to be handled by its container */
.jp-CodeConsole .CodeMirror.cm-s-jupyter,
.jp-Notebook .CodeMirror.cm-s-jupyter {
  background: transparent;
}

.cm-s-jupyter .CodeMirror-cursor {
  border-left: var(--jp-code-cursor-width0) solid var(--jp-editor-cursor-color);
}
.cm-s-jupyter span.cm-keyword {
  color: var(--jp-mirror-editor-keyword-color);
  font-weight: bold;
}
.cm-s-jupyter span.cm-atom {
  color: var(--jp-mirror-editor-atom-color);
}
.cm-s-jupyter span.cm-number {
  color: var(--jp-mirror-editor-number-color);
}
.cm-s-jupyter span.cm-def {
  color: var(--jp-mirror-editor-def-color);
}
.cm-s-jupyter span.cm-variable {
  color: var(--jp-mirror-editor-variable-color);
}
.cm-s-jupyter span.cm-variable-2 {
  color: var(--jp-mirror-editor-variable-2-color);
}
.cm-s-jupyter span.cm-variable-3 {
  color: var(--jp-mirror-editor-variable-3-color);
}
.cm-s-jupyter span.cm-punctuation {
  color: var(--jp-mirror-editor-punctuation-color);
}
.cm-s-jupyter span.cm-property {
  color: var(--jp-mirror-editor-property-color);
}
.cm-s-jupyter span.cm-operator {
  color: var(--jp-mirror-editor-operator-color);
  font-weight: bold;
}
.cm-s-jupyter span.cm-comment {
  color: var(--jp-mirror-editor-comment-color);
  font-style: italic;
}
.cm-s-jupyter span.cm-string {
  color: var(--jp-mirror-editor-string-color);
}
.cm-s-jupyter span.cm-string-2 {
  color: var(--jp-mirror-editor-string-2-color);
}
.cm-s-jupyter span.cm-meta {
  color: var(--jp-mirror-editor-meta-color);
}
.cm-s-jupyter span.cm-qualifier {
  color: var(--jp-mirror-editor-qualifier-color);
}
.cm-s-jupyter span.cm-builtin {
  color: var(--jp-mirror-editor-builtin-color);
}
.cm-s-jupyter span.cm-bracket {
  color: var(--jp-mirror-editor-bracket-color);
}
.cm-s-jupyter span.cm-tag {
  color: var(--jp-mirror-editor-tag-color);
}
.cm-s-jupyter span.cm-attribute {
  color: var(--jp-mirror-editor-attribute-color);
}
.cm-s-jupyter span.cm-header {
  color: var(--jp-mirror-editor-header-color);
}
.cm-s-jupyter span.cm-quote {
  color: var(--jp-mirror-editor-quote-color);
}
.cm-s-jupyter span.cm-link {
  color: var(--jp-mirror-editor-link-color);
}
.cm-s-jupyter span.cm-error {
  color: var(--jp-mirror-editor-error-color);
}
.cm-s-jupyter span.cm-hr {
  color: #999;
}

.cm-s-jupyter span.cm-tab {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=);
  background-position: right;
  background-repeat: no-repeat;
}

.cm-s-jupyter .CodeMirror-activeline-background,
.cm-s-jupyter .CodeMirror-gutter {
  background-color: var(--jp-layout-color2);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| RenderedText
|----------------------------------------------------------------------------*/

.jp-RenderedText {
  text-align: left;
  padding-left: var(--jp-code-padding);
  line-height: var(--jp-code-line-height);
  font-family: var(--jp-code-font-family);
}

.jp-RenderedText pre,
.jp-RenderedJavaScript pre,
.jp-RenderedHTMLCommon pre {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-code-font-size);
  border: none;
  margin: 0px;
  padding: 0px;
  line-height: normal;
}

.jp-RenderedText pre a:link {
  text-decoration: none;
  color: var(--jp-content-link-color);
}
.jp-RenderedText pre a:hover {
  text-decoration: underline;
  color: var(--jp-content-link-color);
}
.jp-RenderedText pre a:visited {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

/* console foregrounds and backgrounds */
.jp-RenderedText pre .ansi-black-fg {
  color: #3e424d;
}
.jp-RenderedText pre .ansi-red-fg {
  color: #e75c58;
}
.jp-RenderedText pre .ansi-green-fg {
  color: #00a250;
}
.jp-RenderedText pre .ansi-yellow-fg {
  color: #ddb62b;
}
.jp-RenderedText pre .ansi-blue-fg {
  color: #208ffb;
}
.jp-RenderedText pre .ansi-magenta-fg {
  color: #d160c4;
}
.jp-RenderedText pre .ansi-cyan-fg {
  color: #60c6c8;
}
.jp-RenderedText pre .ansi-white-fg {
  color: #c5c1b4;
}

.jp-RenderedText pre .ansi-black-bg {
  background-color: #3e424d;
}
.jp-RenderedText pre .ansi-red-bg {
  background-color: #e75c58;
}
.jp-RenderedText pre .ansi-green-bg {
  background-color: #00a250;
}
.jp-RenderedText pre .ansi-yellow-bg {
  background-color: #ddb62b;
}
.jp-RenderedText pre .ansi-blue-bg {
  background-color: #208ffb;
}
.jp-RenderedText pre .ansi-magenta-bg {
  background-color: #d160c4;
}
.jp-RenderedText pre .ansi-cyan-bg {
  background-color: #60c6c8;
}
.jp-RenderedText pre .ansi-white-bg {
  background-color: #c5c1b4;
}

.jp-RenderedText pre .ansi-black-intense-fg {
  color: #282c36;
}
.jp-RenderedText pre .ansi-red-intense-fg {
  color: #b22b31;
}
.jp-RenderedText pre .ansi-green-intense-fg {
  color: #007427;
}
.jp-RenderedText pre .ansi-yellow-intense-fg {
  color: #b27d12;
}
.jp-RenderedText pre .ansi-blue-intense-fg {
  color: #0065ca;
}
.jp-RenderedText pre .ansi-magenta-intense-fg {
  color: #a03196;
}
.jp-RenderedText pre .ansi-cyan-intense-fg {
  color: #258f8f;
}
.jp-RenderedText pre .ansi-white-intense-fg {
  color: #a1a6b2;
}

.jp-RenderedText pre .ansi-black-intense-bg {
  background-color: #282c36;
}
.jp-RenderedText pre .ansi-red-intense-bg {
  background-color: #b22b31;
}
.jp-RenderedText pre .ansi-green-intense-bg {
  background-color: #007427;
}
.jp-RenderedText pre .ansi-yellow-intense-bg {
  background-color: #b27d12;
}
.jp-RenderedText pre .ansi-blue-intense-bg {
  background-color: #0065ca;
}
.jp-RenderedText pre .ansi-magenta-intense-bg {
  background-color: #a03196;
}
.jp-RenderedText pre .ansi-cyan-intense-bg {
  background-color: #258f8f;
}
.jp-RenderedText pre .ansi-white-intense-bg {
  background-color: #a1a6b2;
}

.jp-RenderedText pre .ansi-default-inverse-fg {
  color: var(--jp-ui-inverse-font-color0);
}
.jp-RenderedText pre .ansi-default-inverse-bg {
  background-color: var(--jp-inverse-layout-color0);
}

.jp-RenderedText pre .ansi-bold {
  font-weight: bold;
}
.jp-RenderedText pre .ansi-underline {
  text-decoration: underline;
}

.jp-RenderedText[data-mime-type='application/vnd.jupyter.stderr'] {
  background: var(--jp-rendermime-error-background);
  padding-top: var(--jp-code-padding);
}

/*-----------------------------------------------------------------------------
| RenderedLatex
|----------------------------------------------------------------------------*/

.jp-RenderedLatex {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-content-font-size1);
  line-height: var(--jp-content-line-height);
}

/* Left-justify outputs.*/
.jp-OutputArea-output.jp-RenderedLatex {
  padding: var(--jp-code-padding);
  text-align: left;
}

/*-----------------------------------------------------------------------------
| RenderedHTML
|----------------------------------------------------------------------------*/

.jp-RenderedHTMLCommon {
  color: var(--jp-content-font-color1);
  font-family: var(--jp-content-font-family);
  font-size: var(--jp-content-font-size1);
  line-height: var(--jp-content-line-height);
  /* Give a bit more R padding on Markdown text to keep line lengths reasonable */
  padding-right: 20px;
}

.jp-RenderedHTMLCommon em {
  font-style: italic;
}

.jp-RenderedHTMLCommon strong {
  font-weight: bold;
}

.jp-RenderedHTMLCommon u {
  text-decoration: underline;
}

.jp-RenderedHTMLCommon a:link {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

.jp-RenderedHTMLCommon a:hover {
  text-decoration: underline;
  color: var(--jp-content-link-color);
}

.jp-RenderedHTMLCommon a:visited {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

/* Headings */

.jp-RenderedHTMLCommon h1,
.jp-RenderedHTMLCommon h2,
.jp-RenderedHTMLCommon h3,
.jp-RenderedHTMLCommon h4,
.jp-RenderedHTMLCommon h5,
.jp-RenderedHTMLCommon h6 {
  line-height: var(--jp-content-heading-line-height);
  font-weight: var(--jp-content-heading-font-weight);
  font-style: normal;
  margin: var(--jp-content-heading-margin-top) 0
    var(--jp-content-heading-margin-bottom) 0;
}

.jp-RenderedHTMLCommon h1:first-child,
.jp-RenderedHTMLCommon h2:first-child,
.jp-RenderedHTMLCommon h3:first-child,
.jp-RenderedHTMLCommon h4:first-child,
.jp-RenderedHTMLCommon h5:first-child,
.jp-RenderedHTMLCommon h6:first-child {
  margin-top: calc(0.5 * var(--jp-content-heading-margin-top));
}

.jp-RenderedHTMLCommon h1:last-child,
.jp-RenderedHTMLCommon h2:last-child,
.jp-RenderedHTMLCommon h3:last-child,
.jp-RenderedHTMLCommon h4:last-child,
.jp-RenderedHTMLCommon h5:last-child,
.jp-RenderedHTMLCommon h6:last-child {
  margin-bottom: calc(0.5 * var(--jp-content-heading-margin-bottom));
}

.jp-RenderedHTMLCommon h1 {
  font-size: var(--jp-content-font-size5);
}

.jp-RenderedHTMLCommon h2 {
  font-size: var(--jp-content-font-size4);
}

.jp-RenderedHTMLCommon h3 {
  font-size: var(--jp-content-font-size3);
}

.jp-RenderedHTMLCommon h4 {
  font-size: var(--jp-content-font-size2);
}

.jp-RenderedHTMLCommon h5 {
  font-size: var(--jp-content-font-size1);
}

.jp-RenderedHTMLCommon h6 {
  font-size: var(--jp-content-font-size0);
}

/* Lists */

.jp-RenderedHTMLCommon ul:not(.list-inline),
.jp-RenderedHTMLCommon ol:not(.list-inline) {
  padding-left: 2em;
}

.jp-RenderedHTMLCommon ul {
  list-style: disc;
}

.jp-RenderedHTMLCommon ul ul {
  list-style: square;
}

.jp-RenderedHTMLCommon ul ul ul {
  list-style: circle;
}

.jp-RenderedHTMLCommon ol {
  list-style: decimal;
}

.jp-RenderedHTMLCommon ol ol {
  list-style: upper-alpha;
}

.jp-RenderedHTMLCommon ol ol ol {
  list-style: lower-alpha;
}

.jp-RenderedHTMLCommon ol ol ol ol {
  list-style: lower-roman;
}

.jp-RenderedHTMLCommon ol ol ol ol ol {
  list-style: decimal;
}

.jp-RenderedHTMLCommon ol,
.jp-RenderedHTMLCommon ul {
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon ul ul,
.jp-RenderedHTMLCommon ul ol,
.jp-RenderedHTMLCommon ol ul,
.jp-RenderedHTMLCommon ol ol {
  margin-bottom: 0em;
}

.jp-RenderedHTMLCommon hr {
  color: var(--jp-border-color2);
  background-color: var(--jp-border-color1);
  margin-top: 1em;
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon > pre {
  margin: 1.5em 2em;
}

.jp-RenderedHTMLCommon pre,
.jp-RenderedHTMLCommon code {
  border: 0;
  background-color: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
  font-family: var(--jp-code-font-family);
  font-size: inherit;
  line-height: var(--jp-code-line-height);
  padding: 0;
  white-space: pre-wrap;
}

.jp-RenderedHTMLCommon :not(pre) > code {
  background-color: var(--jp-layout-color2);
  padding: 1px 5px;
}

/* Tables */

.jp-RenderedHTMLCommon table {
  border-collapse: collapse;
  border-spacing: 0;
  border: none;
  color: var(--jp-ui-font-color1);
  font-size: 12px;
  table-layout: fixed;
  margin-left: auto;
  margin-right: auto;
}

.jp-RenderedHTMLCommon thead {
  border-bottom: var(--jp-border-width) solid var(--jp-border-color1);
  vertical-align: bottom;
}

.jp-RenderedHTMLCommon td,
.jp-RenderedHTMLCommon th,
.jp-RenderedHTMLCommon tr {
  vertical-align: middle;
  padding: 0.5em 0.5em;
  line-height: normal;
  white-space: normal;
  max-width: none;
  border: none;
}

.jp-RenderedMarkdown.jp-RenderedHTMLCommon td,
.jp-RenderedMarkdown.jp-RenderedHTMLCommon th {
  max-width: none;
}

:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon td,
:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon th,
:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon tr {
  text-align: right;
}

.jp-RenderedHTMLCommon th {
  font-weight: bold;
}

.jp-RenderedHTMLCommon tbody tr:nth-child(odd) {
  background: var(--jp-layout-color0);
}

.jp-RenderedHTMLCommon tbody tr:nth-child(even) {
  background: var(--jp-rendermime-table-row-background);
}

.jp-RenderedHTMLCommon tbody tr:hover {
  background: var(--jp-rendermime-table-row-hover-background);
}

.jp-RenderedHTMLCommon table {
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon p {
  text-align: left;
  margin: 0px;
}

.jp-RenderedHTMLCommon p {
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon img {
  -moz-force-broken-image-icon: 1;
}

/* Restrict to direct children as other images could be nested in other content. */
.jp-RenderedHTMLCommon > img {
  display: block;
  margin-left: 0;
  margin-right: 0;
  margin-bottom: 1em;
}

/* Change color behind transparent images if they need it... */
[data-jp-theme-light='false'] .jp-RenderedImage img.jp-needs-light-background {
  background-color: var(--jp-inverse-layout-color1);
}
[data-jp-theme-light='true'] .jp-RenderedImage img.jp-needs-dark-background {
  background-color: var(--jp-inverse-layout-color1);
}
/* ...or leave it untouched if they don't */
[data-jp-theme-light='false'] .jp-RenderedImage img.jp-needs-dark-background {
}
[data-jp-theme-light='true'] .jp-RenderedImage img.jp-needs-light-background {
}

.jp-RenderedHTMLCommon img,
.jp-RenderedImage img,
.jp-RenderedHTMLCommon svg,
.jp-RenderedSVG svg {
  max-width: 100%;
  height: auto;
}

.jp-RenderedHTMLCommon img.jp-mod-unconfined,
.jp-RenderedImage img.jp-mod-unconfined,
.jp-RenderedHTMLCommon svg.jp-mod-unconfined,
.jp-RenderedSVG svg.jp-mod-unconfined {
  max-width: none;
}

.jp-RenderedHTMLCommon .alert {
  padding: var(--jp-notebook-padding);
  border: var(--jp-border-width) solid transparent;
  border-radius: var(--jp-border-radius);
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon .alert-info {
  color: var(--jp-info-color0);
  background-color: var(--jp-info-color3);
  border-color: var(--jp-info-color2);
}
.jp-RenderedHTMLCommon .alert-info hr {
  border-color: var(--jp-info-color3);
}
.jp-RenderedHTMLCommon .alert-info > p:last-child,
.jp-RenderedHTMLCommon .alert-info > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-warning {
  color: var(--jp-warn-color0);
  background-color: var(--jp-warn-color3);
  border-color: var(--jp-warn-color2);
}
.jp-RenderedHTMLCommon .alert-warning hr {
  border-color: var(--jp-warn-color3);
}
.jp-RenderedHTMLCommon .alert-warning > p:last-child,
.jp-RenderedHTMLCommon .alert-warning > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-success {
  color: var(--jp-success-color0);
  background-color: var(--jp-success-color3);
  border-color: var(--jp-success-color2);
}
.jp-RenderedHTMLCommon .alert-success hr {
  border-color: var(--jp-success-color3);
}
.jp-RenderedHTMLCommon .alert-success > p:last-child,
.jp-RenderedHTMLCommon .alert-success > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-danger {
  color: var(--jp-error-color0);
  background-color: var(--jp-error-color3);
  border-color: var(--jp-error-color2);
}
.jp-RenderedHTMLCommon .alert-danger hr {
  border-color: var(--jp-error-color3);
}
.jp-RenderedHTMLCommon .alert-danger > p:last-child,
.jp-RenderedHTMLCommon .alert-danger > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon blockquote {
  margin: 1em 2em;
  padding: 0 1em;
  border-left: 5px solid var(--jp-border-color2);
}

a.jp-InternalAnchorLink {
  visibility: hidden;
  margin-left: 8px;
  color: var(--md-blue-800);
}

h1:hover .jp-InternalAnchorLink,
h2:hover .jp-InternalAnchorLink,
h3:hover .jp-InternalAnchorLink,
h4:hover .jp-InternalAnchorLink,
h5:hover .jp-InternalAnchorLink,
h6:hover .jp-InternalAnchorLink {
  visibility: visible;
}

.jp-RenderedHTMLCommon kbd {
  background-color: var(--jp-rendermime-table-row-background);
  border: 1px solid var(--jp-border-color0);
  border-bottom-color: var(--jp-border-color2);
  border-radius: 3px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
  display: inline-block;
  font-size: 0.8em;
  line-height: 1em;
  padding: 0.2em 0.5em;
}

/* Most direct children of .jp-RenderedHTMLCommon have a margin-bottom of 1.0.
 * At the bottom of cells this is a bit too much as there is also spacing
 * between cells. Going all the way to 0 gets too tight between markdown and
 * code cells.
 */
.jp-RenderedHTMLCommon > *:last-child {
  margin-bottom: 0.5em;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-MimeDocument {
  outline: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-filebrowser-button-height: 28px;
  --jp-private-filebrowser-button-width: 48px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-FileBrowser {
  display: flex;
  flex-direction: column;
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);
  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
}

.jp-FileBrowser-toolbar.jp-Toolbar {
  border-bottom: none;
  height: auto;
  margin: var(--jp-toolbar-header-margin);
  box-shadow: none;
}

.jp-BreadCrumbs {
  flex: 0 0 auto;
  margin: 4px 12px;
}

.jp-BreadCrumbs-item {
  margin: 0px 2px;
  padding: 0px 2px;
  border-radius: var(--jp-border-radius);
  cursor: pointer;
}

.jp-BreadCrumbs-item:hover {
  background-color: var(--jp-layout-color2);
}

.jp-BreadCrumbs-item:first-child {
  margin-left: 0px;
}

.jp-BreadCrumbs-item.jp-mod-dropTarget {
  background-color: var(--jp-brand-color2);
  opacity: 0.7;
}

/*-----------------------------------------------------------------------------
| Buttons
|----------------------------------------------------------------------------*/

.jp-FileBrowser-toolbar.jp-Toolbar {
  padding: 0px;
}

.jp-FileBrowser-toolbar.jp-Toolbar {
  justify-content: space-evenly;
}

.jp-FileBrowser-toolbar.jp-Toolbar .jp-Toolbar-item {
  flex: 1;
}

.jp-FileBrowser-toolbar.jp-Toolbar .jp-ToolbarButtonComponent {
  width: 100%;
}

/*-----------------------------------------------------------------------------
| DirListing
|----------------------------------------------------------------------------*/

.jp-DirListing {
  flex: 1 1 auto;
  display: flex;
  flex-direction: column;
  outline: 0;
}

.jp-DirListing-header {
  flex: 0 0 auto;
  display: flex;
  flex-direction: row;
  overflow: hidden;
  border-top: var(--jp-border-width) solid var(--jp-border-color2);
  border-bottom: var(--jp-border-width) solid var(--jp-border-color1);
  box-shadow: var(--jp-toolbar-box-shadow);
  z-index: 2;
}

.jp-DirListing-headerItem {
  padding: 4px 12px 2px 12px;
  font-weight: 500;
}

.jp-DirListing-headerItem:hover {
  background: var(--jp-layout-color2);
}

.jp-DirListing-headerItem.jp-id-name {
  flex: 1 0 84px;
}

.jp-DirListing-headerItem.jp-id-modified {
  flex: 0 0 112px;
  border-left: var(--jp-border-width) solid var(--jp-border-color2);
  text-align: right;
}

.jp-DirListing-narrow .jp-id-modified,
.jp-DirListing-narrow .jp-DirListing-itemModified {
  display: none;
}

.jp-DirListing-headerItem.jp-mod-selected {
  font-weight: 600;
}

/* increase specificity to override bundled default */
.jp-DirListing-content {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  list-style-type: none;
  overflow: auto;
  background-color: var(--jp-layout-color1);
}

/* Style the directory listing content when a user drops a file to upload */
.jp-DirListing.jp-mod-native-drop .jp-DirListing-content {
  outline: 5px dashed rgba(128, 128, 128, 0.5);
  outline-offset: -10px;
  cursor: copy;
}

.jp-DirListing-item {
  display: flex;
  flex-direction: row;
  padding: 4px 12px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.jp-DirListing-item.jp-mod-selected {
  color: white;
  background: var(--jp-brand-color1);
}

.jp-DirListing-item.jp-mod-dropTarget {
  background: var(--jp-brand-color3);
}

.jp-DirListing-item:hover:not(.jp-mod-selected) {
  background: var(--jp-layout-color2);
}

.jp-DirListing-itemIcon {
  flex: 0 0 20px;
  margin-right: 4px;
}

.jp-DirListing-itemText {
  flex: 1 0 64px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  user-select: none;
}

.jp-DirListing-itemModified {
  flex: 0 0 125px;
  text-align: right;
}

.jp-DirListing-editor {
  flex: 1 0 64px;
  outline: none;
  border: none;
}

.jp-DirListing-item.jp-mod-running .jp-DirListing-itemIcon:before {
  color: limegreen;
  content: '\25CF';
  font-size: 8px;
  position: absolute;
  left: -8px;
}

.jp-DirListing-item.lm-mod-drag-image,
.jp-DirListing-item.jp-mod-selected.lm-mod-drag-image {
  font-size: var(--jp-ui-font-size1);
  padding-left: 4px;
  margin-left: 4px;
  width: 160px;
  background-color: var(--jp-ui-inverse-font-color2);
  box-shadow: var(--jp-elevation-z2);
  border-radius: 0px;
  color: var(--jp-ui-font-color1);
  transform: translateX(-40%) translateY(-58%);
}

.jp-DirListing-deadSpace {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  list-style-type: none;
  overflow: auto;
  background-color: var(--jp-layout-color1);
}

.jp-Document {
  min-width: 120px;
  min-height: 120px;
  outline: none;
}

.jp-FileDialog.jp-mod-conflict input {
  color: red;
}

.jp-FileDialog .jp-new-name-title {
  margin-top: 12px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Private CSS variables
|----------------------------------------------------------------------------*/

:root {
}

/*-----------------------------------------------------------------------------
| Main OutputArea
| OutputArea has a list of Outputs
|----------------------------------------------------------------------------*/

.jp-OutputArea {
  overflow-y: auto;
}

.jp-OutputArea-child {
  display: flex;
  flex-direction: row;
}

.jp-OutputPrompt {
  flex: 0 0 var(--jp-cell-prompt-width);
  color: var(--jp-cell-outprompt-font-color);
  font-family: var(--jp-cell-prompt-font-family);
  padding: var(--jp-code-padding);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
  opacity: var(--jp-cell-prompt-opacity);
  /* Right align prompt text, don't wrap to handle large prompt numbers */
  text-align: right;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  /* Disable text selection */
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.jp-OutputArea-output {
  height: auto;
  overflow: auto;
  user-select: text;
  -moz-user-select: text;
  -webkit-user-select: text;
  -ms-user-select: text;
}

.jp-OutputArea-child .jp-OutputArea-output {
  flex-grow: 1;
  flex-shrink: 1;
}

/**
 * Isolated output.
 */
.jp-OutputArea-output.jp-mod-isolated {
  width: 100%;
  display: block;
}

/*
When drag events occur, `p-mod-override-cursor` is added to the body.
Because iframes steal all cursor events, the following two rules are necessary
to suppress pointer events while resize drags are occurring. There may be a
better solution to this problem.
*/
body.lm-mod-override-cursor .jp-OutputArea-output.jp-mod-isolated {
  position: relative;
}

body.lm-mod-override-cursor .jp-OutputArea-output.jp-mod-isolated:before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: transparent;
}

/* pre */

.jp-OutputArea-output pre {
  border: none;
  margin: 0px;
  padding: 0px;
  overflow-x: auto;
  overflow-y: auto;
  word-break: break-all;
  word-wrap: break-word;
  white-space: pre-wrap;
}

/* tables */

.jp-OutputArea-output.jp-RenderedHTMLCommon table {
  margin-left: 0;
  margin-right: 0;
}

/* description lists */

.jp-OutputArea-output dl,
.jp-OutputArea-output dt,
.jp-OutputArea-output dd {
  display: block;
}

.jp-OutputArea-output dl {
  width: 100%;
  overflow: hidden;
  padding: 0;
  margin: 0;
}

.jp-OutputArea-output dt {
  font-weight: bold;
  float: left;
  width: 20%;
  padding: 0;
  margin: 0;
}

.jp-OutputArea-output dd {
  float: left;
  width: 80%;
  padding: 0;
  margin: 0;
}

/* Hide the gutter in case of
 *  - nested output areas (e.g. in the case of output widgets)
 *  - mirrored output areas
 */
.jp-OutputArea .jp-OutputArea .jp-OutputArea-prompt {
  display: none;
}

/*-----------------------------------------------------------------------------
| executeResult is added to any Output-result for the display of the object
| returned by a cell
|----------------------------------------------------------------------------*/

.jp-OutputArea-output.jp-OutputArea-executeResult {
  margin-left: 0px;
  flex: 1 1 auto;
}

.jp-OutputArea-executeResult.jp-RenderedText {
  padding-top: var(--jp-code-padding);
}

/*-----------------------------------------------------------------------------
| The Stdin output
|----------------------------------------------------------------------------*/

.jp-OutputArea-stdin {
  line-height: var(--jp-code-line-height);
  padding-top: var(--jp-code-padding);
  display: flex;
}

.jp-Stdin-prompt {
  color: var(--jp-content-font-color0);
  padding-right: var(--jp-code-padding);
  vertical-align: baseline;
  flex: 0 0 auto;
}

.jp-Stdin-input {
  font-family: var(--jp-code-font-family);
  font-size: inherit;
  color: inherit;
  background-color: inherit;
  width: 42%;
  min-width: 200px;
  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;
  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0em 0.25em;
  margin: 0em 0.25em;
  flex: 0 0 70%;
}

.jp-Stdin-input:focus {
  box-shadow: none;
}

/*-----------------------------------------------------------------------------
| Output Area View
|----------------------------------------------------------------------------*/

.jp-LinkedOutputView .jp-OutputArea {
  height: 100%;
  display: block;
}

.jp-LinkedOutputView .jp-OutputArea-output:only-child {
  height: 100%;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Collapser {
  flex: 0 0 var(--jp-cell-collapser-width);
  padding: 0px;
  margin: 0px;
  border: none;
  outline: none;
  background: transparent;
  border-radius: var(--jp-border-radius);
  opacity: 1;
}

.jp-Collapser-child {
  display: block;
  width: 100%;
  box-sizing: border-box;
  /* height: 100% doesn't work because the height of its parent is computed from content */
  position: absolute;
  top: 0px;
  bottom: 0px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Header/Footer
|----------------------------------------------------------------------------*/

/* Hidden by zero height by default */
.jp-CellHeader,
.jp-CellFooter {
  height: 0px;
  width: 100%;
  padding: 0px;
  margin: 0px;
  border: none;
  outline: none;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Input
|----------------------------------------------------------------------------*/

/* All input areas */
.jp-InputArea {
  display: flex;
  flex-direction: row;
}

.jp-InputArea-editor {
  flex: 1 1 auto;
}

.jp-InputArea-editor {
  /* This is the non-active, default styling */
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  border-radius: 0px;
  background: var(--jp-cell-editor-background);
}

.jp-InputPrompt {
  flex: 0 0 var(--jp-cell-prompt-width);
  color: var(--jp-cell-inprompt-font-color);
  font-family: var(--jp-cell-prompt-font-family);
  padding: var(--jp-code-padding);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  opacity: var(--jp-cell-prompt-opacity);
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
  opacity: var(--jp-cell-prompt-opacity);
  /* Right align prompt text, don't wrap to handle large prompt numbers */
  text-align: right;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  /* Disable text selection */
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Placeholder
|----------------------------------------------------------------------------*/

.jp-Placeholder {
  display: flex;
  flex-direction: row;
  flex: 1 1 auto;
}

.jp-Placeholder-prompt {
  box-sizing: border-box;
}

.jp-Placeholder-content {
  flex: 1 1 auto;
  border: none;
  background: transparent;
  height: 20px;
  box-sizing: border-box;
}

.jp-Placeholder-content .jp-MoreHorizIcon {
  width: 32px;
  height: 16px;
  border: 1px solid transparent;
  border-radius: var(--jp-border-radius);
}

.jp-Placeholder-content .jp-MoreHorizIcon:hover {
  border: 1px solid var(--jp-border-color1);
  box-shadow: 0px 0px 2px 0px rgba(0, 0, 0, 0.25);
  background-color: var(--jp-layout-color0);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Private CSS variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-cell-scrolling-output-offset: 5px;
}

/*-----------------------------------------------------------------------------
| Cell
|----------------------------------------------------------------------------*/

.jp-Cell {
  padding: var(--jp-cell-padding);
  margin: 0px;
  border: none;
  outline: none;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Common input/output
|----------------------------------------------------------------------------*/

.jp-Cell-inputWrapper,
.jp-Cell-outputWrapper {
  display: flex;
  flex-direction: row;
  padding: 0px;
  margin: 0px;
  /* Added to reveal the box-shadow on the input and output collapsers. */
  overflow: visible;
}

/* Only input/output areas inside cells */
.jp-Cell-inputArea,
.jp-Cell-outputArea {
  flex: 1 1 auto;
}

/*-----------------------------------------------------------------------------
| Collapser
|----------------------------------------------------------------------------*/

/* Make the output collapser disappear when there is not output, but do so
 * in a manner that leaves it in the layout and preserves its width.
 */
.jp-Cell.jp-mod-noOutputs .jp-Cell-outputCollapser {
  border: none !important;
  background: transparent !important;
}

.jp-Cell:not(.jp-mod-noOutputs) .jp-Cell-outputCollapser {
  min-height: var(--jp-cell-collapser-min-height);
}

/*-----------------------------------------------------------------------------
| Output
|----------------------------------------------------------------------------*/

/* Put a space between input and output when there IS output */
.jp-Cell:not(.jp-mod-noOutputs) .jp-Cell-outputWrapper {
  margin-top: 5px;
}

/* Text output with the Out[] prompt needs a top padding to match the
 * alignment of the Out[] prompt itself.
 */
.jp-OutputArea-executeResult .jp-RenderedText.jp-OutputArea-output {
  padding-top: var(--jp-code-padding);
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-Cell-outputArea {
  overflow-y: auto;
  max-height: 200px;
  box-shadow: inset 0 0 6px 2px rgba(0, 0, 0, 0.3);
  margin-left: var(--jp-private-cell-scrolling-output-offset);
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-OutputArea-prompt {
  flex: 0 0
    calc(
      var(--jp-cell-prompt-width) -
        var(--jp-private-cell-scrolling-output-offset)
    );
}

/*-----------------------------------------------------------------------------
| CodeCell
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| MarkdownCell
|----------------------------------------------------------------------------*/

.jp-MarkdownOutput {
  flex: 1 1 auto;
  margin-top: 0;
  margin-bottom: 0;
  padding-left: var(--jp-code-padding);
}

.jp-MarkdownOutput.jp-RenderedHTMLCommon {
  overflow: auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------

/*-----------------------------------------------------------------------------
| Styles
|----------------------------------------------------------------------------*/

.jp-NotebookPanel-toolbar {
  padding: 2px;
}

.jp-Toolbar-item.jp-Notebook-toolbarCellType .jp-select-wrapper.jp-mod-focused {
  border: none;
  box-shadow: none;
}

.jp-Notebook-toolbarCellTypeDropdown select {
  height: 24px;
  font-size: var(--jp-ui-font-size1);
  line-height: 14px;
  border-radius: 0;
  display: block;
}

.jp-Notebook-toolbarCellTypeDropdown span {
  top: 5px !important;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Private CSS variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-notebook-dragImage-width: 304px;
  --jp-private-notebook-dragImage-height: 36px;
  --jp-private-notebook-selected-color: var(--md-blue-400);
  --jp-private-notebook-active-color: var(--md-green-400);
}

/*-----------------------------------------------------------------------------
| Imports
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Notebook
|----------------------------------------------------------------------------*/

.jp-NotebookPanel {
  display: block;
  height: 100%;
}

.jp-NotebookPanel.jp-Document {
  min-width: 240px;
  min-height: 120px;
}

.jp-Notebook {
  padding: var(--jp-notebook-padding);
  outline: none;
  overflow: auto;
  background: var(--jp-layout-color0);
}

.jp-Notebook.jp-mod-scrollPastEnd::after {
  display: block;
  content: '';
  min-height: var(--jp-notebook-scroll-padding);
}

.jp-Notebook .jp-Cell {
  overflow: visible;
}

.jp-Notebook .jp-Cell .jp-InputPrompt {
  cursor: move;
}

/*-----------------------------------------------------------------------------
| Notebook state related styling
|
| The notebook and cells each have states, here are the possibilities:
|
| - Notebook
|   - Command
|   - Edit
| - Cell
|   - None
|   - Active (only one can be active)
|   - Selected (the cells actions are applied to)
|   - Multiselected (when multiple selected, the cursor)
|   - No outputs
|----------------------------------------------------------------------------*/

/* Command or edit modes */

.jp-Notebook .jp-Cell:not(.jp-mod-active) .jp-InputPrompt {
  opacity: var(--jp-cell-prompt-not-active-opacity);
  color: var(--jp-cell-prompt-not-active-font-color);
}

.jp-Notebook .jp-Cell:not(.jp-mod-active) .jp-OutputPrompt {
  opacity: var(--jp-cell-prompt-not-active-opacity);
  color: var(--jp-cell-prompt-not-active-font-color);
}

/* cell is active */
.jp-Notebook .jp-Cell.jp-mod-active .jp-Collapser {
  background: var(--jp-brand-color1);
}

/* collapser is hovered */
.jp-Notebook .jp-Cell .jp-Collapser:hover {
  box-shadow: var(--jp-elevation-z2);
  background: var(--jp-brand-color1);
  opacity: var(--jp-cell-collapser-not-active-hover-opacity);
}

/* cell is active and collapser is hovered */
.jp-Notebook .jp-Cell.jp-mod-active .jp-Collapser:hover {
  background: var(--jp-brand-color0);
  opacity: 1;
}

/* Command mode */

.jp-Notebook.jp-mod-commandMode .jp-Cell.jp-mod-selected {
  background: var(--jp-notebook-multiselected-color);
}

.jp-Notebook.jp-mod-commandMode
  .jp-Cell.jp-mod-active.jp-mod-selected:not(.jp-mod-multiSelected) {
  background: transparent;
}

/* Edit mode */

.jp-Notebook.jp-mod-editMode .jp-Cell.jp-mod-active .jp-InputArea-editor {
  border: var(--jp-border-width) solid var(--jp-cell-editor-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
  background-color: var(--jp-cell-editor-active-background);
}

/*-----------------------------------------------------------------------------
| Notebook drag and drop
|----------------------------------------------------------------------------*/

.jp-Notebook-cell.jp-mod-dropSource {
  opacity: 0.5;
}

.jp-Notebook-cell.jp-mod-dropTarget,
.jp-Notebook.jp-mod-commandMode
  .jp-Notebook-cell.jp-mod-active.jp-mod-selected.jp-mod-dropTarget {
  border-top-color: var(--jp-private-notebook-selected-color);
  border-top-style: solid;
  border-top-width: 2px;
}

.jp-dragImage {
  display: flex;
  flex-direction: row;
  width: var(--jp-private-notebook-dragImage-width);
  height: var(--jp-private-notebook-dragImage-height);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background);
  overflow: visible;
}

.jp-dragImage-singlePrompt {
  box-shadow: 2px 2px 4px 0px rgba(0, 0, 0, 0.12);
}

.jp-dragImage .jp-dragImage-content {
  flex: 1 1 auto;
  z-index: 2;
  font-size: var(--jp-code-font-size);
  font-family: var(--jp-code-font-family);
  line-height: var(--jp-code-line-height);
  padding: var(--jp-code-padding);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background-color);
  color: var(--jp-content-font-color3);
  text-align: left;
  margin: 4px 4px 4px 0px;
}

.jp-dragImage .jp-dragImage-prompt {
  flex: 0 0 auto;
  min-width: 36px;
  color: var(--jp-cell-inprompt-font-color);
  padding: var(--jp-code-padding);
  padding-left: 12px;
  font-family: var(--jp-cell-prompt-font-family);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  line-height: 1.9;
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
}

.jp-dragImage-multipleBack {
  z-index: -1;
  position: absolute;
  height: 32px;
  width: 300px;
  top: 8px;
  left: 8px;
  background: var(--jp-layout-color2);
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  box-shadow: 2px 2px 4px 0px rgba(0, 0, 0, 0.12);
}

/*-----------------------------------------------------------------------------
| Cell toolbar
|----------------------------------------------------------------------------*/

.jp-NotebookTools {
  display: block;
  min-width: var(--jp-sidebar-min-width);
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);
  /* This is needed so that all font sizing of children done in ems is
    * relative to this base size */
  font-size: var(--jp-ui-font-size1);
  overflow: auto;
}

.jp-NotebookTools-tool {
  padding: 0px 12px 0 12px;
}

.jp-ActiveCellTool {
  padding: 12px;
  background-color: var(--jp-layout-color1);
  border-top: none !important;
}

.jp-ActiveCellTool .jp-InputArea-prompt {
  flex: 0 0 auto;
  padding-left: 0px;
}

.jp-ActiveCellTool .jp-InputArea-editor {
  flex: 1 1 auto;
  background: var(--jp-cell-editor-background);
  border-color: var(--jp-cell-editor-border-color);
}

.jp-ActiveCellTool .jp-InputArea-editor .CodeMirror {
  background: transparent;
}

.jp-MetadataEditorTool {
  flex-direction: column;
  padding: 12px 0px 12px 0px;
}

.jp-RankedPanel > :not(:first-child) {
  margin-top: 12px;
}

.jp-KeySelector select.jp-mod-styled {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  border: var(--jp-border-width) solid var(--jp-border-color1);
}

.jp-KeySelector label,
.jp-MetadataEditorTool label {
  line-height: 1.4;
}

/*-----------------------------------------------------------------------------
| Presentation Mode (.jp-mod-presentationMode)
|----------------------------------------------------------------------------*/

.jp-mod-presentationMode .jp-Notebook {
  --jp-content-font-size1: var(--jp-content-presentation-font-size1);
  --jp-code-font-size: var(--jp-code-presentation-font-size);
}

.jp-mod-presentationMode .jp-Notebook .jp-Cell .jp-InputPrompt,
.jp-mod-presentationMode .jp-Notebook .jp-Cell .jp-OutputPrompt {
  flex: 0 0 110px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

</style>

    <style type="text/css">
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*
The following CSS variables define the main, public API for styling JupyterLab.
These variables should be used by all plugins wherever possible. In other
words, plugins should not define custom colors, sizes, etc unless absolutely
necessary. This enables users to change the visual theme of JupyterLab
by changing these variables.

Many variables appear in an ordered sequence (0,1,2,3). These sequences
are designed to work well together, so for example, `--jp-border-color1` should
be used with `--jp-layout-color1`. The numbers have the following meanings:

* 0: super-primary, reserved for special emphasis
* 1: primary, most important under normal situations
* 2: secondary, next most important under normal situations
* 3: tertiary, next most important under normal situations

Throughout JupyterLab, we are mostly following principles from Google's
Material Design when selecting colors. We are not, however, following
all of MD as it is not optimized for dense, information rich UIs.
*/

:root {
  /* Elevation
   *
   * We style box-shadows using Material Design's idea of elevation. These particular numbers are taken from here:
   *
   * https://github.com/material-components/material-components-web
   * https://material-components-web.appspot.com/elevation.html
   */

  --jp-shadow-base-lightness: 0;
  --jp-shadow-umbra-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.2
  );
  --jp-shadow-penumbra-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.14
  );
  --jp-shadow-ambient-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.12
  );
  --jp-elevation-z0: none;
  --jp-elevation-z1: 0px 2px 1px -1px var(--jp-shadow-umbra-color),
    0px 1px 1px 0px var(--jp-shadow-penumbra-color),
    0px 1px 3px 0px var(--jp-shadow-ambient-color);
  --jp-elevation-z2: 0px 3px 1px -2px var(--jp-shadow-umbra-color),
    0px 2px 2px 0px var(--jp-shadow-penumbra-color),
    0px 1px 5px 0px var(--jp-shadow-ambient-color);
  --jp-elevation-z4: 0px 2px 4px -1px var(--jp-shadow-umbra-color),
    0px 4px 5px 0px var(--jp-shadow-penumbra-color),
    0px 1px 10px 0px var(--jp-shadow-ambient-color);
  --jp-elevation-z6: 0px 3px 5px -1px var(--jp-shadow-umbra-color),
    0px 6px 10px 0px var(--jp-shadow-penumbra-color),
    0px 1px 18px 0px var(--jp-shadow-ambient-color);
  --jp-elevation-z8: 0px 5px 5px -3px var(--jp-shadow-umbra-color),
    0px 8px 10px 1px var(--jp-shadow-penumbra-color),
    0px 3px 14px 2px var(--jp-shadow-ambient-color);
  --jp-elevation-z12: 0px 7px 8px -4px var(--jp-shadow-umbra-color),
    0px 12px 17px 2px var(--jp-shadow-penumbra-color),
    0px 5px 22px 4px var(--jp-shadow-ambient-color);
  --jp-elevation-z16: 0px 8px 10px -5px var(--jp-shadow-umbra-color),
    0px 16px 24px 2px var(--jp-shadow-penumbra-color),
    0px 6px 30px 5px var(--jp-shadow-ambient-color);
  --jp-elevation-z20: 0px 10px 13px -6px var(--jp-shadow-umbra-color),
    0px 20px 31px 3px var(--jp-shadow-penumbra-color),
    0px 8px 38px 7px var(--jp-shadow-ambient-color);
  --jp-elevation-z24: 0px 11px 15px -7px var(--jp-shadow-umbra-color),
    0px 24px 38px 3px var(--jp-shadow-penumbra-color),
    0px 9px 46px 8px var(--jp-shadow-ambient-color);

  /* Borders
   *
   * The following variables, specify the visual styling of borders in JupyterLab.
   */

  --jp-border-width: 1px;
  --jp-border-color0: var(--md-grey-400);
  --jp-border-color1: var(--md-grey-400);
  --jp-border-color2: var(--md-grey-300);
  --jp-border-color3: var(--md-grey-200);
  --jp-border-radius: 2px;

  /* UI Fonts
   *
   * The UI font CSS variables are used for the typography all of the JupyterLab
   * user interface elements that are not directly user generated content.
   *
   * The font sizing here is done assuming that the body font size of --jp-ui-font-size1
   * is applied to a parent element. When children elements, such as headings, are sized
   * in em all things will be computed relative to that body size.
   */

  --jp-ui-font-scale-factor: 1.2;
  --jp-ui-font-size0: 0.83333em;
  --jp-ui-font-size1: 13px; /* Base font size */
  --jp-ui-font-size2: 1.2em;
  --jp-ui-font-size3: 1.44em;

  --jp-ui-font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica,
    Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol';

  /*
   * Use these font colors against the corresponding main layout colors.
   * In a light theme, these go from dark to light.
   */

  /* Defaults use Material Design specification */
  --jp-ui-font-color0: rgba(0, 0, 0, 1);
  --jp-ui-font-color1: rgba(0, 0, 0, 0.87);
  --jp-ui-font-color2: rgba(0, 0, 0, 0.54);
  --jp-ui-font-color3: rgba(0, 0, 0, 0.38);

  /*
   * Use these against the brand/accent/warn/error colors.
   * These will typically go from light to darker, in both a dark and light theme.
   */

  --jp-ui-inverse-font-color0: rgba(255, 255, 255, 1);
  --jp-ui-inverse-font-color1: rgba(255, 255, 255, 1);
  --jp-ui-inverse-font-color2: rgba(255, 255, 255, 0.7);
  --jp-ui-inverse-font-color3: rgba(255, 255, 255, 0.5);

  /* Content Fonts
   *
   * Content font variables are used for typography of user generated content.
   *
   * The font sizing here is done assuming that the body font size of --jp-content-font-size1
   * is applied to a parent element. When children elements, such as headings, are sized
   * in em all things will be computed relative to that body size.
   */

  --jp-content-line-height: 1.6;
  --jp-content-font-scale-factor: 1.2;
  --jp-content-font-size0: 0.83333em;
  --jp-content-font-size1: 14px; /* Base font size */
  --jp-content-font-size2: 1.2em;
  --jp-content-font-size3: 1.44em;
  --jp-content-font-size4: 1.728em;
  --jp-content-font-size5: 2.0736em;

  /* This gives a magnification of about 125% in presentation mode over normal. */
  --jp-content-presentation-font-size1: 17px;

  --jp-content-heading-line-height: 1;
  --jp-content-heading-margin-top: 1.2em;
  --jp-content-heading-margin-bottom: 0.8em;
  --jp-content-heading-font-weight: 500;

  /* Defaults use Material Design specification */
  --jp-content-font-color0: rgba(0, 0, 0, 1);
  --jp-content-font-color1: rgba(0, 0, 0, 0.87);
  --jp-content-font-color2: rgba(0, 0, 0, 0.54);
  --jp-content-font-color3: rgba(0, 0, 0, 0.38);

  --jp-content-link-color: var(--md-blue-700);

  --jp-content-font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji',
    'Segoe UI Symbol';

  /*
   * Code Fonts
   *
   * Code font variables are used for typography of code and other monospaces content.
   */

  --jp-code-font-size: 13px;
  --jp-code-line-height: 1.3077; /* 17px for 13px base */
  --jp-code-padding: 5px; /* 5px for 13px base, codemirror highlighting needs integer px value */
  --jp-code-font-family-default: Menlo, Consolas, 'DejaVu Sans Mono', monospace;
  --jp-code-font-family: var(--jp-code-font-family-default);

  /* This gives a magnification of about 125% in presentation mode over normal. */
  --jp-code-presentation-font-size: 16px;

  /* may need to tweak cursor width if you change font size */
  --jp-code-cursor-width0: 1.4px;
  --jp-code-cursor-width1: 2px;
  --jp-code-cursor-width2: 4px;

  /* Layout
   *
   * The following are the main layout colors use in JupyterLab. In a light
   * theme these would go from light to dark.
   */

  --jp-layout-color0: white;
  --jp-layout-color1: white;
  --jp-layout-color2: var(--md-grey-200);
  --jp-layout-color3: var(--md-grey-400);
  --jp-layout-color4: var(--md-grey-600);

  /* Inverse Layout
   *
   * The following are the inverse layout colors use in JupyterLab. In a light
   * theme these would go from dark to light.
   */

  --jp-inverse-layout-color0: #111111;
  --jp-inverse-layout-color1: var(--md-grey-900);
  --jp-inverse-layout-color2: var(--md-grey-800);
  --jp-inverse-layout-color3: var(--md-grey-700);
  --jp-inverse-layout-color4: var(--md-grey-600);

  /* Brand/accent */

  --jp-brand-color0: var(--md-blue-700);
  --jp-brand-color1: var(--md-blue-500);
  --jp-brand-color2: var(--md-blue-300);
  --jp-brand-color3: var(--md-blue-100);
  --jp-brand-color4: var(--md-blue-50);

  --jp-accent-color0: var(--md-green-700);
  --jp-accent-color1: var(--md-green-500);
  --jp-accent-color2: var(--md-green-300);
  --jp-accent-color3: var(--md-green-100);

  /* State colors (warn, error, success, info) */

  --jp-warn-color0: var(--md-orange-700);
  --jp-warn-color1: var(--md-orange-500);
  --jp-warn-color2: var(--md-orange-300);
  --jp-warn-color3: var(--md-orange-100);

  --jp-error-color0: var(--md-red-700);
  --jp-error-color1: var(--md-red-500);
  --jp-error-color2: var(--md-red-300);
  --jp-error-color3: var(--md-red-100);

  --jp-success-color0: var(--md-green-700);
  --jp-success-color1: var(--md-green-500);
  --jp-success-color2: var(--md-green-300);
  --jp-success-color3: var(--md-green-100);

  --jp-info-color0: var(--md-cyan-700);
  --jp-info-color1: var(--md-cyan-500);
  --jp-info-color2: var(--md-cyan-300);
  --jp-info-color3: var(--md-cyan-100);

  /* Cell specific styles */

  --jp-cell-padding: 5px;

  --jp-cell-collapser-width: 8px;
  --jp-cell-collapser-min-height: 20px;
  --jp-cell-collapser-not-active-hover-opacity: 0.6;

  --jp-cell-editor-background: var(--md-grey-100);
  --jp-cell-editor-border-color: var(--md-grey-300);
  --jp-cell-editor-box-shadow: inset 0 0 2px var(--md-blue-300);
  --jp-cell-editor-active-background: var(--jp-layout-color0);
  --jp-cell-editor-active-border-color: var(--jp-brand-color1);

  --jp-cell-prompt-width: 64px;
  --jp-cell-prompt-font-family: 'Source Code Pro', monospace;
  --jp-cell-prompt-letter-spacing: 0px;
  --jp-cell-prompt-opacity: 1;
  --jp-cell-prompt-not-active-opacity: 0.5;
  --jp-cell-prompt-not-active-font-color: var(--md-grey-700);
  /* A custom blend of MD grey and blue 600
   * See https://meyerweb.com/eric/tools/color-blend/#546E7A:1E88E5:5:hex */
  --jp-cell-inprompt-font-color: #307fc1;
  /* A custom blend of MD grey and orange 600
   * https://meyerweb.com/eric/tools/color-blend/#546E7A:F4511E:5:hex */
  --jp-cell-outprompt-font-color: #bf5b3d;

  /* Notebook specific styles */

  --jp-notebook-padding: 10px;
  --jp-notebook-select-background: var(--jp-layout-color1);
  --jp-notebook-multiselected-color: var(--md-blue-50);

  /* The scroll padding is calculated to fill enough space at the bottom of the
  notebook to show one single-line cell (with appropriate padding) at the top
  when the notebook is scrolled all the way to the bottom. We also subtract one
  pixel so that no scrollbar appears if we have just one single-line cell in the
  notebook. This padding is to enable a 'scroll past end' feature in a notebook.
  */
  --jp-notebook-scroll-padding: calc(
    100% - var(--jp-code-font-size) * var(--jp-code-line-height) -
      var(--jp-code-padding) - var(--jp-cell-padding) - 1px
  );

  /* Rendermime styles */

  --jp-rendermime-error-background: #fdd;
  --jp-rendermime-table-row-background: var(--md-grey-100);
  --jp-rendermime-table-row-hover-background: var(--md-light-blue-50);

  /* Dialog specific styles */

  --jp-dialog-background: rgba(0, 0, 0, 0.25);

  /* Console specific styles */

  --jp-console-padding: 10px;

  /* Toolbar specific styles */

  --jp-toolbar-border-color: var(--jp-border-color1);
  --jp-toolbar-micro-height: 8px;
  --jp-toolbar-background: var(--jp-layout-color1);
  --jp-toolbar-box-shadow: 0px 0px 2px 0px rgba(0, 0, 0, 0.24);
  --jp-toolbar-header-margin: 4px 4px 0px 4px;
  --jp-toolbar-active-background: var(--md-grey-300);

  /* Input field styles */

  --jp-input-box-shadow: inset 0 0 2px var(--md-blue-300);
  --jp-input-active-background: var(--jp-layout-color1);
  --jp-input-hover-background: var(--jp-layout-color1);
  --jp-input-background: var(--md-grey-100);
  --jp-input-border-color: var(--jp-border-color1);
  --jp-input-active-border-color: var(--jp-brand-color1);
  --jp-input-active-box-shadow-color: rgba(19, 124, 189, 0.3);

  /* General editor styles */

  --jp-editor-selected-background: #d9d9d9;
  --jp-editor-selected-focused-background: #d7d4f0;
  --jp-editor-cursor-color: var(--jp-ui-font-color0);

  /* Code mirror specific styles */

  --jp-mirror-editor-keyword-color: #008000;
  --jp-mirror-editor-atom-color: #88f;
  --jp-mirror-editor-number-color: #080;
  --jp-mirror-editor-def-color: #00f;
  --jp-mirror-editor-variable-color: var(--md-grey-900);
  --jp-mirror-editor-variable-2-color: #05a;
  --jp-mirror-editor-variable-3-color: #085;
  --jp-mirror-editor-punctuation-color: #05a;
  --jp-mirror-editor-property-color: #05a;
  --jp-mirror-editor-operator-color: #aa22ff;
  --jp-mirror-editor-comment-color: #408080;
  --jp-mirror-editor-string-color: #ba2121;
  --jp-mirror-editor-string-2-color: #708;
  --jp-mirror-editor-meta-color: #aa22ff;
  --jp-mirror-editor-qualifier-color: #555;
  --jp-mirror-editor-builtin-color: #008000;
  --jp-mirror-editor-bracket-color: #997;
  --jp-mirror-editor-tag-color: #170;
  --jp-mirror-editor-attribute-color: #00c;
  --jp-mirror-editor-header-color: blue;
  --jp-mirror-editor-quote-color: #090;
  --jp-mirror-editor-link-color: #00c;
  --jp-mirror-editor-error-color: #f00;
  --jp-mirror-editor-hr-color: #999;

  /* Vega extension styles */

  --jp-vega-background: white;

  /* Sidebar-related styles */

  --jp-sidebar-min-width: 180px;

  /* Search-related styles */

  --jp-search-toggle-off-opacity: 0.5;
  --jp-search-toggle-hover-opacity: 0.8;
  --jp-search-toggle-on-opacity: 1;
  --jp-search-selected-match-background-color: rgb(245, 200, 0);
  --jp-search-selected-match-color: black;
  --jp-search-unselected-match-background-color: var(
    --jp-inverse-layout-color0
  );
  --jp-search-unselected-match-color: var(--jp-ui-inverse-font-color0);

  /* Icon colors that work well with light or dark backgrounds */
  --jp-icon-contrast-color0: var(--md-purple-600);
  --jp-icon-contrast-color1: var(--md-green-600);
  --jp-icon-contrast-color2: var(--md-pink-600);
  --jp-icon-contrast-color3: var(--md-blue-600);
}
</style>

<style type="text/css">
a.anchor-link {
   display: none;
}
.highlight  {
    margin: 0.4em;
}

/* Input area styling */
.jp-InputArea {
    overflow: hidden;
}

.jp-InputArea-editor {
    overflow: hidden;
}

@media print {
  body {
    margin: 0;
  }
}
</style>



<!-- Load mathjax -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/latest.js?config=TeX-MML-AM_CHTML-full,Safe"> </script>
    <!-- MathJax configuration -->
    <script type="text/x-mathjax-config">
    init_mathjax = function() {
        if (window.MathJax) {
        // MathJax loaded
            MathJax.Hub.Config({
                TeX: {
                    equationNumbers: {
                    autoNumber: "AMS",
                    useLabelIds: true
                    }
                },
                tex2jax: {
                    inlineMath: [ ['$','$'], ["\\(","\\)"] ],
                    displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
                    processEscapes: true,
                    processEnvironments: true
                },
                displayAlign: 'center',
                CommonHTML: {
                    linebreaks: { 
                    automatic: true 
                    }
                },
                "HTML-CSS": {
                    linebreaks: { 
                    automatic: true 
                    }
                }
            });
        
            MathJax.Hub.Queue(["Typeset", MathJax.Hub]);
        }
    }
    init_mathjax();
    </script>
    <!-- End of mathjax configuration --></head>
<body class="jp-Notebook" data-jp-theme-light="true" data-jp-theme-name="JupyterLab Light">

<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h1 id="1.Fetch-data">1.Fetch data<a class="anchor-link" href="#1.Fetch-data">&#182;</a></h1>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[1]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="kn">import</span> <span class="nn">seaborn</span> <span class="k">as</span> <span class="nn">sb</span>
<span class="kn">from</span> <span class="nn">warnings</span> <span class="kn">import</span> <span class="n">filterwarnings</span>
<span class="n">filterwarnings</span><span class="p">(</span><span class="s2">&quot;ignore&quot;</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[2]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">A</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;C:/users/Paresh/My documents/Cars93.csv&quot;</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[3]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">A</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[3]:</div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/html">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Id</th>
      <th>Manufacturer</th>
      <th>Model</th>
      <th>Type</th>
      <th>Min.Price</th>
      <th>Price</th>
      <th>Max.Price</th>
      <th>MPG.city</th>
      <th>MPG.highway</th>
      <th>AirBags</th>
      <th>...</th>
      <th>Passengers</th>
      <th>Length</th>
      <th>Wheelbase</th>
      <th>Width</th>
      <th>Turn.circle</th>
      <th>Rear.seat.room</th>
      <th>Luggage.room</th>
      <th>Weight</th>
      <th>Origin</th>
      <th>Make</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>Acura</td>
      <td>Integra</td>
      <td>Small</td>
      <td>12.9</td>
      <td>15.9</td>
      <td>18.8</td>
      <td>25</td>
      <td>31</td>
      <td>None</td>
      <td>...</td>
      <td>5</td>
      <td>177</td>
      <td>102</td>
      <td>68</td>
      <td>37</td>
      <td>26.5</td>
      <td>11.0</td>
      <td>2705</td>
      <td>non-USA</td>
      <td>Acura Integra</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>Acura</td>
      <td>Legend</td>
      <td>Midsize</td>
      <td>29.2</td>
      <td>33.9</td>
      <td>38.7</td>
      <td>18</td>
      <td>25</td>
      <td>Driver &amp; Passenger</td>
      <td>...</td>
      <td>5</td>
      <td>195</td>
      <td>115</td>
      <td>71</td>
      <td>38</td>
      <td>30.0</td>
      <td>15.0</td>
      <td>3560</td>
      <td>non-USA</td>
      <td>Acura Legend</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>Audi</td>
      <td>90</td>
      <td>Compact</td>
      <td>25.9</td>
      <td>29.1</td>
      <td>32.3</td>
      <td>20</td>
      <td>26</td>
      <td>Driver only</td>
      <td>...</td>
      <td>5</td>
      <td>180</td>
      <td>102</td>
      <td>67</td>
      <td>37</td>
      <td>28.0</td>
      <td>14.0</td>
      <td>3375</td>
      <td>non-USA</td>
      <td>Audi 90</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4</td>
      <td>Audi</td>
      <td>100</td>
      <td>Midsize</td>
      <td>30.8</td>
      <td>37.7</td>
      <td>44.6</td>
      <td>19</td>
      <td>26</td>
      <td>NaN</td>
      <td>...</td>
      <td>6</td>
      <td>193</td>
      <td>106</td>
      <td>70</td>
      <td>37</td>
      <td>31.0</td>
      <td>17.0</td>
      <td>3405</td>
      <td>non-USA</td>
      <td>Audi 100</td>
    </tr>
    <tr>
      <th>4</th>
      <td>5</td>
      <td>BMW</td>
      <td>535i</td>
      <td>Midsize</td>
      <td>23.7</td>
      <td>30.0</td>
      <td>36.2</td>
      <td>22</td>
      <td>30</td>
      <td>Driver only</td>
      <td>...</td>
      <td>4</td>
      <td>186</td>
      <td>109</td>
      <td>69</td>
      <td>39</td>
      <td>27.0</td>
      <td>13.0</td>
      <td>3640</td>
      <td>non-USA</td>
      <td>BMW 535i</td>
    </tr>
  </tbody>
</table>
<p>5 rows × 28 columns</p>
</div>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h1 id="Delete-unnecssary-columns">Delete unnecssary columns<a class="anchor-link" href="#Delete-unnecssary-columns">&#182;</a></h1>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[4]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">A</span><span class="o">.</span><span class="n">drop</span><span class="p">(</span><span class="n">labels</span><span class="o">=</span><span class="p">[</span><span class="s2">&quot;Id&quot;</span><span class="p">,</span><span class="s2">&quot;Make&quot;</span><span class="p">,</span><span class="s2">&quot;Model&quot;</span><span class="p">],</span><span class="n">axis</span><span class="o">=</span><span class="mi">1</span><span class="p">,</span><span class="n">inplace</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[5]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">A</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">2</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[5]:</div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/html">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Manufacturer</th>
      <th>Type</th>
      <th>Min.Price</th>
      <th>Price</th>
      <th>Max.Price</th>
      <th>MPG.city</th>
      <th>MPG.highway</th>
      <th>AirBags</th>
      <th>DriveTrain</th>
      <th>Cylinders</th>
      <th>...</th>
      <th>Fuel.tank.capacity</th>
      <th>Passengers</th>
      <th>Length</th>
      <th>Wheelbase</th>
      <th>Width</th>
      <th>Turn.circle</th>
      <th>Rear.seat.room</th>
      <th>Luggage.room</th>
      <th>Weight</th>
      <th>Origin</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Acura</td>
      <td>Small</td>
      <td>12.9</td>
      <td>15.9</td>
      <td>18.8</td>
      <td>25</td>
      <td>31</td>
      <td>None</td>
      <td>Front</td>
      <td>4</td>
      <td>...</td>
      <td>13.2</td>
      <td>5</td>
      <td>177</td>
      <td>102</td>
      <td>68</td>
      <td>37</td>
      <td>26.5</td>
      <td>11.0</td>
      <td>2705</td>
      <td>non-USA</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Acura</td>
      <td>Midsize</td>
      <td>29.2</td>
      <td>33.9</td>
      <td>38.7</td>
      <td>18</td>
      <td>25</td>
      <td>Driver &amp; Passenger</td>
      <td>Front</td>
      <td>6</td>
      <td>...</td>
      <td>18.0</td>
      <td>5</td>
      <td>195</td>
      <td>115</td>
      <td>71</td>
      <td>38</td>
      <td>30.0</td>
      <td>15.0</td>
      <td>3560</td>
      <td>non-USA</td>
    </tr>
  </tbody>
</table>
<p>2 rows × 25 columns</p>
</div>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h1 id="Missing-Data-Treatment">Missing Data Treatment<a class="anchor-link" href="#Missing-Data-Treatment">&#182;</a></h1>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[6]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">A</span><span class="o">.</span><span class="n">isna</span><span class="p">()</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[6]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>Manufacturer           0
Type                   0
Min.Price              0
Price                  0
Max.Price              0
MPG.city               0
MPG.highway            0
AirBags                4
DriveTrain             0
Cylinders              0
EngineSize             0
Horsepower             0
RPM                    0
Rev.per.mile           0
Man.trans.avail        0
Fuel.tank.capacity     0
Passengers             0
Length                 0
Wheelbase              0
Width                  0
Turn.circle            0
Rear.seat.room         2
Luggage.room          11
Weight                 0
Origin                 0
dtype: int64</pre>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[7]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">from</span> <span class="nn">miss</span> <span class="kn">import</span> <span class="n">replacer</span>
<span class="n">replacer</span><span class="p">(</span><span class="n">A</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[8]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">A</span><span class="o">.</span><span class="n">isna</span><span class="p">()</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[8]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>Manufacturer          0
Type                  0
Min.Price             0
Price                 0
Max.Price             0
MPG.city              0
MPG.highway           0
AirBags               0
DriveTrain            0
Cylinders             0
EngineSize            0
Horsepower            0
RPM                   0
Rev.per.mile          0
Man.trans.avail       0
Fuel.tank.capacity    0
Passengers            0
Length                0
Wheelbase             0
Width                 0
Turn.circle           0
Rear.seat.room        0
Luggage.room          0
Weight                0
Origin                0
dtype: int64</pre>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h1 id="Divide-data-into-categorical-and-continuous">Divide data into categorical and continuous<a class="anchor-link" href="#Divide-data-into-categorical-and-continuous">&#182;</a></h1>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[9]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">A</span><span class="o">.</span><span class="n">info</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>&lt;class &#39;pandas.core.frame.DataFrame&#39;&gt;
RangeIndex: 93 entries, 0 to 92
Data columns (total 25 columns):
 #   Column              Non-Null Count  Dtype  
---  ------              --------------  -----  
 0   Manufacturer        93 non-null     object 
 1   Type                93 non-null     object 
 2   Min.Price           93 non-null     float64
 3   Price               93 non-null     float64
 4   Max.Price           93 non-null     float64
 5   MPG.city            93 non-null     int64  
 6   MPG.highway         93 non-null     int64  
 7   AirBags             93 non-null     object 
 8   DriveTrain          93 non-null     object 
 9   Cylinders           93 non-null     object 
 10  EngineSize          93 non-null     float64
 11  Horsepower          93 non-null     int64  
 12  RPM                 93 non-null     int64  
 13  Rev.per.mile        93 non-null     int64  
 14  Man.trans.avail     93 non-null     object 
 15  Fuel.tank.capacity  93 non-null     float64
 16  Passengers          93 non-null     int64  
 17  Length              93 non-null     int64  
 18  Wheelbase           93 non-null     int64  
 19  Width               93 non-null     int64  
 20  Turn.circle         93 non-null     int64  
 21  Rear.seat.room      93 non-null     float64
 22  Luggage.room        93 non-null     float64
 23  Weight              93 non-null     int64  
 24  Origin              93 non-null     object 
dtypes: float64(7), int64(11), object(7)
memory usage: 18.3+ KB
</pre>
</div>
</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[10]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">cat</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">con</span> <span class="o">=</span> <span class="p">[]</span>
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="n">A</span><span class="o">.</span><span class="n">columns</span><span class="p">:</span>
    <span class="k">if</span><span class="p">(</span><span class="n">A</span><span class="p">[</span><span class="n">i</span><span class="p">]</span><span class="o">.</span><span class="n">dtypes</span><span class="o">==</span><span class="s2">&quot;object&quot;</span><span class="p">):</span>
        <span class="n">cat</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">i</span><span class="p">)</span>
    <span class="k">else</span><span class="p">:</span>
        <span class="n">con</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">i</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[11]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">cat</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[11]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>[&#39;Manufacturer&#39;,
 &#39;Type&#39;,
 &#39;AirBags&#39;,
 &#39;DriveTrain&#39;,
 &#39;Cylinders&#39;,
 &#39;Man.trans.avail&#39;,
 &#39;Origin&#39;]</pre>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[12]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">con</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[12]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>[&#39;Min.Price&#39;,
 &#39;Price&#39;,
 &#39;Max.Price&#39;,
 &#39;MPG.city&#39;,
 &#39;MPG.highway&#39;,
 &#39;EngineSize&#39;,
 &#39;Horsepower&#39;,
 &#39;RPM&#39;,
 &#39;Rev.per.mile&#39;,
 &#39;Fuel.tank.capacity&#39;,
 &#39;Passengers&#39;,
 &#39;Length&#39;,
 &#39;Wheelbase&#39;,
 &#39;Width&#39;,
 &#39;Turn.circle&#39;,
 &#39;Rear.seat.room&#39;,
 &#39;Luggage.room&#39;,
 &#39;Weight&#39;]</pre>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h1 id="EDA-CHARTS:">EDA CHARTS:<a class="anchor-link" href="#EDA-CHARTS:">&#182;</a></h1>
</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h1 id="1.-Univariate-Analysis">1. Univariate Analysis<a class="anchor-link" href="#1.-Univariate-Analysis">&#182;</a></h1>
</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h1 id="Univariate-Analysis-of-continous-columns">Univariate Analysis of continous columns<a class="anchor-link" href="#Univariate-Analysis-of-continous-columns">&#182;</a></h1>
</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h1 id="Histogram">Histogram<a class="anchor-link" href="#Histogram">&#182;</a></h1>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[14]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">pd</span><span class="o">.</span><span class="n">set_option</span><span class="p">(</span><span class="s2">&quot;display.Max_rows&quot;</span><span class="p">,</span><span class="kc">None</span><span class="p">)</span>
<span class="n">pd</span><span class="o">.</span><span class="n">set_option</span><span class="p">(</span><span class="s2">&quot;display.MAx_columns&quot;</span><span class="p">,</span><span class="kc">None</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[15]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">A</span><span class="o">.</span><span class="n">sort_values</span><span class="p">(</span><span class="n">by</span><span class="o">=</span><span class="p">[</span><span class="s2">&quot;Horsepower&quot;</span><span class="p">])[[</span><span class="s2">&quot;Horsepower&quot;</span><span class="p">]]</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[15]:</div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/html">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Horsepower</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>38</th>
      <td>55</td>
    </tr>
    <tr>
      <th>30</th>
      <td>63</td>
    </tr>
    <tr>
      <th>82</th>
      <td>70</td>
    </tr>
    <tr>
      <th>79</th>
      <td>73</td>
    </tr>
    <tr>
      <th>72</th>
      <td>74</td>
    </tr>
    <tr>
      <th>43</th>
      <td>81</td>
    </tr>
    <tr>
      <th>87</th>
      <td>81</td>
    </tr>
    <tr>
      <th>52</th>
      <td>82</td>
    </tr>
    <tr>
      <th>83</th>
      <td>82</td>
    </tr>
    <tr>
      <th>78</th>
      <td>85</td>
    </tr>
    <tr>
      <th>39</th>
      <td>90</td>
    </tr>
    <tr>
      <th>80</th>
      <td>90</td>
    </tr>
    <tr>
      <th>22</th>
      <td>92</td>
    </tr>
    <tr>
      <th>28</th>
      <td>92</td>
    </tr>
    <tr>
      <th>61</th>
      <td>92</td>
    </tr>
    <tr>
      <th>71</th>
      <td>92</td>
    </tr>
    <tr>
      <th>45</th>
      <td>92</td>
    </tr>
    <tr>
      <th>23</th>
      <td>93</td>
    </tr>
    <tr>
      <th>32</th>
      <td>96</td>
    </tr>
    <tr>
      <th>26</th>
      <td>100</td>
    </tr>
    <tr>
      <th>59</th>
      <td>100</td>
    </tr>
    <tr>
      <th>24</th>
      <td>100</td>
    </tr>
    <tr>
      <th>41</th>
      <td>102</td>
    </tr>
    <tr>
      <th>53</th>
      <td>103</td>
    </tr>
    <tr>
      <th>33</th>
      <td>105</td>
    </tr>
    <tr>
      <th>88</th>
      <td>109</td>
    </tr>
    <tr>
      <th>68</th>
      <td>110</td>
    </tr>
    <tr>
      <th>63</th>
      <td>110</td>
    </tr>
    <tr>
      <th>11</th>
      <td>110</td>
    </tr>
    <tr>
      <th>12</th>
      <td>110</td>
    </tr>
    <tr>
      <th>5</th>
      <td>110</td>
    </tr>
    <tr>
      <th>14</th>
      <td>110</td>
    </tr>
    <tr>
      <th>73</th>
      <td>110</td>
    </tr>
    <tr>
      <th>91</th>
      <td>114</td>
    </tr>
    <tr>
      <th>34</th>
      <td>115</td>
    </tr>
    <tr>
      <th>44</th>
      <td>124</td>
    </tr>
    <tr>
      <th>31</th>
      <td>127</td>
    </tr>
    <tr>
      <th>46</th>
      <td>128</td>
    </tr>
    <tr>
      <th>85</th>
      <td>130</td>
    </tr>
    <tr>
      <th>81</th>
      <td>130</td>
    </tr>
    <tr>
      <th>57</th>
      <td>130</td>
    </tr>
    <tr>
      <th>89</th>
      <td>134</td>
    </tr>
    <tr>
      <th>84</th>
      <td>135</td>
    </tr>
    <tr>
      <th>86</th>
      <td>138</td>
    </tr>
    <tr>
      <th>60</th>
      <td>140</td>
    </tr>
    <tr>
      <th>77</th>
      <td>140</td>
    </tr>
    <tr>
      <th>0</th>
      <td>140</td>
    </tr>
    <tr>
      <th>42</th>
      <td>140</td>
    </tr>
    <tr>
      <th>36</th>
      <td>140</td>
    </tr>
    <tr>
      <th>20</th>
      <td>141</td>
    </tr>
    <tr>
      <th>25</th>
      <td>142</td>
    </tr>
    <tr>
      <th>35</th>
      <td>145</td>
    </tr>
    <tr>
      <th>21</th>
      <td>147</td>
    </tr>
    <tr>
      <th>64</th>
      <td>150</td>
    </tr>
    <tr>
      <th>65</th>
      <td>151</td>
    </tr>
    <tr>
      <th>19</th>
      <td>153</td>
    </tr>
    <tr>
      <th>67</th>
      <td>155</td>
    </tr>
    <tr>
      <th>55</th>
      <td>155</td>
    </tr>
    <tr>
      <th>40</th>
      <td>160</td>
    </tr>
    <tr>
      <th>13</th>
      <td>160</td>
    </tr>
    <tr>
      <th>50</th>
      <td>160</td>
    </tr>
    <tr>
      <th>74</th>
      <td>160</td>
    </tr>
    <tr>
      <th>66</th>
      <td>160</td>
    </tr>
    <tr>
      <th>54</th>
      <td>164</td>
    </tr>
    <tr>
      <th>16</th>
      <td>165</td>
    </tr>
    <tr>
      <th>92</th>
      <td>168</td>
    </tr>
    <tr>
      <th>15</th>
      <td>170</td>
    </tr>
    <tr>
      <th>8</th>
      <td>170</td>
    </tr>
    <tr>
      <th>6</th>
      <td>170</td>
    </tr>
    <tr>
      <th>76</th>
      <td>170</td>
    </tr>
    <tr>
      <th>17</th>
      <td>170</td>
    </tr>
    <tr>
      <th>69</th>
      <td>170</td>
    </tr>
    <tr>
      <th>70</th>
      <td>170</td>
    </tr>
    <tr>
      <th>2</th>
      <td>172</td>
    </tr>
    <tr>
      <th>3</th>
      <td>172</td>
    </tr>
    <tr>
      <th>90</th>
      <td>178</td>
    </tr>
    <tr>
      <th>7</th>
      <td>180</td>
    </tr>
    <tr>
      <th>48</th>
      <td>185</td>
    </tr>
    <tr>
      <th>37</th>
      <td>190</td>
    </tr>
    <tr>
      <th>9</th>
      <td>200</td>
    </tr>
    <tr>
      <th>1</th>
      <td>200</td>
    </tr>
    <tr>
      <th>75</th>
      <td>200</td>
    </tr>
    <tr>
      <th>62</th>
      <td>202</td>
    </tr>
    <tr>
      <th>4</th>
      <td>208</td>
    </tr>
    <tr>
      <th>51</th>
      <td>210</td>
    </tr>
    <tr>
      <th>29</th>
      <td>214</td>
    </tr>
    <tr>
      <th>58</th>
      <td>217</td>
    </tr>
    <tr>
      <th>49</th>
      <td>225</td>
    </tr>
    <tr>
      <th>56</th>
      <td>255</td>
    </tr>
    <tr>
      <th>47</th>
      <td>278</td>
    </tr>
    <tr>
      <th>10</th>
      <td>295</td>
    </tr>
    <tr>
      <th>27</th>
      <td>300</td>
    </tr>
    <tr>
      <th>18</th>
      <td>300</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[16]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">plt</span><span class="o">.</span><span class="n">hist</span><span class="p">(</span><span class="n">A</span><span class="o">.</span><span class="n">Horsepower</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">&quot;HP_Histogram&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s2">&quot;Horsepower&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s2">&quot;No of Hp&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[24]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">bins</span> <span class="o">=</span> <span class="p">[</span><span class="mi">50</span><span class="p">,</span><span class="mi">75</span><span class="p">,</span><span class="mi">100</span><span class="p">,</span><span class="mi">125</span><span class="p">,</span><span class="mi">150</span><span class="p">,</span><span class="mi">175</span><span class="p">,</span><span class="mi">200</span><span class="p">,</span><span class="mi">225</span><span class="p">,</span><span class="mi">250</span><span class="p">,</span><span class="mi">275</span><span class="p">,</span><span class="mi">300</span><span class="p">,</span><span class="mi">325</span><span class="p">]</span>
<span class="n">plt</span><span class="o">.</span><span class="n">hist</span><span class="p">(</span><span class="n">A</span><span class="o">.</span><span class="n">Horsepower</span><span class="p">,</span><span class="n">bins</span><span class="p">,</span><span class="n">rwidth</span><span class="o">=</span><span class="mf">0.8</span><span class="p">,</span><span class="n">color</span><span class="o">=</span><span class="s2">&quot;red&quot;</span><span class="p">,</span><span class="n">label</span><span class="o">=</span><span class="p">[</span><span class="s2">&quot;HP_Histogram&quot;</span><span class="p">])</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">&quot;HP_Histogram&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s2">&quot;Horsepower&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s2">&quot;No of Hp&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">loc</span><span class="o">=</span><span class="mi">2</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">grid</span><span class="p">(</span><span class="kc">True</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h1 id="distribution-plot">distribution plot<a class="anchor-link" href="#distribution-plot">&#182;</a></h1>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[26]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">sb</span><span class="o">.</span><span class="n">distplot</span><span class="p">(</span><span class="n">A</span><span class="o">.</span><span class="n">Horsepower</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xticks</span><span class="p">(</span><span class="nb">range</span><span class="p">(</span><span class="mi">0</span><span class="p">,</span><span class="mi">380</span><span class="p">,</span><span class="mi">25</span><span class="p">))</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[26]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>([&lt;matplotlib.axis.XTick at 0xd6c0700&gt;,
  &lt;matplotlib.axis.XTick at 0xd6c06d0&gt;,
  &lt;matplotlib.axis.XTick at 0xd413a00&gt;,
  &lt;matplotlib.axis.XTick at 0xd3f8d90&gt;,
  &lt;matplotlib.axis.XTick at 0xd3f8b50&gt;,
  &lt;matplotlib.axis.XTick at 0xd3e6af0&gt;,
  &lt;matplotlib.axis.XTick at 0xd3e63a0&gt;,
  &lt;matplotlib.axis.XTick at 0xd3f80a0&gt;,
  &lt;matplotlib.axis.XTick at 0xd3e6580&gt;,
  &lt;matplotlib.axis.XTick at 0xd3f0f40&gt;,
  &lt;matplotlib.axis.XTick at 0xd6bd3a0&gt;,
  &lt;matplotlib.axis.XTick at 0xd3a5430&gt;,
  &lt;matplotlib.axis.XTick at 0xd3a5910&gt;,
  &lt;matplotlib.axis.XTick at 0xd3a5e50&gt;,
  &lt;matplotlib.axis.XTick at 0xd3c9370&gt;,
  &lt;matplotlib.axis.XTick at 0xd3c9a00&gt;],
 [Text(0, 0, &#39;&#39;),
  Text(0, 0, &#39;&#39;),
  Text(0, 0, &#39;&#39;),
  Text(0, 0, &#39;&#39;),
  Text(0, 0, &#39;&#39;),
  Text(0, 0, &#39;&#39;),
  Text(0, 0, &#39;&#39;),
  Text(0, 0, &#39;&#39;),
  Text(0, 0, &#39;&#39;),
  Text(0, 0, &#39;&#39;),
  Text(0, 0, &#39;&#39;),
  Text(0, 0, &#39;&#39;),
  Text(0, 0, &#39;&#39;),
  Text(0, 0, &#39;&#39;),
  Text(0, 0, &#39;&#39;),
  Text(0, 0, &#39;&#39;)])</pre>
</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h1 id="Univariate-of-categorical-columns">Univariate of categorical columns<a class="anchor-link" href="#Univariate-of-categorical-columns">&#182;</a></h1>
</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h1 id="Bar-plot">Bar plot<a class="anchor-link" href="#Bar-plot">&#182;</a></h1>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[27]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">A</span><span class="o">.</span><span class="n">Type</span><span class="o">.</span><span class="n">value_counts</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[27]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>Midsize    22
Small      21
Compact    16
Sporty     14
Large      11
Van         9
Name: Type, dtype: int64</pre>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[31]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">A</span><span class="o">.</span><span class="n">Type</span><span class="o">.</span><span class="n">value_counts</span><span class="p">()</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">kind</span><span class="o">=</span><span class="s2">&quot;bar&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">&quot;Car_Type_Bar&quot;</span><span class="p">,</span><span class="n">fontsize</span><span class="o">=</span><span class="mi">15</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s2">&quot;Car type&quot;</span><span class="p">,</span><span class="n">fontsize</span><span class="o">=</span><span class="mi">12</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s2">&quot;No of Cars&quot;</span><span class="p">,</span><span class="n">fontsize</span><span class="o">=</span><span class="mi">12</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[32]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">A</span><span class="o">.</span><span class="n">Type</span><span class="o">.</span><span class="n">value_counts</span><span class="p">()</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">kind</span><span class="o">=</span><span class="s2">&quot;barh&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">&quot;Car_Type_Bar&quot;</span><span class="p">,</span><span class="n">fontsize</span><span class="o">=</span><span class="mi">15</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s2">&quot;Car type&quot;</span><span class="p">,</span><span class="n">fontsize</span><span class="o">=</span><span class="mi">12</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s2">&quot;No of Cars&quot;</span><span class="p">,</span><span class="n">fontsize</span><span class="o">=</span><span class="mi">12</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h1 id="Pie-plot">Pie plot<a class="anchor-link" href="#Pie-plot">&#182;</a></h1>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[33]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">A</span><span class="o">.</span><span class="n">Type</span><span class="o">.</span><span class="n">value_counts</span><span class="p">()</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">kind</span><span class="o">=</span><span class="s2">&quot;pie&quot;</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[33]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>&lt;AxesSubplot:ylabel=&#39;Type&#39;&gt;</pre>
</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h1 id="countplot">countplot<a class="anchor-link" href="#countplot">&#182;</a></h1>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[34]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">sb</span><span class="o">.</span><span class="n">countplot</span><span class="p">(</span><span class="n">A</span><span class="o">.</span><span class="n">Type</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[34]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>&lt;AxesSubplot:xlabel=&#39;Type&#39;, ylabel=&#39;count&#39;&gt;</pre>
</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[35]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">sb</span><span class="o">.</span><span class="n">countplot</span><span class="p">(</span><span class="n">A</span><span class="o">.</span><span class="n">Type</span><span class="p">,</span><span class="n">order</span><span class="o">=</span><span class="p">[</span><span class="s2">&quot;Van&quot;</span><span class="p">,</span><span class="s2">&quot;Large&quot;</span><span class="p">,</span><span class="s2">&quot;Sporty&quot;</span><span class="p">,</span><span class="s2">&quot;Compact&quot;</span><span class="p">,</span><span class="s2">&quot;Small&quot;</span><span class="p">,</span><span class="s2">&quot;Midsize&quot;</span><span class="p">])</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[35]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>&lt;AxesSubplot:xlabel=&#39;Type&#39;, ylabel=&#39;count&#39;&gt;</pre>
</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h1 id="Multiple-plots-in-one-area">Multiple plots in one area<a class="anchor-link" href="#Multiple-plots-in-one-area">&#182;</a></h1>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[36]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">cat</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[36]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>[&#39;Manufacturer&#39;,
 &#39;Type&#39;,
 &#39;AirBags&#39;,
 &#39;DriveTrain&#39;,
 &#39;Cylinders&#39;,
 &#39;Man.trans.avail&#39;,
 &#39;Origin&#39;]</pre>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[37]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="nb">len</span><span class="p">(</span><span class="n">cat</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[37]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>7</pre>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[38]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">13</span><span class="p">,</span><span class="mi">10</span><span class="p">))</span>

<span class="n">plt</span><span class="o">.</span><span class="n">subplot</span><span class="p">(</span><span class="mi">3</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span><span class="mi">1</span><span class="p">)</span>
<span class="n">sb</span><span class="o">.</span><span class="n">countplot</span><span class="p">(</span><span class="n">A</span><span class="o">.</span><span class="n">Manufacturer</span><span class="p">)</span>

<span class="n">plt</span><span class="o">.</span><span class="n">subplot</span><span class="p">(</span><span class="mi">3</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span><span class="mi">2</span><span class="p">)</span>
<span class="n">sb</span><span class="o">.</span><span class="n">countplot</span><span class="p">(</span><span class="n">A</span><span class="o">.</span><span class="n">Type</span><span class="p">)</span>

<span class="n">plt</span><span class="o">.</span><span class="n">subplot</span><span class="p">(</span><span class="mi">3</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span><span class="mi">3</span><span class="p">)</span>
<span class="n">sb</span><span class="o">.</span><span class="n">countplot</span><span class="p">(</span><span class="n">A</span><span class="o">.</span><span class="n">AirBags</span><span class="p">)</span>

<span class="n">plt</span><span class="o">.</span><span class="n">subplot</span><span class="p">(</span><span class="mi">3</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span><span class="mi">4</span><span class="p">)</span>
<span class="n">sb</span><span class="o">.</span><span class="n">countplot</span><span class="p">(</span><span class="n">A</span><span class="o">.</span><span class="n">DriveTrain</span><span class="p">)</span>

<span class="n">plt</span><span class="o">.</span><span class="n">subplot</span><span class="p">(</span><span class="mi">3</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span><span class="mi">5</span><span class="p">)</span>
<span class="n">sb</span><span class="o">.</span><span class="n">countplot</span><span class="p">(</span><span class="n">A</span><span class="o">.</span><span class="n">Cylinders</span><span class="p">)</span>

<span class="n">plt</span><span class="o">.</span><span class="n">subplot</span><span class="p">(</span><span class="mi">3</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span><span class="mi">6</span><span class="p">)</span>
<span class="n">sb</span><span class="o">.</span><span class="n">countplot</span><span class="p">(</span><span class="n">A</span><span class="p">[</span><span class="s2">&quot;Man.trans.avail&quot;</span><span class="p">])</span>

<span class="n">plt</span><span class="o">.</span><span class="n">subplot</span><span class="p">(</span><span class="mi">3</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span><span class="mi">7</span><span class="p">)</span>
<span class="n">sb</span><span class="o">.</span><span class="n">countplot</span><span class="p">(</span><span class="n">A</span><span class="o">.</span><span class="n">Origin</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[38]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>&lt;AxesSubplot:xlabel=&#39;Origin&#39;, ylabel=&#39;count&#39;&gt;</pre>
</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAwUAAAJNCAYAAABgGdnMAAAAOXRFWHRTb2Z0d2FyZQBNYXRwbG90bGliIHZlcnNpb24zLjMuNCwgaHR0cHM6Ly9tYXRwbG90bGliLm9yZy8QVMy6AAAACXBIWXMAAAsTAAALEwEAmpwYAABglUlEQVR4nO3debgkZX33//fHARVFNhkIijjGEBU30JGoGBcQ444LLjyiozEheRKJGjVizE9RnyQkLtHgkoe4gEtUBBEkbjwoEpcAgyCLqLgQREZmcGMRQeD7++O+j6c5nDNzZuZ095np9+u6+uqu6lq+XV13VX3rvqsqVYUkSZKkyXWbcQcgSZIkabxMCiRJkqQJZ1IgSZIkTTiTAkmSJGnCmRRIkiRJE86kQJIkSZpwW4w7gPnYcccda9myZeMOQ9psnH322VdW1dJxxzEfln9pYVn+pcm1tvK/SSQFy5YtY+XKleMOQ9psJPmfcccwX5Z/aWFZ/qXJtbbyb/MhSZIkacKZFEiSJEkTbixJQZKXJ7kwyQVJPprk9uOIQ5IkSdIYkoIkdwX+ClheVfcDlgDPHXUckiRJkppxNR/aAtgqyRbAHYDLxxSHJEmSNPFGnhRU1Y+BtwCXAquAX1bVF0YdhyRJkqRm5LckTbI9cABwD+AXwCeSHFxVH54x3CHAIQC77bbbqMOc1Rff+6Rb9dv3T/5zpDG8+rjHz9r/nw783EjjkASXvvH+I5/nbq87f+TzlKTNxT5H7jPuEIbuq4d+dYPGG0fzoccCP6yqNVX1G+CTwMNnDlRVR1XV8qpavnTpJvGMFUmSJGmTNI6k4FLgoUnukCTAfsBFY4hDkiRJEuO5puAM4DjgG8D5PYajRh2HJEmSpGbk1xQAVNXrgdePY96SJEmSbsknGkuSJEkTzqRAkiRJmnBjaT4kSRvqwa/64Ejnd/abXzDS+UmSNA7WFEiSJEkTzqRAkiRJmnAmBZIWXJK7JflSkouSXJjkpb3/DklOSXJxf99+3LFKkiSTAknDcSPwiqq6D/BQ4C+T7AEcBpxaVbsDp/ZuSZI0ZiYFkhZcVa2qqm/0z1fTnlp+V+AA4Jg+2DHA08YSoCRJugWTAklDlWQZsBdwBrBzVa2CljgAO40xNEmS1JkUSBqaJFsDxwMvq6qr1mO8Q5KsTLJyzZo1wwtQkiQBJgWShiTJlrSE4CNV9cne+4oku/TvdwFWzzZuVR1VVcuravnSpUtHE7AkSRPMpEDSgksS4H3ARVX1toGvTgJW9M8rgBNHHZuk0UiyJMk5SU7u3d59TFrETAokDcM+wPOBfZOc219PBI4A9k9yMbB/75a0eXop7SYDU7z7mLSIbTHuACRtfqrqK0Dm+Hq/UcYiafSS7Ao8Cfh74K977wOAR/fPxwCnAa8edWySZmdNgSRJWmhvB/4GuHmgn3cfkxYxkwJJkrRgkjwZWF1VZ2/g+N59TBoDkwJJkrSQ9gGemuQS4GO0a4s+jHcfkxY1kwJJkrRgquo1VbVrVS0Dngt8saoOxruPSYuaSYEkSRoF7z4mLWLefUiSJA1FVZ1Gu8sQVfVTvPuYtGhZUyBJkiRNOJMCSZIkacKZFEiSJEkTzqRAkiRJmnAmBZIkSdKEMymQJEmSJpxJgSRJkjThTAokSZKkCWdSIEmSJE24sSQFSbZLclySbye5KMnDxhGHJEmSJNhiTPN9B/C5qjowyW2BO4wpDkmSJGnijTwpSLIN8EjghQBVdQNww6jjkCRJktSMo/nQ7wJrgA8kOSfJe5PccQxxSJIkSWI8zYe2AB4EHFpVZyR5B3AY8P8NDpTkEOAQgN12223kQY7C//3QH92q3589//NjiESSJEmTbBw1BZcBl1XVGb37OFqScAtVdVRVLa+q5UuXLh1pgJIkSdIkGXlSUFU/AX6U5F69137At0YdhyRJkqRmXHcfOhT4SL/z0A+AF40pDknabOxz5D4jnd9XD/3qSOcnSRqesSQFVXUusHwc85YkSZJ0S+OqKZAkSdpgD37VB8cdwtCd/eYXjDsETZCxPNFY0uYtyfuTrE5ywUC/w5P8OMm5/fXEccYoSZKmmRRIGoajgcfP0v9fqmrP/vrMiGOSJElzMCmQtOCq6nTgZ+OOQ5IkzY9JgaRRekmS83rzou3HHYwkSWpMCiSNynuAewJ7AquAt841YJJDkqxMsnLNmjUjCk+SpMllUiBpJKrqiqq6qapuBv4d2Hstw/pEc2kTleT2Sc5M8s0kFyZ5Q++/Q5JTklzc360tlBYRkwJJI5Fkl4HOpwMXzDWspE3a9cC+VfVAWs3g45M8FDgMOLWqdgdO7d2SFgmfUyBpwSX5KPBoYMcklwGvBx6dZE+ggEuAPxtXfJKGp6oKuKZ3btlfBRxA2y4AHAOcBrx6xOFJmoNJgaQFV1UHzdL7fSMPRNJYJFkCnA38HvCuqjojyc5VtQqgqlYl2WmsQUq6BZsPSZKkBdWvH9oT2BXYO8n95juuNxqQxsOkQJIkDUVV/YLWTOjxwBVT1xb199VzjOONBqQxsPmQJGmz985XfHqk83vJW58y0vktJkmWAr+pql8k2Qp4LPBPwEnACuCI/n7i+KKUNJNJgSRJWki7AMf06wpuAxxbVScn+TpwbJIXA5cCzxpnkJJuyaRAI/OU446/Vb9PH/jMMUSy/j778Stv1e8Jz9lxDJFI0uJWVecBe83S/6fAfqOPSNJ8eE2BJEmSNOFMCiRJkqQJt1FJQZJT59NP0qbLci5NLsu/NDk26JqCJLcH7kB7Wun2QPpX2wB3WaDYJI2R5VyaXJZ/afJs6IXGfwa8jLZhOJvpjcVVwLs2PixJi4DlXJpcln9pwmxQUlBV7wDekeTQqjpygWOStAhYzqXJZfmXJs9G3ZK0qo5M8nBg2eC0quqDGxmXpEXCci5NLsu/NDk2KilI8iHgnsC5wE29dwFuLKTNhOVcmlyWf2lybOzDy5YDe1RVLUQwkhYly7k0uSz/0oTY2OcUXAD8zkIEImnRspxLk8vyL02Ija0p2BH4VpIzgeunelbVUzdyupIWD8u5NLks/9KE2Nik4PCFCELSonb4uAOQNDaHjzsASaOxsXcf+vJCBSJpcbKcS5PL8i9Njo29+9DVtLsQANwW2BK4tqq22djAJC0OlnNpcln+pcmxsTUFdxrsTvI0YO/5jJtkCbAS+HFVPXlj4pA0PBtTziVt2iz/0uTY2LsP3UJVfQrYd56DvxS4aCHnL2n41rOcS9qMWP6lzdfGNh96xkDnbWj3M17nvYyT7Ao8Cfh74K83JgZJw7Wh5VzSps/yL02Ojb370FMGPt8IXAIcMI/x3g78DXCndQwnafw2tJxL2vRZ/qUJsbHXFLxofcdJ8mRgdVWdneTRaxnuEOAQgN12221DQ5zT9955623a773kxAWfz2L3xBP+cdb+n3n6a0YcycI66JOX3KrfR5+xjH86YdWsw7/66bsMOaKNd8Xbz7pVv51f9hAAVh/5pVt9t9Ohj1mQ+W5IOZe+/MhHjXyejzrdG+UsNMu/NDk26pqCJLsmOSHJ6iRXJDm+Nw1am32Apya5BPgYsG+SD88cqKqOqqrlVbV86dKlGxOmpI2wgeVc0mbA8i9Njo290PgDwEnAXYC7Ap/u/eZUVa+pql2rahnwXOCLVXXwRsYhaXjWu5xL2mxY/qUJsbFJwdKq+kBV3dhfRwOe1pc2L+tdzpO8v59ZvGCg3w5JTklycX/fftiBS9po7uelCbGxScGVSQ5OsqS/DgZ+Ot+Rq+o0n1EgLXobUs6PBh4/o99hwKlVtTtwau+WtLht1H5e0qZjY5OCPwaeDfwEWAUcCHhRkrR5We9yXlWnAz+b0fsA4Jj++RjgaQsapaRhcD8vTYiNTQreBKyoqqVVtRNt43H4RkclaTFZqHK+c1WtAujvOy1ciJKGZL3Lf5K7JflSkouSXJjkpb2/TQilRWxjk4IHVNXPpzqq6mfAXhs5TUmLy8jLeZJDkqxMsnLNmjXDnJWktduQ8n8j8Iqqug/wUOAvk+yBTQilRW1jk4LbDGb6SXZg4x+IJmlxWahyfkWSXfo0dgFWzzWgtySWFo31Lv9VtaqqvtE/Xw1cRLtzkU0IpUVsYw/g3wp8LclxtMeePxv4+42OStJislDl/CRgBXBEf5+8pwVKm56NKv9JltFqFs5gRhPCJDYhlBaRjX2i8QeTrAT2BQI8o6q+tSCRSVoUNqScJ/ko8GhgxySXAa+nJQPHJnkxcCnwrKEGLmmjbcx+PsnWwPHAy6rqqiTzmmeSQ4BDAHbbbbcNilvS+tvopj5942AiIG3G1recV9VBc3y138JEJGlUNmQ/n2RLWkLwkar6ZO99RZJdei3BnE0Iq+oo4CiA5cuX14ZHLml9bOw1BZIkSb+VViXwPuCiqnrbwFdTTQjBJoTSouNFwZIkaSHtAzwfOD/Jub3f32ITQmlRMymQJGmE/v7gA0c+z9d++LiRzauqvkK7/mA2NiGUFimbD0mSJEkTzqRAkiRJmnAmBZIkSdKEMymQJEmSJpwXGk+IJ37qFbfq95mnvXUMkQjgx29edat+d33VLmOIRJIkyZoCSZIkaeKZFEiSJEkTzqRAkiRJmnAmBZIkSdKEMymQJEmSJpxJgSRJkjThTAokSZKkCWdSIEmSJE04kwJJkiRpwpkUSJIkSRNui3EHIEmSpIVz6RvvP+4Qhm63150/7hA2O9YUSJIkSRPOpECSJEmacCYFkiRJ0oQbeVKQ5G5JvpTkoiQXJnnpqGOQJEmSNG0cFxrfCLyiqr6R5E7A2UlOqapvjSEWSZIkaeKNvKagqlZV1Tf656uBi4C7jjoOSZIkSc1Yb0maZBmwF3DGOOOQNDpJLgGuBm4Cbqyq5eONSJIkjS0pSLI1cDzwsqq6apbvDwEOAdhtt91Y854P32oaS//3waz+tyNnnf5Of37oBsV11v99yqz9H/Jnn96g6X3k6D+atf/zXvj5tY735o/eerxXHbT2cZ564uNv1e+kAz631nE21JOOf9+t+v3nM1/Mk4/7yKzDn3zg89Y6vQOO++yt+p144BN4+vFfnnX4E575KA48/hu36n/cMx+01vlMmtXv2rD1dgQeU1VXjjsISZLUjOXuQ0m2pCUEH6mqT842TFUdVVXLq2r50qVLRxugJEnaIEnen2R1kgsG+u2Q5JQkF/f37ccZo6RbG8fdhwK8D7ioqt426vlLGrsCvpDk7F4jKGnzcjQws+r6MODUqtodOLV3S1pExlFTsA/wfGDfJOf21xPHEIek8dinqh4EPAH4yySPnDlAkkOSrEyycs2aNaOPUNIGq6rTgZ/N6H0AcEz/fAzwtFHGJGndRn5NQVV9Bcio5ytpcaiqy/v76iQnAHsDp88Y5ijgKIDly5fXyIOUtNB2rqpV0O5CmGSncQck6ZZ8orGkkUlyx/58EpLcEXgccMHax5I0SawplMbDpEDSKO0MfCXJN4Ezgf+squHcIkvSYnJFkl0A+vvquQb0RiPSeIz1OQWSJktV/QB44LjjkDRyJwErgCP6+4njDUfSTNYUSJKkBZPko8DXgXsluSzJi2nJwP5JLgb2792SFhFrCiRJ0oKpqoPm+Gq/kQYiab1YUyBJkiRNOJMCSZIkacKZFEiSJEkTzqRAkiRJmnAmBZIkSdKEMymQJEmSJpxJgSRJkjThTAokSZKkCWdSIEmSJE24zfqJxqve/epb9dvlL/5pKPM68f1PuFW/A/74s0OZ16g86ZNH3qrffz7j0DFEMhof/uSaW/U7+BlL1zrO14659TgAD1+xlAv/7Ypb9b/vn++81un95K3fnrX/77zi3msdT5IkaWNYUyBJkiRNOJMCSZIkacKZFEiSJEkTzqRAkiRJmnAmBZIkSdKEMymQJEmSJpxJgSRJkjThTAokSZKkCWdSIEmSJE04kwJJkiRpwpkUSJIkSRPOpECSJEmacCYFkiRJ0oQzKZAkSZIm3FiSgiSPT/KdJN9Lctg4YpA0HpZ/aXJZ/qXFa+RJQZIlwLuAJwB7AAcl2WPUcUgaPcu/NLks/9LiNo6agr2B71XVD6rqBuBjwAFjiEPS6Fn+pcll+ZcWsXEkBXcFfjTQfVnvJ2nzZ/mXJpflX1rEUlWjnWHyLOCPqupPevfzgb2r6tAZwx0CHNI77wV8p3/eEbhyjslvyHdOz+lN4vTuXlVL5xhuaBag/G+MtS2bUVtMscDiimcxxQKbZzyTWP4XymJbHxYTl83cFtOymbv8V9VIX8DDgM8PdL8GeM16jL9yIb9zek7P6Y3utbHlfyPnPfbfvxhjWWzxLKZYjGfBYx9b+Xf5u2xcNut+jaP50FnA7knukeS2wHOBk8YQh6TRs/xLk8vyLy1iW4x6hlV1Y5KXAJ8HlgDvr6oLRx2HpNGz/EuTy/IvLW4jTwoAquozwGc2cPSjFvg7p+f0nN4IbWT53xiL4vd3iykWWFzxLKZYwHgW1BjL/0LZpJf/kLls5rZJLJuRX2gsSZIkaXEZyxONJUmSJC0eY08Kkjw9SSW59/oMl+SmJOcm+WaSbyR5+ED/SvLrJNcnuW6g3+okn05yQ5L04R/Wv/tiku8nubIP/2dJvpvkWUkuSPKbJD9I8pk+zOdnxDcVz4U9pr9OclqS5UkuSbLjwDBTr8MGxv/bPtzbZxlu2Yx5XZfkx0luTnJ2f1z8Z5K8MMk7B4ZbluSCge5rZkynknxo8PsZy+yuSY4b+P7PkxyV5J2D4/Z537kvl/OTPDXJYUnu0ocbHHaLJGv6fE4eWGaH9e9fnGRVf30/yTv6+B9PcnIf5pVJDu8x/ijJjX3eP+ix35x2S7vB3/regeV6QZJPJLnDwPenJVk+y3r3qb6+nNdjuqQv+3OTfDXJvyT5ZZ/2d5K8vI/3wh7bWUl+nuR/kvwkyelJ3jfw3/5kYHo3JNll5v82mx7vdTP6vayvD8fNMvwlSXZc2zQ3NUle29ed8/ry+4MFmOY1/X3O/2CWcjO1Tk+tn0/NQNmebfprmf9nkmy3jmF+J8nHevn4Vh/n99fx00air/d3Gehe6+8dlSGtK49O3+8shF6m/2hGv5clefdCzUO31svzWwe6X5nk8DHGM9uxxKzHan0fe6vt/QLFsWOSL/Uyc2aSrecR8632rYvZYlnW6yvJ0UkOHMa0x54UAAcBX6HdhWB9hruuqvasqgfSbmv2j0m2AH4NXA+sBr5Puy/sD4DvAV8Ezuzf36dP5+HAtcD3q+qewGeBS4GdgO8Cfw1c0vs9G/hb2gVSwG8f2z4Yz32B/YEnAstm/IapYaZeRwx897ezDQcsr6pLBuYX4LbAT4FfVdWDgfcAd2T9/89rgfsl2ap3LwEKuKLH8OOq+u2KV1X/BnxtxrhbV9UTaU+qXE27/+1JVXVEVV3eh7sZuH+fz/7AVbT/acrPquqI/tuOAH4BHAr8PrA1cBPwSGDLGfFfV1V3oz0Ap2j/7/eBXwH/lHZ3C5JsUe2+2FPL9X7ADcCfr23hJHkYsDvw/4A/6/N5HvBz4LE91ofS1pXrgCOB+/fRX0j7j+4NfBp4BfBB4HeBowf+338D/qV/vhz4zRyxZMbG6qPc+pqg5wL3GfzPNlf9v3ky8KCqegDt//jR2sdaMDPLzf7Aj6e+nFr/N2TCVfXEqvrFXN/3MnICcFpV3bOq9qBtO3bekPkNwQuBu6xroHXp2/IFMYx1pcf3aNr+Y6F8lFvvB5/b+2t4rgeesYhOmsx2LPH6mQP1/drlC7G9n6O8/W/g9F5mnkbbZ64r5nntWxeRxbKsF49x3g+VdsD3Y9rB37d7vyXAW4DzgfNoB4dbAzcCfwB8G1hOO1A8GTgcOIV2IPh12sHmzf37m/v0fwp8gLay/px24PULYBXtAPgG2oHqGX38m2g7/t8A1/T3q/t8D6MdgP6oD3djn8/NwL/3YX/T51l9etfREpPqw/2kz/eXfdib+3fV4/oN8F8Dv+EGpg92r+nDTY13Li1hmfptq/p41WP4DrBN/776d78ELuyx39SX0Y8H4pt6/evA75sa96oeR/X3qXnd2H9r9d/764F5Vh/v+oFpTc3jl/31q4Fhp17fpCUaNTDedf2/uarPe+o/+B+mk4Op16/6ch9cvtfQ1q0amO5UXIPDTU13qvta2jrwvT7cdX2Yq5le366fZRo1sBxu5Ja//ce0deGqvgymxvtNf59aP67r/+Pf9P7fo61/U7/xy8A3Bsa7uf/OC4FPAWuYXu++AvxFL2tPZDpp/lfaOnZBf32JdvvAc4AD+vAvBD4JfA64GPjnMW47ngF8epb+lwD/QNsWrAQeRLvTyfeBPx/Y7pzal9n5U7+vf3dNf18GXDDHvK/p8ziwd38QeDVw8sByemf/fI8ey1nAmwamvwtwOq38XgD84UD8O9J2quf21w+BL/XvX9XXl28AnwC27v0DvLlP63zgOb3/o/v6cSztJMcRtMT2zD7cPftwR9MS1P/qwz15YDn8V5/fN4CHDyyHv+nT+Gaf7oF92Xynx73V1O+dsfyeQtvWnkNLuHfu/Q+nXYz3BeA/gKW0bfs3gP9LK+M79mEP7r/h3P7dkg1cV/6pT+dM4Pd6/7vT1o/z+vtuA8vobbSycTytPP24x/CH/X/asg+7TZ/+luuxTt+ZVlZvN7DsL6Wd9FlJK89vmBH/G5hej+89zv35pvrq6+xrgL/v3a8EDp/HuvCvtJNkP6BvCwbK6Fl9nDdsSDwzun+Xti8PbdvyCdqJpi8ysJ3qZeq+A+OdBjyYdsLw/cy+Pf/ttGaJ49XA+9Y3Ztq2693MXc4fxfS27RzgTsy9PXwcbfs5c3s367rPem4z+n9/DfDGHuuzx7Ss/5rpfe/Ler9lwEW048oLadvFrQbWvwOB/YATBqazP/DJjSoPYy6MB0+tdLTC9SBadno8sEXvv0Mf7mrazvJrtJ3a1EHTlbSDr0/0BT91UDZ10HhVH+af+vsJtIOsG4AX9fcbaTu2s/v4H+kr3M20lfkntAO+jwDf6tP9Ne3A7PAex/V9WlfTahumkotz+0q3qk/v17SDt1/TDjTP7H/+dT3ui5g+OLye6YJyE23jc+XAd4MHtmtoSUHRDg6OYfpA9j09hhv78vtFH+dXtAJwQ18+UwekUwfSH+1xXj6wbK6jFZCpZXw60wfQJ/dhzu/zv5DpxKhoB+3nMX2Aek2P4ee0nd/UgfS1/f+4iZYU3NyX+820//7SHuNUwlZ9GoMH5Gf0ca/uv+9nvf85PdYbe7+p5OoXA//ByUwnTINJzy96vDfSnrb5P336U8vt2/3/vJr2f08lcDfPmEbRNlo/GvgNP+7L58g+z98A/6sPe1ovC9/p03pmXwZT69dvaBvCVUyvQ2/o8RxMK0P/0/ufQzvAuH2f/8XAbrQDvzW0DeXbaevZLsB2tIPEO9LK1w+Abfv4/wPcbUzbjq37b/8ubQf0qIGdxf/un/+Ftr7dibazWN37bwFs0z/vSEuypm66MN+k4AHAcX05nEs7+J4tKTgJeEH//JcD038F8Nr+eQlwp4H4dxyY15b9v3nKQKxH1vRO+3X98zP7OrCEVmtwaf//Hk1b53YBbkdbz97Qx3kp8PaBncznaLWNu9PWxdsDdwBu34fZnf4AHuAJtG3JHaa20wM7x+WDy2qW5bf9wPL+E+Ct/fPhtO3M1I7vnfQHWwGPp63bO9JqeT/N9AH4u6eW8QasK1P/wQsG/r9PAyv65z8GPjWwjE6mJyA93lcOzOcDwNP650Omftd6rtf/yfSBxGG0bfnUsl3Sl+8DBuI/tH/+C+C94yiLm/qLVp6nkrhtuWVSsLZ14RO9vOwBfK/3fxwtsU3/7mTgkesbzyz9fk4r1y+klc2pdWIZ0weqL2e6bO8CfLd//gfg4P55O265Pf/ttGaZ54G0bcefzzdm2rb1RNpx3Fzl/NPAPv3z1n2cW20PaWX9dOCOvf/g9m7WdZ/13GYwvY9+9riWNS2ZOL8PtzXtuGmvPr8bgT37cMcOTPvo/v+Etp9f2vv/B/CUjSkP424+dBDwsf75Y737scC/VdWNAFX1s97/2oHh/oh2cPRftJXg/cC+/fups7FTf/adaAe1oS30fWkHU1vSFvpvaAeNt6OtOAEeAzyf6YP/C2kr7nKmm72c07/fllb4b9v7b0VLCs7t0/psnza9+1e0A3poO9z70Db0t+/97sb0gWRoG6ulA+Nu04fbog9Df99uYD5PplVr36bP4wDaynlj/61TicfNfTn8mlYLczPTNRw392V1O9pK/6Aew1TtBbSDyz/s8wmwa38/DbgrrQaIgbh26fFcTTsrNtVm+060DcjUMgrtDOvNtIPT0JrhFG1jsx3t4GYrppty3UArdPQY70c7aLtd/4136t/dr49zc++3ZGCcqTPqa3p3gK/Skp+raOvPf/ff+67+G6eWxZL+e5fTCvbv9OGnakB+04e5so9zG9oZx2v7vKA1Q3pO/65oZ5ZvBrbq7cy37zH9Ke3gqWg7pGuBPQfmdVtgH+DDtAPR82jr1e/T1vldaP/bFbQD5UtpCdLlVXUT8Aja+vVVptfN3XqMp1bVL6vq17RE7e6MQVVdQ9uYHkL7vz6e5IX966mHIZ0PnFFVV1fVGuDXfTkG+Ick59GS/ruyns1vquo82rI8iLXfXnEfppt/fGig/1nAi3rb5ftX1dVzjP8O2pmlT9Oaqv0O8Jwk5wIrmF7+jwA+WlU3VdUVtNqBh0zNq6pWVdX1tBqTL/T+53PLJo7HVtXNVXUxLfm7N63s/HuS82kHQXv0YR8LfKCqftWXx8/Wsgxm2hX4fJ/mq4D7Dnx3UlVNXSvzCPr+oao+R9tZQzs79mDgrL4c9qOdTZ3VOtaVjw68P6x/fhht5wrtP3vEwOQ+0cvIbN5LO9FEf//AXDGtxWAToqmmQ89O8g3aPue+TP8H0GruoG0Plm3A/ARU1VW0Gr+/mvHV2taFT/Xy8i2mtx+P669zaCd+7k1LpjdWBj6fMkd5OxZ4Vv/8bFp5nYrpsF5WTuOW2/NZp5XkrsBrgXsBf5Lkmb3/eUm2mTk8bR91Lu2Y4FLgfcxdzr8KvC3JXwHb9WO92baHD6Wt61+dZXsHs6/7G7LNuIl2Ivq3P3/g89CXdY/5hKq6tm+rPknbPwP8sKrOneV30n9j0dbLg/u+7WG0Y84NNrakIMmdaQed701yCW2lGTwgmjncnWmF7FW0pACm4/8O7WDzTgP9XkA7AIN2oHsfpg/ETuvzeADtYG9LWtXv1bQD5LfRzgr8nLbiTB287sh0u/Zf0/7whzGd2Ew1Ofop7cCsaNnpElotQ/XvrqGtPL+hHWTehXZA95OBed0IrKrW1vwdtLPYU6aSnuv6+9FMNzGBdiZpd6abmNyG6QPGG5le6afe19AK4NQB7pQ7934fpGX/l9MOoqYMJklXMZ0YhbYxuXRgWU0lJHej/U83Mn3Afy3tzP7NtIPT82gbju/Tljm0/wba8t6CdmA7uDx+REsCpuLZinYdwiracp7akR/N9H802NwGpte9JbT/+Samawau7NOaSnze0se/LdO1LlMJ0xraGV1oB+a36b/9ZlrCMBXz1LK6TZ/f5Uwnjb/p3QX8Hu3g82ima2Uey3RyUbT1f2X/fEfgnrQE8h59epfR1rUz+nCPpSWbU+vu4IYwtIPKl1Vrb7lbVV3Uv7t+YLibGNOzTgD6AfBpVfV64CW0s+UwHePN3DLem2nxPo/22x/cy9cVTCfl6+Mk2nqwrjbfdaseVafT1s8fAx9K8oKZw/QD17vTan2g/S9n0ppa7llVe1TViwe+m8vMZTC4fAb/v5lxFu2M2BXAA2nlfbCM3+p3zdORtJqU+9Ou1Rlc9tcOfJ7rNwU4pqavzbpXVR2+thmuZV0Z/A1z/Z7B/tfOMQxV9VVgWZJH0WoT1nqzgDl8CtgvyYNo27Cf085c71etbfd/csvlNfVfjrUsbibeDryYtv2cy+C6MFiuBvep/ziwbv5eVb1vY4JK8rtM15rDHOtgVf0Y+GmSB9COpQa37c8ciGlwez7X+rwP8M1+guFJwBuS/AVwSU+gZhq8XvLQqrqBOcp5teut/oS2fv93knvPsT0M7UB6arqD2zuYfd3fkG3Gr6cS/TEt6/luu+cq4x+gtQg4iHbS4sa1TG+dxllTcCDwwaq6e1Utq3bB6A9pB/5/PnAxxgtoB6VfBv6sDzd1MeYetAO4XWk7q6nagdAufJ0qwFvQDrqW0A7Ad+rD/CHtbOcS2oHWDrQzy/el1RZUH+8e/fPPuOXBaJhuOjR1tv76/jseSNug39Dj/cv++Q59Pj+gJQHb9fhupJ1t+D2mD+SXJNmHViiX9HEv6/Oduuhn6iwYtNqJolVr06dxG9oB/T36eD+hJUjV5zuV3JzTx9lh4PdN1bpMXUi8Je3AYMqWtGs+iukLgotWbXcT7QwsPfYAH6dVp8J0AbmZ6bPsN/Xp7NW/24rpBOIL/bes7vPdhpYIXcd0odqv/5ap9eOutCYRUwf4N9Oa5FxHO3D/xUB8v+q//Wba8gztv/wd2n+0lLasp+6q8KA+zalaEJj+H2838Nv/oMdzx75stmK6BufRtJqmm3v/O9P+j9v15XNIH/b2wN/RmlTdhtZGfip5uawviy1pZzvSf8e5tMTzyh73kv679qYlBo+ilYX/7nFuB+zSL5z/L9r6fyZAkqn/Y9FIcq8kg2fg9qQ1Z5qPbWk1JL9J8hg2vLbj/cAbq+r8tQzzVabP/D5vqmeSu/cY/p12Vu1BgyMleTDtYPDgqppKWv+btn3YJsmfJrlDkt9P8hDatuY5SZYkWUrbwZ65nr/nWUluk+SetJMh36Etq1U9huczXbP2BeCPp+4ykmRqu3E107Vyc9mW6QuzV6xluK/QzsKR5HFM1yaeChyYZKepefflOat1rCvPGXj/ev/8NW75n31ljknP9ls/SEsSN6SWYKpW4zTauvVRWtm+Fvhlkp1pzbY0BP0s7rG0xGDKfNeFKZ+nlYutoZ1xn1pPN0Qvy/9GO7ieTxL+Mdq1PtsObJc+Dxzab1Iw3+35ecBjktylJwYvp9WO/8faR7uFWct5kntW1flV9U+0E1T3nmN7+N/APkl+r493h6z7LmsbvM0Y47I+HXha/313BJ5O2wfPS7UbulxOO0Y4er7jzWWcZxYOol2cNuh42gHrpcB5SX5DO3g6lLZhfF+Sv6XtrO5KO5B6De1A7AymD6YL+PuB6T6MdkAf2oHRDbQDvu1ozWoeSDugnGqSs4LpM8t/B7ysT/f3aAdmd6YdhF1H20k+l+kEa1tam/sLaDvWqUJ0uz7/Xfq0p9qE34XpZk5h+j85lnaB3OlMN6NZOhDXdn3Y29IOOEO7yORXtOqr1zCdZb6alvnvQjsovI62s5k6w30VrZpz6vffnekmNkuYPlsPbWc6VVtyLO3OJzcNLJ+bmU5ABpMyaP/5ln2Y7WnJw1V93KX9u+v7b5pqD3gt7aD4Gb17hx7Ttn24X/Zp34vpA/bbM30Nw1R7/q16TFvR/v/79OlcT/tvljJ9wLMH08nlAweW9zZMX6PwOKavgdii/wdX9WFuy3Si8kBu2cRoG1qS8PtMr4e/oSVre/T+1Yfbh+nkb0fa/3gD8Nb+nt5/qvnWXWgbv8f25ffuPs0/6PH/grZeXt7jvYh2VuZK2gHkjrT1m959St+4XUJrkraYbA0c2atMb6TVzBzC/OL8CPDpJCtpydO3NySAqrqMVou3Ni8F/iPJS7llFfWjgVf1bdw1tJMfg15CW9e/1PcvK6vqT3rtwdtobc3fSTuLfz5tG7U17f8r4G+q6idZx62eZ/gO7eTLzrR2xL9Oux3m8UmexXRzN6rqc0n2BFYmuYHWhOpv6Rcsp90u92HAHZJcNjCPt9FOWnwiyY9pO/57zBHPG4CPJnlOj2sVcHVVXZnk74Av9DtyTZ10mSspXNu6crskZ9DK0EF9+L8C3p/kVbSTBy+61RSbTwPHJTmA1r75v2jr1v9h4+4Y9FFaE4LnVtW3k5xDa8L6A1qSqeF5K63sTZnvugBAVX0hyX2Ar/dyew3tLO7qtY03w1RTnC1p6+uHaOVmPo6jbZPeNNDvTbRakPPmuz3v691rac1/fkPbzjwXOCLJN6rqu/OI5XBmL+cv6ydjbqKdlP1sn/YttodVtaZv7z6aZOrk29/Rjtnmsr7bjK0AkkzdeGUcy/obSY5m+iTOe6vqnMy4Ff06fIR2XcG31mOcWflE4wWS5JW0jPH/W5/v1jK9qWYmv6ZdHP0L2q07X7oe0ziQdtHa8+c7zuamn8k8n3bmYXfa7T//cO1jLS5pz544Z2OroWeZ7tZVdU3feL0LuLiq/mUh56FNQ98pnVxVx407lin9QOCmqrox7bai7+nNvRZq+pfQLoq+cl3Drsc0J36bK43LsLcZi9VCHiPYBnEBJDmB1oZ73/X5bh0OpzWx+h3a2bn/pt22ar4xHUmran7ies53s5HksbRq+LfRLlD+3ww04dgUJDmb9v+/YgiT/9MkK2g1G+fQbtMmLRa7Acf2M3s30C6wX7Tc5kpjt0ltMxbCQh8jWFMgSZIkTbhx35JUkiRJ0piZFEiSJEkTzqRAkiRJmnAmBZuRJJXkQwPdWyRZk+TktY23gfNamuSMJOckWa+7+STZM4kX40mLXJI7Jzm3v36S5McD3bdd9xQkbQqSPL0fQ9y7d98lyax3I0uyLMl1fTvwzSRfS3Kv0UasYTAp2LxcC9wvyVa9e3+mHx6y0PajPVl1r35/7vWxJ+t5h44061xf5zucpHWrqp9OPZ2T9mCffxl4WucN6xhd0qbjINrDv54L7aFYVXXgzIEy/WDZ7/ftwAOBY2jPKdEmzoOnzc9naU9AhlbIf/sQnSR794z+nMHMPskLk3wyyeeSXJzknwfGuWbg84FJju4PLfpn4In9TMFWSd6TZGWSC5O8YWCch/R5fTPJmUm2Bd5Ie/rquUmek+Tw/iyHqXEu6GciliW5KO0BSt8A7pbkVUnOSnLe1HxmG26hF6okoD1Y6YdJtgRIsk2SS5JsmeS0JG/v5f2CJHv3Ye6Y5P293J6T9rAvSYtEfy7SPrSnOT+391uW5IL++YVJPpHk07Snmc+0De2p6lPj/VeSb/TXw3v/2yR5dz9GODnJZ9Ke60GSI5J8q+/X3zL8X6y5+JyCzc/HgNf1JkMPoN2nf6p5z7eBR/YHezwW+Afgmf27PYG9aE/Y/U6SI6vqR7PNoKrOTfI62oN/XgKQ5LVV9bMkS4BTkzygz+/jwHOq6qwk29CeoDxz3MPX8nvuBbyoqv4i7bHlu9OeyhzgpCSPpD0d+rfDrdfSkrQ+rgNOo514+BTtAOL4qvpN2hNc71hVD+/l8v3A/YDXAl+sqj9Oe6rwmUn+X1VdO4b4Jd3a04DPVdV3k/wsyYOAn80Y5mHAA/p+fhlwz7QnL98JuAPwB3241cD+/Ynou9NOTC4HngEsA+4P7ARcRHta9A7A04F7V1X1bYTGxJqCzUxVnUcreAcBn5nx9ba0x45fAPwLcN+B706tql9W1a9pjx6/+3rO+tlJvkF7CNZ9gT1oB+qrquqsHttVVXXjek73f6rqv/vnx/XXObQagXvTkoSZw0kanvcCL+qfXwR8YOC7jwJU1enANn0H/zjgsH4AcRpwe9pDhiQtDgfRTijS3w+aZZhTqmowUZhqPnRP4GXAUb3/lsC/Jzkf+ATtWADgEcAnqurmqvoJ8KXe/yrg18B7kzyDduJQY2JNwebpJOAtwKOBOw/0fxPwpap6es/0Txv47vqBzzcxvW4MPt3u9rPNLMk9gFcCD6mqnyc5ug+bGePP5UZumaAOzmfwbGKAf6yqWzx5t/8WzzpKI1BVX+1NBB4FLKmqCwa/njk4rdw+s6q+M7IgJc1LkjsD+9KuRyxgCa3cvnvGoGvbx57E9MmBlwNXAA+k7dd/PTWr2UbsLRf2pl2n+FzgJT0ejYE1BZun9wNvrKrzZ/TflukLj184z2ldkeQ+/eLdp88xzDa0DcYvk+wMPKH3/zZwlyQPAUhyp36R0tW0KscplwAP6sM8CLjHHPP5PPDHvf0jSe6aZKd5/g5JC+eDtFqBD8zo/xyAJI8AfllVv6SV20PT2xcl2WuUgUpaqwOBD1bV3atqWVXdDfghsOt6TOMRwPf7521pLQRuBp5PSzKgXcT8zH5twc60k5ZT1zNsW1WfodU47LlxP0cbw5qCzVBVXQa8Y5av/hk4JslfA1+c5+QOA04GfgRcAGw9y/y+meQc4ELgB8BXe/8bkjwHODLtjkjXAY+lVRtONSf4R+B44AW9+yzgu3P8ri8kuQ/w9X58cQ1wMK1mQ9LofAT4PwzcyKD7eZKv0U4U/HHv9ybg7cB5PTG4BHjyaMKUtA4HAUfM6Hc8676b0NQ1BQFuAP6k9383cHySZ9H29VM1DMfTagMuoO3jzwB+STtBeGKSqdYFL9+YH6ONk6r5tO6QJKnpdw05oKqeP9DvNOCVVbVybIFJWrSSbF1V1/QmS2cC+/TrC7RIWFMgSZq3JEfSmgj6AEJJ6+PkfvOB2wJvMiFYfKwpkCRJkibcJlFTsOOOO9ayZcvGHYa02Tj77LOvrKql445jPiz/0sKy/EuTa23lf5NICpYtW8bKlTZTlRZKkv8ZwTwuod1p6ibgxqpa3h9U83HaszQuAZ5dVT9f23Qs/9LCGkX5XyiWf2lhra38e0tSScP0mP6Am+W9+zDag/J2B07t3ZIkacxMCiSN0gHAMf3zMcDTxheKJEmaYlIgaVgK+EKSs5Mc0vvtXFWrAPq7D5+TJGkR2CSuKZC0Sdqnqi7vT50+Jcm35ztiTyIOAdhtt92GFZ8kSeqsKZA0FFV1eX9fDZwA7A1ckWQXgP6+eo5xj6qq5VW1fOnSTeImKZIGJNkuyXFJvp3koiQPS7JDklOSXNzftx93nJKmmRRIWnBJ7pjkTlOfgcfRHm9/ErCiD7YCOHE8EUoasncAn6uqewMPBC7CGw1Ii9om33zowa/64LhDGLqz3/yCcYcgra+dgROSQNvO/EdVfS7JWcCxSV4MXAo8a30nPOoyb/mT1k+SbYBHAi8EqKobgBuSHAA8ug92DHAa8OqFmu8kHA+Mmtu/ybLJJwWSFp+q+gHt7ODM/j8F9ht9RJJG6HeBNcAHkjwQOBt4KTNuNNCvN5K0SNh8SJIkLaQtgAcB76mqvYBrWY+mQkkOSbIyyco1a9YMK0ZJM5gUSJKkhXQZcFlVndG7j6MlCd5oQFrETAokSdKCqaqfAD9Kcq/eaz/gW3ijAWlR85oCSZK00A4FPpLktsAPgBfRTkRu1I0GJA2PSYEkSVpQVXUusHyWr7zRgLRI2XxIkiRJmnAmBZIkSdKEMymQJEmSJpxJgSRJkjThTAokSZKkCTfUpCDJdkmOS/LtJBcleViSHZKckuTi/r79MGOQJEmStHbDril4B/C5qro38EDgItqjzk+tqt2BU1mPR59LkiRJWnhDSwqSbAM8EngfQFXdUFW/AA4AjumDHQM8bVgxSJIkSVq3YdYU/C6wBvhAknOSvDfJHYGdq2oVQH/faYgxSJIkSVqHYSYFWwAPAt5TVXsB17IeTYWSHJJkZZKVa9asGVaMkiRJ0sQbZlJwGXBZVZ3Ru4+jJQlXJNkFoL+vnm3kqjqqqpZX1fKlS5cOMUxJkiRpsg0tKaiqnwA/SnKv3ms/4FvAScCK3m8FcOKwYpAkSZK0blsMefqHAh9JclvgB8CLaInIsUleDFwKPGvIMUiSJElai6EmBVV1LrB8lq/2G+Z8JUmSJM2fTzSWJEmSJpxJgSRJkjThhn1NgSRJmjBJLgGuBm4Cbqyq5Ul2AD4OLAMuAZ5dVT8fV4ySbsmaAklDk2RJf3jhyb17hySnJLm4v28/7hglDc1jqmrPqpq6tvAw4NSq2h04lfV4dpGk4TMpkDRMLwUuGuj2oECaXAcAx/TPxwBPG18okmYyKZA0FEl2BZ4EvHegtwcF0mQo4AtJzk5ySO+3c1WtAujvO40tOkm34jUFkobl7cDfAHca6HeLg4IkHhRIm6d9quryXsZPSfLt+Y7Yk4hDAHbbbbdhxSdpBmsKJC24JE8GVlfV2Rs4/iFJViZZuWbNmgWOTtKwVdXl/X01cAKwN3BFkl0A+vvqOcY9qqqWV9XypUuXjipkaeKZFEgahn2Ap/Y7kHwM2DfJh/GgQNrsJbljkjtNfQYeB1wAnASs6IOtAE4cT4SSZmNSIGnBVdVrqmrXqloGPBf4YlUdjAcF0iTYGfhKkm8CZwL/WVWfA44A9k9yMbB/75a0SHhNgaRROgI4NsmLgUuBZ405HkkLrKp+ADxwlv4/BfYbfUSS5sOkQNJQVdVpwGn9swcFkiQtQjYfkiRJkiacSYEkSZI04UwKJEmSpAlnUiBJkiRNOJMCSZIkacKZFEiSJEkTzqRAkiRJmnAmBZIkSdKEMymQJEmSJpxJgSRJkjThTAokSZKkCWdSIEmSJE04kwJJkiRpwpkUSJIkSRPOpECSJEmacCYFkiRpwSVZkuScJCf37h2SnJLk4v6+/bhjlDTNpECSJA3DS4GLBroPA06tqt2BU3u3pEXCpECSJC2oJLsCTwLeO9D7AOCY/vkY4GkjDkvSWpgUSJKkhfZ24G+Amwf67VxVqwD6+05jiEvSHEwKJEnSgknyZGB1VZ29geMfkmRlkpVr1qxZ4OgkzcWkQJIkLaR9gKcmuQT4GLBvkg8DVyTZBaC/r55t5Ko6qqqWV9XypUuXjipmaeKZFEiSpAVTVa+pql2rahnwXOCLVXUwcBKwog+2AjhxTCFKmoVJgaQFl+T2Sc5M8s0kFyZ5Q+/vLQmlyXUEsH+Si4H9e7ekRWKLcQcgabN0PbBvVV2TZEvgK0k+CzyDdkvCI5IcRrsl4avHGejGuPSN9x/5PHd73fkjn6e0oarqNOC0/vmnwH7jjEfS3IZeU+DDS6TJU801vXPL/iq8JaEkSYvSKJoP+fASaQL1EwLn0i4mPKWqzsBbEkqStCgNNSnw4SXS5Kqqm6pqT2BXYO8k95vvuN6SUJKk0ZpXUpDk1Pn0m8Xb8eEl0iZtI8o/AFX1C1qb4sfjLQmlTcrGln9Jm461JgX9DiI7ADsm2b5fD7BDkmXAXdYxrg8vkTZhG1n+lybZrn/eCngs8G28JaG0SdiY8i9p07Suuw/9GfAy2gbgbCC9/1XAu9Yx7tTDS54I3B7YZvDhJVW1al1nCoGjAJYvX17z+C2SFtbGlP9dgGOSLKGdfDi2qk5O8nXg2CQvBi4FnjWMwCVttI0p/5I2QWtNCqrqHcA7khxaVUeuz4Sr6jXAawCSPBp4ZVUdnOTNtDOER+CZQmnR2sjyfx6w1yz9vSWhtAnYmPIvadM0r+cUVNWRSR4OLBscp6o+uAHzPALPFEqbjAUu/5I2IZZ/aXLMKylI8iHgnsC5wE29dwHz2ij48BJp07Wx5V/SpsvyL02O+T7ReDmwR1XZtl+aPJZ/aXJZ/qUJMd/nFFwA/M4wA5G0aFn+pcll+ZcmxHxrCnYEvpXkTOD6qZ5V9dShRCVpMbH8S5PL8i9NiPkmBYcPMwhJi9rh4w5A0tgcPu4AJI3GfO8+9OVhByJpcbL8S5PL8i9Njvnefehq2t0GAG4LbAlcW1XbDCswSYuD5V+aXJZ/aXLMt6bgToPdSZ4G7D2MgCQtLpZ/aXJZ/rXQLn3j/ccdwmZpt9edv9HTmO/dh26hqj4F7LvRc5e0ybH8S5NrPuU/ye2TnJnkm0kuTPKG3n+HJKckubi/bz+KmCXNz3ybDz1joPM2tPsWe89iaQJY/qXJtYHl/3pg36q6JsmWwFeSfBZ4BnBqVR2R5DDgMODVw4hb0vqb792HnjLw+UbgEuCABY9G0mJk+Zcm13qX//6gs2t655b9VX28R/f+xwCnYVIgLRrzvabgRcMORNLiZPmXJteGlv8kS4Czgd8D3lVVZyTZuapW9emuSrLTAoYqaSPN65qCJLsmOSHJ6iRXJDk+ya7DDk7S+Fn+pcm1oeW/qm6qqj2BXYG9k9xvPeZ5SJKVSVauWbNmI6KXtD7me6HxB4CTgLsAdwU+3ftJ2vxZ/qXJtVHlv6p+QWsm9HjgiiS7APT31XOMc1RVLa+q5UuXLt2o4CXN33yTgqVV9YGqurG/jgYsqdJksPxLk2u9y3+SpUm265+3Ah4LfJuWXKzog60AThxa1JLW23yTgiuTHJxkSX8dDPx0mIFJWjQs/9Lk2pDyvwvwpSTnAWcBp1TVycARwP5JLgb2792SFon53n3oj4F3Av9Cu4PA1wAvPpQmg+VfmlzrXf6r6jxgr1n6/xTYbwgxSloA800K3gSsqKqfQ3sACfAW2sZC0ubN8i9NLsu/NCHm23zoAVMbBICq+hmznAWQtFmy/EuTy/IvTYj5JgW3GXwceT9TMN9aBkmbNsu/NLks/9KEmG/BfivwtSTH0doUPhv4+6FFJWkxsfxLk8vyL02I+T7R+INJVgL7AgGeUVXfGmpkkhaFDSn/Se4GfBD4HeBm4Kiqekc/y/hxYBlwCfDswaYJkhYX9//S5Jh3FWDfCLghkCbQBpT/G4FXVNU3ktwJODvJKcALgVOr6ogkhwGHAa9e8IAlLRj3/9JkmO81BZI0b1W1qqq+0T9fDVxEexrqAcAxfbBjgKeNJUBJknQLJgWShirJMtrdSs4Adq6qVdASB2CnMYYmSZI6kwJJQ5Nka+B44GVVddV6jHdIkpVJVq5Zs2Z4AUqSJMCkQNKQJNmSlhB8pKo+2XtfkWSX/v0uwOrZxq2qo6pqeVUtX7p06WgCliRpgpkUSFpwSQK8D7ioqt428NVJwIr+eQVw4qhjkyRJt+YDSCQNwz7A84Hzk5zb+/0tcARwbJIXA5cCzxpPeJIkaZBJgaQFV1Vfod3TfDb7jTIWSZK0bjYfkiRJkiacSYEkSZI04UwKJEmSpAlnUiBJkhZMkrsl+VKSi5JcmOSlvf8OSU5JcnF/337csUqaZlIgSZIW0o3AK6rqPsBDgb9MsgdwGHBqVe0OnNq7JS0SJgWSJGnBVNWqqvpG/3w1cBFwV+AA4Jg+2DHA08YSoKRZmRRIkqShSLIM2As4A9i5qlZBSxyAncYYmqQZhpYU2KZQkqTJlWRr4HjgZVV11XqMd0iSlUlWrlmzZngBSrqFYdYU2KZQkqQJlGRLWkLwkar6ZO99RZJd+ve7AKtnG7eqjqqq5VW1fOnSpaMJWNLwkgLbFEqSNHmSBHgfcFFVvW3gq5OAFf3zCuDEUccmaW5bjGIma2tTmMQ2hZIkbT72AZ4PnJ/k3N7vb4EjgGOTvBi4FHjWeMKTNJuhJwUz2xS2EwjzGu8Q4BCA3XbbbXgBSpKkBVNVXwHm2tnvN8pYJM3fUO8+ZJtCSZIkafEb5t2HbFMoSZIkbQKG2XzINoWSJEnSJmBoSYFtCiVJkqRNg080liRJkiacSYEkSZI04UwKJEmSpAlnUiBJkiRNOJMCSZIkacIN/YnGGp9L33j/cYcwdLu97vxxhyBJkrTJs6ZA0oJL8v4kq5NcMNBvhySnJLm4v28/zhglSdI0kwJJw3A08PgZ/Q4DTq2q3YFTe7ckSVoETAokLbiqOh342YzeBwDH9M/HAE8bZUySJGluJgWSRmXnqloF0N93GnM8kiSpMymQtOgkOSTJyiQr16xZM+5wJEna7JkUSBqVK5LsAtDfV881YFUdVVXLq2r50qVLRxagJEmTyqRA0qicBKzon1cAJ44xFklD4t3HpE2TSYGkBZfko8DXgXsluSzJi4EjgP2TXAzs37slbX6OxruPSZscH14macFV1UFzfLXfSAORNHJVdXqSZTN6HwA8un8+BjgNePXoopK0LtYUSJKkYfPuY9IiZ1IgSZIWDe8+Jo2HSYEkSRo27z4mLXJeU6CJtM+R+4w7hKH76qFfHXcIkjRl6u5jR+Ddx6RFyaRAkjYTo052TTw1m373sUcDOya5DHg9LRk4tt+J7FLgWeOLUNJsTAokSdKC8e5j0qbJawokSZKkCWdSIEmSJE04kwJJkiRpwpkUSJIkSRPOpECSJEmacCYFkiRJ0oQzKZAkSZImnEmBJEmSNOFMCiRJkqQJZ1IgSZIkTTiTAkmSJGnCbTHuACRJm58vP/JRI5/no07/8sjnKUmbC2sKJEmSpAlnUiBJkiRNOJsPSZI0Qn9/8IEjn+drP3zcyOcpadNiTYEkSZI04caSFCR5fJLvJPleksPGEYOk8bD8S5PL8i8tXiNvPpRkCfAuYH/gMuCsJCdV1bdGHYuk0bL8a1ze+YpPj3R+L3nrU0Y6v02B5V9a3MZRU7A38L2q+kFV3QB8DDhgDHFIGj3LvzS5LP/SIjaOpOCuwI8Gui/r/SRt/iz/0uSy/EuL2DjuPpRZ+tWtBkoOAQ7pndck+c5Qo1o/OwJXjmpmecuKUc1qIYx02fD62VanRWu0681frXXZ3H1UccwwzvK/Qct/SOVvw9eF4azzG7Zs1r6ObagNXzZZPPEc+rYhRNJsUDx/95FbLJtJLP+LyWj3kxthEzv+GIZN5r9aj33DnOV/HEnBZcDdBrp3BS6fOVBVHQUcNaqg1keSlVW1fNxxLEYum7m5bIAxlv/FtPwXUyywuOJZTLGA8SywTX7/vxA28f9wokzafzWO5kNnAbsnuUeS2wLPBU4aQxySRs/yL00uy7+0iI28pqCqbkzyEuDzwBLg/VV14ajjkDR6ln9pcln+pcVtLE80rqrPAJ8Zx7wXyGZbrbkAXDZzc9kw1vK/mJb/YooFFlc8iykWMJ4FtRns/xfCJv0fTpiJ+q9SdatrfCRJkiRNkLE80ViSJEnS4mFSACS5Kcm5A69lCzDNlyW5wwKEN3YDy+eCJJ9Ost24Y1pMkixJck6Sk5M8MMm5A98dlORXSbbs3fdPcl7/fFqS7yQ5L8m3k7zTZTscg//RIohluyTH9f/8oiQPG2MsL09yYS/bH01y+zHGcvskZyb5Zo/pDWOIYVmS/zXq+c5HkkuSnN+3xSvHHY/mluYrSZ4w0O/ZST43zrg0tySV5K0D3a9McvgYQxoLk4Lmuqrac+B1ydQXvXBvyHJ6GbBZJAVML5/7AT8D/nJjJ5hkLNezDMlLgYv65/OBuye5U+9+OPBtYK+B7q8OjPu8qnoA8ADgeuDE4Yc7kQb/o3F7B/C5qro38EDGFFeSuwJ/BSzvZXsJ7W4w43I9sG9VPRDYE3h8kocOY0Zr2a4vA9YrKUiyZEGCmp/H9G3xxNwicVNUrV32nwNv68nuHYG/ZwH2nRqa64FnJNlx3IGMk0nBLPrZoouSvBv4BnC3JG/uZ9POT/KcPtyj+9neqbN+H+k7m78C7gJ8KcmXxvlbhuDr9CdQJrlnks8lOTvJfyW5d+//lCRn9DOz/y/Jzr3/4UmOSvIF4IPj+wkLJ8muwJOA9wJU1c202+79QR/kwcC7aMkA/f1rM6dTVTcAfwPsluSBQw57osz8j8YcyzbAI4H3Qfvfq+oXYwxpC2CrnqTfgVnuGT8q1VzTO7fsrwW76G2W7fr7Zm7TgSOAP+xn41/ex/mvJN/or4f3aT06yZeS/AdwfpI3JXnpwLz+vu8HNKGq6gLg08CrgdcDHwZem+Ssvm88ACDJfXsN2bm91nj3MYY9yW6kXVT88plfJLl7klP7/3Nqkt1GH95omBQ0W2W66dAJvd+9gA9W1V7ActqZqwcCjwXenGSXPtxetFqBPYDfBfapqn+l7VwfU1WPGd3PGK5+Rmw/pu8rfRRwaFU9GHgl8O7e/yvAQ/uy+xjtYHfKg4EDqmpRVtFvgLfTft/NA/2+Bjy8nx26GTiNWyYFgzUFv1VVNwHfBO49pFgn1du59X80Lr8LrAE+0A8M3tvXk5Grqh8DbwEuBVYBv6yqL4wjlilpzbzOBVYDp1TVGQs8i3vRTkj8H9qDs2Zu0w8D/qufjf+XHsf+VfUg4DnAvw5Ma2/gtVW1By3JW9F/w21oNS4fWeDYC/hCPwlzyDqH1mLwBlrN0xOA2wNfrKqHAI+hrXN3pNUovKOq9qQda1w2pljVTuA9L8m2M/q/k3Y8+ABauf7XW425mTApaAabDz299/ufqvrv/vkRwEer6qaqugL4MvCQ/t2ZVXVZP0N8Lq36eXOzVd9R/xTYATglyda0A9xP9O/+LzCVKO0KfD7J+cCrgPsOTOukqrpuVIEPU5InA6ur6uwZX32Vtmz2Bs6qqu8Dv5dkKbB1Vf1gbZMdTrSTaS3/0bhsATwIeE9Pmq+lHYiOXJLtgQOAe9BqNu+Y5OBxxDKlb2P3pG1D9k5yvwWexdR2fW3b9EFbAv/et2WfoJ38mXJmVf2wx30J8NMkewGPA86pqp8ucOz79OTkCcBfJnnkAk9fC6yqrgU+DnwI2B84rO8vT6MlCbvRat//NsmrgbtvLvvHTVFVXUU7aTCzlu9hwH/0zx+ibT82SyYFc7t24PPaDtSuH/h8E2N69sOQXdd31HcHbktrF3kb4BczrsW4Tx/+SOCdVXV/4M9oG78pg8t1U7cP8NQkl9BqRPZN8mHgv2kHGI+gbfChnf15LrM0HZrSa2Luz+Jp+745mOs/GpfLgMsGzoAfR0sSxuGxwA+rak1V/Qb4JNM1WmPVm1SdBjx+gSc9tf2Zb/L9cuAKWo3Cctr2b+a0prwXeCHwIuD9Gx7i7Krq8v6+GjiBdtJBi9/N/RXgmQP7y92q6qKq+g/gqcB1tJNp+44zWPF24MXA2mpwN9t7+ZsUzM/pwHN61fZSWpvgM9cxztXAndYxzCalqn5Jy6BfSduA/TDJs+C3F+5NtYXfFvhx/7xi5IGOSFW9pqp2rapltAP+L1bVwVV1NfAj2gHCVFLwdVozs1mTgrS7E/0j8KOqOm/IoU+Muf6jMcbzE+BHSe7Ve+0HfGtM4VwKPDTJHZKkxzK2hDTJ0vS7byXZipa0fHtIs5trmz5zu70tsKrXBD+fdjH2XE6gJTEPoT2xd8EkuWP6zQt6k5PHARcs5Dw0dJ8HDu1ljV6rRJLfBX7Qmx2fRLvphMakqn4GHEtLDKZ8jembMDyP1kR6s2RSMD8nAOfR2nt/EfibvnNfm6OAz25uFxpX1Tm05fBcWuF4cZJvAhfSmiIAHE5rVvRfwJXjiHMR+Cpwu6r6Ue/+Oq09+cyk4CNptyi9gHZm4gC0uTuU6f99T+AfxhFEr604jnbR7fm0/cE4n965C+3mDOfRLtY/paqGdQvZubbp5wE3pt0W9eW066RWJPlv4PdZS01nv1nAl4Bj+/VBC2ln4Ct9W3sm8J9V5e0tNy1vojVHOy/JBb0b2rUqF/RmRfdmM7kJxyburcDgXYj+CnhR3zY9n3Y3u82STzSWJGkj9QuMvwE8q6ouHnc8krS+rCmQJGkjJNkD+B5wqgmBpE2VNQWSJEnShLOmQJIkSZpwJgWSJEnShDMpkCRJkiacScEESXJTknOTXNhvuffX/Y4Zsw17lyTHbcA8/qjP49wk1yT5Tv88r9usJfnzJC9Y3/lKmr8kv5PkY0m+n+RbST6T5PfnGPbRSU7un5+aZL2ewJzk6CQHLkTckiBJJfnQQPcWSdZMldMFmP4Lk9xlIaY1aoPHEG571t/m+PRdzW3qycQk2Yn22O5tgdcPDpRki/70zPUuTFX1efqDe5KcBryyqlbOmP6Sue7jXVX/tr7zlDR//eFJJwDHVNVze789affC/+7axq2qk2gPWBpmfFtU1Y3DnIe0ibsWuF+SrarqOmB/ph8YuhBeSHt2zuUzv1jb/nsx8Bhi41hTMKGqajVwCPCS/jTiFyb5RJJPA19Isqw/YIUkZyS579S4SU5L8uD+lM33JzkryTlJ5nzwVpJLkrwuyVeAZyX50z7eN5Mcn+QOfbjDk7xyYD7/lOTMJN9N8ofDXCbShHgM8JvBnWdVnQscMliGk3wkyVMHR+zbiXf2z0cn+dckX0vyg6kzcn178s5eA/GfwE4D4z84yZeTnJ3k80l26f1PS/IPSb4MvDTJs5Jc0LcPpw9xWUibqs8CT+qfDwI+OvVFkr17uTynv9+r939hkk8m+VySi5P888yJ9nK8nPaAxXOTbLUe+++5tgm7JDm9T++C2fbls00zybZ93rfpw9whyY+SbDmfYwitP5OCCVZVP6CtA1M77YcBK6pq3xmDfgx4NrTCDdylqs4GXgt8saoeQjvQeHOSO65llr+uqkdU1ceAT1bVQ6rqgcBF3PKR4oO2qKq9gZcxo0ZD0ga5H3D2LP3fC7wIIMm2wMOBz6xjWrsAjwCeDBzR+z0duBdwf+BP+3RIsiVwJHBgVT0YeD/w9wPT2q6qHlVVbwVeB/xR3z7cIjGRBLT98nOT3B54AHDGwHffBh5ZVXvRytLgU9P3pD1F+f7Ac5LcbXCiVXUcsBJ4XlXt2WsiYP7779m2Cf8L+HxvqfBA4NxZfs+tpllVv6Q9dfxRfZin9On8Zh0xaAPZfEgZ+HxKVf1slmGOBU6hHZQ/G/hE7/844KkDWfntgd1oBXQ2Hx/4fL8k/wfYDtia3uRoFp/s72cDy+b8FZI2SlV9Ocm70poWPgM4vqpuTLK20T5VVTcD30qyc+/3SOCjvYnB5Um+2Pvfi5aQnNKnuQRYNTCtwe3DV4GjkxzL9DZAUldV5yVZRqslmJm8bwsck2R3oIAtB747tR9sk+RbwN2BH81jlvPdf8+2TTgLeH8/MfCpXjM501zT/DgtifkS8Fzg3fOIQRvImoIJluR3gZuA1b3XtbMNV1U/Bn6a5AG0wvmxqUkAz+xnE/asqt2qaq6EYOb0jwZeUlX3B95ASyhmc31/vwmTWGkhXAg8eI7vPgQ8j1Zj8IF5TOv6gc+D2cNsT8UMcOHA9uL+VfW4ge9/u32oqj8H/g64G3BukjvPIxZp0pwEvIWBpkPdm4AvVdX9aGfXB/evg2V2ffar891/32qbUFWn004W/Bj4UGa/mchc0zwJeEKSHWjbrS+uY3htBJOCCZVkKfBvwDtrfo+1/hjwN8C2VXV+7/d54ND0035J9lqPEO4ErOpnDp63HuNJ2jhfBG6X5E+neiR5SJJH0Xa0LwOoqgs3cPqn05o1LOnNDR/T+38HWJrkYX2eW2bgWqVBSe5ZVWdU1euAK2nJgaRbej/wxoF98pRtmb7w+IUbMN2rafvouazX/jvJ3YHVVfXvwPuAB813mlV1DXAm8A7g5IGLnD2GGAKTgsmyVb/Q50Lg/wFfoGXY83Ecreru2IF+b6JVS56XdlHym9Yjlv+P1gbyFFr7R0kj0E8CPB3YP+2WpBcChwOXV9UVtOZ/86klmMsJwMXA+cB7gC/3+d5Au6PZPyX5Jq1d8cPnmMabk5zftyun09oVSxpQVZdV1Ttm+eqfgX9M8lVaM711SvLeJMt759HAv01daDzL4Ou7/340rcbvHOCZtAP8mfNc2zQ/DhzMLZsweQwxBJnfSeINnHhyCS3jvAm4saqW9yqgj9Pah18CPLuqfj60ICRJ89Lv4HE+8KCpdseSpMkwipqCx/T2o1PZ4GG0C112B07t3ZKkMUryWNoZtyNNCCRp8oyipmB5VV050O87wKOralVvb3paVd1raEFIkiRJWqthJwU/BH5OuxPF/62qo5L8oqq2Gxjm51W1/dqms+OOO9ayZcuGFqc0ac4+++wrq2rpuOOQJEmLw7Bv8bhPVV3e73t9SpJ5XwyS5BDaE3fZbbfdWLly5bBilCZOkv8ZdwySJGnxGOo1BVV1eX9fTbsjxd7AFZl+tP0uTN8jf+a4R1XV8qpavnSpJzQlSZKkYRlaUpDkjknuNPWZ9vTbC2gPoljRB1sBnDisGCRJkiSt2zCbD+0MnNCfa7UF8B9V9bkkZwHHJnkxcCnwrCHGIEmSJGkdhpYUVNUPgAfO0v+nwH7Dmq8kSZKk9eMTjSVJkqQJZ1IgSZIkTbhh35JUmtWlb7z/uEPYLO32uvPHHYIkSdoEWVMgSZIkTTiTAkmSJGnCmRRIkiRJE86kQJIkSZpwJgWSJEnShDMpkCRJkiacSYEkSZI04UwKJEmSpAm32T287MGv+uC4Q9jsnP3mF4w7BEmSJA2RNQWSJEnShDMpkCRJkiacSYEkSZI04UwKJEmSpAlnUiBJkiRNOJMCSZIkacKZFEiSJEkTzqRAkiRJmnAmBZIkSdKEMymQJEmSJpxJgSRJkjThhp4UJFmS5JwkJ/fuHZKckuTi/r79sGOQJEmSNLdR1BS8FLhooPsw4NSq2h04tXdLkiRJGpOhJgVJdgWeBLx3oPcBwDH98zHA04YZgyRJkqS1G3ZNwduBvwFuHui3c1WtAujvOw05BkmSJElrMbSkIMmTgdVVdfYGjn9IkpVJVq5Zs2aBo5MkSZI0ZZg1BfsAT01yCfAxYN8kHwauSLILQH9fPdvIVXVUVS2vquVLly4dYpiSJEnSZBtaUlBVr6mqXatqGfBc4ItVdTBwErCiD7YCOHFYMUiSJElat3E8p+AIYP8kFwP7925JkiRJY7LFKGZSVacBp/XPPwX2G8V8JUmSJK2bTzSWJEmSJpxJgSRJkjThTAokSZKkCWdSIEmSJE04kwJJkiRpwpkUSJIkSRPOpECSJEmacCYFkiRJ0oQzKZAkSZImnEmBJEmSNOFMCiRJkqQJZ1IgSZIkTTiTAkmSJGnCmRRIkiRJE86kQJIkSZpwJgWSJEnShDMpkCRJkiacSYEkSZI04UwKJEmSpAlnUiBJkiRNOJMCSZIkacKZFEiSJEkTzqRAkiRJmnBDSwqS3D7JmUm+meTCJG/o/XdIckqSi/v79sOKQZIkSdK6DbOm4Hpg36p6ILAn8PgkDwUOA06tqt2BU3u3JEmSpDEZWlJQzTW9c8v+KuAA4Jje/xjgacOKQZIkSdK6DfWagiRLkpwLrAZOqaozgJ2rahVAf99pmDFIkiRJWruhJgVVdVNV7QnsCuyd5H7zHTfJIUlWJlm5Zs2aocUoSZIkTbqR3H2oqn4BnAY8HrgiyS4A/X31HOMcVVXLq2r50qVLRxGmJEmSNJGGefehpUm265+3Ah4LfBs4CVjRB1sBnDisGCRJkiSt27ySgiSnzqffDLsAX0pyHnAW7ZqCk4EjgP2TXAzs37slSZIkjckWa/syye2BOwA79ucJpH+1DXCXtY1bVecBe83S/6fAfhsUrSRJkqQFt9akAPgz4GW0BOBsppOCq4B3DS8sSZIkSaOy1qSgqt4BvCPJoVV15IhikiRJkjRC66opAKCqjkzycGDZ4DhV9cEhxSVJkiRpROaVFCT5EHBP4Fzgpt67AJMCSZIkaRM3r6QAWA7sUVU1zGAkSZIkjd58n1NwAfA7wwxEkiRJ0njMt6ZgR+BbSc4Erp/qWVVPHUpUkiRJkkZmvknB4cMMQpIkSdL4zPfuQ18ediCSJEmSxmO+dx+6mna3IYDbAlsC11bVNsMKTJIkSdJozLem4E6D3UmeBuw9jIAkSZIkjdZ87z50C1X1KWDfhQ1FkiRJ0jjMt/nQMwY6b0N7boHPLJAkSZI2A/O9+9BTBj7fCFwCHLDg0UiSJEkaufleU/CiYQciSZIkaTzmdU1Bkl2TnJBkdZIrkhyfZNdhBydJkiRp+OZ7ofEHgJOAuwB3BT7d+0mSJEnaxM03KVhaVR+oqhv762hg6RDjkiRJkjQi800KrkxycJIl/XUw8NNhBiZJkiRpNOabFPwx8GzgJ8Aq4EDAi48lSZKkzcB8b0n6JmBFVf0cIMkOwFtoyYIkSZKkTdh8awoeMJUQAFTVz4C9hhOSJEmSpFGab1JwmyTbT3X0moK11jIkuVuSLyW5KMmFSV46NW6SU5Jc3N+3X9t0JEmSJA3XfJOCtwJfS/KmJG8Evgb88zrGuRF4RVXdB3go8JdJ9gAOA06tqt2BU3u3JEmSpDGZ7xONP5hkJbAvEOAZVfWtdYyzinZRMlV1dZKLaM84OAB4dB/sGOA04NUbErwkSZKkjTffC43pScBaE4G5JFlGuwbhDGDnnjBQVauS7LQh05QkSZK0MObbfGiDJdkaOB54WVVdtR7jHZJkZZKVa9asGV6AkiRJ0oQbalKQZEtaQvCRqvpk731Fkl3697sAq2cbt6qOqqrlVbV86VIfnixJkiQNy9CSgiQB3gdcVFVvG/jqJGBF/7wCOHFYMUiSJElat3lfU7AB9gGeD5yf5Nze72+BI4Bjk7wYuBR41hBjkCRJkrQOQ0sKquortDsVzWa/Yc1XkiRJ0voZ+oXGkiRJkhY3kwJJkiRpwpkUSJIkSRPOpECSJEmacCYFkiRJ0oQzKZAkSZImnEmBJEmSNOFMCiRJkqQJZ1IgSZIkTTiTAkmSJGnCmRRIkiRJE86kQJIkSZpwJgWSJEnShDMpkCRJkiacSYEkSZI04UwKJEmSpAlnUiBJkiRNOJMCSZIkacKZFEiSJEkTzqRAkiRJmnAmBZIkSdKEMymQJEmSJpxJgSRJkjThhpYUJHl/ktVJLhjot0OSU5Jc3N+3H9b8JUmSJM3PMGsKjgYeP6PfYcCpVbU7cGrvliRJkjRGQ0sKqup04Gczeh8AHNM/HwM8bVjzlyRJkjQ/o76mYOeqWgXQ33ca8fwlSZIkzbBoLzROckiSlUlWrlmzZtzhSJIkSZutUScFVyTZBaC/r55rwKo6qqqWV9XypUuXjixASZIkadKMOik4CVjRP68AThzx/CVJkiTNMMxbkn4U+DpwrySXJXkxcASwf5KLgf17tyRJkqQx2mJYE66qg+b4ar9hzVOSJEnS+lu0FxpLkiRJGg2TAkmSJGnCmRRIkiRJE86kQJIkSZpwJgWSJEnShDMpkCRJkiacSYEkSZI04UwKJEmSpAlnUiBJkiRNOJMCSZIkacKZFEiSJEkTzqRAkiRJmnAmBZIkSdKEMymQJEmSJpxJgSRJkjThTAokSZKkCWdSIEmSJE04kwJJkiRpwpkUSJIkSRPOpECSJEmacCYFkiRJ0oQzKZAkSZImnEmBJEmSNOHGkhQkeXyS7yT5XpLDxhGDJEmSpGbkSUGSJcC7gCcAewAHJdlj1HFIkiRJasZRU7A38L2q+kFV3QB8DDhgDHFIkiRJYjxJwV2BHw10X9b7SZIkSRqDLcYwz8zSr241UHIIcEjvvCbJd4Ya1ejtCFw57iDmI29ZMe4Qxm2T+a94/WzFa1Z3H2YYkiRp0zKOpOAy4G4D3bsCl88cqKqOAo4aVVCjlmRlVS0fdxxaN/8rSZK0uRtH86GzgN2T3CPJbYHnAieNIQ5JkiRJjKGmoKpuTPIS4PPAEuD9VXXhqOOQJEmS1Iyj+RBV9RngM+OY9yKy2TaN2gz5X0mSpM1aqm51ja8kSZKkCTKWJxpLkiRJWjxMCsYsyWlJlg90L0tyQf98hyQfSXJ+kguSfCXJ1gPD7pWkkvzROGLfHAwu74F+hyd5ZZKHJjkjyblJLkpy+Izh3pHkx0ksR5IkaZM2lmsKNG8vBa6oqvsDJLkX8JuB7w8CvtLfPz/68DZ7xwDPrqpvJlkC3Gvqi54IPJ32IL5HAqeNJUJJkqQF4BnOeepnlC9K8u9JLkzyhSRbJdkzyX8nOS/JCUm278OfluSfkpyZ5LtJ/nADZrsL8OOpjqr6TlVd36cf4EDghcDjktx+43+lZtgJWAVQVTdV1bcGvnsMcAHwHlpSJkmStMkyKVg/uwPvqqr7Ar8Angl8EHh1VT0AOB94/cDwW1TV3sDLZvSfr/cDr07y9ST/J8nuA9/tA/ywqr5PO0v9xA2YvtbuX4Dv9GTvz2YkXgcBHwVOAJ6cZMuxRChJkrQATArWzw+r6tz++WzgnsB2VfXl3u8YWlOSKZ8cGHbZHNOc7fZPBdDn9bvAm4EdgLOS3KcPcxDwsf75Y3i2ekPNdfutqqo3AsuBLwD/C/gcQH/o3hOBT1XVVcAZwONGEKskSdJQeE3B+rl+4PNNwHbzHP4m+rJO8gFgL+Dyqnoi8FNg+4FxdgCunOqoqmtoycUnk9wMPDHJd2m1FE9N8logwJ2T3Kmqrt7A3zapZi5/aP/BDwF6Tcx7kvw7sCbJnWm1NNsC57dWXNwB+BXwn6MKWpIkaSFZU7Bxfgn8fOB6gecDX17L8FTVi6pqz54QQGv6c3C/RgBgBfAlgCT7DFyjcFtgD+B/gMcC36yqu1XVsqq6O3A88LQF+2UToiddq5LsB5BkB+DxwFeSPGngf9mdltz9glYr8yd92S8D7kG7ruMOo45fkiRpIZgUbLwVwJuTnAfsCbxxPcc/Crga+GaSbwJbA2/p390T+HKS84FzgJW0g/+DaG3ZBx1Pa+Ki9fcC4O+SnAt8EXhDryF4Pu2agnOBDwHPA24H/BEDtQJVdS3tLlBPGW3YkiRJC8MnGkuSJEkTzpoCSZIkacKZFEiSJEkTzqRAkiRJmnAmBZIkSdKEMymQJEmSJpxJgWaVZNckJya5OMn3k7yjPyth5nB3SXLcPKb3mSTbDSVYSZIkbRRvSapb6Q/sOgN4T1V9IMkS2vMUflZVrxoYbouqunFccUqSJGlhbDHuALQo7Qv8uqo+AFBVNyV5OfDDJD8EHgPcHrhjkj8GTq6q+/Un+h4N3Bu4CFgG/GVVrUxyCbCc9nC2z9Ie9vVw4MfAAVV13Qh/nyRJkgbYfEizuS9w9mCPqroKuJSWSD4MWFFV+84Y7y+An1fVA4A3AQ+eY/q7A++qqvsCvwCeuXChS5IkaX2ZFGg2AWZrVzbV/5Sq+tks3z8C+BhAVV0AnDfH9H9YVef2z2fTahQkSZI0JiYFms2FtKY+v5VkG+BuwE3AtXOMl3lO//qBzzdhMzZJkqSxMinQbE4F7pDkBQD9QuO30q4X+NVaxvsK8Ow+zh7A/YcbpiRJkhaCSYFupdotqZ4OPCvJxcB3gV8Df7uOUd8NLE1yHvBqWvOhXw4zVkmSJG08b0mqBdNrFLasql8nuSetxuH3q+qGMYcmSZKktbAttxbSHYAvJdmSdn3B/zYhkCRJWvysKZAkSZImnNcUSJIkSRPOpECSJEmacCYFkiRJ0oQzKZAkSZImnEmBJEmSNOFMCiRJkqQJ9/8DqoroVrm45zAAAAAASUVORK5CYII=
"
>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h1 id="Bivariate-Analysis">Bivariate Analysis<a class="anchor-link" href="#Bivariate-Analysis">&#182;</a></h1>
</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h1 id="1.-(X-cat,Y-con)">1. (X-cat,Y-con)<a class="anchor-link" href="#1.-(X-cat,Y-con)">&#182;</a></h1>
</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h1 id="Box-plot">Box plot<a class="anchor-link" href="#Box-plot">&#182;</a></h1>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[39]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">sb</span><span class="o">.</span><span class="n">boxplot</span><span class="p">(</span><span class="n">A</span><span class="o">.</span><span class="n">Type</span><span class="p">,</span><span class="n">A</span><span class="o">.</span><span class="n">Width</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[39]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>&lt;AxesSubplot:xlabel=&#39;Type&#39;, ylabel=&#39;Width&#39;&gt;</pre>
</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[40]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">A</span><span class="o">.</span><span class="n">Type</span><span class="o">.</span><span class="n">unique</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[40]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>array([&#39;Small&#39;, &#39;Midsize&#39;, &#39;Compact&#39;, &#39;Large&#39;, &#39;Sporty&#39;, &#39;Van&#39;],
      dtype=object)</pre>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[41]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="n">A</span><span class="o">.</span><span class="n">Type</span><span class="o">.</span><span class="n">unique</span><span class="p">():</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Results of category&quot;</span><span class="p">,</span><span class="n">i</span><span class="p">)</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">A</span><span class="p">[</span><span class="n">A</span><span class="o">.</span><span class="n">Type</span><span class="o">==</span><span class="n">i</span><span class="p">][[</span><span class="s2">&quot;Width&quot;</span><span class="p">]]</span><span class="o">.</span><span class="n">describe</span><span class="p">()[</span><span class="mi">3</span><span class="p">:</span><span class="mi">9</span><span class="p">])</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;-------------------------------</span><span class="se">\n\n</span><span class="s2">&quot;</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>Results of category Small
     Width
min   60.0
25%   63.0
50%   66.0
75%   67.0
max   68.0
-------------------------------


Results of category Midsize
     Width
min  69.00
25%  69.00
50%  70.00
75%  71.75
max  74.00
-------------------------------


Results of category Compact
     Width
min   66.0
25%   67.0
50%   67.0
75%   68.0
max   69.0
-------------------------------


Results of category Large
     Width
min   69.0
25%   74.0
50%   74.0
75%   77.0
max   78.0
-------------------------------


Results of category Sporty
     Width
min   64.0
25%   67.0
50%   69.0
75%   71.5
max   75.0
-------------------------------


Results of category Van
     Width
min   71.0
25%   72.0
50%   72.0
75%   74.0
max   78.0
-------------------------------


</pre>
</div>
</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h1 id="2.-(X-cat,Y-cat)">2. (X-cat,Y-cat)<a class="anchor-link" href="#2.-(X-cat,Y-cat)">&#182;</a></h1>
</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h1 id="Countplot-with-hue">Countplot with hue<a class="anchor-link" href="#Countplot-with-hue">&#182;</a></h1>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[43]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">cat</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[43]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>[&#39;Manufacturer&#39;,
 &#39;Type&#39;,
 &#39;AirBags&#39;,
 &#39;DriveTrain&#39;,
 &#39;Cylinders&#39;,
 &#39;Man.trans.avail&#39;,
 &#39;Origin&#39;]</pre>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[45]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">sb</span><span class="o">.</span><span class="n">countplot</span><span class="p">(</span><span class="n">A</span><span class="o">.</span><span class="n">Type</span><span class="p">,</span><span class="n">hue</span><span class="o">=</span><span class="n">A</span><span class="p">[</span><span class="s2">&quot;AirBags&quot;</span><span class="p">])</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[45]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>&lt;AxesSubplot:xlabel=&#39;Type&#39;, ylabel=&#39;count&#39;&gt;</pre>
</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAX4AAAEGCAYAAABiq/5QAAAAOXRFWHRTb2Z0d2FyZQBNYXRwbG90bGliIHZlcnNpb24zLjMuNCwgaHR0cHM6Ly9tYXRwbG90bGliLm9yZy8QVMy6AAAACXBIWXMAAAsTAAALEwEAmpwYAAAjrElEQVR4nO3deXxV1bn/8c9DAMMgLUNAkYtBf2JBwBCCqCBFKTjhCLGgIoOKs1irLb76s0Kr3t7iQCveKiqDSoPKYJ16C6KoREQJRgSBom2wEa4MKmUQmZ77x96JISThEHLOSbK/79crr+yz9vTsc/Z5zjprr7O2uTsiIhIddZIdgIiIJJYSv4hIxCjxi4hEjBK/iEjEKPGLiERM3WQHEIsWLVp4enp6ssMQEalR8vLyNrl7WunyGpH409PTWbJkSbLDEBGpUcxsbVnlauoREYkYJX4RkYhR4hcRiZga0cYvIgfavXs3hYWF7Ny5M9mhSJKlpqbSpk0b6tWrF9PySvwiNVRhYSFHHnkk6enpmFmyw5EkcXc2b95MYWEh7dq1i2kdNfWI1FA7d+6kefPmSvoRZ2Y0b978kL75xS3xm9lkM9tgZstLld9iZqvNbIWZ/T5e+xeJAiV9gUM/D+JZ458KnFOywMzOBC4Curj7ScADcdy/iIiUIW6J393fBr4qVXwD8Dt3/y5cZkO89i8i1ducOXMwM1atWgXAunXrGDRoUJnLFhQU0KBBAzIyMjj55JM5/fTTWb16dSLDrVUSfXG3PXCGmd0H7ATucPcPylrQzEYBowDatm1b5sa63fl0pYLIG39VpdYTkaqTk5NDr169mDFjBmPHjqV169bMnDnzgOX27NkDwPHHH09+fj4Ajz/+OPfffz/Tpk1LZMi1RqIv7tYFmgKnAncCz1s5jVPuPsnds9w9Ky3tgKEmRKQG27ZtG7m5uTz11FPMmDEDCGr1nTp1AmDq1KlkZ2dzwQUX0L9//wPW//e//03Tpk2L1zvjjDPIzMwkMzOTd999F4B9+/Zx4403ctJJJzFgwADOO++84g+WMWPG0LFjR7p06cIdd9yRiEOuVhJd4y8EZntwv8f3zWwf0ALYmOA4RCSJXnzxRc455xzat29Ps2bNWLp0Kc2aNdtvmUWLFrFs2TKaNWtGQUEBn332GRkZGWzdupUdO3awePFiAFq2bMm8efNITU1lzZo1DBkyhCVLljB79mwKCgr4+OOP2bBhAx06dGDkyJF89dVXzJkzh1WrVmFmfPPNN0l4BpIr0TX+F4GzAMysPVAf2JTgGEQkyXJychg8eDAAgwcPJicn54Bl+vXrt9+HQVFTz2effcaECRMYNWoUEPyQ7dprr6Vz585kZ2fzySefALBw4UKys7OpU6cORx11FGeeeSYATZo0ITU1lWuuuYbZs2fTsGHDeB9utRO3Gr+Z5QB9gBZmVgjcA0wGJoddPHcBw1x3exeJlM2bN/PGG2+wfPlyzIy9e/diZtx44437LdeoUaNyt3HhhRcyYsQIAB5++GFatWrFRx99xL59+0hNTQWCHzaVpW7durz//vvMnz+fGTNmMHHiRN54440qOrqaIZ69eoa4+9HuXs/d27j7U+6+y92vdPdO7p7p7tF6tkWEmTNnctVVV7F27VoKCgr417/+Rbt27SgsLIx5GwsXLuT4448HYMuWLRx99NHUqVOHZ555hr179wLQq1cvZs2axb59+/jyyy9ZsGABEFxf2LJlC+eddx4TJkwovmAcJRqyQUQSKicnhzFjxuxXNnDgQO6///4K1ytq43d36tevz5NPPgnAjTfeyMCBA3nhhRc488wzi78pDBw4kPnz59OpUyfat29Pjx49+MEPfsDWrVu56KKL2LlzJ+7Oww8/HJ8DrcasJrS0ZGVleVk3YlF3TomylStX0qFDh2SHUa1t27aNxo0bs3nzZk455RRyc3M56qijkh1WXJR1PphZnrtnlV5WNX4RqbUGDBjAN998w65du7j77rtrbdI/VEr8IlJrFbXry/40OqeISMQo8YuIRIwSv4hIxCjxi4hEjC7uitQSle3eXJ5Yuj2bGbfffjsPPvggAA888ADbtm1j7NixVRqLVC3V+EWk0o444ghmz57Npk0acqsmUeIXkUqrW7cuo0aNKvPXr2vXrqVv37506dKFvn378vnnnwMwfPhwbr31Vk4//XSOO+64/cbgHz9+PN27d6dLly7cc889CTuOqFHiF5HDctNNNzF9+nS2bNmyX/nNN9/MVVddxbJly7jiiiu49dZbi+etX7+ehQsX8sorrxQP3zB37lzWrFnD+++/T35+Pnl5ebz99tsJPZaoUOIXkcPSpEkTrrrqKv74xz/uV75o0SIuv/xyAIYOHcrChQuL51188cXUqVOHjh078uWXXwJB4p87dy5du3YlMzOTVatWsWbNmsQdSITo4q6IHLbbbruNzMzM4qGSy1LyZntHHHFE8XTReGHuzl133cV1110Xv0AFUI1fRKpAs2bNuOyyy3jqqaeKy04//fTi2ypOnz6dXr16VbiNs88+m8mTJ7Nt2zYAvvjiCzZs2BC/oCNMNX6RWiLZo87+/Oc/Z+LEicWP//jHPzJy5EjGjx9PWloaU6ZMqXD9/v37s3LlSk477TQAGjduzLPPPkvLli3jGncUxfMOXJOBAcAGd+9Uat4dwHggzd3VD0ykhiqqnQO0atWKHTt2FD9OT08v885WU6dOLXcbo0ePZvTo0VUfqOwnnk09U4FzShea2X8A/YDP47hvEREpRzxvvfg28FUZsx4GfgFU/zvAiIjUQgm9uGtmFwJfuPtHidyviIh8L2EXd82sIfAroH+My48CRgG0bds2jpGJiERLImv8xwPtgI/MrABoAyw1szLvhebuk9w9y92z0tLSEhimiEjtlrAav7t/DBT3ywqTf5Z69YiIJFY8u3PmAH2AFmZWCNzj7k9VvJaIVNbnv+lcpdtr++uPK5yfkpJC586d2b17N3Xr1mXYsGHcdttt1KlzYEPCunXruPXWW/cbkK2qbNq0iezsbDZv3kxqaipvvPEGjRs3rjDmPXv20KFDB6ZNm0bDhg2rPKbqLp69eoa4+9HuXs/d25RO+u6ertq+SM3VoEED8vPzWbFiBfPmzeO1115j3LhxByy3Z88eWrduXSVJf8+ePQeU/elPf6J3794sW7aMF198kfr16x805uXLl1O/fn0ee+yxw44pGfbu3XtY62vIBhE5bC1btmTSpElMnDgRd2fq1KlkZ2dzwQUX0L9/fwoKCujUKfgdZ48ePVixYkXxun369CEvL4/t27czcuRIunfvTteuXfnLX/4CcMC2Sqtfvz6FhYUAtG7dusLEX9IZZ5zBp59+yssvv0yPHj3o2rUrP/nJT4oHjXvrrbfIyMggIyODrl27snXrVtavX0/v3r3JyMigU6dOvPPOO0AwwNxpp51GZmYm2dnZxT9KS09P55577iEzM5POnTuzatUqADZu3Ei/fv3IzMzkuuuu49hjjy2+p8Gzzz7LKaecQkZGBtddd11xkm/cuDG//vWv6dGjB4sWLTq0F6gUJX4RqRLHHXcc+/btKx5fZ9GiRUybNu2AX+8OHjyY559/HgiGZ163bh3dunXjvvvu46yzzuKDDz7gzTff5M4772T79u0Vbgvg+OOPZ9asWYdUe9+zZw9//etf6dy5M7169eK9997jww8/ZPDgwfz+978HgruJPfroo+Tn5/POO+/QoEED/vznP3P22WeTn5/PRx99REZGBps2beLee+/l9ddfZ+nSpWRlZfHQQw8V76tFixYsXbqUG264gQceeACAcePGcdZZZ7F06VIuueSS4nsVrFy5kueee47c3Fzy8/NJSUlh+vTpAGzfvp1OnTqxePHig457dDAaq0dEqkzRSJsA/fr1o1mzZgcsc9lll9GvXz/GjRvH888/T3Z2NhDUml966aXi5Lhz587ihFjetr744gvuu+8+Vq9ezfnnn09aWhoDBw6kS5cuLFy4kCZNmuy3/LfffktGRgYQ1PivvvpqVq9ezU9/+lPWr1/Prl27aNeuHQA9e/bk9ttv54orruDSSy+lTZs2dO/enZEjR7J7924uvvhiMjIyeOutt/jkk0/o2bMnALt27Soebwjg0ksvBaBbt27Mnj0bgIULFzJnzhwAzjnnHJo2bQrA/PnzycvLo3v37sXxFo1VlJKSwsCBA2N7IQ5CiV9EqsQ//vEPUlJSihNVo0aNylzumGOOoXnz5ixbtoznnnuOxx9/HAg+NGbNmsWJJ5643/KLFy8ud1u5ubmcfPLJtGrVildffZW+ffvy5Zdfkp6efkDSh+/b+Eu65ZZbuP3227nwwgtZsGBB8f2Cx4wZw/nnn89rr73Gqaeeyuuvv07v3r15++23efXVVxk6dCh33nknTZs2pV+/fuTk5JQZY9EQ1CkpKcXXKEp+QJbk7gwbNoz//M//PGBeamoqKSkpZa53qNTUIyKHbePGjVx//fXcfPPN+427X56iJpUtW7bQuXPQG+nss8/mkUceKU6KH3744UG306VLF958803WrVtHq1atePjhh7npppuKbwATiy1btnDMMccAMG3atOLyzz77jM6dO/PLX/6SrKwsVq1axdq1a2nZsiXXXnstV199NUuXLuXUU08lNzeXTz/9FIAdO3bw97//vcJ99urVq7i5a+7cuXz99dcA9O3bl5kzZxY3l3311VesXbs25mOJlWr8IrXEwbpfVrWiZpOi7pxDhw7l9ttvj2ndQYMGMXr0aO6+++7isrvvvpvb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
"
>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h1 id="2.-(X-con,Y-con)">2. (X-con,Y-con)<a class="anchor-link" href="#2.-(X-con,Y-con)">&#182;</a></h1>
</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h1 id="Scatter-plot">Scatter plot<a class="anchor-link" href="#Scatter-plot">&#182;</a></h1>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[46]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">con</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[46]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>[&#39;Min.Price&#39;,
 &#39;Price&#39;,
 &#39;Max.Price&#39;,
 &#39;MPG.city&#39;,
 &#39;MPG.highway&#39;,
 &#39;EngineSize&#39;,
 &#39;Horsepower&#39;,
 &#39;RPM&#39;,
 &#39;Rev.per.mile&#39;,
 &#39;Fuel.tank.capacity&#39;,
 &#39;Passengers&#39;,
 &#39;Length&#39;,
 &#39;Wheelbase&#39;,
 &#39;Width&#39;,
 &#39;Turn.circle&#39;,
 &#39;Rear.seat.room&#39;,
 &#39;Luggage.room&#39;,
 &#39;Weight&#39;]</pre>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[49]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">plt</span><span class="o">.</span><span class="n">scatter</span><span class="p">(</span><span class="n">A</span><span class="o">.</span><span class="n">Horsepower</span><span class="p">,</span><span class="n">A</span><span class="o">.</span><span class="n">Price</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">&quot;HP vs Price&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s2">&quot;Horsepower&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s2">&quot;Price&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span> 
</pre></div>

     </div>
</div>
</div>
</div>

</div>
</body>







</html>
