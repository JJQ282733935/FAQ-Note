# 深度学习环境安装
语言：python<br> 环境：anaconda<br> 工具包:pytorch<br> GPU:cuda<br> IDE:Pycharm or VScode 

## 1.安装python
python下载网址：https://www.python.org/<br>
python安装教程：https://blog.csdn.net/qq_24923619/article/details/160594145?ops_request_misc=elastic_search_misc&request_id=09f20319a54aa6c9d99437e97866ef63&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~top_positive~default-2-160594145-null-null.142^v102^pc_search_result_base5&utm_term=python%E5%AE%89%E8%A3%85&spm=1018.2226.3001.4187

## 2.安装Pycham or VScode
Pycharm下载网址：https://www.jetbrains.com/pycharm/<br>
Pycharm安装教程：https://blog.csdn.net/2401_83413238/article/details/145422332?ops_request_misc=elastic_search_misc&request_id=2235030ab07aa1f3b99619cd4fe91001&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~top_click~default-2-145422332-null-null.142^v102^pc_search_result_base5&utm_term=pycharm%E5%AE%89%E8%A3%85&spm=1018.2226.3001.4187

## 3.安装cuda
cuda网址：https://developer.nvidia.com/cuda/toolkit<br>
cuda安装教程：https://blog.csdn.net/AI_dataloads/article/details/133043869<br>

## 4.安装anaconda
anaconda网址：https://www.anaconda.com/<br>
anaconda安装教程：https://blog.csdn.net/2503_91827165/article/details/147575874?ops_request_misc=&request_id=&biz_id=102&utm_term=anaconda%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduweb~default-0-147575874.142^v102^pc_search_result_base5&spm=1018.2226.3001.4187<br>
环境问题：https://blog.csdn.net/qq_51872445/article/details/130023351?ops_request_misc=elastic_search_misc&request_id=5a5dd8eeeb55ce5ab8d906759896d1e1&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~top_positive~default-1-130023351-null-null.142^v102^pc_search_result_base5&utm_term=anaconda%E7%8E%AF%E5%A2%83%E5%8F%98%E9%87%8F&spm=1018.2226.3001.4187<br>
如果不行，用户变量与系统变量都添加<br>
查看版本是否安装成功:conda -V<br>

## 5.创建coda环境，并安装pytorch<br>
打开anaconda prompt<br>
查看存在环境指令：conda env list<br>
创建环境指令：conda creste -n env_name python3.XX<br>
激活环境：conda activate encv_name<br>
下载pytorch(激活你需要的环境在下载):pip <br>
pytorch网址获取下载指令：https://pytorch.org/<br>
关闭当前环境：conda deactivate<br>
测试：<br>
```python
import torch
print("PyTorch版本:", torch.__version__)
print("绑定的CUDA版本:", torch.version.cuda)
print("cuDNN版本:", torch.backends.cudnn.version())
print("CUDA是否可用:", torch.cuda.is_available())
```