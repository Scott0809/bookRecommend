图书推荐系统

> 项目太久，不再维护，如需定制开发，请加微信：17600977634（备注 合作），点击查看合作介绍：[点击查看详情](https://mp.weixin.qq.com/s/PtX9ukKRBmazAWARprGIAg)


图书推荐系统，依托豆瓣的图书和评分信息，使用基于items的推荐算法，实现推荐

## 1：环境说明
Mysql 5.6 + python 2.7 + django 1.8 + MySQLdb

## 2：文件夹说明
- bookrecommend：是项目综合展示的目录，是一个django的工程，使用时，只需在该目录下打开cmd，运行manage.py runserver 即可
- 数据集（里边是项目所需要的数据集）
	- books.csv:书本的相关信息
	- users.csv:用户的相关信息
	- uid_score_bid.csv:用户给书本的打分信息
- 数据库备份：使用时在数据中新建一个bookrecommend数据库，导入sql文件即可
- 算法原型：协同过滤基于items的推荐算法

3：爬取数据部分代码不提供（因为代码太久了，我的代码也找不到了）
