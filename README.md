> [!IMPORTANT]
> **本仓库是 [deminimis/minimalimageviewer](https://github.com/deminimis/minimalimageviewer) 的 Fork**

## 定制改动点

- 图片序号/总数是右键菜单里可点击的一项，位于「下一张图片」上方；点击后就地变为底部叠加输入框，直接打数字、回车跳页（`Esc` 取消、退格删除），不弹任何对话框。Preferences 的「Show image index in context menu」可关闭。
- 快捷键打开外部编辑器（默认 `E` → `mspaint.exe`）；编辑器路径在 Preferences，快捷键在 Keybindings 中可改。
- 平滑缩放在整数倍放大时同样生效，呈现 FastStone 式柔化观感（Preferences → Smooth Scaling）。
- `Ctrl+0`–`Ctrl+5` 设置 0–5 星评级，评级保存在便携 INI 并尽力写入 Windows Rating 属性；快捷键改评级后右下角短暂显示星级提示。右键菜单的评级区是一条星级条：鼠标移到哪里就实时预览几颗星，点击应用；菜单不再提供评级筛选。
- 无参数启动自动打开上次查看的图片，路径记录在便携 INI 的 `Settings/LastImagePath`；文件已不存在时跳过。
- 编辑保存后自动重新加载同一张图，序号与缩放位置保持不变；另存/缩放产生的新文件插在原图之后，不会把浏览位置甩到列表末尾。
- 界面文案全部走多语言表（含中文），右键菜单不再有硬编码英文。
