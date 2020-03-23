# unity安装以及安卓版本的发布配置
- unity安装及安卓打包配置
## 安装java
- 默认路径安装在C:/Program Files (x86)/Java/jdk1.8.0_144
- ![]()
- ![]()
## 配置环境变量
- 在我的电脑属性中打开高级系统设置>环境变量，添加变量名JAVA_HOME以及值C:\Program Files (x86)\Java\jdk1.8.0_144\
- ![]()
- 再添加变量名path，以及其值%JAVA_HOME%\bin
- ![]()
- 打开cmd进行环境检测
- ![]()
- ![]()
- ![]()
- 上面的命令，如果输入完之后，没有出现相对应的界面，说明环境变量配置的有问题。
## 安装安装开放平台
- 下载sdk安装包，以及点击sdk manger进行其他模块的下载
- ![]()
- 启动unity找到preference，打开external tool,修改里面的sdk和jdk
- ![]()
## 尝试打包文件
- 新建场景，保存场景，添加到build里面去切换平台为安卓Android平台，切换，点击Player settings修改Other Settings BundleIdentifiercom.Company.ProductName为自己的自定义的，例如：com.wahhh.sj，修改完成后，点击Build。
- ![]()
- ![]()
