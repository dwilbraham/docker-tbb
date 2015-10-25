# [docker-tbb](https://github.com/dwilbraham/docker-tbb)

A Docker container with the latest stable  [GNU Compiler Collection](https://hub.docker.com/_/gcc/ "Docker Hub GCC") and [Intel Thread Building Blocks](https://www.threadingbuildingblocks.org/ "TBB") development environment.

Quick Start:

```bash
docker run -it dwilbraham/tbb
```

To run one of the TBB code examples try:

```bash
cd ${TBB_INSTALL_DIR}/tbb${TBB_VERSION}oss/examples/GettingStarted/sub_string_finder
make
```

The Dockerfile is available on [GitHub](https://github.com/dwilbraham/docker-tbb) and the pre-built container from [Docker Hub](https://hub.docker.com/r/dwilbraham/tbb/).

> Written with [StackEdit](https://stackedit.io/).