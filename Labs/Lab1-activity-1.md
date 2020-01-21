# การทดลองที่ 1 กิจกรรมที่ 1

### ทดลองทำใบงานและส่งงานผ่าน github

## การเชื่อมต่อ visual studio เข้ากับ github

## การส่งงาน

1. fork repository นี้ แล้วสร้าง folder ขึ้นในโฟลเดอร์ย่อยที่่ชื่อ ```Lab submits```

1.1 ตั้งชื่อตามรหัสนักศึกษา ไม่ต้องใส่ชื่อ

1.2 สร้างโปรเจคด้วย visual studio ขึ้นใน folder ตามข้อ 1.1 โดยสร้างเป็นโปรเจคง่ายๆ (.NET framework)

1.3 ตรวจสอบไฟล์ .gitignore ว่าได้ ignore ไฟล์ต่างๆ ที่ visual studio สร้างขึ้น ให้ commit เฉพาะไฟ์ที่นักศึกษาสร้างขึ้นเท่านั้น ดูตัวอย่างไฟล์ gitignore ได้จาก (https://github.com/github/gitignore/blob/master/VisualStudio.gitignore)

1.4 เมื่อทุกอย่างเรียบร้อย ให้ทำการ Pull request โดยใช้ request message ในรูปแบบ ```stu_id:Lab_no_activity_no``` เช่น ```30xxxxxx: Lab2 Activity 1```

## ข้อควรระวัง

1. การทำ pull request โดยมีไฟล์อยู่นอก folder งานของตนเอง จะทำความเสียหายต่อ repository และอาจทำให้เกิด merge conflict จนนักศึกษาคนอื่นไม่สามารถส่งงานได้
