# 🎯 YÊU CẦU CỤ THỂ:

- Bản đồ Vietnam với các điểm monitoring stations
- Hover/click → Advanced Station Details tooltip
- Data real-time cho current status

# System Architecture
![final12 drawio](https://github.com/user-attachments/assets/1fe41a35-d7e6-4075-8358-688038607297)

# Set up 
# Estimate Gold Layer size:
- DIM_LOCATION:     20 records
- DIM_DATE:         730 records  
- FACT_AIR_QUALITY: ~175K records/year
- MART_CURRENT:     20 records (real-time)

=> Total: ~176K records (very lightweight!)
