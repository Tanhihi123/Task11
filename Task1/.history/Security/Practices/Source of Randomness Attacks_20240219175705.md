- Randomness Attack là một cuộc tấn công phổ biến trong các dự án (White list,...) / smart contract cần dùng số ngẫu nhiên . Trong SmartContract có 2 thông số có thể sử dụng để làm số ngẫu nhiên đó là : Block hash , block timestamp .Nhưng vì bản chất của 2 thông số này là thông số của block trên blockchain nên sẽ minh bạch và ai cũng xem được .Vậy thay vào đó , có một số hàm của blockchain khác tương tác khá tốt với EVM : 

  1. Chainlink VRF
  2. API3 