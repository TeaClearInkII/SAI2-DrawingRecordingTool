# SAI2-DrawingRecordingTool-绘画录制工具
支持任意SAI2版本以及任意绘画软件；Supports any version of SAI2 and any painting software

Bilibili视频Video：[【推荐】SAI2绘画录制工具](https://www.bilibili.com/video/BV16J576WE8t)
# 作者：[茶清墨刂](https://space.bilibili.com/388428308) & DeepSeek & Trae

[GitHub资源页下载&更新说明](https://github.com/TeaClearInkII/SAI2-DrawingRecordingTool/releases)

[123云盘](https://1818650178.share.123865.com/123pan/gjihjv-NfVad)

[夸克云盘](https://pan.quark.cn/s/741112689264)

[GitHub仓库](https://github.com/TeaClearInkII/SAI2-DrawingRecordingTool)

[反馈](https://github.com/TeaClearInkII/SAI2-DrawingRecordingTool/issues)

# 捐赠&支持-Donations&Support
1. [哔哩哔哩⚡️充电](https://space.bilibili.com/388428308)

2. 软件内附二维码
<img src="./茶清墨刂微信收款码.png" alt="茶清墨刂微信收款码" style="width: 50%; height: auto;">
<img src="./茶清墨刂支付宝收款码.jpg" alt="茶清墨刂支付宝收款码" style="width: 50%; height: auto;">

# 界面展示
![主界面展示](./主界面展示.png)
![录制历史与打卡日历界面展示](./录制历史与打卡日历界面展示.png)

# 使用说明

！！！请不要将录制窗口最小化！！！

1. "其它"→"设置"→"首选项"→"导航器"设置最大分辨率4096、隐藏参考线

2. 在SAI2界面上找到"窗口"→"分离操作面板"→"分离导航器"

3.将导航器拉伸到画布合适大小（因SAI2本身问题，请使用本软件的"还原功能"在下次启动自动恢复窗口）

4.软件中选中导航器并裁剪合适大小

5.将导航器放到边边角角上不影响观看画面

推荐使用 PotPlayer 视频播放器

【功能介绍】
- 窗口选择：支持选择主窗口和子窗口（导航器）进行录制
- 录制控制：开始录制 / 停止录制
- 区域裁剪：支持角放大镜定位、键盘方向键微调裁剪区域
- 视频合成：支持自定义FPS和实时时长预览，支持多种编码器
- 历史管理：录制历史窗口，支持日历视图、统计汇总、搜索筛选、排序
- 分辨率缩放：原始分辨率 / 百分比缩放 / 固定宽度输出
- 配置记忆：自动记住窗口选择和裁剪配置

【录制特点】
- 智能去重：基于感知哈希算法，只保存画面变化的帧
- 操作触发：检测鼠标按键抬起时自动截图，精准捕捉绘画动作
- 双时统计：分别统计实际绘画时间和总录制时间
- 高效存储：无冗余帧，文件体积小
- 恢复录制：可在已有录制后继续追加新帧

【合成视频编码器】
- MP4V(.mp4) FFmpeg★：压缩率最高，兼容性最好
- XVID(.avi) ★推荐：兼容性极佳，系统播放器直接播放
- MJPG(.avi)：高兼容性，画质好，文件较大
- DIB(.avi) 无损：未压缩原始视频，100%兼容，文件很大
- DIVX(.avi)：兼容较老设备

【合成视频参数】
- 可自定义每秒帧数（FPS），实时显示预计视频时长
- 无需记住配置，每次合成单独设置

【历史记录界面功能】
- 日历视图：按月/年查看录制记录
- 统计汇总：显示总录制次数、总帧数、总大小、累计时长
- 搜索筛选：按名称搜索、按日期筛选
- 排序功能：支持按日期、大小、帧数、时长排序
- 批量操作：单个记录的打开、详情查看、视频合成

【保存位置】
- 保存路径可自定义，文件夹名可自定义
- 工具会自动记住上次使用的路径
- 录制信息保存为 recording_info.json

【运行环境】
- Windows 7 或更高版本
- 无需安装 Python 或任何依赖（已打包为单文件）

【第三方开源组件许可证】
本软件使用了以下开源组件：
- FFmpeg：LGPL 2.1+ 开源许可证
  官网：https://ffmpeg.org/
  本软件内置的 FFmpeg 用于视频编码功能。
  根据 LGPL 许可证要求，FFmpeg 的源代码可在上述官网获取。
  本软件用户有权在使用本软件的同时：
  · 获得 FFmpeg 的源代码
  · 修改 FFmpeg 以满足个性化需求
  · 重发布 FFmpeg（需遵循 LGPL 条款）
  LGPL 详情请参阅：https://ffmpeg.cpp.org.cn/legal.html
