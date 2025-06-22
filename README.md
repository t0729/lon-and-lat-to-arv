# 経度と緯度を表層地盤増幅率に変換する
AIに生成してもらったコードです。
同じディレクトリにlon.txtとlat.txtをZ-V4-JAPAN-AMP-VS400_M250.csvが必要です。
## lat.txt
調べたい緯度を一行ずつ入れます。
## lon.txt
調べたい経度を一行ずつ入れます。
緯度と同じ数入れてください。
## Z-V4-JAPAN-AMP-VS400_M250.csv
[ここ](https://www.j-shis.bosai.go.jp/map/JSHIS2/download.html?lang=jp)の地盤情報→表層地盤からダウンロードします。
フォーマットはcsvでデータ範囲は全国一括です。
## output_arv.csv
出力先です。
すでにファイルがある場合は上書きされます。
