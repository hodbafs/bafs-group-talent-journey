# BAFS GROUP Talent Journey (2027–2030)
### *Executive Pitch & Interactive Web Experience for Leadership Development*

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Demo-2ea44f?logo=github)](https://YOUR_GITHUB_USERNAME.github.io/bafs-talent-journey-2030/)
[![HTML5](https://img.shields.io/badge/Built%20with-HTML5%20%2F%20CSS3%20%2F%20ES%20Modules-E34F26?logo=html5&logoColor=white)](#)
[![Zero Dependency](https://img.shields.io/badge/Dependencies-Zero%20(Self--contained)-brightgreen)](#)
[![Encoding](https://img.shields.io/badge/Encoding-UTF--8%20(Pristine%20Thai)-blue)](#)

---

## 📌 แนะนำชื่อโปรเจกต์ (Project Naming Options)

สำหรับการนำขึ้น GitHub ขอแนะนำชื่อโปรเจกต์และชื่อ Repository ดังนี้:

| ลำดับ | ชื่อ Repository (GitHub Repo Name) | ชื่อแสดงผล (Project Title) | จุดเด่น |
| :---: | :--- | :--- | :--- |
| **1 (แนะนำ)** | **`bafs-talent-journey-2030`** | **BAFS Talent Journey 2030** | ระบุองค์กร (BAFS), วัตถุประสงค์ (Talent Journey) และวิสัยทัศน์เป้าหมายปี 2030 ชัดเจน ได้ URL สวยงาม: `https://<user>.github.io/bafs-talent-journey-2030/` |
| 2 | `bafs-talent-journey` | BAFS Group Talent Journey | ชื่อทางการแบบย่อ กะทัดรัด เป็นสากล |
| 3 | `bafs-talent-gateway` | BAFS Talent Gateway | เน้นคอนเซ็ปต์ทางเข้าสู่บทบาทใหม่ตามสโลแกน *"Your next chapter starts here"* |
| 4 | `bafs-leadership-journey` | BAFS Leadership Journey 2027-2030 | เน้นกลุ่มเป้าหมายระดับผู้นำ (Ultimate Leaders & Young Talent) |

---

## 🚀 วิธีนำโปรเจกต์ขึ้น GitHub และเปิดใช้งาน GitHub Pages

โฟลเดอร์นี้ได้รับการจัดเตรียมให้เป็น **Ready-to-Deploy Static Site** เรียบร้อยแล้ว (ไฟล์ `index.html` คือตัวเว็บแอปพลิเคชัน Standalone แบบรวมทุกอย่างไว้ในไฟล์เดียว ทั้งโค้ด ฟอนต์ และรูปภาพ Base64)

### 🌟 วิธีที่ 1: อัปโหลดผ่านหน้าเว็บ GitHub (ง่ายที่สุด — ไม่ต้องติดตั้งโปรแกรมใดๆ)

1. เข้าเว็บไซต์ [github.com](https://github.com) และเข้าสู่ระบบ (Sign in)
2. คลิกปุ่ม **New** (หรือเครื่องหมาย `+` มุมขวาบน -> **New repository**)
3. กรอกข้อมูล:
   - **Repository name:** ตั้งชื่อ เช่น `bafs-talent-journey-2030`
   - **Visibility:** เลือก `Public` (หากต้องการใช้ GitHub Pages ฟรี) หรือ `Private` (ขึ้นกับประเภทบัญชี GitHub)
   - ไม่ต้องติ๊กเลือก *Add a README file* (เนื่องจากในโฟลเดอร์นี้มีไฟล์ README อยู่แล้ว)
   - คลิกปุ่ม **Create repository**
4. ในหน้าถัดไป ให้คลิกลิงก์ **"uploading an existing file"**
5. ลากไฟล์และโฟลเดอร์ทั้งหมดในโฟลเดอร์ `bafs-talent-journey-2030` นี้ไปวางในหน้าเว็บ:
   - `index.html`
   - `bafs-talent-journey-standalone.html`
   - `README.md`
   - `.gitignore`
   - โฟลเดอร์ `.github` (ถ้าลากไม่ติด สามารถใช้วิธีที่ 2 หรือ 3 ได้)
6. พิมพ์ Commit message เช่น `Initial commit: BAFS Talent Journey 2030 standalone build` แล้วคลิก **Commit changes**
7. **เปิดใช้งาน GitHub Pages:**
   - ไปที่แท็บ **Settings** ของ Repository
   - เมนูด้านซ้าย เลือก **Pages**
   - ในหัวข้อ **Build and deployment** > **Source**:
     - เลือก **Deploy from a branch**
     - Branch: เลือก `main` (หรือ `master`) และโฟลเดอร์ `/ (root)`
     - คลิก **Save**
8. รอประมาณ 1–2 นาที GitHub จะแสดงแถบสีเขียวพร้อมลิงก์เว็บไซต์ เช่น:
   ```
   Your site is live at https://<username>.github.io/bafs-talent-journey-2030/
   ```

---

### 💻 วิธีที่ 2: ใช้ Git Command Line (สำหรับผู้มี Git ติดตั้งในเครื่อง)

เปิด Terminal / PowerShell แล้วรันคำสั่งดังนี้:

```bash
# 1. เข้าไปที่โฟลเดอร์โปรเจกต์
cd "bafs-talent-journey-2030"

# 2. เริ่มต้น git repository
git init
git branch -M main

# 3. เพิ่มไฟล์ทั้งหมดและ Commit
git add .
git commit -m "feat: initial commit BAFS Talent Journey 2030 standalone"

# 4. เชื่อมโยงกับ GitHub Repository (เปลี่ยน YOUR_USERNAME และ REPO_NAME)
git remote add origin https://github.com/YOUR_USERNAME/bafs-talent-journey-2030.git

# 5. Push ขึ้น GitHub
git push -u origin main
```

จากนั้นไปที่แท็บ **Settings** > **Pages** แล้วเปิดใช้งานตามขั้นตอนด้านบน หรือใช้ GitHub Actions จากไฟล์ `.github/workflows/deploy-pages.yml` ที่แนบไว้

---

### 🖥️ วิธีที่ 3: ใช้ GitHub Desktop

1. เปิดโปรแกรม **GitHub Desktop**
2. ไปที่เมนู **File** > **Add Local Repository...**
3. เลือกโฟลเดอร์ `bafs-talent-journey-2030` แล้วคลิก **Add Repository** (หากมีแจ้งเตือนว่ายังไม่ได้เป็น git repository ให้คลิก *create a repository*)
4. คลิกปุ่ม **Publish repository** เพื่อส่งขึ้นบัญชี GitHub ของคุณ
5. ไปเปิด GitHub Pages ในหน้าเว็บ GitHub Settings ตามปกติ

---

## 📂 โครงสร้างไฟล์ในโฟลเดอร์นี้

```
bafs-talent-journey-2030/
├── index.html                           # ไฟล์เว็บแอปพลิเคชันหลัก (GitHub Pages จะเปิดไฟล์นี้ที่ Root URL)
├── bafs-talent-journey-standalone.html   # ไฟล์ Standalone ฉบับสมบูรณ์ (เข้าผ่าน path ตรงได้)
├── README.md                            # คู่มือโปรเจกต์และการ Deploy
├── .gitignore                           # รายการไฟล์ที่ไม่ต้องนำขึ้น Git
└── .github/
    └── workflows/
        └── deploy-pages.yml             # GitHub Actions สำหรับ Deploy อัตโนมัติเมื่อ push
```

---

## ✨ ไฮไลท์และฟีเจอร์เด่นในระบบ

1. **Self-Contained & Zero Dependency:**
   - รวม HTML, CSS Design Tokens, JavaScript ES Modules และภาพความละเอียดสูง (Base64) ในไฟล์เดียว
   - ไม่ต้องติดตั้ง Node.js หรือรันเว็บเซิร์ฟเวอร์ สามารถดับเบิลคลิกเปิดบนเบราว์เซอร์ได้ทันที
2. **Modern Executive Typography:**
   - ใช้ฟอนต์ **Prompt** ร่วมกับ **Plus Jakarta Sans** คมชัดสวยงามทุกขนาดหน้าจอ
   - ปลด Negative Letter-spacing ทั้งหมด ป้องกันสระและวรรณยุกต์ไทยซ้อนทับกัน
   - มีฟอนต์สำรองระบบ Windows (`Leelawadee UI`, `Segoe UI`, `Tahoma`) ครบถ้วน
3. **Interactive Pitch Shell (ตรวจดูได้ 10 หน้าจอ):**
   - 🌟 **Landing Gateway:** ประตูสู่เส้นทางความก้าวหน้า พร้อม Ambient Canvas Motion
   - 🧭 **Program Overview:** ภาพรวมโปรแกรม 4 ช่วงปี (BUILD -> PROVE -> STRETCH -> PREPARE) และ 3 Gateways
   - 🔐 **Login & Persona Switcher:** เลือกลองเป็น Talent (คุณเมย์ YT / คุณต้น UL), Manager (หัวหน้างาน), หรือ HROD Admin
   - 📊 **Talent Dashboard:** สรุป 4-Year Stepper, สถานีปัจจุบัน, และ Priority Focus Action Cards
   - 🗺️ **My Journey:** แผนผังสถานีการเรียนรู้ตาม Track ที่ได้รับมอบหมาย พร้อมเกณฑ์การผ่าน
   - 📝 **My IDP (Individual Development Plan):** กรอบพัฒนา 70:20:10 ครบ 14 ฟิลด์ พร้อมระบบ Check-in และ Version History
   - 🎯 **Activities & Reflection:** ตารางกิจกรรมและแบบสะท้อนการเรียนรู้
   - 💼 **My Project:** การบริหารโครงการยุทธศาสตร์ (Strategic Project / Leading Safe Ops) และ Milestones
   - 👥 **Manager Review Queue:** คิวตรวจแผนของหัวหน้างาน พร้อมระบบ Privacy Guard (ดูได้เฉพาะ Snapshot ที่ส่งแล้ว)
   - 🛡️ **Admin Control Center:** ศูนย์ควบคุมกลางของ HROD สำหรับติดตามสถานะและบันทึก Audit Logs

---

## 🔒 ความปลอดภัยและความเป็นส่วนตัว (Privacy Notice)

- ไฟล์นี้เป็นฉบับ **Interactive Prototype & Pitch Build** ข้อมูลบุคคลทั้งหมดเป็นเพียงข้อมูลจำลอง (Demo Personas)
- ไม่มีข้อมูลพนักงานจริง ไม่มีรหัสผ่าน หรือ Secret Keys ใดๆ บรรจุอยู่ในโค้ด
- สามารถเผยแพร่บน GitHub Pages ได้อย่างปลอดภัย 100%
