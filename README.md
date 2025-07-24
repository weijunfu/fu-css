# fu-css

> 一个开源可扩展的CSS样式库

> An open-source and extensible CSS style library

## 一、基础样式

### 1.1 Layout

#### z-index
> `<number>`目前支持`1~6`

|class|style|
|--|--|
|z-index-`<number>`|z-index: `<number>`;|
|z-index-auto|z-index: auto;


##### 使用方式
```html
<div class="circle z-index-1"></div>
<div class="circle z-index-2"></div>
<div class="circle z-index-3"></div>
```

##### 扩展

```css
.z-index-10 { --z-value: 10; }
.z-index-20 { --z-value: 20; }
```