# 🎯 YÊU CẦU CỤ THỂ:

- Bản đồ Vietnam với các điểm monitoring stations
- Hover/click → Advanced Station Details tooltip
- Data real-time cho current status

# System Architecture
![final9 drawio](https://github.com/user-attachments/assets/189b885a-de5c-4960-9ee9-5f19db1f41b2)







# Set up 
# Estimate Gold Layer size:
- DIM_LOCATION:     20 records
- DIM_DATE:         730 records  
- FACT_AIR_QUALITY: ~175K records/year
- MART_CURRENT:     20 records (real-time)

=> Total: ~176K records (very lightweight!)
