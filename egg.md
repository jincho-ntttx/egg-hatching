# 卵のプログラムの作り方

## 1.プログラムを作る前の準備(Preparation before develop the program)

- Scratch 3.0を起動し、スプライト1を削除してください。(スプライト1を選択→×をクリック)

  Start Scratch 3.0 and delete sprite 1.(Select sprite 1　→　Click ×)

![sprite-cat-delete](figure/egg/sprite-cat-delete.png)

- ![sprite-select-button](figure/common/sprite-select-button.png) ボタンをクリックしてください。

  Click on the ![sprite-select-button](figure/common/sprite-select-button.png)  button.

- **Hatchlingを選択**、クリックしてください。

  Select a Hatchling and click on it.

![sprite-select-hatching](figure/egg/sprite-select-hatching.png)

- スプライトが設定されていることを確認してください。

![sprite-egg](figure/egg/sprite-egg.png)

- **大きさを『200』 に変更**してください。(数字をダブルクリックすることで、数字を編集できる状態になります。)

  Change the size to "200".(Double-clicking on a number, you will be able to edit the number.)

![egg-size200](figure/egg/egg-size200.png)

## 2. プログラムの作り方(How to develop a program)

### 2-1. 完成イメージ(Completed image)

![egg-program-completed](figure/egg/egg-program-completed.png)

### 2-2. 作り方(How to develop)

- ![block-button](figure/common/block-button.png) を押してください。

  Press ![block-button](figure/common/block-button.png) .

- ![make-block-button](figure/common/make-block-button.png) を押してください。

  Press ![make-block-button](figure/common/make-block-button.png) .

- 以下の画面が表示されるので、**『ブロック名』を『ブルブルの角度』に変更**してください。

  When the following screen appears, change the "Block Name" to "Angle of the Bulbul".

![init-screen](figure/common/init-screen.png)

- 『引数を追加(数値またはテキスト)』をクリックし、**『number or text』を『角度』に変更**してください。

  Click on 'Add argument (number or text)' and change "number or text" to "angle".

![init-screen_angle](figure/common/init-screen_angle.png)

- もう一度『引数を追加(数値またはテキスト)』をクリックし、**『number or text』を『タイマー』に変更**し、OKボタンを押してください。

  Click on 'Add argument (number or text)' again, change "number or text" to "timer" and press the OK button.

![init-screen_timer](figure/common/init-screen_timer.png)

- 以下の画面が表示されることを確認してください。

  Confirm that the following screen is displayed.

![angle-definition](figure/common/angle-definition.png)

- 以下のブロックを画面中央にドラッグ&ドロップします。

  Drag and drop the following blocks to the center of the screen.

  ![action-button](figure/common/action-button.png) ![action-angle](figure/common/action-angle.png)

  ![control-button](figure/common/control-button.png) ![control-wait-sec](figure/common/control-wait-sec.png)

- ![action-angle](figure/common/action-angle.png) の『90』に ![angle](figure/common/angle.png) をドラッグ&ドロップしてください。

  Drag and drop the ![angle](figure/common/angle.png) to the "90" of ![action-angle](figure/common/action-angle.png) .

- ![control-wait-sec](figure/common/control-wait-sec.png) の『1』に ![timer](figure/common/timer.png) をドラッグ&ドロップしてください。

  Drag and drop ![timer](figure/common/timer.png) to "1" of ![control-wait-sec](figure/common/control-wait-sec.png) .

- ブロックをくっつけてください。

  Connect the blocks.

![block-definition_angle](figure/common/block-definition_angle.png)

- ![block-button](figure/common/block-button.png) を押してください。

  Press ![block-button](figure/common/block-button.png) .

- ![make-block-button](figure/common/make-block-button.png) を押してください。

  Press ![make-block-button](figure/common/make-block-button.png) .

- 以下の画面が表示されるので、**『ブロック名』を『ブルブル』に変更**してください。

  When the following screen appears, change the "Block Name" to "Bulbul".

![init-screen](figure/common/init-screen.png)

- 『引数を追加(数値またはテキスト)』をクリックし、**『number or text』を『リスト番号』に変更**してください。

  Click 'Add argument (number or text)' and change 'number or text' to 'list number'.

![init-screen_list-number](figure/common/init-screen_list-number.png)

- ![variable-button](figure/common/variable-button.png) を押してください。

  Press ![variable-button](figure/common/variable-button.png) .

- ![make-list-button](figure/common/make-list-button.png) を押してください。

  Press ![make-list-button](figure/common/make-list-button.png) .

- **『新しいリスト名：』に『角度』と入力後、『このスプライトのみ』を選択**してOKボタンを押してください。

  Enter "Angle" in the "New List Name:" field, select "This Sprite Only" and click the OK button.

![make-new-list](figure/common/make-new-list.png)

- 空のリストが画面上に表示されることを確認してください。

  Confirm that the blank list display on the screen.

![blank-list](figure/egg/blank-list.png)

- リストの＋ボタンを押し、 **105、90、75、90、115、90、65、90、125、90、55、90** と計12項目設定してください。(1つ入力したら＋ボタンで項目を追加していってください。)

  Press the + button on the list and set a total of 12 items: 105, 90, 75, 90, 115, 90, 65, 90, 125, 90, 55, and 90. (Once you have entered one item, please add more items by pressing the + button.)

![angle-list](figure/egg/angle-list.png)

- 以下のブロックを画面中央にドラッグ&ドロップします。

  Drag and drop the following blocks to the center of the screen.

![control-button](figure/common/control-button.png) ![control-repeat](figure/common/control-repeat.png)

![operation-button](figure/common/operation-button.png) ![operation-adding-up](figure/common/operation-adding-up.png) ×3

![variable-button](figure/common/variable-button.png) ![variable-angle-number](figure/common/variable-angle-number.png) ×4

![block-button](figure/common/block-button.png) ![block-angle](figure/common/block-angle.png) ×4

- ![operation-adding-up](figure/common/operation-adding-up.png) の左側の○に ![list-number](figure/common/list-number.png) をドラッグ&ドロップし、右側の○にそれぞれ **1,2,3と入れて** ください。

    Drag and drop ![list-number](figure/common/list-number.png) into the left-hand circles of ![operation-adding-up](figure/common/operation-adding-up.png) , and put 1,2,3 into the right-hand circles, respectively.

![operation_list-number_add1](figure/egg/operation_list-number_add1.png) , ![operation_list-number_add2](figure/egg/operation_list-number_add2.png) , ![operation_list-number_add3](figure/egg/operation_list-number_add3.png)

- ![block-angle](figure/common/block-angle.png) の左側の○に ![variable-angle-number](figure/common/variable-angle-number.png) をドラッグ&ドロップし、右側の○に **0.02と入れて** ください。

  Drag and drop ![variable-angle-number](figure/common/variable-angle-number.png) into the left circle of the ![block-angle](figure/common/block-angle.png) and put 0.02 into the right circle.

![block-angle_number-timer](figure/egg/block-angle_number-timer.png) ×4

- ![block-angle_number-timer](figure/egg/block-angle_number-timer.png) の『1』の部分に ![list-number](figure/common/list-number.png) 、 ![operation_list-number_add1](figure/egg/operation_list-number_add1.png) 、 ![operation_list-number_add2](figure/egg/operation_list-number_add2.png) 、 ![operation_list-number_add3](figure/egg/operation_list-number_add3.png) をドラッグ&ドロップしてください。

  Drag and drop ![list-number](figure/common/list-number.png) , ![operation_list-number_add1](figure/egg/operation_list-number_add1.png) , ![operation_list-number_add2](figure/egg/operation_list-number_add2.png) , and ![operation_list-number_add3](figure/egg/operation_list-number_add3.png) into the "1" part of ![block-angle_number-timer](figure/egg/block-angle_number-timer.png) .

![block-angle_list-number](figure/egg/block-angle_list-number.png) , ![block-angle_operation-add1](figure/egg/block-angle_operation-add1.png) , ![block-angle_operation-add2](figure/egg/block-angle_operation-add2.png) , ![block-angle_operation-add3](figure/egg/block-angle_operation-add3.png)

- ブロックをくっつけてください。

  Connect the blocks.

![block-definition_buruburu](figure/common/block-definition_buruburu.png)

- 以下のブロックを画面中央にドラッグ&ドロップします。

  Drag and drop the following blocks to the center of the screen.

![appearance-button](figure/common/appearance-button.png) ![appearance_costume-change](figure/egg/appearance_costume-change.png) ![appearance_next-costume](figure/common/appearance_next-costume.png) ×2

![event-button](figure/common/event-button.png) ![event-flag](figure/common/event-flag.png) ![event_send-message1](figure/common/event_send-message1.png) ×2

![control-button](figure/common/control-button.png) ![control-wait-sec](figure/common/control-wait-sec.png)

![variable-button](figure/common/variable-button.png) ![variable_hide-list](figure/common/variable_hide-list.png)

![block-button](figure/common/block-button.png) ![block-angle](figure/common/block-angle.png) ![block-buruburu](figure/common/block-buruburu.png) ×3

- 『コスチュームをhatchling-cにする』の▼ボタンを押し、表示される **コスチュームの一覧から『hatchling-a』を選んで** ください 。

  Press the ▼ button on "Make costume hatchling-c" and select "hatchling-a" from the list of costumes that will appear.

![appearance_costume-select](figure/egg/appearance_costume-select.png)

- 『メッセージ1を送る』のうち一つに対し、▼ボタンを押して **『新しいメッセージ』を選択して** ください。

  For one of the "Send Message 1" options, press the ▼ button and select "New Message".

![event_new-message](figure/egg/event_new-message.png)

- 以下の画面が表示されることを確認し、 **『新しいメッセージ名：』に『メッセージ2』と入力し** OKボタンを押してください。

  Enter "Message 2" in the "New Message Name:" field and click the OK button.

![init-screen_new-message](figure/common/init-screen_new-message.png)

- 以下のブロックができます。

  You can create the following blocks.

![event_message2](figure/egg/event_message2.png)

- 『1秒待つ』の「1」を **『0.05』に変更** してください。(数字をダブルクリックすることで、数字を編集できる状態になります。)

  Change "1" in "1 second wait" to "0.05". (Double-click on the number to make it ready for editing.)

![control_wait-sec005](figure/egg/control_wait-sec005.png)

- 『ブルブルの角度○○』に **『90と1』** を入れてください。

  Put "90 and 1" in "Bulbul XX".

![block-angle_90](figure/egg/block-angle_90.png)

- 『ブルブル○』に、それぞれ **『1』『5』『9』** を入れてください。

  Put "1", "5", and "9" in the "Bulbul X", respectively.

![block-buru_list1](figure/egg/block-buru_list1.png) , ![block-buru_list5](figure/egg/block-buru_list5.png) , ![block-buru_list9](figure/egg/block-buru_list9.png)

- ブロックをくっつけてください。

  Connect the blocks.

![egg-program](figure/egg/egg-program.png)
