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

