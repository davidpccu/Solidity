# BlockChain & Solidity 學習筆記

## Podcast
+ [區塊勢](https://open.spotify.com/show/76SfOPXWxSl5eRTs1saDUL?si=bDwDWuYOS0eucdgZiahzNg&dl_branch=1)
+ [寶博朋友說](https://open.spotify.com/show/6kTbqVnANnR3PGpYtp6sw5?si=Kutx-oAQRkaCB6oVpwI94Q&dl_branch=1)

## 基礎知識
+ [0x1學院](https://www.0x1.academy/)
+ [區塊鏈神鵰俠侶](https://hahow.in/courses/5c7a37be4bcf1c0021375ded/discussions?item=5c9da18f0d468f001f4aad03)

## Online IDE
+ [ethfiddle](https://ethfiddle.com/)
+ [remix](https://remix.ethereum.org/)

## 教學
+ [cryptozombies](https://cryptozombies.io/zh/course)

## Gas

### Gas Price
使用者願意出的 Gas 單價，以 Gwei 為單位，礦工的邏輯會依據你出的 Gas Price 來排序，價錢越高的會越優先執行。

### Gas Limit
就是一個保護機制，你可以設定一個交易 or 部署合約，最多花費多少，避免使用者寫出了一個有 bug 的合約，導致無窮盡的消耗資源在區塊鏈中，只要使用到資料就會一直付費，所以 Gas Limit 就是一個保護機制。

> 但是也不能因為這樣刻意把 Gas Limit 調整得很低，因為這樣可能導致你的合約執行到一半，就踩到 Gas Limit 的限制，導致合約執行到一半就失敗。
有一點要注意，已經消耗掉的 Gas 是不會退還的。

每個 gwei 等於 0.000000001 ETH，假設gas 限額為 21,000 單位，gas 價格為 200 gwei。

總費用為：Gas 單位（限制）* 每單位 Gas 價格，即 21,000 * 200 = 4,200,000 gwei 或 0.0042 ETH

待續...
