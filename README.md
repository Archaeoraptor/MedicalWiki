# 一个医学知识库

Yet Another Medical Content Management System

## 说明

直接把Mindoc拿过来魔改糊一个骗钱项目，这边需求和场景跟Mindoc差的还是有点多，就不fork了，直接新建了一个仓库。由于Mindoc采用Apache 2.0协议，按照协议要求在此声明。
后面看看有没有什么有用的功能，再fork了挑一点有用的功能给Mindoc提个pr什么的。

## 待做事项

- 集成Elasticsearch或者其他搜索引擎，改善搜索效果
- 添加按照日期、分组等限定的按条件过滤和高级检索功能
- 使用elasticsearch的SuggestionDiscovery、SuggestionService等实现搜索建议
- 添加对医学词典或其他词典的支持（支持mdx等格式）
- 知识图谱和neo4j展示支持
- 升级go至1.16，升级其他依赖版本
- 修复mindoc的一些小bug


## 关于

~~这又是老板拉一个骗钱项目~~

java不想再碰了决定试试Go？（）

本来是打算用Gin或者不用框架用Go的基础库慢慢打磨糊一个出来，然而研究僧每月补助变成了KPI考核，迫于考核压力开始大干快上了。

于是在找现成的轮子的时候找到了Mindoc，直接拿过来改吧