# 基于知识图谱的论文搜索引擎
基于知识图谱，实现了论文搜索引擎，包括以关键词搜索模式以及智能问答模式。  

整个项目包含了数据获取（爬虫—）、简单数据处理、图数据库建立、算法设计、后端、前端。本项目是后端与前端与算法部分。
爬虫部分：[BirdBirdLee/CnkiSpider: 知网爬虫](https://github.com/BirdBirdLee/CnkiSpider)
数据处理之建库数据生成：[BirdBirdLee/data_import: 从原始数据中抽取Neo4j图数据库导入所需的csv文件](https://github.com/BirdBirdLee/data_import)
前端：未上传

注意：
1. `/src/main/resources/application.properties` 文件涉及数据库密码，已隐藏，文件内容如下：
    ```
    spring.neo4j.uri=
    spring.neo4j.authentication.username=
    spring.neo4j.authentication.password=
    ```

2. `/src/main/resources/hanlp/data/dictionary` ，Hanlp 词典文件已隐藏，请自行下载
