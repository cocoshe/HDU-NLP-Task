## 实训专题4：⽂本分类
本专题将提供⼀份80万条经过脱敏处理的短信数据，其中包含⼤量垃圾短信信息，数据由3个字段构成，分别是“短
信id"、"是否垃圾短信"(0代表常规短信，1代表垃圾短信)和”短信⽂本内容“。任务要求采⽤朴素⻉叶斯模型或其他
分类模型，对垃圾短信进⾏分类。主要步骤可包括：
1. 数据读取
2. ⽂本预处理。对原始数据进⾏预处理，如去重、脱敏和分词等操作，然后进⾏词频统计，分别统计垃圾短信和
⾮垃圾短信的词频分布情况，可⽤相应的可视化形式呈现（如词云）。本题提供的数据量较⼤，有80万条，
如实验条件有限，可考虑对数据进⾏采⽤，⽐如抽取5-10万条进⾏模型训练与分类
3. 分类。可采⽤⾃定义的朴素⻉叶斯模型，也可以调⽤第三⽅⼯具，如sci-learn等库内置函数进⾏分类
4. 模型评价。根据划定的测试集进⾏预测，对⽐真实值与预测值，获得准确率，并进⾏结果分析。