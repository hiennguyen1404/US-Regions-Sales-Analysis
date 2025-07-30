# US Regions Sales Analysis (Phân tích Doanh số Khu vực Hoa Kỳ)
## Tổng quan
Dự án này phân tích dữ liệu giả định doanh số khu vực Hoa Kỳ từ năm 2018 đến 2020, được lấy từ GitHub. Bộ dữ liệu gồm 6 bảng, ỏ bảng phân tích chính có 7.991 dòng và 16 cột, bao gồm thông tin về sản phẩm, hành vi khách hàng, kênh bán hàng và hiệu suất khu vực. Phân tích được thực hiện bằng Microsoft Power BI để đưa ra các đề xuất chiến lược tối ưu hóa kinh doanh, đặc biệt trong bối cảnh xu hướng mua sắm trực tuyến tăng mạnh do đại dịch COVID-19.

## Mục tiêu
- Phân tích theo sản phẩm: Xác định sản phẩm có hiệu suất cao và thấp.
- Phân tích tác động của thời gian giao hàng đến doanh số.
- Phân tích theo yếu tố khách hàng: Đánh giá hành vi và sở thích khách hàng.
- So sánh hiệu suất giữa các kênh bán hàng (Cửa hàng, Trực tuyến, Nhà phân phối, Bán buôn).
- Đề xuất chiến lược tối ưu hóa doanh thu và lợi nhuận.

## Bộ dữ liệu
- **Nguồn**: [GitHub - quantumudit](https://github.com/quantumudit)
- **Kích thước bảng Fact - Sales**: 7.991 dòng, 16 cột (bảng chính)
- **Các bảng dim**: Customers, Products, State_Regions, Locations, Sales_Team
- **Thời gian**: 2018–2020


## Quy trình thực hiện
1. **Tiền xử lý dữ liệu**:
   - Nhập file excel vào Power BI.
   - Transform data, xử lý các giá trị bất thường
   - Thêm cột "Delivery Days", "Sales", "Profit","Category".
2. **Phân tích khám phá (EDA)**:
   - Phân tích theo sản phẩm (Accessories, Rugs, Platters là sản phẩm có doanh số và lợi nhuận dẫn đầu; các nhóm Bedroom Furniture, Bean Bags có doanh số kém hiệu quả).
   - Đánh giá phân bố khách hàng (khoảng 50 khách hàng, và khoảng 42% số lượng khách hàng đem lại doanh số trên trung bình 0.56M USD ).
   - Phân tích doanh số theo kênh bán hàng để cải thiện hiệu quả kinh doanh (In-Store chiến tỷ trọng doanh số cao nhất 41.4%).
   - Xác định xu hướng khu vực (Khu vực Wesr và South là 2 thị trường chủ lực).
3. **Đề xuất chiến lược**:
   - Tập trung vào sản phẩm chủ lực (Accessories, Rugs, Platters).
   - Tăng cường kênh bán hàng cốt lõi.
   - Nhắm đến khách hàng lớn (như Medline, Pure Group) và đề xuất chiến lược cụ thể cho từng khu vực.
   - Đẩy mạnh marketing vào mùa cao điểm (tháng 6, tháng 11).

## Công cụ sử dụng
- **Microsoft Power BI**: Dùng để làm sạch dữ liệu, trực quan hóa và phân tích.
- **Excel**: Lưu trữ và xử lý dữ liệu ban đầu.

## Kết quả
- **Nhóm sản phẩm chủ lực**: Accessories, Rugs và Platters đóng góp lớn vào doanh thu, trong khi Bedroom Furniture và Bean Bags kém hiệu quả.
- **Xu hướng kênh bán hàng**: Doanh số Online tăng mạnh vào năm 2020 cao hơn kênh In-store khoảng 0.1M vào các tháng cao điểm.
- **Thông tin khách hàng**: Trong cả 2 năm, khoảng 40% số lượng khách hàng đem lại doanh thu trên trung bình. Khách hàng giá trị cao là Pure Group, WakeFern, Apotheca, Ltd và khu vực trọng điểm là West và South để tiếp tục mở rộng.
- **Đề xuất chiến lược**:
   - Phát triển đa dạng sản phẩm với các nhóm Electronics, General, Accessories.
   - Tập trung vào các khách hàng trọng điểm.
   - Tăng cường kênh Online
   - Khai thác tập trung vào các mùa cao điểm tháng 6, tháng 11.
   - Mở rộng chuỗi cửa hàng tại West và South.

## Hạn chế
- Bộ dữ liệu là giả định, có thể hạn chế trong thực tế.
- Thiếu thông tin chi tiết về phương thức giao hàng, ảnh hưởng đến phân tích.
