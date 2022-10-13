# qiime2bit
Qiime2 build files

# Assumptions
In order to build this Qiime2 custom build, the base image must be build or caches first:
```
docker build \
-t quay.io/qiime2/core:$(QIIME2_RELEASE) \
-t quay.io/qiime2/core:latest \
--build-arg QIIME2_RELEASE=$(QIIME2_RELEASE) docker
```
