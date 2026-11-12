# Android 6.6 内核构建

SM8750 与 MT6991 的独立构建入口。

| 平台 | 可选版本 |
| --- | --- |
| SM8750 | 6.6.30、6.6.56、6.6.57、6.6.66、6.6.89、6.6.118 |
| MT6991 | 6.6.50、6.6.89 |

默认启用原生风驰。可选功能只有 SUSFS、LZ4 + Zstd、Unicode 修复、ADIOS、基带保护，默认全部选中。支持选择 Root 管理器、填写绑定序列号，以及指定内核后缀和构建时间。选择无内置 Root 管理器时跳过 SUSFS。

在 Actions 选择相应版本运行，或使用现有构建机器人。6.6 与 6.12 的功能配置分别保存，自己构建和帮别人构建仍各自独立。产物通过现有受限交付流程获取。

公开内核源码：

- [SM8750](https://github.com/zaominn/android_kernel_common_oneplus_sm8750)
- [MT6991](https://github.com/zaominn/android_kernel_oneplus_mt6991)

请选择与设备平台、内核版本和系统相符的入口；云端编译通过不代表所有设备已完成实机验证。
