[title]: 弹性盒子flex

# 弹性盒子flex

## flex常用记录

```css
display: -webkit-box;
display: -ms-flexbox;
display: -webkit-flex;
display: flex;

-webkit-box-align: center;
-webkit-align-items: center;
align-items: center;

-webkit-box-pack: justify;
-webkit-justify-content: space-between;
justify-content: space-between;

-webkit-box-orient: vertical;
-webkit-flex-direction: column;
flex-direction: column;

-webkit-line-clamp: 2;
-webkit-box-orient: vertical;
display: -webkit-box;

-webkit-box-flex: 1;
-webkit-flex: 1;
flex: 1;
```

## 定义为flex

```css
display: -webkit-box;
display: -ms-flexbox;
display: -webkit-flex;
display: flex;
```

## flex方向

默认横向水平方向
```css
-webkit-box-orient: horizontal;
-webkit-flex-direction: row;
flex-direction: row;
```

竖向垂直方向
```css
-webkit-box-orient: vertical;
-webkit-flex-direction: column;
flex-direction: column;
```

### flex横向水平方向

```css
-webkit-box-pack: justify;
-webkit-justify-content: space-between;
justify-content: space-between;
```

### flex竖向垂直方向

```css
-webkit-box-align: center;
-webkit-align-items: center;
align-items: center;
```

## flex显示省略号

```css
-webkit-line-clamp: 2;
-webkit-box-orient: vertical;
display: -webkit-box;
```

## flex为1

```css
-webkit-box-flex: 1;
-webkit-flex: 1;
flex: 1;
```
