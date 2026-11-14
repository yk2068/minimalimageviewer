> [!IMPORTANT]
> **本仓库是 [deminimis/minimalimageviewer](https://github.com/deminimis/minimalimageviewer) 的 Fork**

## 定制改动点

- 图片序号/总数：系统标题栏前缀 `[i / n]`；右键菜单打开期间、或切换图片后 1.5 秒，在图片上方居中短暂显示。Preferences 可关闭，界面不展示评级。
- 快捷键打开外部编辑器（默认 `E` → `mspaint.exe`）；编辑器路径在 Preferences，快捷键在 Keybindings 中可改。
- 平滑缩放在整数倍放大时同样生效，呈现 FastStone 式柔化观感（Preferences → Smooth Scaling）。
- `Ctrl+0`–`Ctrl+5` 设置 0–5 星评级，评级保存在便携 INI 并尽力写入 Windows Rating 属性；右键菜单提供按评级排序与按最低星级筛选。
- 无参数启动自动打开上次查看的图片，路径记录在便携 INI 的 `Settings/LastImagePath`；文件已不存在时跳过。
