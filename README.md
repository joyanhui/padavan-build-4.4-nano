# Padavan-build说明

步骤

0.点击右上角的Fork按钮，进入自己fork后的仓库。

1.修改/workflows/build-padavan.yml里的插件与机型。修改TNAME: K2P 中的K2P为需要编译的型号， 可以自定义几个模块

2.点击页面上部的Actions按钮，点击I understand my workflows，go ahead and enable them绿色按钮启用action。

3.点击右上角的 Star 星星按钮即可开始自动编译（自己点击才会编译）。修改配置后若需再次编译，先点击Star取消Star后，再点击Star即可重新编译。

编译完成后在Actions页面底部下载固件。
# joyanhui 补充
> 因为ubuntu18.04已经不支持，换到20.04

部分插件的源失效，自己找新源替换一下  

## 参考
https://github.com/chongshengB/Padavan-build  
https://github.com/xiaiohuan/Padavan-build-4.4  
