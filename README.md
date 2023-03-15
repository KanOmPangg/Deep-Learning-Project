# Deep-Learning-Project
## รายชื่อสมาชิก
- 6310400975 นายณัฐกฤษฎิ์ พรรณจักร 
- 6310406302 นายธนินท์พัชร์ ศรีขันแก้ว
## ความคืบหน้าครั้งที่ 1
- การเตรียมข้อมูลโดยจัดหาชุดข้อมูลจากทางอินเทอร์เน็ต และสร้างชุดข้อมูลขึ้นเองจากการจับภาพจากในวิดีโอ
- จัดการทำ Data augmentation
## ความคืบหน้าครั้งที่ 2
- การแปลงรูปแบบชุดข้อมูลที่สร้างขึ้นเองให้อยู่ในรูปแบบเดียวกันกับชุดข้อมูลที่จัดหาจากทางอินเทอร์เน็ต
- ทำการรวมชุดข้อมูลที่สร้างขึ้นเองและชุดข้อมูลที่จัดหาจากทางอินเทอร์เน็ต
- ทำการแบ่งข้อมูลเป็น Train set Test set และ Validation set เพื่อนำไปใช้ในการเทรน
- สร้างและเทรน Model
- ตรวจสอบดูผลลัพธ์จากการเทรน
## ความคืบหน้าครั้งที่ 3
- การทำนายผลลัพธ์จากการเทรนด้วยการใช้ชุดข้อมูลเทส และข้อมูลที่สร้างขึ้นมาเอง
## วิธีการใช้งาน
- อัปโหลดคลิปวิดีโอที่ต้องการทำนายภาษามือแบบอเมริกันเข้าไปยัง Folder ที่มีไฟล์ Deep-Learning-Project-15032023 อยู่
- ในส่วน Read new input data to predict ทำการเปลี่ยน path ไปยังวิดีโอที่อัปโหลดเข้ามาและทำการ run cell Convert new input video and write to csv เพื่อสร้างไฟล์ csv ของข้อมูลรูปภาพที่จับได้จากวิดีโอ
- ทำการอ่านไฟล์ csv ที่สร้างขึ้นจาก section ที่แล้วและนำมาทำนาย
