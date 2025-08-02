# 🎯 YÊU CẦU CỤ THỂ:

- Bản đồ Vietnam với các điểm monitoring stations
- Hover/click → Advanced Station Details tooltip
- Data real-time cho current status

# System Architecture
![final14 drawio](https://github.com/user-attachments/assets/459a4eb4-0394-4409-a6c2-7c232d066f23)




# Set up 
# Estimate Gold Layer size:
- DIM_LOCATION:     20 records
- DIM_DATE:         730 records  
- FACT_AIR_QUALITY: ~175K records/year
- MART_CURRENT:     20 records (real-time)

=> Total: ~176K records (very lightweight!)
