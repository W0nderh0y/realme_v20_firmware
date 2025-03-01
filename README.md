# realme V20 全网通 (RMX3611) 官方系统包
## realme V20 carrier unlocked (RMX3611) official firmware
### 自己抓取方法（需要一台运行Windows的电脑和一根数据线无需root，理论上适用所有realme, oppo, oneplus）
1. 安装运行[mitmproxy](https://mitmproxy.org/)，配置好系统全局代理8080端口和[CA根证书](http://mitm.it/)
2. 安装运行[realme UI升级工具](https://rms11.realme.net/SW/Tools/realmeUpgradeToolSetup_CN_V1.0.7.exe)（oppo安装[ColorOS升级工具](https://coloros-website-cn.allawnfs.com/upgradetool/OplusUpgradeToolSetup.exe)）
3. 手机打开USB调试连接电脑，点击开始升级
4. 在mitmproxy里找到最后一条allawnfs.com请求，复制URL（.zip结尾）
5. 用aria2下载 参照[403报错解决教程](https://oxygenupdater.com/article/474/)

### 历史版本
[A.36（补丁版本25年1月）](https://www.dropbox.com/scl/fi/4lhbgxauo137hsjzpr2eu/RMX3611_11_A.36.zip?rlkey=qgjz2w6r21qpz627eqe5eg94f&dl=0)
