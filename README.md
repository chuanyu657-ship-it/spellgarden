# 结界之庭 · Spellgarden

一个日式魔法学院题材的 Windows 可玩原型：学习魔法、打怪、认识导师、培养好感、发展天赋与派系，并在庭院建家。

![雾灯之森 · 实机画面](images/mistwood.png)

## 下载与启动

[下载 Windows 游戏包](https://github.com/chuanyu657-ship-it/spellgarden/releases/download/v0.4.1/Spellgarden-v041-Windows.zip) · [查看最新发行版](https://github.com/chuanyu657-ship-it/spellgarden/releases/latest)

下载 `Spellgarden-v041-Windows.zip`，解压整个文件夹，再运行 `Spellgarden.exe`。请保留同目录的 `.pck` 和 `.dat` 文件。

游戏不需要安装 Godot 或 Blender。默认使用 Vulkan；如画面无法正常显示，可运行 `Start-Compatible.cmd`。

## 和朋友联机

1. 所有人使用相同版本，最多 4 人。
2. 在不同网络时，安装 [Radmin VPN](https://www.radmin-vpn.com/)，由一人创建网络，其余人加入同一网络。已有同一局域网时可以直接连接。
3. 房主进游戏按 **M**，创建庭园，选中 **Radmin VPN** 地址并复制邀请。
4. 朋友在游戏按 **M**，粘贴邀请并加入。
5. 若连接被 Windows 防火墙阻止，按压缩包内的《联机快速开始》启用仅供本游戏使用的 UDP 24567 规则。

邀请地址只提供连接目标，不会自动创建 VPN 网络。房主必须保持游戏和 VPN 在线；房主退出后房间结束。个人成长各自保存，房间建筑由房主保存。

## 当前内容

- 第一人称双手与法杖；V 可切换第三人称。
- 五种魔法、脚下法阵与裂界大招，天赋树和派系。
- NPC 任务感叹号、地面引路与一段可完成的学院序章。
- 学院、雾灯之森、星眠湖畔三个可通过传送阵往返的区域。
- 怪物、灵晶采集、种植和室外家园建造。
- 最多四人 ENet 联机，跨区域同步位置、施法、战斗与建筑。

## 操作

WASD 移动，Shift 奔跑，Space 跳跃；鼠标环顾与瞄准；按住 Alt 使用光标。

E 互动 / 传送；1–4 普通魔法；Q 大招；V 切视角；G 引路；J 任务；T 天赋；B 建家；M 联机；Esc 菜单。

## 范围

这是实验性可玩原型。没有公网匹配、内置中继或常驻专用服务器；异地连接依赖你们的虚拟局域网或自行配置的可达地址。三个区域不是无缝开放世界。任务进度、好感与材料是个人数据。

发布包附带运行库的第三方许可。Witchbrook 仅为氛围参考，未使用其游戏素材。
