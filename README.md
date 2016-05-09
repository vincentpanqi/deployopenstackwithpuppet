# 关于写此书的动力

人是很奇怪的动物，天生懒惰，但是在压力的驱使下，又能做成一些连自己都会觉得惊讶的成就。对于天生喜欢写随便喝技术文章的我，在近三年的时间里，虽有多名出版社编辑的循循善诱，仍然不为所动，心想着有这闲时间我不如多吃几份美食，多打两盘DOTA。

更深层次地讲其实是源于对于未知的恐惧，源于面对数十万文字工作量的害怕，这就是一场体力和脑力并存的马拉松，普通人在看到终点的艰巨时，在起点就已经选择放弃了，然而我不是一个普通人，因此早在6个月前我就富有先见之明地创建了这本书，并且写上了大约83个字符的详细介绍，然后就没有了下文。

无数个教训告诉我：决心虽然重要，但是坚持更加可贵。让我重新拾起笔（键盘）的原因是源于今晚的一顿饭。今晚注定是一个平凡的夜晚，Devops组的同事像往常一样忙到晚上8点多正纷纷收拾东西下班，大家站在公司门前讨论去哪里吃饭，这时我走出来，虽刚从纽约飞回到空气清新的帝都，时差还没有倒回来，脑袋浑浑噩噩，但又担心这帮邋遢的家伙站在公司大门口持续影响公司形象，于是忙把他们连哄带骗全都打包上车，拉到了附近的一家馆子里，几口飘香的云南饭菜入肚，大家就开始天南地北地扯东扯西，无外乎是谁谁谁今天又看了一本MySQL从删库到跑路，谁谁谁今天又当了一回Puppet背锅侠，谁谁谁的项目又埋了一个大坑。

不知不觉，我们就聊到了Openstack自动化部署这个话题上。作为一名从2011年开始接触Openstack的老人，在2013年进入PuppetOpenstack社区项目的core develeloper，我深深地感觉到是时候召(忽)唤（悠）这帮孩子来一起填这个史诗级别的远古巨坑了。
    
UnitedStack DevOps Team从13年伊始就全身心投入到Openstack持续交付和持续集成事业中，目前使用了86个puppet module, 6台PuppetMaster, 持续管理着约60个Openstack线上集群和12个Openstack开发测试集群近7种不同环境，支撑了近3000台Openstack集群服务器，独立开发了UOS部署工具(CTask)， 软件包管理工具(Packforge, Specforge, Repoforge)， IaaS虚拟资源池(Chameleon）, Openstack平滑升级工具(Screenwriter)，这里面涉及到了大量的自动化运维工具，例如：Ansible, Foreman, Puppet, ClusterShell, Mcollective；同时还有编写了大量各种语言的脚本：Shell, Ruby, Python, Puppet。

说实话，DevOps团队里每个人平时都有忙不完的事情，从早上还没到公司到晚上回到家中，随时随刻会被人call online，就像今天吃饭那样，站在门口等我上个厕所，就有人被其他同事喊回去处理任务去了。但并不是说因此就有理由说，我们很忙，因此没有时间可以去写一本书。我们的确应该来停下脚步，回头看一看过去三年团队的努力，然后做一个系统性的梳理和总结了。

这本书涉及的是我们过去三年时间里对于Openstack自动化部署工作的最核心部分：PuppetOpenstack核心库和模块的详细使用说明。我们规划每天晚上抽出2到3小时的不固定时间，计划在2个星期内完成第一版的初稿工作，然后开始进入稳定地迭代周期。

期望各位关注此书的读者可以从中有所思，有所得。

<br/>

于阳光明媚昏昏欲睡的五月
    
余兴超


# 关于作者

> * 余兴超 (Newptone)  UnitedStack R&D Director, 2011年开始接触Openstack，PuppetOpenstack官方项目core developer，目前负责打酱油相关事宜。
> * 廖鹏辉
> * 陆源
> * 周维宇