#### 导出收藏夹里的网址内容
- 火狐：点击星星右边书签侧栏 -> 导入和备份 -> 导出书签到HTML。
- IE：直接点击星星 -> 添加到收藏夹 -> 导入和导出 -> 导出到文件 -> 收藏夹（源、cookies）。
- 谷歌：点击星星右边书签侧栏 -> 书签 -> 书签管理器 -> 整理 -> 将书签导出到HTML文件。

然后选择备份的储存地址并命名保存即可。这个时候收藏夹的保存里面是一个个网站。

##### 书签内容
- HREF，网站链接。
- ADD_DATE，书签收藏时间。
- ICON，图标。

#### 浏览器编码
1. 类chrome浏览器（chrome、360极速浏览器等）

方法：点击浏览器右侧菜单图标，然后依次将鼠标移到“工具”→“编码”即可查看或更改当前页面的编码模式。

2. firefox（Gecko内核）、类IE浏览器（包括IE、搜狗、360浏览器等）

点击浏览器上方菜单栏中“查看”，然后将鼠标移到“编码”。（ie、firefox提供了一个快捷键操作，按alt键菜单栏就会显示，不过过一会又会自动隐藏，所以要再设置下。“菜单栏”-->“查看”-->“工具栏”-->勾选“菜单栏”。）

ie浏览器还有一种简单方法，即：在当前页面右键→“编码”即可。

3. safari（webkit内核）

点击浏览器右侧“打开当前页面菜单”图标，然后打开“文本编码”即可看到编码模式。

4. 除了以上方法查看编码模式之外，还有一种特殊的方法可以实现目标：即通过浏览器的“程序员工具”（在element窗口可查看）

5. 也可在console窗口输入“document.charset”或“document.characterSet”查看。

##### 浏览器引擎（内核）
- WebKit(Safari)
- Gecko(Mozilla Firefox)
- Chorme(Google Chorme)
- Trident/MSHTML(IE)

#### WebKit
WebKit 所包含的 WebCore排版引擎和 JSCore 引擎，均是从KDE的KHTML及KJS引擎衍生而来。它们都是自由软件，在GPL条约下授权，同时支持BSD系统的开发。所以Webkit也是自由软件，同时开放源代码。

WebKit的优势在于高效稳定，兼容性好，且源码结构清晰，易于维护。

尽管Webkit内核是个非常好的网页解析机制，但是由于以往微软把IE捆绑在Windows里(Webkit内核的Safari捆绑在Apple产品里，Chrome捆绑在Google产品里)，导致许多网站都是按照IE来架设的，很多网站不兼容Webkit内核，比如登录界面、网银等网页均不可使用Webkit内核的浏览器。

WebKit内核在手机上的应用：Google的Android、Apple的iPhone、Nokia’s Series 60 browser等所使用的 Browser 内核引擎，都是基于WebKit。uc手机浏览器自称使用u3内核开发，本质是基于开源内核Webkit开发，在Webkit的基础上进行二次优化，并不能算是完全的自主内核。
