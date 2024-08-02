# Gazebo Package Report

## 必要依赖

对于 **Gazebo 11** 而言以下依赖是必备依赖：
1. SDFormat 9
2. Ign-common3
3. Ign-fuel-tool 4
4. Ign-math 6
5. Ign-transport 8
6. Ign-msgs 5
7. ignition-cmake 0

依赖参考[来源](https://classic.gazebosim.org/tutorials?tut=install_dependencies_from_source&cat=install)。

## ros-humble 包状况

> 说明：如下标记 x 的为缺包。

| 包名称             | 官方要求版本 | 已有包                                           | 版本    |
|------------------|------------|----------------------------------------------|-------|
| sdformat         | 9          | ros-humble-sdformat-test-files.x86_64        | unknown |
| ignition-cmake   | 0          | ros-humble-ignition-cmake2-vendor.x86_64     | 2     |
| ignition-common  | 3          | x                                            | x     |
| ignition-fuel-tool | x        | x                                            | x     |
| ignition-math    | 6          | ros-humble-ignition-math6.x86_64             | 6     |
| ignition-msgs    | 5          | ros-humble-gazebo-msgs.x86_64                | unknown |
| ignition-transport | x        | x                                            | x     |

