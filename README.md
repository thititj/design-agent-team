# Design Agent Team (Multi-Agent Workflow)

ชุดบอทออกแบบ UI/UX อัตโนมัติด้วยสถาปัตยกรรม Hierarchical Multi-Agent สำหรับ Google Antigravity

## บทบาทของบอทในทีม (`.agents/`)

1. **`chief_of_staff.md`** - หน้าด่านรับงาน แตก Task บริหาร Loop การรีวิว และส่งงานสรุป
2. **`research_bot.md`** - รีเสิร์ชคู่แข่ง วิเคราะห์ Flow และ Patterns จาก Mobbin และ Web
3. **`ui_bot.md`** - ร่าง Layout หน้าจอ ออกแบบ Component และส่งงานขึ้น Figma
4. **`ux_bot.md`** - ตรวจสอบ Usability, Accessibility (WCAG), Thumb-zone และส่ง Feedback ให้ UI Bot แก้ไข
5. **`design_system_bot.md`** - ตรวจสอบความสอดคล้องของ Tokens (สี, ฟอนต์, Spacing, Radius)

## วิธีเปิดใช้งาน

1. เปิดโฟลเดอร์นี้เป็น Active Workspace ใน Antigravity IDE / VS Code
2. พิมพ์คำสั่ง `/agents` แล้วเลือก **`chief_of_staff`**
3. เริ่มต้นสั่งงาน เช่น:
   > "ช่วยออกแบบหน้า Home และ Cart สำหรับแอป Delivery ตามสไตล์ Minimalist"
