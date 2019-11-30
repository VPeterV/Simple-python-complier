# Simple_python_complier
A simple complier that supports parts of lexical and syntax of python

Update the support for semantic translation (only supporting some simple assignment statement now). For the convenience of the coding, temporally remove the return of results

Python词法分析、语法分析器，语义分析器

词法分析程序：
程序所需文件及环境：

	1、data文件 用来存放本次分析的python语法的程序
	2、wordCode.xlsx文件里面存放有程序支持的所有字符和对应的种别码
	3、程序使用了pandas包，需要在有pandas的环境下运行此程序
	4、python 3 (3.5+ best)
  
程序运行说明：

	1、先根据需求更改data中的语法
	2、可以查看wordCode中的种别码
	3、运行程序
	4、结果会输出在控制台，同时也会以Excel的形式保存在result.xlsx中

语法分析程序、语义分析器：
语法分析程序集成了词法分析程序，简单语义分析器，运行语法/语义分析程序，即可以得到词法分析的结果(result.xlsx)

程序所需文件：
		1、data_expr.txt，改变其中的内容即更改输入（当前仅支持赋值语句）
	  	2、种别码文件（如上词法分析程序所示）

环境：

	1、pandas
	2、python 3 (3.5+ best)

程序运行说明：

	1、根据需要更改data_expr中的语法
	2、运行Syntactic.py文件
	3、结果会输出在控制台
	4、同时也会以Excel的形式保存在SyntaxAndSemanticResults.xlsx中的error_recorder sheet中
	5、语义分析的结果会同时显示在控制台，并且会写在SyntaxAndSemanticResults.xlsx的results sheet 中
	
	
