# 蓝牙协议总结

| profile名称 | profile全称 | 作用 | 举例 |
| :--------: | :--------: | :--  | :----- | 
| OppProfile | Object Push Profie | 文件传输协议：用于蓝牙设备间的文件传输 | 手机间的文件传输 |
| PanProfile | Personal Area Networking Profile |个人局域网协议：(有三个角色NAP,PANU,GN)设备一方开启蓝牙网络共享给其他设备使用 | 手机上的蓝牙共享网络
| PbapServerProfile | Phone Book Access Profile(PSE) | 读取联系人协议:作为server，本设备的联系人可共享给其他设备 |
| PbapClientProfile | Phone Book Access Profile(PCE) | 读取联系人协议:作为client角色，本设备可读取server端的联系人 | 读取联系人列表
| A2dpProfile | Advanced Audio Distribution Profile(SRC:Source) | 高级音频分发协议:作为server提供音频源 | 可以提供音频源的手机
| A2dpProfile | Advanced Audio Distribution Profile(SRC:Source) | 高级音频分发协议:作为server提供音频源 | 可以提供音频源的手机
| A2dpSinkProfile | Advanced Audio Distribution Profile(SINK) | 高级音频分发协议:作为client播放接收到的音频 | 车载蓝牙，蓝牙音响
| HeadsetProfile | Headset Profile | 耳机协议:提供手机音频 | 连接蓝牙耳机
| HfpClientProfile | Hands-Free Profile | 免提设备：播放音频 | 蓝牙耳机
| HidProfile | Human Interface Device | 人机接口设备 | 蓝牙鼠标，蓝牙键盘
| MapProfile | Message Access Profile | 读取短消息协议 | |
| SapProfile | SIM Access Profile | 读取sim卡协议 | |
