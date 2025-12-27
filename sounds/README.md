# 音频文件说明

## 请将你的音频文件放在这个文件夹中

### 需要的音频文件：
- ak.mp3
- ap.mp3  
- at.mp3
- ah.mp3

### 音频格式要求：
- 格式：.mp3 或 .wav
- 采样率：建议 44.1kHz
- 比特率：建议 128kbps 或以上
- 声道：单声道或立体声均可

### 示例文件：
`example.mp3` 是一个示例音频文件，你可以先用它测试程序是否正常运行。

测试时，记得在 index.html 中修改文件名：
```javascript
var stimuli = [
    { audio: 'sounds/example.mp3', correct_answer: 0 },
];
```

### 上传到GitHub：
音频文件会和其他文件一起上传到GitHub。GitHub对单个文件的大小限制是100MB，一般的音频文件都不会超过这个限制。
