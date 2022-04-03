---
title: Migrate Javascript to Typescript of Portfolio
date: 03-04-2022
categories:
- Typescript
- Javascript
tags:
- Typescript
- Portfolio
---

### 回忆从Javascript迁移到Typescript的修复bug的过程

> 首先在原有的React project上安装typescript的模板，运行```yarn add typescript @types/node @types/react @types/react-dom @types/jest```.
> 因为不知道该怎么下手，所以搜索了一下油管的一些视频,像[How to add Typescript to existing ReactJS project? Step by step tutorial](https://www.youtube.com/watch?v=A_rrMXLwyqI).
> 看了一点点视频后发现视频的内容比较简单，而修改我自己的portfolio却是一个巨大的工程，所以我决定在这个视频的启发下开始自己动手改代码。
> 心里比较没底，所以一开始就从简单的components改。打开 ***components*** folder,从第一个 ***About*** 文件改起。

> 遇到的第一个问题是需要手动添加后缀名 ***.tsx*** 到import的语句里。
> 
>