# TikTok Discovery Engine

<p align="center">
  <strong>Dashboard mô phỏng cách tín hiệu hành vi trên TikTok được diễn giải theo thời gian thực.</strong>
</p>

<p align="center">
  <a href="https://github.com/BinCry/Demo"><img src="https://img.shields.io/badge/Trạng_thái-Demo-22c55e?style=for-the-badge&logo=github&logoColor=white" alt="Trạng thái: Demo"></a>
  <img src="https://img.shields.io/badge/Giao_diện-Tiếng_Việt-ef4444?style=for-the-badge&logo=googletranslate&logoColor=white" alt="Giao diện tiếng Việt">
  <img src="https://img.shields.io/badge/Video-63.1_giây-8b5cf6?style=for-the-badge&logo=video&logoColor=white" alt="Video demo 63.1 giây">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=1f2937" alt="JavaScript">
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Google_Fonts-4285F4?style=for-the-badge&logo=googlefonts&logoColor=white" alt="Google Fonts">
</p>

---

## Tổng quan

**TikTok Discovery Engine** là một trang demo trực quan hoá “ngôn ngữ cơ thể số” (digital body language). Ứng dụng phát video mô phỏng và đồng bộ các chỉ số telemetry để minh hoạ cách hệ thống có thể đọc những tín hiệu như thời gian dừng xem, tốc độ vuốt, tương tác vi mô và mức độ quan tâm nội dung.

> Đây là sản phẩm mô phỏng phục vụ mục đích trình diễn/giáo dục, không kết nối API TikTok hoặc thu thập dữ liệu người dùng thực.

## Điểm nổi bật

- Phát video demo trực tiếp trong khung điện thoại mô phỏng.
- Cập nhật timeline và chỉ số hành vi theo từng mốc thời gian.
- Hiển thị phân loại nội dung, dwell time, swipe velocity và micro-interaction.
- Bảng telemetry, activity log và các tín hiệu suy luận AI trực quan.
- Màn hình kết luận với kịch bản phân phối nội dung tiếp theo.
- Có trạng thái dự phòng khi không tìm thấy tệp video.

## Công nghệ sử dụng

| Công nghệ | Vai trò |
| :-- | :-- |
| HTML5 | Cấu trúc trang và phần tử phát video gốc. |
| CSS3 | Hiệu ứng neon, animation và tuỳ biến giao diện. |
| JavaScript thuần | Đồng bộ video, timeline, telemetry và các thao tác điều khiển. |
| Tailwind CSS CDN | Xây dựng layout/dashboard nhanh bằng utility class. |
| Google Fonts | Sử dụng Inter và JetBrains Mono cho giao diện hiện đại, dễ đọc. |

## Khởi chạy nhanh

1. Clone repository:

   ```bash
   git clone https://github.com/BinCry/Demo.git
   ```

2. Mở thư mục dự án và chạy `index.html` bằng trình duyệt hiện đại.

3. Nhấn **▶ Chạy Demo** để bắt đầu phiên mô phỏng. Nút **↻ Reset** sẽ đưa toàn bộ chỉ số về trạng thái ban đầu.

Không cần cài đặt Node.js, package hay build step.

## Cấu trúc dự án

```text
Demo/
├── index.html  # Giao diện dashboard và logic mô phỏng
├── demo.mp4    # Video dùng cho phiên trình diễn
└── README.md   # Tài liệu dự án
```

## Lưu ý về video

Trang sử dụng đường dẫn tương đối sau:

```html
<video id="mainVideo" src="demo.mp4" ...></video>
```

Nếu thay video, hãy giữ tên là `demo.mp4` và đặt cùng thư mục với `index.html`; hoặc cập nhật thuộc tính `src` thành tên tệp mới.

## Tương thích

Khuyến nghị dùng phiên bản mới của Chrome, Edge, Firefox hoặc Safari. Các badge trong README sử dụng SVG từ Shields.io, tự co giãn theo luồng nội dung nên hiển thị tốt trên màn hình điện thoại và laptop.

## Giấy phép

Chưa có giấy phép mã nguồn được khai báo. Hãy liên hệ tác giả trước khi tái sử dụng cho mục đích thương mại.
