由于rime+万象输入 初次安装有点门槛,这里整了一个初始化好的版本.只要把本仓库下载下来放到rime的用户目录就行.

方便的话支持一下万象的原作者: https://github.com/amzxyz/rime_wanxiang

用户目录:
 - macos: /Users/~/Library/Rime/
 - windows: C:\Users\%userprofile%\AppData\Roaming\Rime

ai语法模型的文件需要自行下载(因为文件太大,github不让在仓库放).下载完了把文件也放到rime的用户目录,再重新部署一下rime.

ai语法模型下载地址自行在万象仓库的releases里找一下: https://github.com/amzxyz/rime_wanxiang/releases


初始化的点:
- 自然码双拼+间接辅助码
- 候选词横向展示
- 去掉针对部分app默认英文的设置
- 默认中文
- 默认英文标点
- 按CapsLock切换中英文
- 按shift无反应
- 去掉切换中英文时的提示框

已测试可用的环境: 
- macos15.2
- windows11