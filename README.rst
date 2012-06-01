ikandou.douban
==============
这是爱看豆万卷书在Chrome或者Firefox的greasemonkey脚本源代码。在豆瓣读书旁自动显示这本书是否在爱看豆万卷书有相应的电子书，并提供下载链接。

多谢 `satoru <https://github.com/suzaku>`_ 童鞋提供的脚本，我做了稍微的样式修改，你现在可以在豆瓣读书的页面随时看到这本书是否在 `万卷书 <http://ikandou.com/book>`_ 上有对应的电子书。

如何使用这个插件
==================

下载和安装插件
-------------

* 如果你是Chrome用户

  请猛击 `这个页面 <http://userscripts.org/scripts/show/134658/>`_ ，点击页面右上角的Install，就会自动安装到你的浏览器。

* 如果你是Firefox用户

  先安装 `greasemonkey <https://addons.mozilla.org/zh-CN/firefox/addon/greasemonkey/>`_ 插件
然后就跟Chrome安装一样了，点击 `这个页面 <http://userscripts.org/scripts/show/134658>`_ 上方的install，就可以安装到Firefox了。

安装之后的效果
-----------------

比如豆瓣读书的 `这个页面 <http://book.douban.com/subject/1146267/>`_ ，会成为 `这个样子 <http://blog.ikindle.mobi/wp-content/uploads/2012/05/Screenshot-10.png>`_ 

如何测试安装时否成功
----------------

猛击豆瓣读书的 `这个页面 <http://book.douban.com/subject/1146267/>`_  ,如果显示跟上图一样，说明安装成功了。有任何问题或者建议，发送邮件到okidogiii@gmail.com 。

如何贡献源代码到这个插件
====================
如果你有建议对这个插件进行改进，可以使用github 的 pull request，这儿是一个如何使用pull request的简单流程：

* Fork on GitHub (click Fork button)
* Clone to computer ($ git clone git@github.com:you/ikandou.douban.git)
* Don't forget to cd into your repo: ($ cd ikandou.douban/)
* Set up remote upstream ($ git remote add upstream git@github.com:fengli/ikandou.douban.git)
* Create a branch for new issue ($ git checkout -b 100-new-feature, if you don't have a bug report no worries just skip the number)
* Develop on issue branch. [Time passes, the main ikandou repository accumulates new commits]
* Commit changes to issue branch. ($ git add . ; git commit -m 'commit message')
* Fetch upstream ($ git fetch upstream)
* Update local master ($ git checkout master; git pull upstream master)
* Repeat steps 5-8 till dev is complete
* Rebase issue branch ($ git checkout 100-new-feature; git rebase master)
* Push branch to GitHub ($ git push origin 100-new-feature)
* Issue pull request (Click Pull Request button)

