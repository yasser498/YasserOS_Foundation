---
id: AI-0002
title: AI Gateway Rules
version: 1.0.0
status: approved
owner: YasserOS
depends:
  - AI-0001
---

# AI Gateway Rules

## المبدأ

كل مشاريع YasserOS تتعامل مع طبقة AI Gateway وليس مع مزود AI مباشرة.

## الهدف

- منع Vendor Lock-in.
- تغيير المزود دون تعديل المشاريع.
- تسجيل الاستخدام.
- ضبط التكاليف.
- توحيد البرومبتات.
- تطبيق معايير الشركة.

## المزودون المدعومون مستقبلاً

- OpenAI
- Gemini
- Claude
- OpenRouter
- Ollama
- Local Models

## القاعدة الذهبية

لا تضع مفاتيح API داخل كود المشاريع. المفاتيح تكون في السيرفر أو Secret Manager فقط.
