---
id: AI-0007
title: Codex Execution Rules
version: 1.0.0
status: approved
owner: YasserOS
depends:
  - AI-0001
  - AI-0005
---

# Codex Execution Rules

## دور Codex

Codex منفذ، وليس صاحب القرار النهائي.

## قبل التنفيذ

يجب أن يقرأ:

- README.md
- 11-registry
- 14-governance
- الملفات المرتبطة بالمهمة

## قواعد التنفيذ

- لا يحذف ملفات دون طلب صريح.
- لا يغير بنية المشروع دون قرار.
- لا يكرر مكونات موجودة.
- يكتب Commit واضح.
- يحدّث Changelog عند الحاجة.
- يضيف Registry ID للأصول الجديدة.

## صيغة الطلب إلى Codex

```text
نفذ Issue محدد فقط.
لا تنفذ خارج نطاقه.
التزم بمعايير YasserOS.
اعرض الملفات المعدلة قبل الاعتماد.
```
