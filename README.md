# mojo🔥

mojoがローカルで使えるようになったので触ってみた．
以下，忘れないようにメモっとく．

## mojo🔥とは

Mojoは，Python構文の長所をシステムプログラミングとメタプログラミングと組み合わせることで，研究と生産のギャップを埋める新しいプログラミング言語である．
Mojoを使えば，Cよりも高速で，Pythonエコシステムとシームレスに相互運用できる移植性の高いコードを書くことができる．

<https://docs.modular.com/mojo/>


## 環境構築

基本的に，mojoが公式で提供している情報通りに進めると使えた．

1. VScode，WSL，mojoのインストール
2. Ubuntu22.04 for WSLをインストール
3. Ubuntuのターミナルで，配布されたModulr CLIを実行
4. Mojo SDKをインストール

後は，VScode上でWSLに切り替えたら使える．

## Hello World!

hello.mojo というファイルを作成．

    print("Hello, world!")

VScodeのターミナルで以下を実行．

    mojo hello.mojo

出力．

    Hello, world!
