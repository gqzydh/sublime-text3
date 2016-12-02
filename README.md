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

  ## 选择类##

  - Ctrl+D 选中光标所占的文本，继续操作则会选中下一个相同的文本。
  - Alt+F3 选中文本按下快捷键，即可一次性选择全部的相同文本进行同时编辑。举个栗子：快速选中并更改所有相同的变量名、函数名等。
  - Ctrl+L 选中整行，继续操作则继续选择下一行，效果和 Shift+↓ 效果一样。
  - Ctrl+Shift+L 先选中多行，再按下快捷键，会在每行行尾插入光标，即可同时编辑这些行。
  - Ctrl+Shift+M 选择括号内的内容（继续选择父括号）。举个栗子：快速选中删除函数中的代码，重写函数体代码或重写括号内里的内容。
  - Ctrl+M 光标移动至括号内结束或开始的位置。
  - Ctrl+Enter 在下一行插入新行。举个栗子：即使光标不在行尾，也能快速向下插入一行。
  - Ctrl+Shift+Enter 在上一行插入新行。举个栗子：即使光标不在行首，也能快速向上插入一行。
  - Ctrl+Shift+[ 选中代码，按下快捷键，折叠代码。
  - Ctrl+Shift+] 选中代码，按下快捷键，展开代码。
  - Ctrl+K+0 展开所有折叠代码。
  - Ctrl+← 向左单位性地移动光标，快速移动光标。
  - Ctrl+→ 向右单位性地移动光标，快速移动光标。
  - shift+↑ 向上选中多行。
  - shift+↓ 向下选中多行。
  - Shift+← 向左选中文本。
  - Shift+→ 向右选中文本。
  - Ctrl+Shift+← 向左单位性地选中文本。
  - Ctrl+Shift+→ 向右单位性地选中文本。
  - Ctrl+Shift+↑ 将光标所在行和上一行代码互换（将光标所在行插入到上一行之前）。
  - Ctrl+Shift+↓ 将光标所在行和下一行代码互换（将光标所在行插入到下一行之后）。
  - Ctrl+Alt+↑ 向上添加多行光标，可同时编辑多行。
  - Ctrl+Alt+↓ 向下添加多行光标，可同时编辑多行。


## 编辑类	##

- - Ctrl+J 合并选中的多行代码为一行。举个栗子：将多行格式的CSS属性合并为一行。
  - Ctrl+Shift+D  复制光标所在整行，插入到下一行。
  - Tab 向右缩进。
  - Shift+Tab 向左缩进。
  - Ctrl+K+K 从光标处开始删除代码至行尾。
  - Ctrl+Shift+K 删除整行。
  - Ctrl+/ 注释单行。
  - Ctrl+Shift+/ 注释多行。
  - Ctrl+K+U 转换大写。
  - Ctrl+K+L 转换小写。
  - Ctrl+Z 撤销。
  - Ctrl+Y 恢复撤销。
  - Ctrl+U 软撤销，感觉和 Gtrl+Z 一样。
  - Ctrl+F2 设置书签
  - Ctrl+T 左右字母互换。
  - F6 单词检测拼写

## 搜索类##

- Ctrl+F 打开底部搜索框，查找关键字。
- Ctrl+shift+F 在文件夹内查找，与普通编辑器不同的地方是sublime允许添加多个文件夹进行查找，略高端，未研究。
- Ctrl+P 打开搜索框。举个栗子：1、输入当前项目中的文件名，快速搜索文件，2、输入@和关键字，查找文件中函数名，3、输入：和数字，跳转到文件中该行代码，4、输入#和关键字，查找变量名。
- Ctrl+G 打开搜索框，自动带：，输入数字跳转到该行代码。举个栗子：在页面代码比较长的文件中快速定位。
- Ctrl+R 打开搜索框，自动带@，输入关键字，查找文件中的函数名。举个栗子：在函数较多的页面快速查找某个函数。
- Ctrl+： 打开搜索框，自动带#，输入关键字，查找文件中的变量名、属性名等。
- Ctrl+Shift+P 打开命令框。场景栗子：打开命名框，输入关键字，调用sublime text或插件的功能，例如使用package安装插件。
- Esc 退出光标多行选择，退出搜索框，命令框等。

## 显示类 ##

- Ctrl+Tab 按文件浏览过的顺序，切换当前窗口的标签页。


- Ctrl+PageDown 向左切换当前窗口的标签页。
- Ctrl+PageUp 向右切换当前窗口的标签页。
- Alt+Shift+1 窗口分屏，恢复默认1屏（非小键盘的数字）
- Alt+Shift+2 左右分屏-2列
- Alt+Shift+3 左右分屏-3列
- Alt+Shift+4 左右分屏-4列
- Alt+Shift+5 等分4屏
- Alt+Shift+8 垂直分屏-2屏
- Alt+Shift+9 垂直分屏-3屏
- Ctrl+K+B 开启/关闭侧边栏。
- F11 全屏模式
- Shift+F11 免打扰模式