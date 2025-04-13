
# Markdown书写格式

![版本](https://img.shields.io/badge/version-1.0-blue)

> 项目作者：**XWF8188**  
> 本项目介绍 Markdown 的详细语法及其在 GitHub 项目 `README.md` 文件中的应用方法。

---

## 目录

- [1. 创建 README.md](#1-创建-readmemd)
- [2. Markdown 基础语法](#2-markdown-基础语法)
  - [2.1 标题](#21-标题)
  - [2.2 文本格式](#22-文本格式)
  - [2.3 列表](#23-列表)
  - [2.4 链接](#24-链接)
  - [2.5 图片](#25-图片)
  - [2.6 代码块](#26-代码块)
  - [2.7 表格](#27-表格)
- [3. 高级功能](#3-高级功能)
  - [3.1 任务列表](#31-任务列表)
  - [3.2 引用块](#32-引用块)
  - [3.3 目录链接](#33-目录链接)
- [4. GitHub 美化功能](#4-github-美化功能)
- [5. 示例 README 模板](#5-示例-readme-模板)
- [6. 总结](#6-总结)

---

## 1. 创建 README.md

在项目根目录创建文件：

```bash
touch README.md
git add README.md
git commit -m "Add README.md"
git push origin main
```

---

## 2. Markdown 基础语法

### 2.1 标题

```md
# 一级标题
## 二级标题
### 三级标题
```

### 2.2 文本格式

```md
**加粗**
*斜体*
~~删除线~~
`行内代码`
```

### 2.3 列表

```md
- 无序项 1
  - 子项
- 无序项 2

1. 有序项一
2. 有序项二
```

### 2.4 链接

```md
[GitHub](https://github.com)
```

### 2.5 图片

```md
![示例图片](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```

### 2.6 代码块

<pre>
```python
print("Hello, World!")
```
</pre>

### 2.7 表格

```md
| 姓名 | 年龄 | 性别 |
|------|------|------|
| 张三 | 25   | 男   |
| 李四 | 30   | 女   |
```

---

## 3. 高级功能

### 3.1 任务列表

```md
- [x] 已完成
- [ ] 未完成
```

### 3.2 引用块

```md
> 这是引用文字
```

### 3.3 目录链接

```md
[跳转到使用方法](#使用方法)
```

---

## 4. GitHub 美化功能

- **徽章**：
```md
![Build](https://img.shields.io/badge/build-passing-brightgreen)
```

- **GIF 演示**：
```md
![演示](https://media.giphy.com/media/3o7abldj0b3rxrZUxW/giphy.gif)
```

---

## 5. 示例 README 模板

```md
# 项目名称

## 安装

```bash
git clone https://github.com/yourrepo.git
cd yourrepo
```

## 使用

```python
print("Hello Markdown")
```

## 许可证

MIT License
```

---

## 6. 总结

- `README.md` 是 GitHub 项目的门面
- 使用 Markdown 提升文档的清晰度与美观性
- 可嵌入图像、代码块、目录、徽章等组件
- 建议使用 VS Code + Markdown 插件增强体验

---

> 文档最后更新时间：2025 年 4 月 13 日  
> 作者：XWF8188
