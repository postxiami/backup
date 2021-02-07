# 备份虾米资源
![](https://img.shields.io/github/v/release/xiami2021/backup.svg)
![](https://img.shields.io/github/last-commit/xiami2021/backup)
![](https://img.shields.io/github/issues/xiami2021/backup)

备份虾米收藏歌曲，导出歌曲风格标签

***目前还能正常工作！***

## 功能
- [x] 根据虾米ID一键备份收藏数据，支持专辑、歌曲、艺人、歌单(自建/收藏) 导出为JSON
- [x] 批量备份音频资源
- [x] 收藏歌曲风格标签的可视化
- [x] 备份数据查看可排序（如发现自己播放量最高的原创歌单
### 02-04
- [x] 已备份的音源不重复备份
- [x] 提供最大质量音源可选项，方便有足够空间的朋友
- [x] 支持把歌单的歌曲，添加到备份列队？
- [ ] 更有意思的数据分析？

## 标签云
![tag](tag.png)  

## 下载
用迅雷\离线下载可能会快一点
- [Windows](https://github.91chifun.workers.dev//https://github.com/xiami2021/backup/releases/download/0.0.7/Setup.0.0.7.exe)  
- [Mac](https://github.91chifun.workers.dev//https://github.com/xiami2021/backup/releases/download/0.0.7/0.0.7.dmg)



## 如何使用

需要关闭防火墙

### 本地解析
增加本地Host解析 （备份歌单需要该步骤，如不需要可忽略）
#### Windows
`C:\Windows\System32\drivers\etc\hosts`
#### Mac
`/etc/hosts`

``` 
203.119.244.126 emumo.xiami.com
203.119.212.1   emumo.xiami.com
203.119.211.255 emumo.xiami.com

182.118.14.185  music.xiami.com
119.36.225.179  music.xiami.com
117.24.3.176    music.xiami.com
117.24.3.175    music.xiami.com
1.81.1.144      music.xiami.com

# 02-07 新增
203.119.169.83  h5api.m.xiami.com
203.119.169.158 h5api.m.xiami.com
203.119.169.246 h5api.m.xiami.com
``` 

### 数据备份

> 输入你的虾米数字ID 
>
> https://www.xiami.com/user/xxxx
>
> xxxx链接尾部的数字 就是你的虾米ID  
> 等待备份完毕

### 音源备份
- 点击【批量备份收藏】
- 备份文件夹用英文文件名 如: F:\allsong

### 常见问题
#### no such file or directroy
填错备份文件夹的路径了，需要重启应用、填对，再备份

