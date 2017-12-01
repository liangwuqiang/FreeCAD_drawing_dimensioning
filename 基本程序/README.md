FreeCAD_drawing_dimensioning
============================
>FreeCAD 工程图标注

Drawing dimensioning workbench for FreeCAD v0.15.4576 and newer.
>工程图标注工作台用于 FreeCAD v0.15.4576 及以上版本。

Although the original programmer of the workbench (hamish) is no longer active, 
this workbench is still actively maintained.  
Feel free to post issues and pull requests.
>尽管原来的工作台 (hamish) 程序不再更新了，
>但是这个工作台仍在积极的维护中。
>随意 post issues 和 pull requests。

Linux Installation Instructions
-------------------------------
>Linux环境下的安装指南

For Ubuntu (Linux Mint) we recommend adding the community ppa to your systems software resources 
and install, via the sysnaptic package manager, the desired addon.
>对于 Ubuntu (含 Linux Mint) 系统，我们建议将社区 ppa 添加到你的系统的软件源中，
>通过 synaptic 新立得软件包管理器来安装所需的插件。

Refer here for more information:
https://launchpad.net/~freecad-community/+archive/ubuntu/ppa
>这里有更多的参考信息：

On other Linux distros try to install manually via Terminal and git, 
replacing **apt-get** if not installed, with your distro's package manager:
>在其他 Linux 发行版本中，通过终端和 git 进行手动安装：
>（使用你的 Linux 发行版本的软件包管理器 替换掉下面的 **apt-get**）

```bash
$ sudo apt-get install git python-numpy python-pyside
$ mkdir ~/.FreeCAD/Mod
$ cd ~/.FreeCAD/Mod
$ git clone https://github.com/hamish2014/FreeCAD_drawing_dimensioning.git
```

Once installed, use git to easily update to the latest version:
>安装成功后，使用 git 可以很容易地更新到最新版本：

```bash
$ cd ~/.FreeCAD/Mod/FreeCAD_drawing_dimensioning
$ git pull
$ rm *.pyc
```

Windows Installation Instructions
---------------------------------

Please use the FreeCAD-Addons-Installer provided here:
https://github.com/FreeCAD/FreeCAD-addons

For more in-depth information refer to the corresponding tutorial on the FreeCAD-Homepage:
http://www.freecadweb.org/wiki/index.php?title=How_to_install_additional_workbenches

Mac Installation Instructions
-----------------------------

Copy or unzip the drawing dimensioning folder to the directory *FreeCAD.app*/Contents/Mod
where *FreeCAD.app* is the folder where FreeCAD is installed. (thanks PLChris)

For more in-depth information refer to the corresponding tutorial on the FreeCAD-Homepage:
http://www.freecadweb.org/wiki/index.php?title=How_to_install_additional_workbenches

Wiki
----
>维基百科

For instructions on usage of the workbench refer to the wiki (link on top of the page)
[https://github.com/hamish2014/FreeCAD_drawing_dimensioning/wiki]
>有关该工作台的使用说明 参考这个wiki。