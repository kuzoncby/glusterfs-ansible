# Install GlusterFS by Ansible

Edit [production.ini](./production.ini)

## Test connection

```bash
make test
```

## Install

```bash
make install
```

## Mount

```bash
mount -t glusterfs host-1.cluster.local:/vol_disperse /mnt/
```

## License

MIT
