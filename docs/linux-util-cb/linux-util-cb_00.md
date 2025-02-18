# 前言

《Linux 实用工具手册》展示了如何解决 Linux 计算机上的典型问题。信息以“配方格式”提供，允许用户快速高效地找到所需的主题。执行任务的步骤得到了清晰的解释并经过了测试以确保准确性。还有一个关于 shell 脚本的部分。

# 本书涵盖内容

第一章，使用终端/命令行，介绍了如何充分利用 Linux 命令行。

第二章，桌面，介绍了 Linux 可用的一些桌面环境。

第三章，文件和目录，解释了文件、目录以及如何管理它们。

第四章，网络和互联网，涵盖了连接性以及连接性中断时如何修复。

第五章，权限、访问和安全，简要概述了 Linux 安全功能。

第六章，进程，解释了如何在 Linux 中管理进程。

第七章，磁盘和分区，简要介绍了磁盘管理。

第八章，使用脚本，介绍了如何在 Linux 中编写脚本。

第九章，使用 Cron 自动化任务，解释了如何自动运行作业。

第十章，内核，介绍了如何为您的系统制作自定义内核。

附录 A，Linux 最佳实践，展示了如何像专业人士一样设置和运行您的系统。

附录 B，寻找帮助，涵盖了快速定位所需信息。

# 您需要为本书做好准备

要跟随本书中的示例，您需要在计算机上运行主流 Linux 发行版。作者使用了 Red Hat 的 Fedora 来创建本书以及示例和脚本。但是，任何发行版都应该可以正常工作。请注意，大多数可以从制造商的网站免费下载和安装。

# 本书适合对象

本书适用于希望了解更多关于 Linux 的有些经验的计算机用户。该配方格式旨在允许快速访问经常出现的典型任务。

# 约定

在本书中，您会发现一些文本样式，用于区分不同类型的信息。以下是一些这些样式的示例，以及它们的含义解释。

文本中的代码、数据库表名、文件夹名、文件名、文件扩展名、路径名、虚拟 URL、用户输入和 Twitter 句柄显示如下：“我们可以通过使用`include`指令包含其他上下文。”

任何命令行输入或输出都以以下形式书写：

```
export PS1=”screen$WINDOW \h \u \w \$ "
```

**新术语**和**重要单词**以**粗体**显示。例如，屏幕上看到的单词，如菜单或对话框中的单词，会以这种形式出现在文本中：“点击**下一步**按钮会将您移至下一个屏幕”。

### 注意

警告或重要提示会以这种形式出现在一个框中。

### 提示

提示和技巧会以这种形式出现。

文本部分的命令将以这种形式指示：运行`cd /tmp`

# 读者反馈

我们始终欢迎读者的反馈。请让我们知道您对本书的看法——您喜欢或不喜欢的地方。读者的反馈对我们开发您真正受益的标题非常重要。

要向我们发送一般反馈，只需发送电子邮件至`<feedback@packtpub.com>`，并在消息主题中提及书名。

如果有您擅长的话题，并且您有兴趣撰写或为书籍做出贡献，请参阅我们的作者指南[www.packtpub.com/authors](http://www.packtpub.com/authors)。

# 客户支持

现在您是 Packt 书籍的自豪所有者，我们有许多事情可以帮助您充分利用您的购买。

## 勘误

尽管我们已经尽一切努力确保内容的准确性，但错误确实会发生。如果您在我们的书中发现错误——也许是文本或代码中的错误——我们将不胜感激地向我们报告。通过这样做，您可以帮助其他读者避免挫折，并帮助我们改进本书的后续版本。如果您发现任何勘误，请访问[`www.packtpub.com/submit-errata`](http://www.packtpub.com/submit-errata)报告，选择您的书，点击**勘误提交表**链接，并输入您的勘误详情。一旦您的勘误经过验证，您的提交将被接受，并且勘误将被上传到我们的网站上，或者添加到该标题的勘误列表中的任何现有勘误下的勘误部分。您可以通过从[`www.packtpub.com/support`](http://www.packtpub.com/support)选择您的标题来查看任何现有的勘误。

## 盗版

互联网上的版权盗版是所有媒体的持续问题。在 Packt，我们非常重视版权和许可的保护。如果您在互联网上发现我们作品的任何非法副本，请立即向我们提供位置地址或网站名称，以便我们采取补救措施。

请通过链接到涉嫌盗版材料的电子邮件`<copyright@packtpub.com>`与我们联系。

我们感谢您在保护我们的作者和为您带来有价值的内容方面的帮助。

## 问题

如果您在书的任何方面遇到问题，请通过`<questions@packtpub.com>`与我们联系，我们将尽力解决。
