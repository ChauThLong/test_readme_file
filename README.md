# README.md Cheat Sheet

File này là mẫu README.md và giải thích cách dùng các cú pháp Markdown cơ bản trên GitHub.

---

## 1. Headings

Sử dụng dấu `#` để tạo tiêu đề. Số lượng dấu `#` tương ứng với cấp độ tiêu đề (1–6).

```markdown
# Heading cấp 1
## Heading cấp 2
### Heading cấp 3
#### Heading cấp 4
##### Heading cấp 5
###### Heading cấp 6
```

---

## 2. Inline Code

Dùng dấu `` ` `` để đánh dấu đoạn code ngắn trong dòng văn bản.

``Use `git status` để xem thay đổi hiện tại.``

---

## 3. Fenced Code Blocks

Dùng ba dấu backticks để tạo khối code, hỗ trợ nhiều dòng.

```markdown
```
function hello() {
  console.log("Hello world");
}
```
```

---

## 4. Code Block với Syntax Highlight

Chỉ định ngôn ngữ ngay sau ba dấu backticks để kích hoạt highlighting.

```bash
npm install
php artisan serve
```

---

## 5. Lists

- **Unordered list** (dấu `-`, `*` hoặc `+`):  
  - Item 1  
  - Item 2  

1. **Ordered list** (dấu `1.`, `2.`, ...):  
   1. Item A  
   2. Item B  

---

## 6. Links & Images

- **Link**: `[Tên liên kết](https://example.com)`  
- **Image**: `![Alt text](https://example.com/image.png)`  

---

## 7. Blockquotes

Dùng dấu `>` để trích dẫn:

```markdown
> Đây là một blockquote.
```

---

## 8. Horizontal Rule

Dùng ba hoặc nhiều hơn dấu `-`, `_`, hoặc `*` trên một dòng:

```markdown
---
```

---

## 9. Tables

```markdown
| Cột 1 | Cột 2 |
|-------|-------|
| A     | B     |
| C     | D     |
```

---

*Tham khảo thêm “Basic writing and formatting syntax” trên GitHub Docs.*

