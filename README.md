# Face Cropper / 顔切り抜き

Code / コード：https://github.com/GhaithKhoja/ARG_Project

**Description / 説明:**

This web app aims to simplify and accelerate the process of cropping human heads/faces from images. The input would be a normal image and the output would be the cropped head with a transparent background. The backbone of the project would be using the Mask R-CNN imported from PyTorch library ( https://arxiv.org/abs/1703.06870 ) to detect faces and fine tune under dataset such as Face/Head Segmentation Dataset Community Edition.

人物画像から顔を切り抜くWebアプリです。人物画像を入力として受け入れ、切り抜いた顔画像を出力します。PyTorchライブラリ( https://arxiv.org/abs/1703.06870 )から取り込んだMask R-CNNを使用して、Face/Head Segmentation Dataset Community Editionなどのデータセット下で顔を検出し微調整を行いました。

**Targeted Audience / ターゲットユーザー:**

This app targets individuals and groups who want to crop heads from images in an easy and timely manner. The main target user audience is artists and designers who want to use cropped images to create new products. This can include a person who wants to paste a cropped head image on another image or someone who wants to create stickers with these cropped images.  

Instead of going to photoshop and manually cropping the head portion, which can be a tedious process, the user can easily upload the image to the website, and an image of the cropped image will be generated in seconds for the user to download. Users can start their own businesses to create products. Since this may require users to use our app repeatedly to get cropped images to be used for new designs of their products, it is important for them to use an app, like ours, which completes the task of cropping heads in an efficient manner. 

画像から顔を簡単かつ短い時間に切り出したい人をターゲットユーザーにしています。主なターゲットユーザー層は、切り抜き画像を使って新しい製品を作りたいアーティストやデザイナーです。例えば、切り抜いた画像を別の画像に貼り付けたい人や、ステッカーを作りたい人などです。 フォトショップで顔部分を切り取るという面倒な作業をしなくても、ユーザーが画像をサイトにアップロードすれば、数秒で切り抜いた画像が出力されます。




| Home page / ホームページ | 
| ------ | 
| <img alt="Screen Shot 2022-06-14 at 13 28 56" src="https://user-images.githubusercontent.com/52717342/173502519-d0fdec68-591f-4d44-9d3b-9b677386918d.png"> |

| Uploading an image / 人物画像をアップロード | 
| ------ | 
| <img width="1440" alt="Screen Shot 2022-06-21 at 20 57 48" src="https://user-images.githubusercontent.com/52717342/174793863-3fceea26-4c90-4a54-b67a-58a06871d475.png"> |

| Cropped image / 切り抜いた画像 | 
| ------ | 
| <img width="1440" alt="Screen Shot 2022-06-21 at 20 57 06" src="https://user-images.githubusercontent.com/52717342/174793880-bd825d97-8680-43bc-8e8f-26257ad0caea.png"> |


<!-- `FLASK_APP = FaceRipper flask run` to run the app locally. -->
<!-- ローカルで実行する際のコマンド: `FLASK_APP = FaceRipper flask run` -->

