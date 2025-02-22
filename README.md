# 学翼 - 您的一站式智能化学习平台

![学翼-主页面](https://cdn.luogu.com.cn/upload/image_hosting/5m7958hg.png)

> 一款专为Windows打造的智能化学习任务管理工具，集成AI问答、进度跟踪、数据可视化等功能

**下载最新版本**：[TaskWing V1.0.5 安装包](https://github.com/TiantianYZJ/TaskWing/releases/download/V1.0.5/TaskWing-V1.0.5_Setup.exe)  

*支持 Windows 10/11 系统 | 大小：不超过150MB | 更新时间：2024.02.22*

---

## 🌟 为什么选择 TaskWing？

在快节奏的学习与工作中，**TaskWing** 将传统任务管理与人工智能深度结合，为您提供**极简操作**与**专业级效率工具**的完美平衡。不同于普通待办清单，我们通过**动态剩余天数计算**、**AI 即时答疑**和**沉浸式番茄钟**三大核心模块，重构任务管理体验——无论是备考冲刺的日程规划，还是科研项目的进度追踪，TaskWing 都能成为您最可靠的学习伴侣。

---

## 🚀 核心亮点

### 智能化任务生态
- **动态感知**：自动计算任务剩余天数，通过系统级通知推送即将截止的提醒  
- **深度整合 AI**：一键调用 **Deepseek-V3/R1 双模型**，支持 Markdown 渲染的智能问答  
- **专注力赋能**：内置白噪音的番茄钟模块，专注时长自动计入学习统计报告  

### 专业级交互设计
- **双主题自适应**：根据时间自动切换深色/浅色模式，支持手动锁定主题  
- **零数据丢失**：采用 SQLite 数据库持久化存储，重启后任务状态完整保留  
- **多形态入口**：支持主窗口操作与系统托盘快捷控制，满足全场景使用需求  

### 企业级功能扩展
- **私有 API 支持**：可配置 Deepseek/硅基流动 API 密钥，满足高频使用需求  
- **一键数据清理**：提供 6 位动态验证码保护的数据核销机制  
- **跨平台推送**：通过 Windows Toast 通知实现系统层级的消息提醒  

---

## 📦 功能全景

| 模块          | 功能描述                                                                 |
|---------------|--------------------------------------------------------------------------|
| **任务管理**  | 增删改查任务 · 截止日期智能提醒 · 完成状态图标化 · 批量清空              |
| **专注模式**  | 自定义番茄钟时长 · 白噪音场景 · 学习数据统计 · 实时进度条                |
| **AI 智答**   | 深度思考模式切换 · 浏览器/窗口双显 · 代码块复制 · 私有 API 配置          |
| **数据可视化**| 任务分布饼图 · 状态趋势分析 · 番茄钟时长统计 · 即将截止任务列表          |
| **系统集成**  | 开机自启动 · 窗口置顶 · 任务栏托盘驻留 · 高清图标适配 · 多分辨率支持     |

---

## 🛠️ 使用全流程

1. **任务创建**  
   在简洁的输入框中填写任务名称与截止日期，支持`回车键快速提交`。添加成功后，系统会通过 Windows 通知提示待办事项总量。

2. **进度跟踪**  
   - 双击任务可直接编辑详细信息，剩余天数会每秒动态更新  
   - 点击✅图标标记完成时，将触发**成就反馈通知**（如"已完成 80% 任务"）  

3. **沉浸式学习**  
   通过「专注」按钮启动番茄钟，可选择 1-600 分钟专注时长：  
   - 内置 8 种白噪音场景（雨声/篝火/溪流等）  
   - 专注结束时自动弹出任务完成确认窗口  
   - 所有专注记录会计入「统计报告」的总学习时长  

4. **AI 协作**  
   在专注过程中或任务列表页，点击「AI 智答」可快速提问：  
   - 支持数学公式、代码块、表格等复杂内容渲染  
   - 通过`⚡深度思考`模式切换 V3/R1 模型  
   - 回答内容支持**一键复制**或浏览器高级渲染  

5. **数据分析**  
   「统计报告」模块提供多维度的学习画像：  
   - 核心指标看板（总任务/完成率/明日到期数）  
   - 番茄钟历史记录与平均专注时长  
   - 过期任务预警列表（支持颜色标记紧急程度）  

6. **数据维护**  
   任务完成后可通过右键菜单删除，所有操作均记录在「任务计数器」中。提供「删除所有数据」功能，需输入动态验证码确保操作安全。

---

## 📌 高级技巧

- **快捷键**：任务名称输入框支持 `Enter` 快速提交  
- **主题切换**：在设置中选择「自动切换」可让主题随时间变化  
- **API 优化**：频繁使用 AI 功能时，建议通过教程配置私有 API 以提升稳定性  
- **数据安全**：用户数据存储在 `%APPDATA%\Roaming\TaskWing\TaskWing_data.db` ，重装系统前建议备份  

---

## 开源协议
本项目基于 **GPLv3 协议**开源，欢迎贡献代码或提交改进建议。图标资源来自[阿里巴巴矢量图标库](https://www.iconfont.cn/collections/detail?cid=50153)，核心 AI 能力由 [Deepseek](https://www.deepseek.com/) 和 [硅基流动](https://www.siliconflow.com/zh/home) 提供支持。

*让 TaskWing 为您的每一次学习注入澎湃动力！* 🚀