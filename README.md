# GIWAXS Studio

本仓库仅发布 GIWAXS Studio 的桌面安装包、版本说明和校验信息。软件源码及私人实验数据不在此仓库中。

## 下载

请在 [Releases](https://github.com/zm865217397/giwaxs-studio-releases/releases) 页面选择对应系统和处理器的安装包。5.0.2 采用免费安装包发布：Windows 未签名，可能显示“未知发布者”；macOS 仅 ad-hoc 签名，未进行 Developer ID 签名和公证，首次启动可能需要在系统设置中允许打开。

- Windows：x64 EXE 安装包。
- macOS Apple Silicon：arm64 DMG。
- macOS Intel：x64 DMG（以实际发布附件为准）。

桌面版内置 Python 数值计算和绘图环境，不需要用户自行安装 Python。首次使用请导入自己的衍射数据或载入 `.giwaxs` experiment。发行包不内置私人样品或标准样数据。

## 工作区与更新

退出前会保存本机恢复快照，重启后尝试恢复；重要实验仍建议单独导出 `.giwaxs` 文件。安装目录与用户数据目录分离。

5.0.2 起，启动后或点击“软件更新”可检查 GitHub Releases 的正式新版，显示说明和下载进度。按系统和架构下载对应安装包，核对 SHA-256 与大小，打开前再次校验。Windows 保存 experiment 后打开安装程序，请选择原安装位置；macOS 保存后打开 DMG，将新版拖入“应用程序”替换旧版。完成后重新打开软件恢复工作区。\n\n5.0 预览版未启用在线检查，需要先手动安装一次新版。

当前免费安装包更新使用 GitHub 原站，国内 HTTPS 镜像尚未部署。国内下载速度和可用性取决于网络；未来配置镜像后会在版本说明中注明。

## 功能

- 二维探测器 / q 空间图、自动 mask、IP / OOP sector 曲线。
- AgB 多环实验几何校准。
- experiment 保存与恢复、多样品曲线 transfer、排版。
- Gaussian、Lorentzian、Pseudo-Voigt 多峰与多项式拟合，残差、参数和独立分量数据导出。
- PDF、SVG、TIFF、JPEG、PNG 科研图导出。

拟合分量和背景是模型计算曲线；实际几何、mask、背景和拟合解释应按实验条件核对。
