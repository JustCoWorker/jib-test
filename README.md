# jib-test
jib 打包docker 镜像demo

#### 构建镜像并push远程仓库

```shell
mvn compile jib:build
```

#### 把镜像直接构建到本地docker

```shell
mvn compile jib:dockerBuild
```