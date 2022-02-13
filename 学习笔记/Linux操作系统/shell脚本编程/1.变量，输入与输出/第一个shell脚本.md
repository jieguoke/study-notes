# 第一个shell脚本

```bash
#!/bin/bash
#文件名 1.firsh.sh
echo 'hello Kaikeba' #this is a commint 这是注释
```



## 调试

### 通过终端进行调试

```bash
bash -x 1.firsh.sh
```







### 在shell脚本中设置调试

```bash
#!/bin/bash
#文件名 1.firsh.sh
set -x				 #开始调试
echo 'hello Kaikeba' #this is a commint 这是注释
set +x				 #结束调试
echo 'bye'
```


