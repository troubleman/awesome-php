# 棒棒哒PHP 
A curated list of amazingly awesome PHP libraries, resources and shiny things.
### [ENGLISH](https://github.com/troubleman/awesome-php/blob/master/README.md)

## 贡献
详情请看 [CONTRIBUTING](https://github.com/troubleman/awesome-php/blob/master/CONTRIBUTING.md)

## 目录
- [Awesome PHP](#awesome-php)
	- [依赖管理](#依赖管理)
	- [依赖管理的附加部分](#依赖管理的附加部分)
	- [框架](#框架)
	- [框架的附加部分](#框架的附加部分)
	- [框架组件](#框架组件)
	- [微型框架](#微型框架)
	- [微型框架的附加部分](#微型框架的附加部分)
    - [路由](#路由)
	- [模板](#模板)
	- [静态站点生成器](#静态站点生成器)
	- [HTTP](#http)
	- [Middlewares](#middlewares)
	- [URL](#url)
	- [Email](#email)
	- [文件](#文件)
	- [流](#流)
	- [依赖注入](#依赖注入)
	- [图像](#图像)
	- [测试](#测试)
	- [持续集成](#持续集成)
	- [文档](#文档)
	- [安全性](#安全性)
	- [密码](#密码)
	- [代码分析](#代码分析)
	- [Architectural](#architectural)
	- [调试和分析](#调试和分析)
	- [Build Tools](#build-tools)
	- [Task Runners](#task-runners)
	- [Navigation](#navigation)
	- [Asset Management](#asset-management)
	- [Geolocation](#geolocation)
	- [Date and Time](#date-and-time)
	- [Event](#event)
	- [Logging](#logging)
	- [E-commerce](#e-commerce)
	- [PDF](#pdf)
	- [Office](#office)
	- [Database](#database)
	- [Migrations](#migrations)
	- [NoSQL](#nosql)
	- [Queue](#queue)
	- [Search](#search)
	- [Command Line](#command-line)
	- [Authentication and Authorization](#authentication-and-authorization)
	- [Markup](#markup)
	- [Strings](#strings)
	- [Numbers](#numbers)
	- [Filtering and Validation](#filtering-and-validation)
	- [API](#api)
	- [Caching](#caching)
	- [Data Structure and Storage](#data-structure-and-storage)
	- [Notifications](#notifications)
	- [Deployment](#deployment)
	- [Internationalisation and Localisation](#internationalisation-and-localisation)
	- [Third Party APIs](#third-party-apis)
	- [Extensions](#extensions)
	- [Miscellaneous](#miscellaneous)
- [Software](#software)
	- [PHP Installation](#php-installation)
	- [Development Environment](#development-environment)
	- [Virtual Machines](#virtual-machines)
	- [Integrated Development Environment](#integrated-development-environment)
	- [Web Applications](#web-applications)
- [Resources](#resources)
	- [PHP Websites](#php-websites)
	- [Other Websites](#other-websites)
	- [PHP Books](#php-books)
	- [PHP Videos](#php-videos)
	- [PHP Reading](#php-reading)
	- [PHP Internals Reading](#php-internals-reading)
- [Contributing](#contributing)

## 依赖管理
*——用于依赖管理的包和框架*

* [Composer](http://getcomposer.org/)/[Packagist](http://packagist.org/) - 一个包和依赖管理器。
* [Composer Installers](https://github.com/composer/installers) - 一个多框架Composer库安装器。
* [Pickle](https://github.com/FriendsOfPHP/pickle) - 可以在任意平台上安装PHP扩展包。

## 依赖管理的附加部分
*——其它依赖管理的相关工具*

* [Satis](https://github.com/composer/satis) - 静态的Composer库生成器。
* [Toran Proxy](https://toranproxy.com) - A static Composer repository and proxy.
* [Composition](https://github.com/bamarni/composition) - 一个运行时检查Composer环境的库。
* [Version](https://github.com/herrera-io/php-version) - 一个在语义上分析和比较的库。
* [NameSpacer](https://github.com/ralphschindler/Namespacer) - 将下划线转为命名空间的库。
* [Patch Installer](https://github.com/goatherd/patch-installer) - 使用Composer安装补丁的库。
* [Composer Checker](https://github.com/silpion/composer-checker) - 一个验证Composer配置的工具。

## 框架
*——Web开发框架*

* [Symfony2](http://symfony.com/) -由独立组件构成的框架。
* [Zend Framework 2](http://framework.zend.com) - 同样是由独立组件构成的框架
* [Laravel 5](http://laravel.com/) - 简洁优雅的PHP Web开发框架。
* [Aura PHP](http://auraphp.com/) - 独立组件的框架。
* [Yii2](https://github.com/yiisoft/yii2/) - 用于开发大型Web应用的高性能PHP框架。
* [Nette](http://nette.org) - 同样是由独立组件构成的框架。
* [PPI Framework 2](http://www.ppi.io) - 一个交互性的框架。
* [CakePHP](http://cakephp.org/) - A rapid application development framework.
* [Phalcon](http://phalconphp.com/en/) - 一个作为C扩展的框架。

## 框架的附加部分
*——其它关于Web开发框架的相关工具*

* [Symfony CMF](https://github.com/symfony-cmf/symfony-cmf) - 一个创建自定义CMS的内容管理框架。
* [Knp RAD Bundle](http://rad.knplabs.com/) - Symfony2的快速应用程序包（RAD）。

## Components
*——来自Web开发框架的组件*

* [Symfony2 Components](http://symfony.com/doc/master/components/index.html) - 关于Symphony2的组件。
* [Zend Framework 2 Components](https://packages.zendframework.com/) - 关于ZF2的组件。
* [Aura Components](http://auraphp.github.com/) - 一个PHP5.4的组件包。
* [Hoa Project](http://hoa-project.net/En/) - 另一个PHP组件包。
* [League of Extraordinary Packages](https://thephpleague.com/) - A PHP package development group.

## 微型框架
*——微型框架和路由*

* [Silex](http://silex.sensiolabs.org/) - 基于Symphony2组件的微型框架。
* [Slim](http://www.slimframework.com/) - 另一个简单的微型框架。
* [Bullet PHP](http://bulletphp.com/) - 用于构建REST APIs的微型框架。
* [Lumen](http://lumen.laravel.com) - A micro-framework by Laravel.

## 微型框架的附加部分
*——其它相关的微型框架和路由*

* [Silex Skeleton](https://github.com/fabpot/Silex-Skeleton) - 用于Silex的项目框架。
* [Silex Web Profiler](https://github.com/silexphp/Silex-WebProfiler) - 用于Silex的Web调试工具条。
* [Slim Skeleton](https://github.com/codeguy/Slim-Skeleton) -  用于Slim的框架。
* [Slim View](https://github.com/codeguy/Slim-Views) - Slim的自定义视图集。

## 路由
*Libraries for handling application routing.*
* [Fast Route](https://github.com/nikic/FastRoute) - A fast routing library.
* [Route](https://github.com/thephpleague/route) - A routing library built on top of Fast Route.
* [Pux](https://github.com/c9s/Pux) - Another fast routing library.
* [Klein](https://github.com/chriso/klein.php) - A flexible router.

## 模板
*——模板和词法分析的库与工具*

* [Twig](http://twig.sensiolabs.org/) - 一种综合的模板语言。
* [Twig Cache Extension](https://github.com/asm89/twig-cache-extension) - 用于Twig的模板片段缓存库。
* [Mustache](https://github.com/bobthecow/mustache.php) - PHP实现的Mustache模板语言。
* [Phly Mustache](https://github.com/weierophinney/phly_mustache) - 另一个PHP实现的Mustache模板语言。
* [MtHaml](https://github.com/arnaud-lb/MtHaml) -  PHP实现的HAML模板语言。
* [PHPTAL](http://phptal.org/) -  PHP实现的TAL模板语言。 [TAL](http://en.wikipedia.org/wiki/Template_Attribute_Language) 模板语言。
* [Plates](http://platesphp.com/) - 一个原始的PHP模板库。
* [Lex](https://github.com/pyrocms/lex) -一个轻量级模板解析器。

## 静态站点生成器
*——生成Web页面内容的预处理工具*

* [Sculpin](http://sculpin.io) - 将Markdown和Twig转换为静态HTML的工具
* [Phrozn](http://phrozn.info) - 另一款将Textile、Markdown和Twig转为HTML的工具

## HTTP
*——用于HTTP和抓取网站的库*

* [Guzzle]( https://github.com/guzzle/guzzle) - 一个完整的HTTP客户端。
* [Buzz](https://github.com/kriswallsmith/Buzz) - 另一个HTTP客户端。
* [Requests](https://github.com/rmccue/Requests) - 一个简单的HTTP库。
* [HTTPFul](https://github.com/nategood/httpful) - 一个链式HTTP客户端。
* [Goutte](https://github.com/fabpot/Goutte) -  一个简单的Web抓取器。
* [PHP VCR](http://php-vcr.github.io/) - 一个录制和回放HTTP请求的库。

## Middlewares
*Libraries for building application using middlewares.*

* [Stack](https://github.com/stackphp) - A library of stackable middleware for Silex/Symfony.
* [Slim Middleware](https://github.com/codeguy/Slim-Middleware) - A collection of custom middleware for Slim.
* [Conduit](https://github.com/phly/conduit) - A port of [Sencha Connect](https://github.com/senchalabs/connect) to PHP.

## URL
*——解析URL的库*

* [Purl](https://github.com/jwage/purl) - 一个URL操作库。
* [PHP Domain Parser](https://github.com/jeremykendall/php-domain-parser) - 一个域名后缀解析器
* [Url](https://github.com/thephpleague/url) - 一个简单的URL操作库。

## Email
*——用于发送和解析Email的库*

* [SwiftMailer](http://swiftmailer.org/) - 一个邮件程序的解决方案。
* [PHPMailer](https://github.com/PHPMailer/PHPMailer) - 另一个邮件程序的解决方案。
* [Fetch](https://github.com/tedivm/Fetch) - 一个IMAP库。
* [Email Reply Parser](https://github.com/willdurand/EmailReplyParser) - 一个邮件回复解析器库。
* [Stampie](https://github.com/henrikbjorn/Stampie) - 关于邮件服务的库，比如 [SendGrid](http://sendgrid.com), [PostMark](http://postmarkapp.com), [MailGun](http://www.mailgun.com) 和 [Mandrill](http://www.mandrill.com).
* [CssToInlineStyles](https://github.com/tijsverkoyen/CssToInlineStyles) - 邮件模板中一个内联的CSS库。
* [Email Validator](https://github.com/nojacko/email-validator) - 一个小的电子邮件地址验证库。

## 文件
*——关于文件处理和MIME类型检查*

* [Gaufrette](https://github.com/KnpLabs/Gaufrette) - 一个文件流的抽象层。
* [Flysystem](https://github.com/FrenkyNet/Flysystem) - 另一个文件流的抽象层。
* [Canal](https://github.com/dflydev/dflydev-canal) - 一个检查互联网媒体类型的库。
* [Apache MIME Types](https://github.com/dflydev/dflydev-apache-mime-types) - 一个解析Apache MIME类型的库。
* [Ferret](https://github.com/versionable/Ferret) - 一个MIME检测库。
* [Hoa Mime](https://github.com/hoaproject/Mime) -  另一个MIME检测库。
* [Lurker](https://github.com/henrikbjorn/Lurker) - 一个资源跟踪库。
* [PHP File Locator](https://github.com/herrera-io/php-file-locator) - 一个在大型项目中定位文件的库。
* [PHP FFmpeg](https://github.com/alchemy-fr/PHP-FFmpeg/) - 一个用于[FFmpeg](http://www.ffmpeg.org/) 视频包装的库
* [CSV](https://github.com/thephpleague/csv) - 一个CSV数据操作库。

## 流
*——处理流的库*

* [Streamer](https://github.com/fzaninotto/Streamer) - 一个简单的面向对象流包装库。

## 依赖注入
*——实现依赖注入设计模式的库*

* [Pimple](http://pimple.sensiolabs.org/) - 一个小的依赖注入容器
* [Auryn](https://github.com/rdlowrey/Auryn) - 另一个小的依赖注入容器
* [Container](https://github.com/thephpleague/container) - 另一个灵活的依赖注入容器。
* [PHP DI](http://mnapoli.github.com/PHP-DI/) - 一个使用标注实现的依赖注入。
* [Acclimate](https://github.com/jeremeamia/acclimate) - 依赖注入容器和服务定位器的通用接口。

## 图像
*——处理图像的库*

* [Imagine](http://imagine.readthedocs.org/en/latest/index.html) - 一个图像处理库。
* [PHP Image Workshop](https://github.com/Sybio/ImageWorkshop) - 另一个图像处理库。
* [Intervention Image](https://github.com/Intervention/image) - 同样还是一个图像处理库。
* [GIF Frame Extractor](https://github.com/Sybio/GifFrameExtractor) - 一个提取GIF动画帧信息的库。
* [GIF Creator](https://github.com/Sybio/GifCreator) - 从多幅图片中创建GIF动画的库。
* [Image With Text](https://github.com/nmcteam/image-with-text) - 在图像中嵌入文本的库。
* [Color Extractor](https://github.com/php-loep/color-extractor) - 从图像中提取颜色的库。
* [Glide](https://github.com/thephpleague/glide) - 按需求而定的图像处理库。
* [Image Optimizer](https://github.com/psliwa/image-optimizer) - 优化图像的库。

## 测试
*——测试代码库和生成测试数据的库*

* [PHPUnit](https://github.com/sebastianbergmann/phpunit) - 一个单元测试框架。
* [DBUnit](https://github.com/sebastianbergmann/dbunit) - PHPUnit的代码测试库
* [ParaTest](https://github.com/brianium/paratest) - PHPUnit的并行测试库。
* [PHPSpec](https://github.com/phpspec/phpspec) - 根据规范的单元测试库。
* [Codeception](https://github.com/Codeception/Codeception) - 一个全栈测试框架。
* [AspectMock](https://github.com/Codeception/AspectMock) - PHPUnit/Codeception的模拟框架。
* [Atoum](https://github.com/atoum/atoum) - 一个简单的测试库。
* [Mockery](https://github.com/padraic/mockery) - 一个用于测试的模拟对象库。
* [Phake](https://github.com/mlively/Phake) - 另一个用于测试的模拟对象库。
* [Prophecy](https://github.com/phpspec/prophecy) - 一个强大的模拟框架。
* [Faker](https://github.com/fzaninotto/Faker) - 一个伪数据生成库。
* [Samsui](https://github.com/mauris/samsui) - 另一个伪数据生成库
* [Alice](https://github.com/nelmio/alice) - 用于生成复杂数据的库。
* [Behat](http://behat.org/) - 一个行为驱动开发（BDD）的测试框架。
* [Pho](https://github.com/danielstjules/pho) - 另一个行为驱动开发的测试框架。
* [Mink](http://mink.behat.org/) - Web验收测试。
* [HTTP Mock](https://github.com/InterNations/http-mock) - 一个在单元测试中模拟HTTP请求的库。
* [VFS Stream](https://github.com/mikey179/vfsStream) - 一个用于测试的虚拟文件系统流包装。
* [VFS](https://github.com/adlawson/vfs.php) - 另一个用于测试的虚拟文件系统。
* [Locust](http://locust.io/) - 一个Python开发的现代负载测试库。
* [Peridot](https://github.com/peridot-php/peridot) - 一个事件驱动的测试框架。

## 持续集成
*——持续集成的库和应用*

* [Travis CI](https://travis-ci.org/) - 一个持续集成的平台。
* [SemaphoreCI](https://semaphoreapp.com/) - 一个开放源码和私人项目持续集成平台。
* [PHPCI](http://www.phptesting.org/) - 一个PHP的开源持续集成平台。
* [Sismo](http://sismo.sensiolabs.org/) - 一个持续的测试服务器库。
* [Jenkins](http://jenkins-ci.org/) ——  [PHP support](http://jenkins-php.org/index.html)的持续集成平台。
* [JoliCi](https://github.com/jolicode/JoliCi) —— PHP开发的由Docker支持的持续集成客户端。

## 文档
*——生成项目文档的库*

* [Sami](https://github.com/fabpot/Sami) - 一个API文档生成器。
* [APIGen](https://github.com/apigen/apigen) - 另一个API文档生成器。
* [PHP Documentor 2](https://github.com/phpDocumentor/phpDocumentor2) - 文档生成器。
* [phpDox](http://phpdox.de/) - PHP项目的文档生成器（不仅仅是API文档）。

## 安全性
*——用于生成安全的随机数、加密数据、扫描漏洞的库*

* [HTML Purifier](https://github.com/ezyang/htmlpurifier) - 标准的HTML过滤器。
* [RandomLib](https://github.com/ircmaxell/RandomLib) - 生成随机数和随机字符串的库。
* [True Random](https://github.com/pixeloution/true-random) - 使用 [www.random.org](http://www.random.org/)生成随机数的库。
* [SecurityMultiTool](https://github.com/padraic/SecurityMultiTool) - 一个PHP安全库。
* [PHPSecLib](http://phpseclib.sourceforge.net/) - 一个纯的PHP安全通信库。
* [TCrypto](https://github.com/timoh6/TCrypto) - 一个简单的键值加密存储库。
* [PHP IDS](https://github.com/PHPIDS/PHPIDS) - 一个结构化的PHP安全层。
* [PHP SSH](https://github.com/Herzult/php-ssh) - 面向对象的SSH包装库。
* [IniScan](https://github.com/psecio/iniscan) - 一个扫描PHP INI文件安全的工具。
* [SensioLabs Security Check](https://security.sensiolabs.org/) - 一个根据安全建议检查Composer依赖的Web工具。
* [Zed](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project) - 用于Web应用的集成渗透测试工具。

## Passwords
*Libraries and tools for working with and storing passwords.*

* [Password Compat](https://github.com/ircmaxell/password_compat) - A compatibility library for the new PHP 5.5 password functions.
* [phpass](http://www.openwall.com/phpass/) - A portable password hashing framework.
* [PHP Password Lib](https://github.com/ircmaxell/PHP-PasswordLib) - A library for generating and validating passwords.
* [Password Policy](https://github.com/ircmaxell/password-policy) - A password policy library for PHP and JavaScript.
* [Password Validator](https://github.com/jeremykendall/password-validator) - A library for validating and upgrading password hashes.
* [Zxcvbn PHP](https://github.com/bjeavons/zxcvbn-php) - A realistic PHP password strength estimate library based on Zxcvbn JS.
* [GenPhrase](https://github.com/timoh6/GenPhrase) - A library for generating secure random passphrases.

## Code Analysis
*Libraries and tools for analysing, parsing and manipulating codebases.*

* [PHP Parser](https://github.com/nikic/PHP-Parser) - A PHP parser written in PHP.
* [PHPPHP](https://github.com/ircmaxell/PHPPHP) - A PHP VM implementation in PHP.
* [PHPSandbox](https://github.com/fieryprophet/php-sandbox) - A PHP sandbox environment.
* [Dissect](https://github.com/jakubledl/dissect) - A set of tools for lexical and syntactical analysis.
* [PHP Mess Detector](http://phpmd.org/) - A library that scans code for bugs, sub-optimal code, unused parameters and more.
* [PHP Code Sniffer](https://github.com/squizlabs/PHP_CodeSniffer) - A library that detects PHP, CSS and JS coding standard violations.
* [PHPCPD](https://github.com/sebastianbergmann/phpcpd) - A library that detects copied and pasted code.
* [PHP Analyser](https://github.com/scrutinizer-ci/php-analyzer) - A library for analysing PHP code to find bugs and errors.
* [PHP CS Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer) - A coding standards fixer library.
* [PHP Manipulator](https://github.com/schmittjoh/php-manipulator) - A library for analysing and modifying PHP Source Code.
* [PHP Metrics](https://github.com/Halleck45/PhpMetrics) - A static metric library.
* [PHP Refactoring Browser](https://github.com/QafooLabs/php-refactoring-browser) - A command line utility for refactoring PHP code.
* [UBench](https://github.com/devster/ubench) - A simple micro benchmark library.
* [Athletic](https://github.com/polyfractal/athletic) - An annotation based benchmark framework.
* [Mondrian](https://github.com/Trismegiste/Mondrian) - A code analysis tool using Graph Theory.
* [Scrutinizer](https://scrutinizer-ci.com/) - A web tool to scrutinise PHP code.
* [PHPLOC](https://github.com/sebastianbergmann/phploc) - A tool for quickly measuring the size of a PHP project.
* [PHPCheckstyle](https://github.com/jbrooksuk/phpcheckstyle) - A tool to help adhere to certain coding conventions.
* [PhpDependencyAnalysis](https://github.com/mamuz/PhpDependencyAnalysis) - A tool to create customisable dependency graphs.

## Architectural
*Libraries related to design patterns, programming approaches and ways to organize code.*

* [PHP Option](https://github.com/schmittjoh/php-option) An option type library.
* [Ruler](https://github.com/bobthecow/Ruler) - A simple stateless production rules engine.
* [Finite](http://yohan.giarel.li/Finite) - A simple PHP finite state machine.
* [Compose](https://github.com/igorw/compose) - A function composition library.
* [Monad PHP](https://github.com/ircmaxell/monad-php) - A simple Monad library.
* [Patchwork](http://antecedent.github.io/patchwork/) - A library for redefining userland functions.
* [Galapagos](https://github.com/endel/galapagos) - Evolutionary language transformation.
* [Design Patterns PHP](https://github.com/domnikl/DesignPatternsPHP) - A repository of software patterns implemented in PHP.
* [Functional PHP](https://github.com/lstrojny/functional-php) - A functional programming library.
* [Lib Accessor](https://github.com/phine/lib-accessor) - A library for simplifying accessors.
* [Iter](https://github.com/nikic/iter) - A library that provides iteration primitives using generators.

## 调试和分析
*Libraries and tools for debugging and profiling code.*

* [xDebug](https://github.com/xdebug/xdebug) - A debug and profile tool for PHP.
* [PHP Debug Bar](http://phpdebugbar.com/) - A debugging toolbar.
* [PHP Console](https://github.com/Seldaek/php-console) - A web debugging console.
* [Barbushin PHP Console](https://github.com/barbushin/php-console) - Another web debugging console using Google Chrome.
* [PHPDBG](http://phpdbg.com/) - An interactive PHP debugger.
* [Tracy](https://github.com/nette/tracy) - A simple error detection, logging and time measuring library.
* [Z-Ray](http://www.zend.com/en/products/server/z-ray) - A debug and profile tool for Zend Server.
* [XHProf](https://github.com/phacility/xhprof) - A profiling tool originally developed by Facebook.
* [Blackfire.io](http://blackfire.io) - A low-overhead code profiler.

## Build Tools
*Project build and automation tools.*

* [Go](https://github.com/herrera-io/php-go) - A simple PHP build tool.
* [Bob](https://github.com/CHH/bob) - A simple project automation tool.
* [Phake](https://github.com/jaz303/phake) - A rake PHP clone library.
* [Box](https://github.com/kherge/Box) - A utility to build PHAR files.
* [Phing](http://www.phing.info/) - A PHP project build system inspired by Apache Ant.

## Task Runners
*Libraries for automating and running tasks.*
* [Task](http://taskphp.github.io/) - A pure PHP task runner inspired by Grunt and Gulp.
* [Robo](https://github.com/Codegyre/Robo) - A PHP Task runner with object-orientated configurations.
* [Bldr](http://bldr.io/) - A PHP Task runner built on Symfony components.

## Navigation
*Tools for building navigation structures.*

* [KnpMenu](https://github.com/KnpLabs/KnpMenu) - A menu library.
* [Cartographer](https://github.com/tackk/cartographer) - A sitemap generation library.

## Asset Management
*Tools for managing, compressing and minifying website assets.*

* [Assetic](https://github.com/kriswallsmith/assetic) - An asset manager pipeline library.
* [Pipe](https://github.com/CHH/pipe) - Another asset manager pipeline library.
* [Munee](https://github.com/meenie/munee) - An asset optimiser library.
* [JShrink](https://github.com/tedivm/JShrink) - A JavaScript minifier library.
* [Puli](https://github.com/webmozart/puli) - A library for determining assets absolute paths.

## Geolocation
*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [GeoCoder](http://geocoder-php.org/) - A geocoding library.
* [GeoTools](https://github.com/php-loep/Geotools) - A library of geo-related tools.
* [PHPGeo](https://github.com/mjaschen/phpgeo) - A simple geo library.
* [GeoJSON](https://github.com/jmikola/geojson) - A GeoJSON implementation.

## Date and Time
*Libraries for working with dates and times.*

* [Carbon](https://github.com/briannesbitt/Carbon) - A simple DateTime API extension.
* [ExpressiveDate](https://github.com/jasonlewis/expressive-date) - Another DateTime API extension.
* [CalendR](http://yohan.giarel.li/CalendR) - A calendar management library.

## Event
*Libraries that are event-driven or implement non-blocking event loops.*

* [React](https://github.com/reactphp/react) - An event driven non-blocking I/O library.
* [Rx.PHP](https://github.com/asm89/Rx.PHP) - A reactive extension library.
* [Ratchet](https://github.com/cboden/Ratchet) - A web socket library.
* [Hoa WebSocket](https://github.com/hoaproject/Websocket) - Another web socket library.
* [Elephant.io](https://github.com/Wisembly/Elephant.io) - Yet another web socket library.
* [Hoa EventSource](https://github.com/hoaproject/Eventsource) - An event source library.
* [Evenement](https://github.com/igorw/evenement) - An event dispatcher library.
* [Event](https://github.com/thephpleague/event) - An event library with a focus on domain events.
* [Broadway](https://github.com/qandidate-labs/broadway) - An event source and CQRS library.

## Logging
*Libraries for generating and working with log files.*

* [Monolog](https://github.com/Seldaek/monolog) - A comprehensive logger.
* [KLogger](https://github.com/katzgrau/KLogger) - An easy-to-use PSR-3 compliant logging class.
* [Analog](https://github.com/jbroadway/analog) - A closure-based micro logging package.

## E-commerce
*Libraries and applications for taking payments and building online e-commerce stores.*

* [OmniPay](https://github.com/thephpleague/omnipay) - A framework agnostic multi-gateway payment processing library.
* [Payum](https://github.com/payum/payum) - A payment abstraction library.
* [Sylius](http://www.sylius.org/) - An open source e-commerce solution.
* [Thelia](http://thelia.net/v2/) - Another open source e-commerce solution.
* [Money](https://github.com/mathiasverraes/money) - A PHP implementation of Fowler's money pattern.
* [Sebastian Money](https://github.com/sebastianbergmann/money) - Another library for working with monetary values.
* [Swap](https://github.com/florianv/swap) - An exchange rates library.

## PDF
*Libraries and software for working with PDF files.*

* [Snappy](https://github.com/KnpLabs/snappy) - A PDF and image generation library.
* [WKHTMLToPDF](https://github.com/antialize/wkhtmltopdf) - A tool to convert HTML to PDF.
* [PHPPdf](https://github.com/psliwa/PHPPdf) - A library for generating PDFs and images from XML.

## Office
*Libraries for working with office suite documents.*

* [PHPWord](https://github.com/PHPOffice/PHPWord) - A library for working with Microsoft Word documents.
* [PHPExcel](https://github.com/PHPOffice/PHPExcel) - A library for working with Microsoft Excel documents.
* [PHPPowerPoint](https://github.com/PHPOffice/PHPPowerPoint) - A library for working with Microsoft Word documents.
* [ExcelAnt](https://github.com/Wisembly/ExcelAnt) - A library for manipulating Microsoft Excel documents.

## Database
*Libraries for interacting with databases using object-relational mapping (ORM) or datamapping techniques.*

* [Doctrine](http://www.doctrine-project.org/) - A comprehensive DBAL and ORM.
* [Doctrine Extensions](https://github.com/l3pp4rd/DoctrineExtensions) - A collection of Doctrine behavioural extensions.
* [Propel](http://www.propelorm.org/) - A fast ORM, migration library and query builder.
* [Eloquent](https://github.com/illuminate/database) - The Laravel 4 ORM.
* [Baum](https://github.com/etrepat/baum) - A nested set implementation for Eloquent.
* [Spot2](https://github.com/vlucas/spot2) - A MySQL datamapper ORM.
* [RedBean](http://redbeanphp.com/) - A lightweight, configuration-less ORM.
* [Pomm](https://github.com/chanmix51/Pomm) - An Object Model Manager for PostgreSQL.
* [ProxyManager](https://github.com/Ocramius/ProxyManager) - A set of utilities to generate proxy objects for data mappers.

## Migrations
Libraries to help manage database schemas and migrations.

* [PHPMig](https://github.com/davedevelopment/phpmig) - Another migration management library.
* [Phinx](https://github.com/robmorgan/phinx) - Another database migration library.
* [Migrations](https://github.com/icomefromthenet/Migrations) - A migration management library.
* [Doctrine Migrations](http://docs.doctrine-project.org/projects/doctrine-migrations/en/latest/toc.html) - A migration library for Doctrine.

## NoSQL
*Libraries for working with "NoSQL" backends.*

* [MongoQB](https://github.com/alexbilbie/MongoQB) - A MongoDB query builder library.
* [Monga](https://github.com/thephpleague/monga) - A MongoDB abstraction library.
* [Predis](https://github.com/nrk/predis) - A feature complete Redis library.

## Queue
*Libraries for working with event and task queues.*

* [Pheanstalk](https://github.com/pda/pheanstalk) - A Beanstalkd client library.
* [PHP AMQP](https://github.com/videlalvaro/php-amqplib) - A pure PHP AMQP library.
* [Thumper](https://github.com/videlalvaro/Thumper) - A RabbitMQ pattern library.
* [Bernard](https://github.com/bernardphp/bernard) - A multibackend abstraction library.

## Search
*Libraries and software for indexing and performing search queries on data.*

* [ElasticSearch PHP](https://github.com/elasticsearch/elasticsearch-php) - The official client library for [ElasticSearch](http://www.elasticsearch.org/).
* [Elastica](https://github.com/ruflin/Elastica) - A client library for ElasticSearch.
* [Solarium](http://www.solarium-project.org/) - A client library for [Solr](http://lucene.apache.org/solr/).
* [SphinxQL query builder](http://foolcode.github.io/SphinxQL-Query-Builder/) - A query library for the [Sphinx](http://sphinxsearch.com/) search engine.

## Command Line
*Libraries related to the command line.*

* [Boris](https://github.com/d11wtq/boris) - A tiny PHP REPL.
* [PsySH](https://github.com/bobthecow/psysh) - Another PHP REPL.
* [Pecan](https://github.com/mcrumm/pecan) - An event-driven, non-blocking shell.
* [GetOpt](https://github.com/ulrichsg/getopt-php) - A command line opt parser.
* [OptParse](https://github.com/CHH/optparse) - Another command line opt parser.
* [Commando](https://github.com/nategood/commando) - Another simple command line opt parser.
* [GetOptionKit](https://github.com/c9s/php-GetOptionKit) - Another command line opt parser.
* [Cron Expression](https://github.com/mtdowling/cron-expression) - A library to calculate cron run dates.
* [ShellWrap](https://github.com/MrRio/shellwrap) - A simple command line wrapper library.
* [Hoa Console](https://github.com/hoaproject/Console) - Another command line library.
* [Shunt](https://github.com/php-loep/shunt) - A library for running commands in parallel on multiple remote machines.
* [Cilex](https://github.com/Cilex/Cilex) - A micro framework for building command line tools.
* [CLImate](https://github.com/thephpleague/climate) - A library for outputting colours and special formatting.

## Authentication and Authorization
*Libraries for implementing user authentication and authorization.*

* [Sentry](https://github.com/cartalyst/sentry) - A framework agnostic authentication & authorisation library.
* [Sentry Social](http://docs.cartalyst.com/sentry-social-2/introduction) - A library for social network authentication.
* [Opauth](https://github.com/opauth/opauth) - A multi-provider authentication framework.
* [OAuth2 Server](http://oauth2.thephpleague.com/) - An OAuth2 authentication server, resource server and client library.
* [OAuth2 Server](http://bshaffer.github.io/oauth2-server-php-docs/) - Another OAuth2 server implementation.
* [PHP oAuthLib](https://github.com/Lusitanian/PHPoAuthLib) - Another OAuth library.
* [TwitterOAuth](https://github.com/ruudk/twitteroauth) - A Twitter OAuth library.
* [TwitterSDK](https://github.com/lyrixx/twitter-sdk) - A fully tested Twitter SDK.
* [Hawk](https://github.com/dflydev/dflydev-hawk) - A Hawk HTTP authentication library.
* [HybridAuth](https://github.com/hybridauth/hybridauth) - An open source social sign on library.
* [Lock](https://github.com/BeatSwitch/lock) - A library for implementing Access Control Lists (ACL) systems.
* [OAuth 1.0 Client](https://github.com/thephpleague/oauth1-client) - An OAuth 1.0 client library.
* [OAuth 2.0 Client](https://github.com/thephpleague/oauth2-client) - An OAuth 2.0 client library.

## Markup
*Libraries for working with markup.*

* [Decoda](http://milesj.me/code/php/decoda) - A lightweight markup parser library.
* [PHP Markdown](https://github.com/michelf/php-markdown) - A Markdown parser.
* [CommonMark PHP](https://github.com/thephpleague/commonmark) - A Markdown parser which supports the full [CommonMark spec](https://jgm.github.io/stmd/spec.html).
* [Dflydev Markdown](https://github.com/dflydev/dflydev-markdown) - Another Markdown parser.
* [Parsedown](https://github.com/erusev/parsedown) - Another Markdown parser.
* [Ciconia](https://github.com/kzykhys/Ciconia) - Another Markdown parser that supports Github flavoured Markdown.
* [Cebe Markdown](https://github.com/cebe/markdown) - An fast and extensible Markdown parser.
* [HTML5 PHP](https://github.com/Masterminds/html5-php) - An HTML5 parser and serializer library.

## Strings
*Libraries for parsing and manipulating strings.*

* [ANSI to HTML5](https://github.com/sensiolabs/ansi-to-html) - An ANSI to HTML5 converter library.
* [Patchwork UTF-8](https://github.com/nicolas-grekas/Patchwork-UTF8) - A portable library for working with UTF-8 strings.
* [Hoa String](https://github.com/hoaproject/String) - Another UTF-8 string library.
* [Stringy](https://github.com/danielstjules/Stringy) - A string manipulation library with multibyte support.
* [Color Jizz](https://github.com/mikeemoo/ColorJizz-PHP) - A library for manipulating and converting colours.
* [UUID](https://github.com/ramsey/uuid) - A library for generating UUIDs.
* [Slugify](https://github.com/cocur/slugify) - A library to convert strings to slugs.
* [Urlify](https://github.com/jbroadway/urlify) - A PHP port of Django's URLify.js.
* [Text](https://github.com/kzykhys/Text) - A text manipulation library.
* [SQL Formatter](https://github.com/jdorn/sql-formatter/) - A library for formatting SQL statements.
* [UA Parser](https://github.com/tobie/ua-parser/tree/master/php) - A library for parsing user agent strings.
* [Device Detector](https://github.com/piwik/device-detector) - Another library for parsing user agent strings.
* [Mobile-Detect](https://github.com/serbanghita/Mobile-Detect) - A lightweight PHP class for detecting mobile devices (including tablets).

## Numbers
*Libraries for working with numbers.*

* [Numbers PHP](https://github.com/powder96/numbers.php) - A library for working with numbers.
* [Math](https://github.com/moontoast/math) - A library for working with large numbers.
* [ByteUnits](https://github.com/gabrielelana/byte-units) - A library to parse, format and convert byte units in binary and metric systems.
* [PHP Units of Measure](https://github.com/triplepoint/php-units-of-measure) - A library for converting between units of measure.
* [PHP Conversion](https://github.com/Crisu83/php-conversion) - Another library for converting between units of measure.
* [LibPhoneNumber for PHP](https://github.com/giggsey/libphonenumber-for-php) - A PHP implementation of Google's phone number handling library.

## Filtering and Validation
*Libraries for filtering and validating data.*

* [Filterus](https://github.com/ircmaxell/filterus) - A simple PHP filtering library.
* [Respect Validate](https://github.com/Respect/Validation) - A simple validation library.
* [Valitron](https://github.com/vlucas/valitron) - Another validation library.
* [Upload](https://github.com/codeguy/Upload) - A library for handling file uploads and validation.
* [DMS Filter](https://github.com/rdohms/DMS-Filter) - An annotation filtering library.
* [MetaYaml](https://github.com/romaricdrigon/MetaYaml) - A schema validation library that supports YAML, JSON and XML.
* [ISO-codes](https://github.com/ronanguilloux/IsoCodes) - A library for validating various ISO and ZIP codes (IBAN, SWIFT/BIC, BBAN, VAT, SSN, UKNIN).

## API
*Libraries and web tools for developing APIs.*

* [Apigility](https://github.com/zfcampus/zf-apigility-skeleton) - An API builder built with Zend Framework 2.
* [Hateoas](https://github.com/willdurand/Hateoas) - A HATEOAS REST web service library.
* [HAL](https://github.com/blongden/hal) - A Hypertext Application Language (HAL) builder library.
* [Negotiation](https://github.com/willdurand/Negotiation) - A content negotiation library.
* [Drest](https://github.com/leedavis81/drest) - A library for exposing Doctrine entities as REST resource endpoints.
* [Restler](https://github.com/Luracast/Restler) - A lightweight framework to expose PHP methods as RESTful web API.
* [wsdl2phpgenerator](https://github.com/wsdl2phpgenerator/wsdl2phpgenerator) - A tool to generate PHP classes from SOAP WSDL files.

## Caching
*Libraries for caching data.*

* [Alternative PHP Cache (APC)](http://www.php.net/manual/en/book.apc.php) - Open opcode cache for PHP.
* [Cache](https://github.com/doctrine/cache) - A caching library (part of Doctrine).
* [Stash](https://github.com/tedivm/Stash) - Another library for caching.

## Data Structure and Storage
*Libraries that implement data structure or storage techniques.*

* [Ardent](https://github.com/morrisonlevi/Ardent) - A library of data structures.
* [PHP Collections](https://github.com/schmittjoh/php-collection) - A simple collections library.
* [Serializer](https://github.com/schmittjoh/serializer) - A library for serialising and de-serialising data.
* [PHP Object Storage](https://github.com/herrera-io/php-object-storage) - A library for object storage.
* [Fractal](https://github.com/php-loep/fractal) - A library for converting complex data structures to JSON output.
* [Totem](http://github.com/Wisembly/Totem) - A library to manage and create data changesets.
* [PINQ](https://github.com/TimeToogo/Pinq) - A real Linq library for PHP.
* [JsonMapper](https://github.com/netresearch/jsonmapper) - A library that maps nested JSON structures onto PHP classes.

## Notifications
*Libraries for working with notification software.*

* [Nod](https://github.com/filp/nod) - A notification library (e.g., Growl).
* [Notificato](https://github.com/wrep/notificato) - A library for handling push notifications.
* [Notification Pusher](https://github.com/Ph3nol/NotificationPusher) - A standalone library for device push notifications.
* [Notificator](https://github.com/namshi/notificator) - A lightweight notification library.

## Deployment
*Libraries for project deployment.*

* [Pomander](https://github.com/tamagokun/pomander) - A deployment tool for PHP applications.
* [Rocketeer](https://github.com/Anahkiasen/rocketeer) - A fast and easy deployer for the PHP world.
* [Envoy](https://github.com/laravel/envoy) - A tool to run SSH tasks with PHP.
* [Plum](https://github.com/aerialls/Plum) - A deployer library.
* [Deployer](https://github.com/deployphp/deployer) - A deployment tool.

## Internationalisation and Localisation
*Libraries for Internationalization (I18n) and Localization (L10n).*

* [Aura Intl](https://github.com/auraphp/Aura.Intl)

## Third Party APIs
*Libraries for accessing third party APIs.*

* [Amazon Web Service SDK](https://github.com/aws/aws-sdk-php) - The official PHP AWS SDK library.
* [S3 Stream Wrapper](https://github.com/gwkunze/S3StreamWrapper) - A stream wrapper library for Amazon S3.
* [Stripe](https://github.com/stripe/stripe-php) - The official Stripe PHP library.
* [Campaign Monitor](http://campaignmonitor.github.com/createsend-php/) - The official Campaign Monitor PHP library.
* [Digital Ocean](https://github.com/toin0u/DigitalOcean) - A library to interface with the Digital Ocean API.
* [Github](https://github.com/dsyph3r/github-api3-php) - A library to interface with the Github API.
* [PHP Github API](https://github.com/KnpLabs/php-github-api) - Another library to interface with the Github API.
* [Twitter OAuth](https://github.com/widop/twitter-oauth) - A library to interface with Twitter's OAuth workflow.
* [Twitter REST](https://github.com/widop/twitter-rest) - A library to interact with Twitter's REST API.
* [Dropbox SDK](https://github.com/dropbox/dropbox-sdk-php) - The official PHP Dropbox SDK library.
* [Twilio](https://github.com/twilio/twilio-php) - The official Twilio PHP REST API.
* [Mailgun](https://github.com/mailgun/mailgun-php) The official Mailgun PHP API.

## Extensions
*Libraries to help build PHP extensions.*

* [Zephir](https://github.com/phalcon/zephir) - A compiled language between PHP and C++ for developing PHP extensions.
* [PHP CPP](http://www.php-cpp.com/) - A C++ library for developing PHP extensions.

## Miscellaneous
*Useful libraries or tools that don't fit in the categories above.*

* [Spork](https://github.com/kriswallsmith/spork) - A process forking library.
* [JSON Lint](https://github.com/Seldaek/jsonlint) - A JSON lint utility.
* [JSONPCallbackValidator](https://github.com/willdurand/JsonpCallbackValidator) - A library for validating JSONP callbacks.
* [Pagerfanta](https://github.com/whiteoctober/Pagerfanta) - A pagination library.
* [LiteCQRS](https://github.com/beberlei/litecqrs-php) - A CQRS (Command Query Responsibility Separation) library.
* [Sslurp](https://github.com/EvanDotPro/Sslurp) - A library that makes dealing with SSL suck less.
* [Metrics](https://github.com/beberlei/metrics) - A simple metrics API library.
* [Sabre VObject](https://github.com/evert/sabre-vobject) - A library for parsing VCard and iCalendar objects.
* [Annotations](https://github.com/doctrine/annotations) - An annotations library (part of Doctrine).
* [Whoops](https://github.com/filp/whoops) - A pretty error handling library.
* [LadyBug](https://github.com/raulfraile/Ladybug) - A dumper library.
* [Procrastinator](https://github.com/lstrojny/Procrastinator) - A library for running time consuming tasks.
* [SuperClosure](https://github.com/jeremeamia/super_closure) - A library that allows Closures to be serialized.
* [Jumper](https://github.com/kakawait/Jumper) - A remote service executor library.
* [Underscore](http://anahkiasen.github.io/underscore-php/) - A PHP port of the Underscore JS library.
* [PHP PassBook](https://github.com/eymengunay/php-passbook) - A PHP library for iOS PassBook.
* [PHP Expression](https://github.com/Kitano/php-expression) - A PHP expression language.
* [RMT](https://github.com/liip/RMT) - A library for versioning and releasing software.
* [Wise](https://github.com/herrera-io/php-wise) - A configuration manager.
* [Opengraph](https://github.com/euskadi31/Opengraph) - An opengraph library.
* [Essence](https://github.com/felixgirault/essence) - A library for extracting web media.
* [Embera](https://github.com/mpratt/Embera) - An Oembed consumer library.
* [Graphviz](https://github.com/alexandresalome/graphviz) - A Graphviz library.
* [Flux](https://github.com/selvinortiz/flux) - A regular expression building library.
* [PHPCR](https://github.com/phpcr/phpcr) - A PHP port of the Java Content Repository (JCR).
* [ClassPreloader](https://github.com/mtdowling/ClassPreloader) - A library for optimising autoloading.
* [Lib Country](https://github.com/phine/lib-country) - A library for country and subdivision data.
* [PHPStack](http://dunkels.com/adam/phpstack/) - A TCP/IP stack proof of concept written in PHP.
* [Nmap](https://github.com/willdurand/nmap) - A PHP wrapper around [Nmap](http://nmap.org/).
* [Code Mover](https://github.com/dantleech/code-mover) - A library for moving code.
* [Lambda PHP](https://github.com/igorw/lambda-php) - A Lambda calculus interpreter in PHP.
* [Country List](https://github.com/umpirsky/country-list) - A list of all countries with names and ISO 3166-1 codes.
* [PHP-GPIO](https://github.com/ronanguilloux/php-gpio) - A library for playing with the Raspberry PI's GPIO pins.
* [print_o](https://github.com/koriym/print_o) - An object graph visualizer.
* [Alias](https://github.com/fuelphp/alias) - A class aliasing library.

# Software
*Software for creating a development environment.*

## PHP Installation
*Tools to help install and manage PHP on your computer.*

* [HomeBrew](http://mxcl.github.com/homebrew/) - A package manager for OSX.
* [HomeBrew PHP](https://github.com/josegonzalez/homebrew-php) - A PHP tap for HomeBrew.
* [PHP OSX](http://php-osx.liip.ch/) - A PHP installer for OSX.
* [PHP Brew](https://github.com/c9s/phpbrew) - A PHP version manager and installer.
* [PHP Env](https://github.com/CHH/phpenv) - Another PHP version manager.
* [PHP Switch](https://github.com/jubianchi/phpswitch) - Another version manager.
* [PHP Build](https://github.com/CHH/php-build) - Another PHP version installer.
* [VirtPHP](http://virtphp.org/) - A tool for creating and managing isolated PHP environments.

## Development Environment
*Software and tools for creating a sandboxed development environment.*

* [Vagrant](http://www.vagrantup.com/) - A portable development environment utility.
* [Ansible](http://www.ansibleworks.com/) - A radically simple orchestration framework.
* [Puppet](http://puppetlabs.com/) - A server automation framework and application.
* [PuPHPet](https://puphpet.com/) - A web tool for building PHP development virtual machines.
* [Protobox](http://getprotobox.com/) - Another web tool for building PHP development virtual machines.
* [Phansible](http://phansible.com/) - A web tool for building PHP development virtual machines with Ansible.

## Virtual Machines
*Alternative PHP virtual machines.*

* [HipHop PHP](https://github.com/facebook/hiphop-php) - A Virtual Machine, Runtime and JIT for PHP by Facebook.
* [HippyVM](http://hippyvm.com/) - Another PHP virtual machine.
* [Hack](http://hacklang.org/) - A programming language for [HHVM](https://github.com/facebook/hiphop-php) that interoperates seamlessly with PHP.

## Integrated Development Environment
*Integrated Development Environments with support for PHP.*

* [Netbeans](https://netbeans.org) - An IDE with support for PHP and HTML5.
* [Eclipse for PHP Developers](https://www.eclipse.org/downloads/) - A PHP IDE based on the Eclipse platform.
* [PhpStorm](http://www.jetbrains.com/phpstorm/) - A commercial PHP IDE.

## Web Applications
*Web-based applications and tools.*

* [3V4L](http://3v4l.org/) - An online PHP shell.
* [DBV](http://dbv.vizuina.com/) - A database version control application.
* [PHP Queue](https://github.com/CoderKungfu/php-queue) - An application for managing queueing backends.
* [Composer as a Service](http://composer.borreli.com/) - A tool for downloading Composer packages as a zip file.
* [MailCatcher](https://github.com/sj26/mailcatcher) - A web tool for capturing and viewing emails.
* [Cachet](https://github.com/cachethq/cachet) - The open source status page system.

# Resources
Various resources, such as books, websites and articles, for improving your PHP development skills and knowledge.

## PHP Websites
*Useful PHP-related websites.*

* [PHP The Right Way](http://www.phptherightway.com/) - A PHP best practice quick reference guide.
* [PHP Best Practices](http://phpbestpractices.org/) - A PHP best practice guide.
* [PHP Weekly](http://www.phpweekly.com/archive.html) - A weekly PHP newsletter.
* [Securing PHP](http://securingphp.com/) - A newsletter about PHP security and library recommendations.
* [PHP Security](http://phpsecurity.readthedocs.org/en/latest/index.html) - A guide to PHP security.
* [PHP FIG](http://www.php-fig.org/) - The PHP Framework Interoperability Group.
* [PHP UG](http://php.ug) - A website to help people locate their nearest PHP user group (UG).
* [Seven PHP](http://7php.com/) - A website that interviews members of the PHP community.
* [Nomad PHP](http://nomadphp.com/) - A online PHP learning resource.
* [PHP Mentoring](http://phpmentoring.org/) - Peer to peer PHP mentorship organization.

## Other Websites
*Useful websites related to web development.*

* [The Open Web Application Security Project (OWASP)](https://www.owasp.org/index.php/Main_Page) - An open software security community.
* [WebSec IO](http://websec.io/) - A web security community resource.
* [Web Advent](http://webadvent.org) - An advent calendar for web developers.
* [Semantic Versioning](http://semver.org/) - A website explaining semantic versioning.
* [Atlassian Git Tutorials](https://www.atlassian.com/git) - A series of Git tutorials.
* [Hg Init](http://hginit.com/) - A series of Mercurial tutorials.
* [Servers for Hackers](http://serversforhackers.com/) - A newsletter about server management.

## PHP Books
*Fantastic PHP-related books.*

* [Scaling PHP Applications](http://www.scalingphpbook.com) - An ebook about scaling PHP applications by Steve Corona.
* [The Grumpy Programmer's Guide to Building Testable PHP Applications](https://leanpub.com/grumpy-testing) - A book about building testing PHP applications by Chris Hartjes.
* [Grumpy PHPUnit](https://leanpub.com/grumpy-phpunit) - A book about unit testing with PHPUnit by Chris Hartjes.
* [Mastering Object-Orientated PHP](http://www.brandonsavage.net) - A book about object-orientated PHP by Brandon Savage.
* [Signaling PHP](https://leanpub.com/signalingphp) - A book about catching PCNTL signals in CLI scripts by Cal Evans.
* [Securing PHP: Core Concepts](https://leanpub.com/securingphp-coreconcepts) - A book about common security terms and practices for PHP by Chris Cornutt.
* [Modernising Legacy Applications in PHP](https://leanpub.com/mlaphp) - A book about modernising legacy PHP applications by Paul M. Jones.
* [Modern PHP New Features and Good Practices](http://shop.oreilly.com/product/0636920033868.do) - A book about new PHP features and best practices by Josh Lockhart.

## Other Books
*Books related to general computing and web development.*

* [The Linux Command Line](http://linuxcommand.org/tlcl.php) - A book about the Linux command line by William Shotts.
* [Understanding Computation](http://computationbook.com) - A book about computation theory by Tom Stuart.
* [The Tangled Web — Securing Web Applications](http://www.amazon.ca/The-Tangled-Web-Securing-Applications/dp/1593273886) - A book about securing web applications by Michal Zalewski.
* [Elasticsearch: The Definitive Guide](http://www.elasticsearch.org/guide/) - A guide to working with Elasticsearch by Clinton Gormley and Zachary Tong.
* [Eloquent JavaScript](http://eloquentjavascript.net/) - A book about JavaScript programming by Marijn Haverbeke.
* [Vagrant Cookbook](https://leanpub.com/vagrantcookbook) A book about creating Vagrant environments by Erika Heidi.
* [Pro Git](http://git-scm.com/book/en/v2) - A book about Git by Scott Chacon and Ben Straub.

## PHP Videos
*Fantastic PHP-related videos.*

* [Taking PHP Seriously](http://www.infoq.com/presentations/php-history) - A talk outlining PHP's strengths by Keith Adams of Facebook.
* [PHP Town Hall](http://phptownhall.com/) - A casual PHP podcast by Ben Edmunds and Phil Sturgeon.
* [Programming with Anthony](http://www.youtube.com/playlist?list=PLM-218uGSX3DQ3KsB5NJnuOqPqc5CW2kW) - A video series by Anthony Ferrara.

## PHP Reading
*PHP-releated reading materials.*

* [Create Your Own PHP Framework](http://fabien.potencier.org/article/50/create-your-own-framework-on-top-of-the-symfony2-components-part-1) - A series of articles on how to make your own PHP framework by Fabien Potencier.
* [Seven Ways to Screw Up BCrypt](http://blog.ircmaxell.com/2012/12/seven-ways-to-screw-up-bcrypt.html) - An article about correct BCrypt implementation.
* [Preventing CSRF Attacks](http://blog.ircmaxell.com/2013/02/preventing-csrf-attacks.html) - An article on preventing CSRF attacks.
* [Don't Worry About BREACH](http://blog.ircmaxell.com/2013/08/dont-worry-about-breach.html) - An article about the BREACH hack and CSRF tokens.
* [On PHP 5.3, Lamda Functions and Closures](http://fabien.potencier.org/article/17/on-php-5-3-lambda-functions-and-closures) - An article about lambda functions and closures.
* [Use Env](http://seancoates.com/blogs/use-env) - An article about using the unix environment helper.
* [Composer Primer](http://daylerees.com/composer-primer) - A Composer primer.
* [Composer Versioning](https://igor.io/2013/01/07/composer-versioning.html) - An article about Composer versioning.
* [Composer Stability Flags](https://igor.io/2013/02/07/composer-stability-flags.html) - An article about Composer stability flags.
* [Innocent Villagefolk or a Pillagin’ Pirate?](http://blog.astrumfutura.com/2012/04/php-innocent-villagefolk-or-a-pillagin-pirate/) - An article about PHP taking ideas from other language.
* [Predicting Random Numbers in PHP](http://blog.astrumfutura.com/2013/03/predicting-random-numbers-in-php-its-easier-than-you-think/) - An article about generating random numbers.
* [A 20 Point List for Preventing XSS in PHP](http://blog.astrumfutura.com/2013/04/20-point-list-for-preventing-cross-site-scripting-in-php/) - An article about preventing XSS.
* [PHP Sucks! But I Like It!](http://blog.ircmaxell.com/2012/04/php-sucks-but-i-like-it.html) - An article about the pros and cons of PHP.
* [PHP Is Much Better Than You Think](http://fabien.potencier.org/article/64/php-is-much-better-than-you-think) - An article about the PHP language and ecosystem.

## PHP Internals Reading
*Reading materials related to the PHP internals or performance.*

* [PHP RFCs](https://wiki.php.net/rfc) - The home of PHP RFCs (Request for Comments).
* [PHP Internals Book](http://www.phpinternalsbook.com) - An online book about PHP internals, written by three core developers.
* [Print vs Echo, Which One is Faster?](http://fabien.potencier.org/article/8/print-vs-echo-which-one-is-faster) - An article about print and echo performance.
* [The PHP Ternary Operator. Fast or Not?](http://fabien.potencier.org/article/48/the-php-ternary-operator-fast-or-not) - An article ternary performance.
* [Disproving the Single Quotes Myth](http://nikic.github.com/2012/01/09/Disproving-the-Single-Quotes-Performance-Myth.html) - An article about performance of single and double quoted strings.
* [You're Being Lied To](http://blog.golemon.com/2007/01/youre-being-lied-to.html) - An article about internal ZVALs.
* [How Long is a Piece of String](http://blog.golemon.com/2006/06/how-long-is-piece-of-string.html) - An article about string internals.
* [Understanding OpCodes](http://blog.golemon.com/2008/01/understanding-opcodes.html) - An article about opcodes.
* [How Foreach Works](http://stackoverflow.com/questions/10057671/how-foreach-actually-works/14854568#14854568) - A detailed StackOverflow answer about foreach.
* [When Does Foreach Copy?](http://nikic.github.com/2011/11/11/PHP-Internals-When-does-foreach-copy.html) - An article about the internals of foreach.
* [How Big Are PHP Arrays (And Values) Really?](http://nikic.github.com/2011/12/12/How-big-are-PHP-arrays-really-Hint-BIG.html) - An article about array internals.
* [Why Objects (Usually) Use Less Memory Than Arrays](https://gist.github.com/nikic/5015323) - An article about object and array internals.
* [PHP Evaluation Order](https://gist.github.com/nikic/6699370) - An article about evaluation order in PHP.
* PHP Source Code for Developers: [1](http://blog.ircmaxell.com/2012/03/phps-source-code-for-php-developers.html) [2](http://nikic.github.com/2012/03/16/Understanding-PHPs-internal-function-definitions.html) [3](http://blog.ircmaxell.com/2012/03/phps-source-code-for-php-developers_21.html) [4](http://nikic.github.com/2012/03/28/Understanding-PHPs-internal-array-implementation.html) - A series about the PHP source code.
* Collecting Garbage: [1](http://www.php.net/manual/en/features.gc.refcounting-basics.php) [2](http://www.php.net/manual/en/features.gc.collecting-cycles.php) [3](http://www.php.net/manual/en/features.gc.performance-considerations.php) - A series about the PHP garbage collection internals.
