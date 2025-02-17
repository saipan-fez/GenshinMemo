- [何ができる？](#%E4%BD%95%E3%81%8C%E3%81%A7%E3%81%8D%E3%82%8B)
- [はじめに](#%E3%81%AF%E3%81%98%E3%82%81%E3%81%AB)
- [セットアップ手順](#%E3%82%BB%E3%83%83%E3%83%88%E3%82%A2%E3%83%83%E3%83%97%E6%89%8B%E9%A0%86)
	- [1. 武器・聖遺物のスキャン](#1-%E6%AD%A6%E5%99%A8%E3%83%BB%E8%81%96%E9%81%BA%E7%89%A9%E3%81%AE%E3%82%B9%E3%82%AD%E3%83%A3%E3%83%B3)
	- [2. スキャン結果の取り込み](#2-%E3%82%B9%E3%82%AD%E3%83%A3%E3%83%B3%E7%B5%90%E6%9E%9C%E3%81%AE%E5%8F%96%E3%82%8A%E8%BE%BC%E3%81%BF)
	- [3. キャラクター設定](#3-%E3%82%AD%E3%83%A3%E3%83%A9%E3%82%AF%E3%82%BF%E3%83%BC%E8%A8%AD%E5%AE%9A)
	- [4. チーム設定](#4-%E3%83%81%E3%83%BC%E3%83%A0%E8%A8%AD%E5%AE%9A)
- [組み合わせ探索手順](#%E7%B5%84%E3%81%BF%E5%90%88%E3%82%8F%E3%81%9B%E6%8E%A2%E7%B4%A2%E6%89%8B%E9%A0%86)
- [探索結果の見方](#%E6%8E%A2%E7%B4%A2%E7%B5%90%E6%9E%9C%E3%81%AE%E8%A6%8B%E6%96%B9)

Genshin Optimizer  
https://frzyc.github.io/genshin-optimizer
## 何ができる？
「会心率100%を保った状態で最大ダメージが出る聖遺物の組み合わせ」など、  
特定の条件下での手持ち聖遺物での最適な組み合わせを探すことができます。    
組み合わせ結果では、装備中聖遺物との詳細な比較確認なども行えます。  
![](Pasted%20image%2020250210023656.png)

## はじめに
Genshin Optimizer (以降 本ツール)で最適な聖遺物の組み合わせを計算するために、  
手持ちの武器や聖遺物などを外部ツールを使って取り込むか、  
それらの情報を手入力する必要があります。    

外部ツールの使用は**自己責任**になりますので、ご注意ください。  
また、外部ツールはPCのみ対応です。  

> 外部ツールといってもチートやデータ改ざんを行うようなものではなく、  
> 原神のアイテム画面での操作→スクショ作成→聖遺物の解析を自動で行うぐらいのものです。
## セットアップ手順
初回または手持ちキャラ・武器・聖遺物更新時のみ行う必要がある手順です。  
なお、登録/設定したデータ等は全て自動でブラウザに保存されているため、いつブラウザを閉じても問題ありません。  
### 1. 武器・聖遺物のスキャン
[InventryCamera](https://github.com/Andrewthe13th/Inventory_Kamera) を使って手持ちの武器・聖遺物の情報を取得する。  

ツールのDL/使い方  
https://youtu.be/51bVCd0zKwo?si=e1fQ_w9CX8RVQAq9&t=112

> 普段の画面サイズのアスペクト比が 21:10 など 4:3, 16:9 以外の解像度から画面サイズを変更した場合、  
> 一度ゲームを再起動しないとうまく解析が開始されないことがあります。

> キャラ情報も解析可能ですが、放浪者の名前が日本語だとうまく認識されないのか良く分からないため、  
> 自分はキャラ情報(Lv/天賦Lv等)は後程手動で行っています。  
> 面倒であれば併せてキャラ情報も自動取得で良いかと。

### 2. スキャン結果の取り込み
URL: https://frzyc.github.io/genshin-optimizer/  
1. ページ右上の[DataBase]で設定ページを開く。  
2. Database1のアップロードから、InventryCamera で出力されたjsonファイルを選択する。  ![](Drawing%202025-02-10%2002.04.09.excalidraw.png)
3. [データベースの入れ替え] を押下。  ![](Pasted%20image%2020250210020947.png)

### 3. キャラクター設定

4. 上部メニューから[キャラクター]を選択し、聖遺物の組み合わせを試すキャラクターを選択  ![](Pasted%20image%2020250210021206.png)
5. 選択したキャラの天賦(1)、レベル(2)、凸数(3)を選択  ![](Drawing%202025-02-10%2002.12.47.excalidraw.png)
6. **上記手順をPTメンバー残り3名とも行う**

### 4. チーム設定
7. 上部メニューから[Teams]を選択し、[Add Team]を押下   ![](Pasted%20image%2020250210022852.png)
8. [クイック選択]を押下し、PTメンバー4名を選択   ![](Drawing%202025-02-10%2002.30.23.excalidraw.png)

## 組み合わせ探索手順
9. [Teams]ページを開き、作成したPTを選択する  
10. シミュレート時の各キャラ・武器のバフ/デバフ状態を選択する ([To Field]で表に出ているキャラを切替) ![](Drawing%202025-02-10%2002.43.14.excalidraw.png)
11. 組み合わせ探索したいキャラを選択し、[改良]を選択   ![](Drawing%202025-02-10%2002.46.51.excalidraw.png)
12. 組み合わせ探索条件を設定（詳細は下記）
13. [改良ターゲットを選択]を押下し、組み合わせの検索候補となるステータスまたは攻撃を選択する（ここで選択した数値が高い順に探索結果が表示される） ![](Drawing%202025-02-10%2002.52.09.excalidraw.png)
14. 探索ビルド数・スレッド数を変更（基本的にMAX値推奨）し、[ビルドを生成]を押下

#### 組み合わせ探索条件について
![](Pasted%20image%2020250210025851.png)

**ボーナスステータス**  
不明。変更することはないと思う。  

**複数改良ターゲット構成**  
不明。上記手順5の「改良ターゲットを選択」を複数選択できる？  

**聖遺物レベルフィルター**  
探索する聖遺物のレベル。  
デフォルトのLv0～20では候補が多すぎるため、**Lv20のみに変更推奨**。  

**メイン効果フィルター・構成**  
探索する聖遺物のメインオプション。  
デフォルトでは全てが候補となるため、**絞り込み推奨**。  
以下の画像では　時計：HP　杯：HP or 水　冠：HP or 会心率 or 会心ダメ　に絞っている状態。  
![](Pasted%20image%2020250210030541.png)

**聖遺物を除外**  
歯車アイコンから選択した聖遺物を探索から除外する。  
ほぼ使うことはないと思われる。  

**Use artifacts in teammates' active builds**  
チームメンバーが現在装備している聖遺物を探索から除外する。  

**部分的なビルドを許可する**  
不明。全ての部位を装備していない状態を許可する？  

**聖遺物セットの設定**  
探索するセット、およびセット効果の制約を設定する。  
まず最初に  
「すべての2セットを除外」  
「すべての4セットを除外」  
「2セット効果のみ」  
「セット効果無し」  
の4つを押下し、**探索したい組み合わせのみ選択することを推奨**。  

(例1) マーヴィカが火魔女4 or 黒曜4 を装備する前提  
![](Pasted%20image%2020250210031634.png)

(例2)夜蘭がHP2セット/水2セットを装備する前提  
![](Pasted%20image%2020250210031749.png)

**装備中聖遺物構成**  
歯車アイコンから選択したキャラが装備中の聖遺物を除外する。  

**最小ビルド制約**  
最低限満たしていなければならない条件を設定する（複数設定可能）。  
例えば次の画像は以下の条件を設定している。  
- 会心率は `100%` 以上
- チャージ効率は `120%` 以上
- 元素熟知は `80` 以上

![](Pasted%20image%2020250210031939.png)
## 探索結果の見方
基本的には表示されている通り。  
左側ボタンで表示するダメージを変更する。  
**右側ボタンで現在装備中の聖遺物との比較値が表示できる。**  
![](Drawing%202025-02-10%2003.25.08.excalidraw.png)