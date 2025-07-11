<h1 align="center">UniVerse Kit</h1>

[![license](https://img.shields.io/badge/LICENSE-MIT-green.svg)](LICENSE.md)

# 概要

Unityで汎用的に使えるモジュール群です。

以下のパッケージから構成されています。

### UniVerse Core
サービスロケータやステートマシンの機能、MVPパターンのインターフェースを提供
※UniTaskに依存

### UniVerse ViwSystem

セーフエリアの対応するためのコンポーネント、2層のViewのレイヤー管理システムを提供
※UniVerse Coreに依存

### UniVerse Component Ex

Addressables, PlayableAPI, UGUI, の拡張機能を提供
※ UniTask, R3に依存

### AudioAnker

Unityのオーディオ機能を提供

# インストール
※ 各パッケージは依存しているパッケージをインストール済みしていることが前提

### UniVerse Kit のインストール
1. PackageManager > Install package from git URL...
```
https://github.com/chinpanGX/UniVerseKit.git?path=UniVerseUnityProject/Assets/UniVerse
```

> [!TIP]
> Core, ViewSystem, ComponentExを単体でインストールすることも可能です。
> 
> `https://github.com/chinpanGX/UniVerseKit.git?path=UniVerseUnityProject/Assets/UniVerse/Core`
> 
> `https://github.com/chinpanGX/UniVerseKit.git?path=UniVerseUnityProject/Assets/UniVerse/ViewSystem`
> 
> `https://github.com/chinpanGX/UniVerseKit.git?path=UniVerseUnityProject/Assets/UniVerse/ComponentEx`

### AudioAnker のインストール
1. PackageManager > Install package from git URL...
```
https://github.com/chinpanGX/UniVerseKit.git?path=UniVerseUnityProject/Assets/AudioAnker
```

# ライセンス
本ソフトウェアはMITライセンスで公開しています。

https://github.com/chinpanGX/UniVerseKit/blob/main/LICENSE
