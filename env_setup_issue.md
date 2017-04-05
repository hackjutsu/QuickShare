# 环境配置中常见的问题

## 正常步骤
```
git clone https://github.com/bittiger-java/vagrant-workstation.git
cd vagrant-workstation
vagrant up
```
结束以后
```
vagrant reload
```
一切顺利的话，我们会看到下面的登录界面
![vagrant_login](https://cloud.githubusercontent.com/assets/7756581/24634889/170865fe-1885-11e7-80de-47e9471adae9.png)

## 常见问题
### 报错姿势
#### 不巧当的姿势 
- “跑不了”、“不能用”、“不行”、“还是不行”、“跑了很多遍还是不行”……
- 模糊的电脑屏幕照片……

#### 建议姿势 
- 操作系统：Windows还是macOS
- 系统版本
- Virtual Box 和 Vagrant 版本
- 执行到哪一步？
  - expected behaviors
  - actual behaviors
  - logs (screenshots, not photos)

#### 善用Google + StackOverflow + GitHub issue
- [CS504专用GitHub Issue](https://github.com/BitTigerInst/BitTiger-CS504-FAQ/issues)

### 从Virtual Box中打开虚拟机出错？
- 不需要从Virtual Box界面里打开虚拟机

### VM not created
- 删除Virtual Box中已有的Image，或者重新安装Virtual Box

### 图形界面不出来
- https://github.com/BitTigerInst/BitTiger-CS504-FAQ/issues/1

### cannot access '/root/Development/'
-  `vagrant reload`

### 在哪里安装IntelliJ？
- 虚拟机中

### [Windows] requested address is not valid
- https://github.com/BitTigerInst/BitTiger-CS504-FAQ/issues/2

### [Windows] Which interface should the network bridge to?
- 如果没有出现选项，安装最新版Virtual Box（v5.1）
