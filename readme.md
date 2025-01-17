# Customer 360 – Phân Tích Hành Vi Khách Hàng  

## Giới thiệu  
Dự án **Customer 360** được triển khai nhằm cung cấp một góc nhìn toàn diện về hành vi giao dịch của khách hàng trong danh sách chuyển khoản của một tài khoản ngân hàng mẫu. Dự án tập trung phân tích dữ liệu giao dịch dựa trên các yếu tố địa lý, tần suất, giá trị và xu hướng, từ đó đưa ra các đề xuất chiến lược để cải thiện hiệu quả kinh doanh.  

## Mục tiêu dự án  
1. **Phân tích giao dịch theo khu vực**:  
   - Đánh giá các khu vực có lượng giao dịch cao hoặc thấp hơn trung bình.  
   - Hiểu rõ sự khác biệt trong hành vi khách hàng giữa các vùng địa lý.  

2. **Nhận diện xu hướng giao dịch**:  
   - Phân tích tần suất và giá trị giao dịch để xác định các xu hướng nổi bật.  
   - Xác định các yếu tố ảnh hưởng như mức độ phát triển kinh tế, thói quen giao dịch, và mức độ cạnh tranh.  

3. **Đề xuất hành động chiến lược**:  
   - Cung cấp các khuyến nghị cụ thể để cải thiện hiệu quả hoạt động tại các khu vực giao dịch thấp.  
   - Định hướng các chiến dịch marketing và tối ưu hóa mạng lưới chi nhánh.  

## Ý nghĩa thực tiễn  
Dự án không chỉ dừng lại ở việc phân tích dữ liệu mà còn đề xuất các giải pháp thực tế, giúp doanh nghiệp:  
- Tăng cường sự hiện diện tại các khu vực tiềm năng.  
- Điều chỉnh dịch vụ và sản phẩm để đáp ứng nhu cầu địa phương.  
- Nâng cao hiệu quả kinh doanh thông qua các quyết định dựa trên dữ liệu.  

## Bảng mô tả Data Mẫu  
Dưới đây là bảng mô tả các cột trong bộ dữ liệu mẫu:

| **Tên Cột**              | **Ý Nghĩa Cột**                                                                 |
|--------------------------|---------------------------------------------------------------------------------|
| **TT**                   | Thứ tự giao dịch (mã định danh duy nhất cho mỗi giao dịch).                    |
| **Mã giao dịch**         | Mã số giao dịch (có thể là mã định danh của ngân hàng hoặc hệ thống).         |
| **Ngân hàng**            | Tên ngân hàng thực hiện giao dịch.                                              |
| **Số tài khoản**         | Số tài khoản của khách hàng thực hiện giao dịch.                               |
| **Số tài khoản ảo**      | Số tài khoản ảo (nếu có) liên quan đến giao dịch (đối với các tài khoản ảo).  |
| **Tên dòng tiền**        | Tên dòng tiền, có thể là loại giao dịch (ví dụ: chuyển khoản, nạp tiền, rút tiền).|
| **Số tiền**              | Giá trị số tiền giao dịch.                                                      |
| **Ngày giao dịch**       | Ngày tháng năm thực hiện giao dịch.                                             |
| **Nội dung chuyển khoản**| Nội dung ghi chú hoặc lý do của giao dịch (nếu có).                            |
| **Cơ sở/Cửa hàng**       | Tên cơ sở hoặc cửa hàng nơi giao dịch diễn ra (có thể là chi nhánh ngân hàng hoặc điểm bán).|
