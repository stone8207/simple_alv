# simple_alv
oo alv封装,使得调用和function alv一样简单.
由于本人的系统是7.3版本,falv的7.3版本的代码没有随着更新,
个人也有些其他的需求和想法,所以自己封了一个alv,
其中部分代码参考了falv,也借鉴了falv的设计思路,
在此感谢fidley大神.

第一版特性:
1.封装oo alv,力求和function一样简单调用,又能保持oo alv的灵活性
2.可以全屏显示,或弹窗显示,弹窗显示必须基于一个已有屏幕的情况才能使用.
3.增加collection_mode参数,可以将显示的字段进行合计(collect 内表操作),达成类似于excel数据透视表的拖拽自动合计的效果.

安装方法
1.使用saplink,导入NUGG_ZCL_ALV.nugg文件完成自动安装
2.demo程序未包括在nugg中,请按照自己需求copy到系统中.

待完善
1.demo待完善.

