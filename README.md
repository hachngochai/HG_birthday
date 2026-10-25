# 🍭 Hương Giang Birthday — Candy Pink VR 💗

> Một món quà sinh nhật tương tác 3D dành riêng cho **em Hương Giang**, với thế giới kẹo ngọt mang sắc **hồng pastel**.

[🎂 Xem website sinh nhật](https://hachngochai.github.io/HG_birthday/) · [💻 Mã nguồn](https://github.com/hachngochai/HG_birthday)

## ✨ Điểm nổi bật

- **Không gian 3D** xây dựng bằng Three.js, có thể kéo để xoay góc nhìn và khám phá.
- **Nhân vật Hương Giang** mặc váy hồng pastel, tóc dài, đeo nơ và cầm **kẹo gậy sọc hồng – trắng**.
- **Candy theme** với các cột trang trí sọc kẹo, sắc hồng dịu và ánh sáng phù hợp.
- **Chạm vào nhân vật:** 36 trái tim hồng/trắng xuất hiện rồi tỏa ra xung quanh. 💕
- **Hành trình sinh nhật:** mở quà → khám phá → bánh kem → cắm đủ 5 nến → thổi nến → nghe giai điệu *Happy Birthday* → mở lá thư.
- **Thổi nến bằng micro**, có cách chạm vào bánh thay thế khi không cấp được quyền micro.
- **Chế độ ngày/đêm**, bật/tắt âm thanh, thiết kế hỗ trợ màn hình điện thoại và tùy chọn VR trên thiết bị tương thích.

## 🎮 Cách trải nghiệm

1. Mở trang web và **chạm món quà** để bắt đầu.
2. Khám phá đảo kẹo và làm theo lời thoại/nhãn hướng dẫn.
3. **Nhấn vào Hương Giang** để kích hoạt hiệu ứng trái tim.
4. Nhấn vào bánh kem để **cắm lần lượt 5 cây nến**.
5. Cho phép dùng micro để thổi nến; nếu không thể sử dụng micro, nhấn bánh theo hướng dẫn trên màn hình.
6. Nghe giai điệu chúc mừng sinh nhật rồi mở **lá thư dành cho Giang**.

**Điều khiển:** Kéo/giữ chuột hoặc vuốt trên màn hình để thay đổi góc nhìn; nhấn vào vật thể để tương tác.

## 🛠 Công nghệ

- **HTML, CSS, JavaScript** — website tĩnh, không cần backend.
- **Three.js** — dựng cảnh, ánh sáng, nhân vật, vật thể và hiệu ứng 3D.
- **Web Audio API** — tạo giai điệu, âm thanh.
- **MediaDevices / microphone API** — nhận tín hiệu âm thanh để thổi nến (cần quyền truy cập).
- **WebXR** — tùy chọn trải nghiệm VR khi trình duyệt và thiết bị hỗ trợ.

## 📁 Cấu trúc dự án

```text
HG_birthday/
├── index.html     # Toàn bộ giao diện, cảnh 3D, trò chơi và tương tác
└── README.md      # Giới thiệu và hướng dẫn
```

## 🚀 Chạy thử trên máy

Có thể mở `index.html` qua máy chủ HTTP cục bộ, ví dụ bằng VS Code **Live Server**, hoặc từ thư mục dự án chạy:

```bash
python -m http.server 8000
```

Sau đó truy cập `http://localhost:8000`. Cần kết nối Internet để tải các module Three.js từ CDN. Khi dùng micro, trình duyệt thường yêu cầu **HTTPS hoặc localhost**.

## 🌐 Triển khai GitHub Pages

Trong repository, vào **Settings → Pages**. Ở **Build and deployment**, chọn **Deploy from a branch**, chọn nhánh **main** và thư mục **/(root)**, rồi **Save**.

Sau khi workflow triển khai thành công, truy cập:

**https://hachngochai.github.io/HG_birthday/**

> Nếu trang chưa hoạt động, kiểm tra mục **Actions** và cấu hình **Pages** trong repository.

## 💌 Lời nhắn

Chúc mừng sinh nhật **em Hương Giang**! Mong tuổi mới của em luôn ngọt ngào, rực rỡ và có thật nhiều điều đáng yêu. 🎀

---

Made with 💗 for Hương Giang · Repository: [hachngochai/HG_birthday](https://github.com/hachngochai/HG_birthday)
