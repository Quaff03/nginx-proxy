# Nginx 反代

<h1 style='color: red;'>警告：请在使用前确认您所在的司法管辖区允许您使用本软件。由使用此软件带来的一切后果，Github与本软件的所有贡献者概不负责。</h1>

## 使用
- 点Code下载本仓库压缩包
- 解压到有可执行权限的目录下
- 安装 conf 中的 proxy.cer 证书至 受信任的根证书颁发者
- 修改 hosts 文件，加入下面几行：

<code>
127.0.0.1 zh.wikipedia.org

127.0.0.1 zh.m.wikipedia.org
</code>

- 运行 nginx.exe