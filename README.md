# 🎉 README.md Cheat Sheet (Phiên bản tiếng Việt)

File này là mẫu **README.md** giúp bạn tạo file README đẹp mắt và dễ hiểu trên GitHub.

---

## 📖 Mục Lục

- [🎯 Giới thiệu](#giới-thiệu)
- [📝 Cú pháp cơ bản](#cú-pháp-cơ-bản)
  - [🔤 Tiêu đề (Headings)](#tiêu-đề-headings)
  - [📜 Danh sách (Lists)](#danh-sách-lists)
  - [💻 Đoạn mã (Code)](#đoạn-mã-code)
    - [🔸 Inline Code](#inline-code)
    - [🔹 Code block](#code-block)
    - [🔹 Code block có highlight](#code-block-có-highlight)
  - [🎨 Định dạng inline (Inline styling)](#định-dạng-inline-inline-styling)
  - [🔗 Liên kết & 🖼️ Hình ảnh](#liên-kết--hình-ảnh)
  - [❝ Trích dẫn (Blockquote)](#trích-dẫn-blockquote)
  - [➖ Gạch ngang (Horizontal rule)](#gạch-ngang-horizontal-rule)
  - [📊 Bảng (Table)](#bảng-table)
  - [🎬 Thêm video/GIF vào README](#thêm-videogif-vào-readme)
- [💡 Mẹo (Tips)](#mẹo-tips)

---

## 🎯 Giới thiệu

README.md là nơi đầu tiên người khác nhìn thấy dự án. Viết README rõ ràng giúp người dùng hiểu nhanh mục đích, cách cài đặt và sử dụng.

---

## 📝 Cú pháp cơ bản

### 🔤 Tiêu đề (Headings)

Dùng dấu `#` để tạo tiêu đề, cấp độ từ 1 đến 6:

```markdown
# Tiêu đề cấp 1
## Tiêu đề cấp 2
### Tiêu đề cấp 3
#### Tiêu đề cấp 4
##### Tiêu đề cấp 5
###### Tiêu đề cấp 6
```

### 📜 Danh sách (Lists)

- **Không thứ tự** (unordered):
  ```markdown
  - Mục 1
  - Mục 2
  ```
- **Có thứ tự** (ordered):
  ```markdown
  1. Mục A
  2. Mục B
  ```

### 💻 Đoạn mã (Code)

#### 🔸 Inline Code

Dùng dấu `` ` `` cho đoạn code ngắn trong dòng:

```markdown
Sử dụng `git status` để kiểm tra trạng thái.
```

#### 🔹 Code block

Dùng ba dấu backticks cho nhiều dòng:

```markdown
```
echo "Hello, world!";
```
```

#### 🔹 Code block có highlight

Thêm tên ngôn ngữ ngay sau backticks đầu:

```bash
npm install
php artisan serve
```

### 🎨 Định dạng inline (Inline styling)

- **Đậm**: `**Chữ đậm**` → **Chữ đậm**
- *Nghiêng*: `*Chữ nghiêng*` → *Chữ nghiêng*
- ~~Gạch ngang~~: `~~Gạch ngang~~` → ~~Gạch ngang~~
- Phím bấm: `<kbd>ENTER</kbd>` → <kbd>ENTER</kbd>
- Làm nổi bật dòng: `> Đây là dòng nổi bật` →  
  > Đây là dòng nổi bật

### 🔗 Liên kết & 🖼️ Hình ảnh

- **Liên kết**: `[Tên liên kết](https://example.com)`
- **Hình ảnh**: `![Alt text](https://example.com/image.png)`

### ❝ Trích dẫn (Blockquote)

Dùng `>` để tạo blockquote:

```markdown
> Đây là một trích dẫn.
```

### ➖ Gạch ngang (Horizontal rule)

Dùng ba dấu `-`, `_` hoặc `*`:

```markdown
---
```

### 📊 Bảng (Table)

```markdown
| Cột 1 | Cột 2 |
|-------|-------|
| A     | B     |
| C     | D     |
```

### 🎬 Thêm video/GIF vào README

GitHub không hỗ trợ nhúng video trực tiếp, bạn có thể:

1. Chuyển video thành GIF.
2. Tải GIF lên repo (ví dụ thư mục `demo/`).
3. Thêm vào README:

```markdown
![Demo GIF](demo/video-demo.gif)
```

---

## 💡 Mẹo (Tips)

- ✏️ Viết ngắn gọn, rõ ràng.
- 🎨 Dùng emoji để tăng tính trực quan.
- 📚 Thêm ảnh GIF/screenshot minh họa.
- 🔍 Cập nhật README khi có thay đổi lớn.
- 📑 Sử dụng mục lục để điều hướng nhanh.

