Dùng USB CAN Của MJBOT cấu trúc send lệnh để SteadyWin nhận:

can send id_des data f

id_des là ID của CAN nhận
data là số hex cần truyền : vd:FFFFFFFFFFFFFFFD để OFF motor FFFFFFFFFFFFFFFC để On motor
f là option để cho USB biết khongo phải chuẩn của fdcanusb(MJBOTS)