---
title: 'Contributing'
linkTitle: 'Contributing'
weight: 8
description: >
  Contributors are welcome! Find out how to get start.
---

---

See something that needs fixing? Got an idea for a new feature? Contribute a [Pull Request](#Create-a-Pull-Request)!

## Ready-to Code Dev env

[![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/cdimascio/express-openapi-validator)

Click the Gitpod badge to setup a ready to code dev env in the cloud.

## Local Dev env

### Prerequisites / Setup

Fork the repo

```shell
# The clone your copy
git clone <forked-repo>
```

Install the dependencies

```shell
# From the project directory, run
npm i
```

Be [Create a Pull Request](#create-a-pull-request) once you've written you code.

### Run the tests

Run the tests

```shell
npm test
```

### Develop

- Write code
- Add tests to validate new behaviors
- Ensure all tests succeed
- Create a PR
- Have fun!

### Create a Pull Request

1. Fork it
2. Clone it to your local system
3. Make a new branch
4. Make your changes
5. Push it back to your repo
6. From the Github UI, Click the Compare & pull request button

   NOTE: this button will be present for some period of time after 5. If the button no longer there, Create pull request and select the branches manually)

7. From the Github UI, Click Create pull request to open a new pull request
8. Detailed steps with example here:

### Project structure

`src` contains the source code
`test` contains the tests

## Need help?

Reach out on [gitter](https://gitter.im/cdimascio-oss/community).

We're happy to help!

## FAQ

**Q:** I don't have permission to create a branch and I can't push my changes

**A:** You cannot directly create a branch in this repo. Instead [Create a Pull Request](#create-a-pull-request)

### Generate Change Log

_If you are not project owner, ignore everything below_

Run the following each time a release is cut.

```shell
npm install -g conventional-changelog-cli
conventional-changelog -p express-openapi-validator -i CHANGE_HISTORY.md -s
```

## Thanks!