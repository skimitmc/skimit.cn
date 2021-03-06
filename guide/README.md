# skimit服务器指南
[返回服务器网站主页](../)  
## 目录
[[toc]]
## 服务器地址
### Java版进入服务器
- 主要地址: `skimit.cn`（浙江电信直连）  
- 备用地址1: `play.skimit.cn`（浙江电信直连）  
- 备用地址2: `play.skimit.cn:1536`（浙江电信直连）  
- 备用地址3: `mc.skimit.cn`（河南电信转发）
  **`skimit.world`已停止使用**  
### 基岩版进入服务器
- 主要地址（浙江电信直连）
  - 地址: `be.skimit.cn`  
  - 端口: `1792`  
- 备用地址（河南电信转发）  
  - 地址: `be2.skimit.cn`  
  - 端口: `17171`  

## 指令
说明: **<>**和**[]**分别指指令中的必须参数和可选参数
#### `/backup start`: 手动备份服务器存档
#### `/ping`: 查看你的延迟
### here mod的功能
- `/here`: 广播你的坐标  
  - 点击蓝色坐标文字可以让你的小地图mod设置高亮（导航点）  
- `/glowing`: 将玩家自己高亮15秒  
#### `/distance`: 计算两个坐标的距离
  - 用法: `/distance from X Y Z to X Y Z`  
  - 输出: Spherical: 空间直线距离（[球面距离](https://baike.baidu.com/item/%E7%90%83%E9%9D%A2%E8%B7%9D%E7%A6%BB)？）  
  - 输出: Cylindrical: 平面直线距离  
  - 输出: Manhattan: [曼哈顿距离](https://baike.baidu.com/item/%E6%9B%BC%E5%93%88%E9%A1%BF%E8%B7%9D%E7%A6%BB)  
### 登录系统
  - `/reg <密码> <重复密码>`或`/register <密码> <重复密码>`: 注册  
  - `/l <你的密码>`或`/login <你的密码>`: 使用已注册的密码登录  
  - `/cpass <当前密码> <新密码>`或`/change <当前密码> <新密码>`: 更改密码  
  - `/unlog`: 退出已登录的账户  
#### `/glist`: 显示服务器所有子服的在线玩家列表
#### `/list`: 显示玩家当前子服的在线玩家列表
#### `/info`: 查看方块或实体的信息
  - 用法: `/info <block> <方块坐标（X Y Z）>`显示当前世界当前维度指定坐标方块的信息  
  - 用法: `/info <entity> <实体名称>`显示当前世界已存在的实体的信息  
#### `/msg <玩家名> <信息>`或`/w <玩家名> <信息>`或`/tell <玩家名> <信息>`: 给指定玩家发送**私聊**消息
### 子服权限系统（仅权限为owner的可用）
  - `role assign 玩家ID admin`: 将玩家加入权限组  
  - `role remove 玩家ID admin`: 将玩家移出权限组  
  - `role list 玩家ID`: 列出玩家所在的权限组  
  - `role reload`: 重载配置文件  
### 待补充 

## 群内机器人的使用
- 发送`#绑定：<你的ID>`: 将你的QQ号绑定游戏ID以实现群聊消息同步到服务器聊天  
- 发送`#在线人数`: 查看服务器的在线人数  
- 待补充  

## 服务器网页卫星地图的查看
- 在[服务器地图导航页](../map/)导航到要浏览的服务器卫星地图  

## 待补充，欢迎提交PR或issue补充

## 联系
[加入QQ群597691030](https://jq.qq.com/?_wv=1027&k=5GAlEKg)
[加QQ2738345462](http://wpa.qq.com/msgrd?v=3&uin=2738345462&site=qq&menu=yes)
