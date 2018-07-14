# TF-IDF(Term Frequency - Inverse Document Frequency)
Calculate cosine-similarity between documents using TF-IDF
此專案以新聞資料進行tf-idf結合cosine similarity實作
### TF-IDF Introduction:
TF-IDF是一種統計方法，用以評估一字詞對於一個檔案集或一個語料庫中的其中一份檔案的重要程度。字詞的重要性隨著它在檔案中出現的次數(TF)成正比增加，但同時會隨著它在語料庫中出現的頻率(IDF)成反比下降。

### Cosine Similarity Introduction:
餘絃相似度（cosine similarity）是資訊檢索中常用的相似度計算方式，可用來計算文件之間的相似度，也可以計算詞彙之間的相似度，更可以計算查詢字串與文件之間的相似度。

### IDF補充:


### 補充:
新聞資料大概只有200篇，且斷詞使用jieba，造成很多詞斷錯或只出現在某一篇新聞文檔。
