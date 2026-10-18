# Protenix＋PXDesign 研发硬件询租单

2026-10-18 · [阅读入口](../../index.html) · [选型工具](runtime-hardware.html)

**建议选二档：单 RTX PRO 6000 Blackwell 96 GB，先短租，用于研发调试和小批量内测。只有硬要求两任务各有一张卡，才选三档。**

| 档位 | 显卡完整型号 | 用途 | 优点 | 局限 |
| --- | --- | --- | --- | --- |
| 一档：基础 | 1×RTX PRO 5000 Blackwell 48 GB | 部署验证、小任务调试 | 单卡配置简单。 | 单卡 48 GB，输入规模和并发待测。 |
| **二档：推荐** | **1×RTX PRO 6000 Blackwell 96 GB** | 研发、小批量内测 | 单任务显存空间更大。 | 可试同卡共享，但两模型并发未实测。 |
| 三档：分卡并发 | 2×RTX 6000 Ada Generation，各 48 GB | 两任务分别用卡 | GPU 可分别分配。 | 单任务仍限单卡 48 GB，共用整机 128 GB 内存。 |

三档共同询租目标：**24 vCPU 起、整机 128 GB 内存、可用 2 TB NVMe SSD、Linux 原生部署**。这是工程询价目标，非实测最低值；CPU 型号及实际分配由商家列明。

一档有货时可另报 **RTX PRO 5000 72GB Blackwell**，单列型号；三档可另报 **2×L20 48 GB** 整机替代方案，物料分开写。

必要条件：Blackwell 的 PXDesign 旧依赖需适配；三档都要两工具各自完整跑通，再验并发与整机内存，不能凭卡数保证同时完成。

可整段转发采购：

> 主报 1×RTX PRO 6000 Blackwell 96 GB；备选 1×RTX PRO 5000 Blackwell 48 GB、2×RTX 6000 Ada Generation（各 48 GB）。三档均按 24 vCPU 起、整机 128 GB 内存、可用 2 TB NVMe SSD、Linux 原生环境询租。请注明 GPU 具体版本及整卡独占、CPU 型号与分配、磁盘是否持久保留、NVIDIA 驱动支持，分别报短租／续租及配套存储总价，替代物料单列。

规格参考：[PRO 5000](https://www.nvidia.com/en-us/products/workstations/professional-desktop-gpus/rtx-pro-5000/) · [PRO 6000](https://www.nvidia.com/en-us/products/workstations/professional-desktop-gpus/rtx-pro-6000/)
