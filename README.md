

# practice-front-end2019

## このリポジトリについて

- このリポジトリはこれからWebサイトのフロントエンド開発を学ぶ人のためのカリキュラムです。
- このリポジトリをご自身のGithubアカウントにfolkして、<a href="https://github.com/es335ab/practice-front-end/blob/master/COURSE.md">COURSE.md</a>に沿ってご自身のリポジトリで勉強を進めてください。
- このカリキュラムを終えればモダンなWebサイトのフロントエンド開発ができるようになります。（複雑なWebアプリケーションの開発は対象外

## カリキュラムをすすめるのに必要なもの

- Mac
- Homebrew（Mac用のパッケージ管理ツール）
- Xcode（MacのIDE）
- Git（ソースコードのバージョン管理ツール）
- Githubのアカウント
- ruby 2.3.7
 - <a href="http://dev.classmethod.jp/server-side/language/build-ruby-environment-by-rbenv/">ruby 2.3.7 を入れるための参考ページ</a>
- bundler（GemというRubyのパッケージ管理ツールにて、gem install bundler とする）
- Chrome（ブラウザ）
- エディタ（Sublime textなど）

## このリポジトリの動かし方

- 前項の必要なものをパソコンに入れておく
- ローカル環境に`git clone`した上で下記のコマンドをターミナルに打ち込む

```
$ bundle install --path vendor/bundle
```

- MiddlemanのWebサーバーを起動させるために下記のコマンドを打ち込む

```
$ bundle exec middleman s
```

- `http://localhost:4567/`にブラウザでアクセスする


## このカリキュラムで学べる技術領域

- HTML5
 - 情報設計の理解
 - haml
- CSS3
 - scss
 - OOCSS
 - SMACSS
- JavaScript
 - jquery
