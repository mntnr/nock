# Contribute

👋 Thanks for thinking about contributing to nock! We, the maintainers, are glad you're here and will be excited to help you get started if you have any questions. For now, here are some basic instructions for how we manage this project.

Please note that this project is released with a [Contributor Code of Conduct](./CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

**Table of Contents**

<!-- toc -->

- [Commit Message conventions](#commit-message-conventions)
- [Generate README TOC](#generate-readme-toc)
- [Running tests](#running-tests)
  * [Airplane mode](#airplane-mode)
- [Become a Maintainer](#become-a-maintainer)

<!-- tocstop -->

### Commit Message conventions

`nock` releases are automated using [semantic-release](https://github.com/semantic-release/semantic-release).
To automatically calculate the correct version number as well as changelogs,
three commit message conventions need to be followed

- Commit bug fixes with `fix: ...` or `fix(scope): ...` prefix in commit subject
- Commit new features with `feat: ...` or `feat(scope): ...` prefix in commit subject
- Commit breaking changes by adding `BREAKING CHANGE: ` in the commit body
  (not the subject line)

Other helpful conventions are

- Commit test files with `test: ...` or `test(scope): ...` prefix
- Commit changes to `package.json`, `.gitignore` and other meta files with
  `chore(filename-without-ext): ...`
- Commit changes to README files or comments with `docs: ...`
- Code style changes with `style: standard`

The commit message(s) of a pull request can be fixed using the `squash & merge` button.

### Generate README TOC

Make sure to update the README's table of contents whenever you update the README using the following npm script.

```
$ npm run toc
```

### Running tests

```
$ npm test
```

#### Airplane mode

Some of the tests depend on online connectivity. To skip them, set the `AIRPLANE` environment variable to some value.

```
$ export AIRPLANE=true
$ npm test
```

### Become a Maintainer

Nock is an open source project. That means that we depend upon people to submit code patches, and that we depend upon maintainers to keep work going. This means people who either work on their own time, or who take time while they are doing their jobs elsewhere to help out. We'd love to have more maintainers!

At the moment, there isn't a clear "Do X to become Y" for Nock. The general rule is this: get involved. If you want to be one of the maintainers of Nock, along with all of the fame and glory and 🎉 that entails, then start contributing any way you can. Here are some ideas:

- Suggest labels for issues;
- Help diagnose bugs;
- Suggest enhancements that will help Nock be better;
- Review other people's PRs! You don't need to be a maintainer to say that you approve of one;
- Generally be welcoming and helpful!

We'll notice. If you'd like to become a maintainer with commit access, speak to one of the other maintainers (see the list of contributors and look at the people who've recently merged PRs) on another medium, like Twitter, and ask if you can help out. We'd love to help!

Here, we believe that helpful community members become frequent contributors, and that great contributors make the best maintainers. Our doors are open.
