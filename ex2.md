# Bài 2 : Quản lí quyền truy cập báo cáo tài chính 
## 1. Vấn đề đang gặp phải
Nhân viên gửi link chứa thông tin CV chứa SDT và mức lương kì vọng với quyền edit cho một ứng viên bên ngoài 
## 2. Yêu cầu xử lí : 
bảng thiết kế phân quyền truy cập cho từng đối tượng gồm vỉewer , editor , comments 
quyền viewer bao gồm các thành viên có nhiệm vụ tổng quát lại dữ liệu , editor là những người được cấp quyền chỉnh sửa như mã nguồn ..., comment là những người chỉ có quyền xem và quyền cung cấp thêm ý tưởng nhưng k thay đổi nội dung 

|đối tượng |quyền |
|-|-|
|trưởng phòng nhân sự | edit|
|trưởng bộ phận | comments|
|nhân viên tuyển dụng HR| edit|
|Nhân viên công ty IT| view|
|ứng viên|không có quyền gì |

## 3. 3 bước xử lý khi gửi link với quyền truy cập edit cho ứng viên khác 
b1: thu hồi quyền truy cập
b2: rà soát nội dung chỉnh sửa
b3: phân loại quyền , rút kinh nghiệm , đánh giá thiệt hại và phong án phòng 
