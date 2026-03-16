# 使用帮助
- 本页将帮助您使用『流明AI』，如有需要可点击前往[了解『流明AI』](/info/)

## 疑问
- 如果使用帮助没有解决您的疑问，可以尝试以下方式：
  - 查看[常见疑问](issue)
  - 查看[已知问题](question)

## 提交Bug和建议
- 建议在[流明AI的GitHub项目](https://github.com/coolight7/lumenxx-docx/issues)中的Issue提出Bug和建议（**访问Github很可能需要挂VPN/梯子**）；
- **如果联系作者可能会被覆盖看不到。**

## 开始
- AI功能的运行环境或整合包我们一般会兼容：
  - 流明分享的一键整合包（操作简单，一般解压即可使用）
  - 大部分时候可以兼容bili上部分其他UP分享的整合包（和我们分享的整合包类似，但如果改动较大可能和`流明`不兼容，可以向我们反馈）
  - 对应AI项目的Github官方流程搭建的运行环境（手动搭建比较麻烦，且需要一定的专业知识）
- `流明`的软件本体并没有附带各种AI功能的运行环境，因此部分功能需要额外下载解压AI运行环境整合包
  - 以下功能安装`流明`即可使用：
    - 音频工具
    - 文件工具
  - 以下功能安装`流明`后还需要下载解压对应的整合包：
    - Llama.cpp
    - StableDiffusion.cpp
    - DDSP-SVC
    - RVC
    - MSST
    - GPT-SoVITS
    - ACE-Step
    - FunASR

## 其他
- [过渡动画]
- [关于字体大小和样式]；可使用`屏幕缩放与边距调整`缩放字体大小
- [屏幕缩放与边距调整]；设置-界面-屏幕缩放与边距调整，可以调整整体界面、按钮、文字大小

## 功能
- [音频工具]；格式转换、响度平衡、自动切片
- [文件工具]；批量重命名、批量平铺移动文件
- 流明对AI模型的支持：
  - [Llama.cpp](./plugins/llama-cpp/)；运行语言聊天模型，可理解 文本/图像
  - [StableDiffusion.cpp](./plugins/stablediffusion-cpp)；输入描述/参考图，生成 图像/视频
  - [DDSP-SVC](./plugins/ddsp-svc/)；AI变声/翻唱
  - [RVC]；AI变声/翻唱
  - [MSST](./plugins/msst/)；人声伴奏分离、和声混音分离、降噪
  - [GPT-SoVITS](./plugins/gpt-sovits/)；TTS、音色克隆、AI配音，模仿一段参考音频的音色和语气，将文本朗读出来
  - [ACE-Step](./plugins/ace-step/)；AI编曲
  - [FunASR](./plugins/funasr/)；AI语音识别，附带时间戳。也可用于自动歌词打轴

## 综合指南
