<details>
<summary>研究紹介（一時的に書いておきます）</summary>

## 🐋 水環境工学研究室

渡辺先生の研究グループと平川の研究グループがあります．

私の方は，
***「プログラムを直に扱って流体と物体の相互作用に関する数値解析を行う」***
方で，下のメンバーがいます．

* 4年生：5名
* 修士1年生：1名

### ✍️ 指導方針や研究環境

* 4年生は就職活動が終わるまでは忙しいと思うので，研究はゆっくり進めてもらっています
* 研究の質問はいつでも来て下さい
* プログラミングに膨大な時間を費やすことができる人は向いていると思います
* 創造工房実習は，4年生が行っている研究に沿った内容を行います
* 今は4年生が使っていますが，研究室には５，６台MacのPCがあります

### 📚 研究テーマ

自分のやりたいことがある学生には，それに沿った研究をしてもらっています．
それ以外の学生は，以下のようなテーマを中心に研究を進めています．

- 境界要素法（BEM-MEL）の高効率化（[Longuet-Higgins](https://en.wikipedia.org/wiki/Michael_S._Longuet-Higgins)が発案した方法です）
- 境界要素法（BEM-MEL）を使ったバージ型浮体の動揺解析
- 陽解法型SPH（EISPH）の開発
- 🐡水棲動物の遊泳効率に関する研究（[Lighthill](https://en.wikipedia.org/wiki/James_Lighthill)も関心があった面白い内容ですが，今は学生任せになっています）
    * 実際に魚のように動くロボットを作成して，その遊泳効率を実験で調べようとしています
    * 魚の学校🐟🐠🐡を数値シミュレーションも行っています

## 👤 自己紹介

- 💻 流体の流れを数値的にシミュレートする研究をしています．海洋の波や流れの計算に興味が湧き，研究を始めました
- 🛠️ 大学院のときはスペクトル法を学んでいましたが，現在は**境界要素法**と**粒子法**を用いたソフトウェア開発を行っています

理論にも興味はありますが，何よりもまず現実の現象をシミュレートできるソフトを作りたいと思っています．

### 🚢 研究と開発

主に[浮体式洋上風力発電](https://en.wikipedia.org/wiki/Floating_wind_turbine)に関する研究を行っています．
浮体の動揺や係留索に関連する数値シミュレーションの需要は，今後増えていくと考えられます（最後に関連するリンクを貼っています）．

現在すでに[OrcaFlex](https://www.orcina.com/)や[WAMIT](https://www.wamit.com/)といった商用ソフトウェアがありますが，
現在の目標は，多くの浮体を含めウィンドファーム全領域をシミュレートできる
計算手法を提案することと，実用的なソフトウェアを開発することです．

* 境界要素法を使った浮体動揺解析ソフト
    - 説明 : 境界要素法は，流体の運動方程式を流体境界上で解く手法です 
    - 使用言語 : [C++](https://en.wikipedia.org/wiki/C%2B%2B), [python](https://www.python.org/) 
    - リンク : [build_bem](https://github.com/tomoakihirakawa/cpp/blob/main/builds/build_bem/README.md) 

<table style="border-collapse:collapse;border:2;cellspacing:5;cellpadding:5;">
<tr>
<td>
<img src="sample0.gif" width="220px" alt="Sample 0 Image">
</td>
<td>
<img src="sample1.gif" width="220px" alt="Sample 1 Image">
</td>
</tr>
</table>

* 粒子法を使った流体物体相互作用解析ソフト
    - 説明 : 粒子法は，粒子の集まりで流体を表現し，流体の運動方程式を解く手法です
    - 使用言語 : [C++](https://en.wikipedia.org/wiki/C%2B%2B), [python](https://www.python.org/) 
    - リンク : [build_sph](https://github.com/tomoakihirakawa/cpp/blob/main/builds/build_sph/README.md)

### 👩‍💻 数値解析を中心とした研究の魅力

興味のある現象を理解し上手に説明することを研究目的とする人が多いと思います．
私もそうです．もっと言えば，数値解析を通して，その現象を理解することが好きです．
というのも，自分が設定した条件下で，その現象を完璧に再現できれば，
その現象をある程度は理解できたと考えるからです．

**数値解析手法**は，数学とプログラミングを組み合わせ，以下の様な問題を解くものです．
既に多くの手法が開発されています．この問題はあらゆる分野で見られるため，数値解析はとても有用です，
ゲームに限らず単純なアプリにも数値解析手法が使われていますし，
今これを見るために使っているPCやスマホの中にも，数値解析手法が組み込まれています．

<table style="border-collapse:collapse;border:2;cellspacing:5;cellpadding:5;">
<tr>
<td><a href="https://github.com/tomoakihirakawa/cpp/blob/main/builds/build_interpolation/README.md">関数近似/補間</a></td>
<td>←関数の微分</td>
<td><a href="https://github.com/tomoakihirakawa/cpp/blob/main/builds/build_integration/README.md">関数の積分</a></td>
<td><a href="https://github.com/tomoakihirakawa/cpp/blob/main/builds/build_root_finding/README.md">方程式の根を求める</a></td>
<td><a href="https://github.com/tomoakihirakawa/cpp/blob/main/builds/build_eigen_value/README.md">固有値問題の解法</a></td>
</tr>

<tr>
<td><a href="https://github.com/tomoakihirakawa/cpp/blob/main/builds/build_system_of_linear_eqs/README.md">線形方程式の解法</a>
<td><a href="https://github.com/tomoakihirakawa/cpp/blob/main/builds/build_ODE/README.md">常微分方程式の解法</a></td>
<td>偏微分方程式の解法</td>
<td><a href="https://github.com/tomoakihirakawa/cpp/blob/main/builds/build_Network/README.md">幾何学（格子生成/データ構造）</a>
</td>
</tr>
</table>

この数値解析手法を組み合わせ，物理現象を表す方程式を数値的に解くことで，現象をシミュレートすることができます．

<!-- #### 有用で普遍的な知識が身につけざるを得ない -->

十分に理解しないまま作成したプログラムで得られる結果は，実際の現象と大きく異なることが多いです．
適当でも結果が得られることもありますが，いろいろと試すうちにおかしいことに気づくことが多いです．
そのため，力学・数学・プログラミングの正確な理解がこの研究を行う上で重要です．
反対に言えば，この研究を通して，力学・数学・プログラミングを正確に学んでいくことができます．
私にとって，これがこの研究の魅力です．

<!-- ## ✉️ 連絡先

- 📧 Email: hirakawa`at`gipc.akita-u.ac.jp
- 🌐 Website: [秋田大学研究者総覧](https://akitauinfo.akita-u.ac.jp/html/100000862_ja.html?k=%E5%B9%B3%E5%B7%9D), [researchmap](https://researchmap.jp/tomoakihirakawa) -->

### 浮体式洋上風力発電に関するリンク

|説明|リンク|
|:---------|-|
|HywindTanpenはノルウェーにある現在世界最大の浮体式洋上ウィンドファーム|https://www.equinor.com/energy/hywind-tampen|
|戸田建設は五島福江島にウィンドファームを建設する予定|https://www.toda.co.jp/business/ecology/special/|
|BW ideolはバージ型浮体の動揺を抑えるダンピングプールの特許を保有するフランス企業|https://bw-ideol.com/en|
|NEDOの委託を受けて日本でもバージ型浮体の研究開発が行われてきました|https://www.nedo.go.jp/floating/|
|アメリカのエネルギー省も浮体式の研究開発を活発に行っています|https://www.nrel.gov/wind/offshore-wind.html|
|その他様々な企業が低コスト化を目標に研究開発を進めています|https://www.jpower.co.jp/news_release/2023/05/news230530.html|


</details>