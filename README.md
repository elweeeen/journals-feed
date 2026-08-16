# 建築環境・設備 新着論文フィード

建築環境・設備分野の学術誌6誌と業界誌3誌から新着を集め、日本語のタイトルと要約を付けた
Atom フィードを配信しています。RSS リーダー（Inoreader など）で購読できます。

## 購読URL

まとめて読むか、誌ごとに分けて読むかを選べます。誌ごとのURLは
`https://elweeeen.github.io/journals-feed/` にファイル名をつけたものです。

### 学術誌（査読を通った論文）

| 誌名 | 国・発行 | 刊行ペースの目安 | ファイル名 |
|---|---|---|---|
| [日本建築学会 環境系論文集](https://www.jstage.jst.go.jp/browse/aije) | 日本／日本建築学会 | 月7本前後 | `aije.xml` |
| [空気調和・衛生工学会 論文集](https://www.jstage.jst.go.jp/browse/shase) | 日本／空気調和・衛生工学会 | 月1本前後 | `shase.xml` |
| [Energy and Buildings](https://www.journals.elsevier.com/energy-and-buildings) | オランダ／Elsevier | 月140本前後（うち抄録公開は3割） | `enbuild.xml` |
| [Building and Environment](https://www.journals.elsevier.com/building-and-environment) | 英国／Elsevier | 月105本前後（うち抄録公開は3割） | `buildenv.xml` |
| [Journal of Building Performance Simulation](https://www.tandfonline.com/toc/tbps20/current) | 英国／Taylor & Francis（IBPSA 学会誌） | 月4本前後 | `jbps.xml` |
| [Science and Technology for the Built Environment](https://www.tandfonline.com/toc/uhvc21/current) | 米国／Taylor & Francis（ASHRAE 査読誌） | 月8本前後 | `stbe.xml` |

### 大会論文（年1回まとめて公開されるものを、毎朝少しずつ）

| 誌名 | 国・発行 | 規模 | 配信ペース | ファイル名 |
|---|---|---|---|---|
| [空気調和・衛生工学会大会 学術講演論文集](https://www.jstage.jst.go.jp/browse/shasetaikai) | 日本／空気調和・衛生工学会 | 年611〜775本 | 1日10本（約78日で完走） | `shasetaikai.xml` |

年1回まとめて数百本が公開されるため、そのままでは読みきれません。いったん貯めておき、
**毎朝少しずつ配信**しています。分野（空調・熱源・換気など）が記事の区分として付くので、
RSSリーダー側で絞り込めます。査読論文とは性格が違うため、**全誌まとめには含めていません**。

### 業界誌（査読なし。実在建物の事例と技術解説）

| 誌名 | 国・性格 | 取り込む区分 | 配信ペース | ファイル名 |
|---|---|---|---|---|
| [CIBSE Journal](https://www.cibsejournal.com/) | 英国／CIBSE（英国建築設備技術者協会）会員誌 | Case Studies、Technical | 月2本前後 | `cibse.xml` |
| [Consulting-Specifying Engineer](https://www.csemag.com/) | 米国／設備設計コンサルタント向け | Case Study、Sustainability | 月1〜2本 | `cse.xml` |
| [HPAC Engineering](https://www.hpac.com/) | 米国／商業・産業・公共建築の HVAC | Industry Perspectives | 月1〜2本 | `hpac.xml` |

**全誌まとめは `feed.xml`**（最新50件）。

業界誌は誌全体ではなく上の区分だけを取り込んでいます。製品発表・買収・表彰・会議案内は
除いているため、配信ペースは誌の発行量より少なくなります。

刊行ペースは 2026-08-16 時点の実測にもとづく目安で、保証ではありません。

## 各記事に載せている内容

- 論文タイトル（日本語訳）と原題
- 著者・掲載誌
- **AI が作成した日本語要約**（背景・目的／方法／結果／実務への示唆）
- 出版社ページへのリンク（DOI）

CIBSE Journal / Consulting-Specifying Engineer / HPAC Engineering は学術誌ではなく
業界誌のため、要約が **何の話か／要点／日本との違い** の3項目になります。それぞれ英国・
米国の法規・気候が前提の記事なので、日本にそのまま当てはめると誤読する点を明示しています。
掲載欄に入る区分（`Case Studies` / `Technical` / `Case Study` / `Sustainability` /
`Industry Perspectives`）で絞り込めます。

## 要約について

要約は生成AI（Claude）が各論文の抄録から作成したもので、**原著者による記述ではありません**。
解釈の誤りが含まれる可能性があります。内容を判断に用いる際は、必ずリンク先の原論文に
あたってください。

論文の抄録そのもの（原文・訳文とも）はこのフィードには含めていません。著作権は各出版社に
帰属します。タイトル・著者・書誌情報は事実情報として掲載しています。

## 生成方法

各誌の公開API（J-STAGE WebAPI / OpenAlex）から新着を取得し、翻訳と要約を付けて
生成しています。このフィードは自動生成されたもので、内容の正確性は保証されません。
