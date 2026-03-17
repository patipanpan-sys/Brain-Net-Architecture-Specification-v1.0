# Brain-Net Project: Roles, Responsibilities & Boundaries Matrix
**Team Role Assignment & Operational Boundaries - New Network / Brain-Net**

---

## 👥 Team Role Assignment Table

| Role | Assigned To | Primary Responsibilities | Extended Responsibilities (Sprint 3 & 4) | Decision Authority |
|------|-------------|-------------------------|-------------------------------------------|--------------------|
| **Network Architect** | เจม (ปฏิภาณ) | • ออกแบบสถาปัตยกรรมเครือข่ายใหม่<br>• กำหนด TTP (Thought Transfer Protocol) | • ทำ Math Formalization ของ TTP<br>• กำหนด Protocol Maturity Metrics | • โครงสร้าง Protocol<br>• มาตรฐานตัวชี้วัดคุณภาพเครือข่าย (QoS) |
| **BCI Engineer** | บี (ณัฐชา) | • กำหนดมาตรฐาน BCI และ Neural Dust<br>• สร้าง Neural Dictionary | • รับผิดชอบ Domain Mapping (Bio/Phy/Neuro)<br>• ปรับปรุง Model Maturity ขานรับฝั่งกายภาพ | • แนวทางการเชื่อมต่อทางกายภาพ<br>• ค่า Threshold ของสัญญาณประสาท |
| **Security Specialist** | รักบี้ (อาณัฐ) | • ออกแบบระบบ Consensual Handshake<br>• ป้องกันการดัดแปลงความคิด | • รัน DAFT [Extended Edition] เพื่อค้นหาช่องโหว่<br>• ออกแบบกลไก HITL Override | • กฎความปลอดภัยของเครือข่าย<br>• การสับสวิตช์ Kill-Switch (System Halt) |
| **Neuroethics Lead** | โอเล่ (รัชชานนท์) | • กำหนด "สิทธิในจิตใจ" (Cognitive Liberty)<br>• ร่างจริยธรรมประสาทวิทยา | • แปลงกฎหมาย (Regulations) ลงตรรกะคอมพิวเตอร์<br>• วาง Governance Framework สำหรับ HITL | • กฎเหล็กด้านจริยธรรม<br>• กฎการแทรกแซงโดยมนุษย์ (HITL Boundaries) |
| **Quantum Specialist** | โยรุ (ดรัณภพ) | • ออกแบบระบบ Quantum Decoding<br>• วางสถาปัตยกรรม QKD | • ทำ Math Formalization ในมิติของ Quantum State | • โครงสร้างการเข้ารหัส<br>• QBER (Quantum Bit Error Rate) Tolerances |

---

## 📅 Detailed Responsibility Matrix (By Sprint Phase)

| Phase | Architect (เจม) | BCI Engineer (บี) | Security (รักบี้) | Neuroethics (โอเล่) | Quantum (โยรุ) |
|-------|-----------------|-------------------|-------------------|--------------------|----------------|
| **Week 1: Foundation** | วิเคราะห์ข้อจำกัด TCP/IP | ศึกษาข้อจำกัด BCI ปัจจุบัน | ร่างกลไกความปลอดภัยเบื้องต้น | ร่างกฎหมายสิทธิในจิตใจ | ประเมินความพร้อมควอนตัม |
| **Week 2: Protocol** | ออกแบบ TTP และ Context Layer | เริ่มแมปโครงสร้าง AI Translator | กำหนด Consensual Handshake | รีวิว Protocol ว่าละเมิดสิทธิหรือไม่ | วางแผน Quantum-ready Protocol |
| **Week 3: Physical & Validation** | เชื่อมโยง TTP ด้วย Math Formalization | แก้ไข Noise จากผลลัพธ์ DAFT | ติดตั้งและรัน DAFT [Extended Edition] | กำหนดขอบเขตพื้นที่ความคิดส่วนบุคคล | แมปคณิตศาสตร์ระดับ Quantum State |
| **Week 4: Delivery & Governance** | สรุป Maturity Metrics & Architecture | อัปเดต Model Maturity ให้เสถียร | สรุป Post-Quantum Security & HITL | ฝัง Regulation Rules เข้าสู่ Protocol | สรุปโครงสร้าง QKD |

---

## 🧩 Responsibility Area Matrix (By Component)

| Component | Design Owner | Implementation / Research | Validation Owner |
|-----------|--------------|---------------------------|------------------|
| **TTP & Math Formalization** | Architect | Architect + BCI Engineer | Security (DAFT) |
| **HITL & Consensual Handshake** | Security | Security + Neuroethics | Architect |
| **BCI & Domain Mapping** | BCI Engineer | BCI Engineer | Quantum + Architect |
| **Regulatory & Cognitive Liberty** | Neuroethics | Neuroethics | All Team |
| **Quantum Decoding & QKD** | Quantum | Quantum + Security | Architect |
