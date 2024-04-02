# Depth Video Player
[![](https://img.youtube.com/vi/9t6Q_n_9fto/0.jpg)](https://www.youtube.com/watch?v=9t6Q_n_9fto)


# セットアップ手順

1. **ネットワーク接続**
   - PCとiPhoneを同じネットワークに接続してください。

2. **アプリケーションのインストール**
   - iPhone/iPadにアプリをインストールしてください。
     * ダウンロードリンクについては私にお問い合わせください [X](https://twitter.com/Taka_Yoshinaga),[LinkedIn](https://www.linkedin.com/in/tks-yoshinaga/)
     * LiDARセンサーが必要です。
   - このリポジトリからLooking Glass用のアプリをダウンロードしてください。
   - 公式ウェブサイトからLooking Glass Bridgeをダウンロードしてインストールしてください： [Looking Glass Bridge](https://lookingglassfactory.com/software/looking-glass-bridge).
   - ディスプレイ設定を確認してください。[Display Setting](https://docs.lookingglassfactory.com/software-tools/looking-glass-bridge/display-settings-on-windows)

# アプリケーションの使用方法

1. **デバイスの接続**
   - PCとLooking Glass PortraitをHDMIケーブルで接続してください。

2. **ソフトウェアの起動**
   - Looking Glass Bridgeを起動します。
   - `DepthVideoPlayer.exe` (Windows)または `DepthVideoPlayer.app`(Mac) を起動します。
   - PCのIPアドレスがLooking Glassに表示されていることを確認してください。

3. **iPhone/iPadアプリの開始**
   - iPhone/iPadアプリを開きます。
   - アプリ内でIPアドレスを入力し、`Set`ボタンをタップしてください。

4. **録画**
   - `Rec`ボタンをタップして録画を開始します。
     * 色付きの領域の奥行きが録画され、遠景（灰色の領域）の奥行きは録画されません。
     * 青線で示された奥行きの周囲の領域がLooking Glassにクリアに表示されます。
      <img src="https://github.com/TakashiYoshinaga/DepthVideoPlayer/blob/main/Materials/example.jpg?raw=true" width="200">
   - `Stop`ボタンをタップして録画を終了します。

5. **再生**
   - Depthデータ(奥行き)を含むビデオはPCに自動的に転送され、再生が始まります。

# ビデオファイルの手動追加と削除

1. **iPhone/iPadのファイル保存場所**
   - ファイル -> Depth Recorder -> Capturesに進んでください。
   - ファイルを削除するか、PCに転送してください。

2. **PCのファイル保存場所**
   - Windows: DepthVideoPlayer.exeと同じディレクトリ内の`dl`フォルダ内。
   - Mac: DepthVideoPlayer.app内の`dl`フォルダ内。

# トラブルシューティング
iPhoneで奥行き付きのビデオを録画した後、すぐにLookingGlassにビデオが表示されない場合は、ファイヤーウォールの設定からDepthVideoPlayer.exeを一度削除してください。  
または、このアプリケーションを使用しているときだけ一時的にファイヤーウォールをオフにしてください。  
[アプリ毎のファイヤウォール設定(Windows)](https://www.fmworld.net/cs/azbyclub/qanavi/jsp/qacontents.jsp?PID=9810-8377)
  
  
# リアルタイム通信アプリ
ポイントクラウドを使用したリアルタイム通信に興味がある場合は、以下のアプリを試してみてください。  
注意：
セキュリティが厳しい環境で通信が妨げられる場合は、テザリングなどの代替手段を検討してください。  
[https://github.com/HoloTuberKit/HoloTuberKit-RealTime](https://github.com/HoloTuberKit/HoloTuberKit-RealTime)
