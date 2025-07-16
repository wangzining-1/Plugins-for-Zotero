# citation-styles

#### 介绍
参考文献样式，适用于Zotero和Endnotes

#### 软件架构
zotero-styles目录下为适用于Zotero的样式csl文件，XML格式


#### Zotero样式说明
从Zotero菜单“Edit”-“Preferences”-“Cite”标签，可看到目前Zotero里已经安装的引文style列表，点击“+”按钮可导入csl文件。

1.  chinese-gbt7714-2015-numeric-etal.csl
在Zotero原GBT7714-2015-numeric的基础上有如下修改
（1）支持语言为en时，省略作者显示为et al.，语言标识为zh-CN或无语言标识时仍显示为“等”。该文件导入Zotero时会提示不符合格式规范（因为双语支持的部分），不必理会，点击OK即可。如果发现外文（不限于英文）文献并不显示et al.仍然是“等”，到该条目info标签找到Laguage，填上en就可以了。
（2）不显示OL。有网络资源时，类型会加上一个OL，如期刊为[J/OL]，很多会议论文也会被识别为网络资源加上OL。
（3）DOI显示为小写带空格“doi: ”
（4）不显示引用日期[accessed-date]。就是插入引用的日期，完全不需要。
（5）作者姓首字母大写，非全大写。名 仍然只有一个大写字母。

2.  chinese-gbt7714-2015-numeric-etal-nodoi.csl
在1、基础上去掉了DOI

3.  chinese-gbt7714-2015-numeric-fullname.csl
（1）显示作者名全名，首字母大写。
（2）显示全部作者，不需要et al.了，导入Zotero时不会提示格式不符合规范。

4.  chinese-gbt7714-2015-numeric-fullname-nodoi.csl
在3、基础上去掉了DOI

5.  elsevier-harvard-fullname.csl
显示作者全名，显示期刊全名。保留默认显示全部作者，默认姓-名顺序。

6.  elsevier-harvard-fullname-nodoi.csl
在5、的基础上去掉了DOI

7.  ieee-fullname.csl
在ieee.csl基础上，显示作者全名，仍按名-姓顺序，显示期刊全名。

8.  ieee-fullname-nodoi.csl
在7、基础上去掉了DOI

9.  使用nature.csl原版的时候注意，如果文献有卷号Volume，则不显示DOI，否则显示DOI。缺失卷号，显示的DOI和前一项之间不是“.”而是空格。所以如果应该有卷号的文献缺失卷号注意补全。另外引文行距为2倍。
（1）显示作者全名，保持默认姓-名顺序，去掉姓和名之间的逗号。
（2）显示期刊全名。
（3）无论是否有Volume都显示DOI，且和前一项之间以“.”分隔。
（4）引文行距改为默认

10.  nature-fullname-nodoi.csl
在9、的基础上去掉了DOI


#### Endnotes样式说明

1.  xxxx
2.  xxxx
3.  xxxx

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
