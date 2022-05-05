### 不倒翁圆环

```
//倒影效果
-webkit-box-reflect: below 1px linear-gradient(transparent, #0001) ;

//利用border的特性画月亮
    width:200px;
    height: 200px;
    border-radius: 50%;
    border-bottom: 20px solid #06c8f0;
    border-right: 20px solid #06c8f0;
```

### 炫彩登录页面

```
可以利用style属性定义变量
<div class="square" style="--i:0"></div
<div class="square" style="--i:1"></div>
<div class="square" style="--i:2"></div
<div class="square" style="--i:3"></div>
 <div class="square" style="--i:4"></div>
 
 .square{
 animation-delay: calc(-1s * var(--i));
 }
filter可以弄出很好看的过渡颜色
filter:blur(150px)
```

