# Hackintosh

## 配置

| 配置   | 型号                    | 价格 |
| ------ | ----------------------- | ---- |
| CPU    | Intel 13490F            | 1244 |
| 主板   | 铭瑄B760ITX WIFI        | 834  |
| 显卡   | 蓝宝石RX6650XT 8G超白金 | 1999 |
| 内存   | 金百达银爵 16G 3600  X2 | 365  |
| 硬盘   | 爱国者P7000Z 1T PCIE4.0 | 318  |
| 电源   | 银欣SFX SX-600W         | 345  |
| 散热器 | 乔思伯HX6210            | 172  |
| 网卡   | 博通94360NG             | 256  |
| 机箱   | 笨牛U45                 | 163  |
| 风扇   | 利民TL-P9W X1           | 24   |

```text
注意：
铭瑄B760I主板板载网卡为A211，并不适合用来黑苹果，所以加钱更换为博通的最强黑果卡
因为不想买矿卡，所以显卡买了全新的蓝宝石6650XT，与6600XT GPU 相同，相当于6600XT的超频版本，但是核心不同，需要进行仿冒的操作。
```

## 启动盘制作

准备一个大于16G的U盘用于制作启动U盘。

**大致有以下步骤**

* 下载MacOS镜像：[黑果小兵镜像下载地址](https://blog.daliansky.net/)

黑果小兵的懒人镜像很不错，但是有很多分区什么的，这里不太了解。所以我下载的是B站UP主小明同学的镜像，这里我下载的是Ventura版本的。

![image-20230901204014227](https://bestacou-1317041502.cos.ap-guangzhou.myqcloud.com/image-20230901204014227.png)

* 下载U盘刻录工具：[balenaEthcher](https://www.balena.io/etcher)

![image-20230901020407677](https://bestacou-1317041502.cos.ap-guangzhou.myqcloud.com/image-20230901020407677.png)

* 刻录U盘制作启动盘

![image-20230901020421406](https://bestacou-1317041502.cos.ap-guangzhou.myqcloud.com/image-20230901020421406.png)

**检查**

烧录结束之后，不管是显示成功还是失败好像都是可以用的。个人有点强迫症，烧了3次才显示成功，成功之后

重新拔插一下U盘，如果提示需要格式化直接取消就可以了。

Windows环境下使用DG检查一下

![image-20230901204439923](https://bestacou-1317041502.cos.ap-guangzhou.myqcloud.com/image-20230901204439923.png)

![image-20230901204456104](https://bestacou-1317041502.cos.ap-guangzhou.myqcloud.com/image-20230901204456104.png)

虽然这个分区名叫ESP，但是叫什么名字并不要紧，只需要确保分区格式是FAT格式即可。

到这里启动U盘就制作完成了。







## EFI制作

// TODO

## 安装实战

// TODO

## 各种修复

### 三码重注

// TODO

### 显卡仿冒

// TODO

### 关闭MacOS SIP安全保护

// TODO

### 消除跑代码以及OC引导

// TODO

## 性能测试

// TODO































