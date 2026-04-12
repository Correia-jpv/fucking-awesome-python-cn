# Python 资源大全中文版 

<b><code>291835⭐</code></b> <b><code>&nbsp;27649🍴</code></b> [awesome-python](https://github.com/vinta/awesome-python)) 是 vinta 发起维护的 Python 资源列表，内容包括：Web 框架、网络爬虫、网络内容提取、模板引擎、数据库、数据可视化、图片处理、文本处理、自然语言处理、机器学习、日志、代码分析等。由「开源前哨」和「Python开发者」微信公号团队维护更新。


### 本项目的参与者

- 维护者 🌎 [「开源前哨」和「Python开发者」微信公号团队](github-1255921244.cos.ap-nanjing.myqcloud.com/awesome-python-cn.png)。「开源前哨」会定期在知乎专栏分享最新、有趣和热门的开源项目，每个项目都有详细的介绍和示例。传送门：<https://www.zhihu.com/column/c_1317124962785062912>

- 贡献者：<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [唐尤华](https://github.com/orgs/jobbole/people/tangyouhua))、[qtvspa](https://github.com/qtvspa)、[艾凌风](https://github.com/hanxiaomax)、Namco、[Daetalus](https://github.com/Daetalus)、黄利民、atupal、rainbow、[木头lbj](https://github.com/mutoulbj)、beyondwu、[cissoid](https://github.com/cissoid)、[李广胜](https://github.com/liguangsheng)、[polyval](https://github.com/polyval)、冰斌、赵叶宇、л stalgic、硕恩、[strongit](https://github.com/strongit)、yuukilp、[chenjiandongx](https://github.com/chenjiandongx)、[autopenguin](https://github.com/autopenguin)、[visonforcoding](https://github.com/visonforcoding)、[Super赛亚人](https://github.com/No-96)、[Since-future](https://github.com/Since-future)、[knktc](https://github.com/knktc)、[zhucebuliaopx](https://github.com/zhucebuliaopx)、[wardseptember](https://github.com/wardseptember)、[vmp65l3](https://github.com/vmp65l3)、[JiaxingZhao](https://github.com/JiaxingZhao)、[zhtyyx](https://github.com/zhtyyx)、[Lynn Cao](https://github.com/caolincn)、[River](https://github.com/lihuafengzi)、You

注：名单不分排名，不定期补充更新

## 资源列表

### 环境管理

管理 Python 版本和环境的工具

*   <b><code>&nbsp;&nbsp;&nbsp;779⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [p](https://github.com/qw3rtman/p))：非常简单的交互式 Python 版本管理工具。
*   <b><code>&nbsp;44594⭐</code></b> <b><code>&nbsp;&nbsp;3239🍴</code></b> [pyenv](https://github.com/yyuu/pyenv))：简单的 Python 版本管理工具。
*   <b><code>&nbsp;&nbsp;&nbsp;370⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Vex](https://github.com/sashahart/vex))：可以在虚拟环境中执行命令。
*   🌎 [virtualenv](pypi.python.org/pypi/virtualenv)：创建独立 Python 环境的工具。
*   🌎 [virtualenvwrapper](pypi.python.org/pypi/virtualenvwrapper)：virtualenv 的一组扩展。
*   [buildout](http://www.buildout.org/en/latest)：在隔离环境初始化后使用声明性配置管理。

### 包管理

管理包和依赖的工具。

*   🌎 [pip](pip.pypa.io/)：Python 包和依赖关系管理工具。
*   <b><code>&nbsp;&nbsp;8001⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;661🍴</code></b> [pip-tools](https://github.com/nvie/pip-tools))：保证 Python 包依赖关系更新的一组工具。
*   🌎 [PyPI](pypi.org/)：Python 正式的第三方包软件存储库。
*   <b><code>&nbsp;25090⭐</code></b> <b><code>&nbsp;&nbsp;1881🍴</code></b> [pipenv](https://github.com/pypa/pipenv))：Python 官方推荐的新一代包管理工具。
*   🌎 [poetry](poetry.eustace.io)：可完全取代 setup.py 的包管理工具。
*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [conda](https://github.com/conda/conda/))：跨平台的 Python 二进制包管理工具。
*   [Curdling](http://clarete.li/curdling/)：管理 Python 包的命令行工具。
*   [wheel](http://pythonwheels.com/)：Python 分发的新标准，意在取代 eggs。

### 包仓库

本地 PyPI 仓库服务和代理。

*   <b><code>&nbsp;&nbsp;4000⭐</code></b> <b><code>&nbsp;&nbsp;1149🍴</code></b> [warehouse](https://github.com/pypa/warehouse))：下一代 PyPI。
*   🌎 [bandersnatch](bitbucket.org/pypa/bandersnatch)：PyPA 提供的 PyPI 镜像工具。
*   [devpi](http://doc.devpi.net/)：PyPI 服务和打包/测试/分发工具。
*   <b><code>&nbsp;&nbsp;&nbsp;401⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;110🍴</code></b> [localshop](https://github.com/mvantellingen/localshop))：本地 PyPI 服务（自定义包并且自动对 PyPI 镜像）。

### 分发

打包为可执行文件以便分发。

*   <b><code>&nbsp;12948⭐</code></b> <b><code>&nbsp;&nbsp;2018🍴</code></b> [PyInstaller](https://github.com/pyinstaller/pyinstaller))：将 Python 程序转换成独立的执行文件（跨平台）。
*   🌎 [cx_Freeze](cx-freeze.readthedocs.io/en/latest/index.html)：将python程序转换为带有一个动态链接库的可执行文件。
*   [dh-virtualenv](http://dh-virtualenv.readthedocs.org/)：构建并将 virtualenv 虚拟环境作为一个 Debian 包来发布。
*   [Nuitka](http://nuitka.net/)：将脚本、模块、包编译成可执行文件或扩展模块。
*   [py2app](http://pythonhosted.org/py2app/)：将 Python 脚本变为独立软件包（Mac OS X）。
*   [py2exe](http://www.py2exe.org/)：将 Python 脚本变为独立软件包（Windows）。
*   [pynsist](http://pynsist.readthedocs.org/)：一个用来创建 Windows 安装程序的工具，可以在安装程序中打包 Python 本身。
*   <b><code>&nbsp;&nbsp;5025⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;354🍴</code></b> [pyarmor](https://github.com/dashingsoft/pyarmor))：一个用于加密 python 脚本的工具，也可以将加密后的脚本绑定到固件上，或设置已加密脚本的有效期。
*   <b><code>&nbsp;&nbsp;1927⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;109🍴</code></b> [shiv](https://github.com/linkedin/shiv))：一个命令行工具，可用于构建完全独立的 zip 应用（PEP 441 所描述的那种），同时包含了所有的依赖项。

### 构建工具

将源码编译成软件。

*   [buildout](http://www.buildout.org/)：一个构建系统，从多个组件来创建，组装和部署应用。
*   [BitBake](http://www.yoctoproject.org/docs/1.6/bitbake-user-manual/bitbake-user-manual.html)：针对嵌入式 Linux 的类似 make 的构建工具。
*   🌎 [fabricate](code.google.com/archive/p/fabricate)：对任何语言自动找到依赖关系的构建工具。
*   <b><code>&nbsp;&nbsp;9004⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;862🍴</code></b> [PlatformIO](https://github.com/platformio/platformio))：多平台命令行构建工具。
*   <b><code>&nbsp;&nbsp;1974⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;272🍴</code></b> [PyBuilder](https://github.com/pybuilder/pybuilder))：纯 Python 实现的持续化构建工具。
*   [SCons](http://www.scons.org/)：软件构建工具。

### 交互式解析器

交互式 Python 解析器。

*   <b><code>&nbsp;16690⭐</code></b> <b><code>&nbsp;&nbsp;4470🍴</code></b> [IPython](https://github.com/ipython/ipython))：功能丰富的工具，非常有效的使用交互式 Python。
*   <b><code>&nbsp;&nbsp;2771⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;252🍴</code></b> [bpython](https://github.com/bpython/bpython))：界面丰富的 Python 解析器。
*   <b><code>&nbsp;&nbsp;5422⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;290🍴</code></b> [ptpython](https://github.com/jonathanslenders/ptpython))：高级交互式 Python 解析器， 构建于 <b><code>&nbsp;10387⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;778🍴</code></b> [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit)) 之上。
*   🌎 [Jupyter Notebook (IPython)](jupyter.org)：一个能够让你最大限度地以交互式方式使用 Python 的丰富工具包。
    * <b><code>&nbsp;&nbsp;4578⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;452🍴</code></b> [awesome-jupyter](https://github.com/markusschanta/awesome-jupyter))

### 文件

文件管理和 MIME（多用途的网际邮件扩充协议）类型检测。

*   <b><code>&nbsp;&nbsp;3242⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;164🍴</code></b> [aiofiles](https://github.com/Tinche/aiofiles))：基于 asyncio，提供文件异步操作。
*   🌎 [imghdr](docs.python.org/2/library/imghdr.html)：（Python 标准库）检测图片类型。
*   🌎 [mimetypes](docs.python.org/2/library/mimetypes.html)：（Python 标准库）将文件名映射为 MIME 类型。
*   <b><code>&nbsp;&nbsp;1124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;151🍴</code></b> [path.py](https://github.com/jaraco/path.py))：对 os.path 进行封装的模块。
*   🌎 [pathlib](pathlib.readthedocs.org/en/pep428/)：（Python3.4+ 标准库）跨平台的、面向对象的路径操作库。
*   <b><code>&nbsp;&nbsp;2903⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;306🍴</code></b> [python-magic](https://github.com/ahupp/python-magic))：文件类型检测的第三方库 libmagic 的 Python 接口。
*   <b><code>&nbsp;&nbsp;&nbsp;510⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [Unipath](https://github.com/mikeorr/Unipath))：用面向对象的方式操作文件和目录。
*   <b><code>&nbsp;&nbsp;7306⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;746🍴</code></b> [watchdog](https://github.com/gorakhargosh/watchdog))：管理文件系统事件的 API 和 shell 工具。
*   <b><code>&nbsp;&nbsp;2097⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;187🍴</code></b> [PyFilesystem2](https://github.com/pyfilesystem/pyfilesystem2))：Python 的文件系统抽象层。

### 日期和时间

操作日期和时间的类库。

*   <b><code>&nbsp;&nbsp;9036⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;732🍴</code></b> [arrow](https://github.com/crsmithdev/arrow))：更好的 Python 日期时间操作类库。
*   <b><code>&nbsp;&nbsp;&nbsp;342⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [Chronyk](https://github.com/KoffeinFlummi/Chronyk))：Python 3 的类库，用于解析手写格式的时间和日期。
*   🌎 [dateutil](pypi.python.org/pypi/python-dateutil)：Python datetime 模块的扩展。
*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [delorean](https://github.com/myusuf3/delorean/))：解决 Python 中有关日期处理的棘手问题的库。
*   <b><code>&nbsp;&nbsp;3415⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;197🍴</code></b> [maya](https://github.com/kennethreitz/maya))：人性化的时间处理库。
*   <b><code>&nbsp;&nbsp;6652⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;426🍴</code></b> [pendulum](https://github.com/sdispater/pendulum))：一个比 arrow 更具有明确的，可预测的行为的时间操作库。
*   <b><code>&nbsp;&nbsp;&nbsp;158⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [PyTime](https://github.com/shinux/PyTime))：一个简单易用的 Python 模块，用于通过字符串来操作日期/时间。
*   🌎 [pytz](launchpad.net/pytz)：现代以及历史版本的世界时区定义。将时区数据库引入 Python。
*   <b><code>&nbsp;&nbsp;&nbsp;188⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [when.py](https://github.com/dirn/When.py))：提供用户友好的函数来帮助用户进行常用的日期和时间操作。
*   <b><code>&nbsp;&nbsp;2609⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;541🍴</code></b> [dateutil](https://github.com/dateutil/dateutil))：Python 标准包 🌎 [datetime](docs.python.org/3/library/datetime.html) 的扩展。
*   <b><code>&nbsp;&nbsp;&nbsp;741⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [moment](https://github.com/zachwill/moment))：一个处理日期/时间的库，灵感来自 [Moment.js](http://momentjs.com/)。
*   🌎 [pytz](launchpad.net/pytz)：支持跨平台时区计算，并将 🌎 [tz database](en.wikipedia.org/wiki/Tz_database) 引入 Python。

### 文本处理

用于解析和操作文本的库。

*   通用
    *   <b><code>&nbsp;&nbsp;2590⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;295🍴</code></b> [chardet](https://github.com/chardet/chardet))：字符编码检测器，兼容 Python 2 和 Python 3。
    *   🌎 [difflib](docs.python.org/2/library/difflib.html)：(Python 标准库)帮助我们进行差异化比较。
    *   <b><code>&nbsp;&nbsp;4024⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;124🍴</code></b> [ftfy](https://github.com/LuminosoInsight/python-ftfy))：让 Unicode 文本更完整更连贯。
    *   <b><code>&nbsp;&nbsp;3608⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;158🍴</code></b> [thefuzz](https://github.com/seatgeek/thefuzz))：模糊字符串匹配。
    *   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Levenshtein](https://github.com/ztane/python-Levenshtein/))：快速计算编辑距离以及字符串的相似度。
    *   <b><code>&nbsp;&nbsp;&nbsp;275⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [pangu.py](https://github.com/vinta/pangu.py))：在中日韩语字符和数字字母之间添加空格。
    *   <b><code>&nbsp;&nbsp;5285⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;630🍴</code></b> [pypinyin](https://github.com/mozillazg/python-pinyin))：汉字拼音转换工具 Python 版。
    *   <b><code>&nbsp;&nbsp;2182⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [shortuuid](https://github.com/stochastic-technologies/shortuuid))：一个生成器库，用以生成简洁的，明白的，URL 安全的 UUID。
    *   <b><code>&nbsp;&nbsp;1707⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;356🍴</code></b> [simplejson](https://github.com/simplejson/simplejson))：Python 的 JSON 编码、解码器。
    *   🌎 [unidecode](pypi.python.org/pypi/Unidecode)：Unicode 文本的 ASCII 转换形式 。
    *   <b><code>&nbsp;&nbsp;&nbsp;158⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [uniout](https://github.com/moskytw/uniout))：打印可读的字符，而不是转义的字符串。
    *   <b><code>&nbsp;&nbsp;&nbsp;831⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;174🍴</code></b> [xpinyin](https://github.com/lxneng/xpinyin))：一个用于把汉字转换为拼音的库。
    *   <b><code>&nbsp;&nbsp;1552⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;151🍴</code></b> [pyfiglet](https://github.com/pwaller/pyfiglet))：figlet 的 Python 实现。
    *   <b><code>&nbsp;&nbsp;5709⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;598🍴</code></b> [flashtext](https://github.com/vi3k6i5/flashtext))：一个高效的文本查找替换库。
    *   <b><code>&nbsp;&nbsp;3527⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;257🍴</code></b> [textdistance](https://github.com/orsinium/textdistance))：支持 30 多种算法来计算序列之间的距离。
*   Slug 化
    *   <b><code>&nbsp;&nbsp;&nbsp;491⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [awesome-slugify](https://github.com/dimka665/awesome-slugify))：一个 Python slug 化库，可以保持 Unicode。
    *   <b><code>&nbsp;&nbsp;1603⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;117🍴</code></b> [python-slugify](https://github.com/un33k/python-slugify))：Python slug 化库，可以把 unicode 转化为 ASCII。
    *   <b><code>&nbsp;&nbsp;&nbsp;327⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [unicode-slugify](https://github.com/mozilla/unicode-slugify))：一个 slug 工具，可以生成 unicode slugs ,需要依赖 Django 。
*   解析器
    *   <b><code>&nbsp;&nbsp;3729⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;440🍴</code></b> [phonenumbers](https://github.com/daviddrysdale/python-phonenumbers))：解析，格式化，储存，验证电话号码。
    *   <b><code>&nbsp;&nbsp;3729⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;440🍴</code></b> [python-phonenumbers](https://github.com/daviddrysdale/python-phonenumbers))：解析，格式化，存储，校验国际电话号码。
    *   [PLY](http://www.dabeaz.com/ply/)：lex 和 yacc 解析工具的 Python 实现。
    *   [Pygments](http://pygments.org/)：通用语法高亮工具。
    *   [pyparsing](http://pyparsing.wikispaces.com/)：生成通用解析器的框架。
    *   <b><code>&nbsp;&nbsp;&nbsp;707⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;105🍴</code></b> [python-nameparser](https://github.com/derek73/python-nameparser))：把一个人名分解为几个独立的部分。
    *   <b><code>&nbsp;&nbsp;1515⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;195🍴</code></b> [python-user-agents](https://github.com/selwin/python-user-agents))：浏览器 user agent 解析器。
    *   🌎 [sqlparse](sqlparse.readthedocs.org/en/latest/)：一个无验证的 SQL 解析器。

### 特殊文本格式处理

一些用来解析和操作特殊文本格式的库。

*   通用
    *   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [tablib](https://github.com/kennethreitz/tablib))：一个用来处理中表格数据的模块。
*   Office
    *   <b><code>&nbsp;&nbsp;&nbsp;172⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Marmir](https://github.com/brianray/mm))：把输入的 Python 数据结构转换为电子表单。
    *   🌎 [openpyxl](openpyxl.readthedocs.org/en/latest/)：一个用来读写 Excel 2010 xlsx/xlsm/xltx/xltm 文件的库。
    *   <b><code>&nbsp;&nbsp;1281⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;167🍴</code></b> [pyexcel](https://github.com/pyexcel/pyexcel))：一个提供统一 API，用来读写，操作 Excel 文件的库。
    *   <b><code>&nbsp;&nbsp;5514⭐</code></b> <b><code>&nbsp;&nbsp;1268🍴</code></b> [python-docx](https://github.com/python-openxml/python-docx))：读取，查询以及修改 Microsoft Word 2007/2008 docx 文件。
    *   <b><code>&nbsp;&nbsp;3282⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;688🍴</code></b> [python-pptx](https://github.com/scanny/python-pptx))：可用于创建和修改 ppt 文件的 Python 库。
    *   [relatorio](http://relatorio.tryton.org/)：模板化 OpenDocument 文件。
    *   <b><code>&nbsp;&nbsp;2755⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;373🍴</code></b> [unoconv](https://github.com/dagwieers/unoconv))：在 LibreOffice/OpenOffice 支持的任意文件格式之间进行转换。
    *   🌎 [XlsxWriter](xlsxwriter.readthedocs.org/en/latest/)：一个用于创建 Excel .xlsx 文件的 Python 模块。
    *   [xlwings](http://xlwings.org/)：一个使得在 Excel 中方便调用 Python 的库（反之亦然），基于 BSD 协议。
    *   <b><code>&nbsp;&nbsp;1046⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;281🍴</code></b> [xlwt](https://github.com/python-excel/xlwt)) / <b><code>&nbsp;&nbsp;2204⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;440🍴</code></b> [xlrd](https://github.com/python-excel/xlrd))：读写 Excel 文件的数据和格式信息。
    *   <b><code>&nbsp;&nbsp;2608⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;432🍴</code></b> [docxtpl](https://github.com/elapouya/python-docx-template))：通过 jinja2 模版编辑 docx 文档。
*   PDF
    *   <b><code>&nbsp;&nbsp;5298⭐</code></b> <b><code>&nbsp;&nbsp;1116🍴</code></b> [PDFMiner](https://github.com/euske/pdfminer))：一个用于从 PDF 文档中抽取信息的工具。
    *   <b><code>&nbsp;&nbsp;9915⭐</code></b> <b><code>&nbsp;&nbsp;1559🍴</code></b> [PyPDF2](https://github.com/mstamy2/PyPDF2))：一个可以分割，合并和转换 PDF 页面的库。
    *   [ReportLab](http://www.reportlab.com/opensource/)：快速创建富文本 PDF 文档。
*   Markdown
    *   <b><code>&nbsp;&nbsp;3013⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;279🍴</code></b> [Mistune](https://github.com/lepture/mistune))：快速并且功能齐全的纯 Python 实现的 Markdown 解析器。
    *   <b><code>&nbsp;&nbsp;4193⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;895🍴</code></b> [Python-Markdown](https://github.com/waylan/Python-Markdown))：John Gruber’s Markdown 的 Python 版实现。
    *   <b><code>&nbsp;&nbsp;2810⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;446🍴</code></b> [Python-Markdown2](https://github.com/trentm/python-markdown2))：纯 Python 实现的 Markdown 解析器，比 Python-Markdown 更快，更准确，可扩展。
*   YAML
    *   [PyYAML](http://pyyaml.org/)：Python 版本的 YAML 解析器。
*   CSV
    *   <b><code>&nbsp;&nbsp;6367⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;675🍴</code></b> [csvkit](https://github.com/wireservice/csvkit))：用于转换和操作 CSV 的工具。
*   Archive
    *   <b><code>&nbsp;&nbsp;&nbsp;456⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [unp](https://github.com/mitsuhiko/unp))：一个用来方便解包归档文件的命令行工具。

### 自然语言处理

用来处理人类语言的库。

*   [NLTK](http://www.nltk.org/)：一个先进的平台，用以构建处理人类语言数据的 Python 程序。
*   <b><code>&nbsp;16389⭐</code></b> <b><code>&nbsp;&nbsp;4411🍴</code></b> [gensim](https://github.com/piskvorky/gensim))：人性化的话题建模库。
*   <b><code>&nbsp;34846⭐</code></b> <b><code>&nbsp;&nbsp;6705🍴</code></b> [jieba](https://github.com/fxsjy/jieba))：中文分词工具。
*   <b><code>&nbsp;&nbsp;2453⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;322🍴</code></b> [langid.py](https://github.com/saffsd/langid.py))：独立的语言识别系统。
*   [Pattern](http://www.clips.ua.ac.be/pattern)：Python 网络信息挖掘模块。
*   <b><code>&nbsp;&nbsp;6618⭐</code></b> <b><code>&nbsp;&nbsp;1355🍴</code></b> [SnowNLP](https://github.com/isnowfy/snownlp))：一个用来处理中文文本的库。
*   [TextBlob](http://textblob.readthedocs.org/en/latest/)：为进行普通自然语言处理任务提供一致的 API。
*   <b><code>&nbsp;&nbsp;&nbsp;683⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;206🍴</code></b> [TextGrocery](https://github.com/2shou/TextGrocery))：一简单高效的短文本分类工具，基于 LibLinear 和 Jieba。
*   <b><code>&nbsp;&nbsp;2090⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;333🍴</code></b> [thulac](https://github.com/thunlp/THULAC-Python))：清华大学自然语言处理与社会人文计算实验室研制推出的一套中文词法分析工具包。
*   <b><code>&nbsp;&nbsp;2368⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;341🍴</code></b> [polyglot](https://github.com/aboSamoor/polyglot))：支持数百种语言的自然语言处理管道。
*   <b><code>&nbsp;&nbsp;6305⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;791🍴</code></b> [pytext](https://github.com/facebookresearch/pytext))：基于 PyTouch 的自然语言模型框架。
*   <b><code>&nbsp;&nbsp;2228⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;256🍴</code></b> [PyTorch-NLP](https://github.com/PetrochukM/PyTorch-NLP))：一个支持快速深度学习 NLP 原型研究的工具包。
*   🌎 [spacy](spacy.io/)：Python 和 Cython 中用于工业级自然语言处理的库。
*   <b><code>&nbsp;&nbsp;7770⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;941🍴</code></b> [Stanza](https://github.com/stanfordnlp/stanza))：斯坦福 NLP 集团的官方 Python 库，支持 60 多种语言。
*   <b><code>&nbsp;79929⭐</code></b> <b><code>&nbsp;15157🍴</code></b> [funNLP](https://github.com/fighting41love/funNLP))：中文自然语言处理的工具和数据集。
*   <b><code>&nbsp;&nbsp;6703⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;986🍴</code></b> [pkuseg-python](https://github.com/lancopku/pkuseg-python))：一个支持对不同领域进行中文分词的工具箱。

### 文档

用以生成项目文档的库。

*   [Sphinx](http://www.sphinx-doc.org/en/latest/)：Python 文档生成器。
    * <b><code>&nbsp;&nbsp;&nbsp;974⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [awesome-sphinxdoc](https://github.com/yoloseem/awesome-sphinxdoc))
*   [MkDocs](http://www.mkdocs.org/)：对 Markdown 友好的文档生成器。
*   <b><code>&nbsp;&nbsp;2491⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;221🍴</code></b> [pdoc](https://github.com/BurntSushi/pdoc))：一个可以替换 Epydoc 的库，可以自动生成 Python 库的 API 文档。
*   <b><code>&nbsp;&nbsp;&nbsp;862⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;143🍴</code></b> [Pycco](https://github.com/pycco-docs/pycco))：文学编程（literate-programming）风格的文档生成器。
*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [readthedocs](https://github.com/rtfd/readthedocs.org/))：一个基于 Sphinx/MkDocs 的在线文档托管系统，对开源项目免费开放使用。

### 配置

用来保存和解析配置的库。

*   🌎 [config](www.red-dove.com/config-doc/) 🌎 [logging](docs.python.org/2/library/logging.html) 模块作者写的分级配置模块。
*   [ConfigObj](http://www.voidspace.org.uk/python/configobj.html)：INI 文件解析器，带验证功能。
*   🌎 [ConfigParser](docs.python.org/2/library/configparser.html)：(Python 标准库) INI 文件解析器。
*   [profig](http://profig.readthedocs.org/en/default/)：通过多种格式进行配置，具有数值转换功能。
*   <b><code>&nbsp;&nbsp;3024⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;213🍴</code></b> [python-decouple](https://github.com/henriquebastos/python-decouple))：将设置和代码完全隔离。
*   <b><code>&nbsp;10310⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;827🍴</code></b> [hydra](https://github.com/facebookresearch/hydra))：一个优雅地配置复杂应用程序的框架。

### 命令行工具

用于创建命令行程序的库。

*   命令行程序开发
    *   [cement](http://builtoncement.com/)：Python 的命令行程序框架。
    *   [click](http://click.pocoo.org/dev/)：一个通过组合的方式来创建精美命令行界面的包。
    *   [cliff](http://docs.openstack.org/developer/cliff/)：一个用于创建命令行程序的框架，可以创建具有多层命令的命令行程序。
    *   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [clint](https://github.com/kennethreitz/clint))：Python 命令行程序工具。
    *   [docopt](http://docopt.org/)：Python 风格的命令行参数解析器。
    *   <b><code>&nbsp;21935⭐</code></b> <b><code>&nbsp;&nbsp;1045🍴</code></b> [Gooey](https://github.com/chriskiehl/Gooey))：一条命令，将命令行程序变成一个 GUI 程序。
    *   <b><code>&nbsp;10387⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;778🍴</code></b> [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit))：一个用于构建强大的交互式命令行程序的库。
    *   <b><code>&nbsp;28160⭐</code></b> <b><code>&nbsp;&nbsp;1477🍴</code></b> [python-fire](https://github.com/google/python-fire))：Google 出品的一个基于 Python 类的构建命令行界面的库。
    *   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Pythonpy](https://github.com/Russell91/pythonpy/wiki))：在命令行中直接执行任何 Python 指令。
*   终端呈现方式
    * <b><code>&nbsp;&nbsp;4276⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;261🍴</code></b> [asciimatics](https://github.com/peterbrittain/asciimatics))：跨平台，全屏终端包（即鼠标/键盘输入和彩色，定位文本输出），完整的复杂动画和特殊效果的高级 API。
    * <b><code>&nbsp;&nbsp;6263⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;232🍴</code></b> [alive-progress](https://github.com/rsalmei/alive-progress))：一款新的进度条，具有实时吞吐量信息以及非常酷的动画。
    * 🌎 [colorama](pypi.python.org/pypi/colorama)：跨平台彩色终端文本。
    * <b><code>&nbsp;&nbsp;1921⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;142🍴</code></b> [bashplotlib](https://github.com/glamp/bashplotlib))：在终端中进行基本绘图。
    * <b><code>&nbsp;56052⭐</code></b> <b><code>&nbsp;&nbsp;2099🍴</code></b> [rich](https://github.com/willmcgugan/rich))：一个在终端中支持富文本和格式美化的 Python 库， 同时提供了`RichHandler`日志处理程序。
    * <b><code>&nbsp;31102⭐</code></b> <b><code>&nbsp;&nbsp;1442🍴</code></b> [tqdm](https://github.com/tqdm/tqdm))：一个可在循环和命令行中使用的快速、可扩展的进度条。
*   生产力工具
    *   <b><code>&nbsp;16874⭐</code></b> <b><code>&nbsp;&nbsp;4515🍴</code></b> [aws-cli](https://github.com/aws/aws-cli))：Amazon Web Services 的通用命令行界面。
    *   <b><code>&nbsp;&nbsp;&nbsp;411⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [caniusepython3](https://github.com/brettcannon/caniusepython3))：判断是哪个项目妨碍你你移植到 Python 3。
    *   <b><code>&nbsp;24802⭐</code></b> <b><code>&nbsp;&nbsp;2224🍴</code></b> [cookiecutter](https://github.com/audreyr/cookiecutter))：从 cookiecutters（项目模板）创建项目的一个命令行工具。
    *   <b><code>&nbsp;&nbsp;3562⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;100🍴</code></b> [doitlive](https://github.com/sloria/doitlive))：一个用来在终端中进行现场演示的工具。
    *   <b><code>&nbsp;&nbsp;1809⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;279🍴</code></b> [pyftpdlib](https://github.com/giampaolo/pyftpdlib))：一个速度极快和可扩展的 Python FTP 服务库。
    *   <b><code>&nbsp;10832⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;864🍴</code></b> [howdoi](https://github.com/gleitz/howdoi))：通过命令行获取即时的编程问题解答。
    *   <b><code>&nbsp;&nbsp;5224⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;281🍴</code></b> [PathPicker](https://github.com/facebook/PathPicker))：从 bash 输出中选出文件。
    *   <b><code>&nbsp;&nbsp;3330⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;144🍴</code></b> [percol](https://github.com/mooz/percol))：向 UNIX shell 传统管道概念中加入交互式选择功能。
    *   <b><code>&nbsp;96427⭐</code></b> <b><code>&nbsp;&nbsp;3906🍴</code></b> [thefuck](https://github.com/nvbn/thefuck))：修正你之前的命令行指令。
    *   <b><code>&nbsp;&nbsp;&nbsp;749⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [try](https://github.com/timofurrer/try))：一个极其简单的命令行工具，用来试用 python 库。
    *   <b><code>&nbsp;&nbsp;3267⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;251🍴</code></b> [copier](https://github.com/pykong/copier))：用于呈现项目模板的库和命令行实用程序。
    *   <b><code>&nbsp;&nbsp;4732⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;389🍴</code></b> [Invoke](https://github.com/pyinvoke/invoke#readme))：用于管理面向 shell 的子进程，同时支持将可执行的 Python 代码组织成命令行可调用的状态。
    *   <b><code>&nbsp;&nbsp;4476⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;237🍴</code></b> [tmuxp](https://github.com/tony/tmuxp))： <b><code>&nbsp;44403⭐</code></b> <b><code>&nbsp;&nbsp;2575🍴</code></b> [tmux](https://github.com/tmux/tmux)) 会话管理器。
*   高级 CLI
    * <b><code>&nbsp;37908⭐</code></b> <b><code>&nbsp;&nbsp;3888🍴</code></b> [httpie](https://github.com/jkbrzt/httpie))：一个命令行 HTTP 客户端，cURL 的替代品，易用性更好。
    * <b><code>&nbsp;&nbsp;2729⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;117🍴</code></b> [iredis](https://github.com/laixintao/iredis))：支持自动补全和高亮显示的 redis 命令行工具。
    * <b><code>&nbsp;&nbsp;2399⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;176🍴</code></b> [kube-shell](https://github.com/cloudnativelabs/kube-shell))：K8S 命令行集成的 shell 工具。
    * <b><code>&nbsp;&nbsp;3226⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [litecli](https://github.com/dbcli/litecli))：支持自动补全和语法高亮的 SQLite 命令行工具。
    * <b><code>&nbsp;11896⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;688🍴</code></b> [mycli](https://github.com/dbcli/mycli))：支持自动补全和语法高亮的 MySQL 命令行客户端
    * <b><code>&nbsp;13101⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;585🍴</code></b> [pgcli](https://github.com/dbcli/pgcli))：支持自动补全和语法高亮的 Postgres 命令行工具。
    * <b><code>&nbsp;&nbsp;5306⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;281🍴</code></b> [SAWS](https://github.com/donnemartin/saws))：一个加强版的 AWS 命令行。
*   Shell
    * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [xonsh](https://github.com/xonsh/xonsh/))：一种基于 python 的跨平台，面向 unix 的 shell 语言和命令提示符。

### 下载器

用来进行下载的库.

*   <b><code>&nbsp;&nbsp;4875⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;907🍴</code></b> [s3cmd](https://github.com/s3tools/s3cmd))：一个用来管理 Amazon S3 和 CloudFront 的命令行工具。
*   <b><code>&nbsp;&nbsp;1397⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;211🍴</code></b> [s4cmd](https://github.com/bloomreach/s4cmd))：超级 S3 命令行工具，性能更加强劲。
*   🌎 [you-get](www.soimort.org/you-get/)：一个 YouTube/Youku/Niconico 视频下载器，使用 Python 3 编写。
*   [youtube-dl](http://rg3.github.io/youtube-dl/)：一个小巧的命令行程序，用来下载 YouTube 视频。
*   <b><code>&nbsp;18182⭐</code></b> <b><code>&nbsp;&nbsp;3031🍴</code></b> [akshare](https://github.com/jindaxiang/akshare))：为方便人使用而创建的金融数据接口库。

### 图像处理

用来操作图像的库.

*   [pillow](http://pillow.readthedocs.org/en/latest/)：Pillow 是一个更加易用版的 [PIL](http://www.pythonware.com/products/pil/)。
*   <b><code>&nbsp;&nbsp;&nbsp;214⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [hmap](https://github.com/rossgoodwin/hmap))：图像直方图映射。
*   🌎 [imgSeek](sourceforge.net/projects/imgseek/)：一个使用视觉相似性搜索一组图片集合的项目。
*   <b><code>&nbsp;&nbsp;&nbsp;922⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;126🍴</code></b> [nude.py](https://github.com/hhatto/nude.py))：裸体检测。
*   <b><code>&nbsp;&nbsp;&nbsp;653⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;134🍴</code></b> [python-barcode](https://github.com/WhyNotHugo/python-barcode))：不借助其他库在 Python 程序中生成条形码。
*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [pygram](https://github.com/ajkumar25/pygram))：类似 Instagram 的图像滤镜。
*   <b><code>&nbsp;&nbsp;4881⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;726🍴</code></b> [python-qrcode](https://github.com/lincolnloop/python-qrcode))：一个纯 Python 实现的二维码生成器。
*   <b><code>&nbsp;&nbsp;1226⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;152🍴</code></b> [Quads](https://github.com/fogleman/Quads))：基于四叉树的计算机艺术。
*   [scikit-image](http://scikit-image.org/)：一个用于（科学）图像处理的 Python 库。
*   <b><code>&nbsp;10472⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;863🍴</code></b> [thumbor](https://github.com/thumbor/thumbor))：一个小型图像服务，具有剪裁，尺寸重设和翻转功能。
*   <b><code>&nbsp;&nbsp;1483⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;198🍴</code></b> [wand](https://github.com/dahlia/wand))：[MagickWand ](http://www.imagemagick.org/script/magick-wand.php)的 Python 绑定。MagickWand 是 ImageMagick 的 C API 。
*   <b><code>&nbsp;56287⭐</code></b> <b><code>&nbsp;13715🍴</code></b> [face_recognition](https://github.com/ageitgey/face_recognition))：简单易用的 Python 人脸识别库。
*   <b><code>&nbsp;&nbsp;&nbsp;306⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [pagan](https://github.com/daboth/pagan))：基于输入和哈希的复古风图标（头像）生成工具。
*   <b><code>&nbsp;&nbsp;1895⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;226🍴</code></b> [PyMatting](https://github.com/pymatting/pymatting))：支持 alpha matting 的库。
*   <b><code>&nbsp;&nbsp;9054⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;358🍴</code></b> [pywal](https://github.com/dylanaraps/pywal))：由图像生成配色方案的工具。
*   <b><code>&nbsp;&nbsp;&nbsp;795⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [pyvips](https://github.com/libvips/pyvips))：低内存消耗且快速的图像处理库。

### OCR

光学字符识别库。
*   <b><code>&nbsp;75412⭐</code></b> <b><code>&nbsp;10229🍴</code></b> [paddleocr](https://github.com/PaddlePaddle/PaddleOCR)): 除光学字符识别外还引入了表格识别。
*   🌎 [pyocr](gitlab.gnome.org/World/OpenPaperwork/pyocr)：Tesseract 和 Cuneiform 的一个封装。
*   <b><code>&nbsp;&nbsp;6332⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;754🍴</code></b> [pytesseract](https://github.com/madmaze/pytesseract))：[Google Tesseract OCR](https://github.com/tesseract-ocr) 的一个封装。

### 音频

用来操作音频的库

*   <b><code>&nbsp;&nbsp;&nbsp;712⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [audiolazy](https://github.com/danilobellini/audiolazy))：Python 的数字信号处理包。
*   <b><code>&nbsp;&nbsp;&nbsp;536⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;111🍴</code></b> [audioread](https://github.com/beetbox/audioread))：交叉库 (GStreamer + Core Audio + MAD + FFmpeg) 音频解码。
*   [beets](http://beets.io/)：一个音乐库管理工具及 🌎 [MusicBrainz](musicbrainz.org/) 标签添加工具。
*   <b><code>&nbsp;&nbsp;6740⭐</code></b> <b><code>&nbsp;&nbsp;1465🍴</code></b> [dejavu](https://github.com/worldveil/dejavu))：音频指纹提取和识别。
*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [django-elastic-transcoder](https://github.com/StreetVoice/django-elastic-transcoder))：Django + [Amazon Elastic Transcoder](http://aws.amazon.com/elastictranscoder/)。
*   [eyeD3](http://eyed3.nicfit.net/)：一个用来操作音频文件的工具，具体来讲就是包含 ID3 元信息的 MP3 文件。
*   [id3reader](http://nedbatchelder.com/code/modules/id3reader.py)：一个用来读取 MP3 元数据的 Python 模块。
*   <b><code>&nbsp;&nbsp;2256⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;494🍴</code></b> [m3u8](https://github.com/globocom/m3u8))：一个用来解析 m3u8 文件的模块。
*   🌎 [mutagen](bitbucket.org/lazka/mutagen)：一个用来处理音频元数据的 Python 模块。
*   <b><code>&nbsp;&nbsp;9753⭐</code></b> <b><code>&nbsp;&nbsp;1124🍴</code></b> [pydub](https://github.com/jiaaro/pydub))：通过简单、简洁的高层接口来操作音频文件。
*   <b><code>&nbsp;&nbsp;&nbsp;678⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;856🍴</code></b> [pyechonest](https://github.com/echonest/pyechonest))：[Echo Nest](http://developer.echonest.com/) API 的 Python 客户端。
*   [talkbox](http://scikits.appspot.com/talkbox)：一个用来处理演讲/信号的 Python 库。
*   <b><code>&nbsp;&nbsp;&nbsp;393⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [TimeSide](https://github.com/Parisson/TimeSide))：开源 web 音频处理框架。
*   <b><code>&nbsp;&nbsp;&nbsp;809⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;104🍴</code></b> [tinytag](https://github.com/devsnd/tinytag))：一个用来读取 MP3, OGG, FLAC 以及 Wave 文件音乐元数据的库。
*   [mingus](http://bspaans.github.io/python-mingus/)：一个高级音乐理论和曲谱包，支持 MIDI 文件和回放功能。
*   <b><code>&nbsp;&nbsp;&nbsp;946⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;148🍴</code></b> [kapre](https://github.com/keunwoochoi/kapre))：Keras 音频处理器。
*   <b><code>&nbsp;&nbsp;8317⭐</code></b> <b><code>&nbsp;&nbsp;1045🍴</code></b> [librosa](https://github.com/librosa/librosa))：音频音乐分析 Python 库。
*   <b><code>&nbsp;&nbsp;2480⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;263🍴</code></b> [matchering](https://github.com/sergree/matchering))：用于音频母带制作的库。
* <b><code>&nbsp;&nbsp;6233⭐</code></b> <b><code>&nbsp;&nbsp;1222🍴</code></b> [pyAudioAnalysis](https://github.com/tyiannak/pyAudioAnalysis))：音频特征提取，分类，分段和应用。
* <b><code>&nbsp;14957⭐</code></b> <b><code>&nbsp;&nbsp;2000🍴</code></b> [beets](https://github.com/beetbox/beets))：一个音乐库管理器和 🌎 [MusicBrainz](musicbrainz.org/) 标记器。

### Video

用来操作视频和 GIF 的库。

*   [moviepy](http://zulko.github.io/moviepy/)：一个用来进行基于脚本的视频编辑模块，适用于多种格式，包括动图 GIFs。
*   <b><code>&nbsp;&nbsp;&nbsp;152⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [scikit-video](https://github.com/aizvorski/scikit-video))：SciPy 视频处理常用程序。
*   <b><code>&nbsp;&nbsp;3693⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;281🍴</code></b> [vidgear](https://github.com/abhiTronix/vidgear))： 强大的多线程视频处理框架。

### 地理位置

地理编码地址以及用来处理经纬度的库。

*   🌎 [GeoDjango](docs.djangoproject.com/en/dev/ref/contrib/gis/)：世界级地理图形 web 框架。
*   <b><code>&nbsp;&nbsp;&nbsp;231⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [GeoIP](https://github.com/maxmind/geoip-api-python))：MaxMind GeoIP Legacy 数据库的 Python API。
*   <b><code>&nbsp;&nbsp;&nbsp;987⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;128🍴</code></b> [geojson](https://github.com/frewsxcv/python-geojson))：GeoJSON 的 Python 绑定及工具。
*   <b><code>&nbsp;&nbsp;4800⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;664🍴</code></b> [geopy](https://github.com/geopy/geopy))：Python 地址编码工具箱。
*   <b><code>&nbsp;&nbsp;1205⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;143🍴</code></b> [GeoIP2](https://github.com/maxmind/GeoIP2-python))：GeoIP2 Webservice 客户端与数据库 Python API。
*   <b><code>&nbsp;&nbsp;1525⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;302🍴</code></b> [django-countries](https://github.com/SmileyChris/django-countries))：一个 Django 应用程序，提供用于表格的国家选择功能，国旗图标静态文件以及模型中的国家字段。
*   <b><code>&nbsp;&nbsp;&nbsp;481⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;108🍴</code></b> [pygeoip](https://github.com/appliedsec/pygeoip))：Python GeoIP 接口。

### HTTP

使用 HTTP 的库。

*   <b><code>&nbsp;16396⭐</code></b> <b><code>&nbsp;&nbsp;2243🍴</code></b> [aiohttp](https://github.com/aio-libs/aiohttp))：基于 asyncio 的异步 HTTP 网络库。
*   [requests](http://docs.python-requests.org/en/latest/)：人性化的 HTTP 请求库。
*   <b><code>&nbsp;&nbsp;4584⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;329🍴</code></b> [grequests](https://github.com/kennethreitz/grequests))：requests 库 + gevent ，用于异步 HTTP 请求。
*   <b><code>&nbsp;&nbsp;&nbsp;380⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;167🍴</code></b> [httplib2](https://github.com/jcgregorio/httplib2))：全面的 HTTP 客户端库。
*   <b><code>&nbsp;&nbsp;&nbsp;605⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;142🍴</code></b> [treq](https://github.com/twisted/treq))：类似 requests 的 Python API 构建于 Twisted HTTP 客户端之上。
*   <b><code>&nbsp;&nbsp;4020⭐</code></b> <b><code>&nbsp;&nbsp;1314🍴</code></b> [urllib3](https://github.com/shazow/urllib3))：一个具有线程安全连接池，支持文件 post，清晰友好的 HTTP 库。
*   <b><code>&nbsp;15184⭐</code></b> <b><code>&nbsp;&nbsp;1108🍴</code></b> [httpx](https://github.com/encode/httpx))：下一代 Python HTTP 客户端。

### 数据库

Python 实现的数据库。

*   🌎 [pickleDB](pythonhosted.org/pickleDB/)：一个简单，轻量级键值储存数据库。
*   🌎 [PipelineDB](www.pipelinedb.com/)：流式 SQL 数据库。
*   <b><code>&nbsp;&nbsp;7496⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;607🍴</code></b> [TinyDB](https://github.com/msiemens/tinydb))：一个微型的，面向文档型数据库。
*   [ZODB](http://www.zodb.org/en/latest/)：一个 Python 原生对象数据库。一个键值和对象图数据库。

### 数据库驱动

用来连接和操作数据库的库。

*   MySQL：[awesome-mysql](http://shlomi-noach.github.io/awesome-mysql/) 系列
    *   <b><code>&nbsp;&nbsp;1889⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;263🍴</code></b> [aiomysql](https://github.com/aio-libs/aiomysql))：基于 asyncio 的异步 MySQL 数据库操作库。
    *   🌎 [mysql-python](sourceforge.net/projects/mysql-python/)：Python 的 MySQL 数据库连接器。
    *   ysqlclient：<b><code>&nbsp;&nbsp;2527⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;445🍴</code></b> [mysql-python](https://github.com/PyMySQL/mysqlclient-python)) 分支，支持 Python 3。
    *   🌎 [oursql](pythonhosted.org/oursql/)：一个更好的 MySQL 连接器，支持原生预编译指令和 BLOBs。
    *   <b><code>&nbsp;&nbsp;7831⭐</code></b> <b><code>&nbsp;&nbsp;1440🍴</code></b> [PyMySQL](https://github.com/PyMySQL/PyMySQL))：纯 Python MySQL 驱动，兼容 mysql-python。
*   PostgreSQL
    *   [psycopg2](http://initd.org/psycopg/)：Python 中最流行的 PostgreSQL 适配器。
    *   <b><code>&nbsp;&nbsp;&nbsp;255⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [queries](https://github.com/gmr/queries))：psycopg2 库的封装，用来和 PostgreSQL 进行交互。
    *   [txpostgres](http://txpostgres.readthedocs.org/en/latest/)：基于 Twisted 的异步 PostgreSQL 驱动。
*   其他关系型数据库
    *   [apsw](http://rogerbinns.github.io/apsw/)：另一个 Python SQLite 封装。
    *   dataset：在数据库中存储 Python 字典
    *   [pymssql](http://www.pymssql.org/en/latest/)：一个简单的 Microsoft SQL Server 数据库接口。
*   NoSQL 数据库
    *   <b><code>&nbsp;&nbsp;&nbsp;551⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;73🍴</code></b> [asyncio-redis](https://github.com/jonathanslenders/asyncio-redis))：基于 asyncio 的 redis 客户端 (PEP 3156)。
    *   <b><code>&nbsp;&nbsp;1427⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;577🍴</code></b> [cassandra-python-driver](https://github.com/datastax/python-driver))：Cassandra 的 Python 驱动。
    *   [HappyBase](http://happybase.readthedocs.org/en/latest/)：一个为 Apache HBase 设计的，对开发者友好的库。
    *   🌎 [Plyvel](plyvel.readthedocs.org/en/latest/)：一个快速且功能丰富的 LevelDB 的 Python 接口。
    *   [py2neo](http://py2neo.org/2.0/)：Neo4j restful 接口的 Python 封装客户端。
    *   <b><code>&nbsp;&nbsp;&nbsp;500⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;138🍴</code></b> [pycassa](https://github.com/pycassa/pycassa))：Cassandra 的 Python Thrift 驱动。
    *   🌎 [PyMongo](docs.mongodb.org/ecosystem/drivers/python/)：MongoDB 的官方 Python 客户端。
    *   <b><code>&nbsp;13519⭐</code></b> <b><code>&nbsp;&nbsp;2671🍴</code></b> [redis-py](https://github.com/andymccurdy/redis-py))：Redis 的 Python 客户端。
    *   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [telephus](https://github.com/driftx/Telephus))：基于 Twisted 的 Cassandra 客户端。
    *   <b><code>&nbsp;&nbsp;&nbsp;128⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [txRedis](https://github.com/deldotdr/txRedis))：基于 Twisted 的 Redis 客户端。
    *   <b><code>&nbsp;&nbsp;5887⭐</code></b> <b><code>&nbsp;&nbsp;1450🍴</code></b> [kafka-python](https://github.com/dpkp/kafka-python))：Apache Kafka Python 客户端。
*   异步客户端
    * <b><code>&nbsp;&nbsp;2525⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;214🍴</code></b> [motor](https://github.com/mongodb/motor))：支持 MongoDB 的异步 Python 驱动程序。

### ORM

实现对象关系映射或数据映射技术的库。

*   关系型数据库
    *   🌎 [Django Models](docs.djangoproject.com/en/dev/topics/db/models/)：Django 的一部分。
    *   [SQLAlchemy](http://www.sqlalchemy.org/)：Python SQL 工具以及对象关系映射工具。
        * <b><code>&nbsp;&nbsp;3040⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;158🍴</code></b> [awesome-sqlalchemy](https://github.com/dahlia/awesome-sqlalchemy))
    *   <b><code>&nbsp;&nbsp;3040⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;158🍴</code></b> [awesome-sqlalchemy](https://github.com/dahlia/awesome-sqlalchemy)) 系列
    *   <b><code>&nbsp;11961⭐</code></b> <b><code>&nbsp;&nbsp;1386🍴</code></b> [Peewee](https://github.com/coleifer/peewee))：一个小巧，富有表现力的 ORM。
    *   🌎 [PonyORM](ponyorm.com/)：提供面向生成器的 SQL 接口的 ORM。
    *   🌎 [python-sql](pypi.python.org/pypi/python-sql)：编写 Python 风格的 SQL 查询。
    *   <b><code>&nbsp;&nbsp;4862⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;297🍴</code></b> [dataset](https://github.com/pudo/dataset))：在数据库中存储字典，支持 SQLite，MySQL 和 PostgreSQL。
    *   <b><code>&nbsp;&nbsp;1420⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;169🍴</code></b> [orator](https://github.com/sdispater/orator))：Orator ORM，提供了一个简单而美观的 ActiveRecord 实现。
    *   <b><code>&nbsp;&nbsp;1868⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97🍴</code></b> [orm](https://github.com/encode/orm))：一个异步的 ORM。
    *   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [pony](https://github.com/ponyorm/pony/))：提供面向生成器的SQL接口的ORM。
    *   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [pydal](https://github.com/web2py/pydal/))：纯 Python 数据库抽象接口层。
*   NoSQL 数据库
    *   <b><code>&nbsp;&nbsp;&nbsp;869⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;210🍴</code></b> [django-mongodb-engine](https://github.com/django-nonrel/mongodb-engine))：Django MongoDB 后端。
    *   <b><code>&nbsp;&nbsp;2647⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;426🍴</code></b> [PynamoDB](https://github.com/jlafon/PynamoDB)) 🌎 [Amazon DynamoDB](aws.amazon.com/dynamodb/) 的一个 Python 风格接口。
    *   <b><code>&nbsp;&nbsp;&nbsp;127⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [flywheel](https://github.com/mathcamp/flywheel))：Amazon DynamoDB 的对象映射工具。
    *   [MongoEngine](http://mongoengine.org/)：一个 Python 对象文档映射工具，用于 MongoDB。
    *   <b><code>&nbsp;&nbsp;&nbsp;296⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [hot-redis](https://github.com/stephenmcd/hot-redis))：为 Redis 提供 Python 丰富的数据类型。
    *   <b><code>&nbsp;&nbsp;&nbsp;443⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75🍴</code></b> [redisco](https://github.com/kiddouk/redisco))：一个 Python 库，提供可以持续存在在 Redis 中的简单模型和容器。
*   其他
    *   <b><code>&nbsp;&nbsp;&nbsp;341⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [butterdb](https://github.com/Widdershin/butterdb))：Google Drive 电子表格的 Python ORM。

### Web 框架

全栈 Web 框架。

*   🌎 [Django](www.djangoproject.com/)：Python 界最流行的 web 框架。
    *   <b><code>&nbsp;&nbsp;1905⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;287🍴</code></b> [awesome-django(by shahraizali)](https://github.com/shahraizali/awesome-django)) 系列
    *   <b><code>&nbsp;11057⭐</code></b> <b><code>&nbsp;&nbsp;1454🍴</code></b> [awesome-django(by wsvincent)](https://github.com/wsvincent/awesome-django)) 系列
*   [Flask](http://flask.pocoo.org/)：一个 Python 微型框架。
    *   <b><code>&nbsp;12716⭐</code></b> <b><code>&nbsp;&nbsp;1576🍴</code></b> [awesome-flask](https://github.com/humiaozuzu/awesome-flask)) 系列
*   🌎 [Pyramid](pylonsproject.org/)：一个小巧，快速，接地气的开源 Python web 框架。
    *   <b><code>&nbsp;&nbsp;&nbsp;570⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [awesome-pyramid](https://github.com/uralbash/awesome-pyramid)) 系列
*   [Bottle](http://bottlepy.org/docs/dev/index.html)：一个快速小巧，轻量级的 WSGI 微型 web 框架。
*   [CherryPy](http://www.cherrypy.org/)：一个极简的 Python web 框架，服从 HTTP/1.1 协议且具有 WSGI 线程池。
*   [TurboGears](http://www.turbogears.org/)：一个可以扩展为全栈解决方案的微型框架。
*   [web.py](http://webpy.org/)：一个 Python 的 web 框架，既简单，又强大。
*   [web2py](http://www.web2py.com/)：一个全栈 web 框架和平台，专注于简单易用。
*   [Tornado](http://www.tornadoweb.org/en/latest/)：一个 web 框架和异步网络库。
*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [sanic](https://github.com/channelcat/sanic/))：基于 Python3.5+ 的异步网络框架。
*   🌎 [starlette](www.starlette.io/)： 一款轻量级，高性能的 ASGI 框架。
*   <b><code>&nbsp;&nbsp;2363⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;137🍴</code></b> [Masonite](https://github.com/MasoniteFramework/masonite))：以开发者为中心的现代 Python Web 框架。

### WebSocket

Web socket 相关库。

* <b><code>&nbsp;&nbsp;2536⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;767🍴</code></b> [autobahn-python](https://github.com/crossbario/autobahn-python))：适用于 Twisted 和 asyncio 的 Python WebSocket 和 WAMP。
* <b><code>&nbsp;&nbsp;6342⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;821🍴</code></b> [channels](https://github.com/django/channels))：开发者友好的 Django 异步工具。
* <b><code>&nbsp;&nbsp;5661⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;589🍴</code></b> [websockets](https://github.com/aaugustin/websockets))：一个用于构建 WebSocket 服务器和客户端的库，着重于正确性和简单性。

### 权限

允许或拒绝用户访问数据或功能的库。

*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Carteblanche](https://github.com/neuman/python-carteblanche/))：站在用户和设计者角度开发的一个代码对齐模块，很好地处理了代码导航及权限。
*   <b><code>&nbsp;&nbsp;3899⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;587🍴</code></b> [django-guardian](https://github.com/django-guardian/django-guardian))：Django 1.2+ ，实现了单个对象权限。
*   <b><code>&nbsp;&nbsp;1969⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;152🍴</code></b> [django-rules](https://github.com/dfunckt/django-rules))：一个小巧但是强大的应用，提供对象级别的权限管理，且不需要使用数据库。

### CMS

内容管理系统。

*   [odoo-cms](http://www.odoo.com)：一个开源的，企业级 CMS，基于 odoo。
*   [django-cms](http://www.django-cms.org/en/)：一个开源的，企业级 CMS，基于 Django。
*   [djedi-cms](http://djedi-cms.org/)：一个轻量级但却非常强大的 Django CMS ，考虑到了插件，内联编辑以及性能。
*   [FeinCMS](http://www.feincms.org/)：基于 Django 构建的最先进的内容管理系统之一。
*   [Kotti](http://kotti.pylonsproject.org/)：一个高级的，Python 范的 web 应用框架，基于 Pyramid 构建。
*   [Mezzanine](http://mezzanine.jupo.org/)：一个强大的，持续的，灵活的内容管理平台。
*   [Opps](http://opps.github.io/opps/)：一个为杂志，报纸网站以及大流量门户网站设计的 CMS 平台，基于 Django。
*   🌎 [Plone](plone.org/)：一个构建于开源应用服务器 Zope 之上的 CMS。
*   🌎 [Quokka](quintagroup.com/cms/python/quokka)：灵活，可扩展的小型 CMS，基于 Flask 和 MongoDB。
*   🌎 [Wagtail](wagtail.io/)：一个 Django 内容管理系统。
*   🌎 [Widgy](wid.gy/)：最新的 CMS 框架，基于 Django。
*   <b><code>&nbsp;&nbsp;2054⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;524🍴</code></b> [indico](https://github.com/indico/indico))：一个功能丰富的事件管理系统，由  🌎 [CERN](en.wikipedia.org/wiki/CERN) 开发。

### 电子商务

用于电子商务以及支付的框架和库。

*   [django-oscar](http://oscarcommerce.com/)：一个用于 Django 的开源的电子商务框架。
*   <b><code>&nbsp;&nbsp;3316⭐</code></b> <b><code>&nbsp;&nbsp;1044🍴</code></b> [django-shop](https://github.com/awesto/django-shop))：一个基于 Django 的店铺系统。
*   <b><code>&nbsp;&nbsp;&nbsp;713⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;296🍴</code></b> [Cartridge](https://github.com/stephenmcd/cartridge))：一个基于 Mezzanine 构建的购物车应用。
*   🌎 [shoop](www.shoop.io/en/)：一个基于 Django 的开源电子商务平台。
*   <b><code>&nbsp;&nbsp;&nbsp;326⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90🍴</code></b> [alipay](https://github.com/lxneng/alipay))：非官方的 Python 支付宝 API。
*   <b><code>&nbsp;&nbsp;1023⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;172🍴</code></b> [merchant](https://github.com/agiliq/merchant))：一个可以接收来自多种支付平台支付的 Django 应用。
*   <b><code>&nbsp;&nbsp;&nbsp;236⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [money](https://github.com/carlospalol/money))：一个货币类库。带有可选的 CLDR 后端本地化格式，提供可扩展的货币兑换解决方案。
*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [python-currencies](https://github.com/Alir3z4/python-currencies))：显示货币格式以及它的数值。
*   <b><code>&nbsp;&nbsp;&nbsp;701⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;198🍴</code></b> [forex-python](https://github.com/MicroPyramid/forex-python))：外汇汇率，比特币价格指数和货币换算。
*   [saleor](http://getsaleor.com/)：一款兼容 Django 的电子商务平台。

### RESTful API

用来开发 RESTful APIs 的库

*   Django
    *   [django-rest-framework](http://www.django-rest-framework.org/)：一个强大灵活的工具，用来构建 web API。
    *   [django-tastypie](http://tastypieapi.org/)：为 Django 应用开发 API。
    *   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [django-formapi](https://github.com/5monkeys/django-formapi))：为 Django 的表单验证，创建 JSON APIs 。
*   Flask
    *   [flask-api](http://www.flaskapi.org/)：为 flask 开发的，可浏览 Web APIs 。
    *   [flask-restful](http://flask-restful.readthedocs.org/en/latest/)：为 flask 快速创建 REST APIs 。
    *   🌎 [flask-restless](flask-restless.readthedocs.org/en/latest/)：为 SQLAlchemy 定义的数据库模型创建 RESTful APIs 。
    *   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [flask-api-utils](https://github.com/marselester/flask-api-utils))：为 Flask 处理 API 表示和验证。
    *   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [eve](https://github.com/nicolaiarocci/eve))：REST API 框架，由 Flask, MongoDB 等驱动。
*   Pyramid
    *   🌎 [cornice](cornice.readthedocs.org/en/latest/)：一个 Pyramid 的 REST 框架 。
*   与框架无关的
    *   [falcon](http://falconframework.org/)：一个用来建立云 API 和 web app 后端的高性能框架。
    *   <b><code>&nbsp;&nbsp;2292⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;168🍴</code></b> [sandman](https://github.com/jeffknupp/sandman))：为现存的数据库驱动系统自动创建 REST APIs 。
    *   [restless](http://restless.readthedocs.org/en/latest/)：框架无关的 REST 框架 ，基于从 Tastypie 学到的知识。
    *   <b><code>&nbsp;&nbsp;&nbsp;199⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [ripozo](https://github.com/vertical-knowledge/ripozo))：快速创建 REST/HATEOAS/Hypermedia APIs。
    *   <b><code>&nbsp;&nbsp;5556⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;407🍴</code></b> [apistar](https://github.com/encode/apistar))：专为Python 3设计的智能 Web API 框架。
    *   <b><code>&nbsp;97096⭐</code></b> <b><code>&nbsp;&nbsp;9058🍴</code></b> [fastapi](https://github.com/tiangolo/fastapi))：一个现代，快速，基于标准 Python 类型注解的的 web框架，可使用 Python3.6+ 版本构建 API。
    *   <b><code>&nbsp;&nbsp;6897⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;389🍴</code></b> [hug](https://github.com/hugapi/hug))：一个为纯净公开的 API 打造的 Python 3 框架。
    *   <b><code>&nbsp;&nbsp;2043⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;217🍴</code></b> [sandman2](https://github.com/jeffknupp/sandman2))：为数据库驱动的系统自动生成 REST API。
    *   🌎 [vibora](vibora.io/)：快速高效且支持异步的 Web 框架，灵感来源于 Flask。

### 验证

实现验证方案的库。

*   OAuth
    *   <b><code>&nbsp;&nbsp;5270⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;527🍴</code></b> [authlib](https://github.com/lepture/authlib))：一个强大的Python库，用来构建 OAuth 和 OpenID 服务端。包括：JWS, JWK, JWA, JWT。
    *   [Authomatic](http://peterhudec.github.io/authomatic/)：简单但是强大的框架，身份验证/授权客户端。
    *   <b><code>&nbsp;10317⭐</code></b> <b><code>&nbsp;&nbsp;3116🍴</code></b> [django-allauth](https://github.com/pennersr/django-allauth))：Django 的验证应用。
    *   <b><code>&nbsp;&nbsp;3317⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;840🍴</code></b> [django-oauth-toolkit](https://github.com/evonove/django-oauth-toolkit))：为 Django 用户准备的 OAuth2。
    *   <b><code>&nbsp;&nbsp;&nbsp;338⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;254🍴</code></b> [django-oauth2-provider](https://github.com/caffeinehit/django-oauth2-provider))：为 Django 应用提供 OAuth2 接入。
    *   <b><code>&nbsp;&nbsp;1450⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;452🍴</code></b> [Flask-OAuthlib](https://github.com/lepture/flask-oauthlib))：OAuth 1.0/a, 2.0 客户端实现，供 Flask 使用。
    *   <b><code>&nbsp;&nbsp;2960⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;505🍴</code></b> [OAuthLib](https://github.com/idan/oauthlib))：一个 OAuth 请求-签名逻辑通用、 完整的实现。
    *   <b><code>&nbsp;&nbsp;3010⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;902🍴</code></b> [python-oauth2](https://github.com/joestump/python-oauth2))：一个完全测试的抽象接口。用来创建 OAuth 客户端和服务端。
    *   <b><code>&nbsp;&nbsp;2809⭐</code></b> <b><code>&nbsp;&nbsp;1070🍴</code></b> [python-social-auth](https://github.com/omab/python-social-auth))：一个设置简单的社会化验证方式。
    *   <b><code>&nbsp;&nbsp;1601⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;171🍴</code></b> [rauth](https://github.com/litl/rauth))：OAuth 1.0/a, 2.0, 和 Ofly 的 Python 库。
    *   <b><code>&nbsp;&nbsp;&nbsp;189⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [sanction](https://github.com/demianbrecht/sanction))：一个超级简单的 OAuth2 客户端实现。
*   其他
    *   <b><code>&nbsp;&nbsp;5639⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;749🍴</code></b> [PyJWT](https://github.com/jpadilla/pyjwt))：JSON Web 令牌草案 01。
    *   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [python-jws](https://github.com/brianloveswords/python-jws))：JSON Web 签名草案 02 的实现。
    *   <b><code>&nbsp;&nbsp;&nbsp;222⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [python-jwt](https://github.com/davedoesdev/python-jwt))：一个用来生成和验证 JSON Web 令牌的模块。
    *   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [python-jose](https://github.com/mpdavis/python-jose/))：python 版 JOSE 实现。

### 模板引擎

模板生成和词法解析的库和工具。

*   <b><code>&nbsp;11557⭐</code></b> <b><code>&nbsp;&nbsp;1724🍴</code></b> [Jinja2](https://github.com/pallets/jinja))：一个现代的，对设计师友好的模板引擎。
*   🌎 [Chameleon](chameleon.readthedocs.org/en/latest/)：一个 HTML/XML 模板引擎。 模仿了 ZPT（Zope Page Templates）, 进行了速度上的优化。
*   🌎 [Genshi](genshi.edgewall.org/)：Python 模板工具，用以生成 web 感知的结果。
*   [Mako](http://www.makotemplates.org/)：Python 平台的超高速轻量级模板。

### 队列

处理事件以及任务队列的库。

*   [celery](http://www.celeryproject.org/)：一个异步任务队列/作业队列，基于分布式消息传递
*   <b><code>&nbsp;&nbsp;5201⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;358🍴</code></b> [daramatiq](https://github.com/Bogdanp/dramatiq))：适用于Python 3的快速可靠的后台任务处理库。
*   <b><code>&nbsp;&nbsp;5918⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;393🍴</code></b> [huey](https://github.com/coleifer/huey))：小型多线程任务队列。
*   <b><code>&nbsp;&nbsp;&nbsp;895⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;115🍴</code></b> [mrq](https://github.com/pricingassistant/mrq))：一个 Python 的分布式 worker 任务队列， 使用 Redis 和 gevent。
*   [rq](http://python-rq.org/)：简单的 Python 作业队列。
*   <b><code>&nbsp;&nbsp;&nbsp;160⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [simpleq](https://github.com/rdegges/simpleq))：一个简单的，可无限扩张的，基于亚马逊 SQS 的队列。

### 搜索

对数据进行索引和执行搜索查询的库和软件。

*   <b><code>&nbsp;&nbsp;3771⭐</code></b> <b><code>&nbsp;&nbsp;1312🍴</code></b> [django-haystack](https://github.com/django-haystack/django-haystack))：Django 模块化搜索。
*   🌎 [elasticsearch-py](www.elastic.co/guide/en/elasticsearch/client/python-api/current/index.html)：Elasticsearch 的官方底层 Python 客户端。
*   <b><code>&nbsp;&nbsp;3877⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;793🍴</code></b> [elasticsearch-dsl-py](https://github.com/elastic/elasticsearch-dsl-py))：Elasticsearch 的官方高级 Python 客户端。
*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [solrpy](https://github.com/edsu/solrpy))：[solr](http://lucene.apache.org/solr/) 的 Python 客户端。
*   <b><code>&nbsp;&nbsp;&nbsp;697⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;338🍴</code></b> [pysolr](https://github.com/django-haystack/pysolr))：支持 🌎 [Apache Solr](lucene.apache.org/solr/) 的轻量级 Python 装饰器。
*   [Whoosh](http://whoosh.readthedocs.org/en/latest/)：一个快速的纯 Python 搜索引擎库。

### 动态消息

用来创建用户活动的库。

*   <b><code>&nbsp;&nbsp;2440⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;472🍴</code></b> [django-activity-stream](https://github.com/justquick/django-activity-stream))：从你的站点行为中生成通用活动信息流。
*   <b><code>&nbsp;&nbsp;4750⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;530🍴</code></b> [Stream-Framework](https://github.com/tschellenbach/Stream-Framework))：使用 Cassandra 和 Redis 创建动态消息和通知系统。

### Web 资源管理

管理、压缩、缩小网站资源的工具。

*   <b><code>&nbsp;&nbsp;2872⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;608🍴</code></b> [django-compressor](https://github.com/django-compressor/django-compressor))：将链接和内联的 JavaScript 或 CSS 压缩到一个单独的缓存文件中。
*   <b><code>&nbsp;&nbsp;1542⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;371🍴</code></b> [django-pipeline](https://github.com/jazzband/django-pipeline))：Django 的资源包装库。
*   [django-storages](http://django-storages.readthedocs.org/en/latest/)：一个针对 Django 的自定义存储后端的工具集合。
*   [fanstatic](http://www.fanstatic.org/en/latest/)：打包、优化，并且把静态文件依赖作为 Python 的包来提供。
*   🌎 [File Conveyor](wimleers.com/fileconveyor/)：一个后台驻留的程序，用来发现和同步文件到 CDNs, S3 和 FTP。
*   [Flask-Assets](http://flask-assets.readthedocs.org/en/latest/)：帮你将 web 资源整合到你的 Flask app 中。
*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [jinja-assets-compressor](https://github.com/jaysonsantos/jinja-assets-compressor))：一个 Jinja 扩展，用来编译和压缩你的资源。
*   [webassets](http://webassets.readthedocs.org/en/latest/)：为你的静态资源打包、优化和管理生成独一无二的缓存 URL。

### 缓存

缓存数据的库。

*   [Beaker](http://beaker.readthedocs.org/en/latest/)：一个缓存和会话库，可以用在 web 应用和独立 Python 脚本和应用上。
*   <b><code>&nbsp;&nbsp;&nbsp;885⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;159🍴</code></b> [django-cache-machine](https://github.com/django-cache-machine/django-cache-machine))：Django 模型的自动缓存和失效。
*   <b><code>&nbsp;&nbsp;2267⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;236🍴</code></b> [django-cacheops](https://github.com/Suor/django-cacheops))：具有自动颗粒化事件驱动失效功能的 ORM。
*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [django-viewlet](https://github.com/5monkeys/django-viewlet))：渲染模板，同时具有额外的缓存控制功能。
*   [dogpile.cache](http://dogpilecache.readthedocs.org/en/latest/)：dogpile.cache 是 Beaker 的下一代替代品，由同一作者开发。
*   🌎 [HermesCache](pypi.python.org/pypi/HermesCache)：Python 缓存库，具有基于标签的失效和 dogpile effect 保护功能。
*   <b><code>&nbsp;&nbsp;&nbsp;310⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [johnny-cache](https://github.com/jmoiron/johnny-cache))：django 应用缓存框架。
*   <b><code>&nbsp;&nbsp;&nbsp;492⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;140🍴</code></b> [pylibmc](https://github.com/lericson/pylibmc))：[libmemcached](http://libmemcached.org/libMemcached.html) 接口的 Python 封装。
*   [python-diskcache](http://www.grantjenks.com/docs/diskcache/)：SQLite 和文件支持的缓存后端，具有比 memcached 和 redis 更快的查找速度。

### 电子邮件

用来发送和解析电子邮件的库。

*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [django-celery-ses](https://github.com/StreetVoice/django-celery-ses))：带有 AWS SES 和 Celery 的 Django email 后端。
*   [envelopes](http://tomekwojcik.github.io/envelopes/)：供人类使用的电子邮件库。
*   <b><code>&nbsp;&nbsp;1651⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;210🍴</code></b> [flanker](https://github.com/mailgun/flanker))：一个 email 地址和 Mime 解析库。
*   <b><code>&nbsp;&nbsp;1212⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;188🍴</code></b> [imbox](https://github.com/martinrusev/imbox))：Python IMAP 库。
*   <b><code>&nbsp;&nbsp;1501⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;136🍴</code></b> [inbox.py](https://github.com/kennethreitz/inbox.py))：Python SMTP 服务器。
*   <b><code>&nbsp;&nbsp;3505⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;347🍴</code></b> [inbox](https://github.com/nylas/sync-engine))：一个开源电子邮件工具箱。
*   <b><code>&nbsp;&nbsp;&nbsp;742⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;197🍴</code></b> [lamson](https://github.com/zedshaw/lamson))：Python 风格的 SMTP 应用服务器。
*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [mailjet](https://github.com/WoLpH/mailjet))：Mailjet API 实现，用来提供批量发送邮件，统计等功能。
*   <b><code>&nbsp;&nbsp;&nbsp;293⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [marrow.mailer](https://github.com/marrow/mailer))：高性能可扩展邮件分发框架。
*   <b><code>&nbsp;&nbsp;3475⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;463🍴</code></b> [modoboa](https://github.com/tonioo/modoboa))：一个邮件托管和管理平台，具有现代的、简约的 Web UI。
*   [pyzmail](http://www.magiksys.net/pyzmail/)：创建，发送和解析电子邮件。
*   <b><code>&nbsp;&nbsp;1324⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;301🍴</code></b> [Talon](https://github.com/mailgun/talon))：Mailgun 库，用来抽取信息和签名。
*   🌎 [yagmail](pypi.org/project/yagmail/)：yagmail是一个GMAIL / SMTP客户端，旨在使其尽可能简单地发送电子邮件。
*   <b><code>&nbsp;&nbsp;&nbsp;662⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70🍴</code></b> [salmon](https://github.com/moggers87/salmon))：一个 Python 邮件服务器。
*   <b><code>&nbsp;&nbsp;&nbsp;293⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [mailer](https://github.com/marrow/mailer))：一款高性能可扩展的邮件投递框架。

### 国际化

用来进行国际化的库。

*   [Babel](http://babel.pocoo.org/en/latest/)：一个 Python 的国际化库。
*   🌎 [Korean](korean.readthedocs.org/en/latest/)：一个韩语词态库。
*   <b><code>&nbsp;&nbsp;&nbsp;138⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [PyICU](https://github.com/ovalhub/pyicu))：一个封装了 [ICU](http://site.icu-project.org/) C++ 库的 Python 扩展。

### URL 处理

解析 URLs 的库

*   <b><code>&nbsp;&nbsp;2799⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;158🍴</code></b> [furl](https://github.com/gruns/furl))：一个让处理 URL 更简单小型 Python 库。
*   <b><code>&nbsp;&nbsp;&nbsp;303⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [purl](https://github.com/codeinthehole/purl))：一个简单的，不可变的 URL 类，具有简洁的 API 来进行询问和处理。
*   <b><code>&nbsp;&nbsp;&nbsp;406⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [pyshorteners](https://github.com/ellisonleao/pyshorteners))：一个纯 Python URL 缩短库。
*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [shorturl](https://github.com/Alir3z4/python-shorturl))：生成短小 URL 和类似 bit.ly 短链的 Python 实现。
*   <b><code>&nbsp;&nbsp;1407⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;161🍴</code></b> [webargs](https://github.com/sloria/webargs))：一个解析 HTTP 请求参数的库，内置对流行 web 框架的支持，包括 Flask, Django, Bottle, Tornado 和 Pyramid。

### HTML 处理

处理 HTML 和 XML 的库。

*   [BeautifulSoup](http://www.crummy.com/software/BeautifulSoup/bs4/doc/)：以 Python 风格的方式来对 HTML 或 XML 进行迭代，搜索和修改。
*   [bleach](http://bleach.readthedocs.org/en/latest/)：一个基于白名单的 HTML 清理和文本链接库。
*   🌎 [cssutils](pypi.python.org/pypi/cssutils/)：一个 Python 的 CSS 库。
*   <b><code>&nbsp;&nbsp;1220⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;303🍴</code></b> [html5lib](https://github.com/html5lib/html5lib-python))：一个兼容标准的 HTML 文档和片段解析及序列化库。
*   [lxml](http://lxml.de/)：一个非常快速，简单易用，功能齐全的库，用来处理 HTML 和 XML。
*   <b><code>&nbsp;&nbsp;&nbsp;685⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;178🍴</code></b> [MarkupSafe](https://github.com/pallets/markupsafe))：为 Python 实现 XML/HTML/XHTML 标记安全字符串。
*   <b><code>&nbsp;&nbsp;2381⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;186🍴</code></b> [pyquery](https://github.com/gawel/pyquery))：一个解析 HTML 的库，类似 jQuery。
*   <b><code>&nbsp;&nbsp;&nbsp;330⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [requests-html](https://github.com/kennethreitz/requests-html))：人性化的，Pythonic 的 HTML 解析库。
*   <b><code>&nbsp;&nbsp;&nbsp;632⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88🍴</code></b> [untangle](https://github.com/stchris/untangle))：将 XML 文档转换为 Python 对象，使其可以方便的访问。
*   <b><code>&nbsp;&nbsp;2383⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;654🍴</code></b> [xhtml2pdf](https://github.com/xhtml2pdf/xhtml2pdf))：HTML/CSS 转 PDF 工具。
*   <b><code>&nbsp;&nbsp;5734⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;469🍴</code></b> [xmltodict](https://github.com/martinblech/xmltodict))：像处理 JSON 一样处理 XML。
*   [WeasyPrint](http://weasyprint.org)：用于HTML和CSS的可视化呈现引擎，并可以导出为 PDF。
*   🌎 [xmldataset](xmldataset.readthedocs.io/en/latest/)：简单 XML 解析。

爬取网络站点的库

*   [Scrapy](http://scrapy.org/)：一个快速高级的屏幕爬取及网页采集框架。
*   <b><code>&nbsp;&nbsp;3400⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;587🍴</code></b> [ScrapydWeb](https://github.com/my8100/scrapydweb))：一个用于 Scrapyd 集群管理的全功能 web UI，支持 Scrapy 日志分析和可视化，自动打包，定时器任务和邮件通知等特色功能。
*   <b><code>&nbsp;&nbsp;1504⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;528🍴</code></b> [cola](https://github.com/chineking/cola))：一个分布式爬虫框架。
*   <b><code>&nbsp;&nbsp;&nbsp;118⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Demiurge](https://github.com/matiasb/demiurge))：基于 PyQuery 的爬虫微型框架。
*   [feedparser](http://pythonhosted.org/feedparser/)：通用 feed 解析器。
*   [Grab](http://grablib.org/)：站点爬取框架。
*   <b><code>&nbsp;&nbsp;4852⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;388🍴</code></b> [MechanicalSoup](https://github.com/hickford/MechanicalSoup))：用于自动和网络站点交互的 Python 库。
*   <b><code>&nbsp;&nbsp;9495⭐</code></b> <b><code>&nbsp;&nbsp;1389🍴</code></b> [portia](https://github.com/scrapinghub/portia))：Scrapy 可视化爬取。
*   <b><code>&nbsp;16886⭐</code></b> <b><code>&nbsp;&nbsp;3649🍴</code></b> [pyspider](https://github.com/binux/pyspider))：一个强大的爬虫系统。
*   <b><code>&nbsp;&nbsp;3695⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;335🍴</code></b> [RoboBrowser](https://github.com/jmcarp/robobrowser))：一个简单的，Python 风格的库，用来浏览网站，而不需要一个独立安装的浏览器。

### 网页内容提取

用于进行网页内容提取的库。

*   <b><code>&nbsp;&nbsp;&nbsp;162⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [Haul](https://github.com/vinta/Haul))：一个可以扩展的图像爬取工具。
*   <b><code>&nbsp;&nbsp;2140⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;292🍴</code></b> [html2text](https://github.com/Alir3z4/html2text))：将 HTML 转换为 Markdown 格式文本。
*   <b><code>&nbsp;&nbsp;&nbsp;629⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [lassie](https://github.com/michaelhelmick/lassie))：人性化的网页内容检索库。
*   <b><code>&nbsp;&nbsp;&nbsp;675⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [micawber](https://github.com/coleifer/micawber))：一个小型网页内容提取库，用来从 URLs 提取富内容。
*   <b><code>&nbsp;15019⭐</code></b> <b><code>&nbsp;&nbsp;2126🍴</code></b> [newspaper](https://github.com/codelucas/newspaper))：使用 Python 进行新闻提取，文章提取以及内容策展。
*   <b><code>&nbsp;&nbsp;&nbsp;233⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80🍴</code></b> [opengraph](https://github.com/erikriver/opengraph))：一个用来解析开放内容协议(Open Graph Protocol)的 Python 模块。
*   <b><code>&nbsp;&nbsp;4075⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;780🍴</code></b> [python-goose](https://github.com/grangier/python-goose))：HTML 内容/文章提取器(python2)。
*   <b><code>&nbsp;&nbsp;&nbsp;905⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;109🍴</code></b> [goose3](https://github.com/goose3/goose3))：HTML 内容/文章提取器(python3)。
*   <b><code>&nbsp;&nbsp;2895⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;353🍴</code></b> [python-readability](https://github.com/buriy/python-readability))：arc90 公司 readability 工具的 Python 高速端口。
*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [sanitize](https://github.com/Alir3z4/python-sanitize))：为杂乱的数据世界带来调理性。
*   <b><code>&nbsp;&nbsp;3672⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;543🍴</code></b> [sumy](https://github.com/miso-belica/sumy))：一个为文本文件和 HTML 页面进行自动摘要的模块。
*   <b><code>&nbsp;&nbsp;4507⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;670🍴</code></b> [textract](https://github.com/deanmalmgren/textract))：从任何格式的文档中提取文本，Word，PowerPoint，PDFs 等等。

### 表单

进行表单操作的库。

*   [Deform](http://deform.readthedocs.org/en/latest/)：Python HTML 表单生成库，受到了 formish 表单生成库的启发。
*   <b><code>&nbsp;&nbsp;2335⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;676🍴</code></b> [django-bootstrap3](https://github.com/dyve/django-bootstrap3))：集成了 Bootstrap 3 的 Django。
*   <b><code>&nbsp;&nbsp;1030⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;258🍴</code></b> [django-bootstrap4](https://github.com/zostera/django-bootstrap4))：集成了 Bootstrap 4 的 Django。
*   [django-crispy-forms](http://django-crispy-forms.readthedocs.org/en/latest/)：一个 Django 应用，他可以让你以一种非常优雅且 DRY (Don't repeat yourself) 的方式来创建美观的表单。
*   <b><code>&nbsp;&nbsp;&nbsp;220⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;110🍴</code></b> [django-remote-forms](https://github.com/WiserTogether/django-remote-forms))：一个平台独立的 Django 表单序列化工具。
*   [WTForms](http://wtforms.readthedocs.org/en/latest/)：一个灵活的表单验证和呈现库。
*   [WTForms-JSON](http://wtforms-json.readthedocs.org/en/latest/)：一个 WTForms 扩展，用来处理 JSON 数据。

### 数据验证

数据验证库。多用于表单验证。

*   [Cerberus](http://docs.python-cerberus.org/en/stable/)：一个映射验证器（mappings-validator）。支持多种规则，提供归一化功能，可以方便地定制为 Python 风格的 schema 定义。
*   [colander](http://docs.pylonsproject.org/projects/colander/en/latest/)：一个用于对从 XML, JSON，HTML 表单获取的数据或其他同样简单的序列化数据进行验证和反序列化的系统。
*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [kmatch](https://github.com/ambitioninc/kmatch))：一种用于匹配/验证/筛选 Python 字典的语言。
*   <b><code>&nbsp;&nbsp;2943⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;222🍴</code></b> [schema](https://github.com/keleshev/schema))：一个用于对 Python 数据结构进行验证的库。
*   <b><code>&nbsp;&nbsp;2589⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;292🍴</code></b> [Schematics](https://github.com/schematics/schematics))：数据结构验证。
*   <b><code>&nbsp;&nbsp;&nbsp;262⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [valideer](https://github.com/podio/valideer))：轻量级可扩展的数据验证和适配库。
*   <b><code>&nbsp;&nbsp;1847⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;221🍴</code></b> [voluptuous](https://github.com/alecthomas/voluptuous))：一个 Python 数据验证库。主要是为了验证传入 Python 的 JSON，YAML 等数据。
*   <b><code>&nbsp;&nbsp;4942⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;612🍴</code></b> [jsonschema](https://github.com/Julian/jsonschema))：[JSON Schema](http://json-schema.org/) 的 python 实现，用于 JSON 数据的验证。

### 序列化

复杂数据类型序列化相关库。

* <b><code>&nbsp;&nbsp;7230⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;686🍴</code></b> [marshmallow](https://github.com/marshmallow-code/marshmallow))：一个轻量级的库，用于将复杂对象与简单 Python 数据类型相互转换。
* <b><code>&nbsp;&nbsp;&nbsp;762⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63🍴</code></b> [pysimdjson](https://github.com/TkTech/pysimdjson))：与 Python 绑定的 <b><code>&nbsp;23628⭐</code></b> <b><code>&nbsp;&nbsp;1237🍴</code></b> [simdjson](https://github.com/lemire/simdjson)) 。
* <b><code>&nbsp;&nbsp;&nbsp;533⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [python-rapidjson](https://github.com/python-rapidjson/python-rapidjson))： <b><code>&nbsp;15032⭐</code></b> <b><code>&nbsp;&nbsp;3640🍴</code></b> [RapidJSON](https://github.com/Tencent/rapidjson)) 的 Python 封装。
* <b><code>&nbsp;&nbsp;4484⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;380🍴</code></b> [ultrajson](https://github.com/esnme/ultrajson))：使用 Python 绑定的，用 C 编写的快速 JSON 解码器和编码器。

### 反垃圾技术

帮助你和电子垃圾进行战斗的库。

*   <b><code>&nbsp;&nbsp;1427⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;326🍴</code></b> [django-simple-captcha](https://github.com/mbi/django-simple-captcha))：一个简单、高度可定制的 Django 应用，可以为任何 Django 表单添加验证码。
*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [django-simple-spam-blocker](https://github.com/moqada/django-simple-spam-blocker))：一个用于 Django 的简单的电子垃圾屏蔽工具。

### 标记

用来进行标记的库。

*   <b><code>&nbsp;&nbsp;3431⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;623🍴</code></b> [django-taggit](https://github.com/alex/django-taggit))：简单的 Django 标记工具。

### 管理面板

管理界面库。

*   <b><code>&nbsp;&nbsp;7914⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;868🍴</code></b> [Ajenti](https://github.com/ajenti/ajenti))：一个你的服务器值得拥有的管理面板。
*   [django-suit](http://djangosuit.com/)：Django 管理界面的一个替代品（仅对于非商业用途是免费的）。
*   <b><code>&nbsp;&nbsp;4763⭐</code></b> <b><code>&nbsp;&nbsp;1390🍴</code></b> [django-xadmin](https://github.com/sshwsfc/django-xadmin))：Django admin 的一个替代品，具有很多不错的功能。
*   <b><code>&nbsp;&nbsp;6058⭐</code></b> <b><code>&nbsp;&nbsp;1632🍴</code></b> [flask-admin](https://github.com/flask-admin/flask-admin))：一个用于 Flask 的简单可扩展的管理界面框架。
*   <b><code>&nbsp;&nbsp;7147⭐</code></b> <b><code>&nbsp;&nbsp;1140🍴</code></b> [flower](https://github.com/mher/flower))：一个对 Celery 集群进行实时监控和提供 web 管理界面的工具。
*   [Grappelli](http://grappelliproject.com/)：Django 管理界面的一个漂亮的皮肤。
*   <b><code>&nbsp;&nbsp;2218⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;185🍴</code></b> [Wooey](https://github.com/wooey/wooey))：一个 Django 应用，可以为 Python 脚本创建 web 用户界面。
*   🌎 [django-grappelli](grappelliproject.com/)：拥有绚丽外观的 Django Admin 界面。
*   <b><code>&nbsp;&nbsp;3629⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;772🍴</code></b> [django-jet](https://github.com/geex-arts/django-jet))：具有改进功能的现代响应式 Django 管理界面模板。
* <b><code>&nbsp;&nbsp;1796⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;169🍴</code></b> [jet-bridge](https://github.com/jet-admin/jet-bridge))：管理面板框架，适用于任何具有良好 UI 的应用（例如 Django）。

### Serverless 框架

使用 Python 开发 Serverless 模型相关的库。

* <b><code>&nbsp;&nbsp;1518⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;225🍴</code></b> [python-lambda](https://github.com/nficano/python-lambda)) ：在 AWS Lambda 开发和部署 Python 代码的工具包。
* <b><code>&nbsp;11845⭐</code></b> <b><code>&nbsp;&nbsp;1175🍴</code></b> [Zappa](https://github.com/Miserlou/Zappa))：在 AWS Lambda 和 API Gateway 部署 WSGI 应用的工具。

### 静态站点生成器

静态站点生成器是一个软件，它把文本和模板作为输入，然后输出 HTML 文件。

*   [Pelican](http://blog.getpelican.com/)：使用 Markdown 或 ReST 来处理内容， Jinja 2 来制作主题。支持 DVCS, Disqus.。AGPL 许可。
*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Cactus](https://github.com/koenbok/Cactus/))：为设计师设计的静态站点生成器。
*   [Hyde](http://hyde.github.io/)：基于 Jinja2 的静态站点生成器。
*   🌎 [Nikola](www.getnikola.com/)：一个静态网站和博客生成器。
*   [Tinkerer](http://tinkerer.me/)：Tinkerer 是一个博客引擎/静态站点生成器，由 Sphinx 驱动。
*   🌎 [Lektor](www.getlektor.com/)：一个简单易用的静态 CMS 和博客引擎。
*   <b><code>&nbsp;&nbsp;1871⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;306🍴</code></b> [makesite](https://github.com/sunainapai/makesite))：简单轻量的站点/博客生成器（小于 130 行代码）。

### 进程

操作系统进程启动及通信库。

*   <b><code>&nbsp;&nbsp;2263⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;252🍴</code></b> [envoy](https://github.com/kennethreitz/envoy))：比 Python 🌎 [subprocess](docs.python.org/2/library/subprocess.html) 模块更人性化。
*   [sarge](http://sarge.readthedocs.org/en/latest/)：另一 种 subprocess 模块的封装。
*   <b><code>&nbsp;&nbsp;7234⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;504🍴</code></b> [sh](https://github.com/amoffat/sh))：一个完备的 subprocess 替代库。
*   <b><code>&nbsp;&nbsp;1746⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88🍴</code></b> [delegator.py](https://github.com/amitt001/delegator.py))：人性化的 🌎 [Subprocesses](docs.python.org/3/library/subprocess.html) 2.0 版本。

### 并发和并行

用以进行并发和并行操作的库。

*   🌎 [multiprocessing](docs.python.org/2/library/multiprocessing.html)：(Python 标准库) 基于进程的“线程”接口。
*   🌎 [threading](docs.python.org/2/library/threading.html)：(Python 标准库)更高层的线程接口。
*   [eventlet](http://eventlet.net/)：支持 WSGI 的异步框架。
*   [gevent](http://www.gevent.org/)：一个基于协程的 Python 网络库，使用 <b><code>&nbsp;&nbsp;1820⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;266🍴</code></b> [greenlet](https://github.com/python-greenlet/greenlet))。
*   <b><code>&nbsp;&nbsp;1452⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96🍴</code></b> [Tomorrow](https://github.com/madisonmay/Tomorrow))：用于产生异步代码的神奇的装饰器语法实现。
*   <b><code>&nbsp;11746⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;606🍴</code></b> [uvloop](https://github.com/MagicStack/uvloop))：在 libuv 之上超快速实现 asyncio 事件循环。
*   🌎 [concurrent.futures](docs.python.org/3/library/concurrent.futures.html)：(Python 标准库) 异步执行可调用对象的高级接口。
*   [gevent](http://www.gevent.org/)：使用 <b><code>&nbsp;&nbsp;1820⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;266🍴</code></b> [greenlet](https://github.com/python-greenlet/greenlet)) 且基于协程的 Python 网络库。
*   <b><code>&nbsp;&nbsp;&nbsp;660⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86🍴</code></b> [scoop](https://github.com/soravux/scoop))：支持在 Python 中进行可伸缩并行操作。

### 网络

用于网络编程的库。

*   🌎 [asyncio](docs.python.org/3/library/asyncio.html)：(Python 标准库) 异步 I/O，事件循环，协程以及任务。
*   <b><code>&nbsp;&nbsp;7238⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;395🍴</code></b> [trio](https://github.com/python-trio/trio))：异步并发和 I/O 友好的库。
*   🌎 [Twisted](twistedmatrix.com/trac/)：一个事件驱动的网络引擎。
*   <b><code>&nbsp;&nbsp;1853⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;158🍴</code></b> [pulsar](https://github.com/quantmind/pulsar))：事件驱动的并发框架。
*   <b><code>&nbsp;&nbsp;&nbsp;581⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [diesel](https://github.com/dieseldev/diesel))：基于 Greenlet 的事件 I/O 框架。
*   [pyzmq](http://zeromq.github.io/pyzmq/)：一个 ZeroMQ 消息库的 Python 封装。
*   <b><code>&nbsp;&nbsp;3553⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;237🍴</code></b> [Toapi](https://github.com/gaojiuli/toapi))：一个轻巧，简单，快速的 Flask 库，致力于为所有网站提供 API 服务。
*   <b><code>&nbsp;&nbsp;&nbsp;150⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55🍴</code></b> [txZMQ](https://github.com/smira/txZMQ))：基于 Twisted 的 ZeroMQ 消息库的 Python 封装。

### WebSocket

帮助使用 WebSocket 的库。

*   <b><code>&nbsp;&nbsp;2536⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;767🍴</code></b> [AutobahnPython](https://github.com/crossbario/autobahn-python))：给 Python、使用的 WebSocket & WAMP 基于 Twisted 和 🌎 [asyncio](docs.python.org/3/library/asyncio.html)。
*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Crossbar](https://github.com/crossbario/crossbar/))：开源统一应用路由(Websocket & WAMP for Python on Autobahn)。
*   <b><code>&nbsp;&nbsp;1318⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;241🍴</code></b> [django-socketio](https://github.com/stephenmcd/django-socketio))：给 Django 用的 WebSockets。
*   <b><code>&nbsp;&nbsp;1129⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;285🍴</code></b> [WebSocket-for-Python](https://github.com/Lawouach/WebSocket-for-Python))：为 Python2/3 以及 PyPy 编写的 WebSocket 客户端和服务器库。

### WSGI 服务器

兼容 WSGI 的 web 服务器

*   🌎 [gunicorn](pypi.python.org/pypi/gunicorn)：Pre-forked, 部分是由 C 语言编写的。
*   🌎 [uwsgi](uwsgi-docs.readthedocs.org/en/latest/)：uwsgi 项目的目的是开发一组全栈工具，用来建立托管服务，由 C 语言编写。
*   🌎 [bjoern](pypi.python.org/pypi/bjoern)：异步，非常快速，由 C 语言编写。
*   [fapws3](http://www.fapws.org/)：异步 (仅对于网络端)，由 C 语言编写。
*   🌎 [meinheld](pypi.python.org/pypi/meinheld)：异步，部分是由 C 语言编写的。
*   <b><code>&nbsp;&nbsp;&nbsp;119⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [netius](https://github.com/hivesolutions/netius))：异步，非常快速。
*   [paste](http://pythonpaste.org/)：多线程，稳定，久经考验。
*   🌎 [rocket](pypi.python.org/pypi/rocket)：多线程。
*   🌎 [waitress](waitress.readthedocs.org/en/latest/)：多线程，是它驱动着 Pyramid 框架。
*   [Werkzeug](http://werkzeug.pocoo.org/)：一个 WSGI 工具库，驱动着 Flask，而且可以很方便大嵌入到你的项目中去。

### ASGI 服务器

兼容 ASGI 的 web 服务器。

* <b><code>&nbsp;&nbsp;2659⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;287🍴</code></b> [daphne](https://github.com/django/daphne))：用于 ASGI 和 ASGI-HTTP 的，支持 HTTP，HTTP2 和 WebSocket 协议的服务器。
* <b><code>&nbsp;10584⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;932🍴</code></b> [uvicorn](https://github.com/encode/uvicorn))：使用 uvloop 和 httptools 实现的闪电般快速的 ASGI 服务器。

### RPC 服务器

兼容 RPC 的服务器。

*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [SimpleJSONRPCServer](https://github.com/joshmarshall/jsonrpclib/))：这个库是 JSON-RPC 规范的一个实现。
*   🌎 [SimpleXMLRPCServer](docs.python.org/2/library/simplexmlrpcserver.html)：(Python 标准库) 简单的 XML-RPC 服务器实现，单线程。
*   <b><code>&nbsp;&nbsp;3234⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;382🍴</code></b> [zeroRPC](https://github.com/0rpc/zerorpc-python))：zerorpc 是一个灵活的 RPC 实现，基于 [ZeroMQ](http://zeromq.org/) 和 [MessagePack](http://msgpack.org/)。
*   <b><code>&nbsp;&nbsp;1694⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;249🍴</code></b> [RPyC](https://github.com/tomerfiliba/rpyc)) (Remote Python Call)：适用于 Python 的透明且对称的RPC库。

### 密码学

*   🌎 [cryptography](cryptography.io/en/latest/)：这个软件包意在提供密码学基本内容和方法提供给 Python 开发者。
*   <b><code>&nbsp;&nbsp;1420⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;104🍴</code></b> [hashids](https://github.com/davidaurelio/hashids-python))：在 Python 中实现 [hashids](http://hashids.org/) 。
*   [Paramiko](http://www.paramiko.org/)：SSHv2 协议的 Python (2.6+, 3.3+) ，提供客户端和服务端的功能。
*   🌎 [Passlib](pythonhosted.org/passlib/)：安全密码存储／哈希库。
*   🌎 [PyCrypto](www.dlitz.net/software/pycrypto/)：Python 密码学工具箱。
*   <b><code>&nbsp;&nbsp;1189⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;255🍴</code></b> [PyNacl](https://github.com/pyca/pynacl))：网络和密码学(NaCl) 库的 Python 绑定。

### 图形用户界面

用来创建图形用户界面程序的库。

*   🌎 [curses](docs.python.org/2/library/curses.html#module-curses)：内建的 [ncurses](http://www.gnu.org/software/ncurses/) 封装，用来创建终端图形用户界面。
*   <b><code>&nbsp;&nbsp;1576⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;132🍴</code></b> [enaml](https://github.com/nucleic/enaml))：使用类似 QML 的 Declaratic 语法来创建美观的用户界面。
*   🌎 [kivy](kivy.org/)：一个用来创建自然用户交互（NUI）应用程序的库，可以运行在 Windows, Linux, Mac OS X, Android 以及 iOS 平台上。
*   🌎 [pyglet](bitbucket.org/pyglet/pyglet/wiki/Home)：一个 Python 的跨平台窗口及多媒体库。
*   🌎 [PyQt](riverbankcomputing.com/software/pyqt/intro)：跨平台用户界面框架 [Qt](http://www.qt.io/) 的 Python 绑定 ，支持 Qt v4 和 Qt v5。
*   🌎 [PySide](wiki.qt.io/PySide)：跨平台用户界面框架 [Qt](http://www.qt.io/) 的 Python 绑定 ，支持 Qt v4。
*   🌎 [Tkinter](wiki.python.org/moin/TkInter)：Tkinter 是 Python GUI 的一个事实标准库。
*   <b><code>&nbsp;&nbsp;5335⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;797🍴</code></b> [Toga](https://github.com/pybee/toga))：一个 Python 原生的，操作系统原生的 GUI 工具包。
*   [urwid](http://urwid.org/)：一个用来创建终端 GUI 应用的库，支持组件，事件和丰富的色彩等。
*   [wxPython](http://wxpython.org/)：wxPython 是 wxWidgets C++ 类库和 Python 语言混合的产物。
*   🌎 [PyGObject](wiki.gnome.org/Projects/PyGObject)：GLib/GObject/GIO/GTK+ (GTK+3) 的 Python 绑定。
*   <b><code>&nbsp;&nbsp;3341⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;259🍴</code></b> [Flexx](https://github.com/zoofIO/flexx))：Flexx 是一个纯 Python 语言编写的用来创建 GUI 程序的工具集，它使用 web 技术进行界面的展示。
*   <b><code>&nbsp;&nbsp;6749⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;608🍴</code></b> [Eel](https://github.com/ChrisKnott/Eel))：用于制作简单离线 HTML/JS GUI 应用的库。
*   <b><code>&nbsp;13699⭐</code></b> <b><code>&nbsp;&nbsp;1825🍴</code></b> [PySimpleGUI](https://github.com/PySimpleGUI/PySimpleGUI))：tkinter，Qt，WxPython 和 Remi 的封装。
*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [pywebview](https://github.com/r0x0r/pywebview/))：围绕网页视图组件的轻量级跨平台的原生包装。
*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [DearPyGui](https://github.com/RaylockLLC/DearPyGui/))：一个简单的可使用 GPU 加速的 Python GUI 框架。

### 游戏开发

超赞的游戏开发库。

*   [Cocos2d](http://cocos2d.org/)：cocos2d 是一个用来开发 2D 游戏， 示例和其他图形/交互应用的框架。基于 pyglet。
*   🌎 [Panda3D](www.panda3d.org/)：由迪士尼开发的 3D 游戏引擎，并由卡内基梅陇娱乐技术中心负责维护。使用 C++ 编写, 针对 Python 进行了完全的封装。
*   [Pygame](http://www.pygame.org/news.html)：Pygame 是一组 Python 模块，用来编写游戏。
*   [PyOgre](http://www.ogre3d.org/tikiwiki/PyOgre)：Ogre 3D 渲染引擎的 Python 绑定，可以用来开发游戏和仿真程序等任何 3D 应用。
*   [PyOpenGL](http://pyopengl.sourceforge.net/)：OpenGL 的 Python 绑定及其相关 APIs。
*   [PySDL2](http://pysdl2.readthedocs.org/en/latest/)：SDL2 库的封装，基于 ctypes。
*   🌎 [RenPy](www.renpy.org/)：一个视觉小说（visual novel）引擎。
*   🌎 [Arcade](arcade.academy/index.html)：一个现代 Python 框架，用于制作具有引人入胜的图形与声音的游戏。
*   [Harfang3D](http://www.harfang3d.com)：支持3D，VR 与游戏开发的 Python 框架。

### 日志

用来生成和操作日志的库。

*   🌎 [logging](docs.python.org/2/library/logging.html)：(Python 标准库) 为 Python 提供日志功能。
*   [logbook](http://pythonhosted.org/Logbook/)：Logging 库的替代品。
*   🌎 [Eliot](eliot.readthedocs.org/en/latest/)：为复杂的和分布式系统创建日志。
*   [Raven](http://raven.readthedocs.org/en/latest/)：Sentry 的 Python 客户端。
*   🌎 [Sentry](pypi.python.org/pypi/sentry)：实时记录和收集日志的服务器。
*   <b><code>&nbsp;&nbsp;2166⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;603🍴</code></b> [sentry-python](https://github.com/getsentry/sentry-python))：Python 版 Sentry SDK。
*   <b><code>&nbsp;23798⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;784🍴</code></b> [loguru](https://github.com/Delgan/loguru))：旨在带来愉悦体验的 Python 日志库。
*   🌎 [structlog](www.structlog.org/en/stable/)：结构化日志，让日志变得简单。

### 测试

进行代码库测试和生成测试数据的库。

*   测试框架
    *   🌎 [unittest](docs.python.org/2/library/unittest.html)：(Python 标准库) 单元测试框架。
    *   🌎 [nose](nose.readthedocs.org/en/latest/)：nose 扩展了 unittest 的功能。
    *   <b><code>&nbsp;&nbsp;&nbsp;824⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;135🍴</code></b> [nose2](https://github.com/nose-devs/nose2)) `nose`的继任者，基于 `unittest2`。
    *   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [contexts](https://github.com/benjamin-hodgson/Contexts))：一个 Python 3.3+ 的 BDD 框架。受到 C#  Machine.Specifications 的启发。
    *   <b><code>&nbsp;&nbsp;8571⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;640🍴</code></b> [hypothesis](https://github.com/DRMacIver/hypothesis))：Hypothesis 是一个基于先进的 Quickcheck 风格特性的测试库。
    *   [mamba](http://nestorsalceda.github.io/mamba/)：Python 的终极测试工具， 拥护 BDD。
    *   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [pyshould](https://github.com/drslump/pyshould))：Should 风格的断言，基于 <b><code>&nbsp;&nbsp;&nbsp;804⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [PyHamcrest](https://github.com/hamcrest/PyHamcrest))。
    *   [pytest](http://pytest.org/latest/)：一个成熟的全功能 Python 测试工具。
    *   <b><code>&nbsp;&nbsp;&nbsp;804⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [green](https://github.com/CleanCut/green))：干净，多彩的测试工具。
    *   [pyvows](http://heynemann.github.io/pyvows/)：BDD 风格的测试工具，受 Vows.js 的启发。
    *   <b><code>&nbsp;11549⭐</code></b> <b><code>&nbsp;&nbsp;2538🍴</code></b> [Robot Framework](https://github.com/robotframework/robotframework))：一个通用的自动化测试框架。
    *   🌎 [tox](tox.readthedocs.io/en/latest/)：自动化测试与发布的工具，支持多个 Python 版本。
*   GUI / Web 测试
    *   🌎 [Selenium](pypi.python.org/pypi/selenium)：[Selenium](http://www.seleniumhq.org/) WebDriver 的 Python 绑定。
    *   <b><code>&nbsp;12418⭐</code></b> <b><code>&nbsp;&nbsp;1405🍴</code></b> [PyAutoGUI](https://github.com/asweigart/pyautogui))：PyAutoGUI 是一个人性化的跨平台 GUI 自动测试模块。
    *   <b><code>&nbsp;27696⭐</code></b> <b><code>&nbsp;&nbsp;3196🍴</code></b> [locust](https://github.com/locustio/locust))：使用 Python 编写的，可扩展的用户加载测试工具。
    *   <b><code>&nbsp;&nbsp;1760⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;178🍴</code></b> [sixpack](https://github.com/seatgeek/sixpack))：一个和语言无关的 A/B 测试框架。
    *   🌎 [splinter](splinter.readthedocs.org/en/latest/)：开源的 web 应用测试工具。
    *   <b><code>&nbsp;&nbsp;3211⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;204🍴</code></b> [Schemathesis](https://github.com/kiwicom/schemathesis))：基于属性的自动测试工具，用于测试使用 Open API / Swagger 规范构建的 Web 应用程序。
*   Mock 测试
    *   🌎 [mock](docs.python.org/3/library/unittest.mock.html)：(Python 标准库) 一个用于伪造测试的库。
    *   🌎 [doublex](pypi.python.org/pypi/doublex)：Python 的一个功能强大的 doubles 测试框架。
    *   <b><code>&nbsp;&nbsp;4499⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;295🍴</code></b> [freezegun](https://github.com/spulec/freezegun))：通过伪造日期模块来生成不同的时间。
    *   <b><code>&nbsp;&nbsp;&nbsp;472⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [httmock](https://github.com/patrys/httmock))：针对 Python 2.6+ 和 3.2+ 生成 伪造请求的库。
    *   [httpretty](http://falcao.it/HTTPretty/)：Python 的 HTTP 请求 mock 工具。
    *   <b><code>&nbsp;&nbsp;4338⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;364🍴</code></b> [responses](https://github.com/getsentry/responses))：伪造 Python 中的 requests 库的一个通用库。
    *   <b><code>&nbsp;&nbsp;2956⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;424🍴</code></b> [VCR.py](https://github.com/kevin1024/vcrpy))：在你的测试中记录和重放 HTTP 交互。
    *   <b><code>&nbsp;&nbsp;&nbsp;309⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [mocket](https://github.com/mindflayer/python-mocket))：gevent/asyncio/SSL 支持的 socket mock 框架。
*   对象工厂
    *   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [factoryboy](https://github.com/rbarrois/factoryboy))：一个 Python 用的测试固件 (test fixtures) 替代库。
    *   <b><code>&nbsp;&nbsp;&nbsp;955⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94🍴</code></b> [mixer](https://github.com/klen/mixer))：另外一个测试固件 (test fixtures) 替代库，支持 Django, Flask, SQLAlchemy, Peewee 等。
    *   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [modelmommy](https://github.com/vandersonmota/modelmommy))：为 Django 测试创建随机固件。
*   代码覆盖率
    *   🌎 [coverage](pypi.python.org/pypi/coverage)：代码覆盖率测量。
    *   🌎 [Codecov](codecov.io/)：一个代码覆盖率测试工具，为开源项目提供免费代码覆盖率测试服务。
*   伪数据
    *   [faker](http://www.joke2k.net/faker/)：一个 Python 库，用来生成伪数据。
    *   <b><code>&nbsp;&nbsp;2350⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;123🍴</code></b> [fake2db](https://github.com/emirozer/fake2db))：伪数据库生成器。
    *   <b><code>&nbsp;&nbsp;4797⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;359🍴</code></b> [mimesis](https://github.com/lk-geimfari/mimesis))：一个帮助你生成伪数据的 Python 库。
    *   🌎 [radar](pypi.python.org/pypi/radar)：生成随机的日期/时间。
*   错误处理
    *   <b><code>&nbsp;&nbsp;5287⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;178🍴</code></b> [FuckIt.py](https://github.com/ajalt/fuckitpy))：使用最先进的技术来保证你的 Python 代码无论对错都能继续运行。

### 渗透测试

渗透测试相关框架和工具。

* <b><code>&nbsp;11975⭐</code></b> <b><code>&nbsp;&nbsp;2104🍴</code></b> [fsociety](https://github.com/Manisso/fsociety))：一款渗透测试框架。
* <b><code>&nbsp;14768⭐</code></b> <b><code>&nbsp;&nbsp;3332🍴</code></b> [setoolkit](https://github.com/trustedsec/social-engineer-toolkit))：社会工程工具包。
* <b><code>&nbsp;37051⭐</code></b> <b><code>&nbsp;&nbsp;6239🍴</code></b> [sqlmap](https://github.com/sqlmapproject/sqlmap))：自动 SQL 注入和数据库接管工具。

### 代码分析和 Lint 工具

进行代码分析、解析和操作代码库的库和工具。

*   代码分析
    *   [coala](http://coala-analyzer.org/)：语言独立和易于扩展的代码分析应用程序。
    *   <b><code>&nbsp;&nbsp;4558⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;327🍴</code></b> [code2flow](https://github.com/scottrogowski/code2flow))：把你的 Python 和 JavaScript 代码转换为流程图。
    *   <b><code>&nbsp;&nbsp;1868⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;344🍴</code></b> [pycallgraph](https://github.com/gak/pycallgraph))：这个库可以把你的 Python 应用的流程(调用图)进行可视化。
    *   <b><code>&nbsp;&nbsp;1426⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;502🍴</code></b> [pysonar2](https://github.com/yinwang0/pysonar2))：Python 类型推断和检索工具。
    *   <b><code>&nbsp;&nbsp;2075⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;180🍴</code></b> [prospector](https://github.com/PyCQA/prospector))：分析 Python 代码的工具。
    *   <b><code>&nbsp;&nbsp;4515⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;182🍴</code></b> [vulture](https://github.com/jendrikseipp/vulture))：用于发现和分析无效 Python 代码的工具。
    
* Lint 工具
  *   🌎 [Flake8](pypi.python.org/pypi/flake8)：模块化源码检查工具，提供与 `pycodestyle`、`pyflakes` 、McCabe 相关的装饰器。
      * <b><code>&nbsp;&nbsp;1273⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [awesome-flake8-extensions](https://github.com/DmytroLitvinov/awesome-flake8-extensions))

  *   🌎 [Pylint](www.pylint.org/)：一个完全可定制的源码分析器。
  *   <b><code>&nbsp;13982⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;901🍴</code></b> [YAPF](https://github.com/google/yapf))：Google 的 Python 代码格式化工具。
  *   🌎 [pylama](pylama.readthedocs.org/en/latest/)：Python 和 JavaScript 的代码审查工具。
  *   <b><code>&nbsp;&nbsp;2837⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;419🍴</code></b> [wemake-python-styleguide](https://github.com/wemake-services/wemake-python-styleguide))：有史以来最严格的 Python 代码审查工具。

*   代码格式化
    *   <b><code>&nbsp;&nbsp;4667⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;288🍴</code></b> [autopep8](https://github.com/hhatto/autopep8))：自动格式化 Python 代码，以使其符合 PEP8 规范。
    *   <b><code>&nbsp;41460⭐</code></b> <b><code>&nbsp;&nbsp;2756🍴</code></b> [black](https://github.com/ambv/black))：一个坚定的 Python 代码格式化工具。
    *   <b><code>&nbsp;&nbsp;6927⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;624🍴</code></b> [isort](https://github.com/timothycrosley/isort))：用于纠正包导入顺序的 Python 库。
    
*   静态类型检查，也可以参考 <b><code>&nbsp;&nbsp;1954⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [awesome-python-typing](https://github.com/typeddjango/awesome-python-typing))

    * [mypy](http://mypy-lang.org/)：在编译期间检查变量类型。
    * <b><code>&nbsp;&nbsp;7151⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;449🍴</code></b> [pyre-check](https://github.com/facebook/pyre-check))：性能类型检查。
    * <b><code>&nbsp;&nbsp;5042⭐</code></b> <b><code>&nbsp;&nbsp;1997🍴</code></b> [typeshed](https://github.com/python/typeshed))：带有静态类型的Python库存根的集合。

*   静态类型注释生成器

    * <b><code>&nbsp;&nbsp;5001⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;201🍴</code></b> [MonkeyType](https://github.com/Instagram/MonkeyType))：通过收集运行时的类型来为 Python 生成静态类型注释的系统。
    * <b><code>&nbsp;&nbsp;1447⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [pyannotate](https://github.com/dropbox/pyannotate))：自动生成符合 PEP-484 的注解。
    * <b><code>&nbsp;&nbsp;5030⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;291🍴</code></b> [pytype](https://github.com/google/pytype))：检查和推断 Python 代码中的类型，无需添加注解。

### 调试工具

用来进行代码调试的库。

*   调试器
    *   🌎 [ipdb](pypi.python.org/pypi/ipdb)：IPython 启用的 🌎 [pdb](docs.python.org/2/library/pdb.html)。
    *   🌎 [pudb](pypi.python.org/pypi/pudb)：全屏，基于控制台的 Python 调试器。
    *   <b><code>&nbsp;&nbsp;1457⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [pdb++](https://github.com/antocuni/pdb))：另一种 pdb 的替代。
    *   <b><code>&nbsp;&nbsp;1630⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [pyringe](https://github.com/google/pyringe))：可以在 Python 进程中附加和注入代码的调试器。
    *   <b><code>&nbsp;&nbsp;1593⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;120🍴</code></b> [wdb](https://github.com/Kozea/wdb))：一个奇异的 web 调试器，通过 WebSockets 工作。
    *   [winpdb](http://winpdb.org/)：一个具有图形用户界面的 Python 调试器，可以进行远程调试，基于 rpdb2。
*   追踪器
    * <b><code>&nbsp;&nbsp;&nbsp;703⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [lptrace](https://github.com/khamidou/lptrace))：为 Python 程序打造的 [strace](http://man7.org/linux/man-pages/man1/strace.1.html)。
    * <b><code>&nbsp;&nbsp;&nbsp;402⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [manhole](https://github.com/ionelmc/python-manhole))：调试UNIX套接字连接，并显示所有线程的堆栈跟踪和交互式提示。
    * <b><code>&nbsp;&nbsp;1630⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [pyringe](https://github.com/google/pyringe))：能够附加到 Python 进程并将代码注入Python进程的调试器。
    * <b><code>&nbsp;&nbsp;&nbsp;864⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [python-hunter](https://github.com/ionelmc/python-hunter))：一个灵活的代码追踪工具包。

*   性能分析器
    *   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [lineprofiler](https://github.com/rkern/lineprofiler))：逐行性能分析。
    *   [Memory Profiler](http://pypi.python.org/pypi/memory_profiler)、<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [内存](https://github.com/fabianp/memoryprofiler))：监控 Python 代码的内存使用。
    *   <b><code>&nbsp;&nbsp;2940⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;112🍴</code></b> [profiling](https://github.com/what-studio/profiling))：一个交互式 Python 性能分析工具。
    *   <b><code>&nbsp;15097⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;507🍴</code></b> [py-spy](https://github.com/benfred/py-spy))：Python 程序采样分析器，使用 Rust 实现。
    *   <b><code>&nbsp;&nbsp;2987⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;242🍴</code></b> [pyflame](https://github.com/uber/pyflame))：用于 Python 的跟踪分析器。
    *   <b><code>&nbsp;&nbsp;3980⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;151🍴</code></b> [vprof](https://github.com/nvdv/vprof))：视觉 Python 分析器。
*   其他
    *   <b><code>&nbsp;&nbsp;2229⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;536🍴</code></b> [pyelftools](https://github.com/eliben/pyelftools))：解析和分析 ELF 文件以及 DWARF 调试信息。
    *   <b><code>&nbsp;&nbsp;&nbsp;111⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [python-statsd](https://github.com/WoLpH/python-statsd))：<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [statsd](https://github.com/etsy/statsd/)) 服务器的 Python 客户端。
    *   <b><code>&nbsp;&nbsp;8349⭐</code></b> <b><code>&nbsp;&nbsp;1083🍴</code></b> [django-debug-toolbar](https://github.com/django-debug-toolbar/django-debug-toolbar))：为 Django 显示各种调试信息。
    *   <b><code>&nbsp;&nbsp;1265⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;155🍴</code></b> [django-devserver](https://github.com/dcramer/django-devserver))：一个 Django 运行服务器的替代品。
    *   <b><code>&nbsp;&nbsp;&nbsp;978⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;149🍴</code></b> [flask-debugtoolbar](https://github.com/mgood/flask-debugtoolbar))：django-debug-toolbar 的 flask 版。
    *   <b><code>&nbsp;10036⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;217🍴</code></b> [icecream](https://github.com/gruns/icecream))：通过一个简单的函数调用检查变量、表达式和程序执行情况。

### 科学计算和数据分析

用来进行科学计算和数据分析的库。

*   [astropy](http://www.astropy.org/)：一个天文学 Python 库。
*   <b><code>&nbsp;&nbsp;1029⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;355🍴</code></b> [bcbio-nextgen](https://github.com/chapmanb/bcbio-nextgen))：这个工具箱为全自动高通量测序分析提供符合最佳实践的处理流程。
*   <b><code>&nbsp;&nbsp;&nbsp;644⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;243🍴</code></b> [bccb](https://github.com/chapmanb/bcbb))：生物分析相关代码集合。
*   [Biopython](http://biopython.org/wiki/MainPage)：Biopython 是一组可以免费使用的用来进行生物计算的工具。
*   [blaze](http://blaze.readthedocs.org/en/latest/index.html)：NumPy 和 Pandas 的大数据接口。
*   [cclib](http://cclib.github.io/)：一个用来解析和解释计算化学软件包输出结果的库。
*   🌎 [NetworkX](networkx.github.io/)：一个为复杂网络设计的高性能软件。
*   [Neupy](http://neupy.com/pages/home.html)：执行和测试各种不同的人工神经网络算法。
*   [NumPy](http://www.numpy.org/)：使用 Python 进行科学计算的基础包。
*   [Open Babel](http://openbabel.org/wiki/MainPage)：一个化学工具箱，用来描述多种化学数据。
*   <b><code>&nbsp;&nbsp;1283⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;236🍴</code></b> [Open Mining](https://github.com/mining/mining))：使用 Python 挖掘商业情报 (BI) (Pandas web 接口)。
*   [orange](http://orange.biolab.si/)：通过可视化编程或 Python 脚本进行数据挖掘，数据可视化，分析和机器学习。
*   [Pandas](http://pandas.pydata.org/)：提供高性能，易用的数据结构和数据分析工具。
*   [PyDy](http://www.pydy.org/)：PyDy 是 Python Dynamics 的缩写，用来为动力学运动建模工作流程提供帮助， 基于 NumPy, SciPy, IPython 和 matplotlib。
*   <b><code>&nbsp;&nbsp;9572⭐</code></b> <b><code>&nbsp;&nbsp;2244🍴</code></b> [PyMC](https://github.com/pymc-devs/pymc3))：马尔科夫链蒙特卡洛采样工具。
*   [RDKit](http://www.rdkit.org/)：化学信息学和机器学习软件。
*   [SciPy](http://www.scipy.org/)：由一些基于 Python ，用于数学，科学和工程的开源软件构成的生态系统。
*   <b><code>&nbsp;11355⭐</code></b> <b><code>&nbsp;&nbsp;3325🍴</code></b> [statsmodels](https://github.com/statsmodels/statsmodels))：统计建模和计量经济学。
*   <b><code>&nbsp;14561⭐</code></b> <b><code>&nbsp;&nbsp;5261🍴</code></b> [SymPy](https://github.com/sympy/sympy))：一个用于符号数学的 Python 库。
*   <b><code>&nbsp;19621⭐</code></b> <b><code>&nbsp;&nbsp;4961🍴</code></b> [zipline](https://github.com/quantopian/zipline))：一个 Python 算法交易库。
*   <b><code>&nbsp;&nbsp;1140⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;256🍴</code></b> [Bayesian-belief-networks](https://github.com/eBay/bayesian-belief-networks))：优雅的贝叶斯理念网络框架。
*   <b><code>&nbsp;&nbsp;4105⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;724🍴</code></b> [AWS Data Wrangler](https://github.com/awslabs/aws-data-wrangler))：AWS 平台上使用的 Pandas。
*   <b><code>&nbsp;&nbsp;1536⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;232🍴</code></b> [Optimus](https://github.com/ironmussa/Optimus))：在使用 PySpark 时，让敏捷数据科学工作流程变得简单。
*   [Colour](http://colour-science.org/)：大量色彩理论转换和算法的实现。
*   <b><code>&nbsp;&nbsp;2275⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;257🍴</code></b> [Karate Club](https://github.com/benedekrozemberczki/karateclub))：用于图形结构化数据的无监督机器学习工具箱。
*   [NIPY](http://nipy.org)：神经影响学工具箱集合。
*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [ObsPy](https://github.com/obspy/obspy/wiki/))：地震学 Python 工具箱。
*   [QuTiP](http://qutip.org/)：Python 版 Quantum 工具箱。
*   🌎 [SimPy](gitlab.com/team-simpy/simpy)：一个基于过程的离散事件模拟框架。

### 数据可视化

进行数据可视化的库。 参见：<b><code>&nbsp;34923⭐</code></b> <b><code>&nbsp;&nbsp;4531🍴</code></b> [awesome-javascript](https://github.com/sorrycc/awesome-javascript#data-visualization))。

*   [matplotlib](http://matplotlib.org/)：一个 Python 2D 绘图库。
*   <b><code>&nbsp;20375⭐</code></b> <b><code>&nbsp;&nbsp;4253🍴</code></b> [bokeh](https://github.com/bokeh/bokeh))：用 Python 进行交互式 web 绘图。
*   <b><code>&nbsp;&nbsp;3694⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;564🍴</code></b> [ggplot](https://github.com/yhat/ggplot))：ggplot2 给 R 提供的 API 的 Python 版本。
*   🌎 [plotly](plot.ly/python/)：协同 Python 和 matplotlib 工作的 web 绘图库。
*   <b><code>&nbsp;15747⭐</code></b> <b><code>&nbsp;&nbsp;2862🍴</code></b> [pyecharts](https://github.com/chenjiandongx/pyecharts))：基于百度 Echarts 的数据可视化库。
*   [pygal](http://www.pygal.org/en/latest/)：一个 Python SVG 图表创建工具。
*   🌎 [pygraphviz](pypi.python.org/pypi/pygraphviz)：Graphviz 的 Python 接口。
*   [PyQtGraph](http://www.pyqtgraph.org/)：交互式实时 2D/3D/ 图像绘制及科学/工程学组件。
*   [SnakeViz](http://jiffyclub.github.io/snakeviz/)：一个基于浏览器的 Python's cProfile 模块输出结果查看工具。
*   <b><code>&nbsp;&nbsp;2027⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;224🍴</code></b> [vincent](https://github.com/wrobstory/vincent))：把 Python 转换为 Vega 语法的转换工具。
*   [VisPy](http://vispy.org/)：基于 OpenGL 的高性能科学可视化工具。
*   <b><code>&nbsp;10321⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;843🍴</code></b> [Altair](https://github.com/altair-viz/altair))：用于 Python 的声明式统计可视化库。
*   <b><code>&nbsp;&nbsp;3686⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;480🍴</code></b> [bqplot](https://github.com/bloomberg/bqplot))：Jupyter Notebook 的交互式绘图库。
*   <b><code>&nbsp;&nbsp;1598⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;395🍴</code></b> [Cartopy](https://github.com/SciTools/cartopy))：具有 matplotlib 支持的 Python 制图库。
*   🌎 [Dash](plot.ly/products/dash/)：构建在 Flask、React 和 Plotly 之上，旨在用于分析 Web 应用程序。
    * <b><code>&nbsp;&nbsp;2253⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;261🍴</code></b> [awesome-dash](https://github.com/Acrotrend/awesome-dash))
*   <b><code>&nbsp;42171⭐</code></b> <b><code>&nbsp;&nbsp;2722🍴</code></b> [diagrams](https://github.com/mingrammer/diagrams))：用图表作为代码。
*   <b><code>&nbsp;&nbsp;4538⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;247🍴</code></b> [plotnine](https://github.com/has2k1/plotnine))：基于ggplot2的Python图形语法。
*   🌎 [PyGraphviz](pypi.org/project/pygraphviz/)： [Graphviz](http://www.graphviz.org/) 的 Python 接口。
*   <b><code>&nbsp;13800⭐</code></b> <b><code>&nbsp;&nbsp;2094🍴</code></b> [Seaborn](https://github.com/mwaskom/seaborn))：使用 Matplotlib 进行统计数据可视化。

### 计算机视觉

计算机视觉相关库。

*   [OpenCV](http://opencv.org/)：开源计算机视觉库。
*   <b><code>&nbsp;&nbsp;&nbsp;929⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;150🍴</code></b> [pyocr](https://github.com/jflesch/pyocr))：Tesseract 和 Cuneiform 的包装库。
*   <b><code>&nbsp;&nbsp;6332⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;754🍴</code></b> [pytesseract](https://github.com/madmaze/pytesseract))：[Google Tesseract OCR](https://github.com/tesseract-ocr) 的另一包装库。
*   [SimpleCV](http://simplecv.org/)：一个用来创建计算机视觉应用的开源框架。
*   <b><code>&nbsp;29279⭐</code></b> <b><code>&nbsp;&nbsp;3554🍴</code></b> [EasyOCR](https://github.com/JaidedAI/EasyOCR))：支持40多种语言的即用型 OCR。
*   <b><code>&nbsp;56287⭐</code></b> <b><code>&nbsp;13715🍴</code></b> [Face Recognition](https://github.com/ageitgey/face_recognition))：简单的面部识别库。
*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Kornia](https://github.com/kornia/kornia/))：PyTorch 的开源差异化计算机视觉库。
*   <b><code>&nbsp;&nbsp;2162⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;261🍴</code></b> [tesserocr](https://github.com/sirfz/tesserocr))：另一个简单的，兼容 Pillow 的 `tesseract-ocr` API 装饰器，可用于 OCR。

### 深度学习

神经网络和深度学习相关框架。 也可以参考 <b><code>&nbsp;27881⭐</code></b> <b><code>&nbsp;&nbsp;6300🍴</code></b> [awesome-deep-learning](https://github.com/ChristosChristofidis/awesome-deep-learning))。

*   [Caffe](http://caffe.berkeleyvision.org)：一个 <b><code>&nbsp;34653⭐</code></b> <b><code>&nbsp;18524🍴</code></b> [Caffe](https://github.com/BVLC/caffe)) 的 python 接口。
*   🌎 [Caffe2](caffe2.ai/)：一个轻量级的，模块化的，可扩展的深度学习框架。
*   🌎 [keras](keras.io/)：以 tensorflow/theano/CNTK 为后端的深度学习封装库，快速上手神经网络。
*   [MXNet](http://mxnet.incubator.apache.org/)：一个高效和灵活的深度学习框架。
*   [Pytorch](http://pytorch.org/)：一个具有张量和动态神经网络，并有强大 GPU 加速能力的深度学习框架。
*   <b><code>&nbsp;&nbsp;6982⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;801🍴</code></b> [SerpentAI](https://github.com/SerpentAI/SerpentAI))：游戏代理框架，可使用任意视频游戏作为深度学习沙箱。
*   <b><code>&nbsp;&nbsp;9986⭐</code></b> <b><code>&nbsp;&nbsp;2469🍴</code></b> [Theano](https://github.com/Theano/Theano))：一个快速数值计算库。
*   [TensorFlow](http://tensorflow.org/)：谷歌开源的最受欢迎的深度学习框架。
*   <b><code>&nbsp;&nbsp;3169⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;439🍴</code></b> [skflow](https://github.com/tensorflow/skflow))：一个 <b><code>194667⭐</code></b> <b><code>&nbsp;75279🍴</code></b> [TensorFlow](https://github.com/tensorflow/tensorflow)) 的简化接口(模仿 scikit-learn)。
*   <b><code>&nbsp;&nbsp;1170⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;117🍴</code></b> [hebel](https://github.com/hannes-brt/hebel))：GPU 加速的深度学习库。
*   <b><code>&nbsp;&nbsp;1375⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;299🍴</code></b> [pydeep](https://github.com/andersbll/deeppy))：Python 深度学习库。

### 机器学习

机器学习相关库，也可以参考 <b><code>&nbsp;72137⭐</code></b> <b><code>&nbsp;15403🍴</code></b> [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning#python))。

*   <b><code>&nbsp;&nbsp;1176⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;371🍴</code></b> [Crab](https://github.com/muricoca/crab))：灵活、快速的推荐引擎。
*   <b><code>&nbsp;&nbsp;6356⭐</code></b> <b><code>&nbsp;&nbsp;1541🍴</code></b> [NuPIC](https://github.com/numenta/nupic))：智能计算 Numenta 平台。
*   <b><code>&nbsp;&nbsp;8859⭐</code></b> <b><code>&nbsp;&nbsp;1565🍴</code></b> [pattern](https://github.com/clips/pattern))：Python 网络挖掘模块。
*   <b><code>&nbsp;&nbsp;2865⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;786🍴</code></b> [PyBrain](https://github.com/pybrain/pybrain))：另一个 Python 机器学习库。
*   <b><code>&nbsp;&nbsp;2771⭐</code></b> <b><code>&nbsp;&nbsp;1086🍴</code></b> [Pylearn2](https://github.com/lisa-lab/pylearn2))：一个基于 <b><code>&nbsp;&nbsp;9986⭐</code></b> <b><code>&nbsp;&nbsp;2469🍴</code></b> [Theano](https://github.com/Theano/Theano)) 的机器学习库。
*   <b><code>&nbsp;&nbsp;1480⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;434🍴</code></b> [python-recsys](https://github.com/ocelma/python-recsys))：一个用来实现推荐系统的 Python 库。
*   [scikit-learn](http://scikit-learn.org/)：基于 SciPy 构建的机器学习 Python 模块。
*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [vowpalporpoise](https://github.com/josephreisinger/vowpalporpoise))：轻量级 <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Vowpal Wabbit](https://github.com/JohnLangford/vowpalwabbit/)) 的 Python 封装。
*   <b><code>&nbsp;37155⭐</code></b> <b><code>&nbsp;&nbsp;8705🍴</code></b> [gym](https://github.com/openai/gym))：开发和比较强化学习算法的工具包。
*   <b><code>&nbsp;&nbsp;7487⭐</code></b> <b><code>&nbsp;&nbsp;2034🍴</code></b> [H2O](https://github.com/h2oai/h2o-3))：开源快速可扩展的机器学习平台。
*   <b><code>&nbsp;&nbsp;1650⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;454🍴</code></b> [Metrics](https://github.com/benhamner/Metrics))：机器学习的评估指标。
*   <b><code>&nbsp;&nbsp;&nbsp;174⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [vowpal_porpoise](https://github.com/josephreisinger/vowpal_porpoise))：Python 版 <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Vowpal Wabbit](https://github.com/JohnLangford/vowpal_wabbit/)) 装饰器。
*   <b><code>&nbsp;28254⭐</code></b> <b><code>&nbsp;&nbsp;8867🍴</code></b> [xgboost](https://github.com/dmlc/xgboost))：可扩展，便携式和分布式梯度提升库。
*   <b><code>&nbsp;38958⭐</code></b> <b><code>&nbsp;&nbsp;6185🍴</code></b> [MindsDB](https://github.com/mindsdb/mindsdb))：MindsDB 是现有数据库的开源 AI 层，可让使用标准查询轻松地进行开发，训练和部署最新的机器学习模型。

### 推荐系统

用于构建推荐系统的相关库。

* <b><code>&nbsp;14213⭐</code></b> <b><code>&nbsp;&nbsp;1220🍴</code></b> [annoy](https://github.com/spotify/annoy))：对 C++/Python 实现的近似近邻算法进行了内存优化。
* <b><code>&nbsp;&nbsp;1088⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;204🍴</code></b> [fastFM](https://github.com/ibayer/fastFM))：Factorization Machine 相关库。
* <b><code>&nbsp;&nbsp;3783⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;626🍴</code></b> [implicit](https://github.com/benfred/implicit))：对隐式数据集进行协作过滤的快速 Python 实现。
* <b><code>&nbsp;&nbsp;1600⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;457🍴</code></b> [libffm](https://github.com/guestwalk/libffm))：Field-aware Factorization Machine (FFM) 相关库。
* <b><code>&nbsp;&nbsp;5074⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;726🍴</code></b> [lightfm](https://github.com/lyst/lightfm))：很多流行的推荐算法的 Python 实现。
* <b><code>&nbsp;&nbsp;3044⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;424🍴</code></b> [spotlight](https://github.com/maciejkula/spotlight))：使用 PyTorch 实现的深度推荐模型。
* <b><code>&nbsp;&nbsp;6776⭐</code></b> <b><code>&nbsp;&nbsp;1053🍴</code></b> [Surprise](https://github.com/NicolasHug/Surprise))：用于构建和分析推荐系统的科学工具。
* <b><code>&nbsp;&nbsp;1303⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;221🍴</code></b> [tensorrec](https://github.com/jfkirk/tensorrec))：TensorFlow 的推荐引擎框架。

### 分布式计算

分布式计算相关的框架和库。

*   <b><code>&nbsp;&nbsp;2672⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;522🍴</code></b> [dpark](https://github.com/douban/dpark))：Spark 的 Python 克隆版，一个类似 MapReduce 的框架。
*   <b><code>&nbsp;&nbsp;1031⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;145🍴</code></b> [dumbo](https://github.com/klbostee/dumbo))：这个 Python 模块可以让人轻松的编写和运行 Hadoop 程序。
*   <b><code>&nbsp;18701⭐</code></b> <b><code>&nbsp;&nbsp;2452🍴</code></b> [luigi](https://github.com/spotify/luigi))：这个模块帮你构建批处理作业的复杂流水线。
*   <b><code>&nbsp;&nbsp;2616⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;582🍴</code></b> [mrjob](https://github.com/Yelp/mrjob))：在 Hadoop 或 Amazon Web Services 上运行 MapReduce 任务。
*   <b><code>&nbsp;13799⭐</code></b> <b><code>&nbsp;&nbsp;1862🍴</code></b> [dask](https://github.com/dask/dask))：用于分析计算的灵活的并行计算库。
*   [PySpark](http://spark.apache.org/docs/latest/programming-guide.html)：Spark 的 Python API 。
*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Ray](https://github.com/ray-project/ray/))：一个用于并行和分布式 Python 的系统，它统一了机器学习生态系统。
*   <b><code>&nbsp;&nbsp;6821⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;535🍴</code></b> [faust](https://github.com/robinhood/faust))：一个 Python 流处理库，核心思想来源 🌎 [Kafka Streams](kafka.apache.org/documentation/streams/)。
*   <b><code>&nbsp;&nbsp;1507⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;221🍴</code></b> [streamparse](https://github.com/Parsely/streamparse))：运行针对事实数据流的 Python 代码。集成了 [Apache Storm](http://storm.apache.org/)。
*   <b><code>&nbsp;&nbsp;2745⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;324🍴</code></b> [mars](https://github.com/mars-project/mars))：是基于张量的，用于进行大规模数据计算的统一计算框架。

### 函数式编程

使用 Python 进行函数式编程。

*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [CyToolz](https://github.com/pytoolz/cytoolz/))：Toolz 的 Cython 实现：高性能函数式工具。
*   <b><code>&nbsp;&nbsp;3379⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;203🍴</code></b> [fn.py](https://github.com/kachayev/fn.py))：在 Python 中进行函数式编程：实现了一些享受函数式编程缺失的功能。
*   <b><code>&nbsp;&nbsp;3500⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;150🍴</code></b> [funcy](https://github.com/Suor/funcy))：炫酷又实用的函数式工具。
*   <b><code>&nbsp;&nbsp;5135⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;271🍴</code></b> [Toolz](https://github.com/pytoolz/toolz))：一组用于迭代器，函数和字典的函数式编程工具。
*   <b><code>&nbsp;&nbsp;4320⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;140🍴</code></b> [Coconut](https://github.com/evhub/coconut))：为了简单、优雅、更 Pythonic 的函数式编程而构建的 Python 变体。
*   <b><code>&nbsp;&nbsp;4053⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;315🍴</code></b> [more-itertools](https://github.com/erikrose/more-itertools))：比 `itertools` 拥有更多的可迭代对象的操作方式。
*   <b><code>&nbsp;&nbsp;4255⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;146🍴</code></b> [returns](https://github.com/dry-python/returns))：一个类型安全的单元、转换器与合成工具集合。

### 第三方 API

用来访问第三方 API 的库。 参见： <b><code>&nbsp;&nbsp;2163⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;413🍴</code></b> [List of Python API Wrappers and Libraries](https://github.com/realpython/list-of-python-api-wrappers))。

*   🌎 [apache-libcloud](libcloud.apache.org/)：一个为各种云设计的 Python 库。
*   <b><code>&nbsp;&nbsp;9762⭐</code></b> <b><code>&nbsp;&nbsp;1970🍴</code></b> [boto3](https://github.com/boto/boto3))：Amazon Web Services 的 Python 接口。
*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [django-wordpress](https://github.com/sunlightlabs/django-wordpress/))：Django 的 WordPress 模型与视图。
*   <b><code>&nbsp;&nbsp;2785⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;941🍴</code></b> [facebook-sdk](https://github.com/mobolic/facebook-sdk))：Facebook 平台的 Python SDK。
*   <b><code>&nbsp;&nbsp;&nbsp;852⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;198🍴</code></b> [facepy](https://github.com/jgorset/facepy))：Facepy 让和 Facebook's Graph API 的交互变得更容易。
*   <b><code>&nbsp;&nbsp;1791⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;383🍴</code></b> [gmail](https://github.com/charlierguo/gmail))：Gmail 的 Python 接口。
*   <b><code>&nbsp;&nbsp;8786⭐</code></b> <b><code>&nbsp;&nbsp;2562🍴</code></b> [google-api-python-client](https://github.com/google/google-api-python-client))：Python 用的 Google APIs 客户端库。
*   <b><code>&nbsp;&nbsp;7461⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;977🍴</code></b> [gspread](https://github.com/burnash/gspread))：Google 电子表格的 Python API。
*   <b><code>&nbsp;&nbsp;1865⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;392🍴</code></b> [twython](https://github.com/ryanmcgrath/twython))：Twitter API 的封装。

### DevOps 工具

用于 DevOps 的软件和库。

*   <b><code>&nbsp;68349⭐</code></b> <b><code>&nbsp;24157🍴</code></b> [Ansible](https://github.com/ansible/ansible))：一个非常简单的 IT 自动化平台。
*   <b><code>&nbsp;15322⭐</code></b> <b><code>&nbsp;&nbsp;5584🍴</code></b> [SaltStack](https://github.com/saltstack/salt))：基础设施自动化和管理系统。
*   [OpenStack](http://www.openstack.org/)：用于构建私有和公有云的开源软件。
*   🌎 [Docker Compose](docs.docker.com/compose/)：快速，分离的开发环境，使用 Docker。
*   [Fabric](http://www.fabfile.org/)：一个简单的，Python 风格的工具，用来进行远程执行和部署。
*   <b><code>&nbsp;&nbsp;1266⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;159🍴</code></b> [cuisine](https://github.com/sebastien/cuisine))：为 Fabric 提供一系列高级函数。
*   <b><code>&nbsp;&nbsp;1251⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;203🍴</code></b> [Fabtools](https://github.com/ronnix/fabtools))：一个用来编写超赞的 Fabric 文件的工具。
*   🌎 [gitapi](bitbucket.org/haard/gitapi)：Git 的纯 Python API。
*   🌎 [hgapi](bitbucket.org/haard/hgapi)：Mercurial 的纯 Python API。
*   <b><code>&nbsp;&nbsp;1696⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;147🍴</code></b> [honcho](https://github.com/nickstenning/honcho))：<b><code>&nbsp;&nbsp;6144⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;629🍴</code></b> [Foreman](https://github.com/ddollar/foreman)) 的 Python 克隆版，用来管理基于 🌎 [Procfile](devcenter.heroku.com/articles/procfile) 的应用。
*   <b><code>&nbsp;&nbsp;2830⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;491🍴</code></b> [pexpect](https://github.com/pexpect/pexpect))：在一个伪终端中控制交互程序，就像 GNU expect 一样。
*   <b><code>&nbsp;11137⭐</code></b> <b><code>&nbsp;&nbsp;1478🍴</code></b> [psutil](https://github.com/giampaolo/psutil))：一个跨平台进程和系统工具模块。
*   <b><code>&nbsp;&nbsp;9027⭐</code></b> <b><code>&nbsp;&nbsp;1266🍴</code></b> [supervisor](https://github.com/Supervisor/supervisor))：UNIX 的进程控制系统。
*   🌎 [cloudinit](cloudinit.readthedocs.io/en/latest/)：一个多分发包，用于处理云实例的早期初始化。
*   <b><code>&nbsp;&nbsp;4946⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;483🍴</code></b> [pyinfra](https://github.com/Fizzadar/pyinfra))：一个通用的 CLI 工具包和 python 库，用于自动化的基础设施。
*   <b><code>&nbsp;&nbsp;1696⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;147🍴</code></b> [honcho](https://github.com/nickstenning/honcho))：<b><code>&nbsp;&nbsp;6144⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;629🍴</code></b> [Foreman](https://github.com/ddollar/foreman)) 的 Python 克隆版，用于管理基于 Procfile 的应用。
*   🌎 [BorgBackup](www.borgbackup.org/)：具有压缩和加密功能的重复数据删除存档器。
*   🌎 [docker-compose](docs.docker.com/compose/)： 使用 🌎 [Docker](www.docker.com/) 的快速独立的开发环境。

### 任务调度

任务调度库。

*   [APScheduler](http://apscheduler.readthedocs.org/en/latest/)：轻巧但强大的进程内任务调度，使你可以调度函数。
*   <b><code>&nbsp;&nbsp;&nbsp;849⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;276🍴</code></b> [django-schedule](https://github.com/thauber/django-schedule))：一个 Django 排程应用。
*   [doit](http://pydoit.org/)：一个任务执行和构建工具。
*   <b><code>&nbsp;&nbsp;&nbsp;768⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72🍴</code></b> [gunnery](https://github.com/gunnery/gunnery))：分布式系统使用的多用途任务执行工具 ，具有 web 交互界面。
*   [Joblib](http://pythonhosted.org/joblib/index.html)：一组为 Python 提供轻量级作业流水线的工具。
*   <b><code>&nbsp;&nbsp;1181⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [Plan](https://github.com/fengsp/plan))：如有神助地编写 crontab 文件。
*   <b><code>&nbsp;12243⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;996🍴</code></b> [schedule](https://github.com/dbader/schedule))：人性化的 Python 任务调度库。
*   <b><code>&nbsp;&nbsp;1874⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;336🍴</code></b> [Spiff](https://github.com/knipknap/SpiffWorkflow))：使用纯 Python 实现的强大的工作流引擎。
*   [TaskFlow](http://docs.openstack.org/developer/taskflow/)：一个可以让你方便执行任务的 Python 库，一致并且可靠。
*   🌎 [Airflow](airflow.apache.org/) ：是一个工作流分配管理系统，通过有向非循环图的方式管理任务流程，设置任务依赖关系和时间调度。
*   <b><code>&nbsp;22149⭐</code></b> <b><code>&nbsp;&nbsp;2260🍴</code></b> [Prefect](https://github.com/PrefectHQ/prefect))：一个现代的工作流程编排框架，使构建、计划和监视健壮的数据管道变得容易。

### 外来函数接口

使用外来函数接口的库。

*   🌎 [cffi](pypi.python.org/pypi/cffi)：用来调用 C 代码的外来函数接口。
*   🌎 [ctypes](docs.python.org/2/library/ctypes.html)：(Python 标准库) 用来调用 C 代码的外来函数接口。
*   🌎 [PyCUDA](mathema.tician.de/software/pycuda/)：Nvidia CUDA API 的封装。
*   [SWIG](http://www.swig.org/Doc1.3/Python.html)：简化的封装和接口生成器。

### 重构

Python 重构相关库和工具。

 * [Bicycle Repair Man](http://bicyclerepair.sourceforge.net/)：Python 的重构工具。
 * 🌎 [Bowler](pybowler.io/)：适用于现代Python的安全代码重构。
 * <b><code>&nbsp;&nbsp;2193⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;184🍴</code></b> [Rope](https://github.com/python-rope/rope))：一个 Python 的重构库。

### 高性能

让 Python 更快的库。

*   [Cython](http://cython.org/)：优化的 Python 静态编译器。使用类型混合使 Python 编译成 C 或 C++ 模块来获得性能的极大提升。
*   <b><code>&nbsp;&nbsp;&nbsp;395⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [CLPython](https://github.com/metawilm/cl-python))：用 Common Lisp 编写的 Python 编程语言的实现。
*   <b><code>&nbsp;10511⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;636🍴</code></b> [Grumpy](https://github.com/google/grumpy))：编译器比解释器更强大的 cpython2.7 替代品（alpha）。 
*   <b><code>&nbsp;&nbsp;2736⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;311🍴</code></b> [IronPython](https://github.com/IronLanguages/ironpython3))：用 C＃ 编写的 Python 编程语言的实现。
*   🌎 [Jython](hg.python.org/jython)：为 JVM 用 Java 编写的 Python 编程语言的实现。
*   <b><code>&nbsp;21610⭐</code></b> <b><code>&nbsp;&nbsp;8792🍴</code></b> [MicroPython](https://github.com/micropython/micropython))：精简高效的 Python 编程语言实现。
*   <b><code>&nbsp;&nbsp;1598⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;132🍴</code></b> [Pyjion](https://github.com/Microsoft/Pyjion))：基于 CoreCLR 的 Python JIT。
*   [Numba](http://numba.pydata.org/)：Python JIT (just in time) 编译器，针对科学用的 Python ，由 Cython 和 NumPy 的开发者开发。
*   <b><code>&nbsp;&nbsp;2050⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;167🍴</code></b> [PeachPy](https://github.com/Maratyszcza/PeachPy))：嵌入 Python 的 x86-64 汇编器。可以被用作 Python 内联的汇编器或者是独立的汇编器，用于 Windows，Linux，OS X，Native Client 或者 Go 。
*   [PyPy](http://pypy.org/)：使用 Python 实现的 Python。解释器使用黑魔法加快 Python 运行速度且不需要加入额外的类型信息。
*   <b><code>&nbsp;&nbsp;4854⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;283🍴</code></b> [Pyston](https://github.com/dropbox/pyston))：使用 LLVM 和现代 JIT 技术构建的 Python 实现，目标是为了获得很好的性能。
*   🌎 [Stackless Python](bitbucket.org/stackless-dev/stackless/overview)：一个强化版的 Python。

### 微软的 Windows 平台

在 Windows 平台上进行 Python 编程。

*   [Python(x,y)](http://python-xy.github.io/)：面向科学应用的 Python 发行版，基于 Qt 和 Spyder。
*   [pythonlibs](http://www.lfd.uci.edu/~gohlke/pythonlibs/)：非官方的 Windows 平台 Python 扩展二进制包。
*   <b><code>&nbsp;&nbsp;5439⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;772🍴</code></b> [PythonNet](https://github.com/pythonnet/pythonnet))：Python 与 .NET 公共语言运行库 (CLR)的集成。
*   🌎 [PyWin32](sourceforge.net/projects/pywin32/)：针对 Windows 的 Python 扩展。
*   🌎 [WinPython](winpython.github.io/)：Windows 7/8 系统下便携式开发环境。

### 网络可视化和 SDN

用来进行网络可视化和 SDN(软件定义网络)的工具和库。

*   [Mininet](http://mininet.org/)：一款流行的网络模拟器以及用 Python 编写的 API。
*   <b><code>&nbsp;&nbsp;&nbsp;648⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;478🍴</code></b> [POX](https://github.com/noxrepo/pox))：一个针对基于 Python 的软件定义网络应用（例如 OpenFlow SDN 控制器）的开源开发平台。
*   [Pyretic](http://frenetic-lang.org/pyretic/)：火热的 SDN 编程语言中的一员，为网络交换机和模拟器提供强大的抽象能力。
*   <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [SDX Platform](https://github.com/sdn-ixp/internet2award))：基于 SDN 的 IXP 实现，影响了 Mininet, POX 和 Pyretic。
*   [NRU](http://ryu.readthedocs.io/en/latest/)：一个基于组件的软件定义网络框架。
*   <b><code>&nbsp;&nbsp;2446⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;582🍴</code></b> [napalm](https://github.com/napalm-automation/napalm))：可跨供应商 API 来操纵网络设备。

### 硬件

用来对硬件进行编程的库。

*   [ino](http://inotool.org/)：操作 🌎 [Arduino](www.arduino.cc/) 的命令行工具。
*   [Pyro](http://pyrorobotics.com/)：Python 机器人编程库。
*   <b><code>&nbsp;&nbsp;1070⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;241🍴</code></b> [PyUserInput](https://github.com/SavinaRoja/PyUserInput))：跨平台的，控制鼠标和键盘的模块。
*   <b><code>&nbsp;12181⭐</code></b> <b><code>&nbsp;&nbsp;2200🍴</code></b> [scapy](https://github.com/secdev/scapy))：一个非常棒的操作数据包的库。
*   🌎 [wifi](wifi.readthedocs.org/en/latest/)：一个 Python 库和命令行工具用来在 Linux 平台上操作 WiFi。
*   [Pingo](http://www.pingo.io/)：Pingo 为类似 Raspberry Pi，pcDuino， Intel Galileo 等设备提供统一的 API 用以编程。
*   <b><code>&nbsp;&nbsp;3972⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;456🍴</code></b> [keyboard](https://github.com/boppreh/keyboard))：在 Windows 和 Linux 上挂钩并模拟全局键盘事件。
*   <b><code>&nbsp;&nbsp;&nbsp;961⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;142🍴</code></b> [mouse](https://github.com/boppreh/mouse))：在 Windows 和 Linux 上挂钩并模拟全局鼠标事件。

### 兼容性

帮助从 Python 2 向 Python 3 迁移的库。

*   [Python-Future](http://python-future.org/index.html)：这就是 Python 2 和 Python 3 之间丢失的那个兼容性层。
*   🌎 [Six](pypi.python.org/pypi/six)：Python 2 和 3 的兼容性工具。
*   <b><code>&nbsp;&nbsp;&nbsp;370⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [modernize](https://github.com/PyCQA/modernize))：使 Python 代码更加现代化以便最终迁移到 Python 3。

### 算法和设计模式

数据结构、算法和设计模式的 Python 实现。也可以参考 <b><code>&nbsp;24989⭐</code></b> <b><code>&nbsp;&nbsp;2950🍴</code></b> [awesome-algorithms](https://github.com/tayllan/awesome-algorithms)) 。

* 算法
  * <b><code>&nbsp;25417⭐</code></b> <b><code>&nbsp;&nbsp;4734🍴</code></b> [algorithms](https://github.com/keon/algorithms))：数据结构和算法的简单示例。
  * <b><code>&nbsp;&nbsp;3082⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;624🍴</code></b> [python-ds](https://github.com/prabhupant/python-ds))：用于面试的数据结构和算法的集合。
  * <b><code>&nbsp;&nbsp;3937⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;228🍴</code></b> [sortedcontainers](https://github.com/grantjenks/python-sortedcontainers))：排序集合的快速的纯 Python 实现。
  * <b><code>219531⭐</code></b> <b><code>&nbsp;50317🍴</code></b> [TheAlgorithms](https://github.com/TheAlgorithms/Python))：所有算法的 Python 实现。
* 设计模式
  * <b><code>&nbsp;&nbsp;2341⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;158🍴</code></b> [PyPattyrn](https://github.com/tylerlaberge/PyPattyrn))：一个简单而有效的库，用于实现常见的设计模式。
  * <b><code>&nbsp;42704⭐</code></b> <b><code>&nbsp;&nbsp;7037🍴</code></b> [python-patterns](https://github.com/faif/python-patterns))：一个 Python 设计模式集合。
  * <b><code>&nbsp;&nbsp;6482⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;568🍴</code></b> [transitions](https://github.com/pytransitions/transitions))：轻量级的，面向对象的有限状态机实现。
  
  

### 内置类的增强版实现

一些 Python 内置类的增强版实现库。

* <b><code>&nbsp;&nbsp;5770⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;426🍴</code></b> [attrs](https://github.com/python-attrs/attrs))：一个在类定义时可替换 `__init__`, `__eq__`, `__repr__`等方法的样板。
* <b><code>&nbsp;&nbsp;1578⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [bidict](https://github.com/jab/bidict))：高效的 Pythonic 的双向映射数据结构和相关功能。
* <b><code>&nbsp;&nbsp;2823⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;122🍴</code></b> [Box](https://github.com/cdgriffith/Box))：具有高级点符号访问权限的 Python 字典。
* 🌎 [dataclasses](docs.python.org/3/library/dataclasses.html)：(Python 标准库) 数据类。
* <b><code>&nbsp;&nbsp;&nbsp;222⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [DottedDict](https://github.com/carlosescri/DottedDict))：提供一种使用点路径符号访问列表和字典的方法的库。

### 机器人

机器人相关库。

* <b><code>&nbsp;29127⭐</code></b> <b><code>&nbsp;&nbsp;7243🍴</code></b> [PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics))：各种具有可视化效果的机器人算法的汇总。
* [rospy](http://wiki.ros.org/rospy)：ROS (Robot Operating System) 库。

### 聊天工具

聊天机器人开发相关的库。

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [errbot](https://github.com/errbotio/errbot/))：实现 ChatOps 的最简单最受欢迎的聊天机器人。

### 编辑器插件和 IDE

* Emacs
  * <b><code>&nbsp;&nbsp;1936⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;262🍴</code></b> [elpy](https://github.com/jorgenschaefer/elpy))：Emacs Python 开发环境。
* Sublime Text
  * <b><code>&nbsp;&nbsp;2241⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;260🍴</code></b> [anaconda](https://github.com/DamnWidget/anaconda))：Anaconda 可将功能齐全的 Python 开发 IDE 转换为 Sublime Text 3。
  * <b><code>&nbsp;&nbsp;&nbsp;930⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;107🍴</code></b> [SublimeJEDI](https://github.com/srusskih/SublimeJEDI))：一个很棒的自动补全库 Jedi 的Sublime Text 插件。
* Vim
  * <b><code>&nbsp;&nbsp;5314⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;368🍴</code></b> [jedi-vim](https://github.com/davidhalter/jedi-vim))：用于 Python 的 Jedi 自动补全库的 Vim 绑定。
  * <b><code>&nbsp;&nbsp;5475⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;765🍴</code></b> [python-mode](https://github.com/python-mode/python-mode))：一个将 Vim 转换为 Python IDE 的多合一插件。
  * <b><code>&nbsp;26056⭐</code></b> <b><code>&nbsp;&nbsp;2764🍴</code></b> [YouCompleteMe](https://github.com/Valloric/YouCompleteMe))：包含 Jedi 补全的 Python 引擎。
* Visual Studio
  * <b><code>&nbsp;&nbsp;2568⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;672🍴</code></b> [PTVS](https://github.com/Microsoft/PTVS))：Visual Studio Python 工具。
* Visual Studio Code
  * 🌎 [Python](marketplace.visualstudio.com/items?itemName=ms-python.python)：对 Python 有丰富支持的官方 VSCode 扩展。
* IDE
  * 🌎 [PyCharm](www.jetbrains.com/pycharm/)：JetBrains 提供的商业 Python IDE，也有免费的社区版。
  * <b><code>&nbsp;&nbsp;9186⭐</code></b> <b><code>&nbsp;&nbsp;1758🍴</code></b> [spyder](https://github.com/spyder-ide/spyder))： 开源 Python IDE。

### 企业级应用集成

企业级环境中用于集成的平台与工具。

* 🌎 [Zato](zato.io)：ESB, SOA, REST, APIs 以及云的 Python 整合。

### GraphQL

GraphQL 相关库。

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [graphene](https://github.com/graphql-python/graphene/))：Python GraphQL 框架。
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [tartiflette-aiohttp](https://github.com/tartiflette/tartiflette-aiohttp/))：Tartiflette 的基于 aiohttp 的装饰器，用于通过 HTTP 公开 GraphQL API。
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [tartiflette-asgi](https://github.com/tartiflette/tartiflette-asgi/))：Tartiflette GraphQL 引擎的 ASGI 支持。
* 🌎 [tartiflette](tartiflette.io)：支持 Python 3.6+ 和 asyncio 的 SDL 优先的 GraphQL 引擎实现。

### 股票金融
- <b><code>&nbsp;10280⭐</code></b> <b><code>&nbsp;&nbsp;3327🍴</code></b> [QUANTAXIS](https://github.com/QUANTAXIS/QUANTAXIS))：支持任务调度，分布式部署的股票/期货/期权/港股/虚拟货币的数据/回测/模拟/交易/可视化/多账户纯本地量化解决方案
- <b><code>&nbsp;16806⭐</code></b> <b><code>&nbsp;&nbsp;4506🍴</code></b> [abu](https://github.com/bbfamily/abu)): 基于python的开源量化交易，量化投资架构
- <b><code>&nbsp;&nbsp;3081⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;750🍴</code></b> [Hikyuu Quant](https://github.com/fasiondog/hikyuu))：基于C++/Python的开源量化交易研究框架，用于策略分析及回测（仅受限于数据，如有数据也可用于期货等）
- <b><code>&nbsp;39257⭐</code></b> <b><code>&nbsp;11398🍴</code></b> [vnpy](https://github.com/vnpy/vnpy))：基于Python的开源量化交易系统开发框架，整合了多种交易接口，并针对具体策略算法和功能开发提供了简洁易用的API，用于快速构建交易员所需的量化交易应用

### 杂项

不属于上面任何一个类别，但是非常有用的库。

*   <b><code>&nbsp;&nbsp;2042⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;191🍴</code></b> [blinker](https://github.com/jek/blinker))：快速的 Python 运行时信号/事件分配系统。
*   <b><code>&nbsp;&nbsp;6868⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;390🍴</code></b> [boltons](https://github.com/mahmoud/boltons))：一组纯 Python 实用工具。
*   <b><code>&nbsp;&nbsp;3106⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;234🍴</code></b> [itsdangerous](https://github.com/pallets/itsdangerous))：将受信任的数据传递到不受信任的环境的帮助工具。
*   <b><code>&nbsp;19774⭐</code></b> <b><code>&nbsp;&nbsp;3782🍴</code></b> [magenta](https://github.com/magenta/magenta))：使用人工智能生成音乐与艺术的工具。
*   <b><code>&nbsp;&nbsp;1140⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;141🍴</code></b> [pluginbase](https://github.com/mitsuhiko/pluginbase))：一个简单但灵活的 Python 插件系统。
*   [tryton](http://www.tryton.org/)：一个通用业务框架。

## Source
<b><code>&nbsp;30325⭐</code></b> <b><code>&nbsp;&nbsp;7972🍴</code></b> [jobbole/awesome-python-cn](https://github.com/jobbole/awesome-python-cn))