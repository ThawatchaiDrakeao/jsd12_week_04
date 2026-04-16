### 📝 โครงสร้าง HTML Card
โค้ดนี้ประกอบด้วยส่วนหัวและส่วนเนื้อหา โดยใช้คลาส CSS แบบสถาปัตยกรรม BEM:

* **Header**: คลาส `card__title` ใช้แสดงชื่อหัวข้อ
* **Content**: คลาส `card__content` พร้อม Modifier `--light` สำหรับปรับการแสดงผลเนื้อหาให้ดูเบาหรือสว่างขึ้น
* **Status**: โครงสร้างปัจจุบันยังเป็น Empty State (ไม่มีเนื้อหาข้างใน content)

**Code Snippet:**
```html
<div class="card__title">
    title
    <div class="card__content card__content--light">
        </div>
</div>