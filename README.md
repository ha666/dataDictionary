# dataDictionary

#### 介绍
生成数据字典

#### 应用场景
根据mysql数据库生成html格式数据字典，目前仅支持macos/linux/windows

#### 使用步骤

##### 运行程序
windows:
```shell
dataDictionary -c root:1234567890@tcp(127.0.0.1:3306)/ha666db?charset=utf8
```
linux/macos:
```shell
./dataDictionary -c root:1234567890@tcp(127.0.0.1:3306)/ha666db?charset=utf8
```
