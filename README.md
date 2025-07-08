# ระบบรายงานการพัฒนาตนเองและวิชาชีพ

เว็บแอปพลิเคชันสร้างด้วย Google Apps Script และ HTML เพื่อรายงานผลการพัฒนาตนเองของบุคลากรในรูปแบบ Web App พร้อมฟีเจอร์:
- กรอกแบบฟอร์มกิจกรรม + ลงชื่อ
- ดูข้อมูลแดชบอร์ด
- จัดการข้อมูล (admin)

## วิธีใช้งาน

### 1. ติดตั้ง CLASP
```bash
npm install -g @google/clasp
```

### 2. Login Google
```bash
clasp login
```

### 3. ผูกกับโปรเจกต์ Apps Script
```bash
clasp create --title "Bannanualschool Self-Dev System" --type webapp
```

### 4. Push โค้ดขึ้น Apps Script
```bash
clasp push
```

### 5. Deploy เป็น Web App
เปิดใน [script.google.com](https://script.google.com) แล้ว `Deploy → Manage deployments → New deployment → Web app`

## License
MIT
