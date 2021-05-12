**# jupyterlab-访问远程服务器**

1 下载安装好anaconda
2 clone已有集群环境   conda create -n your_env_name  --clone jiqun_env_name
3 进入新建环境    source activate your_env_name source
4 安装jupyterlab    pip install jupyterlab
5 配置    jupyter notebook --generate-config
6 安装kernel    python -m ipykernel install --name your_env_name --user
7 启动jupyterlab    jupyter lab --ip=10.198.6.31 --port=10000
