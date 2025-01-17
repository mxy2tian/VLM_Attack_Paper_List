# VLM_Attack_Paper_List
[VLM-Attack-Survey-2024] Paper list and projects for VLM attacks
# Attacks on Vision-Language Models: A Survey and Beyond

This repository organizes the relevant research papers and information mentioned in the review paper **"Attacks on Vision-Language Models: A Survey and Beyond"** The review focuses on the attacks and defense methods for Vision-Language Models (VLMs), covering attack goals, data manipulation methods, and relevant evaluation metrics.
## Scope of the Survey
- **Research Topics**: Classification of VLM attacks and defense strategies.
- **Involved Models**: Including CLIP, BLIP, MiniGPT-4, GPT-4V, etc.
- **Main Categories**:
  1. **Attack Goals**: Jailbreak, Camouflage, Exploitation.
  2. **Data Manipulation Methods**: Visual Perturbation、Gradient-Driven Prompts、Human-Like Deceptive Prompts、Typography。
  3. **Evaluation Metrics**: Transferability, Efficiency, Effectiveness.

---

# **1:Taxonomy of Attack Goal**
## **1.1：Jailbreak Attack**
- **1.1.1:NSFW 图像**
- [57]: To generate or not? safety-driven unlearned diffusion models are still easy to generate unsafe images ... for now
- [58]: Ring-a-bell! how reliable are concept removal methods for diffusion models? 
- [50]: Mma-diffusion: Multimodal attack on diffusion models
- **1.1.2:Hateful Memes**
- [59]: Unsafe diffusion: On the generation of unsafe images and hateful memes from text-to-image models.
- **1.1.3:NSFW Text**
- [47]: Jailbreaking large vision-language models via typographic visual prompts.
- [49]: Mm-safetybench:A benchmark for safety evaluation of multimodal large language models
- [60]: Compositional adversarial attacks on multi-modal language models.
- [61]: Whitebox multimodal jailbreaks against large vision-language models
- [62]: Jailbreaking multimodal large language models via shuffle inconsistency
- **:Training Data Extraction**
- [63]: Extracting training data from large language models
- [64]: Va3: Virtually assured amplification attack on probabilistic copyright protection for text-to-image generative models
- [23]: Jailbreaking gpt-4v via self-adversarial attacks with system prompts
## **Adversarially**
- **Model-level Defense**
- [70]: Dress:Instructing large vision-language models to align and interact with humans via natural language feedback
- [71]: lm-protector: Ensuring mllm’s safety without hurting performance
- [72]: Safety fine-tuning at (almost) no cost: A baseline for vision large language models
- **Response Assessment-based Defense**
- [73]: Eyes closed, safety on: Protecting multimodal llms via image-to-text transformation
- **Prompt-level Defense**
- [74]: Jailguard: A universal detection framework for llm prompt-based attacks
- [75]: Adashield: Safeguarding multimodal large language models from structure-based attack via adaptive shield prompting
## **1.2：Camouflage**
- [53]: On evaluating adversarial robustness of large vision-languagemodels
- [76]: Adversarial illusions in multi-modal embeddings
- [54]: Physical backdoor attack can jeopardize driving with vision-large-language models
- [77]: Misusing tools in large language models with visual adversarial examples
## **Adversarially**
- [5]: Learning transferable visual models from natural language supervision
- [78]: Steering away from harm: An adaptive approach to defending vision language model against jailbreaks
## **1.3：Exploitation**
- [79]: Nicgslowdown: Evaluating the efficiency robustness of neural image caption generation models
- [80]: Slowlidar: Increasing the latency of lidar-based detection using adversarial examples
- [81]: The dark side of dynamic routing neural networks: Towards efficiency backdoor injection
- [82]: Chain-of-thought prompting elicits reasoning in large language models
- [83]: Self-consistency improves chain of thought reasoning in language models
- [84]: Stop reasoning! when multimodal llm with chain-of-thought reasoning meets adversarial image

# **2:Taxonomy of Data Manipulation Strategy**
## **2.1:Visual Perturbation**
- [85]: Explaining and harnessing adversarial examples
- [86]: Adversarial examples in the physical world
- [87]: Towards deep learning models resistant to adversarial attacks
- [88]: Boosting adversarial attacks with momentum
- [89]: On the adversarial robustness of multi-modal foundation models
- [90]: Transferable multimodal attack on vision-language pre-training models
- [91]: Vlattack: Multimodal adversarial attacks on vision-language tasks via pre-trained models
- [92]: Set-level guidance attack: Boosting adversarial transferability of vision-language pre-training models
- [93]: Boosting transferability in vision-language attacks via diversification along the intersection region of adversarial trajectory
- [77]: Misusing tools in large language models with visual adversarial examples
- [96]: Poisoning and backdooring contrastive learning
- [97]: Advclip: Downstream-agnostic adversarial examples in multimodal contrastive learning
- [98]: Text-to-image diffusion models can be easily backdoored through multimodal data poisoning
- [99]: Vl-trojan: Multimodal instruction backdoor attacks against autoregressive visual language models,
- [100]: Towards feature space adversarial attack by style perturbation
## **Adversarially**
- [101]: Robust clip: Unsupervised adversarial fine-tuning of vision embeddings for robust large vision-language models,
- [102]: On the robustness of large multimodal models against image adversarial attacks

## **2.2:Gradient-Driven Prompts**
- [46]: Universal and transferable adversarial attacks on aligned language models
- [63]: Extracting training data from large language models
- [105]: Deep text classification can be fooled
- [106]: Textbugger: Generating adversarial text against real-world applications
- [107]: Is bert really robust? a strong baseline for natural language attack on text classification and entailment
- [51]: Arondight: Red teaming large vision language models with auto-generated multi-modal jailbreak prompts
- [50]: Mma-diffusion: Multimodal attack on diffusion models
## **Adversarially**
- [108]: Securing vision-language models with a robust encoder against jailbreak and adversarial attacks
- [109]: One prompt word is enough to boost adversarial robustness for pre-trained vision-language models

## **2.3:Human-Like Deceptive Prompts**
- [23]: Jailbreaking gpt-4v via self-adversarial attacks with system prompts
- [32]: OpenAI, “Gpt-4v(ision) system card
## **Adversarially**
- [113]: How easy is it to fool your multimodal llms? an empirical analysis on deceptive prompts
## **2.4:Typography**
- [47]: Figstep: Jailbreaking large vision-language models via typographic visual prompts
- [52]: Visual-roleplay: Universal jailbreak attack on multimodal large language models via role-playing image character
- [60]: Jailbreak in pieces: Compositional adversarial attacks on multi-modal language models
- [114]: Vision-llms can fool themselves with self-generated typographic attacks
- [115]: Empirical analysis of large vision-language models against goal hijacking via visual prompt injection
- [49]: Mm-safetybench: A benchmark for safety evaluation of multimodal large language models
- [60]: Jailbreak in pieces: Compositional adversarial attacks on multi-modal language models
## **Adversarially**
- [116]: Defense-prefix for preventing typographic attacks on clip
- [117]: Unveiling typographic deceptions: Insights of the typographic vulnerability in large vision-language models


---

## 数据集概览

| Dataset Name        | year  | size         | Application Scenario        | Security-Related  |
|---------------------|-------|--------------|-----------------------------|-------------------|
| ImageNet            | 2009  | 14M          | Image Classification        | ✗                |
| MS-COCO             | 2014  | 164K         | Image Captioning            | ✗                |
| Realtoxicityprompts | 2020  | 100K         | Hate Speech Detection       | ✓                |
| SafeBench           | 2023  | 500          | Multi-task Scenario Testing | ✓                |
| JailBreakV          | 2024  | 28K          | Multimodal Attack Testing   | ✓                |

---

## Key Research Contributions
1. **Proposed a systematic classification of attacks**, covering different goals and data manipulation strategies:
   - **Attack Goals**: Jailbreak attacks (bypassing security restrictions), Camouflage attacks (inducing incorrect outputs), Exploitation attacks (increasing resource consumption).
   - **Data Manipulation Methods**: Including visual perturbation, gradient-driven prompt generation, human-like deceptive prompts, and typography attacks.
2. **Evaluated defense strategies**: Including model-level defenses, response assessment-based defenses, and prompt-level defenses.
3. **Explored future research directions**: Including improving evaluation metrics, enhancing model robustness, and developing new defense mechanisms.

---

## Links
- [Project Homepage](https://github.com/AobtDai/VLM_Attack_Paper_List)
- [Paper Link](https://arxiv.org/abs/XXXXXX)

---



## License
This repository is licensed under the MIT License.
