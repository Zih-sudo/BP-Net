如果 `pip install` 速度太慢，可以尝试切换镜像源，或者永久设置镜像配置，在终端中运行以下命令：

```bash
python -m pip install --upgrade pip
pip config set global.index-url https://mirrors.tuna.tsinghua.edu.cn/pypi/web/simple
