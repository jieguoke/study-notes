# for循环

```bash
#!/bin/bash
for i in words; do
	#statements
done

for (( i = 0; i < 6; i++ )); do
	#statements
done
```



```bash
#!/bin/bash
#文件名1.for.sh
for x in `ls`; do
    echo ${x}
done
echo "---------------"

for i in a b c d e; do
    echo ${i}
done
echo "---------------"

for j in 1 2 3 4 5; do
    echo ${j}
done
echo "---------------"
```



![image-20211016215533217](C:\Users\lk\AppData\Roaming\Typora\typora-user-images\image-20211016215533217.png)



```bash
#!/bin/bash
#文件名2.for.sh
#for (( i = 20; $i > 0; i-- )); do		#$i > 0 或者 i > 0两种都可以
for (( i = 20; i > 0; i-- )); do
    echo ${i}
done
```



![image-20211016215723100](C:\Users\lk\AppData\Roaming\Typora\typora-user-images\image-20211016215723100.png)

