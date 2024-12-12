---
title: Hugo使用教程
date: 2024-02-17
weight: 1
---

## 1.1 选择一个喜欢的模板

{{% steps %}}

###
访问hugo 的[模板地址](https://hugoblox.com/templates/)，选择一个免费的模板。自己还是比较喜欢简介一点的模板

![image-20241204103114411](./image-20241204103114411.png)

###
点击edit ,会跳转到github 仓库。也可以点击view demo 查看演示效果

![image-20241204103318198](./image-20241204103318198.png)

###
复制模板为自己的仓库

![image-20241204103647371](./image-20241204103647371.png)
{{% /steps %}}

## 1.2 编辑自己的博客内容
{{% steps %}}
###
跳转到仓库首页，点击“create codespace on main”

![create-codespace.ONu2r4OP_1306hT](./create-codespace.ONu2r4OP_1306hT.jpeg)
{{% /steps %}}


## 1.3. 发布编辑的内容
{{% steps %}}

###

点击“Settings”->"Pages"->"GitHub ACtions", 打开pages功能

![create-codespace.ONu2r4OP_1306hT](./create-codespace.ONu2r4OP_1306hT.png)
###

点击"Actions"->"Run workflow",开始运行构建工作

![trigger-workflow.2noFNHBc_1w53OS](./trigger-workflow.2noFNHBc_1w53OS.webp)
###

等一段时间后，页面面自动发布成功

![repo-link.PZui0L9N_Z1VOyMi](./repo-link.PZui0L9N_Z1VOyMi.webp)
{{% /steps %}}

## 下一章

章节列表

{{< cards >}}
  {{< card url="../guide/project-structure" title="Project Structure" icon="document-duplicate" >}}
  {{< card url="../guide/configuration" title="Configuration" icon="adjustments-vertical" >}}
{{< /cards >}}
