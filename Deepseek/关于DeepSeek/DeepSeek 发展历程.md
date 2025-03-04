## DeepSeek 发展历程

## 创立与发展

### 创立背景

- **起源于金融量化领域**
  DeepSeek 的前身团队来自于中国领先的量化投资机构——幻方量化。创始人及团队在量化交易中积累了丰富的深度学习和大数据应用经验，他们最初利用 AI 技术实现股票交易和数据分析。随着全球对大语言模型（LLM）关注度的急剧上升，团队意识到研发通用型大模型对于中文市场及专业领域（如编程、数学等）的重要性。
- **国产大模型自主研发的需求**
  在中美技术竞争和芯片出口限制等背景下，国内急需突破国外垄断的大模型技术。DeepSeek 团队选择成立一家独立的人工智能基础技术研究公司，专注于低成本、高性能模型的研发，既满足国内市场对中文语境下 AI 的需求，又为国产大模型产业提供标杆。
- **战略定位与资金支持**
  2023 年 7 月，DeepSeek 正式在杭州成立，其全称为“杭州深度求索人工智能基础技术研究有限公司”，隶属于幻方量化。充足的资金和技术积累为 DeepSeek 的早期研发提供了坚实保障，同时也定位于未来在人工智能领域实现“通用智能”的长远目标。

### 发展阶段

- 2023年7月17日，幻方量化成立了DeepSeek。
- 2023年10月28日，DeepSeek发布DeepSeek-Coder，这是深度求索的第一个大模型，11月29日，发布DeepSeek-LLM。
- 2023年12月15日，DeepSeek发布DreamCraft3D，是一个3D生成模型。
- 2024年1月11日，DeepSeek发布DeepSeek-MoE，性能超越Llama 2-7B，且计算量降低60%。
- 2024年2月5日，DeepSeek发布DeepSeekMath，DeepSeekMath 在竞赛级MATH基准测试中获取了51.7%的优异成绩，且未依赖外部工具包和投票技术，接近Gemini-Ultra和GPT-4的性能水平。
- 2024年3月11日，DeepSeek发布DeepSeek-VL。
- 2024年5月，DeepSeek发布并开源了旗下MoE大模型DeepSeek-V2，因其模型架构与经济性而脱颖而出，DeepSeek-V2的API定价为每百万tokens输入1元、输出2元，价格仅为GPT-4 Turbo的百分之一。
- 2024年6月17日，DeepSeek发布DeepSeek-Coder-V2，DeepSeek-Coder-V2在代码特定任务中达到了与GPT4-Turbo相当的性能。 DeepSeek-Coder-V2在程序设计和数学基准测试中表现优异，超越了GPT4-Turbo、Claude 3 Opus和Gemini 1.5 Pro等模型。
- 2024年8月16日，DeepSeek同时发布DeepSeek-Prover-V1.5和DeepSeek-Prover-V1。
- 2024年9月5日，DeepSeek 宣布合并 DeepSeek Coder V2 和 DeepSeek V2 Chat 两个模型，升级推出全新的 DeepSeek V2.5 新模型。
- 2024年11月20日，DeepSeek 发布 DeepSeek-R1-Lite，是深度求索第一个推理模型。
- 2024年12月13日，发布用于高级多模态理解的专家混合视觉语言模型——DeepSeek-VL2。同月26日，DeepSeek发布并开源了DeepSeek-V3，DeepSeek表示该大模型的训练系基于2,048块英伟达H800型GPU（针对中国大陆市场的低配版GPU）集群上运行55天完成，训练耗资557.6万美元；DeepSeek-V3的评测成绩超越Qwen2.5-72B（阿里自研大模型）和LLaMA 3.1-405B（Meta自研大模型）等开源模型，能与GPT-4o、Claude 3.5-Sonnet（Anthropic自研大模型）等闭源模型相抗衡。
- 2025年1月20日， DeepSeek发布并开源了DeepSeek-R1模型，该模型在数学、代码、自然语言推理等任务上，性能与OpenAI o1正式版相当。
- 2025年1月27日，DeepSeek智能助手在美区苹果App Store下载榜上超越ChatGPT，并登顶App Store免费应用榜榜首。
- 2025年1月27日，DeepSeek发布多模态大模型Janus-Pro。
- 2025年2月9日，DeepSeek宣布结束优惠体验期，调整后的API服务的输入tokens和输出tokens价格分别上涨100%和300%。

## 重要里程碑

### **创立与早期探索（2023 年下半年）**

- **2023 年 7 月**：

  - **公司成立**
    杭州深度求索人工智能基础技术研究有限公司（DeepSeek）正式成立，隶属于幻方量化。团队凭借在量化交易中积累的深度学习和大数据经验，开始向通用大模型研发转型，目标是解决中文语境下的 AI 应用需求，同时应对中美技术竞争背景下的国产自主研发挑战。

- **初步产品发布与探索阶段（2023 年末）**
- **2023 年 11 月**：
  - **DeepSeek Coder 发布**
    这是 DeepSeek 的首个产品，专注于编程辅助、代码生成与自动补全，标志着团队在技术迁移和专业场景应用上的初步尝试。
  - **DeepSeek-LLM 系列发布**
    随后推出的通用大语言模型产品，开始尝试与国际主流 LLM（如 Llama 系列）接轨，同时针对中文和特定专业领域进行优化。

### **产品细分与技术扩展（2024 年）**

- **2024 年初至中期**：
  - **DeepSeek-MoE（1 月）**
    引入了专家混合模型（MoE）架构，通过“共享专家”与“路由专家”的设计，既保证了通用知识的捕捉，也能高效地处理特定领域的输入。
  - **DeepSeek-Math（4 月）**
    专注于数学推理，推出了多个版本（Base、Instruct、RL），利用强化学习和专用奖励机制（如过程奖励模型）大幅提升在数学问题上的表现。
  - **DeepSeek-V2 系列（5 月）**
    在之前产品的基础上，DeepSeek-V2 通过进一步优化数据集、引入多头潜在注意力（MLA）和 MoE 技术，实现了在模型性能、成本控制和推理效率方面的突破。
  - **DeepSeek-Coder V2 系列（6 月）**
    对编程辅助模型进行了升级，进一步提高了代码生成的准确性和上下文理解能力。

- **2024 年后期**：
  - **DeepSeek-V2.5（9 月至 12 月）**
    作为 V2 系列的升级版，V2.5 融合了语言与代码模型的优势，提供了更好的稳定性和响应速度。
  - **DeepSeek-V3（12 月）**
    发布了 DeepSeek-V3-Base 及聊天版本，主要特点包括超长上下文支持（最高 128K tokens）、进一步优化的 MLA 以及更精细的 MoE 架构设计，大幅降低了训练成本，同时提升了模型生成质量。

### **商业化爆发与生态扩展（2025 年及以后）**

- **2025 年初**：
  - **DeepSeek-R1-Lite-Preview（11 月 2024 发布，2025 年初推广）**
    针对复杂推理任务推出了 R1 系列预览版本，该模型在数学、逻辑推理和编程等方面表现出色，为后续正式版的推出奠定了基础。
  - **DeepSeek-R1 正式发布（2025 年 1 月）**
    在经过大量 SFT（监督微调）与强化学习（采用 GRPO 等算法）的训练后，DeepSeek-R1 在推理能力上取得了与国际主流模型（如 OpenAI o1）相当的表现，并通过移动端聊天机器人迅速走红。
  - **蒸馏与小模型应用**
    基于 R1 的强大推理能力，团队还推出了多款通过蒸馏技术优化后的轻量级版本（DeepSeek-R1-Distill 系列），使得小型模型也能具备卓越的逻辑推理和问题求解能力，便于在更广泛的场景中应用。

## 版本更新

- **DeepSeek Coder 与 DeepSeek-LLM（2023 年 11 月）**
- 以初版产品为起点，重点展示了团队在自然语言处理和代码生成上的基本能力，并为后续产品提供了技术积累和市场验证。
- **DeepSeek-MoE（2024 年 1 月）**
- 推出了基于 MoE 架构的模型，通过共享专家和路由专家的创新设计，使得模型在参数规模极大的情况下，仅激活一部分计算资源，从而显著提高了效率和成本效益。
- **DeepSeek-Math（2024 年 4 月）**
- 针对数学与逻辑推理任务推出专门版本，采用专用的强化学习策略（如 GRPO 算法）和奖励机制，显著提升了模型在数学基准测试中的得分，满足了高难度专业任务的需求。
- **DeepSeek-V2 与 V2.5（2024 年 5 月—12 月）**
- **V2 系列**：在预训练数据和模型架构上进行了优化，采用了多头潜在注意力（MLA）和 MoE 技术，使模型在长文本生成、中文理解和专业场景（如编程）的表现上有显著提升。
- **V2.5**：作为对 V2 的改进，进一步整合了语言模型与代码模型的优势，在响应速度、生成质量以及训练成本上实现了更优平衡。
- **DeepSeek-V3（2024 年 12 月）**
- V3 系列是 DeepSeek 的又一重大升级版本，主要突破包括：
  - **上下文扩展**：支持高达 128K tokens 的上下文处理，使模型能处理超长文本任务；
  - **架构优化**：在 MLA、MoE、以及多 token 预测技术上进行了全面优化，极大地降低了训练成本并提升了推理效率；
  - **应用场景**：不仅提升了通用文本生成能力，同时在专业任务（如数学推理、编程辅助）上表现更为突出。

- **DeepSeek-R1 系列（2024 年 11 月预览、2025 年 1 月正式发布）**
- **R1-Lite-Preview**：最初推出预览版本，主要用于验证模型在推理链生成、逻辑推理及数学编程任务上的能力；
- **正式版 R1**：经过 SFT 和大规模强化学习训练后，R1 在推理、数学和代码生成等方面达到了与国际领先模型相当的水平，并迅速在全球市场（尤其是移动端应用）走红；
- **蒸馏版本**：基于 R1 输出的高质量推理数据，进一步训练出轻量级版本，使得小型模型也能获得强大的逻辑推理能力，便于在资源受限的场景中应用。

## DeepSeek 的未来发展方向

### 技术与算法创新

1. **深度优化基础架构**
   DeepSeek 已在 Transformer 架构上通过引入多头潜在注意力（MLA）、混合专家模型（MoE）以及低精度混合训练等技术，实现了大幅降低训练与推理成本的目标。未来，DeepSeek 可能会继续沿着这条路深入：
  - 持续改进 MoE 架构和专家路由策略，使得模型在保持参数规模庞大的同时，每个 token 仅激活一小部分参数，进一步提高计算效率。
  - 推动强化学习与模型蒸馏技术的进步，通过更简单高效的奖励机制（如 GRPO 算法），使得模型在复杂推理和长链思考上的能力不断突破。

1. **多模态与跨领域融合**
   目前 DeepSeek 已开始布局视觉语言模型（如 DeepSeek-VL），未来有望在语音、视频等多模态领域取得突破。多模态融合不仅能丰富模型的表达能力，还将满足智慧客服、智能监控、自动驾驶等对跨模态信息处理的迫切需求。[]
2. **内生智能与自主智能探索**
   长远来看，DeepSeek 将不仅仅满足于生成文本或代码，而是探索让 AI 自主学习、自我提升的内生智能（EI）和自主智能（II）方向。这意味着模型将更主动地理解环境、规划决策，甚至在一定程度上实现自我反思和改进，从而向 AGI 的方向迈进。

### 应用场景拓展

1. **边缘计算与本地部署**
   随着数据隐私、实时性要求的提升，本地部署和边缘计算将成为重要发展方向。DeepSeek 未来可能会进一步优化部署方案，使模型能够在企业内部、终端设备或边缘设备上高效运行，满足金融、医疗、工业等对数据安全和实时响应要求较高的场景。
2. **垂直行业定制解决方案**
   随着技术成熟，DeepSeek 有望针对不同行业（如金融风控、智能客服、医疗影像、智慧教育等）推出定制化模型和应用。通过细粒度微调和数据集成，这些垂直解决方案将更好地满足行业特定需求，实现商业价值的突破。
3. **端侧应用与轻量模型普及**
   利用模型蒸馏技术，DeepSeek 已在推动小模型的高效推理能力，使得部署在个人电脑、手机甚至智能终端的端侧模型变得可行。低成本、高效率的端侧模型将帮助更多中小企业及个人用户享受到先进的 AI 能力，促进 AI 的普及应用。

### 生态构建与商业模式

1. **开放生态与全球协作**
   DeepSeek 坚持开源战略，通过开放 API 和模型代码，吸引全球开发者和企业共同构建生态系统。未来，该公司将继续与硬件供应商（如华为、阿里云等）、学术机构和其他 AI 初创企业展开合作，共同推动“算力–模型–场景”的协同创新，形成开放互惠的生态圈。
2. **商业化应用与定制化服务**
   随着技术不断成熟，DeepSeek 将不仅专注于基础模型研发，更会向商业应用延伸。通过与金融、医疗、教育等行业的深度合作，推出行业专属的 AI 解决方案，实现从技术研发到商业落地的全链条转化。
3. **成本控制与高效资源利用**
   通过低成本训练策略与高效分布式训练技术，DeepSeek 在保持竞争力的同时，也将继续优化硬件与能源消耗，推动 AI 模型在全球范围内的普及和应用。这一优势有望吸引更多企业采用其技术，从而推动整个产业向更高性价比的方向发展。



> 参考：[https://zh.wikipedia.org/wiki/%E6%B7%B1%E5%BA%A6%E6%B1%82%E7%B4%A2](https://zh.wikipedia.org/wiki/深度求索)
>
> [https://blog.csdn.net/lly576403061/article/details/145490147](https://blog.csdn.net/lly576403061/article/details/145490147)
>
> [https://blog.csdn.net/lly576403061/article/details/145490147](https://api-docs.deepseek.com/zh-cn/updates)