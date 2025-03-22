⚠️ これは **非公式** プロジェクトであり、**LM Studio によって承認または支持されているわけではありません**。

またこれは更に**非公式**のフォークであり**フォーク元のYorkie氏に承認又は支持されているわけではありません**。

⚠️ This is **an unofficial project** and is not endorsed or supported by LM Studio.
Furthermore, this is an unofficial fork and is not endorsed or supported by the original forker, Yorkie.


# LM Studio チャット WebUI（非公式）

これは、LM Studio サーバーと対話するためのシンプルなブラウザベースのチャットインターフェースです。ローカルにホストされた LM Studio モデルに接続し、任意のデバイスからチャットすることができます。

## 特徴

- ダークモードインターフェース
- 任意の LM Studio サーバーに接続可能
- LM Studio モデルとのチャット
- 各メッセージのトークン使用量と応答時間の表示
- LaTeX 数式レンダリングと Markdown レンダリング
- モバイルフレンドリーなデザイン
- 新しいパープルテーマ **NEW**
- チャット機能 **NEW**
- ビジョンモデルサポート **NEW**
- モデルの選択 **NEW**
- チャットの削除 **NEW**

## スクリーンショット 📸
![image](https://github.com/user-attachments/assets/7944a30a-6e52-467b-bf27-309f8db0bfde)
![image](https://github.com/user-attachments/assets/cecc2e50-1583-4ce6-a092-10adcb2359f3)
![image](https://github.com/user-attachments/assets/717bb8c6-ff62-4574-95e4-146909302180)
![image](https://github.com/user-attachments/assets/22275a46-f332-4ab9-b727-678a98aef7af)
![image](https://github.com/user-attachments/assets/d7cba468-166b-4d74-a98a-37ca72093b83)

## セットアップ手順

### デスクトップユーザー向け

1. このリポジトリから `lmstudiowebui.html` ファイルをダウンロードします。
2. コンピュータのアクセスしやすい場所に保存します。

### モバイルユーザー向け
これは Android デバイスでそのまま動作します。iOS では Microsoft Edge または他のブラウザでファイルを開く必要があります。Safari/Chrome は動作しません。
以下の方法で `lmstudiowebui.html` ファイルをモバイルデバイスに取得できます：

1. **直接ダウンロード**：
   - モバイルデバイスのウェブブラウザでこのリポジトリを開きます。
   - `lmstudiowebui.html` ファイルを見つけて直接デバイスにダウンロードします。

2. **自分にメール**：
   - コンピュータで `lmstudiowebui.html` ファイルをダウンロードします。
   - 添付ファイルとして自分にメールします。
   - モバイルデバイスでメールを開き、添付ファイルをダウンロードします。

3. **クラウドストレージ**：
   - `lmstudiowebui.html` ファイルを Google ドライブ、Dropbox、iCloud などのクラウドストレージサービスにアップロードします。
   - それぞれのクラウドストレージアプリを使用してモバイルデバイスからファイルにアクセスします。

4. **ファイル転送アプリ**：
   - AirDrop（iOS デバイス用）や近くの共有（Android デバイス用）などのアプリを使用して、コンピュータからモバイルデバイスにファイルを転送します。

## 使用手順

1. **LM Studio サーバーを起動**：
   - コンピュータで LM Studio を開きます。
   - 「サーバー」タブに移動します（0.3.x -> 開発者 -> ローカルサーバー）。
   - CORS が有効でローカルネットワークでの提供が有効であることを確認します。
   - 「サーバーを開始」をクリックし、サーバーアドレスをメモします。

2. **チャットインターフェースを開く**：
   - デスクトップでは：`lmstudiowebui.html` ファイルをダブルクリックしてデフォルトのウェブブラウザで開きます。
   - モバイルでは：ファイルマネージャーアプリを使用してダウンロードした `lmstudiowebui.html` ファイルを見つけ、ウェブブラウザで開きます。

3. **LM Studio サーバーに接続**：
   - チャットインターフェースの上部にある入力フィールドに LM Studio サーバーアドレスを入力します。
   - 「接続」ボタンをクリックします。

4. **チャットを開始**：
   - 接続が完了したら、画面下部の入力フィールドにメッセージを入力して送信します。
   - Enter キーを押すか、送信をタップしてメッセージを送信します。
   - モデルの応答がチャットウィンドウに表示されます。

## トラブルシューティング

- **サーバーに接続できない**：
  - LM Studio サーバーがコンピュータで稼働していることを確認します。
  - 正しいサーバーアドレスを使用していることを確認します。
  - 別のデバイスからアクセスする場合、両方のデバイスが同じネットワークに接続されていることを確認します。

- **応答が遅い**：
  - LM Studio の処理速度はコンピュータの性能に依存します。大きなモデルは応答に時間がかかることがあります。

- **インターフェースが読み込まれない**：
  - `lmstudiowebui.html` ファイルを別のウェブブラウザで開いてみてください。

## セキュリティに関する注意

このインターフェースはローカル使用のみを目的としています。適切なセキュリティ対策を講じずに LM Studio サーバーを公開インターネットに公開しないでください。

## フィードバックと貢献

問題が発生した場合や改善の提案がある場合は、このリポジトリに issue を作成してください。プルリクエストによる貢献も歓迎します！

## スター履歴

[![Star History Chart](https://api.star-history.com/svg?repos=YorkieDev/LMStudioWebUI&type=Date)](https://star-history.com/#YorkieDev/LMStudioWebUI&Date)
