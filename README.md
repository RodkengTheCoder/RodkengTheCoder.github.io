# Learning Labs — GitHub Pages

โฟลเดอร์นี้จัดโครงสร้างให้พร้อมอัปโหลดขึ้น GitHub Pages แล้ว

## เว็บไซต์ที่รวมไว้

- `learning-labs.html` — หน้าเลือกเครื่องมือหลัก
- `hr-prompt-lab/hr-prompt-lab.html` — HR Prompt Lab
- `employee-prompt-lab/employee-prompt-lab-1000-use-cases.html` — Employee Prompt Lab 1,000 Use Cases
- `excel-practice/excel-100-formulas.html` — Excel 100 สูตรใช้บ่อย

## วิธีนำขึ้น GitHub Pages

1. สร้าง Repository ใหม่ใน GitHub
2. อัปโหลด **ไฟล์และโฟลเดอร์ทั้งหมดที่อยู่ภายในโฟลเดอร์นี้** ไปที่รากของ Repository
3. เปิด `Settings` → `Pages`
4. ในหัวข้อ `Build and deployment` เลือก `Deploy from a branch`
5. เลือก Branch `main` และ Folder `/(root)` แล้วกด `Save`
6. รอสักครู่ จากนั้นเปิดลิงก์ที่ GitHub แสดงในหน้า Pages

ไฟล์เว็บจริงใช้ชื่อที่สื่อความหมาย ส่วน `index.html` ในแต่ละตำแหน่งเป็นไฟล์ทางเข้าขนาดเล็กที่จะพาผู้ใช้ไปยังเว็บจริงอัตโนมัติ โครงสร้างนี้จึงยังรองรับ Project Pages เช่น `https://USERNAME.github.io/REPOSITORY/`

## การอัปเดต

แทนที่ไฟล์เว็บที่มีชื่อเฉพาะภายในโฟลเดอร์ย่อยที่ต้องการ จากนั้น Commit การเปลี่ยนแปลงไปยัง Branch `main` โดยคงชื่อไฟล์และโครงสร้างโฟลเดอร์เดิมไว้ ไม่ต้องแก้ไฟล์ `index.html` ที่ใช้สำหรับส่งต่อ
