# awesome-java

A curated list of awesome and amazing Java frameworks, libraries and software.

* Learning and Reference
	* [Tutorials and Books](#tutorials-and-books)
	* [Examples and Exercises](#examples-and-exercises)
* Language and Tooling
	* [Compilers and Interpreters](#compilers-and-interpreters)
	* [Build Systems](#build-systems)
	* [Linters and Formatters](#linters-and-formatters)
	* [Debugging and Profiling](#debugging-and-profiling)
* Web
	* [Web Frameworks](#web-frameworks)
	* [HTTP and Networking Clients](#http-and-networking-clients)
	* [API and GraphQL](#api-and-graphql)
	* [Web Servers and Proxies](#web-servers-and-proxies)
	* [Scraping and Crawling](#scraping-and-crawling)
* Data and Storage
	* [Databases](#databases)
	* [Database Clients and ORMs](#database-clients-and-orms)
	* [Serialization and Formats](#serialization-and-formats)
	* [Caching and Queues](#caching-and-queues)
	* [Search and Indexing](#search-and-indexing)
* Machine Learning and AI
	* [LLM and Inference](#llm-and-inference)
	* [Machine Learning Frameworks](#machine-learning-frameworks)
	* [Natural Language Processing](#natural-language-processing)
	* [Data Science and Analytics](#data-science-and-analytics)
* Networking and Distributed
	* [Networking](#networking)
	* [RPC and Messaging](#rpc-and-messaging)
	* [Distributed Systems](#distributed-systems)
	* [Cloud and Infrastructure](#cloud-and-infrastructure)
	* [Monitoring and Observability](#monitoring-and-observability)
* User Interface
	* [Mobile](#mobile)
	* [Applications and End User Tools](#applications-and-end-user-tools)
* Graphics and Media
	* [Game Development](#game-development)
	* [Image and Video](#image-and-video)
* Security
	* [Security Tools](#security-tools)
	* [Authentication and Authorization](#authentication-and-authorization)
	* [Reverse Engineering](#reverse-engineering)
* Concurrency and Performance
	* [Concurrency and Parallelism](#concurrency-and-parallelism)
* Testing and Quality
	* [Testing](#testing)
* Utilities
	* [Logging and Configuration](#logging-and-configuration)
	* [Text Processing](#text-processing)
	* [Files and Operating System](#files-and-operating-system)
	* [Automation and Scripting](#automation-and-scripting)
	* [General Purpose Libraries](#general-purpose-libraries)
* [Other](#other)

## Learning and Reference

### Tutorials and Books

* [Snailclimb/JavaGuide](https://github.com/Snailclimb/JavaGuide) - Java 面试 & 后端通用面试指南，覆盖计算机基础、数据库、分布式、高并发、系统设计与 AI 应用开发
* [krahets/hello-algo](https://github.com/krahets/hello-algo) - 《Hello 算法》：动画图解、一键运行的数据结构与算法教程。支持简中、繁中、English、日本語，提供 Python, Java, C++, C, C#, JS, Go, Swift, Rust, Ruby, Kotlin, TS, Dart 等代码实现
* [crossoverJie/JCSprout](https://github.com/crossoverJie/JCSprout) - 👨‍🎓 Java Core Sprout : basic, concurrent, algorithm
* [hollischuang/toBeTopJavaer](https://github.com/hollischuang/toBeTopJavaer) - To Be Top Javaer - Java工程师成神之路
* [kunal-kushwaha/DSA-Bootcamp-Java](https://github.com/kunal-kushwaha/DSA-Bootcamp-Java) - This repository consists of the code samples, assignments, and notes for the Java data structures & algorithms + interview preparation bootcamp of WeMakeDevs.
* [itwanger/toBeBetterJavaer](https://github.com/itwanger/toBeBetterJavaer) - 一份通俗易懂、风趣幽默的Java学习指南，内容涵盖Java基础、Java并发编程、Java虚拟机、Java企业级开发、Java面试等核心知识点。学Java，就认准二哥的Java进阶之路😄
* [winterbe/java8-tutorial](https://github.com/winterbe/java8-tutorial) - Modern Java - A Guide to Java 8
* [DuGuQiuBai/Java](https://github.com/DuGuQiuBai/Java) - 27天成为Java大神
* [frank-lam/fullstack-tutorial](https://github.com/frank-lam/fullstack-tutorial) - 🚀 fullstack tutorial 2022，后台技术栈/架构师之路/全栈开发社区，春招/秋招/校招/面试
* [doocs/jvm](https://github.com/doocs/jvm) - 🤗 JVM 底层原理最全知识总结
* [chefyuan/algorithm-base](https://github.com/chefyuan/algorithm-base) - 一位酷爱做饭的程序员，立志用动画将算法说的通俗易懂。我的面试网站 www.chengxuchu.com
* [xuchengsheng/spring-reading](https://github.com/xuchengsheng/spring-reading) - 涵盖了 Spring 框架的核心概念和关键功能，包括控制反转（IOC）容器的使用，面向切面编程（AOP）的原理与实践，事务管理的方式与实现，Spring MVC 的流程与控制器工作机制，以及 Spring 中数据访问、安全、Boot 自动配置等方面的深入研究。此外，它还包含了 Spring 事件机制的应用、高级主题如缓存抽象和响应式编程，以及对 Spring 源码的编程风格与设计模式的深入探讨。
* [h2pl/JavaTutorial](https://github.com/h2pl/JavaTutorial) - 【Java工程师面试复习指南】本仓库涵盖大部分Java程序员所需要掌握的核心知识，整合了互联网上的很多优质Java技术文章，力求打造为最完整最实用的Java开发者学习指南，如果对你有帮助，给个star告诉我吧，谢谢！
* [macrozheng/springcloud-learning](https://github.com/macrozheng/springcloud-learning) - 2024最新微服务实战教程，Spring Cloud组件、微服务项目实战、Kubernetes容器化部署全方位解析。技术栈：Spring Cloud Alibaba + Spring Boot 3.2 + JDK 17。
* [fuzhengwei/itstack-demo-design](https://github.com/fuzhengwei/itstack-demo-design) - :art: 《重学Java设计模式》是一本互联网真实案例实践书籍。以落地解决方案为核心，从实际业务中抽离出，交易、营销、秒杀、中间件、源码等22个真实场景，来学习设计模式的运用。欢迎关注小傅哥，微信(fustack)，公众号：bugstack虫洞栈，博客：https://bugstack.cn
* [amitshekhariitbhu/from-java-to-kotlin](https://github.com/amitshekhariitbhu/from-java-to-kotlin) - From Java To Kotlin - Your Cheat Sheet For Java To Kotlin
* [liyifeng1994/ssm](https://github.com/liyifeng1994/ssm) - 手把手教你整合最优雅SSM框架：SpringMVC + Spring + MyBatis
* [youlookwhat/DesignPattern](https://github.com/youlookwhat/DesignPattern) - 📚 Java 23种设计模式全归纳
* [javastacks/spring-boot-best-practice](https://github.com/javastacks/spring-boot-best-practice) - Spring Boot 最佳实践，已适配 Spring Boot 4.x，包括自动配置、核心原理、源码分析、国际化支持、调试、日志集成、热部署等。
* [fuzhengwei/small-spring](https://github.com/fuzhengwei/small-spring) - 🌱《 Spring 手撸专栏》，本专栏以 Spring 源码学习为目的，通过手写简化版 Spring 框架，了解 Spring 核心原理。在手写的过程中会简化 Spring 源码，摘取整体框架中的核心逻辑，简化代码实现过程，保留核心功能，例如：IOC、AOP、Bean生命周期、上下文、作用域、资源处理等内容实现。
* [nisrulz/android-tips-tricks](https://github.com/nisrulz/android-tips-tricks) - :ballot_box_with_check: [Cheatsheet] Tips and tricks for Android Development
* [RedSpider1/concurrent](https://github.com/RedSpider1/concurrent) - 这是RedSpider社区成员原创与维护的Java多线程系列文章。
* [mouredev/hello-java](https://github.com/mouredev/hello-java) - Curso para aprender el lenguaje de programación Java y Programación Orientada a Objetos (POO) desde cero y para principiantes. 75 lecciones, más de 8 horas en vídeo y 150 ejercicios prácticos.
* [s4kibs4mi/java-developer-roadmap](https://github.com/s4kibs4mi/java-developer-roadmap) - Roadmap to becoming a Java developer in 2026
* [javagrowing/JGrowing](https://github.com/javagrowing/JGrowing) - Java is Growing up but not only Java。Java成长路线，但学到不仅仅是Java。
* [brianway/java-learning](https://github.com/brianway/java-learning) - 旨在打造在线最佳的 Java 学习笔记，含博客讲解和源码实例，包括 Java SE 和 Java Web
* [mercyblitz/tech-weekly](https://github.com/mercyblitz/tech-weekly) - 「小马哥技术周报」
* [rbmonster/learning-note](https://github.com/rbmonster/learning-note) - Java开发及面试（个人面试、工作总结、资料收集站）
* [coderbruis/JavaSourceCodeLearning](https://github.com/coderbruis/JavaSourceCodeLearning) - 一份面向 Java 后端工程师的源码阅读地图：从 JDK / JUC 到 Spring、Netty、Kafka、RocketMQ，按核心链路拆解框架设计与底层实现。
* [ByteLegend/ByteLegend](https://github.com/ByteLegend/ByteLegend) - Enjoy programming while playing a game.
* [chengxy-nds/Springboot-Notebook](https://github.com/chengxy-nds/Springboot-Notebook) - Springboot-Notebook 一个以 springboot 为基础开发框架， 整合 Redis 、Mysql 、 Rabbitmq 、ES 、MongoDB、sharding-jdbc 分库分表、zookeeper 、web人脸识别 、实时消息推送 、SQL优化、注册中心 、数据脱敏 等互联网主流技术， 文章图解理论配合实战案例，实现开发中常见功能点的综合项目。 本着拿来即用的原则，助力于减少开发者在工作中的学习成本。
* [dunwu/javacore](https://github.com/dunwu/javacore) - ☕ JavaCore 是对 Java 核心技术的经验总结。
* [wenbochang888/house](https://github.com/wenbochang888/house) - 有完整版的PDF下载。
* [amitshekhariitbhu/android-developer-roadmap](https://github.com/amitshekhariitbhu/android-developer-roadmap) - Android Developer Roadmap - A complete roadmap to learn Android App Development
* [DreamCats/java-notes](https://github.com/DreamCats/java-notes) - 自己的学习笔记。包含：个人秋招经历、🐂客面经问题按照频率总结、Java一系列知识、数据库、分布式、微服务、前端、技术面试、每日文章等(持续更新)
* [Y4tacker/JavaSec](https://github.com/Y4tacker/JavaSec) - a rep for documenting my study, may be from 0 to 0.1
* [bin392328206/six-finger](https://github.com/bin392328206/six-finger) - 📓从Java基础、JavaWeb基础到常用的框架再到面试题、微服务、分布式、大数据都有完整的教程，几乎涵盖了Java必备的知识点
* [qiurunze123/threadandjuc](https://github.com/qiurunze123/threadandjuc) - ⭐⭐⭐⭐高并发-高可靠-高性能three-high-import导入系统-高并发多线程进阶
* [Jstarfish/JavaKeeper](https://github.com/Jstarfish/JavaKeeper) - ✍️ Java 工程师必备架构体系知识总结：涵盖分布式、微服务、RPC等互联网公司常用架构，以及数据存储、缓存、搜索等必备技能
* [scalad/Note](https://github.com/scalad/Note) - 常规Java工具，算法，加密，数据库，面试题，源代码分析，解决方案
* [CarpenterLee/JavaLambdaInternals](https://github.com/CarpenterLee/JavaLambdaInternals) - 深入理解Java函数式编程和Streams API
* [phith0n/JavaThings](https://github.com/phith0n/JavaThings) - Share Things Related to Java - Java安全漫谈笔记相关内容
* [Froussios/Intro-To-RxJava](https://github.com/Froussios/Intro-To-RxJava) - An extensive tutorial on RxJava
* [liuyubobobo/Play-with-Data-Structures](https://github.com/liuyubobobo/Play-with-Data-Structures) - Codes of my MOOC Course <Play Data Structures in Java>. Updated contents and practices are also included. 我在慕课网上的课程《Java语言玩转数据结构》示例代码。课程的更多更新内容及辅助练习也将逐步添加进这个代码仓。
* [learning-zone/java-basics](https://github.com/learning-zone/java-basics) - Java Basics ( Java-25 )
* [dunwu/java-tutorial](https://github.com/dunwu/java-tutorial) - :coffee: 老司机在 Java 技术领域的十年积累。
* [in28minutes/master-spring-and-spring-boot](https://github.com/in28minutes/master-spring-and-spring-boot) - Spring and Spring Boot Tutorial For Absolute Beginners - 10-in-1 - Spring to Spring Boot to REST API to Full Stack to Containers to Cloud
* [JosephZhu1983/java-common-mistakes](https://github.com/JosephZhu1983/java-common-mistakes) - 书籍《Java 开发坑点解析：从根因分析到最佳实践》 & 极客时间专栏《Java业务开发常见错误100例》源码
* [roncoo/spring-boot-demo](https://github.com/roncoo/spring-boot-demo) - Spring Boot的基础教程，由浅入深，一步一步学习Spring Boot，最后学到的不单单是基础！Spring Cloud基础教程请看：https://github.com/roncoo/spring-cloud-demo
* [fuzhengwei/interview](https://github.com/fuzhengwei/interview) - Java 面经手册，全书共计 5 章 29 节，417页11.5万字，耗时 4 个月完成。涵盖数据结构、算法逻辑、并发编程、JVM以及简历和互联网大厂面试等内容。
* [shekhargulati/java8-the-missing-tutorial](https://github.com/shekhargulati/java8-the-missing-tutorial) - Java 8 for all of us
* [kangjianwei/LearningJDK](https://github.com/kangjianwei/LearningJDK) - JDK源码阅读笔记
* [wupeixuan/JDKSourceCode1.8](https://github.com/wupeixuan/JDKSourceCode1.8) - Jdk1.8源码解析
* [mercyblitz/segmentfault-lessons](https://github.com/mercyblitz/segmentfault-lessons) - Segment Fault 在线讲堂 代码工程
* [cami-la/loops-e-arrays](https://github.com/cami-la/loops-e-arrays) - Repositório do curso Estruturas de Repetição e Arrays com Java. Curso este oferecido pela Digital Innovation one e ministrado por mim.
* [hellokaton/learn-java8](https://github.com/hellokaton/learn-java8) - 💖《跟上 Java 8》视频课程源码
* [spring-attic/spring-data-book](https://github.com/spring-attic/spring-data-book) - Spring Data - The Definitive Guide - Modern Data Access for Enterprise Java Developers *(archived)*

### Examples and Exercises

* [iluwatar/java-design-patterns](https://github.com/iluwatar/java-design-patterns) - Design patterns implemented in Java
* [doocs/advanced-java](https://github.com/doocs/advanced-java) - 😮 Core Interview Questions & Answers For Experienced Java(Backend) Developers | 互联网 Java 工程师进阶知识完全扫盲：涵盖高并发、分布式、高可用、微服务、海量数据处理等领域知识
* [TheAlgorithms/Java](https://github.com/TheAlgorithms/Java) - All Algorithms implemented in Java
* [kdn251/interviews](https://github.com/kdn251/interviews) - Everything you need to know to get the job.
* [doocs/leetcode](https://github.com/doocs/leetcode) - 🔥LeetCode solutions in any programming language | 多种编程语言实现 LeetCode、《剑指 Offer（第 2 版）》、《程序员面试金典（第 6 版）》题解
* [xkcoding/spring-boot-demo](https://github.com/xkcoding/spring-boot-demo) - 🚀一个用来深入学习并实战 Spring Boot 的项目。
* [ityouknow/spring-boot-examples](https://github.com/ityouknow/spring-boot-examples) - about learning Spring Boot via examples. Spring Boot 教程、技术栈示例代码，快速简单上手教程。
* [gyoogle/tech-interview-for-developer](https://github.com/gyoogle/tech-interview-for-developer) - 👶🏻 신입 개발자 전공 지식 & 기술 면접 백과사전 📖
* [android10/Android-CleanArchitecture](https://github.com/android10/Android-CleanArchitecture) - This is a sample app that is part of a series of blog posts I have written about how to architect an android application using Uncle Bob's clean architecture approach.
* [newbee-ltd/newbee-mall](https://github.com/newbee-ltd/newbee-mall) - 🔥 🎉newbee-mall是一套电商系统，包括基础版本(Spring Boot+Thymeleaf)、前后端分离版本(Spring Boot+Vue 3+Element-Plus+Vue-Router 4+Pinia+Vant 4) 、秒杀版本、Go语言版本、微服务版本(Spring Cloud Alibaba+Nacos+Sentinel+Seata+Spring Cloud Gateway+OpenFeign+ELK)。 前台商城系统包含首页门户、商品分类、新品上线、首页轮播、商品推荐、商品搜索、商品展示、购物车、订单结算、订单流程、个人订单管理、会员中心、帮助中心等模块。 后台管理系统包含数据面板、轮播图管理、商品管理、订单管理、会员管理、分类管理、设置等模块。
* [careercup/CtCI-6th-Edition](https://github.com/careercup/CtCI-6th-Edition) - Cracking the Coding Interview 6th Ed. Solutions
* [awsdocs/aws-doc-sdk-examples](https://github.com/awsdocs/aws-doc-sdk-examples) - Welcome to the AWS Code Examples Repository. This repo contains code examples used in the AWS documentation, AWS SDK Developer Guides, and more. For more information, see the Readme.md file below.
* [lihengming/spring-boot-api-project-seed](https://github.com/lihengming/spring-boot-api-project-seed) - :seedling::rocket:一个基于Spring Boot & MyBatis的种子项目，用于快速构建中小型API、RESTful API项目~
* [Blankj/awesome-java-leetcode](https://github.com/Blankj/awesome-java-leetcode) - :crown: LeetCode of algorithms with java solution(updating).
* [krahets/LeetCode-Book](https://github.com/krahets/LeetCode-Book) - 《剑指 Offer》《图解算法数据结构》《Krahets 笔面试精选 88 题》Python, Java, C++ 解题代码
* [gunnarmorling/1brc](https://github.com/gunnarmorling/1brc) - 1️⃣🐝🏎️ The One Billion Row Challenge -- A fun exploration of how quickly 1B rows from a text file can be aggregated with Java
* [kaushikgopal/RxJava-Android-Samples](https://github.com/kaushikgopal/RxJava-Android-Samples) - Learning RxJava for Android by example
* [CoderLeixiaoshuai/java-eight-part](https://github.com/CoderLeixiaoshuai/java-eight-part) - 『Java八股文』Java面试套路，Java进阶学习，打破内卷拿大厂Offer，升职加薪！
* [201206030/novel](https://github.com/201206030/novel) - novel 是一套基于时下最新 Java 技术栈 Spring Boot 3 + Vue 3 开发的前后端分离学习型小说项目，配备保姆级教程手把手教你从零开始开发上线一套生产级别的 Java 系统，由小说门户系统、作家后台管理系统、平台后台管理系统等多个子系统构成。包括小说推荐、作品检索、小说排行榜、小说阅读、小说评论、会员中心、作家专区、充值订阅、新闻发布等功能。
* [ZHENFENG13/spring-boot-projects](https://github.com/ZHENFENG13/spring-boot-projects) - :fire: 该仓库中主要是 Spring Boot 的入门学习教程以及一些常用的 Spring Boot 实战项目教程，包括 Spring Boot 使用的各种示例代码，同时也包括一些实战项目的项目源码和效果展示，实战项目包括基本的 web 开发以及目前大家普遍使用的线上博客项目/企业大型商城系统/前后端分离实践项目等，摆脱各种 hello world 入门案例的束缚，真正的掌握 Spring Boot 开发。
* [zhanglei-workspace/shopping-management-system](https://github.com/zhanglei-workspace/shopping-management-system) - 该项目为多个小项目的集合（持续更新中...）。内容类似淘宝、京东等网购管理系统以及图书管理、超市管理等系统。目的在于便于Java初级爱好者在学习完某一部分Java知识后有一个合适的项目锻炼、运用所学知识，完善知识体系。适用人群：Java基础到入门的爱好者。
* [2227324689/gpmall](https://github.com/2227324689/gpmall) - 【咕泡学院实战项目】-基于SpringBoot+Dubbo构建的电商平台-微服务架构、商城、电商、微服务、高并发、kafka、Elasticsearch
* [amitshekhariitbhu/RxJava2-Android-Samples](https://github.com/amitshekhariitbhu/RxJava2-Android-Samples) - RxJava 2 Android Examples - How to use RxJava 2 in Android
* [zq2599/blog_demos](https://github.com/zq2599/blog_demos) - CSDN博客专家程序员欣宸的github，这里有六百多篇原创文章的详细分类和汇总，以及对应的源码，内容涉及Java、Docker、Kubernetes、DevOPS等方面
* [hansonwang99/Spring-Boot-In-Action](https://github.com/hansonwang99/Spring-Boot-In-Action) - Spring Boot 系列实战合集
* [phishman3579/java-algorithms-implementation](https://github.com/phishman3579/java-algorithms-implementation) - Algorithms and Data Structures implemented in Java
* [awangdev/leet-code](https://github.com/awangdev/leet-code) - Java Solutions to problems on LintCode/LeetCode
* [NotFound9/interviewGuide](https://github.com/NotFound9/interviewGuide) - 《大厂面试指北》——包括Java基础、JVM、数据库、mysql、redis、计算机网络、算法、数据结构、操作系统、设计模式、系统设计、框架原理。
* [jbloch/effective-java-3e-source-code](https://github.com/jbloch/effective-java-3e-source-code) - The source code from the third edition of Effective Java, with minor additions as necessary to make it runnable.
* [fishercoder1534/Leetcode](https://github.com/fishercoder1534/Leetcode) - Solutions to LeetCode problems; updated daily. Subscribe to my YouTube channel for more.
* [rengwuxian/RxJavaSamples](https://github.com/rengwuxian/RxJavaSamples) - RxJava 2 和 Retrofit 结合使用的几个最常见使用方式举例
* [HelloWorld521/Java](https://github.com/HelloWorld521/Java) - java项目实战练习
* [liuyubobobo/Play-with-Algorithms](https://github.com/liuyubobobo/Play-with-Algorithms) - Codes of my MOOC Course <Play with Algorithms>, Both in C++ and Java language. Updated contents and practices are also included. 我在慕课网上的课程《算法与数据结构》示例代码，包括C++和Java版本。课程的更多更新内容及辅助练习也将逐步添加进这个代码仓。
* [lenve/JavaEETest](https://github.com/lenve/JavaEETest) - Spring、SpringMVC、MyBatis、Spring Boot案例
* [sherxon/AlgoDS](https://github.com/sherxon/AlgoDS) - Implementation of Algorithms and Data Structures, Problems and Solutions
* [gouthampradhan/leetcode](https://github.com/gouthampradhan/leetcode) - Leetcode solutions
* [BruceEckel/OnJava8-Examples](https://github.com/BruceEckel/OnJava8-Examples) - Code Examples for the book "On Java 8"
* [szerhusenBC/jwt-spring-security-demo](https://github.com/szerhusenBC/jwt-spring-security-demo) - A demo for using JWT (Json Web Token) with Spring Security and Spring Boot 2
* [Jackson0714/PassJava-Platform](https://github.com/Jackson0714/PassJava-Platform) - 一款面试刷题的 Spring Cloud 开源系统。零碎时间利用小程序查看常见面试题，夯实Java基础。 该项目可以教会你如何搭建SpringBoot项目，Spring Cloud项目。 采用流行的技术，如 SpringBoot、MyBatis、Redis、 MySql、 MongoDB、 RabbitMQ、Elasticsearch，采用Docker容器化部署。
* [spring-ai-alibaba/examples](https://github.com/spring-ai-alibaba/examples) - Examples demonstrating usage of Spring AI & Spring AI Alibaba 📜
* [AweiLoveAndroid/CommonDevKnowledge](https://github.com/AweiLoveAndroid/CommonDevKnowledge) - :octocat::fire: :star2::star::star::star: :star: 史上最全的BAT大厂Android面试题汇集，以及常用的Android开发的一些技能点，冷门知识点汇总，开发中遇到的坑汇总等干货。
* [liweiwei1419/LeetCode-Solutions-in-Good-Style](https://github.com/liweiwei1419/LeetCode-Solutions-in-Good-Style) - 首页已经更新，希望能对大家有帮助。
* [nanchen2251/RxJava2Examples](https://github.com/nanchen2251/RxJava2Examples) - :fire:RxJava2 Examples —— 这可能是从 RxJava1 跳到 RxJava2（学习 RxJava2 ）最好的例子 Demo：https://github.com/nanchen2251/RxJava2Examples
* [pedrovgs/Algorithms](https://github.com/pedrovgs/Algorithms) - Solutions for some common algorithm problems written in Java.
* [RodneyShag/HackerRank_solutions](https://github.com/RodneyShag/HackerRank_solutions) - 317 efficient solutions to HackerRank problems
* [liyupi/yu-ai-agent](https://github.com/liyupi/yu-ai-agent) - 编程导航 AI 开发实战新项目，基于 Spring Boot 3 + Java 21 + Spring AI 构建 AI 恋爱大师应用和 ReAct 模式自主规划智能体YuManus，覆盖 AI 大模型接入、Spring AI 核心特性、Prompt 工程和优化、RAG 检索增强、向量数据库、Tool Calling 工具调用、MCP 模型上下文协议、AI Agent 开发（Manas Java 实现）、Cursor AI 工具等核心知识。用一套教程将程序员必知必会的 AI 技术一网打尽，帮你成为 AI 时代企业的香饽饽，给你的简历和求职大幅增加竞争力。
* [googlemaps-samples/android-samples](https://github.com/googlemaps-samples/android-samples) - Samples demonstrating how to use Maps SDK for Android
* [javaee-samples/javaee7-samples](https://github.com/javaee-samples/javaee7-samples) - Java EE 7 Samples
* [techa03/goodsKill](https://github.com/techa03/goodsKill) - 🐎基于SpringCloud 2025.x + Dubbo 3.x + AI构建的模拟秒杀微服务项目，集成了Elasticsearch🔍、Gateway、Mybatis-Plus、Sharding-JDBC等常用开源组件
* [hellokaton/30-seconds-of-java8](https://github.com/hellokaton/30-seconds-of-java8) - ☕ 30 seconds to collect useful Java 8 snippet.
* [apache/incubator-seata-samples](https://github.com/apache/incubator-seata-samples) - Apache Seata(incubating) Samples for Java
* [anitaa1990/Android-Cheat-sheet](https://github.com/anitaa1990/Android-Cheat-sheet) - Cheat Sheet for Android Interviews
* [indy256/codelibrary](https://github.com/indy256/codelibrary) - :gem:Collection of algorithms and data structures
* [binarywang/weixin-java-mp-demo](https://github.com/binarywang/weixin-java-mp-demo) - 基于Spring Boot 和 WxJava 实现的微信公众号Java后端Demo，支持多公众号
* [nashtech-garage/yas](https://github.com/nashtech-garage/yas) - YAS: Yet Another Shop, a sample microservices project in Java
* [boylegu/SpringBoot-vue](https://github.com/boylegu/SpringBoot-vue) - A example demo base SpringBooot with vueJS2.x + webpack2.x as Java full stack web practice
* [javahongxi/whatsmars](https://github.com/javahongxi/whatsmars) - Java生态研究(Spring Boot + Redis + Dubbo + RocketMQ + Elasticsearch)🔥🔥🔥🔥🔥
* [nayuki/Project-Euler-solutions](https://github.com/nayuki/Project-Euler-solutions) - Runnable code for solving Project Euler problems in Java, Python, Mathematica, Haskell.
* [mercyblitz/thinking-in-spring-boot-samples](https://github.com/mercyblitz/thinking-in-spring-boot-samples) - 小马哥书籍《Spring Boot 编程思想》示例工程
* [GoogleCloudPlatform/java-docs-samples](https://github.com/GoogleCloudPlatform/java-docs-samples) - Java and Kotlin Code samples used on cloud.google.com
* [waylau/netty-4-user-guide-demos](https://github.com/waylau/netty-4-user-guide-demos) - Netty demos. （Netty 案例大全）
* [in28minutes/spring-microservices](https://github.com/in28minutes/spring-microservices) - OLD - Microservices using Spring Boot, Spring Cloud, Docker and Kubernetes. Replaced by https://github.com/in28minutes/spring-microservices-v3
* [Java-aid/Hackerrank-Solutions](https://github.com/Java-aid/Hackerrank-Solutions) - hackerrank solutions github | hackerrank all solutions | hackerrank solutions for java | hackerrank video tutorial | hackerrank cracking the coding interview solutions | hackerrank data structures | hackerrank solutions algorithms | hackerrank challenge | hackerrank coding challenge | hackerrank algorithms solutions github| hackerrank problem solving | hackerrank programs solutions | JAVAAID |all hackerrank solutions | Coding Interview Preparation
* [RichardWarburton/java-8-lambdas-exercises](https://github.com/RichardWarburton/java-8-lambdas-exercises) - Exercises and Answers for Java 8 Lambdas book
* [ZHENFENG13/ssm-demo](https://github.com/ZHENFENG13/ssm-demo) - :banana:Spring+SpringMVC+Mybatis+easyUI实现简单的后台管理系统
* [centic9/jgit-cookbook](https://github.com/centic9/jgit-cookbook) - Provides examples and code snippets for the JGit Java Git implementation
* [mattia-battiston/clean-architecture-example](https://github.com/mattia-battiston/clean-architecture-example) - Clean Architecture Example (Java): Example of what clean architecture would look like (in Java)
* [j3ers3/Hello-Java-Sec](https://github.com/j3ers3/Hello-Java-Sec) - ☕️ Java Security，安全编码和代码审计
* [FreeTymeKiyan/LeetCode-Sol-Res](https://github.com/FreeTymeKiyan/LeetCode-Sol-Res) - Clean, Understandable Solutions and Resources for LeetCode Online Judge Algorithm Problems.
* [JeffLi1993/java-core-learning-example](https://github.com/JeffLi1993/java-core-learning-example) - 关于Java核心技术学习积累的例子，是初学者及核心技术巩固的最佳实践。
* [aimacode/aima-java](https://github.com/aimacode/aima-java) - Java implementation of algorithms from Russell And Norvig's "Artificial Intelligence - A Modern Approach"
* [LeonardoZ/java-concurrency-patterns](https://github.com/LeonardoZ/java-concurrency-patterns) - Concurrency Patterns and features found in Java, through multithreaded programming. Threads, Locks, Atomics and more.
* [cachecats/coderiver](https://github.com/cachecats/coderiver) - 致力于打造全平台全栈精品开源项目，计划做成包含 pc 端（Vue、React）、移动 H5（Vue、React）、ReactNative、Flutter、Android 原生、微信小程序、Angular、Node、java 后端的全平台型全栈项目，欢迎关注。
* [netgloo/spring-boot-samples](https://github.com/netgloo/spring-boot-samples) - Spring Boot samples by Netgloo
* [lenve/javaboy-code-samples](https://github.com/lenve/javaboy-code-samples) - 公众号【江南一点雨】文章案例汇总，技术文章请戳这里----->

## Language and Tooling

### Compilers and Interpreters

* [openjdk/jdk](https://github.com/openjdk/jdk) - JDK main-line development https://openjdk.org/projects/jdk
* [oracle/graal](https://github.com/oracle/graal) - GraalVM compiles applications into native executables that start instantly, scale fast, and use fewer compute resources 🚀
* [antlr/antlr4](https://github.com/antlr/antlr4) - ANTLR (ANother Tool for Language Recognition) is a powerful parser generator for reading, processing, executing, or translating structured text or binary files.
* [projectlombok/lombok](https://github.com/projectlombok/lombok) - Very spicy additions to the Java programming language.
* [square/javapoet](https://github.com/square/javapoet) - A Java API for generating .java source files. *(archived)*
* [google/auto](https://github.com/google/auto) - A collection of source code generators for Java.
* [raphw/byte-buddy](https://github.com/raphw/byte-buddy) - Runtime code generation for the Java virtual machine.
* [javaparser/javaparser](https://github.com/javaparser/javaparser) - Java 1-25 Parser and Abstract Syntax Tree for Java with advanced analysis functionalities.
* [google/j2objc](https://github.com/google/j2objc) - A Java to iOS Objective-C translation tool and runtime.
* [alibaba/QLExpress](https://github.com/alibaba/QLExpress) - QLExpress is a powerful, lightweight, dynamic language for the Java platform aimed at improving developers’ productivity in different business scenes.
* [killme2008/aviatorscript](https://github.com/killme2008/aviatorscript) - A high performance scripting language hosted on the JVM.
* [cglib/cglib](https://github.com/cglib/cglib) - cglib - Byte Code Generation Library is high level API to generate and transform Java byte code. It is used by AOP, testing, data access frameworks to generate dynamic proxy objects and intercept field access.
* [dragonwell-project/dragonwell8](https://github.com/dragonwell-project/dragonwell8) - Alibaba Dragonwell8 JDK
* [jboss-javassist/javassist](https://github.com/jboss-javassist/javassist) - Java bytecode engineering toolkit
* [eclipse-openj9/openj9](https://github.com/eclipse-openj9/openj9) - Eclipse OpenJ9: A Java Virtual Machine for OpenJDK that's optimized for small footprint, fast start-up, and high throughput. Builds on Eclipse OMR (https://github.com/eclipse/omr) and combines with the Extensions for OpenJDK for OpenJ9 repo.
* [luontola/retrolambda](https://github.com/luontola/retrolambda) - Backport of Java 8's lambda expressions to Java 7, 6 and 5
* [konsoletyper/teavm](https://github.com/konsoletyper/teavm) - Compiles Java bytecode to JavaScript, WebAssembly and C
* [manifold-systems/manifold](https://github.com/manifold-systems/manifold) - Manifold is a Java compiler plugin, its features include Metaprogramming, Properties, Extension Methods, Operator Overloading, Templates, a Preprocessor, and more.
* [eclipsesource/J2V8](https://github.com/eclipsesource/J2V8) - Java Bindings for V8
* [openjdk/loom](https://github.com/openjdk/loom) - https://openjdk.org/projects/loom
* [dcevm/dcevm](https://github.com/dcevm/dcevm) - Dynamic Code Evolution VM for Java 7/8
* [SpongePowered/Mixin](https://github.com/SpongePowered/Mixin) - Mixin is a trait/mixin and bytecode weaving framework for Java using ASM
* [jphp-group/jphp](https://github.com/jphp-group/jphp) - JPHP - an implementation of PHP on Java VM
* [sofastack/sofa-ark](https://github.com/sofastack/sofa-ark) - SOFAArk is a light-weight，java based classloader isolation framework.
* [cincheo/jsweet](https://github.com/cincheo/jsweet) - A Java to JavaScript transpiler.
* [albertlatacz/java-repl](https://github.com/albertlatacz/java-repl) - Read Eval Print Loop for Java

### Build Systems

* [facebook/buck](https://github.com/facebook/buck) - A fast build system that encourages the creation of small, reusable modules over a variety of platforms and languages. *(archived)*
* [apache/maven](https://github.com/apache/maven) - Apache Maven core
* [evant/gradle-retrolambda](https://github.com/evant/gradle-retrolambda) - A gradle plugin for getting java lambda support in java 6, 7 and android
* [mcxiaoke/packer-ng-plugin](https://github.com/mcxiaoke/packer-ng-plugin) - 下一代Android打包工具（对Gradle 7.x的支持，欢迎提PR） *(archived)*
* [apache/maven-mvnd](https://github.com/apache/maven-mvnd) - Apache Maven Daemon
* [spotify/dockerfile-maven](https://github.com/spotify/dockerfile-maven) - MATURE: A set of Maven tools for dealing with Dockerfiles *(archived)*
* [spotify/docker-maven-plugin](https://github.com/spotify/docker-maven-plugin) - INACTIVE: A maven plugin for Docker *(archived)*
* [fabric8io/docker-maven-plugin](https://github.com/fabric8io/docker-maven-plugin) - Maven plugin for running and creating Docker images
* [jbangdev/jbang](https://github.com/jbangdev/jbang) - Unleash the power of Java - JBang Lets Students, Educators and Professional Developers create, edit and run self-contained source-only Java programs with unprecedented ease.

### Linters and Formatters

* [checkstyle/checkstyle](https://github.com/checkstyle/checkstyle) - Checkstyle is a development tool to help programmers write Java code that adheres to a coding standard. By default it supports the Google Java Style Guide and Sun Code Conventions, but is highly configurable. It can be invoked with an ANT task and a command line program.
* [google/error-prone](https://github.com/google/error-prone) - Catch common Java mistakes as compile-time errors
* [google/google-java-format](https://github.com/google/google-java-format) - Reformats Java source code to comply with Google Java Style.
* [diffplug/spotless](https://github.com/diffplug/spotless) - Keep your code spotless
* [pmd/pmd](https://github.com/pmd/pmd) - An extensible multilanguage static code analyzer.
* [uber/NullAway](https://github.com/uber/NullAway) - A tool to help eliminate NullPointerExceptions (NPEs) in your Java code with low build-time overhead
* [spotbugs/spotbugs](https://github.com/spotbugs/spotbugs) - SpotBugs is FindBugs' successor. A tool for static analysis to look for bugs in Java code.
* [openrewrite/rewrite](https://github.com/openrewrite/rewrite) - Automated mass refactoring of source code.
* [soot-oss/soot](https://github.com/soot-oss/soot) - Soot - A Java optimization framework
* [uber/piranha](https://github.com/uber/piranha) - A tool for refactoring code related to feature flag APIs
* [INRIA/spoon](https://github.com/INRIA/spoon) - Spoon is a metaprogramming library to analyze and transform Java source code. :spoon: is made with :heart:, :beers: and :sparkles:. It parses source files to build a well-designed AST with powerful analysis and transformation API.
* [pascal-lab/Tai-e](https://github.com/pascal-lab/Tai-e) - An easy-to-learn/use static analysis framework for Java and Android
* [kalessil/phpinspectionsea](https://github.com/kalessil/phpinspectionsea) - A Static Code Analyzer for PHP (a PhpStorm/Idea Plugin)

### Debugging and Profiling

* [alibaba/arthas](https://github.com/alibaba/arthas) - Alibaba Java Diagnostic Tool Arthas/Alibaba Java诊断利器Arthas
* [btraceio/btrace](https://github.com/btraceio/btrace) - Production-safe dynamic tracing and diagnostics for Java applications—attach to live JVMs with no restart or recompilation.
* [chewiebug/GCViewer](https://github.com/chewiebug/GCViewer) - Fork of tagtraum industries' GCViewer. Tagtraum stopped development in 2008, I aim to improve support for Sun's / Oracle's java 1.6+ garbage collector logs (including G1 collector)
* [qunarcorp/bistoury](https://github.com/qunarcorp/bistoury) - Bistoury是去哪儿网的java应用生产问题诊断工具，提供了一站式的问题诊断方案
* [oldmanpushcart/greys-anatomy](https://github.com/oldmanpushcart/greys-anatomy) - Java诊断工具
* [oracle/visualvm](https://github.com/oracle/visualvm) - VisualVM is an All-in-One Java Troubleshooting Tool
* [spring-projects/spring-loaded](https://github.com/spring-projects/spring-loaded) - Java agent that enables class reloading in a running JVM
* [HotswapProjects/HotswapAgent](https://github.com/HotswapProjects/HotswapAgent) - Java unlimited redefinition of classes at runtime.
* [uber-common/jvm-profiler](https://github.com/uber-common/jvm-profiler) - JVM Profiler Sending Metrics to Kafka, Console Output or Custom Reporter
* [square/haha](https://github.com/square/haha) - DEPRECATED Java library to automate the analysis of Android heap dumps. *(archived)*

## Web

### Web Frameworks

* [spring-projects/spring-boot](https://github.com/spring-projects/spring-boot) - Spring Boot helps you to create Spring-powered, production-grade applications and services with absolute minimum fuss.
* [alibaba/spring-cloud-alibaba](https://github.com/alibaba/spring-cloud-alibaba) - Spring Cloud Alibaba provides a one-stop solution for application development for the distributed solutions of Alibaba middleware.
* [quarkusio/quarkus](https://github.com/quarkusio/quarkus) - Quarkus: Supersonic Subatomic Java.
* [eclipse-vertx/vert.x](https://github.com/eclipse-vertx/vert.x) - Vert.x is a tool-kit for building reactive applications on the JVM
* [perwendel/spark](https://github.com/perwendel/spark) - A simple expressive web framework for java. Spark has a kotlin DSL https://github.com/perwendel/spark-kotlin
* [dropwizard/dropwizard](https://github.com/dropwizard/dropwizard) - A damn simple library for building production-ready RESTful web services.
* [hs-web/hsweb-framework](https://github.com/hs-web/hsweb-framework) - hsweb (haʊs wɛb) 是一个基于spring-boot 2.x开发 ,首个使用全响应式编程的企业级后台管理系统基础项目。
* [chillzhuang/SpringBlade](https://github.com/chillzhuang/SpringBlade) - SpringBlade 是一个由商业级项目升级优化而来的微服务架构，采用Spring Boot 4 、Spring Cloud 2025、Java 21 等核心技术构建，完全遵循阿里巴巴编码规范。提供基于React和Vue的两个前端框架用于快速搭建企业级的SaaS多租户微服务平台。
* [micronaut-projects/micronaut-core](https://github.com/micronaut-projects/micronaut-core) - Micronaut Application Framework
* [dromara/lamp-cloud](https://github.com/dromara/lamp-cloud) - [灯灯]微服务中后台快速开发平台，支持jdk21、jdk17、jdk8，专注于多租户、开放平台解决方案，亦可作为普通项目（非SaaS架构）的基础开发框架使用，目前已实现插拔式数据库隔离、SCHEMA隔离、字段隔离 等租户隔离方案。
* [spring-cloud/spring-cloud-netflix](https://github.com/spring-cloud/spring-cloud-netflix) - Integration with Netflix OSS components
* [zlt2000/microservices-platform](https://github.com/zlt2000/microservices-platform) - 基于SpringBoot2.x、SpringCloud和SpringCloudAlibaba并采用前后端分离的企业级微服务多租户系统架构。并引入组件化的思想实现高内聚低耦合，项目代码简洁注释丰富上手容易，适合学习和企业中使用。真正实现了基于RBAC、jwt和oauth2的无状态统一权限认证的解决方案，面向互联网设计同时适合B端和C端用户，支持CI/CD多环境部署，并提供应用管理方便第三方系统接入；同时还集合各种微服务治理功能和监控功能。模块包括:企业级的认证系统、开发平台、应用监控、慢sql监控、统一日志、单点登录、Redis分布式高速缓存、配置中心、分布式任务调度、接口文档、代码生成等等。
* [helidon-io/helidon](https://github.com/helidon-io/helidon) - Java libraries for writing microservices
* [networknt/light-4j](https://github.com/networknt/light-4j) - A fast, lightweight and more productive microservices framework
* [jfinal/jfinal](https://github.com/jfinal/jfinal) - JAVA WEB + ORM Framework
* [opensolon/solon](https://github.com/opensolon/solon) - 🔥 Java enterprise application development framework for full scenario: Restrained, Efficient, Open, Ecologicalll!!! 700% higher concurrency 50% memory savings Startup is 10 times faster. Packing 90% smaller; Compatible with java8 ~ java26; Supports LTS. (Replaceable spring)
* [erupts/erupt](https://github.com/erupts/erupt) - Why write many code when few annotation do trick — annotation-driven Java framework, one class become full admin, now with built-in AI harness too
* [nutzam/nutz](https://github.com/nutzam/nutz) - Nutz -- Web Framework(Mvc/Ioc/Aop/Dao/Json) for ALL Java developer
* [jeecgboot/jeecg](https://github.com/jeecgboot/jeecg) - JEECG是一款基于代码生成器的J2EE快速开发平台，开源界“小普元”超越传统商业企业级开发平台。引领新的开发模式(Online Coding模式(自定义表单) - > 代码生成器模式 - > 手工MERGE智能开发)， 可以帮助解决Java项目90%的重复工作，让开发更多关注业务逻辑。既能快速提高开发效率，帮助公司节省人力成本，同时又不失灵活性。具备：表单配置能力（无需编码）、移动配置能力、工作流配置能力、报表配置能力（支持移动端）、插件开发能力（可插拔）
* [BroadleafCommerce/BroadleafCommerce](https://github.com/BroadleafCommerce/BroadleafCommerce) - Broadleaf Commerce CE - an eCommerce framework based on Java and Spring
* [ninjaframework/ninja](https://github.com/ninjaframework/ninja) - Ninja is a full stack web framework for Java. Rock solid, fast and super productive.
* [vaadin/framework](https://github.com/vaadin/framework) - Vaadin 6, 7, 8 is a Java framework for modern Java web applications.
* [jooby-project/jooby](https://github.com/jooby-project/jooby) - The modular web framework for Java and Kotlin
* [spotify/apollo](https://github.com/spotify/apollo) - Java libraries for writing composable microservices *(archived)*
* [rapidoid/rapidoid](https://github.com/rapidoid/rapidoid) - Rapidoid - Extremely Fast, Simple and Powerful Java Web Framework and HTTP Server!
* [bootique/bootique](https://github.com/bootique/bootique) - Bootique is a minimally opinionated platform for modern runnable Java apps.
* [cuba-platform/cuba](https://github.com/cuba-platform/cuba) - CUBA Platform is a high level framework for enterprise applications development

### HTTP and Networking Clients

* [lysine-dev/retrofit](https://github.com/lysine-dev/retrofit) - A type-safe HTTP client for Android and the JVM
* [binarywang/WxJava](https://github.com/binarywang/WxJava) - 微信开发 Java SDK ，支持包括微信支付，开放平台，小程序，企业微信，视频号，公众号等的后端开发
* [android-async-http/android-async-http](https://github.com/android-async-http/android-async-http) - An asynchronous, callback-based Http client for Android built on top of Apache's HttpClient libraries.
* [OpenFeign/feign](https://github.com/OpenFeign/feign) - Feign makes writing java http clients easier
* [AsyncHttpClient/async-http-client](https://github.com/AsyncHttpClient/async-http-client) - Asynchronous, non-blocking HTTP & WebSocket client for the JVM
* [discord-jda/JDA](https://github.com/discord-jda/JDA) - Java wrapper for the popular chat & VOIP service: Discord https://discord.com
* [kevinsawicki/http-request](https://github.com/kevinsawicki/http-request) - Java HTTP Request Library
* [Twitter4J/Twitter4J](https://github.com/Twitter4J/Twitter4J) - Twitter4J is an open-source Java library for the Twitter API.
* [chanjarster/weixin-java-tools](https://github.com/chanjarster/weixin-java-tools) - 微信公众号、企业号Java SDK *(archived)*
* [Kong/unirest-java](https://github.com/Kong/unirest-java) - Unirest in Java: Simplified, lightweight HTTP client library.
* [liyiorg/weixin-popular](https://github.com/liyiorg/weixin-popular) - 微信SDK JAVA (公众平台、开放平台、 商户平台、 服务商平台)
* [dromara/forest](https://github.com/dromara/forest) - A high-level and lightweight declarative HTTP client framework for Java. it makes sending HTTP requests in Java easier.
* [LianjiaTech/retrofit-spring-boot-starter](https://github.com/LianjiaTech/retrofit-spring-boot-starter) - A spring-boot starter for retrofit, supports rapid integration and feature enhancements.（适用于retrofit的spring-boot-starter，支持快速集成和功能增强）
* [googlemaps/google-maps-services-java](https://github.com/googlemaps/google-maps-services-java) - Java client library for Google Maps API Web Services
* [googleapis/google-http-java-client](https://github.com/googleapis/google-http-java-client) - Google HTTP Client Library for Java

### API and GraphQL

* [swagger-api/swagger-core](https://github.com/swagger-api/swagger-core) - Examples and server integrations for generating the Swagger API Specification, which enables easy access to your REST API
* [graphql-java/graphql-java](https://github.com/graphql-java/graphql-java) - GraphQL Java implementation
* [springfox/springfox](https://github.com/springfox/springfox) - Automated JSON API documentation for API's built with Spring
* [springdoc/springdoc-openapi](https://github.com/springdoc/springdoc-openapi) - Library for OpenAPI 3 with spring-boot
* [hapifhir/hapi-fhir](https://github.com/hapifhir/hapi-fhir) - 🔥 HAPI FHIR - Java API for HL7 FHIR Clients and Servers
* [apilayer/restcountries](https://github.com/apilayer/restcountries) - Get information about countries via a RESTful API *(archived)*
* [ssssssss-team/magic-api](https://github.com/ssssssss-team/magic-api) - magic-api 是一个接口快速开发框架，通过Web页面编写脚本以及配置，自动映射为HTTP接口，无需定义Controller、Service、Dao、Mapper、XML、VO等Java对象

### Web Servers and Proxies

* [apache/shenyu](https://github.com/apache/shenyu) - Apache ShenYu is a Java native API Gateway for service proxy, protocol conversion and API governance.
* [apache/tomcat](https://github.com/apache/tomcat) - Apache Tomcat
* [NanoHttpd/nanohttpd](https://github.com/NanoHttpd/nanohttpd) - Tiny, easily embeddable HTTP server in Java.
* [spring-cloud/spring-cloud-gateway](https://github.com/spring-cloud/spring-cloud-gateway) - An API Gateway built on Spring Framework and Spring Boot providing routing and more.
* [jetty/jetty.project](https://github.com/jetty/jetty.project) - Eclipse Jetty® - Web Container & Clients - supports HTTP/3, HTTP/2, HTTP/1, websocket, servlets, and more
* [undertow-io/undertow](https://github.com/undertow-io/undertow) - High performance non-blocking webserver
* [monkeyWie/proxyee](https://github.com/monkeyWie/proxyee) - HTTP proxy server,support HTTPS&websocket.MITM impl,intercept and tamper HTTPS traffic.
* [mitre/HTTP-Proxy-Servlet](https://github.com/mitre/HTTP-Proxy-Servlet) - Smiley's HTTP Proxy implemented as a Java servlet

### Scraping and Crawling

* [SeleniumHQ/selenium](https://github.com/SeleniumHQ/selenium) - A browser automation framework and ecosystem.
* [code4craft/webmagic](https://github.com/code4craft/webmagic) - A scalable web crawler framework for Java.
* [jhy/jsoup](https://github.com/jhy/jsoup) - jsoup: the Java HTML parser, built for HTML editing, cleaning, scraping, and XSS safety.
* [yasserg/crawler4j](https://github.com/yasserg/crawler4j) - Open Source Web Crawler for Java
* [internetarchive/heritrix3](https://github.com/internetarchive/heritrix3) - Heritrix is the Internet Archive's open-source, extensible, web-scale, archival-quality web crawler project.
* [apache/nutch](https://github.com/apache/nutch) - Apache Nutch is an extensible and scalable web crawler
* [CrawlScript/WebCollector](https://github.com/CrawlScript/WebCollector) - WebCollector is an open source web crawler framework based on Java.It provides some simple interfaces for crawling the Web,you can setup a multi-threaded web crawler in less than 5 minutes.
* [brianway/webporter](https://github.com/brianway/webporter) - 基于 webmagic 的 Java 爬虫应用
* [xtuhcy/gecco](https://github.com/xtuhcy/gecco) - Easy to use lightweight web crawler（易用的轻量化网络爬虫）
* [zhegexiaohuozi/SeimiCrawler](https://github.com/zhegexiaohuozi/SeimiCrawler) - 一个简单、敏捷、分布式的支持SpringBoot的Java爬虫框架;An agile, distributed crawler framework.

## Data and Storage

### Databases

* [questdb/questdb](https://github.com/questdb/questdb) - QuestDB is a high performance, open-source, time-series database
* [prestodb/presto](https://github.com/prestodb/presto) - The official home of the Presto distributed SQL query engine for big data
* [trinodb/trino](https://github.com/trinodb/trino) - Official repository of Trino, the distributed SQL query engine for big data, formerly known as PrestoSQL (https://trino.io)
* [realm/realm-java](https://github.com/realm/realm-java) - Realm is a mobile database: a replacement for SQLite & ORMs
* [apache/cassandra](https://github.com/apache/cassandra) - Open source transactional distributed database. Linear scalability and proven fault-tolerance on commodity hardware or cloud infrastructure without compromising performance.
* [apache/iotdb](https://github.com/apache/iotdb) - Apache IoTDB
* [apache/pinot](https://github.com/apache/pinot) - Apache Pinot - A realtime distributed OLAP datastore
* [apache/hive](https://github.com/apache/hive) - Apache Hive
* [apache/hbase](https://github.com/apache/hbase) - Apache HBase
* [apache/calcite](https://github.com/apache/calcite) - Apache Calcite
* [jankotek/mapdb](https://github.com/jankotek/mapdb) - MapDB provides concurrent Maps, Sets and Queues backed by disk storage or off-heap-memory. It is a fast and easy to use embedded Java database engine.
* [h2database/h2database](https://github.com/h2database/h2database) - H2 is an embeddable RDBMS written in Java.
* [objectbox/objectbox-java](https://github.com/objectbox/objectbox-java) - Database for Android and JVM - first and fast, lightweight on-device vector database
* [crate/crate](https://github.com/crate/crate) - CrateDB is a distributed and scalable SQL database for storing and analyzing massive amounts of data in near real-time, even with complex queries. It is PostgreSQL-compatible, and based on Lucene.
* [pilgr/Paper](https://github.com/pilgr/Paper) - Paper is a fast NoSQL-like storage for Java/Kotlin objects on Android with automatic schema migration support.
* [apache/drill](https://github.com/apache/drill) - Apache Drill is a distributed MPP query layer for self describing data
* [npgall/cqengine](https://github.com/npgall/cqengine) - Ultra-fast SQL-like queries on Java collections
* [kairosdb/kairosdb](https://github.com/kairosdb/kairosdb) - Fast scalable time series database
* [MyCATApache/Mycat2](https://github.com/MyCATApache/Mycat2) - MySQL Proxy using Java NIO based on Sharding SQL,Calcite ,simple and fast
* [dain/leveldb](https://github.com/dain/leveldb) - Port of LevelDB to Java

### Database Clients and ORMs

* [redisson/redisson](https://github.com/redisson/redisson) - Redisson: Valkey & Redis Java Client and Real-Time Data Platform. Sync/Async/RxJava/Reactive API. Over 50 Valkey and Redis based Java objects and services: Set, Multimap, SortedSet, Map, List, Queue, Deque, Semaphore, Lock, AtomicLong, Map Reduce, Bloom filter, Spring, Tomcat, Scheduler, JCache API, Hibernate, RPC, local cache..
* [brettwooldridge/HikariCP](https://github.com/brettwooldridge/HikariCP) - 光 HikariCP・A solid, high-performance, JDBC connection pool at last.
* [mybatis/mybatis-3](https://github.com/mybatis/mybatis-3) - MyBatis SQL mapper framework for Java
* [redis/jedis](https://github.com/redis/jedis) - Redis Java client
* [flyway/flyway](https://github.com/flyway/flyway) - Flyway by Redgate • Database Migrations Made Easy.
* [jOOQ/jOOQ](https://github.com/jOOQ/jOOQ) - jOOQ is the best way to write SQL in Java
* [hibernate/hibernate-orm](https://github.com/hibernate/hibernate-orm) - Idiomatic persistence for Java and relational databases
* [JSQLParser/JSqlParser](https://github.com/JSQLParser/JSqlParser) - JSqlParser parses an SQL statement and translate it into a hierarchy of Java classes. The generated hierarchy can be navigated using the Visitor Pattern
* [redis/lettuce](https://github.com/redis/lettuce) - Advanced Java Redis client for thread-safe sync, async, and reactive usage. Supports Cluster, Sentinel, Pipelining, and codecs.
* [liquibase/liquibase](https://github.com/liquibase/liquibase) - Main Liquibase Source
* [querydsl/querydsl](https://github.com/querydsl/querydsl) - Unified Queries for Java
* [mybatis/spring-boot-starter](https://github.com/mybatis/spring-boot-starter) - MyBatis integration with Spring Boot
* [xerial/sqlite-jdbc](https://github.com/xerial/sqlite-jdbc) - SQLite JDBC Driver
* [spring-projects/spring-data-jpa](https://github.com/spring-projects/spring-data-jpa) - Simplifies the development of creating a JPA-based data access layer.
* [requery/requery](https://github.com/requery/requery) - requery - modern SQL based query & persistence for Java / Kotlin / Android
* [spring-projects/spring-data-elasticsearch](https://github.com/spring-projects/spring-data-elasticsearch) - Provide support to increase developer productivity in Java when using Elasticsearch. Uses familiar Spring concepts such as a template classes for core API usage and lightweight repository style data access.
* [mybatis/spring](https://github.com/mybatis/spring) - Spring integration for MyBatis 3
* [vladmihalcea/hypersistence-utils](https://github.com/vladmihalcea/hypersistence-utils) - The Hypersistence Utils library (previously known as Hibernate Types) gives you Spring and Hibernate utilities that can help you get the most out of your data access layer.
* [mybatis-flex/mybatis-flex](https://github.com/mybatis-flex/mybatis-flex) - mybatis-flex is an elegant Mybatis Enhancement Framework
* [mongodb/mongo-java-driver](https://github.com/mongodb/mongo-java-driver) - The official MongoDB drivers for Java, Kotlin, and Scala
* [shyiko/mysql-binlog-connector-java](https://github.com/shyiko/mysql-binlog-connector-java) - MySQL Binary Log connector
* [p6spy/p6spy](https://github.com/p6spy/p6spy) - P6Spy is a framework that enables database data to be seamlessly intercepted and logged with no code changes to the application.
* [jdbi/jdbi](https://github.com/jdbi/jdbi) - The Jdbi library provides convenient, idiomatic access to relational databases in Java and other JVM technologies such as Kotlin, Clojure or Scala.
* [speedment/speedment](https://github.com/speedment/speedment) - Speedment is a Stream ORM Java Toolkit and Runtime
* [spring-projects/spring-data-redis](https://github.com/spring-projects/spring-data-redis) - Provides support to increase developer productivity in Java when using Redis, a key-value store. Uses familiar Spring concepts such as a template classes for core API usage and lightweight repository style data access.
* [schemacrawler/SchemaCrawler](https://github.com/schemacrawler/SchemaCrawler) - Free database schema discovery and comprehension tool
* [pgjdbc/pgjdbc](https://github.com/pgjdbc/pgjdbc) - Postgresql JDBC Driver
* [spring-projects/spring-data-mongodb](https://github.com/spring-projects/spring-data-mongodb) - Provides support to increase developer productivity in Java when using MongoDB. Uses familiar Spring concepts such as a template classes for core API usage and lightweight repository style data access.
* [MorphiaOrg/morphia](https://github.com/MorphiaOrg/morphia) - MongoDB object-document mapper in Java based on https://github.com/mongodb/mongo-java-driver
* [ClickHouse/clickhouse-java](https://github.com/ClickHouse/clickhouse-java) - ClickHouse Java Clients & JDBC Driver
* [j256/ormlite-android](https://github.com/j256/ormlite-android) - ORMLite Android functionality used in conjunction with ormlite-core
* [ebean-orm/ebean](https://github.com/ebean-orm/ebean) - Ebean ORM
* [tobato/FastDFS_Client](https://github.com/tobato/FastDFS_Client) - Java Client for FastDFS

### Serialization and Formats

* [alibaba/easyexcel](https://github.com/alibaba/easyexcel) - 快速、简洁、解决大文件内存溢出的java处理Excel工具 *(archived)*
* [alibaba/fastjson](https://github.com/alibaba/fastjson) - FASTJSON 2.0.x has been released, faster and more secure, recommend you upgrade. *(archived)*
* [google/gson](https://github.com/google/gson) - A Java serialization/deserialization library to convert Java Objects into JSON and back
* [json-path/JsonPath](https://github.com/json-path/JsonPath) - Java JsonPath implementation
* [joelittlejohn/jsonschema2pojo](https://github.com/joelittlejohn/jsonschema2pojo) - Generate Java types from JSON or JSON Schema and annotate those types for data-binding with Jackson, Gson, etc
* [apache/fesod](https://github.com/apache/fesod) - Fast. Easy. Done. Processing spreadsheets without worrying about large files causing OOM.
* [stleary/JSON-java](https://github.com/stleary/JSON-java) - A reference implementation of a JSON package in Java.
* [apache/fory](https://github.com/apache/fory) - A blazingly fast multi-language serialization framework for idiomatic domain objects, schema IDL, and cross-language data exchange.
* [alibaba/fastjson2](https://github.com/alibaba/fastjson2) - 🚄 FASTJSON2 is a Java JSON library with excellent performance.
* [aeron-io/simple-binary-encoding](https://github.com/aeron-io/simple-binary-encoding) - Simple Binary Encoding (SBE) - High Performance Message Codec
* [apache/avro](https://github.com/apache/avro) - Apache Avro is a data serialization system.
* [apache/parquet-java](https://github.com/apache/parquet-java) - Apache Parquet Java
* [apache/parquet-format](https://github.com/apache/parquet-format) - Apache Parquet Format
* [apache/poi](https://github.com/apache/poi) - Mirror of Apache POI gitbox. The Java API for Microsoft Documents.
* [protostuff/protostuff](https://github.com/protostuff/protostuff) - Java serialization library, proto compiler, code generator
* [bazaarvoice/jolt](https://github.com/bazaarvoice/jolt) - JSON to JSON transformation library written in Java.
* [java-json-tools/json-schema-validator](https://github.com/java-json-tools/json-schema-validator) - A JSON Schema validation implementation in pure Java, which aims for correctness and performance, in that order
* [RuedigerMoeller/fast-serialization](https://github.com/RuedigerMoeller/fast-serialization) - FST: fast java serialization drop in-replacement
* [json-iterator/java](https://github.com/json-iterator/java) - jsoniter (json-iterator) is fast and flexible JSON parser available in Java and Go
* [msgpack/msgpack-java](https://github.com/msgpack/msgpack-java) - MessagePack serializer implementation for Java / msgpack.org[Java]

### Caching and Queues

* [apache/kafka](https://github.com/apache/kafka) - Apache Kafka - A distributed event streaming platform
* [apache/rocketmq](https://github.com/apache/rocketmq) - Apache RocketMQ is a cloud native messaging and streaming platform, making it simple to build event-driven applications.
* [ben-manes/caffeine](https://github.com/ben-manes/caffeine) - A high performance caching library for Java
* [sohutv/cachecloud](https://github.com/sohutv/cachecloud) - 搜狐视频(sohu tv)Redis私有云平台 ：支持Redis多种架构(Standalone、Sentinel、Cluster)高效管理、有效降低大规模redis运维成本，提升资源管控能力和利用率。平台提供快速搭建/迁移，运维管理，弹性伸缩，统计监控，客户端整合接入等功能。(CacheCloud is a Redis cloud management platform. It supports Standalone, Sentinel, and Cluster architectures for Redis, effectively reducing large-scale Redis operation and maintenance costs, and improving resource management and utilization. The platform provides rapid construction/migration, operation and maintenance management, elastic scaling, statistical monitoring, client integration and access and other functions)
* [hazelcast/hazelcast](https://github.com/hazelcast/hazelcast) - Hazelcast is a unified real-time data platform combining stream processing with a fast data store, allowing customers to act instantly on data-in-motion for real-time insights.
* [JakeWharton/DiskLruCache](https://github.com/JakeWharton/DiskLruCache) - Java implementation of a Disk-based LRU cache which specifically targets Android compatibility. *(archived)*
* [alibaba/jetcache](https://github.com/alibaba/jetcache) - JetCache is a Java cache framework.
* [OpenHFT/Chronicle-Queue](https://github.com/OpenHFT/Chronicle-Queue) - Micro second messaging that stores everything to disk
* [yangfuhai/ASimpleCache](https://github.com/yangfuhai/ASimpleCache) - a simple cache for android and java
* [jobrunr/jobrunr](https://github.com/jobrunr/jobrunr) - An extremely easy way to perform background processing in Java. Backed by persistent storage. Open and free for commercial use.
* [apache/activemq](https://github.com/apache/activemq) - Apache ActiveMQ
* [moquette-io/moquette](https://github.com/moquette-io/moquette) - Java MQTT lightweight broker
* [square/tape](https://github.com/square/tape) - A lightning fast, transactional, file-based FIFO for Android and Java. *(archived)*
* [VictorAlbertos/RxCache](https://github.com/VictorAlbertos/RxCache) - Reactive caching library for Android and Java *(archived)*
* [sohutv/mqcloud](https://github.com/sohutv/mqcloud) - RocketMQ企业级一站式服务平台
* [qiujiayu/AutoLoadCache](https://github.com/qiujiayu/AutoLoadCache) - AutoLoadCache 是基于AOP+Annotation等技术实现的高效的缓存管理解决方案，实现缓存与业务逻辑的解耦，并增加异步刷新及“拿来主义机制”，以适应高并发环境下的使用。

### Search and Indexing

* [elastic/elasticsearch](https://github.com/elastic/elasticsearch) - Free and Open Source, Distributed, RESTful Search Engine
* [infinilabs/analysis-ik](https://github.com/infinilabs/analysis-ik) - 🚌 The IK Analysis plugin integrates Lucene IK analyzer into Elasticsearch and OpenSearch, support customized dictionary.
* [opensearch-project/OpenSearch](https://github.com/opensearch-project/OpenSearch) - 🔎 Open source distributed and RESTful search engine.
* [vespa-engine/vespa](https://github.com/vespa-engine/vespa) - The AI search platform
* [oracle/opengrok](https://github.com/oracle/opengrok) - OpenGrok is a fast and usable source code search and cross reference engine, written in Java
* [apache/lucene](https://github.com/apache/lucene) - Apache Lucene open-source search software
* [komoot/photon](https://github.com/komoot/photon) - an open source geocoder for openstreetmap data
* [searchbox-io/Jest](https://github.com/searchbox-io/Jest) - Elasticsearch Java Rest Client. *(archived)*
* [MarginaliaSearch/MarginaliaSearch](https://github.com/MarginaliaSearch/MarginaliaSearch) - Internet search engine for text-oriented websites. Indexing the small, old and weird web.
* [datastax/jvector](https://github.com/datastax/jvector) - JVector: the most advanced embedded vector search engine

## Machine Learning and AI

### LLM and Inference

* [langchain4j/langchain4j](https://github.com/langchain4j/langchain4j) - LangChain4j is an idiomatic, open-source Java library for building LLM-powered applications on the JVM. It offers a unified API over popular LLM providers and vector stores, and makes implementing tool calling (including MCP support), agents and RAG easy. It integrates seamlessly with enterprise Java frameworks like Quarkus and Spring Boot.
* [alibaba/spring-ai-alibaba](https://github.com/alibaba/spring-ai-alibaba) - Agentic AI Framework for Java Developers
* [spring-projects/spring-ai](https://github.com/spring-projects/spring-ai) - An Application Framework for AI Engineering
* [agentscope-ai/agentscope-java](https://github.com/agentscope-ai/agentscope-java) - Build distributed, production-grade, long-running agents.
* [TheoKanning/openai-java](https://github.com/TheoKanning/openai-java) - OpenAI Api Client in Java *(archived)*
* [Atmosphere/atmosphere](https://github.com/Atmosphere/atmosphere) - Portable AI agent runtime for the JVM. One @Agent class runs on Spring AI, LangChain4j, Anthropic, or 9 more behind one SPI. Token streaming, tool calls, human approvals, and governance over WebSocket, SSE, gRPC, or WebTransport/HTTP3. Speaks MCP, A2A, and AG-UI.
* [modelcontextprotocol/java-sdk](https://github.com/modelcontextprotocol/java-sdk) - The official Java SDK for Model Context Protocol servers and clients. Maintained in collaboration with Spring AI
* [PlexPt/chatgpt-java](https://github.com/PlexPt/chatgpt-java) - ChatGPT Java SDK。支持 GPT-4o、 GPT-5 API。开箱即用。An unofficial Java SDK for seamless integration with ChatGPT's GPT-5 and GPT-4 APIs. Ready-to-use, simple setup, and efficient for building AI-powered applications.
* [Grt1228/chatgpt-java](https://github.com/Grt1228/chatgpt-java) - ChatGPT Java SDK支持流式输出、Gpt插件、联网。支持OpenAI官方所有接口。ChatGPT的Java客户端。OpenAI GPT-3.5-Turb GPT-4 Api Client for Java
* [teaql/teaql-agent-kit](https://github.com/teaql/teaql-agent-kit) - A model-mediated harness for reliable agentic software development.
* [hncboy/ai-beehive](https://github.com/hncboy/ai-beehive) - AI 蜂巢，基于 Java 使用 Spring Boot 3 和 JDK 17，支持的功能有 ChatGPT、OpenAi Image、Midjourney、NewBing、文心一言等等
* [ModelEngine-Group/fit-framework](https://github.com/ModelEngine-Group/fit-framework) - FIT: 企业级AI开发框架，提供多语言函数引擎（FIT）、流式编排引擎（WaterFlow）及Java生态的LangChain替代方案（FEL）。原生/Spring双模运行，支持插件热插拔与智能聚散部署，无缝统一大模型与业务系统。

### Machine Learning Frameworks

* [deeplearning4j/deeplearning4j](https://github.com/deeplearning4j/deeplearning4j) - Suite of tools for deploying and training deep learning models using the JVM. Highlights include model import for keras, tensorflow, and onnx/pytorch, a modular and tiny c++ library for running math code and a java based math library on top of the core c++ library. Also includes samediff: a pytorch/tensorflow like library for running deep learn...
* [deepjavalibrary/djl](https://github.com/deepjavalibrary/djl) - An Engine-Agnostic Deep Learning Framework in Java
* [guoguibing/librec](https://github.com/guoguibing/librec) - LibRec: A Leading Java Library for Recommender Systems, see
* [yusugomori/DeepLearning](https://github.com/yusugomori/DeepLearning) - Deep Learning (Python, C, C++, Java, Scala, Go)
* [apache/mahout](https://github.com/apache/mahout) - Apache Mahout - an environment for quickly creating scalable, performant machine learning applications.
* [OryxProject/oryx](https://github.com/OryxProject/oryx) - Oryx 2: Lambda architecture on Apache Spark, Apache Kafka for real-time large scale machine learning *(archived)*
* [SeldonIO/seldon-server](https://github.com/SeldonIO/seldon-server) - Machine Learning Platform and Recommendation Engine built on Kubernetes

### Natural Language Processing

* [stanfordnlp/CoreNLP](https://github.com/stanfordnlp/CoreNLP) - CoreNLP: A Java suite of core NLP tools for tokenization, sentence segmentation, NER, parsing, coreference, sentiment analysis, etc.
* [NLPchina/ansj_seg](https://github.com/NLPchina/ansj_seg) - ansj分词.ict的真正java实现.分词效果速度都超过开源版的ict. 中文分词,人名识别,词性标注,用户自定义词典
* [huaban/jieba-analysis](https://github.com/huaban/jieba-analysis) - 结巴分词(java版)
* [FudanNLP/fnlp](https://github.com/FudanNLP/fnlp) - 中文自然语言处理工具包 Toolkit for Chinese natural language processing
* [marytts/marytts](https://github.com/marytts/marytts) - MARY TTS -- an open-source, multilingual text-to-speech synthesis system written in pure java
* [ysc/QuestionAnsweringSystem](https://github.com/ysc/QuestionAnsweringSystem) - QuestionAnsweringSystem是一个Java实现的人机问答系统，能够自动分析问题并给出候选答案。
* [ysc/word](https://github.com/ysc/word) - Java分布式中文分词组件 - word分词
* [NLPchina/nlp-lang](https://github.com/NLPchina/nlp-lang) - 这个项目是一个基本包.封装了大多数nlp项目中常用工具
* [cmusphinx/sphinx4](https://github.com/cmusphinx/sphinx4) - Pure Java speech recognition library

### Data Science and Analytics

* [apache/flink](https://github.com/apache/flink) - Apache Flink
* [airbytehq/airbyte](https://github.com/airbytehq/airbyte) - Open-source data movement for ELT pipelines and AI agents — from APIs, databases & files to warehouses, lakes, and AI applications. Both self-hosted and Cloud.
* [elastic/logstash](https://github.com/elastic/logstash) - Logstash - transport and process your logs, events, or other data
* [OpenRefine/OpenRefine](https://github.com/OpenRefine/OpenRefine) - OpenRefine is a free, open source power tool for working with messy data and improving it
* [apache/beam](https://github.com/apache/beam) - Apache Beam is a unified programming model for Batch and Streaming data processing.
* [jeecgboot/jimureport](https://github.com/jeecgboot/jimureport) - 一款真正的 AI 报表诞生了！JimuChatBI —— 首款免费开源对话式智能数据分析产品（Chat2BI）。 一句话生成报表和数据大屏，支持对话式 AI 修改优化；类 Excel 在线报表设计，兼容国产信创数据源。 对着 AI 说句话，报表就出来了——表格、图表、分组汇总自动生成，复杂报表场景轻松应对。想做数据大屏？同样一句话搞定，让数据分析进入 AI 时代。
* [apache/zeppelin](https://github.com/apache/zeppelin) - Web-based notebook that enables data-driven, interactive data analytics and collaborative documents with SQL, Scala and more.
* [apache/nifi](https://github.com/apache/nifi) - Apache NiFi
* [SPLWare/esProc](https://github.com/SPLWare/esProc) - esProc SPL is a JVM-based programming language designed for structured data computation, serving as both a data analysis tool and an embedded computing engine.
* [DTStack/chunjun](https://github.com/DTStack/chunjun) - A data integration framework
* [Netflix/maestro](https://github.com/Netflix/maestro) - Maestro: Netflix’s Workflow Orchestrator
* [jtablesaw/tablesaw](https://github.com/jtablesaw/tablesaw) - Java dataframe and visualization library
* [apache/linkis](https://github.com/apache/linkis) - Apache Linkis builds a computation middleware layer to facilitate connection, governance and orchestration between the upper applications and the underlying data engines.
* [spring-projects/spring-batch](https://github.com/spring-projects/spring-batch) - Spring Batch is a framework for writing batch applications using Java and Spring
* [apache/logging-flume](https://github.com/apache/logging-flume) - Apache Flume is a distributed, reliable, and available service for efficiently collecting, aggregating, and moving large amounts of log-like data
* [apache/sedona](https://github.com/apache/sedona) - A cluster computing framework for processing large-scale geospatial data
* [youseries/ureport](https://github.com/youseries/ureport) - UReport2 is a high-performance pure Java report engine based on Spring architecture, where complex Chinese-style statements and reports can be prepared by iterating over cells.
* [apache/atlas](https://github.com/apache/atlas) - Apache Atlas - Open Metadata Management and Governance capabilities across the Hadoop platform and beyond
* [Netflix/genie](https://github.com/Netflix/genie) - Distributed Big Data Orchestration Service
* [xianrendzw/EasyReport](https://github.com/xianrendzw/EasyReport) - A simple and easy to use Web Report System for java.EasyReport是一个简单易用的Web报表工具(支持Hadoop,HBase及各种关系型数据库),它的主要功能是把SQL语句查询出的行列结构转换成HTML表格(Table)，并支持表格的跨行(RowSpan)与跨列(ColSpan)。同时它还支持报表Excel导出、图表显示及固定表头与左边列的功能。
* [knowm/XChart](https://github.com/knowm/XChart) - XChart is a light-weight Java library for plotting data.

## Networking and Distributed

### Networking

* [lionsoul2014/ip2region](https://github.com/lionsoul2014/ip2region) - Ip2region is an offline IP-to-Region localization library and IP data management framework with both IPv4 and IPv6 supports, 10-microsecond level query efficiency, xdb search client for many programming languages
* [TooTallNate/Java-WebSocket](https://github.com/TooTallNate/Java-WebSocket) - A barebones WebSocket client and server implementation written in 100% Java.
* [aeron-io/aeron](https://github.com/aeron-io/aeron) - Efficient reliable UDP unicast, UDP multicast, and IPC message transport
* [mrniko/netty-socketio](https://github.com/mrniko/netty-socketio) - Socket.IO server implemented on Java. Realtime java framework
* [ffay/lanproxy](https://github.com/ffay/lanproxy) - lanproxy是一个将局域网个人电脑、服务器代理到公网的内网穿透工具，支持tcp流量转发，可支持任何tcp上层协议（访问内网网站、本地支付接口调试、ssh访问、远程桌面、http代理、https代理、socks5代理...）。技术交流QQ群 736294209
* [socketio/socket.io-client-java](https://github.com/socketio/socket.io-client-java) - Full-featured Socket.IO Client Library for Java, which is compatible with Socket.IO v1.0 and later.
* [igniterealtime/Openfire](https://github.com/igniterealtime/Openfire) - An XMPP server licensed under the Open Source Apache License.
* [i2p/i2p.i2p](https://github.com/i2p/i2p.i2p) - I2P is an anonymizing network, offering a simple layer that identity-sensitive applications can use to securely communicate. All data is wrapped with several layers of encryption, and the network is both distributed and dynamic, with no trusted parties.
* [hierynomus/sshj](https://github.com/hierynomus/sshj) - ssh, scp and sftp for java
* [igniterealtime/Smack](https://github.com/igniterealtime/Smack) - A modular and portable open source XMPP client library written in Java for Android and Java (SE) VMs
* [TakahikoKawasaki/nv-websocket-client](https://github.com/TakahikoKawasaki/nv-websocket-client) - High-quality WebSocket client implementation in Java.
* [turms-im/turms](https://github.com/turms-im/turms) - 🕊️ The world's most advanced open source instant messaging engine for 100K~10M concurrent users https://turms-im.github.io/docs
* [EsotericSoftware/kryonet](https://github.com/EsotericSoftware/kryonet) - TCP/UDP client/server library for Java, based on Kryo
* [tywo45/t-io](https://github.com/tywo45/t-io) - T-io is a network programming framework developed based on Java AIO. From the collected cases, t-io is widely used for IoT, IM, and customer service, making it a top-notch network programming framework
* [4thline/cling](https://github.com/4thline/cling) - UPnP/DLNA library for Java and Android
* [crossbario/autobahn-java](https://github.com/crossbario/autobahn-java) - WebSocket & WAMP in Java for Android and Java 8
* [mpetazzoni/ttorrent](https://github.com/mpetazzoni/ttorrent) - BitTorrent Java library with tracker and download client

### RPC and Messaging

* [apache/dubbo](https://github.com/apache/dubbo) - The java implementation of Apache Dubbo. An RPC and microservice framework.
* [greenrobot/EventBus](https://github.com/greenrobot/EventBus) - Event bus for Android and Java that simplifies communication between Activities, Fragments, Threads, Services, etc. Less code, better quality.
* [grpc/grpc-java](https://github.com/grpc/grpc-java) - The Java gRPC implementation. HTTP/2 based RPC
* [apache/camel](https://github.com/apache/camel) - Apache Camel is an open source integration framework with 350+ connectors. Write routes in Java, YAML, or XML. Run on Spring Boot, Quarkus, or standalone. Apache License 2.0.
* [sofastack/sofa-rpc](https://github.com/sofastack/sofa-rpc) - SOFARPC is a high-performance, high-extensibility, production-level Java RPC framework.
* [mpusher/mpush](https://github.com/mpusher/mpush) - MPush开源实时消息推送系统
* [grpc-ecosystem/grpc-spring](https://github.com/grpc-ecosystem/grpc-spring) - Spring Boot starter module for gRPC framework.
* [AxonIQ/AxonFramework](https://github.com/AxonIQ/AxonFramework) - Framework for Evolutionary Message-Driven Microservices on the JVM
* [Tencent/spring-cloud-tencent](https://github.com/Tencent/spring-cloud-tencent) - Spring Cloud Tencent is a Spring Cloud based Service Governance Framework provided by Tencent.
* [sofastack/sofa-bolt](https://github.com/sofastack/sofa-bolt) - SOFABolt is a lightweight, easy to use and high performance remoting framework based on Netty.
* [zeromq/jeromq](https://github.com/zeromq/jeromq) - JeroMQ is a pure Java implementation of the ZeroMQ messaging library, offering high-performance asynchronous messaging for distributed or concurrent applications.
* [rsocket/rsocket-java](https://github.com/rsocket/rsocket-java) - Java implementation of RSocket
* [eclipse-paho/paho.mqtt.java](https://github.com/eclipse-paho/paho.mqtt.java) - Eclipse Paho Java MQTT client library. Paho is an Eclipse IoT project.
* [LogNet/grpc-spring-boot-starter](https://github.com/LogNet/grpc-spring-boot-starter) - Spring Boot starter module for gRPC framework.
* [zfoo-project/zfoo](https://github.com/zfoo-project/zfoo) - 💡Extremely fast enterprise server framework, can be used in RPC, game server, web server.
* [apache/servicecomb-java-chassis](https://github.com/apache/servicecomb-java-chassis) - ServiceComb Java Chassis is a Software Development Kit (SDK) for rapid development of microservices in Java, providing service registration, service discovery, dynamic routing, and service management features
* [spring-projects/spring-integration](https://github.com/spring-projects/spring-integration) - Spring Integration provides an extension of the Spring programming model to support the well-known Enterprise Integration Patterns (EIP)
* [fengjiachun/Jupiter](https://github.com/fengjiachun/Jupiter) - Jupiter是一款性能非常不错的, 轻量级的分布式服务框架
* [yidongnan/grpc-spring-boot-starter](https://github.com/yidongnan/grpc-spring-boot-starter) - Spring Boot starter module for gRPC framework. *(archived)*

### Distributed Systems

* [alibaba/Sentinel](https://github.com/alibaba/Sentinel) - A powerful flow control component enabling reliability, resilience and monitoring for microservices. (面向云原生微服务的高可用流控防护组件)
* [apache/zookeeper](https://github.com/apache/zookeeper) - Apache ZooKeeper
* [apache/storm](https://github.com/apache/storm) - Apache Storm
* [changmingxie/tcc-transaction](https://github.com/changmingxie/tcc-transaction) - tcc-transaction是TCC型事务java实现
* [LFDT-web3j/web3j](https://github.com/LFDT-web3j/web3j) - Lightweight Java and Android library for integration with Ethereum clients
* [bitcoinj/bitcoinj](https://github.com/bitcoinj/bitcoinj) - A library for working with Bitcoin
* [tronprotocol/java-tron](https://github.com/tronprotocol/java-tron) - Java implementation of the Tron whitepaper
* [sofastack/sofa-jraft](https://github.com/sofastack/sofa-jraft) - A production-grade java implementation of RAFT consensus algorithm.
* [apache/curator](https://github.com/apache/curator) - Apache Curator
* [atomix/atomix](https://github.com/atomix/atomix) - A Kubernetes toolkit for building distributed applications using cloud native principles
* [ethereum/ethereumj](https://github.com/ethereum/ethereumj) - DEPRECATED! Java implementation of the Ethereum yellowpaper. For JSON-RPC and other client features check Ethereum Harmony *(archived)*
* [besu-eth/besu](https://github.com/besu-eth/besu) - An enterprise-grade Java-based, Apache 2.0 licensed Ethereum client https://github.com/besu-eth/besu/wiki

### Cloud and Infrastructure

* [jenkinsci/jenkins](https://github.com/jenkinsci/jenkins) - Jenkins automation server
* [GoogleContainerTools/jib](https://github.com/GoogleContainerTools/jib) - 🏗 Build container images for your Java applications.
* [aws/aws-sdk-java](https://github.com/aws/aws-sdk-java) - The official AWS SDK for Java 1.x (In Maintenance Mode, End-of-Life on 12/31/2025). The AWS SDK for Java 2.x is available here: https://github.com/aws/aws-sdk-java-v2/
* [kubernetes-client/java](https://github.com/kubernetes-client/java) - Official Java client library for kubernetes
* [fabric8io/kubernetes-client](https://github.com/fabric8io/kubernetes-client) - Java client for Kubernetes & OpenShift
* [spring-cloud/spring-cloud-kubernetes](https://github.com/spring-cloud/spring-cloud-kubernetes) - Kubernetes integration with Spring Cloud Discovery Client, Configuration, etc...
* [docker-java/docker-java](https://github.com/docker-java/docker-java) - Java Docker API Client
* [apache/cloudstack](https://github.com/apache/cloudstack) - Apache CloudStack is an opensource Infrastructure as a Service (IaaS) cloud computing platform
* [aws/aws-sdk-java-v2](https://github.com/aws/aws-sdk-java-v2) - The official AWS SDK for Java - Version 2
* [Azure/azure-sdk-for-java](https://github.com/Azure/azure-sdk-for-java) - This repository is for active development of the Azure SDK for Java. For consumers of the SDK we recommend visiting our public developer docs at https://docs.microsoft.com/java/azure/ or our versioned developer docs at https://azure.github.io/azure-sdk-for-java.
* [apache/ambari](https://github.com/apache/ambari) - Apache Ambari simplifies provisioning, managing, and monitoring of Apache Hadoop clusters.
* [spotify/helios](https://github.com/spotify/helios) - Docker container orchestration platform *(archived)*
* [googleapis/google-cloud-java](https://github.com/googleapis/google-cloud-java) - Google Cloud Client Library for Java
* [semicons/java_oci_manage](https://github.com/semicons/java_oci_manage) - Web SSH Smart Terminal for multi-cloud management (OCI / AWS / GCP / Azure / DO / SolusVM /VirtFusion), with cloud panel, Telegram bot, and Cloudflare integration — 面向多云管理的 Web SSH 智能终端，集成云管理面板、Telegram 机器人与Cloudflare
* [dromara/Jpom](https://github.com/dromara/Jpom) - 【dromara】🚀简而轻的低侵入式在线构建、自动部署、日常运维、项目监控软件
* [FlowCI/flow-core-x](https://github.com/FlowCI/flow-core-x) - Powerful and user-friendly CI/CD server with high availability, parallel processing, runner auto-scaling
* [aws/serverless-java-container](https://github.com/aws/serverless-java-container) - A Java wrapper to run Spring, Spring Boot, Jersey, and other apps inside AWS Lambda.
* [spotify/docker-client](https://github.com/spotify/docker-client) - INACTIVE: A simple docker client for the JVM *(archived)*
* [aliyun/aliyun-openapi-java-sdk](https://github.com/aliyun/aliyun-openapi-java-sdk) - The Alibaba Cloud V1.0 SDK will soon enter the Basic Security Maintenance phase and is no longer recommended for use. V2.0 SDK is available here: https://github.com/aliyun/alibabacloud-java-sdk

### Monitoring and Observability

* [dianping/cat](https://github.com/dianping/cat) - CAT 作为服务端项目基础组件，提供了 Java, C/C++, Node.js, Python, Go 等多语言客户端，已经在美团点评的基础架构中间件框架（MVC框架，RPC框架，数据库框架，缓存框架等，消息队列，配置系统等）深度集成，为美团点评各业务线提供系统丰富的性能指标、健康状况、实时告警等。
* [codecentric/spring-boot-admin](https://github.com/codecentric/spring-boot-admin) - Admin UI for administration of spring boot applications
* [dropwizard/metrics](https://github.com/dropwizard/metrics) - :chart_with_upwards_trend: Capturing JVM- and application-level metrics. So you know what's going on.
* [micrometer-metrics/micrometer](https://github.com/micrometer-metrics/micrometer) - An application observability facade for the most popular observability tools. Think SLF4J, but for observability.
* [LinShunKang/MyPerf4J](https://github.com/LinShunKang/MyPerf4J) - High performance Java APM. Powered by ASM. Try it. Test it. If you feel its better, use it.
* [prometheus/jmx_exporter](https://github.com/prometheus/jmx_exporter) - A process for collecting metrics using JMX MBeans for Prometheus consumption
* [javamelody/javamelody](https://github.com/javamelody/javamelody) - JavaMelody : monitoring of JavaEE applications
* [Qihoo360/ArgusAPM](https://github.com/Qihoo360/ArgusAPM) - Powerful, comprehensive (Android) application performance management platform. 360线上移动性能检测平台
* [open-telemetry/opentelemetry-java-instrumentation](https://github.com/open-telemetry/opentelemetry-java-instrumentation) - OpenTelemetry auto-instrumentation and instrumentation libraries for Java
* [open-telemetry/opentelemetry-java](https://github.com/open-telemetry/opentelemetry-java) - OpenTelemetry Java SDK
* [openzipkin/brave](https://github.com/openzipkin/brave) - Java distributed tracing implementation compatible with Zipkin backend services.
* [prometheus/client_java](https://github.com/prometheus/client_java) - Prometheus instrumentation library for JVM applications
* [spring-attic/spring-cloud-sleuth](https://github.com/spring-attic/spring-cloud-sleuth) - Distributed tracing for spring cloud *(archived)*
* [stagemonitor/stagemonitor](https://github.com/stagemonitor/stagemonitor) - an open source solution to application performance monitoring for java server applications *(archived)*
* [opentracing/opentracing-java](https://github.com/opentracing/opentracing-java) - OpenTracing API for Java. 🛑 This library is DEPRECATED! https://github.com/opentracing/specification/issues/163 *(archived)*
* [hawtio/hawtio](https://github.com/hawtio/hawtio) - Hawtio web console helps you manage your JVM stuff and stay cool!
* [yahoo/mysql_perf_analyzer](https://github.com/yahoo/mysql_perf_analyzer) - MySQL performance monitoring and analysis.

## User Interface

### Mobile

* [PhilJay/MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) - A powerful 🚀 Android chart view / graph view library, supporting line- bar- pie- radar- bubble- and candlestick charts as well as scaling, panning and animations.
* [microg/GmsCore](https://github.com/microg/GmsCore) - Free implementation of Play Services
* [Yalantis/uCrop](https://github.com/Yalantis/uCrop) - Image Cropping Library for Android
* [permissions-dispatcher/PermissionsDispatcher](https://github.com/permissions-dispatcher/PermissionsDispatcher) - A declarative API to handle Android runtime permissions.
* [androidannotations/androidannotations](https://github.com/androidannotations/androidannotations) - Fast Android Development. Easy maintainance. *(archived)*
* [happydog-intj/JsBridge](https://github.com/happydog-intj/JsBridge) - android java and javascript bridge, inspired by wechat webview jsbridge
* [roughike/BottomBar](https://github.com/roughike/BottomBar) - (Deprecated) A custom view component that mimics the new Material Design Bottom Navigation pattern.
* [florent37/MaterialViewPager](https://github.com/florent37/MaterialViewPager) - A Material Design ViewPager easy to use library *(archived)*
* [Bearded-Hen/Android-Bootstrap](https://github.com/Bearded-Hen/Android-Bootstrap) - Bootstrap style widgets for Android, with Glyph Icons
* [cymcsg/UltimateRecyclerView](https://github.com/cymcsg/UltimateRecyclerView) - A RecyclerView(advanced and flexible version of ListView in Android) with refreshing,loading more,animation and many other features.
* [rey5137/material](https://github.com/rey5137/material) - A library to bring fully animated Material Design components to pre-Lolipop Android. *(archived)*
* [prolificinteractive/material-calendarview](https://github.com/prolificinteractive/material-calendarview) - A Material design back port of Android's CalendarView
* [sockeqwe/mosby](https://github.com/sockeqwe/mosby) - A Model-View-Presenter / Model-View-Intent library for modern Android apps
* [facebookarchive/rebound](https://github.com/facebookarchive/rebound) - A Java library that models spring dynamics and adds real world physics to your app. *(archived)*
* [Yalantis/Side-Menu.Android](https://github.com/Yalantis/Side-Menu.Android) - Side menu with some categories to choose.
* [orhanobut/dialogplus](https://github.com/orhanobut/dialogplus) - Advanced dialog solution for android
* [Ramotion/folding-cell-android](https://github.com/Ramotion/folding-cell-android) - :octocat: 📃 FoldingCell is a material design expanding content cell inspired by folding paper material made by @Ramotion
* [Yalantis/Phoenix](https://github.com/Yalantis/Phoenix) - Phoenix Pull-to-Refresh
* [CameraKit/blurkit-android](https://github.com/CameraKit/blurkit-android) - The missing Android blurring library. Fast blur-behind layout that parallels iOS.
* [anggrayudi/android-hidden-api](https://github.com/anggrayudi/android-hidden-api) - A library that provides access to Android hidden APIs and internal resources.
* [johncarl81/parceler](https://github.com/johncarl81/parceler) - :package: Android Parcelables made easy through code generation.
* [chenBingX/SuperTextView](https://github.com/chenBingX/SuperTextView) - Hi，Developer，Welcome to use SuperTextView ！
* [ragunathjawahar/android-saripaar](https://github.com/ragunathjawahar/android-saripaar) - UI form validation library for Android
* [mxdldev/android-mvp-mvvm-flytour](https://github.com/mxdldev/android-mvp-mvvm-flytour) - 🔥🔥🔥 FlyTour是Android MVVM+MVP+Dagger2+Retrofit+RxJava+组件化+插件组成的双编码架构+双工程架构+双语言Android应用开发框架，通过不断的升级迭代该框架已经有了十个不同的版本，5.0之前工程架构采用gradle配置实现组件化，5.0之后的工程架构采用VirtualAPK实现了插件化，5.0之前采用Java编码实现，5.0之后采用Kotlin编码实现，编码架构由MVVM和MVP组成，工程架构和编码架构及编码语言开发者可根据自己具体的项目实际需求去决定选择使用，该框架是Android组件化、Android插件化、Android MVP架构、Android MVVM架构的集大成者，帮助你快速的搭建自己的App项目开发框架，以便把主要的精力放在自己的项目的业务功能实现上，另外在长期的工作实践中总结整理大量的实用工具类在项目lib_common组件的util包当中方便大家调用。
* [ZieIony/Carbon](https://github.com/ZieIony/Carbon) - Material Design implementation for Android 4.0+. Shadows, ripples, vectors, fonts, animations, widgets, rounded corners and more. *(archived)*
* [jasonross/Nuwa](https://github.com/jasonross/Nuwa) - Nuwa, pure java implementation, can hotfix your android application.
* [FinalTeam/RxGalleryFinal](https://github.com/FinalTeam/RxGalleryFinal) - 图片选择库，单选/多选、拍照、裁剪、压缩，自定义。包括视频选择和录制。
* [florent37/ExpectAnim](https://github.com/florent37/ExpectAnim) - Describe your animation and run ! *(archived)*
* [lizhangqu/CoreLink](https://github.com/lizhangqu/CoreLink) - Android 开发中的日常积累
* [Yalantis/GuillotineMenu-Android](https://github.com/Yalantis/GuillotineMenu-Android) - Neat library, that provides a simple way to implement guillotine-styled animation
* [Krupen/FabulousFilter](https://github.com/Krupen/FabulousFilter) - Android library to animate Floating Action Button to Bottom Sheet Dialog and vice-versa
* [r0adkll/Slidr](https://github.com/r0adkll/Slidr) - Easily add slide to dismiss functionality to an Activity *(archived)*
* [yingLanNull/ShadowImageView](https://github.com/yingLanNull/ShadowImageView) - 🔥可以根据图片内容变阴影颜色，更加细腻的阴影效果 It can change color according to the picture, more delicate shadow effect
* [akexorcist/round-corner-progress-bar](https://github.com/akexorcist/round-corner-progress-bar) - [Android] Round Corner Progress Bar Library for Android
* [Ramotion/paper-onboarding-android](https://github.com/Ramotion/paper-onboarding-android) - :octocat: PaperOnboarding is a material design slider made by @Ramotion
* [balysv/material-menu](https://github.com/balysv/material-menu) - [deprecated] Animations for Android L drawer, back, dismiss and check icons
* [balysv/material-ripple](https://github.com/balysv/material-ripple) - [deprecated] Android L Ripple effect wrapper for Views
* [Ramotion/cardslider-android](https://github.com/Ramotion/cardslider-android) - :octocat: 🃏 Cardslider is a material design UI controller that allows you to swipe through cards with pictures and accompanying descriptions.
* [Yalantis/Horizon](https://github.com/Yalantis/Horizon) - Horizon - Simple visual equaliser for Android
* [Zhaoss/WeiXinRecordedDemo](https://github.com/Zhaoss/WeiXinRecordedDemo) - 仿微信视频拍摄UI, 基于ffmpeg的视频录制编辑
* [steelkiwi/cropiwa](https://github.com/steelkiwi/cropiwa) - 📐 Configurable Custom Crop widget for Android
* [Yalantis/Euclid](https://github.com/Yalantis/Euclid) - User Profile Interface Animation
* [cymcsg/UltimateAndroid](https://github.com/cymcsg/UltimateAndroid) - UltimateAndroid is a rapid development framework for developing your apps
* [Ramotion/android-ui-animation-components-and-libraries](https://github.com/Ramotion/android-ui-animation-components-and-libraries) - Android UI libraries, components and animations by @ramotion
* [Muddz/StyleableToast](https://github.com/Muddz/StyleableToast) - Android library that takes the standard toast to the next level with many styling options. Works on all Android versions.
* [Ramotion/expanding-collection-android](https://github.com/Ramotion/expanding-collection-android) - :octocat: ExpandingCollection is a material design card peek/pop controller. Android UI Library made by @Ramotion
* [Yalantis/StarWars.Android](https://github.com/Yalantis/StarWars.Android) - This component implements transition animation to crumble view into tiny pieces.
* [Ramotion/circle-menu-android](https://github.com/Ramotion/circle-menu-android) - :octocat: ⭕️ CircleMenu is a simple, elegant UI menu with a circular layout and material design animations. Android UI library made by @Ramotion
* [jchambers/pushy](https://github.com/jchambers/pushy) - A Java library for sending APNs (iOS/macOS/Safari) push notifications
* [airbnb/AirMapView](https://github.com/airbnb/AirMapView) - A view abstraction to provide a map user interface with various underlying map providers
* [codenameone/CodenameOne](https://github.com/codenameone/CodenameOne) - Open-source framework for native apps from one Java codebase, with a custom-rendered UI you control across iOS, Android, desktop, web, and watches.
* [Ramotion/garland-view-android](https://github.com/Ramotion/garland-view-android) - :octocat: ≡ GarlandView seamlessly transitions between multiple lists of content. Made by @Ramotion
* [Yalantis/FlipViewPager.Draco](https://github.com/Yalantis/FlipViewPager.Draco) - This project aims to provide a working page flip implementation for usage in ListView.
* [notnoop/java-apns](https://github.com/notnoop/java-apns) - Java Apple Push Notification Service Provider
* [qdrzwd/VideoRecorder](https://github.com/qdrzwd/VideoRecorder) - android视频录制，模仿微视，支持按下录制、抬起暂停。进度条断点显示。
* [eschao/android-PageFlip](https://github.com/eschao/android-PageFlip) - 3D Style Page Flip on Android
* [liuguangqiang/SwipeBack](https://github.com/liuguangqiang/SwipeBack) - SwipeBack is an android library that can finish a activity by using gesture.
* [janheinrichmerker/material-intro](https://github.com/janheinrichmerker/material-intro) - A simple material design app intro with cool animations and a fluent API.
* [bravoborja/ReadMoreTextView](https://github.com/bravoborja/ReadMoreTextView) - A Custom TextView with trim text
* [iqiyi/Qigsaw](https://github.com/iqiyi/Qigsaw) - 🔥🔥Qigsaw ['tʃɪɡsɔ] is a dynamic modularization library which is based on Android App Bundles(Do not need Google Play Service). It supports dynamic delivery for split APKs without reinstalling the base one.
* [Yalantis/ToDoList](https://github.com/Yalantis/ToDoList) - Micro-Transitions for Smooth Android To-Do List Animations
* [devnied/EMV-NFC-Paycard-Enrollment](https://github.com/devnied/EMV-NFC-Paycard-Enrollment) - A Java library used to read and extract data from NFC EMV credit cards (Android/PCSC).
* [Yalantis/Taurus](https://github.com/Yalantis/Taurus) - A little more fun for the pull-to-refresh interaction.
* [majidgolshadi/Android-Download-Manager-Pro](https://github.com/majidgolshadi/Android-Download-Manager-Pro) - Android/Java download manager library help you to download files in parallel mechanism in some chunks.
* [wangjiegulu/WheelView](https://github.com/wangjiegulu/WheelView) - Android滚动选择控件
* [SundeepK/CompactCalendarView](https://github.com/SundeepK/CompactCalendarView) - An android library which provides a compact calendar view much like the one used in google calenders.
* [jrvansuita/MaterialAbout](https://github.com/jrvansuita/MaterialAbout) - 🔖 It's a material-design about screen to use on your Android apps. A developer profile and application information easy to integrate.
* [anvil-ui/anvil](https://github.com/anvil-ui/anvil) - Minimal UI library for Android inspired by React
* [Yalantis/pull-to-make-soup](https://github.com/Yalantis/pull-to-make-soup) - Custom animated pull-to-refresh that can be easily added to RecyclerView
* [mmin18/FlexLayout](https://github.com/mmin18/FlexLayout) - A powerful Android layout view that use java expression in layout params to describe relative positions.

### Applications and End User Tools

* [Stirling-Tools/Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF) - #1 PDF Application on GitHub that lets you edit PDFs on any device anywhere
* [macrozheng/mall](https://github.com/macrozheng/mall) - mall项目是一套电商系统，包括前台商城系统及后台管理系统，基于Spring Boot+MyBatis实现，采用Docker容器化部署。 前台商城系统包含首页门户、商品推荐、商品搜索、商品展示、购物车、订单流程、会员中心、客户服务、帮助中心等模块。 后台管理系统包含商品管理、订单管理、会员管理、促销管理、运营管理、内容管理、统计报表、财务管理、权限管理、设置等模块。
* [dbeaver/dbeaver](https://github.com/dbeaver/dbeaver) - Free universal database tool and SQL client
* [jeecgboot/JeecgBoot](https://github.com/jeecgboot/JeecgBoot) - 【低代码v2.0，一句话即可生成整个系统】企业级AI低代码平台，一键生成前后端代码甚至整个系统。 AI Skills 一句话画流程、设计表单、生成报表、大屏。内置 AI应用平台涵盖：AI聊天、知识库、流程编排、MCP插件等，兼容主流大模型。引领AI低代码「Skills 生成 → 在线配置 → 代码生成 → 手工合并->AI修改」开发模式，解决 Java 项目 90% 重复工作，提高效率又不失灵活。
* [yuliskov/SmartTube](https://github.com/yuliskov/SmartTube) - Browse media content with your own rules on Android TV
* [xiaojieonly/Ehviewer_CN_SXJ](https://github.com/xiaojieonly/Ehviewer_CN_SXJ) - ehviewer，用爱发电，快乐前行
* [thingsboard/thingsboard](https://github.com/thingsboard/thingsboard) - Open-source IoT Platform - Device management, data collection, processing and visualization.
* [cryptomator/cryptomator](https://github.com/cryptomator/cryptomator) - Cryptomator for Windows, macOS, and Linux: Secure client-side encryption for your cloud storage, ensuring privacy and control over your data.
* [kekingcn/kkFileView](https://github.com/kekingcn/kkFileView) - Universal File Online Preview Project based on Spring-Boot
* [xpipe-io/xpipe](https://github.com/xpipe-io/xpipe) - Access your entire server infrastructure from your local desktop
* [LawnchairLauncher/lawnchair](https://github.com/LawnchairLauncher/lawnchair) - No clever tagline needed.
* [macrozheng/mall-swarm](https://github.com/macrozheng/mall-swarm) - mall-swarm是一套微服务商城系统，采用了 Spring Cloud Alibaba、Spring Boot 3.5、Sa-Token、MyBatis、Elasticsearch、Docker、Kubernetes等核心技术，同时提供了基于Vue的管理后台方便快速搭建系统。mall-swarm在电商业务的基础集成了注册中心、配置中心、监控中心、网关等系统功能。
* [Team-xManager/xManager](https://github.com/Team-xManager/xManager) - Ad-Free, New Features & Freedom *(archived)*
* [ZCShou/GoGoGo](https://github.com/ZCShou/GoGoGo) - 一个基于 Android 调试 API + 百度地图实现的虚拟定位工具，并且同时实现了一个可以自由移动的摇杆
* [alibaba/ali-dbhub](https://github.com/alibaba/ali-dbhub) - 已迁移新仓库，此版本将不再维护 *(archived)*
* [traccar/traccar](https://github.com/traccar/traccar) - Open source GPS tracking platform - self-hosted or managed, 200+ device protocols
* [gephi/gephi](https://github.com/gephi/gephi) - Gephi - The Open Graph Viz Platform
* [jetlinks/jetlinks-community](https://github.com/jetlinks/jetlinks-community) - JetLinks 基于Java,Spring Boot ,WebFlux,Netty,Vert.x,Reactor等开发, 是一个全响应式的企业级物联网平台。支持统一物模型管理,多种设备,多种厂家,统一管理。统一设备连接管理,多协议适配(TCP,MQTT,UDP,CoAP,HTTP等),屏蔽网络编程复杂性,灵活接入不同厂家不同协议等设备。实时数据处理,设备告警,消息通知,数据转发。地理位置,数据可视化等。能帮助你快速建立物联网相关业务系统。
* [TeamAmaze/AmazeFileManager](https://github.com/TeamAmaze/AmazeFileManager) - Material design file manager for Android
* [gz-yami/mall4cloud](https://github.com/gz-yami/mall4cloud) - ⭐️⭐️⭐️微服务商城系统 springcloud微服务商城 小程序商城
* [jagrosh/MusicBot](https://github.com/jagrosh/MusicBot) - 🎶 A Discord music bot that's easy to set up and run yourself!
* [nextcloud/android](https://github.com/nextcloud/android) - 📱 Nextcloud Android app
* [Docile-Alligator/Infinity-For-Reddit](https://github.com/Docile-Alligator/Infinity-For-Reddit) - A Reddit client for Android
* [nICEnnnnnnnLee/BilibiliDown](https://github.com/nICEnnnnnnnLee/BilibiliDown) - (GUI-多平台支持) B站 哔哩哔哩 视频下载器。支持稍后再看、收藏夹、UP主视频批量下载|Bilibili Video Downloader 😳
* [gz-yami/mall4j](https://github.com/gz-yami/mall4j) - ⭐️⭐️⭐️ 电商商城 小程序电商商城系统 PC商城 H5商城 APP商城 Java商城 O2O商城 跨境商城
* [bisq-network/bisq](https://github.com/bisq-network/bisq) - A decentralized bitcoin exchange network
* [Aliucord/Aliucord](https://github.com/Aliucord/Aliucord) - A mod for the Discord Android App
* [JabRef/jabref](https://github.com/JabRef/jabref) - Desktop app for managing BibTeX and BibLaTeX (.bib) libraries
* [981011512/--](https://github.com/981011512/--) - 停车场系统源码，新能源充电桩系统，停车场小程序，智能停车，Parking system，【功能介绍】：①兼容市面上主流的多家相机，理论上兼容所有硬件，可灵活扩展，②相机识别后数据自动上传到云端并记录，校验相机唯一id和硬件序列号，防止非法数据录入，③用户手机查询停车记录详情可自主缴费(支持微信，支付宝，银行接口支付，支持每个停车场指定不同的商户进行收款)，支付后出场在免费时间内会自动抬杆。④支持app上查询附近停车场(导航，可用车位数，停车场费用，优惠券，评分，评论等)，可预约车位。⑤断电断网支持岗亭人员使用app可接管硬件进行停车记录的录入。 【技术架构】：后端开发语言java，框架oauth2+springboot2+dubble，数据库mysql/mongodb/redis，即时通讯底层框架netty4，安卓和ios均为原生开发，后台管理模板vue专业定制
* [saysky/ForestBlog](https://github.com/saysky/ForestBlog) - 一个简单漂亮的SSM(Spring+SpringMVC+Mybatis)博客系统
* [rememberber/WePush](https://github.com/rememberber/WePush) - 专注批量推送的小而美的工具，目前支持：模板消息-公众号、模板消息-小程序、微信客服消息、微信企业号/企业微信消息、阿里云短信、阿里大于模板短信 、腾讯云短信、云片网短信、E-Mail、HTTP请求、钉钉、华为云短信、百度云短信、又拍云短信、七牛云短信
* [torakiki/pdfsam](https://github.com/torakiki/pdfsam) - PDFsam, a desktop application to split, merge, mix, rotate PDF files and extract pages
* [jellyfin/jellyfin-androidtv](https://github.com/jellyfin/jellyfin-androidtv) - Android TV Client for Jellyfin
* [SplashCodes/JAViewer](https://github.com/SplashCodes/JAViewer) - 更优雅的驾车体验
* [geoserver/geoserver](https://github.com/geoserver/geoserver) - Official GeoServer repository
* [freeplane/freeplane](https://github.com/freeplane/freeplane) - Application for Mind Mapping, Knowledge Management, Project Management. Develop, organize and communicate your ideas and knowledge in the most effective way.
* [grimmory-tools/grimmory](https://github.com/grimmory-tools/grimmory) - A self-hosted library for your ebooks, comics, and audiobooks
* [jitsi/jitsi](https://github.com/jitsi/jitsi) - Jitsi is an audio/video and chat communicator that supports protocols such as SIP, XMPP/Jabber, IRC and many other useful features.
* [lilishop/lilishop](https://github.com/lilishop/lilishop) - Java 开源商城系统，基于 Spring Boot / Spring Cloud / Vue / Uniapp 的 B2B2C 多商户商城源码，支持小程序商城、微服务、分销、直播、秒杀、Docker 私有化部署。
* [syncthing/syncthing-android](https://github.com/syncthing/syncthing-android) - Wrapper of syncthing for Android. *(archived)*
* [bitcoin-wallet/bitcoin-wallet](https://github.com/bitcoin-wallet/bitcoin-wallet) - Bitcoin Wallet app for your Android device. Standalone Bitcoin node, no centralized backend required.
* [RipMeApp/ripme](https://github.com/RipMeApp/ripme) - Downloads albums from the web in bulk for archive purposes
* [portfolio-performance/portfolio](https://github.com/portfolio-performance/portfolio) - Track and evaluate the performance of your investment portfolio across stocks, cryptocurrencies, and other assets.
* [javahuang/SurveyKing](https://github.com/javahuang/SurveyKing) - One command to deploy a more powerful, self‑hosted alternative to SurveyMonkey.
* [shopizer-ecommerce/shopizer](https://github.com/shopizer-ecommerce/shopizer) - Shopizer java e-commerce software
* [Haleydu/Cimoc](https://github.com/Haleydu/Cimoc) - 漫画阅读器
* [ZHENFENG13/My-Blog](https://github.com/ZHENFENG13/My-Blog) - :palm_tree::octocat:A simple & beautiful blogging system implemented with spring-boot & thymeleaf & mybatis My Blog 是由 SpringBoot + Mybatis + Thymeleaf 等技术实现的 Java 博客系统，页面美观、功能齐全、部署简单及完善的代码，一定会给使用者无与伦比的体验
* [1024-lab/smart-admin](https://github.com/1024-lab/smart-admin) - SmartAdmin国内首个以「高质量代码」为核心，「简洁、高效、安全」快速开发平台；基于SpringBoot2/3 + Sa-Token + Mybatis-Plus 和 Vue3 + Vite5 + Ant Design Vue 4.x (同时支持JavaScript和TypeScript双版本)；满足国家三级等保要求、支持登录限制、接口数据国产加解密、高防SQL注入等一系列安全体系。
* [tchiotludo/akhq](https://github.com/tchiotludo/akhq) - Kafka GUI for Apache Kafka to manage topics, topics data, consumers group, schema registry, connect and more...
* [Athou/commafeed](https://github.com/Athou/commafeed) - Google Reader inspired self-hosted personal RSS reader.
* [bastillion-io/Bastillion](https://github.com/bastillion-io/Bastillion) - Bastillion gives you a clean, browser-based way to manage SSH access across all your systems—like a bastion host with a friendly dashboard.
* [wushuo894/ani-rss](https://github.com/wushuo894/ani-rss) - 基于RSS自动追番、订阅、下载、刮削、洗版
* [connectbot/connectbot](https://github.com/connectbot/connectbot) - ConnectBot is the first SSH client for Android.
* [AnySoftKeyboard/AnySoftKeyboard](https://github.com/AnySoftKeyboard/AnySoftKeyboard) - Android on screen keyboard for multiple languages and NO internet access
* [PlayEdu/PlayEdu](https://github.com/PlayEdu/PlayEdu) - 100%开源的企业培训系统，界面美观，操作简单，一键部署您的私有化培训平台！
* [Snailclimb/interview-guide](https://github.com/Snailclimb/interview-guide) - 基于 Spring Boot 4.1、Java 25、Spring AI 2.0、React、PostgreSQL/pgvector、Redis 和 RustFS 构建的开源 AI 面试平台，支持简历智能分析、模拟面试、语音面试和知识库 RAG。
* [vran-dev/PrettyZoo](https://github.com/vran-dev/PrettyZoo) - 😉 Pretty nice Zookeeper GUI, Support Win / Mac / Linux Platform *(archived)*
* [qaiu/netdisk-fast-download](https://github.com/qaiu/netdisk-fast-download) - 聚合多种主流网盘的直链解析下载服务, 一键解析下载，已支持夸克网盘/uc网盘/蓝奏云/蓝奏优享/小飞机盘/123云盘等. 支持文件夹分享解析. 体验地址: https://lz.qaiu.top https://189.qaiu.top
* [yangzongzhuan/RuoYi-Vue](https://github.com/yangzongzhuan/RuoYi-Vue) - :tada: (RuoYi)官方仓库 基于SpringBoot，Spring Security，JWT，Vue & Element 的前后端分离权限管理系统，同时提供了 Vue3 的版本
* [Wisser/Jailer](https://github.com/Wisser/Jailer) - Database Subsetting and Relational Data Browsing Tool.
* [itwanger/paicoding](https://github.com/itwanger/paicoding) - ⭐️一款好用又强大的开源社区，基于 Spring Boot、MyBatis-Plus、MySQL、Redis、ElasticSearch、MongoDB、Docker、RabbitMQ 等主流技术栈，附详细教程，包括Java、Spring、MySQL、Redis、微服务&分布式、消息队列等核心知识点。学编程，就上技术派😁。
* [crmeb/crmeb_java](https://github.com/crmeb/crmeb_java) - Java商城 免费 开源 CRMEB商城JAVA版，SpringBoot + Maven + Swagger + Mybatis Plus + Redis + Uniapp +Vue+elementUI 包含移动端、小程序、PC后台、Api接口；有产品、用户、购物车、订单、积分、优惠券、营销、余额、权限、角色、系统设置、组合数据、可拖拉拽的form表单等模块，大量的减少了二开的成本。
* [MewX/light-novel-library_Wenku8_Android](https://github.com/MewX/light-novel-library_Wenku8_Android) - [CASUALLY MAINTAINED] 轻小说文库 (Wenku8.com) 安卓版第三方公益App，始于2014年的初版Material Design风格、非盈利、Play Store上安装包最小的轻小说阅读器 (light novel reader)。目前网站的API由于被大量滥用，已更新成我自己架的 Cloudflare Worker API 中继节点，不然的话网站关闭API就全军覆没了。
* [88250/symphony](https://github.com/88250/symphony) - 🎶 一款用 Java 实现的现代化社区（论坛/问答/BBS/社交网络/博客）系统平台。A modern community (forum/Q&A/BBS/SNS/blog) system platform implemented in Java. https://ld246.com
* [cskefu/cskefu](https://github.com/cskefu/cskefu) - 🌲 春松客服，开源客服系统
* [federicoiosue/Omni-Notes](https://github.com/federicoiosue/Omni-Notes) - Open source note-taking application for Android
* [anonfaded/FadCam](https://github.com/anonfaded/FadCam) - Open-source, ad-free Android multimedia recorder with background video recording, screen recording, live streaming, and remote camera control
* [xuchengsheng/wx-dump-4j](https://github.com/xuchengsheng/wx-dump-4j) - 一款基于Java开发的微信数据分析工具。
* [paulpacifico/shutter-encoder](https://github.com/paulpacifico/shutter-encoder) - A professional video compression tool accessible to all, mostly based on FFmpeg.
* [karimknaebel/Phonograph](https://github.com/karimknaebel/Phonograph) - A material designed music player for Android *(archived)*
* [JsonChao/Awesome-WanAndroid](https://github.com/JsonChao/Awesome-WanAndroid) - :zap:致力于打造一款极致体验的 http://www.wanandroid.com/ 客户端，知识和美是可以并存的哦QAQn(*≧▽≦*)n
* [yzcheng90/x-springboot](https://github.com/yzcheng90/x-springboot) - X-SpringBoot是一个轻量级的Java快速开发平台，基于springboot3和jdk21，使用虚拟线程，可配置的SaaS功能具备RBAC功能、自动代码生成、多种存储系统，多种短信平台，可开放api授权。代码简洁，架构清晰，能快速开发项目并交付【接私活利器】
* [UniversalMediaServer/UniversalMediaServer](https://github.com/UniversalMediaServer/UniversalMediaServer) - A DLNA, UPnP and HTTP(S) Media Server.
* [risesoft-y9/Digital-Infrastructure](https://github.com/risesoft-y9/Digital-Infrastructure) - 数字底座是一款面向大型政府、企业数字化转型，基于身份认证、组织架构、岗位职务、应用系统、资源角色、数据目录、安全控制等功能构建的统一且安全的管理支撑平台。数字底座基于三员管理模式，具备微服务、多租户、容器化和国产化，支持用户利用代码生成器快速构建自己的业务应用，同时可关联诸多成熟且好用的内部生态应用。
* [mendhak/gpslogger](https://github.com/mendhak/gpslogger) - :satellite: Lightweight GPS Logging Application For Android.
* [Peergos/Peergos](https://github.com/Peergos/Peergos) - A p2p, secure file storage, social network and application protocol
* [apache/fineract](https://github.com/apache/fineract) - Apache Fineract
* [caoxinyu/RedisClient](https://github.com/caoxinyu/RedisClient) - Java Redis Client GUI Tool
* [WuKongOpenSource/WukongCRM-11.0-JAVA](https://github.com/WuKongOpenSource/WukongCRM-11.0-JAVA) - 悟空CRM-基于Spring Cloud Alibaba微服务架构 +vue ElementUI的前后端分离CRM系统
* [metasfresh/metasfresh](https://github.com/metasfresh/metasfresh) - We do Open Source ERP - Fast, Flexible & Free Software to scale your Business.
* [gitblit-org/gitblit](https://github.com/gitblit-org/gitblit) - pure java git solution
* [geogebra/geogebra](https://github.com/geogebra/geogebra) - GeoGebra apps (mirror)
* [hidroh/materialistic](https://github.com/hidroh/materialistic) - A material-design Hacker News Android reader
* [EXALAB/AnLinux-App](https://github.com/EXALAB/AnLinux-App) - AnLinux allow you to run Linux on Android without root access.
* [kerwincui/FastBee](https://github.com/kerwincui/FastBee) - FastBee开源物联网平台，简单易用，可用于搭建物联网平台以及二次开发和学习。适用于智能家居、智慧办公、智慧社区、农业监测、水利监测、工业控制等。
* [maliangnansheng/bbs-springboot](https://github.com/maliangnansheng/bbs-springboot) - 【南生论坛】- 开源Java论坛（社区/问答/BBS/社交网络/博客），仿掘金风格，技术架构采用SpringBoot + Vue，前后端分离，多端适配，界面优雅，功能全面，性能高效，企业级微服务开源项目。官网：https://bbs.nansin.top
* [winder/Universal-G-Code-Sender](https://github.com/winder/Universal-G-Code-Sender) - A cross-platform G-Code sender for GRBL, Smoothieware, TinyG and G2core.
* [julian-klode/dns66](https://github.com/julian-klode/dns66) - DNS-based Host Blocker (and lightweight ad blocker) for Android *(archived)*
* [864381832/xJavaFxTool](https://github.com/864381832/xJavaFxTool) - 基于JavaFx搭建的实用小工具集合，方便开发过程中的代码编写与调试，想学习javaFx的同学可以参考参考。其中包括文件复制、Cron表达式生成器、编码转换、加密解密、Time转换、路径转换、二维码生成工具、身份证生成器、正则表达式生成工具、网址缩短、转义字符、字符串转换、Mq调试工具、Http调试工具、json格式化编辑工具、图标生成工具、Redis连接工具、网页源码下载工具、切换Hosts工具、Ftp服务器、Cmd调试工具、Ftp/Ftps/Sftp客户端调试工具、Pdf转换工具、文件列表生成器、图片压缩工具、图片转码工具、Kafka调试工具、Email群发工具、颜色代码转换工具、短信群发工具、脚本引擎调试、文件重命名、Json转换、语音转换、Socket调试、图片解析、微信小程序反编译、Zookeeper操作、Excel拆分合并、文件夹监控、文件编码检测、传输、端口扫描、久坐提醒、随机数生成、剪贴板历史、文件搜索、mp3转换、印章生成等工具
* [avjinder/Minimal-Todo](https://github.com/avjinder/Minimal-Todo) - Material To-Do App
* [DSheirer/sdrtrunk](https://github.com/DSheirer/sdrtrunk) - A cross-platform java application for decoding, monitoring, recording and streaming trunked mobile and related radio protocols using Software Defined Radios (SDR). Website:
* [timusus/Shuttle](https://github.com/timusus/Shuttle) - Shuttle Music Player *(archived)*
* [fossasia/pslab-app](https://github.com/fossasia/pslab-app) - PSLab App for Android, iOS, desktop and web https://play.google.com/store/apps/details?id=io.pslab
* [ZongXR/SuperMarket](https://github.com/ZongXR/SuperMarket) - 设计精良的网上商城系统，包括前端、后端、数据库、负载均衡、数据库缓存、分库分表、读写分离、全文检索、消息队列等，使用SpringCloud框架，基于Java开发。该项目可部署到服务器上，不断完善中……
* [liyupi/sql-father-backend-public](https://github.com/liyupi/sql-father-backend-public) - 新项目：快速生成 SQL 和模拟数据的网站（Java 后端），大幅提高开发测试效率！by 程序员鱼皮
* [sanluan/PublicCMS](https://github.com/sanluan/PublicCMS) - More than 2.7 million lines of code modification continuously iterated for 9 years to modernize java cms, easily supporting tens of millions of data, tens of millions of PV; Support static, server side includes; Currently has 0.0005% of the world's users (w3techs provided data), language support in Chinese, Japanese, English
* [asciidocfx/AsciidocFX](https://github.com/asciidocfx/AsciidocFX) - Asciidoc Editor and Toolchain written with JavaFX 21 (Build PDF, Epub, Mobi and HTML books, documents and slides)
* [airsonic/airsonic](https://github.com/airsonic/airsonic) - :satellite: :cloud: :notes:Airsonic, a Free and Open Source community driven media server (fork of Subsonic and Libresonic) *(archived)*
* [670848654/SakuraAnime](https://github.com/670848654/SakuraAnime) - 使用jsoup爬取樱花动漫(Yhdm)、嘶哩嘶哩(SiliSili)部分内容编写的第三方Android客户端。 *(archived)*
* [rememberber/MooTool](https://github.com/rememberber/MooTool) - Handy tool set for developers
* [atjiu/pybbs](https://github.com/atjiu/pybbs) - 更实用的Java开发的社区(论坛)，Better use of Java development community (forum)
* [airsquared/blobsaver](https://github.com/airsquared/blobsaver) - A cross-platform GUI and CLI app for automatically saving SHSH blobs
* [FJ-OMS/oms-erp](https://github.com/FJ-OMS/oms-erp) - 一站式全渠道业务中台系统包括订单管理系统OMS/电商ERP、库存WMS统一管理系统和SAP财务管理系统等，实现快速部署，并帮助企业后续自主进行开发迭代，实现数字化转型，并有多个经典案例。中台系统包括：通用业务中台、强大的技术中台Springcloud/Istio、后续开发方案的设计，技术(K8S,SERVERLESS)及管理人员的培训等。
* [openmrs/openmrs-core](https://github.com/openmrs/openmrs-core) - OpenMRS API and web application code
* [jberkel/sms-backup-plus](https://github.com/jberkel/sms-backup-plus) - Backup Android SMS, MMS and call log to Gmail / Gcal / IMAP
* [kanwangzjm/funiture](https://github.com/kanwangzjm/funiture) - github: https://github.com/kanwangzjm/funiture, spring项目，权限管理、系统监控、定时任务动态调整、qps限制、sql监控(邮件)、验证码服务、短链接服务、动态配置等
* [TEAMMATES/teammates](https://github.com/TEAMMATES/teammates) - TEAMMATES is a feedback management tool for education
* [redsolution/xabber-android](https://github.com/redsolution/xabber-android) - Open-source XMPP client for Android
* [moxi624/mogu_blog_v2](https://github.com/moxi624/mogu_blog_v2) - 蘑菇博客(MoguBlog)，一个基于微服务架构的前后端分离博客系统。Web端使用Vue + Element , 移动端使用uniapp和ColorUI。后端使用Spring cloud + Spring boot + mybatis-plus进行开发，使用 Jwt + Spring Security做登录验证和权限校验，使用ElasticSearch和Solr作为全文检索服务，使用Github Actions完成博客的持续集成，使用ELK收集博客日志，文件支持上传七牛云和Minio，支持Docker Compose脚本一键部署。
* [wsk1103/Used-Trading-Platform](https://github.com/wsk1103/Used-Trading-Platform) - basice of SSM，基于Java的校园二手交易平台
* [88250/solo](https://github.com/88250/solo) - 🎸 B3log 分布式社区的 Java 博客端节点系统，欢迎加入下一代社区网络。B3log distributed community blog-end node based on Java, welcome to join the next generation community network.
* [Qbian61/forum-java](https://github.com/Qbian61/forum-java) - 一款用 Java（spring boot） 实现的现代化社区（论坛/问答/BBS/社交网络/博客）系统平台。A modern community (forum/Q&A/BBS/SNS/blog) system platform implemented in Java（spring boot）.
* [jammy928/CoinExchange_CryptoExchange_Java](https://github.com/jammy928/CoinExchange_CryptoExchange_Java) - The best Java open source crypto currency exchange platform, bitcoin exchange based on Java | BTC exchange | ETH exchange | digital currency exchange | trading platform | matching trading engine. This project is based on the development of Spring Cloud microservices and can be used to build and secondary development of digital currency exchanges. It has a complete source code for matching trading engines, back-end management (back-end + front-end), front-end (transaction page, activity page, personal center, etc.), Android APP source code, Apple APP source code, currency wallet RPC source code. Contact Email: 877070886@qq.com
* [klinker24/talon-twitter-holo](https://github.com/klinker24/talon-twitter-holo) - [Deprecated] The Holo version of my popular Android Talon for Twitter app, 100% open-source *(archived)*
* [iTXTech/Daedalus](https://github.com/iTXTech/Daedalus) - No root required Android DNS modifier and Hosts/DNSMasq resolver.
* [JaceyRx/Examination_System](https://github.com/JaceyRx/Examination_System) - 一个简单的教务查询系统（主要技术SpringMVC + Spring + Mybatis + Shiro + Bootstrap）
* [jiayaoO3O/18-comic-finder](https://github.com/jiayaoO3O/18-comic-finder) - 禁漫天堂Github Actions下载器🧘

## Graphics and Media

### Game Development

* [Anuken/Mindustry](https://github.com/Anuken/Mindustry) - The automation tower defense RTS
* [libgdx/libgdx](https://github.com/libgdx/libgdx) - Desktop/Android/HTML5/iOS Java game development framework
* [Grasscutters/Grasscutter](https://github.com/Grasscutters/Grasscutter) - A server software reimplementation for a certain anime game.
* [PaperMC/Paper](https://github.com/PaperMC/Paper) - The most widely used, high performance Minecraft server that aims to fix gameplay and mechanics inconsistencies
* [PojavLauncherTeam/PojavLauncher](https://github.com/PojavLauncherTeam/PojavLauncher) - A Minecraft: Java Edition Launcher for Android and iOS based on Boardwalk. Succeeded by https://github.com/AngelAuraMC/Amethyst-Android *(archived)*
* [cabaletta/baritone](https://github.com/cabaletta/baritone) - google maps for block game
* [MinecraftForge/MinecraftForge](https://github.com/MinecraftForge/MinecraftForge) - Modifications to the Minecraft base files to assist in compatibility between mods. New Discord: https://discord.minecraftforge.net/
* [00-Evan/shattered-pixel-dungeon](https://github.com/00-Evan/shattered-pixel-dungeon) - Shattered Pixel Dungeon is an open-source traditional roguelike dungeon crawler with randomized levels and enemies, and hundreds of items to collect and use. It's based on the source code of Pixel Dungeon, by Watabou.
* [GeyserMC/Geyser](https://github.com/GeyserMC/Geyser) - A bridge/proxy allowing you to connect to Minecraft: Java Edition servers with Minecraft: Bedrock Edition.
* [AlmasB/FXGL](https://github.com/AlmasB/FXGL) - Java / JavaFX / Kotlin Game Library (Engine)
* [FCL-Team/FoldCraftLauncher](https://github.com/FCL-Team/FoldCraftLauncher) - Fold Craft Launcher, an Android Minecraft : Java Edition launcher.
* [PaperMC/Folia](https://github.com/PaperMC/Folia) - Fork of Paper which adds regionised multithreading to the dedicated server.
* [jMonkeyEngine/jmonkeyengine](https://github.com/jMonkeyEngine/jmonkeyengine) - A complete 3-D game development suite written in Java.
* [MovingBlocks/Terasology](https://github.com/MovingBlocks/Terasology) - Terasology - open source voxel world
* [EngineHub/WorldEdit](https://github.com/EngineHub/WorldEdit) - 🗺️ Minecraft map editor and mod
* [Minestom/Minestom](https://github.com/Minestom/Minestom) - 26.2 Lightweight Minecraft server
* [FabricMC/fabric-api](https://github.com/FabricMC/fabric-api) - Essential hooks for modding with Fabric.
* [Card-Forge/forge](https://github.com/Card-Forge/forge) - An unofficial rules engine for the world's greatest card game.
* [PurpurMC/Purpur](https://github.com/PurpurMC/Purpur) - Purpur is a drop-in replacement for Paper servers designed for configurability, and new fun and exciting gameplay features.
* [magefree/mage](https://github.com/magefree/mage) - XMage - Magic Another Game Engine
* [EssentialsX/Essentials](https://github.com/EssentialsX/Essentials) - The modern Essentials suite for Spigot and Paper.
* [PaperMC/Velocity](https://github.com/PaperMC/Velocity) - The modern, next-generation Minecraft server proxy.
* [Pugmatt/BedrockConnect](https://github.com/Pugmatt/BedrockConnect) - Join any Minecraft Bedrock Edition server IP on Xbox One, Nintendo Switch, and PS4/PS5
* [IzzelAliz/Arclight](https://github.com/IzzelAliz/Arclight) - A Bukkit(1.20/1.21) server implementation in modding environment using Mixin. ⚡
* [neoforged/NeoForge](https://github.com/neoforged/NeoForge) - Neo Modding API for Minecraft: Java Edition, based on Forge
* [Luohuayu/CatServer](https://github.com/Luohuayu/CatServer) - 高性能和高兼容性的1.12.2/1.16.5/1.18.2版本Forge+Bukkit+Spigot服务端 (A high performance and high compatibility 1.12.2/1.16.5/1.18.2 version Forge+Bukkit+Spigot server)
* [GlowstoneMC/Glowstone](https://github.com/GlowstoneMC/Glowstone) - A fast, customizable and compatible open source server for Minecraft: Java Edition
* [AppliedEnergistics/Applied-Energistics-2](https://github.com/AppliedEnergistics/Applied-Energistics-2) - A Minecraft Mod about Matter, Energy and using them to conquer the world..
* [jwpttcg66/NettyGameServer](https://github.com/jwpttcg66/NettyGameServer) - 使用netty4.X实现的手机游戏分布式服务器,支持tcp,udp,http,websocket链接，采用protobuf自定义协议栈进行网络通信,支持rpc远程调用,使用mybatis3支持db存储分库分表，支持异步mysql存储，db保存时同步更新reids缓存。 使用ExcelToCode工程，将excel数据生成java类和json数据字典，DictService直接读取json，减少数据字典部分代码。使用game-executor工程，增加游戏内的异步事件全局服务, 支持事件sharding,均衡的异步执行事件逻辑

### Image and Video

* [zxing/zxing](https://github.com/zxing/zxing) - ZXing ("Zebra Crossing") barcode scanning library for Java, Android
* [google/ExoPlayer](https://github.com/google/ExoPlayer) - This project is deprecated and stale. The latest ExoPlayer code is available in https://github.com/androidx/media
* [wasabeef/glide-transformations](https://github.com/wasabeef/glide-transformations) - An Android transformation library providing a variety of image transformations for Glide.
* [wasabeef/android-gpuimage](https://github.com/wasabeef/android-gpuimage) - Android filters based on OpenGL (idea from GPUImage for iOS)
* [nayuki/QR-Code-generator](https://github.com/nayuki/QR-Code-generator) - High-quality QR Code generator library in Java, TypeScript/JavaScript, Python, Rust, C++, C.
* [wasabeef/Blurry](https://github.com/wasabeef/Blurry) - Blurry is an easy blur library for Android
* [coobird/thumbnailator](https://github.com/coobird/thumbnailator) - Thumbnailator - a thumbnail generation library for Java
* [fyhertz/libstreaming](https://github.com/fyhertz/libstreaming) - A solution for streaming H.264, H.263, AMR, AAC using RTP on Android
* [Red5/red5-server](https://github.com/Red5/red5-server) - Red5 Server core
* [cropsly/ffmpeg-android-java](https://github.com/cropsly/ffmpeg-android-java) - Android java library for FFmpeg binary compiled using https://github.com/writingminds/ffmpeg-android
* [pedroSG94/RootEncoder](https://github.com/pedroSG94/RootEncoder) - RootEncoder for Android (rtmp-rtsp-stream-client-java) is a stream encoder to push video/audio to media servers using protocols RTMP, RTSP, SRT and UDP with all code written in Java/Kotlin
* [androidx/media](https://github.com/androidx/media) - Jetpack Media3 support libraries for media use cases, including ExoPlayer, an extensible media player for Android
* [drewnoakes/metadata-extractor](https://github.com/drewnoakes/metadata-extractor) - Extracts Exif, IPTC, XMP, ICC and other metadata from image, video and audio files
* [sannies/mp4parser](https://github.com/sannies/mp4parser) - A Java API to read, write and create MP4 files
* [sarxos/webcam-capture](https://github.com/sarxos/webcam-capture) - The goal of this project is to allow integrated or USB-connected webcams to be accessed directly from Java. Using provided libraries users are able to read camera images and detect motion. Main project consist of several sub projects - the root one, which contains required classes, build-in webcam driver compatible with Windows, Linux and Mac OS, which can stream images as fast as your camera can serve them (up to 50 FPS). Main project can be used standalone, but user is able to replace build-in driver with different one - such as OpenIMAJ, GStreamer, V4L4j, JMF, LTI-CIVIL, FMJ, etc.
* [haraldk/TwelveMonkeys](https://github.com/haraldk/TwelveMonkeys) - TwelveMonkeys ImageIO: Additional plug-ins and extensions for Java's ImageIO
* [bramp/ffmpeg-cli-wrapper](https://github.com/bramp/ffmpeg-cli-wrapper) - Java wrapper around the FFmpeg command line tool
* [kenglxn/QRGen](https://github.com/kenglxn/QRGen) - a simple QRCode generation api for java built on top ZXING
* [qiujuer/ImageBlurring](https://github.com/qiujuer/ImageBlurring) - Android blurring image(bitmap) by java and jni.

## Security

### Security Tools

* [frohoff/ysoserial](https://github.com/frohoff/ysoserial) - A proof-of-concept tool for generating payloads that exploit unsafe Java object deserialization.
* [karma9874/AndroRAT](https://github.com/karma9874/AndroRAT) - A Simple android remote administration tool using sockets. It uses java on the client side and python on the server side
* [threedr3am/learnjavabug](https://github.com/threedr3am/learnjavabug) - Java安全相关的漏洞和技术demo，原生Java、Fastjson、Jackson、Hessian2、XML反序列化漏洞利用和Spring、Dubbo、Shiro、CAS、Tomcat、RMI、Nexus等框架\中间件\功能的exploits以及Java Security Manager绕过、Dubbo-Hessian2安全加固等等实践代码。
* [JoyChou93/java-sec-code](https://github.com/JoyChou93/java-sec-code) - Java web common vulnerabilities and security code which is base on springboot and spring security
* [find-sec-bugs/find-sec-bugs](https://github.com/find-sec-bugs/find-sec-bugs) - The SpotBugs plugin for security audits of Java web applications and Android applications. (Also work with Kotlin, Groovy and Scala projects)
* [pen4uin/java-memshell-generator](https://github.com/pen4uin/java-memshell-generator) - 一款支持自定义的 Java 内存马生成工具｜A customizable Java in-memory webshell generation tool.
* [0Chencc/CTFCrackTools](https://github.com/0Chencc/CTFCrackTools) - The next-generation CTF Swiss Army Knife powered by Rust & Tauri. Features a visual node-based workflow and local AI intelligence for extreme performance and automation.China's first CTFTools framework.
* [sleeyax/burp-awesome-tls](https://github.com/sleeyax/burp-awesome-tls) - Burp extension to evade TLS fingerprinting. Bypass WAF, spoof any browser.
* [ron190/jsql-injection](https://github.com/ron190/jsql-injection) - jSQL Injection is a Java application for automatic SQL database injection.
* [qi4L/JYso](https://github.com/qi4L/JYso) - JNDIExploit or a ysoserial.

### Authentication and Authorization

* [dromara/Sa-Token](https://github.com/dromara/Sa-Token) - ✨ 开源、免费、一站式 Java 权限认证框架，让鉴权变得简单、优雅！—— 登录认证、权限认证、分布式 Session 会话、微服务网关鉴权、SSO 单点登录、OAuth2.0 统一认证、jwt 集成、API Key 秘钥授权、API 参数签名
* [supertokens/supertokens-core](https://github.com/supertokens/supertokens-core) - Open source alternative to Auth0 / Firebase Auth / AWS Cognito
* [apereo/cas](https://github.com/apereo/cas) - Apereo CAS - Identity & Single Sign On for all earthlings and beyond.
* [jwtk/jjwt](https://github.com/jwtk/jjwt) - Java JWT: JSON Web Token for Java and Android
* [spring-projects/spring-security](https://github.com/spring-projects/spring-security) - Spring Security
* [auth0/java-jwt](https://github.com/auth0/java-jwt) - Java implementation of JSON Web Token (JWT)
* [scribejava/scribejava](https://github.com/scribejava/scribejava) - Simple OAuth library for Java
* [apache/shiro](https://github.com/apache/shiro) - Apache Shiro is a powerful and easy-to-use Java security framework that performs authentication, authorization, cryptography, and session management
* [apache/casbin-jcasbin](https://github.com/apache/casbin-jcasbin) - An authorization library that supports access control models like ACL, RBAC, ABAC in Java
* [pac4j/pac4j](https://github.com/pac4j/pac4j) - Security engine for Java (authentication, authorization, multi frameworks): OpenID Connect, SAML2, CAS, OAuth, LDAP, JWT...
* [a466350665/smart-sso](https://github.com/a466350665/smart-sso) - SpringBoot SSO 单点登录 权限认证，OAuth2实现，支持跨域、前后端分离、分布式部署
* [xuxueli/xxl-sso](https://github.com/xuxueli/xxl-sso) - A distributed single-sign-on framework.（单点登录框架XXL-SSO）
* [raodv/captcha](https://github.com/raodv/captcha) - 行为验证码(滑动拼图、点选文字)，前后端(java)交互，包含h5/Android/IOS/flutter/uni-app的源码和实现
* [murraco/spring-boot-jwt](https://github.com/murraco/spring-boot-jwt) - JWT auth service using Spring Boot, Spring Security and MySQL
* [cloudfoundry/uaa](https://github.com/cloudfoundry/uaa) - CloudFoundry User Account and Authentication (UAA) Server
* [Smith-Cruise/Spring-Boot-Shiro](https://github.com/Smith-Cruise/Spring-Boot-Shiro) - Shiro基于SpringBoot +JWT搭建简单的restful服务
* [mitreid-connect/OpenID-Connect-Java-Spring-Server](https://github.com/mitreid-connect/OpenID-Connect-Java-Spring-Server) - An OpenID Connect reference implementation in Java on the Spring platform.

### Reverse Engineering

* [skylot/jadx](https://github.com/skylot/jadx) - Dex to Java decompiler
* [Konloch/bytecode-viewer](https://github.com/Konloch/bytecode-viewer) - A Java 8+ Jar & Android APK Reverse Engineering Suite (Decompiler, Editor, Debugger & More)
* [java-decompiler/jd-gui](https://github.com/java-decompiler/jd-gui) - A standalone Java Decompiler GUI
* [pxb1988/dex2jar](https://github.com/pxb1988/dex2jar) - Tools to work with android .dex and java .class files
* [google/android-classyshark](https://github.com/google/android-classyshark) - Android and Java bytecode viewer *(archived)*
* [Col-E/Recaf](https://github.com/Col-E/Recaf) - The modern Java bytecode editor
* [deathmarine/Luyten](https://github.com/deathmarine/Luyten) - An Open Source Java Decompiler Gui for Procyon
* [charles2gan/GDA-android-reversing-Tool](https://github.com/charles2gan/GDA-android-reversing-Tool) - the fastest and most powerful android decompiler(native tool working without Java VM) for the APK, DEX, ODEX, OAT, JAR, AAR, and CLASS file. which supports malicious behavior detection, privacy leaking detection, vulnerability detection, path solving, packer identification, variable tracking, deobfuscation, python&java scripts, device memory extraction, data decryption, and encryption, etc.
* [CalebFenton/simplify](https://github.com/CalebFenton/simplify) - Android virtual machine and deobfuscator
* [tiann/epic](https://github.com/tiann/epic) - Dynamic java method AOP hook for Android(continution of Dexposed on ART), Supporting 5.0~11
* [JetBrains/fernflower](https://github.com/JetBrains/fernflower) - Decompiler from Java bytecode to Java, used in IntelliJ IDEA.
* [bethington/ghidra-mcp](https://github.com/bethington/ghidra-mcp) - Ghidra MCP Server — 200+ MCP tools for AI-powered reverse engineering. GUI plugin + headless server, lazy tool loading, convention enforcement, batch operations, Ghidra Server integration, and Docker deployment.
* [sleuthkit/autopsy](https://github.com/sleuthkit/autopsy) - Autopsy® is a digital forensics platform and graphical interface to The Sleuth Kit® and other digital forensics tools. It can be used by law enforcement, military, and corporate examiners to investigate what happened on a computer. You can even use it to recover photos from your camera's memory card.
* [google/bindiff](https://github.com/google/bindiff) - Quickly find differences and similarities in disassembled code
* [google/binnavi](https://github.com/google/binnavi) - BinNavi is a binary analysis IDE that allows to inspect, navigate, edit and annotate control flow graphs and call graphs of disassembled code. *(archived)*
* [zinja-coder/jadx-ai-mcp](https://github.com/zinja-coder/jadx-ai-mcp) - Plugin for JADX to integrate MCP server
* [leibnitz27/cfr](https://github.com/leibnitz27/cfr) - This is the public repository for the CFR Java decompiler
* [Vineflower/vineflower](https://github.com/Vineflower/vineflower) - Modern Java decompiler aiming to be as accurate as possible, with an emphasis on output quality. Fork of the Fernflower decompiler.
* [REAndroid/APKEditor](https://github.com/REAndroid/APKEditor) - Powerful android apk editor - aapt/aapt2 independent
* [jar-analyzer/jar-analyzer](https://github.com/jar-analyzer/jar-analyzer) - Jar Analyzer - 一个 JAR 包 GUI 分析工具，内置 AI 助手协助分析，支持 JAR DIFF 分析，方法调用关系搜索，方法调用链 DFS 算法分析，模拟 JVM 的污点分析验证 DFS 结果，字符串搜索，Java Web 组件入口分析，CFG 程序分析，JVM 栈帧分析，自定义表达式搜索等
* [asLody/legend](https://github.com/asLody/legend) - A framework for hook java methods.

## Concurrency and Performance

### Concurrency and Parallelism

* [ReactiveX/RxJava](https://github.com/ReactiveX/RxJava) - RxJava – Reactive Extensions for the JVM – a library for composing asynchronous and event-based programs using observable sequences for the Java VM.
* [LMAX-Exchange/disruptor](https://github.com/LMAX-Exchange/disruptor) - High Performance Inter-Thread Messaging Library
* [alibaba/transmittable-thread-local](https://github.com/alibaba/transmittable-thread-local) - 📌 a missing Java std lib(simple & 0-dependency) for framework/middleware, provide an enhanced InheritableThreadLocal that transmits values between threads even using thread pooling components.
* [opengoofy/hippo4j](https://github.com/opengoofy/hippo4j) - 📌 异步线程池框架，支持线程池动态变更&监控&报警，无需修改代码轻松引入。Asynchronous thread pool framework, support Thread Pool Dynamic Change & monitoring & Alarm, no need to modify the code easily introduced.
* [dromara/dynamic-tp](https://github.com/dromara/dynamic-tp) - A lightweight dynamic thread pool framework with built-in monitoring and alerting, unified third-party thread pool management, and support for popular configuration centers (Nacos, Apollo, Zookeeper, Consul, and Etcd), extensible via SPI。
* [puniverse/quasar](https://github.com/puniverse/quasar) - Fibers, Channels and Actors for the JVM
* [OpenHFT/Java-Thread-Affinity](https://github.com/OpenHFT/Java-Thread-Affinity) - Bind a java thread to a given core
* [kilim/kilim](https://github.com/kilim/kilim) - Lightweight threads for Java, with message passing, nio, http and scheduling support.
* [jdeferred/jdeferred](https://github.com/jdeferred/jdeferred) - Java Deferred/Promise library similar to JQuery.
* [electronicarts/ea-async](https://github.com/electronicarts/ea-async) - EA Async implements async-await methods in the JVM.

## Testing and Quality

### Testing

* [mockito/mockito](https://github.com/mockito/mockito) - Most popular Mocking framework for unit tests written in Java
* [apache/jmeter](https://github.com/apache/jmeter) - Apache JMeter open-source load testing tool for analyzing and measuring the performance of a variety of services
* [testcontainers/testcontainers-java](https://github.com/testcontainers/testcontainers-java) - Testcontainers is a Java library that supports JUnit tests, providing lightweight, throwaway instances of common databases, Selenium web browsers, or anything else that can run in a Docker container.
* [junit-team/junit4](https://github.com/junit-team/junit4) - A programmer-oriented testing framework for Java — :warning: maintenance mode
* [wiremock/wiremock](https://github.com/wiremock/wiremock) - A tool for mocking HTTP services
* [rest-assured/rest-assured](https://github.com/rest-assured/rest-assured) - Java DSL for easy testing of REST services
* [junit-team/junit-framework](https://github.com/junit-team/junit-framework) - ✅ The programmer-friendly testing framework for Java and the JVM
* [robolectric/robolectric](https://github.com/robolectric/robolectric) - Android Unit Testing Framework
* [mock-server/mockserver-monorepo](https://github.com/mock-server/mockserver-monorepo) - MockServer is an HTTP(S) mock server and proxy for testing that lets you mock APIs, inspect and modify live traffic, and inject failures. It supports HTTP/1.1, HTTP/2, gRPC, WebSockets, TCP and more on a single port, with additional support for HTTP/3, message brokers, and AI/LLM APIs.
* [DiUS/java-faker](https://github.com/DiUS/java-faker) - Brings the popular ruby faker gem to Java
* [jacoco/jacoco](https://github.com/jacoco/jacoco) - :microscope: Java Code Coverage Library
* [powermock/powermock](https://github.com/powermock/powermock) - PowerMock is a Java framework that allows you to unit test code normally regarded as untestable.
* [awaitility/awaitility](https://github.com/awaitility/awaitility) - Awaitility is a small Java DSL for synchronizing asynchronous operations
* [TNG/ArchUnit](https://github.com/TNG/ArchUnit) - A Java architecture test library, to specify and assert architecture rules in plain Java
* [spockframework/spock](https://github.com/spockframework/spock) - The Enterprise-ready testing and specification framework.
* [assertj/assertj](https://github.com/assertj/assertj) - Fluent testing assertions for Java and the JVM
* [cucumber/cucumber-jvm](https://github.com/cucumber/cucumber-jvm) - Cucumber for the JVM
* [google/truth](https://github.com/google/truth) - Fluent assertions for Java and Android
* [bonigarcia/webdrivermanager](https://github.com/bonigarcia/webdrivermanager) - Automated driver management and other helper features for Selenium WebDriver in Java
* [alibaba/jvm-sandbox-repeater](https://github.com/alibaba/jvm-sandbox-repeater) - A Java server-side recording and playback solution based on JVM-Sandbox
* [hamcrest/JavaHamcrest](https://github.com/hamcrest/JavaHamcrest) - Java (and original) version of Hamcrest
* [testng-team/testng](https://github.com/testng-team/testng) - TestNG testing framework
* [selenide/selenide](https://github.com/selenide/selenide) - Concise UI Tests with Java!
* [hcoles/pitest](https://github.com/hcoles/pitest) - State of the art mutation testing system for the JVM
* [datafaker-net/datafaker](https://github.com/datafaker-net/datafaker) - Generating fake data for the JVM (Java, Kotlin, Groovy) has never been easier!
* [SonicCloudOrg/sonic-agent](https://github.com/SonicCloudOrg/sonic-agent) - 🎉Agent of Sonic cloud real machine platform. Sonic云真机平台Agent端。 *(archived)*
* [j-easy/easy-random](https://github.com/j-easy/easy-random) - The simple, stupid random Java beans/records generator
* [galenframework/galen](https://github.com/galenframework/galen) - Layout and functional testing framework for websites

## Utilities

### Logging and Configuration

* [orhanobut/logger](https://github.com/orhanobut/logger) - ✔️ Simple, pretty and powerful logger for android
* [apple/pkl](https://github.com/apple/pkl) - A configuration as code language with rich validation and tooling.
* [apache/logging-log4j2](https://github.com/apache/logging-log4j2) - Apache Log4j is a versatile, feature-rich, efficient logging API and backend for Java.
* [qos-ch/logback](https://github.com/qos-ch/logback) - The reliable, generic, fast and flexible logging framework for Java.
* [qos-ch/slf4j](https://github.com/qos-ch/slf4j) - Simple Logging Facade for Java
* [zalando/logbook](https://github.com/zalando/logbook) - An extensible Java library for HTTP request and response logging
* [spring-cloud/spring-cloud-config](https://github.com/spring-cloud/spring-cloud-config) - External configuration (server and client) for Spring Cloud
* [google/flogger](https://github.com/google/flogger) - A Fluent Logging API for Java
* [ff4j/ff4j](https://github.com/ff4j/ff4j) - Feature Flags for Java made easy

### Text Processing

* [houbb/sensitive-word](https://github.com/houbb/sensitive-word) - 👮‍♂️The sensitive word tool for java.(敏感词/违禁词/违法词/脏词。基于 DFA 算法实现的高性能 java 敏感词过滤工具框架。内置支持单词标签分类分级。请勿发布涉及政治、广告、营销、翻墙、违反国家法律法规等内容。高性能敏感词检测过滤组件，附带繁体简体互换，支持全角半角互换，汉字转拼音，模糊搜索等功能。)
* [Sayi/poi-tl](https://github.com/Sayi/poi-tl) - Generate awesome word(docx) with template
* [LibrePDF/OpenPDF](https://github.com/LibrePDF/OpenPDF) - OpenPDF is an open-source Java library for creating, editing, rendering, and encrypting PDF documents, as well as generating PDFs from HTML. It is licensed under the LGPL and MPL.
* [apache/tika](https://github.com/apache/tika) - The Apache Tika toolkit detects and extracts metadata and text from over a thousand different file types (such as PPT, XLS, and PDF).
* [promeG/TinyPinyin](https://github.com/promeG/TinyPinyin) - 适用于Java和Android的快速、低内存占用的汉字转拼音库。
* [apache/pdfbox](https://github.com/apache/pdfbox) - Mirror of Apache PDFBox
* [thymeleaf/thymeleaf](https://github.com/thymeleaf/thymeleaf) - Thymeleaf is a modern server-side Java template engine for both web and standalone environments.
* [tdebatty/java-string-similarity](https://github.com/tdebatty/java-string-similarity) - Implementation of various string similarity and distance algorithms: Levenshtein, Jaro-winkler, n-Gram, Q-Gram, Jaccard index, Longest Common Subsequence edit distance, cosine similarity ...
* [commonmark/commonmark-java](https://github.com/commonmark/commonmark-java) - Java library for parsing and rendering CommonMark (Markdown)
* [vdurmont/emoji-java](https://github.com/vdurmont/emoji-java) - The missing emoji library for Java :heart:
* [vsch/flexmark-java](https://github.com/vsch/flexmark-java) - CommonMark/Markdown Java parser with source level AST. CommonMark 0.28, emulation of: pegdown, kramdown, markdown.pl, MultiMarkdown. With HTML to MD, MD to PDF, MD to DOCX conversion modules.
* [VerbalExpressions/JavaVerbalExpressions](https://github.com/VerbalExpressions/JavaVerbalExpressions) - Java regular expressions made easy.
* [plutext/docx4j](https://github.com/plutext/docx4j) - JAXB-based Java library for Word docx, Powerpoint pptx, and Excel xlsx files
* [itext/itext-java](https://github.com/itext/itext-java) - iText for Java represents the next level of SDKs for developers that want to take advantage of the benefits PDF can bring. Equipped with a better document engine, high and low-level programming capabilities and the ability to create, edit and enhance PDF documents, iText can be a boon to nearly every workflow.
* [flyingsaucerproject/flyingsaucer](https://github.com/flyingsaucerproject/flyingsaucer) - XML/XHTML and CSS 2.1 renderer in pure Java
* [danfickle/openhtmltopdf](https://github.com/danfickle/openhtmltopdf) - An HTML to PDF library for the JVM. Based on Flying Saucer and Apache PDF-BOX 2. With SVG image support. Now also with accessible PDF support (WCAG, Section 508, PDF/UA)!
* [tabulapdf/tabula-java](https://github.com/tabulapdf/tabula-java) - Extract tables from PDF files
* [itext/itextpdf](https://github.com/itext/itextpdf) - [DEPRECATED] Core Java Library + PDF/A, xtra and XML Worker. Only security fixes will be added — please use iText 7
* [JonathanLink/PDFLayoutTextStripper](https://github.com/JonathanLink/PDFLayoutTextStripper) - Converts a pdf file into a text file while keeping the layout of the original pdf. Useful to extract the content from a table in a pdf file for instance. This is a subclass of PDFTextStripper class (from the Apache PDFBox library).
* [jknack/handlebars.java](https://github.com/jknack/handlebars.java) - Logic-less and semantic Mustache templates with Java
* [shekhargulati/strman-java](https://github.com/shekhargulati/strman-java) - A Java 8 string manipulation library.

### Files and Operating System

* [java-native-access/jna](https://github.com/java-native-access/jna) - Java Native Access
* [oshi/oshi](https://github.com/oshi/oshi) - Native Operating System and Hardware Information
* [bytedeco/javacpp](https://github.com/bytedeco/javacpp) - The missing bridge between Java and native C++
* [google/jimfs](https://github.com/google/jimfs) - An in-memory file system for Java
* [dromara/x-file-storage](https://github.com/dromara/x-file-storage) - 一行代码将文件存储到 本地、FTP、SFTP、WebDAV、谷歌云存储、阿里云OSS、华为云OBS、七牛云Kodo、腾讯云COS、百度云 BOS、又拍云USS、MinIO、 AWS S3、FastDFS、 Azure Blob Storage、金山云 KS3、美团云 MSS、京东云 OSS、天翼云 OOS、移动云 EOS、沃云 OSS、 网易数帆 NOS、Ucloud US3、青云 QingStor、平安云 OBS、首云 OSS、IBM COS、其它兼容 S3 协议的平台。后续即将支持 Samba、NFS
* [kwhat/jnativehook](https://github.com/kwhat/jnativehook) - Global keyboard and mouse listeners for Java.
* [happyfish100/fastdfs-client-java](https://github.com/happyfish100/fastdfs-client-java) - FastDFS java client SDK

### Automation and Scripting

* [conductor-oss/conductor](https://github.com/conductor-oss/conductor) - Conductor is an event driven agentic workflow engine providing durable and highly resilient execution engine for applications and AI Agents
* [kestra-io/kestra](https://github.com/kestra-io/kestra) - Event Driven Orchestration & Scheduling Platform for Mission Critical Applications
* [Netflix/conductor](https://github.com/Netflix/conductor) - Conductor is a microservices orchestration engine. *(archived)*
* [Activiti/Activiti](https://github.com/Activiti/Activiti) - Activiti is a light-weight workflow and Business Process Management (BPM) Platform targeted at business people, developers and system admins. Its core is a super-fast and rock-solid BPMN 2 process engine for Java. It's open-source and distributed under the Apache license. Activiti runs in any Java application, on a server, on a cluster or in the cloud. It integrates perfectly with Spring, it is extremely lightweight and based on simple concepts.
* [flowable/flowable-engine](https://github.com/flowable/flowable-engine) - A compact and highly efficient workflow and Business Process Management (BPM) platform for developers, system admins and business users.
* [apache/incubator-kie](https://github.com/apache/incubator-kie) - Apache KIE (Knowledge Is Everything) is the home of Drools, OptaPlanner, jBPM, and Kogito.
* [rubenlagus/TelegramBots](https://github.com/rubenlagus/TelegramBots) - Java library to create bots using Telegram Bots API
* [camunda/camunda](https://github.com/camunda/camunda) - Process Orchestration Framework
* [camunda/camunda-bpm-platform](https://github.com/camunda/camunda-bpm-platform) - Camunda 7 CE is End of Life (EoL). Please check out Camunda 8 instead (https://github.com/camunda/camunda) or read about Camunda 7 Enterprise End of Life (https://camunda.com/blog/2025/02/camunda-7-enterprise-end-of-life-extension/) – Camunda 7 CE was a flexible framework for workflow and decision automation using BPMN and DMN. *(archived)*
* [oculix-org/SikuliX1](https://github.com/oculix-org/SikuliX1) - SikuliX version 2.0.0+ (2019+)
* [moshowgame/SpringBootCodeGenerator](https://github.com/moshowgame/SpringBootCodeGenerator) - 又名大狼狗代码生成器，基于SpringBoot2+Freemarker的JAVA代码生成器，以释放双手为目的，支持mysql/oracle/pgsql三大数据库， 用DDL-SQL语句生成JPA/JdbcTemplate/Mybatis/MybatisPlus/BeetlSQL等相关代码.
* [yaphone/itchat4j](https://github.com/yaphone/itchat4j) - itchat4j -- 用Java扩展个人微信号的能力
* [openhab/openhab-addons](https://github.com/openhab/openhab-addons) - Add-ons for openHAB
* [alibaba/compileflow](https://github.com/alibaba/compileflow) - 🎨 core business process engine of Alibaba Halo platform, best process engine for trade scenes. | 一个高性能流程编排引擎
* [pengrad/java-telegram-bot-api](https://github.com/pengrad/java-telegram-bot-api) - Telegram Bot API for Java
* [youseries/urule](https://github.com/youseries/urule) - URULE是一款基于RETE算法的纯Java规则引擎，提供规则集、决策表、决策树、评分卡，规则流等各种规则表现工具及基于网页的可视化设计器，可快速开发出各种复杂业务规则。
* [Discord4J/Discord4J](https://github.com/Discord4J/Discord4J) - Discord4J is a fast, powerful, unopinionated, reactive library to enable quick and easy development of Discord bots for Java, Kotlin, and other JVM languages using the official Discord Bot API.
* [wfh45678/radar](https://github.com/wfh45678/radar) - 实时风控引擎(Risk Engine)，自定义规则引擎（Rule Script），完美支持中文，适用于反欺诈(Anti-fraud)应用场景，开箱即用！！！移动互联网时代的风险管理利器，你 Get 到了吗？

### General Purpose Libraries

* [google/guava](https://github.com/google/guava) - Google core libraries for Java
* [chinabugotech/hutool](https://github.com/chinabugotech/hutool) - 🍬A set of tools that keep Java sweet.
* [google/guice](https://github.com/google/guice) - Guice (pronounced 'juice') is a lightweight dependency injection framework for Java 11 and above, brought to you by Google.
* [mapstruct/mapstruct](https://github.com/mapstruct/mapstruct) - An annotation processor for generating type-safe bean mappers
* [vipshop/vjtools](https://github.com/vipshop/vjtools) - The vip.com's java coding standard, libraries and tools
* [square/dagger](https://github.com/square/dagger) - A fast dependency injector for Android and Java. *(archived)*
* [vavr-io/vavr](https://github.com/vavr-io/vavr) - vʌvr (formerly called Javaslang) is a non-commercial, non-profit object-functional library that runs with Java 8+. It aims to reduce the lines of code and increase code quality.
* [ronmamo/reflections](https://github.com/ronmamo/reflections) - Java runtime metadata analysis
* [failsafe-lib/failsafe](https://github.com/failsafe-lib/failsafe) - Fault tolerance and resilience patterns for the JVM
* [oblac/jodd](https://github.com/oblac/jodd) - Jodd! Lightweight. Java. Zero dependencies. Use what you like.
* [RoaringBitmap/RoaringBitmap](https://github.com/RoaringBitmap/RoaringBitmap) - A better compressed bitset in Java: used by Apache Spark, Netflix Atlas, Apache Pinot, Tablesaw, and many others
* [immutables/immutables](https://github.com/immutables/immutables) - Java annotation processor to create immutable objects and builders, for records too. Sweep boilerplate code under the rug!
* [aeron-io/agrona](https://github.com/aeron-io/agrona) - High Performance data structures and utility methods for Java
* [classgraph/classgraph](https://github.com/classgraph/classgraph) - An uber-fast parallelized Java classpath scanner and module scanner.
* [williamfiset/DEPRECATED-data-structures](https://github.com/williamfiset/DEPRECATED-data-structures) - A collection of powerful data structures
* [jOOQ/jOOR](https://github.com/jOOQ/jOOR) - jOOR - Fluent Reflection in Java jOOR is a very simple fluent API that gives access to your Java Class structures in a more intuitive way. The JDK's reflection APIs are hard and verbose to use. Other languages have much simpler constructs to access type meta information at runtime. Let us make Java reflection better.
* [bucket4j/bucket4j](https://github.com/bucket4j/bucket4j) - Java rate limiting library based on token-bucket algorithm.
* [pf4j/pf4j](https://github.com/pf4j/pf4j) - Plugin Framework for Java (PF4J)
* [eclipse-collections/eclipse-collections](https://github.com/eclipse-collections/eclipse-collections) - Eclipse Collections is a collections framework for Java with optimized data structures and a rich, functional and fluent API.
* [amaembo/streamex](https://github.com/amaembo/streamex) - Enhancing Java Stream API
* [addthis/stream-lib](https://github.com/addthis/stream-lib) - Stream summarizer and cardinality estimator. *(archived)*
* [hekailiang/squirrel](https://github.com/hekailiang/squirrel) - squirrel-foundation is a State Machine library, which provided a lightweight, easy use, type safe and programmable state machine implementation for Java.
* [vigna/fastutil](https://github.com/vigna/fastutil) - fastutil extends the Java™ Collections Framework by providing type-specific maps, sets, lists and queues.
* [lets-mica/mica](https://github.com/lets-mica/mica) - Spring Cloud 微服务开发核心工具集。工具类、验证码、http、redis、ip2region、xss 等，开箱即用。 🔝 🔝 记得右上角点个star 关注更新！
* [jOOQ/jOOL](https://github.com/jOOQ/jOOL) - jOOλ - The Missing Parts in Java 8 jOOλ improves the JDK libraries in areas where the Expert Group's focus was elsewhere. It adds tuple support, function support, and a lot of additional functionality around sequential Streams. The JDK 8's main efforts (default methods, lambdas, and the Stream API) were focused around maintaining backwards compatibility and implementing a functional API for parallelism.
* [DozerMapper/dozer](https://github.com/DozerMapper/dozer) - Dozer is a Java Bean to Java Bean mapper that recursively copies data from one object to another.
* [spring-attic/spring-statemachine](https://github.com/spring-attic/spring-statemachine) - Spring Statemachine is a framework for application developers to use state machine concepts with Spring. *(archived)*
* [functionaljava/functionaljava](https://github.com/functionaljava/functionaljava) - Functional programming in Java
* [aNNiMON/Lightweight-Stream-API](https://github.com/aNNiMON/Lightweight-Stream-API) - Stream API from Java 8 rewritten on iterators for Java 7 and below
* [EsotericSoftware/reflectasm](https://github.com/EsotericSoftware/reflectasm) - High performance Java reflection
* [jayZheng87/Thusy](https://github.com/jayZheng87/Thusy) - Java 工具类库；在全面集成 Hutool 上进行工具类二次收集的一个类库
* [greenrobot/essentials](https://github.com/greenrobot/essentials) - General purpose utilities and hash functions for Android and Java (aka java-common)

## Other

* [NationalSecurityAgency/ghidra](https://github.com/NationalSecurityAgency/ghidra) - Ghidra is a software reverse engineering (SRE) framework
* [MisterBooo/LeetCodeAnimation](https://github.com/MisterBooo/LeetCodeAnimation) - Demonstrate all the questions on LeetCode in the form of animation.（用动画的形式呈现解LeetCode题目的思路,完整单步/回看/变速/语音讲解在 algomooc.com）
* [termux/termux-app](https://github.com/termux/termux-app) - Termux - a terminal emulator application for Android OS extendible by variety of packages.
* [spring-projects/spring-framework](https://github.com/spring-projects/spring-framework) - Spring Framework
* [ashishps1/awesome-system-design-resources](https://github.com/ashishps1/awesome-system-design-resources) - Learn System Design concepts and prepare for interviews using free resources.
* [halo-dev/halo](https://github.com/halo-dev/halo) - Halo 是一款强大易用的开源建站工具，从个人博客、知识库，到企业官网、在线商城，Halo 都能助您轻松实现，一站式满足您的多样化建站需求。
* [TeamNewPipe/NewPipe](https://github.com/TeamNewPipe/NewPipe) - A libre lightweight streaming front-end for Android.
* [YunaiV/ruoyi-vue-pro](https://github.com/YunaiV/ruoyi-vue-pro) - 🔥 官方推荐 🔥 RuoYi-Vue 全新 Pro 版本，优化重构所有功能。基于 Spring Boot + MyBatis Plus + Vue & Element 实现的后台管理系统 + 微信小程序，支持 RBAC 动态权限、数据权限、SaaS 多租户、Flowable 工作流、三方登录、支付、短信、商城、CRM、ERP、MES、IM、AI 大模型、IoT 物联网等功能。你的 ⭐️ Star ⭐️，是作者生发的动力！
* [eugenp/tutorials](https://github.com/eugenp/tutorials) - Getting Started with Spring Boot 3:
* [keycloak/keycloak](https://github.com/keycloak/keycloak) - Open Source Identity and Access Management For Modern Applications and Services
* [geekxh/hello-algorithm](https://github.com/geekxh/hello-algorithm) - 🌍 针对小白的算法训练 | 包括四部分：①.大厂面经 ②.力扣图解 ③.千本开源电子书 ④.百张技术思维导图（项目花了上百小时，希望可以点 star 支持，🌹感谢~）推荐免费ChatGPT使用网站
* [airbnb/lottie-android](https://github.com/airbnb/lottie-android) - Render After Effects animations natively on Android and iOS, Web, and React Native
* [netty/netty](https://github.com/netty/netty) - Netty project - an event-driven asynchronous network application framework
* [bumptech/glide](https://github.com/bumptech/glide) - An image loading and caching library for Android focused on smooth scrolling
* [Blankj/AndroidUtilCode](https://github.com/Blankj/AndroidUtilCode) - :fire: Android developers should collect the following utils(updating).
* [alibaba/nacos](https://github.com/alibaba/nacos) - an easy-to-use dynamic service discovery, configuration and service management platform for building AI cloud native applications.
* [xuxueli/xxl-job](https://github.com/xuxueli/xxl-job) - A distributed task scheduling framework.（分布式任务调度平台XXL-JOB）
* [DrKLO/Telegram](https://github.com/DrKLO/Telegram) - Telegram for Android source
* [apolloconfig/apollo](https://github.com/apolloconfig/apollo) - Apollo is a reliable configuration management system suitable for microservice configuration management scenarios.
* [alibaba/canal](https://github.com/alibaba/canal) - 阿里巴巴 MySQL binlog 增量订阅&消费组件
* [opendataloader-project/opendataloader-pdf](https://github.com/opendataloader-project/opendataloader-pdf) - PDF Parser for AI-ready data. Automate PDF accessibility. Open-source.
* [wuyouzhuguli/SpringAll](https://github.com/wuyouzhuguli/SpringAll) - 循序渐进，学习Spring Boot、Spring Boot & Shiro、Spring Batch、Spring Cloud、Spring Cloud Alibaba、Spring Security & Spring Security OAuth2，博客Spring系列源码：https://mrbird.cc
* [alibaba/druid](https://github.com/alibaba/druid) - 阿里云计算平台DataWorks(https://help.aliyun.com/document_detail/137663.html) 团队出品，为监控而生的数据库连接池
* [OtterMind/Chat2DB](https://github.com/OtterMind/Chat2DB) - Chat2DB is a free, cross-platform, local-first database client and SQL workspace for developers, DBAs, analysts, and data teams. Connect to 40+ databases, manage data, edit and run SQL, and use your own AI model to generate, explain, and optimize queries. Available on desktop, web, Docker, and CLI, with MCP support.
* [lenve/vhr](https://github.com/lenve/vhr) - 微人事是一个前后端分离的人力资源管理系统，项目采用SpringBoot+Vue开发。
* [ashishps1/awesome-low-level-design](https://github.com/ashishps1/awesome-low-level-design) - Learn Low Level Design (LLD) and prepare for interviews using free resources.
* [OpenAPITools/openapi-generator](https://github.com/OpenAPITools/openapi-generator) - OpenAPI Generator allows generation of API client libraries (SDK generation), server stubs, documentation and configuration automatically given an OpenAPI Spec (v2, v3)
* [qiurunze123/miaosha](https://github.com/qiurunze123/miaosha) - ⭐⭐⭐⭐秒杀系统设计与实现.互联网工程师进阶与分析🙋🐓
* [apache/incubator-seata](https://github.com/apache/incubator-seata) - :fire: Seata is an easy-to-use, high-performance, open source distributed transaction solution.
* [bazelbuild/bazel](https://github.com/bazelbuild/bazel) - a fast, scalable, multi-language and extensible build system
* [iBotPeaches/Apktool](https://github.com/iBotPeaches/Apktool) - A tool for reverse engineering Android apk files
* [JakeWharton/butterknife](https://github.com/JakeWharton/butterknife) - Bind Android views and callbacks to fields and methods.
* [scwang90/SmartRefreshLayout](https://github.com/scwang90/SmartRefreshLayout) - 🔥下拉刷新、上拉加载、二级刷新、淘宝二楼、RefreshLayout、OverScroll，Android智能下拉刷新框架，支持越界回弹、越界拖动，具有极强的扩展性，集成了几十种炫酷的Header和 Footer。
* [apache/skywalking](https://github.com/apache/skywalking) - APM, Application Performance Monitoring System
* [LSPosed/LSPosed](https://github.com/LSPosed/LSPosed) - LSPosed Framework
* [proxyee-down-org/proxyee-down](https://github.com/proxyee-down-org/proxyee-down) - http下载工具，基于http代理，支持多连接分块下载 *(archived)*
* [Netflix/Hystrix](https://github.com/Netflix/Hystrix) - Hystrix is a latency and fault tolerance library designed to isolate points of access to remote systems, services and 3rd party libraries, stop cascading failure and enable resilience in complex distributed systems where failure is inevitable.
* [dataease/dataease](https://github.com/dataease/dataease) - 🔥 人人可用的开源 BI 工具，数据可视化神器。An open-source BI tool alternative to Tableau.
* [floci-io/floci](https://github.com/floci-io/floci) - Light, fluffy, and always free - The AWS Local Emulator alternative
* [EnterpriseQualityCoding/FizzBuzzEnterpriseEdition](https://github.com/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition) - FizzBuzz Enterprise Edition is a no-nonsense implementation of FizzBuzz made by serious businessmen for serious business purposes.
* [doocs/source-code-hunter](https://github.com/doocs/source-code-hunter) - 😱 从源码层面，剖析挖掘互联网行业主流技术的底层实现原理，为广大开发者 “提升技术深度” 提供便利。目前开放 Spring 全家桶，Mybatis、Netty、Dubbo 框架，及 Redis、Tomcat 中间件等
* [elunez/eladmin](https://github.com/elunez/eladmin) - eladmin jpa 版本：项目基于 Spring Boot 2.7.18、 Jpa、 Spring Security、Redis、Vue的前后端分离的后台管理系统，项目采用分模块开发方式， 权限控制采用 RBAC，支持数据字典与数据权限管理，支持一键生成前后端代码，支持动态路由
* [CarGuo/GSYVideoPlayer](https://github.com/CarGuo/GSYVideoPlayer) - Video players (IJKplayer, ExoPlayer, MediaPlayer), HTTPS, 16k page size, danmaku (bullet chat) support, external subtitles, support for filters, watermarks, and GIF screenshots, pre-roll and mid-roll ads, multiple simultaneous playback, basic seeking/dragging, volume and brightness adjustment, play-while-cache support
* [apache/shardingsphere](https://github.com/apache/shardingsphere) - Empowering Data Intelligence with Distributed SQL for Sharding, Scalability, and Security Across All Databases.
* [JetBrains/intellij-community](https://github.com/JetBrains/intellij-community) - IntelliJ IDEA & IntelliJ Platform
* [didi/DoKit](https://github.com/didi/DoKit) - 一款面向泛前端产品研发全生命周期的效率平台。
* [linlinjava/litemall](https://github.com/linlinjava/litemall) - 又一个小商城。litemall = Spring Boot后端 + Vue管理员前端 + 微信小程序用户前端 + Vue用户移动端
* [yudaocode/SpringBoot-Labs](https://github.com/yudaocode/SpringBoot-Labs) - 一个涵盖六个专栏：Spring Boot 2.X、Spring Cloud、Spring Cloud Alibaba、Dubbo、分布式消息队列、分布式事务的仓库。希望胖友小手一抖，右上角来个 Star，感恩 1024
* [ReactiveX/RxAndroid](https://github.com/ReactiveX/RxAndroid) - RxJava bindings for Android
* [YunaiV/yudao-cloud](https://github.com/YunaiV/yudao-cloud) - ruoyi-vue-pro 全新 Cloud 版本，优化重构所有功能。基于 Spring Cloud Alibaba + MyBatis Plus + Vue & Element 实现的后台管理系统 + 用户小程序，支持 RBAC 动态权限、多租户、数据权限、工作流、三方登录、支付、短信、商城、CRM、ERP、MES、IM、AI 大模型、IoT 物联网等功能。你的 ⭐️ Star ⭐️，是作者生发的动力！
* [Baseflow/PhotoView](https://github.com/Baseflow/PhotoView) - Implementation of ImageView for Android that supports zooming, by various touch gestures.
* [williamfiset/algorithms](https://github.com/williamfiset/algorithms) - A collection of algorithms and data structures
* [APIJSON/APIJSON](https://github.com/APIJSON/APIJSON) - 🏆 Real-Time no-code, powerful and secure ORM 🚀 providing APIs and Docs without coding by Backend, and Frontend(Client) can customize response JSONs 🏆 实时 零代码、全功能、强安全 ORM 库 🚀 后端接口和文档零代码，前端(客户端) 定制返回 JSON 的数据和结构
* [forezp/SpringCloudLearning](https://github.com/forezp/SpringCloudLearning) - 《史上最简单的Spring Cloud教程源码》
* [ashishps1/awesome-leetcode-resources](https://github.com/ashishps1/awesome-leetcode-resources) - Awesome LeetCode resources to learn Data Structures and Algorithms and prepare for Coding Interviews.
* [Tencent/tinker](https://github.com/Tencent/tinker) - Tinker is a hot-fix solution library for Android, it supports dex, library and resources update without reinstall apk.
* [justauth/JustAuth](https://github.com/justauth/JustAuth) - 🏆Gitee 最有价值开源项目 🚀:100: 小而全而美的第三方登录开源组件。目前已支持Github、Gitee、微博、钉钉、百度、Coding、腾讯云开发者平台、OSChina、支付宝、QQ、微信、淘宝、Google、Facebook、抖音、领英、小米、微软、今日头条、Teambition、StackOverflow、Pinterest、人人、华为、企业微信、酷家乐、Gitlab、美团、饿了么、推特、飞书、京东、阿里云、喜马拉雅、Amazon、Slack和 Line 等第三方平台的授权登录。 Login, so easy!
* [baomidou/mybatis-plus](https://github.com/baomidou/mybatis-plus) - An powerful enhanced toolkit of MyBatis for simplify development
* [openzipkin/zipkin](https://github.com/openzipkin/zipkin) - Zipkin is a distributed tracing system
* [material-components/material-components-android](https://github.com/material-components/material-components-android) - [MAINTENANCE MODE] Modular and customizable Material Design UI components for Android
* [alibaba/DataX](https://github.com/alibaba/DataX) - DataX是阿里云DataWorks数据集成的开源版本。
* [neo4j/neo4j](https://github.com/neo4j/neo4j) - Graphs for Everyone
* [heibaiying/BigData-Notes](https://github.com/heibaiying/BigData-Notes) - 大数据入门指南 :star:
* [nostra13/Android-Universal-Image-Loader](https://github.com/nostra13/Android-Universal-Image-Loader) - Powerful and flexible library for loading, caching and displaying images on Android.
* [shuzheng/zheng](https://github.com/shuzheng/zheng) - 基于Spring+SpringMVC+Mybatis分布式敏捷开发系统架构，提供整套公共微服务服务模块：集中权限管理（单点登录）、内容管理、支付中心、用户管理（支持第三方登录）、微信平台、存储系统、配置中心、日志分析、任务和通知等，支持服务治理、监控和追踪，努力为中小型企业打造全方位J2EE企业级开发解决方案。
* [JeffLi1993/springboot-learning-example](https://github.com/JeffLi1993/springboot-learning-example) - spring boot 实践学习案例，是 spring boot 初学者及核心技术巩固的最佳实践。
* [android-hacker/VirtualXposed](https://github.com/android-hacker/VirtualXposed) - A simple app to use Xposed without root, unlock the bootloader or modify system image, etc.
* [apache/doris](https://github.com/apache/doris) - Apache Doris is a real-time analytics and hybrid search database for AI agents.
* [zaproxy/zaproxy](https://github.com/zaproxy/zaproxy) - The ZAP by Checkmarx Core project
* [dyc87112/SpringBoot-Learning](https://github.com/dyc87112/SpringBoot-Learning) - 《Spring Boot基础教程》，2.x版本持续连载中！点击下方链接直达教程目录！
* [apache/hadoop](https://github.com/apache/hadoop) - Apache Hadoop
* [apache/pulsar](https://github.com/apache/pulsar) - Apache Pulsar - distributed pub-sub messaging system
* [theonedev/onedev](https://github.com/theonedev/onedev) - The Unified and Autonomous Development Platform
* [zhisheng17/flink-learning](https://github.com/zhisheng17/flink-learning) - flink learning blog. http://www.54tianzhisheng.cn/ 含 Flink 入门、概念、原理、实战、性能调优、源码解析等内容。涉及 Flink Connector、Metrics、Library、DataStream API、Table API & SQL 等内容的学习案例，还有 Flink 落地应用的大型项目案例（PVUV、日志存储、百亿数据实时去重、监控告警）分享。欢迎大家支持我的专栏《大数据实时计算引擎 Flink 实战与性能优化》
* [languagetool-org/languagetool](https://github.com/languagetool-org/languagetool) - Style and Grammar Checker for 25+ Languages
* [arduino/Arduino](https://github.com/arduino/Arduino) - Arduino IDE 1.x
* [hdodenhof/CircleImageView](https://github.com/hdodenhof/CircleImageView) - A circular ImageView for Android
* [Tencent/QMUI_Android](https://github.com/Tencent/QMUI_Android) - 提高 Android UI 开发效率的 UI 库
* [apache/dolphinscheduler](https://github.com/apache/dolphinscheduler) - Apache DolphinScheduler is the modern data orchestration platform. Agile to create high performance workflow with low-code
* [alibaba/ARouter](https://github.com/alibaba/ARouter) - 💪 A framework for assisting in the renovation of Android componentization (帮助 Android App 进行组件化改造的路由框架)
* [janishar/mit-deep-learning-book-pdf](https://github.com/janishar/mit-deep-learning-book-pdf) - MIT Deep Learning Book in PDF format (complete and parts) by Ian Goodfellow, Yoshua Bengio and Aaron Courville
* [Netflix/zuul](https://github.com/Netflix/zuul) - Zuul is a gateway service that provides dynamic routing, monitoring, resiliency, security, and more.
* [apache/druid](https://github.com/apache/druid) - Apache Druid: a high performance real-time analytics database.
* [sqshq/piggymetrics](https://github.com/sqshq/piggymetrics) - Microservice Architecture with Spring Boot, Spring Cloud and Docker
* [pinpoint-apm/pinpoint](https://github.com/pinpoint-apm/pinpoint) - APM, (Application Performance Management) tool for large-scale distributed systems.
* [seaswalker/spring-analysis](https://github.com/seaswalker/spring-analysis) - Spring源码阅读
* [JessYanCoding/AndroidAutoSize](https://github.com/JessYanCoding/AndroidAutoSize) - 🔥 A low-cost Android screen adaptation solution (今日头条屏幕适配方案终极版，一个极低成本的 Android 屏幕适配方案).
* [LuckSiege/PictureSelector](https://github.com/LuckSiege/PictureSelector) - Picture Selector Library for Android or 图片选择器
* [lgvalle/Material-Animations](https://github.com/lgvalle/Material-Animations) - Android Transition animations explanation with examples.
* [tink-crypto/tink](https://github.com/tink-crypto/tink) - Tink is a multi-language, cross-platform, open source library that provides cryptographic APIs that are secure, easy to use correctly, and hard(er) to misuse. *(archived)*
* [metersphere/metersphere](https://github.com/metersphere/metersphere) - MeterSphere 是新一代的开源持续测试工具，内置 AI 助手，让软件测试工作更简单、更高效，不再成为持续交付的瓶颈。
* [Bigkoo/Android-PickerView](https://github.com/Bigkoo/Android-PickerView) - This is a picker view for android , support linkage effect, timepicker and optionspicker.（时间选择器、省市区三级联动）
* [macrozheng/mall-learning](https://github.com/macrozheng/mall-learning) - mall学习教程，架构、业务、技术要点全方位解析。mall项目（60k+star）是一套电商系统，使用现阶段主流技术实现。涵盖了SpringBoot、MyBatis、Elasticsearch、RabbitMQ、Redis、MongoDB、MySQL等技术，采用Docker容器化部署。
* [plantuml/plantuml](https://github.com/plantuml/plantuml) - Generate diagrams from textual description
* [debezium/debezium](https://github.com/debezium/debezium) - Change data capture for a variety of databases. Please log issues at https://github.com/debezium/dbz/issues.
* [beemdevelopment/Aegis](https://github.com/beemdevelopment/Aegis) - A free, secure and open source app for Android to manage your 2-step verification tokens.
* [alibaba/COLA](https://github.com/alibaba/COLA) - 🥤 COLA: Clean Object-oriented & Layered Architecture
* [youth5201314/banner](https://github.com/youth5201314/banner) - 🔥🔥🔥Banner 2.0 来了！Android广告图片轮播控件，内部基于ViewPager2实现，Indicator和UI都可以自定义。
* [Netflix/eureka](https://github.com/Netflix/eureka) - AWS Service registry for resilient mid-tier load balancing and failover.
* [facebook/stetho](https://github.com/facebook/stetho) - Stetho is a debug bridge for Android applications, enabling the powerful Chrome Developer Tools and much more. *(archived)*
* [greenrobot/greenDAO](https://github.com/greenrobot/greenDAO) - greenDAO is a light & fast ORM solution for Android that maps objects to SQLite databases.
* [zhihu/Matisse](https://github.com/zhihu/Matisse) - :fireworks: A well-designed local image and video selector for Android
* [daimajia/AndroidViewAnimations](https://github.com/daimajia/AndroidViewAnimations) - Cute view animation collection.
* [amitshekhariitbhu/android-interview-questions](https://github.com/amitshekhariitbhu/android-interview-questions) - Your Cheat Sheet For Android Interview - Android Interview Questions and Answers
* [daimajia/AndroidSwipeLayout](https://github.com/daimajia/AndroidSwipeLayout) - The Most Powerful Swipe Layout!
* [pagehelper-org/Mybatis-PageHelper](https://github.com/pagehelper-org/Mybatis-PageHelper) - Mybatis通用分页插件
* [provectus/kafka-ui](https://github.com/provectus/kafka-ui) - Open-Source Web UI for Apache Kafka Management
* [StarRocks/starrocks](https://github.com/StarRocks/starrocks) - The world's fastest open query engine for sub-second analytics both on and off the data lakehouse. With the flexibility to support nearly any scenario, StarRocks provides best-in-class performance for multi-dimensional analytics, real-time analytics, and ad-hoc queries. A Linux Foundation project.
* [Tencent/matrix](https://github.com/Tencent/matrix) - Matrix is a plugin style, non-invasive APM system developed by WeChat.
* [jd-opensource/joyagent-jdgenie](https://github.com/jd-opensource/joyagent-jdgenie) - 开源的端到端产品级通用智能体
* [Tencent/VasSonic](https://github.com/Tencent/VasSonic) - VasSonic is a lightweight and high-performance Hybrid framework developed by tencent VAS team, which is intended to speed up the first screen of websites working on Android and iOS platform.
* [gyf-dev/ImmersionBar](https://github.com/gyf-dev/ImmersionBar) - android 4.4以上沉浸式状态栏和沉浸式导航栏管理，适配横竖屏切换、刘海屏、软键盘弹出等问题，可以修改状态栏字体颜色和导航栏图标颜色，以及不可修改字体颜色手机的适配，适用于Activity、Fragment、DialogFragment、Dialog，PopupWindow，一句代码轻松实现，以及对bar的其他设置，详见README。简书请参考：http://www.jianshu.com/p/2a884e211a62
* [mission-peace/interview](https://github.com/mission-peace/interview) - Interview questions
* [ssssssss-team/spider-flow](https://github.com/ssssssss-team/spider-flow) - 新一代爬虫平台，以图形化方式定义爬虫流程，不写代码即可完成爬虫。
* [daniulive/SmarterStreaming](https://github.com/daniulive/SmarterStreaming) - 业内为数不多致力于极致体验的超强全自研跨平台(windows/linux/android/iOS)流媒体内核，通过模块化自由组合，支持实时RTMP推流、RTSP推流、RTMP播放器、RTSP播放器、录像、多路流媒体转发、音视频导播、动态视频合成、音频混音、直播互动、内置轻量级RTSP服务等，比快更快，业界真正靠谱的超低延迟直播SDK(延迟低至100~200ms)。
* [lingochamp/FileDownloader](https://github.com/lingochamp/FileDownloader) - Multitask、MultiThread(MultiConnection)、Breakpoint-resume、High-concurrency、Simple to use、Single/NotSingle-process
* [asLody/VirtualApp](https://github.com/asLody/VirtualApp) - Virtual Engine for Android(Support 14.0 in business version)
* [H07000223/FlycoTabLayout](https://github.com/H07000223/FlycoTabLayout) - An Android TabLayout Lib
* [SonarSource/sonarqube](https://github.com/SonarSource/sonarqube) - Continuous Inspection
* [jfeinstein10/SlidingMenu](https://github.com/jfeinstein10/SlidingMenu) - An Android library that allows you to easily create applications with slide-in menus. You may use it in your Android apps provided that you cite this project and include the license in your app. Thanks!
* [clojure/clojure](https://github.com/clojure/clojure) - The Clojure programming language
* [zfile-dev/zfile](https://github.com/zfile-dev/zfile) - 在线云盘、网盘、OneDrive、云存储、私有云、对象存储、h5ai、上传、下载
* [aosp-mirror/platform_frameworks_base](https://github.com/aosp-mirror/platform_frameworks_base) - *(archived)*
* [AutoMQ/automq](https://github.com/AutoMQ/automq) - Diskless Kafka® on S3. 10x Cost-Effective. No Cross-AZ Traffic Cost. Autoscale in seconds. Single-digit ms latency. Multi-AZ Availability.
* [resilience4j/resilience4j](https://github.com/resilience4j/resilience4j) - Resilience4j is a fault tolerance library designed for Java8 and functional programming
* [alibaba/vlayout](https://github.com/alibaba/vlayout) - Project vlayout is a powerfull LayoutManager extension for RecyclerView, it provides a group of layouts for RecyclerView. Make it able to handle a complicate situation when grid, list and other layouts in the same recyclerview. *(archived)*
* [signalapp/Signal-Server](https://github.com/signalapp/Signal-Server) - Server supporting the Signal Private Messenger applications on Android, Desktop, and iOS
* [jeasonlzy/okhttp-OkGo](https://github.com/jeasonlzy/okhttp-OkGo) - OkGo - 3.0 震撼来袭，该库是基于 Http 协议，封装了 OkHttp 的网络请求框架，比 Retrofit 更简单易用，支持 RxJava，RxJava2，支持自定义缓存，支持批量断点下载管理和批量上传管理功能
* [github/copilot-sdk](https://github.com/github/copilot-sdk) - Multi-platform SDK for integrating GitHub Copilot Agent into apps and services
* [lipangit/JiaoZiVideoPlayer](https://github.com/lipangit/JiaoZiVideoPlayer) - MediaPlayer exoplayer ijkplayer ffmpeg *(archived)*
* [niedev/RTranslator](https://github.com/niedev/RTranslator) - Open source real-time translation app for Android that runs locally
* [tbruyelle/RxPermissions](https://github.com/tbruyelle/RxPermissions) - Android runtime permissions powered by RxJava2 *(archived)*
* [JessYanCoding/MVPArms](https://github.com/JessYanCoding/MVPArms) - ⚔️ A common architecture for Android applications developing based on MVP, integrates many open source projects, to make your developing quicker and easier (一个整合了大量主流开源项目高度可配置化的 Android MVP 快速集成框架).
* [HMCL-dev/HMCL](https://github.com/HMCL-dev/HMCL) - A Minecraft Launcher which is multi-functional, cross-platform and popular
* [LaurieWired/GhidraMCP](https://github.com/LaurieWired/GhidraMCP) - MCP Server for Ghidra
* [JakeWharton/ViewPagerIndicator](https://github.com/JakeWharton/ViewPagerIndicator) - Paging indicator widgets compatible with the ViewPager from the Android Support Library and ActionBarSherlock. *(archived)*
* [googlesamples/easypermissions](https://github.com/googlesamples/easypermissions) - Simplify Android M system permissions *(archived)*
* [paascloud/paascloud-master](https://github.com/paascloud/paascloud-master) - spring cloud + vue + oAuth2.0全家桶实战，前后端分离模拟商城，完整的购物流程、后端运营平台，可以实现快速搭建企业级微服务项目。支持微信登录等三方登录。
* [seven332/EhViewer](https://github.com/seven332/EhViewer) - [DEPRECATED] An Unofficial E-Hentai Application for Android *(archived)*
* [hackware1993/MagicIndicator](https://github.com/hackware1993/MagicIndicator) - A powerful, customizable and extensible ViewPager indicator framework. As the best alternative of ViewPagerIndicator, TabLayout and PagerSlidingTabStrip —— 强大、可定制、易扩展的 ViewPager 指示器框架。是ViewPagerIndicator、TabLayout、PagerSlidingTabStrip的最佳替代品。支持角标，更支持在非ViewPager场景下使用（使用hide()、show()切换Fragment或使用setVisibility切换FrameLayout里的View等），http://www.jianshu.com/p/f3022211821c
* [spinnaker/spinnaker](https://github.com/spinnaker/spinnaker) - Spinnaker is an open source, multi-cloud continuous delivery platform for releasing software changes with high velocity and confidence.
* [HarlonWang/AVLoadingIndicatorView](https://github.com/HarlonWang/AVLoadingIndicatorView) - DEPRECATED
* [YoKeyword/Fragmentation](https://github.com/YoKeyword/Fragmentation) - [DEPRECATED] A powerful library that manage Fragment for Android
* [apache/seatunnel](https://github.com/apache/seatunnel) - SeaTunnel is a multimodal, high-performance, distributed, massive data integration tool.
* [koral--/android-gif-drawable](https://github.com/koral--/android-gif-drawable) - Views and Drawable for displaying animated GIFs on Android
* [react-native-camera/react-native-camera](https://github.com/react-native-camera/react-native-camera) - A Camera component for React Native. Also supports barcode scanning! *(archived)*
* [bilibili/DanmakuFlameMaster](https://github.com/bilibili/DanmakuFlameMaster) - Android开源弹幕引擎·烈焰弹幕使 ～
* [ksoichiro/Android-ObservableScrollView](https://github.com/ksoichiro/Android-ObservableScrollView) - Android library to observe scroll events on scrollable views.
* [MyCATApache/Mycat-Server](https://github.com/MyCATApache/Mycat-Server)
* [liaohuqiu/android-Ultra-Pull-To-Refresh](https://github.com/liaohuqiu/android-Ultra-Pull-To-Refresh) - Ultra Pull to Refresh for Android. Support all the views.
* [crossoverJie/cim](https://github.com/crossoverJie/cim) - 📲cim(cross IM) 适用于开发者的分布式即时通讯系统
* [umano/AndroidSlidingUpPanel](https://github.com/umano/AndroidSlidingUpPanel) - This library provides a simple way to add a draggable sliding up panel (popularized by Google Music and Google Maps) to your Android application. Brought to you by Umano.
* [Justson/AgentWeb](https://github.com/Justson/AgentWeb) - AgentWeb is a powerful library based on Android WebView.
* [FongMi/TV](https://github.com/FongMi/TV)
* [huanghaibin-dev/CalendarView](https://github.com/huanghaibin-dev/CalendarView) - RecyclerView? ListView or ViewGroup? No, it's Canvas! Ultra performance and free customization interface! Vertical and horizontal, Fast rendering and extremely low memory. Android上一个优雅、万能自定义UI、仿iOS、自定义动画，支持垂直、水平方向切换、支持周视图、自定义周起始、性能高效的日历控件，热插拔实现UI定制！Canvas绘制，渲染速度快、占用内存低，你真的想不到日历居然还可以如此优雅。
* [LSPosed/LSPatch](https://github.com/LSPosed/LSPatch) - LSPatch: A non-root Xposed framework extending from LSPosed *(archived)*
* [pockethub/PocketHub](https://github.com/pockethub/PocketHub) - PocketHub Android App
* [GcsSloop/AndroidNote](https://github.com/GcsSloop/AndroidNote) - 安卓学习笔记
* [android/testing-samples](https://github.com/android/testing-samples) - A collection of samples demonstrating different frameworks and techniques for automated testing
* [apache/iceberg](https://github.com/apache/iceberg) - Apache Iceberg
* [didi/VirtualAPK](https://github.com/didi/VirtualAPK) - A powerful and lightweight plugin framework for Android *(archived)*
* [iflytek/astron-agent](https://github.com/iflytek/astron-agent) - Enterprise-grade, commercial-friendly agentic workflow platform for building next-generation SuperAgents.
* [MuntashirAkon/AppManager](https://github.com/MuntashirAkon/AppManager) - A full-featured package manager and viewer for Android
* [karatelabs/karate](https://github.com/karatelabs/karate) - Test Automation Made Simple
* [Freelander/Android_Data](https://github.com/Freelander/Android_Data) - Some Android learning materials, hoping to help you learn Android development.
* [KunMinX/Jetpack-MVVM-Best-Practice](https://github.com/KunMinX/Jetpack-MVVM-Best-Practice) - 难得一见 Jetpack MVVM 最佳实践。在 "以简驭繁" 代码中，对 "视图控制器" 乃至 "标准化开发模式" 形成正确、深入理解。
* [navasmdc/MaterialDesignLibrary](https://github.com/navasmdc/MaterialDesignLibrary) - This is a library with components of Android L to you use in android 2.2
* [nathanmarz/storm](https://github.com/nathanmarz/storm) - Distributed and fault-tolerant realtime computation: stream processing, continuous computation, distributed RPC, and more
* [laobie/StatusBarUtil](https://github.com/laobie/StatusBarUtil) - A util for setting status bar style on Android App.
* [amitshekhariitbhu/Android-Debug-Database](https://github.com/amitshekhariitbhu/Android-Debug-Database) - A library for debugging android databases and shared preferences - Make Debugging Great Again
* [shwenzhang/AndResGuard](https://github.com/shwenzhang/AndResGuard) - proguard resource for Android by wechat team
* [chrisbanes/Android-PullToRefresh](https://github.com/chrisbanes/Android-PullToRefresh) - DEPRECATED *(archived)*
* [ybq/Android-SpinKit](https://github.com/ybq/Android-SpinKit) - Android loading animations
* [react-native-image-picker/react-native-image-picker](https://github.com/react-native-image-picker/react-native-image-picker) - :sunrise_over_mountains: A React Native module that allows you to use native UI to select media from the device library or directly from the camera.
* [google/tsunami-security-scanner](https://github.com/google/tsunami-security-scanner) - Tsunami is a general purpose network security scanner with an extensible plugin system for detecting high severity vulnerabilities with high confidence.
* [airbnb/epoxy](https://github.com/airbnb/epoxy) - Epoxy is an Android library for building complex screens in a RecyclerView
* [wildfirechat/im-server](https://github.com/wildfirechat/im-server) - 即时通讯(IM)系统
* [chrisjenx/Calligraphy](https://github.com/chrisjenx/Calligraphy) - Custom fonts in Android the easy way... *(archived)*
* [DImuthuUpe/AndroidPdfViewer](https://github.com/DImuthuUpe/AndroidPdfViewer) - Android view for displaying PDFs rendered with PdfiumAndroid
* [loks666/get_jobs](https://github.com/loks666/get_jobs) - 💼【AI找工作助手】全平台自动投简历脚本：(boss、前程无忧、猎聘、智联招聘)
* [pentaho/pentaho-kettle](https://github.com/pentaho/pentaho-kettle) - Pentaho Data Integration ( ETL ) a.k.a Kettle
* [bytedeco/javacv](https://github.com/bytedeco/javacv) - Java interface to OpenCV, FFmpeg, and more
* [exadel-inc/CompreFace](https://github.com/exadel-inc/CompreFace) - Leading free and open-source face recognition system
* [apache/shardingsphere-elasticjob](https://github.com/apache/shardingsphere-elasticjob) - Distributed scheduled job
* [AntennaPod/AntennaPod](https://github.com/AntennaPod/AntennaPod) - A podcast manager for Android
* [alibaba/atlas](https://github.com/alibaba/atlas) - A powerful Android Dynamic Component Framework.
* [freeok/so-novel](https://github.com/freeok/so-novel) - 小说下载｜网文下载 | 网络小说
* [Graylog2/graylog2-server](https://github.com/Graylog2/graylog2-server) - Free and open log management
* [alibaba/otter](https://github.com/alibaba/otter) - 阿里巴巴分布式数据库同步系统(解决中美异地机房)
* [aritraroy/UltimateAndroidReference](https://github.com/aritraroy/UltimateAndroidReference) - :rocket: Ultimate Android Reference - Your Road to Become a Better Android Developer
* [guolindev/LitePal](https://github.com/guolindev/LitePal) - An Android library that makes developers use SQLite database extremely easy.
* [junixapp/XPopup](https://github.com/junixapp/XPopup) - 🔥XPopup2.0版本重磅来袭，2倍以上性能提升，带来可观的动画性能优化和交互细节的提升！！！功能强大，交互优雅，动画丝滑的通用弹窗！可以替代Dialog，PopupWindow，PopupMenu，BottomSheet，DrawerLayout，Spinner等组件，自带十几种效果良好的动画， 支持完全的UI和动画自定义！(Powerful and Beautiful Popup for Android，can absolutely replace Dialog，PopupWindow，PopupMenu，BottomSheet，DrawerLayout，Spinner. With built-in animators , very easy to custom popup view.)
* [davemorrissey/subsampling-scale-image-view](https://github.com/davemorrissey/subsampling-scale-image-view) - Android library (AAR). Highly configurable, easily extendable deep zoom view for displaying huge images without loss of detail. Perfect for photo galleries, maps, building plans etc.
* [Netflix/SimianArmy](https://github.com/Netflix/SimianArmy) - Tools for keeping your cloud operating in top form. Chaos Monkey is a resiliency tool that helps applications tolerate random instance failures. *(archived)*
* [snehasishroy/leetcode-companywise-interview-questions](https://github.com/snehasishroy/leetcode-companywise-interview-questions) - Contains latest company wise questions of LeetCode as of July 2026.
* [Genymobile/gnirehtet](https://github.com/Genymobile/gnirehtet) - Gnirehtet provides reverse tethering for Android
* [JakeWharton/hugo](https://github.com/JakeWharton/hugo) - Annotation-triggered method call logging for your debug builds.
* [HannahMitt/HomeMirror](https://github.com/HannahMitt/HomeMirror) - Android application powering the mirror in my house
* [PowerJob/PowerJob](https://github.com/PowerJob/PowerJob) - Enterprise job scheduling middleware with distributed computing ability.
* [Tencent/Shadow](https://github.com/Tencent/Shadow) - 零反射全动态Android插件框架
* [ChrisRM/material-theme-jetbrains](https://github.com/ChrisRM/material-theme-jetbrains) - JetBrains theme of Material Theme
* [goldze/MVVMHabit](https://github.com/goldze/MVVMHabit) - 👕基于谷歌最新AAC架构，MVVM设计模式的一套快速开发库，整合Okhttp+RxJava+Retrofit+Glide等主流模块，满足日常开发需求。使用该框架可以快速开发一个高质量、易维护的Android应用。
* [Suwayomi/Suwayomi-Server](https://github.com/Suwayomi/Suwayomi-Server) - A rewrite of Tachiyomi for the Desktop
* [dependency-check/DependencyCheck](https://github.com/dependency-check/DependencyCheck) - OWASP dependency-check is a software composition analysis utility that detects publicly disclosed vulnerabilities in application dependencies.
* [gedoor/MyBookshelf](https://github.com/gedoor/MyBookshelf) - 阅读是一款可以自定义来源阅读网络内容的工具，为广大网络文学爱好者提供一种方便、快捷舒适的试读体验。
* [trello-archive/RxLifecycle](https://github.com/trello-archive/RxLifecycle) - Lifecycle handling APIs for Android apps using RxJava
* [logisim-evolution/logisim-evolution](https://github.com/logisim-evolution/logisim-evolution) - Digital logic design tool and simulator
* [lecho/hellocharts-android](https://github.com/lecho/hellocharts-android) - Charts library for Android compatible with API 8+, several chart types with scaling, scrolling and animations 📊
* [koush/AndroidAsync](https://github.com/koush/AndroidAsync) - Asynchronous socket, http(s) (client+server) and websocket library for android. Based on nio, not threads.
* [kevin-wayne/algs4](https://github.com/kevin-wayne/algs4) - Algorithms, 4th edition textbook code and libraries
* [yuanguangxin/LeetCode](https://github.com/yuanguangxin/LeetCode) - LeetCode刷题记录与面试整理
* [enso-org/enso](https://github.com/enso-org/enso) - Enso Analytics is a self-service data prep and analysis platform designed for data teams.
* [gocd/gocd](https://github.com/gocd/gocd) - GoCD - Continuous Delivery server main repository
* [lenve/VBlog](https://github.com/lenve/VBlog) - V部落，Vue+SpringBoot实现的多用户博客管理平台!
* [apache/hertzbeat](https://github.com/apache/hertzbeat) - An AI-powered next-generation open source real-time observability system.
* [dyc87112/SpringCloud-Learning](https://github.com/dyc87112/SpringCloud-Learning) - Spring Cloud基础教程，持续连载更新中
* [abel533/Mapper](https://github.com/abel533/Mapper) - Mybatis Common Mapper - Easy to use
* [Qihoo360/RePlugin](https://github.com/Qihoo360/RePlugin) - RePlugin - A flexible, stable, easy-to-use Android Plug-in Framework
* [leolin310148/ShortcutBadger](https://github.com/leolin310148/ShortcutBadger) - An Android library supports badge notification like iOS in Samsung, LG, Sony and HTC launchers.
* [648540858/wvp-GB28181-pro](https://github.com/648540858/wvp-GB28181-pro) - 基于GB28181-2016、部标808、部标1078标准实现的开箱即用的网络视频平台。自带管理页面，支持NAT穿透，支持海康、大华、宇视等品牌的IPC、NVR接入。支持国标级联，支持将普通摄像机/直播流/直播推流转国标共享到国标平台。
* [Alluxio/alluxio](https://github.com/Alluxio/alluxio) - Alluxio, data orchestration for analytics and machine learning in the cloud
* [Exrick/xmall](https://github.com/Exrick/xmall) - 基于SOA架构的分布式电商购物商城 前后端分离 前台商城:Vue全家桶 后台管理系统:Dubbo/SSM/Elasticsearch/Redis/MySQL/ActiveMQ/Shiro/Zookeeper等
* [zhongyi-tong/WeChatLuckyMoney](https://github.com/zhongyi-tong/WeChatLuckyMoney) - :money_with_wings: WeChat's lucky money helper (微信抢红包插件) by Zhongyi Tong. An Android app that helps you snatch red packets in WeChat groups. *(archived)*
* [crazycodeboy/TakePhoto](https://github.com/crazycodeboy/TakePhoto) - 一款用于在Android设备上获取照片（拍照或从相册、文件中选择）、裁剪图片、压缩图片的开源工具库
* [pedant/sweet-alert-dialog](https://github.com/pedant/sweet-alert-dialog) - SweetAlert for Android, a beautiful and clever alert dialog
* [didi/KnowStreaming](https://github.com/didi/KnowStreaming) - 一站式云原生实时流数据平台，通过0侵入、插件化构建企业级Kafka服务，极大降低操作、存储和管理实时流数据门槛
* [google/agera](https://github.com/google/agera) - Reactive Programming for Android *(archived)*
* [ogaclejapan/SmartTabLayout](https://github.com/ogaclejapan/SmartTabLayout) - A custom ViewPager title strip which gives continuous feedback to the user when scrolling *(archived)*
* [JakeWharton/ActionBarSherlock](https://github.com/JakeWharton/ActionBarSherlock) - [DEPRECATED] Action bar implementation which uses the native action bar on Android 4.0+ and a custom implementation on pre-4.0 through a single API and theme. *(archived)*
* [naman14/Timber](https://github.com/naman14/Timber) - Material Design Music Player
* [NLPchina/elasticsearch-sql](https://github.com/NLPchina/elasticsearch-sql) - Use SQL to query Elasticsearch
* [DroidPluginTeam/DroidPlugin](https://github.com/DroidPluginTeam/DroidPlugin) - A plugin framework on android,Run any third-party apk without installation, modification or repackage
* [alibaba/jvm-sandbox](https://github.com/alibaba/jvm-sandbox) - Real - time non-invasive AOP framework container based on JVM
* [smuyyh/BookReader](https://github.com/smuyyh/BookReader) - :closed_book: "任阅" 网络小说阅读器，3D翻页效果、txt/pdf/epub书籍阅读、Wifi传书~
* [getActivity/AndroidProject](https://github.com/getActivity/AndroidProject) - Android 技术中台，但愿人长久，搬砖不再有
* [rabbitmq/rabbitmq-tutorials](https://github.com/rabbitmq/rabbitmq-tutorials) - Tutorials for using RabbitMQ in various ways
* [Meituan-Dianping/walle](https://github.com/Meituan-Dianping/walle) - Android Signature V2 Scheme签名下的新一代渠道包打包神器
* [hongyangAndroid/okhttputils](https://github.com/hongyangAndroid/okhttputils) - [停止维护]okhttp的辅助类
* [guardianproject/haven](https://github.com/guardianproject/haven) - Haven is for people who need a way to protect their personal spaces and possessions without compromising their own privacy, through an Android app and on-device sensors
* [getActivity/XXPermissions](https://github.com/getActivity/XXPermissions) - Android Permissions Framework, Adapt to Android 17
* [Angel-ML/angel](https://github.com/Angel-ML/angel) - A Flexible and Powerful Parameter Server for large-scale machine learning
* [gzu-liyujiang/AndroidPicker](https://github.com/gzu-liyujiang/AndroidPicker) - 安卓选择器类库，包括日期及时间选择器（可用于出生日期、营业时间等）、单项选择器（可用于性别、民族、职业、学历、星座等）、二三级联动选择器（可用于车牌号、基金定投日期等）、城市地址选择器（分省级、地市级及区县级）、数字选择器（可用于年龄、身高、体重、温度等）、日历选日期择器（可用于酒店及机票预定日期）、颜色选择器、文件及目录选择器、图片选择器等……WheelPicker/DatePicker/TimePicker/OptionPicker/NumberPicker/LinkagePicker/AddressPicker/CarPlatePicker/CalendarPicker/ColorPicker/FilePicker/ImagePicker etc.
* [zo0r/react-native-push-notification](https://github.com/zo0r/react-native-push-notification) - React Native Local and Remote Notifications *(archived)*
* [Meituan-Dianping/Leaf](https://github.com/Meituan-Dianping/Leaf) - Distributed ID Generate Service
* [527515025/springBoot](https://github.com/527515025/springBoot) - springboot 框架与其它组件结合如 jpa、mybatis、websocket、security、shiro、cache等
* [quartz-scheduler/quartz](https://github.com/quartz-scheduler/quartz) - Code for Quartz Scheduler
* [markzhai/AndroidPerformanceMonitor](https://github.com/markzhai/AndroidPerformanceMonitor) - A transparent ui-block detection library for Android. (known as BlockCanary)
* [graphhopper/graphhopper](https://github.com/graphhopper/graphhopper) - Open source routing engine for OpenStreetMap. Use it as Java library or standalone web server.
* [pig-mesh/pig](https://github.com/pig-mesh/pig) - ↥ ↥ ↥ Follow for updates An RBAC permission management system based on Spring Cloud 2025, Spring Boot 4, and OAuth2.
* [zouzg/mybatis-generator-gui](https://github.com/zouzg/mybatis-generator-gui) - mybatis-generator界面工具，让你生成代码更简单更快捷
* [hongyangAndroid/AndroidAutoLayout](https://github.com/hongyangAndroid/AndroidAutoLayout) - [停止维护]Android屏幕适配方案，直接填写设计图上的像素尺寸即可完成适配，最大限度解决适配问题。
* [JesusFreke/smali](https://github.com/JesusFreke/smali) - smali/baksmali *(archived)*
* [yanzhenjie/AndPermission](https://github.com/yanzhenjie/AndPermission) - :strawberry: Permissions manager for Android platform.
* [Javen205/IJPay](https://github.com/Javen205/IJPay) - IJPay 让支付触手可及，封装了微信支付、QQ支付、支付宝支付、京东支付、银联支付、PayPal 支付等常用的支付方式以及各种常用的接口。不依赖任何第三方 mvc 框架，仅仅作为工具使用简单快速完成支付模块的开发，可轻松嵌入到任何系统里。右上角点下小星星✨
* [GrenderG/Toasty](https://github.com/GrenderG/Toasty) - The usual Toast, but with steroids 💪
* [ximsfei/Android-skin-support](https://github.com/ximsfei/Android-skin-support) - Android-skin-support is an easy dynamic skin framework to use for Android, Only one line of code to integrate it. Android 换肤框架, 极低的学习成本, 极好的用户体验. "一行"代码就可以实现换肤, 你值得拥有!!!
* [processing/processing](https://github.com/processing/processing) - ⚠️ Processing moved to processing/processing4 ⚠️
* [apache/flink-cdc](https://github.com/apache/flink-cdc) - Flink CDC is a streaming data integration tool
* [ArthurHub/Android-Image-Cropper](https://github.com/ArthurHub/Android-Image-Cropper) - Image Cropping Library for Android, optimized for Camera / Gallery.
* [haifengl/smile](https://github.com/haifengl/smile) - Statistical Machine Intelligence & Learning Engine
* [wxiaoqi/Spring-Cloud-Platform](https://github.com/wxiaoqi/Spring-Cloud-Platform) - 🔥🔥🔥国内首个Spring Cloud微服务化RBAC的管理平台，核心采用Spring Boot 2.4、Spring Cloud 2020.0.0 & Alibaba，前端采用d2-admin中台框架。 🔝 🔝 记得上边点个star 关注更新
* [vinc3m1/RoundedImageView](https://github.com/vinc3m1/RoundedImageView) - A fast ImageView that supports rounded corners, ovals, and circles. *(archived)*
* [aa112901/remusic](https://github.com/aa112901/remusic) - 仿网易云音乐 安卓版，netease android，音乐播放器 在线 下载
* [ikarus23/MifareClassicTool](https://github.com/ikarus23/MifareClassicTool) - An Android NFC app for reading, writing, analyzing, etc. MIFARE Classic RFID tags.
* [jeequan/jeepay](https://github.com/jeequan/jeepay) - Jeepay是一套适合互联网企业使用的开源支付系统，支持多渠道服务商和普通商户模式。已对接微信支付，支付宝，云闪付官方接口，支持聚合码支付。
* [DerekYRC/mini-spring](https://github.com/DerekYRC/mini-spring) - mini-spring is a simplified version of the Spring framework that helps you quickly familiarize yourself with Spring source code and master Spring's core principles. It extracts Spring's core logic with extremely simplified code while preserving Spring's core functionality.
* [SuperMonster003/AutoJs6](https://github.com/SuperMonster003/AutoJs6) - 安卓平台 JavaScript 自动化工具 (Auto.js 二次开发项目)
* [wasabeef/richeditor-android](https://github.com/wasabeef/richeditor-android) - RichEditor for Android is a beautiful Rich Text WYSIWYG Editor for Android.
* [sshahine/JFoenix](https://github.com/sshahine/JFoenix) - JavaFX Material Design Library
* [lightbend/config](https://github.com/lightbend/config) - configuration library for JVM languages using HOCON files
* [zhukunpenglinyutong/jetbrains-cc-gui](https://github.com/zhukunpenglinyutong/jetbrains-cc-gui) - Jetbrains Claude Code and Codex GUI Plugin
* [alipay/SoloPi](https://github.com/alipay/SoloPi) - SoloPi 自动化测试工具
* [PBH-BTN/PeerBanHelper](https://github.com/PBH-BTN/PeerBanHelper) - Automatically block unwanted, leeches and abnormal BT peers with support for customized and cloud rules.| BT 反吸血工具 - 自动封禁不受欢迎、吸血和异常的 BT 客户端，并支持自定义规则。支持 qB/qBEE/Deluge/BiglyBT/BitComet
* [apache/hudi](https://github.com/apache/hudi) - Upserts, Deletes And Incremental Processing on Big Data.
* [koush/ion](https://github.com/koush/ion) - Android Asynchronous Networking and Image Loading
* [Archmage83/tvapk](https://github.com/Archmage83/tvapk) - 收集各大AndroidTV的apk应用，可免费看vip和国外电影电视。如大家有也可以贡献一下。
* [Vedenin/useful-java-links](https://github.com/Vedenin/useful-java-links) - A list of useful Java frameworks, libraries, software and hello worlds examples
* [ityouknow/spring-cloud-examples](https://github.com/ityouknow/spring-cloud-examples) - Spring Cloud 学习案例，服务发现、服务治理、链路追踪、服务监控等
* [obsidiandynamics/kafdrop](https://github.com/obsidiandynamics/kafdrop) - Kafka Web UI
* [google/grafika](https://github.com/google/grafika) - Grafika test app *(archived)*
* [LandGrey/SpringBootVulExploit](https://github.com/LandGrey/SpringBootVulExploit) - SpringBoot 相关漏洞学习资料，利用方法和技巧合集，黑盒安全评估 check list
* [gsantner/markor](https://github.com/gsantner/markor) - Text editor - Notes & ToDo (for Android) - Markdown, todo.txt, plaintext, math, ..
* [daimajia/NumberProgressBar](https://github.com/daimajia/NumberProgressBar) - A beautiful, slim Android ProgressBar.
* [ZhongFuCheng3y/austin](https://github.com/ZhongFuCheng3y/austin) - 消息推送平台🔥 推送下发【邮件】【短信】【微信服务号】【微信小程序】【企业微信】【钉钉】等消息类型。
* [ikew0ng/SwipeBackLayout](https://github.com/ikew0ng/SwipeBackLayout) - An Android library that help you to build app with swipe back gesture.
* [rengwuxian/MaterialEditText](https://github.com/rengwuxian/MaterialEditText) - EditText in Material Design *(archived)*
* [youtube/api-samples](https://github.com/youtube/api-samples) - Code samples for YouTube APIs, including the YouTube Data API, YouTube Analytics API, and YouTube Live Streaming API. The repo contains language-specific directories that contain the samples. *(archived)*
* [WeiYe-Jing/datax-web](https://github.com/WeiYe-Jing/datax-web) - DataX集成可视化页面，选择数据源即可一键生成数据同步任务，支持RDBMS、Hive、HBase、ClickHouse、MongoDB等数据源，批量创建RDBMS数据同步任务，集成开源调度系统，支持分布式、增量同步数据、实时查看运行日志、监控执行器资源、KILL运行进程、数据源信息加密等。
* [osmandapp/OsmAnd](https://github.com/osmandapp/OsmAnd) - OsmAnd
* [hneemann/Digital](https://github.com/hneemann/Digital) - A digital logic designer and circuit simulator.
* [singwhatiwanna/dynamic-load-apk](https://github.com/singwhatiwanna/dynamic-load-apk) - DL : dynamic load framework in android
* [TGX-Android/Telegram-X](https://github.com/TGX-Android/Telegram-X) - The main repository of Telegram X — official alternative Telegram client for Android.
* [pedrovgs/EffectiveAndroidUI](https://github.com/pedrovgs/EffectiveAndroidUI) - Sample project created to show some of the best Android practices to work in the Android UI Layer. The UI layer of this project has been implemented using MVP or MVVM (without binding engine) to show how this patterns works. This project is used during the talk "EffectiveAndroidUI".
* [google/physical-web](https://github.com/google/physical-web) - The Physical Web: walk up and use anything *(archived)*
* [wyouflf/xUtils3](https://github.com/wyouflf/xUtils3) - Android orm, bitmap, http, view inject...
* [strimzi/strimzi-kafka-operator](https://github.com/strimzi/strimzi-kafka-operator) - Apache Kafka® running on Kubernetes
* [journeyapps/zxing-android-embedded](https://github.com/journeyapps/zxing-android-embedded) - Barcode scanner library for Android, based on the ZXing decoder
* [meefik/linuxdeploy](https://github.com/meefik/linuxdeploy) - Install and run GNU/Linux on Android
* [amitshekhariitbhu/Fast-Android-Networking](https://github.com/amitshekhariitbhu/Fast-Android-Networking) - 🚀 A Complete Fast Android Networking Library that also supports HTTP/2 🚀
* [antoniolg/androidmvp](https://github.com/antoniolg/androidmvp) - MVP Android Example *(archived)*
* [jindrapetrik/jpexs-decompiler](https://github.com/jindrapetrik/jpexs-decompiler) - JPEXS Free Flash Decompiler
* [lets-blade/blade](https://github.com/lets-blade/blade) - :rocket: Lightning fast and elegant mvc framework for Java8
* [weibocom/motan](https://github.com/weibocom/motan) - A cross-language remote procedure call(RPC) framework for rapid development of high performance distributed services.
* [ddd-by-examples/library](https://github.com/ddd-by-examples/library) - A comprehensive Domain-Driven Design example with problem space strategic analysis and various tactical patterns.
* [microsoft/typespec](https://github.com/microsoft/typespec)
* [JanusGraph/janusgraph](https://github.com/JanusGraph/janusgraph) - JanusGraph: an open-source, distributed graph database
* [Nightonke/BoomMenu](https://github.com/Nightonke/BoomMenu) - A menu which can ... BOOM! - Android
* [yarolegovich/DiscreteScrollView](https://github.com/yarolegovich/DiscreteScrollView) - A scrollable list of items that centers the current element and provides easy-to-use APIs for cool item animations.
* [CaffeineMC/sodium](https://github.com/CaffeineMC/sodium) - A high-performance rendering engine replacement for Minecraft, which greatly improves frame rates and reduces micro-stutter
* [tonikelope/megabasterd](https://github.com/tonikelope/megabasterd) - Yet another unofficial (and ugly) cross-platform MEGA downloader/uploader/streaming suite.
* [Nepxion/Discovery](https://github.com/Nepxion/Discovery) - ☀️ Nepxion Discovery is a solution for Spring Cloud with blue green, gray, route, limitation, circuit breaker, degrade, isolation, tracing, dye, failover, active 蓝绿灰度发布、路由、限流、熔断、降级、隔离、追踪、流量染色、故障转移、多活
* [cinit/QAuxiliary](https://github.com/cinit/QAuxiliary) - QNotified phoenix - To make OICQ great again
* [dmytrodanylyk/circular-progress-button](https://github.com/dmytrodanylyk/circular-progress-button) - Android Circular Progress Button
* [k0shk0sh/FastHub](https://github.com/k0shk0sh/FastHub) - FastHub the ultimate GitHub client for Android. *(archived)*
* [killbill/killbill](https://github.com/killbill/killbill) - Open-Source Subscription Billing & Payments Platform
* [yanzhenjie/SwipeRecyclerView](https://github.com/yanzhenjie/SwipeRecyclerView) - :melon: RecyclerView侧滑菜单，Item拖拽，滑动删除Item，自动加载更多，HeaderView，FooterView，Item分组黏贴。
* [ageerle/ruoyi-ai](https://github.com/ageerle/ruoyi-ai) - An enterprise AI development framework for building AI agents. It provides unified management of multi-provider LLMs, secure enterprise knowledge bases with high-precision retrieval, visual workflow orchestration and multi-agent coordination. Compatible with mainstream Agent Skill standards, it enables developers to efficiently build production-gra
* [jpush/aurora-imui](https://github.com/jpush/aurora-imui) - General IM UI components. Android/iOS/RectNative ready. 通用 IM 聊天 UI 组件，已经同时支持 Android/iOS/RN。
* [mik3y/usb-serial-for-android](https://github.com/mik3y/usb-serial-for-android) - Android USB host serial driver library for CDC, FTDI, Arduino and other devices.
* [Devlight/InfiniteCycleViewPager](https://github.com/Devlight/InfiniteCycleViewPager) - Infinite cycle ViewPager with two-way orientation and interactive effect.
* [ElderDrivers/EdXposed](https://github.com/ElderDrivers/EdXposed) - Elder driver Xposed Framework.
* [crazycodeboy/react-native-splash-screen](https://github.com/crazycodeboy/react-native-splash-screen) - A splash screen for react-native, hide when application loaded ,it works on iOS and Android.
* [springside/springside4](https://github.com/springside/springside4) - A Spring Framework based, pragmatic style JavaEE application reference architecture.
* [hanks-zyh/HTextView](https://github.com/hanks-zyh/HTextView) - Animation effects to text, not really textview
* [JakeWharton/u2020](https://github.com/JakeWharton/u2020) - A sample Android app which showcases advanced usage of Dagger among other open source libraries.
* [TommyLemon/Android-ZBLibrary](https://github.com/TommyLemon/Android-ZBLibrary) - 🔥 Android MVP 快速开发框架，做国内 「示例最全面」「注释最详细」「使用最简单」「代码最严谨」的 Android 开源 UI 框架。 🔥 An Android MVP Framework with many demos, detailed documents, simple usages and strict codes.
* [daimajia/AndroidImageSlider](https://github.com/daimajia/AndroidImageSlider) - An amazing and convenient Android image slider.
* [hongyangAndroid/FlowLayout](https://github.com/hongyangAndroid/FlowLayout) - [不再维护]Android流式布局，支持单选、多选等，适合用于产品标签等。
* [baidu/uid-generator](https://github.com/baidu/uid-generator) - UniqueID generator
* [iflytek/astron-rpa](https://github.com/iflytek/astron-rpa) - Agent-ready RPA suite with out-of-the-box automation tools. Built for individuals and enterprises.
* [amlcurran/ShowcaseView](https://github.com/amlcurran/ShowcaseView) - [Archived] Highlight the best bits of your app to users quickly, simply, and cool...ly *(archived)*
* [knightliao/disconf](https://github.com/knightliao/disconf) - Distributed Configuration Management Platform(分布式配置管理平台)
* [nhaarman/ListViewAnimations](https://github.com/nhaarman/ListViewAnimations) - [DEPRECATED] An Android library which allows developers to easily add animations to ListView items *(archived)*
* [wuhaoyu1990/MagicCamera](https://github.com/wuhaoyu1990/MagicCamera) - Real-time Filter Camera&VideoRecorder And ImageEditor With Face Beauty For Android---包含美颜等40余种实时滤镜相机，可拍照、录像、图片修改
* [Jasonchenlijian/FastBle](https://github.com/Jasonchenlijian/FastBle) - Android Bluetooth Low Energy (BLE) Fast Development Framework. It uses simple ways to filter, scan, connect, read ,write, notify, readRssi, setMTU, and multiConnection.
* [danikula/AndroidVideoCache](https://github.com/danikula/AndroidVideoCache) - Cache support for any video player with help of single line
* [apache/groovy](https://github.com/apache/groovy) - Apache Groovy: A powerful multi-faceted programming language for the JVM platform
* [motianhuo/wechat](https://github.com/motianhuo/wechat) - A High Copy WeChat ,SNS APP (高仿微信)
* [emilsjolander/StickyListHeaders](https://github.com/emilsjolander/StickyListHeaders) - An android library for section headers that stick to the top
* [KeepSafe/TapTargetView](https://github.com/KeepSafe/TapTargetView) - An implementation of tap targets from the Material Design guidelines for feature discovery.
* [runelite/runelite](https://github.com/runelite/runelite) - Open source Old School RuneScape client
* [LWJGL/lwjgl3](https://github.com/LWJGL/lwjgl3) - LWJGL is a Java library that enables cross-platform access to popular native APIs useful in the development of graphics (OpenGL, Vulkan, bgfx), audio (OpenAL, Opus), parallel computing (OpenCL, CUDA) and XR (OpenVR, LibOVR, OpenXR) applications.
* [alibaba/freeline](https://github.com/alibaba/freeline) - A super fast build tool for Android, an alternative to Instant Run
* [dm77/barcodescanner](https://github.com/dm77/barcodescanner) - Barcode Scanner Libraries for Android *(archived)*
* [remkop/picocli](https://github.com/remkop/picocli) - Picocli is a modern framework for building powerful, user-friendly, GraalVM-enabled command line apps with ease. It supports colors, autocompletion, subcommands, and more. In 1 source file so apps can include as source & avoid adding a dependency. Written in Java, usable from Groovy, Kotlin, Scala, etc.
* [spring-projects/spring-data-examples](https://github.com/spring-projects/spring-data-examples) - Spring Data Example Projects
* [CellularPrivacy/Android-IMSI-Catcher-Detector](https://github.com/CellularPrivacy/Android-IMSI-Catcher-Detector) - AIMSICD • Fight IMSI-Catcher, StingRay and silent SMS!
* [ReChronoRain/HyperCeiler](https://github.com/ReChronoRain/HyperCeiler) - HyperOS enhancement module - Make HyperOS Great Again!
* [apache/dubbo-spring-boot-project](https://github.com/apache/dubbo-spring-boot-project) - Spring Boot Project for Apache Dubbo
* [dunwu/db-tutorial](https://github.com/dunwu/db-tutorial) - 📚 后端程序员应该掌握的主流数据库知识
* [Fuzion24/JustTrustMe](https://github.com/Fuzion24/JustTrustMe) - An xposed module that disables SSL certificate checking for the purposes of auditing an app with cert pinning
* [google/google-authenticator](https://github.com/google/google-authenticator) - Open source version of Google Authenticator (except the Android app) *(archived)*
* [novicezk/midjourney-proxy](https://github.com/novicezk/midjourney-proxy) - 代理 MidJourney 的discord频道，实现api形式调用AI绘图
* [facebookarchive/shimmer-android](https://github.com/facebookarchive/shimmer-android) - An easy, flexible way to add a shimmering effect to any view in an Android app. *(archived)*
* [Evernote/android-job](https://github.com/Evernote/android-job) - Android library to handle jobs in the background.
* [Doikki/DKVideoPlayer](https://github.com/Doikki/DKVideoPlayer) - Android Video Player. 安卓视频播放器，封装MediaPlayer、ExoPlayer、IjkPlayer。模仿抖音并实现预加载，列表播放，悬浮播放，广告播放，弹幕，视频水印，视频滤镜
* [h6ah4i/android-advancedrecyclerview](https://github.com/h6ah4i/android-advancedrecyclerview) - RecyclerView extension library which provides advanced features. (ex. Google's Inbox app like swiping, Play Music app like drag and drop sorting)
* [zfdang/Android-Touch-Helper](https://github.com/zfdang/Android-Touch-Helper) - AdSkip — an Android assistant for automatically skipping app launch ads
* [commonsguy/cw-omnibus](https://github.com/commonsguy/cw-omnibus) - Source code to omnibus edition of _The Busy Coder's Guide to Android Development_
* [jgilfelt/SystemBarTint](https://github.com/jgilfelt/SystemBarTint) - [DEPRECATED] Apply background tinting to the Android system UI when using KitKat translucent modes
* [mybatis/generator](https://github.com/mybatis/generator) - A code generator for MyBatis.
* [Exrick/xpay](https://github.com/Exrick/xpay) - XPay个人免签收款支付系统 完全免费 资金直接到达本人账号 支持 支付宝 微信 QQ 云闪付 无需备案 无需签约 无需挂机监控APP 无需插件 无需第三方支付SDK 无需营业执照身份证 只需收款码 搞定支付流程 现已支持移动端支付
* [citerus/dddsample-core](https://github.com/citerus/dddsample-core) - This is the new home of the original DDD Sample app (previously hosted at sf.net)..
* [XRecyclerView/XRecyclerView](https://github.com/XRecyclerView/XRecyclerView) - A RecyclerView that implements pullrefresh and loadingmore featrues.you can use it like a standard RecyclerView
* [crimera/piko](https://github.com/crimera/piko) - morphe patches for twitter and instagram
* [CodingDocs/springboot-guide](https://github.com/CodingDocs/springboot-guide) - SpringBoot2.0+从入门到实战！
* [j-easy/easy-rules](https://github.com/j-easy/easy-rules) - The simple, stupid rules engine for Java
* [yixia/VitamioBundle](https://github.com/yixia/VitamioBundle) - Vitamio for Android
* [razerdp/BasePopup](https://github.com/razerdp/BasePopup) - Android下打造通用便捷的PopupWindow弹窗库
* [xxv/android-lifecycle](https://github.com/xxv/android-lifecycle) - A diagram of the Android Activity / Fragment lifecycle
* [lingochamp/okdownload](https://github.com/lingochamp/okdownload) - A Reliable, Flexible, Fast and Powerful download engine.
* [reactor/reactor-core](https://github.com/reactor/reactor-core) - Non-Blocking Reactive Foundation for the JVM
* [brianfrankcooper/YCSB](https://github.com/brianfrankcooper/YCSB) - Yahoo! Cloud Serving Benchmark
* [thinkaurelius/titan](https://github.com/thinkaurelius/titan) - Distributed Graph Database
* [huangyanbin/smartTable](https://github.com/huangyanbin/smartTable) - 一款android自动生成表格框架---An Android automatically generated table framework
* [zhkl0228/unidbg](https://github.com/zhkl0228/unidbg) - Allows you to emulate an Android native library, and an experimental iOS emulation
* [NotHarshhaa/DevOps-Projects](https://github.com/NotHarshhaa/DevOps-Projects) - 🚀 Real-world DevOps projects for aspiring engineers — Beginner to Advanced. Covers AWS, Kubernetes, Docker, CI/CD, Terraform, Jenkins, and more. Hands-on learning with step-by-step guides.
* [Threekiii/Awesome-POC](https://github.com/Threekiii/Awesome-POC) - 一个漏洞 PoC 知识库。A knowledge base for vulnerability PoCs(Proof of Concept), with 1k+ vulnerabilities.
* [lucasr/twoway-view](https://github.com/lucasr/twoway-view) - [DEPRECATED] RecyclerView made simple *(archived)*
* [Karumi/Dexter](https://github.com/Karumi/Dexter) - Android library that simplifies the process of requesting permissions at runtime. *(archived)*
* [hustcc/JS-Sorting-Algorithm](https://github.com/hustcc/JS-Sorting-Algorithm) - 一本关于排序算法的 GitBook 在线书籍 《十大经典排序算法》，多语言实现。
* [baomidou/dynamic-datasource](https://github.com/baomidou/dynamic-datasource) - dynamic datasource for springboot 多数据源 动态数据源 主从分离 读写分离 分布式事务
* [tianshiyeben/wgcloud](https://github.com/tianshiyeben/wgcloud) - Linux运维监控工具，支持系统硬件信息，内存，CPU，温度，磁盘空间及IO，硬盘smart，GPU，防火墙，网络流量速率等监控，服务接口监测，大屏展示，拓扑图，端口监控，进程监控，docker监控，日志监控，文件防篡改，数据库监控，指令批量下发执行，web ssh，Linux面板(探针)，告警，SNMP监测，K8S，Redis，Nginx，Kafka，资产管理，计划任务，密码管理，工作笔记
* [Clans/FloatingActionButton](https://github.com/Clans/FloatingActionButton) - Android Floating Action Button based on Material Design specification *(archived)*
* [android/views-widgets-samples](https://github.com/android/views-widgets-samples) - Multiple samples showing the best practices in views-widgets on Android. *(archived)*
* [line/armeria](https://github.com/line/armeria) - Your go-to microservice framework for any situation, from the creator of Netty et al. You can build any type of microservice leveraging your favorite technologies, including gRPC, Thrift, Kotlin, Retrofit, Reactive Streams, Spring Boot and Dropwizard.
* [careercup/ctci](https://github.com/careercup/ctci) - Cracking the Coding Interview, 5th Edition
* [grobidOrg/grobid](https://github.com/grobidOrg/grobid) - A machine learning software for extracting information from scholarly documents
* [natario1/CameraView](https://github.com/natario1/CameraView) - 📸 A well documented, high-level Android interface that makes capturing pictures and videos easy, addressing all of the common issues and needs. Real-time filters, gestures, watermarks, frame processing, RAW, output of any size.
* [iflytek/skillhub](https://github.com/iflytek/skillhub) - Self-hosted, open-source agent skill registry for enterprises. Publish & version skill packages, govern with RBAC and audit logs, deploy on-premise with Docker or Kubernetes.
* [angryip/ipscan](https://github.com/angryip/ipscan) - Angry IP Scanner - fast and friendly network scanner
* [square/otto](https://github.com/square/otto) - An enhanced Guava-based event bus with emphasis on Android support. *(archived)*
* [spring-attic/spring-authorization-server](https://github.com/spring-attic/spring-authorization-server) - Spring Authorization Server *(archived)*
* [tencentmusic/supersonic](https://github.com/tencentmusic/supersonic) - SuperSonic is the next-generation AI+BI platform that unifies Chat BI (powered by LLM) and Headless BI (powered by semantic layer) paradigms.
* [apache/ignite](https://github.com/apache/ignite) - Apache Ignite
* [xuexiangjys/XUI](https://github.com/xuexiangjys/XUI) - 💍A simple and elegant Android native UI framework, free your hands! (一个简洁而优雅的Android原生UI框架，解放你的双手！)
* [sofastack/sofa-boot](https://github.com/sofastack/sofa-boot) - SOFABoot is a framework that enhances Spring Boot and fully compatible with it, provides readiness check, class isolation, etc.
* [OpenTSDB/opentsdb](https://github.com/OpenTSDB/opentsdb) - A scalable, distributed Time Series Database.
* [rstudio/rstudio](https://github.com/rstudio/rstudio) - RStudio is an integrated development environment (IDE) for R
* [wequick/Small](https://github.com/wequick/Small) - A small framework to split app into small parts
* [youlookwhat/CloudReader](https://github.com/youlookwhat/CloudReader) - 🗡️ 云阅：一款基于网易云音乐UI，使用玩Android Api，Retrofit2 + RxJava2 + Room + MVVM-databinding架构开发的Android客户端
* [Trinea/android-common](https://github.com/Trinea/android-common) - Android common lib, include ImageCache, HttpCache, DropDownListView, DownloadManager, Utils and so on
* [react-native-webrtc/react-native-webrtc](https://github.com/react-native-webrtc/react-native-webrtc) - The WebRTC module for React Native
* [yipianfengye/android-zxingLibrary](https://github.com/yipianfengye/android-zxingLibrary) - 几行代码快速集成二维码扫描功能
* [roncoo/roncoo-pay](https://github.com/roncoo/roncoo-pay) - 龙果支付系统（roncoo-pay）是国内首款开源的互联网支付系统，拥有独立的账户体系、用户体系、支付接入体系、支付交易体系、对账清结算体系。目标是打造一款集成主流支付方式且轻量易用的支付收款系统，满足互联网业务系统打通支付通道实现支付收款和业务资金管理等功能。
* [orientechnologies/orientdb](https://github.com/orientechnologies/orientdb) - OrientDB is the most versatile DBMS supporting Graph, Document, Reactive, Full-Text and Geospatial models in one Multi-Model product. OrientDB can run distributed (Multi-Master), supports SQL, ACID Transactions, Full-Text indexing and Reactive Queries.
* [JodaOrg/joda-time](https://github.com/JodaOrg/joda-time) - Joda-Time is the widely used replacement for the Java date and time classes prior to Java SE 8.
* [rubensousa/GravitySnapHelper](https://github.com/rubensousa/GravitySnapHelper) - A SnapHelper that snaps a RecyclerView to an edge.
* [DingMouRen/LayoutManagerGroup](https://github.com/DingMouRen/LayoutManagerGroup) - :point_right: Customize the LayoutManager of RecyclerView(自定义LayoutManager)
* [spring-attic/spring-mvc-showcase](https://github.com/spring-attic/spring-mvc-showcase) - Demonstrates the features of the Spring MVC web framework *(archived)*
* [Kodezi/Chronos](https://github.com/Kodezi/Chronos) - Kodezi Chronos is a debugging-first language model that achieves state-of-the-art results on SWE-bench Lite (80.33%) and 67% real-world fix accuracy, over six times better than GPT-4. Built with Adaptive Graph-Guided Retrieval and Persistent Debug Memory. Model available Q1 2026 via Kodezi OS.
* [alibaba/UltraViewPager](https://github.com/alibaba/UltraViewPager) - UltraViewPager is an extension for ViewPager to provide multiple features in a single ViewPager. *(archived)*
* [frogermcs/InstaMaterial](https://github.com/frogermcs/InstaMaterial) - Implementation of Instagram with Material Design (originally based on Emmanuel Pacamalan's concept)
* [Devlight/NavigationTabBar](https://github.com/Devlight/NavigationTabBar) - Navigation tab bar with colorful interactions.
* [AsamK/signal-cli](https://github.com/AsamK/signal-cli) - signal-cli provides an unofficial commandline, JSON-RPC and dbus interface for the Signal messenger.
* [traex/RippleEffect](https://github.com/traex/RippleEffect) - Implementation of Ripple effect from Material Design for Android API 9+
* [reactive-streams/reactive-streams-jvm](https://github.com/reactive-streams/reactive-streams-jvm) - Reactive Streams Specification for the JVM
* [Querz/mcaselector](https://github.com/Querz/mcaselector) - A tool to select chunks from Minecraft worlds for deletion or export.
* [claritylab/lucida](https://github.com/claritylab/lucida) - Speech and Vision Based Intelligent Personal Assistant
* [iterate-ch/cyberduck](https://github.com/iterate-ch/cyberduck) - Cyberduck is a libre FTP, SFTP, WebDAV, Amazon S3, Backblaze B2, Microsoft Azure & OneDrive and OpenStack Swift file transfer client for Mac and Windows.
* [andkulikov/Transitions-Everywhere](https://github.com/andkulikov/Transitions-Everywhere) - Set of extra Transitions on top of Jetpack Transitions Library
* [tuguangquan/mybatis](https://github.com/tuguangquan/mybatis) - mybatis源码中文注释
* [kyleduo/SwitchButton](https://github.com/kyleduo/SwitchButton) - A cute widget of Switch Button for you to create beautiful and friendly UI.
* [saiwu-bigkoo/Android-ConvenientBanner](https://github.com/saiwu-bigkoo/Android-ConvenientBanner) - Simple and convenient banner, loop viewpager with 3D effects
* [emanuele-f/PCAPdroid](https://github.com/emanuele-f/PCAPdroid) - No-root network monitor, firewall and PCAP dumper for Android
* [ant-media/Ant-Media-Server](https://github.com/ant-media/Ant-Media-Server) - Ant Media Server — Ultra-low latency streaming engine with WebRTC (~0.5s), SRT, RTMP, HLS, CMAF, adaptive bitrate, transcoding & scaling
* [201206030/novel-plus](https://github.com/201206030/novel-plus) - novel-plus 是一个多端（PC、WAP）阅读 、功能完善的小说 CMS 系统。包括小说推荐、小说检索、小说排行、小说阅读、小说书架、小说评论、小说爬虫、会员中心、作家专区、充值订阅、新闻发布等功能。
* [etsy/AndroidStaggeredGrid](https://github.com/etsy/AndroidStaggeredGrid) - An Android staggered grid view which supports multiple columns with rows of varying sizes. *(archived)*
* [cjlin1/libsvm](https://github.com/cjlin1/libsvm) - LIBSVM -- A Library for Support Vector Machines
* [google/cameraview](https://github.com/google/cameraview) - [DEPRECATED] Easily integrate Camera features into your Android app *(archived)*
* [hongyangAndroid/baseAdapter](https://github.com/hongyangAndroid/baseAdapter) - Android 万能的Adapter for ListView,RecyclerView,GridView等，支持多种Item类型的情况。
* [spring-attic/spring-security-oauth](https://github.com/spring-attic/spring-security-oauth) - Support for adding OAuth1(a) and OAuth2 features (consumer and provider) for Spring web applications. *(archived)*
* [jgilfelt/chuck](https://github.com/jgilfelt/chuck) - An in-app HTTP inspector for Android OkHttp clients
* [linhaojun857/aurora](https://github.com/linhaojun857/aurora) - 基于SpringBoot+Vue开发的个人博客系统
* [Heeexy/SpringBoot-Shiro-Vue](https://github.com/Heeexy/SpringBoot-Shiro-Vue) - 提供一套基于Spring Boot-Shiro-Vue的权限管理思路.前后端都加以控制,做到按钮/接口级别的权限。（当前新版本已移除shiro依赖，简化了配置）
* [zongzibinbin/MallChat](https://github.com/zongzibinbin/MallChat) - mallchat的后端项目，是一个既能购物又能聊天的电商系统。以互联网企业级开发规范的要求来实现它，电商该有的购物车，订单，支付，推荐，搜索，拉新，促活，推送，物流，客服，它都必须有。持续更新ing。。（点个star，不迷路）
* [pardom-zz/ActiveAndroid](https://github.com/pardom-zz/ActiveAndroid) - Active record style SQLite persistence for Android
* [hussien89aa/AndroidTutorialForBeginners](https://github.com/hussien89aa/AndroidTutorialForBeginners) - Step by step to build Android apps using Android Studio
* [M66B/FairEmail](https://github.com/M66B/FairEmail) - Fully featured, open source, privacy friendly email app for Android
* [wdullaer/MaterialDateTimePicker](https://github.com/wdullaer/MaterialDateTimePicker) - Pick a date or time on Android in style
* [romandanylyk/PageIndicatorView](https://github.com/romandanylyk/PageIndicatorView) - An page indicator for Android ViewPager
* [Netflix/ribbon](https://github.com/Netflix/ribbon) - Ribbon is a Inter Process Communication (remote procedure calls) library with built in software load balancers. The primary usage model involves REST calls with various serialization scheme support.
* [gabrielemariotti/cardslib](https://github.com/gabrielemariotti/cardslib) - Android Library to build a UI Card
* [JZ-Darkal/AndroidHttpCapture](https://github.com/JZ-Darkal/AndroidHttpCapture) - AndroidHttpCapture网络诊断工具 是一款Android手机抓包软件 主要功能包括：手机端抓包、PING/DNS/TraceRoute诊断、抓包HAR数据上传分享。你也可以看成是Android版的"Fiddler" \(^o^)/~
* [apache/rocketmq-externals](https://github.com/apache/rocketmq-externals) - Mirror of Apache RocketMQ (Incubating)
* [Freeyourgadget/Gadgetbridge](https://github.com/Freeyourgadget/Gadgetbridge) - We are on codeberg.org now! https://codeberg.org/Freeyourgadget/Gadgetbridge - Gadgetbridge - A free and cloudless replacement for your gadget vendors' closed source Android applications. Supports Pebble, Mi Band, Liveview, HPlus and more. *(archived)*
* [jishenghua/jshERP](https://github.com/jishenghua/jshERP) - 管伊佳ERP（原名华夏ERP）基于SpringBoot框架和SaaS模式，立志为中小企业提供开源好用的ERP软件，目前专注进销存+财务功能。主要模块有零售管理、采购管理、销售管理、仓库管理、财务管理、报表查询、系统管理等。支持预付款、收入支出、仓库调拨、组装拆卸、订单等特色功能。拥有库存状况、出入库统计等报表。同时对角色和权限进行了细致全面控制，精确到每个按钮和菜单。
* [IoT-Technology/IoT-Technical-Guide](https://github.com/IoT-Technology/IoT-Technical-Guide) - :honeybee: IoT Technical Guide --- 从零搭建高性能物联网平台及物联网解决方案和Thingsboard源码分析 :sparkles: :sparkles: :sparkles: (IoT Platform, SaaS, MQTT, CoAP, HTTP, Modbus, OPC, WebSocket, 物模型，Protobuf, PostgreSQL, MongoDB, Spring Security, OAuth2, RuleEngine, Kafka, Docker)
* [chentao0707/SimplifyReader](https://github.com/chentao0707/SimplifyReader) - 一款基于Google Material Design设计开发的Android客户端，包括新闻简读，图片浏览，视频爽看 ，音乐轻听以及二维码扫描五个子模块。项目采取的是MVP架构开发，由于还是摸索阶段，可能不是很规范。但基本上应该是这么个套路，至少我个人认为是这样的~恩，就是这样的！
* [zhanghai/Douya](https://github.com/zhanghai/Douya) - 开源的 Material Design 豆瓣客户端（A Material Design app for douban.com） *(archived)*
* [go-lang-plugin-org/go-lang-idea-plugin](https://github.com/go-lang-plugin-org/go-lang-idea-plugin) - Google Go language IDE built using the IntelliJ Platform
* [square/sqlbrite](https://github.com/square/sqlbrite) - A lightweight wrapper around SQLiteOpenHelper which introduces reactive stream semantics to SQL operations. *(archived)*
* [danielzeller/Depth-LIB-Android-](https://github.com/danielzeller/Depth-LIB-Android-) - A library that gives depth to Views.
* [castorflex/SmoothProgressBar](https://github.com/castorflex/SmoothProgressBar) - A small Android library allowing you to have a smooth and customizable horizontal or circular indeterminate ProgressBar
* [Creators-of-Create/Create](https://github.com/Creators-of-Create/Create) - [NeoForge Mod] Building Tools and Aesthetic Technology
* [azkaban/azkaban](https://github.com/azkaban/azkaban) - Azkaban workflow manager.
* [jdamcd/android-crop](https://github.com/jdamcd/android-crop) - Android library project for cropping images *(archived)*
* [alibaba/dexposed](https://github.com/alibaba/dexposed) - dexposed enable 'god' mode for single android application. *(archived)*
* [Flipboard/bottomsheet](https://github.com/Flipboard/bottomsheet) - Android component which presents a dismissible view from the bottom of the screen
* [water8394/flink-recommandSystem-demo](https://github.com/water8394/flink-recommandSystem-demo) - :helicopter::rocket:基于Flink实现的商品实时推荐系统。flink统计商品热度，放入redis缓存，分析日志信息，将画像标签和实时记录放入Hbase。在用户发起推荐请求后，根据用户画像重排序热度榜，并结合协同过滤和标签两个推荐模块为新生成的榜单的每一个产品添加关联产品，最后返回新的用户列表。
* [HotBitmapGG/bilibili-android-client](https://github.com/HotBitmapGG/bilibili-android-client) - An unofficial bilibili client for android http://www.jianshu.com/p/f69a55b94c05 -- 该项目已停止维护！
* [JakeWharton/NineOldAndroids](https://github.com/JakeWharton/NineOldAndroids) - [DEPRECATED] Android library for using the Honeycomb animation API on all versions of the platform back to 1.0! *(archived)*
* [Meituan-Dianping/Robust](https://github.com/Meituan-Dianping/Robust) - Robust is an Android HotFix solution with high compatibility and high stability. Robust can fix bugs immediately without a reboot.
* [dreamhead/moco](https://github.com/dreamhead/moco) - Easy Setup Stub Server
* [Snailclimb/guide-rpc-framework](https://github.com/Snailclimb/guide-rpc-framework) - A custom RPC framework implemented by Netty+Kyro+Zookeeper.（一款基于 Netty+Kyro+Zookeeper 实现的自定义 RPC 框架-附详细实现过程和相关教程。）
* [janishar/android-mvp-architecture](https://github.com/janishar/android-mvp-architecture) - This repository contains a detailed sample app that implements MVP architecture using Dagger2, GreenDao, RxJava2, FastAndroidNetworking and PlaceholderView
* [square/android-times-square](https://github.com/square/android-times-square) - Standalone Android widget for picking a single date from a calendar view. *(archived)*
* [Tencent/GT](https://github.com/Tencent/GT) - GT (Great Tit) is a portable debugging tool for bug hunting and performance tuning on smartphones anytime and anywhere just as listening music with Walkman. GT can act as the Integrated Debug Environment by directly running on smartphones.
* [eirslett/frontend-maven-plugin](https://github.com/eirslett/frontend-maven-plugin) - "Maven-node-grunt-gulp-npm-node-plugin to end all maven-node-grunt-gulp-npm-plugins." A Maven plugin that downloads/installs Node and NPM locally, runs NPM install, Grunt, Gulp and/or Karma.
* [robinhood/ticker](https://github.com/robinhood/ticker) - An Android text view with scrolling text change animation
* [jlegewie/zotfile](https://github.com/jlegewie/zotfile) - Zotero plugin to manage your attachments: automatically rename, move, and attach PDFs (or other files) to Zotero items, sync PDFs from your Zotero library to your (mobile) PDF reader (e.g. an iPad, Android tablet, etc.), and extract PDF annotations.
* [ThirtyDegreesRay/OpenHub](https://github.com/ThirtyDegreesRay/OpenHub) - An open source GitHub Android client app, faster and concise.
* [google/open-location-code](https://github.com/google/open-location-code) - Open Location Code is a library to generate short codes, called "plus codes", that can be used as digital addresses where street addresses don't exist.
* [Ashok-Varma/BottomNavigation](https://github.com/Ashok-Varma/BottomNavigation) - This Library helps users to use Bottom Navigation Bar (A new pattern from google) with ease and allows ton of customizations
* [pytorch/serve](https://github.com/pytorch/serve) - Serve, optimize and scale PyTorch models in production *(archived)*
* [apache/streampark](https://github.com/apache/streampark) - The Open Control Plane for Real-Time Data
* [termux/termux-api](https://github.com/termux/termux-api) - Termux add-on app which exposes device functionality as API to command line programs.
* [mywalkb/LSPosed_mod](https://github.com/mywalkb/LSPosed_mod) - My changes to LSPosed
* [jeasonlzy/ImagePicker](https://github.com/jeasonlzy/ImagePicker) - 完全仿微信的图片选择，并且提供了多种图片加载接口，选择图片后可以旋转，可以裁剪成矩形或圆形，可以配置各种其他的参数
* [bingoogolapple/BGARefreshLayout-Android](https://github.com/bingoogolapple/BGARefreshLayout-Android) - 多种下拉刷新效果、上拉加载更多、可配置自定义头部广告位
* [JFormDesigner/FlatLaf](https://github.com/JFormDesigner/FlatLaf) - FlatLaf - Swing Look and Feel (with Darcula/IntelliJ themes support)
* [bjmashibing/InternetArchitect](https://github.com/bjmashibing/InternetArchitect) - 年薪百万互联网架构师课程文档及源码(公开部分)
* [microsoft/malmo](https://github.com/microsoft/malmo) - Project Malmo is a platform for Artificial Intelligence experimentation and research built on top of Minecraft. We aim to inspire a new generation of research into challenging new problems presented by this unique environment. --- For installation instructions, scroll down to *Getting Started* below, or visit the project page for more information: *(archived)*
* [zendesk/maxwell](https://github.com/zendesk/maxwell) - Maxwell's daemon, a mysql-to-json kafka producer
* [nining377/dolby_beta](https://github.com/nining377/dolby_beta) - 杜比大喇叭的β版迎来了重大的革新，合并了UnblockMusic Pro的所有功能且更加强大，同时UnblockMusicPro_Xposed项目将会停止维护，让我们欢送这位老朋友！
* [mcxiaoke/android-volley](https://github.com/mcxiaoke/android-volley) - DEPRECATED *(archived)*
* [ongakuer/CircleIndicator](https://github.com/ongakuer/CircleIndicator) - A lightweight indicator like in nexus 5 launcher
* [grantland/android-autofittextview](https://github.com/grantland/android-autofittextview) - A TextView that automatically resizes text to fit perfectly within its bounds.
* [aporter/coursera-android](https://github.com/aporter/coursera-android) - Source Code for Android Course Example Applications
* [lukas-krecan/ShedLock](https://github.com/lukas-krecan/ShedLock) - Distributed lock for your scheduled tasks
* [RikkaApps/Sui](https://github.com/RikkaApps/Sui) - Modern super user interface implementation on Android.
* [DependencyTrack/dependency-track](https://github.com/DependencyTrack/dependency-track) - Dependency-Track is an intelligent Component Analysis platform that allows organizations to identify and reduce risk in the software supply chain.
* [yhaolpz/FloatWindow](https://github.com/yhaolpz/FloatWindow) - Andorid 任意界面悬浮窗，实现悬浮窗如此简单
* [hugeterry/CoordinatorTabLayout](https://github.com/hugeterry/CoordinatorTabLayout) - Combination of TabLayout and CoordinatorLayout./TabLayout和CoordinatorLayout相结合的折叠控件
* [Jacksgong/JKeyboardPanelSwitch](https://github.com/Jacksgong/JKeyboardPanelSwitch) - For resolve the layout conflict when keybord & panel are switching (Android键盘面板冲突 布局闪动处理方案)
* [dromara/hmily](https://github.com/dromara/hmily) - Distributed transaction solutions
* [codingapi/tx-lcn](https://github.com/codingapi/tx-lcn) - LCN distributed transaction framework, compatible with dubbo, spring cloud and Motan framework, supports various relational databases
* [bingoogolapple/BGABanner-Android](https://github.com/bingoogolapple/BGABanner-Android) - 引导界面滑动导航 + 大于等于1页时无限轮播 + 各种切换动画轮播效果
* [oddfar/campus-imaotai](https://github.com/oddfar/campus-imaotai) - i茅台app自动预约，每日自动预约，支持docker一键部署（本项目不提供成品，使用的是已淘汰的算法）
* [pedrovgs/AndroidWiFiADB](https://github.com/pedrovgs/AndroidWiFiADB) - IntelliJ/AndroidStudio plugin which provides a button to connect your Android device over WiFi to install, run and debug your applications without a USB connected. *(archived)*
* [pqpo/SmartCropper](https://github.com/pqpo/SmartCropper) - 🔥 A library for cropping image in a smart way that can identify the border and correct the cropped image. 智能图片裁剪框架。自动识别边框，手动调节选区，使用透视变换裁剪并矫正选区；适用于身份证，名片，文档等照片的裁剪。
* [dinuscxj/LoadingDrawable](https://github.com/dinuscxj/LoadingDrawable) - Some beautiful android loading drawable, can be combined with any view as the LoadingView or the ProgressBar. Besides, some Drawable can customize the loading progress too.
* [alibaba/Tangram-Android](https://github.com/alibaba/Tangram-Android) - Tangram is a modular UI solution for building native page dynamically including Tangram for Android, Tangram for iOS and even backend CMS. This project provides the sdk on Android. *(archived)*
* [code4craft/tiny-spring](https://github.com/code4craft/tiny-spring) - A tiny IoC container refer to Spring.
* [knowm/XChange](https://github.com/knowm/XChange) - XChange is a Java library providing a streamlined API for interacting with 60+ Bitcoin and Altcoin exchanges providing a consistent interface for trading and accessing market data.
* [rubensousa/ViewPagerCards](https://github.com/rubensousa/ViewPagerCards) - ViewPager cards inspired by Duolingo *(archived)*
* [Manabu-GT/ExpandableTextView](https://github.com/Manabu-GT/ExpandableTextView) - Android's TextView that can expand/collapse like the Google Play's app description *(archived)*
* [Dimezis/BlurView](https://github.com/Dimezis/BlurView) - Dynamic iOS-like blur of underlying Views for Android
* [luckybilly/CC](https://github.com/luckybilly/CC) - 业界首个支持渐进式组件化改造的Android组件化开源框架，支持跨进程调用。Componentize your android project gradually.
* [yacy/yacy_search_server](https://github.com/yacy/yacy_search_server) - Distributed Peer-to-Peer Web Search Engine and Intranet Search Appliance
* [google/bundletool](https://github.com/google/bundletool) - Bundletool is a command-line tool to manipulate Android App Bundles
* [nageoffer/ragent](https://github.com/nageoffer/ragent) - 企业级 Agentic RAG 智能体 - 全链路覆盖文档解析、多路检索、意图识别、问题重写、会话记忆、MCP 工具调用与深度思考。面向真实业务场景，从 0 到 1 完整工程实现。
* [xcltapestry/XCL-Charts](https://github.com/xcltapestry/XCL-Charts) - Android图表库(XCL-Charts is a free charting library for Android platform.),基于Android Canvas来绘制各种图表,使用简便,定制灵活。目前支持3D/非3D/背向式/横向/竖向柱形图(Bar Chart)、3D/非3D饼图(Pie Chart)、堆叠图(Stacked Bar Chart)、面积图(Area Chart)、 折线图(Line Chart)、曲线图(Spline Chart)、环形图(Dount Chart)、南丁格尔玫瑰图(Rose Chart)、仪表盘(Dial Chart)、刻度盘(Gauge Chart)、雷达图(Radar Chart)、漏斗图(Funnel Chart)、圆形图(Circle Chart)、弧线比较图、散点图(Scatter Chart)、气泡图(Bubble Chart)、范围条形图(RangeBar Chart)等图表。其它特性还包括支持图表缩放、手势移动、点击响应、动画效果、多轴显示、图表参考线、混合图表及同数据源不同图表类型切换等。
* [BoltsFramework/Bolts-Android](https://github.com/BoltsFramework/Bolts-Android) - Bolts is a collection of low-level libraries designed to make developing mobile apps easier. *(archived)*
* [orhanobut/hawk](https://github.com/orhanobut/hawk) - ✔️ Secure, simple key-value storage for Android
* [shuzijun/leetcode-editor](https://github.com/shuzijun/leetcode-editor) - Do Leetcode exercises in IDE, support leetcode.com and leetcode-cn.com, to meet the basic needs of doing exercises.Support theoretically: IntelliJ IDEA PhpStorm WebStorm PyCharm RubyMine AppCode CLion GoLand DataGrip Rider MPS Android Studio
* [JeremyLiao/LiveEventBus](https://github.com/JeremyLiao/LiveEventBus) - :mailbox_with_mail:EventBus for Android，消息总线，基于LiveData，具有生命周期感知能力，支持Sticky，支持AndroidX，支持跨进程，支持跨APP
* [Piasy/BigImageViewer](https://github.com/Piasy/BigImageViewer) - Big image viewer supporting pan and zoom, with very little memory usage and full featured image loading choices. Powered by Subsampling Scale Image View, Fresco, Glide, and Picasso. Even with gif and webp support! 🍻
* [rovo89/XposedInstaller](https://github.com/rovo89/XposedInstaller) - *(archived)*
* [lcodecorex/TwinklingRefreshLayout](https://github.com/lcodecorex/TwinklingRefreshLayout) - RefreshLayout that support for OverScroll and better than iOS. 支持下拉刷新和上拉加载的RefreshLayout,自带越界回弹效果，支持RecyclerView,AbsListView,ScrollView,WebView
* [makovkastar/FloatingActionButton](https://github.com/makovkastar/FloatingActionButton) - [DEPRECATED] Android floating action button
* [qstumn/BadgeView](https://github.com/qstumn/BadgeView) - 支持自由定制外观、拖拽消除的MaterialDesign风格Android BadgeView
* [zzhoujay/RichText](https://github.com/zzhoujay/RichText) - Android平台下的富文本解析器，支持Html和Markdown
* [pingfangushi/screw](https://github.com/pingfangushi/screw) - 简洁好用的数据库表结构文档生成器
* [watabou/pixel-dungeon](https://github.com/watabou/pixel-dungeon) - Traditional roguelike game with pixel-art graphics and simple interface
* [linyiqun/DataMiningAlgorithm](https://github.com/linyiqun/DataMiningAlgorithm) - 数据挖掘18大算法实现以及其他相关经典DM算法
* [VaughnVernon/IDDD_Samples](https://github.com/VaughnVernon/IDDD_Samples) - These are the sample Bounded Contexts from the book "Implementing Domain-Driven Design" by Vaughn Vernon: http://vaughnvernon.co/?page_id=168
* [binIoter/GuideView](https://github.com/binIoter/GuideView) - 东半球最好用的新手引导库，能够快速为任何一个View创建一个遮罩层，支持单个页面，多个引导串联展示，支持为高亮区域设置不同的图形，支持引导动画，方便扩展,良好支持fragment
* [oasisfeng/island](https://github.com/oasisfeng/island) - Island for Android
* [JoanZapata/android-iconify](https://github.com/JoanZapata/android-iconify) - Android integration of multiple icon providers such as FontAwesome, Entypo, Typicons,...
* [databricks/learning-spark](https://github.com/databricks/learning-spark) - Example code from Learning Spark book
* [amirzaidi/Launcher3](https://github.com/amirzaidi/Launcher3) - The Launcher3 fork known as "Rootless Pixel Launcher"
* [bluelinelabs/Conductor](https://github.com/bluelinelabs/Conductor) - A small, yet full-featured framework that allows building View-based Android applications
* [Exrick/xboot](https://github.com/Exrick/xboot) - 基于Spring Boot 2.x的一站式前后端分离快速开发平台XBoot 微信小程序+Uniapp 前端：Vue+iView Admin 后端：Spring Boot 2.x/Spring Security/JWT/JPA+Mybatis-Plus/Redis/Elasticsearch/Activiti 分布式限流/同步锁/验证码/SnowFlake雪花算法ID 动态权限 数据权限 工作流 代码生成 定时任务 社交账号 短信登录 单点登录 OAuth2开放平台 客服机器人 数据大屏 暗黑模式
* [react-native-share/react-native-share](https://github.com/react-native-share/react-native-share) - Social share, sending simple data to other apps.
* [vipulasri/Timeline-View](https://github.com/vipulasri/Timeline-View) - Timeline View is a simple and highly customizable android library for creating shipment/order tracking, step progress indicators, etc.
* [JavaNoober/BackgroundLibrary](https://github.com/JavaNoober/BackgroundLibrary) - A framework for directly generating shape through Tags, no need to write shape.xml again（通过标签直接生成shape，无需再写shape.xml）
* [uncle-novel/uncle-novel](https://github.com/uncle-novel/uncle-novel)
* [wendux/DSBridge-Android](https://github.com/wendux/DSBridge-Android) - :earth_americas: A modern cross-platform JavaScript bridge, through which you can invoke each other's functions synchronously or asynchronously between JavaScript and native.
* [M66B/NetGuard](https://github.com/M66B/NetGuard) - A simple way to block access to the internet per app
* [Nekogram/Nekogram](https://github.com/Nekogram/Nekogram) - Open-source third-party Telegram client with not many but useful modifications.
* [JCTools/JCTools](https://github.com/JCTools/JCTools)
* [alibaba/jstorm](https://github.com/alibaba/jstorm) - Enterprise Stream Process Engine *(archived)*
* [proninyaroslav/libretorrent](https://github.com/proninyaroslav/libretorrent) - Free and Open Source, full-featured torrent client for Android. Mirrored from https://gitlab.com/proninyaroslav/libretorrent
* [MeteorDevelopment/meteor-client](https://github.com/MeteorDevelopment/meteor-client) - Based Minecraft utility mod.
* [dromara/liteflow](https://github.com/dromara/liteflow) - Lightweight, fast, stable, programmable component-based rule engine — where AI Agents orchestrate just like ordinary components. Uniquely designed DSL: component reuse, sync/async & dynamic orchestration, multi-language scripting, nested rules, hot deployment and smooth refresh. If you can orchestrate LiteFlow, you can orchestrate AI.
* [yanzhenjie/AndServer](https://github.com/yanzhenjie/AndServer) - :cherries: Web server and web framework of Android platform.
* [Aefyr/SAI](https://github.com/Aefyr/SAI) - Android split APKs installer
* [google/copybara](https://github.com/google/copybara) - Copybara: A tool for transforming and moving code between repositories.
* [IrisShaders/Iris](https://github.com/IrisShaders/Iris) - A modern shaders mod for Minecraft compatible with existing OptiFine shader packs
* [aurelhubert/ahbottomnavigation](https://github.com/aurelhubert/ahbottomnavigation) - A library to reproduce the behavior of the Bottom Navigation guidelines from Material Design.
* [MiguelCatalan/MaterialSearchView](https://github.com/MiguelCatalan/MaterialSearchView) - Cute library to implement SearchView in a Material Design Approach
* [blossom-editor/blossom](https://github.com/blossom-editor/blossom) - A markdown editor that you can deploy on your own servers to achieve cloud storage and device synchronization（支持私有部署的云端存储双链笔记软件）
* [happydog-intj/CircleProgress](https://github.com/happydog-intj/CircleProgress) - CircleProgress, DonutProgress, ArcProgress for Android
* [mcxtzhang/SwipeDelMenuLayout](https://github.com/mcxtzhang/SwipeDelMenuLayout) - The most simple SwipeMenu in the history, 0 coupling, support any ViewGroup. Step integration swipe (delete) menu, high imitation QQ, iOS. ~史上最简单侧滑菜单，0耦合，支持任意ViewGroup。一步集成侧滑(删除)菜单，高仿QQ、IOS。~
* [sunfusheng/MarqueeView](https://github.com/sunfusheng/MarqueeView) - 俗名：可垂直跑、可水平跑的跑马灯；学名：可垂直翻、可水平翻的翻页公告
* [timehop/sticky-headers-recyclerview](https://github.com/timehop/sticky-headers-recyclerview) - [UNMAINTAINED] Sticky Headers decorator for Android's RecyclerView *(archived)*
* [zhpanvip/BannerViewPager](https://github.com/zhpanvip/BannerViewPager) - 🚀 An awesome banner view for Android，Based on ViewPager2. 这可能是全网最好用的ViewPager轮播图。简单、高效，一行代码实现循环轮播，一屏三页任意变，指示器样式任你挑。
* [apache/kylin](https://github.com/apache/kylin) - Apache Kylin
* [microservices-patterns/ftgo-application](https://github.com/microservices-patterns/ftgo-application) - Example code for the book Microservice patterns
* [DataLinkDC/dinky](https://github.com/DataLinkDC/dinky) - Dinky is a real-time data development platform based on Apache Flink, enabling agile data development, deployment and operation.
* [lygttpod/SuperTextView](https://github.com/lygttpod/SuperTextView) - a super textview for android
* [Ereza/CustomActivityOnCrash](https://github.com/Ereza/CustomActivityOnCrash) - Android library that allows launching a custom activity when your app crashes, instead of showing the hated "Unfortunately, X has stopped" dialog.
* [FasterXML/jackson-databind](https://github.com/FasterXML/jackson-databind) - General data-binding package for Jackson: works on streaming API (core) implementation(s)
* [lihangleo2/ShadowLayout](https://github.com/lihangleo2/ShadowLayout) - 可定制化阴影的万能阴影布局ShadowLayout 3.0 震撼上线。效果赶超CardView。阴影支持x,y轴偏移，支持阴影扩散程度，支持阴影圆角，支持单边或多边不显示阴影；控件支持动态设置shape和selector（项目里再也不用画shape了）；支持随意更改颜色值，支持随意更改颜色值，支持随意更改颜色值。重要的事情说三遍
* [nageoffer/12306](https://github.com/nageoffer/12306) - 🔥 官方推荐 🔥 大学春招、秋招、应届项目，SpringBoot3 + Java17 + SpringCloud Alibaba + Vue3 等技术架构，完成高仿铁路 12306 用户 + 抢票 + 订单 + 支付服务，帮助学生主打就业的项目。
* [stfalcon-studio/ChatKit](https://github.com/stfalcon-studio/ChatKit) - Android library. Flexible components for chat UI implementation with flexible possibilities for styling, customizing and data management. Made by Stfalcon
* [Mojang/brigadier](https://github.com/Mojang/brigadier) - Brigadier is a command parser & dispatcher, designed and developed for Minecraft: Java Edition.
* [ethanhua/Skeleton](https://github.com/ethanhua/Skeleton) - A library provides an easy way to show skeleton loading view like Facebook and Alipay
* [niumoo/bing-wallpaper](https://github.com/niumoo/bing-wallpaper) - 必应每日超清壁纸（4K） Bing Daily Wallpaper (4K)
* [roboguice/roboguice](https://github.com/roboguice/roboguice) - Google Guice on Android, version 3.0 [RETIRED]
* [yanzhenjie/NoHttp](https://github.com/yanzhenjie/NoHttp) - :lemon: Android实现Http标准协议框架，支持多种缓存模式，底层可动态切换OkHttp、URLConnection。
* [mbechler/marshalsec](https://github.com/mbechler/marshalsec)
* [andOTP/andOTP](https://github.com/andOTP/andOTP) - [Unmaintained] Open source two-factor authentication for Android *(archived)*
* [spring-io/initializr](https://github.com/spring-io/initializr) - A quickstart generator for Spring projects
* [dingjikerbo/Android-BluetoothKit](https://github.com/dingjikerbo/Android-BluetoothKit) - Android BLE蓝牙通信库
* [ryanhoo/StylishMusicPlayer](https://github.com/ryanhoo/StylishMusicPlayer) - A stylish music player for android device 16+
* [linkedin/databus](https://github.com/linkedin/databus) - Source-agnostic distributed change data capture system
* [lisawray/groupie](https://github.com/lisawray/groupie) - Groupie helps you display and manage complex RecyclerView layouts.
* [Guardsquare/proguard](https://github.com/Guardsquare/proguard) - ProGuard, Java optimizer and obfuscator
* [google/rejoiner](https://github.com/google/rejoiner) - Generates a unified GraphQL schema from gRPC microservices and other Protobuf sources *(archived)*
* [MorpheApp/morphe-patches](https://github.com/MorpheApp/morphe-patches) - Morphe Patches
* [cSploit/android](https://github.com/cSploit/android) - cSploit - The most complete and advanced IT security professional toolkit on Android.
* [huburt-Hu/NewbieGuide](https://github.com/huburt-Hu/NewbieGuide) - Android 快速实现新手引导层的库，通过简洁链式调用，一行代码实现引导层的显示
* [KunMinX/Linkage-RecyclerView](https://github.com/KunMinX/Linkage-RecyclerView) - 即使不用饿了么订餐，也请务必收藏好该库！🔥 一行代码即可接入，二级联动订餐列表。
* [apache/incubator-heron](https://github.com/apache/incubator-heron) - Apache Heron (Incubating) is a realtime, distributed, fault-tolerant stream processing engine from Twitter *(archived)*
* [dtinit/data-transfer-project](https://github.com/dtinit/data-transfer-project) - The Data Transfer Project makes it easy for platforms to build interoperable user data portability features. We are establishing a common framework, including data models and protocols, to enable direct transfer of data both into and out of participating online service providers.
* [oxylabs/google-ai-mode-scraper](https://github.com/oxylabs/google-ai-mode-scraper) - Scrape Google AI Mode responses without blocks on a large scale.
* [PeterCxy/Shelter](https://github.com/PeterCxy/Shelter) - This repository is a mirror of https://gitea.angry.im/PeterCxy/Shelter. For bug reports, use https://lists.sr.ht/~petercxy/shelter
* [litesuits/android-common](https://github.com/litesuits/android-common) - Android Common Utils or Helper. Such as Log, Averager, Base64, Check, FlashLight, KeyguardLock, LogReader, Network, SilentInstaller, TimeAverager, TimeCounter, Toastor, WakeLock, ScreenReceiver, SmsReceiver, PhoneReceiver, NotificationService, AndroidUtil, AppUtil, BitmapUtil, ByteUtil, ClassUtil, DialogUtil, FieldUtil, FileUtil, HexUtil, MD5Util, NotificationUtil, NumberUtil, PackageUtil, RandomUtil, ShellUtil, TelephoneUtil, VibrateUtil, IOUtils, FileUtils, AsyncExecutor, etc. 通用性强，纯洁简单，体积不到50K！其中包括bitmap处理，文件操作，加密存储器，shell命令，静默安装，计数器，均值器，吐司，日志，校验，提示，网络监测等基础功能，以及一些Base64、MD5、Hex、Byte、Number、Dialog、Filed、Class、Package、Telephone、Random等工具类。
* [hmkcode/Android](https://github.com/hmkcode/Android) - Android related examples
* [alibaba/Alink](https://github.com/alibaba/Alink) - Alink is the Machine Learning algorithm platform based on Flink, developed by the PAI team of Alibaba computing platform.
* [Netflix/concurrency-limits](https://github.com/Netflix/concurrency-limits)
* [rockerhieu/emojicon](https://github.com/rockerhieu/emojicon) - A library to show emoji in TextView, EditText (like WhatsApp) for Android
* [dropbox/hackpad](https://github.com/dropbox/hackpad) - Hackpad is a web-based realtime wiki.
* [vert-x3/vertx-examples](https://github.com/vert-x3/vertx-examples) - Vert.x examples
* [WVector/AppUpdate](https://github.com/WVector/AppUpdate) - 🚀 Android 版本更新 🚀 a library for android version update 🚀
* [davideas/FlexibleAdapter](https://github.com/davideas/FlexibleAdapter) - Fast and versatile Adapter for RecyclerView which regroups several features into one library to considerably improve the user experience :-)
* [tyrantgit/ExplosionField](https://github.com/tyrantgit/ExplosionField) - explosive dust effect for views
* [kikoso/android-stackblur](https://github.com/kikoso/android-stackblur) - Android StackBlur is a library that can perform a blurry effect on a Bitmap based on a gradient or radius, and return the result. The library is based on the code of Mario Klingemann.
* [rom1v/sndcpy](https://github.com/rom1v/sndcpy) - Android audio forwarding PoC (scrcpy, but for audio)
* [dongjunkun/DropDownMenu](https://github.com/dongjunkun/DropDownMenu) - 一个实用的多条件筛选菜单
* [code4craft/netty-learning](https://github.com/code4craft/netty-learning) - Netty learning.
* [JakeWharton/ThreeTenABP](https://github.com/JakeWharton/ThreeTenABP) - An adaptation of the JSR-310 backport for Android. *(archived)*
* [dariuszseweryn/RxAndroidBle](https://github.com/dariuszseweryn/RxAndroidBle) - An Android Bluetooth Low Energy (BLE) Library with RxJava3 interface
* [bilibili/MagicaSakura](https://github.com/bilibili/MagicaSakura) - MagicaSakura 是 Android 多主题框架。~ is an Android multi theme library which supporting both daily colorful theme and night theme.
* [unitycatalog/unitycatalog](https://github.com/unitycatalog/unitycatalog) - Open, Multi-modal Catalog for Data & AI
* [arimorty/floatingsearchview](https://github.com/arimorty/floatingsearchview) - A search view that implements a floating search bar also known as persistent search
* [apache/incubator-kie-optaplanner](https://github.com/apache/incubator-kie-optaplanner) - OplaPlanner has moved to https://github.com/apache/incubator-kie-drools. This repository is archived. OptaPlanner is an AI constraint solver in Java to optimize the vehicle routing problem, employee rostering, task assignment, maintenance scheduling, conference scheduling and other planning problems. *(archived)*
* [getActivity/Toaster](https://github.com/getActivity/Toaster) - Android 吐司框架，专治 Toast 各种疑难杂症
* [andremion/Music-Player](https://github.com/andremion/Music-Player) - From UI Proposal to Code :notes::arrow_forward:
* [apache/netbeans](https://github.com/apache/netbeans) - Apache NetBeans
* [egzosn/pay-java-parent](https://github.com/egzosn/pay-java-parent) - 第三方支付对接全能支付Java开发工具包.优雅的轻量级支付模块集成支付对接支付整合（微信,支付宝,银联,友店,富友,跨境支付paypal,payoneer(P卡派安盈)易极付）app,扫码,网页刷脸付刷卡付条码付转账服务商模式,微信分账,微信合单支付、支持多种支付类型多支付账户，支付与业务完全剥离，简单几行代码即可实现支付，简单快速完成支付模块的开发，可轻松嵌入到任何系统里 目前仅是一个开发工具包（即SDK），只提供简单Web实现，建议使用maven或gradle引用本项目即可使用本SDK提供的各种支付相关的功能
* [AndroidIDEOfficial/AndroidIDE](https://github.com/AndroidIDEOfficial/AndroidIDE) - AndroidIDE is an IDE for Android to develop full featured Android apps. *(archived)*
* [openrocket/openrocket](https://github.com/openrocket/openrocket) - Model-rocketry aerodynamics and trajectory simulation software
* [ulisesbocchio/jasypt-spring-boot](https://github.com/ulisesbocchio/jasypt-spring-boot) - Jasypt integration for Spring boot
* [tlaplus/tlaplus](https://github.com/tlaplus/tlaplus) - TLC is a model checker for specifications written in TLA+. The TLA+Toolbox is an IDE for TLA+.
* [ltsopensource/light-task-scheduler](https://github.com/ltsopensource/light-task-scheduler) - Distributed Scheduled Job Framework
* [starcwang/easy_javadoc](https://github.com/starcwang/easy_javadoc) - IntelliJ IDEA 插件，自动生成javadoc文档注释
* [bytedeco/javacpp-presets](https://github.com/bytedeco/javacpp-presets) - The missing Java distribution of native C++ libraries
* [Audiveris/audiveris](https://github.com/Audiveris/audiveris) - Latest generation of Audiveris OMR engine
* [bcgit/bc-java](https://github.com/bcgit/bc-java) - Bouncy Castle Java Distribution (Mirror)
* [JetBrains/skija](https://github.com/JetBrains/skija) - Java bindings for Skia
* [exchange-core/exchange-core](https://github.com/exchange-core/exchange-core) - Ultra-fast matching engine written in Java based on LMAX Disruptor, Eclipse Collections, Real Logic Agrona, OpenHFT, LZ4 Java, and Adaptive Radix Trees.
* [mabe02/lanterna](https://github.com/mabe02/lanterna) - Java library for creating text-based GUIs
* [ta4j/ta4j](https://github.com/ta4j/ta4j) - A Java library for technical analysis.
* [eclipse-jdtls/eclipse.jdt.ls](https://github.com/eclipse-jdtls/eclipse.jdt.ls) - Java language server
* [vipshop/Saturn](https://github.com/vipshop/Saturn) - The vip.com's distributed job scheduling platform.
* [locationtech/jts](https://github.com/locationtech/jts) - The JTS Topology Suite is a Java library for creating and manipulating vector geometry.
* [srikanth-lingala/zip4j](https://github.com/srikanth-lingala/zip4j) - A Java library for zip files and streams
* [JorenSix/TarsosDSP](https://github.com/JorenSix/TarsosDSP) - A Real-Time Audio Processing Framework in Java
* [kaikramer/keystore-explorer](https://github.com/kaikramer/keystore-explorer) - KeyStore Explorer is a free GUI replacement for the Java command-line utilities keytool and jarsigner.
* [cbeust/jcommander](https://github.com/cbeust/jcommander) - Command line parsing framework for Java
* [flutter/flutter-intellij](https://github.com/flutter/flutter-intellij) - Flutter Plugin for IntelliJ
* [devzwy/open_nsfw_android](https://github.com/devzwy/open_nsfw_android) - 🔥🔥🔥色情图片离线识别，基于TensorFlow实现。识别只需20ms,可断网测试，成功率99%，调用只要一行代码，从雅虎的开源项目open_nsfw移植，该模型文件可用于iOS、java、C++等平台 *(archived)*
* [geotools/geotools](https://github.com/geotools/geotools) - Official GeoTools repository
* [graphhopper/jsprit](https://github.com/graphhopper/jsprit) - jsprit is a java based, open source toolkit for solving rich vehicle routing problems
* [gaopu/Java](https://github.com/gaopu/Java) - 一些用Java写的小东西（没什么用，大家不要star了😄）
* [jline/jline3](https://github.com/jline/jline3) - JLine is a Java library for handling console input.
* [nguyenq/tess4j](https://github.com/nguyenq/tess4j) - Java JNA wrapper for Tesseract OCR API
* [opensourceBIM/BIMserver](https://github.com/opensourceBIM/BIMserver) - The open source BIMserver platform
* [KikiLetGo/VirusBroadcast](https://github.com/KikiLetGo/VirusBroadcast) - A java virus broadcast simulation
* [the3deer/android-3D-model-viewer](https://github.com/the3deer/android-3D-model-viewer) - Android OpenGL 2.x/3.x application to view 3D models. Published on Play Store
* [HanSolo/tilesfx](https://github.com/HanSolo/tilesfx) - A JavaFX library containing tiles that can be used for dashboards.
* [JackJiang2011/beautyeye](https://github.com/JackJiang2011/beautyeye) - BeautyEye is a Java Swing cross-platform look and feel.
* [kiegroup/optaplanner](https://github.com/kiegroup/optaplanner) - Midstream of https://github.com/apache/incubator-kie-optaplanner
* [kiegroup/drools](https://github.com/kiegroup/drools) - This repository is a fork of apache/incubator-kie-drools. Please use upstream repository for development.
* [chriswhocodes/jitwatch](https://github.com/chriswhocodes/jitwatch) - Log analyser / visualiser for Java HotSpot JIT compiler. Inspect inlining decisions, hot methods, bytecode, and assembly. View results in the JavaFX user interface.
* [yuanzhongqiao/printfilm](https://github.com/yuanzhongqiao/printfilm) - 短剧平台 AI Short Film Motion Comic Generation Platform Industrial AI Motion Comic & Video Workbench
