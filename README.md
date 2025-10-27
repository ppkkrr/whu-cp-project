# COPT 和 GUROBI 优化器的搭建（windows系统，python语言）
## COPT==8.0.1
### 程序包安装
https://pub.shanshu.ai/download/copt/8.0.1/win64/CardinalOptimizer-8.0.1-win64-installer.zip
### python接口安装
假设上一步copt根目录为 C:\Program Files\copt80，此处将coptpy包安装在自定义python中
```bash
cd "C:\Program Files\copt80\python"
python ".\setup.py" install
```
### 获取许可
登录杉树网站 https://www.shanshu.ai/copt直接申请后配置即可

## GUROBI==12.0.3
### 程序包安装（安装后须重启）
https://www.gurobi.com/downloads/gurobi-software/
### 安装license
先在官网注册gurobi账号后，连接校园网，在https://portal.gurobi.com/iam/home/中选择 Licenses → Requests → Named-User Academic的GENERATE NOW！

复制弹出的命令在 cmd 中运行，即可实现安装
### python接口
```bash
pip install gurobi
```