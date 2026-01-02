# Proposal: โครงการความร่วมมือ KueKan (คือกัน)
## ระหว่าง องค์การบริหารส่วนจังหวัดนครราชสีมา และหอการค้าจังหวัดนครราชสีมา

**ผู้จัดทำ:** Digitalmedia Outsource Solution Co., Ltd. (DOS)
**วันที่:** 1 มกราคม 2026
**เวอร์ชัน:** 1.0

---

## Executive Summary: The Recommendation

**เราแนะนำให้สร้างแพลตฟอร์ม KueKan (คือกัน) เป็นโครงสร้างพื้นฐานดิจิทัลทางเศรษฐกิจ (Digital Economic Infrastructure) ร่วมกันระหว่าง อบจ.นครราชสีมา และหอการค้าจังหวัดนครราชสีมา เพื่อบรรลุเป้าหมาย 3 ประการในปีแรก:**

1. **เพิ่มมูลค่าหมุนเวียนทางเศรษฐกิจในจังหวัด 300 ล้านบาท** ผ่านระบบสะสมแต้มกลางที่กระตุ้นการใช้จ่ายในร้านค้าสมาชิก
2. **ดึงดูดนักท่องเที่ยว 500,000 คน/ปี** ไปยังแหล่งท่องเที่ยวรอง (32 อำเภอ) ด้วยกลไก Gamification
3. **เก็บข้อมูลพฤติกรรมผู้บริโภคระดับจังหวัด** เพื่อการวางแผนนโยบายแบบ Data-Driven

### Size of the Prize (มูลค่าโครงการ)

**การเพิ่มมูลค่าทางเศรษฐกิจ (Base Case Scenario):**
- ค่าใช้จ่ายเฉลี่ยนักท่องเที่ยว 600 บาท/คน/ทริป (ที่ร้านค้าสมาชิกหอการค้า ไม่รวมที่พัก) × 500,000 คน = 300 ล้านบาท/ปี*
- เพิ่มยอดขายร้านค้าสมาชิก 20-30% (อ้างอิงจากข้อมูล True Money Wallet Report 2023 และ The 1 Card Performance)**
- ลดต้นทุน CRM SaaS 60,000 บาท/ปี × 3 ปี = 180,000 บาท/ร้าน (เทียบกับการสมัคร Loyalty Platform อย่าง Eber หรือ Yollty)***

**Sensitivity Analysis (การวิเคราะห์ความอ่อนไหว):**

| Scenario | Users | ค่าใช้จ่ายเฉลี่ย/ทริป | มูลค่าหมุนเวียน | Economic Impact |
|----------|-------|----------------------|----------------|-----------------|
| **Conservative** | 300,000 คน | 500 บาท | 150 ล้านบาท | 37.5:1 |
| **Base Case** | 500,000 คน | 600 บาท | 300 ล้านบาท | 75:1 |
| **Optimistic** | 600,000 คน | 700 บาท | 420 ล้านบาท | 105:1 |

*สมมติฐาน: นักท่องเที่ยว 500,000 คน หมายถึง Unique Users ที่ใช้แอป KueKan และใช้จ่ายที่ร้านสมาชิกเฉลี่ย 600 บาท/ทริป (ไม่รวมที่พัก ค่าน้ำมัน) ซึ่งต่ำกว่าค่าใช้จ่ายเฉลี่ยนักท่องเที่ยว TAT (2,500-3,000 บาท/ทริป) เพราะคำนวณเฉพาะส่วนที่ใช้จ่ายที่ร้านสมาชิกเท่านั้น
**กรณีศึกษา: True Money Wallet รายงานว่าร้านค้าที่เข้าร่วมโปรแกรม Cashback เพิ่มยอดขาย 15-40%, The 1 Card (Central Group) สมาชิกใช้จ่ายมากกว่าลูกค้าทั่วไป 3-5 เท่า, M Card (The Mall Group) Redemption Rate ~30% และสมาชิกกลับมาซื้อซ้ำ 2x
***หมายเหตุ: SMEs ในโคราชส่วนใหญ่ไม่มีระบบ CRM แต่ถ้าต้องการฟีเจอร์คล้าย KueKan จะต้องจ่ายค่า SaaS ~60,000 บาท/ปี หรือพัฒนาเอง 300,000-800,000 บาท

**งบลงทุนเฟสแรก (MVP):** THB 4,000,000
**Economic Impact (มูลค่าผลกระทบทางเศรษฐกิจ):** 75:1 (ทุก 1 บาทที่ลงทุน สร้างมูลค่าหมุนเวียน 75 บาท ใน Base Case Scenario)

---

## 1. The Solution & Prototype (The "What")

### 1.1 แนวคิดและวิสัยทัศน์โครงการ

KueKan ไม่ใช่แค่ "แอปสะสมแต้ม" อีกหนึ่งตัว แต่เป็น **"ระบบนิเวศเศรษฐกิจดิจิทัลแบบบูรณาการ"** ที่ผสานพลังของ:

- **ภาครัฐ (อบจ.นครราชสีมา):** เป็น Policy Enabler และ Trust Builder สร้างความน่าเชื่อถือและช่วยขับเคลื่อนนโยบาย Smart City
- **ภาคเอกชน (หอการค้าจังหวัดนครราชสีมา):** เป็น Ecosystem Operator ดูแลและขยายเครือข่ายร้านค้าสมาชิก
- **ประชาชนและนักท่องเที่ยว:** เป็นผู้รับประโยชน์โดยตรง ได้รับรางวัลจากการมีส่วนร่วมกับเศรษฐกิจท้องถิ่น

### 1.2 MVP (Minimum Viable Product): The 80/20 Focus

**เราจะเริ่มต้นจากฟีเจอร์ 20% ที่สร้างผลลัพธ์ 80%:**

| ฟีเจอร์หลัก (Core Features) | เป้าหมายผลลัพธ์ |
|------------------------------|------------------|
| **1. LINE Login (ล็อกอินผ่านไลน์)** | ลดอุปสรรคการใช้งาน - ไม่ต้องโหลดแอปใหม่ เข้าถึงได้ 95% ของประชากรวัยทำงาน (ข้อมูล LINE Thailand 2024) |
| **2. Mission Center (ศูนย์ภารกิจ)** - Location-Based Check-in | กระตุ้นการท่องเที่ยว - นักท่องเที่ยวเช็คอินที่แหล่งท่องเที่ยว 32 อำเภอ |
| **3. Partner QR Scanner (สแกนให้แต้ม-ตัดแต้ม)** | ง่ายต่อร้านค้า - ระบบเดียว ทำได้ทั้งให้แต้มและรับแลกของ |
| **4. Reward Catalog (แคตตาล็อกของรางวัล)** | กระตุ้นการใช้จ่าย - ของรางวัลที่เป็นสินค้าท้องถิ่น OTOP ช่วยกระจายรายได้ |
| **5. Admin Dashboard (แดชบอร์ดภาพรวม)** | วัดผลได้ชัด - แสดงตัวเลข ROI และพฤติกรรมผู้ใช้แบบเรียลไทม์ |

**สิ่งที่เราจะ "ไม่ทำ" ในเฟสแรก:**
- ระบบโอนแต้มให้เพื่อน (P2P Transfer) - เสี่ยงต่อการขายแต้ม
- เชื่อมต่อบัตรเครดิต - ซับซ้อนและใช้เวลานาน
- AI Fraud Detection - เริ่มจากกฎง่ายๆ ก่อน ใช้ AI ในเฟส 3

### 1.3 Technology Selection: Fit for Purpose

| Technology | เหตุผลการเลือกใช้ |
|------------|-------------------|
| **LINE Login & Messaging** | LINE มี Active Users 53 ล้านคน หรือ 75% ของประชากร และครอบคลุม 95% ของประชากรวัยทำงาน (18-59 ปี) - ข้อมูลจาก LINE Thailand Report 2024 |
| **Laravel PHP (Backend)** | ทีม DOS มีประสบการณ์ 12+ ปี พร้อมซัพพอร์ตภาษาไทย |
| **PostgreSQL + Redis** | เสถียรและรองรับธุรกรรมแต้มได้หลักล้านรายการ |
| **Google Cloud Platform** | รองรับ Auto-Scaling เมื่อมีงาน Event ใหญ่ (เช่น Korat Mega Sale) |

---

## 2. The Value Bridge (The "Why"): ประโยชน์สำหรับทั้งสองหน่วยงาน

### 2.1 ประโยชน์สำหรับ อบจ.นครราชสีมา

| ประเภทประโยชน์ | รายละเอียด | Value Impact |
|----------------|-----------|--------------|
| **1. วัดผลนโยบายได้จริง (Measurable Impact)** | ทราบว่านโยบายส่งเสริมการท่องเที่ยวได้ผลจริงเท่าไหร่ - มีคนไปเที่ยวกี่คน ใช้จ่ายเท่าไหร่ ที่อำเภอไหน | ลดการตัดสินใจแบบเดาเอา 100% |
| **2. ภาพลักษณ์เมืองอัจฉริยะ (Smart City Branding)** | โคราชเป็นจังหวัดแรกในอีสานที่มีระบบ Digital Loyalty Infrastructure ระดับจังหวัด | เพิ่มโอกาสได้รับงบสนับสนุน Smart City จากรัฐบาล |
| **3. กระจายรายได้สู่ชุมชน (Economic Distribution)** | กำหนดเงื่อนไขให้แต้มต้องแลกที่ร้านค้า OTOP หรือ SMEs ในชุมชน ไม่ไหลกลับไปห้างใหญ่ | ส่งเงินหมุนเวียน 70% ไปฐานราก |
| **4. ช่องทางสื่อสารทางตรง (Direct Engagement)** | ส่ง LINE Push Message แจ้งนโยบายสำคัญ ข่าวภัยพิบัติ ถึงประชาชน 500,000+ คนได้ทันที | ลดต้นทุนการประชาสัมพันธ์ 60% |
| **5. Big Data for Policy (ข้อมูลวางแผนนโยบาย)** | ข้อมูล Heatmap การเดินทาง, ช่วงเวลาคนเที่ยวเยอะ, สินค้า OTOP ยอดนิยม | วางแผนโครงสร้างพื้นฐานได้แม่นยำขึ้น |

**Strategic Alignment กับนโยบาย อบจ.:**

```
ยุทธศาสตร์ อบจ. 2567-2572          →  บทบาทของ KueKan
┌──────────────────────────────────┐  ┌──────────────────────────────────┐
│ 1. พัฒนาเศรษฐกิจ (Soft Power)   │→│ Mission Center: Check-in ท่อง    │
│    - Korat Creative Splash       │  │ เที่ยว Unseen 32 อำเภอ          │
├──────────────────────────────────┤  ├──────────────────────────────────┤
│ 2. พัฒนาคุณภาพชีวิต (Smart     │→│ ภารกิจสุขภาพ: วิ่งออกกำลังกาย   │
│    People)                       │  │ ในสวนสาธารณะ อบจ.               │
├──────────────────────────────────┤  ├──────────────────────────────────┤
│ 3. พัฒนาเมือง (Smart City)      │→│ Real-time Dashboard: ข้อมูล      │
│                                  │  │ พฤติกรรมประชาชนสด               │
├──────────────────────────────────┤  ├──────────────────────────────────┤
│ 4. เศรษฐกิจฐานราก (OTOP)        │→│ Reward Catalog: แลกของรางวัล    │
│                                  │  │ OTOP จากร้านชุมชน                │
└──────────────────────────────────┘  └──────────────────────────────────┘
```

### 2.2 ประโยชน์สำหรับหอการค้าจังหวัดนครราชสีมา

| ประเภทประโยชน์ | รายละเอียด | Value Impact |
|----------------|-----------|--------------|
| **1. Shared Loyalty System (ระบบสะสมแต้มกลาง)** | ร้านค้าสมาชิก SMEs ไม่ต้องลงทุนทำระบบเอง (ประหยัด TCO 180,000 บาท/ร้าน เทียบกับ CRM SaaS 3 ปี) มีระบบ CRM ทันที | ประหยัดต้นทุนรวม 45 ล้านบาท (250 ร้าน × 180,000 บาท) พร้อมได้เครือข่ายลูกค้าร่วมกับร้านอื่น |
| **2. Cross-Promotion Automation (โยงร้านค้าอัตโนมัติ)** | ลูกค้าที่ซื้อร้าน A เสร็จ ได้คูปองลดร้าน B → สร้างเครือข่ายธุรกิจแข็งแกร่ง | เพิ่มยอดขาย Cross-Store 25% |
| **3. Event Gamification Engine (เครื่องมือทำงาน Event)** | ใช้ KueKan ขับเคลื่อน Korat Mega Sale 2025 - ช้อป 3 ร้านรับคูปองพิเศษ | เพิ่ม Footfall ในงาน 40% |
| **4. Big Data Ownership (เจ้าของข้อมูล)** | หอการค้ามีข้อมูลพฤติกรรมผู้บริโภคทั้งจังหวัด → อำนาจต่อรองนโยบายกับภาครัฐ | มูลค่าข้อมูล 10+ ล้านบาท/ปี |
| **5. Member Acquisition Tool (ดึงสมาชิกใหม่)** | ผู้ประกอบการรุ่นใหม่เห็นคุณค่าระบบ KueKan → สมัครสมาชิกหอการค้าเพิ่ม | เพิ่มสมาชิกใหม่ 30% ในปีแรก |

**Strategic Alignment กับยุทธศาสตร์หอการค้า:**

```
ยุทธศาสตร์หอการค้า 2568-2569      →  บทบาทของ KueKan
┌──────────────────────────────────┐  ┌──────────────────────────────────┐
│ 1. สร้างประโยชน์สมาชิก (Member │→│ Shared CRM: ลดต้นทุน Tech 80%   │
│    Benefits)                     │  │                                  │
├──────────────────────────────────┤  ├──────────────────────────────────┤
│ 2. กระตุ้นเศรษฐกิจ (Korat Mega │→│ Mission: ช้อปครบ 3 ร้าน รับคูปอง│
│    Sale 2025)                    │  │ → เพิ่ม Cross-Spending           │
├──────────────────────────────────┤  ├──────────────────────────────────┤
│ 3. ยกระดับ 32 อำเภอ             │→│ Mobile Site: ร้านต่างอำเภอเข้าถึง│
│                                  │  │ Tech ง่าย ลด Digital Divide      │
├──────────────────────────────────┤  ├──────────────────────────────────┤
│ 4. Korat Wellness & MICE         │→│ Privilege Passport: สะสมแต้มใช้  │
│                                  │  │ บริการโรงแรม/โรงพยาบาล           │
└──────────────────────────────────┘  └──────────────────────────────────┘
```

### 2.3 Value Waterfall: แหล่งที่มาของมูลค่า

```
                            มูลค่าหมุนเวียนทางเศรษฐกิจ (ปีแรก)

รายได้ฐาน                        +100 ล้านบาท
                                 ═══════════════════════════
+ นักท่องเที่ยวเพิ่ม              +120 ล้านบาท (500,000 คน × 240 บาท/คน)
  (จากภารกิจ Check-in)
                                 ────────────────────────────
+ ยอดขายร้านสมาชิกเพิ่ม           +80 ล้านบาท (เพิ่ม 25% จากฐาน 320 ล้าน)
  (จาก Cross-Promotion)
                                 ────────────────────────────
+ การใช้จ่าย OTOP เพิ่ม           +50 ล้านบาท (จากระบบ Reward → ร้าน OTOP)
                                 ────────────────────────────
- ต้นทุนรางวัลและแต้ม             -50 ล้านบาท (ของรางวัล + ส่วนลดร้านค้า)
                                 ════════════════════════════
= มูลค่าสุทธิที่เพิ่ม              300 ล้านบาท
                                 ════════════════════════════
```

---

## 3. ขอบเขตการทำงานร่วมกัน (Collaboration Framework)

### 3.1 รูปแบบความร่วมมือ (Partnership Model)

| หน่วยงาน | บทบาท | ความรับผิดชอบ |
|----------|--------|--------------|
| **อบจ.นครราชสีมา** | **The Enabler & Policy Driver** | 1. สนับสนุนงบประมาณเฟสแรก (MVP) 40%<br>2. นำระบบไปใช้ในงาน Event ท่องเที่ยว/สุขภาพ<br>3. ประชาสัมพันธ์เป็น "แอปประจำจังหวัด"<br>4. เปิดข้อมูล Open Data (แหล่งท่องเที่ยว, สถานที่ท่องเที่ยว) |
| **หอการค้าจังหวัดนครราชสีมา** | **The Operator & Ecosystem Builder** | 1. สนับสนุนงบประมาณเฟสแรก (MVP) 60%<br>2. เชิญชวนร้านค้าสมาชิก 250+ ร้าน เข้าเป็น Partner<br>3. บริหารจัดการ Reward Catalog (ของรางวัล)<br>4. ดูแล Customer Support ร่วมกับ DOS |
| **DOS (Developer)** | **The Builder & Technology Partner** | 1. พัฒนาระบบ MVP ตาม Timeline<br>2. ฝึกอบรมทีมงานทั้งสองฝ่าย<br>3. ดูแลระบบ (Maintenance) 12 เดือนแรก<br>4. Transfer Knowledge ให้ทีม IT ท้องถิ่น |

### 3.2 โครงการนำร่อง (Pilot Projects)

**เราเสนอโครงการนำร่อง 3 โครงการ เพื่อพิสูจน์ Value ในช่วง 100 วันแรก:**

| โครงการ | เป้าหมาย | KPI วัดผล | Timeline |
|---------|----------|-----------|----------|
| **1. "เที่ยวโคราช ครบ จบ ได้แต้ม"** | ดึงนักท่องเที่ยวไป Unseen 32 อำเภอ | 10,000 คน Check-in ในเดือนแรก | สัปดาห์ที่ 12-16 |
| **2. "Korat Mega Sale 2025 with KueKan"** | ทดสอบระบบ Event Gamification | ผู้เข้าร่วม 50,000 คน, ยอดขายเพิ่ม 30% | สัปดาห์ที่ 16-20 |
| **3. "ชาวโคราชดูแลสุขภาพ"** | ส่งเสริมการออกกำลังกายในสวนสาธารณะ | 5,000 คนเข้าร่วมภารกิจสุขภาพ | สัปดาห์ที่ 14-20 |

**Expected Quick Wins (ผลลัพธ์ที่เห็นได้ใน 100 วัน):**
- เพิ่มยอดขายร้านสมาชิกหอการค้า 20-25%
- ดึงนักท่องเที่ยวไปแหล่งท่องเที่ยวรอง 15,000+ คน
- สร้าง Buzz บน Social Media (Facebook, LINE, TikTok) มีคนพูดถึง 100,000+ Reach

---

## 4. Features ที่เหมาะสมกับโครงการ (Solution Features)

### 4.1 Features สำหรับ MVP (16-20 สัปดาห์)

**Customer Mobile Site (เว็บลูกค้า):**
| Feature ID | ฟีเจอร์ | Use Case สำหรับโครงการนี้ |
|------------|---------|----------------------------|
| 1.1.1 | KueKan Pocket (กระเป๋าแต้ม) | เก็บแต้มจากการท่องเที่ยว + ช้อปปิ้ง ในที่เดียว |
| 1.2.1 | Mission: Location-Based Check-in | นักท่องเที่ยว Check-in ที่แหล่งท่องเที่ยว 32 อำเภอ |
| 1.2.4 | Mission: Purchase-Based | ซื้อของครบ 500 บาทที่ร้านสมาชิกหอการค้า รับ 50 Points |
| 1.3.1 | Reward Catalog | แสดงของรางวัล OTOP และสิทธิพิเศษจากร้านค้า |
| 1.4.1-1.4.2 | Tiering System (ระดับสมาชิก) | Standard Tier (ทั่วไป) / Exclusive Tier (VIP นักท่องเที่ยว MICE) |
| 1.6.1 | LINE Login | ล็อกอินง่าย ไม่ต้องโหลดแอปใหม่ |
| 1.7.1 | LINE Push Messages | อบจ.ส่งข่าวประชาสัมพันธ์งาน Event ได้ทันที |

**Partner Mobile Site (เว็บพันธมิตร):**
| Feature ID | ฟีเจอร์ | Use Case สำหรับโครงการนี้ |
|------------|---------|----------------------------|
| 2.1.1 | Hybrid QR Scanner | ร้านค้าสมาชิกสแกน QR ตัวเดียว ทำได้ทั้งให้แต้ม + รับแลกของ |
| 2.1.3 | Manual Point Award | พนักงาน Event กดให้แต้มเมื่อลูกค้าทำภารกิจสำเร็จ |
| 2.3.1-2.3.2 | Partner Dashboard | ร้านค้าดูยอดลูกค้าและแต้มที่แจกไป-ถูกแลกมา |

**Admin Console (ระบบจัดการหลังบ้าน):**
| Feature ID | ฟีเจอร์ | Use Case สำหรับโครงการนี้ |
|------------|---------|----------------------------|
| 3.1.1-3.1.6 | Real-Time Dashboard | อบจ. + หอการค้าดูผลลัพธ์แบบเรียลไทม์ (จำนวนคนเข้าร่วม, ยอดขาย, ROI) |
| 3.2.1-3.2.4 | Mission Management | สร้างภารกิจใหม่ตามแคมเปญ (เช่น ภารกิจพิเศษช่วง Korat Mega Sale) |
| 3.3.1-3.3.4 | Geofence Manager | วาดพื้นที่ Check-in ให้ครบ 32 อำเภอ |
| 3.4.1-3.4.6 | Reward Management | จัดการของรางวัล OTOP, สินค้าท้องถิ่น, คูปองร้านสมาชิก |
| 3.6.1-3.6.6 | Fraud Detection | ป้องกันการปั๊มแต้มปลอม, GPS Spoofing Detection |

**Backend & Infrastructure:**
| Feature ID | ฟีเจอร์ | Use Case สำหรับโครงการนี้ |
|------------|---------|----------------------------|
| 4.1.1-4.1.5 | RESTful API + JWT Auth | API ให้ระบบอื่นเชื่อมต่อ (เช่น เว็บไซต์ท่องเที่ยว TAT ในอนาคต) |
| 4.2.1-4.2.3 | PostgreSQL + Redis | รองรับธุรกรรมแต้มหลักแสนรายการ/วัน |
| 4.3.1-4.3.3 | Google Cloud Platform | Auto-Scaling ในช่วง Event ใหญ่ (Korat Mega Sale) |
| 4.4.1 | Google Maps API | แสดงแผนที่แหล่งท่องเที่ยว + ร้านค้าสมาชิก |

**Security & Compliance:**
| Feature ID | ฟีเจอร์ | Use Case สำหรับโครงการนี้ |
|------------|---------|----------------------------|
| 5.1.1-5.1.5 | HTTPS + Data Encryption | ปกป้องข้อมูลผู้ใช้ตามมาตรฐาน |
| 5.2.1-5.2.2 | GPS Verification + Anti-Spoofing | ป้องกันการแอบอ้าง Check-in ปลอม |
| 5.4.1-5.4.7 | PDPA Compliance | ปฏิบัติตาม พ.ร.บ.คุ้มครองข้อมูลส่วนบุคคล |

### 4.2 Features ที่เราจะ Defer ไปเฟส 3 (Full-Scale)

**เพื่อให้ทีมโฟกัสกับ 80/20:**
- AI Fraud Detection (ใช้กฎง่ายๆ ก่อนในเฟส MVP)
- Credit Card Integration (ซับซ้อน ใช้เวลานาน)
- Multi-Tenant Architecture (ยังไม่จำเป็นในช่วงแรก)
- Predictive Analytics & ML (รอให้มีข้อมูลพอก่อน 6-12 เดือน)

---

## 5. Mobilization Plan: The "Monday Morning" Approach

### 5.1 The 100-Day Plan (Mobilize → Prototype → Launch)

**Week 1-4: Discovery & Foundation (Mobilize)**
- สัปดาห์ที่ 1: Kickoff Workshop ร่วมกัน (อบจ. + หอการค้า + DOS)
  - ทำ Co-creation Session กำหนด Top 10 Missions
  - ทำ Stakeholder Mapping (ระบุร้านค้า Partner แรก 50 ร้าน)
- สัปดาห์ที่ 2-3: Architecture Setup
  - ติดตั้ง Cloud Infrastructure (GCP)
  - เซ็ตอัพ LINE Official Account + LINE Login
  - นำเข้าข้อมูลแหล่งท่องเที่ยว 32 อำเภอ
- สัปดาห์ที่ 4: Database Design & Geofence Mapping
  - วาดพื้นที่ Geofence ครบ 32 อำเภอ (ใช้ KML จาก Google Earth)
  - ออกแบบโครงสร้างฐานข้อมูล

**Week 5-12: Build Core Features (Sprint 1-4)**
- Sprint 1 (สัปดาห์ 5-6): Customer App - LINE Login + KueKan Pocket + Profile
- Sprint 2 (สัปดาห์ 7-8): Mission Center - Location-Based Check-in + Progress Tracking
- Sprint 3 (สัปดาห์ 9-10): Partner App - QR Scanner + Manual Point Award
- Sprint 4 (สัปดาห์ 11-12): Reward Catalog + Redemption Flow

**Week 13-15: Build Admin & Integration (Sprint 5-6)**
- Sprint 5 (สัปดาห์ 13-14): Admin Console - Dashboard + Mission Management
- Sprint 6 (สัปดาห์ 15): Geofence Manager + Partner Management

**Week 16-18: UAT & Pilot Launch**
- สัปดาห์ที่ 16: User Acceptance Testing (UAT) กับ Focus Group
  - ทีมงาน อบจ. (10 คน)
  - ทีมงานหอการค้า + YEC (20 คน)
  - ร้านค้าสมาชิกนำร่อง (10 ร้าน)
- สัปดาห์ที่ 17: Soft Launch - โครงการนำร่อง "เที่ยวโคราช ครบ จบ ได้แต้ม"
- สัปดาห์ที่ 18: Fix Bugs + Iteration ตาม Feedback

**Week 19-20: Grand Launch**
- สัปดาห์ที่ 19: เตรียมความพร้อม Korat Mega Sale 2025
  - Onboard ร้านค้าสมาชิก 250 ร้าน
  - สร้าง Mission พิเศษสำหรับงาน
- สัปดาห์ที่ 20: **Grand Launch ในงาน Korat Mega Sale 2025**
  - เป้าหมาย: 50,000 Users ในสัปดาห์แรก

### 5.2 Team Topology: Bain + Client Co-Creation Model

```
                        Project Leadership
                ┌──────────────────────────────┐
                │  Steering Committee          │
                │  - อบจ. (ผู้บริหารระดับสูง)  │
                │  - หอการค้า (นายกหอการค้า)   │
                │  - DOS (COO)                 │
                └──────────────────────────────┘
                             │
                ┌────────────┴────────────┐
                │                         │
    ┌───────────▼────────────┐  ┌────────▼──────────┐
    │  Client Core Team       │  │  DOS Delivery Team│
    │  (ฝังตัวร่วมงาน)        │  │                   │
    ├─────────────────────────┤  ├───────────────────┤
    │ • อบจ. (2 คน)          │  │ • PM (1 คน)       │
    │   - Policy Lead         │  │ • Tech Lead (1)   │
    │   - Marketing Lead      │  │ • Developers (4)  │
    │                         │  │ • Designer (1)    │
    │ • หอการค้า (3 คน)      │  │ • QA (1 คน)       │
    │   - Operations Lead     │  │                   │
    │   - YEC Champion        │  │ Total: 8 คน       │
    │   - Customer Support    │  │                   │
    │                         │  │                   │
    │ Total: 5 คน             │  │                   │
    └─────────────────────────┘  └───────────────────┘
```

**Knowledge Transfer Approach:**
- ทุกสัปดาห์: Sprint Review + Demo ให้ Client Core Team เห็น (ทำไปแสดงไป)
- ทุก 2 สัปดาห์: Hands-on Workshop สอนใช้ Admin Console
- สัปดาห์ที่ 20: Handover Complete Documentation + Training Video

---

## 6. งบประมาณและระยะเวลา (Budget & Timeline)

### 6.1 งบประมาณเฟส MVP (16-20 สัปดาห์)

| หมวดรายจ่าย | รายละเอียด | จำนวนเงิน (THB) | % |
|-------------|-----------|----------------|---|
| **1. Development Cost** | ค่าพัฒนาระบบ (Backend + Frontend + Admin) | 2,200,000 | 55% |
| **2. Cloud Infrastructure** | GCP (12 เดือน), LINE OA, Google Maps API | 400,000 | 10% |
| **3. Security & Compliance** | Penetration Test, PDPA Audit, SSL Certificate | 300,000 | 7.5% |
| **4. Project Management** | PM, Scrum Master, Knowledge Transfer | 500,000 | 12.5% |
| **5. UAT & Training** | Focus Group, Onboarding ร้านค้า 250 ร้าน | 300,000 | 7.5% |
| **6. Contingency (10%)** | สำรองกรณีเจอปัญหาไม่คาดคิด | 300,000 | 7.5% |
| **TOTAL** | | **4,000,000** | **100%** |

**แบ่งสัดส่วนการลงทุน:**
- อบจ.นครราชสีมา: 1,600,000 บาท (40%)
- หอการค้าจังหวัดนครราชสีมา: 2,400,000 บาท (60%)

**Rationale:** หอการค้าลงทุนมากกว่า เพราะได้ประโยชน์ทางธุรกิจโดยตรง (Shared CRM สำหรับสมาชิก 250+ ร้าน)

### 6.2 Ongoing Cost (ปีที่ 2 เป็นต้นไป)

| หมวดรายจ่าย | รายละเอียดการคำนวณ | จำนวนเงิน (THB/ปี) |
|-------------|-------------------|-------------------|
| **Cloud Hosting (GCP)** | Compute Engine (30K/เดือน) + Cloud SQL (15K/เดือน) + Redis (8K/เดือน) + Storage & Bandwidth (5K/เดือน) = 58K × 12 เดือน | 696,000 |
| **LINE OA + Google Maps API** | LINE OA (500K Users, 2M Messages/เดือน: 70K/เดือน) + Google Maps API (15K/เดือน) = 85K × 12 เดือน | 1,020,000 |
| **Maintenance & Support (SLA 99%)** | Full Support Team (2-3 คน) + Bug Fix + Minor Updates | 800,000 |
| **Feature Enhancement** | 2-3 Features ใหม่/ปี (150-200K/feature) | 400,000 |
| **TOTAL Yearly Cost** | | **2,916,000** |

**หมายเหตุ:** ค่าใช้จ่าย Cloud + API จะขึ้นกับจำนวนผู้ใช้งานจริง สามารถลดลงได้ถ้าผู้ใช้น้อยกว่าที่ประมาณการ (Conservative Estimate: 2.4M บาท/ปี, Base Case: 2.9M บาท/ปี)

**Revenue Model เพื่อ Self-Sustain:**
- Sponsorship: ขายพื้นที่โฆษณา Banner + Sponsored Missions (1,000,000 บาท/ปี)
- Transaction Fee: 1% จากมูลค่าการแลกของรางวัล (600,000 บาท/ปี)
- Premium Membership สำหรับร้านค้า: 5,000 บาท/ปี × 100 ร้าน = 500,000 บาท/ปี
- **Total Revenue:** 2,100,000 บาท/ปี → **ครอบคลุมต้นทุน 72%** (ขาดอีก ~800,000 บาท/ปี ต้องหาสนับสนุนเพิ่มเติม หรือเพิ่ม Revenue Stream)

**ทางเลือกเพิ่มเติม:**
- เพิ่ม Transaction Fee เป็น 1.5-2% (ยังคงแข่งขันได้)
- ขาย Aggregated Data Insights Report ให้องค์กรภายนอก (300-500K บาท/ปี)
- งบสนับสนุนจาก อบจ./หอการค้า เพื่อ Public Good (400-600K บาท/ปี)

### 6.3 Timeline Overview

```
Timeline: 20 Weeks MVP Development + 4 Weeks Buffer
═══════════════════════════════════════════════════

Week 1-4     │████████░░░░░░░░░░░░░░│ Discovery & Foundation
Week 5-12    │░░░░░░░░████████████░░│ Core Features (Sprint 1-4)
Week 13-15   │░░░░░░░░░░░░░░░░████░░│ Admin & Integration
Week 16-18   │░░░░░░░░░░░░░░░░░░████│ UAT & Pilot Launch
Week 19-20   │░░░░░░░░░░░░░░░░░░░░██│ Grand Launch (Korat Mega Sale)
Week 21-24   │░░░░░░░░░░░░░░░░░░░░░░│ Buffer & Iteration (ถ้าจำเป็น)

Key Milestones:
▼ Week 4:  Architecture Sign-off
▼ Week 12: Core Features Demo
▼ Week 16: UAT Start
▼ Week 20: Grand Launch 🚀
```

---

## 7. KPIs และผลลัพธ์ที่คาดหวัง (Expected Outcomes)

### 7.1 KPIs ระดับ Strategic (ระดับจังหวัด)

| KPI | เป้าหมายปีแรก | วิธีวัด |
|-----|---------------|---------|
| **1. มูลค่าหมุนเวียนเศรษฐกิจ** | 300 ล้านบาท | Σ (ยอดซื้อที่ร้านสมาชิก × จำนวน Transaction) |
| **2. จำนวนนักท่องเที่ยว** | 500,000 คน | Unique Users ที่ Check-in ที่แหล่งท่องเที่ยว |
| **3. การกระจายรายได้สู่ 32 อำเภอ** | 70% ของแต้มถูกแลกที่ร้าน OTOP/SMEs | % Redemption ที่ร้านเล็ก vs ร้านใหญ่ |
| **4. Data Coverage** | ครอบคลุม 80% ของกิจกรรมทางเศรษฐกิจ | % Transaction ที่ผ่านระบบ KueKan |

### 7.2 KPIs ระดับ Operational (ระดับโครงการ)

| KPI | เป้าหมาย 3 เดือนแรก | เป้าหมาย 12 เดือน | เงื่อนไขสำคัญ |
|-----|---------------------|------------------|----------------|
| **Total Registered Users** | 100,000 คน | 500,000 คน | ต้องมี Marketing Budget และ Grand Launch Event ใหญ่ |
| **Active Users (MAU)** | 40,000 คน (40% Retention) | 200,000 คน (40% Retention) | ต้องมี Fresh Missions อย่างน้อย 2-3 Missions/สัปดาห์ |
| **Partner Merchants** | 250 ร้าน | 500 ร้าน | ต้องมี YEC Champions และ Onboarding Support Team |
| **Missions Completed** | 200,000 ครั้ง | 2,000,000 ครั้ง | ต้อง Gamification Mechanics น่าสนใจและรางวัลน่าดึงดูด |
| **Redemption Rate** | 25% (25,000 คนแลกของ) | 30% (150,000 คนแลกของ) | ต้องมีของรางวัลหลากหลายและ Low Entry Barrier |
| **Cross-Store Transactions** | 15% (ซื้อครบ 2+ ร้าน) | 25% | ต้องมี Cross-Promotion Missions และ Incentives |
| **App Uptime** | 99.5% (3.6 ชม. Downtime/เดือน) | 99.9% (43 นาที Downtime/เดือน) | ต้องมี GCP Auto-Scaling และ Monitoring System |
| **Fraud Detection Accuracy** | 85% (Rule-Based + Human Audit) | 90-95% (ปรับปรุงกฎและเพิ่ม ML ในเฟส 2) | ต้องมี GPS + Cell Tower Verification และ Manual Review Queue |

### 7.3 Leading vs Lagging Indicators

**Leading Indicators (ตัวชี้วัดนำ - แสดงว่าจะสำเร็จ):**
- จำนวน Daily Active Users (DAU)
- จำนวน Missions Created โดย อบจ./หอการค้า
- จำนวนร้านค้า Partner ที่ Active (แจกแต้มอย่างน้อย 1 ครั้ง/สัปดาห์)
- NPS Score (Net Promoter Score) > 50

**Lagging Indicators (ตัวชี้วัดตาม - ผลลัพธ์สุดท้าย):**
- มูลค่าหมุนเวียนเศรษฐกิจ
- จำนวนนักท่องเที่ยวสะสม
- ROI ของโครงการ

### 7.4 Success Criteria (เกณฑ์ความสำเร็จ)

**เราจะถือว่าโครงการสำเร็จ เมื่อครบ 12 เดือน:**

```
                  Threshold Targets (ขั้นต่ำ)
                  ═════════════════════════════

  ✓ Registered Users        ≥ 400,000 คน    (80% ของเป้า)
  ✓ Economic Impact         ≥ 250 ล้านบาท   (83% ของเป้า)
  ✓ Partner Retention       ≥ 80%            (ร้านค้ายังใช้งานต่อ)
  ✓ User Satisfaction       ≥ 4.0/5.0        (จาก App Store Review)
  ✓ Data Accuracy           ≥ 95%            (ข้อมูล Dashboard ตรงกับความเป็นจริง)

                  Stretch Targets (เกินความคาดหวัง)
                  ═════════════════════════════

  ★ Registered Users        ≥ 600,000 คน    (120% ของเป้า)
  ★ Economic Impact         ≥ 400 ล้านบาท   (133% ของเป้า)
  ★ Data-Driven Decisions   5+ นโยบายใช้ข้อมูล KueKan
```

---

## 8. Risk Management: Red/Amber/Green Status

### 8.1 Top 3 Risks & Mitigation

| Risk | Impact | Probability | Severity | Mitigation Strategy | Status |
|------|--------|-------------|----------|---------------------|--------|
| **1. Low Merchant Adoption** (ร้านค้าไม่สนใจเข้าร่วม) | สูง | ปานกลาง | 🔴 RED | **Quick Win Proof:** จัด Pilot กับร้านค้า 10 ร้าน พิสูจน์ยอดขายเพิ่ม 25% → นำไป Convince ร้านอื่น<br>**YEC as Champions:** ให้ YEC เป็น Early Adopters ช่วยชวนร้านสมาชิก<br>**Free Onboarding:** DOS ช่วย Onboard ฟรี 250 ร้านแรก (มูลค่า 50,000 บาท) | 🟡 AMBER |
| **2. User Confusion** (ผู้ใช้ไม่เข้าใจระบบ) | ปานกลาง | สูง | 🟡 AMBER | **LINE-First Design:** ใช้ LINE ที่คนไทยคุ้นเคย ไม่ต้องเรียนรู้ใหม่<br>**Onboarding Flow:** มี Tutorial สอนใช้งานครั้งแรก (30 วินาที)<br>**Customer Support:** มีทีม Support ตอบคำถามผ่าน LINE OA | 🟢 GREEN |
| **3. GPS Spoofing (ปลอมพิกัด Check-in)** | สูง | ปานกลาง | 🔴 RED | **Technical:** ใช้ GPS + Cell Tower + WiFi Triangulation ตรวจสอบ<br>**Business Rule:** จำกัด Check-in เดียวกัน 1 ครั้ง/12 ชม.<br>**Human Audit:** ทีม Fraud Detection สุ่มตรวจ 5% ของ Transaction | 🟢 GREEN |

### 8.2 Change Management Risks

| Stakeholder | Potential Resistance | How to Overcome |
|-------------|---------------------|-----------------|
| **ร้านค้ารุ่นเก่า** | "ไม่เก่ง Tech, กลัวยุ่งยาก" | จัด Training Workshop แบบ Hands-on, มีทีมช่วย Onboard ฟรี |
| **ประชาชนชาวบ้าน** | "ไม่อยากให้ข้อมูลส่วนตัว" | ชี้แจง PDPA Compliance ชัดเจน, ขออนุญาตก่อนเก็บข้อมูลทุกครั้ง |
| **ข้าราชการ อบจ.** | "กลัวระบบจะไม่ยั่งยืน ทิ้งงานครึ่งทาง" | ผูกสัญญา SLA 12 เดือน + มี Revenue Model ทำให้ Self-Sustain |

---

## 9. Next Steps: The "Monday Morning" Action Items

### 9.1 สิ่งที่ต้องทำ "จันทร์นี้" (Immediate Actions)

**สำหรับ อบจ.นครราชสีมา:**
1. ☑ แต่งตั้ง Project Champion (1 คน) จากฝ่ายท่องเที่ยว/เศรษฐกิจ
2. ☑ จัดประชุม Steering Committee ครั้งแรก (ภายใน 2 สัปดาห์)
3. ☑ เตรียมข้อมูลแหล่งท่องเที่ยว 32 อำเภอ (ชื่อ, พิกัด GPS, รูปภาพ)

**สำหรับหอการค้าจังหวัดนครราชสีมา:**
1. ☑ แต่งตั้ง Operations Lead และ YEC Champion
2. ☑ สำรวจร้านค้าสมาชิกที่สนใจ (Target: 50 ร้านแรก)
3. ☑ เตรียมรายชื่อของรางวัล OTOP (อย่างน้อย 30 รายการ)

**สำหรับ DOS:**
1. ☑ เตรียม Detailed Project Plan (Gantt Chart)
2. ☑ Mobilize ทีม Developer 8 คน
3. ☑ เซ็ตอัพ LINE Official Account สำหรับโครงการ

### 9.2 Decision Points (จุดตัดสินใจสำคัญ)

| Timeline | Decision Point | ผู้ตัดสินใจ |
|----------|---------------|------------|
| **Week 4** | Go/No-Go: Architecture & Budget Sign-off | Steering Committee |
| **Week 12** | Go/No-Go: Core Features ผ่าน Demo หรือไม่ | Steering Committee |
| **Week 16** | Go/No-Go: UAT ผ่านหรือไม่ เปิด Pilot หรือไม่ | Client Core Team |
| **Week 20** | Go/No-Go: Grand Launch หรือเลื่อน | Steering Committee |

### 9.3 Success Celebration (ฉลองความสำเร็จ)

**Milestone Celebrations:**
- **Week 12:** "First Mission Complete" Party → เมื่อ User คนแรกทำภารกิจสำเร็จ
- **Week 20:** Grand Launch Event ในงาน Korat Mega Sale 2025
- **Month 3:** "100,000 Users" Milestone Party
- **Month 12:** Year-End Review พร้อมมอบรางวัล "Partner of the Year" ให้ร้านค้าที่ Active ที่สุด

---

## 10. Why DOS? (ทำไมต้อง Digitalmedia Outsource Solution)

### 10.1 Track Record ที่พิสูจน์แล้ว

| ข้อมูล | รายละเอียด |
|--------|-----------|
| **ประสบการณ์** | 12+ ปี, 100+ โครงการ, 30+ ทีมงาน |
| **ลูกค้า Enterprise** | SCG, CP ALL, Central, The Mall Group |
| **เชี่ยวชาญ** | Loyalty & Rewards, E-Commerce, Mobile Apps |
| **Tech Stack** | Laravel, Next.js, Flutter, GCP/AWS - ตรงกับโครงการนี้ 100% |
| **ท้องถิ่น** | ทีมอยู่ในไทย สื่อสารภาษาไทยได้คล่อง เข้าใจ Context ตลาดไทย |

### 10.2 Bain-Style Delivery Philosophy

**เราไม่ได้แค่ "ส่งมอบโค้ด" - เราส่งมอบ "ความสามารถ" (Capability Transfer):**
- ✓ Co-creation Workshop: ทำร่วมกับทีม Client ตั้งแต่วันแรก
- ✓ Knowledge Transfer: สอนให้ทีม IT ท้องถิ่นดูแลระบบได้เอง
- ✓ Results-Oriented: มี KPI ชัดเจน ไม่ใช่แค่ทำตาม Spec

---

## 11. Appendix: Visual Summary

### 11.1 Value Waterfall Chart

```
มูลค่าหมุนเวียนทางเศรษฐกิจ (THB ล้าน/ปี)
500 │
    │   ┌───┐
400 │   │   │  ┌───┐
    │   │   │  │   │
300 │   │   │  │   │  ┌───┐       ┌───────┐
    │   │   │  │   │  │   │       │       │
200 │   │120│  │+80│  │+50│       │ -50   │  = 300
    │   │(ท่อ│  │(ช้อ│  │(OTO│       │(รางวัล│
100 │   │เที่ย│  │ปิ้ง│  │P) │       │)      │
    ├───┤ว) ├──┤)  ├──┤   ├───────┤       ├────
  0 │100│   │  │   │  │   │       │       │
    └───┴───┴──┴───┴──┴───┴───────┴───────┴────
    ฐาน  +นท  +ร้าน +OTOP        -ต้น     =สุทธิ
                                   ทุน
```

### 11.2 100-Day Roadmap (Chevron Process Flow)

```
    Mobilize              Build                Test & Learn        Launch
┌──────────────┐  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐
│  Week 1-4    │→ │  Week 5-15   │→ │  Week 16-18  │→ │  Week 19-20  │
│              │  │              │  │              │  │              │
│ • Kickoff    │  │ • Sprint 1-6 │  │ • UAT        │  │ • Grand      │
│ • Discovery  │  │ • Core       │  │ • Pilot      │  │   Launch     │
│ • Setup      │  │   Features   │  │ • Iteration  │  │ • Korat Mega │
│              │  │ • Integration│  │              │  │   Sale 2025  │
└──────────────┘  └──────────────┘  └──────────────┘  └──────────────┘
     ▼                  ▼                  ▼                  ▼
  Arch OK          Features Demo      UAT Pass          100K Users
```

---

## 12. Call to Action

**เราขอเสนอให้:**

1. **จันทร์หน้า (7 มกราคม 2026):** จัด Kickoff Workshop ร่วมกัน (อบจ. + หอการค้า + DOS)
   - **Agenda:** Co-create Top 10 Missions, ทำ Stakeholder Mapping, เห็นตัวอย่าง Demo
   - **Location:** ห้องประชุมหอการค้าจังหวัดนครราชสีมา
   - **Duration:** 4 ชั่วโมง (09:00-13:00)

2. **สัปดาห์ที่ 2 (14 มกราคม 2026):** Steering Committee Meeting ครั้งแรก
   - **Decision:** Go/No-Go สำหรับงบประมาณและ Timeline

3. **เป้าหมาย Grand Launch:** งาน Korat Mega Sale 2025 (พฤษภาคม 2026)

---

**หากท่านสนใจหรือมีข้อสงสัย กรุณาติดต่อ:**

**Jakapong Lomvong (Tle)** - Chief Operating Officer
Digitalmedia Outsource Solution Co., Ltd.
📧 Email: jakapong@digitalmedia.co.th
📱 Phone: 088-622-2488

---

**"True North: ทำให้โคราชเป็นจังหวัดแรกในอีสานที่มี Digital Economic Infrastructure ระดับโลก"**

---

## Appendix A: Data Sources & References

### ข้อมูลการท่องเที่ยว
- **Tourism Authority of Thailand (TAT):** ค่าใช้จ่ายเฉลี่ยนักท่องเที่ยวภายในประเทศ 2,500-3,000 บาท/ทริป
- **สถิติการท่องเที่ยวนครราชสีมา (2023):** ~3.5 ล้านคน/ปี ทั้งไทยและต่างชาติ

### ข้อมูล LINE Platform
- **LINE Corporation Thailand Report 2024:** Active Users 53 ล้านคน (75% ของประชากร), 95% ของประชากรวัยทำงาน (18-59 ปี)
- **Digital 2024 Thailand Report:** Social Media Penetration Rates

### กรณีศึกษา Loyalty Programs
- **True Money Wallet Report 2023:** ร้านค้าที่เข้าร่วมโปรแกรม Cashback เพิ่มยอดขาย 15-40%
- **The 1 Card (Central Group):** สมาชิกใช้จ่ายมากกว่าลูกค้าทั่วไป 3-5 เท่า, มีสมาชิก 15+ ล้านคน
- **M Card (The Mall Group):** Redemption Rate ~30%, สมาชิกกลับมาซื้อซ้ำ 2x มากกว่าลูกค้าทั่วไป
- **Bond Brand Loyalty Report:** Loyalty Programs เพิ่มยอดขาย 10-30%
- **Harvard Business Review:** การเพิ่ม Customer Retention 5% เพิ่มกำไร 25-95%
- **Accenture 2021:** Loyalty Members ใช้จ่ายมากกว่า Non-Members 12-18%

### ข้อมูล CRM & Technology Costs
- **HubSpot, Salesforce, Zoho Pricing:** SaaS CRM 15,000-50,000 บาท/ปี
- **Eber, Yollty (Loyalty Platforms):** 50,000-200,000 บาท/ปี
- **Custom Development Benchmark:** 300,000-800,000 บาท สำหรับ Loyalty CRM

### ข้อมูล Cloud Infrastructure
- **Google Cloud Platform Pricing Calculator:** GCP Services Cost Estimates
- **LINE Official Account Pricing:** Message Fee Structure
- **Google Maps API Pricing:** API Request Costs

### ข้อมูล Fraud Detection & Security
- **Rule-Based Fraud Detection Systems:** 80-90% Accuracy
- **ML-Based Fraud Detection Systems:** 95-99% Accuracy
- **Industry Standard SLA:** 99.5% (SME Apps), 99.9% (Enterprise Apps)

### เอกสารอ้างอิงภายใน
- **Feature List:** `/00 Preparation/Prep KueKan Features.md`
- **Business Context:** `/00 Preparation/Business_Context.md`
- **Korat PAO Strategy:** `/00 Preparation/Prep Korat PAO.md`
- **Korat NCC Strategy:** `/00 Preparation/Prep Korat NCC.md`

---

## Appendix B: Assumptions & Constraints

### สมมติฐานสำคัญ (Key Assumptions)

**1. User Acquisition:**
- Grand Launch Event จะดึงผู้ใช้งาน 50,000 คนในสัปดาห์แรก
- Growth Rate 19.6% per month ต้องใช้ Marketing Budget และ LINE OA Push Notifications
- User Acquisition Cost (CAC) ประมาณ 50-80 บาท/User

**2. Merchant Participation:**
- หอการค้าจะช่วย Recruit ร้านค้าสมาชิก
- YEC (Young Entrepreneur Council) จะเป็น Early Adopters และ Champions
- Onboarding Process ใช้เวลาไม่เกิน 30 นาที/ร้าน

**3. Technology Infrastructure:**
- GCP มี Auto-Scaling Capability
- LINE Platform มี Uptime 99.9%+
- Internet Penetration ในจังหวัดนครราชสีมาเพียงพอ

**4. Regulatory & Compliance:**
- PDPA Compliance ครอบคลุมทุก Features
- ไม่มีการเปลี่ยนแปลงกฎหมายที่กระทบโครงการ

### ข้อจำกัด (Constraints)

**1. Timeline:**
- ต้อง Launch ภายใน 20 สัปดาห์เพื่อทัน Korat Mega Sale 2025
- ไม่สามารถเลื่อนได้เพราะ Event มีกำหนดการแน่นอน

**2. Budget:**
- งบประมาณ 4M บาท เป็น Fixed Budget
- ต้องเลือก Features ตาม 80/20 Rule เท่านั้น

**3. Resources:**
- ทีม DOS มี 8 คน ไม่สามารถเพิ่มได้
- Client Core Team (อบจ. + หอการค้า) มี 5 คน Part-time

**4. Risks:**
- Low Merchant Adoption: ต้องมี Pilot Proof
- GPS Spoofing: ต้องใช้ Multi-layer Verification
- Retention Drop: ต้องมี Fresh Content สม่ำเสมอ

---

*Prepared by Digitalmedia Outsource Solution Co., Ltd. (DOS)*
*Version 1.1 | 2 January 2026*
*Validated and Updated based on Data Validation Report*