# US-Regions-Sales-Analysis (Phân tích Doanh số Khu vực Hoa Kỳ)
## Tổng quan
Dự án này phân tích dữ liệu doanh số khu vực Hoa Kỳ từ năm 2018 đến 2020, được lấy từ GitHub. Bộ dữ liệu gồm 7.991 dòng và 16 cột, bao gồm thông tin về sản phẩm, hành vi khách hàng, kênh bán hàng và hiệu suất khu vực. Phân tích được thực hiện bằng Microsoft Power BI để đưa ra các đề xuất chiến lược tối ưu hóa kinh doanh, đặc biệt trong bối cảnh xu hướng mua sắm trực tuyến tăng mạnh do đại dịch COVID-19.

## Mục tiêu
- Xác định sản phẩm có hiệu suất cao và thấp.
- Phân tích tác động của thời gian giao hàng đến doanh số.
- Đánh giá hành vi và sở thích khách hàng.
- So sánh hiệu suất giữa các kênh bán hàng (Cửa hàng, Trực tuyến, Nhà phân phối, Bán buôn).
- Đề xuất chiến lược tối ưu hóa doanh thu và lợi nhuận.

## Bộ dữ liệu
- **Nguồn**: [GitHub - quantumudit](https://github.com/quantumudit)
- **Kích thước**: 7.991 dòng, 16 cột
- **Thời gian**: 2018–2020
- **Các đặc trưng chính**: Danh mục sản phẩm, dữ liệu khách hàng, kênh bán hàng, khu vực (Tây, Đông Bắc, Nam), thời gian giao hàng, doanh số và lợi nhuận.

## Phương pháp thực hiện
1. **Chuẩn bị dữ liệu**:
   - Nhập dữ liệu Excel vào Power BI.
   - Làm sạch và chuyển đổi dữ liệu (thêm cột "Delivery Days", "Sales", "Profit").
2. **Phân tích khám phá (EDA)**:
   - Phân tích hiệu suất sản phẩm (ví dụ: Accessories, Rugs, Platters là sản phẩm dẫn đầu; Bedroom Furniture, Bean Bags kém hiệu quả).
   - Đánh giá phân bố khách hàng (50 khách hàng, chủ yếu ở khu vực Tây và Đông Bắc).
   - So sánh kênh bán hàng (Cửa hàng: 41.4%, Trực tuyến: 29.6%).
   - Xác định xu hướng khu vực (Tây và Nam là thị trường tiềm năng).
3. **Đề xuất chiến lược**:
   - Tập trung vào sản phẩm chủ lực (Accessories, Rugs, Platters).
   - Tăng cường kênh trực tuyến do xu hướng tăng trưởng trong đại dịch.
   - Nhắm đến khách hàng lớn (như Medline, Pure Group) và mở rộng ở khu vực Tây/Nam.
   - Đẩy mạnh marketing vào mùa cao điểm (tháng 6, tháng 11).

## Công cụ sử dụng
- **Microsoft Power BI**: Dùng để làm sạch dữ liệu, trực quan hóa và phân tích.
- **Excel**: Lưu trữ và xử lý dữ liệu ban đầu.

## Kết quả
- **Thông tin sản phẩm**: Accessories, Rugs và Platters đóng góp lớn vào doanh thu, trong khi Bedroom Furniture và Bean Bags kém hiệu quả.
- **Xu hướng kênh bán hàng**: Doanh số trực tuyến tăng mạnh vào năm 2020, vượt qua kênh cửa hàng vào các tháng cao điểm.
- **Thông tin khách hàng**: Xác định khách hàng giá trị cao và khu vực tiềm năng để mở rộng.
- **Đề xuất chiến lược**: Mở rộng kênh trực tuyến, đa dạng hóa sản phẩm điện tử, mở thêm cửa hàng ở khu vực Tây và Nam.

## Hạn chế
- Bộ dữ liệu là giả định, có thể hạn chế ứng dụng thực tế.
- Thiếu thông tin chi tiết về phương thức giao hàng, ảnh hưởng đến phân tích.
