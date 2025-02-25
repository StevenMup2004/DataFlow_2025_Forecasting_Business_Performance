# Dataflow_2025_Forecasting_Business_Performance

## Giới thiệu
Đây là bài thi vòng 1 của cuộc thi DataFlow 2025, tập trung vào dự báo hiệu suất kinh doanh bằng các phương pháp phân tích dữ liệu và mô hình học máy. Dự án nhằm xây dựng một mô hình dự báo doanh thu và doanh số trong tương lai dựa trên dữ liệu lịch sử, giúp doanh nghiệp đưa ra các quyết định chiến lược chính xác hơn.

## Thành viên nhóm
- **Vũ Hải Đăng**
- **Phạm Văn Thanh**
- **Nguyễn Minh Nhật**

## Mục tiêu dự án
- Phân tích dữ liệu lịch sử doanh thu và số lượng bán.
- Trực quan hóa xu hướng doanh thu theo thời gian (năm, tháng, quý).
- Xác định các yếu tố ảnh hưởng đến doanh thu như mùa vụ, khu vực, dòng sản phẩm.
- Xây dựng mô hình LSTM, Transformer, Sarima để dự báo doanh thu.
- Kiểm tra và đánh giá mô hình để tối ưu hóa kết quả dự báo.

## Dữ liệu sử dụng
Dữ liệu bao gồm:
- Lịch sử doanh thu theo thời gian.
- Thông tin về sản phẩm và khu vực bán hàng.
- Các chỉ số kinh tế có thể ảnh hưởng đến hiệu suất kinh doanh.

## Phương pháp tiếp cận
1. **Tiền xử lý dữ liệu**
   - Kiểm tra và làm sạch dữ liệu.
   - Xử lý giá trị bị thiếu hoặc ngoại lệ.
   - Chuẩn hóa dữ liệu bằng Min-Max Scaling.
2. **Phân tích và trực quan hóa dữ liệu**
   - Biểu đồ xu hướng theo năm, tháng, quý.
   - So sánh doanh thu giữa các khu vực và dòng sản phẩm.
3. **Xây dựng mô hình dự báo**
   - Áp dụng mô hình LSTM + Transformer+ Sarima để dự báo chuỗi thời gian.
   - Tích hợp embedding cho chỉ số tháng để cải thiện kết quả.
4. **Đánh giá mô hình**
   - Sử dụng các chỉ số RMSE, MAE , R^2 để đo lường hiệu suất.
   - Kiểm tra độ ổn định và tính hợp lý của kết quả dự báo.

## Cách chạy mô hình
1. File xử lý dữ liệu:
   ```bash
   FORECASTING BUSINESS PERFORMANCE.xlsx
   ```
2. File code:
   ```bash
   FORECASTING BUSINESS PERFORMANCE_TND2004.ipynb
   ```



