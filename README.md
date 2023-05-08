# 中文Instruction tuning datasets

# NLP 任务数据转换
| name | link | license | tip | number |
| ---- | ---- | ----    | ---- | ---- |
|firefly-train-1.1M| [Firefly](https://github.com/yangjianxin1/Firefly)| none | 23个常见中文数据集上由人工书写若干指令模板构造 | 110 万 |
|pCLUE | [pCLUE](https://github.com/CLUEbenchmark/pCLUE) | none |单分类tnews/单分类iflytek/自然语言推理ocnli/语义匹配afqmc/指代消解-cluewsc2020/关键词识别-csl/阅读理解-自由式c3/阅读理解-抽取式cmrc2018/阅读理解-成语填空chid 共9个数据集，73个prompt 转换而来 | 120 万 |
|xP3mt_zh | [xP3mt-zh](https://huggingface.co/datasets/bigscience/xP3mt/tree/main/zh) |apache-2.0 |原始xP3（英语）通过翻译得到的中文数据集 | 3571636 |

# LLM 生成
| name | link | license | tip | number |
| ---- | ---- | ----    | ---- | ---- |
|Belle | [BELLE](https://github.com/LianjiaTech/BELLE) | gpl-3.0 | 参考[Stanford Alpaca](https://github.com/tatsu-lab/stanford_alpaca) 生成的中文数据集 | 50万/100万/200万/1000万 |
|alpaca_chinese_dataset | [alpaca_chinese_dataset](https://github.com/hikariming/alpaca_chinese_dataset) | MIT | 人工校验了21K 左右的[alpaca](https://github.com/carbonz0/alpaca-chinese-dataset) 翻译数据集,并增加了许多中文特色数据集 | > 21 K |
|COIG | [COIG](https://github.com/BAAI-Zlab/COIG) | Apache 2.0/MIT/CC-BY-SA-4.0 | <li> 67798个指令数据集（1616 个来着[Super-NaturalInstructions](https://arxiv.org/abs/2204.07705)的任务表述 + 175 个[self-instruct](https://arxiv.org/abs/2212.10560)中的种子任务 + 66007 个来自[Unnatural Instructions](https://arxiv.org/abs/2212.09689)）的翻译 <li> 63532 个考试（高考/中考/公务员考试）数据集 <li> Human Value Alignment Instructions (34,471) <li>Counterfactural Correction Multi-round Chat (13,653) <li> Leetcode Instructions (11,737)| 191,191|
|MOSS | <li>[moss-002-sft-data](https://huggingface.co/datasets/fnlp/moss-002-sft-data) <li> [moss-003-sft-data](https://github.com/OpenLMLab/MOSS/tree/main/SFT_data/conversations/conversation_without_plugins) | cc-by-4.0 | <li> moss-002-sft-data覆盖有用性、忠实性、无害性三个层面，包含由text-davinci-003生成的约57万条英文对话和59万条中文对话。<li> moss-003-sft-data 基于MOSS-002内测阶段采集的约10万用户输入数据和gpt-3.5-turbo构造而成，相比moss-002-sft-data，moss-003-sft-data更加符合真实用户意图分布，包含更细粒度的有用性类别标记、更广泛的无害性数据和更长对话轮数，约含110万条对话数据。目前仅开源少量示例数据，完整数据将在近期开源。| <li> 59万 中文对话 <li> 110万条对话 |
|HC3-Chinese | [HC3-Chinese](https://huggingface.co/datasets/Hello-SimpleAI/HC3-Chinese) | cc-by-sa-4.0 | 人类-ChatGPT 对比语料 | 12853 |
