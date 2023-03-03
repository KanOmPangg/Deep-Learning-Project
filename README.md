# Deep-Learning-Project
(ในตอนเริ่ม)
- สร้างไฟล์ csv สำหรับเก็บข้อมูลภาพที่ได้จากการแคปเจอร์จากวิดีโอ
- แคปเจอร์ภาพจากวีดิโอตัวอักษรภาษามือใน Folder image
- resize ภาพให้อยู่ในขนาด 28x28 ในแบบ grayscale
- เขียนข้อมูลรูปภาพในไฟล์ csv ที่สร้างขึ้นมา
(หากเคยสร้างไฟล์ csv แล้ว)
- ทำการอ่านข้อมูลภาพจากไฟล์ csv ที่จัดทำด้วยตัวเองและ data set ที่หาจากอินเทอร์เน็ต
- นำข้อมูลทั้ง 2 (ที่จัดทำด้วยตัวเองและ data set ที่หาจากอินเทอร์เน็ต) มา concatenate กัน
- ทำการแสดงผลข้อมูลเพื่อตรวจเช็คข้อมูล
- จัดเตรียมข้อมูล (การทำ normalization การ Reshape)
- การทำ Data Augmentation (rotation_range=10, zoom_range = 0.1, width_shift_range=0.1, height_shift_range=0.1)
- การแสดงข้อมูลเพื่อเปรียบเทียบข้อมูลก่อนทำการ Data Augmentation และข้อมูลหลังทำการ Data Augmentation
- สร้าง Model
- ทำการ Train model
- Plot loss and accuracy graph
