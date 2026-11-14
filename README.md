<div align="center">

# ClassPixelPro Releases

ClassPixelPro 的发布仓库：存放构建流水线、版本更新日志（[CHANGELOG.md](CHANGELOG.md)）与各版本的 GitHub Release 产物。

</div>

## 关于本项目

ClassPixelPro 是一款适用于班级多媒体屏幕的课表信息显示工具，基于 [ClassIsland](https://github.com/ClassIsland/ClassIsland) 二次开发。

- **客户端源码仓库**：[CaizheZhou/ClassPixelPro](https://github.com/CaizheZhou/ClassPixelPro)（GPL-3.0）
- **原项目（上游）**：[ClassIsland/ClassIsland](https://github.com/ClassIsland/ClassIsland)（GPL-3.0，作者 [HelloWRC](https://github.com/HelloWRC)）
- **官网**：[class.imzcz.cn](https://class.imzcz.cn)
- **服务状态页**：[status.imzcz.cn](https://status.imzcz.cn)
- **开源协议**：本项目与上游均遵循 [GPL-3.0](https://github.com/ClassIsland/ClassIsland/blob/master/LICENSE)

> 本仓库仅包含构建流水线与发布产物，不包含源码；源码变更请在客户端仓库提交。

## 发版流程

1. 客户端仓库打 tag（X.Y.Z）
2. 流水线自动构建出安装包并发布 Release
3. 版本说明取自 [CHANGELOG.md](CHANGELOG.md) 顶部的对应段落
