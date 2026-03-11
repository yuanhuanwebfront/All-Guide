# ollama 安装


## 安装

1. 下载安装包

   从 [ollama 官方网站](https://ollama.ai/download) 下载适用于您操作系统的安装包。

2. 安装

   双击下载的安装包，按照提示进行安装。

3. 启动服务

   安装完成后，您可以在命令行中输入以下命令来启动 ollama 服务：

   ```
   ollama serve
   ```

   这将启动 ollama 服务并监听默认端口 11434。

   您也可以在启动时指定自定义端口，例如：

   ```
   ollama serve --port 8000
   ```

   这将使 ollama 服务在端口 8000 上监听。
