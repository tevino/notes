# Hive

## Overview

- [Apache Hive TM](https://hive.apache.org/)

Hive是基于Hadoop的一个数据仓库工具，可以将结构化的数据文件映射为一张数据库表，并提供简单的类SQL(称为HQL)查询功能，可以将HQL语句转换为MapReduce任务进行运行。 其优点是学习成本低，可以通过HQL语句快速实现简单的MapReduce统计，不必开发专门的MapReduce应用，十分适合数据仓库的统计分析。

## Manual

### Command line

hive 命令行显示当前数据库 [How to identify which database the user is using in hive CLI ? - Stack Overflow](http://stackoverflow.com/questions/17986436/how-to-identify-which-database-the-user-is-using-in-hive-cli)

    set hive.cli.print.current.db=true

## Resources

大数据课程实验案例：网站用户行为分析

- [大数据案例-步骤一:本地数据集上传到数据仓库Hive_厦大数据库实验室博客](http://dblab.xmu.edu.cn/blog/959/)
- [大数据案例-步骤二：Hive数据分析_厦大数据库实验室博客](http://dblab.xmu.edu.cn/blog/1005/)
- [大数据案例-步骤三：Hive、MySQL、HBase数据互导_厦大数据库实验室博客](http://dblab.xmu.edu.cn/blog/1059-2/)
- [大数据案例-步骤四:利用R进行数据可视化分析_厦大数据库实验室博客](http://dblab.xmu.edu.cn/blog/1130-2/)

- [Hive导入10G数据的测试 | 粉丝日志](http://blog.fens.me/hadoop-hive-10g/)
- [Hive -- 基于Hadoop的数据仓库分析工具 - hduhans - 博客园](http://www.cnblogs.com/hanganglin/p/4175247.html)
- [使用Sqoop从MySQL导入数据到Hive和HBase 及近期感悟 - 作业部落 Cmd Markdown 编辑阅读器](https://www.zybuluo.com/aitanjupt/note/209968)
