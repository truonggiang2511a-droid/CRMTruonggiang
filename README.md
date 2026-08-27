# CRMTruonggiang — RE OS AI PRO

Web CRM quản lý khách hàng và kho bất động sản, dựng từ source CRM hiện có của Trường Giang.

## Chức năng hiện tại
- Quản lý khách hàng
- Quản lý kho BĐS
- Tìm kiếm nhanh
- Sửa/xóa dữ liệu
- Gọi, SMS, mở Zalo
- Google Maps link
- Tối đa 20 hình ảnh/căn
- Voice AI draft cơ bản
- AI Daily Brief cơ bản
- Backup JSON
- Lưu dữ liệu local bằng IndexedDB

## Chạy local
```bash
npm install
npm run dev
```

## Build production
```bash
npm run build
npm run preview
```

## Ghi chú
Phiên bản này giữ nguyên kiến trúc Local-First/IndexedDB của source gốc. Supabase/đăng nhập đa tài khoản sẽ được tích hợp ở bước tiếp theo.
