# Skill

#### Git
- git 基本命令
- github fork repo
- github PR 相关操作
- github issue 相关操作
- 搭建 git
  
#### Docker
- 安装 Docker
- Docker 基本命令
- 使用 Dockerfile 构建一个 docker 镜像
- 使用具有 multi-stage 特性的 Dockerfile 构建一个 docker 镜像
- 使用 docker-compose 运行一个容器化服务，并使用主机网络
- 通过 veth-paris 和网络名称空间完成两个容器之间的网络通信

#### Kubernetes

- Kubernetes 基本概念
- Kubectl 基本命令
- 使用 RKE 部署一个 Kubernetes 集群(1个主节点和2个节点)
- 在 Kubernetes 中运行 WordPress 应用程序，并使用 ingress 公开服务
- 在 Kubernetes 集群中添加一个动态 NFS 供应器，使用 NFS 存储运行一个应用程序

#### Rancher
- Rancher 基本功能使用
- Rancher 单节点部署
- Rancher HA部署
- Rancher 离线部署
- 托管集群
- 导入集群

#### Linux 
- linux 基本命令使用

#### Pytest
- python 基本语法
- 搭建 pytest 环境
- 本地运行测试 case
- 编写 case

#### Tools
- Jmeter 使用
- Postman 使用
- Charles 使用
- Jenkins 使用

# Plan
#### 1月
学习内容 | 学习计划 | 任务
-- | -- | --
Git | git 基本命令 </br> github fork repo </br> github PR 相关操作 </br> github issue 相关操作 | 1. 完成 git 提交周报 </br>2. 完成 issue 创建/comment/关闭等操作
Docker | 安装 Docker </br> Docker 基本命令 | 1. 构建 Docker 镜像 </br> 2. 运行/停止/重启/删除 Docker 容器 </br> 3. 查看容器日志 </br> 4. Docker 容器执行命令
Kubernetes | Kubernetes 基本概念 </br> Kubectl 基本命令 </br> RKE 部署 Kubernetes 集群| 1. 使用 RKE 部署一个 Kubernetes 集群(1个主节点和2个节点) </br> 2. 部署 pod </br> 3. 部署 service
Rancher | Rancher 基本功能使用 </br> 托管集群 </br> 导入集群 </br> Rancher 单节点部署| 1. 搭建一个单节点Rancher环境 </br> 2. 托管一个集群 </br> 3. 导入一个集群 </br> 4. project/ns相关操作 </br> 5. 工作负载/service/ingress/pod相关操作

#### 3月
学习内容 | 学习计划 | 任务
-- | -- | --
Git | 搭建 git | 1. Linux 环境搭建 git 环境并创建 project
Docker | Docker 容器 | 1. 使用 docker-compose 运行一个容器化服务，并使用主机网络 </br> 2. 通过 veth-paris 和网络名称空间完成两个容器之间的网络通信
Rancher | Rancher HA 部署 </br> Rancher 离线部署 </br> Rancher 功能使用| 1. 搭建一个 Rancher HA 环境 </br> 2. 搭建一个 Rancher 离线环境 </br> 3. 部署监控/日志/全局监控
Pytest | 搭建 pytest 环境 </br> 本地运行测试 case | 1. 本地运行测试 case

#### 5月
学习内容 | 学习计划 | 任务
-- | -- | --
Kubernetes | 在 Kubernetes 中运行 WordPress 应用程序，并使用 ingress 公开服务 | 1. 在 Kubernetes 中运行 WordPress 应用程序，并使用 ingress 公开服务 </br> 2. 在 Kubernetes 集群中添加一个动态 NFS 供应器，使用 NFS 存储运行一个应用程序
Rancher | Rancher 功能使用 | 1. 搭建 Harbor/审计日志/macvlan/GPU/F5 环境
Pytest | 编写 Test case </br> Jenkins 使用 | 1. 编写 Test Case </br> 2. Jenkins 创建/运行 Pipeline
