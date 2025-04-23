id : Unique ID for the customer
Gender : Gender of the customer
Age : Age of the customer
Driving_License 0 : Customer does not have DL, 1 : Customer already has DL
Region_Code : Unique code for the region of the customer
Previously_Insured : 1 : Customer already has Vehicle Insurance, 0 : Customer doesn't have Vehicle Insurance
Vehicle_Age : Age of the Vehicle
Vehicle_Damage :1 : Customer got his/her vehicle damaged in the past. 0 : Customer didn't get his/her vehicle damaged in the past.
Annual_Premium : The amount customer needs to pay as premium in the year
PolicySalesChannel : Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.
Vintage : Number of Days, Customer has been associated with the company
Response : 1 : Customer is interested, 0 : Customer is not interested


## Dataset
Dữ liệu được sử dụng từ [Kaggle](https://www.kaggle.com/competitions/qtdt-project-ii/data).

Do dữ liệu lớn, không thể push lên github. Các bạn có thể tải về từ Kaggle và upload lên Google Drive của mình để sử dụng. Hoặc cho vào trong thư mục `data/raw/` của repo này.

CHÚ Ý: Mình đã cho git ignore thư mục `data/raw/` để tránh việc upload dữ liệu lớn lên github. VẬY NÊN ĐỪNG ĐỂ FILE CSV NẰM Ở ĐÂU KHÁC TRÁNH BỊ LỖI KHI PUSH, kể cả việc tạo thư mục con trong `data/raw/`. Ae cũng ĐỪNG COMMIT các file trong thư mục này nhé. Chỉ cần để file ở đó và chạy notebook là được.