# Codex Skills

这个仓库目前包含两个可独立安装的 Codex Skill。

## CAG 开发术语定位助手

解释研发术语、报错和方案取舍，并按需联系 Cats And Dogs Team、CAD Agent 与小工单的产品背景。

```bash
npx --yes skills add 1106841329-jpg/skill --skill cag-dev-term-decoder -a codex -g -y
```

## 行业知识理解与业务定位助手

解释制造业及其他行业的专业名词、岗位、设备、流程和业务疑问，结合具体业务条件理清职责、数据、因果与关联场景，并按需串联已学知识。

```bash
npx --yes skills add 1106841329-jpg/skill --skill industry-knowledge-business-locator -a codex -g -y
```

安装完成后，新建或重新打开 Codex 任务。也可以显式调用：

```text
$cag-dev-term-decoder 请解释这段研发讨论。
$industry-knowledge-business-locator 请解释这个行业问题，并说明它在业务流程中的位置。
```

两个公开版本均不包含创建者的个人背景文件。当前版本：1.2.0。
