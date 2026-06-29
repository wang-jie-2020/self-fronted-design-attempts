# VTuber Debut 个人资料卡 — 默认配置

```json
{
  "type": "VTuber Debut 个人资料卡",
  "goal": "生成一张可作为 VTuber 出道日的官方个人资料卡视觉",
  "character": {
    "name": "霜白·诺娜",
    "style": "日系 anime + 半写实",
    "gender": "少女",
    "age_setting": "18 岁",
    "appearance": "银白长发，蓝色双瞳，雪绒帽 + 哥特连衣裙",
    "pose": "半身正面，微微侧头微笑"
  },
  "color_theme": {
    "main_color": "冰蓝 + 月白",
    "accent_color": "淡粉"
  },
  "debut_info": {
    "debut_date": "2026.05.20",
    "platform": "YouTube · Bilibili",
    "tags": "#初配信 #雪絨組 #VTuber",
    "agency": "NEX Live"
  },
  "background": {
    "type": "冬日雪原 + 极光",
    "fx": "雪花飘落 + 冷光粒子"
  },
  "layout": {
    "character_position": "画面 1/2 偏右",
    "info_block_position": "画面左侧竖排",
    "logo_position": "右下角 agency logo"
  },
  "aspect_ratio": "3:4",
  "constraints": {
    "must_keep": [
      "角色作为视觉主体",
      "名字与 debut 信息清晰可读",
      "主色与角色配色一致",
      "agency logo 不超过 5%"
    ],
    "avoid": [
      "角色脸部被信息块遮挡",
      "背景特效喧宾夺主",
      "字体多种类",
      "出现真实平台真实 logo（除非用户提供）"
    ]
  }
}
```
