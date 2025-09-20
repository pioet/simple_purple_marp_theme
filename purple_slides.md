---
marp: true
theme: default
paginate: true
style: |
  section {
    background-color: #ffffff;
    color: #333333;
    font-family: 'Microsoft YaHei', '微软雅黑', sans-serif;
    padding: 60px 80px 40px 80px;
    justify-content: flex-start;
    align-items: flex-start;
    text-align: left;
    display: flex;
    flex-direction: column;
  }
  
  h1 {
    color: #6A1B9A;
    font-size: 2.5em;
    font-weight: bold;
    margin-bottom: 0.5em;
    margin-top: 0;
    text-align: left;
    border-bottom: 3px solid #6A1B9A;
    padding-bottom: 10px;
    font-family: 'Microsoft YaHei', '微软雅黑', sans-serif;
  }
  
  h2 {
    color: #6A1B9A;
    font-size: 1.8em;
    font-weight: bold;
    margin-top: 0;
    margin-bottom: 0.5em;
    font-family: 'Microsoft YaHei', '微软雅黑', sans-serif;
  }
  
  h3 {
    color: #6A1B9A;
    font-size: 1.4em;
    font-weight: bold;
    margin-top: 0.8em;
    margin-bottom: 0.4em;
    font-family: 'Microsoft YaHei', '微软雅黑', sans-serif;
  }
  
  p, li {
    font-size: 1.1em;
    line-height: 1.6;
    margin-bottom: 0.8em;
    text-align: justify;
    font-family: 'Microsoft YaHei', '微软雅黑', sans-serif;
  }
  
  ul, ol {
    margin-left: 0;
    margin-top: 0;
    padding-left: 1.2em; /* 只保留足够显示列表符号的空间 */
  }
  
  li {
    margin-bottom: 0.5em;
    font-family: 'Microsoft YaHei', '微软雅黑', sans-serif;
  }
  
  blockquote {
    border-left: 4px solid #6A1B9A;
    padding-left: 20px;
    margin: 1em 0;
    font-style: italic;
    background-color: #f8f4ff;
    padding: 15px 20px;
    font-family: 'Microsoft YaHei', '微软雅黑', sans-serif;
  }
  
  code {
    background-color: #f5f5f5;
    padding: 2px 6px;
    border-radius: 3px;
    font-family: 'Consolas', 'Monaco', 'Courier New', monospace;
  }
  
  pre {
    background-color: #f8f8f8;
    border: 1px solid #ddd;
    border-radius: 5px;
    padding: 15px;
    overflow-x: auto;
    margin: 1em 0;
  }
  
  pre code {
    font-family: 'Consolas', 'Monaco', 'Courier New', monospace;
  }
  
  table {
    border-collapse: collapse;
    width: 100%;
    margin: 1em 0;
    font-family: 'Microsoft YaHei', '微软雅黑', sans-serif;
  }
  
  th, td {
    border: 1px solid #ddd;
    padding: 12px;
    text-align: left;
    font-family: 'Microsoft YaHei', '微软雅黑', sans-serif;
  }
  
  th {
    background-color: #6A1B9A;
    color: white;
    font-weight: bold;
  }
  
  footer {
    color: #666;
    font-size: 0.8em;
    font-family: 'Microsoft YaHei', '微软雅黑', sans-serif;
  }
  
  strong {
    font-family: 'Microsoft YaHei', '微软雅黑', sans-serif;
    font-weight: bold;
  }
  
  em {
    font-family: 'Microsoft YaHei', '微软雅黑', sans-serif;
    font-style: italic;
  }
---

# Simple Purple Marp Theme 
#### Presenter: Pioet 
#### 2025-09-20

---

# Part 1
## 快速开始 

--- 

## 引言 

Marp 是一个高效的幻灯片制作工具，它将符合一定规则的Markdown文档渲染成PDF文档（幻灯片结构）。

基于 Markdown 的PPT制作让我们可以专注在内容上面，快速制作出符合基本美观需求的幻灯片。并且，Markdown 对LaTeX公式的支持可以让我们快速从LaTeX项目当中迁移过来。最后，markdown纯文本的格式更利于原始手稿的保留。

本项目旨在提供一个紫色简约主题风格的 Marp theme。 


---

## 如何使用 

1. 在 vscode 插件中心安装 `Marp for VS Code`
2. 基于该 md 文档进行修改  
3. 点击 1 可以实时显示 Slides,点击 2 选择 export 可以导出 PDF. 

![w:10cm](https://cy-1256894686.cos.ap-beijing.myqcloud.com/20201129171243.png)

---

# Part 2
## 图片处理 

--- 

## 左右排布

将图片放置在右侧。

![bg right h:3cm](https://raw.githubusercontent.com/marp-team/marp/master/marp.png)

---
## 中心分布

将图片放置在中间。

![bg center h:3cm](https://raw.githubusercontent.com/marp-team/marp/master/marp.png)

---

## 更多  

在Marp中，除了bg（背景）之外，图片语法还包含以下与bg并列的选项：

* fit - 图片适配到容器内，保持宽高比 
* contain - 图片完全包含在容器内，可能留有空白 
* cover - 图片覆盖整个容器，可能被裁剪 
* stretch - 图片拉伸填满容器，可能变形 

```md 
![bg fit](image.jpg)
![bg contain](image.jpg)
![bg cover](image.jpg)
![bg stretch](image.jpg)
![bg left](image.jpg)
![bg right split](image.jpg)
```

---

# 致谢 

本项目参考了

* [chenyang1999/Marp_theme_for_THUslides: 使用 Marp 制作清华大学组会 Slides模板](https://github.com/chenyang1999/Marp_theme_for_THUslides)

