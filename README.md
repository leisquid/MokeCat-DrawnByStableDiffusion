# MokeCat-DrawnByStableDiffusion

## 仅使用了 Latest 和 Anything 3.0 这两个 Stable Diffusion 模型，通过文生图模式模型作画，没有使用其他辅助模型，没有使用图生图模式，更没有自行炼丹！！！如有和其他画师画风雷同的情况，纯属巧合！！！

由 [Stable Diffusion web UI](https://github.com/AUTOMATIC1111/stable-diffusion-webui) 绘制的[徵羽摩柯](https://zh.moegirl.org.cn/%E5%BE%B5%E7%BE%BD%E6%91%A9%E6%9F%AF)（VOCALOID 角色）的猫人形象的图片。

## 目录

包含两个文件夹：Initial 和 RealCUGAN4x。Initial 中有 Stable Diffusion 直接生成的、未经处理的、包含生成信息数据的图片（有筛选），RealCUGAN4x 是使用 [Real-CUGAN](https://github.com/bilibili/ailab/tree/main/Real-CUGAN) 进行降噪并放大到 4 倍大小的图片（部分图片有处理）。

## 涉及的正向关键词

```
{{masterpiece}}, illustration, {wallpaper}, checkered, incredibly detailed, {extremely detailed}, absurdres, best quality, highly detailed, official art, doujinshi, solo focus, blurry background, solo, {{{zhiyu moke \(vocaloid\)}}}, {{{boy}}}, {{{1boy}}}, {{{cute boy}}}, {{{shota}}}, short hair, dark blue hair, blue eyes, small ahoge, {cat ears}, {cat tail}
```

这些关键词可以确保生成带有猫耳猫尾的 moke 的图片，您也可以尝试使用这些关键词让 AI 作画。但是可能会随机出现逻辑问题，比如缺失的猫耳或凭空出现的猫尾等，需自行筛选、增减权重或者添加负向关键词进行限定。根据使用训练集模型的不同，生成图片的画风或细节可能也会有不同。

可以根据自己的 XP 系统对关键词进行微调。比如加入 `serafuku` 可以让 moke 穿上水手服（不过最好搭配 `trousers` 使用以避免生成裙子）；`leaning forward` 可以使身体呈前倾的姿态；如果不想看到有呆毛的 moke，可以删掉关键词 `small ahoge`。

## 如何下载这些图片

只需 `clone` 下来即可。

```shell
git clone https://github.com/leisquid/MokeCat-DrawnByStableDiffusion.git
```

由于仓库可能不定时更新，所以不打包配布。您也可以随时 `pull` 来获取新图片。

```shell
cd MokeCat-DrawnByStableDiffusion
git pull
```

## 使用规则

+ 允许个人学习、研究、欣赏用。
+ 允许二次创作（如临摹、改图、视频制作等），但是需要注明使用的素材来自本仓库，并附上地址（仅仅是希望更多的人能发现这个仓库，找到这些图片的最原始来源）。
+ 禁止违反法律、道德、公共秩序或损害社会的使用。
+ 禁止用于商业用途。
+ 禁止用于非法出版物或作品。
+ 禁止政治、宗教、R18 目的的使用。
+ 禁止伪称自己是这些图片的作者，尤其伪称是自己作画而只字未提 AI 创作。

## 其他

如果有什么问题请告诉我（提 issue 或者去 [B 站](https://space.bilibili.com/21790370)私信皆可）罢，我什么都会做的。

李逍鱿（leisquid）的 [GitHub 仓库](https://github.com/leisquid)

2022.11.4

2023.1.22 更新
