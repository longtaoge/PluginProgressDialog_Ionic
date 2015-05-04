# PluginProgressDialog_Ionic
ionic 进度条插件 Android平台 



![](https://github.com/longtaoge/CordovaPluginsDome/raw/master/www/codova_plugin.gif)


###使用方法

    1 cordova plugin add  https://github.com/longtaoge/PluginProgressDialog_Ionic.git

    2 将 import org.apache.cordova.plugs.R; 
	   修改为 AndroidManifest.xml 中的 package="xx.xxx.xxxxxx.xxx" 包名
       例如 package="org.apache.cordova.plugs" 则改为 import  org.apache.cordova.plugs.R;
       
    3 提供的方法
      xiangbalao.showdalog("正在加载数据...");    //打开进度条
      xiangbalao.closedalog();     //关闭进度条