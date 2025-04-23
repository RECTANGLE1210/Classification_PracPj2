[Kaggle](https://www.kaggle.com/competitions/qtdt-project-ii/data)
[]: # 
[]: # ## Cấu trúc dữ liệu
[]: # - `train.csv`: Dữ liệu huấn luyện (training data).
[]: # - `test.csv`: Dữ liệu kiểm tra (testing data).
[]: # 
[]: # Các trường trong dữ liệu:
[]: # - `id`: ID duy nhất cho khách hàng.
[]: # - `Gender`: Giới tính của khách hàng.
[]: # - `Age`: Tuổi của khách hàng.
[]: # - `Driving_License`: 0 : Khách hàng không có giấy phép lái xe, 1 : Khách hàng đã có giấy phép lái xe.
[]: # - `Region_Code`: Mã vùng duy nhất cho khu vực của khách hàng.
[]: # - `Previously_Insured`: 1 : Khách hàng đã có bảo hiểm xe, 0 : Khách hàng chưa có bảo hiểm xe.
[]: # - `Vehicle_Age`: Tuổi của xe.
[]: # - `Vehicle_Damage`: 1 : Khách hàng đã làm hỏng xe trong quá khứ. 0 : Khách hàng chưa làm hỏng xe trong quá khứ.
[]: # - `Annual_Premium`: Số tiền mà khách hàng cần phải trả mỗi năm.
[]: # - `PolicySalesChannel`: Mã hóa ẩn cho kênh tiếp cận khách hàng (ví dụ: qua điện thoại, qua email, trực tiếp, v.v.).
[]: # - `Vintage`: Số ngày khách hàng đã gắn bó với công ty.
[]: # 
[]: # ## Cấu trúc thư mục
[]: # ```
[]: # ├── data
[]: # │   ├── raw
[]: # │   │   ├── train.csv
[]: # │   │   └── test.csv
[]: # │   └── processed
[]: # │       ├── train.csv
[]: # │       └── test.csv
[]: # ├── notebooks
[]: # │   ├── EDA.ipynb
[]: # │   └── Model.ipynb
[]: # ├── src
[]: # │   ├── data_preprocessing.py
[]: # │   ├── feature_engineering.py
[]: # │   ├── model.py
[]: # │   └── utils.py
[]: # ├── test
[]: # │   ├── test_data_preprocessing.py
[]: # │   ├── test_feature_engineering.py
[]: # │   └── test_model.py
[]: # └── README.md
[]: # ```
[]: # 
[]: # - `data/raw/`: Thư mục chứa dữ liệu thô (raw data).
[]: # - `data/processed/`: Thư mục chứa dữ liệu đã được xử lý (processed data).
[]: # - `src/`: Thư mục chứa mã nguồn chính của dự án.
[]: # - `notebooks/`: Thư mục chứa các notebook để thử nghiệm và chạy code.
[]: # - `test/`: Thư mục chứa các file test cho mã nguồn.