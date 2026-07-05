# Sympa! Globe — 地球科学教材ビューア / Earth-science teaching globe

ブラウザだけで動く単一 HTML の地球科学教材ビューアです。プレートテクトニクス（プレート境界・復元モデル）、地震・火山分布、海洋底年代などを 3D 地球儀と地図で観察できます。

**使い方**: https://ut-globalseismology.github.io/sympa-globe/ を開くだけ（初回は約 31 MB の読み込みがあります）。オフライン利用はこのページを「名前を付けて保存」でも可能です。

プレート復元モデルのうち Merdith2021 は同梱済み（オフラインでも利用可）。Matthews2016 / Cao2024 は `map plate-model` で選択した時にオンデマンド取得します（要ネット接続。`plate-*.json` が実体）。オフライン保存版では Merdith2021 をご利用ください。

A single-file HTML viewer for Earth-science teaching: plate tectonics (boundaries and reconstruction models), seismicity, volcanoes, seafloor age and more, on an interactive globe and maps.

## License

GPL-3.0 — see `LICENSE`. This build bundles
[anisotime-js](https://github.com/UT-GlobalSeismology/anisotime-js) (GPL-3.0).
Data sources and citations: see `CREDITS.md` and the in-app `refs` command.

The Sympa! Globe build is generated from the Sympa! source tree
(publication in preparation; source available on request).

## Credits

UT Global Seismology Group, The University of Tokyo.

## 更新手順（メンテナ向け）

1. shinpa リポで `npm run build:globe`（= `node build.js --globe`）
2. `dist/sympa-globe.html` → 本リポ `index.html` にコピー
3. `dist/plate-matthews2016.json` / `plate-matthews2016-topology.json` / `plate-cao2024.json` / `plate-cao2024-topology.json` の4本も本リポ直下にコピー（**index.html と lazy JSON は必ず同時に更新**。片方だけだと版不整合）
4. マニュアル更新時は `dist/sympa-globe-manual.html` もコピー
5. commit → push（Pages が自動デプロイ。スタック時は `gh api -X POST repos/UT-GlobalSeismology/sympa-globe/pages/builds`）
