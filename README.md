# Monthly_Reports

## 背景
- 目的：为方便在cac网站上展示各课题的内容，同时统计各单位各课题的完成情况，选择使用github来管理当前工作流
- 用法：管理员可以督促执行人上传课题，执行人可以将每月课题汇报给管理员
- 仓库：[ccnu-lab/monthly_reports](https://github.com/ccnu-lab/monthly_reports)

## 业务流程图
- Cac-Github分级管理工作流
<img width="722" alt="image" src="https://user-images.githubusercontent.com/101395055/223962915-b4ec6db0-b67c-46b9-8c31-fcc761d03331.png">
- 具体操作见下方文字描述


## 角色分工
1. 项目负责人：负责给各执行人建任务卡
2. 课题负责人：根据管理员创建的任务卡，在对应文件夹下，完成自己所分配的任务


## 具体操作
### 1. 创建项目（管理员）
- 进入仓库 monthly_reports；
- 进入projects，点击New project；
- 点击名称修改Project name（命名规则：项目名称）；
- 在列表里创建任务卡：输入任务名称（命名规则：月份-姓名-课题名称），点击enter
- 点击任务名称，选择Assignees，选择Convert to issue >- monthly_reports，在当前项目下完成创建任务卡

```
 只有新项目才需要创建，若无新项目，跳过该步骤，直接进入步骤2
```

### 2. 创建任务卡（管理员）
- 进入issues，点击New issue创建任务卡；
- 输入title（命名规则：月份-姓名-课题名称），选择Assignees 和 Projects 后，点击Submit new issue完成创建；

### 3. 创建新分支（执行人）
- 进入issues，点击自己的任务卡；
- 在右侧Development，点击Create a branch 创建新分支（记住新分支名）

### 4. 在新分支上传文件（执行人）
- 进入code，选择新分支名
- 在当前新分支名下，选择自己要上传文件的主文件名，进入最末级（示例：https://github.com/ccnu-lab/monthly_reports/tree/17-%E6%9D%8E%E6%98%A5%E9%9B%A8/%E9%A1%B9%E7%9B%AEM/%E8%AF%BE%E9%A2%98AA/%E4%B8%89%E6%9C%88）
- 点击Add file >- Upload files，上传课题文件，同时在Add files via upload输入当前的操作（命名规则：姓名-学校-当前做了什么）；
- 点击commit changes

### 5. 发起pull请求，合入主分支（执行人）
- 进入pull requests，点击Compare & pull request
- 点击create pull request
- 点击Merge pull request
- 点击confirm merge
- 点击Delete branch

## 命名规范
- 项目：项目名称
- issue：月份-姓名-课题名称
- 上传的文件：月份-姓名-课题名称-学校名称
- 上传文件的via：姓名-学校-当前做了什么

