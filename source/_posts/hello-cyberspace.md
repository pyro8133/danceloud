---
title: Hello CYBERSPACE!
date: 2022-07-31T20:59:49.924Z
---
<!--StartFragment-->

After almost three days of tests, I finally built a rudiment of my personal website. Now I decide to record my motivation and my operation as an archive.

7.28

Initially, I was wandering in a social media called coolapk, then I was caught by a title "..markdown...note...". As a person who was blank about programming, I took it for granted that it's an article about how to "mark down" notes on several recommended apps, so I clicked in and found an [external link](https://blog.skywt.cn/posts/seven-notes-and-wiki-systems-evaluation#toc_title5). With strong curiosity about everything unknown and a plenty of spare time, I browsed his blogs, after that I found a person commented below one of his blogs seemed outstanding and left me a little impression. After a while, I found their interactions below another blog which the blogger showed his admiration and willing to subscribe the commentator's "RSS". This was a totally new word to me and I kept it in mind and turned to browse the others blogs. As usual, I selected the articles I interested in and collected the personal information the author showed online. It took me a while to seek his education background. The logical line is "studio\[on his website]-academic advisor'name\[ on connected link]-unit(the university/collage)\[on search engine]-checkout(position)\[on public page]". In this day, I equipped my laptop with RSS reader( irreader), not because I need it(I seldom browse pushed information.) but the notion of freely selecting and all in one got me. But if I decide to subscribe a small crowed website which didn't provide RSS and need cookies, I need to deployment and configuration on my own. From the guidance, I chose to deploy on my own laptop but failed in installing packages.

7.29

I kept trying and searching related information. In this proceed I also perfected my RSS subscriptions and my own private website. Nevertheless I still couldn't handle it. During this proceed I found another method to accomplish deployment and succeeded by almost one click. However, the configuration was totally alien to me and I gave up without hesitation. I turned to search for related information I interested in. By chance I find [this](https://blog.csdn.net/hangvane123/article/details/113751387?ops_request_misc=&request_id=&biz_id=102&utm_term=vercel%E9%83%A8%E7%BD%B2%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AEgitRSS&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduweb~default-3-113751387.142%5Ev35%5Eexperiment_2_v1&spm=1018.2226.3001.4187), I followed its steps but get stuck and asked the author for help( I also learned how to question, it in line with my imagination):

您好，我最近在研究部署，初次接触npm，没有相关基础。看了您关于静态博客部署的文章，我研究了大半天，自我检查“配置已经正确，只是还未上传身份验证器”。我认为问题出在“合并package.json”，我的做法是将验证器仓库中我所没有的部分转移到我的仓库，没有做任何修改。我采取将验证器仓库中的所有文件转移到我的仓库（以不冲突为前提）但无效

我感到我的能力可能不足以解决，希望获得您的帮助，打扰了，多谢。

7.30

He replied:

感谢关注，我这篇文章只是详细记录了手动搭建过程，如果你想按照此法，自建hexo博客的话，建议直接fork我做好的模板即可。具体操作可见readme

<https://github.com/hangvane/hexo-netlify-cms-vercel#usage>

用这个模板，你直接绑定好你的github相关验证密钥，去vercel部署一下就搞定了，不需要按照文章手动集成

In the morning I read [an author' acticles](http://www.ruanyifeng.com/survivor/) recommended in public RSS. I feel finally free from the stereotype of 211/985, and also know an example in reality by chance. That why I love ration, "when I understand, I am free of emotion." Then I kept building my private website and saw what I had made, read patiently about INTP and 5W4. Not until dawn did I find the author replied me. It's easy! However the method I chose helped me understand. I made a fresh start and succeeded. Then I decided to change the theme. But for unfamiliar about how to deal with the files on github, I made many mistakes and waste much time. Finally I succeeded in one and failed in another. I decided to find out the cause and asked:

您好，又打扰了。我想更换主题，next（[https://github.com/theme-next/hexo-theme-next）成功，mellow（https://github.com/codefine/hexo-theme-mellow）失败（点入主页白屏）。我的做法是在根目录创建themes并修改根目录的_config.yml的theme。我想知道是不是next的包比较完善的原因？mellow本身缺少依赖，根据说明我进行如下操作](https://github.com/theme-next/hexo-theme-next%EF%BC%89%E6%88%90%E5%8A%9F%EF%BC%8Cmellow%EF%BC%88https://github.com/codefine/hexo-theme-mellow%EF%BC%89%E5%A4%B1%E8%B4%A5%EF%BC%88%E7%82%B9%E5%85%A5%E4%B8%BB%E9%A1%B5%E7%99%BD%E5%B1%8F%EF%BC%89%E3%80%82%E6%88%91%E7%9A%84%E5%81%9A%E6%B3%95%E6%98%AF%E5%9C%A8%E6%A0%B9%E7%9B%AE%E5%BD%95%E5%88%9B%E5%BB%BAthemes%E5%B9%B6%E4%BF%AE%E6%94%B9%E6%A0%B9%E7%9B%AE%E5%BD%95%E7%9A%84_config.yml%E7%9A%84theme%E3%80%82%E6%88%91%E6%83%B3%E7%9F%A5%E9%81%93%E6%98%AF%E4%B8%8D%E6%98%AFnext%E7%9A%84%E5%8C%85%E6%AF%94%E8%BE%83%E5%AE%8C%E5%96%84%E7%9A%84%E5%8E%9F%E5%9B%A0%EF%BC%9Fmellow%E6%9C%AC%E8%BA%AB%E7%BC%BA%E5%B0%91%E4%BE%9D%E8%B5%96%EF%BC%8C%E6%A0%B9%E6%8D%AE%E8%AF%B4%E6%98%8E%E6%88%91%E8%BF%9B%E8%A1%8C%E5%A6%82%E4%B8%8B%E6%93%8D%E4%BD%9C) C:\Users\astro\git\danceloud\themes\mellow>npm install --save hexo-generator-search@2.1.1 hexo-generator-topindex@0.3.0 hexo-helper-qrcode@1.0.2 hexo-renderer-less@0.2.0

得到结果 npm WARN config global `--global`, `--local` are deprecated. Use `--location=global` instead. npm WARN deprecated cryptiles@2.0.5: This version has been deprecated in accordance with the hapi support policy ([hapi.im/support](http://hapi.im/support)). Please upgrade to the latest version to get the best features, bug fixes, and security patches. If you are unable to upgrade at this time, paid support is available for older versions ([hapi.im/commercial](http://hapi.im/commercial))

npm WARN deprecated boom@2.10.1: This version has been deprecated in accordance with the hapi support policy ([hapi.im/support](http://hapi.im/support)). Please upgrade to the latest version to get the best features, bug fixes, and security patches. If you are unable to upgrade at this time, paid support is available for older versions ([hapi.im/commercial](http://hapi.im/commercial)). npm WARN deprecated sntp@1.0.9: This module moved to @hapi/sntp. Please make sure to switch over as this distribution is no longer supported and may contain bugs and

太多了我就不放了...最后是added 74 packages in 6s。感觉是失败了，请问有什么解决方法吗？谢谢。

7.31

I asked this question because I thought it is very similar to the very first I met when deploy on my own laptop. I decide not to drag deeper for it's not much use (I tried to refining and the steps is too trivial to me for I still didn't handle how to edit locally...) ,and I don't know what to post and I just want to write on my private website for now. I will settle what I learnt and felt in these days, that's really a fruitful journey(not only knowledge but also opinion) and I' m happy. I am going to back to my routine.

GOOD-BYE.

<!-- notionvc: 38ed7b33-97ba-4a0b-a139-2c74bcbdf1c6 -->

<!--EndFragment-->