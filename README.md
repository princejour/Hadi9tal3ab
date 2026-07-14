# Walhero Battle Lite — Unity Android Prototype

نسخة تجريبية أوفلاين للعبة Battle Royale خفيفة، مهيأة للتجربة على هواتف Android.

## الموجود حاليًا

- منظور شخص ثالث وكاميرا قابلة للدوران باللمس.
- حركة، جري، قفز وتصويب.
- 3 أسلحة: Rifle وSMG وShotgun.
- 12 عدوًا Bots بقتال وحركة ومراوغة.
- منطقة آمنة تتقلص تدريجيًا وتسبب ضررًا خارجها.
- ذخيرة وحقائب علاج موزعة على الخريطة.
- شاشة فوز وخسارة وإعادة اللعب.
- تحكم لمس Landscape مولّد بالكامل من الكود.

## ملف المشروع

حمّل `Walhero-Battle-Lite-Unity.zip` وفك الضغط عنه كمشروع Unity 6.

## بناء APK من GitHub Actions

الـWorkflow يفك المشروع تلقائيًا ويبنيه باستعمال Unity. يلزم إضافة أسرار Unity التالية إلى المستودع مرة واحدة:

- `UNITY_LICENSE`
- `UNITY_EMAIL`
- `UNITY_PASSWORD`

بعد نجاح البناء، يظهر APK داخل Artifacts باسم `Walhero-Battle-Lite-APK`.
