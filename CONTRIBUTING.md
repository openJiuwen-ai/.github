# Contributing Guide

[查看中文版](https://github.com/openJiuwen-ai/.github/blob/main/CONTRIBUTING_zh.md)

Welcome to contribute to the openJiuwen community. openJiuwen is an open-source Agent platform dedicated to providing flexible, powerful, and easy-to-use capabilities for developing and running AI Agents. We encourage developers to participate in many ways, including but not limited to code contributions, documentation improvements, issue reports, and feature suggestions.

This guide covers the common collaboration practices for repositories under the [openJiuwen-ai](https://github.com/openJiuwen-ai) organization. For the full contribution path, see also the website: [Join the openJiuwen open-source community](https://www.openjiuwen.com/en/contribute).

## Code Hosting

GitHub and [openJiuwen on GitCode](https://gitcode.com/openJiuwen) are kept in bidirectional sync so developers on either side can browse and collaborate. Sync coverage includes, but is not limited to:

- **Code and files**: Creates, updates, deletes, and other changes are synced on both sides.
- **Issues**: Issues created, updated, or closed on one side are synced to the other.
- **Pull Requests / Merge Requests**: Related collaboration information is also synced with repository state.

Therefore, please avoid filing duplicate Issues or Pull Requests for the same matter on both GitHub and GitCode, which can create duplicate records or conflicts. Contribute on either side for day-to-day work; the other side will sync automatically.

## Before You Start

- Before contributing, please read and follow the [openJiuwen Community Code of Conduct](https://github.com/openJiuwen-ai/community/blob/main/openJiuwen-Community-Code-of-Conduct.md).
- You must sign the openJiuwen community Contributor License Agreement (CLA) before contributing. GitHub repositories use [CLA Assistant](https://github.com/cla-assistant/cla-assistant): when you open your first Pull Request to a repository, CLA Assistant will comment on the PR with a signing link—follow the prompts to complete signing. After you have signed, later PRs usually do not require signing again.
- Find a repository you are interested in under [openJiuwen-ai](https://github.com/openJiuwen-ai), and read that repository’s `README` and related docs first.

## License

[Apache License 2.0 (Apache-2.0)](https://www.apache.org/licenses/LICENSE-2.0)

## Copyright Guidelines

Code you submit must be original and must not infringe others’ intellectual property rights. When contributing code, follow the [License and Copyright Guidelines](https://github.com/openjiuwen-ai/community/tree/main/contribute/License-and-Copyright-Guidelines.md). If new contributions involve introducing third-party open-source software or quoting fragments, strictly follow the requirements in the [License and Special License Guidance](https://github.com/openjiuwen-ai/community/tree/main/contribute/License-and-Special-License-Review-Guidelines.md).

openJiuwen reserves the right to modify or remove contributed content according to the relevant guidelines until it meets the corresponding requirements.

## Ways to Contribute

### Reporting Issues

High-quality issue reports help us continually improve project quality. The more detailed the information you provide, the more helpful it is.

1. Open the **Issues** page of the target repository (go to the repository under [openJiuwen-ai](https://github.com/openJiuwen-ai), then select Issues).
2. Click **New issue**, briefly describe the problem in the title, and add details in the body.
3. After submitting, please wait patiently for the corresponding maintainers to confirm and follow up.

> **How do I file a high-quality issue?**
>
> - Provide a clear description and the specific location of the problem (module, file, documentation section, etc.), and attach screenshots or logs when helpful.
> - Describe reproduction steps, expected behavior, actual behavior, and the impact on users.
> - For runtime or example errors, provide the relevant openJiuwen component versions, runtime environment, and the full error message.
> - Keep the scope of the issue to one concrete topic or task. If the scope is large, split it into smaller issues. For example, “the project needs optimization” is too broad, while “module XX is missing handling for ZZZ in scenario YYY” is specific and actionable.
> - Search existing issues to check whether a related or similar issue already exists.
> - If the new issue relates to other Issues or PRs, reference them with a full URL or `#number`.

### Online Edits

For small content fixes and additions (such as copy corrections or small-scope fixes), you can edit directly on GitHub.

Steps:

1. Open the relevant file in the target repository on GitHub.
2. Click the pencil icon (**Edit this file**) in the upper-right of the file. If prompted to Fork, follow the instructions to Fork the repository to your account, then edit.
3. Make your changes; use preview to confirm the result when applicable.
4. At the bottom of the page, write a brief change description, submit the change, and create a Pull Request.

Commit messages should follow [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/), for example: `fix: handle empty response in runtime`, `docs: fix typo in quickstart`.

Maintainers will review and merge your changes. Thank you for supporting openJiuwen.

### Local Changes

Suitable when you need to change or add more substantial content (feature development, bug fixes, larger documentation updates, and so on).

Steps:

1. Fork the target repository.
2. Clone it locally, and create a change branch from the repository’s default branch (commonly `main` or `develop`; follow the repository docs).
3. After finishing local changes, commit with a sign-off (using the same email you used to sign the CLA), for example:

   ```bash
   git commit -sm "feat: add xxx support"
   ```

   Example: `Signed-off-by: user.name <user.email>`

4. Push the branch to your Fork, and open a Pull Request against the upstream repository on GitHub.
5. Wait for CI checks and maintainer review; it will be merged after approval.

**Suggested PR description:** purpose and background, main changes, testing notes, and related Issue numbers.

## Community Communication

If you run into problems while using or contributing, you can reach us through:

- Website: <https://www.openjiuwen.com>
- Email: contact@openjiuwen.com
- Community repository: <https://github.com/openJiuwen-ai/community>

