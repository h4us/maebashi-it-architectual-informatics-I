# Blender + Sverchok Addon

## Pros / Cons

- ノードグラフのみをJSONとしてエクスポートできる
    - Geometry Nodesは4.0（2023年10月時点ではbeta）以降でNode Toolsという機能でアセットとしてエクスポートできるようになりそう（ https://code.blender.org/2023/10/node-tools/#Tools-specific-Nodes ）
- 組み込みノードの種類、アルゴリズムが豊富
    - Geometry Nodesが（Blender組み込みとしての）汎用性を重視したものを優先しているのに対し、建築系やパラメトリックデザインに 振り切った機能が多い。
        - 言い換えると機能が多い・専門的過ぎてとっつきにくいというデメリットになり得る
- どうやら簡単なPythonスクリプトをノードグラフの一部として直接書ける。
    - Geometry Nodesの場合BlenderのAPI経由で扱うことになるので、若干導入までの敷居が高い。
- サンプルが付属している。

オフィシャルのステートメントとしては以下

https://nortikin.github.io/sverchok/


## 参考資料

- ソースコード

https://github.com/nortikin/sverchok

- ドキュメント

https://nortikin.github.io/sverchok/docs/main.html

本当に授業で使うなら日本語訳検討するか...？

### 動画チュートリアル

2020年前後に作成されたものが多く、若干情報古めの場合あり。

- https://www.youtube.com/playlist?list=PLIKEZ9RntI996BjsohqqL_mI3uamzUEMi
    - オフィシャル？
- https://www.youtube.com/watch?v=H_CG7CVmjog&list=PLVm7O9OzjT6Gacl6Ag1JAySU2tXMUGGMp
    - 他にもBlender全般に取り上げている
- https://www.youtube.com/@vkter5437/videos
    - Sverchokのコミッター
- https://www.youtube.com/@ken26u95/videos
    - チャンネル。貴重な日本語での解説

### 解説記事など

TBA

### その他

- https://www.instagram.com/sverchok.3d/
    Instagram。作例などが載ってる

## 基本的な使い方

<img src="../assets/fig3.webp" width="1200px">

基本は Geometry Nodes の画面構成と同じ

..More details TBA

## Docs 抄訳・解説

https://nortikin.github.io/sverchok/docs/main.html

### User Interfacee

TBA

### Node evealuation system

TBA

### Data structrue

#### Introduction to geometry

- List, Index, Vector, Vertex, Edge, Polygon, Normal, Transformation, and Matrix.

#### Solid

- Blender にも一応「Solid化」するモディファイアはあるが、SverchokでSolidを扱う場合は[FreeCAD](https://www.freecad.org/index.php?lang=ja)経由で処理させる模様。別でインストールが必要。
- Brep モデリング、Solid？

    https://blog.spatial.com/ja/brep%E3%83%A2%E3%83%87%E3%83%AA%E3%83%B3%E3%82%B0%E3%81%AE%E4%B8%BB%E3%81%AA%E3%83%A1%E3%83%AA%E3%83%83%E3%83%88%E3%81%A8%E3%83%87%E3%83%A1%E3%83%AA%E3%83%83%E3%83%88

..More details TBA

### Nodes

TBA


## サンプルを読んでみる・パラメーター変更やノードの追加・削除・変更を試してみる

### Advanced

#### Candy

#### Circle fitting physics

#### Genetic algorithm scripted node

- GPU依存？あり

#### Genetic algorithm simple

#### Grain

#### Petri Spiral Voronoi

#### Pineapple.zip

#### PointsONmeshINlines

#### Strip spools tension

### Architecture

TBA

### CNC

TBA

### Design

TBA

### Fields

TBA

- scipy 依存あり

### Introduction

#### ABCnaming

#### Adaptive Spread

#### BenTorus

#### Circle Generator

#### Donut by hands

#### Interpolations

#### List multymasking

#### Orientation matrix track to

#### Polor coordinates curve

#### Voronoi Trick

### Shapes

TBA

### Surface

TBA

- いくつかエラーあり