
Linux/GUN Ubuntu 14.04.01 LTS 虚拟机环境备份记录			{{{1
==========================================================================================================

 metalmac_Ubuntu_140401_ws_init			{{{2
-----------------------------------------------------------------------------------------------------------

	初步构建基于Linux的Vim集成开发环境，更新如下：
		1.安装配置好Ubuntu14.04系统，配置网络服务，安装相关常用软件和开发库
		2.编译安装Vim7.4，并配置安装相关插件；
		3.编译安装基于llvm,clang的语法检测和代码补全的YouCompleteMe插件;

-----------------------------------------------------------------------------------------------------------

 metalmac_Ubuntu_140401_ws@201412170518			{{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：
		1.在init版本基础上重新编译llvm clang的库;
		2.配置基于Vundle的Vim插件管理插件，便于插件管理;
		
-----------------------------------------------------------------------------------------------------------

 metalmac_Ubuntu_140401_ws@201412171708			{{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：
		1.编译并测试生成的llvm和clang库;
		2.查漏补缺Vim开发环境需要的插件，补全安装，涉及visual-star,autocomplete.pair等
		3.基于Windows下的vim配置文件配置linux环境下的Vim插件激活快捷键，采用<Leader>进行mapper匹配

	
-----------------------------------------------------------------------------------------------------------

metalmac_Ubuntu_140401_ws@201412181747			{{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：
		1.基于linux ubuntu 14.04.01的系统编译llvm和clang类库，编译ycm的辅助类库;
		2.成功配置vim的ycm插件，实现代码语法的智能、自动补全，编译前的静态语法分析功能;

-----------------------------------------------------------------------------------------------------------

metalmac_Ubuntu_140401_ws@201412191720               {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：
		1.配置vimgdb插件，实现基于Vim的gdb全面单步调试功能;
		

-----------------------------------------------------------------------------------------------------------

metalmac_Ubuntu_140401_ws@201412211023               {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：
		1.安装UltiSnips控件，实现基于YCM控件更全面的代码补全功能，提供类似'include','if-else'等关键字补全;
		2.调试ycm插件，支持动态库文件补全提示功能，尚未调试好;

-----------------------------------------------------------------------------------------------------------

metalmac_Ubuntu_140401_ws@201412232024               {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：
        1.针对github中use_vim_as_ide的相关文档与技巧，修改linux中vim的相关键盘映射内容，涉及窗口的跳转;
        2.增加一些vim的常规设置,代码折叠，文档缩进功能;
        3.增加OmniCppComplete插件，与YCM插件集成应用;

-----------------------------------------------------------------------------------------------------------

metalmac_Ubuntu_140401_ws@201412261744{{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：
		1.增加基于gcc的vim编译快捷键映射，尝试进行基于gcc的一键编译，尚有问题待解决;
-----------------------------------------------------------------------------------------------------------


metalmac_Ubuntu_140401_ws@201412281249          {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：
		1.增加vim的easymotion和vim-signature插件，增强vim的快速移动和书签标注功能;
        2.配置基于llvm+clang+cmake的vim一键编译开发环境，详见vim备份记录和yangyangwithgnu github首页;
-----------------------------------------------------------------------------------------------------------


metalmac_Ubuntu_140401_ws@201412282345          {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：
       1.下载编译lldb调试器;
       2.增加vim-lldb插件，配置基于lldb的vim调试编译环境，配置成功使用lldb时反复报错待解决;
       3.更新系统软件和应用软件，apt-get update ,apt-get upgrade;
-----------------------------------------------------------------------------------------------------------


metalmac_Ubuntu_140401_ws@201501121553          {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：
       1.下载vim-latex-suite插件，配置基于vim的latex文本编辑功能，安装好待测试;
       2.进行CSAPP示例代码及习题编码实验，更新csap_sample文件夹为csapp_sample;
-----------------------------------------------------------------------------------------------------------

metalmac_Ubuntu_140401_ws@201501171622          {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：
       1.配置Vim,支持gcc的编译为汇编机器级代码的功能;

       2.常规配置备份;
-----------------------------------------------------------------------------------------------------------

metalmac_Ubuntu_140401_ws@201502161734          {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.常规配置备份;
-----------------------------------------------------------------------------------------------------------

metalmac_Ubuntu_140401_ws@201506090934         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.修改.basrc文件，增加ls,rm,cp的alias,使其更灵活操作命令格式;
       2.常规配置备份;
-----------------------------------------------------------------------------------------------------------

metalmac_Ubuntu_140401_ws@201601260951         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.增加Vim中的查找后无关内容折叠功能;
       2.常规配置备份;
-----------------------------------------------------------------------------------------------------------

metalmac_Ubuntu_140401_ws@201608011359         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.安装增加iperf2/iperf3;
       2.常规配置备份;
-----------------------------------------------------------------------------------------------------------

metalmac_Ubuntu_140401_ws@201608011526         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.安装增加autoconf和automake,并进行功能验证通过;
-----------------------------------------------------------------------------------------------------------

metalmac_Ubuntu_140401_ws@201608021717         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.安装增加npm,nodejs,vim-markdown插件,vim-instant-markdown插件(尚未配置成功待解决);
-----------------------------------------------------------------------------------------------------------

metalmac_Ubuntu_140401_ws@201608031706         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.apt-get update更新相关软件;
       2.安装增加putty;
       3.安装增加tmux,并根据个人喜好配置自启动的tmux界面(出现嵌套调用tmux问题待解决);
-----------------------------------------------------------------------------------------------------------

metalmac_Ubuntu_140401_ws@201608041056         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.配置tmux,设置相关界面配置,尝试配置基于powerline的显示模式;
-----------------------------------------------------------------------------------------------------------

metalmac_Ubuntu_140401_ws@201608041542         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.配置tmux,设置相关界面配置,完成基于powerline的显示模式,配置
-----------------------------------------------------------------------------------------------------------

metalmac_Ubuntu_140401_ws@201608051116         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.通过源码编译更新tmux至V2.2版;
       2.编译安装Libevent库;
       3.安装tmux的tpm(tmux plugin manager)插件,对tmux插件进行管理;
       4.配置tmux并安装vim-tmux-navigator插件,完成vim与tmux之间的无缝切换(通过vim的hjkl);
-----------------------------------------------------------------------------------------------------------

metalmac_Ubuntu_140401_ws@201608051732         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.配置tmux并安装tmux-sidebar,tmux-copycat,tmux-yank,tmux-prefix-highlight插件;
       2.配置vim安装vim-husk插件(出现无效表达式问题待解决);
        
-----------------------------------------------------------------------------------------------------------

metalmac_Ubuntu_140401_ws@201608081125         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       2.配置vim安装vim-husk,vim-surround插件,增强vim的命令行编辑模式及其文本各种括号的编辑能力;
        
-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201608081557         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.配置tmux并安装tmux-yank, tmux-resurrect, tmux-continuum插件;
       2.修改tmux的自定义启动脚本,解决嵌套打开tmux会话问题(nested session);
        
-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201608082047         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.配置tmux,设置powerline字体显示问题,调整tmux下的终端的着色显示;
       2.在Windows下安装对应的Powerline for Consolas字体解决putty显示powerline字体乱码问题;
       3.虚拟机更换宿主机器后tmux及python对应库出问题待解决;
        
-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201608092100         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.虚拟机更换宿主机器后tmux及python对应库出问题待解决;
       2.安装tmuxline.vim插件,通过在tmux的session中利用vim命令效果进行状态栏显示扩展;
        
-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201608122315         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.因python的致命错误尚未找到解决方法,暂时停用相关的powerline终端界面配置功能;
       2.安装oh-my-zsh框架环境,并配置zsh模式的shell,添加tmux等zsh插件(详见.zshrc文件);
        
-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201608152109         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.修复putty登录root用户access denied问题,chsh修改默认shell时为指定绝对路径导致root找不到shell;
       2.配置个人oh-my-zsh环境,添加cp,z等zsh插件(详见.zshrc文件);
       3.安装配置htop;
       4.更改tmuxmy为默认zsh的tmuxz(tmz),tmuxsh对应bash;
        
-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201608161647         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.修改.zshrc文件布局,划分为aliases,commons,functions,envs,exports,plugins,分别对应别名,常规设置,函数,
         环境变量,输出,插件,便于zsh的配置管理;
       2.配置zsh,优化cp插件功能,增加zsh-syntax-highlighting插件增强命令行语法高亮功能(详见.zshrc文件);
       3.常规备份;
        
-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201608171609         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.修改.zshrc文件布局,删除plugins文件,增加plugins_customized文件,并将主题,插件等重要配置移回.zshrc文件,
         修复自动加载出错问题;
       2.常规备份;
        
-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201608191513         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.在.vimrc中对NERDTree插件进行重新配置;
        
-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201608202230         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.编译安装最新版的grep(V2.25);
       2.编辑.zshrc对应的aliases文件,添加对tar,xz格式的默认打开方式,修改grep默认启动别名为V2.25版;

-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201608230903         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.参考GitHub网友建议修改.zshrc布局,将commons和plugins的内容移至source之前,然后删除该两个和plugins_customized文件;
       2.编译并利用gdb单步调试iperf3源代码,找到其对应的二进制码;

-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201608241031         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.升级VirtualBox至5.1.4.r110228版本,并更新Ubuntu虚拟机的ExtensionPack,解决网络桥接不通问题;

-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201608251007         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.配置虚拟机多网卡及其静态IP地址,其中配置eth0为外网IP(192.168.1.223),eth1为内网IP(172.16.55.223);

-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201608261738         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.在.vimrc中对ycm插件进行重新配置,增加对函数,变量声明和定义的定位快捷键,增加vim启动时自动触发功能;
       2.安装增加vim-plugin-minibufexpl插件,增强对vim中的buffer管理功能,并进行一些操作的快捷键映射 ;

-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201608292055         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.从Github中获取个人对Linux/Ubuntu 14.04.01虚拟机的dotfiles的配置信息,并保持更新;
       2.常规备份;

-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201608302102         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.更新dotfiles,更新linux的.vimrc文件;
       2.从Github中获取个人对Linux/Ubuntu 14.04.01虚拟机的log-tracks,并保持更新;
       3.安装并配置vim-fugitive和 vim-unimpaired插件,增强vim中对Git的操作功能及对quickfix窗口的操作功能;

-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201608312112         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.更新dotfiles,更新linux的.vimrc文件;
       2.更新logs-track,同步更新github中的文档仓库;
       3.安装并配置session.vim插件,增强vim中的会话管理功能,安装vim-textobj-user和vim-textobj-entire插件,
         待深入学习使用;

-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201609011236         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.更新logs-track,同步更新github中的文档仓库;
       2.增加metalmac-git-database,对Linux虚拟机中的个人git仓库文档,代码等进行统一管理和归档;

-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201609012044         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.安装并配置DDD可视化调试器;
       2.apt-get update 常规更新与备份;
       3.更新logs-track,同步更新github中的文档仓库;

-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201609022103         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.apt-get update 常规更新与备份;
       2.在vms-git中添加session,对虚拟机的session进行管理记录;
       3.修改tmux的历史显示记录限制选项(history-limit);
       4.更新logs-track,同步更新github中的文档仓库;

-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201609062021         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.apt-get update 常规更新与备份;
       2.安装sysstat系统监测工具;
       3.更新logs-track,同步更新github中的文档仓库;

-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201609141602         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.apt-get update 常规更新与备份;
       2.更新logs-track,同步更新github中的文档仓库;
       3.编译安装Vim8.0版本,暂停使用vimgdb-for-vim7.4插件;

-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201609151124         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.apt-get update 常规更新与备份;
       2.更新logs-track,同步更新github中的文档仓库;
       3.获取vim的git版本,更新patch 8.0.0004,编译安装V8.0.0004版;

-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201609161416         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.更新logs-track,同步更新github中的文档仓库;
       2.获取vim的git版本,更新patch 8.0.0005;
       3.重新编译Vim 至8.0.0005版,修复Vim中缺少python支持的问题;
       4.在Vim中使用Vundle更新插件;
       5.下载最新的ycm-git包,并重新编译安装ycm插件;

-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201609182124         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.更新logs-track,同步更新github中的文档仓库;
       2.增加CapsLock与Ctrl快捷键转换功能,通过xmodmap实现;
       3.更新zsh配置,支持自启动用户登录时进行CapsLock与Ctrl的功能转换;

-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201609191047         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.更新logs-track,同步更新github中的文档仓库;
       2.配置vim环境,安装并配置command-t插件;
       3.更新vim配置,增加及修改vim-fugitive功能映射,;
       4.增加CapsLock与Ctrl快捷键转换功能,通过xmodmap实现;
       5.更新zsh配置,支持自启动用户登录时进行CapsLock与Ctrl的功能转换;

-----------------------------------------------------------------------------------------------------------

metalmac_ubuntu_140401_ws@201609211402         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.更新logs-track,同步更新github中的文档仓库;
       2.打上patch 8.0.0006补丁,重新编译vim更新至V8.0.0006版;
       3.更新.vimrc配置文件,更新vimrc文件,重新布局ycm插件配置内容;


metalmac_ubuntu_140401_ws@201609291246         {{{2
-----------------------------------------------------------------------------------------------------------

	更新如下：

       1.更新logs-track,同步更新github中的文档仓库;
       2.打上patch 6-17补丁,重新编译vim更新至V8.0.0017版;
       3.使用Vundle安装vim-cpp-enhanced-highlight和vim-fswitch插件,增强.cpp.h中语法高亮及接口跳转功能;

-----------------------------------------------------------------------------------------------------------
==========================================================================================================