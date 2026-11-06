# Logisim 电路合集

Logisim 实现的若干数字电路小项目。

| 电路                      | 说明                                             |
| ----------------------- | ---------------------------------------------- |
| `grf.circ`              | 32 × 32 位寄存器堆（A1/A2/A3/WD/WE/RD1/RD2）          |
| `Logisim_4BitSort.circ` | 4 位 4 数排序网络（1bit_swap / 4bit_swap / 4bit_sort） |
| `Logisim_mod5.circ`     | 模 5 计数器状态机，输出 s0–s4                            |
| `fsm.circ`              | 状态机（输入 CLR / In，输出 Z）                          |
| `fibonacci1.circ`       | 计数器 + 寄存器 + 加法器实现的斐波那契序列                       |
| `ftoi.circ`             | 16 位浮点数转 32 位整数                                |
| `crc.circ`              | CRC 计算电路                                       |
| `navigator.circ`        | 导航移动状态机（command / isInvalid / isArrived）       |
| `sokoban.circ`          | 推箱子状态更新逻辑（Sokoban / isInvalid / isArrived）     |

使用：用 Logisim 打开对应 `.circ` 文件即可查看与仿真。