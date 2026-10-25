# Paper Micro-Lessons 📚🦉

把一篇學術論文拆成像 Duolingo 一樣的小堂互動課程。每堂課只講一個概念，課後用**申論題或實作題**（不用選擇題）確認你真的懂了，才進入下一堂。最終目標：你能用自己的話把這篇論文教給別人。

Turn any academic paper into bite-sized, Duolingo-style lessons for Claude, with open-ended quizzes and mastery gating.

## 兩個版本

| Skill | 適合誰 |
|---|---|
| `skills/paper-micro-lessons` | 一般使用者，只在對話中學習 |
| `skills/paper-micro-lessons-obsidian` | 用 Obsidian + Zotero 做筆記的人：每通過一堂就更新 `{citekey}-lessons.md`，並連回 Zotero 文獻筆記 |

## 安裝

### Claude.ai / Claude 桌面版
1. 到 [Releases](../../releases) 或用綠色 **Code → Download ZIP** 下載
2. 把想用的那個 skill 資料夾（例如 `paper-micro-lessons/`）單獨壓成 zip
3. 在 Claude 的 **Settings → Capabilities → Skills** 上傳

### Claude Code
```bash
git clone https://github.com/Wu-Chien-Yi/Paper-micro-lessons.git
cp -r Paper-micro-lessons/skills/paper-micro-lessons ~/.claude/skills/
```

## 使用方式
附上論文 PDF 或連結，說「教我這篇」或「用 Duolingo 的方式帶我讀這篇論文」即可。

## 流程
1. 讀完整篇論文，建立 8–15 堂的課程地圖
2. 由淺入深：專有名詞 → 名詞間的關聯 → 方法原理 → 這篇論文的學習點
3. 每堂：迷你講解 + 一道申論／實作題，答對才前進
4. 總驗收：像教外行朋友一樣講完整篇論文

## License
MIT
