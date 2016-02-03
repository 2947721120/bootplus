# [Bootplus v1.0.5](https://github.io/aozora/bootplus)

bootplus是更快和更容易的Web开发灵感来自最新的谷歌+的外观和感觉的前端框架，创建和维护[Aozora](http://twitter.com/aozoralabs).

Bootplus is based on [Twitter Bootstrap](http://twitter.github.io/bootstrap)
To get started, check out [http://aozora.github.com/bootplus](http://aozora.github.io/bootplus)!



## 快速启动

三快速启动选项：

* [Download the latest release](http://aozora.github.io/bootplus/zipball/master).
* 克隆的地址： `git clone git://github.com/aozora/bootplus.git`.

读 [Getting Started page](http://aozora.github.io/bootplus/getting-started) 有关框架内容、模板和实例的信息，以及更多。



## Versioning

透明度和洞察我们的发布周期，并努力保持向后兼容性，bootplus将保持语义版本的指引下尽可能。

Releases will be numbered with the following format:

`<major>.<minor>.<patch>`

And constructed with the following guidelines:

* Breaking backward compatibility bumps the major (and resets the minor and patch)
* New additions without breaking backward compatibility bumps the minor (and resets the patch)
* Bug fixes and misc changes bumps the patch

For more information on SemVer, please visit [http://semver.org/](http://semver.org/).



## Bug tracker

Have a bug or a feature request? [Please open a new issue](https://github.com/twitter/bootplus/issues). Before opening any issue, please search for existing issues and read the [Issue Guidelines](https://github.com/necolas/issue-guidelines), written by [Nicolas Gallagher](https://github.com/necolas/).



## Community

Keep track of development and community news.

* Follow [@aozoralabs on Twitter](http://twitter.com/aozoralabs).


## Compiling CSS and JavaScript

Bootplus includes a [makefile](Makefile) with convenient methods for working with the framework. Before getting started, be sure to install [the necessary local dependencies](package.json):

```
$ npm install
```

When completed, you'll be able to run the various make commands provided:

#### build - `make`
Runs the recess compiler to rebuild the `/less` files and compiles the docs. Requires recess and uglify-js.

#### test - `make test`
Runs jshint and qunit tests headlessly in [phantomjs](http://code.google.com/p/phantomjs/) (used for ci). Depends on having phantomjs installed.

#### watch - `make watch`
This is a convenience method for watching just Less files and automatically building them whenever you save. Requires the Watchr gem.

Should you encounter problems with installing dependencies or running the makefile commands, be sure to first uninstall any previous versions (global and local) you may have installed, and then rerun `npm install`.




## Authors

**Marcello Palmitessa**

+ [http://twitter.com/aozoralabs](http://twitter.com/aozoralabs)
+ [https://github.com/aozora](https://github.com/aozora)


## Copyright and license

Bootplus is dual licensed, GPL-2 and Apache-2; see the LICENSE file.
