<br/>
<div align="center">

A curated list of awesome Node.js Security resources.

![#](https://badgen.net/badge/tools/30+/blue)
![#](https://badgen.net/badge/incidents/15+/red)
![#](https://badgen.net/badge/educational/8+/green)

[![liran_tal](https://img.shields.io/twitter/url/https/twitter.com/liran_tal.svg?style=social&label=Follow%20%40Liran%20Tal)](https://twitter.com/liran_tal)

<br/>

<hr/>

<p>
  <a href="https://nodejs-security.com">
    <img alt="Node.js Security" align="center" src="https://img.shields.io/badge/%F0%9F%A6%84-Learn%20Node.js%20Security%E2%86%92-gray.svg?colorA=5734F5&colorB=5734F5&style=flat" />
  </a>
</p>

![Screenshot 2024-09-12 at 20 14 27](https://github.com/user-attachments/assets/586f3151-eed9-4542-92f1-de9237f6783c)

<p>
  Learn Node.js Secure Coding techniques and best practices from <a href="https://www.lirantal.com">Liran Tal</a>
</p>

</div>
<br/>

# Contents

- [Tools](#tools)
  - [Web Framework Hardening](#web-framework-hardening)
  - [Static Code Analysis](#static-code-analysis)
  - [Dynamic Application Security Testing](#dynamic-application-security-testing)
  - [Input/Output Validation](#input-validation--output-encoding)
  - [Secure Composition](#secure-composition)
  - [CSRF](#csrf)
  - [Vulnerabilities and Security Advisories](#vulnerabilities-and-security-advisories)
  - [Security Hardening](#security-hardening)
- [Data Sources](#data-sources)
- [Security Incidents](#security-incidents)
- [Educational](#educational)
  - [Hacking Playground](#hacking-playground)
  - [Articles](#articles)
  - [Research Papers](#research-papers)
  - [Books](#books)
  - [Roadmaps](#roadmaps)
- [Companies](#companies)

# Tools

## Web Framework Hardening
- [Helmet](https://www.npmjs.com/package/helmet) - Helmetは、様々なHTTPヘッダーを設定することで、Expressアプリのセキュリティを確保するのに役立ちます。
- [koa-helmet](https://www.npmjs.com/package/koa-helmet) - koa-helmetは、様々なHTTPヘッダを設定することで、Koaアプリの安全性を確保します。
- [fastify-helmet](https://github.com/fastify/fastify-helmet) - fastify-helmetは、重要なセキュリティヘッダを設定することで、[fastify](https://www.fastify.io/)アプリのセキュリティを確保するのに役立ちます。<div><sub>Stars: 405 / Last Update: 2024-09-30 / Initial Date: 2017-06-30</sub></div>
- [nuxt-security](https://github.com/Baroshem/nuxt-security) - OWASP Top 10とHelmetに基づくNuxt用🛡セキュリティモジュール。<div><sub>Stars: 812 / Last Update: 2024-09-27 / Initial Date: 2022-10-08</sub></div>
- [reporting-api](https://github.com/wille/reporting-api) - CSP、Reporting API v0 および v1 レポートをセットアップして収集し、ユーザが処理できるように確実に解析する。<div><sub>Stars: 1 / Last Update: 2024-09-21 / Initial Date: 2024-07-16</sub></div>

## GitHub Actions and CI/CD Security
- [New dependencies advisor](https://github.com/marketplace/actions/new-dependencies-advisor) - GitHub プルリクエストに、新しく追加された npm 依存関係のパッケージヘルス情報をコメントで追加するアクション。
- [OpenSSF Scorecard Monitor](https://github.com/marketplace/actions/openssf-scorecard-monitor) - 自動化されたマークダウンおよび JSON レポートと、オプションの GitHub 課題アラートにより、組織内での OpenSSF スコアカードの追跡を簡素化します。

## Static Code Analysis
- [eslint-plugin-security](https://www.npmjs.com/package/eslint-plugin-security) - ノードセキュリティのためのESLintルール。このプロジェクトは潜在的なセキュリティ・ホットスポットを特定するのに役立ちますが、人間によるトリアージが必要な多くの誤検出を見つけます。
- [tslint-plugin-security](https://www.npmjs.com/package/tslint-config-security) - ノードセキュリティのためのTSLintルール。このプロジェクトは潜在的なセキュリティのホットスポットを特定するのに役立ちますが、人間によるトリアージが必要な誤検出を多く見つけます。
- [safe-regex](https://www.npmjs.com/package/safe-regex) - 星の高さを1に制限することで、破滅的な指数時間正規表現の可能性を検出する。
- [vuln-regex-detector](https://www.npmjs.com/package/vuln-regex-detector) - このモジュールを使うと、正規表現の脆弱性をチェックすることができる。JavaScriptでは、正規表現(regex)は "脆弱 "である可能性があります。アプリケーションがクライアント側で使われる場合、これはパフォーマンスの問題になります。サーバ側では、正規表現サービス拒否(REDOS)にさらされる可能性があります。
- [DevSkim](https://github.com/Microsoft/DevSkim) - DevSkimは、セキュリティの「リンティング」機能を提供するIDEプラグインとルールのセットです。また、CI/CDパイプラインに統合できるようにCLIもサポートしています。<div><sub>Stars: 902 / Last Update: 2024-10-02 / Initial Date: 2016-08-03</sub></div>
- [ban-sensitive-files](https://github.com/bahmutov/ban-sensitive-files) - Git に機密ファイルを保存しないように、コミットするファイル名をファイル名ルールのライブラリと照合します。機密性の高い内容のファイルをチェックします (例えば .npmrc ファイル内の authToken など)。<div><sub>Stars: 63 / Last Update: 2024-09-27 / Initial Date: 2015-12-01</sub></div>
- [NodeSecure CLI](https://github.com/NodeSecure/cli) - Node.jsのCLIで、指定したnpmパッケージやディレクトリの依存関係ツリーを深く分析することができる。<div><sub>Stars: 368 / Last Update: 2024-10-01 / Initial Date: 2019-07-02</sub></div>
- [lockfile-lint](https://github.com/lirantal/lockfile-lint) - lint lockfilesでセキュリティと信頼ポリシーを改善し、悪意のあるパッケージインジェクションやその他の安全でない設定からクリーンな状態を保つ。<div><sub>Stars: 782 / Last Update: 2024-09-12 / Initial Date: 2019-06-01</sub></div>
- [semgrep](https://semgrep.dev) - オープンソースで、オフラインで、多くの言語用にカスタマイズしやすい静的解析。このリストの他のいくつか（NodeJSScan）は、semgrepをエンジンとして使用しています。
- [js-x-ray](https://github.com/NodeSecure/js-x-ray) - JavaScriptとNode.jsのSASTスキャナーは、様々なよく知られた悪意のあるコードパターン（安全でないインポート、安全でないstmt、安全でないRegEx、エンコードされたリテラル、最小化されたコード、難読化されたコード）を検出することができます。<div><sub>Stars: 224 / Last Update: 2024-10-01 / Initial Date: 2020-03-26</sub></div>
- [cspscanner](https://cspscanner.com/) - CSP Scannerは、開発者やセキュリティ専門家がサイトのコンテンツ・セキュリティ（CSP）を簡単に検査・評価できるようにします。
- [sdc-check](https://github.com/mbalabash/sdc-check) - プロジェクトの依存関係リストの潜在的なリスクを知らせる小さなツール<div><sub>Stars: 139 / Last Update: 2023-11-21 / Initial Date: 2022-03-25</sub></div>
- [fix-lockfile-integrity](https://github.com/yoavain/fix-lockfile-integrity) - npm lockfileの弱い整合性ハッシュ(sha1)をより安全な整合性ハッシュ(sha512)に修正するCLIツール。<div><sub>Stars: 5 / Last Update: 2024-10-01 / Initial Date: 2022-09-09</sub></div>
- [Bearer](https://github.com/Bearer/bearer) - OWASP Top 10に従ったコードのセキュリティとプライバシーのリスクを見つけ、修正するためのCLIツール。<div><sub>Stars: 2.0k / Last Update: 2024-09-30 / Initial Date: 2022-09-27</sub></div>
- [GuardDog](https://github.com/DataDog/guarddog) - GuardDogは、悪意のあるPyPIとnpmパッケージを識別するCLIツールです。<div><sub>Stars: 592 / Last Update: 2024-10-03 / Initial Date: 2022-06-14</sub></div>

## Dynamic Application Security Testing

- [PurpleTeam](https://purpleteam-labs.com) - ビルドパイプラインに挿入するのに最適なセキュリティ回帰テストSaaSとCLIです。purpleteamは賢いので、テスト方法を知っています。

## Input Validation & Output Encoding
- [node-esapi](https://www.npmjs.com/package/node-esapi) - node-esapi は ESAPI4JS (Enterprise Security API for JavaScript) エンコーダの最小移植版です。
- [escape-html](https://www.npmjs.com/package/escape-html) - HTMLで使用するエスケープ文字列。
- [js-string-escape](https://www.npmjs.com/package/js-string-escape) - 任意の文字列を二重引用符または一重引用符で囲み、有効なJavaScript文字列リテラルとしてエスケープする。
- [validator](https://github.com/chriso/validator.js) - 文字列バリデータとサニタイザーの npm ライブラリ。<div><sub>Stars: 23.0k / Last Update: 2024-10-01 / Initial Date: 2010-10-06</sub></div>
- [xss-filters](https://www.npmjs.com/package/xss-filters) - XSSを防ぐのに十分な出力フィルタリング！
- [DOMPurify](https://github.com/cure53/DOMPurify) - HTML、MathML、SVG用の、DOMのみの、超高速、超耐性のXSSサニタイザーです。<div><sub>Stars: 13.8k / Last Update: 2024-09-26 / Initial Date: 2014-02-17</sub></div>
- [envalid](https://github.com/af/envalid) - Envalidは、Node.jsで環境変数を検証しアクセスするための小さなライブラリです。<div><sub>Stars: 1.4k / Last Update: 2024-09-23 / Initial Date: 2012-11-29</sub></div>
- [data-guardian](https://www.npmjs.com/package/data-guardian) - data-guardianは小さな、高度にカスタマイズ可能なライブラリで、任意のエンティティの機密データをマスクすることができ、[OWASP Protect Data everywhere](https://owasp.org/www-project-proactive-controls/v3/en/c8-protect-data-everywhere)を支援することができます。

## Secure Composition
- [pug-plugin-trusted-types](https://www.npmjs.com/package/pug-plugin-trusted-types) - Pugテンプレート・プラグインは、信頼できない入力からHTMLを安全に作成し、CSPとCSRF [automagic](https://www.npmjs.com/package/pug-plugin-trusted-types#hdr-automagic)を提供します。
- [safesql](https://www.npmjs.com/package/safesql) - SQLインジェクション](https://www.oreilly.com/library/view/securing-node-applications/9781491982426/ch01.html#idm140399946848800)を防ぐために、[Postgres](https://www.npmjs.com/package/safesql#pg)と[MySQL](https://www.npmjs.com/package/safesql#mysql)のクエリ文法を理解するタグ付きテンプレート(<code>mysql`...˶`</code>)。
- [sh-template-tag](https://www.npmjs.com/package/sh-template-tag) - Bash構文を理解するタグ付きテンプレート(<code>shh`...˶`</code>)は、[シェルインジェクション](https://www.oreilly.com/library/view/securing-node-applications/9781491982426/ch01.html#idm140399951358480)を防止します。

## CSRF
- [csurf](https://www.npmjs.com/package/csurf) - Node.js CSRF 保護ミドルウェア。
- [fastify-csrf](https://github.com/fastify/fastify-csrf) - fastify](https://www.fastify.io)にCSRF保護を追加するプラグイン。<div><sub>Stars: 146 / Last Update: 2024-09-22 / Initial Date: 2019-01-07</sub></div>

## Vulnerabilities and Security Advisories
- [npq](https://github.com/lirantal/npq) - インストールプロセスの一部としてパッケージを監査することで、npmまたはyarnを使用して安全にパッケージをインストールします。<div><sub>Stars: 943 / Last Update: 2024-09-12 / Initial Date: 2017-12-14</sub></div>
- [snyk](https://www.npmjs.com/package/snyk) - Snyk は、Node.js npm、Ruby、および Java の依存関係における既知の脆弱性の検出、修正、および監視を、アドホックに、または CI (Build) システムの一部として支援します。
- [node-release-lines](https://www.npmjs.com/package/node-release-lines) - Node.js リリースメタデータのための Introspection API。各リリースの詳細とともに、リリースライン、相対的なステータスに関する情報を提供します。
- [auditjs](https://github.com/OSSIndex/auditjs) - NPM の package.json ファイルを監査し、[OSSIndex](https://ossindex.sonatype.org/rest) を使って既知の脆弱性を特定します。<div><sub>Stars: 224 / Last Update: 2024-06-19 / Initial Date: 2015-09-01</sub></div>
- [npm-audit](https://docs.npmjs.com/cli/audit) - npm を使って、package.json に基づいてセキュリティ監査を実行します。
- [npm-audit-resolver](https://www.npmjs.com/package/npm-audit-resolver) - 明確で監査可能な方法で特定の問題を無視するオプションを含む、npm-auditの結果を管理します。
- [patch-package](https://www.npmjs.com/package/patch-package) - アプリの作者は、パッチを作成して適用することで、forkしたりマージされたPRを待ったりすることなく、(node_modules内の)npm依存性の修正を作成できるようになります。
- [is-website-vulnerable](https://github.com/lirantal/is-website-vulnerable/) - は、ウェブサイトのフロントエンドJavaScriptライブラリに公知のセキュリティ脆弱性を発見する。<div><sub>Stars: 1.9k / Last Update: 2024-09-12 / Initial Date: 2019-10-05</sub></div>
- [joi-security](https://github.com/Saluki/joi-security/) - Joi検証スキーマのセキュリティ欠陥を検出する。<div><sub>Stars: 45 / Last Update: 2024-06-16 / Initial Date: 2020-04-14</sub></div>
- [nodejs-cve-checker](https://github.com/nodejs/nodejs-cve-checker) - Node.jsのセキュリティリリース後にNVDに公開されたCVEを検証するシンプルなツールです。<div><sub>Stars: 6 / Last Update: 2024-03-11 / Initial Date: 2023-12-11</sub></div>

## Security Hardening
- [hijagger](https://github.com/firefart/hijagger) - npm と PyPI のすべてのパッケージのメンテナに、ドメイン再登録による乗っ取り可能なパッケージがないかチェックします。<div><sub>Stars: 286 / Last Update: 2024-10-02 / Initial Date: 2022-06-01</sub></div>
- [express-limiter](https://www.npmjs.com/package/express-limiter) - redis上に構築されたExpressアプリケーション用のレート制限ミドルウェア。
- [limits](https://www.npmjs.com/package/limits) - シンプルな express/connect ミドルウェアで、アップロードサイズの制限やリクエストタイムアウトの設定などが可能。
- [rate-limiter-flexible](https://www.npmjs.com/package/rate-limiter-flexible) - プロセスメモリ、クラスタ、Redis、MongoDb、MySQL、PostgreSQLにおいて、キーによる高速で柔軟かつフレンドリーなレートリミッタと、DDoSや総当たり攻撃からの保護。ExpressとKoaの例が含まれています。
- [fastify-rate-limit](https://github.com/fastify/fastify-rate-limit) A low overhead rate limiter for your routes.
- [secure-json-parse](https://github.com/fastify/secure-json-parse) `JSON.parse()` drop-in replacement with prototype poisoning protection.
- [ses](https://github.com/endojs/endo/tree/master/packages/ses#ses) A shim for Hardened JavaScript, a language mode that mitigates prototype pollution attacks and supports safely confining multiple tenants in a single JavaScript realm, endowing each other with hardened API objects.
- [lavamoat](https://github.com/lavamoat/lavamoat) Mitigates supply chain attacks using `ses` to confine third-party dependencies and limit their access to host powers based on policies generated by trust-on-first-use static analysis.
- [moddable](https://www.moddable.com/) Implements Hardened JavaScript as the security model for embedded systems.
- [is-my-node-vulnerable](https://github.com/RafaelGSS/is-my-node-vulnerable) - このパッケージは、Node.js のインストールが既知のセキュリティ脆弱性に対して脆弱かどうかをチェックします。<div><sub>Stars: 125 / Last Update: 2024-09-17 / Initial Date: 2023-01-20</sub></div>

# Data Sources

- [resource](https://nodejs.org/dist/index.json) - Node.jsの全バージョン、バイナリビルド、含まれる依存関係（npm、zlib、openssl）とそのバージョン、リリースがセキュリティリリースかどうか、LTSかどうかを構造化したリスト。
- [resource](https://github.com/nodejs/security-wg/tree/main/vuln/core) - nodejs/secuirty-wg`のGitHubリポジトリは、Node.jsのランタイムバージョンに適用されたすべてのCVEを含む`/vuln/core`ディレクトリを管理しています。

# Security Incidents

## Protestware supply chain security issues

The following is a list of known protestware spanning across other ecosystems too:
- [PyPI package author of atomicwrites deletes his own code](https://www.bleepingcomputer.com/news/security/pypi-mandates-2fa-for-critical-projects-developer-pushes-back/) 
- [left-pad](https://qz.com/646467/how-one-programmer-broke-the-internet-by-deleting-a-tiny-piece-of-code/)
- `event-source-polyfill`, Mariusz Nowak and their `es5-ext`, Evan Jacobs and their `styled-components`, [node-ipc](https://snyk.io/blog/peacenotwar-malicious-npm-node-ipc-package-vulnerability/), `peacenotwar`, [nestjs-pino](https://socket.dev/npm/package/nestjs-pino/files/3.1.1/postinstall.js) - ロシアとウクライナの危機に関して。

Articles covering the topics around protestware are:
- [2022's Techcrunch protestware review](https://techcrunch.com/2022/07/27/protestware-code-sabotage/)
- [2022's Snyk protestware types](https://snyk.io/blog/protestware-open-source-types-impact/)

## npm and JavaScript specific security incidents and supply chain security issues

Collection of security incidents that happened in the Node.js, JavaScript and npm related communities with supporting articles:

| Date              | Name                                                                                                                                                            | Reference Links                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|-------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 2024 July 16  | `string-width-cjs` and other Suspicious Maintainer Unveils Threads of npm Supply Chain Attack | [Snyk](https://snyk.io/blog/threads-of-npm-supply-chain-attack/)
| 2024 July 11  | `noblox-ts` starjacking and QuasarRAT on npm | [stacklok](https://stacklok.com/blog/destroyloneliness-npm-starjacking-attack-on-roblox-nodejs-library-delivers-quasarrat)
| 2024 June 17  | `ua-parser-js` switches to AGPL+commercial in "rug pull" move | [Adventures in Nodeland](https://adventures.nodeland.dev/archive/what-happens-when-a-major-npm-library-goes/)
| 2024 June 11  | `cors-parser` npm package hides cross-platform backdoor in PNG files | [Sonatype](https://www.sonatype.com/blog/cors-parser-npm-package-hides-cross-platform-backdoor-in-png-files)
| 2024 June 03  | npm regsitry cache poisoning attack | [landh.tech](https://www.landh.tech/blog/20240603-npm-cache-poisoning/)
| 2024 Apr 26   | Fake job interviews target developers with new Python backdoor | [Bleeping Computer](https://www.bleepingcomputer.com/news/security/fake-job-interviews-target-developers-with-new-python-backdoor/)
| 2024 April 16 | Tea tokens and developers abusing OSS infrastructure for monetization | [Sonatype](https://www.sonatype.com/blog/devs-flood-npm-with-10000-packages-to-reward-themselves-with-tea-tokens)
| 2024 Feb 6    | noblox.js-proxy-server malicious npm Package Masquerades as Noblox.js, Targeting Roblox Users for Data Theft | [Socket](https://socket.dev/blog/malicious-npm-package-masquerades-as-noblox-js)
| 2024 Jan 25   | npm flooded with 748 packages that store movies | [Sonatype](https://blog.sonatype.com/npm-flooded-with-748-packages-that-store-movies)
| 2024 Jan 3    | An `everything` package with a registry-wide dependencies prevents from packages to be unpublished | [SC Media](https://www.scmagazine.com/news/npm-registry-prank-leaves-developers-unable-to-unpublish-packages)
| 2023 Dec 14   | Ledger supply chain security attack introducing crypto drainer malware (@ledgerhq/connect-kit) | [Sonatype](https://blog.sonatype.com/decrypting-the-ledger-connect-kit-compromise-a-deep-dive-into-the-crypto-drainer-attack), Tweets [1](https://twitter.com/Neodyme/status/1735337711555285261) [2](https://twitter.com/Ledger/status/1735370531224834430) [3](https://x.com/josephdelong/status/1735293295301972022?s=20) [4](https://twitter.com/Mudit__Gupta/status/1735301007188406681) [5](https://twitter.com/FrankResearcher/status/1735286837088792794) [6](https://twitter.com/Ledger/status/1735326240658100414) [7](https://twitter.com/AndrewMohawk/status/1735290127084105743) [8](https://twitter.com/bantg/status/1735279127752540465) 
| 2023 Sep 27   | Spoofed Dependabot commits steal GitHub tokens and inject malware to JavaScript files | [Checkmarx](https://checkmarx.com/blog/surprise-when-dependabot-contributes-malicious-code/)
| 2023 Jun 27   | Manifest Confusion - パッケージ・メタデータの不整合を示すnpmパッケージ・マネージャの新たな公開されたバグ｜ [Darcy Clarkeのブログ](https://blog.vlt.sh/blog/the-massive-hole-in-the-npm-ecosystem)
| 2023 Jun 23   | North Korean attackers exploit social engineering and supply chain attacks on npm | [Phylum](https://blog.phylum.io/junes-sophisticated-npm-attack-attributed-to-north-korea/)
| 2023 Jun 15   | Supply Chain Attack Exploits Abandoned S3 Buckets to Distribute Malicious Binaries for [bignum npm package](https://www.npmjs.com/package/bignum?activeTab=versions) | [The Hacker News](https://thehackernews.com/2023/06/new-supply-chain-attack-exploits.html), [Checkmarx](https://checkmarx.com/blog/hijacking-s3-buckets-new-attack-technique-exploited-in-the-wild-by-supply-chain-attackers/)
| 2023 Jun 06   | Recommended packages by ChatGPT may be exploited for supply chain security attack vector| [Vulcan](https://vulcan.io/blog/ai-hallucinations-package-risk)
| 2023 Feb 16   | Researchers Hijack Popular NPM Package with Millions of Downloads | [Illustria on The Hacker News](https://thehackernews.com/2023/02/researchers-hijack-popular-npm-package.html)
| 2023 Feb 10   | Researchers Uncover Obfuscated Malicious Code in PyPI Python Packages, affiliated npm ecosystem evidence too | [The Hacker News](https://thehackernews.com/2023/02/researchers-uncover-obfuscated.html)
| 2023 Jan 29   | Phylum Identifies 137 Malicious npm Packages | [phylum](https://blog.phylum.io/phylum-identifies-98-malicious-npm-packages)
| 2022 Nov 29   | Invisible npm malware may hide in crafted versions and bypass npm audit's security checks | [JFrog](https://jfrog.com/blog/invisible-npm-malware-evading-security-checks-with-crafted-versions/)
| 2022 Nov 24   | Phylum team captures captures malicious npm package imagecompress-mini claims to be an image compress tool | [Louisw Lang on Twitter](https://twitter.com/LouiswLang/status/1595835195382534144)
| 2022 Oct 12   | Aqua security discovers flaw in npm that allows disclosing of privately hosted npm packages on the registry | [Aqua](https://blog.aquasec.com/private-packages-disclosed-via-timing-attack-on-npm) 
| 2022 Oct 07   | LofyGang Distributed ~200 Malicious NPM Packages to Steal Credit Card Data | [TheHackerNews](https://thehackernews.com/2022/10/lofygang-distributed-200-malicious-npm.html)
| 2022 Sep 23    |  Popular Cryptocurrency Exchange dYdX Has Had Its NPM Account Hacked | [Mend](https://www.mend.io/resources/blog/popular-cryptocurrency-exchange-dydx-has-had-its-npm-account-hacked/)
| 2022 Jul 29    | malicious packages `small-sm`, `pern-valids`, `lifeculer`, and `proc-title` target stealing credit card information and discord tokens | [darkreading](https://www.darkreading.com/risk/malicious-npm-packages-discord-tokens-credit-card)
| 2022 May 26    | stolen oAuth GitHub tokens lead to npm security breach, compromised user accounts metadata, private packages, and plain-text passwords in logs | [GitHub](https://github.blog/2022-05-26-npm-security-update-oauth-tokens/)
| 2022 May 24    | malicious npm packages exploiting dependency confusion attacks | [Snyk](https://snyk.io/blog/snyk-200-malicious-npm-packages-cobalt-strike-dependency-confusion-attacks/), [Snyk](https://snyk.io/blog/npm-dependency-confusion-attack-gxm-reference/)
| 2022 May 23    | npm packages hijacked due to expired domains | [TheRegister](https://www.theregister.com/2022/05/23/npm_dependencies_vulnerable/)
| 2022 April 05  | New npm Flaws Let Attackers Better Target Packages for Account Takeover | [Aqua](https://blog.aquasec.com/npm-supply-chain-attack)
| 2022 April 26  | npm package planting | [Aqua](https://blog.aquasec.com/npm-package-planting), [The Hacker News](https://thehackernews.com/2022/04/npm-bug-allowed-attackers-to-distribute.html)
| 2022 March 31  | More protestware from `styled-components` | [Checkmarx Security blog](https://checkmarx.com/blog/new-protestware-found-lurking-in-highly-popular-npm-package/)
| 2022 March 18  | More protestware from `es5-ext` and `event-source-pollyfill`  | [Snyk advisory for event-source-pollyfill](https://security.snyk.io/vuln/SNYK-JS-EVENTSOURCEPOLYFILL-2429580), [es5-ext commit](https://github.com/medikoo/es5-ext/commit/28de285ed433b45113f01e4ce7c74e9a356b2af2), [ArsTechnica](https://arstechnica.com/information-technology/2022/03/sabotage-code-added-to-popular-npm-package-wiped-files-in-russia-and-belarus/) |
| 2022 March 16  | `peacenotwar` module sabotages npm developers in the `node-ipc` package to protest the invasion of Ukraine | [Snyk blog](https://snyk.io/blog/peacenotwar-malicious-npm-node-ipc-package-vulnerability), [Darkreading](https://www.darkreading.com/application-security/recent-code-sabotage-incident-latest-to-highlight-code-dependency-risks), [SC Magazine](https://www.scmagazine.com/analysis/application-security/what-happens-when-protestware-sabotages-open-source-in-response-to-current-events) |
| 2022 March 7  | Malicious packages caught exfiltrating data via legit webhook services | [Checkmarx Security blog](https://medium.com/checkmarx-security/webhook-party-malicious-packages-caught-exfiltrating-data-via-legit-webhook-services-6e046b07d191) |
| 2022 February 22  | 25 Malicious JavaScript Libraries due to typosquatting attacks | [TheHackerNews](https://thehackernews.com/2022/02/25-malicious-javascript-libraries.html) |
| 2022 February 11  | 2,818 npm accounts use email addresses with expired domains | [TheRecord](https://therecord.media/thousands-of-npm-accounts-use-email-addresses-with-expired-domains) |
| 2021 December 08  | 17 JavaScript libraries contained malicious code to collect and steal Discord access tokens and environment variables from users’ computers -                   | [TheRecord](https://therecord.media/malicious-npm-packages-caught-stealing-discord-tokens-environment-variables/)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| 2021 December 01  | The Bladabindi trojan and RAT malware | [Sonatype](https://blog.sonatype.com/bladabindi-njrat-rat-in-jdb.js-npm-malware) |
| 2021 November 04  | coa and rc packages - 人気のnpmライブラリ「coa」が本日乗っ取られ、悪意のあるコードが注入され、世界中のReactパイプラインに刹那的な影響を与えている｜[Bleepingcomputer](https://www.bleepingcomputer.com/news/security/popular-coa-npm-library-hijacked-to-steal-user-passwords), [the record](https://therecord.media/malware-found-in-coa-and-rc-two-npm-packages-with-23m-weekly-downloads/), [npm tweet](https://twitter.com/npmjs/status/1456310627362742284), [npm tweet for rc](https://twitter.com/npmjs/status/1456398505832976384).                                                                                                                                                                                                                                                                                      |
| 2021 October 27   | noblox.js-proxy and noblox.js - roblox 公式 API および SDK のユーザーを対象とした npm パッケージ (noblox.js) の typosquatted｜[the register](https://www.theregister.com/2021/10/27/npm_roblox_ransomware) ｜ Developers.IO
| 2021 October 22   | ua-parser-js - ua-parser-jsという名前の人気のあるNPMパッケージのバージョンに悪意のあるコードが含まれていることが判明｜[Cybersecurity and Infrastructure Security Agency (CISA)](https://us-cert.cisa.gov/ncas/current-activity/2021/10/22/malware-discovered-popular-npm-package-ua-parser-js), [github issue](https://github.com/faisalman/ua-parser-js/issues/536), [IOCs](https://twitter.com/BleepinComputer/status/1451964720974635021?s=20), [portswigger](https://portswigger.net/daily-swig/popular-npm-package-ua-parser-js-poisoned-with-cryptomining-password-stealing-malware), [theregister](https://www.theregister.com/2021/10/27/npm_roblox_ransomware)｜。
| 2021 September 02 | pac-resolver - がHTTPリクエストを行おうとするたびに、ローカルネットワーク上の脅威行為者がNode.jsプロセス内で任意のコードを実行できるようになる可能性がある｜ [arstechnica.com](https://arstechnica.com/information-technology/2021/09/npm-package-with-3-million-weekly-downloads-had-a-severe-vulnerability/)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| 2021 August 07    | npm package ownership process firing back and exposing potential vectors for supply chain security risks.                                                       | [Twitter](https://twitter.com/Andrewmd5/status/1423915732979437571)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| 2021 April 13  |  New Linux, macOS malware hidden in fake Browserify NPM package: web-browserify | [Bleepingcomputer](https://www.bleepingcomputer.com/news/security/new-linux-macos-malware-hidden-in-fake-browserify-npm-package).                                                                                                                                                                 |
| 2020 December 02  | **jdb.js - db-json.js**
| 2020 November 09  | **discord malicious npm package** - Npmパッケージが機密性の高いDiscordとブラウザのファイルを盗んでいたことが発覚｜[sonatype](https://blog.sonatype.com/discord.dll-successor-to-npm-fallguys-), [zdnet](https://www.zdnet.com/article/npm-package-caught-stealing-sensitive-discord-and-browser-files/)。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| 2020 November 03  | **twilio-npm** - 悪意のあるnpmパッケージがプログラマーのコンピューターにバックドアを開く                                                                               | [zdnet](https://www.zdnet.com/article/malicious-npm-package-opens-backdoors-on-programmers-computers)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| 2020 August 29    | **fallguys** - 悪意のあるパッケージが機密ファイルを盗む                                                                                                      | [zdnet](https://www.zdnet.com/article/malicious-npm-package-caught-trying-to-steal-sensitive-discord-and-browser-files/)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| 2020 April 27     | **is-promise** - エコシステムを壊すワンライナーライブラリ                                                                                                         | [フォーブス・リンデッセイ
| 2019 August 22    | **bb-builder** - Windows システムを標的とし、情報を流出させ、リモートサービスに送信する悪意のあるパッケージ。                                            | [Snyk](https://snyk.io/vuln/SNYK-JS-BBBUILDER-460132), [Reversing Labs](https://blog.reversinglabs.com/blog/the-npm-package-that-walked-away-with-all-your-passwords), [Bleeping Computer](https://www.technadu.com/malicious-package-stealing-user-credentials-npm-repository/77482/)                                                                                                                                                                                                                                                                                                                                                                                        |
| 2019 June 05      | **EasyDEX-GUI** - npm パッケージの event-stream に悪意のあるコードが見つかりました。                                                                                             | [npm](https://blog.npmjs.org/post/185397814280/plot-to-steal-cryptocurrency-foiled-by-the-npm), [snyk](https://snyk.io/blog/yet-another-malicious-package-found-in-npm-targeting-cryptocurrency-wallets), [komodo announcement](https://komodoplatform.com/update-agama-vulnerability/) |.
| 2018 November 27  | **event-stream** - npmパッケージのevent-streamに悪意のあるコードが見つかった。                                                                                            | [github issue](https://github.com/dominictarr/event-stream/issues/116) [snyk](https://snyk.io/blog/malicious-code-found-in-npm-package-event-stream), [snykの事後報告](https://snyk.io/blog/a-post-mortem-of-the-malicious-event-stream-backdoor), [schneid](https://schneid.io/blog/event-stream-vulnerability-explained/), [intrinsic](https://medium.com/intrinsic/compromised-npm-package-event-stream-d47d08605502), [npm](https://blog.npmjs.org/post/180565383195/details-about-the-event-stream-incident), [jayden](https://jaydenseric.com/blog/event-stream-compromise), [hillel wayneの事後報告](https://www.hillelwayne.com/post/stamping-on-eventstream/) |
| 2018 July 12      | **eslint** - npm パッケージ eslint-scope と eslint-config-eslint に悪意のあるパッケージが見つかった。                                                                     | [github issue](https://github.com/eslint/eslint-scope/issues/39), [eslint tweet](https://twitter.com/geteslint/status/1017419074136092673?lang=en), [eslintの事後報告](https://eslint.org/blog/2018/07/postmortem-for-malicious-package-publishes), [nodesourceの事後報告](https://nodesource.com/blog/a-high-level-post-mortem-of-the-eslint-scope-security-incident/), [npmの声明](https://status.npmjs.org/incidents/dn7c1fgrr7ng) |.
| 2018 May 02       | **getcookies** - 悪意のあるパッケージ getcookies が上位の express 関連パッケージに埋め込まれる。                                                           | [GitHub issue](https://github.com/RocketChat/Rocket.Chat/issues/10641), [npm](https://blog.npmjs.org/post/173526807575/reported-malicious-module-getcookies), [bleepingcomputer.com](https://www.bleepingcomputer.com/news/security/somebody-tried-to-hide-a-backdoor-in-a-popular-javascript-npm-package/), [Snyk's getcookies vulnerability page](https://snyk.io/vuln/npm:getcookies:20180502), [Hacker News](https://news.ycombinator.com/item?id=16975025) |
| 2018 Feb 13    | maintainer account with access to conventional-changelog npm package compromised and published malware for 1 day and 11 hours | [conventional-changelog repository update](https://github.com/conventional-changelog/conventional-changelog/issues/282#issuecomment-365367804)
| 2017 August 02    | **crossenv** - 悪質なタイポスクワットパッケージcrossenvが環境変数を盗む。                                                                           | [CJ blog on typosquat packages](https://medium.com/@ceejbot/crossenv-malware-on-the-npm-registry-45c7dc29f6f5), [Typosquatting research paper](https://incolumitas.com/2016/06/08/typosquatting-package-managers/), [bleepingcomputer.com](https://www.bleepingcomputer.com/news/security/javascript-packages-caught-stealing-environment-variables/), [Snyk's crossenv vulnerability page](https://snyk.io/vuln/npm:crossenv:20170802), [Hacker News](https://news.ycombinator.com/item?id=14901566) |.
| 2016 March 22     | **left-pad** - ある開発者が11行のJavaScriptでNode、Babel、そして何千ものプロジェクトをどのように壊したか。                                                         | [left-pad.io](http://left-pad.io), [The Register](https://www.theregister.co.uk/2016/03/23/npm_left_pad_chaos), [qurtaz](https://qz.com/646467/how-one-programmer-broke-the-internet-by-deleting-a-tiny-piece-of-code).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |




Follow-up notes:
* A resource for malicious incidents is [BadJS](https://badjs.org/) - ウェブサイト、拡張機能、npmパッケージなど、JavaScriptが存在するあらゆる場所で発見された悪意のあるJavaScriptのリポジトリです。

# Educational

## Newsletters
 - [【Node.jsセキュリティ・メルマガ】(https://newsletter.nodejs-security.com/)

## Articles
 - [A Roadmap for Node.js Security](https://node-sec-roadmap-fyi.uc.r.appspot.com/) (オリジナルドメイン https://nodesecroadmap.fyi/ はありません。42](https://github.com/lirantal/awesome-nodejs-security/issues/42)を参照)
 - [10のnpmセキュリティ・ベスト・プラクティス](https://snyk.io/blog/ten-npm-security-best-practices/)
 - [OWASPチートシートシリーズ
 - [バックドアとは何か Node.jsで作ってみよう】(https://snyk.io/blog/what-is-a-backdoor/)
 - [悪意のあるパッケージの解剖](https://blog.phylum.io/malicious-javascript-code-in-npm-malware/)
 - [なぜnpmのロックファイルは悪意あるモジュールを注入するためのセキュリティ上の盲点になりうるのか](https://snyk.io/blog/why-npm-lockfiles-can-be-a-security-blindspot-for-injecting-malicious-modules/)
 - [npmパッケージを安全に公開するためのGitHubアクション](https://snyk.io/blog/github-actions-to-securely-publish-npm-packages/)
 - [Top 11 Node.js security best practices | Sqreen.com](https://blog.sqreen.com/nodejs-security-best-practices/)
 - (試作品)中毒の話](https://www.fastify.io/docs/latest/Guides/Prototype-Poisoning/)
 - [GitHub orgのセキュリティ確保](https://dev.to/nodesecure/securize-your-github-org-4lb7)

## Research Papers
 - [Visual Studio Code拡張機能のセキュリティ脆弱性を深く掘り下げる】(https://snyk.io/blog/visual-studio-code-extension-security-vulnerabilities-deep-dive)

## Books
- [Secure Your Node.js Web Application: Keep Attackers Out and Users Happy](https://www.amazon.com/Secure-Your-Node-js-Web-Application-ebook/dp/B01BPPUP30) by Karl Duuna, 2016
- [Essential Node.js Security](https://leanpub.com/nodejssecurity) by Liran Tal, 2017 - Node.jsのWebアプリケーションのセキュリティを確保するための実践的なガイドで、ソースコードが豊富です。
- [Securing Node JS Apps
](https://leanpub.com/securingnodeapps) by Ben Edmunds, 2016 - シニア開発者が長年の経験で培ったセキュリティの基本を、このハンドブックに凝縮しました。
- [Web Developer Security Toolbox
](https://leanpub.com/b/webdevelopersecuritytoolbox) - Node.jsとWebセキュリティの書籍がバンドルされています。
- [Thomas Gentilhomme](https://github.com/fraxken) book: [Become a Node.js Developer](https://github.com/fraxken/ebook_nodejs)
- [Node.js Secure Coding: Defending Against Command Injection Vulnerabilities](https://www.nodejs-security.com/book/command-injection/)
- [Node.js Secure Coding: Prevention and Exploitation of Path Traversal Vulnerabilities](https://www.nodejs-security.com/book/path-traversal)
- [Node.js Secure Coding: Mitigate and Weaponize Code Injection Vulnerabilities](https://www.nodejs-security.com/book/code-injection)

## Roadmaps
  - [Node.js開発者ロードマップ](https://roadmap.sh/nodejs)

# Companies
- [Snyk](https://snyk.io) - 開発者ファーストのソリューションで、依存関係の脆弱性の発見と修正を自動化します。
- [Sqreen](https://sqreen.io) - ウェブアプリケーションのセキュリティを自動化
- [NodeSource](https://nodesource.com) - ミッションクリティカルな Node.js アプリケーション。N|Solid および Node 認定モジュールを提供します。
- [GuardRails](https://www.guardrails.io) - プルリクエストに即座にセキュリティフィードバックを与えるGitHubアプリ。
- [NodeSecure](https://github.com/NodeSecure) - フリーでオープンソースのJavaScript/Node.jsセキュリティツールを構築する開発者の団体。

## Hacking Playground
 - [OWASPジュースショップ](https://github.com/bkimminich/juice-shop)<div><sub>Stars: 10.3k / Last Update: 2024-09-28 / Initial Date: 2014-09-19</sub></div>
 - [ドムゴート](https://domgo.at/cxss/intro)

# Contributing
Found an awesome project, package, article, other type of resources related to Node.js Security? Send me a pull request!
Just follow the [guidelines](/CONTRIBUTING.md). Thank you!

---
say *hi* on [Twitter](https://twitter.com/liran_tal)

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
