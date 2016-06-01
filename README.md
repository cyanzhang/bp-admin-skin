# 样式说明文档
---

[TOC]

## 1. 页头 

- `page-title`
 
示例：

```
<div class="page-title">
  <div class="title">
    <h1>一方通行</h1>
    <p class="subtitle">是个前所未有的萝莉控</p>
  </div>
</div>
```

## 2. 按钮

### 1. 按钮样式
 
 - `bp-btn-default` 默认样式（重置、取消...）
 - `bp-btn-primary` 确定、提交、查询...
 - `bp-btn-danger` 删除
 
示例：

```
<button type="button" class="btn bp-btn-default">（默认）default</button>
<button type="button" class="btn bp-btn-primary">（确定）primary</button>
<button type="button" class="btn bp-btn-danger">（删除）danger</button>
```

###2. 按钮置灰

 - `disabled` 
 
示例：

```
<button type="button" class="btn bp-btn-default" disabled>默认</button>
<button type="button" class="btn bp-btn-primary" disabled>确定</button>
<button type="button" class="btn bp-btn-danger" disabled>删除</button>  
```

### 3. 按钮尺寸

- `btn-lg` 大按钮
- `btn-sm` 小按钮
- `btn-xs` 超小按钮

示例：

```
<button type="button" class="btn bp-btn-primary btn-lg">（大按钮）Large button</button>
<button type="button" class="btn bp-btn-primary">（默认尺寸）Default button</button>
<button type="button" class="btn bp-btn-primary btn-sm">（小按钮）Small button</button>
<button type="button" class="btn bp-btn-primary btn-xs">（超小尺寸）Extra small button</button>
```

## 3. 无标题容器 

- `bp-container`

示例：

```
<div class="bp-container">
  <p>我是bp-container</p>
</div>
```

## 4. 有标题容器 

- `panel`

### 1. 标题背景色

- `bp-panel-primary` 标题背景色为**祖母绿**的容器
- `bp-panel-danger` 标题背景色为**红色**的容器

示例：

```
<div class="panel bp-panel-primary">
  <div class="panel-heading">
    <div class="panel-title">通常的Panel</div>
  </div>
  <div class="panel-body">123</div>
  <div class="panel-footer">
    <button type="button" class="btn bp-btn-default">（默认）default</button>
    <button type="button" class="btn bp-btn-primary">（确定）primary</button>
  </div>
</div>
```

### 2. 按钮位置

- 默认 局左
- `panel-footer-btn-right` 局右

示例：

```
<div class="panel bp-panel-danger">
  <div class="panel-heading">
    <div class="panel-title">危险的Panel</div>
  </div>
  <div class="panel-body">123</div>
  <div class="panel-footer panel-footer-btn-right">
    <button type="button" class="btn bp-btn-default">（默认）default</button>
    <button type="button" class="btn bp-btn-primary">（确定）primary</button>
  </div>
</div>
```

## 5. 表格

- `table` `table-condensed` `table-bordered` `table-striped` `table-hover`

示例：

```
<table class="table table-condensed table-bordered table-striped table-hover">
</table>
```

## 6. 表单

- `form-control` 边框色为**祖母绿**
- `required-star` 必填项提示**红***

示例：

```
<div class="form-group">
  <label class="control-label"><span class="required-star">*</span>龙破斩的咒文:</label>
  <input type="text" class="form-control" />
</div>
```

## 7. 弹窗

- `modal-dialog` 弹窗容器

示例：

```
<div class="modal-dialog">
  <div class="modal-content">
    <div class="modal-header">
      <h3 class="modal-title">Modal Title</h3>
    </div>
    <div class="modal-body">
      <div> This is a modal body </div>
    </div>
    <div class="modal-footer">
      <button type="button" class="btn bp-btn-default">（默认）default</button>
      <button type="button" class="btn bp-btn-primary">（确定）primary</button>
    </div>
  </div>
</div>
```