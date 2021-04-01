# tiny-compiler-env

植山 類さんによる[低レイヤを知りたい人のためのCコンパイラ作成入門](https://www.sigbus.info/compilerbook)を<br>
macOS上で学習するための仮想Linux環境です。

Makefileにてエイリアスコマンドを追加しているので多少コマンドを入力するのが楽という程度です。

イメージをビルドする際は
```bash
$ make build
```

コンテナを起動する際は
```bash
$ make boot
```

で実行が可能です。

また、コンテナ起動の際はプロジェクトのルートディレクトリに存在するsrcディレクトリを<br>
コンテナ内部の/home/user/srcにbindするように設定してあります
