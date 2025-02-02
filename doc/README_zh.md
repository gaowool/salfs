# 中文文档

请自己分区!!!(不需要挂载)

## 设置环境变量
set_env.sh 设置环境变量并初始化一些文件例如env.sh

env.sh 这是一些环境变量用于source

## 宿主系统检查
check_host.sh

## 工具检查
chech_tools.sh

## 建立文件系统
mk_fs.sh

## 挂载和初始化
mount_lfs.sh
mk_dir.sh

## 软件包
download.sh
ck_pkg.sh

## 添加用户
add_user.sh

## 配置工作环境(lfs_user)
set_env.sh

## 构建 LFS 交叉工具链和临时工具

### 编译交叉工具链
### 交叉编译临时工具
### 进入 Chroot 并构建其他临时工具

## 构建 LFS 系统

### 安装基本系统软件
### 系统配置
### 使 LFS 系统可引导
#### 编译内核
使用默认配置 or 自己配置