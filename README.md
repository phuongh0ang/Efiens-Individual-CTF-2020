# Efiens-Individual-CTF-2020 - selfModified

## Giới thiệu challenge

Challenge này có 2 cách giải quyết: 
### Cách 1: 
Challenge này chỉ dùng hàm ptrace để ngăn các dân chơi không được debug, nhưng dùng một trình debugger kết hợp với tools như IDA, sửa giá trị của cờ ZF trong thanh ghi [rflags](https://en.wikipedia.org/wiki/FLAGS_register) tại giá trị trả về của hàm ptrace là được. 
Một khi đã vượt qua được debugger, bạn có thể thấy được cách hàm main hoạt động: 
  - Đầu tiên 
