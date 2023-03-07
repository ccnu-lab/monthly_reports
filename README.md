# Monthly_Reports

## 背景
- 目的：为方便在cac网站上展示各课题的内容，同时统计各单位各课题的完成情况，选择使用github来管理当前工作流
- 用法：管理员可以督促执行人上传课题，执行人可以将每月课题汇报给管理员
- 仓库：[ccnu-lab/monthly_reports](https://github.com/ccnu-lab/monthly_reports)

## 业务流程图
- Cac-Github分级管理工作流
![page_1](https://user-images.githubusercontent.com/101395055/223351774-2a6688ae-6f64-4781-aa67-a46c3a8ac31b.png)
- 具体操作见下方文字描述


## 角色分工
1. 管理员：负责给各执行人建任务卡
2. 执行人：根据管理员创建的任务卡，在对应文件夹下，完成自己所分配的任务


## 具体操作
1. 创建项目（管理员）
- 进入仓库 monthly_reports；
- 进入projects，点击New project；
- 点击名称修改Project name（命名规则：项目名称）；
- 在列表里创建任务卡：输入任务名称（命名规则：月份-姓名-课题名称），点击enter
- 点击任务名称，选择Assignees，选择Convert to issue >- monthly_reports，在当前项目下完成创建任务卡

```
 只有新项目才需要创建，若无新项目，跳过该步骤，直接进入步骤2
```

2. 创建任务卡（管理员）
- 进入issues，点击New issue创建任务卡；
- 输入title（比如某某人-提交几月课题），选择Assignees 和 Projects 后，点击Submit new issue完成创建；

3. 创建新分支（执行人）
4. 在新分支上传文件（执行人）
5. 发起pull请求（执行人）
6. 合入主分支（执行人）
## 命名规范
- 项目：项目名称
- issue：月份-姓名-课题名称
- 上传的文件：月份-姓名-课题名称-学校名称

