# 多項式除法預習 App（試版）

馬Sir教室 · 中四 4A Ch6 續多項式（多項式除法）翻轉學習預習頁。

## 公開網址

https://masir-math.github.io/poly-division-preview/

## 本機預覽

用瀏覽器直接開啟本資料夾的 `index.html`，或在資料夾執行：

```bash
python3 -m http.server 8765
```

然後開啟 http://127.0.0.1:8765/

## 老師點用（一句）

派呢條連結俾學生預習影片＋做自測；堂上集中講長除法同逆求除式。

## Google Sites 嵌入

插入 → 嵌入 → 網址，貼上公開網址。建議高度約 1100–1400 px。若 Sites 沙盒預覽出現 YouTube Error 153，叫學生用頁內「新分頁開啟影片」，或以新分頁開啟成個 App。

## 功能

- 左欄：YouTube（youtube-nocookie）＋章節跳轉＋新分頁後備
- 右欄：課題重點（KaTeX）／8 題自測（分層 Hint）／個人正確率／全班數據（本機 localStorage＋模擬同學）

## 已知限制

- 播放影片需要網絡；公式已內嵌 KaTeX，離線仍可顯示重點同題目
- Error 153 常見於沙盒 iframe（Sites 預覽）；公開頁或新分頁一般正常
- 全班數據係試版本機模擬，唔係真雲端班成績，亦唔收集真實姓名／學號
