﻿# GitFromZeroToHero
:root {
  --gradient-dir1: to top right;
  --gradient-dir2: to bottom left;
  --gradient-dir3: to right top;
  --gradient-dir4: to left bottom;
  --gradient-dir5: to top left;
  --size: 5px;
}

.mtk10,
.mtk15 {
  color: transparent;
  background-image: linear-gradient(var(--gradient-dir4), #fc806c, #ff1bd1);
  -webkit-background-clip: text;
  background-clip: text;
  -webkit-text-fill-color: transparent;
}

.mtk5,
.mtk26 {
  color: transparent;
  background-image: linear-gradient(var(--gradient-dir1),
      #4dd78a,
      #20e3b2,
      #a2de6a);
  background-clip: text;
  -webkit-text-fill-color: transparent;
  -webkit-background-clip: text;
  -webkit-font-smoothing: auto;
  font-family: 'DM Mono', monospace;
  font-size: 18px;
}

.mtk26 {
  background-image: linear-gradient(var(--gradient-dir5),
      #4dd78a,
      #20e3b2,
      #a2de6a);
  font-style: italic;
}

.mtk23,
.mtk16 {
  color: transparent;
  background-image: linear-gradient(var(--gradient-dir1), #d66efd, #6a5af9);
  background-clip: text;
  -webkit-text-fill-color: transparent;
  -webkit-background-clip: text;
}

.mtk9,
.mtk17 {
  color: transparent;
  background-image: linear-gradient(var(--gradient-dir2),
      #098dff,
      #2cccff,
      #2979ff);
  background-clip: text;
  -webkit-text-fill-color: transparent;
  -webkit-background-clip: text;
}

.mtk18 {
  color: transparent;
  background-image: linear-gradient(var(--gradient-dir2), #b0beff, #fed9ff);
  background-clip: text;
  -webkit-text-fill-color: transparent;
  -webkit-background-clip: text;
  font-style: normal;
}

.mtk3 {
  color: transparent;
  /* background-image: linear-gradient(
    var(--gradient-dir1),
    #c29ffd,
    #ffb4dc,
    #e39bf7
  ); */
  background-image: linear-gradient(to top, #fce1d0, #ffadd6, #e39bf7);
  background-clip: text;
  -webkit-text-fill-color: transparent;
  -webkit-background-clip: text;
}

.mtk7 {
  color: transparent;
  background-image: linear-gradient(var(--gradient-dir2), #fc6c8f, #ffb86c);
  -webkit-background-clip: text;
  background-clip: text;
  -webkit-text-fill-color: transparent;
}

.mtk8,
.mtk14 {
  color: transparent;
  background-image: linear-gradient(to right, #ffb88c, #eac394);
  -webkit-background-clip: text;
  background-clip: text;
  -webkit-text-fill-color: transparent;
}

.monaco-workbench .activitybar>.content :not(.monaco-menu)>.monaco-action-bar .action-item.checked .active-item-indicator:before {
  border: 0;
  width: 3px;
  height: 100%;
  position: absolute;
  top: 0;
  left: 0;
  background-image: linear-gradient(45deg, #fc6c8f, #ff2ced);
}

.monaco-workbench .activitybar>.content :not(.monaco-menu)>.monaco-action-bar .badge .badge-content {
  background-image: linear-gradient(45deg, #fc6c8f, #ff2ced);
}

.monaco-editor .cursors-layer .cursor {
  background-image: linear-gradient(to top, #6a5af9, #d66efd, #fc6c8f, #ff2ced);
}

.mtki {
  font-style: normal;
}

.monaco-workbench .part.editor>.content .editor-group-container>.title .tabs-container>.tab.active.tab-border-top>.tab-border-top-container {
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  background-color: transparent;
}

.monaco-workbench .part.editor>.content .editor-group-container>.title .tabs-container>.tab.active.tab-border-top>.tab-border-top-container:before,
.monaco-workbench .part.editor>.content .editor-group-container>.title .tabs-container>.tab.active.tab-border-top>.tab-border-top-container:after {
  content: '';
  width: var(--size);
  height: var(--size);
  position: absolute;
  border: 2px solid;
  border-image-slice: 1;
}

.monaco-workbench .part.editor>.content .editor-group-container>.title .tabs-container>.tab.active.tab-border-top>.tab-border-top-container:before {
  top: 0;
  left: 0;
  border-right: 0;
  border-bottom: 0;
  /* border-image-source: linear-gradient(-45deg, #4dd78a, #20e3b2); */
  border-image-source: linear-gradient(-45deg, #4dd78a, #00b163);
}

.monaco-workbench .part.editor>.content .editor-group-container>.title .tabs-container>.tab.active.tab-border-top>.tab-border-top-container:after {
  right: 0;
  bottom: 0;
  border-top: 0;
  border-left: 0;
  /* border-image-source: linear-gradient(-45deg, #6a5af9, #d66efd); */
  border-image-source: linear-gradient(-45deg, #6d13bc, #d66efd);
}

.monaco-workbench .part.editor>.content .editor-group-container>.title .tabs-container>.tab.active:before,
.monaco-workbench .part.editor>.content .editor-group-container>.title .tabs-container>.tab.active:after {
  content: '';
  width: var(--size);
  height: var(--size);
  position: absolute;
  border: 2px solid;
  border-image-slice: 1;
}

.monaco-workbench .part.editor>.content .editor-group-container>.title .tabs-container>.tab.active:before {
  left: 0;
  bottom: 0;
  border-top: 0;
  border-right: 0;
  border-image-source: linear-gradient(-45deg, #fc6c8f, #ffb86c);
}

.monaco-workbench .part.editor>.content .editor-group-container>.title .tabs-container>.tab.active:after {
  top: 0;
  right: 0;
  border-left: 0;
  border-bottom: 0;
  border-image-source: linear-gradient(-45deg, #098dff, #2cccff);
}

.monaco-editor .line-numbers.active-line-number {
  color: #fc6c8f;
  text-shadow: 0 0 4px #d66efd, 0 0 10px #2cccff, 0 0 21px #fc6c8f, 0 0 42px #ffb86c,
    0 0 82px #d66efd, 0 0 92px #2cccff, 0 0 102px #fc6c8f, 0 0 151px #ffb86c;
}

/* a.action-label.codicon.codicon-accounts-view-bar-icon {
  background: url(https://b-f50-zpg-r.zdn.vn/4176572044103705997/61886281d53d16634f2c.jpg) no-repeat;
  background-size: cover;
  object-fit: cover;
  border-radius: 100rem;
  max-width: 42px;
  max-height: 42px;
  margin: 0 auto;
} */

/* a.action-label.codicon.codicon-accounts-view-bar-icon:hover {
  box-shadow: rgba(149, 157, 165, 0.2) 0px 8px 24px;
}

.codicon-accounts-view-bar-icon:before {
  content: "";
} */
