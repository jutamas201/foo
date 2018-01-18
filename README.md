#Homework
อธิบายคำสั่งต่างๆ
mkdir เป็นคำสั่งที่ใช้ในการสร้าง directory
cd เป็นคำสั่งที่ใช้ในการย้าย directory
echo "# Homework" >> README.md echo เป็นคำสั่งที่ใช้ในการแสดงผลในข้อนี้จะแสดงข้อความ # Homework ในไฟล์ README.md
คำสั่ง git init เอาไว้เพื่อสร้าง git repository เปล่าๆขึ้นมา โดย Git จะทำการสร้างโฟลเดอร์ .git ขึ้นมาภายในโปรเจ็คของเรา
git add README.md git add เป็นคำสั่งที่ใช้ในการติดตามการเปลี่ยนแปลงของไฟล์ ในข้อนี้จะติดตามการเปลี่ยนแปลงของไฟล์ README.md
git status ในการตรวจสอบสถานะ
git config --global user.email "email ของเรา" เป็นคำสั่งที่ใช้ในการกำหนดอีเมลล์ผู้ใช้
git config --global user.name "username ของเรา" เป็นคำสั่งที่ใช้ในการกำหนดชื่อผู้ใช้
git commit -m "first commit" git commit -m เป็นคำสั่งที่ใช้ในการยืนยันบันทึก การเปลี่ยนแปลง ต่างๆที่เกิดขึ้นโดยจะมีการอธิบายการเปลี่ยนแปลงไว้ใน double quote ในข้อนี้จะบันทึกการเปลี่ยนแปลงและอธิบายการเปลี่ยนแปลงว่าเป็น first commit
git remote add origin https://github.com/Kuk5835512071/Homework.git เมื่อยังไม่มี remote repository ให้เพิ่มเข้าไปโดยบอกที่อยู่ url ของ repository
git remote -v แสดง remote repository
git push -u origin master เป็นคำสั่งที่ใช้ในการส่งโค๊ดจากเครื่อง local ไปที่ Github
