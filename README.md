สคริปต์ K9
นี่คือสคริปต์ K9 ที่ใช้ AI เพื่อจัดการกับฟังก์ชัน K9

การติดตั้งคำแนะนำ (ตรวจสอบให้แน่ใจว่า WarMenu ถูกติดตั้งก่อน K9)
ดาวน์โหลด K9 สคริปต์จากหน้า github ของฉัน
ลากโฟลเดอร์ k9-master ลงในรีซอร์สของคุณ
เปลี่ยนชื่อทรัพยากรเป็น "k9 "
เพิ่มชื่อทรัพยากร k9 ของคุณไปยังเซิร์ฟเวอร์ของคุณ cfg (เริ่มต้น k9)
ตั้ง ค่า คอน ฟิก
K9_Config = จริงหรือเท็จ
ตั้งค่าว่าสคริปต์ถูกจำกัดเฉพาะบางรุ่น

K9_Config = true หรือ false
ตั้งค่าถ้า k9 ถูกจำกัดให้ป้อนเฉพาะยานพาหนะบางคันเท่านั้น

K9_Config = true หรือ false
ตั้งสุนัขใน godmode ที่จะให้เขามือบนในการไล่การสงสัยของคุณ

ควบคุม
[G]-สลับสุนัขที่จะทำตามหรือเข้าพัก
[AIM + G]-บอกสุนัขที่จะโจมตี ped ที่คุณมีการเล็งที่ (ต้องใช้อาวุธตายที่ระยะทางไกล)
[LeftALT + Z]-เปิดเมนูตัวเลือก K9 (จับภาพเคลื่อนไหว K9, K9 Spawning/ลบ, และสลับรถ)


K9 Script
This is a K9 script that uses the AI to handles the k9 functions.

Installing Instructions (Make sure that WarMenu is installed before the K9)
Download K9 Script From my github page.
Drag the k9-master folder into your resources.
Rename resource to "k9"
Add your k9 resource name to your server.cfg (start k9).
Configuration
K9_Config.PedRestricted = true or false
Sets if the script is restricted to certain ped models

K9_Config.VehicleRestricted = true or false
Sets if the k9 is restricted to only enter certain vehicles.

K9_Config.GodmodeDog = true or false
Sets the dog in godmode to give him the upper hand in chasing your suspects.

Controls
[G] - Toggles the dog to follow or stay.
[AIM + G] - Tells the dog to attack the ped you are aiming at(must use a lethal weapon at longer distances).
[LeftALT + Z] - Opens the K9 options menu. (Handles K9 animations, K9 Spawning / Deleting, And the vehicle toggle)
