★概要

VR 学会 複合現実感研究会用の TeX スタイルファイルとそのサンプルを用いた、
Overleaf用のテンプレートです。

e-pTeX, Version 3.1415926-p3.3-110825-2.5 (sjis) (TeX Live 2012/W32TeX)
で動作を確認しています．以下のものが入っています。

	sigmr2e.sty      スタイルファイル(ver 1.0)です。
	guide.tex        sigmr2e.sty を用いたサンプルファイルです。
	zu.eps           サンプルファイルで使用する eps ファイルです。
	sig-mr_logo.eps  研究会ロゴマークの eps ファイルです。
	guide.pdf        サンプルファイルから作成されたpdfです。
	readme1st.txt    このファイルです。

このファイルの取り込みを行う場合には使っている環境に合わせて改行コ
ードと文字コード(UTF8)を変えてください。特に eps ファイルは文字コード
を正しくシステムに合わせないとエラーになりコンパイルできません。

---------------------------------------
★日本語を表示するには

Google Chromeで以下のプラグインをインストールし、次の3行のスクリプトを設定してください。

https://chrome.google.com/webstore/detail/scriptautorunner/gpgjofmpmjjopcogjgdldidobhmjmdbm

PDFJS.cMapUrl =
'https://crossorigin.me/https://github.com/mozilla/pdf.js/raw/master/external/bcmaps/';
PDFJS.cMapPacked = true;

（参考）
Overleaf で pLaTeX 使って日本語PDFをプレビューした話
http://3846masa.hatenablog.jp/entry/2016/02/15/003843

---------------------------------------
★変更履歴

2013.11.29 (by 清川)
論文誌サンプルファイルを元に初版を作成しました。

2016.09.05 (by 清川)
Overleaf用テンプレートを作成しました。
