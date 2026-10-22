# 透明物体感知实验结果

本公开仓库仅保存MODEST研究项目的`results/`文件夹快照，供他人查看评估JSON、实验日志、预测图和可视化对比图。未包含项目源码、模型权重、数据集、表格文档或原项目Git历史。

## 阅读入口

- [结果文件夹](results/)
- [5375样本评估记录](results/eval_syntodd_test_5375.json)
- [RGB与真实标注及预测结果对比](results/qual_syntodd_test_grid.png)
- [分割预测图](results/seg.png)
- [深度可视化](results/depth.png)
- [初步消融分析](results/ablation_analysis.md)

## 结果解释

本仓库保存已有结果，本次发布没有重新运行实验。记录中的米制深度与归一化深度应分别理解；JSON内的论文参考值不是本项目实测值，比较前需核对指标单位、评价区域和实现。

消融基线和重训变体的测试规模及训练条件尚未统一，`ablation_analysis.md`及图表中关于模块贡献排序的表述属于原始分析，当前不能据此确定各模块的独立贡献或声称优于原模型。这些结果也不代表真实机械臂抓取验证。

算法来源：[D-Robotics-AI-Lab/MODEST](https://github.com/D-Robotics-AI-Lab/MODEST)。此处为独立结果快照，后续原项目的更新不会自动同步。
