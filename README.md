## 这是一个MNIST数据集，可以将此克隆到程序所在的位置,需要将程序中获取数据集方法改为:
  mnist = input_data.read_data_sets('./data/',one_hot=True)
