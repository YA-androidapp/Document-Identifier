# Document-Identifier

識別子

---

<!-- TOC -->autoauto- [Document-Identifier](#document-identifier)auto- [階層](#階層)auto- [内容](#内容)auto    - [Uniform Resource Identifier (URI)](#uniform-resource-identifier-uri)auto    - [Uniform Resource Locator (URL)](#uniform-resource-locator-url)auto    - [Uniform Resource Name (URN)](#uniform-resource-name-urn)auto    - [Universally Unique IDentifier (UUID)](#universally-unique-identifier-uuid)autoauto<!-- /TOC -->

---

# 階層

| 項目   |         |                            |      |
| ------ | ------- | -------------------------- | ---- |
| 識別子 |         |                            |      |
|        | URI     |                            |      |
|        |         | URL                        |      |
|        |         | URN                        |      |
|        |         |                            | UUID |
|        |         |                            |      |
|        | Cuid2   |                            |      |
|        | Nano ID |                            |      |
|        | ULID    |                            |      |
|        | xid     |                            |      |
|        |         |                            |      |
|        | DB      |                            |      |
|        |         | 採番テーブル               |      |
|        |         | AUTO_INCREMENT(IDENTITY)列 |      |
|        |         | シーケンスオブジェクト     |      |
|        |         |                            |      |

---

# 内容

## Uniform Resource Identifier (URI)

- [RFC2396](https://datatracker.ietf.org/doc/html/rfc2396)
- [RFC3986](https://datatracker.ietf.org/doc/html/rfc3986)

## Uniform Resource Locator (URL)

- [RFC1738](https://datatracker.ietf.org/doc/html/rfc1738)

## Uniform Resource Name (URN)

- [RFC2141](https://tools.ietf.org/html/rfc2141)
- [RFC3406](https://tools.ietf.org/html/rfc3406)
- [Uniform Resource Names (URN) Namespaces](http://www.iana.org/assignments/urn-namespaces/urn-namespaces.xhtml)

| URN Namespace       | Template          | Reference                                                                                  |
| ------------------- | ----------------- | ------------------------------------------------------------------------------------------ |
| 3gpp                |                   | [RFC5279]                                                                                  |
| 3gpp2               | [3gpp2-template]  | [RFC8464]                                                                                  |
| adid                |                   | [RFC8107]                                                                                  |
| alert               |                   | [RFC7462]                                                                                  |
| bbf                 |                   | [RFC8057]                                                                                  |
| broadband-forum-org |                   | [RFC8057]                                                                                  |
| cablelabs           |                   | [RFC6289]                                                                                  |
| ccsds               |                   | [RFC7738]                                                                                  |
| cdx                 | [cdx-template]    | [The OWASP Foundation Inc.]                                                                |
| cgi                 |                   | [RFC5138]                                                                                  |
| clei                |                   | [RFC4152]                                                                                  |
| ddi                 |                   | [draft-urn-ddi-00]                                                                         |
| dev                 | [dev-template]    | [RFC9039]                                                                                  |
| dgiwg               |                   | [RFC6288]                                                                                  |
| doi                 | [doi-template]    | [DOI Foundation]                                                                           |
| dslforum-org        |                   | [RFC8057]                                                                                  |
| dvb                 |                   | [RFC5328][RFC7354]                                                                         |
| ebu                 |                   | [RFC5174]                                                                                  |
| eic                 | [eic-template]    | [European Network of Transmission System Operators for Electricity (ENTSO-E)]              |
| eidr                |                   | [RFC7972]                                                                                  |
| epc                 |                   | [RFC5134]                                                                                  |
| epcglobal           |                   | [RFC5134]                                                                                  |
| etsi                | [etsi-template]   | [RFC8515]                                                                                  |
| eurosystem          |                   | [RFC7207]                                                                                  |
| example             |                   | [RFC6963]                                                                                  |
| fdc                 |                   | [RFC4198]                                                                                  |
| fipa                |                   | [RFC3616]                                                                                  |
| gdst                | [gdst-template]   | [Institute of Food Technologists]                                                          |
| geant               |                   | [RFC4926]                                                                                  |
| globus              |                   | [RFC7853]                                                                                  |
| gsma                |                   | [RFC7254]                                                                                  |
| gvat                | [gvat-template]   | [Bundeskanzleramt der Republik Österreich]                                                 |
| hbbtv               |                   | [RFC7528]                                                                                  |
| ieee                |                   | [RFC8069]                                                                                  |
| ietf                |                   | [RFC2648]                                                                                  |
| iptc                |                   | [RFC3937]                                                                                  |
| isan                |                   | [RFC4246]                                                                                  |
| isbn                | [isbn-template]   | [International ISBN Agency]                                                                |
| iso                 |                   | [RFC5141]                                                                                  |
| issn                | [issn-template]   | [ISSN International Centre]                                                                |
| itu                 | [itu-template]    | [International Telecommunications Union (ITU)]                                             |
| ivis                |                   | [RFC4617]                                                                                  |
| lei                 | [lei-template]    | [Global Legal Entity Identifier Foundation (GLEIF)]                                        |
| lex                 | [lex-template]    | [draft-spinosa-urn-lex-15]                                                                 |
| liberty             |                   | [RFC3622]                                                                                  |
| mace                |                   | [RFC3613]                                                                                  |
| mef                 |                   | [RFC7818]                                                                                  |
| meta                | [meta-template]   | [Juha_Hakala]                                                                              |
| mpeg                |                   | [RFC3614]                                                                                  |
| mrn                 | [mrn-template]    | [International Association of Marine Aids to Navigation and Lighthouse Authorities (IALA)] |
| nato                |                   | [RFC7467]                                                                                  |
| nbn                 | [nbn-template]    | [RFC8458]                                                                                  |
| nena                |                   | [RFC6061]                                                                                  |
| newsml              |                   | [RFC3085]                                                                                  |
| nfc                 |                   | [RFC4729]                                                                                  |
| nzl                 |                   | [RFC4350]                                                                                  |
| oasis               |                   | [RFC3121]                                                                                  |
| ogc                 |                   | [RFC5165]                                                                                  |
| ogf                 |                   | [RFC6453]                                                                                  |
| oid                 |                   | [RFC3061]                                                                                  |
| oipf                |                   | [RFC6893]                                                                                  |
| oma                 |                   | [RFC4358]                                                                                  |
| onem2m              | [onem2m-template] | [oneM2M Partnership Project]                                                               |
| onf                 | [onf-template]    | [Open Networking Foundation]                                                               |
| pin                 |                   | [RFC3043]                                                                                  |
| publicid            |                   | [RFC3151]                                                                                  |
| pwid                | [pwid-template]   | [Eld_Zierau]                                                                               |
| reso                | [reso-template]   | [Real Estate Standards Organization (RESO)]                                                |
| s1000d              |                   | [RFC4688]                                                                                  |
| schac               |                   | [RFC6338]                                                                                  |
| service             |                   | [RFC5031]                                                                                  |
| smpte               |                   | [RFC5119]                                                                                  |
| swift               |                   | [RFC3615]                                                                                  |
| tva                 |                   | [RFC4195]                                                                                  |
| uci                 |                   | [RFC4179]                                                                                  |
| ucode               |                   | [RFC6588][RFC Errata 3188][RFC Errata 3189]                                                |
| uuid                |                   | [RFC4122]                                                                                  |
| web3d               |                   | [RFC3541]                                                                                  |
| xmlorg              |                   | [RFC3120]                                                                                  |
| xmpp                |                   | [RFC4854]                                                                                  |
|                     |                   |                                                                                            |

## Universally Unique IDentifier (UUID)

- [RFC4122](https://datatracker.ietf.org/doc/html/rfc4122)
  - [draft-ietf-uuidrev-rfc4122bis](https://datatracker.ietf.org/doc/html/draft-ietf-uuidrev-rfc4122bis) (2023/04/12から2023/10/14)

| バージョン | 内容                                            | 基準日時                 | 正規表現                                                                  | C#                                                                    | C# [UUIDNext](https://www.nuget.org/packages/UUIDNext) | JavaScript                            | PHP [ramsey/uuid](https://github.com/ramsey/uuid)            | PHP [symfony/uid](https://github.com/symfony/uid)                         |     | PowerShell                                                                                     | [Python](https://docs.python.org/ja/3/library/uuid.html)       |      |     |
| ---------- | ----------------------------------------------- | ------------------------ | ------------------------------------------------------------------------- | --------------------------------------------------------------------- | ------------------------------------------------------ | ------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------------------- | --- | ---------------------------------------------------------------------------------------------- | -------------------------------------------------------------- | ---- | --- |
| 1          | 時刻（下→中→上位） ＋ シーケンス ＋ MACアドレス | グレゴリオ暦ベース       | `([0-9a-f]{8})-([0-9a-f]{4})-(1[0-9a-f]{3})-([0-9a-f]{4})-([0-9a-f]{12})` |                                                                       |                                                        | [1](https://github.com/uuidjs/uuid)   | [1](https://uuid.ramsey.dev/en/stable/rfc4122/version1.html) | [1](https://symfony.com/doc/current/components/uid.html#generating-uuids) |     |                                                                                                | [1](https://docs.python.org/ja/3/library/uuid.html#uuid.uuid1) | []() |     |
| 2          |                                                 |                          | `([0-9a-f]{8})-([0-9a-f]{4})-(2[0-9a-f]{3})-([0-9a-f]{4})-([0-9a-f]{12})` |                                                                       |                                                        |                                       | [2](https://uuid.ramsey.dev/en/stable/rfc4122/version2.html) |                                                                           |     |                                                                                                |                                                                | []() |     |
| 3          | MD5                                             |                          | `([0-9a-f]{8})-([0-9a-f]{4})-(3[0-9a-f]{3})-([0-9a-f]{4})-([0-9a-f]{12})` |                                                                       |                                                        | [3](https://github.com/uuidjs/uuid)   | [3](https://uuid.ramsey.dev/en/stable/rfc4122/version3.html) | [3](https://symfony.com/doc/current/components/uid.html#generating-uuids) |     |                                                                                                | [3](https://docs.python.org/ja/3/library/uuid.html#uuid.uuid3) | []() |     |
| 4          | 乱数                                            |                          | `([0-9a-f]{8})-([0-9a-f]{4})-(4[0-9a-f]{3})-([0-9a-f]{4})-([0-9a-f]{12})` | [4](https://learn.microsoft.com/ja-jp/dotnet/api/system.guid.newguid) | [4](https://www.nuget.org/packages/UUIDNext)           | [4](https://github.com/uuidjs/uuid)   | [4](https://uuid.ramsey.dev/en/stable/rfc4122/version4.html) | [4](https://symfony.com/doc/current/components/uid.html#generating-uuids) |     | [4](https://learn.microsoft.com/ja-jp/powershell/module/microsoft.powershell.utility/new-guid) | [4](https://docs.python.org/ja/3/library/uuid.html#uuid.uuid4) | []() |     |
| 5          | SHA-1                                           |                          | `([0-9a-f]{8})-([0-9a-f]{4})-(5[0-9a-f]{3})-([0-9a-f]{4})-([0-9a-f]{12})` |                                                                       | [5](https://www.nuget.org/packages/UUIDNext)           | [5](https://github.com/uuidjs/uuid)   | [5](https://uuid.ramsey.dev/en/stable/rfc4122/version5.html) | [5](https://symfony.com/doc/current/components/uid.html#generating-uuids) |     | [5](https://qiita.com/h53/items/b85aa2fb852f39b0c52e)                                          | [5](https://docs.python.org/ja/3/library/uuid.html#uuid.uuid5) | []() |     |
| (6)        | 時刻（上→中→下位） ＋ シーケンス ＋ MACアドレス | グレゴリオ暦ベース       | `([0-9a-f]{8})-([0-9a-f]{4})-(6[0-9a-f]{3})-([0-9a-f]{4})-([0-9a-f]{12})` |                                                                       |                                                        |                                       | [6](https://uuid.ramsey.dev/en/stable/rfc4122/version6.html) | [6](https://symfony.com/doc/current/components/uid.html#generating-uuids) |     |                                                                                                |                                                                | []() |     |
| (7)        | 時刻 ＋ 乱数                                    | ミリ秒Unixタイムスタンプ | `([0-9a-f]{8})-([0-9a-f]{4})-(7[0-9a-f]{3})-([0-9a-f]{4})-([0-9a-f]{12})` |                                                                       | [7](https://www.nuget.org/packages/UUIDNext)           |                                       | [7](https://uuid.ramsey.dev/en/stable/rfc4122/version7.html) | [7](https://symfony.com/doc/current/components/uid.html#generating-uuids) |     |                                                                                                |                                                                | []() |     |
| (8)        | 任意                                            |                          | `([0-9a-f]{8})-([0-9a-f]{4})-(8[0-9a-f]{3})-([0-9a-f]{4})-([0-9a-f]{12})` |                                                                       | [8](https://www.nuget.org/packages/UUIDNext)           |                                       | [8](https://uuid.ramsey.dev/en/stable/rfc4122/version8.html) | [8](https://symfony.com/doc/current/components/uid.html#generating-uuids) |     |                                                                                                |                                                                | []() |     |
| (Nil UUID) |                                                 |                          | `00000000-0000-0000-0000-000000000000`                                    |                                                                       |                                                        | [Nil](https://github.com/uuidjs/uuid) |                                                              |                                                                           |     |                                                                                                |                                                                | []() |     |
| (Max UUID) |                                                 |                          | `FFFFFFFF-FFFF-FFFF-FFFF-FFFFFFFFFFFF`                                    |                                                                       |                                                        |                                       |                                                              |                                                                           |     |                                                                                                |                                                                | []() |     |
|            |                                                 |                          |                                                                           |                                                                       |                                                        |                                       |                                                              |                                                                           |     |                                                                                                |                                                                |      |     |

- グレゴリオ暦ベース (60 bit)…　1582年10月15日からの100ナノ秒数
- ミリ秒Unixタイムスタンプ（エポックミリ秒）…　1970年1月1日からのミリ秒数

## Cuid2

- [paralleldrive/cuid2](https://github.com/paralleldrive/cuid2)
- [paralleldrive/cuid](https://github.com/paralleldrive/cuid)

> c(固定値) {Timestamp} {Counter} {Client fingerprint} {Random}

| 正規表現        | C#                                                        | Java                                                                  | JavaScript                                                    | PHP                                                         |
| --------------- | --------------------------------------------------------- | --------------------------------------------------------------------- | ------------------------------------------------------------- | ----------------------------------------------------------- |
| `c[a-z0-9]{24}` | [visus-io/cuid.net](https://github.com/visus-io/cuid.net) | [thibaultmeyer/cuid-java](https://github.com/thibaultmeyer/cuid-java) | [paralleldrive/cuid2](https://github.com/paralleldrive/cuid2) | [visus-io/php-cuid2](https://github.com/visus-io/php-cuid2) |

## Nano ID

- [ai/nanoid](https://github.com/ai/nanoid)

乱数のみをBase64エンコード

| 正規表現            | C#                                                        | Java                                                    | JavaScript                                | PHP                                                           | Python                                                  |
| ------------------- | --------------------------------------------------------- | ------------------------------------------------------- | ----------------------------------------- | ------------------------------------------------------------- | ------------------------------------------------------- |
| `[A-Za-z0-9_-]{21}` | [codeyu/nanoid-net](https://github.com/codeyu/nanoid-net) | [aventrix/jnanoid](https://github.com/aventrix/jnanoid) | [ai/nanoid](https://github.com/ai/nanoid) | [hidehalo/nanoid-php](https://github.com/hidehalo/nanoid-php) | [puyuan/py-nanoid](https://github.com/puyuan/py-nanoid) |

## ULID

- [ulid/spec](https://github.com/ulid/spec)

UUIDとの128ビット互換性を持つ、辞書順にソート可能な、ミリ秒Unixタイムスタンプと乱数を組み合わせた26文字の識別子

- Crockford の Base32 を使用 `0123456789ABCDEFGHJKMNPQRSTVWXYZ`
- 大文字小文字を区別せず、特殊文字を使用しない (URL セーフ)
- 同じミリ秒でも正しい順序を保つ

| 正規表現                        | C#                                                                                                                     | Java                                        | JavaScript                                            | PHP                                                                     | PowerShell                                                          | Python                                                                                                           |
| ------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | ------------------------------------------- | ----------------------------------------------------- | ----------------------------------------------------------------------- | ------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| `[0-9a-hjkmnp-zA-HJKMNP-Z]{26}` | [RobThree/NUlid](https://github.com/RobThree/NUlid) <br> [mcb2001/CSharp.Ulid](https://github.com/mcb2001/CSharp.Ulid) | [azam/ulidj](https://github.com/azam/ulidj) | [ulid/javascript](https://github.com/ulid/javascript) | [Lewiscowles1986/php-ulid](https://github.com/Lewiscowles1986/php-ulid) | [PetterBomban/posh-ulid](https://github.com/PetterBomban/posh-ulid) | [ahawker/ulid](https://github.com/ahawker/ulid) <br> [mdomke/python-ulid](https://github.com/mdomke/python-ulid) |

## xid

MongoDBのオブジェクトIDと互換性のある12バイトのIDで、Base32で20文字

> {Unixタイムスタンプ（4バイト）} {マシン識別子(3バイト)} {プロセスID(2バイト)} {ランダムな値で始まるカウンター(3バイト)}

| 正規表現       | Java                                                      | Python                                                    |
| -------------- | --------------------------------------------------------- | --------------------------------------------------------- |
| `[0-9a-v]{20}` | [0xShamil/java-xid](https://github.com/0xShamil/java-xid) | [graham/python_xid](https://github.com/graham/python_xid) |

---

Copyright (c) 2023 YA-androidapp(https://github.com/YA-androidapp) All rights reserved.
