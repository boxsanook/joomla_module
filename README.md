# mod_blackribbon (Joomla 3)

**โมดูลริบบิ้นไว้อาลัย (Black Ribbon)** สำหรับ Joomla 3  
สร้างโดย **Boxs.Me**  
เวอร์ชัน: **1.22**

---

## 🖤 รายละเอียด
`mod_blackribbon` คือโมดูลสำหรับแสดงริบบิ้นไว้อาลัยที่มุมของเว็บไซต์  
สามารถเลือกตำแหน่งได้ 4 มุม ปรับขนาด/ลำดับซ้อน (z-index) ได้  
และมีฟีเจอร์เสริม:
- เปิด/ปิดริบบิ้นได้
- ปรับหน้าเว็บเป็น **ขาวดำทั้งเว็บไซต์**
- แสดง **Popup Image** พร้อมตั้งเวลาแสดง ปิดอัตโนมัติ และจำจำนวนครั้งต่อผู้ใช้

---

## 📦 คุณสมบัติหลัก

| ฟีเจอร์ | รายละเอียด |
|----------|-------------|
| 🎚 Enable Ribbon | เปิด/ปิดการแสดงริบบิ้น |
| 🖼 Ribbon Image URL | กำหนด URL ของภาพริบบิ้น (ถ้าเว้นว่าง ระบบจะเลือกภาพตามมุมให้อัตโนมัติ) |
| 📍 Ribbon Position | เลือกมุมที่ต้องการแสดง (Top-Left / Top-Right / Bottom-Left / Bottom-Right) |
| 📏 Width / Height | ปรับขนาดของริบบิ้น เช่น `90px` หรือ `10vw` |
| 🧱 z-index | กำหนดลำดับการซ้อน (ค่าเริ่มต้น 9999) |
| 🗒 Description | คำอธิบายสำหรับ tooltip และการเข้าถึง (Accessibility) |
| ⚫ Grayscale Mode | บังคับหน้าเว็บเป็นขาวดำได้ทั้งเว็บไซต์ |
| 🖼 Popup Image | แสดงภาพเพิ่มเติมแบบป๊อปอัป ตั้งค่า Delay, Auto Close, จำกัดจำนวนครั้ง ฯลฯ |

---

## 🧩 การเลือกภาพริบบิ้นอัตโนมัติ

หากช่อง **Ribbon Image URL** ว่าง ระบบจะเลือกไฟล์ในตัวอัตโนมัติตามตำแหน่ง:

| Position | ใช้ไฟล์ |
|-----------|----------|
| Top Right | `media/mod_blackribbon/ribbon-top-right.svg` |
| Top Left | `media/mod_blackribbon/ribbon-top-left.svg` |
| Bottom Right | `media/mod_blackribbon/ribbon-bottom-right.svg` |
| Bottom Left | `media/mod_blackribbon/ribbon-bottom-left.svg` |

(คุณสามารถแทนที่ไฟล์เหล่านี้ด้วย SVG ของคุณเองได้ในโฟลเดอร์ `media/mod_blackribbon/`)

---

## ⚙️ การติดตั้ง

1. เข้าสู่ระบบ Joomla Administrator  
2. ไปที่ **Extensions → Manage → Install**  
3. เลือกไฟล์ ZIP ที่ชื่อ `mod_blackribbon_v1.22_j3_flat.zip`  
4. ติดตั้งและเปิดใช้โมดูลใน **Extensions → Module Manager**

---

## 🧠 การตั้งค่า Popup Image

| พารามิเตอร์ | รายละเอียด |
|---------------|-------------|
| Enable Popup | เปิด/ปิดการใช้งาน Popup |
| Popup Image URL | URL ของภาพ (เว้นว่างใช้ placeholder) |
| Delay before show (ms) | หน่วงเวลาก่อนแสดง (หน่วยมิลลิวินาที) |
| Auto close after (ms) | ปิดอัตโนมัติหลังจากเวลาที่กำหนด |
| Max shows per user | จำนวนครั้งสูงสุดที่จะแสดงต่อผู้ใช้แต่ละคน |
| Reset counter after (days) | รีเซ็ตตัวนับหลังจากจำนวนวันที่กำหนด |
| Overlay opacity | ความทึบพื้นหลัง เช่น `0.8` |
| Click URL | ลิงก์เมื่อคลิกที่ภาพ Popup |
| Close button text | ข้อความในปุ่มปิด |

---

## 🔧 โครงสร้างไฟล์

