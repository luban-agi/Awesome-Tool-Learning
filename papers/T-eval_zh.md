

## 指标
将 tool leanring 的评估分成了6个部分，分别是plan、reasone、retrieve、understand、review

### plan
对plans进行sbert 向量化，然后比较最长公共序列相似度
### reason
比较思考的相似度
### retrieve
工具检索的准确性
### understand
参数填参的准确性
### instruct
似乎是retrieve和instrct的结合
### review
判断这个工具是否完成这个子任务，类别准确性判断

## 数据
multi-agent拆分任务到子agent + 人工校验数据

## 结论
大部分都不重要，后面比较不同模型在  T-eval 与 toolbench上的  score趋势，说明t-eval的评估策略与GPT-4评估基本一致
