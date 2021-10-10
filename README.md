# ANOTOKINO

## 概要
- 思い出を保管できるアプリ
- Move on HackathonでのチームGの制作物

## テーマ
- オンラインとオフラインの差を埋めよ

## 私たちの考えたオンラインの課題点
- オンラインでのイベントは思い出に残りにくい

## この課題点を解決するためのアプリのコンセプト
- オンラインで出来事の記録を一ヶ月後に届けてもらうことでその時の気持ちをより鮮明に思い出に残せる

## アプリの機能
- 好きなタイミングで思い出を書き込むことができる
- 記録した思い出を一ヶ月後に届けてくれる
- 届けてもらった思い出は友達にも共有できる

## 使用した技術
- Realm
- UIKit

## アプリの中身
### スタート画面
- 今の気持ちを書き込むボタン: 思い出入力画面へ遷移
- あの時を思い出すボタン: 思い出一覧画面へ遷移
- ANOTOKINOとはボタン: 説明ポップアップ画面へ遷移

![Simulator Screen Shot - iPhone 11 - 2021-10-10 at 16 54 34](https://user-images.githubusercontent.com/75970153/136688468-5f62d690-f897-47b2-9d57-a1a64c69cb62.png)


### 思い出入力画面
- 保管するボタン: 入力した思い出を保存

![Simulator Screen Shot - iPhone 11 - 2021-10-10 at 17 33 58](https://user-images.githubusercontent.com/75970153/136688641-cb4f9f71-31ae-492c-94d7-57722cc5411c.png)

### 説明ポップアップ画面

![Simulator Screen Shot - iPhone 11 - 2021-10-10 at 17 30 52](https://user-images.githubusercontent.com/75970153/136688648-b45b0702-9dc5-4cbd-8c4a-a32d3e46485c.png)

### 思い出一覧画面
- 記録から一ヶ月経っているcell(鍵表示なし)をタップしだ場合:　思い出発掘画面へ遷移
- 記録から一ヶ月経っていないcell(鍵表示あり)をタップしだ場合:　まだ見れないよ画面へ遷移

![Simulator Screen Shot - iPhone 11 - 2021-10-10 at 17 33 47](https://user-images.githubusercontent.com/75970153/136688656-2a5f1c87-7972-4d4c-9b60-17505ada8ea6.png)

### 思い出発掘画面
- 共有ボタン: 本文を共有できる

![Simulator Screen Shot - iPhone 11 - 2021-10-10 at 17 33 58](https://user-images.githubusercontent.com/75970153/136688668-e11f4dd8-c6e8-4056-a016-3a519979dcd6.png)

### まだ見れないよ画面

![Simulator Screen Shot - iPhone 11 - 2021-10-10 at 17 33 50](https://user-images.githubusercontent.com/75970153/136688709-44a34bc6-77ad-4703-87ce-9cb9c05eb7c6.png)
