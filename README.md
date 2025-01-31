# kiftd数据库升级工具
## 该工具可用于将v1.0.35或更早版本的kiftd文件系统中的数据升级为1.1.0或更新版本可识别的格式
### _kiftd官方网站：https://kohgylw.gitee.io/_

------

### 使用方法：
+ 退出旧版本（1.0.35或更早版本）。
+ 解压下载好的新版本（1.1.0或更新版本），并将其中的：jar主程序 、 WebContext文件夹 、 mybatisResource文件夹 、 libs文件夹 以及 fonts文件夹 共【五项】内容全部复制至旧版本的程序主目录内，替换旧版本中对应的文件和文件夹 (旧版本的jar主程序并不会被替换，您可以手动删除它)。
+ 下载并解压本工具，然后将其中的“kiftdDBUpgradeTool.jar”程序拷贝至待升级的kiftd程序主目录内（仅需拷贝指定的jar程序即可，无需拷贝其他文件）。
+ 启动本工具，并点击“升级”按钮。
+ 升级成功后，点击“退出”按钮退出该工具（之后您可以选择删除该工具）。
+ 开始体验新版本。

_提示：如果您希望通过命令的方式使用“kiftd数据库升级工具”来进行升级，也可以通过执行“java -jar kiftdDBUpgradeTool.jar -upgrade”命令来完成第4步的操作。_

------

### 程序界面：

[![kiftd-DBUpgrade-Tool-ui.png](https://i.postimg.cc/htcjqB4Q/kiftd-DBUpgrade-Tool-ui.png)](https://postimg.cc/QHYspvTj)

------

### 开源声明：

您可以免费下载和使用本程序及其源代码，并用于任何目的，详细内容请参阅程序中附带的《使用许可》。

------

青阳龙野@kohgylw by 2022年10月08日