# FF14の文字の画像データセット
## 目的
作者が個人的にエオルゼア文字翻訳アプリ「言語を超える力」のために、FF14の画像データを物体認識によってエオルゼア文字を英数字にクラス分けするためのデータとして、TensorFlowのファイル形式TFRecordにより画像データを作成しました。

作者自身が完成した「言語を超える力」を作れれば良いのですが、他の方により、より良いものが作れるかもしれません。作者としては私よりもより良い翻訳アプリが作成できれば幸いだと考えていますので、画像データを公開したいと思います。

## 使い方
データの形式はTFRecordです。画像の中身はtfrecord-viewerなどで確認してください

- /eorzea : エオルゼア文字のデータセット
- /eorzea/*.tfrecord : 画像に対してタグ付けされたデータ
- /eorzea/labels.txt : タグの名前リスト

## 利用規約
本ファイルはFF14のスクリーンショット及びそれに類するデータの加工データになります。よってFF14の二次創作にあたります。
利用にあたっては、ファイナルファンタジーXIV 著作物利用条件に則ってご利用ください

https://support.jp.square-enix.com/rule.php?id=5381&la=0&tag=authc