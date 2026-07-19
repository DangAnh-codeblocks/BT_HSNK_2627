# 📝 Hướng Dẫn Nộp Bài Tập Lên GitHub

## Bước 1: Tạo Repository Riêng Cho Bạn

1. Đăng nhập vào **GitHub** (github.com)
2. Click vào avatar góc trên phải → **Your repositories** 
3. Click nút **New** (xanh lá cây)
4. Điền thông tin:
   - **Repository name**: `BT_HSNK_2627_TenBanHoc` 
   - Ví dụ: `BT_HSNK_2627_NguyenVanA`
5. Chọn **Public** (để thầy/cô có thể xem)
6. Click **Create repository**

---

## Bước 2: Nộp Bài (Cách 1 - Upload Trực Tiếp - DỄ NHẤT)

### 2.1 Upload File Qua GitHub Web

1. Vào repository của bạn
2. Click **Add file** → **Create new file** (hoặc Upload files)
3. **Tạo thư mục**: Nhập tên file là `Tuan1/Bai1.cpp`
   - GitHub sẽ tự tạo thư mục `Tuan1`
   - File sẽ được đặt trong thư mục đó

4. **Paste code** của bạn vào phần nội dung
5. Cuộn xuống → Click **Commit changes**
6. Nhập tin nhắn commit (VD: "Nộp bài 1 tuần 1")
7. Click **Commit changes**

### ✅ Xong! Bài của bạn đã được nộp!

---

## Bước 3: Nộp Bài (Cách 2 - Git Command - Nâng Cao)

Nếu bạn đã cài Git trên máy:

### 3.1 Clone Repository

```bash
git clone https://github.com/USERNAME/BT_HSNK_2627_TenBanHoc.git
cd BT_HSNK_2627_TenBanHoc
```
*(Thay USERNAME = tên đăng nhập GitHub của bạn)*

### 3.2 Tạo Thư Mục Và File

```bash
# Tạo thư mục Tuan1
mkdir Tuan1

# Tạo file Bai1.cpp (Windows)
type nul > Tuan1\Bai1.cpp

# Tạo file Bai1.cpp (Mac/Linux)
touch Tuan1/Bai1.cpp
```

### 3.3 Chỉnh Sửa File

- Mở file `Tuan1/Bai1.cpp` bằng VS Code hoặc editor
- Paste code của bạn vào
- Lưu file

### 3.4 Upload Lên GitHub

```bash
# Thêm file vào staging area
git add Tuan1/Bai1.cpp

# Commit (lưu thay đổi)
git commit -m "Nộp bài 1 tuần 1"

# Push lên GitHub
git push origin main
```

### ✅ Xong! Bài của bạn đã được nộp lên GitHub!

---

## 📋 Cấu Trúc Folder Chuẩn

```
BT_HSNK_2627_TenBanHoc/
├── Tuan1/
│   ├── Bai1.cpp
│   ├── Bai2.cpp
│   └── ...
├── Tuan2/
│   ├── Bai1.cpp
│   ├── Bai2.cpp
│   └── ...
└── ...
```

---

## ⚠️ Lưu Ý Quan Trọng

✅ **Phải làm:**
- Đặt tên file đúng: `BaiX.cpp` (VD: `Bai1.cpp`, `Bai2.cpp`)
- Đặt file trong thư mục `TuanX` (VD: `Tuan1/`, `Tuan2/`)
- Chọn **Public** repository để thầy/cô xem được
- Commit message phải rõ ràng (VD: "Nộp bài 1 tuần 1")

❌ **Không được làm:**
- Không được đặt tên file sai (VD: `bai1.cpp`, `Bai_1.cpp`)
- Không được để file ở root folder (phải trong thư mục `TuanX/`)
- Không được chọn Private repository
- Không được xóa file sau khi nộp

---

## 🆘 Gặp Lỗi?

**Lỗi 404 khi push:**
- Kiểm tra username GitHub của bạn
- Kiểm tra branch name (thường là `main` hoặc `master`)

**Lỗi authentication:**
- Tạo Personal Access Token trên GitHub
- Hoặc setup SSH key

**Không biết username GitHub:**
- Vào github.com → xem profile → @username ở URL

---

## 📞 Liên Hệ

Nếu gặp vấn đề, liên hệ thầy/cô qua Padlet!

---

**Chúc các bạn học tốt!** 🚀
