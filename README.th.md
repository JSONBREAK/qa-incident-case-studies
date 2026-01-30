---

# 📦 QA Incident Case Studies (Personal Learning Repo)

Repository นี้ถูกสร้างขึ้นเพื่อ  

**ฝึกคิด วิเคราะห์ และจดบันทึกการจัดการ incident ในมุมมองของ QA**
<br/>โดยเน้นการทำงานแบบ end-to-end ตั้งแต่พบปัญหา → วิเคราะห์ → ป้องกันไม่ให้เกิดซ้ำ

> 🎯 โฟกัสหลักคือ **การคิดและการตัดสินใจของ QA ในสถานการณ์จริง**
ไม่ใช่ repo สำหรับสอนพื้นฐานหรือ tutorial

---

## 🎯 เป้าหมายของ Repository นี้

Repo นี้ถูกสร้างขึ้นเพื่อแสดงให้เห็นว่า QA ทำอะไรได้มากกว่าแค่หา bug

สิ่งที่ repo นี้ต้องการสื่อ:
- การจัดการ incident แบบเป็นระบบ
- การเขียน bug report ที่ชัดเจนและ actionable
- Root Cause Analysis (RCA) แบบ system thinking
- การมองปัญหาในมุม regression และ prevention
- QA mindset ใน environment production

Repo นี้ถูกแยกออกจาก learning repo โดยตั้งใจ  
👉 **ทำโจทย์จริง ไม่ปนกับการเรียนพื้นฐาน**

---

## 🧠 แนวคิด QA ที่ใช้ใน Repo นี้

- Incident มาก่อน เอกสารตามทีหลัง
- แยก symptom ออกจาก root cause
- Fix ปัญหา ≠ แก้ที่ต้นเหตุ
- Prevention สำคัญกว่า hotfix
- QA เป็นส่วนหนึ่งของคุณภาพระบบ ไม่ใช่ด่านสุดท้ายอย่างเดียว

---

## 🗂️ โครงสร้าง Repository

```
qa-incident-case-studies/  
├── README.md  
├── incidents/  
│ ├── INC-00-incident-case-template.md 
│ ├── INC-01-login-failure-after-release.md   
│  
├── templates/  
│ └── incident-case-template.md  
│  
├── playbooks/  
│ ├── incident-triage.md  
│ ├── severity-priority-guideline.md  
│ └── regression-strategy.md  
│  
└── glossary/  
└── qa-incident-terms.md
```


---

## 📄 รูปแบบ Incident Case

หนึ่ง incident = **หนึ่งไฟล์ .md จบในไฟล์เดียว**

โครงสร้างหลักจะประกอบด้วย:
1. Incident Summary  
2. Bug Report  
3. Impact / Scope  
4. Root Cause Analysis (RCA)  
5. Resolution  
6. Test Cases Added After Incident  
7. Lessons Learned & Prevention  

รูปแบบนี้อิงจากการทำงานจริงในทีม QA / Engineering

---

## 🧪 ประเภท Incident ที่ครอบคลุม

- Login / Authentication issues
- Regression หลัง deploy
- Data & migration problems
- API / integration failures
- Configuration & environment issues

Incident อาจเป็น scenario จำลอง  
แต่พฤติกรรมของระบบจะอิงจาก **pattern ที่พบได้จริงใน production**

---

## 🔗 Repository ที่เกี่ยวข้อง

-  [QA Learning Repository](https://github.com/JSONBREAK/qa-learning-practice-repository)
  ใช้สำหรับเรียน QA ตั้งแต่พื้นฐาน tools, concepts และ notes

Repo นี้ใช้สำหรับ:
👉 **การลงมือทำ + การคิดเชิงระบบ**

---

## 👤 ผู้ดูแล Repository

Maintained as part of a QA / Technical portfolio  
เพื่อแสดงแนวคิด การจัดการ incident และคุณภาพงานของ QA

---

## 📌 Disclaimer

Incident ทั้งหมดใน repo นี้เป็น scenario จำลองหรือ anonymized  
ไม่มีข้อมูลผู้ใช้จริงหรือระบบของบริษัทใดถูกนำมาใช้

---
