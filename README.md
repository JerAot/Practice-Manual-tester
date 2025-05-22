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
- test cases  [(OAT) Swag Labs.xlsx](https://github.com/user-attachments/files/20389897/OAT.Swag.Labs.xlsx)

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
      - TC005_ตรวจสอบสินค้าในหน้ารถเข็น 📎[Before](./evidence/swag-test-evidence/SWAG_evidence/SC02_ตรวจสอบการเพิ่มสินค้าลงรถเข็น/TC005_check_item_page_cart/TC005_cart_page_Before.jpg) 📎[After](./evidence/swag-test-evidence/SWAG_evidence/SC02_ตรวจสอบการเพิ่มสินค้าลงรถเข็น/TC005_check_item_page_cart/TC005_cart_page_After.jpg)
   - SC03_ตรวจสอบการชำระเงิน
      - TC001_ตรวจสอบการกรอกข้อมูล Checkout (ชื่อ,นามสกุล,รหัสไปรษณีย์) 📎[Before](./evidence/swag-test-evidence/SWAG_evidence/SC03_ตรวจสอบการชำระเงิน/TC001_check_before_checkout/TC001_checkout_form_Before.jpg) 📎[After](./evidence/swag-test-evidence/SWAG_evidence/SC03_ตรวจสอบการชำระเงิน/TC001_check_before_checkout/TC001_checkout_form_After.jpg)
      - TC002_กรอกข้อมูลเฉพาะ Firstname 📎[Before](./evidence/swag-test-evidence/SWAG_evidence/SC03_ตรวจสอบการชำระเงิน/TC002_check_only_firstname/TC002_Checkout_firstname_only_Before.jpg) 📎[After](./evidence/swag-test-evidence/SWAG_evidence/SC03_ตรวจสอบการชำระเงิน/TC002_check_only_firstname/TC002_Checkout_firstname_only_After.jpg)
      - TC003_กรอกข้อมูลเฉพาะ Lastname 📎[Before](./evidence/swag-test-evidence/SWAG_evidence/SC03_ตรวจสอบการชำระเงิน/TC003_check_only_lastname/TC003_checkout_lastname_only_Before.jpg) 📎[After](./evidence/swag-test-evidence/SWAG_evidence/SC03_ตรวจสอบการชำระเงิน/TC003_check_only_lastname/TC003_checkout_lastname_only_after.jpg)
      - TC004_กรอกข้อมูลเฉพาะ Zip/Postal Code 📎[Before](./evidence/swag-test-evidence/SWAG_evidence/SC03_ตรวจสอบการชำระเงิน/TC004_check_only_zip/TC004_checkout_Zip_only_before.jpg) 📎[After](./evidence/swag-test-evidence/SWAG_evidence/SC03_ตรวจสอบการชำระเงิน/TC004_check_only_zip/TC004_checkout_Zip_only_After.jpg)
      - TC005_กรอกช่อง Firstname, Lastname 📎[Before](./evidence/swag-test-evidence/SWAG_evidence/SC03_ตรวจสอบการชำระเงิน/TC005_check_firstname&lastname/TC005_checkout_Firstname&Surname_Before.jpg) 📎[After](./evidence/swag-test-evidence/SWAG_evidence/SC03_ตรวจสอบการชำระเงิน/TC005_check_firstname&lastname/TC005_checkout_Firstname&Surname_After.jpg)
      - TC006_กรอกช่อง Firstname, Zip/Postal Code 📎[Before](./evidence/swag-test-evidence/SWAG_evidence/SC03_ตรวจสอบการชำระเงิน/TC006_check_firstname&zip/TC006_checkout_Firstname&Zip_before.jpg) 📎[After](./evidence/swag-test-evidence/SWAG_evidence/SC03_ตรวจสอบการชำระเงิน/TC006_check_firstname&zip/TC006_checkout_Firstname&Zip_after.jpg)
      - TC007_กรอกช่อง Lastname, Zip/Postal Code 📎[Before](./evidence/swag-test-evidence/SWAG_evidence/SC03_ตรวจสอบการชำระเงิน/TC007_lastname&zip/TC007_checkout_Lastname-Zip_before.jpg) 📎[After](./evidence/swag-test-evidence/SWAG_evidence/SC03_ตรวจสอบการชำระเงิน/TC007_lastname&zip/TC007_checkout_Lastname-Zip_after.jpg)

##### Author / Website
Manual test project by Akawat Chartsirilertsakul

