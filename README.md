## 个人信息

- 贺占峰/男/25
- 本科/软件工程
- 工作年限：3年
- 期望意愿 ：Java、大数据
- 期望城市：西安
- 邮箱：993134187@qq.com
- 电话：15249273140
- 技术博客：[语雀]( https://www.yuque.com/hezhanfeng)、[GitHub](https://github.com/HeZhanfeng/)

## 专业技能

- 熟悉Spring、SpringMVC、Mybatis及SpringBoot等常用框架
- 熟悉基于SpringCloud、SpringCloudAlibaba的微服务架构
- 熟悉Spark 、Alluxio、Dremio等大数据常用组件
- 熟悉Docker容器化技术及K8S容器编排技术
- 熟悉MySQL、PostgreSQL等数据库
- 熟悉RabbitMQ、RocketMQ、Redis及ETCD等中间件
- 熟悉版本控制工具Git、GitLab搭建及使用
- 熟悉WEB开发，了解HTML/CSS/JS等前端技术
- 熟悉爬虫框架Jsoup
- 了解Linux操作系统常用命令，能胜任一般的系统配置
- 了解Python常用数据分析、数据挖掘以及NLP算法库
- 了解 Ethereum等区块链技术

## 工作经历

##### 航天科工集团二院706研究所                                                                                                                       2019.9 – 至今  

* 负责事业部数据实验室的设计与实现
* 事业部虚拟数据湖项目功能模块开发
* 协调项目组前端、后端协同开发
* 负责与产品经理对接产品需求

#####         西安政通信息技术有限公司                                                                                                                    2017.10 – 2019.7  

* 政通机器学习平台设计与实现核心成员
* 负责项目的模块开发及文档编写
* 涉税情报采集模块的开发
* 电商税收分析平台电商数据采集模块的开发

## 教育背景

##### 西安工业大学北方信息工程学院   计算机信息与技术系   软件工程                                                      2014.9 – 2018.7  

系统学习Java语言程序设计、数据结构、数据库、微机原理、操作系统、软件工程、软件测试以及Linux等专业课程。其中数据结构课设、Java语言课设、JavaWeb课设以及数据库课设的考核成绩优秀

## 项目经历

**项目名称：数据实验室(DataLab)**       

* 项目简介： DataLab 致力于打造从接入数据、数据预处理、模型训练、预测以及模型部署的一站式全流程数据【探索】服务；数据实验室是航天科工集团二院706研究所自研数据探索平台，项目前后迭代两个大版本，1.0 基于单体构建并由python算法库提供算法支持，2.0 将混在一起的功能模块拆开构建由Spark提供分布式计算及算法支持并由Docker+K8S提供容器化支持以做到数据和计算资源的隔离

* 开发环境：JDK 8、Scala 2.11.12、Spark 2.4.3、 PostgreSQL、Git

* 项目架构：Spring Boot、 Spring Cloud Gateway 、Spring Security Oauth2、Vue、G6 、K8S、Redis等
* 主要职责：
  * 负责数据实验室的基础架构设计【主要工具亿图图示】、技术选型及流程梳理【主要工具MindMaster】
  * 负责数据实验室数据表结构设计【主要工具PDMan】
  * 负责数据实验室基础框架搭建，项目、实验、模型、组件配置等API接口开发【IDEA、Navicat等 】
  * 协调项目组前端、后端协同开发【Swagger】
  * 负责与产品经理沟通产品需求

**项目名称：政通机器学习平台(ZDML)**

项目简介：一站式全流程的可视化数据挖掘平台

主要职责：前期针对阿里云机器学习PAI、华为云机器学习平台、第四范式等成熟的机器学习平台进行调研；确定             需求后负责机器学习平台原型设计；后期负责部分模块的实现

成果及影响：平台后端整体业务架构基于Spring、SpringMVC以及MyBatis和Python构建，前端基于Vue+G6 Editor构建；采用分布式任务调度系统xxl-job实现离线任务的分发与执行；核心数据挖掘模块基于Python编写，主要用到Numpy、pandas和skleanrn等Python库；基于国内NLP领域出色的HanLP库做文本分析。项目上线后得到西安交通大学有关方便的教授及其团队的一致认可及支持

**项目名称：国家税务总局电商税收应用分析平台**  

项目简介：该项目为国税总局金三系统的子系统。主要针对国内知名电商网站（淘宝、京东、美团、大众点评、聚美、阿里巴巴、唯品会、途牛、去哪儿等）采集店铺信息、店铺旗下商品销量和价格以及店铺对应公司的工商信息，最终经过清洗匹配分析出税负情况

主要职责：项目分外网采集、内网分析和清洗匹配三个小组并行开发。项目中我和另外两个同事负责外网采集工作，主要针对目标网站进行分析形成采集策略文档，最终根据采集策略编写爬虫核心代码

成果及影响：系统基于SpringBoot开发，将每个网站的一套采集任务服务化。值得一提的是十几亿的数据我们采用的独特入库方式。采集过程中不解析入库，而是将数据包打成zip文件存储到服务器上，采集完成后将数据包解析写入到csv文件中，最后使用ETL将csv文件抽到客户指定已授权的oracle库中，这样大大提升了存储效率
