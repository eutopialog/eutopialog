---
title: "【自作PCとBTO】PCを作ってみる #1：パーツ高騰時代のBTO価格を比較"
description: "PCを自作するか、BTOパソコンを買うか。高騰するメモリやストレージの最新相場を交えながら、マウスコンピューターのG-Tuneモデルと比較検証します。"
pubDate: 2026-11-06
tags: ["自作PC", "BTO", "PCパーツ", "G-Tune", "マウスコンピューター"]
---

寒くなってまいりましたが、気づけばもう11月ですね。11月といえばお買い物です。私はブラックフライデーに照準を定め、ここ最近はPCパーツの動向に張り付いていました。

「ハイレゾってどうなの？」という記事を計画しているのですが、最近はこちらにより多くのエネルギーを使っているので、先に「PCを作ってみる」を残しておきたいと思います。おそらく複数回にわたるシリーズになります。

この記事が、これからPCを組んでみたい、あるいは買ってみたいとぼんやりとでも考えている人たちのお役に立てれば幸いです。また自分にとっても2026年のブラックフライデー前の備忘録として、振り返られるものになればとも思っています。

---

## PCって何ができるの？なぜ買うの？

ゲームも遊べますし、だいたいなんでもできます。

しかし、ちょっとした調べ物にはスマートフォンが大変便利ですし、PlayStationを持っておけば映画も観られますし、現行のゲームプレイに関しても不足しないはずです。

それでも「PCを買ってみたい」という動機は、人それぞれでしょう。一歩踏み込んで何かをやってみたい、それは皆さん自身の意思ですから、素晴らしいことです。ちなみに私の場合はAIを使ってゲームを作ることです。

---

## PCの選択肢

PCの選択肢は非常に幅が広いです。

構成するパーツや組み合わせを一つ一つ吟味するのもいいですし、メーカーモデル（BTO）を選ぶのも立派な選択肢です。コストの観点からは、以前であれば個人でパーツをバラ買いして組み上げる方が出費を抑えられました。一方で、メーカーモデルを選択すれば完成品が届きますから、安心と手頃さが得られます。

以下のモデルは、今回私が構成を検討・試算していたものです。

### 【参考】検討当時作成していたパーツ構成・候補リスト
> **目的：ローカルAI導入およびゲーム制作（GPU2枚挿し運用前提）**

| カテゴリ | 候補順位 | パーツ名・型番 / モデル名 | 標準価格/定価 | 備考 |
| :--- | :--- | :--- | :--- | :--- |
| **GPU** | 第1候補 | [AMD Radeon RX 9070 (Nitro+)](https://kakaku.com/item/K0001679955/) | ¥119,800 | 2-GPU setup planned (GPU 1: Display/Unity, GPU 2: AI/CUDA) |
| **GPU** | 第2候補 | [AMD Radeon RX 9070 XT (Crowxis)](https://kakaku.com/item/K0001806915/) | ¥138,800 | 同上 |
| **GPU** | 第3候補 | [PNY GeForce RTX 5060 Ti](https://kakaku.com/item/K0001696163/) | ¥137,800 | 同上 |
| **CPU** | 第1候補 | [Intel Core Ultra 7 270K](https://kakaku.com/search_results/Core+Ultra+7+270K/) | ¥55,980 | - |
| **CPU** | 第2候補 | [Intel Core Ultra 7 265K](https://kakaku.com/search_results/Core+Ultra+7+265K/) | ¥49,551 | - |
| **CPU** | 第3候補 | [AMD Ryzen 7 9700X](https://kakaku.com/search_results/Ryzen+7+9700X/) | ¥43,309 | - |
| **マザーボード** | 第1候補 | [MSI PRO Z890-A WIFI](https://kakaku.com/search_results/MSI+PRO+Z890-A+WIFI/) | ¥27,091 | [ATX / 2-GPU ready] |
| **マザーボード** | 第2候補 | [MSI MAG Z890 TOMAHAWK WIFI II](https://kakaku.com/search_results/MSI+MAG+Z890+TOMAHAWK+WIFI+II/) | ¥46,672 | [ATX / 2-GPU ready] |
| **マザーボード** | 第3候補 | [ASRock B850 Steel Legend WiFi](https://kakaku.com/search_results/ASRock+B850+Steel+Legend+WiFi/) | ¥27,800 | [ATX / 2-GPU ready] |
| **メモリ** | 第1候補 | [DDR5 64GB (64GB×1)](https://kakaku.com/search_results/DDR5+64GB/) | ¥120,000 | - |
| **メモリ** | 第2候補 | [DDR5 64GB (32GB×2)](https://kakaku.com/search_results/DDR5+32GB/) | ¥120,000 | - |
| **メモリ** | 第3候補 | [DDR5 32GB (32GB×1)](https://kakaku.com/search_results/DDR5+32GB/) | ¥60,000 | - |
| **電源** | 第1候補 | [MSI MPG Ai1300TS PCIE5](https://kakaku.com/search_results/MSI+MPG+Ai1300TS/) | ¥56,995 | [1300W / Dual GPU Power Ready] |

AI用にGPUを用意し、Unity用にも用意する「GPU2枚挿し運用」を検討していました。

全く同じ構成のモデルはBTOには存在しないため、構成の近いBTOモデルに組み直して比較してみましょう。

---

### ① [G-Tune FG-A7A70（アッパーミドル・アウトレット価格¥419,800）](https://www.mouse-jp.co.jp/store/g/ggtune-fga7a70g8bfdw101decwa/)と同等自作の比較

#### 【パーツ別】価格.com 最新相場と自作概算一覧

※昨今のメモリー・ストレージ価格高騰を踏まえた最新最安値データです。（10月末~11月初頭）

| 構成パーツ | モデル・クラス想定 | 価格.com 最新最安値・相場 |
| :--- | :--- | :--- |
| **CPU** | [AMD Ryzen 7 9700X BOX](https://kakaku.com/search_results/Ryzen+7+9700X/) | **¥41,500** |
| **GPU** | [Radeon RX 9070 16GB](https://kakaku.com/search_results/Radeon+RX+9070+16GB/) | **¥135,800** |
| **マザーボード** | [B850 ATX (Wi-Fi 6E)](https://kakaku.com/search_results/B850+ATX+WiFi/) | **¥19,800** |
| **メモリ** | [DDR5-5600 32GB (16GB×2)](https://kakaku.com/search_results/DDR5+5600+32GB+16GBx2/) | **¥65,000** |
| **ストレージ** | [Gen4 NVMe M.2 SSD 1TB](https://kakaku.com/search_results/M.2+SSD+1TB+Gen4/) | **¥24,980** |
| **電源ユニット** | [750W 80PLUS GOLD](https://kakaku.com/search_results/750W+80PLUS+GOLD/) | **¥8,479** |
| **CPUクーラー** | [360mm 水冷一体型クーラー](https://kakaku.com/search_results/360mm+cooler/) | **¥15,000** |
| **PCケース** | [ミドルタワーケース相当](https://www.ark-pc.co.jp/i/15201792//) | **¥14,830** |
| **OS** | [Windows 11 Home 64bit](https://kakaku.com/search_results/Windows+11+Home/) | **¥16,000** |
| **合計（税込）** | **自作パーツ単品購入時の合計** | **約 370,280 円** |

#### 差額の分析と評価

* **自作パーツ合計**：**約 341,389 円**
* **マウス販売価格**：**419,800 円**（税込・送料無料）
* **差額**：**+78,411 円**（BTOが約20%高い）

自作に対して差額8万円で、専用フルタワーケース・3年保証・組み立て済みが得られる構成となっています。

---

### ② [G-Tune FG-A7G6T（ミドル・アウトレット価格¥３６３,９００）](https://www.mouse-jp.co.jp/store/goods/search.aspx?search=x&keyword=&search=search&k_uid=SNest6HuiRReDgjsY4lR6eVl8a1m18&q=G-Tune+FG-A7G6T&searchbox=1)と同等自作の比較

#### 【パーツ別】価格.com 最新相場と自作概算一覧

| 構成パーツ | 仕様・モデル想定 | 価格.com 最新最安値・相場 |
| :--- | :--- | :--- |
| **CPU** | [AMD Ryzen 7 7700 BOX](https://kakaku.com/search_results/Ryzen+7+7700/) | **¥38,980** |
| **GPU** | [GeForce RTX 5060 Ti 16GB](https://kakaku.com/search_results/RTX+5060+Ti+16GB/) | **¥148,800** |
| **マザーボード** | [AMD B850 ATX (Wi-Fi 6E)](https://kakaku.com/search_results/B850+ATX+WiFi/) | **¥19,800** |
| **メモリ** | [DDR5-5200 32GB (32GB×1)](https://kakaku.com/pc/pc-memory/itemlist.aspx?pdf_Spec101=7&pdf_Spec102=1&pdf_Spec301=32&pdf_so=p1) | **¥76,980** |
| **ストレージ** | [M.2 NVMe Gen4×4 SSD 1TB](https://kakaku.com/search_results/M.2+SSD+1TB+Gen4/) | **¥24,980** |
| **電源ユニット** | [750W 80PLUS BRONZE](https://kakaku.com/search_results/750W+80PLUS+BRONZE/) | **¥9,800** |
| **CPUクーラー** | [360mm 水冷一体型クーラー](https://kakaku.com/pc/water_cpu-cooler/itemlist.aspx?pdf_Spec311=280-360) | **¥15,000** |
| **PCケース** | [ミドルタワーケース]((https://kakaku.com/item/J0000041467/)) | **¥11,000** |
| **OS** | [Windows 11 Home 64bit] | **¥16,000** |
| **合計（税込）** | **自作パーツ単品購入時の合計** | **約 366,540 円** |

#### 差額の分析と評価

* **自作パーツ合計**：**約 366,540 円**
* **マウス販売価格**：**363,900 円**（税込・送料無料）
* **差額**：**同等の出費で、３年保証の完成品が届く。

 **DDR5 32GB（1枚挿し）単体価格の高騰**
   「DDR5 32GB 1枚モジュール」を個人で購入すると相場が著しく高額（約7.7万円前後）になるため、大口調達の効くBTOのセット価格の方がパーツ単体合計を下回る逆転現象が生じています。また、GeforceのGPUのため、こちらも値上がりが深刻です。   

---

## 自作PCとBTOの現在地

<p style="front-feight: normal;">
現在、メモリ、ストレージ、GPUは史上かつてないほどに高騰しています。そのため、自作PCのコスト面における優位性はかなり危うくなっており、大量調達の効くBTOメーカーが非常に強い印象を受けます。
しかし、BTOも値上がり自体はしていますから、自分でパーツを選び、組み上げる楽しさは自作PCならではの大きな魅力として残っています。
</p>

## 総評
<p style="front-weight: normal;">
本当に一日単位で価格の変動が発生しております。例えば、当初私が目を付けていたSapphire製9070は最安値￥119,800がしばらく続いていましたが、ブラックフライデーセールを待つ間に値上がりしました。逆に9070xtに関してはリニューアルブランドが当初￥129,000手前で登場するという想定外の現象も目の当たりにしました。いずれにせよ、ブラックフライデーセールを待つ間にもジリジリと値上がり傾向にあるように見えます。

## 次回以降について

偉そうにPCについて書いていますが、実は先月まで私自身ほとんど知識はありませんでした。

しかし、勉強して店舗への現地調査にも赴き、それなりに知識を蓄えることができました。お勉強の成果の備忘録を兼ねて、次回はパーツのことをまとめておきたいと思います。
</p>