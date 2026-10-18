# 🎓 المعلم الذكي لمناهج البكالوريا المصرية

قاعدة معرفة مهيكلة تحوّل الكتب المدرسية والمرجعية الرسمية لنظام **البكالوريا المصرية (الصف الثاني بكالوريا — دفعة 2027)** إلى ملفات نصية قياسية (`Raw Markdown`)، مما يتيح لأي ذكاء اصطناعي العمل فورًا كـ **معلم خصوصي خبير بالمنهج المصري** يشرح الدروس ويحل المسائل والأسئلة بدقة الكتاب المدرسي دون تأليف.

---

## ⚡ برومبت التشغيل السريع (انسخه والصقه في أي AI)

لأن نماذج الذكاء الاصطناعي لا تستطيع تصفح واجهة GitHub العادية، يستخدم هذا البرومبت المختصر **الرابط النصي المباشر (`Raw URL`)** الذي يمكّن أي AI يدعم تصفح الويب (مثل ChatGPT وGemini وGrok وPerplexity وClaude) من قراءة فهرس الدروس والوصول لأي فصل مباشرةً:

```text
أنت معلمي الخصوصي للصف الثاني بكالوريا (٢ ثانوي - المنهج المصري 2027).
اقرأ أولًا فهرس المناهج وروابط الفصول النصية المباشرة (Raw URLs) من هذا الرابط:
https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/AGENTS.md

عندما أسألك في أي مادة (الفيزياء / التاريخ الوطني / اللغة الإنجليزية)، افتح رابط الـ Raw الخاص بالدرس المطلوب من داخل الفهرس، والتزم حرفيًا بشرح وقوانين وتعريفات الكتاب المدرسي بدون تأليف، واختبرني بسؤال تطبيقي في نهاية الشرح.
رحّب بي الآن واسألني: أي مادة وأي درس نبدأ به؟
```

> **ملاحظة:** إذا كنت تستخدم نموذجًا لا يتصفح الروابط الخارجية، حمّل ملفات المادة المطلوبة من الجداول أدناه وارفعها في المحادثة أو داخل **Claude Projects / ChatGPT Projects / Google NotebookLM** مع نفس البرومبت.

---

## 📚 المواد الدراسية المتاحة (الصف الثاني بكالوريا — 2027)

| المادة الدراسية | المصدر المعتمد | المحتوى المهيكل | تصفح المجلد | رابط الفهرس المباشر للـ AI (`Raw`) |
|---|---|---|---|---|
| **الفيزياء** | الكتاب المدرسي الرسمي (269 صفحة) | 14 فصلًا (`ch00`–`ch13`) + القاموس + 12 قالب مسائل + الملخص | [`skills/second-year-physics/`](skills/second-year-physics/) | [`SKILL.md (Raw)`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-physics/SKILL.md) |
| **التاريخ الوطني** *(الترم الأول)* | كتاب الامتحان 2027 (454 صفحة) | 3 وحدات / 12 درسًا (`ch00`–`ch12`) + المفاهيم + أنماط الأسئلة + الخط الزمني | [`skills/second-year-history/`](skills/second-year-history/) | [`SKILL.md (Raw)`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-history/SKILL.md) |
| **اللغة الإنجليزية** *(الترم الأول)* | كتاب الأضواء جيم 2027 (426 صفحة) | 5 وحدات / 20 درسًا (`ch00`–`ch11`) + إجابات `JRE` + القاموس + الجرامر والمهارات | [`skills/second-year-english/`](skills/second-year-english/) | [`SKILL.md (Raw)`](https://raw.githubusercontent.com/revolover00/Bakloriya-AI-SKILLS/main/skills/second-year-english/SKILL.md) |

---

## 🗂️ ملخص محتوى المناهج

### 1. اللغة الإنجليزية (`skills/second-year-english/`)
يغطي الوحدات الخمس (`Units 1–5`) بواقع 20 درسًا و10 موضوعات جرامر ومهارات الكتابة واستراتيجية التفكير النقدي **`JRE (Justify – Reason – Evidence)`**:
- **Unit 1 (*Well-being*):** وسائل التواصل والصحة النفسية (`16328` و`PFA`) | القواعد: `Participial Phrases`, `Relative Clauses`, `Hedging & Conditionals` | المهارات: `PEEL Analytical Paragraph`.
- **Unit 2 (*Leisure Time*):** وقت الشاشات والفنون والرياضة | القواعد: `Gerunds & Infinitives` وأفعال تغير المعنى (`remember, forget, regret, stop, try, go on, mean, need`) | المهارات: `Opinion Paragraph & Diary Entry`.
- **Unit 3 (*Echoes of the Past*):** معبد الكرنك، المتحف المصري الكبير (`GEM`)، الخوارزميات والتوثيق التاريخي | القواعد: `Prepositional Phrases of Place & Time`, `Concession Clauses` | المهارات: `Discursive Essay`.
- **Unit 4 (*The Power of Choice*):** هدر الطعام، العلامات التجارية، الاستهلاك الرقمي، وتخفيضات `Black Friday` | القواعد: `Present Perfect Simple & Continuous` وقواعد الـ `Rewrite` السبع | المهارات: `Fronting & Opinion Article`.
- **Unit 5 (*The Greenhouse Effect*):** أزمة المناخ، الطاقة المتجددة (مجمع بنبان والهيدروجين الأخضر)، ومبادرة «اتحضر للأخضر» | القواعد: `Cause & Effect Connectors`, `Modal Verbs`, `Adverbials` | المهارات: `Argumentative Paragraph & Leaflet`.

### 2. التاريخ الوطني (`skills/second-year-history/`)
يغطي الوحدات الثلاث المقررة في الفصل الدراسي الأول:
- **الوحدة الأولى (*مصر بين الماضي والحاضر*):** بناء الدولة المصرية القديمة (الملك مينا، ماعت، وصايا بتاح حتب)، مقاومة الهكسوس ومعركتا مجدو وقادش وأول معاهدة سلام، التحولات الكبرى في العصر الوسيط (مصر الرومانية، عصر الشهداء والرهبنة، الفتح الإسلامي، الدول المستقلة، حطين، عين جالوت، العثمانيون)، والتحولات في العصر الحديث (الحملة الفرنسية، محمد علي والاحتكار، إسماعيل والديون، الطبقات، التيارات الفكرية).
- **الوحدة الثانية (*تحولات القوة وبناء الوعي*):** سياسات الاحتلالين الفرنسي والبريطاني، المراحل السبع لتطور الوعي القومي (وثيقة 1795م، الطهطاوي، الأفغاني، محمد عبده، الثورة العرابية، مصطفى كامل، محمد فريد، سعد زغلول وثورة 1919م، ودور المرأة)، ثورة 23 يوليو 1952م وإنجازاتها، ومواجهة الاستعمار الجديد وحروب الجيل الرابع.
- **الوحدة الثالثة (*مصر وقضايا التحرر الوطني*):** حركات التحرر العربي ضد الاستعمار الفرنسي والإيطالي والبريطاني والإسباني، مرتكزات الدور المصري («ملتقى الدوائر الثلاث» لجمال حمدان، قناة السويس، عدم الانحياز، القوة الناعمة)، ودعم مصر لثورات الجزائر واليمن والعراق وجنوب إفريقيا.

### 3. الفيزياء (`skills/second-year-physics/`)
يغطي 14 فصلًا متكاملًا (`ch00` إلى `ch13`):
- **الميكانيكا والحركة:** الكميات والمتجهات (`ch00`)، السرعة النسبية وعبور النهر (`ch01`)، العجلة ومعادلات الحركة والسقوط الحر (`ch02`)، المقذوفات الأفقية وبزاوية (`ch03`–`ch04`).
- **الاستاتيكا والديناميكا والطاقة:** عزم القوة والروافع (`ch05`)، اتزان القوى وقانون نيوتن الأول (`ch06`)، الشغل والقدرة والكفاءة ومخطط سانكي (`ch07`)، كمية التحرك والدفع والتصادمات ومعامل الارتداد (`ch08`–`ch10`).
- **الحركة الدائرية والجاذبية:** الحركة الدائرية المنتظمة والقوة المركزية (`ch11`)، الدائرية الرأسية والأفقية والبندول المخروطي (`ch12`)، وقوانين كبلر والجاذبية الكونية والأقمار الصناعية (`ch13`).

---

## 🛠️ التشغيل للمطورين وأدوات سطر الأوامر

يدعم المستودع التشغيل التلقائي مع وكلاء الذكاء الاصطناعي البرمجية (Claude Code، Cursor، Windsurf، Copilot، Codex) عبر ملفَي `AGENTS.md` و`CLAUDE.md`:

```bash
git clone https://github.com/revolover00/Bakloriya-AI-SKILLS.git
cd Bakloriya-AI-SKILLS
```

أو عبر أداة `skills` مباشرةً:

```bash
npx skills add https://github.com/revolover00/Bakloriya-AI-SKILLS --skill second-year-physics
npx skills add https://github.com/revolover00/Bakloriya-AI-SKILLS --skill second-year-history
npx skills add https://github.com/revolover00/Bakloriya-AI-SKILLS --skill second-year-english
```

---

## 📐 هيكلة المستودع

```text
Bakloriya-AI-SKILLS/
├── README.md                        # الدليل الشامل وبرومبت التشغيل السريع
├── AGENTS.md                        # الفهرس الرئيسي وروابط Raw المباشرة لجميع الفصول
├── CLAUDE.md                        # نقطة الدخول التلقائية لـ Claude Code
└── skills/
    ├── second-year-physics/         # فيزياء ٢ بكالوريا (SKILL + glossary + patterns + cheatsheet + ch00..ch13)
    ├── second-year-history/         # تاريخ ٢ بكالوريا (SKILL + glossary + patterns + cheatsheet + ch00..ch12)
    └── second-year-english/         # إنجليزي ٢ بكالوريا (SKILL + glossary + patterns + cheatsheet + ch00..ch11)
```
