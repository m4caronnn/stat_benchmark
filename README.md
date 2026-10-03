# 🛡️ Guild Damage Character Benchmark App

เว็บแอปพลิเคชันสำหรับเปรียบเทียบและวิเคราะห์สเตตัสตัวละครในกิลด์ (เทียบกับค่าเฉลี่ยของสายอาชีพ)

> 💡 **Pure Static Web App**: ทำงานด้วย HTML5, Tailwind CSS และ JavaScript (Pure Client-Side) 100% **ไม่ต้องใช้ Python, Database หรือ Backend ใดๆ** เหมาะสำหรับนำขึ้น Vercel หรือ GitHub Pages ได้ฟรีทันที!

---

## 🌟 ฟีเจอร์หลัก (Features)

1. **อ่านไฟล์ CSV สถิติกิลด์ภาษาไทย**:
   - รองรับไฟล์ที่เซฟมาจาก Google Sheets (`guild_damage.csv`)
   - ตรวจจับบรรทัดหัวข้อและข้ามอักขระส่วนเกินให้อัตโนมัติ
2. **วิเคราะห์และเปรียบเทียบตัวละคร (Character Benchmark)**:
   - เลือกระบุสายอาชีพ และเลือกชื่อตัวละครที่ต้องการดู
   - แสดงส่วนต่างสเตตัสเทียบกับค่าเฉลี่ยของเพื่อนในสายอาชีพเดียวกัน ($\Delta$ Higher / Lower %)
   - แสดงหลอด Min-Avg-Max Range Bar และ Radar Chart
3. **ระบบแชร์ลิงก์ไม่ต้องพึ่ง Database (Stateless URL Sharing)**:
   - ปุ่ม **"แชร์ลิงก์ตัวละครนี้"** สร้างลิงก์ที่สามารถส่งให้เพื่อนเปิดดูรายงานเฉพาะตัวละครนั้นได้ทันทีบน Vercel / GitHub Pages

---

## 🚀 วิธีการใช้งาน (Deployment)

เพียงแค่นำไฟล์ทั้งหมดในโฟลเดอร์นี้ไปขึ้น **GitHub** แล้วเชื่อมต่อกับ **Vercel** หรือเปิดใช้งาน **GitHub Pages** ก็สามารถใช้งานและกดแชร์ลิงก์ได้ทันที!

---

## 📁 โครงสร้างโปรเจกต์ (Project Files)
- [index.html](file:///C:/Users/M4caron/.gemini/antigravity/scratch/csv-reader-webapp/index.html) - หน้าเว็บ UI หลัก
- [app.js](file:///C:/Users/M4caron/.gemini/antigravity/scratch/csv-reader-webapp/app.js) - ระบบประมวลผล CSV, คำนวณค่าเฉลี่ย และสร้างลิงก์แชร์
- [styles.css](file:///C:/Users/M4caron/.gemini/antigravity/scratch/csv-reader-webapp/styles.css) - สไตล์และการตกแต่ง UI
- [guild_damage.csv](file:///C:/Users/M4caron/.gemini/antigravity/scratch/csv-reader-webapp/guild_damage.csv) - ไฟล์สถิติกิลด์
- [sample_sales_thai.csv](file:///C:/Users/M4caron/.gemini/antigravity/scratch/csv-reader-webapp/sample_sales_thai.csv) - ไฟล์ตัวอย่าง
