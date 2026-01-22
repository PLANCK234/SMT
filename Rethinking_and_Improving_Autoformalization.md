# Rethinking and Improving Autoformalization:Towards a Faithful Metric and a Dependency Retrieval-based Approach

(Oringinating from Junchi Yan SJTU)

## Statement Autoformalization

### What do we need in statement autoformalization?
- BEq: 判断两个形式化表示是否等价
- RAutoformalizer: dependency retrieval + toplogical informalization 避免llm的hallucinate lemma
- Con-NF benchmark: 用于OOD evaluation

### Evaluation from natural expression to lean
Requirement: faithful, flexible, interpretable, semantic equivalence evaluation <br>
- faithful: 不能引入额外自由度，不要把具体对象变成参数。
- flexible
- interpretable
- semantic equivalence

![Evaluation Metric](./pictures/Qwen2.5-Omin_architecture.png)

### 
