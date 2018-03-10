# **Mô hình TCP/IP**
# Mục Lục
* 
=============================================
<a name=""></a>
# 1. So sánh 2 mô hình OSI và TCP/IP

<img src="https://github.com/Tuantrung/FIL-Tuantrung/blob/master/New%20folder%20(2)/Screenshot_2.png">

# 2. Các kiểu truyền số liệu

<img src="https://github.com/Tuantrung/FIL-Tuantrung/blob/master/New%20folder%20(2)/Screenshot_1.png">

## 2.1. Giao thức UDP(Uses Datagram Protocol)
### - Đặc điểm
 * là giao thức ở tầng transport ở mô hình TCP/IP
 * Kiểu truyền số liệu: Best - effort
 * cho phép ứng dụng truy nhập vào lớp Mạng mà không cần cơ chế kiểm tra lỗi
 * Là giao thức Connectioness
 *  Cung cấp cơ chế kiểm tra lỗi giới hạn
 * Không có cơ chế phục hồi dữ liệu
### - UDP Header

<img src="https://github.com/Tuantrung/FIL-Tuantrung/blob/master/New%20folder%20(2)/Screenshot_3.png">

## 2.2. Giao thức TCP(Transmission Control Protocol)
### - Đặc điểm
 * nằm ở tầng Transport của TCP/IP
 * giúp các ứng dụng có thể truy nhập vào tầng mạng
 * cung cấp cơ chế kiểm tra lỗi
 * cung cấp cơ chế báo nhận tin (Acknowledment of receipt)
 * cung cấp cơ chế phục hồi dữ liệu
### - TCP header
<img src="https://github.com/Tuantrung/FIL-Tuantrung/blob/master/New%20folder%20(2)/Screenshot_4.png">

# 3.Tầng ứng dụng:

Các giao thức:
* Truyền file:
  + FTP
  + TFTP
  + Network File System
* Email:
  + Simple Mail Transfer Protocol (SMTP)
* Truy nhập từ xa
  + Telnet
  + rlogin
* Quản lý mạng
  + Simple Network Management Protocol (SNMP)
* Quản lý tên miền
  + Domain Name System (DNS)
# 4.Nối tầng Transport tới tầng Ứng dụng :
<img src="https://github.com/Tuantrung/FIL-Tuantrung/blob/master/New%20folder%20(2)/Screenshot_5.png">

# 5. 

## 5.1 Three - way handshake 
<img src="https://github.com/Tuantrung/FIL-Tuantrung/blob/master/New%20folder%20(2)/Screenshot_6.png">

## 5.2. Flow Control

<img src="https://github.com/Tuantrung/FIL-Tuantrung/blob/master/New%20folder%20(2)/Screenshot_7.png">



 
