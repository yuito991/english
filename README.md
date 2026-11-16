# English Speaking App

GitHub Pagesで公開するための英語学習アプリです。

## 公開ファイル

- `index.html`: GitHub Pagesで表示される本体
- `assets/a2-good-language-learner.js`: A2リスニング教材の本文と段落ごとの再生位置
- `assets/a2-good-language-learner.mp3`: [Kokoro](https://github.com/hexgrad/kokoro) の米国英語音声で生成したナレーション
- `outputs/osaru_english.html`: 作業用の元ファイル
- `outputs/supabase_setup.sql`: Supabase同期用のSQL

## GitHub Pages設定

GitHubのリポジトリで次のように設定します。

1. `Settings` を開く
2. `Pages` を開く
3. `Source` を `Deploy from a branch` にする
4. `Branch` を `main` にする
5. `Folder` を `/ (root)` にする
6. `Save` を押す

公開URLは次の形になります。

```text
https://GitHubユーザー名.github.io/リポジトリ名/
```

## 更新方法

アプリを修正したら、変更した公開ファイルをGitHubに反映します。数分後にスマホとPCの同じURLへ反映されます。リスニング教材の分割や読み上げを変更したときは、台本とMP3をセットで更新してください。

追加したフレーズの同期には、アプリ内のSupabase同期設定を使います。
