## Embodied AI Sprint | 开发日志

##  2026-03-23 | 环境就绪与学习规划

###  今日进展
- [x] **环境构建**：成功创建 Conda 虚拟环境 `rl_env` (Python 3.10)。
- [x] **项目初始化**：完成 GitHub 仓库配置及本地目录结构搭建。
- [x] **路径规划**：明确了第一阶段的学习路线与技术栈。

---

###  专项学习计划 (Learning Roadmap)

#### 1. 理论与实战课程
- [ ] **强化学习核心**：王树森《强化学习》系列（侧重数学原理与经典算法）。
- [ ] **深度学习进阶**：李宏毅《深度学习》2023版（侧重 Transformer 与大模型基础）。
- [ ] **社区前沿**：Hugging Face Deep RL Course（侧重工程实现与 Stable Baselines3）。
- [ ] **具身实战**：材机战士系列教程（侧重 MuJoCo 仿真与机器人控制实操）。

#### 2. 技术栈复习与巩固
- [ ] **Python 高级特性**：装饰器、生成器、多进程（用于并行仿真）。
- [ ] **PyTorch 深度应用**：
    - 熟练掌握 `Tensor` 维度变换（`permute`, `view`, `expand`）。
    - 掌握自定义 `Dataset` 与 `DataLoader`。
    - 深入理解 `autograd` 自动求导机制。

#### 3. 核心算法研究：DINO (Self-Distillation with No Labels)
- [ ] 阅读 DINO/DINOv2 论文，理解视觉特征提取的自监督逻辑。
- [ ] 跑通 DINOv2 的预训练模型加载 Demo。

---

###  下一步行动 (Next Steps)
1. **模型原型构建**：在 `src/models/` 下编写原始模型定义脚本。
2. **仿真环境安装**：配置 MuJoCo 物理引擎并运行第一个测试用例。
3. **特征对齐**：尝试将 DINOv2 提取的视觉特征输入到基础 MLP 网络中。

---

###  当前环境配置
- **Virtual Env**: `rl_env` (Conda)
- **Python**: 3.10
- **Main Frameworks**: PyTorch (Pending), MuJoCo (Pending)