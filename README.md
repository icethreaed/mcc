# Minecraft Command Controller
コマンドの入力補助ツール。

---
## 概要
GUI上でコマンドの実行が行える。

## 特徴
簡単なマウス操作でコマンド入力を代行してくれる。  
サーバー運用を想定し、一部プラグインのコマンドなどにも対応。

## 動作環境
.NET Framework 4.5.2 がインストールされている  
WIN32 API を利用できる環境 (主にWindows)

## インストール
zipを解凍し、mcc.exeを起動するだけで利用可能。

## アンインストール
解凍したファイルごと削除する。

## 開発環境
Windows 7 Pro 64bit  
Visual Studio 2015  
C#言語にて開発  
外部ライブラリはnugetから自動取得するようにしています。オプション設定にてパッケージ復元が許可されている状態であることを確認してください。

## ビルドとデプロイ
1. Visual Studio からリリースビルドを行う。
2. 生成されたexeファイルと同階層に「lib」フォルダを作成し、dllファイルは全てそこへ置く。

## ライセンス
改造可  
2次配布可  
報告不要

## 開発者
名前：氷緒(ひお)  
Minecraft ID：icethread  
