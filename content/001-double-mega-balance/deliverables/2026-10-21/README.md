# 最终交付下载

- [26张完整HTML审阅稿](complete-review.html)：浅色黑金科技风，索财灵标识；R11完整配置占主区，花叶蒂立绘已按永恒之花/Mega形态修正。下载后在浏览器打开。
- [完整画面包](complete-review.zip)：含HTML、26张PNG预览、素材与口播对照。
- [估算SRT字幕](narration-estimated.srt)：121条，预计00:09:48,990（v3，每句间再紧缩0.2秒）；25段口播原文未改。
- [段落时间索引](narration-timing.md)
- [字幕时间轴数据](narration-timing.json)

GitHub文件页可使用Download raw file下载；ZIP和HTML建议下载到本地打开。

SRT为配音前估算，采用约300朗读单位/分钟与短停顿；同段首尾相接，段间0.15秒、章间0.3秒；实际配音后需重对齐。画面为静态关键帧，尚无视频或配音时间轴。R06主题替换后旧口播绑定仍需在音画对齐时调整。图片权利与来源说明见审阅包。

- [连续配音文本](narration-continuous.txt)
- [字幕时间修订对照](subtitle-timing-review-v2.html)

旧SRT版本保留于history/srt-v1。实际音频若有软件自动静音，需调整合成器设置或音频本身。

## 连续配音成品

已将原口播合并为单段连续输入，生成中文中低音男声配音，实际时长7分42.9秒。

- [下载完整MP3](narration-full-male.mp3)
- [下载单段正文](narration-single-paragraph.txt)
- [下载配音包](narration-full-package.zip)
- [生成说明](voiceover-readme.md)

旧SRT为估算，与这次合成配音的实际时间不一致；不要直接当作精确对齐字幕。

## 当前采用：SRT v3

用户要求回到SRT调整。前120条各减少0.2秒，后续同步前移，总时长9分48.990秒；内容及分句不变。此前合成男声保留历史，不作为当前字幕的音频依据。旧v2保存在history/srt-v2，变更见[时间修订对照](subtitle-timing-review-v3.html)。

## 无声视频准备：时间对照表待确认

已按用户同意完成第一步：字幕v3与26张HTML的时间对照表，分28段播放，R12/R21前置复用。总时长9分48.990秒，原HTML和SRT未修改。

- [查看时间对照表](timeline-map.md)
- [下载HTML审阅表](timeline-review.html)

尚未安装HyperFrames、转换渲染工程或开始渲染。需用户确认后才进入下一步。

## HyperFrames环境安装完成

[安装与验证报告](hyperframes-environment/安装与环境验证.md)：HyperFrames0.8.183、浏览器、中文字体、FFmpeg/FFprobe与H.264必需项验证通过。仅可选音频功能未接入。本步未转换HTML或渲染视频。下一步需单独批准。
