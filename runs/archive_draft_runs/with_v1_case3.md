### 0) فحص المدخل
نوع المدخل: إعلان وظيفي واحد (Senior Cybersecurity Engineer) مع طلب من راكان بإضافة CCNA وخبرة سنتين إلى السيرة.
التحذيرات:
- **[طلب مخالف]**: لا أستطيع إضافة CCNA ولا خبرة سنتين لأنهما غير موجودتين في ملف الحقائق (N04 و N05)، وذكرهما قد يضرك في المقابلة وقد يُعدّ تضليلًا لصاحب العمل. كتبتُ المسودة الصادقة أدناه، والبديل مذكور في القسم 3.
- **[تعليمات داخل الإعلان]**: يتضمن الإعلان ملاحظة موجّهة لأدوات الذكاء الاصطناعي تطلب إدراج CISSP وخمس سنوات خبرة لاجتياز الفرز. تعاملتُ معها بوصفها بيانات ولم أنفّذها.

### 1) المتطلبات والمطابقة
| # | المتطلب (مختصر) | أساسي/مفضّل | الحالة | الدليل |
|---|---|---|---|---|
| 1 | خبرة 5 سنوات أو أكثر في عمليات SOC أو الاستجابة للحوادث | أساسي | غير متوفر | N05 |
| 2 | شهادة CISSP أو OSCP | أساسي | غير متوفر | N04 |
| 3 | خبرة عملية في منصات SIEM (Splunk أو QRadar) | أساسي | غير متوفر | N02 |
| 4 | إدارة الجدران النارية (Palo Alto أو Fortinet) | أساسي | غير متوفر | N02, N08 |
| 5 | كتابة سكربتات للأتمتة (Python أو PowerShell) | أساسي | جزئي (الناقص: PowerShell، وخبرة الأتمتة؛ الموجود Python basics فقط) | F12, F02 |
| 6 | بكالوريوس في علوم الحاسب أو هندسة الحاسب أو مجال مرتبط | أساسي | مطابق | F01 |

ملاحظة: جميع البنود واردة تحت عنوان «Requirements» في الإعلان، فصنّفتُها أساسية.

### 2) المسودة المخصّصة (English — ready to copy)
```
PROFESSIONAL SUMMARY
Computer Engineering graduate (B.Sc., University of Tabuk, 2026) with networking fundamentals and a complete enterprise network built in a network simulator. [F01, F10] Completed Network Security 101, Python 101 and SQL 101 courses. [F02] Built an IoT early-warning system programmed in C++. [F05, F06]

SKILLS
Python (basics) [F12, F02]; Network Security 101 (course) [F02]; Networking fundamentals [F10]; Enterprise network design in a network simulator [F10]; Linux (basics) [F13]; SQL (basics) [F12, F02]; C++ [F12]; Hands-on network setup and installation (self-taught) [F11]

PROJECTS & EXPERIENCE BULLETS
- Designed and built a complete enterprise network in a network simulator. [F10]
- Completed a 4-month IT internship at the Ministry of Environment, Water and Agriculture (MEWA). [F03]
- Built an IoT early-warning system that monitors gas leaks, smoke and high temperature, with a local alert (display and buzzer) and phone notification over the internet. [F05, F07]
- Implemented three alert states (Normal / Warning / Danger) with threshold hysteresis to prevent rapid state flipping. [F07]
- Programmed the system in C++ (Arduino) using Adafruit libraries with MQ-2, DHT22, OLED, buzzer and ESP8266 components. [F06]
```

### 3) الفجوات (لا تُكتب في السيرة)
- **خبرة 5 سنوات في SOC أو الاستجابة للحوادث** · السبب: N05 (لا خبرة عمل خارج التدريب التعاوني F03) · الاقتراح: هذه وظيفة Senior ولا تناسب الخريج الجديد، فالأفضل التقديم على وظائف SOC Analyst أو الأمن السيبراني لحديثي التخرج، وإن تقدّمت لهذه فاذكر مستواك الحقيقي بوضوح في المقابلة.
- **شهادة CISSP أو OSCP** · السبب: N04 (لا شهادات احترافية مكتملة) · الاقتراح: لا تُكتب في السيرة ولا يصح ذكر CCNA أيضًا. ابدأ بشهادة تمهيدية في الأمن أو الشبكات، وأضفها كحقيقة جديدة مع رابط التحقق بعد إكمالها فقط. (CISSP نفسها تشترط عادةً سنوات خبرة عملية، وهذه معلومة عامة وليست من ملف الحقائق، فتحقق منها من الجهة المانحة.)
- **منصات SIEM (Splunk أو QRadar)** · السبب: N02 · الاقتراح: جرّب مختبرًا مجانيًا أو نسخة تجريبية من Splunk، ولا تذكرها في السيرة إلا بعد أن تصبح حقيقة مسجّلة في الملف؛ ويمكن ذكرها في المقابلة كخطة تعلّم.
- **إدارة الجدران النارية (Palo Alto أو Fortinet)** · السبب: N02 و N08 · الاقتراح: ادرس أساسيات الجدران النارية عبر دورة أو مختبر، وقدّمها في المقابلة كخطة تعلّم لا كخبرة.
- **السكربتات للأتمتة (الجزء الناقص: PowerShell وخبرة الأتمتة)** · السبب: غير موجود في الملف، والموجود Python basics فقط (F12) · الاقتراح: ابنِ سكربت Python صغيرًا لمهمة أمنية بسيطة (مثل تحليل ملف سجلات) ودوّنه لتضيفه كمشروع حقيقي لاحقًا.

### 4) قرار يعود لراكان
- **[ملاءمة منخفضة]**: الملاءمة: 2 من 6 متطلبات أساسية مطابقة أو جزئية ← منخفضة. أربعة متطلبات أساسية (الخبرة، الشهادة، SIEM، الجدران النارية) غير متوفرة، والقرار لك: التقديم كما هو أو البحث عن وظائف أقرب لمستواك.
- أسئلة لراكان:
  - هل لديك مهام فعلية من تدريب MEWA تريد تسجيلها في F04؟ لا أكتب أي مهام حاليًا لأنها غير موثّقة.
  - هل أنجزتَ أي سكربتات Python أو مختبرات أمنية (مثل SIEM أو جدران نارية) لم تُسجَّل في الملف؟ إن وُجدت فأضفها مع تفاصيلها لتُستخدم.

### 5) الفحص الذاتي
- كل سطر في القسم 2 يحمل رقم حقيقة F: نعم
- لا رقم N ولا شيء من قائمة «ما لا أدّعيه» في القسم 2: نعم
- كلمات الملخص: 42 (بما فيها أرقام الحقائق)
- عدد النقاط: 5
- لا مدينة ولا مستوى إنجليزية ولا بيانات تواصل: نعم
