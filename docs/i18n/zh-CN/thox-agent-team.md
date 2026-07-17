# THOX GitHub Agent Team（翻译桥接页）

完整规范请参阅[英文源文档](../../thox-agent-team.md)。

## Review coverage

工作流覆盖问题、问题评论、拉取请求、手动验证和每日策略验证。

## Safe merge gates

仅在必需检查通过、分支保护允许、PR 非草稿、head SHA 匹配且敏感更改完成人工审查后合并。

## Branch pruning

仅删除已合并、同仓库、非默认、非受保护且未被其他开放 PR 引用的功能分支。优先启用 GitHub 自动删除合并分支。
