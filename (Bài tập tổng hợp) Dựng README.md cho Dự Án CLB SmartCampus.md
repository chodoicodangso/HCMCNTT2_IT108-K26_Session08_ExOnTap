\# 🚀 Dự án SmartCampus  
\*\*SmartCampus\*\* là \*ứng dụng di động\* giúp sinh viên PTIT tra cứu lịch học, phòng trống và nhận thông báo từ nhà trường.  
\- Tính năng hoàn thành:  
\- Tra cứu lịch học theo mã sinh viên    
\- Xem danh sách phòng trống theo tòa nhà  
\---  
\#\# Cài đặt  
\`\`\`bash  
git clone https\://github.com/clb-lap-trinh/smartcampus.git  
npm install  
npm start  
\`\`\`  
\#\# Thư viện sử dụng  
| Thư viện | Phiên bản | Mục đích |  
| \--- | \--- | \--- |  
| React Native | 0.74 | Xây giao diện đa nền tảng |  
| Axios | 1.6 | Gọi API lấy dữ liệu lịch học |  
\> \*\*Cảnh báo:\*\* Dự án đang trong giai đoạn phát triển, chưa dùng cho mục đích chính thức.  
\- \[Trang chủ CLB Lập trình\](https\://ptit.edu.vn)  
\- \!\[Logo\](https\://unsplash.com)  
\---  
\#\# Giải thích thuật ngữ: API  
\- \*\*Bản chất:\*\* API là trung gian kết nối ứng dụng SmartCampus và máy chủ trường.  
\- \*\*Cơ chế:\*\* Axios gửi \*\*Request\*\* (yêu cầu mã SV), nhận lại \*\*Response\*\* (dữ liệu lịch học) để hiển thị.  
\- \*\*Vai trò:\*\* Giúp ứng dụng cập nhật dữ liệu thời gian thực.  
\---  
\#\# Sửa lỗi cú pháp bẫy (Phần 4\)  
\- \*\*2 lỗi:\*\* Thiếu dòng phân cách bảng (\`| \--- | \--- |\`) và Task list viết dính liền (\`-\[x\]\`).  
\- \*\*Sửa đúng:\*\*  
| Tính năng | Trạng thái |  
| \--- | \--- |  
| Tra cứu lịch học | Xong |  
| Push notification | Đang làm |  
\- \[x\] Tra cứu lịch học  
\- \[ \] Push notification

