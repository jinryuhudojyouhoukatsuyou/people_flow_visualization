
# 人流データ可視化ツール / MLIT People Flow Visualization Tool


「人流データ可視化ツール」（以下、本ツール）は国土交通省不動産・建設経済局情報推進課にて実施した 令和４年度人流データの可視化等検討調査業務 において試作開発したものです。
本ツールは人流データの利活用促進のために、これまで GISや BIツール等で人流データを取り扱ったことのないユーザーに向けて、人流データの活用に取り組むきっかけとなることを狙って試作開発したものです。このため、本ツールは人流データの可視化においてよく使われる表現に絞ってツールをパッケージ化し、できるだけ簡易に可視化できるようにしております。
### <BR>
The "MLIT People Flow Visualization Tool" was developed as a prototype in the 2022 People Flow Data Visualization Study conducted by the Information Promotion Division, Real Estate and Construction Economy Bureau, Ministry of Land, Infrastructure, Transport and Tourism.

This tool was developed as a prototype to promote the utilization of people flow data, aiming to provide an opportunity for users who have never handled people flow data with GIS or BI tools to start utilizing people flow data.

For this reason, we have packaged this tool by focusing on expressions that are often used in visualizing people flow data to make it as easy as possible to visualize.


# サンプル画像/ Sample images
<img width="500" src="./image/use001.png">
<img width="500" src="./image/use002.png">


# 動作環境/ System requirement
本ツールはQGIS 3.28にて動作確認をしております。
### <BR>
  This tool has been tested on QGIS 3.28.

# 利用方法/ How to use
利用方法については、[使い方](document/howtouse.pdf)をご確認ください。
### <BR>
Please refer to [how to use](document/howtouse.pdf) for details on how to use the tool.




# 利用ライブラリ等/ Use libraries
- 分析結果を表示する地図には[地理院タイル](https://www.gsi.go.jp/kikakuchousei/kikakuchousei40182.html)若しくは[CARTO basemap styles](https://github.com/CartoDB/basemap-styles)を利用しています。

- [世界メッシュコード関連関数](https://www.fttsus.org/worldgrids/ja/our_library/)
- 「このライブラリは科学技術振興機構（JST)さきがけ「グローバル・システムの持続可能性評価基盤に関する研究」 [JPMJPR1504](https://projectdb.jst.go.jp/grant/JST-PROJECT-15655008/)およびJST未来社会創造事業「自律分散的世界メッシュ統計基盤アーキテクチャの設計と実証」[JPMJMI20B6](https://projectdb.jst.go.jp/grant/JST-PROJECT-20336716/)の研究成果です。本ライブラリは一般社団法人世界メッシュ研究所から提供されています。」
- MapLibre(https://maplibre.org/)
- D3.js(https://d3js.org/)
- deck.gl(https://deck.gl/)
### <BR>
-  The maps displaying the analysis results are [Geographical Survey Institute tiles](https://www.gsi.go.jp/kikakuchousei/kikakuchousei40182.html) or [CARTO basemap styles](https://github.com/ CartoDB/basemap-styles).

- [World mesh code related functions](https://www.fttsus.org/worldgrids/ja/our_library/)
 
- 「This library is the result of the following two research projects. [JPMJPR1504](https://projectdb.jst.go.jp/grant/JST-PROJECT-15655008/)  and,  [JPMJMI20B6](https://projectdb.jst.go.jp/grant/JST-PROJECT-20336716/). This library is provided by the World Mesh Institute.」
- MapLibre(https://maplibre.org/)
- D3.js(https://d3js.org/)
- deck.gl(https://deck.gl/)





# ライセンス/ Licence
本ツールは GNU GENERAL PUBLIC LICENSE v2 ライセンスが設定されています。
[GNU GENERAL PUBLIC LICENSE Version 2, June 1991](https://www.gnu.org/licenses/old-licenses/gpl-2.0.txt)
### <BR>
This tool is licensed under the GNU GENERAL PUBLIC LICENSE v2 license.
[GNU GENERAL PUBLIC LICENSE Version 2, June 1991](https://www.gnu.org/licenses/old-licenses/gpl-2.0.txt)
