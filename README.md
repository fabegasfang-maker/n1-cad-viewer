# N1 CAD Viewer (DWG / DXF + ภาษาไทย)

เปิดดูไฟล์ .DXF และ .DWG บนเบราว์เซอร์ แปลง DWG ในเครื่องผู้ใช้เอง (LibreDWG WebAssembly) ไม่ต้องมีเซิร์ฟเวอร์

## Deploy บน GitHub Pages
1. อัปโหลดไฟล์ทั้งหมดขึ้น repo (branch `main`)
2. Settings → Pages → Source เลือก **GitHub Actions**
3. รอ Actions รันเสร็จ (แท็บ Actions) เว็บจะอยู่ที่ `https://<ชื่อผู้ใช้>.github.io/<ชื่อ repo>/`
4. ถ้าจะใช้ปุ่ม Google Drive (ล็อกอิน): Firebase Console → Authentication → Settings → Authorized domains → เพิ่ม `<ชื่อผู้ใช้>.github.io`

## รันในเครื่อง
`npm install` แล้ว `npm run dev` (โหมดนี้ใช้ server.ts ซึ่งรองรับโหลด Drive แบบไม่ล็อกอินด้วย)
