# VEXY CheckCMD · FiveM Cheat Scanner

โปรแกรมตรวจหาโปรแกรมช่วยเล่น FiveM ในเครื่อง โดย **VEXY STORE** — อ่านอย่างเดียว ไม่ส่งข้อมูลออก ไม่ติดตั้ง driver

## ดาวน์โหลด

### 👉 [ดาวน์โหลด VEXY CheckCMD (เวอร์ชันล่าสุด)](https://github.com/churiwantuk-hash/vexy-checkcmd/releases/latest/download/VEXY-CheckCMD-Setup.exe)

ดับเบิลคลิกไฟล์ที่ได้ → กด **ติดตั้ง** → เปิดจากทางลัดบน Desktop
ถ้า Windows ขึ้นหน้าจอสีฟ้า "Windows protected your PC" ให้กด **More info** → **Run anyway** (โปรแกรมยังไม่มีใบรับรองผู้พัฒนา)

## ติดตั้ง (คำสั่งเดียว)

เปิด **Command Prompt** แล้ววางคำสั่งนี้ กด Enter:

```bat
powershell -NoProfile -ExecutionPolicy Bypass -Command "[Net.ServicePointManager]::SecurityProtocol=3072; irm https://github.com/churiwantuk-hash/vexy-checkcmd/releases/latest/download/install.ps1 | iex"
```

หรือใน **PowerShell**:

```powershell
[Net.ServicePointManager]::SecurityProtocol=3072; irm https://github.com/churiwantuk-hash/vexy-checkcmd/releases/latest/download/install.ps1 | iex
```

โปรแกรมจะถูกติดตั้งที่ `%LOCALAPPDATA%\Programs\VEXY CheckCMD` และมีทางลัด **VEXY CheckCMD** บน Desktop
ใช้งานต้องมีคีย์จากร้าน VEXY STORE · รองรับ Windows 10/11 64-bit

หรือดาวน์โหลด `VEXY-CheckCMD-Setup.exe` จากหน้า [Releases](https://github.com/churiwantuk-hash/vexy-checkcmd/releases/latest) แล้วกดติดตั้ง
