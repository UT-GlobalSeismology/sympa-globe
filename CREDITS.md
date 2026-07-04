# データソースの出典・ライセンス / Data Credits

シンパ！（配布ビルド `npm run build:dist` / `--globe`）に**実際に同梱される**データソースの出典と
ライセンスです。ソフトウェア本体は GPL-3.0（`LICENSE`）ですが、各データは以下の各ライセンスに従います。
ライセンス方針の詳細と、初回公開で除外したデータは `docs/LICENSING.md` を参照してください。

アプリ内では `refs` コマンドでクリック可能な引用リンクを表示できます。

## 確認済み（明示ライセンス）

| データ | 用途 | ライセンス | 出典・帰属 |
|--------|------|-----------|-----------|
| Natural Earth（海岸線 50m/110m） | 海岸線 | Public Domain | naturalearthdata.com |
| Slab2 | 沈み込み帯形状 | Public Domain (USGS) | Hayes et al. (2018), doi:10.5066/F7PV6JNV |
| USGS NEIC / ComCat | 地震・核実験 | Public Domain (US Gov) | USGS Earthquake Hazards Program |
| Merdith 2021 | プレート復元 | CC-BY 4.0 | Merdith et al. (2021), Zenodo 4485738 |
| Cao 2024 | プレート復元 | CC-BY 4.0 | Cao et al. (2024), GPlates GWS |
| Matthews 2016 | プレート復元 | CC-BY 4.0 | Matthews et al. (2016); Domeier & Torsvik (2014); Müller et al. (2016) |
| LIP (EarthByte v2) | 大規模火成岩区 | CC-BY 4.0 | Johansson, Zahirovic & Müller (2018), GRL 45 |
| 海洋底年代グリッド (EarthByte) | 海洋底の年代 | CC-BY 4.0 | Müller et al.（EarthByte seafloor age grid） |
| 地質区 provinces | 地質区分 | **GPL-3.0** | Hasterok et al. (2022), Earth-Sci. Rev. 231; github.com/dhasterok/global_tectonics |
| 日本シームレス地質図 V2 | 日本の地質 | 政府標準利用規約2.0 (CC-BY 相当) | 産総研地質調査総合センター「20万分の1日本シームレス地質図V2」https://gbank.gsj.jp/seamless/ |
| GNSS (NGL MIDAS/IGS14) | 地表速度 | NGL 公開 | Blewitt, Hammond & Kreemer, Nevada Geodetic Lab |
| FDSN 観測点 | 観測網 | IRIS/EarthScope DMC 公開 | IRIS/EarthScope Data Management Center |

## 公開データ（論文・NCEI 等、要引用／public-domain 濃厚）

以下は公開された論文・政府機関（NCEI 等）由来で、帰属明記のうえ研究・教育目的で広く再利用されているもの。
明示的なライセンスファイルが伴わないものを含むため、正式な再配布条件は各出典で確認のこと（`docs/LICENSING.md` D 節）。

- プレート境界: Bird (2003), doi:10.1029/2001GC000252
- プレート運動: NNR-MORVEL56 / NUVEL-1A (Argus, Gordon & DeMets 2011; DeMets et al.)
- ひずみ速度: GSRM v2.1 (Kreemer, Blewitt & Klein 2014)
- 起伏 / 海底地形: ETOPO1 (Amante & Eakins 2009, NOAA NCEI)
- 熱流量: Lucazeau (2019), G-Cubed 20
- 堆積層厚: GlobSed v3 (Straume et al. 2019, NCEI)
- 磁気異常: EMAG2v3 (Meyer, Saltus & Chulliat 2017, NCEI)
- トモグラフィ (EMC 各モデル): 各モデル著者を要引用（S40RTS: Ritsema et al. 2011 ほか）。IRIS/EarthScope EMC
- ホットスポット: Courtillot et al. (2003), EPSL 205
- 地震カタログ（日本, デモ用サブセット）: 気象庁一元化震源カタログ
- 火山（完新世火山の位置・テクトニクス設定）: Global Volcanism Program, *Volcanoes of the World*, Smithsonian Institution, https://volcano.si.edu/ 。**要出典**（GVP・Smithsonian＋バージョン/取得日を明記）。GVP の DB compilation は米国政府職員の成果物（事実データ＝位置・型は著作権対象外と解される）。ただし Smithsonian 公式 Terms of Use は「教育・非商用目的での利用」を条件とし**商用利用を明示的に制限**する点に注意（本教材＝教育・非商用配布）。詳細は `docs/LICENSING.md` D-3。

## 理論走時 / Travel-time theory

- anisotime-js / ANISOtime: © Kensuke Konishi, Anselme F. E. Borgeaud, Kenji Kawai, Robert J. Geller ほか（UT Global Seismology）。**GPL-3.0**。github.com/UT-GlobalSeismology/anisotime

---
初回 GitHub 公開（2026-07）で再配布可否が未確認のため**除外**したデータ（LIP barcode, Scotese, Müller2019/Li2013,
重力, 発震機構(GCMT), 地殻(CRUST1.0), 古地磁気極(GPMDB), 隕石構造, 日本地体構造, ULVZ, D″モデル 等）は
`docs/LICENSING.md` を参照。ライセンス確認後に順次追加予定。海洋底年代（EarthByte CC-BY）と火山（GVP）は確認のうえ同梱に戻した。
