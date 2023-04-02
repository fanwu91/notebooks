## 常用的国内镜像站
- 清华大学：https://pypi.tuna.tsinghua.edu.cn/simple

- 华为云：https://repo.huaweicloud.com/repository/pypi/simple

- 阿里云：http://mirrors.aliyun.com/pypi/simple/

## 临时使用
### 在使用pip的时候加参数-i 
例如：pip install -i https://pypi.tuna.tsinghua.edu.cn/simple pyspider。

## 长久使用
- 在用户目录下，创建 **pip.conf** 文件

```
mkdir ~/.pip
vim ~/.pip/pip.conf
```

- 输入如下内容，以清华镜像为例
```
[global]
index-url = https://pypi.tuna.tsinghua.edu.cn/simple
[install]
trusted-host = https://pypi.tuna.tsinghua.edu.cn
```