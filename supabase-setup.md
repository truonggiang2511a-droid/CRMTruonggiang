# Supabase CRM Cloud

CRM dùng project Supabase `giang-ea-control` với các bảng riêng:

- `crm_profiles`
- `crm_customers`
- `crm_properties`

RLS giới hạn dữ liệu theo `auth.uid()`. Các bảng EA hiện có không được dùng chung cho CRM.

Frontend sử dụng publishable key; không đặt `service_role` key vào trình duyệt.
