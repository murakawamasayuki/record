# 業務内容
①10:00~　　SQL  
③12:00~　　共有会  
④13:00~　　N予備校  
⑤15:30~　　データ分析  




# 学び　気付き
①BETWEEn句  
レンジ期間を表す場合は　  
Cost >= 100 AND cost < 200  
→cost BETWEEN 100 AND 200  

IN句  
AccountDesriptiveName = ‘マイケア’ OR AccountDesriptiveName = ‘アイム’
→AccountDesriptiveName IN ( ‘マイケア’ , ‘アイム’)
このように簡略して描ける

LIKE句  
曖昧なワードを抽出する  
LIKE ‘%ああ’→ああ××　前方一致  
LIKE’%ああ%’→××ああ××　部分一致  
LIKE’ああ%’→ああで終わる  

論理演算子  
AND  AとBを両方含む  
OR    AまたはBのどちらか含む  
NOT 含まない  

④  
Post.findAll().then(posts => {  
  res.end(  
    pug.renderFile('./views/posts.pug', {  
      posts: posts  
    })  
  );  
});  
Post.findAll()の値をpostsとしてthen関数の引数として渡すことまではわかったがその後の動きがよくわからなかった。  
⑤  
相関係数  
二つのデータまたは確率変数の間にある線形的な関係の強弱を測る指標  
値が負なら負の相関関係  
値が正なら正の相関係数  
0から2はほとんど相関がない  
2から4はやや相関あり  
4から7はやや強い相関あり  
7以降は強い相関がある  



# 次回出社時の業務内容
法務研修  
データ分析オンライン講座  
SQL  



