# حقيبة ورشة «يوم تجهيز Claude» — إضافة واحدة بتسع مهارات

## التثبيت في Claude.ai أو Cowork (يحتاج خطة Pro أو أعلى)
1. Customize > Plugins > **Add** > **Add marketplace** > **Add from a repository**.
2. اكتب: `msrr66/claude-workshop-plugin` (أو رابط المستودع كاملًا).
3. افتح تبويب **Discover**، اختر **claude-workshop**، واضغط **Add**.
4. فعّل الإضافة. المهارات التسع تصير جاهزة؛ استدعِ أي مهارة باسمها الصريح: «استخدم مهارة راجع النتيجة».

## التثبيت في Claude Code
```
claude plugin marketplace add msrr66/claude-workshop-plugin
claude plugin install claude-workshop@claude-workshop-marketplace
```

## المهارات (النداء بالعربي: «استخدم مهارة …»)
| النداء بالعربي | الاسم التقني | متى |
|---|---|---|
| صوتي السعودي | saudi-voice | يكلّمك بلهجة سعودية بسيطة (الفصحى للرسمي فقط) |
| وضّح أولًا | clarify-first | قبل أي طلب غامض أو متعدد الأجزاء |
| كاتب المراسلات | my-voice-correspondence | إيميل أو خطاب بصوتك |
| لخّص المستند | document-distiller | ملف طويل → جدول أرقام/مخاطر/قرارات/إجراءات |
| صانع الملفات | deliverable-maker | محتوى معتمد → Word/PowerPoint/Excel |
| راجع النتيجة | compare-to-brief | مراجعة مخرج مقابل الطلب مع إعادة حساب الأرقام |
| أغلق الجلسة | session-closer | إغلاق محادثة طويلة في موجز |
| وكيل | wakeel-lite | تفويض مهمة ملفات خطوة خطوة |
| استشارة | consult-lite | 3 زوايا + توصية قبل قرار |

## البديل بلا سوق
ارفع ملفات ZIP الثمانية دفعة واحدة من Customize > Skills > Add > Upload skill.

قاعدة الأمان: هذه المهارات نصوص تعليمات فقط؛ لا سكربتات، لا روابط خارجية، لا إرسال بيانات.
