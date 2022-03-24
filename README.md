# symbol_emergence_and_haptics_note



## このリポジトリについて

　記号創発ロボティクスとハプティクスについての調査を備忘的に記録していく。  
 
 
#### 記号創発ロボティクスについて
～まとめ中～

##### [T. Taniguchi, et al., Symbol emergence in robotics:a survey, Advanced Robotics, 30:11-12, 706-728](https://www.tandfonline.com/doi/abs/10.1080/01691864.2016.1164622)
 記号創発ロボティクスのサーベイ。3章までは背景の紹介。4章はマルチモーダルカテゴリ化の研究紹介。4-3節ではカテゴリ数を
自動で算出するbayesian nonparametricsの研究も紹介。5章は言葉の発見のモデル化についての研究紹介。ここでもノンパラベイズ。
6章では二重分節構造について、言語、言語以外の研究について紹介。7章では、通常の自然言語処理であまり言及されない
言語コミュニケーションにおける共有信念についてやintrinsic motivationについての既存研究を紹介。  

__思ったこと__  
 自分の子供の単語発見については、音素、単語、文といったように細かいものから単語を学んでいるように見えない。
 むしろ、多くのセンサー情報の流れをひとまとまりとして区別するのがやっとといった感じである。いないいないあー、
 といって遊んだり、こちらが「おなかすいた？」と聞くと、おそらく食べ物がもらえると思って声色を変えるといった
 感じである。先にマルチモーダルなカテゴリ形成が大雑把にあって、それが後に分化するプロセスがあるように思われる。
 ある程度分化してから見ると、それが階層構造として見えているというだけで、真のモデルは、  
 　　生センサー情報→音素のような意味を与えない単一モーダルのカテゴリ→マルチモーダルカテゴリ  
   　→マルチモーダルカテゴリ同士の共通要素、相違要素の抽出による新マルチモーダルカテゴリ形成(分化)  
    →十分に分化したマルチモーダルカテゴリのあるモーダルへの投影：単一モーダルのカテゴリの組み合わせ  
　となっている気がする。  

->次に読む  
  Word Discovery, mutual belief modeling 関連  
　Iwahashi, Language acquisition through a human-robot interface by combining speech, visual, and  
 behavioral information. Inform. Sci. 2003;156:109-121.  
 →有料だったので一旦保留

 intrinsic motivation関連  
  [Schmidhuber J. Formal theory of creativity, fun, and intrinsic motivation (1990-2010). IEEE Trans.  
 Auton. Mental Dev. 2010;2:230-247](https://ieeexplore.ieee.org/abstract/document/5508364)
 
 
##### [T. Taniguchi et al., "Symbol Emergence in Cognitive Developmental Systems: A Survey," in IEEE Transactions on Cognitive and Developmental Systems, vol. 11, no. 4, pp. 494-516, Dec. 2019](https://ieeexplore.ieee.org/abstract/document/8451965)
AI、神経科学、発達心理学、認知科学、機械学習の視点から、社会における記号のダイナミズムを表現する記号創発システムについて論じている、
認知発達システムにおける記号創発のサーベイ。通して"symbol"という語に２つの意味（単一の離散的なトークンとしての記号、人間の日常生活における記号）があり、
様々な分野で混乱が起きていることを述べている。記号学が現実世界の記号のダイナミズムを表せるコンピュータモデルを持っていないことから、記号創発システムを
提案している。認知科学ではAmodal symbol system(ASS)とPerceptual symbol system(PSS)の２つが提案されており、PSSの方が現実を説明できるとのこと。  
用語の定義を提案している。  
"Category": 例示ベース  
"Concept": 文脈非依存の内的表象  
記号系は小さなコミュニティーや長い時間軸では変化するが、大きなコミュニティーや短い時間軸では不変に見えるため、記号系が不変なものだと誤認されがちと述べている。  
記号創発の計算論モデルを考えると、語用や機能語などについての計算論も求められる。
また、人間とロボットの間に共有信念が必要。岩橋らが提案している。  
  
 __思ったこと__  
 AI、神経科学、発達心理学、認知科学、機械学習の視点から、記号について論じているサーベイ論文。記号創発システムの位置づけがよくわかった。

##### [M. Asada et al., "Cognitive Developmental Robotics: A Survey," in IEEE Transactions on Autonomous Mental Development, vol. 1, no. 1, pp. 12-34, May 2009](https://ieeexplore.ieee.org/abstract/document/4895715)

#### 少し分野の近い論文のメモ

##### Sergey Levine, Reinforcement Learning and Control as Probabilistic Inference: Tutorial and Review



#### 触覚に関連する認知発達ロボティクスの研究について
～まとめ中～  
[T. Taniguchi2016]のサーベイでは、触覚関係は中村先生のマルチモーダルカテゴリ化についての言及があった。



##### 文献メモ

* アンジェロ カンジェロシら著、岡田 浩之ら訳「発達ロボティクスハンドブック」、福村出版(2019)
* ＜未入手＞下条　誠ら、「触覚認識メカニズムと応用技術-触覚センサ・触覚ディスプレイ-【増補版】」、S&T出版(2014)




