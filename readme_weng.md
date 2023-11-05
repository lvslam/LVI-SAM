## compile

idea设置
```
-DCATKIN_DEVEL_PREFIX:PATH=/home/weng/DEV/pros/lslams/lvi_ws/devel_lvi -DGTSAM_DIR=/home/weng/DEV/pros/libs/gtsam/gtsam_install/lib/cmake/GTSAM
```

编译脚本
```bash
cd /home/weng/DEV/pros/lslams/lvi_ws
# git clone https://github.com/TixiaoShan/LVI-SAM.git
catkin_make -DGTSAM_DIR=/home/weng/DEV/pros/libs/gtsam/gtsam_install/lib/cmake/GTSAM -DCATKIN_WHITELIST_PACKAGES="lvi_sam"
```