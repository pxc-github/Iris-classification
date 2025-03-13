# 一、Dataset
Iris数据集是常用的分类实验数据集，由Fisher, 1936收集整理。Iris也称鸢尾花卉数据集，是一类多重变量分析的数据集。数据集包含150个数据样本，分为3类，每类50个数据，每个数据包含4个属性。可通过花萼长度，花萼宽度，花瓣长度，花瓣宽度4个属性预测鸢尾花卉属于（Setosa，Versicolour，Virginica）三个种类中的哪一类。

具体数据详见文件 Iris_data.txt

鸢尾花卉数据集的读取方法是自定义的，继承了pytorch的Dataset类，详见文件 data_loader.py

# 二、Fully connected network
模型的搭建，训练，验证和测试详见文件 fully_connected_network.py 

开启模型的训练，验证和测试只需要在IDE中执行fully_connected_network.py脚本即可；或者在控制台终端执行命令行fully_connected_network.py 脚本的log打印示例如下：
 