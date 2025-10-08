# Dream Interpreter - เว็บแอปถอดรหัสความฝัน

เว็บแอปพลิเคชันสำหรับถอดรหัสความฝันด้วย AI ที่รองรับภาษาไทย พร้อมระบบ Pro สำหรับบันทึกประวัติความฝัน

## ✨ คุณสมบัติ

- 🌙 ถอดรหัสความฝันด้วย AI
- 📱 รองรับการใช้งานบนมือถือ
- 🎨 UI สวยงามและใช้งานง่าย
- 💾 ระบบ Pro สำหรับบันทึกประวัติ
- 🌟 ระบบแท็บสำหรับจัดการเนื้อหา
- 🔒 ระบบความปลอดภัย

## 🚀 การ Deploy บน Vercel

### วิธีที่ 1: Deploy ผ่าน Vercel CLI

1. ติดตั้ง Vercel CLI:
```bash
npm i -g vercel
```

2. Login เข้า Vercel:
```bash
vercel login
```

3. Deploy โปรเจค:
```bash
vercel
```

### วิธีที่ 2: Deploy ผ่าน GitHub

1. Push โค้ดขึ้น GitHub repository
2. เข้าไปที่ [vercel.com](https://vercel.com)
3. เชื่อมต่อกับ GitHub account
4. เลือก repository และ deploy

### วิธีที่ 3: Deploy ผ่าน Vercel Dashboard

1. เข้าไปที่ [vercel.com](https://vercel.com)
2. คลิก "New Project"
3. อัปโหลดโฟลเดอร์โปรเจค
4. Vercel จะ deploy อัตโนมัติ

## 📁 โครงสร้างไฟล์

```
dream-interpreter/
├── dream-interpreter.html  # ไฟล์หลักของเว็บแอป
├── favicon.svg            # ไอคอนเว็บไซต์
├── vercel.json           # การตั้งค่า Vercel
├── package.json          # ข้อมูล project
└── README.md            # คู่มือการใช้งาน
```

## ⚙️ การตั้งค่า

ไฟล์ `vercel.json` ได้ถูกตั้งค่าให้:
- ใช้ `dream-interpreter.html` เป็นหน้าแรก
- รองรับ static files
- มี security headers
- จัดการ routing อย่างถูกต้อง

## 🌐 การใช้งาน

หลังจาก deploy แล้ว เว็บไซต์จะพร้อมใช้งานที่ URL ที่ Vercel ให้มา

### คุณสมบัติหลัก:
- **ถอดรหัสความฝัน**: ใส่ความฝันและรับการตีความ
- **ระบบ Pro**: บันทึกและจัดการประวัติความฝัน
- **แท็บ Navigation**: สลับระหว่างการตีความและประวัติ
- **Responsive Design**: ใช้งานได้ทั้งเดสก์ท็อปและมือถือ

## 🔧 การพัฒนาต่อ

สำหรับการพัฒนาในเครื่อง:

```bash
# เริ่ม local server
python -m http.server 8000

# เปิดเบราว์เซอร์ไปที่
http://localhost:8000/dream-interpreter.html
```

## 📝 License

MIT License - ใช้งานได้อย่างอิสระ

---

สร้างด้วย ❤️ สำหรับการถอดรหัสความฝันภาษาไทย