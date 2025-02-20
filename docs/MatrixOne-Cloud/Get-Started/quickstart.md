# 快速创建 MatrixOne Cloud（MO Cloud）实例

在本篇文档中，我们将指导您快速创建和使用 MatrixOne Cloud (MO Cloud) 实例。

## 第一步：创建 MO Cloud 账户

### 1. 申请试用 MO Cloud

如果您想尝试 MO Cloud 1.0 版本前的内测版本，可以通过以下步骤进行申请。

- 访问 [MO Cloud 试用申请页面](https://example.com)。
- 填写您的申请信息，并提交申请。我们会尽快审核您的申请。

**注意：**申请试用时填写的邮箱将成为您的 MO Cloud 账户邮箱。

使用以下方式注册 MO Cloud 账户：

- 电子邮箱账户
- Github 账户
- Google 账户

请注意，当使用第三方账户注册时，MO Cloud 将获取并使用您账户中的主要邮箱作为平台注册邮箱。因此，MO Cloud 不支持使用相同邮箱进行多个第三方账户或电子邮箱的重复注册。

### 2. 注册 MO Cloud 账户

一旦您的试用申请获得批准，我们会发送一封注册邮件到您提供的邮箱地址。请按照邮件中的链接完成注册。

### 3. 登录 MO Cloud 账户

注册成功后，您可以点击激活邮件中的链接，以登录 MO Cloud 实例管理平台。

请注意，当使用第三方账户注册时，MO Cloud 将获取并使用您账户中的主要邮箱作为平台注册邮箱。因此，MO Cloud 不支持使用相同邮箱进行多个第三方账户或电子邮箱的重复注册。

## 第二步：创建一个 MO Serverless 实例

### 1. 打开实例创建页面

在 **Instances** 页面，点击 **+Create Instance** 按钮。

### 2. 配置实例信息

- **Cloud Provider：**根据您所在地选择合适的公有云供应商和地区。
- **Instance Capacity：**保持默认值 **Free Trial**。
- **Access Control：**设置实例管理员 admin 的初始密码。
- **Instance Name：**为您的实例取一个名称，或者使用平台自动生成的名称。

### 3. 完成创建

点击 **Create Serverless Instance** 完成创建。几秒后，实例状态变为绿色的 **Active** 时，表示实例创建成功。

## 第三步：连接实例

### 1. 打开数据库管理平台

点击实例卡片下方的 **Connect** 按钮，然后选择 **Connect to Platform**，以打开数据库管理平台的登录页面。

### 2. 输入管理员用户名和密码

在登录页面中输入以下信息：

- **用户名：**admin
- **密码：**创建实例时设置的管理员密码

## 运行样例数据

### 1. 加载样例数据 TPC-H

- 在数据库管理平台右下角，找到并点击**快捷互动**按钮。
- 依次选择 **Load Data > Try with Sample Data > TPC-H Benchmark**。
- 点击 **Load TPC-H** 完成样例数据订阅。

### 2. 查询 TPC-H 数据集

- 在菜单栏中点击并进入 **Query > SQL Editor** 页面。
- 在编辑器上方的数据库下拉框中选择 **mo_sample_data_tpch_sf1**。
- 在**快捷互动**窗口的 **Load Data** 中点击 **Try it**，将其中的查询语句复制到编辑器中，然后点击 **Run** 执行查询。

现在，您已经成功创建了一个 MO Serverless 实例并运行了样例数据集的查询。希望这个教程对您有所帮助！

如果您需要更多帮助，请继续查看我们的文档或联系支持团队。
