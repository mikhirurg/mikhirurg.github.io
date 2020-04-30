---
layout: post
title:  "Остовное дерево"
date:   2020-04-30 14:30:00 +0300
categories: algo graphs
permalink: /:categories/:day/:year/:month/:title.html
---

## Задача:
Неориентированный граф задан списком рёбер. Найдите степени вершин графа.

## Решение:
<details><summry>Показать решение</summry>
Считываем ребра графа и наращиваем для вершин число инцидентных им рёбер.

{% highlight java %}
for (int i = 0; i < m; i++) {
	int u = in.nextInt() - 1;
	int v = in.nextInt() - 1;
	graph[u]++;
	graph[v]++;
}
{% endhighlight %}
</details>

### Похожие задачи в тестирующих системах

#### informatics.mccme.ru

[Задача №470, степени вершин](https://informatics.mccme.ru/mod/statements/view3.php?id=359&chapterid=470#1)

