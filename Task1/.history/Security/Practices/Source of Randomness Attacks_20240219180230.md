- Randomness Attack là một cuộc tấn công phổ biến trong các dự án (White list,...) / smart contract cần dùng số ngẫu nhiên. Loại tấn công này khai thác tính dự đoán của các nguồn số ngẫu nhiên được sử dụng trong Smart Contract, cho phép kẻ tấn công thao túng kết quả để trục lợi.

- Trong Smart Contract, block hash và block timestamp là hai thông số thường được sử dụng để tạo số ngẫu nhiên. Tuy nhiên, cả hai đều không hoàn toàn phù hợp vì đó là 2 thông số có thể check được .
- Thay vì sử dụng block hash và block timestamp, có thể sử dụng các hàm của blockchain khác tương tác tốt với EVM như:

1. Chainlink VRF
   - Ưu điểm : 
    Cung cấp nguồn số ngẫu nhiên an toàn và đáng tin cậy.

2. API3
