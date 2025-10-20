## Big Data Project Assignment: Stock Price Big Data
Áp dụng các công nghệ Big Data vào việc lưu trữ và xử lý các dữ liệu trên thị trường chứng khoán (cụ thể ở Thị trường Việt Nam).

## Tổng quan:
Mô phỏng hệ thống Big Data sử dụng Hadoop và Spark cho việc lưu trữ và xử lý dữ liệu chứng khoán (từ năm 2005 đến 2025)

## Mô hình hệ thống
Dữ liệu được lưu trữ trên một cụm HDFS bao gồm:
- 1 Namenode để quản lý các datanode
- 4 Datanode để lưu trữ dữ liệu. 
- 1 Spark Master và 4 Spark Workder để lấy dữ liệu và sử lý

## Công nghệ sử dụng:
- Hadoop 3.2.1 
- Spark 3.2.1

Nền tảng Docker được xử dụng để xây dựng hệ thống mô phỏng. 
Các Namenode, datanode, dịch vụ Yarn, Spark Master và Spark Worker được tạo ra sử dụng các Image của nhóm Big Data Europe (bde2020).

## Báo cao chi tiết được viết tại file pdf stock_bigdata_report.pdf