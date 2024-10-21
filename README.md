# Đây là cách tạo file hex tự động từ bàn phím có sẵn được QMK hỗ trợ.
# Cách nạp flash file hex này bạn tham khảo "QMK toolbox" tải QMK toolbox
## Bước 1: vào trang chính qmk configurator
Link: "https://config.qmk.fm/#/crkbd/rev1/LAYOUT_split_3x6_3"
## Bước 2: Tên keyboard được hỗ trợ. Ví dụ: crkbd/rev1 là tên chính thức của keyboard corne
<img src="https://i.imgur.com/UnjYgxk.png"> 
## Bước 3: keymap theo ý theo từng mục được QMK hỗ trợ.
<img src="https://i.imgur.com/37yOZfG.png"> 
## Bước 4: sau khi keymap nhân "compile" để code tạo tự đông.
<img src="https://i.imgur.com/bbXO6Y3.png"> 
<img src="https://i.imgur.com/0WHVFJD.png"> 
## Bước 5: nhấn firmware để tiến hành tải file hex về
<img src="https://i.imgur.com/YO3RjcP.png"> 
## Bước 6: tiến hành bật QMK toolbox để bắt đầu nạp code hex đã tải
## Chú ý: hầu như tất cả các chip ATmega32u4 đều nạp như nhau. Nhấn giữ reset 5 giây và nhả ra nhấn lại 1 cái nữa liền rồi thả ra đợi code đổ là đúng. Nếu không chạy dòng lệnh thì có rất nhiều nguyên nhân từ đường truyền hoặc mạch đang chạm chưa thể nạp. kiểm tra lại các chân
## Lời khuyên: Atmega32u4 nếu chạm do hàn hầu như không hỏng nếu chỉnh lại đúng vấn hoạt động ổn dù có vẻ chạm âm dương. Chip có cầu chì tự phục hồi nên bền, vấn đề chú ý nên đảm bảo hàn không chạm trước khi nghĩ đến việc chip bị hư hỏng.
