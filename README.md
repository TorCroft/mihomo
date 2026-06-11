# Build Local Images — GitHub Actions

这个 GitHub Actions 工作流用于**拉取并重命名**两个常用的容器镜像（`mihomo` 和 `metacubexd`），然后将它们导出为 `.tar` 归档文件，最后以 Artifact 形式上传。这样就可以在离线环境或其它主机上直接加载使用这些镜像，而无需重新拉取。
