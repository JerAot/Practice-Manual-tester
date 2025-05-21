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
      - TC001_ระบบสามารถ login ได้เมื่อกรอกข้อมูลที่ถูกต้อง
      - TC002_ระบบไม่สามารถ login เมื่อกรอกข้อมูลที่ผิด
      - TC003_ระบบไม่สามารถ login เมื่อไม่กรอกข้อมูล
   - SC02_ตรวจสอบการเพิ่มสินค้าลงรถเข็น
      - TC004	เพิ่มสินค้าหนึ่งชิ้นลงในรถเข็น
      - TC005	เพิ่มสินค้าหลายชิ้นในรถเข็น
      - TC006	ลบสินค้าจากรถเข็น
      - TC007	ตรวจสอบจำนวนสินค้าบนไอคอนรถเข็น
      - TC008	ตรวจสอบสินค้าในหน้ารถเข็น
   - SC03_ตรวจสอบการชำระเงิน
      - TC009	ตรวจสอบการกรอกข้อมูล Checkout (ชื่อ,นามสกุล,รหัสไปรษณีย์)
      - TC010	กรอกข้อมูลเฉพาะ Firstname
      - TC011	กรอกข้อมูลเฉพาะ Lastname
      - TC012	กรอกข้อมูลเฉพาะ Zip/Postal Code
      - TC013	กรอกช่อง Firstname, Lastname
      - TC014	กรอกช่อง Firstname, Zip/Postal Code
      - TC015	กรอกช่อง Lastname, Zip/Postal Code

##### Author / Website

