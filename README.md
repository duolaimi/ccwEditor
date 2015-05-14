
##一个基于Tinymce上扩展的图片热点编辑器

###它主要有以下特点

1.自定义复杂热点(精确定位并,具有超链接,倒计时,锚点,等动作)    
2.支持定时切换图片    
3.支持当前图片上的文字进行样式设定    
4.支持自动将map转换为a

###ccweditor 1.3.41 2015-5-14
1.修正点击toolbar无法识别当前编辑器   
2.修正初始化编辑器 selector 为(.ccweditor), 即支持多示例时的正确性

###ccweditor 1.3.40 2015-4-1
1.优化整体结构


###ccweditor 1.2.40 2015-3-19
1.优化倒计时    
2.修正设置框正确显示

###ccweditor 1.2.38 2015-3-10
1.修正双击图片打开问题    
2.修正图片上传提示    

###ccweditor 1.2.36 2015-3-8
1.修正图片大小问题
2.改进加载图片显示

###ccweditor 1.2.34 2015-3-7
1.新增"可选"是否实现"售罄"图标功能
2.优化一些代码    


###ccweditor 1.2.32 2015-3-6
1.修正了隐藏面板功能    
2.新增了"编辑图片"操作提示    
3.修正了脚本加载问题    
4.修正转换MAP的正确性    
5.修正A覆盖热点编辑的问题   


###ccweditor 1.2.27 2015-2-28

1.新增隐藏面板功能    
2.新增双击图片编辑图片    
3.优化了"编辑图片"功能   
4.改进了加载编辑器时有可能不显示图片    
5.改进了相关动作的前置验证    
6.改进了"编辑图片"页面的布局    

###ccweditor 1.2.21 2015-2-26

1.修正一些bug      

###ccweditor 1.2.20 2015-2-25

1.更新售罄图片    
2.修正某些情况的代码格式

###ccweditor 1.2.18 2015-2-15

1.修正转换格式不正确时    
2.编辑图片无蓝色框提示    
 
###ccweditor 1.2.17 2015-2-14

1.优化主调用文件    
2.修正为RequireJS方式调用    

###ccweditor 1.2.16 2015-2-13

1.修正当编辑图片页面其余空白区不能保存    
2.优化模块结构    

###ccweditor 1.2.15 2015-2-12

1.支持之前编辑器所生成的map,area元素包括(倒计时,链接,锚点,按钮)转换为a元素,并且完全移除map,area元素    

###ccweditor 1.2.14 2015-2-11

1.重要修正:兼容旧编辑器的链接及锚点,当旧编辑器的内容载入时,自动转换为新编辑器的内容格式    
2.修正了加载编辑器时给锚点加边框    
3.新增预览及编辑图片时的loading动画提示    

###ccweditor 1.1.12 2015-2-9

1.新增"售罄"图标提示,当:热点为一个正确链接,将分析该地址,是否存在库存,存在则显示"售罄"图标    
2.重要修正:生成的热点不在是map元素替换之a元素,除了倒计时类型会生成div,其余均为a    
3.重要修正:在编辑器内,对热点元素只能回车/退格/Delete键,并回车会生成前后一个p,确保编辑的正确性    
4.模块化部分代码,优化    
5.优化热点所生成的代码,更简洁    
6.当链接类型为链接并且没修改过,默认值是http://,并校验该地址    

###ccweditor 1.0.11 2015-2-7

1.修正了当图片很小的时候没有出现滚动条

###ccweditor 1.0.10 2015-2-6 修正很重要!很严重的问题!

1.修正对内容按退格键(删除)时,没有删除热点(蓝色框)    
2.修正插入锚点没有删除热点(蓝色框)    
3.修正插入图片/多图上传对当前激活编辑器的正确性    
4.修正在编辑器内对图片各种操作,可能会产生不正确的位置及内容    
5.修正(编辑图片页面)不会自适应宽高    
6.优化编辑器内容所产生的代码    
7.关闭编辑器内容可拖动热点,及改变图片大小    
8.增加这个当前文档在编辑器的工具栏上    
###ccweditor 1.0 2015-2-6 更早之前
1.第一个版本    
