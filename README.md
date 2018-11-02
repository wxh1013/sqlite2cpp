# sqlite2cpp
使用规定的格式sql文件, 自动生成c++ sqlite 接口

使用时请先下载 github.com/MwlLj/scriptbase 到本地
将 scriptbase 重命名为  base

也就是 base 目录与sqlite2cpp 目录同级
然后运行 sqlite2cpp 中的 main.py


python main.py -f sql文件的路径 -ho 头文件的输出目录 -co 源文件的输出目录 -create

python  ./main.py  -create   -f ./example_sql/user_info.sql   -ho ../source/include -co ../source/src



/*
	@bref 插入一条记录
	
	@in_isarr false   表示输入的参数是不是数组
	
	@out_isarr false  表示输出的参数是不是数组
	
	@in username: string
	
	@in userage: int
	
*/
