# AI Marketer
<img width="646" height="153" alt="image" src="https://github.com/user-attachments/assets/85622b11-f92c-454e-8f68-493a249ecbc7" />

Nền tảng Marketing AI hoàn chỉnh, giúp bạn tự động hóa chiến dịch, sáng tạo nội dung và phân tích dữ liệu với sức mạnh của trí tuệ nhân tạo. Tập trung vào chiến lược, không phải công việc tẻ nhạt.

Được xây dựng trên AI Studio.

<img width="1909" height="989" alt="image" src="https://github.com/user-attachments/assets/25442e7f-3666-4ec6-b59a-6d6d0dd0e147" />


## ✨ Tính năng nổi bật

*   **Sáng tạo nội dung thông minh:** Tạo bài viết marketing chuyên nghiệp chỉ trong vài giây bằng cách sử dụng các công thức đã được chứng minh hiệu quả như AIDA, PAS, FAB,...
*   **Kho Prompt phong phú:** Truy cập một thư viện các prompt được tuyển chọn kỹ lưỡng, phân loại theo từng mục tiêu marketing (SEO, Social Media, Email, Branding,...).
*   **Sử dụng Prompt trực tiếp:** Tương tác trực tiếp với các prompt, điền vào các trường thông tin và nhận kết quả từ AI ngay lập tức mà không cần rời khỏi trang.
*   **Giao diện Hiện đại & Trực quan:** Dashboard được thiết kế gọn gàng, dễ sử dụng, giúp bạn tập trung vào công việc.
*   **Chế độ Sáng & Tối:** Tùy chỉnh giao diện theo sở thích của bạn và làm việc thoải mái trong mọi điều kiện ánh sáng.
*   **Thiết kế Responsive:** Trải nghiệm mượt mà trên mọi thiết bị, từ máy tính để bàn đến điện thoại di động.

## 🚀 Công nghệ sử dụng

*   **Frontend:** Preact, HTM, TypeScript
*   **AI:** Google Gemini API (`@google/genai`)
*   **Styling:** CSS3 (với biến CSS cho Theming)

## 🛠️ Cài đặt và Khởi chạy

Dự án này được thiết kế để chạy trực tiếp trên các nền tảng hỗ trợ phát triển web front-end như AI Studio hoặc bất kỳ máy chủ web tĩnh nào.

1.  **Clone Repository:**
    ```bash
    git clone https://github.com/your-username/ai-marketer.git
    cd ai-marketer
    ```

2.  **Thiết lập API Key:**
    Ứng dụng này sử dụng Google Gemini API. Bạn cần đảm bảo rằng biến môi trường `process.env.API_KEY` đã được cấu hình và có sẵn trong môi trường thực thi của bạn. Ứng dụng sẽ tự động sử dụng key này.

3.  **Chạy ứng dụng:**
    Mở tệp `index.html` bằng một trình duyệt web hoặc sử dụng một máy chủ web cục bộ.
    Ví dụ, với Python:
    ```bash
    # Dành cho Python 3
    python -m http.server
    ```
    Sau đó, truy cập `http://localhost:8000` trên trình duyệt của bạn.

## 📖 Cách sử dụng

1.  **Sáng tạo nội dung:**
    *   Vào mục **Sáng tạo** > **Viết bài marketing**.
    *   Nhập mô tả về sản phẩm hoặc ý tưởng của bạn.
    *   Chọn một công thức viết bài (ví dụ: AIDA).
    *   Nhấn "Tạo Nội Dung" và nhận kết quả từ AI.

2.  **Sử dụng Kho Prompt:**
    *   Vào mục **Kho prompt**.
    *   Duyệt qua các danh mục để tìm prompt phù hợp.
    *   Nhấn **Sao chép** để lấy prompt gốc hoặc nhấn **Sử dụng** để mở cửa sổ tương tác.
    *   Điền thông tin vào các ô trống và nhấn "Tạo Nội Dung".

## 📄 Giấy phép

Dự án này được cấp phép theo các điều khoản của Giấy phép Công cộng GNU phiên bản 3.0. Xem chi tiết tại tệp `LICENSE.md`.

## 🙏 Lời cảm ơn

Nội dung các prompt ban đầu được lấy cảm hứng và tham khảo từ **Sociyell (Instagram)**. Xin chân thành cảm ơn vì đã chia sẻ kiến thức giá trị.
