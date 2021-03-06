## Webサーバとは
ハードウェアの観点ではwebサーバソフトウェアとwebサイトのコンポーネントファイルを格納しているコンピュータのこと。  
ソフトウェアの観点では、ホストにあるファイルに対する、webユーザのアクセスを制御する、いくつかの部品の集まり。  
最小限の部品はHTTPサーバ。HTTPサーバはURL(webアドレス)及びHTTP(ブラウザーがWebページを閲覧するためのプロトコル)を理解するソフトウェアのこと。格納しているwebサイトのドメイン名を通してアクセスすることができ、コンテンツをエンドユーザの端末に配信する。  
  
最も基本的な水準では、ブラウザーはWebサーバが保持しているファイルが必要になったらいつでも、HTTPでファイルをリクエストする。リクエストが正しいWebサーバ(ハードウェア)に届くと、HTTPサーバ(ソフトウェア)がリクエストを受付、リクエストされた文書を探し(ない場合は404レスポンスが返される)、
ブラウザーにHTTPを通して送り返す。  
  
webサイトを公開するには、静的または動的サーバが必要です。

静的Webサーバはスタックとも呼ばれますが、コンピュータ(ハードウェア)とHTTPサーバ'ソフトウェア)から構成されます。サーバが保持しているファイルをブラウザーへ「そのまま」送るので、「静的」と呼ばれます。

動的Webサーバは静的Webサーバと追加のソフトウェアからなります。追加ソフトウェアは、一般的にはアプリケーションサーバとデータベースからなります。アプリケーションサーバが、保持しているファイルを変更してから、HTTPサーバを通してブラウザーに送信するので「動的」と呼ぶ。  

例えば、ブラウザーで見ることができる最終的なWebページを生成するために、アプリケーションサーバはデータベースからのコンテンツでHTMLのテンプレートを埋めることがあります。
MDNやウィキペディアのようなサイトは非常に多くのWebページを持っていますが、実際のHTML文章が存在するわけではなく、巨大なデータベースと僅かなHTMLテンプレートのみが損さ剤しているのです。この構成を取ることで、より早く、よりかんたんにコンテンツを保守したり配信したりすることができます。

