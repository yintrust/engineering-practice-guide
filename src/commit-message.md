# commit message

编写规范的 commit message 不仅可以让别人清晰的了解对代码所作的更改，还能便捷的生成 changelog。

事实上，[约定式提交](https://www.conventionalcommits.org/zh-hans/v1.0.0-beta.4/) 就是针对编写 commit message 的一系列规范。
按照此规范，commit message 的结构应如下所示：

```text
<类型>[可选的作用域]: <描述>

[可选的正文]

[可选的脚注]
```

其中，类型指此次提交所属的类型；作用域 **必须** 是一个描述某部分代码的名词，并用圆括号包围；
描述指的是对代码变更的简短总结；正文为代码变更提供额外的上下文信息；
脚注 **必须** 包含关于提交的元信息，例如：关联的合并请求、Reviewer、破坏性变更，每条元信息一行。

[Angular Commit Message Guidelines](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#commit) 中提供了 9 种可选的类型，我们参考此使用以下类型：

- `fix`：修复 bug
- `feat`：新功能
- `refactor`：既没有修复 bug 也没有添加新功能的代码更改
- `test`：添加缺失的测试或更正现有的测试
- `style`：不会影响代码含义的更改（空格，格式，缺少分号等）
- `perf`：提高性能的代码更改
- `docs`：仅文档更改
- `chore`：修改工具相关（包括但不限于文档、代码生成等）

按照上述规范，一个典型的 commit message 如下所示：

```text
fix: correct minor typos in code

see the issue for details on the typos fixed

closes issue #12
```

以下是一些遵守此规范的开源项目，可供参考：

- [Angular](https://github.com/angular/angular)
- [Electron](https://github.com/electron/electron)
- [egg](https://github.com/eggjs/egg)

Tips：如果你的开源项目也遵循 **约定式提交** 规范，不妨在 README 文件中加上徽章吧！

```text
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org)
```

显示效果如下：

[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org)

> **_SEEALSO:_** 
>
> 阮一峰写的关于 commit message 的博客：[Commit message 和 Change log 编写指南](https://www.ruanyifeng.com/blog/2016/01/commit_message_change_log.html)
>
> 知乎上关于 commit message 的讨论：[如何写好 Git commit log?](https://www.zhihu.com/question/21209619)
