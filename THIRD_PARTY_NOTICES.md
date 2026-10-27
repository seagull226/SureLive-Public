# 第三方声明 / Third-Party Notices

适用于 / Applies to SureLive 0.1.7.

## 中文

上游基线：asbplayer 提交 [`4b29212afa25d519286b2eeffd8a91dc18572f98`](https://github.com/asbplayer/asbplayer/commit/4b29212afa25d519286b2eeffd8a91dc18572f98)，采用 MIT 许可。Git 描述为 `v1.20.0-50-g4b29212a`，即 v1.20.0 之后的开发提交，不标为 v1.20.0 正式版。

SureLive 基于 [asbplayer](https://github.com/asbplayer/asbplayer) 进行集成与定制，由 SureLive Studio 独立维护，并非官方关联产品。asbplayer 的 MIT 版权及许可声明保留在扩展包的 `licenses/ASB-LICENSE.md` 中。

SureLive 使用第三方开源组件与语言资源，各组件保留其各自许可。扩展包的 `licenses/` 目录提供具体许可正文及声明，包括：

- **核心与词典资源**：asbplayer（MIT）、CMU 词典、ECDICT（MIT）、Roboto（Apache-2.0）、在线词典来源说明（FreeDictionaryAPI.com / Wiktionary CC BY-SA 4.0、DictionaryAPI.dev）。
- **多语种词频与词形参考**（见 `licenses/VOCABULARY-LEVELS-NOTICE.txt`）：
  - 法语：Lexique 3.83（Newmarch / Lexique.org，CC BY-SA 4.0，含 OpenLexicon / PolylexFLE LGPL-2.1 词条表参考）
  - 日语：wordfreq 3.1.1（Luminoso Technologies, Inc.，CC BY-SA 4.0 数据 / MIT 代码）与 mecab-ipadic v2.7.0-20070801（NAIST / Taku Kudo，BSD 类许可）
  - 西班牙语、德语、中文：wordfreq 3.1.1（CC BY-SA 4.0，含多源开源语料署名）
- **本地自然语言处理依赖**：wink-pos-tagger / wink-lexicon / wink-eng-lite-web-model（MIT）、compromise 及法/西/德插件（MIT）、日语分词相关组件（Apache-2.0 / MIT）。

lamejs 的适用 LGPL 条款、对应库源码、项目补丁、必要适配器、重新组合工具及相关调试许可随包提供，见 `licenses/LAMEJS-NOTICE.txt` 和 `licenses/lamejs-source-0.1.5.zip`。请按归档内说明替换库并重新组合。

词典查询卡保留来源及许可署名。多语种六档难度由 SureLive 根据公开语料词频独立计算，用于学习参考，不代表任何官方考试或课程等级认证。用户打开或导出的媒体仍适用其原有权利与使用条件。

## English

Upstream baseline: asbplayer commit [`4b29212afa25d519286b2eeffd8a91dc18572f98`](https://github.com/asbplayer/asbplayer/commit/4b29212afa25d519286b2eeffd8a91dc18572f98), under the MIT license. Its Git description is `v1.20.0-50-g4b29212a`, a development commit after v1.20.0 rather than the v1.20.0 release itself.

SureLive integrates and customizes [asbplayer](https://github.com/asbplayer/asbplayer) and is independently maintained by SureLive Studio, without official affiliation. The asbplayer MIT copyright and permission notice is retained in `licenses/ASB-LICENSE.md` in the extension package.

SureLive uses third-party open-source components and language resources under their respective licenses. The extension's `licenses/` directory provides applicable texts and notices, including:

- **Core and dictionary resources**: asbplayer (MIT), CMU dictionary, ECDICT (MIT), Roboto (Apache-2.0), and online dictionary attributions (FreeDictionaryAPI.com / Wiktionary CC BY-SA 4.0, DictionaryAPI.dev).
- **Multilingual frequency and lemma references** (see `licenses/VOCABULARY-LEVELS-NOTICE.txt`):
  - French: Lexique 3.83 (Newmarch / Lexique.org, CC BY-SA 4.0, with OpenLexicon / PolylexFLE LGPL-2.1 lexical table reference)
  - Japanese: wordfreq 3.1.1 (Luminoso Technologies, Inc., CC BY-SA 4.0 data / MIT code) and mecab-ipadic v2.7.0-20070801 (NAIST / Taku Kudo, permissive BSD-style license)
  - Spanish, German, and Chinese: wordfreq 3.1.1 (CC BY-SA 4.0, with multi-corpus attributions)
- **Local NLP dependencies**: wink-pos-tagger / wink-lexicon / wink-eng-lite-web-model (MIT), compromise and fr/es/de plugins (MIT), and Japanese tokenization components (Apache-2.0 / MIT).

Applicable LGPL terms for lamejs, corresponding library sources, project patches, the necessary adapter, recombination tools and associated debugging permission accompany the package. See `licenses/LAMEJS-NOTICE.txt` and `licenses/lamejs-source-0.1.5.zip`. Follow its instructions to substitute the library and recombine it.

Dictionary cards retain source and license attribution. Six-band vocabulary difficulty levels are independently computed by SureLive from open corpus frequencies for learning guidance and do not represent official exam or curriculum certification. Media that users open or export remains subject to its original rights and terms of use.
