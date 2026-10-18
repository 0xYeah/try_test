# Protenix＋PXDesign 研发硬件询租单

2026-10-18 · [阅读入口](../../index.html) · [选型工具](runtime-hardware.html) · [配置依据](hardware-reference.html)

**二档单 RTX PRO 6000 Blackwell 96 GB 作为优先短租候选，用于研发调试和小批量内测。三档提供两张独立 GPU。**

| 档位 | 显卡完整型号 | 用途 | 优点 | 局限 |
| --- | --- | --- | --- | --- |
| 一档：基础 | 1×RTX PRO 5000 Blackwell 48 GB | 部署验证、小任务调试 | 单卡配置简单。 | 单卡 48 GB，输入规模和并发待测。 |
| **二档：优先试租** | **1×RTX PRO 6000 Blackwell 96 GB** | 研发、小批量内测 | 单任务显存空间更大。 | 可试同卡共享，但两模型并发未实测。 |
| 三档：双卡分工 | 2×RTX 6000 Ada Generation，各 48 GB | 两任务分别用卡 | GPU 可分别分配。 | 单任务仍限单卡 48 GB，共用整机 128 GB 内存。 |

三档共同询租目标：**24 vCPU 起、整机 128 GB 内存、可用 2 TB NVMe SSD、Linux 原生部署**。这是工程询价目标，非实测最低值；CPU 型号及实际分配由商家列明。

一档有货时可另报 **RTX PRO 5000 72GB Blackwell**，单列型号；三档可另报 **2×L20 48 GB** 整机替代方案，物料分开写。

**三档的两项判断均待实测：① 分别正常运行；② 两套同时正常运行。** 都须完整产出结果。PXDesign 的旧依赖在 Blackwell 上需验证兼容性；实际显存、整机内存和耗时以租机结果为准。

可整段转发采购：

> 主报 1×RTX PRO 6000 Blackwell 96 GB；备选 1×RTX PRO 5000 Blackwell 48 GB、2×RTX 6000 Ada Generation（各 48 GB）。三档均按 24 vCPU 起、整机 128 GB 内存、可用 2 TB NVMe SSD、Linux 原生环境询租。请注明 GPU 具体版本及整卡独占、CPU 型号与分配、磁盘是否持久保留、NVIDIA 驱动支持，分别报短租／续租及配套存储总价，替代物料单列。

规格参考：[PRO 5000](https://www.nvidia.com/en-us/products/workstations/professional-desktop-gpus/rtx-pro-5000/) · [PRO 6000](https://www.nvidia.com/en-us/products/workstations/professional-desktop-gpus/rtx-pro-6000/)
