# XjuSelab Homepage

新疆大学软件开发实验室主页 → **<https://selab.top>**

静态单页（`site/index.html`），Aurash · Notion 风格设计令牌，由 **GitHub Actions** 部署到 GitHub Pages。

## 结构

```
site/
├── index.html     # 主页（单文件，内联样式）
├── CNAME          # selab.top
└── favicon.svg
.github/workflows/deploy.yml   # push 到 main 自动部署
```

## 内容

| 板块 | 条目 |
|------|------|
| 项目 | [飞跃手册](https://github.com/XjuSelab/xju-feiyue) · [FluxEnv](https://github.com/XjuSelab/FluxEnv) |
| 脚本猫脚本 | 成绩单一键导入（`import.user.js`）· [CourseGrading AI 解题助手](https://github.com/XjuSelab/xiji)（`cg-ai-solver.user.js`） |

## 本地预览

```sh
python3 -m http.server -d site 8080   # → http://localhost:8080
```

改动 `site/` 下文件并推送到 `main`，Actions 自动重新部署。
