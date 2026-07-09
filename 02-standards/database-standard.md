# معيار قواعد البيانات

## القاعدة الافتراضية
PostgreSQL.

## الحقول القياسية لكل جدول
- id UUID PRIMARY KEY
- created_at TIMESTAMP
- updated_at TIMESTAMP
- deleted_at TIMESTAMP NULL
- created_by UUID NULL
- updated_by UUID NULL
- is_active BOOLEAN DEFAULT TRUE

## قواعد التصميم
- استخدم أسماء جداول بصيغة snake_case.
- استخدم المفاتيح الأجنبية بوضوح.
- أنشئ فهارس للحقول المستخدمة في البحث والربط.
- لا تخزن نفس المعلومة في أكثر من مكان إلا بسبب واضح وموثق.
- استخدم soft delete للبيانات التشغيلية المهمة.
