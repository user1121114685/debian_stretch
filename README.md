# debian_stretch
## debian stretch 源一键脚本
**食用方法**

## 清华源 HTTPS##

`apt-get install apt-transport-https`

`wget -O /etc/apt/sources.list https://raw.githubusercontent.com/user1121114685/debian_stretch/master/qinghua-sources.list && chmod 777 /etc/apt/sources.list`


`apt-get update && apt-get upgrade`

## 163源 HTTP##

`wget -O /etc/apt/sources.list https://raw.githubusercontent.com/user1121114685/debian_stretch/master/163sources.list && chmod 777 /etc/apt/sources.list`


`apt-get update && apt-get upgrade`

## 阿里源 HTTP##

`wget -O /etc/apt/sources.list https://raw.githubusercontent.com/user1121114685/debian_stretch/master/ali-sources.list && chmod 777 /etc/apt/sources.list`


`apt-get update && apt-get upgrade`

## 上海交大 HTTPS##

`apt-get install apt-transport-https`

`wget -O /etc/apt/sources.list https://raw.githubusercontent.com/user1121114685/debian_stretch/master/jiaoda-sources.list && chmod 777 /etc/apt/sources.list`


`apt-get update && apt-get upgrade`

## 华为 HTTPS##

`apt-get install apt-transport-https`

`wget -O /etc/apt/sources.list https://raw.githubusercontent.com/user1121114685/debian_stretch/master/huawei-sources.list && chmod 777 /etc/apt/sources.list`


`apt-get update && apt-get upgrade`
