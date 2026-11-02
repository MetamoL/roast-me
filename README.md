# roast-me

「知っていることを全部使って、容赦なくローストして」に応える Claude Code 用のスキルです（`SKILL.md` を読むほかのエージェントでも使えます）。会話や作業記録の実話だけを材料に、頼んだ人の言語で、本人が笑えるローストを書きます。SNS に載せる用に、未公開の情報を抜いた版も作れます。

A Claude Code skill that answers "Based on everything you know about me, roast me and don't hold back" with a roast built only from your real record (this conversation, your notes, your git history), in your language.

## 導入

Claude Code で次の2行を実行します。

```
/plugin marketplace add MetamoL/skills
/plugin install roast-me@metamol
```

プラグインを使わないときは、このリポジトリを `~/.claude/skills/roast-me/` に置きます。

```
git clone https://github.com/MetamoL/roast-me ~/.claude/skills/roast-me
```

ほかのスキルは [MetamoL/skills](https://github.com/MetamoL/skills) にまとめています。

## ライセンス

[LICENSE](LICENSE) のとおりです。自分の環境で使うこと・改変すること・作ったものの利用は自由です。再配布と転載はできません。
