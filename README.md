# CAG 开发术语定位助手

面向产品和商业人员的 Codex Skill，用于解释研发术语、报错和方案取舍，并按需联系 Cats And Dogs Team、CAD Agent 与小工单的产品背景。

## 一行安装

```bash
npx --yes skills add 1106841329-jpg/skill --skill cag-dev-term-decoder -a codex -g -y
```

安装完成后，新建或重新打开 Codex 任务，直接提问即可；也可以显式调用：

```text
$cag-dev-term-decoder 请解释这段研发讨论，并说明它位于产品链路的哪里。
```

## 内容

- `SKILL.md`：回答规则与判断边界
- `agents/openai.yaml`：Codex 展示和默认调用信息
- `references/cag-context.md`：CAG 团队与产品背景基线

当前版本：1.2.0。公开版本不包含创建者的个人背景文件。
