# Unit 8 · Animals & Actions (Động vật & hành động)

Trang chung của Unit 8, gồm 4 mục theo thứ tự một buổi học:

1. **Warm-up** – hát khởi động (Can You Swim? · I Can Walk)
2. **Vocab** – Bài 1 (dog, cat, fish, bird, rabbit, mouse) và Bài 2 (run, jump, swim, fly)
3. **Story** – 谁会 · Interactive quiz
4. **Practice** – Bóng đen bí ẩn · Đây là ai? · Vượt chướng ngại

Bấm vào một mục, bài học mở ngay trong trang. Nút **Unit 8** ở góc trên trái đưa bé về trang chung. Mục nào đã mở sẽ có dấu ✓ (lưu trên máy đang dùng; bấm "Xóa dấu đã học" để làm lại từ đầu).

## Cấu trúc thư mục trên GitHub

```
unit-8/                      ← repo mới (hoặc một thư mục trong repo có sẵn)
  index.html                 ← trang chung (file này)
  README.md
  vocab-bai-1/index.html
  vocab-bai-2/index.html
  truyen/index.html
  practice/index.html
```

4 file `index.html` trong các thư mục con lấy từ gói `Unit-8-Little-Seed.zip` đã gửi trước.

## Các bước đưa lên

1. Tạo repo mới tên `unit-8` (Public), hoặc mở repo có sẵn.
2. **Add file → Upload files**, kéo `index.html` (trang chung) và `README.md` vào → **Commit changes**.
3. Tạo từng thư mục con: **Add file → Create new file**, gõ `vocab-bai-1/ghi-chu.txt` ở ô tên file, gõ một chữ bất kỳ, **Commit changes**. Làm tương tự cho `vocab-bai-2`, `truyen`, `practice`.
4. Vào từng thư mục con → **Add file → Upload files** → kéo đúng file `index.html` của thư mục đó → **Commit changes**.
5. Bật trang (chỉ làm một lần với repo mới): **Settings → Pages → Branch: main, thư mục / (root) → Save**.
6. Đợi 1–3 phút rồi mở: `https://<tài-khoản>.github.io/unit-8/`

Nếu vẫn thấy bản cũ, bấm Ctrl + F5 (máy tính) hoặc mở tab ẩn danh.

## Mục Warm-up

Warm-up nằm ở repo `warm-up` cũ, trang chung chỉ mở sang đó, không cần up lại video. Đường dẫn đang đặt là:

```
"/warm-up/unit-8/"
```

Đường dẫn này đúng khi repo warm-up tên là `warm-up` và cùng tài khoản GitHub với repo này. Nếu khác, mở `index.html`, tìm dòng `"warm-up":` trong khối `LINKS` gần cuối file và thay bằng địa chỉ đầy đủ, ví dụ:

```
"warm-up":  { url: "https://<tài-khoản>.github.io/<tên-repo-warm-up>/unit-8/", title: "1 · Warm-up: Hát khởi động" },
```

Sửa trực tiếp trên GitHub: bấm vào `index.html` → biểu tượng bút chì → sửa → **Commit changes**.

## Lưu ý

- Mỗi bài học nằm trong khung của trang chung. Nếu một máy nào đó không cho camera (tab Lồng tiếng của truyện) hoạt động trong khung, bấm **Mở tab riêng** ở góc trên phải.
- Practice còn vài giọng chưa kiểm chứng (狗/鸟 giọng Bunny, 鸟 giọng Xiaobao, "cat" tiếng Anh, các câu 鸟不会游泳, 鸟不会飞, 鱼会跑, 鱼会飞). Nên nghe thử trước khi gửi học sinh.
