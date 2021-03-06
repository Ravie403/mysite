# 導入

この文書はJavaScript言語のソースコードに関するGoogleのコーディングの基準となる**完全な**定義として機能します。JavaScriptのソースファイルはこの規約を守っている場合にのみ、*Googleのスタイル*であると言うことができます。

他のプログラミング言語のスタイルガイドのように、対象とするのはフォーマットの美しさだけでなく、他の規則やコーディングの基準にまで及びます。しかし、この文書は主に私たちが普遍的に従うルールに焦点を当てており、明確に強制できないような助言をすることは避けています。（それが人によるものであれツールによるものであれ。）

## 用語についての注意事項
この文書においては特に明記しない限り、

1. 「コメント」とは「実装においてのコメント」であり、「ドキュメントとしてのコメント」ではありません。代わりに「JSDoc」を人、機械の両方が読める注釈として`/**...*/`内に使用します。
2. このスタイルガイドでは*しなければならない*、*してはならない*、*すべき*、*すべきでない*、*してもよい*の言葉を使用する際に[RFC 2119](http://tools.ietf.org/html/rfc2119)を用いています。*するとよい*、*避ける*　はそれぞれ*すべき*、*すべきでない*に対応しています。命令文、宣言文は規範的であり、*しなければならない* に対応しています。

その他の「用語についての注意事項」は度々文書全体を通じて現れることがあります。

## ガイドラインについて

この文書内のサンプルコードは**模範となるようなものではありません。** すなわち、サンプルコードはGoogleのコードスタイルでも、綺麗なコーディングではない場合があります。サンプルコードのフォーマットに縛られないでください。