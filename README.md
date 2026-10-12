# bella-audio-listening

将英语音频生成自带原声的离线 HTML 听读网页。

提供音频后调用：

```text
使用 $bella-audio-listening，把这段音频生成双语听读网页。
```

支持逐句播放、中英对照、语速、循环、生词笔记及备份恢复。转写与翻译由 Agent 完成，页面由脚本生成。

环境：Python、ffmpeg，以及 MLX Whisper 或 faster-whisper；已有带时间的转写结果也可复用。
