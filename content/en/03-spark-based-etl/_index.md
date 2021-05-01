



+++
title = "基于Spark的ETL任务"
weight = 11

pre = "<b>3. </b>"
+++


这一节将演示在EMR集群上使用多种方式提交Spark ETL任务。例如，可以登录到主节点使用CLI提交任务，或使用JupyterHub notebook来提交，也可以通过添加EMR Steps来实现。



### 任务介绍
* 从S3上读取CSV数据
* 在数据集上新增一列当前日期
* 将更新的数据集以Parquet格式保存到S3



