# 《这就是搜索引擎核心技术详解》相关

 - [搜索引擎的重要地位](#搜索引擎的重要地位)
 
 - [搜索引擎技术发展史](#搜索引擎技术发展史)
 
 - [搜索引擎的3个目标](#搜索引擎的3个目标)
 
 - [搜索引擎的3个核心问题](#搜索引擎的3个核心问题)
 
 - [搜索引擎的技术架构](#搜索引擎的技术架构)
 
 - [搜索引擎架构图](https://www.processon.com/view/link/5ed34f437d9c080702854f3f)
 
 - [网络爬虫](#网络爬虫)
 
 - [通用爬虫框架](#通用爬虫框架)
 
 ### 搜索引擎的重要地位
     由于目前互联网技术的爆炸性增长，信息过载的问题就目前来说越来越严重，由于互联网个性化的发展趋势越逐步展现，普通用户发布信息的成本
     越来越低，这个问题将会更加严重。这就是搜索引擎越来越重要的基础背景，搜索是目前解决信息过载的相对有效的方式，在没有更有效的替代解
     决方式出来之前，搜索引擎作为互联网网站和应用的入口及处于行业制高点的重要地位只会增强。
     
 ### 搜索引擎技术发展史
     1、分类目录
        采取分类目录的方式，纯人工方式并未采取什么高深的技术。如Yahoo、hao123这个时代的代表。
     2、文本检索
        采用经典的信息检索模型，采用布尔模型、向量空间模型或者概率模型，来查询用户的关键词和网页文本内容的相关程度。但是并未用到网页
        之间丰富的链接关系。早起的搜索引擎如AltaVista、Excite等大都采取这种模式。
     3、链接分析
        充分利用网页的链接关系，并深度挖掘和利用了网页链接所代表的含义。通常而言网页链接代表了一种推荐关系，所以通过链接分析可以在海
        量内容中找到重要的网页。如Google率先提出并使用PageRank链接分析技术。
     4、用户中心
        目前的搜索引擎大都可以归入第三代，即以理解用户需求为核心。
        目前搜索引擎大都致力于解决如下问题：如何能够理解用户发出的某个很短的查询词背后包含的真正需求，所以这一代的搜索引擎称之为以用
                                       户为中心的一代。
 ### 搜索引擎的3个目标
     应用形式：用户输入查询词，搜索引擎返回搜索结果。 
     1、更全
        索引的网页数量。可以通过提高网络爬虫相关技术来达到此目标。
     2、更快
        索引相关技术、缓存等技术的提出都是直接为了达到此目的。                                   
     3、更准
        如何使得搜索结果"更准"是最为关键的目标。(排序技术、链接分析技术、用户研究) 
 ### 搜索引擎的3个核心问题
     搜索引擎如何能够搜得更准是其最重要的目标。如何搜得更准涉及3个核心问题。
     1、用户真正的需求是什么
     2、哪些信息是和用户需求真正相关的
     3、哪些信息是用户可以依赖的      
 ### 搜索引擎的技术架构
     作为互联网应用中最具技术含量的应用之一，优秀的搜索引擎需要复杂的架构和算法，以此来支撑对海量数据的获取、存储，以即对用户查询的快
     速而准确的响应。
 ### 网络爬虫
     网络爬虫的作用
         高效的下载系统，将目前网页数以百亿计的网页数据传送到本地，在本地形成互联网网页的镜像备份。
 ### 通用爬虫框架
     爬虫划分以下3种类型
        1、批量型爬虫(Batch Crawler)
           又明确的抓取范围和目标
        2、增量型爬虫(Incremental Crawler)
           更新已有网页
        3、垂直型爬虫(Focused Crawler)
           关注特定主题内容或者属于特定行业的网页
     
            
     
     
     
               
     
  

        
     
     
     
     
     
     
     
     
     
     
     
     
     
     

> reubenwang@foxmail.com
> 没事别找我，找我也不在！--我很忙🦆