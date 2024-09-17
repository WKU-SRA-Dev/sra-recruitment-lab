# SRA软件部2024招聘实验室

此文档中文为AI与分支所有者XinzhiBao-Stefan混合翻译，尽量还原了原有的Markdown样式内容。若有任何错误，敬请谅解，推荐阅读[英文文档](https://github.com/WKU-SRA-Dev/sra-recruitment-lab)。

欢迎来到SRA软件部门2024招聘实验室！本仓库旨在评估您的学习能力。请注意，我们不在此测试编程技能，因此请放松心情，专注于当前任务。

在整个活动中，我们将从多个方面对您进行评判。若遇到问题，请记录下您的解决过程。您也可以在群聊中向团队成员求助。您的有效沟通能力和协助他人的表现将作为申请评估的一部分。

## 需求
在开始练习之前，请确保您已进行以下设置：
- Git：确保已在计算机上安装并正确配置 Git。这意味着您应该设置您的用户信息 （例如您的电子邮件和姓名）。
>参考教程：[git and github, en](https://www.youtube.com/watch?v=hrTQipWp6co)
>或 [一小时git教程, zh-CN](https://www.bilibili.com/video/BV1HM411377j/?spm_id_from=333.337.search-card.all.click)。

- GitHub账户：参与此次实验需拥有GitHub账户，如尚未注册，请创建[此处](https://github.com/join)一个。
- 技术栈： 确保您的计算机上安装了必要的工具和软件。
- 任何 IDE 或代码编辑器：如果您愿意，您可以选择任何代码编辑器，我们建议您使用 vscode，它是开源和轻量级的。
- 了解基本的 shell 命令和 Markdown：需要熟悉基本的 shell 命令和 Markdown （MD） 语法。
>参考教程：
> [30分钟Shell光速入门教程, zh-CN](https://www.bilibili.com/video/BV17m411U7cC/?spm_id_from=333.337.search-card.all.click).   
> 关于 MD 语法，问 [gpt](https://chatgpt.com/) 就行。多写多看，也就会了，没必要专门去学，看教程。

## 说明
若你曾参与过开源社区贡献或进行过个人项目，且申请的是程序员职位，可免除部分实验任务。
### 部长与项目负责人
1. 创建Markdown文件：在本仓库中创建一个 `your-repo-name.md` 文件。
2. 链接你的仓库：在Markdown文件中，提供指向你仓库的链接。
3. 寻找项目成员：确保他人能在本地部署你的项目并基于其进行修改。为此，提供一个简短的教程，指导如何操作你的项目。此外，你需要找到人来部署你的项目，这包括说服他们使用你的项目，协助解决他们遇到的问题，并跟踪他们的进展。
### 代码编写者
1. 请求权限：
	- 请求许可。将您的 github 帐户用户名留给我们。这是为了让您轻松地将自己的分支推送到我们的仓库。
2. 创建您自己的 `git branch`：
	- 在开始代码历程之前。在项目根目录 （`path-to-your-project/`） 中，您刚刚从第 1 步中克隆了它，创建一个名为 （`position/your-name` 如`coder/rupert`） 的新分支
3. 创建一个名为 projects 的目录（可选）：
	如果要克隆多个项目，请在此存储库的主目录中创建一个名为 `projects` 的文件夹。然后，你可以用它来记录你对不同 repo 的编码过程。如果你只想克隆一个项目并进行修改，建议你直接添加你的 `your-repo-name.md`。
	```
     .
     ├── README.md
     └── projects
         ├── react-documentations-website.md
         ├── wku-sra-wiki.md
         └── ...
     
      
	```
	或者是
	```
      .
      ├── README.md
      └── react-documentations-website.md
      
	```
4. 查找并克隆开源项目：
- 从以下选项中选择一个开源项目，因为它们通常比其他项目更容易部署，并且不要假定您之前具有编程知识。如果您愿意，您可以部署您选择的任何项目，或者如果您正在申请项目负责人或部长职位，则可以选择您自己的项目：
	- [React 文档网站](https://github.com/reactjs/react.dev)
	- [Flutter 文档网站](https://github.com/flutter/website)
- 将项目分叉到你[自己的仓库](https://github.com/WKU-SRA-Dev/website)，就像我们向你展示的一样。
- 将所选项目 ***从你自己的仓库*** 克隆到本地，您将基于该存储库进行开发，建议您使用另一个目录来克隆此存储库，因为这将使您的 git 仓库保持清晰。
	如果您位于 lab 目录中，则在前面的示例中：
	```bash
   cd ..
   git clone git@github.com:WKU-SRA-Dev/website.git
   ```
	这个可能是我们lab的仓库：
   ```
   ~/sra-recruitment-lab
   ```
	这个可能是你仓库的克隆：
	```
   ~/website
   ```
   此外：~ 表示当前用户的主目录。
	你可以在各自的项目仓库中找到如何在本地部署该项目的说明。
5. 根据您克隆的项目进行更改：
	- 修改克隆的项目，以展示您快速理解和使用不熟悉的代码库的能力。
	- 获取更改的屏幕截图。
	- 返回到实验室项目
	- 在 `*.md` 文件中总结您所做的和学到的内容，或者您可以使用它来记录您的编码过程中发生的任何内容
将这些屏幕截图保存在此存储库根目录中名为 `img` 的单独文件夹中。文件夹结构应如下所示：
```
     .
     ├── README.md
     ├── projects
     │   ├── react-documentations-website.md
     │   ├── wku-sra-wiki.md
     │   └── ...
     │
     └── img
         ├── change-the-home-page.png
         ├── others.png
         └── ...
```
或者是
```
      .
      ├── README.md
      ├── react-documentations-website.md
      └── img
          ├── change-the-home-page.png
          ├── others.png
          └── ...
```
6. 提交你的更改到你的forked仓库：
	- 将你的更改提交到你克隆的项目仓库（你将其作为你正在开发的项目，而不是实验室（`path-to-your-cloned-repo/`）。
	- 将你的提交推送到你自己的远程仓库（forked仓库）。
>你的提交消息应该清楚地描述了你做了什么。提交消息会显示你的提交时间，所以在实验室内持续贡献。不要试图在2小时内完成：）
![commit](img/commit1.png)
7. 提交此实验：
- 确保你处于自己的分支，如`coder/rupert`
- 提交所有更改
- 推送到我们的实验仓库，确保已接受我们的合作邀请
### 提交样例
[样例](https://github.com/WKU-SRA-Dev/sra-recruitment-lab/tree/coder/stewie)
### 额外奖励部分
上述任务旨在评估您学习不熟悉主题的能力，尤其是在您之前可能没有编程经验的情况下。以下是额外的奖励任务。虽然它们不是我们选拔过程的主要标准，但这些任务中的出色工作可以让您在竞争激烈的环境中与同行区分开来。
- 为此存储库设置`.devcontainer`。您需要提供基础 Linux 映像;建议使用 Alpine，因为它重量轻。然后，帮助没有 Unix 系统的 Peer 节点使用此 devcontainer。您需要将配置文件贡献给 main 分支。Git 冲突可能随时发生，因此您必须知道如何解决它们并帮助您的对等方解决这些冲突。
- 帮助您的同行，无论是通过群聊还是私信，都将始终提高您收到我们录取的机会。