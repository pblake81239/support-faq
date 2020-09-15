
ウォレットとは何かを理解したところで、使用できるウォレットのタイプを見てみましょう。特定のタイプのウォレットを探すには、以下のように進んでください。

エンドユーザーの観点から要約すると、主に2種類のウォレットインターフェイスがあります。:

### ソフトウェア（ホット）ウォレット

ソフトウェアウォレットは、使用するデバイスに暗号化キー（暗号化）が保存されるデジタルウォレットインターフェイスです。ソフトウェアウォレットには、主に次の2種類のウォレットがあります。

<!-- tabs:start -->

#### ** フルノードウォレット **

例: Daedalus

フルノードウォレットは完全に独立したブロックチェーンノードを実行し、ウォレットを操作する機能を提供します。そのようなウォレットの例はダイダロスです。このようなノードを実行する利点はいくつかあります。
 -必要に応じて要求を実行できるように、ブロックチェーン履歴全体がノードでローカルに利用できます。
 -ノードは、ブロックが作成されてデバイスに同期されるときにすべてのブロックを検証します。これにより、ウォレットでの操作に必要な信頼性が低下します。
 -完全なノードを実行する-また、その地域でのブロックチェーンの可用性を高め、ブロック作成ノードのレイテンシを改善します。
 -ノードレベルでサポートされているがウォレットUIではまだサポートされていない機能がある場合-ノードに直接接続して機能にアクセスできます。

これらの利点に加えて、ノードを実行すると、自動的にいくつかの責任が発生します。これは、エンドユーザーの観点からは快適でない可能性があります。
 -デバイスのブロックチェーン全体を同期するには、最初のセットアップ時に時間が必要です。これは、デバイスのネットワークとディスクのスループットによっては数時間かかる場合があります。
 -フルノードに接続されたウォレットを実行するために必要なストレージ、メモリ、およびネットワークの制約があります。
 -フルノードウォレットは、携帯可能なデバイスには理想的とは見なされない場合があります。
 
#### ** ライトウォレット **

Example: Yoroi, ADALite

ライトウォレットは、操作のためにリモートノードに接続するインターフェースを使用します-したがって、完全なブロックチェーンノードを操作する責任から解放されます。ブラウザプラグイン/拡張機能、ウェブサイト、またはモバイルアプリとして利用できる場合があります。
ライトウォレットを使用する利点：
-ウォレットを介してすでに実行中の最新のノードに接続するため、ブロックチェーン全体がデバイスで同期されて操作の実行を開始するのを待つ必要はありません。
-あなたは自分のキーの制御を維持します。軽い財布の一般的な誤解は、キーがネットワーク経由で送信されるため安全ではないということです。ほとんどのプロフェッショナルライトウォレットでは、キーがデバイスから出ることはなく、デバイス上でも常に暗号化された状態になります。これまでのところ、これは完全なノードウォレットとライトウォレットのどちらを選択するかを区別するものではなく、どちらもデバイスと同じくらい安全です。
-サーバー側でブロックチェーンノードのアップグレードを実行できるため、ブロックチェーンノードのアップグレードについて心配する必要はありません。
-軽い財布は、ポータブル/ハンドルデバイスに簡単に統合できます。
-通常、非常に軽量で、高いストレージ/メモリや安定したネットワーク要件はありません。

比較に関する公式リンクについては、IOHKの[このサポート記事]（https://iohk.zendesk.com/hc/en-us/articles/360026058573-Daedalus-wallet-compared-to-Yoroi-wallet）にアクセスしてください。

<!-- tabs:end -->

### ペーパー（コールド）ウォレット

ペーパーウォレットは基本的にソフトウェアインターフェースによって作成されるウォレットですが、それらのペーパーウォレットのキーがオンラインになることはありません。 これらは通常、2つの部分でシードを提供します-紙に印刷された部分と、他の部分には単語（ダイダロスの場合）またはパスワード（ヨロイの場合）です。これで誰かがペーパーにアクセスしたとしても、 あなたのキーにアクセスできません。 
覚えておくべきポイント：
-ペーパーウォレットを作成するソフトウェアは、生成されたウォレットに資金を送金しません。手動で行う必要があります。
-なんらかの理由で紙のウォレットを復元することにした場合、そのウォレットはオンラインのデジタルデバイスに復元されているため、「コールド」ウォレットではなくなります。 したがって、その場合は、セキュリティの観点から新しいペーパーウォレットを作成するのが最善です。

### ハードウェア（コールド）ウォレット

ハードウェアウォレットとヨロイの連携の概要については、Emurgoの[この]（https://emurgo.io/en/blog/hardware-wallet-explanation-yoroi-keep-ada-safe）ブログをご覧ください。