--PIP3和PIP#
pip时python中的包管理工具，pip和pip3时不同的版本，它们都会把下载的包安装在script\中
如果安装了python2版本，则只能用pip安装包
如果安装了python3版本，则pip和pip3都可以使用，二者没有什么区别
如果同时安装了python2和python3，则pip给pyhton2使用，pip3给python3使用
用法如下:   
  pip <command> [options]

命令:
  install                     安装指定包.
  download                    下载指定包.
  uninstall                   卸载指定包.
  freeze                      输出已经安装的某个包的依赖信息.
  list                        列出所有已经安装的包.
  show                        显示指定的某个已经安装的包的详细信息.
  check                       检查已经安装的某个包是否有依赖问题.
  search                      搜索符合条件的包
  wheel                       安装whl格式的wheel包.
  hash                        计算指定包的hash值.
  help                        显示帮助信息.

General Options:
  -h, --help                  Show help.
  --isolated                  在一个单独的环境中运行pip，忽略环境变量和用户配置.
  -v, --verbose               显示更多的输出信息.
  -V, --version               显示pip版本.
  -q, --quiet                 显示更少的输出，只显示WARNING,ERROR, and CRITICALG级别的日志.
  --proxy <proxy>             指定代理，代理格式：
                              [user:passwd@]proxy.server:port.
  --retries <retries>         每个连接的最大重试次数，默认5次.
  --timeout <sec>             设置socket的超时时间，默认15秒.
  --exists-action <action>    Default action when a path already exists:
                              (s)witch, (i)gnore, (w)ipe, (b)ackup, (a)bort.
  --trusted-host <hostname>   Mark this host as trusted, even though it does
                              not have valid or any HTTPS.
  --cert <path>               Path to alternate CA bundle.
  --client-cert <path>        Path to SSL client certificate, a single file
                              containing the private key and the certificate
                              in PEM format.
  --cache-dir <dir>           Store the cache data in <dir>.
  --no-cache-dir              Disable the cache.
  --disable-pip-version-check
                              Don't periodically check PyPI to determine
                              whether a new version of pip is available for
                              download. Implied with --no-index.
