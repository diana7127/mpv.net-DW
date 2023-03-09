# mpv.net-DW
mpv.net_CM的💗DW版本💗，定制了播放界面、右键菜单、缩略图、视频滤镜和着色器

# 简介
🔳mpv.net-DW：mpv.net_CM的个人定制版

🔲mpv.net_CM：mpv.net的中文分支模组

🔲mpv.net：基于mpv开源播放器的Windows媒体播放器

# DW版本特点
基于上游，做出以下个人定制款  

☑️修改播放界面为ModernX（cyl0/ModernX）

☑️集成缩略图引擎thumbfast（po5/thumbfast）

☑️集成旧版懒人包里的SVP补帧插件（hooke007/MPV_lazy）

☑️修改右键菜单   
- 修改部分翻译（参考potplayer）    
- 修改排列顺序    
- 修改预设组的vs滤镜和着色器方案，兼容更多显卡 
		
☑️修改部分mpv设置   
- 默认硬件解码为auto-copy  
- 默认OSD显示为建议方案  
- 默认音量为100  
- 默认开启interpolation  
- 默认开启icc色彩管理  
- 默认模糊识别音频与字幕  
- 不显示mpv.net的logo和特别版logo（否则会闪现原始logo）  
		
☑️修改部分快捷键设置（参考potplayer，用习惯了）  
- 文件详细信息 — TAB  
- 打开字幕 — l  

☑️自解压安装包封装

☑️一些其他细节

# 上游版本特点
引用自hooke007/mpv.net_CM

🔘mpv.net_CM：

- 界面汉化   
- 编辑器选项修改   
- 菜单条目+初始快捷键修改   
- 集成Python+VapourSynth便携式组件   
- 预设脚本与着色器   
- 操作习惯移植自mpv-lazy   
- 有更友好的界面操作性

🔘mpv.net：

- 几乎所有mpv的功能都可用，除去一些窗口行为  
- 兼容几乎所有mpv脚本/着色器，除去部分具有特定依赖的项目  
- 单实例/多实例切换
- 支持基础操作的播放列表、音轨字幕轨列表面板   
- 图形化的设置修改与快捷键编辑器  
- 可自定义的右键菜单  
- 音量、窗口尺寸的退出时记忆 

# 预览
- 播放预览  
![预览图01](https://user-images.githubusercontent.com/125502871/220343125-74366dd1-af9e-41a3-81e4-f1f06328a881.jpg)

- 右键菜单  
![预览图02](https://user-images.githubusercontent.com/125502871/221334160-ce3310fa-b8bb-4258-a76c-992cd1467f39.jpg)
![预览图03](https://user-images.githubusercontent.com/125502871/221334168-57b9a765-2a77-4be5-ac54-e0f5abe7b82c.jpg)
![预览图04](https://user-images.githubusercontent.com/125502871/222751934-2ffc0619-381e-454c-93c7-82fd8b005300.jpg)

- 设置界面  
![预览图05](https://user-images.githubusercontent.com/125502871/220125827-6a33ee6d-14a9-40fa-ae0c-733f6760f7b4.jpg)
![预览图06](https://user-images.githubusercontent.com/125502871/220144657-50817726-37f3-41c5-87be-9e50ca5a4cca.jpg)

# 更新
- **libmpv-2-x86_64** [<2023.02.12>](https://sourceforge.net/projects/mpv-player-windows/files/libmpv)
- **MediaInfo** [<v22.12>](https://mediaarea.net/en/MediaInfo/Download/Windows)
- **Python-embed-amd64** [<3.10.9>](https://www.python.org/downloads)
- **VapourSynth-portable** [<git-R_61>](https://github.com/vapoursynth/vapoursynth/releases)
- **yt-dlp** [<git-2023.01.06>](https://github.com/yt-dlp/yt-dlp/releases)
- **ModernX** [<git-0.6.0>](https://github.com/cyl0/ModernX/releases)
- **Thumbfast** [<git-2022.11.16>](https://github.com/po5/thumbfast)

# 安装
- 安装 .NET framework 4.8 运行库
- 下载并安装 mpv.net-DW
- 运行 mpvnet.exe

# 下载
见网页端右侧Releases或移动端下方Releases

# 鸣谢
感谢hooke007编写的mpv.net_CM，和各项说明；感谢cyl0编写的ModernX osc；感谢po5编写的thumbfast；感谢tsl0922编写的ImPlay，使thumbfast可以在mpvnet上使用
