# [python环境相关](https://github.com/dingyue772/gitBlog/issues/5)

**查看cuda版pytorch是否安装成功**
```python
import torch # 如果pytorch安装成功即可导入
print(torch.cuda.is_available()) # 查看CUDA是否可用
print(torch.cuda.device_count()) # 查看可用的CUDA数量
print(torch.version.cuda) # 查看CUDA的版本号
```
**nvcc -V命令不可用**
cudatoolkit没有在电脑环境中安装或者安装了但没有加入环境变量
参考[检查pytorch是否安装成功、查看torch和cuda的版本](https://blog.csdn.net/qq_41340996/article/details/124326865)

**使用.env文件**
import的是`dotenv`，但install的是`python-dotenv`包

**修改pip命令安装包的默认路径**
参考[python之修改pip默认install路径](https://blog.csdn.net/pyt1234567890/article/details/115866935)

