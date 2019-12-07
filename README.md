# sankaku-spider


库：
requests
json
os
re
math
zipfile
imageio
ThreadPoolExecutor
as_completed
urllib3

函数说明：
 def __init__(self,File)
 /*
 file 文件保存路径
 */

 def Get_html(self,Url)
 /*
 Url 使用requests读取页面源码
 */

 def json_analysis(self, Json):
 /*
 json Json原文
 */

 def Search_Get_Tags(self,Tag)
 /*
 Tag 搜索tag获取原图地址 ---批量
 */

 def Get_Tag(self, Tag)
 /*
 Tag 搜索tag获取原图地址
 */
	
 def New_mkdir(self,Path)
 /*
 Path 新建文件夹
 */
	
 def image_down(self, Link)
 /*
 Link 原图地址
 */
