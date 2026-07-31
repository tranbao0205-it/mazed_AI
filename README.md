# Bài toán mê cung tìm đường đi bằng thuật toán A*

# Hướng dẫn cài đặt và chạy dự án

## 1. Yêu cầu hệ thống

Trước khi bắt đầu, hãy đảm bảo máy tính đã cài đặt:

- Node.js (phiên bản 14 trở lên): https://nodejs.org/
- npm (được cài đặt cùng Node.js)
- Git: https://git-scm.com/

---

## 2. Cài đặt và chạy dự án

### Bước 1: Clone dự án từ GitHub

```sh
git clone https://github.com/tranbao0205-it/mazed_AI.git
```

### Bước 2: Di chuyển vào thư mục dự án

```sh
cd mazed_AI
```

### Bước 3: Cài đặt các thư viện cần thiết

```sh
npm install
```

Nếu dự án yêu cầu Webpack nhưng chưa được cài đặt, chạy thêm:

```sh
npm install --save-dev webpack webpack-cli webpack-dev-server
```

### Bước 4: Chạy chương trình

Nếu dự án sử dụng script `dev`:

```sh
npm run dev
```

Hoặc nếu sử dụng script `start`:

```sh
npm start
```

Sau khi chạy thành công, Terminal sẽ hiển thị địa chỉ truy cập (ví dụ: `http://localhost:8080`). Mở trình duyệt và truy cập vào địa chỉ này để sử dụng chương trình.

---

## 3. Một số lưu ý

- Nếu gặp lỗi thiếu thư viện, chạy lại:

```sh
npm install
```

- Nếu xảy ra lỗi về dependency:

```sh
npm install --force
```

- Trên macOS hoặc Linux, nếu gặp lỗi quyền truy cập:

```sh
sudo npm install
```

---

Chúc bạn cài đặt và sử dụng dự án thành công!
