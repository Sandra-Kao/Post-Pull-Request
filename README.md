# Post-Pull-Request
## 為什麼要做 Pull Request?

- 軟體開發除了地理上跨區，也在時間上跨區，透過 PR 是一個很好的意見交換方式。

- 發 Pull Request Merge 完之後，有個功能可以刪掉 Branch，所以遠端的 Branch 就會很乾淨。

- 透過 WI 留下 Document的方式紀錄各種不同的 commit 和 code change 的 起源和目的。

- 透過綁定同樣類型的WI，並標上 Release Tag，就能夠有留下版號和板本紀錄 Realease Log。

    也能透過版本紀錄回追code change 和 WI，也可以以此建立良好的 Release Note。

- 和 Azure CI 結合

    - Pull Requset 要合併程式碼之前，可以安排CI 跑一次測試程式碼 Pipline 。
    - 這樣就可以管控程式碼合併的安全和完整性。

- 最終目的是讓系統的品質愈來愈好，透過Pull Request 綁定 CI，將小顆粒度的開發TASK，只要一完成就能合併回主線到，可以很有信心合併回去的程式碼是很穩的，穩定程式碼的品質，才不會讓系統衝突愈來愈大。

    

## 為什麼要做 Code Review?

- 通常寫的程式碼好不好，可能只有開發指自己知道

- Code Style 的檢查

- 提升團隊成員技術很重要的方式

- 開發到一定程度，甚至開發到一半，就可以做Code Review
- 藉由 Code Review 來傳達團隊的觀念、習慣、傳統、架構或開發方式
- 建議把顆粒度小的Task ，完成之後就可以做 CR，這樣異動的檔案就不會太多，CR的人就不會改不動太辛苦。



## Git 的板控方式

需要考慮開發團隊或是專案本身的性質，不同情況可選用不同的 Flow。

- Git Flow

    程式碼開發過程中，有時候穩定有時候不穩定。拉不同的分之可以確保軟體正常的交付，而不影響其他開發分之的進行。

    正常的 Feature Branch 通常的生命週期通常運短越好，大部分的開法者認為至少每天要從主幹合併到feature B 中。

- GitHub Flow

    有新的開發就會複製一份 repostory 到新的 repostory 。

- GitLab Flow

    

## Feature Branch 通常的生命週期

在軟體開發和設計思考中，建議 Feature Branch 通常的生命週期的生命長度，會等於一個TASK的結束。

良好的軟體開發和設計思考，可能會占整體開發長度的8成。

有利於提升程式碼開發品質和效率提升，讓系統的品質愈來愈好。



##  Work Item

### 甚麼樣的東西適合開Work Item?

只要跟軟體開發有關的東西，都可以是一個 Work Item。

透過 WI 留下 Document的方式紀錄各種不同的 commit 和 code change 的 起源和目的。

透過綁定同樣類型的WI，並標上 Release Tag，就能夠有留下版號和板本紀錄 Realease Log。

也能透過版本紀錄回追code change 和 WI。
