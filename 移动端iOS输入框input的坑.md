## 移动端iOS兼容问题

1)input无法输入的问题：
`-webkit-user-select:none;`改成`-webkit-user-select:auto;`

2）滚动不流畅（`overflow-y:auto`）
`-webkit-overflow-scrolling: touch;`
注：此属性和`overflow-y:auto`冲突
