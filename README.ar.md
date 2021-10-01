# بيانات المستخدم لمنع الاحتيال

![user-data-for-fraud-prevention logo](./user-data-for-fraud-prevention-logo.png)

[![CircleCI](https://circleci.com/gh/intuit/user-data-for-fraud-prevention/tree/master.svg?style=shield)](https://circleci.com/gh/intuit/user-data-for-fraud-prevention/tree/master)[![Coverage Status](https://coveralls.io/repos/github/intuit/user-data-for-fraud-prevention/badge.svg?branch=master)](https://coveralls.io/github/intuit/user-data-for-fraud-prevention?branch=master)![NPM Version](https://img.shields.io/npm/v/user-data-for-fraud-prevention)![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange)[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->

[![All Contributors](https://img.shields.io/badge/all_contributors-20-orange.svg?style=flat-square)](#contributors-)

<!-- ALL-CONTRIBUTORS-BADGE:END -->

## وصف

هذه مكتبة npm لاكتشاف بعض تفاصيل المتصفح أو الجهاز للمستخدم مثل المنطقة الزمنية وأحجام الشاشة وتهيئة المتصفح وما إلى ذلك.
غالبًا ما يُطلب من مزودي البرامج إرسال مثل هذه التفاصيل إلى مصلحة الضرائب في بلادهم لمنع الاحتيال.

على سبيل المثال: تطلب مصلحة الضرائب في المملكة المتحدة (HMRC) من مزودي البرامج استخدام بعض واجهات برمجة التطبيقات الخاصة بهم لتوفير رؤوس متسقة تُعرف باسم رؤوس منع الاحتيال. تجمع وحدة العقدة هذه المعلومات من أجلك بالتنسيق المطلوب.

كل مجلد من المستوى الأعلى بتنسيق`src/js`لديه README الخاص به مع مزيد من المعلومات المحددة حول حالة الاستخدام. على سبيل المثال[HMRC README](src/js/hmrc/README.md)

## كيف تستعمل

Usage instructions can be found [هنا](./USAGE.md)

## كيف تختبر

يمكن العثور على تعليمات اختبار التغييرات[هنا](./DEMO.md)

## المساهمة

نحن لا نسمح للمساهمين بالمطالبة بالقضايا. إذا وجدت شيئًا مثيرًا للاهتمام يمكنك المساهمة في الريبو ، فلا تتردد في رفع العلاقات العامة. لا نطلب منك إعلامنا مسبقًا.

1.  شوكة الريبو
2.  تثبيت التبعيات محليًا عن طريق التشغيل`yarn`أو`npm install`
3.  قم بإجراء تغييراتك
4.  تأكد من أنه يبني باستخدام`yarn build`أو`npm run build`
5.  قم بتشغيل الاختبارات (أضفت الاختبارات ، أليس كذلك؟) باستخدام`npm test`أو`yarn test`
6.  اختبر تغييراتك في التعليمات البرمجية المستهلكة أو باستخدام مشروعنا التجريبي: Run[`yarn link`](https://classic.yarnpkg.com/en/docs/cli/link)أو[`npm link`](https://docs.npmjs.com/cli/link)
7.  تأكد من أن تغطية الكود هي نفسها أو أعلى مما كانت عليه قبل تغييراتك
8.  تأكد من تنسيق رسالة الالتزام بشكل صحيح:`type(subject): input`. على سبيل المثال:`chore(prettier): update prettier to 2.x`
9.  قم بإنشاء علاقات عامة لـ`master`فرع
10. سيُطلب من مالكي الأكواد المراجعة تلقائيًا ، لذلك لا داعي للإشارة إلى العلاقات العامة الخاصة بك

## الهيكل المتوقع للمشروع

الهيكل الموضح هنا هو كيفية تنظيم الكود الخاص بك في المستودع

يجب إعادة تسمية مجلد التنفيذ وفقًا للمشكلة التي تحلها على سبيل المثال. رمز HMRC في المملكة المتحدة موجود في المجلد المسمى hmrc.

    Project
    └──src
         └──js
            └──common                // Common and non specific code shoud be put in this folder
            └──implementation       // Implementation specific code for solving problem should be in this folder

## كيف يتم إضافة المساهمين إلى README

هناك طريقتان لإضافة نفسك كمساهم في هذا الريبو:

1.  Call @ all-Contributions bot بإضافة هذا التعليق التالي في العلاقات العامة:**@ جميع المساهمين الرجاء إضافة[اسم االمستخدم]ل[مساهمات]**. يرجى الرجوع إلى[المستندات](https://allcontributors.org/docs/en/bot/usage)لمزيد من المعلومات.
2.  استخدم كل المساهمين عن طريق التشغيل`npx all-contributors add [username] [contributions]`. يرجى الرجوع إلى[المستندات](https://allcontributors.org/docs/en/cli/usage)لمزيد من المعلومات.

جميع المعلمات مطلوبة.
انظر[مفتاح الرموز التعبيرية (مرجع أنواع المساهمة)](https://allcontributors.org/docs/en/emoji-key)للحصول على قائمة أنواع المساهمة الصالحة.

## رخصة

[رخصة](LICENSE)

## التغيير

يرجى الاطلاع على[التغيير](CHANGELOG.md)

## المساهمون

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
