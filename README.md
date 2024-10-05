# spring-evol-devops

devops脚本包含Dockerfile、jenkins的Pipeline、k8s的yaml文件

## 版本

| 版本                | 部署服务器              | 说明                    |
|-------------------|--------------------|-----------------------|
| v3                | K8S / 192.168.2.90 | springboot 3.x 、JDK17 |

## clone

```
git clone http://192.168.2.40:9080/kubernetes-group/spring-evol-devops.git
```
```
git clone git@192.168.2.40:9022:kubernetes-group/spring-evol-devops.git
```
#


## 配置镜像仓库

往gitlab推送时，自动把更新push到github

菜单：gitlab / 某个项目 / 设置 / 仓库 /镜像仓库

镜像仓库配置：

| 配置项 | 部署服务器                                                | 
|---|------------------------------------------------------|
| Git仓库URL  | https://username@github.com/itemname/projectname.git |
| 镜像方向  | 推送                                                   |
| 验证方式  | 密码                                                   |
| 密码  | github中个人设置中配置的Personal access tokens                |
