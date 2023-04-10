## installer

Install Kubernetes and containerized software with a simple and comprehensible way.

** Note **
- work well on CentOS/RHEL 7.x/8.x and Ubuntu 18.x/20.x.
- support amd64 (such as intel, amd) and arm64 (such as phytium, kunpeng). 
- for Kubernetes >= 1.24

## Supported

- ShanDong Provincial Key Research and Development Program, China (2021CXGC010101)

## Authors

- wuheng@iscsa.ac.cn
- wuyuewen@iscas.ac.cn
- zhujianxing21@otcaix.iscas.ac.cn
- guohao21@otcaix.iscas.ac.cn

## Quick start

```
curl --url https://raw.githubusercontent.com/WANNA959/installer/master/kubeinst --output /usr/bin/kubeinst
chmod 777 /usr/bin/kubeinst
```

### Kubernetes container

```
kubeinst init-env ctr
kubeinst init-compute ctr
```

