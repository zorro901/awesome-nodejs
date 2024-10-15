# Awesome Generative AI [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> A curated list of modern Generative Artificial Intelligence projects and services.

Generative Artificial Intelligence is a technology that creates original content such as images, sounds, and texts by using machine learning algorithms that are trained on large amounts of data. Unlike other forms of AI, it is capable of creating unique and previously unseen outputs such as photorealistic images, digital art, music, and writing. These outputs often have their own unique style and can even be hard to distinguish from human-created works. Generative AI has a wide range of applications in fields such as of art, entertainment, marketing, academia, and computer science.

Contributions to this list are welcome. Before submitting your suggestions, please review the [Contribution Guidelines](CONTRIBUTING.md) to ensure your entries meet the criteria. Add links through [pull requests](https://github.com/steven2358/awesome-generative-ai/pulls) or create an [issue](https://github.com/steven2358/awesome-generative-ai/issues) to start a discussion. More projects can be found in the [Discoveries List](DISCOVERIES.md), where we showcase a wide range of up-and-coming Generative AI projects.

## Contents

- [Recommended reading](#recommended-reading)
- [Text](#text)
- [Coding](#coding)
- [Agents](#agents)
- [Image](#image)
- [Video](#video)
- [Audio](#audio)
- [Other](#other)
- [Learning resources](#learning-resources)
- [More lists](#more-lists)

## Recommended reading

- [How Large Language Models Will Transform Science, Society, and AI](https://hai.stanford.edu/news/how-large-language-models-will-transform-science-society-and-ai) - GPT-3モデルの能力と限界、そして社会への潜在的影響についてまとめた記事。アレックス・タムキン、ディープ・ガングリ著、2021年2月5日。
- [Generative AI: A Creative New World](https://www.sequoiacap.com/article/generative-ai-a-creative-new-world/) - ジェネレーティブAI業界を包括的に検証し、歴史的視点と業界エコシステムの詳細分析を提供。ソーニャ・ホァン、パット・グレイディ、GPT-3著、2022年9月19日。
- [A Coming-Out Party for Generative A.I., Silicon Valley's New Craze](https://www.nytimes.com/2022/10/21/technology/generative-ai.html) - ジェネレーティブAIの台頭、特にStable Diffusion画像ジェネレーターの成功とそれに伴う論争についての記事。ニューヨーク・タイムズ、2022年10月21日。
- [AI's New Creative Streak Sparks a Silicon Valley Gold Rush](https://www.wired.com/story/ais-new-creative-streak-sparks-a-silicon-valley-gold-rush/) - ジェネレーティブAIの新興企業への宣伝と投資が拡大し、さまざまな業界がその応用の可能性を探っているという記事。ワイアード、2022年10月27日号。
- [ChatGPT Heralds an Intellectual Revolution](https://www.wsj.com/articles/artificial-intelligence-generative-ai-chatgpt-kissinger-84512912) - ヘンリー・キッシンジャー、エリック・シュミット、ダニエル・ハッテンローチャーの論説。ウォール・ストリート・ジャーナル、2023年2月24日。

### Milestones

- [OpenAI API](https://openai.com/blog/openai-api/) - GPT-3をベースとしたtext-to-text汎用AIモデル用OpenAI APIの発表。OpenAIブログ、2020年6月11日。
- [GitHub Copilot](https://github.blog/2021-06-29-introducing-github-copilot-ai-pair-programmer/) - より良いコードを書くための新しいAIペアプログラマー、Copilotの発表。GitHubブログ、2021年6月29日。
- [DALL·E 2](https://openai.com/blog/dall-e-2/) - 解像度の向上、画像作成機能の拡張、様々な安全性緩和を施した高度な画像生成システム「DALL-E 2」リリースのお知らせ。OpenAIブログ、2022年4月6日。
- [Stable Diffusion Public Release](https://stability.ai/blog/stable-diffusion-public-release) - Creative ML OpenRAIL-Mライセンスに基づく、広範なインターネットスクレイプに学習させたAIベースの画像生成モデル、Stable Diffusionの一般公開のお知らせ。Stable Diffusionブログ、2022年8月22日。
- [ChatGPT](https://openai.com/blog/chatgpt/) - フォローアップの質問に答え、間違いを認め、間違った前提に挑戦し、不適切な要求を拒否するように訓練された会話モデル、ChatGPTの発表。OpenAIブログ、2022年11月30日。
- [Bing Search](https://blogs.microsoft.com/blog/2023/02/07/reinventing-search-with-a-new-ai-powered-microsoft-bing-and-edge-your-copilot-for-the-web/) - マイクロソフト、次世代OpenAIモデルを搭載した検索エンジンBingの新バージョンを発表。マイクロソフトブログ、2023年2月7日。
- [GPT-4](https://openai.com/research/gpt-4) - 大型マルチモーダルモデルGPT-4の発表。OpenAIブログ、2023年3月14日。
- [Sora](https://openai.com/research/video-generation-models-as-world-simulators) - 大型映像生成モデル「Sora」を発表。OpenAI、2024年2月15日

## Text

### Models

- [OpenAI API](https://openai.com/api/) - OpenAIのAPIは、さまざまな自然言語タスクを実行するGPT-3およびGPT-4モデルと、自然言語をコードに翻訳するCodexへのアクセスを提供する。
- [Gopher](https://www.deepmind.com/blog/language-modelling-at-scale-gopher-ethical-considerations-and-retrieval) - ディープマインド社のGopherは、2800億パラメータの言語モデルである。
- [OPT](https://huggingface.co/facebook/opt-350m) - FacebookによるOpen Pretrained Transformers (OPT)は、デコーダのみの事前学習済みトランスフォーマー群である。[アナウンス](https://ai.facebook.com/blog/democratizing-access-to-large-scale-language-models-with-opt-175b/)。[OPT-175Bテキスト生成](https://opt.alpa.ai/)はAlpaによってホストされている。
- [Bloom](https://huggingface.co/docs/transformers/model_doc/bloom) - BLOOM by Hugging FaceはGPT-3に似たモデルで、46の異なる言語と13のプログラミング言語で学習されています。#オープンソース
- [LLaMA](https://ai.facebook.com/blog/large-language-model-llama-meta-ai/) - Metaによる、基礎となる650億パラメータの大規模言語モデル。#オープンソース
- [Llama 2](https://ai.meta.com/llama/) - メタのオープンソース大規模言語モデルの次世代。#オープンソース
- [Claude](https://claude.ai/) - AnthropicのAIアシスタント、クロードと話す。
- [Vicuna-13B](https://lmsys.org/blog/2023-03-30-vicuna/) - ShareGPTから収集されたユーザー共有会話にLLaMAを微調整して学習させたオープンソースのチャットボット。#オープンソース
- [Mixtral 8x7B](https://mistral.ai/news/mixtral-of-experts/) - 重みをオープンにした高品質な専門家のスパース混合モデル。#オープンソース
- [Grok](https://grok.x.ai/) - オープンソース](https://github.com/xai-org/grok-1)とオープンウエイトによるxAIによるLLM。#オープンソース<div><sub>Stars: 49.5k / Last Update: 2024-08-30 / Initial Date: 2024-03-17</sub></div>

### Chatbots

- [ChatGPT](https://chat.openai.com/chat) - OpenAIのChatGPTは、会話形式で対話する大規模な言語モデルです。
- [Copilot](https://copilot.microsoft.com/) - マイクロソフトによる日常的なAIコンパニオン。
- [Gemini](https://gemini.google.com/) - Google Deepmindによって開発されたマルチモーダル大規模言語モデルファミリー。
- [Character.AI](https://character.ai/) - Character.AIでは、キャラクターを作成し、チャットすることができます。
- [ChatPDF](https://www.chatpdf.com/) - PDFでチャット。
- [ChatSonic](https://writesonic.com/chat) - テキストや画像の作成を可能にするAI搭載のアシスタント。
- [Pi](https://pi.ai) - デジタルアシスタントとして利用できるパーソナライズされたAIプラットフォーム。

### Custom interfaces

- [LibreChat](https://librechat.ai/) - LibreChat は、アシスタント AIのためのフリーでオープンソースのチャットインターフェースです。[ソースコード](https://github.com/danny-avila/LibreChat)。<div><sub>Stars: 18.1k / Last Update: 2024-10-13 / Initial Date: 2023-02-12</sub></div>
- [Chatbot UI](https://www.chatbotui.com/) - オープンソースのChatGPT UI。[ソースコード](https://github.com/mckaywrigley/chatbot-ui)。<div><sub>Stars: 28.5k / Last Update: 2024-08-03 / Initial Date: 2023-03-11</sub></div>
- [Jan](https://jan.ai/) - MistralやLlama2のようなLLMをコンピュータ上でローカルかつオフラインで実行したり、OpenAIのGPT-4やGroqのようなリモートAI APIに接続することができます。[オープンソース](https://github.com/janhq/jan)<div><sub>Stars: 22.7k / Last Update: 2024-10-14 / Initial Date: 2023-08-17</sub></div>

### Search engines

- [Perplexity AI](https://www.perplexity.ai/) - AIを搭載した検索ツール。
- [Metaphor](https://metaphor.systems/) - 言語モデルによる検索。
- [Phind](https://phind.com/) - AIベースの検索エンジン。
- [You.com](https://you.com/) - AIによって構築された検索エンジンは、ユーザーのデータを100％非公開にしながら、カスタマイズされた検索体験をユーザーに提供する。
- [Komo](https://komo.ai/) - AIを搭載した検索エンジン。

### Local search engines

- [privateGPT](https://github.com/imartinez/privateGPT) - LLMのパワーを使って、インターネットに接続せずに文書に質問する。<div><sub>Stars: 53.9k / Last Update: 2024-09-26 / Initial Date: 2023-05-02</sub></div>
- [quivr](https://github.com/StanGirard/quivr) - LLMsとembeddingsを使用した生成AIセカンドブレインを使用して、すべてのファイルをダンプしてチャットします。<div><sub>Stars: 36.3k / Last Update: 2024-10-14 / Initial Date: 2023-05-12</sub></div>

### Writing assistants

- [Jasper](https://www.jasper.ai/) - 人工知能でより速くコンテンツを作成
- [Compose AI](https://www.compose.ai/) - Compose AIは無料のChrome拡張機能で、AIを活用したオートコンプリートにより、執筆時間を40%短縮します。
- [Rytr](https://rytr.me/) - Rytrは、高品質のコンテンツ作成をサポートするAIライティング・アシスタントです。
- [wordtune](https://www.wordtune.com/) - パーソナル・ライティング・アシスタント。
- [HyperWrite](https://hyperwriteai.com/) - HyperWriteは、アイデアから最終稿まで、自信を持って執筆し、より速く仕事を仕上げるのに役立ちます。
- [Moonbeam](https://www.gomoonbeam.com/) - わずかな時間でより良いブログを。
- [copy.ai](https://www.copy.ai/) - AIを使ってより良いマーケティングコピーやコンテンツを書く。
- [Anyword](https://anyword.com/) - AnywordのAIライティングアシスタントは、誰にでも効果的なコピーを生成します。
- [Contenda](https://contenda.co/) - すでに作ったコンテンツから、オーディエンスが望むコンテンツを作る。
- [Hypotenuse AI](https://www.hypotenuse.ai/) - いくつかのキーワードを、独創的で洞察力のある記事、商品説明、ソーシャルメディアのコピーに変える。
- [Lavender](https://www.lavender.ai/) - ラベンダーのメールアシスタントは、より短時間でより多くの返信を得るのに役立ちます。
- [Lex](https://lex.page/) - 人工知能を組み込んだワードプロセッサ。
- [Jenni](https://jenni.ai/) - ジェニは究極のライティング・アシスタントであり、アイデア出しや執筆の時間を何時間も節約してくれる。
- [LAIKA](https://www.writewithlaika.com/) - LAIKAは、あなたの書いた文章を人工知能に学習させ、あなただけのクリエイティブな相棒を作ります。
- [QuillBot](https://quillbot.com) - AIを搭載した言い換えツール。
- [Postwise](https://postwise.ai/) - AIを使ってツイートを書き、投稿をスケジュールし、フォロワーを増やす。
- [Copysmith](https://copysmith.ai/) - 企業およびeコマース向けのAIコンテンツ作成ソリューション。

### ChatGPT extensions

- [WebChatGPT](https://chrome.google.com/webstore/detail/webchatgpt-chatgpt-with-i/lpfemeioodjbpieminkklglpmhlngfcn) - ChatGPTのプロンプトをウェブからの関連結果で補強します。
- [GPT for Sheets and Docs](https://workspace.google.com/marketplace/app/gpt_for_sheets_and_docs/677318054654) - GoogleシートとGoogleドキュメント用のChatGPT拡張機能。
- [YouTube Summary with ChatGPT](https://chrome.google.com/webstore/detail/youtube-summary-with-chat/nmmicjeknamkfloonkhhcjmomieiodli) - YouTubeの動画を要約するにはChatGPTを使ってください。
- [ChatGPT Prompt Genius](https://chrome.google.com/webstore/detail/chatgpt-prompt-genius/jjdnakkfjnnbbckhifcfchagnpofjffo) - ChatGPTに最適なプロンプトを発見、共有、インポート、使用し、チャット履歴をローカルに保存します。
- [ChatGPT for Search Engines](https://chrome.google.com/webstore/detail/chatgpt-for-search-engine/feeonheemodpkdckaljcjogdncpiiban) - Google、Bing、DuckDuckGoの検索結果と一緒にChatGPTの応答を表示します。
- [ShareGPT](https://sharegpt.com/) - あなたのChatGPTの会話を共有し、他の人が共有する会話を探索します。
- [Merlin](https://merlin.foyer.work/) - すべてのウェブサイトにChatGPT Plusエクステンション。
- [ChatGPT Writer](https://chatgptwriter.ai/) - ChatGPT AIを使ってメールやメッセージを作成します。
- [editGPT](https://www.editgpt.app/) - chatGPTでコンテンツの校正、編集、変更の追跡が簡単にできます。
- [Forefront](https://www.forefront.ai/) - より良いChatGPT体験。

### Productivity

- [Mem](https://mem.ai/) - Memは、あなたにパーソナライズされた世界初のAI搭載ワークスペースです。あなたの創造性を増幅し、平凡な仕事を自動化し、自動的に整理整頓された状態を維持します。
- [Taskade](https://www.taskade.com/) - タスク、メモ、構造化リスト、マインドマップをTaskade AIでアウトライン化。
- [Notion AI](https://www.notion.so/product/ai) - より良い、より効率的なメモや文書を書く。
- [Nekton AI](https://nekton.ai) - AIでワークフローを自動化。ワークフローをステップごとにわかりやすく説明します。
- [Rewind](https://www.rewind.ai/) - Rewindは、あなたが見たり、話したり、聞いたりしたすべてのものによってパーソナライズされたAIです。

### Meeting assistants

- [Otter.ai](https://otter.ai/) - 音声を録音し、メモを書き、自動的にスライドをキャプチャし、要約を生成するミーティングアシスタント。
- [Cogram](https://www.cogram.com/) - コグラムはバーチャル会議で自動的にメモを取り、アクションアイテムを特定します。
- [Sybill](https://www.sybill.ai/) - シビルは、トランスクリプトと感情ベースのインサイトを組み合わせることで、次のステップ、ペインポイント、関心領域を含む営業電話のサマリーを生成します。
- [Loopin AI](https://www.loopinhq.com/) - Loopinは、AIを使って会議の録音、書き起こし、要約ができるだけでなく、会議のメモをカレンダー上に自動整理することもできる共同会議ワークスペースです。

### Academia

- [Elicit](https://elicit.org/) - Elicitは言語モデルを使用して、文献レビューのようなリサーチワークフローの自動化を支援します。
- [genei](https://www.genei.io/) - 学術論文を数秒で要約し、リサーチ時間を80%節約。
- [Explainpaper](https://www.explainpaper.com/) - 学術論文を読むためのより良い方法。論文をアップロードして、わかりにくい文章をハイライトし、解説を得る。
- [Consensus](https://consensus.app/search/) - Consensusは、AIを使って科学研究の答えを見つける検索エンジンである。
- [Synthical](https://synthical.com) - AIを活用した共同研究環境。
- [scite](https://scite.ai/) - 科学論文を発見し、評価するためのプラットフォーム。

### Other text generators

- [EmailTriager](https://www.emailtriager.com/) - AIを使って、バックグラウンドで自動的に返信メールを作成。
- [AI Poem Generator](https://www.aipoemgenerator.org) - AIポエムジェネレーターは、テキストプロンプトがあれば、どんなテーマでも美しい韻を踏んだ詩を書いてくれます。

## Coding

### Coding Assistants

- [OpenAI Codex](https://platform.openai.com/docs/guides/code/) - OpenAIによる、自然言語をコードに翻訳するAIシステム。
- [Ghostwriter](https://blog.replit.com/ai) - レプリットのAI搭載ペアプログラマー。
- [Amazon Q](https://aws.amazon.com/q/) - 質問に答えたり、コードを書いたり、タスクを自動化するAWSのジェネレーティブAIアシスタント。
- [tabnine](https://www.tabnine.com/) - 全行コード補完と全機能コード補完でコードをより速く。
- [Stenography](https://stenography.dev/) - 自動コード文書化。
- [Mintlify](https://mintlify.com/) - AIを搭載したドキュメンテーション・ライター。
- [Debuild](https://debuild.app/) - AIを搭載したウェブアプリケーション用のローコードツール。
- [AI2sql](https://www.ai2sql.io/) - AI2sqlを使えば、エンジニアもそうでない人も、SQLを知らなくても、効率的でエラーのないSQLクエリを簡単に書くことができます。
- [CodiumAI](https://www.codium.ai/) - CodiumAIを使えば、IDE内で自明でないテストが提案されます。
- [PR-Agent](https://github.com/Codium-ai/pr-agent) - 自動PR分析、フィードバック、提案などのためのAI搭載ツール。<div><sub>Stars: 5.8k / Last Update: 2024-10-14 / Initial Date: 2023-07-05</sub></div>
- [MutableAI](https://mutable.ai/) - AIが加速するソフトウェア開発。
- [MetaGPT](https://github.com/geekan/MetaGPT) - マルチエージェント・フレームワーク：1行の要件が与えられると、PRD、設計、タスク、レポを返す。<div><sub>Stars: 44.2k / Last Update: 2024-10-11 / Initial Date: 2023-06-30</sub></div>

### Developer tools

- [co:here](https://cohere.ai/) - Cohere は、高度な大規模言語モデルと NLP ツールへのアクセスを提供します。
- [Haystack](https://haystack.deepset.ai/) - 言語モデルを使ってNLPアプリケーション（エージェント、意味検索、質問応答など）を構築するためのフレームワーク。
- [LangChain](https://langchain.com/) - 言語モデルを利用したアプリケーション開発のためのフレームワーク。
- [gpt4all](https://github.com/nomic-ai/gpt4all) - コード、ストーリー、ダイアログを含む、クリーンなアシスタントデータの膨大なコレクションで訓練されたチャットボット。<div><sub>Stars: 70.0k / Last Update: 2024-10-14 / Initial Date: 2023-03-27</sub></div>
- [LLM App](https://github.com/pathwaycom/llm-app) - リアルタイムLLM対応データパイプラインを構築するためのオープンソースPythonライブラリ。<div><sub>Stars: 4.3k / Last Update: 2024-10-09 / Initial Date: 2023-07-19</sub></div>
- [LMQL](https://lmql.ai/) - LMQL は大規模な言語モデルのためのクエリ言語である。
- [LlamaIndex](https://www.llamaindex.ai/) - 外部データ上でLLMアプリケーションを構築するためのデータフレームワーク。
- [Phoenix](https://phoenix.arize.com/) - Arizeによる、ノートブック環境で動作するML観測可能性のためのオープンソースツール。LLM、CV、表形式モデルを監視し、微調整します。
- [Cursor](https://www.cursor.so/) - Cursorは、パワフルなAIとのペアプログラミングのために構築された、未来のIDEです。
- [SymbolicAI](https://github.com/Xpitfire/symbolicai) - LLMを核としたアプリケーション構築のためのニューロシンボリックフレームワーク。<div><sub>Stars: 970 / Last Update: 2024-10-13 / Initial Date: 2022-11-30</sub></div>
- [Ollama](https://github.com/ollama/ollama) - 大規模な言語モデルをローカルで稼動。<div><sub>Stars: 93.2k / Last Update: 2024-10-13 / Initial Date: 2023-06-26</sub></div>
- [Vanna.ai](https://vanna.ai/) - SQL生成と関連機能のためのオープンソースのPython RAGフレームワーク。[#opensource](https://github.com/vanna-ai/vanna)<div><sub>Stars: 11.2k / Last Update: 2024-09-27 / Initial Date: 2023-05-13</sub></div>

## Agents

### Autonomous agents

- [Auto-GPT](https://github.com/Torantulino/Auto-GPT) - GPT-4を完全に自律化させるオープンソースの実験的試み。<div><sub>Stars: 167.5k / Last Update: 2024-10-14 / Initial Date: 2023-03-16</sub></div>
- [babyagi](https://github.com/yoheinakajima/babyagi) - AIを活用したタスク管理システム。<div><sub>Stars: 20.2k / Last Update: 2024-10-11 / Initial Date: 2023-04-03</sub></div>
- [AgentGPT](https://github.com/reworkd/AgentGPT) - ブラウザ上で自律型AIエージェントを組み立て、設定し、デプロイします。<div><sub>Stars: 31.6k / Last Update: 2024-10-07 / Initial Date: 2023-04-07</sub></div>
- [GPT Engineer](https://github.com/AntonOsika/gpt-engineer) - 何を作ってほしいかを指定すると、AIは説明を求め、それを作ってくれる。<div><sub>Stars: 52.2k / Last Update: 2024-09-12 / Initial Date: 2023-04-29</sub></div>
- [GPT Prompt Engineer](https://github.com/mshumer/gpt-prompt-engineer) - 自動プロンプトエンジニアリング。プロンプトの生成、テスト、ランク付けを行い、最適なプロンプトを見つけます。<div><sub>Stars: 9.3k / Last Update: 2024-07-29 / Initial Date: 2023-07-04</sub></div>
- [MetaGPT](https://github.com/geekan/MetaGPT) - マルチエージェント・フレームワーク：1行の要件が与えられたら、PRD、デザイン、タスク、レポを返す。<div><sub>Stars: 44.2k / Last Update: 2024-10-11 / Initial Date: 2023-06-30</sub></div>
- [AutoGen](https://github.com/microsoft/autogen) - AutoGenは、タスクを解決するために互いに会話できる複数のエージェントを使用して、LLMアプリケーションの開発を可能にするフレームワークです。<div><sub>Stars: 31.9k / Last Update: 2024-10-14 / Initial Date: 2023-08-18</sub></div>
- [GPT Pilot](https://github.com/Pythagora-io/gpt-pilot) - 開発者が実装を監督しながら、スケーラブルなアプリをゼロから書き上げる開発ツール。<div><sub>Stars: 31.3k / Last Update: 2024-10-03 / Initial Date: 2023-08-16</sub></div>
- [Devin](https://devin.ai/) - コグニション・ラボによる自律型AIソフトウェア・エンジニア。
- [OpenDevin](https://github.com/OpenDevin/OpenDevin) - ソフトウェアエンジニアリングの複雑さをナビゲートするために設計された自律エージェント。#オープンソース<div><sub>Stars: 32.9k / Last Update: 2024-10-14 / Initial Date: 2024-03-13</sub></div>
- [Davika](https://github.com/stitionai/devika) - エージェント型AIソフトウェアエンジニア。#オープンソース<div><sub>Stars: 18.4k / Last Update: 2024-09-19 / Initial Date: 2024-03-21</sub></div>

### Custom assistants

- [Poe](https://poe.com/) - ポーはさまざまなボットにアクセスできる。
- [GPT Builder](https://chat.openai.com/gpts/editor) - GPTベースのアシスタントを作成するためのアシスタント。
- [GPTStore](https://gptstore.ai/) - 有用なGPTを見つける。自分のGPTを共有しよう。

## Image

### Models

- [DALL·E 2](https://openai.com/dall-e-2/) - オープンAIによるDALL-E 2は、自然言語による記述からリアルな画像やアートを作成できる新しいAIシステムである。
- [Stable Diffusion](https://huggingface.co/CompVis/stable-diffusion-v1-4) - Stability AIによるStable Diffusionは、テキストから画像を生成する最先端のテキストから画像へのモデルです。#オープンソース
- [Midjourney](https://www.midjourney.com/) - ミッドジャーニーは、新しい思考媒体を探求し、人間という種の想像力を拡大する独立した研究所である。
- [Imagen](https://imagen.research.google/) - Imagen by Googleは、これまでにないフォトリアリズムと深い言語理解レベルを備えたテキストから画像への拡散モデルである。
- [Make-A-Scene](https://ai.facebook.com/blog/greater-creative-control-for-ai-image-generation/) - MetaによるMake-A-Sceneは、マルチモーダルな生成AI手法で、テキスト記述と自由形式のスケッチの両方を通じて自分のビジョンを記述し、説明できるようにすることで、使用する人々の手に創造的なコントロールを与える。

### Services

- [Craiyon](https://www.craiyon.com/) - Craiyon（旧DALL-E mini）は、あらゆるテキストプロンプトからイメージを描くことができるAIモデルである。
- [DreamStudio](https://beta.dreamstudio.ai/) - DreamStudioは、Stable Diffusion画像生成モデルを使用して画像を作成するための使いやすいインターフェースです。
- [Artbreeder](https://www.artbreeder.com/) - Artbreederは、コラボレーションと探求を容易にすることで、ユーザーの創造性を高める新しいタイプのクリエイティブツールです。
- [GauGAN2](http://gaugan.org/gaugan2/) - GauGAN2 is a robust tool for creating photorealistic art using a combination of words and drawings since it integrates segmentation mapping, inpainting, and text-to-image production in a single model.
- [Magic Eraser](https://www.magiceraser.io/) - 画像から不要なものを数秒で削除。
- [Imagine by Magic Studio](https://magicstudio.com/imagine) - マジックスタジオによる、思ったことをそのまま表現できるツール。
- [Alpaca](https://www.getalpaca.io/) - Stable Diffusion Photoshopプラグイン。
- [Patience.ai](https://www.patience.ai/) - Patience.aiは、Stability.AIが開発した最先端のAI、Stable Diffusionを使った画像作成アプリです。
- [GenShare](https://www.genshare.io/) - 無料で数秒でアートを作成。作成したものを所有し、共有することができます。デザインと創造性を民主化するマルチメディアジェネレイティブスタジオ。
- [Playground](https://playground.com/) - Playgroundは無料で使えるオンラインAI画像作成ツールです。アート、ソーシャルメディアへの投稿、プレゼンテーション、ポスター、ビデオ、ロゴなどの作成にご利用ください。
- [Pixelz AI Art Generator](https://pixelz.ai/) - Pixelz AI Art Generator を使用すると、テキストから素晴らしいアートを作成できます。Stable Diffusion、CLIP Guided Diffusion、PXL-Eのリアルなアルゴリズムが利用可能です。
- [modyfi](https://www.modyfi.io/) - ずっと欲しかった画像エディター。AIを搭載したクリエイティブツールをブラウザで。リアルタイムコラボレーション。
- [Ponzu](https://www.ponzu.ai/) - Ponzuは無料のAIロゴジェネレーターです。あなたの想像力だけで、数秒でクリエイティブなデザインのロゴでブランドを構築できます。
- [PhotoRoom](https://www.photoroom.com/) - スマホだけで商品写真やポートレート写真を作成。背景を消したり、背景を変えたり、商品を紹介したり。
- [Avatar AI](https://avatarai.me/) - AIが生成した独自のアバターを作成。
- [ClipDrop](https://clipdrop.co/) - stability.ai](https://stability.ai/)を使って、フォトスタジオなしでプロフェッショナルなビジュアルを作成。
- [Lensa](https://prisma-ai.com/lensa) - Stable Diffusionを使用したパーソナライズされたアバターの生成を含む、オールインワンの画像編集アプリ。
- [RunDiffusion](https://rundiffusion.com/) - クラウドベースのワークスペース。
- [Ideogram](https://ideogram.ai/) - クリエイティブな表現をより身近なものにする、テキストから画像への変換プラットフォーム。
- [KREA](https://www.krea.ai/) - あなたのスタイル、コンセプト、商品について熟知したAIが、高品質のビジュアルを生成します。
- [Nightcafe](https://creator.nightcafe.studio/) - NightCafe Creatorは、複数のAIアート生成方法を備えたAIアート生成アプリです。
- [Leonardo AI](https://leonardo.ai/) - これまでにない品質、スピード、スタイルで、プロダクション品質のビジュアルアセットを作成できます。

### Graphic design

- [Brandmark](https://brandmark.io/) - AIベースのロゴデザインツール。
- [Gamma](https://gamma.app/) - 書式設定やデザイン作業をすることなく、美しいプレゼンテーションやウェブページを作成できます。
- [Microsoft Designer](https://designer.microsoft.com/) - 見事なデザインをあっという間に。

### Image libraries

- [Lexica](https://lexica.art/) - 安定した拡散検索エンジン。
- [OpenArt](https://openart.ai/) - 10M以上のプロンプトを検索し、安定拡散、DALL-E 2を介してAIアートを生成します。
- [PromptHero](https://prompthero.com/) - Stable Diffusion、ChatGPT、Midjourneyなどのモデルの検索プロンプトが表示されます。
- [PromptBase](https://promptbase.com/) - トップ・プロンプト・エンジニアのプロンプトを検索独自のプロンプトを販売。

### Model libraries

- [Civitai](https://civitai.com/) - コミュニティ主導のAIモデル共有ツール。
- [Stable Diffusion Models](https://rentry.org/sdmodels) - rentry.orgの安定拡散チェックポイントの総合リスト。

### Stable Diffusion resources

- [Stable Horde](https://stablehorde.net/) - クラウドソーシングによる安定拡散ワーカーの分散クラスタ。
- [DiffusionDB](https://diffusiondb.com/) - Stable Diffusionのすべての公開アプリ、開発者ツール、ガイド、プラグインのリストです。[Airtableバージョン](https://airtable.com/shr0HlBwbw3nZ8Ht3/tblxOCylXV8ynh7ti)。
- [PublicPrompts](https://publicprompts.art/) - 安定した拡散のための無料プロンプト集。
- [Stableboost](https://stableboost.ai/) - StableboostはStable DiffusionのWebUIで、たくさんの画像を素早く生成し、完璧な画像を見つけることができます。
- [Hugging Face Diffusion Models Course](https://github.com/huggingface/diffusion-models-class) - huggingface](https://github.com/huggingface)による拡散モデルに関するオンラインコース用のPython教材。<div><sub>Stars: 3.6k / Last Update: 2024-08-19 / Initial Date: 2022-10-13</sub></div>

## Video

- [RunwayML](https://runwayml.com/) - 魔法のようなAIツール、リアルタイムのコラボレーション、精密な編集など。次世代のコンテンツ制作スイート。
- [Synthesia](https://www.synthesia.io/) - プレーンテキストからビデオを数分で作成。
- [Rephrase AI](https://www.rephrase.ai/) - Rephraseのテクノロジーは、エンゲージメントとビジネスの効率化を促進する、超パーソナライズされた動画作成を大規模に可能にします。
- [Hour One](https://hourone.ai/) - バーチャルプレゼンターを起用し、テキストを自動的にビデオに変換。
- [D-ID](https://www.d-id.com/) - ボタンを押すだけで、おしゃべりアバターを作成し、対話することができます。
- [Colossyan](https://www.colossyan.com/) - 学習と発達に特化したビデオクリエイター。AIアバターを使って多言語で教育ビデオを作成。
- [Fliki](https://fliki.ai/) - AI音声を使ったテキストからビデオ、テキストからスピーチへのコンテンツを数分で作成できます。
- [Pictory](https://pictory.ai/) - Pictoryの強力なAIは、テキストを使用してプロ品質のビデオを作成し、編集することができます。
- [Pika](https://pika.art/) - あなたのクリエイティビティを動画にする、アイデアから動画へのプラットフォーム。
- [HeyGen](https://app.heygen.com/) - カスタマイズ可能なAIアバターを使って、スクリプトを数分でトーキングビデオに。
- [Sora](https://openai.com/sora) - テキストの指示から、リアルで想像力豊かなシーンを創造できるAIモデル。
- [Luma Dream Machine](https://lumalabs.ai/dream-machine) - テキストや画像から高品質でリアルな動画を高速で作成するAIモデル。
- [Infinity AI](https://infinity.ai/) - インフィニティはビデオ・ファンデーションのモデルで、自分のキャラクターを作り、それに命を吹き込むことができる。

### Animation

- [Wonder Dynamics](https://wonderdynamics.com/) - CGキャラクターをライブシーンに簡単にアニメート、ライティング、合成。

## Audio

### Speech

- [Eleven Labs](https://beta.elevenlabs.io/) - AIボイスジェネレーター。
- [Resemble AI](https://www.resemble.ai/) - AIボイスジェネレーターと音声合成用ボイスクローン。
- [WellSaid](https://wellsaidlabs.com/) - テキストをリアルタイムで音声に変換。
- [Play.ht](https://play.ht/) - AIボイスジェネレータ。AIを使ってオンラインでリアルな音声合成テキストを生成します。テキストを音声に変換。
- [podcast.ai](https://podcast.ai/) - 音声合成AI「Play.ht」を搭載した、人工知能がすべてを生成するポッドキャスト。
- [VALL-E X](https://vallex-demo.github.io/) - クロスリンガル音声合成のためのクロスリンガルニューラルコーデック言語モデル。
- [TorToiSe](https://github.com/neonbjb/tortoise-tts) - 品質を重視して訓練された多音声音声合成システム。#オープンソース<div><sub>Stars: 13.1k / Last Update: 2024-08-19 / Initial Date: 2022-01-28</sub></div>
- [Bark](https://github.com/suno-ai/bark) - トランスフォーマベースのテキスト音声モデル。#オープンソース<div><sub>Stars: 35.7k / Last Update: 2024-08-19 / Initial Date: 2023-04-07</sub></div>

### Music

- [Harmonai](https://www.harmonai.org/) - 私たちは、音楽制作をより身近で楽しいものにするために、オープンソースのジェネレイティブ・オーディオ・ツールをリリースしているコミュニティ主導の組織です。
- [Mubert](https://mubert.com/) - コンテンツ制作者、ブランド、開発者のためのロイヤリティフリーの音楽エコシステム。
- [MusicLM](https://google-research.github.io/seanet/musiclm/examples/) - Google Researchによる、テキスト記述から忠実度の高い音楽を生成するモデル。
- [AudioCraft](https://audiocraft.metademolab.com/) - Metaによる、ジェネレーティブ・オーディオに必要なコードベース。音楽用のMusicGenとサウンド用のAudioGenを含む。#オープンソース
- [Stable Audio](https://stability.ai/stable-audio) - ステイブル・オーディオは、ステイブルAI初の音楽・効果音生成製品です。
- [AIVA](https://www.aiva.ai/) - AIベースの音楽生成アシスタント。250以上のスタイルから選べます。
- [Suno AI](https://www.suno.ai/) - 誰でも素晴らしい音楽を作ることができる。楽器は必要なく、想像力だけでいい。あなたの心から音楽へ。
- [Udio](https://www.udio.com/) - 音楽を発見し、創造し、世界と共有する。

## Other

- [Diagram](https://diagram.com/) - 製品をデザインする魔法のような新しい方法。
- [PromptBase](https://promptbase.com/) - DALL-E、GPT-3、Midjourney、Stable Diffusion用の高品質なプロンプトを売買するマーケットプレイス。
- [This Image Does Not Exist](https://thisimagedoesnotexist.com/) - 画像が人間の手によるものか、コンピューターが作成したものかを見分ける能力を試してみよう。
- [Have I Been Trained?](https://haveibeentrained.com/) - あなたの画像が一般的なAIアートモデルの学習に使用されているかどうかを確認します。
- [AI Dungeon](https://aidungeon.io/) - テキストベースのアドベンチャー・ストーリー・ゲームで、AIが命を吹き込みながら、あなたが監督する（そして出演する）。
- [Clickable](https://www.clickable.so/) - AIで瞬時に広告を生成。あらゆるマーケティングチャネルに、美しく、ブランド一貫性のある、コンバージョンの高い広告を。
- [Scale Spellbook](https://scale.com/spellbook) - Scale Spellbookで大規模な言語モデルアプリを構築、比較、デプロイ。
- [Scenario](https://www.scenario.com/) - AIが生成したゲーム資産。
- [FinChat](https://finchat.io/) - AIを使って、FinChatは上場企業や投資家に関する質問への回答を生成する。
- [Morpher AI](https://morpher.com/ai) - Morpher AIはあらゆる市場に対してリアルタイムの洞察と分析を提供する。
- [Whimsical AI](https://whimsical.com/ai) - GPTを活用したマインドマップ、フローチャート、ビジュアルツールにより、迅速なアイデア開発とプロセス整理を実現。

## Learning resources

- [Learn Prompting](https://learnprompting.org/) - 人工知能とのコミュニケーションに関する無料のオープンソースコース。
- [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) - プロンプトエンジニアリングのためのガイドとリソース。<div><sub>Stars: 49.3k / Last Update: 2024-09-19 / Initial Date: 2022-12-16</sub></div>
- [ChatGPT prompt engineering for developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/) - アイザ・フルフォード（OpenAI）とアンドリュー・ング（DeepLearning.AI）によるショートコース。
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook) - OpenAI APIの使用例とガイドです。<div><sub>Stars: 59.1k / Last Update: 2024-10-14 / Initial Date: 2022-03-11</sub></div>
- [OpenAI Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering) - 大規模言語モデルからより良い結果を得るための戦略と戦術。
- [PromptPerfect](https://promptperfect.jina.ai/) - 迅速なエンジニアリングのためのツール。
- [Anthropic courses](https://github.com/anthropics/courses) - Anthropicの教育コース。<div><sub>Stars: 5.5k / Last Update: 2024-10-11 / Initial Date: 2024-05-30</sub></div>

## More lists

- [Tools and Resources for AI Art](https://pharmapsychotic.com/tools.html) - 生成AIのためのGoogle Colabノートブックの大規模なリスト、[@pharmapsychotic](https://twitter.com/pharmapsychotic)によるもの。
- [The Generative AI Application Landscape](https://twitter.com/sonyatweetybird/status/1584580362339962880) - Sequioa Capitalの[Sonya Huang](https://twitter.com/sonyatweetybird)による、ジェネレーティブAIのエコシステムをマッピングしたインフォグラフィック。
- [Startups - @builtwithgenai](https://airtable.com/shr6nfE9FOHp17IjG/tblL3ekHZfkm3p6YT)
- [The Generative AI Index](https://airtable.com/shrH4REIgddv8SzUo/tbl5dsXdD1P859QLO) - Scale Venture Partners](https://www.scalevp.com/generative-ai)によるAirtableリスト。
- [Generative AI for Games](https://twitter.com/gwertz/status/1593268767269670912) - a16z](https://a16z.com/)による、ゲーム向けGenerative AIに取り組む企業のマーケットマップ。
- [Generative Deep Art](https://github.com/filipecalegario/awesome-generative-deep-art) - filipecalegario](https://github.com/filipecalegario/)による、芸術的用途のための生成ディープラーニングツール、作品、モデルなどのキュレーションリスト。<div><sub>Stars: 2.5k / Last Update: 2024-10-10 / Initial Date: 2021-07-19</sub></div>
- [GPT-3 Demo](https://gpt3demo.com/) - GPT-3の例、デモ、アプリ、ショーケース、NLPユースケースを展示。
- [GPT-4 Demo](https://gpt4demo.com/) - GPT-4の用途と使用例。
- [The Generative AI Landscape](https://github.com/ai-collection/ai-collection) - 素晴らしいジェネレーティブAIアプリケーション集。<div><sub>Stars: 7.5k / Last Update: 2024-10-12 / Initial Date: 2023-01-03</sub></div>
- [Molecular design](https://github.com/AspirinCode/papers-for-molecular-design-using-DL) - ジェネレーティブAIとディープラーニングを用いた分子設計の一覧。<div><sub>Stars: 661 / Last Update: 2024-10-10 / Initial Date: 2023-02-28</sub></div>
- [Open LLMs](https://github.com/eugeneyan/open-llms) - 商用利用可能なオープンLLMのリスト。<div><sub>Stars: 11.0k / Last Update: 2024-07-05 / Initial Date: 2023-05-05</sub></div>

### Lists on ChatGPT

- [Awesome ChatGPT](https://github.com/humanloop/awesome-chatgpt) - jordn](https://github.com/jordn)による、ChatGPTとGPT-3のための素晴らしいツール、デモ、ドキュメントのキュレーションリスト。<div><sub>Stars: 8.2k / Last Update: 2024-05-13 / Initial Date: 2022-12-04</sub></div>
- [Awesome ChatGPT Prompts](https://github.com/f/awesome-chatgpt-prompts) - ChatGPTモデルで使用するプロンプト例集。<div><sub>Stars: 111.6k / Last Update: 2024-09-26 / Initial Date: 2022-12-05</sub></div>
- [FlowGPT](https://flowgpt.com/) - 最適なプロンプトでワークフローを強化。
- [Awesome ChatGPT](https://github.com/sindresorhus/awesome-chatgpt) - ChatGPTのリストがまたひとつ増えた。<div><sub>Stars: 5.1k / Last Update: 2024-09-25 / Initial Date: 2023-05-02</sub></div>
