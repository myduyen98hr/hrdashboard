# **📊 TechBank Vietnam \- HR Analytics & Engagement Dashboard Q3/2025**

Báo cáo Quản trị Nhân sự & Điểm Gắn Kết Nhân Viên thời gian thực trực quan hóa dữ liệu nhân sự TechBank Vietnam.

## **🌟 Tính Năng Chính (Key Features)**

1. **Bộ lọc tương tác đa chiều (Interactive Filters):**  
   * Khoảng thời gian (Ngày tuyển dụng / Ngày nghỉ việc).  
   * Phòng ban (Technology, Sales, Operations, Marketing, Finance, HR).  
   * Giới tính (Nam / Nữ).  
   * Cấp bậc công việc (Job Levels 1-6).  
   * Ô tìm kiếm từ khóa nhanh.  
2. **6 Thẻ KPI Điều Hành (Executive Key Metrics):**  
   * **Tổng nhân viên Active** (800 nhân sự).  
   * **Tỷ lệ giới tính** (57.1% Nam / 42.9% Nữ).  
   * **Tỷ lệ nghỉ việc (Turnover Rate)** (11.9% \- Tự động cảnh báo theo ngưỡng rủi ro).  
   * **Số nhân sự tuyển mới (New Hires)** (136 người).  
   * **Số nhân sự nghỉ việc (Leavers)** (95 người).  
   * **Điểm gắn kết trung bình (Engagement Score)** (3.9 / 5.0).  
3. **5 Biểu đồ Phân tích Đa chiều (Chart.js Visualizations):**  
   * **Biểu đồ 1:** Phân bố Active theo Phòng Ban.  
   * **Biểu đồ 2:** Phân bố Active theo Nhóm Tuổi (20-29, 30-39, 40-49, 50-60).  
   * **Biểu đồ 3:** Điểm Engagement trung bình theo từng Phòng Ban.  
   * **Biểu đồ 4:** Phân loại Nghỉ việc Tự nguyện vs Không tự nguyện (Donut Chart).  
   * **Biểu đồ 5:** Top lý do nghỉ việc hàng đầu trong kỳ.  
4. **Tự động Phân tích Key Insights (Executive Summary):**  
   * Tự động cập nhật nội dung đánh giá rủi ro Turnover, cấu trúc nhân sự và điểm gắn kết dựa trên kết quả lọc hiện tại.  
5. **Tính năng Xuất Báo cáo & Đọc File:**  
   * **Upload Dataset.xlsx:** Nhập file Excel dữ liệu thực tế tùy biến để tự động cập nhật Dashboard.  
   * **Xuất PDF:** Xuất toàn bộ Dashboard sang định dạng PDF chất lượng cao.  
   * **Xem Danh sách Bản ghi:** Xem drill-down 100 bản ghi chi tiết phù hợp bộ lọc hiện tại.

## **🚀 Hướng Dẫn Deploy Lên GitHub Pages (Step-by-Step Guide)**

Để đưa ứng dụng này lên mạng hoàn toàn miễn phí qua **GitHub Pages**, bạn làm theo 4 bước đơn giản sau:

### **Bước 1: Tạo Repository mới trên GitHub**

1. Đăng nhập vào tài khoản [GitHub.com](https://github.com).  
2. Nhấn vào biểu tượng dấu **\+** ở góc trên bên phải ![][image1] Chọn **New repository**.  
3. Đặt tên cho Repository, ví dụ: hr-analytics-dashboard.  
4. Để chế độ **Public**.  
5. Nhấn **Create repository**.

### **Bước 2: Tải file lên GitHub**

1. Trong giao diện Repository mới tạo, nhấn **uploading an existing file**.  
2. Kéo thả 2 file:  
   * index.html  
   * README.md  
3. Nhấn nút **Commit changes**.

### **Bước 3: Kích hoạt GitHub Pages**

1. Vào mục **Settings** (Cấu hình) của Repository.  
2. Ở menu bên trái, tìm và nhấn chọn **Pages**.  
3. Tại phần **Build and deployment** ![][image1] **Branch**:  
   * Chọn nhánh **main** (hoặc master).  
   * Thư mục giữ nguyên **/ (root)**.  
4. Nhấn **Save**.

### **Bước 4: Truy cập đường link Dashboard**

* Cho hệ thống GitHub xử lý trong 1 \- 2 phút.  
* F5 lại trang Settings ![][image1] Pages, bạn sẽ nhận được đường link công khai có dạng:  
  https://\<ten-tai-khoan-github\>.github.io/hr-analytics-dashboard/

## **🛠️ Công Nghệ Sử Dụng (Tech Stack)**

* **Frontend Core:** HTML5, CSS3, JavaScript (ES6+).  
* **Styling:** Tailwind CSS (CDN).  
* **Chart Visualizations:** Chart.js 4.4.  
* **Excel Parser:** SheetJS (xlsx.full.min.js).  
* **PDF Export:** html2pdf.js.  
* **Icons & Typography:** FontAwesome 6, Google Font Inter.

## **📄 Bản Quyền & Giấy Phép (License)**

Dự án này được phát triển cho nội bộ TechBank Vietnam © 2026\. Code mã nguồn mở phục vụ mục đích báo cáo và phân tích HR Analytics.

[image1]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABUAAAAZCAYAAADe1WXtAAAAq0lEQVR4XmNgGAWjYGCBsrKyrLy8fLeCggIHuhzZQElJiR9o6GYg1kSXowjIycmVgzC6OMVAUVHRTEZGRgVdHA5ERUV5gN6RJBUDXfsISCcBDedEN5MBGOgVIAWkYqCB/4H4FVB/PLqZZAFxcXFuoIF9WF1JJmABGjgVSDOiS5ALWIDeXQjEHugSZAOgd6WBrtwsJSUlgi5HNjA2NmYFGizEQEWvj4JRQAAAAF1pKp6Jr3nrAAAAAElFTkSuQmCC>