# ThamerLab Home Assistant

مجموعة مرتبة لملفات Home Assistant الخاصة بي.

هذا الريبو مخصص لحفظ ومشاركة:

- Blueprints
- Dashboard views
- Mushroom cards
- Packages
- Helpers templates
- Automations
- Scripts
- Notification flows

## Structure

```text
blueprints/
  automation/
    irrigation/
      smart_irrigation.yaml
      README.md

dashboards/
  README.md

packages/
  README.md

scripts/
  README.md

automations/
  README.md
```

## Blueprints

### Smart Irrigation

Blueprint لتشغيل سقاية الحديقة عند الشروق والغروب، مع:

- مدة تشغيل قابلة للتعديل
- اختيار أكثر من رشاش
- اختيار حساسات التدفق
- اختيار حساسات حالة الجهاز
- إشعار بداية التشغيل
- إشعار نهاية التشغيل
- إشعار عند الإيقاف اليدوي
- تقدير استهلاك المياه باللتر والمتر المكعب

Import URL:

```text
https://raw.githubusercontent.com/ThamerLab/HA/main/blueprints/automation/irrigation/smart_irrigation.yaml
```

## Import in Home Assistant

Home Assistant → Settings → Automations & Scenes → Blueprints → Import Blueprint

ثم الصق رابط الـ raw أعلاه.

## Notes

- يفضل أن تكون حساسات التدفق بوحدة `m³/h`.
- إذا كان حساس التدفق عندك بوحدة مختلفة، عدل خيار Flow unit عند إنشاء الأتمتة.
- هذا الريبو قابل للتوسع لاحقًا لإضافة صفحات Dashboard و Packages جاهزة.
