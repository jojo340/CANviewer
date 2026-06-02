# CANviewer
# CANviewer 技术支持

CANviewer 是一款用于查看 CAN 日志、解析 DBC 文件并绘制信号曲线的 iOS 工具。

## 支持的文件格式

- ASC CAN 日志
- BLF CAN 日志
- DBC 文件

## 常见问题

如果日志无法导入，请确认文件格式是否为标准 ASC 或 BLF。

如果 DBC 信号无法绘制曲线，请确认：
- 已先导入 CAN 日志
- 已导入匹配的 DBC 文件
- DBC 中的 CAN ID 与日志中的 CAN ID 一致
- 所选信号在日志中有对应报文数据

## 联系方式

如需技术支持或反馈文件兼容性问题，请发送邮件至：

yangnote@qq.com

请尽量提供以下信息：

- iOS 版本
- CANviewer 版本
- 文件格式，例如 ASC、BLF 或 DBC
- 问题描述
- 如方便，可提供可复现的示例文件
