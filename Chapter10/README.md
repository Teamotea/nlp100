# Chapter10
言語処理100本ノックの [第10章](https://nlp100.github.io/ja/ch10.html) の解答をまとめたディレクトリ。


## 実行環境
Google Colab Pro を使用する。以下、補足。
- 解答に使用するモデルが非常に重く大きなメモリが必要なため、Pro プランである必要がある。
- 実際にセルを実行する際は `High RAM` (51GB のメモリ) を選択する。なお、GPU ありの実行環境にするとメモリが足りなくなるので CPU のみにする必要がある。


## 使用したデータ
今回の解答では以下のデータを使用した。
- `kftt-data-1.0` ディレクトリ下のデータ
  - 京都フリー翻訳タスク © Graham Neubig [クリエイティブ・コモンズ・ライセンス（CC BY-SA 3.0）](https://creativecommons.org/licenses/by-sa/3.0/deed.ja)


## 使用したモデル
今回の解答では以下を事前学習モデルとして使用した。
- Hugging Face Transformers の `facebook/mbart-large-50-many-to-many-mmt`（ウェブページは [こちら](https://huggingface.co/facebook/mbart-large-50-many-to-many-mmt)）

なお、ファインチューニングしたモデルについては公開しない（理由としては、上記ページにライセンスに関する表記がないのと、モデルのサイズが非常に大きいため）。


## ライセンス
今回の解答で作成した次のデータを以下のライセンスのもと公開する。
- `kftt-data-1.0-modified` ディレクトリ下のデータ
  - [クリエイティブ・コモンズ・ライセンス（CC BY-SA 3.0）](https://creativecommons.org/licenses/by-sa/3.0/deed.ja)
  - 京都フリー翻訳タスクのクリエイティブ・コモンズ・ライセンスに則り、このようにしている。

