# ห้องเรียน กำลังพัฒนา(ตนเอง)
สำหรับผู้มีพื้นฐานเขียนโปรแกรมได้นิดหน่อย ยังไม่สามารถสร้างเวปแอปออกมาได้ เมื่อเรียนแล้วสามารถทำเวปแอปออกมาเป็นชิ้นเป็นอันได้

การเรียนการสอนจะเริ่มที่ Play list [นี้ครับ](https://www.youtube.com/watch?v=4CpTCmHZyvw&list=PLWMbTFbTi55OgahSw6T78TTWClgXWpDy9) 

# ตั้งค่าเครื่องสำหรับการพัฒนา 
เช็ตอัปเครื่องสำหรับการพัฒนาโปรแกรม แล้วลองสร้างโปรเจ็ก svelte/sveltekit ด้วย NPM เป็น
ท่ามาตรฐานที่ JavaScript framework ทุกตัวใช้กัน  มีวีดีโอตัวอย่างให้ทำตาม "พัฒนาเกมส์บน Svelte ด้วย Phase" ทำแค่ถึง npm install แล้วเปิด VS Code ขึ้นมาก็ได้ครับ(ทำทั้งหมดมันกินเวลา) ไม่เข้าใจความหมาย ทำต่อไม่ได้ไม่เป็นอะไรครับ ลองทำดูก่อน ถ้าติดอะไรก็คุยกันครับ จะได้ประเมินแต่ละคนว่าทำได้แค่ไหน
- เครื่องสำหรับนักพัฒนาเป็น windows, macOS หรือ Linux ก็ได้ RAM 8GB หรือมากกว่า ควรมี SSD และ มีเนื้อที่เพียงพอกับการทำงาน.
- ติดตั้ง Node.js
- Visual Studio Code
- สำหรับวินโดว์ควรติดตั้ง windows terminal ไว้ใช้งาน
- สร้างโปรเจ็ก Svelte (นาทีที่ 00:19)
- สร้างโปรเจ็ก SvelteKit (นาทีที่ 10:00)

คำสั่งที่ใช้ก็ดูในลิงค์ svelte/sveltekit ได้เลย ยังไม่มีการเขียนโปรแกรมอะไรแค่ก็อปแปะทำตามตัวอย่าง เราจะเรียนรู้การใช้เครื่องมือพื้นฐานกันก่อน ทำถึงแค่ npm install แล้วเปิด VS Code ยังไม่ต้องแก้ไขโค้ด เมื่อทำได้ครบทุกขั้นแจ้งกลับมาครับ 

- https://www.youtube.com/watch?v=Xd8x8ahuIDs
- https://svelte.dev/
- https://kit.svelte.dev/
- https://github.com/microsoft/terminal/releases
- https://nodejs.org/en/download/
- https://code.visualstudio.com/download


# ฝึกพิพม์สัมผัส 1 TH/EN (100%,10 คำต่อนาที)
ที่กำหนดไว้เป็นค่าขั้นต่ำสุดที่ยอมรับได้ จะให้ดีควร 20 คำต่อนาทีขึ้นไปครับ

[Lesson 1](https://www.typingstudy.com/lesson/1/part/1) 
New keys: Home row,New key drill 1,New key drill 2,New key drill 3

[บทเรียน 1](https://www.typingstudy.com/th-thai_kedmanee-3/lesson/1/part/1) 
แป้นใหม่: แป้นเหย้า, เจาะคีย์ใหม่ 1,เจาะคีย์ใหม่ 2

# ฝึกพิพม์สัมผัส 2  TH/EN(100%,ไทย 10 คำต่อนาที,อังกฤษ 11 คำต่อนาที)
ลิงค์เดิมเปลี่ยนไปฝึกบทที่ 2 ทั้งภาษาอังกฤษและไทย จากเวปเดิม จะให้ดีควร 20 คำต่อนาทีขึ้นไปครับ

- แป้นใหม่: ำ และ ร
- เจาะคำพิเศษ
- New keys: e and i
- Extra word drill

# My Web
สร้างเวปเบื้องต้นให้ลองทำตาม[ใบงานนี้](../kookkai-IT-classroom/my-web/)

# Simple Web App with SvelteKit
สร้างเวปด้วย SvelteKit Framework ดูใบสั่งงานได้[ที่นี้](./fruit-list/)
# CRUD สำหรับ Frontend เบื้องต้น
ทำแบบฝึกหัดสองงานตามใบงานใน[หน้านี้ครับ](./fetch/)
- Exercise CRUD
- Exercise Todo List 
# Line Notify
ใช้ Form Action เพื่อรใช้งาน [Line Notify](./line/) แสดงการใช้ API และจะมีโค้ดตัวอย่างให้ศึกษา

## ศึกษาเพิ่มเติม 
- https://www.w3schools.com/js/js_objects.asp
- https://www.w3schools.com/js/js_arrays.asp
- https://www.youtube.com/watch?v=-jzu5YH6OMQ
- https://www.youtube.com/watch?v=HrbQMxZ2Ucs&list=PLWMbTFbTi55ODDrafKItIGpJZl8r3XpyT&index=2

# ส่งข้อมูลผ่าน Form และ การใช้ฐานข้อมูล 
ให้ทำงาน [Form Actions + Prisma ORM](./prisma-actions/) ให้สมบูรณ์(Update และ Delete ได้)

# สร้าง Web App แบบใช้ Web API และฐานข้อมูล 
ให้ทำงาน [Web App + Web API](./web-api/) เพื่อสร้าง Web Application ที่ใช้กับฐานข้อมูล SQLite ถ้านักเรียนได้เรียนหัวข้อ Docker แล้วให้ลองเปลี่ยนมาใช้ดาต้าเบสเซิร์ฟเวอร์จริงๆเช่น MySQL, MSSQL ฯลฯ 


