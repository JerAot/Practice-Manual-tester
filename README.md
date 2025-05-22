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
      - TC001_ระบบสามารถ login ได้เมื่อกรอกข้อมูลที่ถูกต้อง 📎 [Before_login](./evidence/swag-test-evidence/SWAG_evidence/SC01_ตรวจสอบการเข้าสู่ระบบ/TC001_valid_login/B_หน้าlogin.jpg) 📎 [After_login](./evidence/swag-test-evidence/SWAG_evidence/SC01_ตรวจสอบการเข้าสู่ระบบ/TC001_valid_login/A_หน้าlogin.jpg)
      - TC002_ระบบไม่สามารถ login เมื่อกรอกข้อมูลที่ผิด 📎[username_ผิด](./evidence/swag-test-evidence/SWAG_evidence/SC01_ตรวจสอบการเข้าสู่ระบบ/TC002_invalid_login/username_ผิด.jpg) 📎[Password_ผิด](./evidence/swag-test-evidence/SWAG_evidence/SC01_ตรวจสอบการเข้าสู่ระบบ/TC002_invalid_login/Password_ผิด.jpg) 📎[Username & Password ผิด](./evidence/swag-test-evidence/SWAG_evidence/SC01_ตรวจสอบการเข้าสู่ระบบ/TC002_invalid_login/Username_Password_ผิด.jpg) 
      - TC003_ระบบไม่สามารถ login เมื่อไม่กรอกข้อมูล 📎[No_username](./evidence/swag-test-evidence/SWAG_evidence/SC01_ตรวจสอบการเข้าสู่ระบบ/TC003_empty_login/No_username.jpg) 📎[No_password](./evidence/swag-test-evidence/SWAG_evidence/SC01_ตรวจสอบการเข้าสู่ระบบ/TC003_empty_login/No_password.jpg) 📎[No_username&password](./evidence/swag-test-evidence/SWAG_evidence/SC01_ตรวจสอบการเข้าสู่ระบบ/TC003_empty_login/No_Username_password.jpg)
   - SC02_ตรวจสอบการเพิ่มสินค้าลงรถเข็น 
      - TC001_เพิ่มสินค้าหนึ่งชิ้นลงในรถเข็น 📎[Before](./evidence/swag-test-evidence/SWAG_evidence/SC02_ตรวจสอบการเพิ่มสินค้าลงรถเข็น/TC001_add_item_cart/TC001_Before_add_to_cart.jpg) 📎[After](./evidence/swag-test-evidence/SWAG_evidence/SC02_ตรวจสอบการเพิ่มสินค้าลงรถเข็น/TC001_add_item_cart/TC001_After_add_to_cart.jpg)
      - TC002_เพิ่มสินค้าหลายชิ้นในรถเข็น 📎[Before](./evidence/swag-test-evidence/SWAG_evidence/SC02_ตรวจสอบการเพิ่มสินค้าลงรถเข็น/TC002_add_items_cart/TC002_Add_to_Cart_Before.jpg) 📎[After](evidence/swag-test-evidence/SWAG_evidence/SC02_ตรวจสอบการเพิ่มสินค้าลงรถเข็น/TC002_add_items_cart/TC002_Add_to_Cart_After.jpg)
      - TC003_ลบสินค้าจากรถเข็น 📎[Before](./evidence/swag-test-evidence/SWAG_evidence/SC02_ตรวจสอบการเพิ่มสินค้าลงรถเข็น/TC003_delete_item_cart/TC003_delete_from_cart_Before.jpg) 📎[After](./evidence/swag-test-evidence/SWAG_evidence/SC02_ตรวจสอบการเพิ่มสินค้าลงรถเข็น/TC003_delete_item_cart/TC003_delete_from_cart_After.jpg)
      - TC004_ตรวจสอบจำนวนสินค้าบนไอคอนรถเข็น 📎[Before](./evidence/swag-test-evidence/SWAG_evidence/SC02_ตรวจสอบการเพิ่มสินค้าลงรถเข็น/TC004_check_icon_cart/TC004_cart_icon_Before.jpg) 📎[After](./evidence/swag-test-evidence/SWAG_evidence/SC02_ตรวจสอบการเพิ่มสินค้าลงรถเข็น/TC004_check_icon_cart/TC004_cart_icon_After.jpg)
      - TC005_ตรวจสอบสินค้าในหน้ารถเข็น
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

