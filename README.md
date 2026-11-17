# superagent

This repository is the work area for a local [dsh-superagent](https://github.com/deepseek-ai/dsh-superagent-prototype)
instance operated by @Forrest-Xiong.

## How to ask for work

Comment on an issue in this repository mentioning the agent account:

```
@Forrest-Xiong <what you need done>
```

The agent opens a work item, works on it in its own session and directory, and
answers in the original conversation, usually with a pull request.

## 如何提问

直接在 issue（或 PR）下留言，并 @agent 账号即可，例如：

```text
@Forrest-Xiong 给 README 加一段“如何提问”的说明
```

为了让 agent 一次理解到位，提问时最好写清这几点：

- **目标**：想要达成什么，例如“给 README 增加使用说明”。
- **范围**：涉及哪些文件、页面或功能，例如“只改 README”。
- **验收标准**：怎样算完成，例如“包含步骤和示例”。
- **限制**：不能改动的部分、需要遵守的规范，或时间要求。

Agent 会为每个请求建立工单，在自己的会话和目录里完成工作，并在原对话中
回复结果，通常还会附上一个 pull request。

## Notes

- Requests arrive through the agent account's GitHub notifications, so a *new*
  issue or comment works. Editing an existing issue body to add a mention does
  not trigger anything.
- Only accounts on the policy allow-list can turn a request into a ticket.
