# مصروفاتي PWA

مدير فلوس أوفلاين كامل (RTL عربي مصري).

التثبيت الجديد يبدأ فاضي: فئات عامة وحساب «كاش» برصيد صفر. مفيش ديون أو حركات جاهزة. استيراد JSON من الإعدادات يرجّع نسخة احتياطية خاصة على الجهاز بس.

## Install
- Android Chrome: افتح اللينك مرة وأنت أونلاين → ⋮ → Install app / Add to Home screen
- iPhone Safari: Share → Add to Home Screen

## Features
Home, Accounts+transfers, Transactions, Debts (عليا/ليا), Budgets, Recurring, Reports (SVG), Goals, Settings (dark/PIN/JSON/CSV), انسخ لنوفا

أول فتح يسألك تضبط PIN من 4 أرقام، وتقدر تتخطاه.

## Privacy
الموقع مش للأرشفة: `noindex, nofollow` و`robots.txt` يمنع كل الزحف. البيانات بتفضل في المتصفح (localStorage) ومش متخزنة في المستودع.

## Offline
Service worker cache-first. localStorage key: `masrofaty_v1`
