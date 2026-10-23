# PimDee — ฝึกพิมพ์สัมผัสภาษาไทย

เว็บไซต์ฝึกพิมพ์ภาษาไทยแบบ Static ใช้งานได้ผ่าน GitHub Pages โดยไม่ต้องใช้ Backend

## เผยแพร่บน GitHub Pages

1. สร้าง **Public repository** บน GitHub ชื่อ `pimdee` โดยเลือกเพิ่ม README ตอนสร้าง repository ได้
2. อัปโหลด `index.html` และโฟลเดอร์ `.github/workflows/deploy.yml` จากแพ็กเกจนี้ไปยัง branch `main` (ใช้ Git CLI หรือ GitHub web editor สำหรับโฟลเดอร์ที่ซ่อน)
3. ไปที่ **Settings → Pages → Build and deployment → Source → GitHub Actions**
4. ไปที่ **Actions** แล้วตรวจผล workflow `Deploy PimDee to GitHub Pages`
5. เมื่อสำเร็จ URL จะเป็น `https://<username>.github.io/pimdee/`

**สำคัญ:** ยังไม่ใช่เว็บไซต์ที่ขึ้นออนไลน์จนกว่าจะมีการสร้าง repository, อัปโหลดไฟล์ และ workflow สำเร็จ

## ใช้งานในเครื่อง
เปิด `index.html` ด้วย Chrome หรือ Edge

## หมายเหตุ
- ผลการฝึกเก็บผ่าน LocalStorage ในเบราว์เซอร์เครื่องที่ใช้
- ตัวช่วยรูปมือแสดงคำแนะนำการใช้นิ้ว ไม่ได้ตรวจจับนิ้วจริง
- ทดสอบผังแป้นพิมพ์เกษมณีและการกด Shift จริงก่อนนำไปใช้เป็นแบบฝึกมาตรฐาน
