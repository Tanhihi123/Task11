Randomness Attack là một cuộc tấn công phổ biến trong các dự án (White list,...) / smart contract cần dùng số ngẫu nhiên. Loại tấn công này khai thác tính dự đoán của các nguồn số ngẫu nhiên được sử dụng trong Smart Contract, cho phép kẻ tấn công thao túng kết quả để trục lợi.

Trong Smart Contract, block hash và block timestamp là hai thông số thường được sử dụng để tạo số ngẫu nhiên. Tuy nhiên, cả hai đều không hoàn toàn phù hợp vì:

Block hash: Mặc dù có tính ngẫu nhiên cao, nhưng kẻ tấn công có thể dự đoán kết quả của block hash bằng cách theo dõi các giao dịch trong mempool.
Block timestamp: Có thể bị thao túng bởi thợ đào bằng cách điều chỉnh thời gian khai thác block. 

  1. Chainlink VRF
  2. API3 