## Mục đích của project này sẽ trả lời các câu hỏi sau:

## 🎯 Yêu cầu cụ thể;

- Bản đồ Vietnam với các điểm monitoring stations
- Hover/click → Advanced Station Details tooltip
- Data real-time cho current status

## 🛰️ System Architecture

![final25 drawio](https://github.com/user-attachments/assets/9e094684-a290-4b81-8c4a-93fe2b955d82)





## ⚙️ Cài đặt môi trường:
1. Cài đặt Miniconda để quản lý môi trường Python
  - Cài đặt playwright (thư viện python phục vụ cho crawl)
  - Cài đặt craw4ai để crawl web data tự động bằng AI (https://github.com/unclecode/crawl4ai)
2. Cài đặt thư viện Transformers để sử dụng model phoBert để phân tích cảm xúc comment
## ⚡ Estimate Gold Layer size:
- DIM_LOCATION:     20 records
- DIM_DATE:         730 records  
- FACT_AIR_QUALITY: ~175K records/year
- MART_CURRENT:     20 records (real-time)

=> Total: ~176K records (very lightweight!)

## 📟 Programming languages
- Python for: Data Source -> Data Ingestion and Parsing -> Database | Airflow | Great expectation
- Scala for: Other

## 🚀 Skills
- 💻 Python, Scala, Java
- 📊 Data Engineering, ETL, Data Warehouse
- ☁️ AWS, Azure, GCP
- 🔒 Security Background

## Nếu anh chị
