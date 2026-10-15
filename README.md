# AI Agent Workspace Starter Template

Bộ khung cấu trúc thư mục và file cấu hình cơ bản cho AI Agent, gọn nhẹ, chuẩn hóa theo cơ chế Antigravity Customizations, có thể sao chép và tái sử dụng ngay cho mọi loại dự án (lập trình, viết tài liệu, nghiên cứu, quản lý dự án,...).

---

## 1. Cấu Trúc Thư Mục

```text
.
├── AGENTS.md                          # Hướng dẫn chung về cách AI Agent hoạt động & giao tiếp
├── README.md                          # Tài liệu giới thiệu và hướng dẫn sử dụng bộ template
├── .agents/                           # Thư mục cấu hình chuẩn hóa cho AI Agent
│   ├── rules/                         # Các quy tắc ràng buộc chung mà AI luôn tuân thủ
│   │   ├── quality-and-accuracy.md    # Tiêu chuẩn chất lượng, tính chính xác và chống ảo giác
│   │   ├── change-management.md       # Quản lý phạm vi và an toàn khi thay đổi
│   │   └── security-and-data-protection.md # Bảo vệ bí mật và dữ liệu an toàn
│   └── skills/                        # Các kỹ năng theo quy trình (On-demand skills)
│       ├── planning/
│       │   └── SKILL.md               # Quy trình phân tích và lập kế hoạch cho tác vụ phức tạp
│       ├── task-execution/
│       │   └── SKILL.md               # Quy trình triển khai có kiểm tra bối cảnh và kỷ luật
│       └── verification/
│           └── SKILL.md               # Quy trình kiểm tra, đối chiếu và nghiệm thu kết quả
└── docs/                              # Tài liệu dự án giúp duy trì ngữ cảnh giữa các phiên làm việc
    ├── requirements.md                # Mục tiêu, phạm vi và tiêu chí nghiệm thu dự án
    ├── roadmap.md                     # Lộ trình và các mốc quan trọng (Milestones)
    └── progress.md                    # Nhật ký công việc và các quyết định đã thống nhất
```

---

## 2. Mô Tả Chức Năng Từng Thành Phần

| Thành Phần | Vai Trò & Chức Năng |
| :--- | :--- |
| **`AGENTS.md`** | Điểm khởi đầu quy định vai trò, nguyên tắc làm việc cốt lõi, quy trình tương tác và phong cách giao tiếp của AI. |
| **`.agents/rules/`** | Chứa các quy tắc bắt buộc mà Agent tự động áp dụng để đảm bảo độ tin cậy, không vượt phạm vi và bảo vệ dữ liệu. |
| **`.agents/skills/`** | Chứa các quy trình thực hiện công việc từng bước (workflow runbooks) với YAML frontmatter chuẩn, được kích hoạt đúng lúc. |
| **`docs/`** | Cung cấp và duy trì ngữ cảnh cho AI qua nhiều phiên làm việc mà không sợ bị trôi mất thông tin quan trọng. |

---

## 3. Cách Sử Dụng Cho Dự Án Mới

1. **Sao chép vào dự án**: Sao chép toàn bộ các tệp và thư mục trên vào thư mục gốc của dự án mới.
2. **Cập nhật mục tiêu**: Điền thông tin dự án vào [requirements.md](docs/requirements.md) và các mốc chính vào [roadmap.md](docs/roadmap.md).
3. **Tùy biến linh hoạt**:
   - Thêm quy tắc riêng của dự án vào `.agents/rules/` (nếu cần).
   - Thêm các kỹ năng đặc thù (như xuất bản bài viết, phân tích dữ liệu, đóng gói ứng dụng) vào `.agents/skills/`.
4. **Bắt đầu làm việc với AI**: AI Agent sẽ tự động đọc `AGENTS.md` và các quy tắc để hỗ trợ bạn với độ chính xác cao nhất.
