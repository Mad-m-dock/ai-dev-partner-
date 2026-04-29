# AI Dev Partner — CLAUDE.md Template

A thinking framework for developers working with Claude.  
Drop this into any project and Claude becomes a proper dev partner — not just a code generator.

---

## How to Use

### Option A — Claude Code (CLI) ✅ แนะนำ

1. ติดตั้ง Claude Code ถ้ายังไม่มี → [claude.ai/code](https://claude.ai/code)
2. Clone หรือ download repo นี้
3. Copy ไฟล์ `CLAUDE.md` ไปวางใน root ของ project ของคุณ
4. เปิด terminal → `cd your-project` → พิมพ์ `claude`
5. Claude จะ pick up ไฟล์นี้อัตโนมัติ — พร้อมใช้เลย

### Option B — Claude.ai (Web)

1. เปิด [claude.ai](https://claude.ai) → ไปที่ **Projects**
2. สร้าง Project ใหม่สำหรับ project ของคุณ
3. เปิดไฟล์ `CLAUDE.md` → Copy ทั้งหมด
4. วางเป็น **Project Instructions** ใน Project settings
5. ทุก conversation ใน Project นั้นจะใช้ framework นี้อัตโนมัติ

---

## Quick Commands

เมื่อคุยกับ Claude ในโปรเจกต์ของคุณ ใช้ command เหล่านี้ได้เลย:

| Command | ทำอะไร |
|---|---|
| `/plan [สิ่งที่อยากทำ]` | วางแผน approach ก่อน code |
| `/debug [ปัญหา]` | วิเคราะห์ root cause |
| `/review` | ตรวจ code ที่เขียนไป |
| `/explain [concept]` | อธิบายจาก first principles |
| `/simplify` | ลด complexity |
| `/risks [feature]` | หาสิ่งที่อาจพังก่อน build |

---

## ปรับให้เข้ากับ Project ของคุณ

เปิดไฟล์ `CLAUDE.md` แล้วแก้ section **Tech Stack Defaults** ให้ตรงกับ stack ที่คุณใช้จริง:

```
Frontend  : React / Vue / Vanilla JS
Backend   : Node.js / Python / PHP
Database  : MySQL / PostgreSQL / MongoDB
```

ส่วนอื่นใช้ได้เลยโดยไม่ต้องแก้ค่ะ

---

## ทำไมต้องใช้ CLAUDE.md?

โดยปกติ Claude ตอบแบบ generic — ไม่รู้ว่าคุณเป็นใคร ใช้ stack อะไร ชอบ style ไหน  
พอมี CLAUDE.md ใน project Claude จะ:

- **คิดก่อน code** — ไม่ยิง solution ทันที
- **บอกตรงๆ** ถ้า approach ของคุณมีปัญหา
- **จำ context** ของ project ตลอด session
- **เตือนเรื่อง security** ก่อนที่จะเป็นปัญหา

---

*Template นี้สร้างโดย [Mad-m-dock](https://github.com/Mad-m-dock)*
