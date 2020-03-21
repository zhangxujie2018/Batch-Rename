# Batch-Rename

## 批量修改字幕名（文件名）


**目前可用功能是批量修改字幕文件名，使其与对应视频相互匹配）**

*（在/src/utlis/RenameUtils.java中已经写了许多批量改名的方法，可以自由修改使用)*

**食用方法：**（必须有jre java运行环境 不需要有jdk）程序入口是src下的Main类
1. 确保所有视频在一个文件夹，而且这个文件夹只有这些视频。
2. 确保所有字幕在一个文件夹，而且这个文件夹只有这些字幕。 **注意**：(字幕原文件名需要有顺序，和视频顺序一致) 如：视频（*1.MP4, 2.MP4, 3.MP4, 4.MP4*），则字幕也和视频必须是按顺序一一对应，可以是（*a1.ass, a2.ass, a3.ass, a4.ass*）。 
3. 最好把“字幕文件”备份一份，但实际理论上不会出错。

UI：
![界面ui样例.png](https://s1.ax1x.com/2020/03/20/8cS94H.png)


## LICENSE
[The MIT License (MIT)](https://opensource.org/licenses/MIT)
