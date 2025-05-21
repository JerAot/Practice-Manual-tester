# Practice-Manual-tester
## 🧪 Manual testing - saucedemo.com
This repository contains manual test cases for [saucedemo.com](https://www.saucedemo.com),  
focused on login, cart, and checkout functionality.

### 🎯 Scope
-🔑Login functionality<br>
-🛒Add/remove from cart<br>
-💵Checkout process<br>
-📝Form validation<br>

#### 📁Folder Structure
manual-test-saucedemo/  
- test cases  
- evidence  
   - SC01_ตรวจสอบการเข้าสู่ระบบ
      - TC001_ระบบสามารถ login ได้เมื่อกรอกข้อมูลที่ถูกต้อง 📎 [Before_login](./evidence/swag-test-evidence/SWAG_evidence/SC01_ตรวจสอบการเข้าสู่ระบบ/TC001_valid_login/B_หน้าlogin.jpg) [After_login](./evidence/swag-test-evidence/SWAG_evidence/SC01_ตรวจสอบการเข้าสู่ระบบ/TC001_valid_login/A_หน้าlogin.jpg)
      - TC002_ระบบไม่สามารถ login เมื่อกรอกข้อมูลที่ผิด 📎  [username_ผิด](./evidence/swag-test-evidence/SWAG_evidence/SC01_ตรวจสอบการเข้าสู่ระบบ/TC002_invalid_login/username_ผิด.jpg)
      - TC003_ระบบไม่สามารถ login เมื่อไม่กรอกข้อมูล
   - SC02_ตรวจสอบการเพิ่มสินค้าลงรถเข็น
      - TC004_เพิ่มสินค้าหนึ่งชิ้นลงในรถเข็น
      - TC005_เพิ่มสินค้าหลายชิ้นในรถเข็น
      - TC006_ลบสินค้าจากรถเข็น
      - TC007_ตรวจสอบจำนวนสินค้าบนไอคอนรถเข็น
      - TC008_ตรวจสอบสินค้าในหน้ารถเข็น
   - SC03_ตรวจสอบการชำระเงิน
      - TC009_ตรวจสอบการกรอกข้อมูล Checkout (ชื่อ,นามสกุล,รหัสไปรษณีย์)
      - TC010_กรอกข้อมูลเฉพาะ Firstname
      - TC011_กรอกข้อมูลเฉพาะ Lastname
      - TC012_กรอกข้อมูลเฉพาะ Zip/Postal Code
      - TC013_กรอกช่อง Firstname, Lastname
      - TC014_กรอกช่อง Firstname, Zip/Postal Code
      - TC015_กรอกช่อง Lastname, Zip/Postal Code

##### Author / Website
Manual test project by Akawat Chartsirilertsakul

