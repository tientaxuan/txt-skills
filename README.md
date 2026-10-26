# txt-skills

Kho lưu trữ các Agent Skills tùy chỉnh phục vụ quy trình phát triển phần mềm, chuẩn hoá kiến trúc và tối ưu hoá dự án với các AI Coding Assistants (Antigravity, Claude Code, Cursor, Copilot...).

## 📚 Danh sách Skills

| Tên Skill | Thư mục | Mô tả ngắn |
| :--- | :--- | :--- |
| **`nextjs-code-quality`** | [`skills/nextjs-code-quality`](./skills/nextjs-code-quality/SKILL.md) | Bộ công cụ chuẩn hoá chất lượng mã nguồn toàn diện cho Next.js (App Router, TS, Tailwind, React 19): ESLint 9 Flat Config, Prettier, Lint-Staged (chunking cho Windows), Husky v9, Commitlint, Vitest + Testing Library, và Zero-broken Build Gate. |

---

## 🚀 Cách cài đặt và sử dụng

### 1. Dùng với Antigravity / Claude Code
Bạn có thể copy thư mục skill tương ứng vào thư mục `.agents/skills/` hoặc `.claude/skills/` của dự án:

```bash
# Ví dụ copy skill nextjs-code-quality vào dự án của bạn
cp -r skills/nextjs-code-quality /path/to/your-project/.agents/skills/
```

### 2. Kích hoạt trong chat
Sau khi thêm skill, bạn có thể yêu cầu trợ lý ảo:
> *"Hãy áp dụng skill `nextjs-code-quality` để thiết lập linter, formatter, husky và testing cho dự án này"*
