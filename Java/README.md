# program_learning

	本部分专门是关于Java后台开发和hadoop分布式开发的学习过程。其中，mahout的分布式推荐开发请看stczwd目录下的Recommendation项目
	hadoop分布式开发学习项目：（均放在program_learning/Java/MyEclipseProfessional2014/目录下）
	
1、wordcount和wordscount工程：

	wordscount为hadoop入门式单词计数程序，包含了mapper、reducer的方法创建和hdfs文件系统的基本使用；
	
	wordcount为hadoop入门式单词计数程序，采用默认mapreduce方式实现单词计数程序。 
	
2、Autherlog工程： 

	authorLog工程为自己编写的mapreduce分析日志程序，专门用来分析近期服务器的人员登录情况，返回人员的不同天数的不同登录情况。其中设计了单词计数和单词提取等，另外还自定义了writable数据类型，辅助分析。 
	
3、FileCopyWithProgress工程： 

	实现了hdfs的shell命令中的put方法，用来将本地文件传送到hdfs的确定目录中。 
	
4、FileSystemCat01工程： 

	实现了hdfs中的文件内容显示 
	
5、canopytest和CanopyKmeans工程： 

	canopy工程为使用了mahout工具包之后，认为修改参数读取过程和模拟写canopy运行总流程，用来了解canopy算法的整体流程。
	
	CanopyKmeans工程为使用了mahout工具包之后，采用类似网上的方法，将canopy和kmeans进行整合。 
	
6、ListdirFiles工程： 

	ListDirFile工程为实现了hdfs的文件夹下的具体文件查询 
	
7、TopK工程： 

	该工程为自己对mapreduce深入理解后按照自己的理解实现的topk算法，用来分析文档内的topk词汇。
	
	其中涉及了wordcount的字数统计和正则提取的内容；
	
	topk程序是自己设计实现的针对词频进行排序统计的算法，其中很重要的一点是使用了mapper和reducer的cleanup方法，从而将topk算法顺利实现。 
	
8、recommender_test 

	实现了mahout的简单协同过滤推荐算法，目前的主要研究就是mahout的协同过滤部分。目前已对mahout协同过滤部分进行了源码分析和文字注释，并且在里面添加了自己的内容，详情请看stczwd/Recommendations
	
