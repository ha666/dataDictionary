# dataDictionary

#### 介绍
生成数据字典

#### 应用场景
根据mysql数据库生成html格式数据字典，目前仅支持macos/linux/windows

#### 使用步骤

##### 运行程序
参数解析  
- "-c" 链接数据库字符串  
- "-t" 输出格式 html\excel\md

windows:
```shell
dataDictionary -c root:1234567890@tcp(127.0.0.1:3306)/ha666db?charset=utf8 -t html
dataDictionary -c root:1234567890@tcp(127.0.0.1:3306)/ha666db?charset=utf8 -t excel
dataDictionary -c root:1234567890@tcp(127.0.0.1:3306)/ha666db?charset=utf8 -t md
```
linux/macos:
```shell
./dataDictionary -c "root:1234567890@tcp(127.0.0.1:3306)/ha666db?charset=utf8" -t html
./dataDictionary -c "root:1234567890@tcp(127.0.0.1:3306)/ha666db?charset=utf8" -t excel
./dataDictionary -c "root:1234567890@tcp(127.0.0.1:3306)/ha666db?charset=utf8" -t md
```
