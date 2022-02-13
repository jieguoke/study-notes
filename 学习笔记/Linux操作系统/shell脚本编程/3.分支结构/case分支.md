# case分支

```bash
#!/bin/bash

case word in
	pattern1 )
		;;				#相当于c语言中的break;
	pattern2 )
		;;
	pattern3 )
		;;
esac
```



```bash
#!/bin/bash
#文件名2.case.sh
read num
flag=$[${num} % 2]
case ${flag} in
    0 )
        echo "偶数"
        ;;
    1 )
        echo "奇数"
        ;;
esac

```



![image-20211016214653785](C:\Users\lk\AppData\Roaming\Typora\typora-user-images\image-20211016214653785.png)

