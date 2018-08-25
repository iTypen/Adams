# iTypen (based on Adams)

[toc]

##特殊页面制作

### 创建友情链接/链接库页面
示例：
```
<article class="post_article">
<ul class="links">
<li><a href="https://www.mocurio.com/" target="_blank" rel="external noopener">默趣 MoCurio</a>
<div class="bg" style="background-image: url('https://www.google.com/s2/favicons?domain=https://www.mocurio.com');"></div>
</li>
</ul>
</article>
```

### 支持其他MDUI框架内嵌的样式

放置在标签 ```<div class="elem">``` 内

例如：
```
<div class="elem>
<div class="mdui-card">
<div class="mdui-card-media">
<img src="https://mdui-aliyun.cdn.w3cbus.com/docs/assets/docs/img/card.jpg"/>
<div class="mdui-card-media-covered">
<div class="mdui-card-primary">
<div class="mdui-card-primary-title">Title</div>
<div class="mdui-card-primary-subtitle">Subtitle</div>
</div>
<div class="mdui-card-actions">
<button class="mdui-btn mdui-ripple mdui-ripple-white">action 1</button>
<button class="mdui-btn mdui-ripple mdui-ripple-white">action 2</button>
</div>
</div>
</div>
</div>
</div>
```
其余元素尚未测试 如有问题，烦请再issues中提出

### 阿里巴巴矢量图标库接入

在主题header.php文件中，修改注释有```阿里巴巴矢量图标库 Javascript 文件接入点```字样的```script```标签。
