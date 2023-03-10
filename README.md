# 使用说明
## 背景
- 目的：为方便在cac网站上展示各课题的内容，同时统计各单位各课题的完成情况，选择使用github来管理当前工作流
- 用法：项目负责人可以督促课题负责人上传课题，课题负责人可以将每月课题汇报给项目负责人
- 仓库：[ccnu-lab/monthly_reports](https://github.com/ccnu-lab/monthly_reports)

## 业务流程图
- Cac-Github分级管理工作流
<img width="722" alt="image" src="https://user-images.githubusercontent.com/101395055/223962915-b4ec6db0-b67c-46b9-8c31-fcc761d03331.png">
- 具体操作见下方文字描述

## 角色分工
### 项目负责人
- 工作流
1. 负责给各课题负责人安排任务，同时对每个任务创建各自的新分支
2. 批准各课题负责人上传的课题文件，同时归档到主分支上
3. 删掉各课题负责人使用完毕的新分支
- 项目管理
1. 人员管理：添加各课题负责人，维护人员信息
2. 文件管理：添加/修改文件名和层级关系

### 课题负责人
- 工作流
1. 找到该任务对应的分支，进入文件夹；
2. 上传课题文件；
3. 告知项目负责人

## 具体操作
### 1. 创建任务卡（项目负责人）
- 进入issues，点击New issue创建任务卡
- 输入title（命名规则：月份-姓名-课题名称），选择Assignees 和 Projects 后，点击Submit new issue完成创建

### 2. 创建新分支（项目负责人）
- 在当前任务卡下，在右侧Development，点击Create a branch 创建新分支
- 在当前任务卡的评论区回复：创建的新分支名，并@课题负责人

### 3. 在新分支上传文件（课题负责人）
- 从接收任务的邮箱，点击view it on GitHub进入该任务卡
- 点击code，选择新分支名（项目负责人已评论在当前任务卡里）
- 在当前新分支名下，选择自己要上传文件的主文件名，进入最末级（示例：https://github.com/ccnu-lab/monthly_reports/tree/17-%E6%9D%8E%E6%98%A5%E9%9B%A8/%E9%A1%B9%E7%9B%AEM/%E8%AF%BE%E9%A2%98AA/%E4%B8%89%E6%9C%88）
- 点击Add file >- Upload files，上传课题文件，同时在Add files via upload输入当前的操作（命名规则：姓名-学校-当前做了什么）
- 点击commit changes

### 4. 告知项目负责人（课题负责人）
- 进入pull requests，点击Compare & pull request
- 右侧Review选择项目负责人，提交——点击create pull request

### 5. 批准任务卡，合入主分支（项目负责人）
- 从接收任务的邮箱，点击view it on GitHub进入该任务卡
- 点击Merge pull request
- 点击confirm merge
- 点击Delete branch

## 命名规范
- 项目：项目名称
- issue：月份-姓名-课题名称
- 上传的文件：月份-姓名-课题名称-学校名称
- 上传文件的via：姓名-学校-当前做了什么

