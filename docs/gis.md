# 地理空間データとは

地理空間データは、空間上の特定の地点または区域の位置を示す情報(位置情報)およびそれに関連付けられたさまざまな情報を持つデータです。次のような地理空間データがあります。

- 土地利用図(自然、災害、経済活動など)
- 地質図
- 主題図(ハザードマップなど)
- 都市計画図
- 地形図
- 統計情報
- 空中写真、衛星画像

## GIS(地理情報システム)

GIS は、Geographic Information System の略で、地理情報システムとも呼ばれます。地理的位置から空間データ(位置に関する情報を持ったデータ)を加工し、分析や判断をするための技術です。地理空間データを分析するうえでは、データを処理したり、可視化したりします。

## CRS(座標参照系)

CRS は Coordinate Reference System の略で、座標参照系とも呼ばれます。地球を平面上の位置に表現するためのルールです。座標参照系は大きく分けて「地理座標系」と「投影座標系」の 2種類があります。地理座標系は地球の重心付近を原点とした緯度経度と角度で位置を表現します。投影座標系は地球のある範囲を平面に投影し、ある原点からの距離を表現します。距離や面積を求める場合は投影座標系が使われます。


## EPSG コード

GISでは、座標系や測地系、投影法などさまざまな要素を組み合わせて利用します。SRID(Spatial Reference System Identifiers)は、これらの要素の集合体として識別するためのコード体系です。このコード体系の事実上の標準としてEPSGコード ※ 3 が使われています。たとえば、EPSG:4326というコードからは、測地系にWGS 84、座標参照系には地理座標系が使われていることが確認できます。

> Pythonデータ分析 実践ハンドブック
> 
> https://book.impress.co.jp/books/1122101021
> 
> p294. 10-1 地理空間データの概要