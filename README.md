# 汽车问答摘要与推理
作者：刘如日    
北京航空航天大学 内容安全课设

代码结构

+ data  数据集  
+ result 结果保存路径    
+ pgn_tf2 指针汇聚网络模型结构（利用TF2实现）  
+ utils 工具包  
    + config  配置文件
    + data_loader 数据处理模块
    + multi_proc_utils 多进程数据处理


训练步骤:
1. 运行utils\data_loader.py可以一键完成 预处理数据 构建数据集
2. 训练与评估模型 运行main.py脚本

参考的模型论文:  
模型论文：Get To The Point: Summarization with Pointer-Generator Networks