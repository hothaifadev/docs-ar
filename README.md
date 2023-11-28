# vuejs.org

> **رابط قناة المحادثة على ديسكورد: https://discord.gg/fhEj5nBRaR**

أنشئ هذا الموقع بواسطة [VitePress](https://github.com/vuejs/vitepress) إعتمادا على [@vue/theme](https://github.com/vuejs/vue-theme). يتواجد محتوى الموقع داخل مجلد `src` على شكل ملفات مكتوبة بصيغة ماركداون (Markdown). التعديلات البسيطة يمكن إجراؤها على Github مباشرة وتُرسل بعد ذلك على شكل طلب دمج Pull Request.

يُفضل استخدام مدير الحزم [pnpm](https://pnpm.io/) عند التطوير المحلي.

```bash
pnpm i
pnpm run dev
```

يحتاج هذا المشروع إلى نسخة Node.js `v14.0.0` فما فوق، وذلك لاستخدامه ميزات Javascript الجديدة، مثل التسلسل الإختياري (optional chaining).

تصفح توثيق VitePress حول [إمتدادات ماركداون](https://vitepress.vuejs.org/guide/markdown.html) المدعومة، [وإمكانية استخدام تراكيب Vue داخل ماركداون](https://vitepress.vuejs.org/guide/using-vue.html).

## دليل المساهمة في الترجمة العربية

1- ادخل إلى [الموقع العربي](https://vuejs-docs-ar.netlify.app) وألقِ نظرة على آخر التطورات في عملية الترجمة.

2- إقرأ هذا الدليل كاملا، لتتعرف على طريقة عملنا والقواعد المعمول بها في الفريق.

3- انضمّ إلينا في [غرفة المحادثة على ديسكورد](https://discord.gg/XFGPM24j) وألقِ التحية، ستجد من يرحب بك هناك.

4- أنشئ نسخة فرعية (fork) من هذ المستودع، ونصّبها على جهازك.

5- أدخل إلى [القضية التي نتابع فيها سير عملية الترجمة](https://github.com/Abdelaziz18003/vuejs-docs-ar/issues/2)، وتصفّح المهام المفتوحة.

6- إذا أردت العمل على مهمّة ما، تأكّد أوّلا أنها غير مُسندة لأحد، بعدها اترك تعليقا عليها بأنك تودّ العمل عليها وستُسند إليك بعد ذلك

7- عند الإنتهاء من ترجمة الصفحة التي تعمل عليها، أرسل طلبا لدمجها في هذا المستودع (Pull Request)، سيراجعها أحد الأعضاء ويدمجها مباشرة إن كانت سليمة من الأخطاء، أو يطلب تعديلات عليها لتتوافق مع باقي الترجمات ويدمجها بعد إجراء التعديلات.

8- هكذا تكون المهمّة الأولى قد تمت بنجاح، الآن ابحث عن مهامّ أخرى وساعدنا في إتمامها 😊

9- إذا واجهتك مشكلة في كتابة اللغة العربية على محرر النصوص، ننصحك باستخدام محرر [دوِّن](https://www.dawin.io/) على الأنترنت.

## توصيات

1- يفضّل قراءة الصفحة كاملة في البداية وفهم سياقها قبل البدء في عملية الترجمة، الترجمة الحرفية في كثير من الأحيان تشوه المعنى وتفشل في إيصاله، لذا يفضّل معرفة السياق وفهم المعنى الإنجليزي والإستعمال البرمجي جيدا قبل ترجمته للعربية.

2- عند مصادفة المصطلحات التقنية (Component أو Slot مثلاً)، يرجى البحث عن ترجمة هذا المصطلح في ملف `glossary.md` داخل المستودع ثم داخل الملفات المترجمة مسبقا قبل محاولة استحداث ترجمة جديدة.

3- إذا لم تجد المصطلح في المصادر السابقة، يرجى البحث عنه في ترجمات إطارات العمل السابقة (ترجمة React مثلاً)، أو الإستعانة بمصادر أخرى للمصطلحات التقنية مثل [موسوعة حسوب](https://wiki.hsoub.com) أو قاموس [مصطلح](https://mostalah.org) أو قاموس [المعاني](https://www.almaany.com/ar/dict/ar-en/).

4- في حالة عدم وجود ترجمة شائعة لمصطلح معين، أو وجود تضارب في الترجمات السابقة، يرجى فتح نقاش حول هذا المصطلح في القناة المخصصة لذلك في غرفة المحادثة، بعدها يتناقش أعضاء الفريق حول الترجمة المناسبة، وتسجل في ملف المصطلحات المعتمد `glossary.md` وتصير الترجمة التي ينبغي اعتمادها مستقبلا داخل هذا الموقع.

## قواعد ترجمة المصطلحات الجديدة

فريق [موقع أعجوبة](https://web.archive.org/web/20220713155406/https://ojuba.org/%D8%A7%D9%84%D8%B1%D8%A6%D9%8A%D8%B3%D8%A9) كان لهم جهد كبير مشكور في ترجمة البرمجيات مفتوحة المصدر، وقد أبدعوا أيّما إبداع في وضع قواعدَ لترجمة مصطلحات الحاسوب إلى اللغة العربية،
سننقل هذه القواعد ونعتمدها كما هي عند الإتيان بالمصطلحات الجديدة، اللهم إلاّ في بعض الحالات الإستثنائية التي يكون هناك سبب مقنع للعدول عنها أو عن بعضها.

**أولا :** عدم الاعتياد على استخدام المصطلح العربي يمثل أهم الحواجز لتقبل المصطلح العربي. لذلك فحالما تعتاد الأذن على المصطلح ويكثر استخدامه يصبح التعامل مع المصطلح واشتقاقاته مسألة طبيعية بل بديهية. لذلك فإننا نحث الجميع على عدم رفض المصطلح أو السخرية منه حتى يثبت أو يزول بالتجربة والاستخدام.

**ثانيا :** الترجمة لا تكون دائما حرفية، بل عليها مراعاة الدلالة العميقة للاستعمال الاصطلاحي وليس للأصل اللغوي. ويجب أن تراعي الترجمة كذلك تداول الكلمة العربية.

**ثالثا :** يجب أن نبتعد قدر الإمكان عن استخدام المصطلح بلفظه الإنجليزي ونحاول في المقابل الإبداع في إيجاد الكلمة العربية الأصيلة المقابلة.

**رابعا :** ننصح دائما باستخدام الصيغة المصدرية للمصطلح بدلا عن صيغ الأفعال عند ترجمة الكلمات المنعزلة. مثلا نفضل قول “حفظ الملف” بدلا عن “احفظ الملف” وننصح بالابتعاد عن الضمائر ومخاطبة المستخدم. مثلا نفضل قول “الصفحة الشخصية” بدلا من “صفحتك الشخصية”. ويكون المصدر نكرة دون “الـ” مثلا “حفظ” وليس “الحفظ”

**خامسا :** إذا كانت الكلمة المترجمة اسما منعزلا مثل About او Preferences يترجم دون التعريف بـ “الـ” (أي “حول” و“تفضيلات” على الترتيب)

**سادسا :** قد تميل الترجمة في المراحل الأولى لئن تكون طويلة وذلك أمر طبيعي لأننا نركز في البداية على توصيل المعنى المطلوب دون لبس أكثر من الاهتمام بالإيجاز ونتوقع أن يتغير هذا مع مرور الوقت عندما يصبح استخدام العربية في علم الحاسوب دارجا أكثر.

**سابعا :** عند اختيار المصطلح العربي علينا اعتبار العديد من الجمل التي تستخدم المصطلح الانجليزي ومن ثم محاولة ترجمة هذه الجمل باستخدام المصطلح الجديد. على سبيل المثال وضعيات المفرد والجمع والاسم والفعل واسم الفاعل واسم المفعول. حتى نتأكد من صحة الاختيار. هنالك حالات محدودة تتغير فيها الكلمة تماما بحسب اشتقاقها ويعود ذلك إلى أن مقابلاتها في اللغة الانجليزية تتغاير كثيرا في المعنى. وهنالك اختبار آخر نقوم به وهو إعادة ترجمة الكلمة العربية إلى الإنجليزية وأن نقدر قرب تلك الترجمة من المصطلح الإنجليزي الأصلي. على سبيل المثال ترجم البعض كلمة Disc إلى أسطوانة وترجمها آخرون إلى قرص. وعندما نعيد كلتا الكلمتين إلى الإنجليزية مرة أخرى نرى أن ترجمة أسطوانة هو Cylinder وليس Disc في حين تعود كلمة قرص إلى Disc وبشكل طبيعي. فيتم بذلك اختيار كلمة قرص.

**ثامنا :** عند ترجمة الجمل والفقرات الانجليزية علينا أن لا نترجم حرفيا أبدا. بل نفهم الجملة جيدا ونفهم سياق الاستخدام ومن ثم نقدم الترجمة العربية حتى لو ترتب على ذلك تغيير شكل الجملة كليا.

باب المشاركة مفتوح للجميع 🤝
