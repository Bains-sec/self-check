1.安装
1.1 数据库安装
本工具使用sql sever数据库，所以需要连接sql sever数据库才能使用工具。有两种方法，一种是在本机安装sql sever2012版本以上的sql sever软件；另一种是找一个服务器安装sql sever去连接。
Sql sever安装步骤：
https://blog.csdn.net/aaahuahua/article/details/117857311
1.2 数据库连接
Sql sever数据库安装好后，右键文件夹中的1.sql脚本文件，使用安装好的sql sever软件打开，然后把图中D:\sql\SelfInspectionToolDB.mdf和D:\sql\SelfInspectionToolDB_log.ldf两个文件SelfInspectionToolDB.mdf和SelfInspectionToolDB_log.ldf前的文件路径换成自己想存放的路径（不能存放在C盘）。
换好后点击左上角执行或者按F5执行。执行完就可以打开exe运行工具了。
 
1.3 新版本更新方式
已经运行过以前旧版本的sql脚本文件的不用运行sql文件了，直接替换exe文件就行。

1.4 安装问题
测试的时候会出现如下问题：
1.提示以压缩，但未驻留在只读数据库或文件组中，必须将文件解压缩。
 
解决方式：
1.存放数据库的盘开启了压缩驱动节省空间，需要右键属性，取消勾选。（盘里只剩几个G的就别试了，我怕你取消勾选空间不够）
 

2.功能说明
2.1 添加任务
点击添加任务，会出现添加任务弹窗，填写任务名称，确认后会在左侧列表显示。
 
2.2 设置问题
点击设置问题会出现设置问题弹窗，这里的问题是为了设置自查模板的测评项，比如三级有十项，二级有五项，添加完后可以做编辑删除操作。
 
 
2.3 设置自查问题模板
这里设置的内容就是新建自查模板里的内容了。
 
点击设置自查问题模板会出现设置自查问题模板，测评项就是在前面设置问题添加的，选择测评项，填写类型、控制项、说明、权重等就可以添加模板了。修改和删除需要双击右边表格里的内容，清除是清除左侧当前填写的内容。
 
2.4 设置系统类型
设置系统类型是添加系统时选择的类型，比如是三级系统系统就点击编辑项，三级有十项我就添加十项，都可以做编辑删除操作。
 
 
 
2.5 导出数据
选择系统，点击导出数据就可以就可以导出excel表格。
 
2.6 导入功能
在设置自查模板处新增导入功能，必须按照文件内导入模板的格式导入，即问题、类型、项、说明、要点、结果和备注七列，注意：导入的问题必须是已经添加进入设置问题处的。

设置自查模板问题这里加个导入功能，直接按excel表格的格式导入，excel文件名对应问题，还是一样备注是选填，导入的时候判断问题有没有，没有就提示“某某问题未添加，请添加问题。”
 
 
2.7 计算分数
选择左侧的系统、模板三级树形中的一个，点击计算分数，就可以算出当前测试系统分数。
 
2.8 一键自查
添加了可以一键自查本机安全配置的脚本，点击一键自查按钮即可。
2.9 树形图任务处右键功能
在左侧树形图添加的任务处右键有删除任务、添加系统和重命名三个功能。
 
2.10 树形图系统处右键功能
在左侧树形图添加的系统处右键有重命名和删除两个功能。
 
2.11 树形图自查模板处右键功能
添加系统后在左侧树形图自查模板处右键有新建自查模板功能，添加后即可在右侧表格界面进行自查。
 
 

3.	等保自查工具1.0.3版本新增功能
3.1新增导入功能
设置自查模板问题处增加导入功能，选择要导入的测评项，然后点击导入按钮即可，类型即安全控制点没有会自动添加。注意：必须按照文件里excel模板去导入。
 
 


