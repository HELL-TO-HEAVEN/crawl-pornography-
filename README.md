# crawl-pornography-
爬取色情图片
========================


  **先说明，这个小项目是有正当用途的~~用于训练色情图片识别模型**
      
      这个是我寒假第一次用python爬虫做的实战，一方面是为了爬取色情图片的数据，一方面是初学者练一下爬虫。
  
  不足之处：
  ---------------
  1、代码不优美，代理池太直接粗暴！
  2、模块独立性不够，内嵌太多
  3、抓取失败的图片太多，要找出原因
  4、单线程抓取，太耗时间！！！
           
      因为是第一次玩爬虫，所以只会单线程爬取，另外在程序里很多地方设置了time.sleep以防被反爬（但是貌似设置的时间太长了点），同时要爬取的图片是比较大的，差不多是2000x1000的大小，一张就一两兆的大小，所以整个程序跑起来爬取图片很慢。而且！！有很多图片是“爬取该图片失败”（我在程序里设置了一旦爬失败就打印出来）。所以控制台里一半信息都是打印出的爬取失败o(╥﹏╥)o



  最后的结果，放张图：(爬下了大概2个g的图片，后来发现因为没做去重处理，所以有一些重复的图片)
  --------------------
  
![如图 打码不易 简单粗暴](https://github.com/HELL-TO-HEAVEN/crawl-pornography-/blob/master/renti3png.png)


  为啥寒假做的项目，现在才放出来？
  。。因为我忘了，而且后续还要继续改动，有时间把改好的再放出来吧
