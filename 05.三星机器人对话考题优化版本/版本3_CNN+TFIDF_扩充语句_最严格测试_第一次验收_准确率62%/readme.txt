深度学习准确率:55%
思路:通过深度学习分类，选出概率最高的10个类别。然后对这10个类别进行打分，与深度学习的得分相加，取最高者。
准确率最终:62%,tf-idf帮助提高了7%

代码执行:train.py即可，http服务暂时没有调整，不可用

数据说明:
	三星机器人考题.xlsx,是招标方提供的数据。test表是测试数据
	sentences.txt，是人工扩充的数据
	data.txt，是扩充后的数据
	sameword.txt，自己定义的同义词词表
	quest_label.txt，是从三星机器人考题抽取出来的问题和标签