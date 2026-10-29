# 超级工厂 v2.0.1

**工厂建模 · 生产仿真 · 云端执行回看**

超级工厂是一款面向工厂布局与生产流程的三维仿真应用。通过设备模型、生产方案和运行时间轴，将设备作业、物料流转与成品运送呈现在同一工厂场景中。

[下载 Windows 版](https://github.com/JunyeFu/superfactory-releases/releases/download/v2.0.1/SuperFactory-2.0.1-Windows-x64.zip) · [下载示例工厂](https://github.com/JunyeFu/superfactory-releases/releases/download/v2.0.1/SuperFactory-2.0.1-Example-Factory.zip) · [版本下载页](https://github.com/JunyeFu/superfactory-releases/releases/tag/v2.0.1)

## 产品功能

- **三维工厂布局**：使用设备模型和工厂模板组织产线，在全厂与流水线视图中查看设备分布。
- **生产与运输仿真**：运行生产方案，观察多工序作业、物料流转和成品运送，通过物品跟随视图查看流转过程。
- **工程保存与回看**：保存工厂工程和运行记录，重新打开后查看布局与生产过程。
- **云端执行回看**：按时间轴查看已保存的设备作业和运输记录；连接部署环境后，可使用云端生产与数据查询功能。

## 下载与运行

| 下载内容 | 用途 |
| --- | --- |
| [Windows x64 应用](https://github.com/JunyeFu/superfactory-releases/releases/download/v2.0.1/SuperFactory-2.0.1-Windows-x64.zip) | 主程序、设备模型、工厂模板及运行资源，首次使用请下载此包。 |
| [纸包装示例工厂](https://github.com/JunyeFu/superfactory-releases/releases/download/v2.0.1/SuperFactory-2.0.1-Example-Factory.zip) | 配套工程，包含92台设备的厂房、本地仿真记录及纸箱产运执行记录，需通过主程序打开。 |

**运行环境：Windows 11 x64，已安装 Microsoft Edge WebView2 Runtime。**

完整解压应用压缩包，双击 `superfactory.exe` 即可启动。请保留解压目录中的全部文件；无需安装开发工具。操作详情见包内《使用说明》。

## 创建第一座工厂

1. 从模板新建工程，选择“纸包装多产品工厂 · 92台设备”。
2. 点击“使用模板演示配置”，查看预览，再点击“创建模板工厂”。
3. 选择“纸包装演示生产”并运行方案，在全厂、流水线或物品跟随视图中查看生产过程。
4. 通过“文件 → 保存工程…”保存；下次使用“文件 → 打开工程目录…”继续查看。

## 浏览示例工厂

解压示例工厂包，在应用中选择“文件 → 打开工程目录…”，打开其中的“纸箱产运演示”目录，即可浏览厂房及已保存的运行记录。

查看云端执行记录时，进入“云端生产 → 执行”，选择“已保存记录1”，向下滚动并点击“回看执行画布与时间轴”。可在“对象类别”中选择“运输记录”，查看物料运送情况。

本地仿真和示例记录浏览无需连接云服务。发起实时云端生产或查询云端数据时，需要由部署管理员提供连接文件，在“设备”页导入后保存工程并重启应用。

## 软件与资源许可

软件及设备模型、字体等资源的许可信息见应用包内的 `LICENSE`、`NOTICE` 和各资源许可文件。
