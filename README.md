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

    
