
#ขั้นตอนการ run program
 - 1.เข้าไปใน VMware แล้วติดตั้ง 2 App โดยพิมพ์ commandline ดังนี้
(*ก่อนลงให้พิมพ์คำสั่ง sudo apt update ด้วย*)

![sudo apt update](https://github.com/oNgTZo/CE341_ID2274/assets/144314188/062739da-a322-4b2e-85ba-57532a13665c)

 - Apache2 - sudo apt install apache2
   
![image](https://github.com/oNgTZo/CE341_ID2274/assets/144314188/b19f3946-c9eb-4019-a522-6b218d286f1e)

 - Git - sudo apt install git
   
![image](https://github.com/oNgTZo/CE341_ID2274/assets/144314188/22034d7c-e146-4be1-a002-b903b22225c4)

 - 2.เมื่อติดตั้ง 2 ตัวนี้แล้ว ให้พิมพ์คำสั่ง git clone "https://github.com/oNgTZo/CE341_ID2274.git"
   
![image](https://github.com/oNgTZo/CE341_ID2274/assets/144314188/735ceafa-b362-4810-9ee0-c362f9a436b8)

 - 3.เมื่อ clone เสร็จ พิมพ์คำสั่ง ls เพื่อเช็ค ไฟล์ภายในนั้น หากเจอข้อความขึ้นว่า CE341_ID2274 ให้พิมพ์ cd CE341_ID2274 เพื่อเข้าไปในไฟล์นั้น
   
![image](https://github.com/oNgTZo/CE341_ID2274/assets/144314188/cf1e6aea-3cec-48dc-9b79-8303dad23baf)

 - 4.เมื่อเข้าไปแล้วให้พิมพ์คำสั่ง ls จะเจอไฟล์อยู่ 2 ไฟล์ ( index.html // readme.md ) จากนั้นพิมพ์คำสั่ง cat index.html เพื่ออ่านไฟล์นั้น
   
![image](https://github.com/oNgTZo/CE341_ID2274/assets/144314188/98f921a5-9cf8-4d87-af0a-09eb8fccc895)






#ขั้นตอนการเอา index.html ไปขึ้นในหน้า browser ด้วย Apache
 - 1.พิมพ์คำสั่ง ip address เพื่อดู IP ของเครื่องเรา

![image](https://github.com/oNgTZo/CE341_ID2274/assets/144314188/20e8f29c-6d75-490d-9bed-4336a28faf5b)

 - 2.พิมพ์คำสั่งว่า sudo mv index.html /var/www/html/
 - 3.เมื่อพิมพ์คำสั่งเสร็จแล้ว ให้ไปที่ browser แล้วพิมพ์ IP ของตัวเองลงไปช่อง URL
   
![image](https://github.com/oNgTZo/CE341_ID2274/assets/144314188/5dac6fff-5862-4692-bc78-95ccc481bf3a)





#หน้าตา index.html

![image](https://github.com/oNgTZo/CE341_ID2274/assets/144314188/7f58963d-6588-499c-bce5-b4e4dca8a985)


