# コマンドプロンプト / Powershell 恐怖症のかたへ


## これだけ知っておこうコマンドプロンプト

基本、コマンドプロンプトでよく使う内部コマンドはこれだけです。

 * dir - 
 * cd
 * rd
 * md
 * copy - ファイルの複写
 * del - ファイルの削除
 * path

このうち危険なコマンドは copy と del です。非可逆的なファイルの破壊を防ぐために使い方をよく確認しましょう。


この段階で外部コマンドやバッチファイルなどを説明し始めると、混乱するでしょうから必要になったらでいいと思います。


== 参考文献
 * [cmd | Microsoft Learn](https://learn.microsoft.com/ja-jp/windows-server/administration/windows-commands/cmd)
