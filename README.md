# Steamlit-translate-to-zh-CN
将官方项目 https://docs.streamlit.io/   中 Get Started 和 Tutorials 译成中文 Markdown 版本

译者注：

1. Github Markdown 预览下大部分超链接会失效（为了适应 GitHub Pages 而不得不牺牲的策略），所以，强烈建议各位读者在 <https://fmw666.github.io/Steamlit-translate-to-zh-CN/> 进行阅读。

1. 本次项目的翻译仅个人爱好所作，并不带有任何商业行为，也杜绝任何未经许可的摘抄者用于其个人利益。

1. 本次项目仅作翻译，以供中文读者能更好的阅读。详情内容或权威性文章请参考原项目 <https://docs.streamlit.io/>

1. 回答访问者的问题，为什么不用机翻？因为想熟练自己的英文技能、和完整的阅读一次原文教程、并且尝试第一次独立完成的英文教程翻译。

---

# 欢迎来到 Streamlit

Streamlit 是一个开源 Python 库，它可以让用户很简单的搭建属于自己的用于机器学习和数据分析的 Web 应用。

想要使用它，只需要使用 `pip install streamlit` 命令进行下载，然后在脚本文件中进行导入，编写您的代码，最后用 `streamlit run [filename]` 在命令行运行您的 Python 脚本。当您在写代码时，Streamlit 会实时监视每次您的保存和更新对于 Web 应用程序的变化。代码从脚本文件自上而下开始运行，并且总是从一个干净并且不需要回调函数的状态开始。它是一个简单使用但功能十分强大的 app 模型可以让您难以置信地快速构建出丰富地 UI 视图。想要跟多的了解 Streamlit 是如何工作的，查看 [Main concepts](https://docs.streamlit.io/main_concepts.html)。

根据下面步骤可以让您在至少 5 分钟内构建出一个可以运行的 app。

1. 确保您已经有 [Python 2.7.0 / Python 3.6.0](https://www.python.org/downloads/) 或更高的版本安装在了您的计算机上。

1. 使用 [PIP](https://pip.pypa.io/en/stable/installing/) 命令来安装 Streamlit：

    ```bash
    $ pip install streamlit
    ```

1. 启用 hello world 项目（默认提供）：

    ```bash
    $ streamlit hello
    ```

1. 就是如此！在接下来的几秒钟里，这个样例项目就会在您默认的浏览器中打开新的窗口来进行展示。

## Get started

学习如何去使用 Streamlit，最简单的方式就是去动手亲自试验。我们的 [get started guide](Get%20started) 将带您学习如何构建最基本的 Streamlit 项目。

## 加入社区

最快得到帮助的方法就是联系我们的社区论坛。我们十分乐意听到使用者们提出的问题、想法或者一些 bugs——请与大家分享！
