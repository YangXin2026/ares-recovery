# ares-recovery

Redmi K40 游戏增强版 / POCO F3 GT (ares, MT6893) 的 recovery 编译。

- 设备树: `AYIKxD/recovery_device_xiaomi_ares@Twrp-HyperOS`（自带预编 kernel + dtb、MTK bootctrl/libmtk_bsg/plpath、MiTEE TAs）
- 变体: `twrp` = 照原树重编 TWRP 12.1；`ofox` = 自移植 OrangeFox fox_12.1（磁盘吃紧，可能失败）
- 目标产物: `boot.img`（recovery-as-boot，A/B 设备无独立 recovery 分区）

跑法: Actions → Build ares recovery → Run workflow
