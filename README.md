# Claude Code Skills

通用 Claude Code 技能集。

## 包含技能

| 技能 | 说明 | 触发词 |
|------|------|--------|
| project-storytelling | 把技术项目整理成有说服力的叙事 | "帮我讲讲这个项目"、"面试怎么讲" |

## 安装
### 命令行
```bash
claude plugin add github:vaynedu/claude-skills
```
### claude中
```bash
/plugin add github:vaynedu/claude-skills
```




## 使用

安装后在 Claude Code 中直接触发：

```text
> 帮我讲讲这个项目
> 面试怎么讲这个项目
> 帮我总结项目亮点
```

## 添加新技能

1. 在根目录创建新文件夹（如 `my-new-skill/`）
2. 在文件夹中创建 `SKILL.md`
3. 在 `.claude-plugin/plugin.json` 的 `skills` 数组中添加路径
4. 提交并推送到 GitHub

## License

MIT

