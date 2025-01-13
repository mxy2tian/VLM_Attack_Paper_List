# VLM_Attack_Paper_List
[VLM-Attack-Survey-2024] Paper list and projects for VLM attacks
# Attacks on Vision-Language Models: A Survey and Beyond

本仓库整理了综述论文 **"Attacks on Vision-Language Models: A Survey and Beyond"** 中提到的相关研究文章及信息。本综述围绕视觉语言模型（VLMs）的攻击与防御方法展开，涵盖了攻击目标、数据操作方法以及相关评估指标。

## 调研范围
- **研究主题**: VLM的攻击分类与防御策略。
- **涉及模型**: 包括 CLIP、BLIP、MiniGPT-4、GPT-4V 等。
- **主要分类**:
  1. **攻击目标**: Jailbreak、Camouflage、Exploitation。
  2. **数据操作方法**: Visual Perturbation、Gradient-Driven Prompts、Human-Like Deceptive Prompts、Typography。
  3. **评估指标**: 转移性、效率、效果。

---

## 核心研究文章列表

| 序号 | 标题                               | 作者            | 目标攻击类型        | 模型           | 发表时间 | 来源       |
|------|------------------------------------|-----------------|---------------------|----------------|----------|------------|
| 1    | **Gradient-Driven Prompts**        | Yang et al.     | Jailbreak           | Stable Diffusion XL | 2024     | CVPR       |
| 2    | **Human-Like Deceptive Prompts**   | Wu et al.       | Jailbreak           | GPT-4V          | 2023     | arXiv      |
| 3    | **Typography Attacks**             | Gong et al.     | Jailbreak           | LLaVA, MiniGPT-4 | 2023     | arXiv      |
| 4    | **Gradient-Driven Prompts**        | Liu et al.      | Jailbreak           | GPT-4          | 2024     | MM         |
| 5    | **Typography Attacks**             | Ma et al.       | Jailbreak           | LLaVA          | 2024     | arXiv      |
| 6    | **Visual Perturbation in Image Captioning** | Zhao et al.     | Camouflage          | CLIP, LLaVA, MiniGPT-4 | 2024     | NeurIPS    |
| 7    | **Visual Perturbation Attacks**    | Ni et al.       | Camouflage          | LLaVA, MiniGPT-4 | 2024     | arXiv      |
| 8    | **Hateful Memes Generation**       | Liang et al.    | Jailbreak           | Stable Diffusion | 2024     | CVPR       |
| 9    | **Exploitation via Visual Inputs** | Gao et al.      | Exploitation        | InstructBLIP, MiniGPT-4 | 2024     | ICLR       |
| 10   | **Gradient-Based Visual Prompt Attacks** | Fan et al.       | Camouflage          | CLIP           | -        | arXiv      |

---

## 数据集概览

| 数据集名称           | 年份  | 数据量       | 适用场景              | 是否与安全相关 |
|----------------------|-------|--------------|-----------------------|---------------|
| ImageNet            | 2009  | 14M          | 图像分类             | ✗             |
| MS-COCO             | 2014  | 164K         | 图像描述             | ✗             |
| Realtoxicityprompts | 2020  | 100K         | 仇恨言论检测         | ✓             |
| SafeBench           | 2023  | 500          | 多任务场景测试       | ✓             |
| JailBreakV          | 2024  | 28K          | 多模态攻击测试       | ✓             |

---

## 主要研究贡献
1. **提出了系统的攻击分类方法**，涵盖不同的目标与数据操作策略：
   - **攻击目标**: Jailbreak 攻击（绕过安全限制）、Camouflage 攻击（诱导错误输出）、Exploitation 攻击（增加资源消耗）。
   - **数据操作方法**: 包括视觉扰动、基于梯度的提示生成、人类模拟的欺骗性提示和印刷体攻击。
2. **评估了防御策略**: 包括模型级防御、响应评估防御、提示级防御等。
3. **探讨了未来研究方向**: 包括改进评估指标、提升模型鲁棒性、开发新的防御机制等。

---

## 链接
- [项目主页](https://github.com/AobtDai/VLM_Attack_Paper_List)
- [论文地址](https://arxiv.org/abs/XXXXXX)

---

## 贡献方式
欢迎通过 PR 提交相关的研究文章或改进建议。

---

## 许可
本仓库遵循 [MIT License](LICENSE)。
