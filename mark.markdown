---
layout: page
title: markdown教程
permalink: /markdown/
---
[markdown教程](https://www.runoob.com/markdown/md-tutorial.html)

    [链接名称](链接地址)

    # 一级标题
    ## 二级标题
    ### 三级标题
    #### 四级标题
    ##### 五级标题
    ###### 六级标题

    无序列表使用星号(*)、加号(+)或是减号(-)作为列表标记，这些标记后面要添加一个空格，然后再填写内容：
    - 第一项
    - 第二项
    - 第三项

    有序列表使用数字并加上 . 号来表示，如：
    1. 第一项
    2. 第二项
    3. 第三项

    超级链接：
    [markdown教程](https://www.runoob.com/markdown/md-tutorial.html)

    - |  表头   | 表头  |
    |  ----  | ----  |
    | 单元格  | 单元格 |
    | 单元格  | 单元格 |

    Markdown 区块引用是在段落开头使用 > 符号 ，然后后面紧跟一个空格符号：
    > 最外层
    > > 第一层嵌套
    > > > 第二层嵌套

    > 区块中使用列表
    > 1. 第一项
    > 2. 第二项
    > + 第一项
    > + 第二项
    > + 第三项

    列表中使用区块实例如下：
    * 第一项
        > 菜鸟教程
        > 学的不仅是技术更是梦想
    * 第二项

    代码区块使用 4 个空格或者一个制表符（Tab 键）。
    你也可以用 ``` 包裹一段代码，并指定一种语言（也可以不指定）：
    ```javascript
    $(document).ready(function () {
        alert('RUNOOB');
    });
    ```

    图片
    ![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png)

    Markdown是没有表头的哦，如果要用表头就用HTML咯。正常的Markdown render，都可以渲染HTML。
    <table><caption> 我是表头 </caption><th>112</th><tr><td>11222</td></tr></table>


- |  表头   | 表头  |
|  ----  | ----  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |

- 代码块示例
```javascript
$(document).ready(function () {
    alert('RUNOOB');
});
```