# 防止欺诈的用户数据

![user-data-for-fraud-prevention logo](./user-data-for-fraud-prevention-logo.png)

[![CircleCI](https://circleci.com/gh/intuit/user-data-for-fraud-prevention/tree/master.svg?style=shield)](https://circleci.com/gh/intuit/user-data-for-fraud-prevention/tree/master)[![Coverage Status](https://coveralls.io/repos/github/intuit/user-data-for-fraud-prevention/badge.svg?branch=master)](https://coveralls.io/github/intuit/user-data-for-fraud-prevention?branch=master)![NPM Version](https://img.shields.io/npm/v/user-data-for-fraud-prevention)![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange)[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->

[![All Contributors](https://img.shields.io/badge/all_contributors-20-orange.svg?style=flat-square)](#contributors-)

<!-- ALL-CONTRIBUTORS-BADGE:END -->

## 描述

这是一个 npm 库，用于检测用户的一些浏览器或设备详细信息，例如时区、屏幕大小、浏览器配置等。
软件供应商通常需要将此类详细信息发送给其所在国家/地区的税务机关，以防止欺诈。

例如：英国税务局 (HMRC) 要求软件提供商使用其某些 API 提供一致的标头，称为欺诈预防标头。此节点模块以所需的格式为您收集此类信息。

中的每个顶级文件夹`src/js`有自己的自述文件，其中包含有关用例的更具体信息。例如。[英国海关总署自述文件](src/js/hmrc/README.md)

## 如何使用

可以找到使用说明[这里](./USAGE.md)

## 如何测试

可以找到测试更改的说明[这里](./DEMO.md)

## 贡献

我们不允许贡献者提出问题。如果你发现一些有趣的东西可以为 repo 做出贡献，请随时提出 PR。我们不要求您提前通知我们。

1.  分叉回购
2.  通过运行在本地安装依赖项`yarn`或者`npm install`
3.  进行更改
4.  确保它使用`yarn build`或者`npm run build`
5.  运行测试（你添加了测试，对吧？）`npm test`或者`yarn test`
6.  在使用代码或使用我们的演示项目中测试您的更改：运行[`yarn link`](https://classic.yarnpkg.com/en/docs/cli/link)或者[`npm link`](https://docs.npmjs.com/cli/link)
7.  确保代码覆盖率与更改前相同或更高
8.  确保提交消息的格式正确：`type(subject): input`.例如：`chore(prettier): update prettier to 2.x`
9.  创建 PR 到`master`分支
10. 代码所有者将被自动要求审核，因此无需在您的 PR 上添加标签

## 预期项目结构

此处显示的结构是您的代码在存储库中的组织方式

应根据您要解决的问题重命名实现文件夹，例如。英国 HMRC 的代码位于名为 hmrc 的文件夹中。

    Project
    └──src
         └──js
            └──common                // Common and non specific code shoud be put in this folder
            └──implementation       // Implementation specific code for solving problem should be in this folder

## 如何将贡献者添加到自述文件中

有两种方法可以将自己添加为此 repo 的贡献者：

1.  通过在 PR 中添加以下注释来调用 @all-contributors bot：**@all-contributors 请添加[用户名]为了[贡献]**.请参考[文档](https://allcontributors.org/docs/en/bot/usage)了解更多信息。
2.  通过运行使用 all-contributors-cli`npx all-contributors add [username] [contributions]`.请参考[文档](https://allcontributors.org/docs/en/cli/usage)了解更多信息。

所有参数都是必需的。
见[表情符号键（贡献类型参考）](https://allcontributors.org/docs/en/emoji-key)获取有效贡献类型的列表。

## 执照

[执照](LICENSE)

## 变更日志

请看我们的[变更日志](CHANGELOG.md)

## 贡献者

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->

<!-- prettier-ignore-start -->

<!-- markdownlint-disable -->

<table>
  <tr>
    <td align="center"><a href="http://rachelquan.xyz/"><img src="https://avatars1.githubusercontent.com/u/39972689?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Rachel Quan</b></sub></a><br /><a href="#tool-rachelquan" title="Tools">🔧</a> <a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=rachelquan" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/reubenae"><img src="https://avatars1.githubusercontent.com/u/17691502?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Reuben</b></sub></a><br /><a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=reubenae" title="Documentation">📖</a> <a href="https://github.com/intuit/user-data-for-fraud-prevention/pulls?q=is%3Apr+reviewed-by%3Areubenae" title="Reviewed Pull Requests">👀</a> <a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=reubenae" title="Tests">⚠️</a> <a href="#question-reubenae" title="Answering Questions">💬</a> <a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=reubenae" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/skodamarthi"><img src="https://avatars0.githubusercontent.com/u/4538858?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Susmitha Kodamarthi</b></sub></a><br /><a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=skodamarthi" title="Documentation">📖</a> <a href="https://github.com/intuit/user-data-for-fraud-prevention/pulls?q=is%3Apr+reviewed-by%3Askodamarthi" title="Reviewed Pull Requests">👀</a> <a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=skodamarthi" title="Tests">⚠️</a> <a href="#question-skodamarthi" title="Answering Questions">💬</a> <a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=skodamarthi" title="Code">💻</a></td>
    <td align="center"><a href="https://www.youtube.com/user/coolbuddymax"><img src="https://avatars2.githubusercontent.com/u/29047276?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Mayank Khanna</b></sub></a><br /><a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=khanna98" title="Code">💻</a></td>
    <td align="center"><a href="https://jitinmaher.me"><img src="https://avatars3.githubusercontent.com/u/7746087?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Jitin Maherchandani</b></sub></a><br /><a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=jitinmaher" title="Code">💻</a></td>
    <td align="center"><a href="https://benknoble.github.io/"><img src="https://avatars3.githubusercontent.com/u/22802209?v=4?s=100" width="100px;" alt=""/><br /><sub><b>D. Ben Knoble</b></sub></a><br /><a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=benknoble" title="Code">💻</a></td>
    <td align="center"><a href="https://linktr.ee/misrayashasvi"><img src="https://avatars.githubusercontent.com/u/54177363?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Yashasvi Misra</b></sub></a><br /><a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=yashasvimisra2798" title="Documentation">📖</a></td>
  </tr>
  <tr>
    <td align="center"><a href="http://www.linkedin.com/in/vijaya-lakshmi-venkatraman"><img src="https://avatars.githubusercontent.com/u/34595292?v=4?s=100" width="100px;" alt=""/><br /><sub><b>vvijayalakshmi21</b></sub></a><br /><a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=vvijayalakshmi21" title="Documentation">📖</a> <a href="#maintenance-vvijayalakshmi21" title="Maintenance">🚧</a></td>
    <td align="center"><a href="http://tylerkrupicka.com/"><img src="https://avatars.githubusercontent.com/u/5761061?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Tyler Krupicka</b></sub></a><br /><a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=tylerkrupicka" title="Code">💻</a> <a href="#plugin-tylerkrupicka" title="Plugin/utility libraries">🔌</a></td>
    <td align="center"><a href="https://github.com/burzynnn"><img src="https://avatars.githubusercontent.com/u/33811303?v=4?s=100" width="100px;" alt=""/><br /><sub><b>burzynnn</b></sub></a><br /><a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=burzynnn" title="Tests">⚠️</a> <a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=burzynnn" title="Code">💻</a></td>
    <td align="center"><a href="https://christyjacob4.github.io/"><img src="https://avatars.githubusercontent.com/u/20852629?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Christy Jacob</b></sub></a><br /><a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=christyjacob4" title="Documentation">📖</a> <a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=christyjacob4" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/joshharrison626"><img src="https://avatars.githubusercontent.com/u/14062743?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Josh Harrison</b></sub></a><br /><a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=joshharrison626" title="Documentation">📖</a> <a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=joshharrison626" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/JohanAludden"><img src="https://avatars.githubusercontent.com/u/11306?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Johan Aludden</b></sub></a><br /><a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=JohanAludden" title="Code">💻</a></td>
    <td align="center"><a href="http://hipstersmoothie.com/"><img src="https://avatars.githubusercontent.com/u/1192452?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Andrew Lisowski</b></sub></a><br /><a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=hipstersmoothie" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://soubai.me/"><img src="https://avatars.githubusercontent.com/u/11523791?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Abderrahim SOUBAI-ELIDRISI</b></sub></a><br /><a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=AbderrahimSoubaiElidrissi" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/dereklouis"><img src="https://avatars.githubusercontent.com/u/71146953?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Derek Louis</b></sub></a><br /><a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=dereklouis" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/sheetalsingala"><img src="https://avatars.githubusercontent.com/u/15062163?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Sheetal Singala</b></sub></a><br /><a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=sheetalsingala" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/salilbc"><img src="https://avatars.githubusercontent.com/u/9673247?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Salil Cuncoliencar</b></sub></a><br /><a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=salilbc" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/Ayushisood"><img src="https://avatars.githubusercontent.com/u/63868702?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Ayushi</b></sub></a><br /><a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=Ayushisood" title="Documentation">📖</a></td>
    <td align="center"><a href="https://www.linkedin.com/in/swasty/"><img src="https://avatars.githubusercontent.com/u/64654203?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Swastika Gupta</b></sub></a><br /><a href="https://github.com/intuit/user-data-for-fraud-prevention/commits?author=Swastyy" title="Documentation">📖</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->

<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
