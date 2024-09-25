---
title: 测试页面
description: Markdown-it 渲染的测试页面
keywords: markdown-it, markdown, test
giscus: false
---

## 标题 1

### 标题 1.1

#### 标题 1.2

##### 标题 1.3

###### 标题 1.4

## 标题2

### **标题 2.2 加粗**

#### _标题 2.3 斜体_

##### **_标题 2.4 斜体加粗_**

###### 标题 2.5

这是一段普通的文本。

## 各个语言

### 简体中文

你好，我是简体中文

### 繁体中文

你好，我是繁體中文

### 英语

Hello, I am English

### 日语

こんにちは、私は日本語です

## 列表

- 无序列表项 1
- 无序列表项 2
  - 无序嵌套列表项 2.1
  - 无序嵌套列表项 2.2
- 无序列表项 3
- 无序列表项 4
  - 无序嵌套列表项 4.1
  - 无序嵌套列表项 4.2
    - 无序嵌套列表项 4.2.1

1. 有序列表项
2. 有序列表项
   1. 嵌套有序列表项
   2. 嵌套有序列表项
3. 有序列表项
4. 有序列表项
   1. 嵌套有序列表项
   2. 嵌套有序列表项
      1. 嵌套有序列表项 x2

## 文字样式

这是 _斜体文本_

这是 **粗体文本**

这是 **_斜体加粗文本_**

这是 ~~删除线~~

这是 <u>下划线</u>

上标：H~2~O

下标：X^2^

## 任务列表

- [x] 任务列表项 1
- [ ] 任务列表项 2
- [x] 任务列表项 3

## 链接和图片

### 超链接

[首页](/)

### [标题超链接](/)

### 链接结尾文件名'md' 转换到 'html'

[index.md 到 index.html](./index.md)

### 这是无大小限制的站点图标

![站点图标](/favicon.png '这是无大小限制的站点图标')

### 这是64x64大小限制的站点图标

![站点图标](/favicon.png '这是64x64大小限制的站点图标'){width=64 height=64}

## 引用

> 这是引用的文本。Markdown支持多层嵌套引用。
> 这是一级引用
>
> > 这是二级引用
> >
> > > 这是三级引用

## 代码块

### 行内代码

输出“Hello, Markdown!”：`console.log('Hello, Markdown!')`。

### JavaScript

```javascript
const text = 'Hello, Markdown!';
console.log(text);
```

### typescript

```typescript
const text: string = 'Hello, Markdown!';
console.log(text);
```

## 表格

| 姓名 | 年龄 | 职业     | 工龄 |
| ---- | ---- | -------- | ---- |
| 小明 | 25   | 前端设计 | 3年  |
| 小红 | 30   | 运维     | 5年  |

## Emoji

:smile:

## HTML

<details>
  <summary>点击展开</summary>
  <p>这是一个 HTML 标签</p>

```html
<details>
  <summary>点击展开</summary>
  <p>这是一个 HTML 标签</p>
</details>
```

</details>

## 公式

$$
\begin{aligned}
\dot{x} & = \sigma(y-x) \\
\dot{y} & = \rho x - y - xz \\
\dot{z} & = -\beta z + xy
\end{aligned}
$$

## 强调信息

### 笔记

> [!NOTE]
> 笔记内容

### 提示

> [!TIP]
> 提示内容

### 警告

> [!WARNING]
> 警告内容

### 危险

> [!DANGER]
> 危险内容

### 重要

> [!IMPORTANT]
> 重要内容

## 脚注

这是一个脚注的示例1[^1].

这是一个脚注的示例2[^2].

这是一个脚注的示例3[^3].

## 分割线

---

## 脚注内容

[^1]: 这是脚注的内容1。

[^2]: 这是脚注的内容2。

[^3]: 这是脚注的内容3。
