# while循环

```bash
#!/bin/bash
while [[ condition ]]; do
	#statements
done
```



```bash
#!/bin/bash
read num
while [[ ${num} -gt 0 ]]; do
    if [[ $[${num} % 10] -eq 0 ]]; then	#模10等于0不输出
        let num--
        continue
    fi
    if [[ ${num} -eq 4 ]]; then			#等于4退出while循环
        break
    fi
    echo ${num}
    #num=$[ ${num} - 1 ]
    let num--
done
```



![image-20211016220610055](C:\Users\lk\AppData\Roaming\Typora\typora-user-images\image-20211016220610055.png)
