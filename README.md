# Goの初学習用レポ

Goの初学者のための学習レポジトリです。ご自由にどうぞ、、、

## やること

1. `mise settings experimental=true`で`go install`を使えるようにする。
2. `mise i`で必要ツールを取得し、.zshrcに以下を記載。
    ```zsh
    export GOPATH=$HOME/go
    export PATH=$PATH:$GOPATH/bin
    export GOROOT="$HOME/.local/share/mise/installs/go"
    export PATH="$GOROOT/bin:$PATH"
    export GOSUMDB=sum.golang.org

    export PATH=$PATH:~/.local/bin
    eval "$(mise activate zsh)"
    export PATH="$HOME/.local/share/mise/shims:$PATH"
    ```
3. Goのプロジェクトを準備
    1. `go mod init ~~`で使用する環境を用意する。（以下ファイルが生成される）
        - go.mod
    2. `go mod tidy`で諸々の初期化
4. Goの基本理念について（宗教チック）
    1. コンパイル言語とインタープリタ言語について
    2. Goという言語とは
5. バックエンドについて
    1. DBとは
    2. コンテナとは
6. 基本文法と基本機能
    1. 標準出力とファイルに記載されている内容について
    2. 型と定数・変数
    3. 関数
    4. 構造体とメソッド
    5. 条件分岐
    6. ループ処理
    7. インターフェース
    8. ディレクトリとパッケージ
    9. Goコマンドについて
    10. （GoRoutine）

