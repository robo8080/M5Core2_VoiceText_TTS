# M5Core2_VoiceText_TTS
M5Stack Core2で、HOYA社が提供する[VoiceText Web APIサービス](https://cloud.voicetext.jp/webapi "Title")を使った音声合成(TTS)を動かすテストプログラムです。


M5Core2_VoiceText_TTSは、kghrlaboさんのesp32_text_to_speechを参考にさせていただきました。<br>
オリジナルはこちら。<br>
esp32_text_to_speech <https://github.com/kghrlabo/esp32_text_to_speech><br>

---

### 必要な物 ###
* [M5Stack Core2 または M5Stack Fire](http://www.m5stack.com/ "Title") (M5Stack Core2、M5Stack Core2 for AWS、M5Stack Fireで動作確認をしました。)<br>
* Arduino IDE (1.8.15で動作確認をしました。)<br>
* [ESP8266Audio](https://github.com/earlephilhower/ESP8266Audio/ "Title")ライブラリ<br><br>

### WiFiの設定 ###
* M5Core2_VoiceText_TTS.inoの8行目付近、SSIDとPASSWORDを設定してください。

### VoiceText Wev API api キーの設定 ###
* AudioFileSourceVoiceTextStream.cppの30行目付近、YOUR_TSS_API_KEYを設定してください。<br>

APIキーは。[ここ](https://cloud.voicetext.jp/webapi/ "Title")の「無料利用登録」から申請すれば、メールで送られて来ます。<br>

### 使い方 ###
* M5Stack Core2のボタンA,B,Cを押すと、それぞれ異なった声でしゃべります。　<br>


<br><br>

