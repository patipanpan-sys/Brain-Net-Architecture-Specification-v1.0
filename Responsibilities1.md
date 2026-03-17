# Brain-Net Project: Roles, Responsibilities & Boundaries Matrix
**Team Role Assignment & Operational Boundaries - New Network / Brain-Net**

---

## 👥 Team Role Assignment Table

| Role | Assigned To | Primary Responsibilities | Extended Responsibilities (Sprint 3 & 4) | Decision Authority |
|------|-------------|-------------------------|-------------------------------------------|--------------------|
| **Network Architect** | เจม (ปฏิภาณ) | • ออกแบบสถาปัตยกรรมเครือข่ายใหม่<br>• กำหนด TTP (Thought Transfer Protocol)<br>• ออกแบบ Contextual Framing | • ทำ Math Formalization ของ TTP<br>• กำหนด Protocol Maturity Metrics | • โครงสร้าง Protocol<br>• มาตรฐานตัวชี้วัดคุณภาพเครือข่าย (QoS) |
| **BCI Engineer** | บี (ณัฐชา) | • กำหนดมาตรฐาน BCI และ Neural Dust<br>• สร้าง Neural Dictionary<br>• ประเมินความแม่นยำคลื่นสมอง | • รับผิดชอบ Domain Mapping (Bio/Phy/Neuro)<br>• ปรับปรุง Model Maturity ขานรับฝั่งกายภาพ | • แนวทางการเชื่อมต่อทางกายภาพ<br>• ค่า Threshold ของสัญญาณประสาท |
| **Security Specialist** | รักบี้ (อาณัฐ) | • ออกแบบระบบ Consensual Handshake<br>• ป้องกันการดัดแปลงความคิด<br>• ประเมินความเสี่ยงด้านไซเบอร์ | • รัน DAFT [Extended Edition] เพื่อค้นหาช่องโหว่<br>• ออกแบบกลไก HITL Override | • กฎความปลอดภัยเครือข่าย<br>• การสับสวิตช์ Kill-Switch (System Halt) |
| **Neuroethics Lead** | โอเล่ (รัชชานนท์) | • กำหนด "สิทธิในจิตใจ" (Cognitive Liberty)<br>• รักษาขอบเขตอัตลักษณ์<br>• ร่างจริยธรรมประสาทวิทยา | • แปลงกฎหมาย (Regulations) ลงตรรกะคอมพิวเตอร์<br>• วาง Governance Framework สำหรับ HITL | • กฎเหล็กด้านจริยธรรม<br>• กฎการแทรกแซงโดยมนุษย์ (HITL Boundaries) |
| **Quantum Specialist** | โยรุ (ดรัณภพ) | • ออกแบบระบบ Quantum Decoding<br>• วางสถาปัตยกรรม QKD<br>• ประเมินวิวัฒนาการควอนตัม | • ทำ Math Formalization ในมิติของ Quantum State | • โครงสร้างการเข้ารหัส<br>• QBER (Quantum Bit Error Rate) Tolerances |

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

---

## ⚖️ Decision Authority Matrix

| Decision Type | Architect | BCI Engineer | Security | Neuroethics | Quantum |
|---------------|-----------|--------------|----------|-------------|---------|
| **Network Architecture & QoS** | **Approve** | Consult | Consult | Consult | Consult |
| **Hardware / Interface Thresholds**| Consult | **Approve** | Consult | Consult | Consult |
| **Security & Kill-Switch Halt** | Consult | Consult | **Approve** | Consult | Consult |
| **Ethics & HITL Intervention** | Consult | Consult | Consult | **Approve** | Consult |
| **Cryptography Methods & QBER** | Consult | Consult | Consult | Consult | **Approve** |

---

## 🚧 Boundaries of Responsibility (In-Scope / Out-of-Scope)

### Architect (เจม)
* **In Scope:** โครงสร้าง TTP, การจัดการ Latency, Math Formalization, Quality Metrics (QoS)
* **Out of Scope:** การเข้ารหัสข้อมูลเชิงลึก, การร่างกฎหมายจริยธรรม, การสร้างอุปกรณ์อ่านคลื่นสมอง

### BCI Engineer (บี)
* **In Scope:** เทคโนโลยี BCI, Neural Dictionary, Domain Mapping (Bio/Phy/Neuro)
* **Out of Scope:** สถาปัตยกรรมเครือข่ายภาพรวม, กฎความปลอดภัยระดับโปรโตคอล

### Security Specialist (รักบี้)
* **In Scope:** Consensual Handshake, DAFT Validation, HITL Override mechanism
* **Out of Scope:** การแมปคลื่นสมอง, การถอดรหัสอารมณ์ด้วยควอนตัม

### Neuroethics Lead (โอเล่)
* **In Scope:** กฎ "สิทธิที่จะไม่ถูกอ่านความคิด", Regulatory Smart Contracts, HITL Rules
* **Out of Scope:** การออกแบบโครงสร้าง Network, การเขียนโค้ด/โปรโตคอลระดับลึก

### Quantum Specialist (โยรุ)
* **In Scope:** อัลกอริทึม QKD, การแปลสัญญาณประสาทเป็นภาษาสากล, Quantum Math Mapping
* **Out of Scope:** การออกแบบ Layer ปกติ, ข้อกำหนดจริยธรรม, การติดตั้ง BCI

---

## 🔄 Overlap & Handoff Boundaries

| Handoff | From | To | Deliverable / Goal |
|---------|------|----|--------------------|
| **Ethics → Protocol** | Neuroethics | Architect | กฎจริยธรรม/Regulations เพื่อใช้เป็นข้อจำกัดและ HITL Parameters |
| **Security → Protocol** | Security | Architect | ผลลัพธ์จากการทดสอบ DAFT เพื่ออุดช่องโหว่ทางคณิตศาสตร์ |
| **Hardware → Protocol**| BCI Engineer| Architect | ข้อกำหนดทางกายภาพของสัญญาณประสาทเพื่อประเมิน Model Maturity |
| **Quantum → Security** | Quantum | Security | มาตรฐานการเข้ารหัสระดับควอนตัม (QKD) เพื่อรวมเข้าระบบป้องกัน |

---

## 🎯 RACI Matrix (Responsible, Accountable, Consulted, Informed)

| Activity | Architect (เจม) | BCI (บี) | Security (รักบี้) | Ethics (โอเล่) | Quantum (โยรุ) |
|----------|-----------------|----------|-------------------|----------------|----------------|
| **Protocol Design & Metrics** | **R/A** | C | C | C | I |
| **Hardware & Domain Mapping**| C | **R/A** | I | C | C |
| **DAFT & Security Architecture**| C | I | **R/A** | C | C |
| **Ethics & Regulations** | I | I | C | **R/A** | I |
| **Quantum Crypto Strategy** | I | I | C | I | **R/A** |
| **Final System Integration**| **R/A** | C | C | C | C |

---

## ⚔️ Conflict Resolution Boundaries

| Conflict Type | Resolution Path | Escalate if Unresolved |
|---------------|-----------------|------------------------|
| สิทธิส่วนบุคคลขัดแย้งกับสถาปัตยกรรม | Neuroethics ตัดสินผ่านกลไก HITL | อาจารย์ประจำวิชา |
| รูปแบบ Protocol ไม่รองรับ BCI/Math | BCI Engineer + Architect หาจุดร่วม | อาจารย์ประจำวิชา |
| ควอนตัมยังไม่พร้อมใช้งานใน Phase 1 | Quantum + BCI Engineer ออกแบบ AI ทดแทน | Architect ประเมินผลกระทบ |
| DAFT เจอช่องโหว่หนักจนรันต่อไม่ได้ | Security มีอำนาจสับสวิตช์ Kill-Switch | ทั้งทีมประชุมด่วน |

---

## 📌 Role Boundaries Quick Reference Card

```text
┌─────────────────────────────────────────────────────────────┐
│                   BRAIN-NET BOUNDARIES CHEAT SHEET                  │
├─────────────┬───────────────────────┬───────────────────────┤
│ ROLE        │ PRIMARY ZONE          │ STAY OUT OF           │
├─────────────┼───────────────────────┼───────────────────────┤
│ ARCHITECT   │ TTP, Math Mapping, QoS│ Ethics, Deep Crypto   │
├─────────────┼───────────────────────┼───────────────────────┤
│ BCI ENGINEER│ Signals, Bio Domains  │ Policy, Protocol core │
├─────────────┼───────────────────────┼───────────────────────┤
│ SECURITY    │ DAFT, Handshake, HITL │ Ethics laws, Hardware │
├─────────────┼───────────────────────┼───────────────────────┤
│ NEUROETHICS │ Rights, Regulations   │ Code, Networking Math │
├─────────────┼───────────────────────┼───────────────────────┤
│ QUANTUM     │ Decoding, QKD         │ Standard IP details   │
└─────────────┴───────────────────────┴───────────────────────┘
