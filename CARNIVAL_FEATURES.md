# 🎪 Carnival Features Documentation

## ภาพรวม (Overview)

Carnival Features คือระบบลูกเล่นแบบสวนสนุกที่เพิ่มความสนุกสนานและความมีชีวิตชีวาให้กับเว็บไซต์ ประกอบด้วยเกมและเอฟเฟกต์ต่างๆ ที่ผู้ใช้สามารถเปิดใช้งานได้ตามต้องการ

## 🎯 ฟีเจอร์ทั้งหมด

### 1. 🎯 Lucky Wheel (วงล้อนำโชค)
- **คำอธิบาย**: วงล้อหมุนที่มี 8 รางวัล พร้อมอนิเมชั่นการหมุนที่สมจริง
- **การใช้งาน**: คลิกปุ่ม "Lucky Wheel" จาก Control Panel
- **คุณสมบัติ**:
  - วงล้อ 8 ช่องพร้อมสีสันสดใส
  - อนิเมชั่นการหมุนแบบ Easing
  - แสดงผลรางวัลพร้อมคอนเฟตตี
  - สามารถหมุนซ้ำได้ไม่จำกัด

### 2. 🎈 Floating Balloons (ลูกโป่งลอย)
- **คำอธิบาย**: ลูกโป่งหลากสีลอยขึ้นจากด้านล่างของหน้าจอ
- **การใช้งาน**: คลิกปุ่ม "Balloons" เพื่อเปิด/ปิด
- **คุณสมบัติ**:
  - ลูกโป่งสุ่มสีและตำแหน่ง
  - คลิกเพื่อทำให้แตกพร้อมมินิคอนเฟตตี
  - สร้างใหม่อย่างต่อเนื่องเมื่อเปิดใช้งาน
  - หายไปอัตโนมัติหลัง 10 วินาที

### 3. 🃏 Memory Game (เกมจับคู่)
- **คำอธิบาย**: เกมจับคู่ไอคอนหัวใจ 8 คู่
- **การใช้งาน**: คลิกปุ่ม "Memory Game"
- **คุณสมบัติ**:
  - การ์ด 16 ใบ (8 คู่)
  - นับจำนวนการเดิน (Moves)
  - นับจำนวนคู่ที่จับได้
  - อนิเมชั่นพลิกการ์ดแบบ 3D
  - เมื่อชนะจะมีดอกไม้ไฟ
  - ปุ่ม Reset เพื่อเล่นใหม่

### 4. ❄️ Snowfall (หิมะตก)
- **คำอธิบาย**: เอฟเฟกต์หิมะตกทั่วหน้าจอ
- **การใช้งาน**: คลิกปุ่ม "Snow" เพื่อเปิด/ปิด
- **คุณสมบัติ**:
  - เกล็ดหิมะขนาดและความโปร่งใสสุ่ม
  - ตกพร้อมหมุนและเคลื่อนที่
  - สร้างใหม่อย่างต่อเนื่องเมื่อเปิดใช้งาน

### 5. 🎆 Fireworks (ดอกไม้ไฟ)
- **คำอธิบาย**: ดอกไม้ไฟระเบิดหลากสี
- **การใช้งาน**: คลิกปุ่ม "Fireworks" เพื่อยิงดอกไม้ไฟ
- **คุณสมบัติ**:
  - ระเบิด 5 ดอกพร้อมกัน
  - ตำแหน่งสุ่มบนหน้าจอ
  - อนุภาคสีสันสดใส 30 อนุภาคต่อดอก
  - เอฟเฟกต์การระเบิดแบบ Radial

### 6. 💖 Love Calculator (เครื่องคำนวณความรัก)
- **คำอธิบาย**: คำนวณเปอร์เซ็นต์ความรักระหว่าง 2 คน
- **การใช้งาน**: คลิกปุ่ม "Love Calculator"
- **คุณสมบัติ**:
  - ใส่ชื่อ 2 คน
  - คำนวณเปอร์เซ็นต์ความรัก (0-100%)
  - แสดงข้อความตามระดับเปอร์เซ็นต์
  - แสดงหัวใจตามคะแนน
  - ดอกไม้ไฟเมื่อได้คะแนนสูง (>70%)

### 7. 💗 Whack-A-Heart (ตีหัวใจ)
- **คำอธิบาย**: เกมตีหัวใจที่โผล่ขึ้นมา คล้าย Whack-A-Mole
- **การใช้งาน**: คลิกปุ่ม "Whack-A-Heart"
- **คุณสมบัติ**:
  - ตาราง 3x3 ช่อง
  - เวลา 30 วินาที
  - คะแนนเพิ่มเมื่อคลิกโดนหัวใจ
  - หัวใจโผล่ขึ้นสุ่ม
  - หัวใจหายไปภายใน 1.5 วินาที

## 🎮 Control Panel

Control Panel เป็นปุ่มควบคุมที่อยู่มุมขวาบน:

- **ไอคอน**: 🎪 (สีชมพู-ม่วง)
- **ตำแหน่ง**: มุมขวาบนของหน้าจอ
- **การใช้งาน**: คลิกเพื่อเปิด/ปิดเมนู
- **ฟีเจอร์**:
  - แสดงปุ่มทั้ง 7 ลูกเล่น
  - อนิเมชั่น Pulse Glow
  - Hover effect แบบ Scale + Rotate

## 📁 ไฟล์

### carnival-features.js
- **ขนาด**: ~18KB
- **คลาสหลัก**: `CarnivalFeatures`
- **ฟังก์ชันหลัก**:
  - `init()` - เริ่มต้นระบบทั้งหมด
  - `createControlPanel()` - สร้างแผงควบคุม
  - `toggleFeature(feature)` - เปิด/ปิดฟีเจอร์
  - `showLuckyWheel()` - แสดงวงล้อ
  - `toggleBalloons()` - เปิด/ปิดลูกโป่ง
  - `showMemoryGame()` - แสดงเกมจับคู่
  - `toggleSnow()` - เปิด/ปิดหิมะ
  - `triggerFireworks()` - ยิงดอกไม้ไฟ
  - `showLoveCalculator()` - แสดงเครื่องคำนวณ
  - `showWhackAHeart()` - แสดงเกมตีหัวใจ

### carnival-features.css
- **ขนาด**: ~15KB
- **ส่วนสำคัญ**:
  - Control Panel styles
  - Modal base styles
  - Lucky Wheel styles
  - Floating Balloons animations
  - Memory Game grid และ card styles
  - Snowfall animations
  - Fireworks particle animations
  - Love Calculator form styles
  - Whack-A-Heart grid styles
  - Responsive styles สำหรับมือถือ

## 🔧 การติดตั้ง

### 1. เพิ่มไฟล์เข้าโปรเจค
วางไฟล์ทั้ง 2 ไฟล์ในโฟลเดอร์เดียวกับ HTML:
```
tee_veeva/
  ├── carnival-features.js
  ├── carnival-features.css
  └── index.html
```

### 2. เพิ่มลิงก์ใน HTML
เพิ่มก่อนปิด `</body>`:
```html
<link rel="stylesheet" href="carnival-features.css">
<script src="carnival-features.js"></script>
```

### 3. ใช้งานได้ทันที!
ระบบจะเริ่มต้นอัตโนมัติเมื่อหน้าเว็บโหลดเสร็จ

## 💡 การใช้งาน

### วิธีเปิดลูกเล่น
1. มองหาปุ่ม 🎪 ที่มุมขวาบน
2. คลิกเพื่อเปิด Control Panel
3. เลือกลูกเล่นที่ต้องการจากเมนู
4. สนุกได้เลย!

### เคล็ดลับ
- **Lucky Wheel**: หมุนบ่อยๆ เพื่อดูข้อความน่ารัก
- **Balloons**: เปิดทิ้งไว้แล้วคลิกตีลูกโป่งที่ลอยขึ้นมา
- **Memory Game**: จำตำแหน่งไอคอนให้ดีเพื่อใช้การเดินน้อยที่สุด
- **Love Calculator**: ลองชื่อต่างๆ เพื่อดูเปอร์เซ็นต์
- **Whack-A-Heart**: คลิกให้เร็วเพื่อคะแนนสูง

## 🎨 การปรับแต่ง

### เปลี่ยนสี
แก้ไขใน `carnival-features.css`:
```css
/* ปรับสีหลักของ Control Panel */
.carnival-panel-toggle {
    background: linear-gradient(135deg, #YOUR_COLOR_1, #YOUR_COLOR_2);
}

/* ปรับสีปุ่ม */
.carnival-btn {
    background: linear-gradient(135deg, #YOUR_COLOR_1, #YOUR_COLOR_2);
}
```

### เปลี่ยนตำแหน่ง Control Panel
แก้ไขใน `carnival-features.css`:
```css
.carnival-control-panel {
    top: 20px;    /* ระยะจากด้านบน */
    right: 20px;  /* ระยะจากด้านขวา */
    /* เปลี่ยนเป็น left: 20px; ถ้าต้องการย้ายไปซ้าย */
}
```

### เพิ่มรางวัลให้ Lucky Wheel
แก้ไขใน `carnival-features.js`:
```javascript
initLuckyWheel() {
    this.wheelPrizes = [
        '💕 You are loved!',
        '⭐ You are special!',
        // เพิ่มรางวัลของคุณที่นี่
        '🎁 Your Custom Prize!'
    ];
}
```

## 📱 Responsive Design

ระบบรองรับหน้าจอทุกขนาด:
- **Desktop**: ขนาดเต็ม
- **Tablet (≤768px)**: ปรับขนาด modal และ grid
- **Mobile (≤480px)**: ย่อขนาดปุ่มและเนื้อหา

## 🔌 API Reference

### Window Object
```javascript
window.carnivalFeatures // CarnivalFeatures instance
```

### วิธีเรียกใช้จาก Console หรือ Code อื่น
```javascript
// ยิงดอกไม้ไฟ
window.carnivalFeatures.triggerFireworks();

// เปิดลูกโป่ง
window.carnivalFeatures.toggleBalloons();

// แสดงวงล้อ
window.carnivalFeatures.showLuckyWheel();
```

## 🐛 Troubleshooting

### ปุ่ม Control Panel ไม่ปรากฏ
- ตรวจสอบว่าเพิ่ม CSS และ JS ถูกต้อง
- ตรวจสอบ Console สำหรับ error
- ตรวจสอบว่า path ของไฟล์ถูกต้อง

### เกมไม่ทำงาน
- รีเฟรชหน้าเว็บ
- ตรวจสอบว่าไม่มี JavaScript error ใน Console
- ตรวจสอบว่า DOM โหลดเสร็จแล้ว

### อนิเมชั่นกระตุก
- ปิดลูกเล่นที่เปิดอยู่หลายอัน
- ลองใช้เบราว์เซอร์อื่น
- ตรวจสอบประสิทธิภาพคอมพิวเตอร์

## 🎯 Performance Tips

1. **ปิดลูกเล่นที่ไม่ใช้**: ลูกโป่งและหิมะใช้ทรัพยากรมาก
2. **ใช้ทีละอย่าง**: ไม่ควรเปิดหลายลูกเล่นพร้อมกัน
3. **ดอกไม้ไฟ**: ใช้แบบ On-demand ไม่ต้องเปิดค้าง

## 🌟 Best Practices

1. **UX**: ให้ผู้ใช้เลือกเปิดเอง ไม่ควรเปิดทุกอย่างพร้อมกัน
2. **Performance**: ตรวจสอบประสิทธิภาพบนมือถือ
3. **Accessibility**: Control Panel อยู่ตำแหน่งที่เข้าถึงง่าย

## 📊 Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ⚠️ IE 11 (ไม่รองรับ)

## 🔄 Updates

### Version 1.0.0 (Current)
- ✅ Lucky Wheel
- ✅ Floating Balloons
- ✅ Memory Game
- ✅ Snowfall
- ✅ Fireworks
- ✅ Love Calculator
- ✅ Whack-A-Heart
- ✅ Control Panel
- ✅ Responsive Design

## 📞 Support

หากพบปัญหาหรือต้องการความช่วยเหลือ:
1. ตรวจสอบ Console สำหรับ errors
2. อ่าน Troubleshooting section
3. ตรวจสอบว่าติดตั้งไฟล์ถูกต้อง

## 🎉 Enjoy!

ระบบ Carnival Features ถูกออกแบบมาเพื่อเพิ่มความสนุกสนานและความมีชีวิตชีวาให้กับเว็บไซต์ของคุณ สนุกกับการใช้งานนะครับ! 🎪✨
