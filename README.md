# toyohashi plateauビューアcesium

**公開URL： https://toyohashi-plateau-viewer-cesium.pages.dev/**

PLATEAU（国土交通省）3D都市モデル 豊橋市（2024年度）の公式3D Tilesを使い、豊橋駅前をCesiumで俯瞰表示するビューアです。

- 既定表示：LOD1、建物を用途別に色分け（凡例あり）
- 切替：LOD1 / LOD2軽量（テクスチャなし）/ LOD2テクスチャ付き
- 建物の接地補正済み（楕円体高と標高・ジオイドの差 約47.5mを補正）
- 建物タップで属性表示、自動回転、視点リセット

出典：PLATEAU 豊橋市（2024年度）・G空間情報センター、地理院タイル
配信：Cloudflare Pages（このリポジトリへのpushで自動デプロイ）
