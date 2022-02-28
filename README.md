# shopee_scraper
บอทเก็บข้อมูลหน้าเวปจาก shopee พร้อมเตรียมข้อมูลสำหรับการนำไปใช้งานในรูปแบบของ Excel บอทตัวนี้เป็นโปรเจคหลักบน Bootcamp ลดงานด้วย Python

## Library และโปรแกรมที่ใช้งาน
1. chrome browser เพื่อใช้งานร่วมกับ Selenium
2. chromedriver ที่มี version ตรงกับ chrome browser บนคอมพิวเตอร์ (https://chromedriver.chromium.org/downloads)
3. Pandas Library
4. Selenium Library
5. BeautifulSoup Library
6. PyautoGui Library

## การใช้งาน
1. สร้างโฟลเดอร์สำหรับเก็บไฟล์ทั้งหมด รวมถึง chromedriver shopee scraper.ipynb จะมีการเรียกถามถึง folder path ที่เก็บตัว chromedriver และโฟลเดอร์ดังกล่าวจะถูกใช้เป็นที่บันทึกผลลัพธ์ของการเก็บข้อมูลจากเวป
2. หลังจากระบุ folder ให้กับโปรแกรม จะมีหน้าต่าง pop up ถามถึง keyword ที่ต้องการใช้เพื่อค้นหาสินค้าบน shopee เมื่อได้รับแล้วบอทจะทำการไปยังหน้าเวป ค้นหาสินค้า และดึงข้อมูลผลการค้นหาหน้าแรก พร้อมชื่อร้านค้าออกมาบันทึกลง Excel
