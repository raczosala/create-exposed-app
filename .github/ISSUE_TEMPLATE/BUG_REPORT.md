---
name: Bug report
about: Something wrong? Create a bug report to improve the project.
title: Summary of Bug Report, Present Tense, < 50 Characters
labels: bug
assignees: iamturns
---

**Checklist**

<!-- Thanks for contributing! Put an x in the boxes that apply: [X]. You can also fill these out after creating the PR. If you're unsure about any of them, don't hesitate to ask. We're here to help! -->

- [ ] Following [CODE_OF_CONDUCT.md](https://github.com/iamturns/create-exposed-app/blob/master/CODE_OF_CONDUCT.md).
- [ ] Checked for [duplicate bug reports](https://github.com/iamturns/create-exposed-app/issues?q=label%3Abug).

**Bug report**
Introduce the bug with a summary.

**Expected behavior**
What should happen?

**Actual behaviour**
What happens instead? Please include if possible and/or relevant: error messages, stack traces, logs, screenshots.

**Steps to reproduce**

1. ...
2. ...
3. ...

Please include if possible and/or relevant: code, config, links, repository that reproduces the bug.

**Environment**

- `create-exposed-app` version:
- Operating System and version:
- _Client-side bug?_
- Device used: [e.g. iPhone 6, MacBook Pro]
- Browser name and version: [e.g. Chrome XX | Safari XX | Android Browser XX ]
- _Server-side bug?_
- Node.js version:
- npm version:

Run the following script to collect version information:

```bash
node -e "\
const os = require('os');\
const cp = require('child_process');\
console.log('Operating System and version:: ' + os.platform() + ' ' + os.release());\
console.log('Node.js version: ' + process.version);\
console.log('npm version: ' + cp.execSync('npm -v'));\
"
```

**Additional**
E.g. suggested solution, theories, etc.