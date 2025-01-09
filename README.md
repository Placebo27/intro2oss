# 开源软件通识课程

欢迎大家来到华科开放原子开源俱乐部的《开源软件通识课程》内部培训课程。本课程将秉持“以开源方式来建设开源课程”的指导方针，带同学们一起畅游开源软件的海洋。

带领俱乐部成员认识开源软件经历如下的不同阶段：

---

### **S0: 无意识使用阶段**

> **目标：** 认识到开源已融入生活，了解自己日常使用的开源软件。

* **开源无处不在**
  * 举例说明：现代科技中广泛应用的开源软件，例如 Android 系统（基于 Linux），浏览器（如 Chrome 和 Firefox），办公工具（如 LibreOffice），以及其他开发工具（如 Git、Vim、Node.js）。
  * 说明开源如何成为现代技术的基石：手机、服务器、云计算、大数据、人工智能等领域。
* **参考任务：**
  * 列举自己日常使用的一些开源软件，并尝试查找它们的开源主页或仓库。
  * 调研一个开源项目的背景，了解它在行业中的应用（如 Linux、Kubernetes）。

---

### **S1: 了解开源阶段**

> **目标：** 初步了解开源的概念、历史、许可证及其影响，培养开源安全意识。

* **开源是什么？**
  * **开源是一种软件类型：** 定义开源软件，与闭源软件对比。
  * **开源是一种软件开发方式：** 举例开源协作的特点，如社区贡献、代码开放。
  * **开源是一种协作与创新模式：** 讲解如何通过开源实现跨组织协作和技术创新。
  * **开源是一种产业生态：** 开源如何驱动技术演进和形成商业生态（如红帽的成功案例）。
* **开源历史**
  * 时间线和重要节点：Unix -> GNU -> Linux -> Git -> Github。
  * 自由软件运动与 Richard Stallman 的贡献。
  * 开源运动的兴起与 Open Source Initiative (OSI)。
* **开源许可证**
  * 介绍许可证的作用和开源定义（Open Source Definition）。
  * **常见开源许可证：**
    * Copyleft：GPL、AGPL 等。
    * Permissive：MIT、Apache-2.0、BSD。
    * 禁用场景：禁止与专利冲突等。
  * **如何选择许可证？** 举例如何根据项目需求选择适当的许可证。
* **开源安全**
  * 开源软件供应链安全：了解漏洞传播机制（如 Log4j 漏洞案例）。
  * 安全最佳实践：开源软件的审计和管理（如使用 Dependabot）。
* **参考任务：**
  1. 创建 Github 帐号，初始化一个简单的项目（如 README 文件）。
  2. 为该项目选择一个开源许可证，并撰写一段文字解释选择理由。

---

### **S2: 拥抱开源阶段（采用或参与开源）**

> **目标：** 开始使用开源软件，初步了解开源项目的协作模式。

* **开源协作模式**
  * **如何贡献：** Issue、Pull Request、Code Review。
  * **工具与平台：** 使用 Github、Gitlab 等托管平台。
  * **开源项目工作流：** 了解从 Issue 到 PR 的完整流程。
* **开源软件的替代方案**
  * 举例：用 Linux 替代 Windows，用 LibreOffice 替代 Microsoft Office，用 GIMP 替代 Photoshop，用 VLC 替代商业播放器。
  * **选择适合的发行版：**
    * 桌面发行版：Ubuntu、Deepin、OpenEuler。
    * 服务器发行版：CentOS Stream、Alpine。
* **活动组织**
  * 了解和参与开源社区活动：如 Linux 101、OpenEuler 社区活动等。
  * 通过参与活动了解更多开源工具和资源。
* **参考任务：**
  1. 找到一个可以替换闭源工具的开源软件，并将其应用到日常工作中。
  2. 记录切换开源软件的过程、问题和解决方案，撰写一篇博客分享。

---

### **S3: 贡献开源阶段**

> **目标：** 学习开源基础技能并通过代码或文档的贡献实践开源。

* **开源基础技能**
  * **Git 学习：**
    * Git 的基本操作（clone、commit、push、pull、merge 等）。
    * Git 的原理：分支、HEAD 指针、合并冲突等概念。
    * 进阶技能：使用 Git 提交签名、提交模板。
  * **代码托管平台：**
    * Github、Gitlab、Gitee 等的使用技巧。
    * 项目管理功能：Issue、Milestone、Wiki。
  * **如何写好一个 commit message：**
    * Linux Kernel Patch。
    * Conventional Commits。
    * RustSBI项目的commit message 规范。
  * **文档撰写：**
* **计算机基础知识**
  * The Missing Semester of Your CS Education。
  * **不同方向的简单介绍与开源项目：**
    * 系统开发：Linux Kernel、QEMU。
    * Web 开发：React、Vue。
    * 网络：WireGuard、Cilium。
    * 数据分析：Pandas、Jupyter。
    * 人工智能：TensorFlow、PyTorch。
  * 找到适合自己的方向并选择活跃的开源项目。
* **表达与交流的重要性**
  * 如何清晰表达问题和想法。
  * 如何有效进行跨文化交流。
* **学会如何提问**
  * 如何查找资料：善用 Google 和 Stack Overflow。
  * 提问的基本规范：明确描述问题、给出复现步骤。
* **参考任务：**
  1. 学习使用 Git，完成一次 Fork 并提交 PR 的流程。
  2. 选择一个开源项目，通过贡献文档或代码提交一个 PR。

---

### **S4: 领导开源阶段**

> **目标：** 成为开源项目的领导者，掌握社区管理和开源治理能力。

* **开源社区及其管理**
  * 如何组织和维护开源社区：Code of Conduct、贡献者指南。
  * 如何吸引和管理贡献者：鼓励多样性和贡献。
* **开源社区安全治理**
  * 如何处理安全问题（如 CVE 报告）。
  * 如何保护社区免受恶意代码或行为影响。
* **开源社区合规**
  * 合规流程的重要性：知识产权管理、许可证合规。
  * 如何进行开源项目的合规审计。
* **参考任务：**
  1. 创建一个开源项目，撰写清晰的 README 和贡献者指南。
  2. 通过自己的开源项目吸引其他人贡献并管理他们的贡献。
  3. 如果不想长期维护，可以将项目捐献到俱乐部。
