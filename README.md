#### Q1. 什么是PHP?
Answer: PHP 是一种基于脚本的web开发语言，广泛用于创建动态网页。
PHP是一直服务器端的脚本语言用于创建web应用程序，已经有很多的框架用来创建web站点。比较出名的有CMS框架有WordPress, osCommerce等。它和java， C#等类似属于面向对象的编程语言，入手很简单。

#### Q2. PHP的缩写是？

Answer: PHP全称 Hypetext Preprocessor. 中文名：“超文本预处理器” 。

#### Q3 PHP 语法类似那种语言

Answer:  PHP 语言类似 Perl 和 C 。

#### Q4 PEAR是指？

Answer: PEAR 是指 "PHP Extension and Application Repository".  它是一个PHP扩展及应用的一个代码仓库。

#### Q5 什么是 Open Source Software?

Answer:  开源软件是指源码可以被任何人免费使用，修改和分享，通常也在某些开源协议下进行分发。

#### Q6 include(), include_once(), require, require_once的差别

Answer: include 语句将在其被调用的位置处包含一个文件，包含一个文件与在该语句所在位置复制指定文件具有相同的效果， require 与 include 类似， 不同的是require在出错时， 脚本将停止运行，而在使用include的情况下，脚本将继续执行。include_once, require_once 函数确保文件只包含一次。

#### Q7  GET, POST，REQUEST 方法的差别

Answer: GET和POST一般用户客户端传递数据到服务器端，GET方法是将请求信息以键值对的形式放在URL上，默认GET方法最大的信息为512个字符。
POST是通过HTTP Header 传递数据，数据大小没有限制，通常传递隐私数据， ASCII 以及二进制数据等。而$_REQUEST则包含$_GET, $_POST, $_COOKIE。

#### Q8  PHP错误类型

Answer: 错误类型有:

* E_ERROR 致命的运行错误。错误无法恢复，暂停执行脚本。
* E_WARNING 运行时警告(非致命性错误)。非致命的运行错误，脚本执行不会停止。
* E_PARSE 编译时解析错误。解析错误只由分析器产生。
* E_NOTICE 运行时提醒(这些经常是你代码中的bug引起的，也可能是有意的行为造成的。)
16 E_CORE_ERROR PHP启动时初始化过程中的致命错误。
32 E_CORE_WARNING PHP启动时初始化过程中的警告(非致命性错)。
64 E_COMPILE_ERROR 编译时致命性错。这就像由Zend脚本引擎生成了一个E_ERROR。
* E_COMPILE_WARNING 编译时警告(非致命性错)。这就像由Zend脚本引擎生成了一个E_WARNING警告。
* E_USER_ERROR 用户自定义的错误消息。这就像由使用PHP函数trigger_error（程序员设置E_ERROR）
* E_USER_WARNING 用户自定义的警告消息。这就像由使用PHP函数trigger_error（程序员设定的一个E_WARNING警告）
* E_USER_NOTICE 用户自定义的提醒消息。这就像一个由使用PHP函数trigger_error（程序员一个E_NOTICE集）
* E_STRICT 编码标准化警告。允许PHP建议如何修改代码以确保最佳的互操作性向前兼容性。
* E_RECOVERABLE_ERROR 开捕致命错误。这就像一个E_ERROR，但可以通过用户定义的处理捕获（又见set_error_handler（））
* E_ALL 所有的错误和警告(不包括 E_STRICT) (E_STRICT will be part of E_ALL as of PHP 6.0)

#### Q9 什么是session, 为什么使用它

Answer:  session是指终端用户访问服务器在这个会话中不同页面切换共享的全局数据。session数据保存在服务器端，每个session都有一个唯一的sessionId。


#### 10 什么是cookie, 为什么使用它

Answer: cookie是保存在客户端的数据，一些网站用来区分鉴别用户。php可以set和get cookie。

















 