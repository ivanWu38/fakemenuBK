
# Burger King Taiwan - Order Flow (Local Images)

這是可直接部署到 **GitHub Pages** 的版本。

## 結構
- `index.html`：主頁（含 JS）
- `styles.css`：樣式
- `images/`：請把所有圖片放在這裡（見下方清單）
- `images/placeholder.jpg`：占位圖（缺圖時顯示）

## 需要的圖片檔名（放在 images/）
whopper.jpg
spicy-whopper.jpg
double-whopper.jpg
angus-peanut.jpg
angus-black-pepper.jpg
bacon-double.jpg
king-chicken.jpg
double-king-chicken.jpg
fish-burger.jpg
buffalo-double.jpg
fries-small.jpg
fries-medium.jpg
onion-rings.jpg
chicken-nuggets.jpg
sweet-potato-fries-s.jpg
sweet-potato-fries-l.jpg
buffalo-wings.jpg
coke-s.jpg
coke-m.jpg
coke-l.jpg
tea-m.jpg
tea-l.jpg
coffee.jpg
family-set.jpg
double-value.jpg
one-plus-one.jpg
placeholder.jpg

## 部署到 GitHub Pages
1. 建立 GitHub Repository（例如 `bk-menu`）。
2. 把整個資料夾內容推上去（包含 images）。
3. 到 Repo -> Settings -> Pages -> Source: `main` / `(root)` -> Save
4. 開啟提供的網址即可。

## 可選：滿版風格
若想讓圖片更滿版（會裁切邊緣），可將 `styles.css` 裡 `.item-card img` 的
`object-fit: contain;` 改成 `object-fit: cover;`。
