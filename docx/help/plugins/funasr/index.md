# FunASR 使用帮助
- [FunASR](https://github.com/modelscope/FunASR) AI语音识别、情感识别、时间轴对齐
- 模型文件夹 [分类/下载](https://github.com/modelscope/FunASR/blob/main/README_zh.md#%E6%A8%A1%E5%9E%8B%E4%BB%93%E5%BA%93)，FunASR 支持多种类型的模型，包括：
  - 语音识别模型 `Paraformer`/`SenseVoice`/`FunASR-Nano`
  - VAD 语音端点检测模型，常用于辅助语音识别模型，将长音频切分为多段短音频再识别文本
  - Punc 标点恢复模型，在语音识别输出的文本插入合适的标点符号

## 如何使用
- 整合包:
  - 正在开发中
- 自制运行环境
  - 流明运行 Funasr 需要3部分文件：
    - `FunASR 目录`，对应官方项目源码，可以从 Github clone 下载：
```sh
git clone https://github.com/modelscope/FunASR
```
- - - `Python 环境`，需要安装:
```sh
torch>=2.9.0
torchaudio>=2.9.0

# 执行安装 pip install -U funasr
funasr>=1.3.0

# FunASR-Nano 需要
transformers>=4.51.3
```
- - - `模型文件`: [点击查看部分模型列表](https://github.com/modelscope/FunASR/blob/main/README_zh.md#%E6%A8%A1%E5%9E%8B%E4%BB%93%E5%BA%93)
      - [Paraformer](https://modelscope.cn/models/damo/speech_paraformer-large_asr_nat-zh-cn-16k-common-vocab8404-online/summary)
      - [SenseVoice](https://www.modelscope.cn/models/iic/SenseVoiceSmall)
      - [FunASR-Nano](https://www.modelscope.cn/models/FunAudioLLM/Fun-ASR-Nano-2512)
      - [时间戳预测模型/fa-zh](https://modelscope.cn/models/damo/speech_timestamp_prediction-v1-16k-offline/summary)
      - [VAD 模型](https://modelscope.cn/models/damo/speech_fsmn_vad_zh-cn-16k-common-pytorch/summary)
      - [Punc 模型](https://modelscope.cn/models/damo/punc_ct-transformer_cn-en-common-vocab471067-large/summary)

## 一键整合包
- 可以在bili搜索其他up分享的整合包，在流明都可以使用的，如果不兼容可以向我们反馈

## 问题

## 相关