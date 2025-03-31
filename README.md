Toy_sales仪表盘里所有图例、背景皆PPT制作。文件：Presentation2.pptx
如果导入dates或其他文件在power query中显示 type error，是导入文件的日期格式有问题，excel误判了日期格式或者是你取数错误又或者是样本量过大导致数据出错。切换成YYYY-MM-DD格式即可。
tips：在创建measure时建议先取空白度量值作为分类支，不同页面/不同计算用途时，添加不同的度量 Measures_1（AVG daily, On hand ） Measures_2 Measures_3 Measures_4 
本可视化仪表盘建议用时3-4个小时，建表调整式样为主！！
分为Sales performance、Goal Projection、Products、Stores 四个主页面，一个Store tooltip 
在Goal Projection交互性设计，可以通过调整目标设定和平均每日销售设定，在折线图上展现总年收，年度营收，剩余年预算额，预计全年营收 
目标设定gobal set和每日平均销售额设定需要parameter参数设定，使用GENERATESERIES函数，比如前者 parameter=GENERATESERIES(60000000，120000000，500000)

