# المستوى 2 — ابنِ إضافتك الخاصة (مهاراتك في حزمة واحدة)

بعد أن تبني 2-3 مهارات خاصة بقالب «مهارتي الخاصة»، اجمعها في إضافة واحدة تثبّتها لك ولزملائك.

## الطريقة السهلة (داخل Cowork)
ثبّت إضافة **cowork-plugin-management** من Discover، ثم اكتب: «اجمع مهاراتي: ___ و___ في إضافة باسم ___ ووصف ___». ستُنشئ البنية والملفات.

## الطريقة اليدوية (5 دقائق)
```
my-plugin/
  .claude-plugin/plugin.json      ← {"name":"my-plugin","version":"1.0.0","description":"..."}
  skills/
    skill-one/SKILL.md
    skill-two/SKILL.md
```
ثم ضعها في سوق (marketplace) على GitHub كما في `claude-workshop-plugin/README.md`، أو شاركها ZIP.

## المعيار
إضافتك جاهزة حين يستطيع زميل تثبيتها بسطر واحد (owner/repo) ويشغّل مهارة منها بالاستدعاء الصريح.
