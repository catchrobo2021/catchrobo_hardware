# Catchrobo 2021 Hardware Design
## 仕様
|                           |                        |                | J1          | J2          | J3         | J4        | J5        | gripper     |
|---------------------------|------------------------|----------------|-------------|-------------|------------|-----------|-----------|-------------|
| リンク                    | 質量                   | g              | 5890.3      | 2323.4      | 1390.5     | 1119.3    | 803.7     | -           |
|                           | 重心位置               | mm             | 0.0         | 635.8       | 441.7      | 58.9      | 8.3       | -           |
|                           | 重力トルク（最大）     | Nm             | 0.0         | 14.5        | 6.0        | 0.6       | 0.1       | -           |
|                           | 慣性モーメント（最小） | g mm^2         | 31614181.0  | 89931948.4  | 22789669.0 | 4522984.0 | 3238892.0 | -           |
|                           | 慣性モーメント（最大） | g mm^2         | 864447935.7 | 268435760.2 | 28833196.4 | 4522984.0 | 3238892.0 | -           |
| モータ                    | トルク定数             | Nm/A           | 0.07        | 0.07        | 0.07       | 0.07      | 0.07      | -           |
|                           | KV値                   | KV             | 105.0       | 105.0       | 105.0      | 105.0     | 105.0     | -           |
|                           | ワット数               | W              | 107.0       | 107.0       | 107.0      | 107.0     | 107.0     | -           |
|                           | 端子間抵抗             | Ohms           | 0.186       | 0.186       | 0.186      | 0.186     | 0.186     | -           |
|                           | 電源電圧               | V              | 24.0        | 24.0        | 24.0       | 24.0      | 24.0      | -           |
|                           | 連続電流               | A              | 24.0        | 24.0        | 24.0       | 24.0      | 24.0      | -           |
|                           | 最大トルク             | Nm             | 1.68        | 1.68        | 1.68       | 1.68      | 1.68      | -           |
|                           | 減速比                 | ul             | 8.0         | 16.0        | 8.0        | 2.8       | 2.8       | -           |
|                           | 減速後                 | Nm             | 13.4        | 26.9        | 13.4       | 4.7       | 4.7       | -           |
|                           | ロータ慣性モーメント   | g mm^2         | 129469.2    | 129469.2    | 129469.2   | 129469.2  | 129469.2  | -           |
|                           | 最大保持電流（各相）   | A              | 0.0         | 12.9        | 10.8       | 3.3       | 0.3       | -           |
|                           | 最大消費電流（実効値） | A              | 4.5         | 4.5         | 4.5        | 4.5       | 4.5       | -           |
| 出力軸                    | 加速度リミット（最小） | rad/s/s        | 15.4        | 41.1        | 199.8      | 732.7     | 1090.5    | -           |
|                           | 加速度リミット（最大） | rad/s/s        | 336.8       | 100.7       | 238.7      | 732.7     | 1090.5    | -           |
|                           | 速度リミット           | rad/s or m/sec | 22.5        | 11.3        | 22.5       | 64.3      | 64.3      | 0.113333333 |
|                           | 可動域（最小）         | deg or m       | -160.0      | -90.0       | -160.0     | -90.0     | -160.0    | 0.02        |
|                           | 可動域（最大）         | deg or m       | 160.0       | 90.0        | 0.0        | 90.0      | 160.0     | 0.12        |
| 姿勢　　　　　　　　　　　 | 起動時                 | deg or m       | 0           | 90          | -160       | 70        | 0         | 0.12        |


# 寸法
* [ロボット寸法](https://github.com/catchrobo2021/catchrobo_hardware/blob/main/assembly_manual/assy-robot.pdf) 
* [フィールド配置図](https://github.com/catchrobo2021/catchrobo_hardware/blob/main/assembly_manual/assy-robot_with_field.pdf)

# 組立図
* [J1](https://github.com/catchrobo2021/catchrobo_hardware/blob/main/assembly_manual/s-assy-unit-j1.pdf)
* [J2](https://github.com/catchrobo2021/catchrobo_hardware/blob/main/assembly_manual/s-assy-unit-j2.pdf)
* [J3](https://github.com/catchrobo2021/catchrobo_hardware/blob/main/assembly_manual/s-assy-unit-j3.pdf)
* [Link0](https://github.com/catchrobo2021/catchrobo_hardware/blob/main/assembly_manual/s-assy-link0.pdf)
* [Link1](https://github.com/catchrobo2021/catchrobo_hardware/blob/main/assembly_manual/s-assy-link1.pdf)
* [Link2](https://github.com/catchrobo2021/catchrobo_hardware/blob/main/assembly_manual/s-assy-link2.pdf)
* [Link3 - Link5](https://github.com/catchrobo2021/catchrobo_hardware/blob/main/assembly_manual/s-assy-link3.pdf)
* [gripper](https://github.com/catchrobo2021/catchrobo_hardware/blob/main/assembly_manual/s-assy-gripper.pdf)
