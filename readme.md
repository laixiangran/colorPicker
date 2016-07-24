# 颜色选择器 colorPicker v1.2

## 简介

支持导出为jQuery插件，CMD模块，AMD模块，全局变量

## 使用

### 引入

```html
<link rel="stylesheet" href="../dist/css/colorPicker.css">
<script src="../dist/js/colorPicker.js"></script>
```

### 添加input

```html
<input type="text" name="user_color" id="user_color" placeholder="点击选择颜色">
```
    
### 初始化

```javascript
var colorPicker = new ColorPicker({
    textInput_id: "user_color"
});
```
