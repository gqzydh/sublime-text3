## Sublime text3 

> 收集sublime text3 一些前端常用插件，包管理，快捷键，等相关内容的聚合。
>
> 不断完善中……

## 慨序

- ### Sublime text 安装，及安装插件

  - [Sublime Text](http://www.sublimetext.com/)     下载安装

    >  按ctrl+~或者菜单View > Show Console打开命令窗口，粘贴以下代码并回车即可：

  ```code
  import urllib.request,os,hashlib; h = '2915d1851351e5ee549c20394736b442' + '8bc59f460fa1548d1514676163dafc88'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by) 
  ```

  - [Package Control](https://packagecontrol.io/)   安装包管理 

    > 按下Ctrl+Shift+P调出命令面板，输入 Install Package 回车，然后可以在列表中选中要安装的插件。

- ### 精选插件

  - Alignment - 自动代码对齐

  - Bracket Highlighter - 匹配括号

  - [docblockr](https://packagecontrol.io/packages/DocBlockr) - 注释插件

  - CSSComb - CSS属性进行排序的格式化插件

  - ConvertToUTF8 - 转码成utf-8，解决乱码

  - CSScomb CSS - 属性排序

  - ColorPicker - 调色盘

  - [Emmet](https://packagecontrol.io/packages/Emmet) - 提高书写 HTML/CSS 代码速度, html,css代码补全。

  - [FoldPython](https://packagecontrol.io/packages/Fold%20Python) -智能折叠和代码导航

  - [GBK to UTF8](http://www.sublimetext.com/forum/viewtopic.php?f=5&p=22274) - 编码从GBK转黄成UTF8，快捷键Ctrl+Shift+C

  - Grunt

  - [Pretty JSON](https://packagecontrol.io/packages/Pretty%20JSON) - 格式化 JSON

  - [Sublime-Minifier](#Sublime-Minifier) - JavaScript和CSS压缩插件

  - SublimeLinter - 代码检查插件

    > 支持JavaScript、CSS、HTML、Java、PHP、Python、Ruby等十多种开发语言，但前提是需要配置相应语言的环境，要检查JavaScript代码需要安装node.js，检查PHP代码需要安装PHP并配置环境等，及时提示编写代码中存在的不规范和错误的写法。

  - [Sublime CodeIntel](https://github.com/SublimeCodeIntel/SublimeCodeIntel) - 代码提示和补全插件

    > 支持 JavaScript、Mason、XBL、XUL、RHTML、SCSS、Python、HTML、Ruby、Python3、XML、Sass、XSLT、Django、HTML5、Perl、CSS、Twig、Less、Smarty、Node.js、Tcl、TemplateToolkit 和 PHP 等所有语言

  - SideBarEnhancements - 设置sublime text2/3支持浏览器预览

  - Side Bar

  - Stylus

  - Tag - Html格式化

  - Prefixr - css自动添加 -webkit 等私有词缀

  - Projects - 项目

  - HTML5 - html5

  - HTML/CSS/JS Prettify

  - CSS3 - css3

  - Sass - sass

  - Nodejs

  - JS Format - 一个JS代码格式化插件。

  - FileDiffs - SublimeText中两个不同文件的差异

  - HTML/CSS/JS Prettify

  - Terminal

- ### HTML/CSS

  - [HTML5](https://packagecontrol.io/packages/HTML5) 
  - [CSS3](https://packagecontrol.io/packages/CSS3) 

- ### HTML 预处理器/模板 

  - [Haml](https://packagecontrol.io/packages/Haml)  
  - [Jade](https://packagecontrol.io/packages/Jade)
  - [Jade Snippets](https://packagecontrol.io/packages/Jade%20Snippets) 
  - [Ruby Slim](https://packagecontrol.io/packages/Ruby%20Slim) 
  - [HTML Mustache](https://packagecontrol.io/packages/HTML%20Mustache)
  - [Handlebars](https://packagecontrol.io/packages/Handlebars) 

- ### CSS预处理器

  - [Sass](https://packagecontrol.io/packages/Sass)
  - [Sass Snippets](https://packagecontrol.io/packages/SASS%20Snippets) 
  - [SCSS](https://packagecontrol.io/packages/SCSS) 
  - [SCSS Snippets](https://packagecontrol.io/packages/SCSS%20Snippets) 
  - [LESS](https://packagecontrol.io/packages/LESS) 
  - [Stylus](https://packagecontrol.io/packages/Stylus) 
  - [Stylus Snippets](https://packagecontrol.io/packages/Stylus-Snippets) 

- ### css框架###

  - [Bootstrap 3 Snippets](https://packagecontrol.io/packages/Bootstrap%203%20Snippets) 
  - [Bootstrap 4 Snippets](https://packagecontrol.io/packages/Bootstrap%204%20Snippets) 
  - [Foundation 5 Snippets](https://packagecontrol.io/packages/Foundation%205%20Snippets) 
  - [Semantic UI](https://packagecontrol.io/packages/Semantic%20UI) -
  - [Materialized](https://packagecontrol.io/packages/Materialized%20CSS%20Snippets) 
  - [Susy](https://packagecontrol.io/packages/Susy%20Snippets) 
  - [UIkit Autocomplete](https://packagecontrol.io/packages/UIkit%20autocomplete) 
  - [PureCSS](https://packagecontrol.io/packages/PureCSS) -

- ### HTML-CSS-JS 美化###

  - [HTMLTidy](https://packagecontrol.io/packages/HtmlTidy) - 格式化HTML代码
  - [HTML-CSS-JS-Prettify](https://packagecontrol.io/packages/HTML-CSS-JS%20Prettify) - 格式化 HTML, CSS 和 JavaScript

- ### 自动化###

  - [Grunt](https://packagecontrol.io/packages/Grunt) 
  - [Gulp](https://packagecontrol.io/packages/Gulp) 
  - [Bower](https://packagecontrol.io/packages/Bower) 

- ### JS 构架###

  - [jQuery](https://packagecontrol.io/packages/jQuery) 
  - [jQuery Mobile Snippets](https://packagecontrol.io/packages/jQuery%20Mobile%20Snippets) 
  - [AngularJS](https://packagecontrol.io/packages/AngularJS) 
  - [Backbone.js](https://packagecontrol.io/packages/Backbone.js) 
  - [Ember.js Snippets](https://packagecontrol.io/packages/Ember.js%20Snippets) 
  - [ReactJS](https://packagecontrol.io/packages/ReactJS) 
  - [Underscorejs Snippets](https://packagecontrol.io/packages/Underscorejs%20snippets) 
  - [Vuejs Snippets](https://packagecontrol.io/packages/Vuejs%20Snippets) 
  - [Sublime-KnockoutJS-Snippets](https://packagecontrol.io/packages/Sublime-KnockoutJS-Snippets) 

- ### sublime常用快捷键  ###

  - Ctrl+Shift+P：打开命令面板
  - Ctrl+Alt+F：对代码进行格式化
  - Ctrl+P：搜索项目中的文件
  - Ctrl+G：跳转到第几行
  - Ctrl+W：关闭当前打开文件
  - Ctrl+Shift+W：关闭所有打开文件
  - Ctrl+Shift+V：粘贴并格式化
  - Ctrl+D：选择单词，重复可增加选择下一个相同的单词
  - Ctrl+L：选择行，重复可依次增加选择下一行
  - Ctrl+Shift+L：选择多行
  - Ctrl+Shift+Enter：在当前行前插入新行
  - Ctrl+X：删除当前行
  - Ctrl+M：跳转到对应括号
  - Ctrl+U：软撤销，撤销光标位置
  - Ctrl+J：选择标签内容
  - Ctrl+F：查找内容
  - Ctrl+Shift+F：查找并替换
  - Ctrl+H：替换
  - Ctrl+R：前往 method
  - Ctrl+N：新建窗口
  - Ctrl+K+B：开关侧栏
  - Ctrl+Shift+M：选中当前括号内容，重复可选着括号本身
  - Ctrl+F2：设置/删除标记
  - Ctrl+/：注释当前行
  - Ctrl+Shift+/：当前位置插入注释
  - Ctrl+Alt+/：块注释，并Focus到首行，写注释说明用的
  - Ctrl+Shift+A：选择当前标签前后，修改标签用的
  - F11：全屏
  - Shift+F11：全屏免打扰模式，只编辑当前文件
  - Alt+F3：选择所有相同的词
  - Alt+.：闭合标签
  - Alt+Shift+数字：分屏显示
  - Alt+数字：切换打开第N个文件
  - Shift+右键拖动：光标多不，用来更改或插入列内容，鼠标的前进后退键可切换Tab文件
    按Ctrl，依次点击或选取，可需要编辑的多个位置
  - 按Ctrl+Shift+上下键，可替换Ctrl+D 选词 （反复按快捷键，即可继续向下同时选中下一个相同的文本进行同时编辑）
  - Ctrl+G 跳转到相应的行
  - Ctrl+J 合并行（已选择需要合并的多行时）
  - Ctrl+L 选择整行（按住-继续选择下行）
  - Ctrl+M 光标移动至括号内开始或结束的位置
  - Ctrl+T 词互换
  - Ctrl+U 软撤销
  - Ctrl+P 查找当前项目中的文件和快速搜索；输入 @ 查找文件主标题/函数；或者输入 : 跳转到文件某行；
  - Ctrl+R 快速列出/跳转到某个函数
  - Ctrl+K Backspace 从光标处删除至行首
  - Ctrl+K+B 开启/关闭侧边栏
  - Ctrl+KK 从光标处删除至行尾
  - Ctrl+K+T 折叠属性
  - Ctrl+K+U 改为大写
  - Ctrl+K+L 改为小写
  - Ctrl+K+0 展开所有
  - Ctrl+Enter 插入行后（快速换行）
  - Ctrl+Tab 当前窗口中的标签页切换
  -   Ctrl+Shift+A 选择光标位置父标签对儿
  -   Ctrl+Shift+D 复制光标所在整行，插入在该行之前
  -   ctrl+shift+F 在文件夹内查找，与普通编辑器不同的地方是sublime允许添加多个文件夹进行查找
  -   Ctrl+Shift+K 删除整行
  -   Ctrl+Shift+L 鼠标选中多行（按下快捷键），即可同时编辑这些行
  -   Ctrl+Shift+M 选择括号内的内容（按住-继续选择父括号）
  -   Ctrl+Shift+P 打开命令面板
  -   Ctrl+Shift+/ 注释已选择内容
  -   Ctrl+Shift+↑可以移动此行代码，与上行互换
  -   Ctrl+Shift+↓可以移动此行代码，与下行互换
  -   Ctrl+Shift+[ 折叠代码
  -   Ctrl+Shift+] 展开代码
  -   Ctrl+Shift+Enter 光标前插入行
  -   Ctrl+PageDown 、Ctrl+PageUp 文件按开启的前后顺序切换
  -   Ctrl+Z 撤销
  -   Ctrl+Y 恢复撤销
  -   Ctrl+F2 设置/取消书签
  -   Ctrl+/ 注释整行（如已选择内容，同“Ctrl+Shift+/”效果）
  -   Ctrl+鼠标左键 可以同时选择要编辑的多处文本
  -   Shift+鼠标右键（或使用鼠标中键）可以用鼠标进行竖向多行选择
  -   Shift+F2 上一个书签
  -   Shift+Tab 去除缩进
  -   Alt+Shift+1（非小键盘）窗口分屏，恢复默认1屏
  -   Alt+Shift+2 左右分屏-2列
  -   Alt+Shift+3 左右分屏-3列 ……
  -   Ctrl+Shift+分屏序号 将当前焦点页分配到分屏序号页
  -   Alt+. 闭合当前标签
  -   Alt+F3 选中文本按下快捷键，即可一次性选择全部的相同文本进行同时编辑
  -   Tab 缩进 自动完成
  -   F2 下一个书签
  -   F6 检测语法错误
  -   F9 行排序(按a-z)
  -   F11 全屏模式


  ​
