# Wwise Unpacker 2.0

Extract audio files from games that use Wwise (`.pck` / `.bnk`) and convert them to **OGG · MP3 · WAV · FLAC** using a modern graphical interface.

(An upgrade to Vextil's original `.bat` script — uses the same set of tools in the `Tools` folder.)

## How to Use

1. Install [Python 3](https://www.python.org/downloads/) (check *Add python.exe to PATH*) — this only needs to be done once. No additional libraries required.
2. Double-click **Start.bat** → The application will launch automatically.
3. Click **Select Folder / Files** (or paste a path) and select your `.pck` / `.bnk` files.
4. Choose the output format and destination folder, then click **Start Extraction**.

## Improvements Over the Original

- Modern dark-themed UI with Thai/English language switching, a circular progress indicator, statistics, and operation logs.
- Select files from anywhere without copying them into the `Game Files` folder.
- Convert multiple audio files simultaneously, with adjustable processing speed.
- Added WAV / FLAC support and configurable MP3 bitrates.
- Automatically organizes output into separate folders for each source file to prevent filename conflicts.
- Supports cancellation mid-process and automatically deletes temporary files.
- Optional source file deletion (disabled by default and protected by a confirmation prompt).

The original script is preserved in the `legacy` folder.

แตกไฟล์เสียงเกมที่ใช้ Wwise (`.pck` / `.bnk`) เป็น **OGG · MP3 · WAV · FLAC** ผ่านหน้าตาโปรแกรมสมัยใหม่
(อัปเกรดจากสคริปต์ .bat ของ Vextil — ใช้เครื่องมือชุดเดิมในโฟลเดอร์ `Tools`)

## วิธีใช้
1. ติดตั้ง [Python 3](https://www.python.org/downloads/) (ติ๊ก *Add python.exe to PATH*) — ทำครั้งเดียว ไม่ต้องติดตั้งไลบรารีเพิ่ม
2. ดับเบิลคลิก **Start.bat** → หน้าต่างโปรแกรมจะเปิดขึ้นเอง
3. กด **เลือกโฟลเดอร์ / ไฟล์** (หรือวางพาธ) เลือกไฟล์ `.pck`/`.bnk`
4. เลือกรูปแบบ, โฟลเดอร์ผลลัพธ์ แล้วกด **เริ่มแตกไฟล์**

## จุดที่ดีขึ้นกว่าเดิม
- UI ธีมมืด สลับไทย/English ได้ มีวงแหวนแสดงความคืบหน้า สถิติ และบันทึกการทำงาน
- เลือกไฟล์จากที่ไหนก็ได้ ไม่ต้องก๊อปปี้เข้าโฟลเดอร์ `Game Files`
- แปลงเสียงหลายไฟล์พร้อมกัน (ปรับความเร็วได้)
- เพิ่ม WAV / FLAC และเลือกบิตเรต MP3 ได้
- แยกโฟลเดอร์ผลลัพธ์ตามไฟล์ต้นทาง ชื่อไม่ทับกัน
- ยกเลิกกลางคันได้ ไฟล์ชั่วคราวถูกลบอัตโนมัติ
- ลบไฟล์ต้นทางเป็นตัวเลือก (ปิดไว้เป็นค่าเริ่มต้น และมีการยืนยัน)

สคริปต์เดิมเก็บไว้ในโฟลเดอร์ `legacy`

<img width="925" height="982" alt="image2" src="https://github.com/user-attachments/assets/fbac9f40-1c48-479d-9d53-d8e983c30416" />
<img width="931" height="979" alt="image1" src="https://github.com/user-attachments/assets/162c9737-d8dc-44f0-978e-762fa63ed695" />
<img width="699" height="534" alt="1" src="https://github.com/user-attachments/assets/c172b2af-d3f2-40fb-9df0-c690f2116f6e" />
<img width="337" height="414" alt="3" src="https://github.com/user-attachments/assets/a4b2451d-9f53-4fc0-9325-7011f386955e" />
<img width="315" height="258" alt="2" src="https://github.com/user-attachments/assets/158bcca5-74b8-4265-8fc2-e92ca3796071" />


