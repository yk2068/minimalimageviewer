> [!IMPORTANT]
> **本仓库是 [deminimis/minimalimageviewer](https://github.com/deminimis/minimalimageviewer) 的 Fork**

## 定制改动点

- 图片序号/总数是右键菜单里可点击的一项，位于「下一张图片」上方；点击输入序号即可跳转。Preferences 的「Show image index in context menu」可关闭，界面不展示评级。
- 快捷键打开外部编辑器（默认 `E` → `mspaint.exe`）；编辑器路径在 Preferences，快捷键在 Keybindings 中可改。
- 平滑缩放在整数倍放大时同样生效，呈现 FastStone 式柔化观感（Preferences → Smooth Scaling）。
- `Ctrl+0`–`Ctrl+5` 设置 0–5 星评级，评级保存在便携 INI 并尽力写入 Windows Rating 属性；右键菜单提供按评级排序与按最低星级筛选。
- 无参数启动自动打开上次查看的图片，路径记录在便携 INI 的 `Settings/LastImagePath`；文件已不存在时跳过。
- 编辑保存后自动重新加载同一张图，序号与缩放位置保持不变；另存/缩放产生的新文件插在原图之后，不会把浏览位置甩到列表末尾。
