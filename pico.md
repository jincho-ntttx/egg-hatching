# ピコのプログラムの作り方(How to develop a Pico program)

## 1. プログラムを作る前の準備(Preparation before develop the program)

- ![sprite-select-button](figure/common/sprite-select-button.png) ボタンをクリックしてください。

  Click on the ![sprite-select-button](figure/common/sprite-select-button.png) button.

- ピコ(Pico)を選択、クリックしてください。

  Select Pico and click on it.

![sprite-select-pico](figure/pico/sprite-select-pico.png)

- スプライトが設定されていることを確認してください。

  Confirm that the selected sprite is set.

![set-sprite-pico](figure/pico/set-sprite-pico.png)

## 2. プログラムの作り方(How to develop a program)

### 2-1. 完成イメージ(Completed image)

![pico-program-complete](figure/pico/pico-program-complete.png)

### 2-2. 作り方(How to develop)

- 以下のブロックを画面中央にドラック＆ドロップします。

  Drag and drop the following blocks to the center of the screen.

![action-button](figure/common/action-button.png) ![action_xy-coordinates](figure/common/action_xy-coordinates.png)

![appearance-button](figure/common/appearance-button.png) ![appearance_costume-d](figure/pico/appearance_costume-d.png) ×2 ![appearance_words-time](figure/common/appearance_words-time.png)

![event-button](figure/common/event-button.png) ![event-flag](figure/common/event-flag.png)

![control-button](figure/common/control-button.png) ![control-wait-sec](figure/common/control-wait-sec.png)

- 『x座標を○、y座標を○にする』の **x座標に『-111』、y座標に『-7』と入れて**ください。(数字をダブルクリックすることで、数字を編集できる状態になります。)

  Enter "-111" in the x-coordinate and "-7" in the y-coordinate in "Make x-coordinate X and y-coordinate X". (Double-click on the number to make it ready for editing.)

![action_xy-change](figure/pico/action_xy-change.png)

- 『コスチュームをpico-dにする』の▼ボタンを押し、表示される **コスチュームの一覧から、それぞれ『pico-a』、『pico-c』を選んで**ください 。

  Press the ▼ button on "Make costume pico-d" and select "pico-a" or "pico-c" from the list of costumes that will appear.

![appearance_costume-a](figure/pico/appearance_costume-a.png) , ![appearance_costume-c](figure/pico/appearance_costume-c.png)

- 『こんにちは！と2秒言う』「こんにちは！」を **『ドキドキ』に変更**してください。(文字をダブルクリックすることで、文字を編集できる状態になります。)

  "Hello! Two seconds to say, "Hello! should be changed to "Doki-Doki". (Double-click on a character to make it ready to be edited.)

![appearance_words-throb](figure/pico/appearance_words-throb.png)

- 『1秒待つ』の「1」を **『1.5』に変更**してください。(数字をダブルクリックすることで、数字を編集できる状態になります。)

  Change "1" in "Wait 1 second" to "1.5". (Double-click on the number to make it ready for editing.)

![control-wait-sec15](figure/pico/control-wait-sec15.png)

- ブロックをくっつけてください。

  Connect the blocks.

![pico-program-1](figure/pico/pico-program-1.png)

・以下のブロックを画面中央にドラッグ&ドロップします。

  Drag and drop the following blocks to the center of the screen.

![appearance-button](figure/common/appearance-button.png) ![appearance_words-time](figure/common/appearance_words-time.png)

![event-button](figure/common/event-button.png) ![event_get-message1](figure/common/event_get-message1.png)

- 『こんにちは！と2秒言う』「こんにちは！」を **『ワクワク』に変更**してください。(文字をダブルクリックすることで、文字を編集できる状態になります。)

  "Hello! Two seconds to say, "Hello! should be changed to "Exciting". (Double-click on a character to make it ready to be edited.)

![appearance_words-exciting](figure/pico/appearance_words-exciting.png)

・ブロックをくっつけてください。

  Connect the blocks.

![pico-program-2](figure/pico/pico-program-2.png)

- 以下のブロックを画面中央にドラッグ&ドロップします。

  Drag and drop the following blocks to the center of the screen.

![appearance-button](figure/common/appearance-button.png) ![appearance_words](figure/common/appearance_words.png) ![appearance_costume-d](figure/pico/appearance_costume-d.png)

![event-button](figure/common/event-button.png) ![event_get-message1](figure/common/event_get-message1.png)

![control-button](figure/common/control-button.png) ![control-wait-sec](figure/common/control-wait-sec.png)

- 『こんにちは！と言う』の「こんにちは！」を **『わぁっ』に変更**してください。(文字をダブルクリックすることで、文字を編集できる状態になります。)

  "Hello! The "hello!" in "say should be changed to "Wow". (Double-click on a character to make it ready to be edited.)

![appearance_words-wow](figure/pico/appearance_words-wow.png)

- 『コスチュームをpico-dにする』の▼ボタンを押し、表示される **コスチュームの一覧から『pico-b』を選んで**ください 。

  Press the ▼ button on "Make costume pico-d" and select "pico-b" from the list of costumes that appears.

![appearance_costume-b](figure/pico/appearance_costume-b.png)

- 『メッセージ1を受け取ったとき』の▼ボタンを押し、表示される **一覧から『メッセージ2』を選んで**ください。

  Press the ▼ button on "When you received message 1" and select "Message 2" from the list that appears.

![event_get-message2](figure/pico/event_get-message2.png)

- 『1秒待つ』の「1」を **『0.3』に変更**してください。(数字をダブルクリックすることで、数字を編集できる状態になります。)

  Change "1" in "Wait 1 second" to "0.3". (Double-click on the number to make it ready for editing.)

![control-wait-sec03](figure/pico/control-wait-sec03.png)

- ブロックをくっつけてください。

  Connect the blocks.

![pico-program-3](figure/pico/pico-program-3.png)

