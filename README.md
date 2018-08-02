### install kubernetes by ansible
### 环境
1. 阿里云vpc专用网络环境，vps私有ip 192.168.0.0/16
2. linux centos 7.4 发行版,建议使用服务商镜像制作自定义镜像(yum update -y)
3. 仅支持linux 或 mac os 作为执行主机
4. 需修改host文件,填入阿里云各主机外网ip(绑定弹性网卡)

### 配置参考
[k8s](https://jimmysong.io/kubernetes-handbook/)

### Todo
1. flanneld 的 网络类型问题 vxlan -> hostgw
2. k8s 插件 dns,dashboard,heapster,elk 自动安装
3. 优化跟进 k8s 1.11 release
4. 统一master node的config文件
