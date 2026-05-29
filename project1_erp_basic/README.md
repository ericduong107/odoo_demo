# Dự Án 1: Cấu Hình ERP Cơ Bản Odoo

## Mô Tả
Dự án này hướng dẫn cấu hình ERP cơ bản trong Odoo, bao gồm:
- Thiết lập công ty
- Cấu hình kho hàng
- Quản lý sản phẩm
- Cài đặt các module bán hàng và mua hàng cơ bản

## Cấu Trúc Thư Mục
```
project1_erp_basic/
├── docker-compose.yml      # Docker configuration
├── addons/                 # Custom modules
├── config/                 # Configuration files
├── migrations/             # Database migrations
└── docs/                   # Documentation
```

## Bắt Đầu

### Yêu Cầu
- Docker & Docker Compose
- Python 3.10+
- PostgreSQL

### Cài Đặt
```bash
cd project1_erp_basic
docker-compose up -d
```

### Truy Cập
- URL: http://localhost:8069
- Database: odoo_erp_basic
- Admin user: admin
- Admin password: admin

## Các Module Chính
- Sale (Bán hàng)
- Purchase (Mua hàng)
- Inventory (Kho)
- Accounting (Kế toán)

## Tài Liệu
Xem thêm chi tiết tại `docs/` folder
