---
external: false
title: 自动提取Word单词使用教程
date: 2024-01-08
---

### 介绍

- 启发点：在学习英语的时候枯燥无味的背诵单词，在我看来效率是不高的。因为在背完之后，去阅读文章还是不能反应出对应的中文意思(对于我而言🤯)。因此思考背单词是为了阅读，那么何不能在阅读的时候背单词。

- 如何操作：仅仅需要找到对应阶段的阅读材料，将你的文章复制到word文档上。如果遇到不会的单词标注为**红色**，然后继续阅读（这时候你阅读完一句话，你大概会对这个单词有初步印象）。然后再次背单词！

- 这时候需要将这些你不会的单词汇总起来，集中背诵。因为你已经阅读过一篇文章了，所以这些单词其实已经有了基本的认识，不是那种单个单个的记忆。下一步就是将这些汇总好的单词，放入不背单词app中，里面有一个自定义。

- **综上，汇总单词是一件费时费力的过程，所以我写了一个小工具去自动获取标记为红的单词，存入.txt文件中，下一步直接将.txt导入到不背单词即可**。

### 如何使用

  > 十分抱歉，大学牲十分的苦命，因此在使用上可能有一定的门槛🥺，**接下来我会更新一个更加方便使用的版本**。

1. 你的电脑需要Java环境！

    ![java-version](/assets/auto-word-java-use/Tweelet.png)  

2. 下载源码

    [链接🔗](https://github.com/Agility6/auto-words-java)

    - 如果你的电脑有`Git` 直接`clone`即可，`git clone https://github.com/Agility6/auto-words-java.git`。

    - 如果没有可以下载压缩包解压即可。

    ![github-auto-java](/assets/auto-word-java-use/Tweelet2.png)

3. 指定路径运行🔥

    ![config](/assets/auto-word-java-use/Tweelet3.png)

### 使用效果图

- 案例文章

    ![1](/assets/auto-word-java-use/example.png)

- 执行🔥

    ![2](/assets/auto-word-java-use/output.png)

- 案例文章继续增加新单词

    ![3](/assets/auto-word-java-use/example-add-new-word.png)

- 再次执行🔥

    > **不会重复添加以前标记过的单词**

    ![4](/assets/auto-word-java-use/output-new.png)

### 欢迎交流:)

- 邮箱：agility1013@gmail.com
