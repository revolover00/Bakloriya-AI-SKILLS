# 🎓 المعلم الذكي لمناهج البكالوريا المصرية (`Bakloriya-AI-SKILLS`)

مستودع تعليمي مهيكل يحوّل الكتب المدرسية والمرجعية الرسمية لنظام **البكالوريا المصرية (الصف الثاني بكالوريا — ٢ ثانوي — دفعة 2027)** إلى ملفات نصية قياسية (`Raw Markdown`) منظمة حسب المواد والفصول، مما يتيح لأي نموذج ذكاء اصطناعي (ChatGPT، Claude، Gemini، Grok، Perplexity، DeepSeek، Cursor، وغيرها) العمل فورًا كـ **معلم خصوصي خبير بالمنهج المصري** يشرح الدروس، ويحل المسائل والأسئلة الاستنتاجية، ويدرّب الطالب على أنماط الامتحانات بدقة الكتاب المدرسي دون تأليف.

---

## 🧭 بوابة المواد الدراسية المتاحة (كل مادة لها دليل `README.md` مستقل ومفصل)

اضغط على اسم أي مادة للانتقال إلى صفحتها الخاصة التي تضم فهرس فصولها، روابطها النصية المباشرة (`Raw`)، والبرومبت المخصص لها:

| الصف الدراسي | المادة الدراسية | الكتاب المرجعي المعتمد | الدليل المفصل للمادة (`README.md`) | الفهرس الخام للـ AI (`Raw SKILL.md`) | الحالة |
|---|---|---|---|---|---|
| **٢ بكالوريا** | **🔬 الفيزياء** | الكتاب المدرسي الرسمي (269 صفحة — 14 فصلًا) | **[📖 دليل الفيزياء المفصل](skills/second-year-physics/README.md)** | [`SKILL.md (Raw)`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-physics/SKILL.md) | 🟢 **مكتمل** |
| **٢ بكالوريا** | **🏛️ التاريخ الوطني** *(الترم الأول 2027)* | كتاب الامتحان (454 صفحة — 3 وحدات / 12 درسًا) | **[📖 دليل التاريخ الوطني المفصل](skills/second-year-history/README.md)** | [`SKILL.md (Raw)`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-history/SKILL.md) | 🟢 **مكتمل** |
| **٢ بكالوريا** | **🌐 اللغة الإنجليزية** *(الترم الأول 2027)* | كتاب الأضواء جيم (426 صفحة — 5 وحدات / 20 درسًا) | **[📖 دليل اللغة الإنجليزية المفصل](skills/second-year-english/README.md)** | [`SKILL.md (Raw)`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-english/SKILL.md) | 🟢 **مكتمل** |
| **٢ بكالوريا** | الكيمياء / الرياضيات / الأحياء | الكتب المدرسية والمرجعية | `skills/second-year-<subject>/` | — | 🟡 قيد الإضافة تباعًا |
| **١ و ٣ بكالوريا** | جميع المواد المقررة | الكتب المدرسية والمرجعية | `skills/<grade>-<subject>/` | — | ⚪ المرحلة القادمة |

---

## ⚡ برومبت التشغيل السريع (انسخه والصقه في أي AI)

لأن نماذج الذكاء الاصطناعي لا تستطيع تصفح واجهة GitHub العادية، يستخدم هذا البرومبت المختصر **الرابط النصي المباشر (`Raw URL`)** الذي يمكّن أي AI يدعم تصفح الويب من قراءة فهرس الدروس والوصول لأي فصل مباشرةً كنص صافي:

### 1️⃣ البرومبت الشامل للمواد الثلاث معًا (الفيزياء + التاريخ الوطني + اللغة الإنجليزية)
```text
أنت معلمي الخصوصي للصف الثاني بكالوريا (٢ ثانوي - المنهج المصري 2027).
اقرأ أولًا فهرس المناهج وروابط الفصول النصية المباشرة (Raw URLs) من هذا الرابط:
https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/AGENTS.md

عندما أسألك في أي مادة (الفيزياء / التاريخ الوطني / اللغة الإنجليزية)، افتح رابط الـ Raw الخاص بالدرس المطلوب من داخل الفهرس، والتزم حرفيًا بشرح وقوانين وتعريفات الكتاب المدرسي بدون تأليف، واختبرني بسؤال تطبيقي في نهاية الشرح.
رحّب بي الآن واسألني: أي مادة وأي درس نبدأ به؟
```

### 2️⃣ برومبت مخصص لمادة واحدة فقط (اختياري)
- **للفيزياء فقط:** استبدل الرابط في البرومبت أعلاه بـ:
  `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-physics/SKILL.md`
- **للتاريخ الوطني فقط:** استبدل الرابط في البرومبت أعلاه بـ:
  `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-history/SKILL.md`
- **للغة الإنجليزية فقط:** استبدل الرابط في البرومبت أعلاه بـ:
  `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-english/SKILL.md`

---

## 📐 الهيكلة التنظيمية للمستودع

يتبع المستودع معمارية موحدة لكل مادة دراسية داخل مجلد `skills/`، بحيث تحتوي كل مادة على 5 مكونات قياسية:
1. **`README.md`:** دليل المادة المفصل للطالب والمعلم، وجدول روابط الفصول والبرومبت الخاص بالمادة.
2. **`SKILL.md`:** نقطة الدخول والتوجيه الذكي للـ AI وبروتوكول التدريس والأخطاء الشائعة.
3. **`glossary.md`:** المسرد الكامل للمصطلحات والتعريفات الرسمية الحرفية بالكتاب.
4. **`patterns.md`:** قوالب واستراتيجيات حل المسائل وأنماط أسئلة الامتحانات خطوة بخطوة.
5. **`cheatsheet.md`:** الملخص المكثف، الجداول المقارنة، والخطوط الزمنية للمراجعة السريعة.
6. **`chapters/ch00..chXX.md`:** الفصول والدروس التفصيلية (تُقرأ عند الطلب `On-Demand` لضمان الدقة وعدم تشتيت نموذج الذكاء الاصطناعي).

```text
Bakloriya-AI-SKILLS/
├── README.md                                  # البوابة الرئيسية للمستودع وبرومبت التشغيل الشامل
├── AGENTS.md                                  # الفهرس الرئيسي وروابط Raw المباشرة لجميع الفصول
├── CLAUDE.md                                  # نقطة الدخول التلقائية لـ Claude Code
└── skills/
    ├── second-year-physics/                   # 🔬 فيزياء ٢ بكالوريا (14 فصلًا)
    │   ├── README.md                          # دليل مادة الفيزياء المفصل
    │   ├── SKILL.md                           # بروتوكول الحل (الخطوات السبع) وتوجيه المسائل
    │   ├── glossary.md                        # قاموس المصطلحات الفيزيائية الحرفية
    │   ├── patterns.md                        # 12 قالبًا قياسيًا لحل مسائل المنهج
    │   ├── cheatsheet.md                      # ملخص القوانين والنسب والتناسبات لأسئلة MCQ
    │   └── chapters/                          # الفصول التفصيلية (ch00 إلى ch13)
    │
    ├── second-year-history/                   # 🏛️ التاريخ الوطني ٢ بكالوريا (الترم الأول 2027)
    │   ├── README.md                          # دليل مادة التاريخ الوطني المفصل
    │   ├── SKILL.md                           # شجرة توجيه الأسئلة ومنهجية الشرح التاريخي
    │   ├── glossary.md                        # مسرد المفاهيم الرسمية والشخصيات والمعاهدات
    │   ├── patterns.md                        # الأنماط السبعة لأسئلة الامتحانات واستراتيجيات حلها
    │   ├── cheatsheet.md                      # الخط الزمني الشامل (3200 ق.م – 2007م) وجداول المقارنات
    │   └── chapters/                          # الدروس التفصيلية (ch00 إلى ch12 — 3 وحدات / 12 درسًا)
    │
    └── second-year-english/                   # 🌐 اللغة الإنجليزية ٢ بكالوريا (جيم — الترم الأول 2027)
        ├── README.md                          # دليل مادة اللغة الإنجليزية المفصل
        ├── SKILL.md                           # بروتوكول الشرح ثنائي اللغة واستراتيجية JRE
        ├── glossary.md                        # قاموس المفردات الرئيسية وفروق الكلمات (Focus)
        ├── patterns.md                        # أنماط الجرامر وتحويلات Rewrite وقوالب الكتابة
        ├── cheatsheet.md                      # ملخص الوحدات الخمس وأهم 12 قاعدة ذهبية في الجرامر
        └── chapters/                          # الوحدات التفصيلية (ch00 إلى ch11 — 5 وحدات / 20 درسًا)
```

---

## 📚 المحتوى التفصيلي للمواد الثلاث

### أولًا: 🔬 الفيزياء — الصف الثاني بكالوريا ([`skills/second-year-physics/`](skills/second-year-physics/README.md))

| الملفات المساندة | [`README.md`](skills/second-year-physics/README.md) • [`SKILL.md`](skills/second-year-physics/SKILL.md) • [`glossary.md`](skills/second-year-physics/glossary.md) • [`patterns.md`](skills/second-year-physics/patterns.md) • [`cheatsheet.md`](skills/second-year-physics/cheatsheet.md) |
|---|---|

| الكود | الفصل الدراسي | أبرز الموضوعات والقوانين | تصفح | `Raw` |
|---|---|---|---|---|
| `ch00` | الكميات والوحدات والمتجهات | القياسية والمتجهة، الأساسية والمشتقة، بادئات `SI`، المسافة والإزاحة، تحليل المتجهات | [فتح](skills/second-year-physics/chapters/ch00-intro-quantities-units-vectors.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-physics/chapters/ch00-intro-quantities-units-vectors.md) |
| `ch01` | متجهات السرعة والسرعة النسبية | محصلة سرعتين، السرعة النسبية $\vec{v}_{AB}=\vec{v}_A-\vec{v}_B$، عبور النهر، القطار والمطر | [فتح](skills/second-year-physics/chapters/ch01-velocity-vectors-relative-velocity.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-physics/chapters/ch01-velocity-vectors-relative-velocity.md) |
| `ch02` | العجلة ومعادلات الحركة | العجلة المنتظمة، معادلات الحركة الأربع، السقوط الحر، منحنيات $(d\text{–}t, v\text{–}t, a\text{–}t)$ | [فتح](skills/second-year-physics/chapters/ch02-acceleration-equations-of-motion.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-physics/chapters/ch02-acceleration-equations-of-motion.md) |
| `ch03` | المقذوفات الأفقية | استقلالية المحورين، $t=\sqrt{2h/g}$، المدى الأفقي، الحل بمعادلات الطاقة | [فتح](skills/second-year-physics/chapters/ch03-horizontal-projectiles.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-physics/chapters/ch03-horizontal-projectiles.md) |
| `ch04` | المقذوفات بزاوية | زمن الصعود والتحليق، أقصى ارتفاع، المدى الأفقي، الزوايا المتتامة، المقذوف من مبنى لمنصة | [فتح](skills/second-year-physics/chapters/ch04-angled-projectiles.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-physics/chapters/ch04-angled-projectiles.md) |
| `ch05` | عزم القوة والاتزان الدوراني | $M = Fd = FL\sin\theta$، قاعدة الإشارات، شرط الاتزان الدوراني $\sum M = 0$ والروافع | [فتح](skills/second-year-physics/chapters/ch05-torque.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-physics/chapters/ch05-torque.md) |
| `ch06` | اتزان القوى وقانون نيوتن الأول | $\sum F_x=0, \sum F_y=0$، المخطط الحر، الشد في حبلين، قوة النابض $F_e=-kx$ | [فتح](skills/second-year-physics/chapters/ch06-force-equilibrium.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-physics/chapters/ch06-force-equilibrium.md) |
| `ch07` | الشغل والقدرة والكفاءة | $W = Fd\cos\theta$، $P = W/t = Fv\cos\theta$، الكفاءة $\eta$، مخطط سانكي والقدرة المهدرة | [فتح](skills/second-year-physics/chapters/ch07-work-power-efficiency.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-physics/chapters/ch07-work-power-efficiency.md) |
| `ch08` | كمية التحرك والدفع | $P = mv$، $J = \bar{F}\Delta t = \Delta P$، الارتداد عن حائط، تطبيقات زمن التصادم والوسائد الهوائية | [فتح](skills/second-year-physics/chapters/ch08-momentum-impulse.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-physics/chapters/ch08-momentum-impulse.md) |
| `ch09` | حفظ كمية التحرك | النظام المعزول، التصادم مع التحام، التصادم المرن، الانفجار والارتداد، التصادم في بُعدين | [فتح](skills/second-year-physics/chapters/ch09-conservation-momentum.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-physics/chapters/ch09-conservation-momentum.md) |
| `ch10` | الطاقة الحركية ومعامل الارتداد | $E_k = \frac{1}{2}mv^2$، الطاقة المفقودة $\Delta E_k$، معامل الارتداد $e = -\frac{v_B'-v_A'}{v_B-v_A}$ | [فتح](skills/second-year-physics/chapters/ch10-momentum-mechanical-energy.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-physics/chapters/ch10-momentum-mechanical-energy.md) |
| `ch11` | الحركة الدائرية المنتظمة والقوة المركزية | $T, f, \omega, l=r\theta, v=\omega r$، علاقة هويغنس $a_C=v^2/r=r\omega^2$، القوة المركزية $F_C$ | [فتح](skills/second-year-physics/chapters/ch11-circular-motion-centripetal.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-physics/chapters/ch11-circular-motion-centripetal.md) |
| `ch12` | الدائرية الرأسية والأفقية والبندول المخروطي | شد القمة/القاع/الجانب، السرعة الحرجة $v_{\min}=\sqrt{gr}$، البندول المخروطي، المخروط الدوار | [فتح](skills/second-year-physics/chapters/ch12-vertical-horizontal-circular.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-physics/chapters/ch12-vertical-horizontal-circular.md) |
| `ch13` | قوانين كبلر والجاذبية الكونية | قوانين كبلر الثلاثة، الجذب العام لنيوتن، السرعة المدارية، شدة المجال $g$، المدار الجغرافي الثابت | [فتح](skills/second-year-physics/chapters/ch13-kepler-gravitation.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-physics/chapters/ch13-kepler-gravitation.md) |

---

### ثانيًا: 🏛️ التاريخ الوطني — الصف الثاني بكالوريا ([`skills/second-year-history/`](skills/second-year-history/README.md))

| الملفات المساندة | [`README.md`](skills/second-year-history/README.md) • [`SKILL.md`](skills/second-year-history/SKILL.md) • [`glossary.md`](skills/second-year-history/glossary.md) • [`patterns.md`](skills/second-year-history/patterns.md) • [`cheatsheet.md`](skills/second-year-history/cheatsheet.md) |
|---|---|

| الكود | الوحدة والدرس | أبرز الموضوعات والقضايا التاريخية | تصفح | `Raw` |
|---|---|---|---|---|
| `ch00` | نظرة عامة وخريطة المنهج | فلسفة منهج التاريخ الوطني بالبكالوريا المصرية، خريطة الوحدات الثلاث، والخيط الناظم للمنهج | [فتح](skills/second-year-history/chapters/ch00-overview-and-curriculum-map.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-history/chapters/ch00-overview-and-curriculum-map.md) |
| `ch01` | **الوحدة 1 — الدرس 1:** بناء الدولة المصرية واستمرارها | عوامل الحضارة، الملك مينا ($3200\text{ ق.م}$)، الحكم المركزي، ماعت، وصايا الحكيم بتاح حتب | [فتح](skills/second-year-history/chapters/ch01-building-egyptian-state.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-history/chapters/ch01-building-egyptian-state.md) |
| `ch02` | **الوحدة 1 — الدرس 2:** الدولة المصرية القديمة ومقاومة الاحتلال | الهكسوس (سقنن رع، كامس، أحموس)، معركة مجدو (تحتمس 3)، معركة قادش ومعاهدة السلام (رمسيس 2) | [فتح](skills/second-year-history/chapters/ch02-ancient-egypt-resisting-occupation.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-history/chapters/ch02-ancient-egypt-resisting-occupation.md) |
| `ch03` | **الوحدة 1 — الدرس 3:** التحولات الكبرى في مصر (العصر الوسيط) | مصر الرومانية، عصر الشهداء ($284\text{م}$) والرهبنة، الفتح الإسلامي ($641\text{م}$)، الدول المستقلة، حطين، عين جالوت، العثمانيون | [فتح](skills/second-year-history/chapters/ch03-major-transformations-middle-ages.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-history/chapters/ch03-major-transformations-middle-ages.md) |
| `ch04` | **الوحدة 1 — الدرس 4:** التحولات الكبرى في مصر (العصر الحديث) | الصدمة الحضارية ($1798\text{م}$)، محمد علي والاحتكار، بلطة ليمان ولندن، إسماعيل والديون، الطبقات، التيارات الفكرية | [فتح](skills/second-year-history/chapters/ch04-major-transformations-modern-era.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-history/chapters/ch04-major-transformations-modern-era.md) |
| `ch05` | **الوحدة 2 — الدرس 1:** سياسات الاحتلال بمصر في العصر الحديث | ازدواجية نابليون (التقرب والقمع)، وصف مصر وحجر رشيد، مراحل التدخل الأجنبي، سياسات الاحتلال البريطاني | [فتح](skills/second-year-history/chapters/ch05-occupation-policies-modern-era.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-history/chapters/ch05-occupation-policies-modern-era.md) |
| `ch06` | **الوحدة 2 — الدرس 2:** صمود الشعب المصري ومقاومة الاحتلال | وثيقة الأزهر ($1795\text{م}$)، المراحل السبع لتطور الوعي القومي (الطهطاوي، الأفغاني، عبده، عرابي، كامل، فريد، زغلول، والمرأة) | [فتح](skills/second-year-history/chapters/ch06-egyptian-steadfastness-resistance.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-history/chapters/ch06-egyptian-steadfastness-resistance.md) |
| `ch07` | **الوحدة 2 — الدرس 3:** ثورة 23 يوليو 1952م والتحولات الكبرى | حادث 4 فبراير $1942\text{م}$، نكبة $1948\text{م}$، ظاهرة النصف في المئة، مقدمات الثورة، الجلاء ($1954\text{م}$)، تأميم القناة ($1956\text{م}$) | [فتح](skills/second-year-history/chapters/ch07-july-1952-revolution-transformations.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-history/chapters/ch07-july-1952-revolution-transformations.md) |
| `ch08` | **الوحدة 2 — الدرس 4:** الهوية الوطنية في مواجهة الاستعمار الجديد | الاستعمار الجديد (فخ الديون، التكنولوجيا، هجوم إستونيا $2007\text{م}$)، أدوات حروب الجيل الرابع السبع، وبناء المناعة الفكرية | [فتح](skills/second-year-history/chapters/ch08-national-identity-vs-neocolonialism.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-history/chapters/ch08-national-identity-vs-neocolonialism.md) |
| `ch09` | **الوحدة 3 — الدرس 1:** حركات التحرر ضد الاحتلال الفرنسي والإيطالي | آليات فرنسا (الجزائر، تونس، المغرب، موريتانيا، سوريا) وإيطاليا (ليبيا وعمر المختار)، والمقاومة المسلحة والسياسية | [فتح](skills/second-year-history/chapters/ch09-national-liberation-french-italian.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-history/chapters/ch09-national-liberation-french-italian.md) |
| `ch10` | **الوحدة 3 — الدرس 2:** حركات التحرر ضد الاحتلال البريطاني والإسباني | آليات بريطانيا (مصر، الخليج، عدن، السودان، العراق، فلسطين) وفشل النجلزة بمصر، وإسبانيا في الريف (الخطابي) | [فتح](skills/second-year-history/chapters/ch10-national-liberation-british-spanish.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-history/chapters/ch10-national-liberation-british-spanish.md) |
| `ch11` | **الوحدة 3 — الدرس 3:** مرتكزات الدور المصري إقليميًا ودوليًا | الموقع الجيوسياسي («ملتقى الدوائر الثلاث» لجمال حمدان)، قناة السويس، عدم الانحياز وباندونج ($1955\text{م}$)، والقوة الناعمة | [فتح](skills/second-year-history/chapters/ch11-pillars-of-egypts-regional-global-role.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-history/chapters/ch11-pillars-of-egypts-regional-global-role.md) |
| `ch12` | **الوحدة 3 — الدرس 4:** دور مصر في دعم حركات التحرر الوطني | الدعم المصري السياسي والعسكري والإعلامي (صوت العرب) والثقافي لثورات الجزائر، واليمن (باب المندب)، والعراق، وجنوب إفريقيا | [فتح](skills/second-year-history/chapters/ch12-egypts-role-supporting-national-liberation.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-history/chapters/ch12-egypts-role-supporting-national-liberation.md) |

---

### ثالثًا: 🌐 اللغة الإنجليزية — الصف الثاني بكالوريا ([`skills/second-year-english/`](skills/second-year-english/README.md))

| الملفات المساندة | [`README.md`](skills/second-year-english/README.md) • [`SKILL.md`](skills/second-year-english/SKILL.md) • [`glossary.md`](skills/second-year-english/glossary.md) • [`patterns.md`](skills/second-year-english/patterns.md) • [`cheatsheet.md`](skills/second-year-english/cheatsheet.md) |
|---|---|

| الكود | المفهوم والوحدة والقسم | الدروس والقواعد والمهارات المشمولة | تصفح | `Raw` |
|---|---|---|---|---|
| `ch00` | **نظرة عامة واستراتيجية `JRE`** | خريطة المنهج (5 مفاهيم، 5 وحدات، 20 درسًا) + شرح استراتيجية **`JRE`** وجميع إجاباتها النموذجية بالكتاب (ص 414–422) | [فتح](skills/second-year-english/chapters/ch00-overview-and-jre-strategy.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-english/chapters/ch00-overview-and-jre-strategy.md) |
| `ch01` | **Unit 1 (Sec A):** *Well-being & Lifestyles* | الدروس `1.1` و`1.2` + القواعد: **`Participial Phrases` (`V-ing`, `P.P.`, `Having + P.P.`)** و**`Relative Clauses`** | [فتح](skills/second-year-english/chapters/ch01-unit1-secA-social-media-and-lifestyles.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-english/chapters/ch01-unit1-secA-social-media-and-lifestyles.md) |
| `ch02` | **Unit 1 (Sec B):** *Responsibility & Mental Health* | الدروس `1.3` و`1.4` (`16328` و`PFA`) + القواعد: **`Hedging` و`Conditionals (0, 1st, 2nd, 3rd)` وبدائل `If` وحالات الحذف** | [فتح](skills/second-year-english/chapters/ch02-unit1-secB-responsibility-and-mental-health.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-english/chapters/ch02-unit1-secB-responsibility-and-mental-health.md) |
| `ch03` | **Unit 1 (Sec C — Skills):** *Analytical Skills* | **`Biased vs. Neutral`**، أساليب الكتابة الإقناعية، **`PEEL Analytical Paragraph`**، وقواعد الترجمة | [فتح](skills/second-year-english/chapters/ch03-unit1-secC-skills.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-english/chapters/ch03-unit1-secC-skills.md) |
| `ch04` | **Unit 2 (Sec A):** *Leisure Time (Part 1)* | الدروس `2.1` و`2.2` + القواعد: **`Gerunds & Infinitives (Part 1)`** وأفعال تغير المعنى (`remember, forget, regret, stop, try`) | [فتح](skills/second-year-english/chapters/ch04-unit2-secA-leisure-time.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-english/chapters/ch04-unit2-secA-leisure-time.md) |
| `ch05` | **Unit 2 (Sec B & C):** *Leisure Time (Part 2) & Skills* | الدروس `2.3` و`2.4` + القواعد: **`too...to`, `enough to`, المصدر بدون `to`, أفعال الإدراك، و`go on / mean / need`** + **`Opinion Paragraph & Diary`** | [فتح](skills/second-year-english/chapters/ch05-unit2-secB-and-skills.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-english/chapters/ch05-unit2-secB-and-skills.md) |
| `ch06` | **Unit 3 (Sec A):** *Echoes of the Past (Part 1)* | الدروس `3.1` (معبد الكرنك) و`3.2` (المتحف المصري الكبير `GEM`) + القواعد: **`Prepositional Phrases of Place & Time`** | [فتح](skills/second-year-english/chapters/ch06-unit3-secA-echoes-of-the-past.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-english/chapters/ch06-unit3-secA-echoes-of-the-past.md) |
| `ch07` | **Unit 3 (Sec B & C):** *Documenting History & Skills* | الدروس `3.3` و`3.4` + القواعد: **`Concession Clauses` (`Although, Despite, While it is true that, Admittedly, However + adj.`)** + **`Discursive Essay`** | [فتح](skills/second-year-english/chapters/ch07-unit3-secB-and-skills.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-english/chapters/ch07-unit3-secB-and-skills.md) |
| `ch08` | **Unit 4 (Sec A):** *The Power of Choice (Part 1)* | الدروس `4.1` (هدر الطعام) و`4.2` (العلامات التجارية) + القواعد: **`Present Perfect Simple` وقواعد التحويل السبع (`7 Rewrite Formulas`)** | [فتح](skills/second-year-english/chapters/ch08-unit4-secA-the-power-of-choice.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-english/chapters/ch08-unit4-secA-the-power-of-choice.md) |
| `ch09` | **Unit 4 (Sec B & C):** *Online Consumption & Skills* | الدروس `4.3` و`4.4` (`Black Friday`) + القواعد: **`Present Perfect Continuous` مقابل البسيط والماضي** + **`Fronting & Opinion Article`** | [فتح](skills/second-year-english/chapters/ch09-unit4-secB-and-skills.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-english/chapters/ch09-unit4-secB-and-skills.md) |
| `ch10` | **Unit 5 (Sec A):** *The Greenhouse Effect (Part 1)* | الدروس `5.1` و`5.2` (مجمع بنبان والهيدروجين الأخضر) + القواعد: **`Cause and Effect Connectors` & `Modal Verbs`** | [فتح](skills/second-year-english/chapters/ch10-unit5-secA-the-greenhouse-effect.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-english/chapters/ch10-unit5-secA-the-greenhouse-effect.md) |
| `ch11` | **Unit 5 (Sec B & C):** *Egypt's Green Change Makers* | الدروس `5.3` (اتحضر للأخضر) و`5.4` + القواعد: **`Adverbials of Degree, Frequency & Stance`** + **`Argumentative Paragraph & Leaflet`** | [فتح](skills/second-year-english/chapters/ch11-unit5-secB-and-skills.md) | [`Raw`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-english/chapters/ch11-unit5-secB-and-skills.md) |

---

## 🛠️ طرق الاستخدام والربط مع جميع منصات الذكاء الاصطناعي

### الطريقة الأولى: عبر المحادثة المباشرة (ChatGPT / Gemini / Grok / Perplexity / Claude)
- انسخ **برومبت التشغيل السريع** من أعلى هذه الصفحة (أو من صفحة المادة المطلوبة) والصقه مباشرةً في المحادثة؛ سيقوم الذكاء الاصطناعي بقراءة الفهرس عبر رابط `raw.githubusercontent.com` وفتح ملف الدرس المطلوب عند سؤالك.

### الطريقة الثانية: عبر رفع الملفات (Claude Projects / ChatGPT Projects / Google NotebookLM / DeepSeek)
- إذا كنت تستخدم منصة تفضّل رفع الملفات مباشرةً، ادخل إلى مجلد المادة المطلوبة (`skills/second-year-physics/` أو `skills/second-year-history/` أو `skills/second-year-english/`)، وحمّل ملفاتها (`SKILL.md`, `glossary.md`, `patterns.md`, `cheatsheet.md`, وملفات `chapters/`) وارفعها داخل مشروعك مع البرومبت.

### الطريقة الثالثة: عبر سطر الأوامر وأدوات البرمجة الذكية (Claude Code / Cursor / Windsurf / Copilot)
بفضل وجود ملفَي `AGENTS.md` و`CLAUDE.md` في جذر المستودع، يتحول أي محرر ذكي يفتح هذا المشروع تلقائيًا إلى معلم خصوصي لمنهج البكالوريا المصرية:

```bash
git clone https://github.com/revolover00/Bakloriya-AI-SKILLS.git
cd Bakloriya-AI-SKILLS
```

أو لتثبيت مهارة مادة محددة مباشرةً عبر `npx skills`:

```bash
npx skills add https://github.com/revolover00/Bakloriya-AI-SKILLS --skill second-year-physics
npx skills add https://github.com/revolover00/Bakloriya-AI-SKILLS --skill second-year-history
npx skills add https://github.com/revolover00/Bakloriya-AI-SKILLS --skill second-year-english
```
