### 0) فحص المدخل
- نوع المدخل: إعلان وظيفي واحد (Junior Network Support Engineer).
- التحذيرات: لا يوجد.

### 1) المتطلبات والمطابقة

| # | المتطلب (مختصر) | أساسي/مفضّل | الحالة | الدليل |
|---|---|---|---|---|
| 1 | بكالوريوس في هندسة الحاسب أو علوم الحاسب أو مجال مرتبط | أساسي | مطابق | F01 |
| 2 | فهم متين لأساسيات الشبكات (TCP/IP، التوجيه، التبديل، VLANs) | أساسي | جزئي: الأساسيات موجودة، وTCP/IP والتوجيه والتبديل وVLANs غير مذكورة في الملف | F10، N08 |
| 3 | تركيب وإعداد أجهزة الشبكة (الخبرة الأكاديمية أو المخبرية مقبولة) | أساسي | جزئي: التركيب والتجهيز العملي وبناء شبكة في المحاكي موجودان، وإعداد أجهزة محددة غير موثّق | F10، F11 |
| 4 | مهارات أساسية في سطر أوامر Linux | أساسي | جزئي: Linux basics فقط، ولا يوجد ذكر لسطر الأوامر | F13 |
| 5 | استكشاف مشاكل الاتصال وإصلاحها وتوثيق الحلول | أساسي | جزئي: تشخيص وإصلاح أعطال في مشروع الواقع المعزز وحل المشكلات، أما أعطال الاتصال والتوثيق فغير موجودة | F09، F14 |
| 6 | برمجة نصية أساسية بـ Python | مفضّل | مطابق (على مستوى basics) | F12، F02 |
| 7 | شهادة CCNA | مفضّل | غير متوفر | N04 |
| 8 | مهارات العمل الجماعي والتواصل | أساسي | مطابق | F14 |

### 2) المسودة المخصّصة (English — ready to copy)
```
PROFESSIONAL SUMMARY
Computer Engineering graduate (B.Sc., 2026) with networking fundamentals and a complete enterprise network designed and built in a simulator. [F01, F10] Self-taught in hands-on network setup and installation, with Linux basics and Python basics. [F11, F13, F12]

SKILLS
Networking fundamentals [F10]; network simulator: enterprise network design and build [F10]; hands-on network setup and installation, self-taught [F11]; Linux basics [F13]; Python basics [F12, F02]; troubleshooting and problem solving [F09, F14]
Teamwork [F14]; communication [F14]; SQL basics [F12, F02]; C++ [F12]; Networking course (Satr platform) and Network Security 101 course [F02]

PROJECTS & EXPERIENCE BULLETS
- Designed and built a complete enterprise network in a network simulator. [F10]
- Performed hands-on network setup and installation through self-study. [F11]
- Diagnosed and fixed tracking and display issues in a Unity 6 and Vuforia AR application, where both models appeared at once and the display disappeared after changing the image target. [F08, F09]
- Built an IoT early-warning system that monitors gas leaks, smoke and high temperature, with three alert states and threshold hysteresis to prevent rapid state flipping. [F05, F07]
- Programmed the early-warning system in C++ (Arduino) using Adafruit libraries, with an ESP8266 Wi-Fi module for phone notification over the internet. [F05, F06, F07]
- Completed courses in Networking (Satr platform), Python 101, SQL 101 and Network Security 101. [F02]
```

### 3) الفجوات (لا تُكتب في السيرة)
- TCP/IP والتوجيه والتبديل وVLANs · السبب: N08 (غير مكتوبة في F10/F11) · اقتراح: ارجع إلى مشروع الشبكة في المحاكي وانظر هل استخدمتها فعلًا. إن كان نعم فأضفها إلى ملف الحقائق بصياغتك، وإن كان لا فاذكرها في المقابلة كخطة تعلم قريبة ونفّذ مختبرًا عمليًا عليها في المحاكي.
- إعداد أجهزة شبكة محددة (Configuring) · السبب: غير موجود في الملف (الموثّق تركيب وتجهيز وبناء شبكة في المحاكي فقط) · اقتراح: وثّق في الملف أي أجهزة أو أوامر إعداد نفّذتها في المحاكي أو عمليًا، وإلا فاعتمد في المقابلة على ما هو موثّق فقط.
- سطر أوامر Linux · السبب: الملف يقول Linux basics فقط (F13) · اقتراح: تدرّب على أوامر الشبكة الأساسية في Linux (مثل ping وip وtraceroute) حتى تستطيع الحديث عنها بثقة، ولا تُضاف إلى السيرة قبل توثيقها في الملف.
- استكشاف مشاكل الاتصال وتوثيق الحلول · السبب: غير موجود في الملف (F09 عن مشاكل تطبيق وليس اتصالًا) · اقتراح: ذكر F09 في المقابلة كمثال على منهجية التشخيص، وبناء ملف توثيق صغير لحالات عطل شبكي في المحاكي.
- شهادة CCNA (مفضّلة) · السبب: N04 (لا توجد شهادات منجزة) · اقتراح: ذكرها في المقابلة كخطة تعلم إن كنت تنوي الدراسة لها فعلًا، ولا تُكتب في السيرة حتى تُنجز.

### 4) قرار يعود لراكان
- الملاءمة: 6 من 6 متطلبات أساسية (مطابقة أو جزئية؛ منها 2 مطابقة و4 جزئية) ← جيدة، مع ملاحظة أن الجزئية تحمل نقصًا في الجانب الشبكي العملي الذي هو محور الوظيفة.
- أسئلة لراكان (قد تكون صحيحة لكنها ليست في الملف):
  - هل شملت شبكة المحاكي عناوين IP وتوجيهًا وتبديلًا وVLANs؟ وما الأجهزة التي أعددتها؟
  - هل كتبت توثيقًا أو تقريرًا لشبكة المحاكي أو لإصلاح الأعطال؟
  - مهام تدريب MEWA (F04) غير موثّقة بعد. إن كان فيها عمل دعم فني أو شبكات، فاكتبها في الملف لأنها ستقوّي الطلب كثيرًا.

### 5) الفحص الذاتي
- كل سطر في القسم 2 يحمل رقم حقيقة F: نعم
- لا رقم N ولا شيء من قائمة «ما لا أدّعيه» في القسم 2: نعم
- كلمات الملخص: 35
- عدد النقاط: 6
- لا مدينة ولا مستوى إنجليزية ولا بيانات تواصل: نعم
