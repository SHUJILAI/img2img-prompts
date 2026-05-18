# GPT Image 2 (image2) Prompts — 100 Curated

> 100 条针对 OpenAI **gpt-image-2**（ChatGPT Images 2.0，2026-04-21 发布）的即拿即用提示词，覆盖 33 个分类：海报、UI、电商、信息图、漫画、游戏截图、海报、电影海报、专辑封面、杂志封面、票据、地铁图、广告牌 mockup、聊天截图、像素艺术、吉卜力风、韦斯安德森风、无人机航拍、显微宏观、餐厅菜单、菜谱卡、包装设计等。

## 文件

| 文件 | 内容 | 推荐使用 |
| --- | --- | --- |
| [`gpt_image_2_prompts_full.json`](./gpt_image_2_prompts_full.json) | 全集 100 条（id 1-100） | ⭐ 推荐 |
| [`gpt_image_2_prompts.json`](./gpt_image_2_prompts.json) | 第一批 50 条（id 1-50） | |
| [`gpt_image_2_prompts_part2.json`](./gpt_image_2_prompts_part2.json) | 第二批 50 条（id 51-100） | |
| [`img2img_prompts.json`](./img2img_prompts.json) | 同 part1 的兼容副本 | |

## JSON 结构

```jsonc
{
  "meta": {
    "model": "gpt-image-2",
    "count": 100,
    "categories": [...],
    "core_tips": [...]
  },
  "prompts": [
    {
      "id": 1,
      "title": "...",
      "category": "poster_typography",
      "tags": ["..."],
      "aspect_ratio": "2:3",
      "prompt": "可直接复制到 ChatGPT 使用的完整提示词"
    }
  ]
}
```

## 33 个分类

`ad_creative` · `album_cover` · `amateur_realistic` · `apparel_mockup` · `billboard_mockup` · `book_cover` · `chat_screenshot` · `chinese_commercial` · `comic_manga` · `diorama_3d` · `drone_aerial` · `game_screenshot` · `ghibli_style` · `illustration_style` · `infographic_diagram` · `logo_branding` · `magazine_cover` · `merch_collectible` · `microscope_macro` · `movie_poster` · `packaging_design` · `photorealistic_portrait` · `poster_typography` · `product_photography` · `recipe_card` · `restaurant_menu` · `search_screenshot` · `stamp_postcard` · `subway_map` · `ticket_stub` · `ui_mockup` · `voxel_pixel_art` · `wes_anderson`

## 使用建议

1. 直接把 `prompt` 字段贴到 ChatGPT，附上对应的 `aspect_ratio`。
2. 复杂排版或中文场景建议切到 **Thinking 模式**（Plus / Pro）。
3. 图中文字一律用英文双引号 `"..."` 包住，渲染准确率 >95%。
4. 二次编辑时显式重申不变项（"same character, same outfit, same lighting"）防止漂移。

## Raw 直链

```
https://raw.githubusercontent.com/SHUJILAI/img2img-prompts/main/gpt_image_2_prompts_full.json
```
