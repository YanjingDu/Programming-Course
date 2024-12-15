# 《冰与火之歌》角色存活率的可视化分析与预测

## 项目简介
《冰与火之歌》系列是乔治·R·R·马丁的杰作，自1996年首部作品《权力的游戏》出版以来，吸引了全球数以百万计的读者。这个系列不仅在文学上取得了巨大成功，还被改编成同名电视剧，进一步扩大了其影响力。故事发生在维斯特洛大陆，一个充满神秘和危险的世界，权力斗争是永恒的主题。本项目旨在通过对《冰与火之歌》角色存活概率的可视化分析及预测，提供一个独特且引人入胜的视角，帮助读者更深入地理解《冰与火之歌》中的权力斗争、家族荣誉、个人选择和命运的交织。
具体来说，首先通过散点图、堆叠条形图、热力图和水平条形图等可视化工具，揭示了角色存活状态与直系亲属死亡数、出场情况、所属文化族群以及流行程度之间的潜在联系。其次，采用 Logistic 回归和 XGBoost 两种机器学习算法进行建模分析，并比较两种算法的不同。分析的最终目的不仅仅是预测角色的生死，更重要的是，它能够为我们提供一种新的视角，

本项目使用的数据集为角色存活概率预测数据集 `character-predictions.csv`，由“A Song of Ice and Data”团队从 http://awoiaf.westeros.org/ 爬取而来，包含了对哪些角色将会死亡的预测。




