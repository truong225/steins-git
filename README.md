Steins;Git
===========

[![Build Status](https://travis-ci.org/o2project/steins-git.svg?branch=master)](https://travis-ci.org/o2project/steins-git) [![Gitter chat](https://badges.gitter.im/o2project/steins-git.png)](https://gitter.im/o2project/steins-git)

C86(日曜日 西地区"な"ブロック-11b)にて頒布予定の、GitをSteins;Gateを使って説明する薄い本です。

http://o2project.github.io/steins-git より見ることができます。

## ローカルで確認する

各種パッケージのインストールやローカルでの確認をおこないたい場合は、以下のコマンドを上から順に実行してください。

事前にNode.jsと、rvmやrbenvを利用してRubyがインストールされている想定です。

```
git clone https://github.com/o2project/steins-git.git steins-git
cd steins-git
./bin/setup.sh
grunt server
```

## 貢献したい

[![Gitter chat](https://badges.gitter.im/o2project/steins-git.png)](https://gitter.im/o2project/steins-git) に意見などどうぞ。

[CONTRIBUTING.md](CONTRIBUTING.md "CONTRIBUTING.md")も、ガイドラインなど書いてあるので参考にしてみてください。

1. リポジトリをフォークしましょう！
2. 新たなfeatureブランチを作ります: <code>git checkout -b my-new-feature</code>
3. 変更点をコミットします: `git commit -am 'ほげもげを追加'`
4. リモートにプッシュします: `git push origin my-new-feature`
5. pull requestしましょう :D

## ライセンス

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a>

文章と、独自に作成した図のライセンスについては、<a rel="license" href="http://creativecommons.org/licenses/by-nc/2.1/jp/">Creative Commons — 表示 - 非営利 2.1 日本 — CC BY-NC 2.1 JP</a>となっております。

クレジットは`(C) O2 Project`をお使いください。

Steins;Gateのゲームのスクリーンショットの著作権については、MAGES./5pb./Nitroplusに帰属します。
