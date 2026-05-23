# cloudpivot-ecc-doc

云枢 Frontend AI 协作治理文档站点（GitHub Pages）。

## 在线访问

https://stogefei.github.io/cloudpivot-ecc-doc/

## 首次启用 GitHub Pages（仅需一次）

1. 打开 [仓库 Settings → Pages](https://github.com/stogefei/cloudpivot-ecc-doc/settings/pages)
2. **Build and deployment → Source** 选 **Deploy from a branch**
3. **Branch** 选 `main`，目录选 **/ (root)**，点 **Save**
4. 等待 1～2 分钟，访问上方链接

## 内容

- `index.html` — Rules & Skills 使用说明（来源：`cloudpivot-ecc/docs/skills-rules-overview.html`）

## 更新

```bash
cp /path/to/cloudpivot-ecc/docs/skills-rules-overview.html index.html
git add index.html && git commit -m "docs: sync skills-rules-overview" && git push
```
