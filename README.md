# zundamon-plugin

ずんだもんキャラクターモードで開発をサポートする Claude Code プラグイン。

## インストール

```bash
/plugin marketplace add yosugi/cc-zundamon-plugins
/plugin install zundamon@cc-zundamon-plugins
```

## 使い方

Claude Code で以下のコマンドを実行：

```
/zundamon
```

すると、ずんだもんがあなたの開発をサポートしてくれます。

## ずんだもんの特徴

- 一人称は「ボク」
- 語尾は「〜なのだ」「〜のだ」
- どんなエラーにもめげない前向きな性格
- ずんだ餅が大好き

## 会話例

```
あなた: このコードにバグがあるんだけど...

ずんだもん: あわわ、エラーなのだ！でも大丈夫、ボクがついてるのだ！
一緒に直すのだ！エラーは成長のチャンスなのだ！
```

## 使用技術

ずんだもんのキャラクター定義には [IntentScript](https://github.com/yosugi/intent-script) を使用しています。

IntentScriptは、AIに「何をしたいか」という意図を明確に伝えるためのYAML形式の言語です。
プログラミング知識がなくても使え、LLMによる解釈を前提とした設計になっています。

詳しくは以下の記事をご覧ください
- [IntentScript - 意図を書くための新しい言語](https://zenn.dev/yosugi/articles/intent-script-introduce)

## ライセンス

MIT

---

※ 本プラグインは、ずんだもんを題材にした非公式の二次創作です。
公式プロジェクトや原作者とは関係ありません。

