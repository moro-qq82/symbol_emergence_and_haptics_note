# symbol_emergence_and_haptics_note



## このリポジトリについて

　記号創発ロボティクスとハプティクスについての調査を備忘的に記録していく。  
 
 
## 記号創発ロボティクスについて
～まとめ中～

### [T. Taniguchi, et al., Symbol emergence in robotics:a survey, Advanced Robotics, 30:11-12, 706-728](https://www.tandfonline.com/doi/abs/10.1080/01691864.2016.1164622)
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
 
 
### [T. Taniguchi et al., "Symbol Emergence in Cognitive Developmental Systems: A Survey," in IEEE Transactions on Cognitive and Developmental Systems, vol. 11, no. 4, pp. 494-516, Dec. 2019](https://ieeexplore.ieee.org/abstract/document/8451965)
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

### [M. Asada et al., "Cognitive Developmental Robotics: A Survey," in IEEE Transactions on Autonomous Mental Development, vol. 1, no. 1, pp. 12-34, May 2009](https://ieeexplore.ieee.org/abstract/document/4895715)
ロボットを用いて人間の発達過程を研究する、認知発達ロボティクスについてのサーベイ。胎児レベルからモデルを作り発達メカニズムについて研究されている。身体表現、motor control、体そのものによる計算、言語獲得、共感能力などの研究についての概要を説明している。  

__思ったこと__  
胎児レベルからシミュレーションにより発達を考えるというのが面白く、また発達過程には未知の領域が多数あることがわかった。胎児の感覚器官の発達において触覚が最も早い（約10週、視覚は18週）のが興味深かった。


->次に読む  
[A. Pitti, et al., "Cross-modal and scale-free action representations through enaction", Neural Netw., 2009](https://perso-etis.ensea.fr/alexpitt/papers/j.neunet.2009.01.007.pdf)  
[L. Natale, et al., "Exploring the world through grasping: A developmental approach", in Proc. 6th CIRA Symp., 2005](https://francesco.orabona.com/papers/05cira.pdf)  
[L. Natale, et al., "Sensorymotor coordination in a 'baby; robot: Learning about objects through grasping," Progr. Brain Res.: From Action to Cogn., vol. 164, 2007](http://www.robotcub.org/misc/papers/07_Natale_Orabona_Metta_Sandini.pdf)  
[L. Natale, et al., "Learning precise 3d reaching in a humanoid robot," in Proc. 6th IEEE Int. Conf. Develop. Learn., 2007](https://www.researchgate.net/profile/Francesco-Nori/publication/4282862_Learning_precise_3D_reaching_in_a_humanoid_robot/links/00b4953a1aa4c76e12000000/Learning-precise-3D-reaching-in-a-humanoid-robot.pdf)  

#### 少し分野の近い論文のメモ

##### [Sergey Levine, Reinforcement Learning and Control as Probabilistic Inference: Tutorial and Review](https://arxiv.org/pdf/1805.00909.pdf)

##### [Masahiro Suzuki, A survey of multimodal deep generative models](https://www.tandfonline.com/doi/abs/10.1080/01691864.2022.2035253)

### 触覚に関連する認知発達ロボティクスの研究について
～まとめ中～  
[T. Taniguchi2016]のサーベイでは、触覚関係は中村先生のマルチモーダルカテゴリ化についての言及があった。
「発達ロボティクスハンドブック」より、國吉らによるFetus model1及び2において、羊水中の胎児を模擬し千個以上の接触センサをつけた胎児シミュレーションモデルを開発し、認知発達を調査した研究について言及あり。論文は下記。  
* [Kuniyoshi, Y., Sangawa, S. Early motor development from partially ordered neural-body dynamics: experiments with a cortico-spinal-musculo-skeletal model. Biol Cybern 95, 589 (2006)](https://link.springer.com/article/10.1007/s00422-006-0127-z)  about 5000Yen.
* [H. Mori and Y. Kuniyoshi, "A human fetus development simulation: Self-organization of behaviors through tactile sensation," 2010 IEEE 9th International Conference on Development and Learning, 2010, pp. 82-87, doi: 10.1109/DEVLRN.2010.5578860. ](https://ieeexplore.ieee.org/abstract/document/5578860) about 1800Yen



#### 文献メモ

* アンジェロ カンジェロシら著、岡田 浩之ら訳「発達ロボティクスハンドブック」、福村出版(2019)
* Angelo Cangelosi(編), Minoru Asada(編), "Cognitive Robotics (Intelligent Robotics and Autonomous Agents series)", The MIT Press(2022)
* ＜未入手＞下条　誠ら、「触覚認識メカニズムと応用技術-触覚センサ・触覚ディスプレイ-【増補版】」、S&T出版(2014)




