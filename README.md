# GitHub 練習用リポジトリ

## 概要
GitHubに慣れるための学習用リポジトリです。
基本的に自由に好き勝手に使っていいです。

## GitHubの導入
1. Git for Windowsをインストールする(Macはすでにインストール済みなので不要）
	- ターミナルでGitHubを扱うために必要なもの
	- 以下のサイトの手順に従ってGit for Windowsをインストールする（「環境設定」はやらなくてもできた）
	- [いまさらGit for Windowsのインストール、GitHubに接続してみた。](https://qiita.com/manabu-watanabe/items/ecf1b434baf305adaa00)
2. GitHubの使い方（リポジトリ作成とコミット、プッシュ）
	- まずは個人ページでリポジトリを作り試してみる
	- 一通り試せたらこのリポジトリにもファイルを上げてみる
	- [【GitHub超初心者入門】この前初めてGitHubを使い始めたエンジニア見習いが書くGitHubの使い方と実践～とりあえず一緒に動かしてみようぜ！～](	 https://qiita.com/nnahito/items/565f8755e70c51532459)	
3. GitHubの使い方（プル、クローン）
	- [git pull コマンドの使い方と、主要オプションまとめ](http://www-creators.com/archives/2295)
	- [git cloneで環境構築！ リポジトリをクローンしよう](https://www.sejuku.net/blog/71436)
4. GitHubの使い方（リポジトリの中にディレクトリを作成する）
	- [GitHubでディレクトリ作成](http://maeokaka.hatenablog.jp/entry/2016/07/07/001441)  
5. GitHubの使い方（プルリクエストとマージ）  
	- 試験用プログラムや本番用プログラムは複数人が同じコードを同時に編集することになります  
	- 競合が発生しないようにプルリクエスを使ってプログラムを更新します
	- 流れとしては   
		- branchの作成  
		- 作成したbranchにcheckout  
		- コードの編集 
		- add, commit, pushする、pushするのはmasterではなく新しく作成したbranch
		- remote上でpullrequestを出す  
		- Slackでpullrequestを出したことをつぶやく  
		- Slackで返信されるまで待つ(本橋がReviewする）  
		- Reviewした結果、問題なければmasterにmergeされたことを確認する  
		- Reviewした結果、修正点があればコードの編集に戻る
	- [初心者がGitを使った複数人での開発をする時の流れ](https://qiita.com/risagon/items/0cd3592b08ee058ffb80)
	- [プルリクエストとは？](https://backlog.com/ja/git-tutorial/pull-request/01/)  

## GitHubを使う上でダウンロードしておいたほうがいいもの
- GitHub Desktop
	- ファイルの操作をGUI上でできる
- Atom
	- エディタ
	- GitHub Desktopから直接開ける
	- C系の作業もAtomで完結する
	- IDEの外部エディタとして使っていいかも

## 参考ページ
- [Gitの使い方　～リポジトリの作成とコミット～](http://proengineer.internous.co.jp/content/columnfeature/6944)
- [Gitの基本 - Gitリポジトリの取得](https://git-scm.com/book/ja/v1/Git-%E3%81%AE%E5%9F%BA%E6%9C%AC-Git-%E3%83%AA%E3%83%9D%E3%82%B8%E3%83%88%E3%83%AA%E3%81%AE%E5%8F%96%E5%BE%97)

## トラブルシューティング
- [Gitのリモートブランチを削除するまとめ](https://qiita.com/yuu_ta/items/519ea47ac2c1ded032d9)
- [Git、削除したファイルがstageに上手く上がらない時](http://chroma.hatenablog.com/entry/2013/10/18/111052)
- [【git】 git pushがrejectされたときの対応方法](https://www.softel.co.jp/blogs/tech/archives/3569)
- [git remote addを取り消す方法](https://qiita.com/ngtkk/items/05097d127db6a415a7d8)
- [Gitリポジトリからファイルを削除したい](https://www-he.scphys.kyoto-u.ac.jp/member/shotakaha/dokuwiki/doku.php?id=toolbox:git:rm:start)
- [Git で不要になったローカルブランチ・リモートブランチを削除する方法](https://qiita.com/iorionda/items/c7e0aca399371068a9b8)
