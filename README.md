# BSC_DPDM2025
Bunyanut Inthawong 663020582-2

---

## บทที่ 1: บทนำสู่ Data Mining
  [Chapter 1. Introduction](https://drive.google.com/file/d/1VJ2ceYxBHDqBz9xVcdErGcm4GLmYzN4W/view?usp=drive_open)

### ทำไมต้องทำ Data Mining ???
- ปริมาณข้อมูลมหาศาล (จากเทรมไบต์ไปยังเพตไบต์)
- แหล่งข้อมูลมากมายและการเก็บข้อมูลอัตโนมัติจากหลายแหล่ง (เว็บ, ธุรกิจ, วิทยาศาสตร์, สังคม)
- ต้องการเครื่องมือวิเคราะห์ข้อมูลเพื่อเปลี่ยนข้อมูลจำนวนมากให้กลายเป็นความรู้
- Data mining เป็นวิธีวิเคราะห์อัตโนมัติที่ช่วยค้นหาความรู้จากข้อมูลขนาดใหญ่

### Data Mining คืออะไร
- กระบวนการดึงรูปแบบหรือความรู้ที่น่าสนใจ (ไม่ง่าย ไม่ธรรมดา ไม่รู้มาก่อน และมีประโยชน์) จากข้อมูลจำนวนมาก
- บางครั้งเรียกว่า Knowledge Discovery in Databases (KDD) หรือคำอธิบายทดแทนอื่นๆ เช่น data/pattern analysis, information harvesting ฯลฯ
- ควรระวังว่าไม่ใช่ทุกอย่างเป็น “data mining”

### กระบวนการ KDD (จากข้อมูลสู่ความรู้)
- ขั้นตอนหลัก: Data Cleaning -> Data Integration -> Data Selection -> Data Transformation -> Data Mining -> Pattern Evaluation -> Knowledge Presentation
- data mining มีบทบาทสำคัญในกระบวนการ KNOWLEDGE DISCOVERY

### ตัวอย่างกรอบการทำงาน
- ตัวอย่างกรอบ Web Mining ที่รวมการทำ data cleaning, integration, warehousing, data cube, data selection, data mining, และการนำเสนอผลลัพธ์

### Data Mining ใน Business Intelligence
- เชื่อมต่อการวิเคราะห์ข้อมูลกับการตัดสินใจทางธุรกิจผ่าน visualization, data exploration, data preprocessing/integration และ data warehouse

### มุมมองระหว่าง Data Mining กับ Data Exploration
- เป้าหมายและวิธีการใช้งานต่างกันตามบริบท (KDD/ML/Statistics/BI)
- ขึ้นกับข้อมูลและวัตถุประสงค์ ผู้ใช้งานอาจเน้นการสำรวจข้อมูล หรือการสร้างโมเดล/การวิจัยข้อมูลมากกว่า

### มุมมองเชิงมัลติ-มิติของ Data Mining
- แผนภาพ: data ที่นำมาขุดสามารถเป็นชุดข้อมูลจากฐานข้อมูล/คลังข้อมูล/ข้อมูลธุรกรรม/สตรีม/ข้อมูลเชิงพื้นที่/ข้อมูลมัลติมีเดีย/ข้อความ/Web ฯลฯ
- ฟังก์ชันการขุด (Data Mining Functions): การจำแนก/การวิเคราะห์ความสัมพันธ์/คลัสเตอริง/การทำนาย/การระบุแนวโน้มและ outliers ฯลฯ
- ความแตกต่างระหว่าง Descriptive กับ Predictive data mining
- สามารถทำการขุดข้อมูลหลายฟังก์ชันพร้อมกันและที่หลายระดับ

### ข้อมูลประเภทที่ Data Mining สามารถทำงานด้วย
- ฐานข้อมูลเชิงสัมพันธ์, data warehouse, transactional databases
- ฐานข้อมูลแบบ object-relational, ฐานข้อมูลหลายประเภท
- ข้อมูลสตรีม, สัญญาณ/ sensor data
- Time-series, sequences (รวมถึงชีวโมเลกุลชีวภาพ)
- โครงสร้างข้อมูล (graphs, networks สังคม-ข้อมูล)
- Spatial, spatiotemporal, multimedia, text, Web
- World Wide Web

### ฟังก์ชันหลักของ Data Mining (รายละเอียดสรุป)
| ฟังก์ชันหลัก (Main Function) | รายละเอียด (Description) | ตัวอย่างการนำไปใช้และแนวคิดที่เกี่ยวข้อง |
| :--- | :--- | :--- |
| **Generalization** | การสรุปรวมและจำแนกข้อมูลให้เป็นหมวดหมู่ที่ใหญ่ขึ้น | - การใช้ Data Cube <br>- การทำ OLAP (Online Analytical Processing) |
| **Pattern Discovery** | การค้นหารูปแบบหรือความสัมพันธ์ที่เกิดขึ้นร่วมกันบ่อยครั้ง | - Frequent patterns (รูปแบบที่พบบ่อย) <br>- Association Rules (กฎความสัมพันธ์) <br>- การตีความความสัมพันธ์ข้อมูล |
| **Classification** | สร้างโมเดลเพื่อจำแนกประเภทหรือทำนายชั้นข้อมูล (Class) ของข้อมูลใหม่ | - การทำนายว่าอีเมลเป็น Spam หรือไม่ <br>- การวิเคราะห์ความเสี่ยงเครดิต |
| **Cluster Analysis** | การจัดกลุ่มข้อมูลที่มีลักษณะคล้ายคลึงกันให้อยู่เป็นกลุ่มก้อน (Cluster) เดียวกัน | - ลดความแตกต่างภายในกลุ่ม (Intra-class similarity) ให้มากที่สุด <br>- เพิ่มความต่างระหว่างกลุ่ม (Inter-class similarity) ให้มากที่สุด |
| **Outlier Analysis** | การวิเคราะห์หาจุดข้อมูลที่ผิดปกติ หรือแตกต่างไปจากกลุ่มส่วนใหญ่ | - การหา Noise หรือข้อผิดพลาดของข้อมูล <br>- การตรวจจับการทุจริต (Fraud detection) หรือเหตุการณ์พิเศษ |
| **Time and Ordering** | การวิเคราะห์ข้อมูลที่มีลำดับเวลาหรือลำดับเหตุการณ์เกี่ยวข้อง | - Sequential Patterns (รูปแบบลำดับเหตุการณ์) <br>- Trend Analysis (วิเคราะห์แนวโน้ม) <br>- Time-series data (ข้อมูลอนุกรมเวลา) |
| **Structure and Network Analysis** | การวิเคราะห์ข้อมูลที่มีโครงสร้างเชื่อมโยงกันเป็นกราฟหรือเครือข่าย | - Graph Mining <br>- Web Mining <br>- Social Network Analysis (วิเคราะห์เครือข่ายสังคม) |
| **Knowledge Evaluation** | การประเมินความน่าสนใจและความรู้ที่ได้จากการขุดข้อมูล | - เปรียบเทียบ Descriptive vs Predictive tasks <br>- เกณฑ์การวัด: Coverage (ความครอบคลุม), Typicality (ความเป็นตัวแทน), Novelty (ความแปลกใหม่), Accuracy (ความแม่นยำ), Timeliness (ความทันกาล) |

### Data Mining เป็นการบรรจบกับหลายศาสตร์
- การเรียนรู้ของเครื่อง (Machine Learning)
- สถิติ (Statistics)
- การออกแบบ/การวิจัยข้อมูลเชิงวิชาการ
- Visualization
- High-performance computing
- ฐานข้อมูลและเทคโนโลยีที่เกี่ยวข้อง

### ประวัติศาสตร์สั้นๆ ของ Data Mining และชุมชน
- ตั้งแต่อย่าง IJCAI Workshop 1989 และพัฒนาขึ้นสู่ KDD conferences, SIGKDD และวารสาร
- มีงานประชุม/วารสารและทิศทางการวิจัยมากมายทั้งในระดับนานาชาติและภูมิภาค (KDD, ICDM, PKDD, PAKDD, WSDM ฯลฯ)

### แหล่งอ้างอิงและแหล่งข้อมูลเพิ่มเติม

![ภาพประกอบ)](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSKZrFKaNZd671g9J4OcA73TsmFz6NR_edcjA&s)

[Data Mining: Concepts and Techniques](https://drive.google.com/file/d/1wXlvhLbftXg5hY38uRVz3xM8c3XahcMv/view?usp=drive_open)

การอ้างอิง Han, J., Kamber, M., & Pei, J. (2011). Data Mining: Concepts and Techniques (3rd ed.). Morgan Kaufmann. Lecture slides: “CS 412 Intro. to Data Mining — Chapter 1 (Jiawei Han, 2017).”

---
