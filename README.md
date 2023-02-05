# PythonでExcelを弄るチュートリアル環境

<br>↓書籍『Pythonでかなえる Excel作業効率化』<br><br>
https://www.amazon.co.jp/Python%E3%81%A7%E3%81%8B%E3%81%AA%E3%81%88%E3%82%8B-Excel%E4%BD%9C%E6%A5%AD%E5%8A%B9%E7%8E%87%E5%8C%96-%E5%8C%97%E9%87%8E-%E5%8B%9D%E4%B9%85/dp/429711450X/ref=sr_1_1?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&crid=8W4ISI9NL3WQ&keywords=python%E3%81%A7%E3%81%8B%E3%81%AA%E3%81%88%E3%82%8B+excel&qid=1675604806&sprefix=python%E3%81%A7%E3%81%8B%E3%81%AA%E3%81%88%E3%82%8B+excel%2Caps%2C178&sr=8-1
<br><br>
pycharmとanacondaを使用
<br>

```
pycharmのインストール（Win）
https://www.jetbrains.com/ja-jp/pycharm/download/#section=windows

anacondaのインストール
https://www.anaconda.com/products/distribution
```

## pycharmでanacondaを使うプロジェクトの立ち上げ方
新規にプロジェクトを立ち上げる際は、このやり方でプロジェクトを作成しないとanacondaと連結できません。

```
１，pyCharmを起動して新規プロジェクトを立ち上げ
　ファイル　→　新規プロジェクト
   （この時、事前にDドライブにdirectoryを作成する必要はなし。pyCharm側で作ってくれる）
   「場所」のところに任意のディレクトリ名を入れること
 
２，「次を使用して新規環境を作成」でanacondaを選択

３、「main.py ウェルカムスクリプトの作成」をオフにする

４，「作成」をクリックするとプロジェクトが立ち上がる
```
