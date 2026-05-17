# ThamerLab Home Assistant

![Home Assistant](https://img.shields.io/badge/Home%20Assistant-Compatible-41BDF5?logo=homeassistant&logoColor=white)
![Blueprint](https://img.shields.io/badge/Blueprint-Irrigation-green)
![Maintained](https://img.shields.io/badge/Maintained-Yes-success)

مجموعة مرتبة وقابلة للمشاركة لملفات Home Assistant.

هذا الريبو مخصص لحفظ ومشاركة:

- Blueprints
- Dashboard views
- Mushroom cards
- Packages
- Helpers templates
- Automations
- Scripts
- Notification flows

---

# Structure

```text
blueprints/
  automation/
    irrigation/
      smart_irrigation.yaml
      README.md

dashboards/
packages/
scripts/
automations/
```

---

# Included Blueprint

## Smart Irrigation System

Blueprint ذكي لسقاية الحديقة يدعم:

- الشروق والغروب
- تشغيل أكثر من منطقة
- التحقق من التدفق
- حساب استهلاك المياه
- كشف الإيقاف اليدوي
- الإشعارات
- حساب اللترات والمتر المكعب

---

# Import Blueprint

استخدم الرابط التالي مباشرة داخل Home Assistant:

```text
https://raw.githubusercontent.com/ThamerLab/HA/main/blueprints/automation/irrigation/smart_irrigation.yaml
```

Home Assistant:

Settings → Automations & Scenes → Blueprints → Import Blueprint

---

# Recommended Hardware

- Zigbee irrigation valves
- Flow sensors
- ESPHome devices
- Aqara relays
- Zigbee2MQTT
- Home Assistant Companion App

---

# Future Plans

- Mushroom dashboards
- Irrigation dashboard package
- Energy monitoring
- Climate control packages
- Notification center
- Mobile-first dashboards
- OLED themes

---

# Author

Created and maintained by ThamerLab.
