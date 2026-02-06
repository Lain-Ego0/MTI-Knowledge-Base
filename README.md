# MTI-KBI 机器人队知识库索引
MTI-KBI（MTI机器人队知识库索引）是MTI机器人队的**统一技术知识管理入口**，用于沉淀机械设计、MCU开发、Linux应用开发、机器视觉、强化学习、深度学习等领域的技术文档、经验总结与工程实践，支撑机器人队项目研发与技术传承。

本仓库采用模块化拆分管理，通过**相对路径**导航所有文档，适配GitHub网页端/本地编辑器浏览。

## 快速导航
### 技术文档模块
| 分类 | 模块入口 | 核心内容 |
| ---- | -------- | -------- |
| 🛠️ 机械设计 | [docs/01_mechanical_design/](docs/01_mechanical_design/README.md) | 设计规范、零件库、装配调试、3D打印 |
| 💻 MCU开发 | [docs/02_mcu_development/](docs/02_mcu_development/README.md) | 环境配置、驱动开发、规范、调试优化 |
| 📦 硬件设计 | [docs/03_hardware_design/](docs/03_hardware_design/README.md) | 设计规范、子系统、调试测试、物料选型 |
| 🐧 Linux应用开发 | [docs/04_linux_dev/](docs/04_linux_dev/README.md) | 环境搭建、节点通信、功能包、部署运维 |
| 👁️ 机器视觉 | [docs/05_computer_vision/](docs/05_computer_vision/README.md) | 标定预处理、目标检测、视觉SLAM |
| 🤖 机器人学 | [docs/06_robotics/](docs/06_robotics/README.md) | 足式机器人、机械臂解算 |
| 🧠 AI算法 | [docs/07_ai_algorithms/](docs/07_ai_algorithms/README.md) | 强化学习、深度学习、硬件部署 |
| 📚 工程实践 | [docs/08_engineering_practice/](docs/08_engineering_practice/README.md) | 工具链、项目管理规范 |

### 规范与协作
- [引用规范](docs/09_citation_specs/README.md)：文档编写与资源引用标准
- [贡献指南](CONTRIBUTING.md)：文档新增/修改提交流程与格式要求
- [更新日志](CHANGELOG.md)：知识库版本迭代记录
- [队伍开源项目汇总](open_source.md)：队内GitHub开源仓库清单

## 仓库说明
- 文档格式：统一使用Markdown编写，适配GitHub渲染规则
- 访问权限：本仓库为Public开源仓库，核心教程全员可见
- 版本管理：通过Git提交记录+CHANGELOG.md追踪文档更新