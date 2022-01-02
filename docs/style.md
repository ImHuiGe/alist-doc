---
sidebar_position: 9
---

# 示例样式
### 仿OLAINDEX样式（haah.net）
```css
.main-box {
  border-radius: 13px !important;
}
.header{
  background-color: #2C3E50 !important;
  color: #FFF !important;
  border-radius: 13px !important;
}
.header .buttons span:hover{
  color:#18BC9C !important;
}
.nav {
    background-color: #ecf0f1 !important;
    padding: 0.75rem 1rem !important;
    margin: 1rem 0 !important;
    border-radius: 13px !important;
   box-shadow:var(--chakra-shadows-lg) !important;
}
a,.nav li span{
    color:#18BC9C !important;
    text-decoration:none !important;
   background-color:transparent !important;
}
a:hover {
    color:#0f7864 !important;
    text-decoration:underline !important;
}
.main-box{
  margin-top: 0 !important;
}
.list-title {
    padding:0.75rem 1.25rem !important;
    margin-bottom:0 !important;
    background-color:rgba(0, 0, 0, 0.03) !important;
    border-bottom:1px solid rgba(0, 0, 0, 0.125) !important;
    border-radius: 13px 13px 0 0 !important;
}
.chakra-offset-slide .list-item:hover{
  background-color:#ecf0f1
}
.chakra-offset-slide:last-child{
  margin-bottom: 0.5rem !important;
}
.main-box .content-box{
   padding: 0 !important;
}
.main-box .content-box .list-box div[class~=chakra-offset-slide]{
   padding:0 var(--chakra-space-2) !important;
}
.chakra-icon{
  height:16px !important;
  width:16px !important;
  color:#18BC9C !important;
}
.chakra-ui-light .readme-box {
  background-color: white !important;
}
.readme-box {
  border-radius: 15px !important;
}
```
### 无边框阴影
```css
.chakra-ui-light{
  background-color: #edddfd;
}
.main-box {
  border-radius: 15px !important;
  box-shadow: unset !important;
}
.chakra-ui-light .main-box {
  background-color: rgba(255,255,255,0.9) !important;
}
.chakra-ui-light .readme-box {
  background-color: rgba(255,255,255,0.9) !important;
}
.readme-box {
  border-radius: 15px !important;
  box-shadow: unset !important;
}
```
### 仿大白样式
```css
.chakra-ui-light{
  background-image: linear-gradient(120deg,#e0c3fc 0%,#8ec5fc 100%) !important;
  background-attachment: fixed;
}
.main-box {
  border-radius: 15px !important;
}
.chakra-ui-light .main-box {
  background-color: white !important;
}
.chakra-ui-light .readme-box {
  background-color: white !important;
}
.readme-box {
  border-radius: 15px !important;
}
```
:::tip
如果你有好看的样式想要分享出来，可以点击下方的[Edit this page](https://github.com/Xhofe/alist-doc/edit/main/docs/style.md)发起pr将你的样式添加到本页面。
:::
