# เว็บขอโทษหวานใจ

หน้าเว็บ static พร้อม deploy บน Render

## Deploy

1. นำโฟลเดอร์นี้ขึ้น GitHub repository
2. ที่ Render เลือก **New +** → **Blueprint** แล้วเชื่อม repository
3. Render จะอ่าน `render.yaml` และเผยแพร่ `index.html` เป็น Static Site

หรือเลือก **New +** → **Static Site** แล้วตั้งค่า:
- Build Command: เว้นว่าง
- Publish Directory: `.`

เว็บนี้ไม่ต้องติดตั้งแพ็กเกจหรือมี backend
