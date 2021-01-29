# 遍历DOM
DOM 让我们可以对元素和它们中的内容做任何事，但是首先我们需要获取到对应的DOM对象。
对DOM的所有操作都是以 `document` 对象开始。它是DOM的主入口点。可以从它访问任何节点。

## 最顶层： documentElement和body
最顶层的树节点可以直接作为 `document` 的属性来使用:
`<body> = document.body`
`<head> = document.head`

## 子节点:childNodes,firstChild,lastChild