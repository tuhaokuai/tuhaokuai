### tuhaokuai php通过composer安装

@官方网站(http://www.tuhaokuai.com)


#### 安装

`composer require tuhaokuai/tuhaokuai`


#### 在视图渲染处添加如下代码

```

    $tu = new tuhaokuai();
    $content = $tu->output($content);

```




