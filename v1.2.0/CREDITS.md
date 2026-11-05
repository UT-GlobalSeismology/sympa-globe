# データソースの出典・ライセンス / Data Credits

シンパ！の配布ビルド（`npm run build:dist` / `--globe`）に**実際に同梱される**データソースの出典と
ライセンスです。ソフトウェア本体とは別に、各データはそれぞれのライセンスに従います。

アプリ内では `refs` コマンドで、クリック可能な引用リンクとして一覧できます。

## 海岸線・地形・地球物理場

| データ | 用途 | ライセンス | 出典・帰属 |
|--------|------|-----------|-----------|
| Natural Earth（海岸線 50m/110m） | 海岸線 | Public Domain | naturalearthdata.com |
| ETOPO1 | 地形・海底地形 | Public Domain (NOAA NCEI) | Amante & Eakins (2009), NOAA NCEI |
| GlobSed v3 | 海洋堆積層厚 | Public Domain (NOAA NCEI) | Straume et al. (2019), doi:10.1029/2018GC008115 |
| EMAG2v3 | 地磁気異常 | Public Domain (NOAA NCEI) | Meyer, Saltus & Chulliat (2017), doi:10.7289/V5H70CVX |

## プレートテクトニクス

| データ | 用途 | ライセンス | 出典・帰属 |
|--------|------|-----------|-----------|
| PB2002 | プレート境界 | **ODC-By 1.0**（帰属表示で商用可・サブライセンス不可） | Bird (2003), doi:10.1029/2001GC000252。整備・再配布: Hugo Ahlenius (Nordpil), github.com/fraxen/tectonicplates |
| NNR-MORVEL56 | 現在のプレート運動 | 非商用利用は許諾（**著者が商用権を留保**） | Argus, Gordon & DeMets (2011), doi:10.1029/2011GC003751 |
| NUVEL-1A | 現在のプレート運動（比較用） | — | DeMets, Gordon, Argus & Stein (1994), doi:10.1029/94GL02118 |
| GSRM v2.1 | ひずみ速度・プレート運動 | 著者（C. Kreemer）より許諾を得て同梱 | Kreemer, Blewitt & Klein (2014), doi:10.1002/2014GC005407 |
| Merdith 2021 | プレート復元 | CC-BY 4.0 | Merdith et al. (2021), Zenodo 4485738 |
| Matthews 2016 | プレート復元 | CC-BY 4.0 | Matthews et al. (2016), doi:10.1016/j.gloplacha.2016.10.002; Domeier & Torsvik (2014); Müller et al. (2016) |
| Cao 2024 | プレート復元 | CC-BY 4.0 | Cao et al. (2024), Zenodo 10910449 |
| 海洋底年代グリッド | 海洋底の年代 | **CC-BY 4.0** | Seton et al. (2020), doi:10.1029/2020GC009214（データ: Zenodo 6782543） |
| Slab2 | 沈み込み帯の形状 | Public Domain (USGS) | Hayes et al. (2018), doi:10.5066/F7PV6JNV |
| World Stress Map 2016 | 地殻応力場 | CC-BY 4.0 | Heidbach et al. (2016), GFZ Data Services, doi:10.5880/WSM.2016.001 |

## 地震・火山・火成活動

| データ | 用途 | ライセンス | 出典・帰属 |
|--------|------|-----------|-----------|
| USGS NEIC / ComCat | 地震・核実験 | Public Domain (US Gov) | USGS Earthquake Hazards Program |
| 気象庁 一元化震源（デモ用サブセット） | 日本の地震 | 公共データ利用規約（第1.0版・CC BY 4.0 互換） | 出典: 気象庁ホームページ https://www.jma.go.jp/ 。**当方が抽出・再フォーマットの編集加工を行っている** |
| Global Volcanism Program | 火山 | Smithsonian Terms of Use（**教育・非商用目的**） | Global Volcanism Program, *Volcanoes of the World*, Smithsonian Institution, https://volcano.si.edu/ （版番号・取得日を要明記） |
| EarthByte LIP v2 | 大規模火成岩区 | CC-BY 4.0 | Johansson, Zahirovic & Müller (2018), doi:10.1029/2017GL076691 |
| LIP 輪郭（Ernst 版） | 大陸洪水玄武岩＋岩脈群（先カンブリア〜現在） | 著者 R. E. Ernst の明示的許諾（2026-09-10。無償版・有償版とも） | Ernst, R.E. & Youbi, N. (2017) *Palaeogeogr. Palaeoclimatol. Palaeoecol.* 478, 30–52, doi:10.1016/j.palaeo.2017.03.014 ／ Ernst, R.E. et al. (2021) Ernst, Dickson & Bekker 編『Large Igneous Provinces: A Driver of Global Environmental and Biotic Changes』AGU Geophys. Monogr. 255, 1–26, doi:10.1002/9781119507444.ch1 ／ Park, Y. et al. (2021) 同書, doi:10.1002/9781119507444.ch7（体裁は権利者本人の指定 2026-09-11） |
| ホットスポット | ホットスポットと移動軌跡 | CC-BY 4.0 | EarthByte GPlates GeoData（Whittaker et al. (2015), doi:10.1038/ngeo2437）。深部起源の分類は Courtillot et al. (2003), doi:10.1016/S0012-821X(02)01048-8 |

## マントル構造（地震波トモグラフィ）

| データ | 用途 | ライセンス | 出典・帰属 |
|--------|------|-----------|-----------|
| S40RTS | S 波速度（深さスライス・断面） | 著者（J. Ritsema）より許諾を得て同梱 | Ritsema, Deuss, van Heijst & Woodhouse (2011), *Geophys. J. Int.* 184, 1223–1236, doi:10.1111/j.1365-246X.2010.04884.x |
| S362ANI | S 波速度 | IRIS/EarthScope EMC で公開（モデルの著者に帰属） | Kustowski, Ekström & Dziewoński (2008), *J. Geophys. Res.* 113, doi:10.1029/2007JB005169 |
| SEISGLOB2 | S 波速度 | 同上 | Durand, Debayle, Ricard, Zaroli & Lambotte (2017), *Geophys. J. Int.* 211, 1628–1639, doi:10.1093/gji/ggx405 |
| GyPSuM | S 波速度 | 同上 | Simmons, Forte, Boschi & Grand (2010), *J. Geophys. Res.* 115, doi:10.1029/2010JB007631 |
| SGLOBE-rani | S 波速度 | 同上 | Chang, Ferreira, Ritsema, van Heijst & Woodhouse (2015), *J. Geophys. Res. Solid Earth* 120, 4278–4300, doi:10.1002/2014JB011824 |
| SAW642AN | S 波速度 | 同上 | Mégnin & Romanowicz (2000), *Geophys. J. Int.* 143, 709–728, doi:10.1046/j.1365-246x.2000.00298.x |
| SEMUCB-WM1 | S 波速度 | 同上 | French & Romanowicz (2014), *Geophys. J. Int.* 199, 1303–1327, doi:10.1093/gji/ggu334 |

## 観測網

| データ | 用途 | ライセンス | 出典・帰属 |
|--------|------|-----------|-----------|
| NGL MIDAS (IGS14) | GNSS 地表速度 | 著者（G. Blewitt ら）より許諾を得て同梱 | Blewitt, Hammond & Kreemer (2018), doi:10.1029/2018EO104623; Blewitt et al. (2016), doi:10.1002/2015JB012552 |
| FDSN 観測点メタデータ | 観測網 | CC-BY 4.0（既定） | IRIS/EarthScope（NSF SAGE Facility）および各観測網の運用機関 |

## 日本の地質（フル版・配布版のみ）

| データ | 用途 | ライセンス | 出典・帰属 |
|--------|------|-----------|-----------|
| 20万分の1日本シームレス地質図 V2 | 日本の地質 | 政府標準利用規約2.0（CC-BY 相当） | 産総研地質調査総合センター「20万分の1日本シームレス地質図V2」https://gbank.gsj.jp/seamless/ |
| 地質区 provinces | 全球の地質区分 | **GPL-3.0** | Hasterok et al. (2022), doi:10.1016/j.earscirev.2022.104069; github.com/dhasterok/global_tectonics |

## 理論走時 / Travel-time theory

- anisotime-js / ANISOtime: © Kensuke Konishi, Anselme F. E. Borgeaud, Kenji Kawai, Robert J. Geller ほか
  （UT Global Seismology）。**GPL-3.0**。github.com/UT-GlobalSeismology/anisotime

## 同梱ライブラリ / Bundled libraries

- QR Code Generator for JavaScript: © 2009 Kazuhiko Arase。**MIT**。github.com/kazuhikoarase/qrcode-generator
  （`share qr` の QR 生成に使用。"QR Code" は株式会社デンソーウェーブの登録商標）

---

各データは、それぞれの配布元が定める条件に従って同梱しています。再配布条件を満たさないデータは
配布ビルドから除外しています。データの利用にあたっては、上記の出典を明記してください。
