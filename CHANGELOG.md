# 2019-06-26 v5.0.0

* ✨ 独自のアイコングリフを導入
* 👍 NerdFontのMaterial Design Iconsを導入しました #45 #46
* 👍 大文字シータΘ と小文字シータθ を判読しやすいようにしました

# 2019-05-27 v4.1.3

* 三点リーダーを半角に変更しました #41 #43

# 2019-04-02 v4.1.2

* U+32FFに `令和(㋿)` を追加しました #42

# 2018-09-17 v4.1.0, v4.1.1

* Icons for Devsを追加しました #37

# 2018-09-15 v4.0.0

* UbuntuMonoをHackに変更しました
* ライセンスの競合を無くし、 SIL Open Font License 1.1 になりました
* 以前のバージョンはライセンスに問題があったので非公開にしました

# 2018-01-04 v2.0.5

上半身Gopherを復活させました #20

# 🎉 2017-10-09 v2.0.0

NERDTreeなどでファイルタイプ別にアイコンを表示させる為のNerd Fontsを統合し、
v2としてリリースしました。

また、CicaEは廃止し、Cica1本にしました。

## NERDFontsを追加

詳細はこちら -> https://github.com/ryanoasis/nerd-fonts

これによりCicaE v1 から DevIcon のUnicodeが変更になりました。

## スタイル追加

Italicをそれぞれ追加し、以下の通りになりました。

- Cica Regular
- Cica RegularItalic
- Cica Bold
- Cica BoldItalic

## ambiguousグリフの変更（全角半角が曖昧なグリフ）

Rounded Mgen+、UbuntuMonoどちらも半角幅になっているグリフを
UbuntuMonoのグリフを採用するように変更しました。

| グリフ                  | 変更前        | 変更後     |
| ----                    | ----          | ----       |
| 0x00a4, # currency      | Rounded Mgen+ | UbuntuMono |
| 0x00a7, # section       | Rounded Mgen+ | UbuntuMono |
| 0x00a8, # dieresis      | Rounded Mgen+ | UbuntuMono |
| 0x00ad, # soft hyphen   | Rounded Mgen+ | UbuntuMono |
| 0x00b0, # degree        | Rounded Mgen+ | UbuntuMono |
| 0x00b1, # plus-minus    | Rounded Mgen+ | UbuntuMono |
| 0x00b4, # acute         | Rounded Mgen+ | UbuntuMono |
| 0x00b6, # pilcrow       | Rounded Mgen+ | UbuntuMono |
| 0x00d7, # multiply      | Rounded Mgen+ | UbuntuMono |
| 0x00f7, # divide        | Rounded Mgen+ | UbuntuMono |
| 0x2018, # left '        | Rounded Mgen+ | UbuntuMono |
| 0x2019, # right '       | Rounded Mgen+ | UbuntuMono |
| 0x201c, # left "        | Rounded Mgen+ | UbuntuMono |
| 0x201d, # right "       | Rounded Mgen+ | UbuntuMono |
| 0x2020, # dagger        | Rounded Mgen+ | UbuntuMono |
| 0x2021, # double dagger | Rounded Mgen+ | UbuntuMono |
| 0x2026, # ...           | Rounded Mgen+ | 変更なし   |
| 0x2122, # TM            | Rounded Mgen+ | UbuntuMono |
| 0x2191, # uparrow       | Rounded Mgen+ | 変更なし   |
| 0x2193, # downarrow     | Rounded Mgen+ | 変更なし   |


## ビルドスクリプトをPythonに

全面的にPythonに書き換えました。

