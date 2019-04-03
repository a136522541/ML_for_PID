# ML_for_PID
主文件是pid.ipynb，
e_info.dat和pi_info.dat是数据文件，分别记录了电子和pion的飞行参数，每一行对应一个事例
利用11维数据，比较它们的分布与标签之间的关系后，建立不同的分类器，并比较分类器之间的性能
根据ROC曲线，比较的结果为XGBoost表现最好，其次为DNN和SVM，然后是LR
