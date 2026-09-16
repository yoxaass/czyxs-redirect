# czyxs.cc.cd 跳转站

把 `czyxs.cc.cd` 做成网盘入口的直达跳转页（GitHub Pages 托管，免备案）。

访问 `czyxs.cc.cd` → 自动跳转到 `https://bj39524.apps.aliyunfile.com/`

## 文件说明

| 文件 | 作用 |
|---|---|
| `index.html` | 首页跳转页 |
| `404.html` | 任意子路径（如 `/s/xxxx`）也会转发到网盘同名路径，实现"整站别名" |
| `CNAME` | GitHub Pages 自定义域名声明，内容为 `czyxs.cc.cd` |
| `.nojekyll` | 关闭 Jekyll 处理，避免静态文件被构建流程干扰 |

## 域名

- 解析：`czyxs.cc.cd` CNAME → `<你的GitHub用户名>.github.io`
- 托管：GitHub Pages（Settings → Pages）
- 换入口只改 `index.html` / `404.html` 里的 `bj39524.apps.aliyunfile.com`
