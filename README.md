# recommend-restaurant
データを貯めてその結果を利用してレコメンドする機能をpythonで実装する練習のためのレポジトリです。<br>
This is a repository to practice implementing a recommendation function in python that stores data and uses the results to make recommendations.

アプリケーションはMVCモデルで作成しているので、ソフトウェアの基本設計も学ぶことができます。
The applications are created using the MVC model, so you can also learn basic software design.
<br></br>


## 起動 (activate)
レポジトリをクローンしたら、ローカル環境で以下のコマンドを入力。<br>
After cloning the repository, enter the following command in the local environment.

```
$ pip install termcolor==1.1.0
```

その後、main.pyをpythonで呼び出すと対話型でアプリが起動する。<br>
After that, call main.py in python to start the application interactively.

```
$ python main.py
```
<br>

## ランキングの確認(check ranking)
対話型によって記入したレストランの名前は、ranking.csvに保存されている。次のコマンドで確認可能。<br>
The names of the restaurants entered by the interactive are saved in "ranking.csv". You can check it with the following command.

```
cat ranking.csv
```
