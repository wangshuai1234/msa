# msa
移动安全联盟MSA oaid库   
from http://www.msa-alliance.cn/  



vertion 1.0.25 2020-12-04  
1.修复了特定情况下会出现“检测到试用版运行”的bug；  
2.解决了联想反射找不到类的问题。  

version 1.0.23 2020-09-07  
1.修改OPPO获取接口  
2.更新混淆字典  
3.修改已知加固方案产生的bug  

version 1.0.22 2020-07-10  
1.为解决之前加固引起的问题，更新加固方式  
2.去除不必要的信息收集问题  
3.更新部分厂家的接口方式  

verstion 1.0.13 2020-02-04  
1.调整sdk包架构，支持系统级接入，目前只在部分手机上支持，开发者不用更新sdk，即可享受sdk的升级。  
2.支持freemeos,ssuios,致濮os  
3.支持一加和黑鲨手机  
4.sdk android sdk提升到28  
5.修复vivo，oppo在低版本不支持的手机上引起的崩溃  
6.部分类不加固，修复部分手机的加固崩溃问题  

version 1.0.11 2019-12-02  
1.修复三星，联想在不支持的手机上不回调的bug  
2.修复webview依赖导致的问题  
3.初始化过程中，出现任何问题都会走回调  
4.sdk里做初始化检查，避免重复初始化  
5.vivo 9.0以下不调用获取oaid  
6.去掉默认aaid的生成  
7.修改华为空指针的bug 

vertion 1.0.10 2019-10-14  
1.支持三星，魅族，nubia手机设备  
2.更新华硕，vivo 支持代码。  
3.调整AsyncTask使用并行线程池，改进性能。  
4.调整输出异常为输出调试信息，避免开发者疑问  
5.vivo改为异步，改进性能  
6.修改加固内联定义，解决崩溃  
7.不再提供udid接口。  

2019年9月18日   miit_mdid_sdk_v1.0.9  
1、解决部分APP、机型崩溃问题；  
2、增加了部分使用建议和F&Q。  
 
2019年8月28日   miit_mdid_sdk_v1.0.8  
1、增加华硕接口支持；  
2、解决动态加载和插件化；  
3、优化代码，支持反射调用；  
4、解决android9以上找不到方法的问题；  
5、更新说明文档。   

2019年8月16日 miit_mdid_sdk_v1.0.6  
1、去掉所有非必需数据的采集；  
2、兼容AndroidX；  
3、修改小米部分手机上取udid的问题；  
4、更新OPPO接口调用；  
5、增加联想接口支持；  
6、优化SDK包体积；  
7、支持armeabi。  

2019年8月6日 miit_mdid_sdk_v1.0.5    
1、去掉所有非必需数据的采集；    
2、兼容AndroidX；    
3、修改小米部分手机上取udid的问题；  
4、更新OPPO接口调用；  
5、增加联想接口支持；  
6、优化SDK包体积。
