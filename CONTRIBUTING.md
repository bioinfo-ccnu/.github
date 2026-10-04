# 参与贡献 · Contributing

欢迎提交代码改进、文档修正、可复现示例、问题反馈和学习资源。中文和英文均可。具体项目有自己的贡献说明时，请优先遵循项目要求。

## 提出问题或建议

先查看 README 和已有 Issue，确认是否已有说明或相关讨论。项目问题请在对应仓库提交；组织首页、资源建议或协作想法请在 [`.github` 仓库](https://github.com/bioinfo-ccnu/.github/issues/new/choose) 提交。

问题反馈请说明：

- 使用的版本、运行环境与实际命令；
- 预期结果与实际结果；
- 能触发问题的最小示例、必要日志，以及你已尝试的解决方式。

大型功能或研究流程调整，建议先用 Issue 讨论目标与验证方法，再投入实现。

## 提交 Pull Request

1. Fork 仓库，从默认分支创建描述清晰的工作分支，例如 `docs/install-guide` 或 `fix/sample-order`。
2. 每个 PR 聚焦一个问题，尽量让改动容易审阅。
3. 同步更新受影响的文档、运行示例和环境说明。
4. 运行项目已有的相关检查；分析流程应说明用于验证的示例输入和预期输出。
5. 在 PR 中说明改动目的、相关 Issue 和验证结果。未能完成的验证请如实记录。

仅修改本组织介绍或文本时，检查内容、链接与渲染即可。涉及分析逻辑时，请提供能发现该问题或验证新行为的检查。

## 科研代码与复现

- 明确数据来源、访问方式与许可；必要时记录 accession、DOI 或下载链接。
- 记录依赖版本、主要参数和随机种子；随机结果同时说明允许的误差。
- 优先使用小型公开数据或合成数据作为示例，避免将大文件直接提交到 Git。
- 修改分析方法时，解释对结果的影响；不要只提供截图或无法运行的片段。
- 引用参考方法、软件和论文；贡献代码、文档或数据前确认有权分享。

公开的 Issue、日志和代码请勿包含访问令牌、个人身份信息、受限临床资料或未获授权的数据；可使用脱敏或合成示例说明问题。

## 协作方式

讨论应围绕具体问题和证据展开，尊重不同背景的贡献者。遇到争议时，解释复现步骤或设计取舍，避免针对个人。

## English quick guide

Read the repository's own instructions first. Open an issue with a minimal example, environment details, and expected versus observed behavior. Keep pull requests focused and document the checks you ran. For research workflows, record data provenance, dependency versions, parameters, and reproducibility details. Use public or synthetic examples and ensure that you have permission to share contributed material.
