# 2025年全国大学生OS比赛--内核赛道--线上测例

## 现场赛题目(预先公布)
能正确运行如下程序，运行环境如下：
- QEMU RISC-V64 with virtio-net/virtio-block
- QEMU LoongArch64 with virtio-net/virtio-block



1. 支持运行git工具在本地文件系统和网络中的基本操作
   
  ```bash
  # basic
  git help
  # FS related
  git init
  cat >README.md
  git commit -m"add README.md"
  git log
  # NET related
  git clone ...
  git pull ...
  ```

2. 测试脚本针对建立在127.0.0.1的git服务，进行拉取操作


