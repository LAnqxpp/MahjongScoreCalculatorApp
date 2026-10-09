# 雀记官网 / 法律与支持页（GitHub Pages）

## 开启 Pages

1. 将本仓库推送到 GitHub（建议仓库名 `QueScore`）
2. GitHub → Settings → Pages  
   - Source: **Deploy from a branch**  
   - Branch: **main**  
   - Folder: **/docs**
3. 等待 1～2 分钟后访问：

```
https://<你的用户名>.github.io/QueScore/
https://<你的用户名>.github.io/QueScore/terms.html
https://<你的用户名>.github.io/QueScore/privacy.html
```

4. 打开 App 工程里的 `WQAppWebLinks.swift`，把 `baseURLString` 改成上面的根地址（不要末尾 `/`）。

## 页面

| 文件 | 说明 |
| --- | --- |
| `index.html` | 技术支持 |
| `terms.html` | 用户协议 |
| `privacy.html` | 隐私政策 |
| `css/site.css` | 样式 |
