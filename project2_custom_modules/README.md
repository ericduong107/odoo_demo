# Dự Án 2: Phát Triển Module Tùy Chỉnh

## Mô Tả
Dự án này tập trung vào phát triển các module Odoo tùy chỉnh:
- Tạo module tùy chỉnh từ đầu
- Models, Views, Controllers
- Business logic phức tạp
- Quản lý dữ liệu nâng cao

## Cấu Trúc Thư Mục
```
project2_custom_modules/
├── docker-compose.yml
├── addons/
│   ├── hr_custom/              # Module quản lý nhân sự tùy chỉnh
│   │   ├── __init__.py
│   │   ├── __manifest__.py
│   │   ├── models/
│   │   ├── views/
│   │   ├── controllers/
│   │   └── static/
│   ├── sale_custom/            # Module bán hàng tùy chỉnh
│   └── inventory_custom/       # Module kho tùy chỉnh
├── config/
└── docs/
```

## Bắt Đầu
```bash
cd project2_custom_modules
docker-compose up -d
```

## Truy Cập
- URL: http://localhost:8070
- Database: odoo_custom_modules

## Các Module Ví Dụ
1. **hr_custom** - Quản lý nhân sự nâng cao
2. **sale_custom** - Quản lý đơn hàng nâng cao
3. **inventory_custom** - Quản lý kho nâng cao

## Quy Trình Phát Triển
1. Tạo manifest file
2. Định nghĩa Models
3. Tạo Views (Form, Tree, Search)
4. Thêm Controllers
5. Thêm Business logic
6. Test & Debug
