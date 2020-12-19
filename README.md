# FunLocks2020年 アピールシート

### プロダクト名
#### - chAt
#### - remoteMic

### コンセプト

- chAt  
 ***「近いのに遠い」*** を解消する
 
- remoteMic  
 ***マイクをもっと便利に！！***

### 対象ユーザ
- chAt
	- 同じ場を共有する人達
		- 大学生
		- 企業の方
		- イベントの参加者
- remoteMic
	- マイクを使う人なら**誰でも！**

### どうやって利用するか

#### 利用シーン
- chAt
	 - 何らかの理由で直接話しかけづらいとき
		 - 交流がまだあまりないとき
		 - 感染症が流行していて、飛沫感染を避けたいとき
	 - 近くにいる人とファイルの共有やチャットをしたいとき
	 - イベントでコミュニケーションツールとして

- remoteMic
  - 企業や大学の説明会などのイベントで質問をするとき
#### 利用方法
- chAt
	- サイトにアクセス
- remoteMic
	- マイクを使って話したい方はclient側のサイトにアクセス
	- マイクの音声の出力をしたい方はhost側のサイトにアクセス


### 推しポイント  
#### 手軽さ
- Webアプリとして機能を実現したため、サイトにアクセスするだけで手軽に使えます。
	- ぜひアクセスしてみてください！
		- chAt: https://funlocks.github.io/team2011/chAt/main/
		- remoteMic(host側): https://funlocks.github.io/team2011/onlineMic/main/host/
		- remoteMic(client側): https://funlocks.github.io/team2011/onlineMic/main/client/
- 同じ場を共有する人(半径５０m以内）と自動的に接続するためスムーズに始めることができます。そのため、事前に相手とコンタクトをとる必要はなく、コミュニケーションを始めるハードルがとても低くなっております。
- さらに、サーバーを使用していないためチャットの記録は残りません。そのため、対面での会話と同じように、その場限りのコミュニケーションをとることができます。
#### デザイン
- remoteMicのデザインは、現実のマイクと同じように使える直感的なデザインにしました。 
- chAtのデザインは、一般的なチャットアプリのデザインを意識しつつ、匿名の個人を識別しやすいようにメッセージの色を割り振りました。
#### スケーラビリティ
- Peer to Peer で通信しているため、ファイルや音声の送受信にはサーバーを使っていません。そのため、サーバーへの負荷はほとんどかかりません。
- SFUという通信方式を使っているため、同時に利用する人数がいくら増えても、利用者の通信量は変わりません。


### スクリーンショット(任意)
![image](https://user-images.githubusercontent.com/68597660/102520667-45e95d00-40d7-11eb-8da4-078c89037778.png)
![image](https://user-images.githubusercontent.com/68597660/102520732-56013c80-40d7-11eb-9e53-51d96456198c.png)
![image](https://user-images.githubusercontent.com/68597660/102522780-0708d680-40da-11eb-9d26-845b96808757.png)


## 開発体制
### 役割分担
- 原　　->　chAtのデザイン, バックエンド
- 古澤　->　remoteMicのデザイン
- 宮澤　->　発表資料, UI, UX
- 福留　->　プロジェクトマネージャー
- 源平　->　バックエンド

### オンライン開発における工夫した点
効率的に開発を進めるために、
「**同期**でやる時間」と「**非同期**でやる時間」に分けました。

「**同期**でやる時間」には、チームで行き違いのないかの確認  
「**非同期**でやる時間」には、それぞれ異なる作業  

をすることでチームですれ違いなく効率的に開発することができました！

## 開発技術(任意)
### 利用したプログラミング言語
*HTML5, CSS3, Javascript*

### 利用したフレームワーク・ライブラリ
*Vue.js, bootstrap4, SkyWay*

### その他開発に使用したツール
*Visual Studio Code, Git Hub, Firebase*
