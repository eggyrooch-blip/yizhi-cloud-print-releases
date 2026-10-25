# 一纸云打印 安装包

这里发布一纸云打印员工客户端的安装包，和官网 https://yizhi.plotlake.com/download.html 上的是同一份文件，sha256 相同。

- Mac：`YizhiCloudPrint-<版本>-macOS.pkg`
- Windows：`YizhiCloudPrint-<版本>-Windows-x64.msi`

在 [Releases](https://github.com/eggyrooch-blip/yizhi-cloud-print-releases/releases) 页面下载。每个版本都附有 `SHA256SUMS`，下载后可以核对：

```sh
shasum -a 256 -c SHA256SUMS   # macOS
sha256sum -c SHA256SUMS       # Linux
```

Windows 上可用 PowerShell：`Get-FileHash .\YizhiCloudPrint-<版本>-Windows-x64.msi -Algorithm SHA256`

## 安装包暂未签名

- Mac：打开时如提示无法验证开发者，到「系统设置 → 隐私与安全性」，点「仍要打开」。
- Windows：如出现 SmartScreen 提示，点「更多信息」→「仍要运行」。

这里只放安装包，不含源码。
