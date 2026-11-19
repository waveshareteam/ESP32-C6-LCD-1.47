# 工厂固件

[English](./README.md)

| 文件 | 用途 |
| --- | --- |
| [ESP32-C6-LCD-1.47_FactoryOnly_20260203.bin](ESP32-C6-LCD-1.47_FactoryOnly_20260203.bin) | 2026-02-03 出厂恢复固件，从 `0x0` 烧录。 |

烧录前：

- 备份必须保留的设备专用数据。
- 确认开发板型号和硬件版本。
- 使用与该镜像对应的产品文档给出的烧录偏移和流程，不要从源码构建结果推断产品镜像。
- 不要把这一镜像与其他项目构建的 bootloader 或分区文件混用。

本镜像已经使用 Flash Download Tool 在对应产品上完成实物验证。SHA-256：`F13C96D16FAE6EBEFCCD9A456884A94E73ECCA96F1D5604D32F5425EE0D5C40D`。

工厂固件与源码构建固件的区别见[固件指南](https://github.com/waveshareteam/esp32-repo-template/blob/main/docs/spec.md)。

## 更新工厂镜像

工厂二进制替换属于开发操作。请在 Pull Request 中记录其来源、预期硬件版本、烧录流程、校验值和用户可见版本。绝不能使用无关的本地构建覆盖现有镜像。
