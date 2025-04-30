# StatMS

## 软件简介(Software Introduction)

本软件是一款面向生物信息学分析的工具，旨在为科研人员提供简单高效的数据分析功能。软件主要包括判别分析、聚类分析、单因素和多因素分析等模块，帮助用户快速挖掘数据中的潜在规律，生成可视化结果，用于学术研究或行业应用。
软件设计灵感来源于 SIMCA 和 MetaboAnalyst，结合了经典的分析算法与直观的用户界面，用户无需编程经验即可操作。

StatMS is a tool designed for bioinformatics analysis, aimed at providing researchers with simple and efficient data analysis functionalities. The software primarily includes modules such as discriminant analysis, cluster analysis, univariate and multivariate analysis, helping users quickly discover underlying patterns in the data and generate visual results for academic research or industry applications. The software design is inspired by SIMCA and MetaboAnalyst, combining classic analysis algorithms with an intuitive user interface, enabling users to operate without programming experience.


## 安装与启动 (Installation and Launch)

系统要求 (System Requirements)： 

- 操作系统：Windows 10 及以上 / macOS
- Operating System: Windows 10 and above / macOS
  
- 内存：8GB 及以上
- Memory: 8GB or more

- Python 环境：3.8 版本及以上，3.12版本以下
- Python Environment: Version 3.8 and above, below 3.12

## 安装步骤 (Installation Steps)：

1.下载软件安装包，解压到本地目录。
使用下列命令直接下载至当前路径下或直接下载zip文件至本地

Download the software installation package and extract it to a local directory.
Use the following command to download directly to the current directory or download the zip file locally:

wget https://github.com/hjzeng111/StatMS/releases/download/StatMS_V1.0.1/StatMS.zip -OutFile StatMS.zip

2.打开终端，进入软件目录，运行以下命令：

Open the terminal, navigate to the software directory, and run the following command:

pip install -r requirements.txt

如有网络连接超时等情况可使用

(pip install -r requirements.txt --index-url https://pypi.tuna.tsinghua.edu.cn/simple)清华源镜像

(pip install -r requirements.txt --index-url https://mirrors.aliyun.com/pypi/simple/)阿里云镜像

(pip install -r requirements.txt --index-url https://pypi.mirrors.ustc.edu.cn/simple/)中科大镜像

(pip install -r requirements.txt--index-url https://mirrors.huaweicloud.com/repository/pypi/simple/)华为云镜像

## 安装完成后，运行以下命令启动软件：
After installation is complete, run the following command to launch the software:

python work.py
