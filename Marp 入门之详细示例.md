---
marp: true
author: Jesse
theme: sysu
paginate: true
backgroundColor: 
backgroundImage: 
backgroundPosition:
backgroundRepeat: 
class: 
color: 
description: 
footer: 
header: 
headingDivider: 
image: 
keywords: 
math: 
size:
style: 
title:
url: 
---


# Marp 中山大学模板🎈🎃

###### 本文档是 Jesse 设计的 Marp-theme 的 **Demo 文件**;
###### 欢迎使用


---
# 使用教程
## Marp-VsCode 插件
在vscode上使用[Marp](https://marp.app/)
### 插件设置主题
在vscode setting中搜索`markdown.marp.themes`
点击添加值
`https://raw.githubusercontent.com/cherryamme/Marp-theme_SYSU/main/themes/sysu.css`

使用主题:   在front中设置  `theme: sysu`


---
# H1 一级标题默认居中
## H2  二级以下标题左对齐
### H3   &nbsp;&nbsp;&nbsp;&nbsp;  代码块: `Code`
#### H4  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;高亮:&nbsp;&nbsp;&nbsp;&nbsp;**Bold&Highlight**
##### H5  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;斜体:&nbsp;&nbsp;&nbsp;*kjdhf*
###### H6  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 链接: [cherryamme](https://cherryamme.com)

**加粗字体** 常规字体

---

## 代码框

  支持高亮,使用highlight.js vs2015主题
```css
<style scoped>
section h1 {text-align: center;font-size: 80px;color:black;}
section {
  background-image:url('./fm.png');
  background-size:cover
}
footer{color:black;font-size: 20px;} 
</style>
```

#### 引用

> 引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用引用



---

# 基本语法
Marp 的基本语法与 Markdown 类似:
- 使用`#` 作为级标题
- 使用`![]()`引用图片或链接
- `- 子弹列表`
- `1. 序列列表`
- ` > 引用`
- ` ```代码框 `

---

###### 页首参数

```yaml
---
marp: true                         # 使用 marp 引擎
theme: sysu                        # 设置SYSU主题
paginate: true                     # 设置右下角的页码
backgroundColor: (red)             # 设置 slide 背景颜色
backgroundImage:                   # 设置 slide 背景图片
backgroundPosition:                # 设置背景位置
backgroundRepeat:                  # 背景重复
class:                             
color:                             
description:                       
footer:  ![](markdown.png)         #可以使用图片
header:   '**bold** _italic_'      #可以加粗或斜体
headingDivider:                    #按几级标题分页
image:                  
keywords:                          #大部分标题不需要设置,建议只使用 marp: true 和 theme: sysu
math:                   
size:                   
style:                  
title:                  
url:                    
---
```

---
# 支持双栏
<div class="twocols">

## 第一栏
- 栏内支持列表
- item
<p class="break"></p>

## 第二栏
这是第二栏
</div>




```html
<div class="twocols">
## 第一栏
- 栏内支持列表
- item
<p class="break"></p>
## 第二栏
这是第二栏
</div>
```