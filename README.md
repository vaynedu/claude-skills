# Claude Code Skills

通用 Claude Code 技能集。

## 包含技能

| 技能 | 说明 | 触发词 |
|------|------|--------|
| project-storytelling | 把技术项目整理成有说服力的叙事 | "帮我讲讲这个项目"、"面试怎么讲" |

## 安装
```bash
git clone https://github.com/vaynedu/claude-skills.git /tmp/cs && cp -r /tmp/cs/project-storytelling ~/.claude/skills/ && rm -rf /tmp/cs

安装完成后在 Claude Code 中执行 /reload-plugins 即可生效。
                                                                                                                             
```
## 验证安装
```bash
# 确认文件存在
ls ~/.claude/skills/project-storytelling/SKILL.md

# 在 Claude Code 中执行
/reload-plugins
/skills
```
在 skills 列表中看到 project-storytelling 即安装成功


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
3. 提交并推送到 GitHub

## License

MIT

