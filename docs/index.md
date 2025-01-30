---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "HayFrp Learn"
  tagline: LEARN MORE CONCERNED WITH HAYFRP.
  image:
    src: /favicon.ico
    alt: HayFrp Learn
  actions:
    - theme: brand
      text: 开始
      link: /what
    - theme: alt
      text: 进入官网
      link: https://www.hayfrp.com/

features:
  - title: 知识文档
    details: 这里，告诉你有关HayFrp的一切。
    link: README
    linkText: 了解我们
  - title: 使用文档
    details: 这里，告诉你怎样用好HayFrp。
    link: usage
    linkText: 探索用法
  - title: 技术文档
    details: 这里，告诉你HayFrp的智慧。
    link: api-doc
    linkText: 深入研究
---

<style>
:root {
  --vp-home-hero-name-color: transparent;
  --vp-home-hero-name-background: -webkit-linear-gradient(120deg, pink, lightblue);

  --vp-home-hero-image-background-image: linear-gradient(-45deg,  pink 50%, lightblue 50%);
  --vp-home-hero-image-filter: blur(44px);

}
</style>