# Folder Icon Maker

เปลี่ยนสีและไอคอนโฟลเดอร์ใน Windows ได้ในคลิกเดียว · Custom folder colors and icons for Windows, in one click.

**[⬇ ดาวน์โหลดเวอร์ชันล่าสุด / Download the latest version](../../releases/latest)**

ใช้ฟรีทุกฟีเจอร์ ไม่จำกัดโฟลเดอร์ ไม่มีโฆษณา ไม่ต้องสมัครบัญชี · Every feature free, unlimited folders, no ads, no account.

**♥ สนับสนุนผู้พัฒนา / Support:** ถ้าแอปมีประโยชน์ กดปุ่ม ♥ ในแอปเพื่อสนับสนุนได้ตามสะดวก (ไม่บังคับ) · If it helps you, the ♥ button in the app lets you chip in. Optional.

> **หมายเหตุ:** repo นี้ใช้แจกไฟล์ติดตั้ง ไม่ใช่ open source · This repo hosts the downloads; the app is free to use but not open source. (The "Source code" links under each release are added by GitHub automatically and only contain this README.)

---

## ติดตั้ง (ภาษาไทย)

1. ดาวน์โหลด `FolderIconMaker-<เวอร์ชัน>.zip` จากหน้า [Releases](../../releases/latest) (ดาวน์โหลดจากหน้านี้เท่านั้น)
2. คลิกขวาที่ zip → **Extract All** ห้ามดึง exe ออกมาไฟล์เดียว เพราะต้องมีโฟลเดอร์ `_internal` อยู่ข้างๆ
3. เปิด `FolderIconMaker.exe`
4. ถ้าขึ้น **"Windows protected your PC"** ให้กด **More info → Run anyway**
   - คำเตือนนี้ขึ้นเพราะแอปยังไม่ได้ซื้อใบรับรองเซ็นโค้ด ไม่ได้แปลว่ามีไวรัส
   - ตรวจเองได้ตามหัวข้อ "ตรวจว่าเป็นไฟล์แท้" ข้างล่าง
5. แอปทำงานอยู่ที่ไอคอนข้างนาฬิกา เรียกหน้าต่างขึ้นมาได้ด้วย **Ctrl+Alt+I**

### ปลอดภัยไหม
- แอปไม่แก้ไฟล์ระบบ แค่เขียนไฟล์ `desktop.ini` กับไฟล์ไอคอนลงในโฟลเดอร์ที่คุณเลือก
- กด "คืนค่า" ได้ทุกเมื่อ
- ไม่ส่งข้อมูลของคุณไปที่ไหน มีแค่การเช็กเวอร์ชันใหม่กับ GitHub วันละครั้ง (ปิดได้ใน ⚙ ตั้งค่า)

## Install (English)

1. Download `FolderIconMaker-<version>.zip` from [Releases](../../releases/latest), and only from there.
2. Right-click the zip → **Extract All**. Keep `FolderIconMaker.exe` next to its `_internal` folder.
3. Run `FolderIconMaker.exe`.
4. If **"Windows protected your PC"** shows up, click **More info → Run anyway**.
   - The warning appears because the app isn't code-signed yet. It doesn't mean there is a virus.
   - You can check the file yourself (see below).
5. The app lives in the tray next to the clock. Press **Ctrl+Alt+I** to bring the window up.

The app only writes `desktop.ini` and icon files into folders you pick, and "Restore" undoes it. The only network request is a once-a-day check for a new version on GitHub, which you can turn off in Settings.

## ตรวจว่าเป็นไฟล์แท้ / Check the download

Each release lists the SHA-256 of the zip and of the exe, plus a VirusTotal scan link. In PowerShell:

```powershell
Get-FileHash .\FolderIconMaker-1.2.0.zip -Algorithm SHA256
```

The number must match the one on the release page.

## ติดต่อ / Contact

แจ้งปัญหาหรือขอฟีเจอร์ได้ที่แท็บ **Issues** · Report problems or ask for features in **Issues**.
