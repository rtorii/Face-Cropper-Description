# 顔切り抜き

コード：https://github.com/GhaithKhoja/ARG_Project

**説明:**

人物画像から顔を切り抜くWebアプリです。人物画像を入力として受け入れ、切り抜いた顔画像を出力します。PyTorchライブラリ( https://arxiv.org/abs/1703.06870 )から取り込んだMask R-CNNを使用して、Face/Head Segmentation Dataset Community Editionなどのデータセット下で顔を検出し微調整を行いました。

**ターゲットユーザー:**

画像から顔を簡単かつ短い時間に切り出したい人をターゲットユーザーにしています。主なターゲットユーザー層は、切り抜き画像を使って新しい製品を作りたいアーティストやデザイナーです。例えば、切り抜いた画像を別の画像に貼り付けたい人や、ステッカーを作りたい人などです。 フォトショップで顔部分を切り取るという面倒な作業をしなくても、ユーザーが画像をサイトにアップロードすれば、数秒で切り抜いた画像が出力されます。



| ホームページ | 
| ------ | 
| <img alt="Screen Shot 2022-06-14 at 13 28 56" src="https://user-images.githubusercontent.com/52717342/173502519-d0fdec68-591f-4d44-9d3b-9b677386918d.png"> |

| 人物画像をアップロード | 
| ------ | 
| <img width="1440" alt="Screen Shot 2022-06-21 at 20 57 48" src="https://user-images.githubusercontent.com/52717342/174793863-3fceea26-4c90-4a54-b67a-58a06871d475.png"> |

| 切り抜いた画像 | 
| ------ | 
| <img width="1440" alt="Screen Shot 2022-06-21 at 20 57 06" src="https://user-images.githubusercontent.com/52717342/174793880-bd825d97-8680-43bc-8e8f-26257ad0caea.png"> |
