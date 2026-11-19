## 中文说明

### 项目简介
本仓库包含了 UC Berkeley CS61A 课程的所有 **家庭作业 (hw)**、**实验 (labs)** 和 **项目 (projects)**。通过 Fork 本仓库，您可以创建自己的工作环境，跟踪学习进度并保存作业的解答。同时，您还可以访问我们提供的 [**CS61A 网站镜像**](https://insideempire.github.io/CS61A-Website-Archive/)，用于参考和学习。


### 功能特色
- **家庭作业 (hw)：** 巩固课程讲解内容，包含概念和代码练习。
- **实验 (labs)：** 指导练习，帮助理解核心概念。
- **项目 (projects)：** 通过大型项目综合应用所学知识。

### 使用方法

#### 1. Fork 本仓库
1. 打开仓库：[CS61A-Assignments](https://github.com/InsideEmpire/CS61A-Assignments)。
2. 点击页面右上角的 "Fork" 按钮，将仓库复制到您的 GitHub 账号下。

#### 2. 克隆您 Fork 的仓库
1. 打开终端或命令提示符。
2. 将 Fork 后的仓库克隆到本地：
   ```bash
   git clone https://github.com/<your-username>/CS61A-Assignments.git
   ```

#### 3. 开始完成作业
1. 进入仓库目录：
   ```bash
   cd CS61A-Assignments
   ```
2. 选择您想完成的作业目录，例如 `hw01` 表示家庭作业 1：
   ```bash
   cd hw/hw01
   ```
3. 打开 `.py` 文件，开始编写代码！

#### 4. 测试您的代码
完成作业或取得进展后，使用以下命令在本地测试代码：
```bash
python3 ok -q <function_name> --local
```
将 `<function_name>` 替换为您希望测试的具体函数名称。

如果想测试整个文件，使用以下命令：
```bash
python3 ok --local
```