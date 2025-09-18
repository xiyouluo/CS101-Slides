---
theme: academic
highlighter: shiki
title: CS101 Slide
info: |
  CS101 2025 Fall Slides
  Presented by xiyouluo
presenter: false
titleTemplate: '%s'
class: text-center
drawings:
  persist: false
transition: fade-out
mdc: true
layout: cover
---

# CS101 Slides {.font-bold.text-sky}

物理学&计算机科学与技术双 罗熙佑{.!text-gray-500}

感谢[卓致用学长]((https://github.com/zhuozhiyongde/Arthals-ICS-Slides))的 [ICS-Slides](https://github.com/zhuozhiyongde/Arthals-ICS-Slides) 模版

一个试图帮助大家解决初识编程时遇到的诸多问题的 Slides，基于 [Slidev](https://sli.dev/)

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/zhuozhiyongde/Arthals-ICS-Slides" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-gray-800 !dark:hover:text-gray-200">
    <carbon-logo-github />
  </a>
</div>

---

# 目录

0. 从零开始的计算机生活
1. 电脑的硬件与使用常识, 电脑选购  
2. "科学上网"  
3. 环境配置  
4. 作业提交, Markdown
5. Git, Github  
6. Shell, Server, Linux  

7. 如何学习计概&答疑

---

# 0. 从零开始的计算机生活 {.text-sky .font-bold}

## 问卷统计结果

<img src="https://raw.githubusercontent.com/xiyouluo/md_images/main/images/202509181451685.png" style="zoom:25%;" />

---

# 0. 从零开始的计算机生活 {.text-sky .font-bold}

## 问卷统计结果

<img src="https://raw.githubusercontent.com/xiyouluo/md_images/main/images/202509181452742.png" style="zoom:25%;" />

---

# 0. 从零开始的计算机生活 {.text-sky .font-bold}

## 问卷统计结果

<img src="https://raw.githubusercontent.com/xiyouluo/md_images/main/images/202509181453360.png" style="zoom:25%;" />

---

# 0. 从零开始的计算机生活 {.text-sky .font-bold}

## 问卷统计结果

<img src="https://raw.githubusercontent.com/xiyouluo/md_images/main/images/202509181836209.png" style="zoom:25%;" />

---

# 0. 从零开始的计算机生活 {.text-sky .font-bold}

- 零基础?  你来对了.
- 准备时间仓促, 水平有限, 任何错误与不准确欢迎大家现场举手打断指正!

---

# 1. 电脑的硬件与使用常识, 电脑选购 {.text-sky .font-bold}

## 硬件

- 装机八大件: 

  **CPU**

  **GPU / 显卡**

  **内存**

  **硬盘**

  主板

  电源

  散热

  机箱  

---

# 1. 电脑的硬件与使用常识, 电脑选购 {.text-sky .font-bold}

## 使用

0. 善用搜索 (搜索引擎与大语言模型 LLM)
1. (Windows 系统) C 盘<img src="https://raw.githubusercontent.com/xiyouluo/md_images/main/images/202509181314118.png" width="200" height="200">
2. 杀 ~~(liu)~~ 毒 ~~(mang)~~ 软件?

---

# 1. 电脑的硬件与使用常识, 电脑选购 {.text-sky .font-bold}

## 电脑选购

0. 性能 vs. 价格
1. 你的需求 (我只爱学习! 我要打游戏! ~~我要在本地部署大模型!~~)
2. Windows vs. macOS
3. 某些专业需要 **macOS 不兼容** 的软件!

---

# 2. "科学上网" {.text-sky .font-bold}

## 这是啥<del>, 好吃吗</del>?

- The Great Firewall
- VPN

---

# 2. "科学上网" {.text-sky .font-bold}

## 这是啥<del>, 好吃吗</del>?

- 代理工具
- 配置文件与订阅地址
- [Clash 生态](https://github.com/xiyouluo/CS101-Slides/blob/main/supplement/Clash_Status.md)

---

# 2. "科学上网" {.text-sky .font-bold}

## 怎么<del>吃</del>用?

0. 推荐 Clash Party, 即使你使用 [WallessPKU](https://wallesspku.space/).
1. 授人以渔: ~~暂时不能给你明确的答复, 这个需要你自己衡量.~~ 类似问题请**善用搜索**, 尤其是查看[官方文档](clashparty.org)!  (https://clashparty.org)

---

# 2. "科学上网" {.text-sky .font-bold}

## 授人以鱼

0. 根据系统架构下载 Clash Party, 可以**善用搜索**确定自己的系统架构. 目前一般的 Windows 系统笔记本与老款 MacBook (Intel) 为 x86-64 (x64) 架构, 新款 Macbook (Apple Silicon) 为 arm64 架构. 

1. 众所周知, ~~卡拉赞毕业才能打卡拉赞~~科学上网的工具需要科学上网才能下载... 

   👇🏻请使用北大网盘输入 IGNB 提取. 

![](https://raw.githubusercontent.com/xiyouluo/md_images/main/images/PKUDisk_CS101)



---

# 2. "科学上网" {.text-sky .font-bold}

## 授人以鱼

3. 获取你的订阅地址
   - 按照 [WallessPKU](https://wallesspku.space/) (https://wallesspku.space/) 的指导获取学校 (非官方) 提供的订阅地址.
   - 自行购买.
4. 利用订阅地址导入配置文件, 选择节点, 打开 Proxy 按钮, 开始愉悦地使用 ~~Youtube 和 Reddit~~ Google 和 Github.
5. (Optional) 建议开启 TUN 模式, 结合使用覆写 (override) 更好地管理你的代理规则.

---

# 2. "科学上网" {.text-sky .font-bold}

## 授人以鱼

- **TUN 模式**会在系统中创建一个虚拟网卡, 将所有 IP 层的流量都引导到代理程序.

- 相比 **HTTP/SOCKS 代理** 只能对单个应用（如浏览器）生效, TUN 可以让 **整个系统**的流量（包括不支持代理的应用、游戏客户端、命令行工具等）都通过代理.

- 更适合北大宝宝体质的覆写配置: 

  https://raw.githubusercontent.com/xiyouluo/clash-override/main/override.yaml.

---

# 3. 环境配置 {.text-sky .font-bold}

## 我需要安装什么?

- Python 解释器
- IDE
- 第三方库 (Git; numpy, matplotlib, pytorch)

---

# 3. 环境配置 {.text-sky .font-bold}

## Python 解释器

- 大家*应该*已经了解到 Python 是一门**解释型语言**, 为了使用 Python 进行编程, 我们必须安装 Python ~~(好像是废话)~~.
- Windows 系统可以在 [**Python 官网**](https://www.python.org/downloads/) (https://www.python.org/downloads/) 下载最新版本并安装, 或在 Microsoft Store 中搜索 Python 下载安装.
- mac OS 早期可能自带了 Python 2, 不过我们现在学习和使用的都是 Python 3; 你同样可以在 [**Python 官网**](https://www.python.org/downloads/) (https://www.python.org/downloads/) 下载最新版本并安装; 熟悉 CLI (Command Line Interface) 的同学可以先安装 homebrew, 再运行`brew install python`安装.

---

# 3. 环境配置 {.text-sky .font-bold}

## *Homebrew

- Homebrew 是 macOS 上最流行的包管理器 (package manager), 它的作用类似 Linux 的 apt 或 yum, 可以方便地安装、升级、卸载软件包和命令行工具.

- Homebrew 安装 Python:

  ✅ 安装/更新/卸载方便

  ✅ 管理多个版本简单

  ✅ 易于集成到命令行工具和自动化脚本

  ❌ 初学者可能不会使用 CLI, 或不会把 Homebrew 加入 PATH

---

# 3. 环境配置 {.text-sky .font-bold}

## IDE (Integrated Development Environment)

- IDE 为我们提供了增强文本编辑 (代码高亮和补全等)、程序运行与调试 (Debug) 等功能.
- 目前 (大概) 最常用的 IDE 是 Visual Studio Code, 常常称为 VS Code; 它功能齐全, 支持多种语言, 几乎可以满足你在编程中的所有需要; *当然严格来说它本身只是一个文本编辑器, 通过插件可以扩展成 IDE 的效果; 我们此处不讨论它是不是 IDE 的问题, 只为给零基础同学解释一个写代码的工具.*
- 就 Python 语言而言, 我们还需要了解 Pycharm 和 Anaconda.
  - Pycharm 是一个专门的 Python IDE.
  - Anaconda 是一个 Python 发行版本, 集成 Python 解释器、conda 包管理器 (管理 Python 编程环境的里的包及其版本)、Spyder (Python IDE)、Jupyter Notebook (交互式笔记本) 等工具.

---

# 3. 环境配置 {.text-sky .font-bold}

## <del>听不懂, 你就说我该干嘛</del>IDE 的选择

- 平时的学习中, 你可以使用任何你喜欢的编程环境.
- 就本课程期末机考而言, 个人**推荐**使用 Pycharm.
  - VS Code 需要插件才能成为 IDE (才能帮你运行和调试); 考试时机房断网 + 你不知道上一个使用这台机子的同学对它做了什么. ![](https://raw.githubusercontent.com/xiyouluo/md_images/main/images/202509181308861.png)
  - Spyder 无法粘贴多行输入.

---

# 3. 环境配置 {.text-sky .font-bold}

## <del>听不懂, 你就说我该干嘛</del>IDE 的选择

- 当你以后接触一些需要写 lab/project/大作业, 以及日后自己在业界写工程/在学术界写科研项目的代码时:
  - 一个常见的场景:  项目 A Python=3.8; 项目 B Python=3.9
  - 虚拟环境, 包管理器 conda
  - Anaconda is all you need!

---

# 3. 环境配置 {.text-sky .font-bold}

## <del>听不懂, 你就说我该干嘛</del>IDE 的安装

- 授人以渔: 略.

---

# 3. 环境配置 {.text-sky .font-bold}

## IDE 的安装 - 授人以鱼

- Pycharm 目前已不区分社区版/专业版, 直接在[官网下载](https://www.jetbrains.com/pycharm/)统一版本: https://www.jetbrains.com/pycharm/
- 使用 edu 邮箱**凭借北京大学学生身份**可申请 [student-pack](https://www.jetbrains.com/academy/student-pack/): https://www.jetbrains.com/academy/student-pack/
- 安装过程与使用演示.
- <span style="background-color: yellow; color: black;">注: 上机课时不小心遗漏了运行与 Debug 的演示, 请有需要的同学"善用搜索"解决或者联系我; 另外目前机房的 Pycharm 不能使用 Debug 的问题已请闫老师向计算中心反映.</span>

---

# 4. 作业提交, Markdown {.text-sky .font-bold}

## 作业提交网站, 提交格式

- 本班不使用教学网, 提交网站: [Canvas](https://pku.instructure.com/login/canvas) (https://pku.instructure.com/login/canvas)
- 提交格式: 
  - 一份 .md 文件, 包含你的源码;
  - 一份由该 .md 文件**导出**的 .pdf 文件.

---

# 4. 作业提交, Markdown {.text-sky .font-bold}

## Markdown 又是啥? <del>好吃吗?</del>

- Markdown 是一种**轻量级**标记语言, 它允许人们使用易读易写的纯文本格式编写文档, 然后转换成有效的 XHTML (或者HTML) 文档;
- .md 是这种文档的后缀, 类似你以前使用 Word 进行文本编辑时的 .doc 或 .docx;
- Markdown 文档的编辑方式与 Word 文档不同;

---

# 4. 作业提交, Markdown {.text-sky .font-bold}

## Markdown 软件

- Markdown 不是软件, 你需要一个支持该格式的文本编辑器来使用它, 例如 Typora 和 Obsidian, 当然你也可以直接在 VS Code 中安装插件来**渲染** Markdown 文件.
- 怎么选择:
  - Typora: 容易上手, 实时渲染, 所见即所得; 收费.
  - Obsidian: 有一定学习成本, 但功能更强大, 接近实时渲染 (但你仍然可能需要切换编辑与阅读模式); 免费.
  - VS Code + 插件: 写代码, 渲染在另一边; 免费.

---

# 4. 作业提交, Markdown {.text-sky .font-bold}

## Markdown 使用

- 刚接触时你可以使用工具栏里的 Format 等选项帮助你设置格式.
- 但你逐渐熟悉 Markdown 的常用语法后, 你会发现**轻量级**编辑的好处.

---

# 4. 作业提交, Markdown {.text-sky .font-bold}

## 语法简介

```markdown
# Markdown 语法简介

## 1. 标题
# 一级标题
## 二级标题
### 三级标题

## 2. 文本样式
**加粗**
*斜体*
~~删除线~~
==高亮== (有些编辑器不支持, 或没有打开该功能)

## 3. 列表
- 无序列表项 1
- 无序列表项 2
  - 子列表项

1. 有序列表项 1
2. 有序列表项 2
```

---

# 4. 作业提交, Markdown {.text-sky .font-bold}

## 语法简介

````markdown
## 4. 链接与图片
[官网下载](https://www.jetbrains.com/pycharm/)

![图片描述](https://example.com/image.png)

## 5. 引用
> 这是一个引用

## 6. 代码
行内代码：`print("Hello, world!")`

代码块：
```python
def hello():
    print("Hello, Markdown!")
```
````

---

# 4. 作业提交, Markdown {.text-sky .font-bold}

## 6. 代码

行内代码：`print("Hello, world!")`

代码块：
```python
def hello():
    print("Hello, Markdown!")
```

---

# 4. 作业提交, Markdown {.text-sky .font-bold}

## 语法简介

```markdown
## 7. 公式
行内公式：$\LaTeX$, $\vec{F} = m \vec{a}$

行间公式：

$$
i \hbar \frac{\partial}{\partial t} \Psi(\mathbf{r}, t)
= \left[ -\frac{\hbar^2}{2m} \nabla^2 + V(\mathbf{r}, t) \right] \Psi(\mathbf{r}, t)
$$
```

---

# 4. 作业提交, Markdown {.text-sky .font-bold}

## 7. 公式

行内公式：$\LaTeX$, $\vec{F} = m \vec{a}$

行间公式：

$$
i \hbar \frac{\partial}{\partial t} \Psi(\mathbf{r}, t)
= \left[ -\frac{\hbar^2}{2m} \nabla^2 + V(\mathbf{r}, t) \right] \Psi(\mathbf{r}, t)
$$

---

# 5. *Git, Github {.text-sky .font-bold}

## Git 是什么

- Git 是一个 **分布式版本控制系统 (VCS)**. 它能帮你:
  - 记录代码的修改历史 (可随时回到过去的版本);
  - 多人协作开发时避免文件互相覆盖;
  - 管理分支 (branch), 方便尝试新功能, 失败了也不影响主项目.

---

# 5. *Git, Github {.text-sky .font-bold}

## Github 是什么

- GitHub 是一个基于 Git 的 **代码托管平台**. 它能帮你:
  - 把本地 Git 仓库里的代码推送到云端, 方便备份和分享;
  - 与他人协作开发, 进行代码审查 (Pull Request);
  - 展示你的开源项目, 建立个人作品集.

---

# 5. *Git, Github {.text-sky .font-bold}

## Git 基础操作

- clone: `git clone https://github.com/xiyouluo/CS101-Slides.git`
- add: `git add .`
- commit: `git commit -m 'Your message.'`
- push : `git push`

---

# 6. *Terminal, Shell, Linux, Server {.text-sky .font-bold}

## 终端 (Terminal) 与命令行 (Command Line)

- **终端 (Terminal)**  
  - 早期是接在大型计算机上的键盘+显示器硬件设备  
  - 现在是电脑上的一个软件窗口，用来输入命令、显示结果  
  - 例子: Windows 的 PowerShell / CMD，macOS 的 Terminal 应用

- **命令行 (Command Line / CLI)**  
  - 一种**基于文本的交互方式**, 通过输入命令与计算机通信  
  - 相比图形界面 (GUI), 命令行更高效、可自动化、适合远程操作

---

# 6. *Terminal, Shell, Linux, Server {.text-sky .font-bold}

## Shell 是什么?

- **Shell** 是操作系统提供的命令行界面 (CLI), 让用户与**内核**交互.
- 常见的 Shell:  
  - **bash** (大多数 Linux 默认)  
  - **zsh** (macOS 默认，从 Catalina 起)  

---

# 6. *Terminal, Shell, Linux, Server {.text-sky .font-bold}

## 常用 Shell 操作

```bash
# 查看目录/文件
ls        # 列出文件
pwd       # 查看当前路径
cd ..     # 返回上一级目录

# 文件操作
touch a.py      # 创建空文件
mkdir folder    # 创建目录
rm a.py         # 删除文件
rm -r folder    # 删除文件夹 (递归)
```

---

# 6. *Terminal, Shell, Linux, Server {.text-sky .font-bold}

## Linux 

- **Linux** 是一种操作系统内核, 广泛用于服务器与科研计算环境.
- 常见发行版:
  - Ubuntu (入门友好)
  - CentOS (服务器常用)
  - Debian, Arch, etc.

---

# 6. *Terminal, Shell, Linux, Server {.text-sky .font-bold}

## Server 

- **服务器 (Server)**: 一台 7x24 小时运行的计算机, 可以提供远程计算/存储/服务.

- 我们通常使用 **SSH (Secure Shell)** 远程登录:

  ```bash
  ssh username@server_address
  ```

- 有需要可以参照北大 Linux 俱乐部提供的 [Clab 平台](https://clab.pku.edu.cn)的教程 (https://clab.pku.edu.cn) 连接服务器并使用.

---

# 8. 如何学习计概&答疑 {.text-sky .font-bold}

- 闫老师讲的有关云主机的没听懂
- 想学习下终端怎么用
- 想了解零基础自学语法的流程和计划，以及计概B考试的知识点/题型概览。谢谢啦
- 虚拟机是什么，可以做什么？命令行怎么用？
- 计算机完全零基础，比如不会创建文件等
- 虚拟机该怎么使用
- 语法怎么学啊啊啊
- 一些常用的库 还有经常在题目里出现的不定行输入，EOFError是啥，sys.readin又是啥 谢谢！

---

# 8. 答疑

- 计算机理论知识应该怎么学
- 怎么学会一些像题解里面那样的简洁巧妙的方法（自己写总是出各种各样的错误一道题要做好久
- 要如何掌握语法
- 虚拟机怎么用 可视化的那个网站怎么用 md文件编辑器有没有免费的以及怎么获取
- 非编程的计算机基础知识如网络，协议，格式，计算机硬件等是否会介绍
- 如何学习语法和算法
- 基础知识教学
- 如何在ai时代学好计概，该往哪里花力气？copilot教育认证怎么弄？
- 语法什么时候教呢

---

# THANKS {.text-sky .font-bold}

Made by xiyouluo with ❤️ ~~and hair~~. {.mb-4}  

[GitHub](https://github.com/xiyouluo) · Wechat

<img src="https://raw.githubusercontent.com/xiyouluo/md_images/main/images/202509181422881.png" width="200" height="200">
