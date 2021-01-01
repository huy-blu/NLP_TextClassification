### Phân loại văn bản Tiếng Việt
- [Yêu cầu hệ thống](#1)
- [Thiết lập môi trường](#2)
- [Tổng quan dữ liệu](#3)
- [Hướng dẫn sử dụng](#4)
  - [Sử dụng mô hình đã huấn luyện](#5)
- [Deploy lên web local](#6)


<div id='1'/>
### Yêu cầu hệ thống
- `Hệ điều hành: *window*`
- `Python: *3.7*`
- `conda 4+`
<div id='2'/>
### Thiết lập môi trường
Tải project 


<div id='3'/>
### Tổng quan về dữ liệu

Dữ liệu của bài toán phân loại văn bản được lưu trong thư mục `data`, gồm hai thư mục con `raw` và `corpus`.

* Dữ liệu thô được lưu trong thư mục `raw` bao gồm hai thư mục con `train` và `test`.
* Dữ liệu huấn luyện và kiểm thử được lưu trong thư mục `data`.

Cấu trúc thư mục

```
.
├── raw
|   ├── Train_Full
|   |   ├── Chinh tri Xa hoi
|   |   ├── Doi song
|   |   ├── Khoa hoc
|   |   └── ...
|   └── Test_Full
|   |   ├── Chinh tri Xa hoi
|   |   ├── Doi song
|   |   ├── Khoa hoc
|   └── └── ...
└── corpus
    ├── train.xlsx
    └── test.xlsx
```
*Ví dụ trong thư mục `Chinh tri Xa hoi`*
```
XH_NLD_ (3672)|text content 3672
XH_NLD_ (3673)|text content 3673
XH_NLD_ (3674)|text content 3674
XH_NLD_ (3675)|text content 3675
```
Tương tự như vậy với 9 thư mục còn lại.

Thư mục `data` chứa dữ liệu huấn luyện và kiểm thử tương tự với 2 file `train.xlsx` và `test.xlsx`.

<div id='6'/>
### Deploy lên web local bằng Flask[]
![][https://github.com/huy-blu/NLP_TextClassification/issues/1#issue-777177402]















