# hunter-cao/soren GitHub Pages 发布包

这个目录是给仓库 `https://github.com/hunter-cao/soren` 准备的可发布内容。

## 目标地址

- Pages 地址：`https://hunter-cao.github.io/soren/`

## 上传内容

把这里的文件放到仓库根目录：

- `index.html`
- `life-map-data.json`
- `.nojekyll`
- `README.md`

## 每次更新

先在主项目里执行：

```bash
npm run life-map:export-pages
```

再重新同步这个目录并推到 GitHub。
