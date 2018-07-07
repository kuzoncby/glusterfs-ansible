# 使用 Ansible 安装 GlusterFS

编辑[production.ini](./production.ini)文件，填写个角色机器。

## 测试连接状态

```bash
make test
```

## 安装

```bash
make install
```

## 挂载

```bash
mount -t glusterfs host-1.cluster.local:/vol_disperse /mnt/
```

