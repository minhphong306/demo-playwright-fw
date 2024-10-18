# Thông tin project
- Project này là automation test cho hệ thống blog wordpress.
- URL của môi trường:
    - Dev: https://pw-practice-dev.playwrightvn.com
    - Staging: 
    - Production:
- Cấu trúc thư mục

```
.
├── README.md
├── fixture/
├── playwright.config.ts
├── pom/
└── src/
```
Trong đó:
- fixture: chứa các fixture của dự án. Tất cả fixture được import tại fixture/index.ts
- pom: chứa các page object model của dự án.
- src: chứa code test. Mỗi folder là một module tương ứng.

# Cài đặt
- Chạy lệnh sau:

```bash
npm install 
hoặc
npm i
```

# Các quy tắc khi viết code
- Viết camelCase

# Câu hỏi thường gặp
1. Cài đặt gặp lỗi: node_module not found?
- Cần chạy lại lệnh `npm i`

2. 
