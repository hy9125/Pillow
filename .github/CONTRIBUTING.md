# Contributing to Pillow

Bug fixes, feature additions, tests, documentation and more can be contributed via [issues](https://github.com/python-pillow/Pillow/issues) and/or [pull requests](https://github.com/python-pillow/Pillow/pulls). All contributions are welcome.

## Bug fixes, feature additions, etc.

Please send a pull request to the master branch. Please include [documentation](https://pillow.readthedocs.io) and [tests](../Tests/README.rst) for new features. Tests or documentation without bug fixes or feature additions are welcome too. Feel free to ask questions [via issues](https://github.com/python-pillow/Pillow/issues/new) or irc://irc.freenode.net#pil

- Fork the Pillow repository.
- Create a branch from master.
- Develop bug fixes, features, tests, etc.
- Run the test suite on Python 2.7 and 3.x. You can enable [Travis CI](https://travis-ci.org/profile/) and [AppVeyor](https://ci.appveyor.com/projects/new) on your repo to catch test failures prior to the pull request, and [Coveralls](https://coveralls.io/repos/new) to see if the changed code is covered by tests.
- Create a pull request to pull the changes from your branch to the Pillow master.

### Guidelines

- Separate code commits from reformatting commits.
- Provide tests for any newly added code.
- Follow PEP8.
- When committing only documentation changes please include [ci skip] in the commit message to avoid running tests on Travis-CI and AppVeyor.

## Reporting Issues

When reporting issues, please include code that reproduces the issue and whenever possible, an image that demonstrates the issue. The best reproductions are self-contained scripts with minimal dependencies.

### Provide details

- What did you do?
- What did you expect to happen?
- What actually happened?
- What versions of Pillow and Python are you using?

## Security vulnerabilities

To report sensitive vulnerability information, email security@python-pillow.org.

If your organisation/employer is a distributor of Pillow and would like advance notification of security-related bugs, please let us know your preferred contact method.
