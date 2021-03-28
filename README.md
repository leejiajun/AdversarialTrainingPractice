# AdversarialTrainingPractice

## 工具：
- AutoAttack [https://github.com/fra31/auto-attack]: 引用上涨有点慢，主要是APGD和PGD不算大。重要的是AA指标混合了4种攻击，测出来的对抗精度更靠谱些。
- FoolBox [https://github.com/bethgelab/foolbox]: 找the worst-case很发方便
- cleverhans [https://github.com/cleverhans-lab/cleverhans]: 收录了benchmark的attck, 社区活跃
- advertorch [https://github.com/BorealisAI/advertorch]: 很久没维护了
- torchattack [https://github.com/Harry24k/adversarial-attacks-pytorch]: 各种重要的攻击方法很全，生成对抗样本的速度对比了ART和FB，torchattack最快。似乎有些bug，且不支持labels=None

## 论文：
- On Evaluating Adversarial Robustness [https://github.com/evaluating-adversarial-robustness/adv-eval-paper]: 开源，可以去贡献
- Obfuscated Gradients Give a False Sense of Security: Circumventing Defenses to Adversarial Examples: 探讨gradient masking, 自行补充和Goodfellow相关的八卦
- Adversarial Machine Learning at Scale [https://arxiv.org/abs/1611.01236]: 讲到了leaking label现象。
