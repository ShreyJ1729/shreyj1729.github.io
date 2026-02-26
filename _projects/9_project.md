---
layout: page
title: "Maze Generator"
description: "Terminal maze generation using the disjoint-set (union-find) ADT in Rust."
img: assets/img/mazegen.png
importance: 9
category: fun
---

[github.com/ShreyJ1729/mazegen](https://github.com/ShreyJ1729/mazegen)

A Rust CLI that generates perfect mazes using Kruskal's algorithm over the disjoint-set (union-find) data structure. Supports path compression for large mazes and renders them directly in the terminal.

```
cargo run --release -- -r 7 -c 20
```
