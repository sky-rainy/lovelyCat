# LovelyCat
###  创建个Config.ini,内容里边填写以下内容 
   
```
[BASIC]
appkey = ecaf7941150242ec8cb292c5065d7db7
jd_lianmeng_id = 联盟ID
positionId = 推广位ID
[fromGroup]
groupid = 
[toGroup]
groupid = 
```
---
### build
```
# build window系统 
 
  CGO_ENABLED=0 GOOS=windows GOARCH=amd64 go build main.go

# build Mac系统

  CGO_ENABLED="1"  GOOS="darwin"  GOARCH="amd64" go build main.go

# build linux

  CGO_ENABLED=0 GOOS=linux GOARCH=amd64 go build main.go

```
