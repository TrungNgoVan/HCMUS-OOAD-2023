# `Hệ thống quản lý tiêm chủng OOAD` 
## Đặt vấn đề
Hệ thống tiêm chủng OOAD chính thức đi vào hoạt động từ tháng 9 năm 2023. Hệ thống tiêm chủng OOAD gồm 3 trung tâm đặt trên địa bàn thành phố HCM, nhàm phục vụ nhu cầu tiêm chủng của cả đối tượng người lớn và trẻ em. 

Hiện tại, các qui trình nghiệp vụ bao gồm: 
- Đăng ký tiêm chủng
- Đăng ký đặt mua vác xin
- Tiêm chủng thanh toán
- Theo dõi lic̣h sử tiêm chủng được thực hiện thủ công tại các trung tâm trong hệ thống. 
- Phân công y - bác sĩ tại các trung tâm

Các trung tâm trong hệ thống tiêm chủng có cùng quy trình vận hành, tuy nhiên hiện tại các trung tâm này quản lý dữ liệu về bệnh nhân, y – bác sĩ và nhân viên riêng biệt dẫn đến các khó khăn trong việc điều phối nhân sự và quản lý thông tin bệnh nhân. Với mục tiêu quản lý tập trung tài nguyên, nhân sự, thông tin bệnh nhân và tận dụng các thiết bị tối ưu hóa qui trình của hệ thống tiêm chủng, người đại diện hệ thống tiêm chủng tin học hóa các hoặt động hiện tại.

## Đặc tả các qui trình nghiệp vụ
- Qui trình đăng ký tiêm chủng

    Khi khách hàng có nhu cầu tiêm vác xin cần đến 1 trong các hệ thống để đăng ký. Khi đăng ký cần cung cấp thông tin cá nhân cần thiết: họ và tên, ngày sinh, giới tính, địa chỉ ,... Nếu người tiêm là trẻ em cần cung cấp thông tin người giám hộ.

    Khách hàng sẽ được nhân viên hướng dẫn giới thiệu các gói tiêm hiện có trên hệ thống. Khách hàng cũng có thể chọn một gói hoặc chọn kết hợp nhiều gói tiêm khi đăng ký tiêm chủng. Khách hàng cũng cần đăng ký ngày mong muốn tiêm. Sau khi điền phiếu xong, khách hàng sẽ gửi phiếu đăng ký lại cho nhân viên kiểm tra thông tin và khả năng cung cấp của vác xin trong thời gian mà khách hàng đã chọn (dựa vào kế hoặch mua vác xin của trung tâm). Nếu thông tin sai, thiếu hoặc không có khả năng cung cấp trong thời gian đó nhân viên sẽ trả lại phiếu cho khách hàng điều chỉnh và hướng dẫn khách hàng đặt mua vác xin để được ưu tiên tiêm khi có vác xin. 
    
    Nếu có thể đắp ứng, phiếu đăng ký sẽ được chuyển đến quy triǹh thanh toán, cấp thể khách hàng và xuất hóa đơn thêo yêu cầu của khách hàng (nếu có).

    Mở rộng (nếu có thể):
    - Khách hàng có thể đặt online và nhân viên sẽ xử lý phiếu đặt và liên hệ lặi trong 1 tuàn
    - Khách hàng có thể đăng ký và tiêm ở 2 trung tâm khác nhau
    - Khách hàng có thể thanh toán trực tuyến
    - Nhác lic̣h tiêm khi đến thời hạn

- Qui trình đặt mua Vacxin
    Đối với gói vác xin hoặc vác xin lẻ mà hệ thóng chưa có hoặc đã hết, khách hàng có thể đặt mua theo nhu càu. khách hàng sẽ cung cấp thông tin vác xin muốn đặt (từ danh sách vác xin của hệ thóng hoặc vác xin khác). Nếu khách hàng là thành viên cần cung cấp mã khách hàng. Nếu khách hàng chưa phải là thành viên cần cung cấp thông tin cá nhân để nhân viên có thể liên hệ khi có vác xin. Nhân viên sẽ kiểm tra thông tin và đưa vào danh sách đặt mua. Danh sách đặt mua sẽ được chuyển đến người quản lý để duyệt. Vác xin được duyệt mua sẽ được lập phiếu đặt hàng và gửi đến nhà cung cấp khi đủ số lượng quy điṇh.

    Mở rộng (nếu có thể):
    - Cho phép khách hàng đặt và thanh toán online
    - Hệ thóng tự động lập phiếu đặt khi quản lý đã duyệt đơn


- Qui trình thanh toán
    Nhân viên kế toán tiếp nhận thông tin đăng ký của khách hàng và tiến hành thanh toán. khách hàng có thể thanh toán thông qua 2 hình thức: tiền mặt hoặc thông qua thẻ (chính chủ). Đối với các đơn hàng trên 10 triệu và chưa đến thời điểm tiêm khách hàng có thể chia thành nhiều đợt thanh toán và mỗi đợt thanh toán ít nhắt 25% tổng tiền (thanh toán hết trước thời điểm tiêm). Nhân viên kế toán sẽ xác nhận khách hàng thanh toán theo đợt hoặc thanh toán toàn bộ. Nếu khách hàng chọn thanh toán một lần, nhân viên sẽ lập hóa đơn và tiến hành thanh toán. Nếu khách hàng chọn thanh toán theo đợt, nhân viên sẽ hướng dẫn khách hàng chia đợt thanh toán theo quy định rồi tiến hành thanh toán.


- Qui trình phân công y - bác sĩ
    Các y – bác sĩ, nhân viên được quản lý riêng biệt tại mỗi trung tâm, thông tin gồm: mã nhân viên, họ tên, ngày sinh, vị trí, bàng cấp, địa chỉ, điện thoại, email, lương, trung tâm làm việc. Các nhân viên (y-bác sĩ và các nhân viên khác) được phân công theo ca, gồm 3 ca mỗi ngày (sáng – chiều – tối). Nhân viên sẽ đăng ký lịch rảnh, bộ phận điều hành sẽ xếp lic̣h làm việc dựa trên lịch rảnh và vị trí của nhân viên. Lịch làm việc sẽ được gửi đến các nhân viên vào cuối mỗi tuần trước khi bắt đầu áp dụng.

    Mở rộng (nếu có thể):
    - Hệ thống cho phép nhân viên đăng ký và xem lịch cá nhân




