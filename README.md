# css3
css3多行文本溢出点点点
```css
  .goods-name{
      line-height:1.5em;
      height: 3em;
      overflow: hidden;
      text-overflow: ellipsis;
      display: -webkit-box;
      -webkit-line-clamp: 2;
      -webkit-box-orient: vertical;
  }
```
