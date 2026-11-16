# AI 協作開發小講義（ai-dev-notes）

一個用 `AGENTS.md` 規則驅動的靜態講義網站，主題是「如何與 AI 協作開發」。

- 網頁：`https://<你的帳號>.github.io/ai-dev-notes/`
- AI 規則：[AGENTS.md](AGENTS.md)（Claude Code 請見 [CLAUDE.md](CLAUDE.md)）

## 本機預覽

```bash
python3 -m http.server 8000
# 瀏覽器開啟 http://localhost:8000
```

## 新增一課

對 AI 說：

```
新增講義：〈主題〉，入門難度，包含 X 個重點。
```

AI 會依 `AGENTS.md` 第 5 節流程，複製 `templates/lesson-template.html`、更新首頁卡片與上下頁連結。
