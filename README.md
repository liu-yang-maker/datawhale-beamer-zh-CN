<p align="center"><img src="https://pic3.zhimg.com/v2-c5466f07fd7242632f1cf7ce19d722d2_xll.jpg"></p>

# `datawhale beamer` (LaTeX)
[datawhale](http://www.datawhale.club) Beamer (LaTeX) 模板（非官方版）

## 简介
* 集简洁、优雅、严肃的特性，用于报告展示的 LaTeX 模板，供大家自由使用，反馈意见请联系 [liuyang2020@amss.ac.cn](mailto:liuyang2020@amss.ac.cn)；
* 查看 \[[输出样例](https://github.com/liu-yang-maker/datawhale-beamer-zh-CN/blob/main/main.pdf)\] \[[下载](https://github.com/liu-yang-maker/datawhale-beamer-zh-CN/archive/refs/heads/main.zip)\]


## 安装 Tex Live
* [官方安装](https://www.tug.org/texlive/)
* [清华大学开源软件镜像站](https://mirrors.tuna.tsinghua.edu.cn/CTAN/systems/texlive/)

## 在线使用
* 推荐：[Overleaf](https://www.overleaf.com) 在线 LaTeX 编辑器

## 使用方法
* 离线使用
  - 手动方式：安装完 TeX Live 之后，先用 `xelatex` 对 `main.tex` 编译一次，再用 `biber` 编译一次，最后用 `xelatex` 连续编译两次；
  - 自动方式：`./build.sh xb main`
* 在线使用：
  1. 下载此模板的压缩包并上传至 Overleaf 的 Project；
    - 模板 \[[下载页面](https://github.com/liu-yang-maker/datawhale-beamer-zh-CN)\]
    - `New Project` - `Upload Project` - `Select a .zip file`
  2. 编译器选项设置为 `XeLaTeX`，然后重新编译即可。
    - `Menu` - `Settings` - `Compiler` - `XeLaTeX`
    - `Recompile`
