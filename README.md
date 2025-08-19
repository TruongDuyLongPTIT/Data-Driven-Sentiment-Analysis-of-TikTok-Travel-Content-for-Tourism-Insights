## Kịch bản:
- Thiết kế một Data-pipeline để phân tích thị hiếu thị trường du lịch (trong nước)

=> Đưa ra Top địa điểm hot nhất theo views, likes, số comment, sentiment tích cực.

=> Đưa ra nhận xét về chất lượng (dịch vụ, cảnh quan) dựa trên phân tích tỷ lệ comment khen, chê của từng địa điểm du lịch.

=> Thu thập danh sách khách hàng mục tiêu (những người follower kênh tiktok, những người tim/comment tích cực tương ứng với mỗi địa điểm du lịch) để giới thiệu tour du lịch cho họ.

## Mục đích của project này sẽ trả lời các câu hỏi sau:


## 🎯 Yêu cầu cụ thể:

- Phân tích cảm xúc của từng comment (bằng AI) sau đó thống kê để đưa ra nhận định về thị hiếu du lịch trong thời điểm hiện tại
- Thu thập thông tin những người dùng quan tâm đến địa điểm du lịch và nhắn tin giới thiệu cho họ tour du lịch mà họ đang quan tâm
  + Ví dụ: 1 bài đăng về du lịch ở Mù Căng Chải thì những người tim bài đăng và những người có comment tích cực về địa điểm này là tệp khách hàng tiềm     năng => Thu thập danh sách khách hàng này và sau này có thể chạy 1 tool gửi tin nhắn cho họ về tour du lịch Mù Căng Chải mà họ đang quan tâm
- Thu thập danh sách follower để gửi tin nhắn về tour du lịch cho họ.

## 🛰️ System Architecture


![fnal27 drawio](https://github.com/user-attachments/assets/2f8178e3-3fb1-4e0f-877c-5c24a20b359c)





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
