# 制作 Webduino 大陆版任务书

|   修订时间    |                     修订内容                      |
| :-----------: | :-----------------------------------------------: |
| 2019年7月10日 |                  初稿，基本内容                   |
| 2019年7月11日 | 相关材料已经收齐，添加 `任务小组`、`任务具体流程` |
| 2019年7月12日 |            添加物料清单、完善具体流程、多人编辑工具             |

## 任务内容

1. 核对板子通用介绍部分的文档，共两篇。
2. 将机翻过的简体 markdown 文档仔细校对和审核，确保大陆版能正常使用，包括图片简体内容等。
3. 使用 `WebBi Setup_1.2.1` 的离线版软件进行各项功能测试，将存在的问题实时反馈给台湾开发团队。
4. 软件使用 Webduino 固件的各项测试和包装发布，目前暂定为重新打包 20190604 的固件版本。
5. 制作修正硬件不同版本的文档以及表格数据，如 1.2 、 1.4 的硬件描述，目前还未仔细审核硬件的各项介绍。
6. 根据软件使用情况编排内容，进行视频的设计和拍摄。

如有遗漏可以补充。

额外任务：*替换大陆不可用的同类积木，如语音、微信、机器人（包含各类查询服务）的积木，目前微信还在开发中。*

## 准备工作

1. 准备烧录工具、安装程序、文档链接，确保每个人都可以开箱使用，已存放U盘。
2. 相关 markdown 文档源码一份，并基于此开始整体的修正工作。
3. 一台全新的 Windows7  32 位家庭简易版 做标准测试机，再加一台 Windows 10 64 位系统。
4. 确保每个文档都有标注这类内容：软件版本、固件版本、文档版本。
5. 准备拍摄视频的器材，较为专业和正式一些。
6. 离线软件准备一个 Github 仓库（https://github.com/junhuanchen/test_repository），用于同步软件体验组的修改记录。
7. 目前文档移交到 https://hackmd-ce.herokuapp.com/ 网站进行多人协助编辑，仓库只做备份。

如有遗漏可以补充。

## 物料清单

| 物料清单                               | 数量 | 备注                     |
| -------------------------------------- | ---- | ------------------------ |
| 硬件驱动、硬件固件、烧录软件、测试软件 | *1   | Github 仓库全打包完毕    |
| 教育版 & 开发版 文档                   | *40  | markdown 文档            |
| 人                                     | *7   |                          |
| 同步文件仓库（或可选其他工具           | *1   | 备选 gitbook 但登录不上  |
| Windows 测试环境                       | *2   | win7 32 位 & win10 64 位 |
| 补光灯、录音卡                         | *2   | 找一找                   |
| 桌子与凳子                             |      |                          |

## 人员情况

TIM 老师、陈俊欢、陈渊、刘煜标、王皓、瞿少敏、光发。

### 任务小组（人员可能混合，主要是划分职责）

文档修订组

- 职责范围：翻译文档，修订文档，统计文档。

视频拍摄组

- 职责范围：准备素材，制作剧本。

软件体验组

- 职责范围：根据文档配合翻译改软，阅读以及使用文档，配合测试软硬件。

## 任务分配（初步

1. 修正预处理的简体文档分软件和硬件使用基础两个阶段，总量为 40 份，包含教育版和~~开发版~~的文档。
2. 针对文档修正后的软件测试体验工作，确保小白在使用过程中没有任何问题和阻碍。
3. 针对通常的软件使用体验进行某类视频拍摄的文案和脚本设计做编排。

如有遗漏可以补充。

### 任务具体流程（20190716起）

分发所有相关的软件、工具、资料、硬件等基础设施，确保有需要的人都有一个基本的套件。（准备工作）

#### 文档组

1. 先是修订文档目录（ 1 - 2 天）

   - 所有文档的总体情况，如下截图。

   - ![1562814844035](images\1562814844035.png)
   - 对以上目录提出建议与修订后，开始划分文档修订人员工作范围（认识、基础、应用等）分类内容。

2. 再根据修订的文档后划分工作量（40 天 / 修订文档人员）

   - 对具体文档的内容进行整理，例如某类文档的内部细节。

   -  ![1562901005633](images\1562901005633.png)

   - 文档要求任何一人，对于期望修订的前一天（以20190715 开始着手准备）对某篇内容进行 **原版打印** 转交给各位需要查阅的人，并在文档开头标注：使用硬件版本、固件版本、软件版本、系统版本、修订时间。

#### 软件组

1. 测评体验软件

   - 获取 https://github.com/junhuanchen/test_repository 仓库直接运行`\WebBit 1.21\WebBit.exe` 即可启动软件。

   - ![1562901379047](images\1562901379047.png)

2. 修改软件内容

   - 在仓库建议使用 VS CODE 查找软件内部文字变量直接对内部进行内容修正与查看效果
   - 使用 Git-hub 仓库能确保所有人在使用软件的时候都能同步到最新的一份，届时修正完毕后也将此代码交给台湾对方比对仓库并合并。

   - 结合文档去体验和使用软硬件，使用过程中可以将反馈和建议提供给文档组，务必确保任何人使用都不会出现困难和错误。

#### 视频组

1. 准备材料
   - 配合其他两个小组准备素材、内容、相关软硬件器件。（文档工作前一周进行协助工作
2. 制作视频
   - 配合文档与软件，策划内容，具体如何制作（文档工作开始一周后再议。
3. 设计内容
   - 结合用户群体考虑，综合考虑宣传、文档、使用、以及缺失内容的补充。



#### 开发 & 维修组（隐藏



如果途中遇到什么软件、硬件工具缺失，务必加急处理修复。



注意，各个小组需要什么帮助也请提出。



## 任务时间

20190716 起预计一个月后，即为 20190816 左右结束。

## 交付内容

- 在大陆可用的简体文档，文档链接。
- 大陆版软件的简体变量，合并打包。
- 在大陆版可用的相同功能拓展积木。
- 大陆版软件文档与对应的视频教程。