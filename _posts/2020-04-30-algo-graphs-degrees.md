---
layout: post
title:  "Степени вершин"
date:   2020-04-30 14:30:00 +0300
categories: algo graphs
---

## Задача:
Неориентированный граф задан списком рёбер, найти степени всех вершин графа.

## Решение:
Считываем ребра и наращиваем для вершин число инцидентных им рёбер.

{% highlight java %}
for (int i = 0; i < m; i++) {
	int u = in.nextInt() - 1;
	int v = in.nextInt() - 1;
	graph[u]++;
	graph[v]++;
}

{% endhighlight %}