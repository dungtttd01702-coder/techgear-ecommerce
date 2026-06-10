# techgear-ecommerce
Tech Gear E-commerce — Nhập môn Kỹ thuật Phần mềm | FPT Polytechnic
[README.md](https://github.com/user-attachments/files/28786653/README.md)
# Tech Gear E-commerce 🛒

> **Môn học:** Nhập môn Kỹ thuật Phần mềm
>
> **Nhóm:** Nhóm 2
>
> **Trường:** FPT Polytechnic

[![Documentation](https://img.shields.io/badge/Documentation-LAB%201--8-blue)](https://github.com/techgear-team/techgear-ecommerce)
[![GitHub](https://img.shields.io/badge/GitHub-techgear--ecommerce-black?logo=github)](https://github.com/techgear-team/techgear-ecommerce)
[![SDLC](https://img.shields.io/badge/SDLC-Waterfall-green)](https://github.com/techgear-team/techgear-ecommerce)

---

## 📋 Mô tả dự án

**Tech Gear E-commerce** là nền tảng thương mại điện tử chuyên biệt dành cho thiết bị công nghệ (laptop, điện thoại, màn hình, bàn phím, chuột, phụ kiện và linh kiện PC) tại Việt Nam. Hệ thống giúp khách hàng cá nhân tìm kiếm và lọc sản phẩm theo thông số kỹ thuật (CPU, RAM, GPU, khoảng giá), đặt mua và theo dõi đơn hàng trực tuyến một cách thuận tiện. Đồng thời, hệ thống hỗ trợ Admin quản lý danh mục sản phẩm, xử lý đơn hàng và xem báo cáo doanh thu một cách tập trung, hiệu quả. Chức năng thanh toán được mô phỏng trong phạm vi phiên bản v1, chưa tích hợp cổng thanh toán thực tế (VNPay, Momo).

---

## 👥 Thành viên nhóm

| Họ tên | MSSV | Vai trò | LAB phụ trách |
|--------|------|---------|---------------|
| Nguyễn Hoàng Sang | [NHÓM TỰ ĐIỀN] | [NHÓM TỰ ĐIỀN] | [NHÓM TỰ ĐIỀN] |
| Lê Hạnh Dung | [NHÓM TỰ ĐIỀN] | [NHÓM TỰ ĐIỀN] | [NHÓM TỰ ĐIỀN] |
| Hoàng Tiến Dũng | [NHÓM TỰ ĐIỀN] | [NHÓM TỰ ĐIỀN] | [NHÓM TỰ ĐIỀN] |
| Trần Trung Dũng | [NHÓM TỰ ĐIỀN] | [NHÓM TỰ ĐIỀN] | [NHÓM TỰ ĐIỀN] |

---

## 🛠️ Công nghệ và công cụ sử dụng

| Công cụ | Mục đích |
|---------|---------|
| **GitHub** | Quản lý phiên bản, lưu trữ tài liệu dự án |
| **Trello** | Quản lý tiến độ theo quy trình SDLC Waterfall |
| **PlantUML** | Vẽ Use Case Diagram, Sequence Diagram, Activity Diagram, Class Diagram |
| **Draw.io** | [NHÓM TỰ ĐIỀN — nếu có sử dụng] |
| **Visual Paradigm** | [NHÓM TỰ ĐIỀN — nếu có sử dụng] |

---

## 📁 Cấu trúc Repository

```
techgear-ecommerce/
├── docs/
│   ├── LAB1/   # Khởi động dự án & Phân tích bài toán (Stakeholder, Phạm vi, Mục tiêu)
│   ├── LAB2/   # Thu thập & Phân tích Yêu cầu (FR, NFR, SRS)
│   ├── LAB3/   # Software Requirements Specification — đặc tả đầy đủ FR/NFR/BR
│   ├── LAB4/   # Use Case Diagram tổng quan (18 UC, 4 Actor)
│   ├── LAB5/   # Thiết kế Kiến trúc Hệ thống (Three-Layer Architecture)
│   ├── LAB6/   # Thiết kế UML (UC chi tiết, Class Diagram, Sequence, Activity Diagram)
│   ├── LAB7/   # Kiểm thử — Test Case (65 TC) & Test Plan
│   └── LAB8/   # Quản lý Dự án (Trello Board, GitHub, Nhật ký tiến độ)
├── diagrams/   # File PlantUML (.puml) và ảnh render (.png)
├── trello/     # Export Trello Board (JSON)
└── README.md
```

---

## 📦 Danh sách Deliverable

| LAB | Nội dung | Trạng thái |
|-----|----------|------------|
| LAB 1 | Khởi động dự án & Phân tích bài toán — Stakeholder Analysis, Phạm vi & Mục tiêu hệ thống, 7 chức năng mong muốn | ✅ Hoàn thành |
| LAB 2 | Thu thập & Phân tích Yêu cầu — 14 Functional Requirements (FR01–FR14), 6 Non-Functional Requirements (NFR01–NFR06) | ✅ Hoàn thành |
| LAB 3 | Software Requirements Specification (SRS) — 15 FR, 6 NFR, 6 Business Rules, mô tả màn hình giao diện | ✅ Hoàn thành |
| LAB 4 | Use Case Diagram tổng quan — 18 Use Case, 4 Actor (Khách hàng, Admin, Nhân viên kho, Hệ thống) | ✅ Hoàn thành |
| LAB 5 | Thiết kế Kiến trúc Hệ thống — Three-Layer Architecture (Presentation, Business Logic, Data Access) | ✅ Hoàn thành |
| LAB 6 | Thiết kế UML — Use Case chi tiết, Class Diagram, Sequence Diagram, Activity Diagram (10 UC mỗi loại) | ✅ Hoàn thành |
| LAB 7 | Kiểm thử — 65 Test Case cho 18 UC, phủ BR01–BR06, Test Plan 4 bước | ✅ Hoàn thành |
| LAB 8 | Quản lý Dự án — Trello Board (32 thẻ), GitHub Version Control, Nhật ký tiến độ | 🔄 Đang thực hiện |

---

## ⚙️ Quy trình phát triển (SDLC Waterfall)

```
Requirement        →  LAB 1, LAB 2
    ↓
Analysis           →  LAB 2, LAB 3 (SRS: FR, NFR, BR)
    ↓
Design             →  LAB 4 (Use Case), LAB 5 (Kiến trúc), LAB 6 (UML)
    ↓
Implementation     →  [NHÓM TỰ ĐIỀN — nếu có code]
    ↓
Testing            →  LAB 7 (Test Case & Test Plan)
    ↓
Deployment/Submit  →  LAB 8 (Quản lý Dự án, nộp bài)
```

Dự án Tech Gear E-commerce được thực hiện theo mô hình **SDLC Waterfall**, mỗi giai đoạn hoàn thành trước khi chuyển sang giai đoạn tiếp theo. Tất cả tài liệu từ LAB 1 đến LAB 8 được lưu trữ và quản lý phiên bản trên GitHub.

---

## 📌 Hướng dẫn sử dụng GitHub

### Quy tắc branch

```
main          ← Nhánh chính, chỉ chứa phiên bản đã hoàn thiện và được review
develop       ← Nhánh tích hợp, merge từ nhánh cá nhân trước khi vào main
branch-[ten]  ← Nhánh cá nhân của từng thành viên (ví dụ: branch-sang, branch-dung)
```

### Quy tắc commit message

```
[LAB1] Add: Stakeholder Analysis và Phạm vi hệ thống
[LAB3] Update: Hoàn thiện SRS — bổ sung Business Rules
[LAB4] Add: Use Case Diagram 18 UC PlantUML
[LAB6] Update: Bổ sung Sequence Diagram UC08
[LAB7] Fix: Chỉnh sửa Test Case TC13_03
docs: cập nhật README — thêm tiến độ LAB 7
```

### Quy trình làm việc nhóm

1. Nhóm trưởng tạo branch cá nhân cho từng thành viên
2. Thành viên chuyển sang branch được giao (`branch-[ten]`)
3. Thực hiện LAB — thêm/chỉnh sửa tài liệu
4. Commit với message rõ ràng theo quy tắc
5. Push lên GitHub
6. Tạo Pull Request từ `branch-[ten]` vào `develop`
7. Nhóm trưởng / Reviewer kiểm tra nội dung
8. Approve và Merge vào `develop`
9. Khi `develop` ổn định, nhóm trưởng merge vào `main`

---

## 📊 Tiến độ dự án

| LAB | Tên LAB | Trạng thái | Người phụ trách |
|-----|---------|------------|-----------------|
| LAB 1 | Khởi động dự án & Phân tích bài toán | ✅ Hoàn thành | [NHÓM TỰ ĐIỀN] |
| LAB 2 | Thu thập & Phân tích Yêu cầu | ✅ Hoàn thành | [NHÓM TỰ ĐIỀN] |
| LAB 3 | Software Requirements Specification (SRS) | ✅ Hoàn thành | [NHÓM TỰ ĐIỀN] |
| LAB 4 | Use Case Diagram tổng quan | ✅ Hoàn thành | [NHÓM TỰ ĐIỀN] |
| LAB 5 | Thiết kế Kiến trúc Hệ thống | ✅ Hoàn thành | [NHÓM TỰ ĐIỀN] |
| LAB 6 | Thiết kế UML (Class, Sequence, Activity) | ✅ Hoàn thành | [NHÓM TỰ ĐIỀN] |
| LAB 7 | Test Case & Test Plan | ✅ Hoàn thành | [NHÓM TỰ ĐIỀN] |
| LAB 8 | Quản lý Dự án | 🔄 Đang thực hiện | [NHÓM TỰ ĐIỀN] |

---

## 🔗 Liên kết quan trọng

- **GitHub Repository:** [NHÓM TỰ ĐIỀN]
- **Trello Board:** [NHÓM TỰ ĐIỀN]
- **Google Drive:** [NHÓM TỰ ĐIỀN]

---

## 📝 Kết luận

Qua 8 LAB của môn Nhập môn Kỹ thuật Phần mềm, nhóm đã xây dựng hoàn chỉnh tài liệu đặc tả cho hệ thống **Tech Gear E-commerce** — từ phân tích bài toán, thu thập yêu cầu, thiết kế kiến trúc Three-Layer, vẽ các loại UML Diagram đến lập kế hoạch kiểm thử với 65 Test Case phủ toàn bộ 18 Use Case và 6 Business Rules. Nhóm học được quy trình phát triển phần mềm theo mô hình Waterfall một cách có hệ thống, hiểu rõ vai trò của từng giai đoạn từ Requirement đến Testing. Việc làm việc nhóm qua Trello và GitHub giúp thành viên rèn luyện kỹ năng quản lý phiên bản, phân công công việc rõ ràng và phối hợp hiệu quả trong môi trường dự án thực tế.

---

*FPT Polytechnic | Nhập môn Kỹ thuật Phần mềm | Nhóm 2*
