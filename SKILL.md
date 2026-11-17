---
name: research-story
description: Build evidence-grounded research stories for AI/ML papers. Use when the user asks to find a paper's story, sharpen contributions, organize an abstract/introduction/experiments, diagnose a weak research narrative, or plan experiments that distinguish competing explanations. Supports Chinese and English scientific writing; not fiction or marketing copy.
---

# Research Story

把研究结果组织成读者能检验的论证。核心产物是：读者原先如何理解问题，哪些证据要求修正理解，作者的贡献在什么条件下成立。按用户语言输出，遵守目标会议篇幅和格式。

## 先确定工作模式

- **只有 idea**：给出可竞争的解释、可证伪预测和最小辨别实验；用将来时，不写成已有结果。
- **已有实验**：先核对结果、预算、负结果与替代解释，再选择主线。
- **已有稿件**：定位主张与证据错位，保留有支持的内容，按请求改写。
- **阅读论文**：从原文提取论证链，标明阅读范围；不要把作者解释当作已证事实。

缺材料时先用已有材料完成可做部分。只询问会改变中心结论的信息；不能用编造数字、消融或引用补齐空缺。

## 工作流程

1. **建主张账本。** 识别最重要的 1–3 个主张，记录证据位置、比较条件、替代解释、适用边界。涉及机制、因果、效率、理论或基准时，读取 [证据规则](references/evidence-and-review.md)。区分事实、作者解释、本次推断、待测假设。
2. **找认知变化。** 用具体旧做法及失败条件建立动机。问题不是“很重要但挑战很大”，而是“当前解释/操作在条件 C 下预期 X，观察却是 Y”。若没有反常现象，可从新能力、表示、资源约束或评价目标出发，不强造反转。
3. **选主线。** 读取 [叙事模式](references/story-patterns.md)，选择证据最充分的一条；若尚不能区分，最多给 2–3 个候选及选择它们所需的证据。模式可以组合，但不要把论文写成模块清单。
4. **安排论证。** 每个设计决定对应具体瓶颈；每个中心主张对应必要实验或证明。实验顺序按读者疑问排列：现象真实吗 → 解释靠谱吗 → 方案有效吗 → 优势来自哪里 → 何时失效。理论、资源和立场论文按各自证明义务调整。
5. **再写文字。** 需要摘要、引言或图表时读取 [写作与图表](references/writing.md)。贡献句写“新增了什么可验证认识/能力”，不要只写“提出新框架、做大量实验”。
6. **反向审核。** 删除任何强于证据的词。保留负结果、未支持的预期、成本和边界。若中心机制证据不足，缩小结论或提出辨别实验，不靠修辞补强。

## 默认交付

按用户所需控制长度，不强制输出所有模板。完整 story 诊断通常包括：

1. 一句话中心论点（含必要条件）。
2. 最关键的主张—证据—缺口表。
3. 从问题到结论的段落或图表顺序。
4. 优先级最高的 1–3 项改进；说明每项会改变哪个结论。

给出改写时直接给可用文本，并将尚缺证据的地方标为“待验证”，不要将占位符写成事实。

## 来源与维护

本技能来自一个仍在扩充的论文阅读库，是研究写作方法归纳，不是“获奖概率公式”。[来源与覆盖](references/corpus-status.md) 记录覆盖口径，[案例索引](references/case-index.md) 提供原文入口。仅在需要例证或继续扩充时读取。

阅读状态使用 `not_read / abstract_only / narrative_first_pass / full_text_checked`。首轮表示已读引言、方法、主要证据及边界，不表示复核了全部附录、证明或复现实验。新增论文需保存版本、章节、支持与不支持的结果，再更新模式；不得只凭摘要或奖项升级阅读状态。
