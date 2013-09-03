UI::Breadcrumb
====================

## Markup

    <ol class="sd-breadcrumb">
        <li><a href="#">Top Level</a></li>
        <li><a href="#">Second Level</a></li>
        <li><a href="#">Third Level</a></li>
        <li class="sd-breadcrumb-active">Current Item</li>
    </ol>

## 纠结

考虑到IE,分隔符不能使用CSS来创建，那么要添加多一个<span class="sd-breadcrumb-sep"></span>标签真是无比的纠结啊。

    <span class="sd-breadcrumb-sep">&gt;</span>
    
    .sd-breadcrumb-sep { font-family: "SimSun"; }

## 参考：

+ http://css-tricks.com/markup-for-breadcrumbs/
+ http://getbootstrap.com/components/#breadcrumbs
