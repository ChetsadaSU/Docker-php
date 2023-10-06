1. ใช้คำสั่ง git clone https://github.com/ChetsadaSU/Docker-php.git
2. จาก clone เสร็จให้ทำการบิว โดยใช้คำสั่ง
3. docker build . -t test-frung
4. ต่อไปรัน โดยใช้คำสั่ง
5. docker run -dit -p 8080:80  --name test-web-chetsada test-frung
6. เสร็จแล้ว เปิดเว็บด้วย http://localhost:8080
