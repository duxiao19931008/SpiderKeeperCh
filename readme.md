根据spiderkeeper更改的汉化和新功能（由于spiderKeeper配置的dubug=True，替换后注意重启服务）

使用方法，找到spiderkeeper的静态页面html，使用我汉化的html来替换

将/[SpiderKeeper](https://github.com/duxiao666/SpiderKeeperCh/tree/master/SpiderKeeper)/[app](https://github.com/duxiao666/SpiderKeeperCh/tree/master/SpiderKeeper/app)/**templates**/下的html文件替换

2019-12-20更新内容：

新增all_periodic_tasks.html和all_projects.html页面显示所有项目和爬虫任务

修改project_stats.html统计表的时间按照天数显示

注意：spider/controller.py和model.py也有更改