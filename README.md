# GitHub Pages 发布目录

这个目录可以直接作为 GitHub Pages 的站点根目录上传。

## 包含内容

- `index.html`
- `life-map-data.json`
- `.nojekyll`

## 最短发布方法

1. 在 GitHub 新建一个公开仓库
2. 把这个目录里的文件上传到仓库根目录
3. 打开仓库 `Settings -> Pages`
4. Source 选择 `Deploy from a branch`
5. Branch 选择 `main`，Folder 选择 `/(root)`
6. 保存后等待几分钟

## 地址规则

- 如果仓库名是 `<username>.github.io`
  - 地址会是 `https://<username>.github.io/`
- 如果仓库名是普通项目名，比如 `caoshuang-life-map`
  - 地址会是 `https://<username>.github.io/caoshuang-life-map/`

## 更新方式

每次源文档更新后，重新执行：

```bash
npm run life-map:export-pages
```

然后把这个目录里的最新文件重新推到 GitHub。
