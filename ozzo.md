# ozzo记录
-------------------------------------

# 安装与使用

  > 使用Glide进行依赖包管理

```
go get github.com/qiangxue/golang-restful-starter-kit #安装项目
go get -u github.com/Masterminds/glide #依赖管理工具
//cd $GOPATH/qiangxue/golang-restful-starter-kit #这个路径有问题，需要修改 tag?????
cd $GOPATH/src/github.com/qiangxue/golang-restful-starter-kit
glide up -u -s #安装依赖包
//配置 config/app.yaml
//postgres://<username>:<password>@<server-address>:<server-port>/<db-name>
go run server.go #运行起来
```


# 验证，记录，修改

### 数据库两种格式

testdata/sql => testdata/postgre.sql
add testdata/mysql.sql

### 文档部分
cd $GOPATH/qiangxue/golang-restful-starter-kit #这个路径有问题，需要修改 tag?

cd $GOPATH/src/github.com/qiangxue/golang-restful-starter-kit
