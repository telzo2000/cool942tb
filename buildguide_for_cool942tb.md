# Buildguide for cool942tb

<br>

この文章は書きかけです。
<br>

## 0 部品の確認
<br>
Follow the BOM on github's readme.md to make sure that all the parts are available.
<br>
githubのreadme.mdのBOMに沿って、部品が全て揃っているかを確認してください。
<br>
There are three PCBs. Of the three pieces, two are left and right keyboard boards, and the remaining one is a trackball board.
<br>
PCBが３枚あります。表裏を確認してください。３枚のうち、2枚が左右のキーボード基板で、残り１枚がトラックボール基板です。
<br>

## 1ダイオードのはんだ付け

If the diode is already soldered, please skip this operation.
<br>
すでにダイオードのはんだ付けされている場合は、この作業を省略してください。
<br>
<br>
This work is done on the left and right keyboard boards respectively.
<br>
この作業は左右のキーボード基板でそれぞれ行います。
<br> 
Solder the diodes to the back of PCB.
<br>
PCBの裏面にダイオードのハンダ付けをします。
<br>
The diode is compatible with SMD.
<br>
ダイオードは、SMDに対応しています。
<br>
Diodes have polarity, so be careful about the direction in which they are installed.
<br>
ダイオードには極性がありますので、取り付ける向きに注意してください。
<br>

[ダイオード（SMD)のはんだ付けの動画](https://youtu.be/ODk16bd4XkA)
 

<br>

## 2  スイッチソケットのハンダ付け

Please solder the switch socket only for cherry MX. In the future, if a switch plate and bottom case compatible with choc V2 are available, it will be able to be used as a keyboard compatible with the choc V2 switch.
<br>
cherry MXについてのみスイッチソケットのはんだ付けをしてください。将来的に、choc V2に対応したスイッチプレートやボトムケースができたら、choc V2スイッチ対応のキーボードとして使えるようになります。
<br>
<br>
Solder the switch socket on the back of the left and right keyboard boards.
<br>
左右のキーボード基板の裏面にスイッチソケットのハンダ付けをします。
<br>

[Switch socketハンダ付け動画](https://youtu.be/ZnbgaueMR4w?si=_JLjD--3HJJ5Pu7Q)

<br>

## 3 Seeed xiao bleのハンダ付け

Solder Seeed xiao ble on the back of the left and right keyboard boards. The difficulty is high, so please do it carefully.
<br>
左右のキーボード基板の裏面に、Seeed xiao bleをハンダ付けします。難度が高いので、注意深く行なってください。
<br>

Please follow the steps below.
<br>
次の手順に沿って行ってください。
<br>
1 The one with the xiao reset switch is the surface. Apply flux to the 4 BAT and NFC terminals on the back.
<br>
1 xiaoのリセットスイッチのある方を表面とする。裏面にある、BATとNFCの端子４つにフラックスを塗る。
<br>
<br> 
2 Put the back of the keyboard board up and put xiao on it. The one with the xiao reset switch is up.
<br>
2 キーボード基板の裏面を上にして、xiaoを載せる。xiaoのリセットスイッチのある方を上にする。
<br>
<br>
3 Use the pin header included with xiao, insert it into the left and right pin holes, and temporarily fix it.
<br>
3 xiao付属のピンヘッダを利用し、左右のピン穴に差し込み、仮固定する。
<br>
<br>
4 Change the orientation of the board and xiao. The surface of the keyboard board is on top.
<br>
4 基板とxiaoの向きを変える。キーボード基板の表面が上になる。
<br>
<br>
5 Make sure that there are two rectangular open places on the board where xiao overlaps. Apply flux to the terminal of that part.
<br>
5 基板には、xiaoが重なっているところに、四角形に開いた箇所が2箇所あることを確認する。その部分の端子にフラックスを塗る。
<br>
<br>
6 Apply the warmed solder to 5 places (there are 4 places, one at a time). At the time when it is warm enough to produce a little smoke, attach the solder wire to the solder and pour in the solder.
<br>
From the open part of the square, if the solder is placed on the terminal of the xiao and sticks to the terminal of the board, it is fine.
<br> 
If you put in too much solder, use the solder suction to remove excess solder.
<br>
6 温めたハンダゴテを５の場所（4箇所あるので、１つずつ）に当てる。少し煙が出るほど温めたタイミングで、ハンダ線をハンダゴテに付けて、ハンダを流し込む。
<br>
　四角形の開いた部分から、xiaoの端子にハンダが載っていて、基板の端子とくっついていれば、大丈夫である。
<br>
　ハンダを多く入れ過ぎた時は、ハンダ吸い取り を使い、余分なハンダを除去する。
<br>
<br>
7 With the back of the keyboard board up, pull out the temporarily fixed pin header from the board and xiao.
<br>
7 キーボード基板の裏面を上にして、仮固定のピンヘッダを基板とxiaoから抜く。
<br>
<br>
8 Apply flux to the left and right outer terminals of xiao. After that, solder each terminal.
<br>
8 xiaoの左右外側にある端子にフラックスを塗る。その後、端子ごとに、ハンダ付けをする。
<br>
<br>
Did you do well?
<br>
上手くできましたか？
<br>
<br>

## 4  JSTケーブルの取り付け

Please turn the back of the keyboard board up.
<br>
キーボード基板の裏面を上向きにしてください。
<br>
Plug the red cable of the JST cable into the BAT and the black cable into the GND and solder.
<br>
JSTケーブルの赤色ケーブルをBATに、黒色ケーブルをGNDに差し込んで、ハンダ付けをしてください。
<br>
<br>
There is something I want you to pay attention to. Make sure that the positive pole of the cable socket of the LiPo battery you want to buy is connected to the BAT and the negative pole to the GND.
<br>
There was a case where the red and black sides of the socket attached to the battery sold were reversed.
<br>
注意してほしいことがあります。購入するLiPoバッテリーのケーブルのソケットのプラス極がBATに、マイナス極がGNDに導通することを確認してください。
<br>
販売されているバッテリーについているソケットの赤色、黒色が左右逆の事例がありました。
<br>
<br>


## 5 スライドスイッチのハンダ付け

Insert the switch from the back of the PCB with the switch knob facing outward.
<br>
スイッチのつまみが外側に向くようにして、PCBの裏面から差し込みます。

After temporarily fixing it with masking tape, etc., solder the exposed part of the PCB.
<br>
マスキングテープなどで仮固定をしてから、PCBの表面に出た部分をはんだ付けします。
<br>


[スライドスイッチのはんだ付けの作業動画](https://youtu.be/5nkRklibay4)

<br>

## 6 L字コンスルー（またはピンヘッダ） のハンダ付け

First, use a nipper or cutter to cut the L-shaped conslue into 7 pins.
<br>
If you suddenly try to cut between the 7th and 8th pins, it is easy to fail, so it is a good idea to cut between the 8th and 9th pins and then adjust them with a file.
<br>
最初にL字コンスルーを7ピンになるようにニッパーやカッターなどを使い、裁断してください。
<br>
いきなり、７つ目のピンと８つ目のピンの間を裁断しようとすると、失敗しやすいので、8つ目と９つ目の間を裁断してからヤスリなどで調整するとよいでしょう。
<br>
<br>
Insert the L-shaped through spring from the surface of the keyboard board and temporarily fix it with masking tape, etc.
<br>
Turn the back of the board up and solder it.
<br>
L字コンスルーのバネのついていない方を、キーボード基板表面から差し込んで、マスキングテープなどで仮固定します。
<br>
基板裏面を上向にして、ハンダ付けをします。
<br>
<br>

## 7 トラックボール基板の作成

The trackball board has components installed from the beginning. The implemented side is the back side.
<br>
トラックボール基板は最初から部品が実装されています。実装されている面を裏面とします。
<br>
<br>
Remove the PWM3610 acrylic parts.
<br>
PWM3610アクリル部品を取り外します。
<br>
<br>
Check the pin of the PWM3610 and insert it from the surface of the trackball board. Temporarily fix it with masking tape.
<br>
PWM3610のピンを確認して、トラックボール基板の表面から差し込みます。マスキングテープで仮固定します。
<br>
<br>
The back of the trackball board is facing up and the part that came out of the pin hole is soldered.
<br>
トラックボール基板の裏面を上向きにして、ピン穴からでた部分をはんだ付けします。
<br>
<br>
The lens part of the PWM3610 is covered with tape, so remove it.
<br>
PWM3610のレンズ部分がテープで覆われているので、それを外します。
<br>
<br>
From the back of the trackball board, cover the acrylic part on the PWM3610, and melt the acrylic on the back with a soldering ick to prevent it from coming off.
<br>
トラックボール基板の裏面の方から、アクリル部品をPWM3610に被せて、その裏側に出たアクリルをハンダごてで溶かして外れないようにします。
<br>
<br>







8
<br>
9
<br>