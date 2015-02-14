## Python
### iPython notebook
#### Quick start
1. ターミナルを起動
2. ipython notebook --pylab inline
3. localhost:8888/treeへアクセス
 

#### gitからインストール(例：numpy)
```
git clone https://github.com/numpy/numpy.git
cd numpy
python setup.py build
sudo python setup.py install
```

./configure ソースファイルをコンパイルする前に、インストール対象となるシステム特有の機能 情報をチェックし、チェック状況を記述したMakefileを作成する。

configureに失敗する場合は、コンパイルに必要なライブラリ、 ヘッダファイル等が不足している事がほとんどなので、 エラーメッセージの内容を確認し、必要なパッケージを事前に インストールしておく。

make configureの実施により作成されたMakefileを元に、 以下のようにmakeコマンドを実行することで、ソースファイルのコンパイルを行う。 コンパイル時にエラーが表示されるようであれば、エラー内容を確認し、 configure実行時に必要なパラメータが不足していないか確認する。

make install make実行時にエラーが表示されなければコンパイル完了である （コンパイル途中に警告メッセージが表示される場合があるが、これは無視してもOK） コマンドでインストール (make で作成したファイルなどを任意のディレクトリにコピー)を行う。

#### 参考サイト
- [IPython notebookでブラウザ内にグラフを描画する](http://slowquery.hatenablog.com/entry/2013/04/01/010927)
- [IPython Notebook チュートリアル](http://qiita.com/payashim/items/d4fe5227b21a5215e78b)

#### 参考ブログ
- [人工知能に関する断創録](http://aidiary.hatenablog.com/)
- 
