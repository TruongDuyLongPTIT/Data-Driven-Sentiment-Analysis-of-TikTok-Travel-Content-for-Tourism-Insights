# 🎯 YÊU CẦU CỤ THỂ:

- Bản đồ Vietnam với các điểm monitoring stations
- Hover/click → Advanced Station Details tooltip
- Data real-time cho current status

# System Architecture
![FINAL5 drawio](https://github.com/user-attachments/assets/56f53e92-5c92-4f5c-ad48-280867a2eacf)




# Set up 
# Estimate Gold Layer size:
- DIM_LOCATION:     20 records
- DIM_DATE:         730 records  
- FACT_AIR_QUALITY: ~175K records/year
- MART_CURRENT:     20 records (real-time)

=> Total: ~176K records (very lightweight!)
