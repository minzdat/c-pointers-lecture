# Học Con Trỏ C - Web Tương Tác (C Pointers Interactive Guide)

Một ứng dụng web tương tác trực quan giúp người mới học lập trình hiểu sâu về bản chất của **Con trỏ (Pointers)** trong ngôn ngữ C. Thay vì những lý thuyết khô khan, dự án sử dụng các mô phỏng trực quan (như hệ thống "Tủ khóa bộ nhớ") để giải thích cách máy tính thực sự quản lý bộ nhớ.

## 🌟 Tính năng nổi bật (Features)

- **Mô phỏng trực quan (Visual Simulations):** Trực quan hóa RAM thành các "ngăn tủ" (lockers), giúp dễ dàng hình dung biến, địa chỉ và con trỏ.
- **Tương tác trực tiếp (Interactive Execution):** Cho phép bấm nút mô phỏng quá trình thực thi mã C (ví dụ: `p++`, `*p = 99`) và xem bộ nhớ thay đổi theo thời gian thực (animations).
- **Phân tách ngữ cảnh (Contextual Explanations):** 
  - Khai báo con trỏ vs Sử dụng con trỏ (Toán tử `*` và `&`).
  - Truyền tham trị (Pass by Value) vs Truyền tham chiếu (Pass by Reference) trong Hàm.
  - Mối quan hệ mật thiết giữa Mảng và Con trỏ.
- **Đa ngôn ngữ (Bilingual):** Hỗ trợ chuyển đổi ngôn ngữ Anh - Việt trực tiếp trên giao diện (i18n).
- **Bài tập thực hành (Mini Challenges):** Tích hợp các bài tập từ cơ bản đến nâng cao kèm theo giải thích chi tiết code.
- **Zero-Setup (Không cần cài đặt):** Chạy trực tiếp mọi thứ trên trình duyệt mà không cần cài đặt Node.js hay Webpack.

## 🚀 Cách sử dụng (How to Run)

Dự án được thiết kế hoàn toàn theo dạng Standalone (chạy không cần build). 

1. Clone hoặc tải mã nguồn về máy:
   ```bash
   git clone https://github.com/minzdat/c-pointers-lecture.git
   ```
2. Mở trực tiếp file `index.html` bằng bất kỳ trình duyệt web hiện đại nào (Chrome, Edge, Firefox, Safari).
3. Hoặc có thể deploy lên **GitHub Pages** / **Vercel** / **Netlify** một cách nhanh chóng chỉ bằng cách trỏ vào thư mục chứa `index.html`.

## 🛠️ Công nghệ sử dụng (Tech Stack)

- **HTML5 & CSS3:** Cấu trúc và một số keyframes animations.
- **React 18:** Viết các component tương tác (được load trực tiếp qua CDN `esm.sh`).
- **Tailwind CSS:** Styling nhanh gọn thông qua CDN script.
- **Babel Standalone:** Biên dịch JSX ngay trên trình duyệt (In-browser transpilation).
- **Lucide React:** Sử dụng bộ icon mã nguồn mở tuyệt đẹp.

## 📝 Cấu trúc nội dung

Bài giảng được chia thành 5 tab chính:
1. **Bản chất bộ nhớ:** Hiểu bộ nhớ qua hình ảnh ẩn dụ (Tủ khóa).
2. **Cú pháp & Ký hiệu:** Giải phẫu hai toán tử `*` và `&`.
3. **Con trỏ & Hàm:** Khác biệt giữa Truyền bản sao và Truyền địa chỉ (thông qua mô phỏng đổi chỗ Swap).
4. **Con trỏ & Mảng:** Bản chất của mảng và toán tử trượt con trỏ `p++`.
5. **Bài tập tổng hợp:** Các bài tập như Trả về 2 kết quả, Tìm Max/Min, Đảo ngược mảng bằng Two Pointers.

---

*Dự án phục vụ mục đích giáo dục, giúp môn học Lập trình C trở nên trực quan và bớt đáng sợ hơn với người mới bắt đầu!*