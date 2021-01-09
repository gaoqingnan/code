anaconda是一个环境和包的管理工具
conda list                         查看安装了哪些包
conda env list                  查看当前存在哪些虚拟环境
conda create -n your_env_name python=X.X（2.7、3.6等)命令创建python版本为X.X、名字为your_env_name的虚拟环境
your_env_name文件可以在Anaconda安装目录envs文件下找到
activate your_env_name(虚拟环境名称)  
conda deactivate关闭虚拟环境(即从当前环境退出返回使用PATH环境中的默认python版本)
conda install -n your_env_name [package]对虚拟环境中安装额外的包  
conda remove -n your_env_name(虚拟环境名称)  删除虚拟环境  
conda remove --name your_env_name  package_name 删除环境中的某个包