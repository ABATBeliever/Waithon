# Waithon
日本語にPythonを翻訳(という名の歪曲)したわいそんです。よろしくお願いします。

Waithon(わいそん)はCPython 3.11.3をベースに開発されています。

CPython 3.12.8及びその派生(Waithonを含むが、これに限定されない)には、PSF LICENSE がかけられており、Waithonプロジェクトとその派生もこれに従う義務があります。

PSF LICENSEについては、当リポジトリのLICENSEファイルのほかに、<a href="https://docs.python.org/ja/3.11/license.html">Python公式サイト</a>などでも確認できます。

最新バージョンは 1.0.3113.0 です。

# 入手方法
<h2>・<a href="https://github.com/ABATBeliever/Waithon/releases">ビルド済みイメージを入手</a></h2>

<h2>・自力でビルド</h2>

1:このリポジトリをダウンロードします

2:PCBuild\get_externals.batを実行し、依存関係を入手 [ライセンス上ここに含めないやつをフォルダに追加]

3: PCBuild\build.bat に引数 --regen を付けて実行   [CPythonから変更した設定をコミット]

4: PCBuild\build.bat を実行                       [ビルド]

5: PCBuild\arm64に作成されます
