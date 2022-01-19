```
# 参考: https://www.cnblogs.com/hezhiyao/p/8292512.html
# 必须创建python3.6的环境 scipy1.1.0不支持3.8
conda install requests pillow
pip install -U tensorflow-gpu -i https://pypi.tuna.tsinghua.edu.cn/simple
pip install keras ipykernel
pip install scipy==1.12.1 numpy==1.17
```

```
# ipykernel内核
https://blog.csdn.net/weixin_43590796/article/details/115689009
```

```
https://stackoverflow.com/questions/66221788/tf-gradients-is-not-supported-when-eager-execution-is-enabled-use-tf-gradientta
ipynb初始化时添加
tf.compat.v1.disable_eager_execution()
使用tf1兼容模式
```