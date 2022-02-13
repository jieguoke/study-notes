# until循环

```bash
#!/bin/bash
until [[ condition ]]; do		#直到什么为真之前都进行循环
	#statements
done
```



```bash
#!/bin/bash
#文件名4.until.sh
read num
i=1
until [[ ${i} -eq ${num} ]]; do #直到i=num时,退出循环
    echo ${i}
    let i++
done
```



![image-20211016221215051](C:\Users\lk\AppData\Roaming\Typora\typora-user-images\image-20211016221215051.png)

