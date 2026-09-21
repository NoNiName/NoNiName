<div align="center">

# Kitsuna &nbsp;·&nbsp; `@NoNiName`

**ระบบเกมบน Unity · เว็บด้วย Next.js · เครื่องมือสาย Lua**

ส่วนใหญ่ที่ทำคือ *โครงข้างใต้* — ระบบเวลา, ระบบบทสนทนา, หน้าแอดมิน, UI library
ชั้นที่ฟีเจอร์อื่นจะมายืนอยู่ข้างบนได้

[![English](https://img.shields.io/badge/%F0%9F%87%AC%F0%9F%87%A7_Read_in_English-README.md-1f6feb?style=for-the-badge)](./README.md)

</div>

---

## เกี่ยวกับ

ทำงานคาบเกี่ยวกันอยู่สามโลก และชอบแต่ละโลกด้วยเหตุผลคนละแบบ:

- **เกม** — Unity + C# เน้นระบบแนวซิมูเลชันและเครื่องมือสำหรับงานเล่าเรื่อง
- **เว็บ** — Next.js, TypeScript, Supabase, deploy บน Vercel
- **สคริปต์และเครื่องมือ** — Lua UI library, งานอัตโนมัติด้วย Python, งานกาวสาย sysadmin

ใช้ได้ทั้ง Linux (Ubuntu) และ Windows เขียนเอกสารโปรเจกต์เป็นไทย เขียนโค้ดเป็นอังกฤษ

---

## เครื่องมือที่ใช้

**ภาษา**

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=flat-square&logo=lua&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**เกม**

![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)
![ShaderLab](https://img.shields.io/badge/ShaderLab-222C37?style=flat-square&logo=unity&logoColor=white)
![Roblox](https://img.shields.io/badge/Roblox_Lua-00A2FF?style=flat-square&logo=roblox&logoColor=white)

**เว็บ**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

**ทั่วไป**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D4?style=flat-square&logo=windows&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)

---

## กำลังทำอะไรอยู่

### 🎮 งานเกม

**DESTINY / `UnityDestiny`** &nbsp;·&nbsp; *Unity, C#* &nbsp;·&nbsp; 🔒 ส่วนตัว

เกมแนวจำลองชีวิต ที่สร้างเป็นระบบย่อยหลายตัวแยกกัน แทนที่จะยัดทุกอย่างลง `GameManager` ตัวเดียว
— ระบบเวลา, ค่าสถานะ (เงิน เกรด หนี้), กิจกรรม, สถานที่และการเดินทางที่ต้องแลกเงินกับเวลา,
การกดคุยกับของ, บทสนทนา, โทรศัพท์ในเกมที่มีแอปและแชท, NPC เดินไปมา, แสงกลางวัน-กลางคืน,
ตู้เกมมินิเกม แต่ละระบบมีเอกสารของตัวเอง และมีแผนระยะยาวแบ่งเป็นเฟสไว้ล่วงหน้า

**Unity Dialogue System** &nbsp;·&nbsp; *Unity + เอดิเตอร์ TypeScript* &nbsp;·&nbsp; 🔒 ส่วนตัว

ชุดเครื่องมือทำบทสนทนา / visual novel ที่ใช้ไฟล์บทแบบข้อความธรรมดา
พร้อมเอดิเตอร์บนเว็บ จะได้ไม่ต้องนั่งเขียนบทแตกกิ่งอยู่ใน inspector ของ Unity

**[`Dungenos-Cube`](https://github.com/NoNiName/Dungenos-Cube)** &nbsp;·&nbsp; *Unity, ShaderLab* &nbsp;·&nbsp; สาธารณะ

โปรเจกต์ Unity ฝั่งงานภาพ — เชเดอร์และการทดลองด้านการเรนเดอร์

### 🌐 งานเว็บ

**New Web Portfolio** &nbsp;·&nbsp; *Next.js, TypeScript, Supabase, Vercel* &nbsp;·&nbsp; 🔒 ส่วนตัว

เว็บพอร์ตโฟลิโอที่มีหลังบ้านจริงจัง: หน้า `/dashboard` สำหรับแอดมิน, activity log พร้อมตัวกรอง,
อัปโหลดรูปปกที่บีบและแปลงฟอร์แมตให้, ชั้นเก็บข้อมูลที่สลับได้ระหว่าง Supabase กับ `DATA_DIR` ในเครื่อง,
และเอกสาร deploy ที่เขียนไว้แก้ปัญหาคลาสสิก "รันในเครื่องได้ แต่พังบน Vercel"

**[`DOOXY-SHOP`](https://github.com/NoNiName/DOOXY-SHOP)** &nbsp;·&nbsp; *Next.js, TypeScript* &nbsp;·&nbsp; สาธารณะ &nbsp;·&nbsp; [เว็บจริง ↗](https://dooxy-shop.vercel.app)

หน้าร้านที่ทำด้วย Next.js App Router และ deploy บน Vercel

**`nextjs-boilerplate`** &nbsp;·&nbsp; *Next.js, TypeScript* &nbsp;·&nbsp; 🔒 ส่วนตัว

ตัวตั้งต้นของตัวเองสำหรับโปรเจกต์ Next.js ใหม่ ไอเดียใหม่จะได้เริ่มล้ำหน้าไปหลายชั่วโมง

### 🌙 Lua & Roblox

**[`Library`](https://github.com/NoNiName/Library)** &nbsp;·&nbsp; *Lua* &nbsp;·&nbsp; สาธารณะ

คลังโมดูลและ UI library ที่สะสมมานาน — เก่าที่สุดในนี้ และเป็นตัวที่มีคอมมิตเยอะที่สุด

**[`Celestara-Hub`](https://github.com/NoNiName/Celestara-Hub)** &nbsp;·&nbsp; *Lua* &nbsp;·&nbsp; สาธารณะ

UI library ตัวใหม่ เขียนใหม่จากบทเรียนที่ได้จากตัวเก่า

### 📚 เรียนรู้และทดลอง

[`Learn-MMD`](https://github.com/NoNiName/Learn-MMD) · [`MiNiProject`](https://github.com/NoNiName/MiNiProject) · [`Html`](https://github.com/NoNiName/Html) — repo เล็ก ๆ ที่เอาไว้ลองของแล้วเก็บโน้ตไว้

---

## หลักที่ยึด

กฎไม่กี่ข้อที่กลับมาใช้ตลอด ส่วนใหญ่ได้มาจากการเจ็บตัวมาก่อน:

- **ห่อของเดิม ไม่เขียนทับ** ถ้ามีระบบกลางวัน-กลางคืนอยู่แล้ว ระบบเวลาก็ไปห่อมัน
  มีนาฬิกาสองอันในโปรเจกต์เดียวคือบั๊กที่รอวันเดดไลน์
- **แยก Data ออกจาก Runtime** ตัวที่ *อธิบาย* กิจกรรม กับตัวที่ *ทำ* กิจกรรม ต้องเป็นคนละอัน
- **ตรรกะเกมต้องเทสได้โดยไม่เข้า Play Mode** `Tick(float deltaTime)` แยกออกจาก `Update()` เสมอ
- **เขียนเอกสารตอนที่ยังจำบริบทได้** ทุกโปรเจกต์ในนี้มีโฟลเดอร์ `docs/`
  ที่เขียนให้คนที่จะเปิดมันอีกทีในอีกหกเดือน — ซึ่งมักจะเป็นตัวเอง

---

## ติดต่อ

[![GitHub](https://img.shields.io/badge/GitHub-@NoNiName-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NoNiName)
[![Discord](https://img.shields.io/badge/Discord-Negative-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com)

<div align="center">

*หลาย repo ข้างบนเป็นส่วนตัว — แต่ยินดีคุยเรื่องสถาปัตยกรรมของแต่ละตัวได้เสมอ*

</div>
