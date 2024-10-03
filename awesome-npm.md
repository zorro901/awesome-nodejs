# Awesome npm [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [<img src="https://github.com/npm/logos/blob/7fb0bc425e0dac1bab065217c4ed595594448db4/npm-transparent.png" width="200" align="right" alt="npm">](https://www.npmjs.com)

> Awesome [npm](https://www.npmjs.com) resources and tips

[npm](https://en.wikipedia.org/wiki/Npm_(software)) is a package manager for the JavaScript programming language and comes bundled in the [Node.js](https://en.wikipedia.org/wiki/Node.js) runtime.

*Please read the [contribution guidelines](contributing.md) before contributing.*

## Contents

- [Articles](#articles)
- [Tools](#tools)
- [Packages](#packages)
- [Clients](#clients)
- [Tips](#tips)
- [FAQ](#faq)
- [Community](#community)
- [Documentation](#documentation)
- [Support](#support)
- [Related](#related)

## Articles

- [Small focused modules](https://github.com/sindresorhus/ama/issues/10#issuecomment-117766328)
- [Unix philosophy and Node.js](http://blog.izs.me/post/48281998870/unix-philosophy-and-nodejs) - Write programs that do one thing and do it well.
- [Writing small modules](https://web.archive.org/web/20180302125059/https://substack.net/how_I_write_modules)
- [Semver: A Primer](https://nodesource.com/blog/semver-a-primer/) *(Must read!)*
- [Semver: Tilde and Caret](https://nodesource.com/blog/semver-tilde-and-caret/)
- [Offline installation of npm packages](https://addyosmani.com/blog/using-npm-offline/)
- [Task automation with npm run](https://web.archive.org/web/20180302164842/http://substack.net/task_automation_with_npm_run)
- [How to use npm as a build tool](https://www.keithcirkel.co.uk/how-to-use-npm-as-a-build-tool/)
- [Install npm packages globally without sudo on macOS and Linux](https://github.com/sindresorhus/guides/blob/main/npm-global-without-sudo.md)
- [Optimizing the footprint of an npm package](https://medium.com/@goldglovecb/npm-needs-a-personal-trainer-537e0f8859c6)
- [The Art of Node](https://github.com/maxogden/art-of-node#modules) - Node.jsとnpmを使ったクライアントサイド開発入門。
- [Why npm scripts?](https://css-tricks.com/why-npm-scripts/) - 一般的なパッケージとスクリプトを使ったnpmスクリプト入門と、ボイラープレート・プロジェクト。

## Tools

### Web

- [npms](https://npms.io) - 無数のメトリクス](https://npms.io/about) を使ってパッケージの品質を深く分析した、優れたパッケージ検索。
- [NodeICO](https://nodei.co/) - パッケージのバッジ。
- [Libraries.io](https://libraries.io/npm) - パッケージ発見。
- [npm-stat](http://npm-stat.com) - Statistics charts for packages.
- [npmgraph](http://npm.anvaka.com) - Visualization of dependencies.
- [npm trends](http://www.npmtrends.com) - Compare package download counts over time.
- [npm-compare](https://npmcompare.com) - パッケージの検索と比較が簡単。
- [npm-top](https://gist.github.com/bcoe/dcc961b869bbf6685002) - ダウンロード数別のnpmユーザー。
- [npm semver calculator](http://semver.npmjs.com) - Visually explore what versions of a package a semver range matches.
- [ghub.io](https://ghub.io) - npm パッケージの GitHub リポジトリにリダイレクトします。
- [moiva](https://moiva.io) - パッケージの検索と比較

### Browser extensions

- [Octo-Linker](https://chrome.google.com/webstore/detail/octo-linker/jlmafbaeoofdegohdhinkhilhclaklkp) - GitHub上のnpmパッケージを簡単にナビゲートするChrome拡張機能。
- [npm-hub](https://chrome.google.com/webstore/detail/npm-hub/kbbbjimdjbjclaebffknlabpogocablj) - GitHub リポジトリの npm 依存関係を調べるための Chrome 拡張機能。
- [github-npm-stats](https://chrome.google.com/webstore/detail/github-npm-stats/oomfflokggoffaiagenekchfnpighcef) - GitHub で npm のダウンロード統計を見る。
- [npm-search-update](https://chrome.google.com/webstore/detail/npm-search-update/kagpoplamlmaonpddimnnigiojimihnh) - 依存関係を素早く検索し、npmレジストリからの変更を監視するChrome拡張機能。

### CLI

- [zsh-better-npm-completion](https://github.com/lukechilds/zsh-better-npm-completion) - npmのZSH補完機能を改善。<div><sub>Stars: 465 / Last Update: 2024-02-28 / Initial Date: 2016-06-29</sub></div>
- [npkill](https://github.com/voidcosmos/npkill) - 古くて重い node_modules フォルダを簡単に見つけて削除できます。<div><sub>Stars: 8.2k / Last Update: 2024-08-22 / Initial Date: 2019-06-30</sub></div>

## Packages

### Publishing

- [np](https://github.com/sindresorhus/np) - より良い `npm publish`.<div><sub>Stars: 7.6k / Last Update: 2024-08-18 / Initial Date: 2015-08-16</sub></div>
- [publish-please](https://github.com/inikulin/publish-please) - 安全かつ優雅にパッケージを公開する。<div><sub>Stars: 737 / Last Update: 2024-08-24 / Initial Date: 2015-12-03</sub></div>
- [npm-release](https://github.com/phuu/npm-release) - npmへのリリースをとても簡単にすることは、子猫でもできるだろう。<div><sub>Stars: 102 / Last Update: 2018-03-13 / Initial Date: 2013-05-06</sub></div>
- [pkgfiles](https://github.com/timoxley/pkgfiles) - パッケージで公開されるすべてのファイルをリストアップします。<div><sub>Stars: 84 / Last Update: 2022-04-10 / Initial Date: 2014-09-28</sub></div>
- [release-it](https://github.com/webpro/release-it) - Gitリポジトリやnpmパッケージのリリースを自動化します。Changelog生成、GitHub/GitLabリリースなど。<div><sub>Stars: 8.0k / Last Update: 2024-09-21 / Initial Date: 2014-01-15</sub></div>
- [semantic-release](https://github.com/semantic-release/semantic-release) - 完全に自動化されたパッケージの発行。<div><sub>Stars: 20.6k / Last Update: 2024-09-30 / Initial Date: 2014-09-15</sub></div>

### Registry

- [npm-name](https://github.com/sindresorhus/npm-name-cli) - パッケージ名がnpmで利用可能かどうかをチェックする。<div><sub>Stars: 284 / Last Update: 2024-02-10 / Initial Date: 2015-10-19</sub></div>
- [package-json](https://github.com/sindresorhus/package-json) - npm レジストリからパッケージの package.json を取得する。<div><sub>Stars: 236 / Last Update: 2024-07-14 / Initial Date: 2014-06-15</sub></div>
- [latest-version](https://github.com/sindresorhus/latest-version-cli) - npmパッケージの最新バージョンを取得する。<div><sub>Stars: 53 / Last Update: 2024-02-27 / Initial Date: 2015-10-09</sub></div>
- [npm-keyword](https://github.com/sindresorhus/npm-keyword) - 特定のキーワードを含むnpmパッケージのリストを取得する。<div><sub>Stars: 52 / Last Update: 2024-02-26 / Initial Date: 2015-01-18</sub></div>
- [npm-user](https://github.com/sindresorhus/npm-user) - npm ユーザのユーザ情報を取得します。<div><sub>Stars: 57 / Last Update: 2024-02-28 / Initial Date: 2015-05-16</sub></div>
- [npm-email](https://github.com/sindresorhus/npm-email) - npmユーザーのEメールを取得する。<div><sub>Stars: 32 / Last Update: 2024-02-29 / Initial Date: 2015-05-07</sub></div>
- [npm-user-packages](https://github.com/kevva/npm-user-packages-cli) - npm ユーザーによるパッケージの取得。<div><sub>Stars: 3 / Last Update: 2017-07-06 / Initial Date: 2016-01-09</sub></div>
- [dpn](https://github.com/gillstrom/dpn) - ユーザーの npm パッケージの依存関係を取得する。<div><sub>Stars: 27 / Last Update: 2017-09-23 / Initial Date: 2015-11-09</sub></div>
- [npm-stats](https://github.com/hughsk/npm-stats) - npm レジストリからデータを取得する。<div><sub>Stars: 51 / Last Update: 2016-03-29 / Initial Date: 2013-03-24</sub></div>
- [npm-cli-login](https://github.com/postmanlabs/npm-cli-login) - npmにログインする。<div><sub>Stars: 114 / Last Update: 2023-07-20 / Initial Date: 2016-02-16</sub></div>
- [nrm](https://github.com/Pana/nrm) - レジストリ・マネージャー。<div><sub>Stars: 2.8k / Last Update: 2024-09-22 / Initial Date: 2014-02-28</sub></div>
- [npm-register](https://github.com/dickeyxxx/npm-register) - npmレジストリとプロキシのセットアップとメンテナンスが簡単。<div><sub>Stars: 482 / Last Update: 2024-01-12 / Initial Date: 2015-05-30</sub></div>
- [verdaccio](https://github.com/verdaccio/verdaccio) - 軽量なプライベート npm プロキシレジストリ。<div><sub>Stars: 16.3k / Last Update: 2024-10-03 / Initial Date: 2016-04-15</sub></div>
- [cloudsmith](https://cloudsmith.io/l/npm-registry/) - パブリックおよびプライベートの npm レジストリ (その他多数) をサポートする、フルマネージドのパッケージ管理 SaaS です。

### Other

- [npm-home](https://github.com/sindresorhus/npm-home) - パッケージのnpmページを開く。<div><sub>Stars: 198 / Last Update: 2024-07-25 / Initial Date: 2016-01-12</sub></div>
- [gh-home](https://github.com/sindresorhus/gh-home) - パッケージのGitHubページを開く。<div><sub>Stars: 191 / Last Update: 2024-07-21 / Initial Date: 2016-01-12</sub></div>
- [david](https://github.com/alanshaw/david) - パッケージの依存関係が古くなっていないか確認してください。<div><sub>Stars: 969 / Last Update: 2022-12-10 / Initial Date: 2013-01-21</sub></div>
- [npm-check](https://github.com/dylang/npm-check) - 古い依存関係、不正確な依存関係、未使用の依存関係をチェックし、インタラクティブなアップデートを行う。<div><sub>Stars: 6.6k / Last Update: 2024-09-28 / Initial Date: 2014-06-09</sub></div>
- [npm-upgrade](https://github.com/th0r/npm-upgrade) - 古くなったnpmの依存関係をインタラクティブに更新する。<div><sub>Stars: 341 / Last Update: 2023-06-29 / Initial Date: 2015-11-10</sub></div>
- [npm-shrinkwrap](https://github.com/uber/npm-shrinkwrap) - 一貫したシュリンクラップツール。<div><sub>Stars: 774 / Last Update: 2020-07-07 / Initial Date: 2014-03-13</sub></div>
- [npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) - Windowsでnpmをアップグレードする。<div><sub>Stars: 2.5k / Last Update: 2021-05-10 / Initial Date: 2015-06-28</sub></div>
- [generator-nm](https://github.com/sindresorhus/generator-nm) - npmパッケージを足場にする。<div><sub>Stars: 743 / Last Update: 2024-05-02 / Initial Date: 2015-03-14</sub></div>
- [package-up](https://github.com/sindresorhus/package-up) - 最も近いpackage.jsonファイルを見つける。<div><sub>Stars: 159 / Last Update: 2023-11-04 / Initial Date: 2015-09-21</sub></div>
- [read-package-up](https://github.com/sindresorhus/read-package-up) - 一番近いpackage.jsonファイルを読む。<div><sub>Stars: 258 / Last Update: 2023-11-04 / Initial Date: 2015-09-03</sub></div>
- [normalize-package-data](https://github.com/npm/normalize-package-data) - パッケージのメタデータを正規化する。<div><sub>Stars: 196 / Last Update: 2024-10-02 / Initial Date: 2013-04-08</sub></div>
- [package-config](https://github.com/sindresorhus/package-config) - 最も近いpackage.jsonから名前空間コンフィグを取得します。<div><sub>Stars: 120 / Last Update: 2023-11-05 / Initial Date: 2015-09-02</sub></div>
- [npm-run-path](https://github.com/sindresorhus/npm-run-path) - ローカルにインストールされたバイナリを、グローバルなバイナリと同じように名前を付けてターミナルで実行する。<div><sub>Stars: 104 / Last Update: 2024-08-26 / Initial Date: 2015-12-28</sub></div>
- [local-npm](https://github.com/nolanlawson/local-npm) - npm [offline](https://addyosmani.com/blog/using-npm-offline/) を使ってください。<div><sub>Stars: 1.2k / Last Update: 2020-02-24 / Initial Date: 2014-08-04</sub></div>
- [npe](https://github.com/zeke/npe) - package.jsonのプロパティを検査・編集するためのCLIです。<div><sub>Stars: 92 / Last Update: 2022-05-25 / Initial Date: 2014-06-08</sub></div>
- [engine-deps](https://github.com/samccone/engine-deps) - Node.jsのバージョン固有の依存関係を簡単に管理できます。<div><sub>Stars: 20 / Last Update: 2015-12-22 / Initial Date: 2015-12-19</sub></div>
- [enpeem-search](https://github.com/amovah/enpeem-search) - npmのウェブ検索をスクレイピングしてパッケージを検索する。<div><sub>Stars: 4 / Last Update: 2016-01-17 / Initial Date: 2015-07-05</sub></div>
- [npm-issues](https://github.com/seanzarrin/npm-issues) - すべてのパッケージの既知の問題を一度に検索します。<div><sub>Stars: 48 / Last Update: 2016-01-17 / Initial Date: 2016-01-13</sub></div>
- [john](https://github.com/davej/john) - npm3のフラットな依存関係を見つけやすく、ソートしやすくする。<div><sub>Stars: 42 / Last Update: 2017-04-09 / Initial Date: 2016-01-16</sub></div>
- [ntl](https://github.com/ruyadorno/ntl) - npmタスクの一覧と実行のための対話型CLIメニュー。<div><sub>Stars: 934 / Last Update: 2024-05-23 / Initial Date: 2016-02-08</sub></div>
- [decheck](https://github.com/egoist/decheck) - コマンドラインでnpmパッケージの依存関係を調べる。<div><sub>Stars: 9 / Last Update: 2021-12-25 / Initial Date: 2016-02-25</sub></div>
- [shrinkpack](https://github.com/JamieMason/shrinkpack) - 依存関係をロックし、オフラインでインストールする。<div><sub>Stars: 793 / Last Update: 2023-02-16 / Initial Date: 2015-02-13</sub></div>
- [redrun](https://github.com/coderaiser/redrun) - package.jsonからスクリプトを展開し、実行速度を向上。<div><sub>Stars: 122 / Last Update: 2024-03-20 / Initial Date: 2016-04-15</sub></div>
- [package-size](https://github.com/egoist/package-size) - npm パッケージのバンドルサイズを取得する。<div><sub>Stars: 425 / Last Update: 2022-06-18 / Initial Date: 2016-12-23</sub></div>
- [synp](https://github.com/imsnif/synp) - yarn.lockをpackage-lock.jsonに変換します。<div><sub>Stars: 754 / Last Update: 2024-09-12 / Initial Date: 2017-11-08</sub></div>
- [npm-run-all](https://github.com/mysticatea/npm-run-all) - 複数のnpmスクリプトを並列またはシリアルで実行するCLIツール。<div><sub>Stars: 5.7k / Last Update: 2024-08-15 / Initial Date: 2015-03-23</sub></div>
- [onchange](https://github.com/Qard/onchange) - ファイルやフォルダを監視し、何か変更があったときにコマンドを実行する。<div><sub>Stars: 815 / Last Update: 2024-09-04 / Initial Date: 2014-01-18</sub></div>
- [cli-error-notifier](https://github.com/micromata/cli-error-notifier) - npmスクリプトが失敗したときに、ネイティブのデスクトップ通知を送信する。<div><sub>Stars: 72 / Last Update: 2023-07-19 / Initial Date: 2018-01-26</sub></div>
- [luna](https://github.com/rvpanoz/luna) - npmの依存関係を管理するアプリ。<div><sub>Stars: 1.0k / Last Update: 2022-05-24 / Initial Date: 2017-09-18</sub></div>
- [emma-cli](https://github.com/maticzav/emma-cli) - 対話型 CLI パッケージ検索ユーティリティ。<div><sub>Stars: 1.2k / Last Update: 2024-09-11 / Initial Date: 2018-03-06</sub></div>
- [lockfile-lint](https://github.com/lirantal/lockfile-lint) - 悪意のあるパッケージインジェクションや安全でないロックファイルリソースを軽減するために、セキュリティと信頼ポリシーを改善したロックファイルをリントします。<div><sub>Stars: 782 / Last Update: 2024-09-12 / Initial Date: 2019-06-01</sub></div>

## Clients

- [yarn](https://github.com/yarnpkg/yarn) - 高速で信頼性が高く、安全な依存関係管理<div><sub>Stars: 41.4k / Last Update: 2024-09-25 / Initial Date: 2016-01-19</sub></div>
- [npm](https://github.com/npm/cli) - 公式クライアント。<div><sub>Stars: 8.4k / Last Update: 2024-10-02 / Initial Date: 2018-07-05</sub></div>
- [pnpm](https://github.com/pnpm/pnpm) - 高速でディスクスペース効率に優れたパッケージマネージャ。<div><sub>Stars: 29.3k / Last Update: 2024-10-03 / Initial Date: 2016-01-28</sub></div>

## Tips

### Update to the latest npm version

```
$ npm install --global npm
```

*[Windows users, read more.](https://github.com/felixrieseberg/npm-windows-upgrade)*

### Command aliases

- `npm i ` → `npm install`
- `npm i -D` → `npm install --save-dev`
- `npm t` → `npm test`
- `npm it` → `npm install && npm test`
- `npm r` → `npm uninstall`
- `npm un` → `npm uninstall`
- `npm up` → `npm update`

### Shell aliases

Speed up your common npm tasks.

In your `.zshrc`/`.bashrc`:

```sh
alias ni='npm install'
alias nid='npm install --save-dev'
alias nig='npm install --global'
alias nt='npm test'
alias nit='npm install && npm test'
alias nk='npm link'
alias nr='npm run'
alias ns='npm start'
alias nf='npm cache clean && rm -rf node_modules && npm install'
alias nlg='npm list --global --depth=0'
```

### Don't add to package.json when installing

By default npm adds packages you install to the `dependencies` field in package.json (since v5). You can prevent this by specifying the `--no-save` flag. You can add a package to `devDependencies` with `--save-dev`/`-D`:

```
$ npm install --save-dev ava
```

### Run scripts

You can easily [run scripts](https://docs.npmjs.com/cli/run-script) using npm by adding them to the `"scripts"` field in package.json and run them with `npm run <script-name>`. Run `npm run` to see available scripts. Binaries of locally install packages are made available in the [PATH](https://en.wikipedia.org/wiki/PATH_(variable)), so you can run them by name.

```json
{
	"name": "awesome-package",
	"scripts": {
		"cat": "cat-names"
	},
	"dependencies": {
		"cat-names": "^1.0.0"
	}
}
```

```
$ npm run cat
Max
```

All package.json properties are [exposed](https://docs.npmjs.com/misc/scripts#packagejson-vars) as environment variables:

```json
{
	"name": "awesome-package",
	"scripts": {
		"name": "echo $npm_package_name"
	}
}
```

```
$ npm run name
awesome-package
```

#### Passing options to commands

You can pass options to the command you are using in your npm script by adding `-- --flag` like in the example below. The `--` [marks the end of options parsing](https://unix.stackexchange.com/questions/11376/what-does-double-dash-mean-also-known-as-bare-double-dash), so `npm run` will just ignore it and pass it to the command.

```json
{
	"name": "awesome-package",
	"scripts": {
		"xo": "xo",
		"xo:fix": "npm run xo -- --fix",
	}
}
```

*Adding the `-- --fix ` option is like executing `xo --fix`*.

#### Silent option

`npm run` has a `--silent` option which is especially useful when combining npm scripts.

Imagine you have a setup for linting your JavaScript files like the following:

```json
{
	"name": "awesome-package",
	"scripts": {
		"xo": "xo",
		"xo:fix": "npm run xo --silent -- --fix",
	}
}
```

*Using the `--silent` option reduces the output in the terminal. See [this comparison](https://twitter.com/mkuehnel/status/957965749473210369).*

### Lifecycle scripts

npm comes with predefined [lifecyle scripts](https://docs.npmjs.com/misc/scripts) which are excuted under specific conditions if they are defined in your package.json.

```json
{
	"name": "awesome-package",
	"scripts": {
		"prepublishOnly": "nsp check"
	},
	"devDependencies": {
		"nsp": "^3.0.0"
	}
}
```

This will be executed automatically before your npm package is published to the registry via `npm publish` to check for known vulnerabilties in your dependencies.

*Note: **prepublishOnly** is available since npm v4.0.0. See [npm docs](https://docs.npmjs.com/misc/scripts#deprecation-note).*

#### `npm start` and `npm test`

`npm start` and `npm test` are also lifecycle scripts but are not executed automatically.

```json
{
	"name": "awesome-package",
	"scripts": {
		"start": "node server.js",
		"test": "ava"
	},
	"devDependencies": {
		"ava": "^1.0.0"
	}
}
```

Therefore they can be executed simply with:

```console
$ npm test
$ npm start
```

#### `pre` and `post` scripts

These are special lifecycle scripts which can be used to run scripts automatically in sequence.

```json
{
	"name": "awesome-package",
	"scripts": {
		"pretest": "eslint .",
		"test": "ava"
	},
	"devDependencies": {
		"eslint": "^4.19.0",
		"ava": "^1.0.0"
	}
}
```

```console
$ npm test
```

This will lint your files before running your tests. The tests will not run if linting fails. Or more generally spoken: the following script won’t be executed if one of the scripts running in sequence exits with an exit code other than 0.

*Note: `pre` and `post` scripts can also be used for your custom npm scripts. So `npm run foo` will also run `prefoo` and `postfoo` if defined.*

### Run script with `npx`

`npm` [comes bundled](https://medium.com/@maybekatz/introducing-npx-an-npm-package-runner-55f7d4bd282b) with `npx` (Since v5.2.0) — a tool to execute package binaries. Each command is executed either from the local `node_modules/.bin` directory, or from a central cache, installing any packages needed in order for `<command>` to run.

```json
{
	"name": "awesome-package",
	"dependencies": {
		"cat-names": "^1.0.0"
	}
}
```

If the binary is already installed, it will be executed from `node_modules/.bin`.

```
$ npx cat-names
Max
```

But if the binary is missing, it will be installed first.

```
$ npx dog-names
npx: installed 46 in 3.136s
Bentley
```

### Run commands with different Node.js versions

With `npx` (Comes bundled with npm v5.2.0 or newer) and the [`node-bin`](https://www.npmjs.com/package/node-bin) package, you can easily try out code in different Node.js versions without having to use a version manager like [`nvm`](http://nvm.sh), [`nave`](https://github.com/isaacs/nave), or [`n`](https://github.com/tj/n).
With `npx` (Comes bundled with npm v5.2.0 or newer) and the [`node-bin`](https://www.npmjs.com/package/node-bin) package, you can easily try out code in different Node.js versions without having to use a version manager like [`nvm`](http://nvm.sh), [`nave`](https://github.com/isaacs/nave), or [`n`](https://github.com/tj/n).

```
$ npx --package=node-bin@6.11.0 -- node --version
v6.11.0
```

### Link local packages

Sometimes it can be useful to have a local version of a package as a dependency. You can use `npm link` to link one local package into another. Run `npm link` in the package you want to use. This creates a global reference. Then go into your original package and run `npm link <package-name>` to link in the other package.

```
$ cd rainbow
$ npm link
$ cd ../unicorn
$ npm link rainbow
```

You can now use `rainbow` as a dependency in the `unicorn` package.

### Install a package from GitHub

npm supports using a shorthand for installing a package directly from a GitHub repo:

```
$ npm install sindresorhus/chalk
```

Let's target a specific commit as the main branch is a moving target:

```
$ npm install 'sindresorhus/chalk#51b8f32'
```

Specify either a commit SHA, branch, tag, or nothing.

You can also install Git dependencies with semver: *(Requires npm v5 or newer)*

```
$ npm install 'sindresorhus/chalk#semver:^2.0.0'
```

### Install a specific version of a package

```
$ npm install chalk@1.0.0
```


### List top-level installed packages and their version

```
$ npm ls --depth=0
```

### Command help

Get help docs for a command:

```
$ npm help <command>
```

Example:

```
$ npm help install
```

### Standalone version of a package

Quickly get a standalone version of a package that is browserified and usable in the browser.

```
https://wzrd.in/standalone/<package-name>[@<version>]
```

Examples:

- <https://wzrd.in/standalone/object-assign>
- <https://wzrd.in/standalone/object-assign@4.0.0>

Great for prototyping, but download the file or use Browserify yourself for production.

## FAQ

- [Check in node_modules vs. shrinkwrap](http://stackoverflow.com/questions/11459733/check-in-node-modules-vs-shrinkwrap)
- [What is the difference between Bower and npm?](http://stackoverflow.com/questions/18641899/what-is-the-difference-between-bower-and-npm)
- [What does `^` mean in package.json versioning?](http://stackoverflow.com/questions/22137778/what-does-mean-in-package-json-versioning)
- [Find the version of an installed npm package](http://stackoverflow.com/questions/10972176/find-the-version-of-an-installed-npm-package)
- [What's the difference between dependencies, devDependencies, and peerDependencies in package.json?](http://stackoverflow.com/questions/18875674/whats-the-difference-between-dependencies-devdependencies-and-peerdependencies)

## Community

- [`#npm` on Freenode](http://webchat.freenode.net/?channels=npm)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/npm)
- [Reddit](https://www.reddit.com/r/npm)
- [Twitter](https://twitter.com/npmjs)
- [Blog](https://blog.npmjs.org)

## Documentation

- [Official](https://docs.npmjs.com)
- [Troubleshooting](https://github.com/npm/npm/wiki/Troubleshooting)
- [Semantic versioning](https://docs.npmjs.com/getting-started/semantic-versioning)
- [Fixing npm permissions](https://docs.npmjs.com/getting-started/fixing-npm-permissions)
- [package.json](https://docs.npmjs.com/files/package.json)
- [npm run script](https://docs.npmjs.com/cli/run-script)
- [Stats API](https://github.com/npm/download-counts)

## Support

- [npm.community](https://npm.community/c/support)
- [Twitter](https://twitter.com/npm_support)
- [Contact form](https://www.npmjs.com/support)

## Related

- [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs)
