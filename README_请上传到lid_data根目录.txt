这个补丁用于修复 GitHub Pages 报错：
archive/reports/2026/06/2026-06-30.json: HTTP 404

上传方式：
1. 解压本压缩包。
2. 把解压出来的 archive 文件夹上传到 GitHub 仓库 deerinwild/lid_data 的根目录。
3. 如果提示覆盖 archive/summary/2026/2026-06.json，允许覆盖。
4. 上传后确认仓库中存在：
   archive/reports/2026/06/2026-06-30.json
   archive/summary/2026/2026-06.json
5. 等 GitHub Pages 刷新 1-3 分钟后，打开：
   https://deerinwild.github.io/lid_data/archive/reports/2026/06/2026-06-30.json
   如果能看到 JSON 数组，就说明 404 已修复。

本补丁不包含 latest.json，不会覆盖 2026-07-01 的最新索引。
