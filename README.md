# حقيبة ورشة «يوم تجهيز Claude» — إضافة واحدة بثماني مهارات

## التثبيت في Claude.ai أو Cowork (يحتاج خطة Pro أو أعلى)
1. Customize > Plugins > **Add** > **Add marketplace** > **Add from a repository**.
2. اكتب: `msrr66/claude-workshop-plugin` (أو رابط المستودع كاملًا).
3. افتح تبويب **Discover**، اختر **claude-workshop**، واضغط **Add**.
4. فعّل الإضافة. المهارات الثماني تصير جاهزة؛ استدعِ أي مهارة باسمها الصريح: «استخدم مهارة compare-to-brief».

## التثبيت في Claude Code
```
claude plugin marketplace add msrr66/claude-workshop-plugin
claude plugin install claude-workshop@claude-workshop-marketplace
```

## المهارات
| المهارة | متى |
|---|---|
| clarify-first | قبل أي طلب غامض أو متعدد الأجزاء |
| my-voice-correspondence | إيميل أو خطاب بصوتك (3 عينات) |
| document-distiller | ملف طويل → جدول أرقام/مخاطر/قرارات/إجراءات |
| deliverable-maker | محتوى معتمد → Word/PowerPoint/Excel |
| compare-to-brief | مراجعة مخرج مقابل الطلب مع إعادة حساب الأرقام |
| session-closer | إغلاق محادثة طويلة في موجز Project |
| wakeel-lite | تفويض مهمة ملفات محدودة خطوة خطوة |
| consult-lite | 3 زوايا محاكاة + توصية قبل قرار |

## البديل بلا سوق
ارفع ملفات ZIP الثمانية دفعة واحدة من Customize > Skills > Add > Upload skill.

قاعدة الأمان: هذه المهارات نصوص تعليمات فقط؛ لا سكربتات، لا روابط خارجية، لا إرسال بيانات.
