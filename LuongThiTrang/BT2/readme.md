Bài Toán: Kiểm Tra Năm Nhuận

1. Thuật Toán
Điều kiện: Năm nhuận là năm chia hết cho 4 và không chia hết cho 100
hoặc chia hết cho 400

2. Hướng giải quyết
- Hàm inputYear(int year): nhập vào một năm bất kì.
- Hàm checkYear(int year): Kiểm tra năm đã nhập
+ Nếu là năm nhuận: trả về kết quả Right leap year.
+ Nếu không phải năm nhuận: trả về kết quả Not right leap year.
+ Nếu không phải là một năm hợp lệ: trả về kết quả Invalid year.

3. Tiêu chuẩn MDCD
year%400 | year%4 | year%100 | Kết quả T | T | F | T T | T | T | T F | T | F | T F | T | T | F