# 🚀 Landing Page - TechFlow

หน้า Landing Page ที่สวยงามและทันสมัยพร้อมระบบสมัครสมาชิกและเข้าสู่ระบบ

## ✨ คุณสมบัติหลัก

### 🎨 การออกแบบ
- **Modern UI/UX**: ออกแบบสวยงามด้วย Gradient และ Animation
- **Responsive Design**: รองรับทุกขนาดหน้าจอ (Desktop, Tablet, Mobile)
- **Thai Font**: ใช้ฟอนต์ Kanit สำหรับการแสดงผลภาษาไทยที่สวยงาม
- **Smooth Animations**: การเคลื่อนไหวที่นุ่มนวลและสวยงาม

### 🔐 ระบบ Authentication
- **Modal Login**: ฟอร์มเข้าสู่ระบบแบบ Pop-up
- **Modal Signup**: ฟอร์มสมัครสมาชิกแบบ Pop-up
- **Form Validation**: ตรวจสอบข้อมูลที่กรอกอย่างละเอียด
- **Loading States**: แสดงสถานะการโหลดขณะประมวลผล

### 🌟 ส่วนประกอบหลัก
1. **Navigation Bar**: เมนูนำทางที่มีเอฟเฟกต์เมื่อเลื่อนหน้า
2. **Hero Section**: ส่วนหลักที่โดดเด่นพร้อม CTA Buttons
3. **Features Section**: แสดงคุณสมบัติของบริการ
4. **CTA Section**: เรียกใช้งานสำหรับการสมัครสมาชิก
5. **Footer**: ข้อมูลติดต่อและลิงก์ต่างๆ

### 🎯 Interactive Elements
- **Floating Cards**: การ์ดลอยในส่วน Hero
- **Hover Effects**: เอฟเฟกต์เมื่อ Hover บนปุ่มและการ์ด
- **Scroll Animations**: Animation เมื่อเลื่อนหน้า
- **Parallax Effect**: เอฟเฟกต์ Parallax ในส่วน Hero
- **Counter Animation**: ตัวเลขที่นับขึ้นเมื่อเลื่อนมาเจอ

## 🚀 การใช้งาน

### เปิดหน้าเว็บ
1. เปิดไฟล์ `index.html` ในเบราว์เซอร์
2. หน้าเว็บจะโหลดพร้อมแอนิเมชันเริ่มต้น

### การสมัครสมาชิก
1. คลิกปุ่ม "สมัครสมาชิก" ในเมนูหรือปุ่ม "เริ่มต้นฟรี"
2. กรอกข้อมูล:
   - ชื่อ-นามสกุล
   - อีเมล
   - รหัสผ่าน (อย่างน้อย 6 ตัวอักษร)
   - ยืนยันรหัสผ่าน
3. ติ๊กยอมรับเงื่อนไข
4. คลิก "สมัครสมาชิก"

### การเข้าสู่ระบบ
1. คลิกปุ่ม "เข้าสู่ระบบ" ในเมนู
2. กรอกอีเมลและรหัสผ่าน
3. เลือก "จดจำฉันไว้" (ถ้าต้องการ)
4. คลิก "เข้าสู่ระบบ"

## 📱 การรองรับอุปกรณ์

### Desktop (1200px+)
- แสดงผลเต็มรูปแบบพร้อมทุกเอฟเฟกต์
- Layout แบบ 2 คอลัมน์ในส่วน Hero

### Tablet (768px - 1024px)
- Layout ปรับเป็น 1 คอลัมน์
- ปรับขนาดฟอนต์และระยะห่าง

### Mobile (480px - 768px)
- เมนูแบบ Hamburger
- ปุ่มเรียงแนวตั้ง
- ซ่อนการ์ดลอยที่ซับซ้อน

### Small Mobile (< 480px)
- ปรับขนาดทุกส่วนให้เหมาะกับหน้าจอเล็ก
- Modal เต็มหน้าจอเกือบหมด

## 🎨 สีและธีม

### Color Palette
- **Primary**: `#667eea` (สีน้ำเงินอมม่วง)
- **Secondary**: `#764ba2` (สีม่วง)
- **Accent**: `#f093fb` (สีชมพู)
- **Background**: `#ffffff` (สีขาว)
- **Text**: `#2d3748` (สีเทาเข้ม)

### Gradients
- **Primary Gradient**: `linear-gradient(135deg, #667eea 0%, #764ba2 100%)`
- **Secondary Gradient**: `linear-gradient(135deg, #f093fb 0%, #f5576c 100%)`

## 🔧 การปรับแต่ง

### เปลี่ยนสี
แก้ไขในไฟล์ `styles.css` ที่ส่วน `:root` variables:
```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    /* ... */
}
```

### เปลี่ยนข้อความ
แก้ไขในไฟล์ `index.html` ตามต้องการ

### เพิ่มฟีเจอร์
แก้ไขในไฟล์ `script.js` เพื่อเพิ่มฟังก์ชันใหม่

## 🌐 ไฟล์ที่สำคัญ

- `index.html` - โครงสร้างหน้าเว็บหลัก
- `styles.css` - การจัดรูปแบบและ Animation
- `script.js` - ฟังก์ชันการทำงานและ Interactive
- `README.md` - คู่มือการใช้งาน

## 📦 Dependencies

### External CDN
- **Font Awesome 6.0.0** - ไอคอน
- **Google Fonts (Kanit)** - ฟอนต์ภาษาไทย

### Browser Support
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 🚀 Tips การใช้งาน

1. **ทดสอบในหลายขนาดหน้าจอ** เพื่อให้แน่ใจว่า Responsive
2. **ใช้ Developer Tools** เพื่อดูการทำงานของ Animation
3. **ปรับ Throttle ของ Scroll Event** ถ้าต้องการประสิทธิภาพดีขึ้น
4. **เพิ่ม Loading State** สำหรับ API จริง

## 📈 ฟีเจอร์ที่จะเพิ่มในอนาคต

- [ ] Dark Mode Support
- [ ] Multi-language Support
- [ ] PWA Features
- [ ] Real API Integration
- [ ] Google/Facebook Login
- [ ] Email Verification
- [ ] Forgot Password Feature

---

✨ **สร้างด้วยความใส่ใจ** - TechFlow Team