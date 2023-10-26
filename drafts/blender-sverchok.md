# Blender + Sverchok Addon

- ノードグラフのみをJSONとしてエクスポートできる
    - Geometry Nodesは4.0（2023年10月時点ではbeta）以降でNode Toolsという機能でアセットとしてエクスポートできるようになりそう（ https://code.blender.org/2023/10/node-tools/#Tools-specific-Nodes ）
- 組み込みノードの種類、アルゴリズムが豊富
    - Geometry Nodesが（Blender組み込みとしての）汎用性を重視したものを優先しているのに対し、建築系やパラメトリックデザインに 振り切った機能が多い。
        - 言い換えると機能が多い・専門的過ぎてとっつきにくいというデメリットになり得る
- どうやら簡単なPythonスクリプトをノードグラフの一部として直接書ける。
    - Geometry Nodesの場合BlenderのAPI経由で扱うことになるので、若干導入までの敷居が高い。
- サンプルが付属している。

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

