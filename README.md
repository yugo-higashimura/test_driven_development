# 書籍『テスト駆動開発』の写経

## レギュレーション
テスト駆動開発の書籍では、実装を使われ方から考えることを徹底している。  
また、小さいステップを踏むことも重要と表現しているため、コミット単位をこの小さいステップの単位で行うこととする。 　

## コミットメッセージのフォーマット
`Condition` - Commit message 

#### Condition
`Red` = テスト失敗  
`Green` = テスト成功  
`Refactor` = リファクタリング

## 感想
コミットを細かくすることで、「Red > Green > Refactor」のフローを意識しながらコーディングできたので、良かった。  
面倒なことには変わりなく、何度もコミットを忘れ、巻き戻ってコミットし直すことになった。  

チームで運用する何ら、Refactorを積み上げがベターかな。  
個人開発なら、Greenでコミットを作っておくことで、Refactorで無茶しやすい感じがした。  
（やっぱ、やーめた。が簡単にできるので気持ち的に楽）  
