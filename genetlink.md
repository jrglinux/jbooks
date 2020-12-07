## userspace与kernel的通信方式学习

### 1.1 netlink

netlink.h头文件有三个地方：按顺序依次include下一个（包含关系）

```c
include/net/netlink.h
include/linux/netlink.h
include/uapi/linux/netlink.h
```





### 1.2 genetlink

genetlink.h头文件与netlink.h头文件类似，也是有三个地方：按顺序依次include下一个（包含关系）

```c
include/net/genetlink.h  /*定义genl_ops, genl_family等结构体及函数*/
include/linux/genetlink.h
include/uapi/linux/genetlink.h  /*定义controller的枚举变量，family长度等*/
```

