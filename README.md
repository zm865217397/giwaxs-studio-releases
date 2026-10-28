# GIWAXS Studio

本仓库仅发布 GIWAXS Studio 的桌面安装包、版本说明和校验信息。软件源码及私人实验数据不在此仓库中。

## 下载

请在 [Releases](https://github.com/zm865217397/giwaxs-studio-releases/releases) 页面选择对应系统和处理器的安装包。尚未完成发布者签名与 macOS 公证的版本会明确标为预览版，不能视为正式签名发行版。

- Windows：x64 EXE 安装包。
- macOS Apple Silicon：arm64 DMG。
- macOS Intel：x64 DMG（以实际发布附件为准）。

桌面版内置 Python 数值计算和绘图环境，不需要用户自行安装 Python。首次使用请导入自己的衍射数据或载入 `.giwaxs` experiment。发行包不内置私人样品或标准样数据。

## 工作区与更新

退出前会保存本机恢复快照，重启后尝试恢复；重要实验仍建议单独导出 `.giwaxs` 文件。安装目录与用户数据目录分离。

更新界面支持检查版本、下载进度以及保存后重启安装。正式在线更新需完成签名和发布配置；预览构建暂不自动安装在线更新。

国内用户访问 GitHub 的速度和可用性因网络而异。软件已预留国内 HTTPS 镜像优先、GitHub 备用的地址配置；镜像尚未部署时不能保证国内网络可用性。备用源需要提供相同版本和校验信息的安装包。

## 功能

- 二维探测器 / q 空间图、自动 mask、IP / OOP sector 曲线。
- AgB 多环实验几何校准。
- experiment 保存与恢复、多样品曲线 transfer、排版。
- Gaussian、Lorentzian、Pseudo-Voigt 多峰与多项式拟合，残差、参数和独立分量数据导出。
- PDF、SVG、TIFF、JPEG、PNG 科研图导出。

拟合分量和背景是模型计算曲线；实际几何、mask、背景和拟合解释应按实验条件核对。
