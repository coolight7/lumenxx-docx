---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "流明AI"
  text: "AI音视频处理工具"
  tagline: AI翻唱,人声伴奏分离,文字转语音
  actions:
    - theme: brand
      text: 下载
      link: https://download.lumenxx.bool.run/
    - theme: alt
      text: 使用帮助
      link: /help/
    - theme: alt
      text: GitHub
      link: https://github.com/coolight7/lumenxx-docx
  image:
      src: images/logo-tran.png
      alt: 流明AI

features:
  - title: 多模型支持
    details: 支持运行 DDSP-SVC、MSST、GPT-SoVITS 等模型
  - title: 工作流
    details: 可将AI模型搭建工作流执行自动化任务
  - title: 简便操作
    details: UI界面操作、选择文件(夹)时自动推荐、快捷播放预览等
---
<style>
:root {
  --vp-home-hero-name-color: transparent;
  --vp-home-hero-name-background: -webkit-linear-gradient(120deg, #66ccff 30%, #41d1ff);

  --vp-home-hero-image-background-image: linear-gradient(-45deg, #e1edfa 50%, #fff9ec 50%);
  --vp-home-hero-image-filter: blur(44px);
}

html.dark {
  --vp-home-hero-image-background-image: linear-gradient(-45deg, #13e4ea 50%, #7d78eb 50%);
}

@media (min-width: 640px) {
  :root {
    --vp-home-hero-image-filter: blur(56px);
  }
}

@media (min-width: 960px) {
  :root {
    --vp-home-hero-image-filter: blur(68px);
  }
}
</style>
