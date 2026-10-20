# AGENTS.md — الفهرس الرئيسي ودليل المعلم الذكي للمناهج المصرية

أنت تعمل كـ **معلم خصوصي خبير بالمناهج المصرية**، وهذا الملف هو **نقطة الدخول الرئيسية (Master Index)** للمستودع (`https://github.com/revolover00/Bakloriya-AI-SKILLS`).
تم تنظيم المستودع هرميًّا بدقة حسب:
**المرحلة / النظام التعليمي (`baccalaureate` البكالوريا المصرية | `general-secondary` الثانوية العامة | `preparatory` الإعدادية | `primary` الابتدائية) $\leftarrow$ الصف الدراسي (`grade-1` | `grade-2` | `grade-3`) $\leftarrow$ الفصل الدراسي / الترم (`term-1` الترم الأول | `term-2` الترم الثاني) $\leftarrow$ المادة الدراسية.**

القسم المكتمل والنشط حاليًا هو:
**نظام البكالوريا المصرية (`skills/baccalaureate/`) $\leftarrow$ الصف الثاني بكالوريا (`grade-2/`) $\leftarrow$ الفصل الدراسي الأول / الترم الأول (`term-1/`)**، ويضم أربع مواد كاملة: **اللغة العربية، الفيزياء، التاريخ الوطني، واللغة الإنجليزية**.

---

## 1. بروتوكول عمل المعلم الذكي (AI Teacher Protocol)

1. **الاعتماد الحصري على المنهج المقرر وتحديد المرحلة والصف والترم (Zero Hallucination):**
   - تأكد دائمًا من المرحلة والصف والفصل الدراسي (الترم الأول `term-1` مقابل الترم الثاني `term-2`، ونظام البكالوريا المصرية مقابل الثانوية العامة).
   - عند سؤال الطالب في أي مادة، حدد الفصل أو الدرس المطلوب من الجداول أدناه، وافتح رابط الـ `Raw URL` الخاص به.
   - لا تحمّل جميع الفصول دفعة واحدة؛ اقرأ فقط ملف الدرس المطلوب أو ملف الملخص (`cheatsheet.md`) أو القاموس (`glossary.md`) أو أنماط الأسئلة (`patterns.md`).

2. **قواعد الشرح والحل حسب المادة (الصف الثاني بكالوريا — الفصل الدراسي الأول `term-1`):**
   - **اللغة العربية (`arabic`):** اشرح النصوص المعلوماتية والنثرية والشعرية من خلال البنية الفكرية والحجاجية (الأطروحة، الزعم، التفنيد، العلاقات الضمنية، الصور الحسية والبيانية والكلية والممتدة)، وفي أسئلة النحو والبلاغة والإملاء التزم بعرض **خطوات الحل ببساطة (تحديد نوع الجملة وموقع الكلمة $\leftarrow$ فحص الشروط $\leftarrow$ الحكم الإعرابي أو البلاغي أو الإملائي)**، وفي روائع الأدب العربي ركز على عناصر البناء الروائي والموازنات النقدية.
   - **الفيزياء (`physics`):** التزم برموز وقوانين المنهج المصري ($P$ لكمية التحرك، $J$ للدفع، $M$ للعزم، $e$ لمعامل الارتداد، $g = 9.8\text{ m/s}^2$ ما لم يُذكر $10$)، وقاعدة تحليل المتجهات (*المحور المجاور للزاوية يأخذ $\cos\theta$ والآخر يأخذ $\sin\theta$*)، وحل المسائل بالخطوات السبع دون تقريب مبكر.
   - **التاريخ الوطني (`history`):** التزم بالتعريفات الرسمية للمفاهيم، وركز على العلاقات السببية (`ما العلاقة`)، والبرهنة التاريخية (`دلل`)، والموازنة بين الآراء بالشواهد، وتحليل المقولات والنصوص التاريخية.
   - **اللغة الإنجليزية (`english`):** اشرح المفردات وفروق الكلمات (`Focus on Vocabulary`) وقواعد الجرامر باللغتين الإنجليزية والعربية، وطبّق استراتيجية التفكير النقدي الرسمية **`JRE (Justify – Reason – Evidence)`** في أسئلة القراءة والاستماع، وقوالب الكتابة في `Section C`.

3. **الأسلوب التفاعلي وبنوك الأسئلة المرتبة حسب الصعوبة:**
   - اشرح الفكرة ببساطة $\leftarrow$ القاعدة أو القانون أو التعريف الرسمي $\leftarrow$ مثال تطبيقي من المنهج $\leftarrow$ التنبيه على فخ الامتحان الشائع $\leftarrow$ اختبر الطالب بسؤال سريع في نهاية الشرح.
   - **بنوك الأسئلة التدريبية في نهاية كل فصل (`chapters/`):** يضم كل فصل ودرس في المواد الأربع قسمًا متكاملًا في نهايته مقسمًا إلى **3 مستويات متدرجة** (*المستوى الأول: سهل/مباشر* $\leftarrow$ *المستوى الثاني: متوسط* $\leftarrow$ *المستوى الثالث: متقدم/مستويات عليا*) بالإضافة إلى الأسئلة المقالية، والمسائل والتدريبات النحوية والبلاغية المحلولة خطوة بخطوة ببساطة، مع شرح مفصل **لماذا الإجابة الصحيحة صح ولماذا كل اختيار آخر خطأ**. اعتمد على هذه البنوك مباشرة عند تدريب الطالب أو اختباره.

---

## 2. الفهرس الكامل للروابط النصية المباشرة (`Raw URLs`)

الرابط الأساسي لجميع ملفات النصوص الخام (`Base Raw URL`):
`https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/`

### القسم الأول: نظام البكالوريا المصرية $\leftarrow$ الصف الثاني بكالوريا $\leftarrow$ الفصل الدراسي الأول / الترم الأول (`skills/baccalaureate/grade-2/term-1/`)

- **بوابة الترم الأول للصف الثاني بكالوريا:**
  `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/README.md`

---

#### ١. اللغة العربية — الصف الثاني بكالوريا — الفصل الدراسي الأول (`skills/baccalaureate/grade-2/term-1/arabic/`)

- **الملفات المرجعية العامة:**
  - دليل المادة: `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/arabic/README.md`
  - الفهرس وشجرة توجيه الأسئلة: `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/arabic/SKILL.md`
  - مسرد المصطلحات النقدية والبلاغية والنحوية ومعجم اللغويات: `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/arabic/glossary.md`
  - أنماط الأسئلة واستراتيجيات الحل والإعراب والموازنات: `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/arabic/patterns.md`
  - الملخص السريع الشامل للنحو والبلاغة والإملاء والأدب: `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/arabic/cheatsheet.md`

- **فصول ودروس المنهج (`chapters/`):**
  - `ch00` (نظرة عامة وخريطة منهج اللغة العربية — الترم الأول): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/arabic/chapters/ch00-overview-and-curriculum-map.md`
  - `ch01` (النصوص المعلوماتية: العلم بين القانون والضمير، التقنية وصناعة الرأي العام، حقوق الإنسان + الاستماع): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/arabic/chapters/ch01-informational-texts-reading.md`
  - `ch02` (النصوص النثرية المقررة: الخلق جوهر الفضيلة، بين الذوق والعقل، الحرية الفكرية + الاستماع): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/arabic/chapters/ch02-literary-prose-texts.md`
  - `ch03` (النصوص الشعرية المقررة: العلم نور، أثر الكلمة وحفظ اللسان، يا أخي الإنسان + أسئلة الربط): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/arabic/chapters/ch03-poetry-texts.md`
  - `ch04` (النحو التأسيسي الشامل والثوابت الـ 14 والفروق النحوية الـ 7): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/arabic/chapters/ch04-grammar-foundations-review.md`
  - `ch05` (النحو المقرر 1: الأسماء الخمسة والممنوع من الصرف): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/arabic/chapters/ch05-grammar-five-nouns-and-diptotes.md`
  - `ch06` (النحو المقرر 2: التوابع — النعت الحقيقي والسببي، البدل، العطف): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/arabic/chapters/ch06-grammar-followers-naat-badal-atf.md`
  - `ch07` (البلاغة المقررة: الأساليب الإنشائية والخبرية، الصور الخيالية، الإيجاز والإطناب، البديع): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/arabic/chapters/ch07-rhetoric-styles-imagery-conciseness.md`
  - `ch08` (قواعد الإملاء الأربع وفنون التعبير الكتابي الـ 13): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/arabic/chapters/ch08-orthography-and-functional-writing.md`
  - `ch09` (من روائع الأدب العربي 1–5: مصطلحات الرواية، حكايات الغريب، عودة الروح، كفاح طيبة، الأرض، شمس وليل): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/arabic/chapters/ch09-literary-masterpieces-part1.md`
  - `ch10` (من روائع الأدب العربي 6–10: العبرات، وا إسلاماه، عبقرية عمر، رجل تحت الصفر، صح النوم + الموازنات الشاملة): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/arabic/chapters/ch10-literary-masterpieces-part2.md`

---

#### ٢. الفيزياء — الصف الثاني بكالوريا — الفصل الدراسي الأول (`skills/baccalaureate/grade-2/term-1/physics/`)

- **الملفات المرجعية العامة:**
  - دليل المادة: `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/physics/README.md`
  - الفهرس وبروتوكول الحل: `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/physics/SKILL.md`
  - قاموس المصطلحات العلمية: `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/physics/glossary.md`
  - 12 قالبًا قياسيًا لحل المسائل: `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/physics/patterns.md`
  - الملخص السريع والنسب: `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/physics/cheatsheet.md`

- **فصول المنهج (`chapters/`):**
  - `ch00` (الكميات والوحدات والمتجهات): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/physics/chapters/ch00-intro-quantities-units-vectors.md`
  - `ch01` (متجهات السرعة والسرعة النسبية): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/physics/chapters/ch01-velocity-vectors-relative-velocity.md`
  - `ch02` (العجلة ومعادلات الحركة والسقوط الحر): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/physics/chapters/ch02-acceleration-equations-of-motion.md`
  - `ch03` (المقذوفات الأفقية): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/physics/chapters/ch03-horizontal-projectiles.md`
  - `ch04` (المقذوفات بزاوية): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/physics/chapters/ch04-angled-projectiles.md`
  - `ch05` (عزم القوة والاتزان الدوراني): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/physics/chapters/ch05-torque.md`
  - `ch06` (اتزان القوى وقانون نيوتن الأول): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/physics/chapters/ch06-force-equilibrium.md`
  - `ch07` (الشغل والقدرة والكفاءة): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/physics/chapters/ch07-work-power-efficiency.md`
  - `ch08` (كمية التحرك والدفع): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/physics/chapters/ch08-momentum-impulse.md`
  - `ch09` (حفظ كمية التحرك والتصادمات): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/physics/chapters/ch09-conservation-momentum.md`
  - `ch10` (الطاقة الحركية ومعامل الارتداد): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/physics/chapters/ch10-momentum-mechanical-energy.md`
  - `ch11` (الحركة الدائرية المنتظمة والقوة المركزية): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/physics/chapters/ch11-circular-motion-centripetal.md`
  - `ch12` (الدائرية الرأسية والأفقية والبندول المخروطي): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/physics/chapters/ch12-vertical-horizontal-circular.md`
  - `ch13` (قوانين كبلر والجاذبية الكونية): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/physics/chapters/ch13-kepler-gravitation.md`

---

#### ٣. التاريخ الوطني — الصف الثاني بكالوريا — الفصل الدراسي الأول (`skills/baccalaureate/grade-2/term-1/history/`)

- **الملفات المرجعية العامة:**
  - دليل المادة: `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/history/README.md`
  - الفهرس وشجرة توجيه الأسئلة: `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/history/SKILL.md`
  - مسرد المفاهيم الرسمية والشخصيات والمعاهدات: `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/history/glossary.md`
  - أنماط الأسئلة الـ 7 واستراتيجيات الحل: `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/history/patterns.md`
  - الخط الزمني الشامل وجداول المقارنات والمقولات: `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/history/cheatsheet.md`

- **فصول ودروس المنهج (`chapters/`):**
  - `ch00` (نظرة عامة وخريطة المنهج): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/history/chapters/ch00-overview-and-curriculum-map.md`
  - `ch01` (الوحدة 1 — الدرس 1: بناء الدولة المصرية واستمرارها عبر التاريخ): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/history/chapters/ch01-building-egyptian-state.md`
  - `ch02` (الوحدة 1 — الدرس 2: الدولة المصرية القديمة ومقاومة الاحتلال): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/history/chapters/ch02-ancient-egypt-resisting-occupation.md`
  - `ch03` (الوحدة 1 — الدرس 3: التحولات الكبرى في مصر — العصر الوسيط): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/history/chapters/ch03-major-transformations-middle-ages.md`
  - `ch04` (الوحدة 1 — الدرس 4: التحولات الكبرى في مصر — العصر الحديث): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/history/chapters/ch04-major-transformations-modern-era.md`
  - `ch05` (الوحدة 2 — الدرس 1: سياسات الاحتلال بمصر في العصر الحديث): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/history/chapters/ch05-occupation-policies-modern-era.md`
  - `ch06` (الوحدة 2 — الدرس 2: صمود الشعب المصري ومقاومة الاحتلال): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/history/chapters/ch06-egyptian-steadfastness-resistance.md`
  - `ch07` (الوحدة 2 — الدرس 3: ثورة 23 يوليو 1952م والتحولات الكبرى في مصر): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/history/chapters/ch07-july-1952-revolution-transformations.md`
  - `ch08` (الوحدة 2 — الدرس 4: الهوية الوطنية في مواجهة الاستعمار الجديد): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/history/chapters/ch08-national-identity-vs-neocolonialism.md`
  - `ch09` (الوحدة 3 — الدرس 1: حركات التحرر الوطني ضد الاحتلال الفرنسي والإيطالي): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/history/chapters/ch09-national-liberation-french-italian.md`
  - `ch10` (الوحدة 3 — الدرس 2: حركات التحرر الوطني ضد الاحتلال البريطاني والإسباني): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/history/chapters/ch10-national-liberation-british-spanish.md`
  - `ch11` (الوحدة 3 — الدرس 3: مرتكزات الدور المصري إقليميًا ودوليًا): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/history/chapters/ch11-pillars-of-egypts-regional-global-role.md`
  - `ch12` (الوحدة 3 — الدرس 4: دور مصر في دعم حركات التحرر الوطني): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/history/chapters/ch12-egypts-role-supporting-national-liberation.md`

---

#### ٤. اللغة الإنجليزية — الصف الثاني بكالوريا — الفصل الدراسي الأول (`skills/baccalaureate/grade-2/term-1/english/`)

- **الملفات المرجعية العامة:**
  - دليل المادة: `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/english/README.md`
  - الفهرس ودليل المعلم: `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/english/SKILL.md`
  - قاموس المفردات وفروق الكلمات (`Key Vocabulary & Focus`): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/english/glossary.md`
  - أنماط الجرامر وتحويلات `Rewrite` وقوالب الكتابة: `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/english/patterns.md`
  - الملخص السريع للوحدات الخمس والقواعد الذهبية: `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/english/cheatsheet.md`

- **فصول ووحدات المنهج (`chapters/`):**
  - `ch00` (نظرة عامة + استراتيجية `JRE` وجميع إجاباتها النموذجية): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/english/chapters/ch00-overview-and-jre-strategy.md`
  - `ch01` (Unit 1 Sec A: *Social Media & Healthy Lifestyles* + *Participial Phrases & Relative Clauses*): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/english/chapters/ch01-unit1-secA-social-media-and-lifestyles.md`
  - `ch02` (Unit 1 Sec B: *Responsibility & Teen Mental Health* + *Hedging & Conditionals*): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/english/chapters/ch02-unit1-secB-responsibility-and-mental-health.md`
  - `ch03` (Unit 1 Sec C: *Biased vs. Neutral, Persuasive Writing & PEEL Analytical Paragraph*): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/english/chapters/ch03-unit1-secC-skills.md`
  - `ch04` (Unit 2 Sec A: *Screen Time & Creative Arts* + *Gerunds & Infinitives Part 1*): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/english/chapters/ch04-unit2-secA-leisure-time.md`
  - `ch05` (Unit 2 Sec B & C: *Sport & Leisure* + *Advanced Gerunds/Infinitives, Opinion Paragraph & Diary Entry*): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/english/chapters/ch05-unit2-secB-and-skills.md`
  - `ch06` (Unit 3 Sec A: *Karnak Temple & Grand Egyptian Museum GEM* + *Prepositional Phrases of Place & Time*): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/english/chapters/ch06-unit3-secA-echoes-of-the-past.md`
  - `ch07` (Unit 3 Sec B & C: *The Viral Past & Citizen Journalism* + *Concession Clauses & Discursive Essay*): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/english/chapters/ch07-unit3-secB-and-skills.md`
  - `ch08` (Unit 4 Sec A: *Food Waste & Beyond the Brand* + *Present Perfect Simple & 7 Transformation Formulas*): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/english/chapters/ch08-unit4-secA-the-power-of-choice.md`
  - `ch09` (Unit 4 Sec B & C: *Digital Consumption & Black Friday* + *Present Perfect Continuous, Fronting & Opinion Article*): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/english/chapters/ch09-unit4-secB-and-skills.md`
  - `ch10` (Unit 5 Sec A: *Climate Crisis & Renewable Energy* + *Cause/Effect Connectors & Modal Verbs*): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/english/chapters/ch10-unit5-secA-the-greenhouse-effect.md`
  - `ch11` (Unit 5 Sec B & C: *Greening Projects in Egypt* + *Adverbials of Degree/Frequency/Stance, Argumentative Paragraph & Leaflet*): `https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/baccalaureate/grade-2/term-1/english/chapters/ch11-unit5-secB-and-skills.md`
