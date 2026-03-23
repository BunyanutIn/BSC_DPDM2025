# BSC_DPDM2025
Bunyanut Inthawong 663020582-2
---

**รายวิชา** : Data Preparation and Data Mining การเตรียมข้อมูลและการทำเหมืองข้อมูล (SC310003)

**คำอธิบายรายวิชา** : ความสำคัญของการจัดการข้อมูลในองค์กร วงชีวิตของข้อมูล แนวคิดการจัดการข้อมูลขององค์กรที่ประกอบด้วย การกำกับดูแลข้อมูล การจัดการสถาปัตยกรรมข้อมูล การพัฒนาข้อมูล การจัดการการดำเนินงานข้อมูล การจัดการความมั่นคงปลอดภัยของข้อมูลรวมทั้งข้อกฎหมายที่เกี่ยวข้อง การจัดการคุณภาพข้อมูล การอ้างอิงและการจัดการข้อมูลหลัก การจัดการเอกสารและเนื้อหา การจัดการข้อมูลเมตา ตลอดจนการวิเคราะห์และการจัดทำสารสนเทศเพื่อการบริหารองค์กร เน้นกรณีศึกษา

---
**Course Work and Grading**
| รายละเอียด | คะแนน |
| :--- | :--- |
| Midterm (data prepocessing ปฏิบัติ (เดี่ยว))| 25% |
| Final(ทฤษฎี data mining เดี่ยว) | 25% |
| Project (data prepocessing + data mining (จัดกลุ่มเอง 5-6 คน)) | 20% |
| Homework (แบ่งกลุ่มใหม่ทุกครั้ง) | 15% |
| Quiz (เดี่ยว ถามในห้อง) | 10% |
| GitHub | 5% |

***Final Score = Score * %attendance***

----

## เนื้อหาที่เรียน📖
### 💡Chapter 1. Introduction (บทนำสู่ Data Mining)
นำเสนอภาพรวมของ Data Mining ในฐานะเครื่องมือสำคัญสำหรับค้นหาความรู้จากข้อมูลจำนวนมหาศาลที่เกิดขึ้นในยุคดิจิทัล อธิบายถึงเหตุผลที่ต้องทำ Data Mining แนวคิดพื้นฐานของกระบวนการ KDD รวมถึงประเภทข้อมูลและงานหลักที่เกี่ยวข้องกับการขุดข้อมูล พร้อมทั้งชี้ให้เห็นว่าการทำ Data Mining เป็นศาสตร์ที่ผสานความรู้จากหลายสาขา และมีบทบาทสำคัญทั้งด้านการวิเคราะห์ข้อมูลและการสนับสนุนการตัดสินใจทางธุรกิจ

### 🔎Chapter 2. Getting to Know Your Data (มาทำความรู้จักกับข้อมูลกันเถอะ)
บทนี้กล่าวถึงการทำความเข้าใจข้อมูลก่อนการทำ Data Mining โดยครอบคลุมประเภทของข้อมูลและคุณลักษณะ (attributes), การใช้สถิติเบื้องต้นเพื่อดูค่ากลางและการกระจาย, การใช้ visualization เพื่อมองเห็นโครงสร้างและรูปแบบของข้อมูล และการวัดความคล้าย–ความต่างของข้อมูลเพื่อเตรียมพร้อมสำหรับการวิเคราะห์ขั้นต่อไป เช่น clustering และ classification.

### 📄Chapter 3. Data Preprocessing
ในขั้นแรกของการทำเหมืองข้อมูล สิ่งที่สำคัญที่สุดคือ การเตรียมข้อมูล (Data Preprocessing) ตามเนื้อหาในบทที่ 3 เนื่องจากข้อมูลในโลกจริงมักจะ "สกปรก" หรือไม่มีคุณภาพ กระบวนการนี้จึงเริ่มจากการทำความสะอาดข้อมูล (Data Cleaning) เพื่อแก้ไขค่าที่ขาดหายหรือกำจัดข้อมูลรบกวน ต่อด้วยการรวมข้อมูลจากหลายแหล่ง (Data Integration) การลดขนาดข้อมูล (Data Reduction) เพื่อให้ประมวลผลได้รวดเร็วขึ้น และการแปลงรูปแบบข้อมูล (Data Transformation) เช่น การทำ Normalization เพื่อให้ข้อมูลทุกตัวอยู่ในบรรทัดฐานเดียวกันพร้อมสำหรับการวิเคราะห์ในขั้นตอนถัดไป

### 📈Chapter 6. Mining Frequent Patterns, Association and Correlations: Basic Concepts and Methods
เมื่อข้อมูลพร้อมแล้ว เราสามารถเริ่มค้นหารูปแบบความสัมพันธ์ได้ด้วย การทำเหมืองรูปแบบที่พบบ่อย (Mining Frequent Patterns) ในบทที่ 6 ซึ่งเน้นไปที่การหาชุดรายการสินค้าหรือเหตุการณ์ที่มักเกิดขึ้นร่วมกันบ่อยๆ (Frequent Itemsets) เพื่อสร้างเป็นกฎความสัมพันธ์ (Association Rules) ที่ช่วยให้เราเข้าใจพฤติกรรมหรือแนวโน้มของข้อมูล เช่น การวิเคราะห์ว่าลูกค้ามักซื้ออะไรพร้อมกัน โดยใช้ค่าความสนับสนุน (Support) และความเชื่อมั่น (Confidence) เป็นตัวตัดสินความแข็งแกร่งของกฎเหล่านั้น

### 📊Chapter 8. Classification: Basic Concepts
ในบทนี้จะนำเสนอหัวใจสำคัญของการทำเหมืองข้อมูลที่เรียกว่า "การจำแนกประเภท" (Classification) ซึ่งถือเป็นรูปแบบหนึ่งของการเรียนรู้แบบมีผู้สอน (Supervised Learning) โดยเนื้อหาจะเริ่มจากการปูพื้นฐานให้เห็นถึงความแตกต่างระหว่างการเรียนรู้แบบมีตัวแปรบ่งชี้ (Labels) กับการเรียนรู้แบบไม่มีผู้สอน เพื่อให้เข้าใจว่าคอมพิวเตอร์สามารถใช้ข้อมูลในอดีตมาสร้างเป็นโมเดลหรือ "กฎเกณฑ์" ในการตัดสินใจได้อย่างไร

### 🔠Chapter 9. Classification: Advanced Methods
บทนี้มุ่งเน้นไปที่อัลกอริทึมการจำแนกประเภทที่มีความซับซ้อนสูง เพื่อจัดการกับข้อมูลในโลกจริงที่มีความสัมพันธ์ไม่เป็นเส้นตรงและมีมิติสูง โดยเนื้อหาครอบคลุมตั้งแต่ Support Vector Machines (SVM) ที่ใช้การสร้างไฮเปอร์เพลนเพื่อแยกข้อมูลด้วยระยะห่างที่กว้างที่สุด, Neural Networks และ Deep Learning ที่จำลองการทำงานของโครงข่ายประสาท ไปจนถึง Bayesian Belief Networks ที่ยอมรับความสัมพันธ์ระหว่างตัวแปร และเทคนิค Lazy Learners อย่าง KNN ที่จะเรียนรู้เมื่อมีข้อมูลใหม่เข้ามาเท่านั้น

### 📚Chapter 10. Cluster Analysis: Basic Concepts and Methods
บทนี้เปลี่ยนเข้าสู่การเรียนรู้แบบไม่มีผู้สอน (Unsupervised Learning) โดยมีเป้าหมายเพื่อจัดกลุ่มข้อมูลที่มีความคล้ายคลึงกัน (Similarity) ให้อยู่รวมกันเป็นกลุ่ม (Clusters) โดยที่ไม่มีการกำหนดเลเบลหรือคลาสไว้ล่วงหน้า เนื้อหาจะแนะนำวิธีการแบ่งกลุ่มที่หลากหลาย เช่น Partitioning Methods (เช่น K-Means) ที่แบ่งกลุ่มตามจุดศูนย์กลาง, Hierarchical Methods ที่จัดกลุ่มเป็นลำดับชั้น และ Density-based Methods ที่สร้างกลุ่มตามความหนาแน่นของข้อมูลเพื่อตรวจจับกลุ่มที่มีรูปร่างซับซ้อนและกำจัดข้อมูลรบกวน


---------
สรุปเนื้อหา
| บท | สไลด์ | Lecture |
| :--- | :--- | :--- |
| บทที่ 1 | [Chapter 1. Introduction](https://drive.google.com/file/d/1VJ2ceYxBHDqBz9xVcdErGcm4GLmYzN4W/view?usp=drive_open) |[บทนำ](https://docs.google.com/document/d/1lWRxXek18dBk1yOg03SSAE6HMCnqce7pMmV3DGz8kNg/edit?usp=sharing)  | |
| บทที่ 2 | [Chapter 2.Getting to Know Your Data](https://drive.google.com/file/d/1lx4HYNJakfe3dhvIDt1BVE_PMifXomqy/view) | [มาทำความรู้จักกับข้อมูลกันเถอะ](https://docs.google.com/document/d/1lWRxXek18dBk1yOg03SSAE6HMCnqce7pMmV3DGz8kNg/edit?usp=sharing)|
| บทที่ 3 | [Chapter 3. Data Preprocessing](https://drive.google.com/file/d/1lWPmRlh5AVZDmc9wgqwscSu9rlBSif7O/view?usp=drive_link) | [ข้อมูลที่ดีต้องผ่านกระบวนการ preprocessing ก่อนเสมอ](https://docs.google.com/document/d/1lWRxXek18dBk1yOg03SSAE6HMCnqce7pMmV3DGz8kNg/edit?usp=sharing)|
| บทที่ 6 | [Chapter 6. Mining Frequent Patterns, Association and Correlations: Basic Concepts and Methods](https://drive.google.com/file/d/159gCgO58IonqT8LGRd_VrY662qRmXTxN/view?usp=sharing) | [การค้นหารูปแบบที่เกิดขึ้นบ่อย ความสัมพันธ์ และความเกี่ยวโยง: แนวคิดและวิธีการพื้นฐาน](https://docs.google.com/document/d/1lWRxXek18dBk1yOg03SSAE6HMCnqce7pMmV3DGz8kNg/edit?usp=sharing)|
| บทที่ 8 | [Chapter 8. Classification: Basic Concepts](https://drive.google.com/file/d/1qoAxBKNbYYqvEr_GDydiZVqH_yn97s-O/view?usp=drive_link) | [พื้นฐานการจำแนกประเภทข้อมูล](https://docs.google.com/document/d/1lWRxXek18dBk1yOg03SSAE6HMCnqce7pMmV3DGz8kNg/edit?usp=sharing)|
| บทที่ 9 | [Chapter 9. Classification: Advanced Methods](https://drive.google.com/file/d/1GnoJ0xg1I2yaO0TsrCIwceNrj9SxDmxg/view?usp=drive_link) | [การจำแนกประเภท: วิธีการขั้นสูง](https://docs.google.com/document/d/1lWRxXek18dBk1yOg03SSAE6HMCnqce7pMmV3DGz8kNg/edit?usp=sharing)|
| บทที่ 10 | [Chapter 10. Cluster Analysis: Basic Concepts and Methods](https://drive.google.com/file/d/1-wTPukWN9kmAUk7P9qDY1GfS3btTGV0Q/view?usp=drive_link) | [การวิเคราะห์กลุ่ม:แนวคิดพื้นฐานและวิธีการ](https://docs.google.com/document/d/1lWRxXek18dBk1yOg03SSAE6HMCnqce7pMmV3DGz8kNg/edit?usp=sharing)|



### แหล่งอ้างอิงและแหล่งข้อมูลเพิ่มเติม

![ภาพประกอบ)](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSKZrFKaNZd671g9J4OcA73TsmFz6NR_edcjA&s)

[Data Mining: Concepts and Techniques](https://drive.google.com/file/d/1wXlvhLbftXg5hY38uRVz3xM8c3XahcMv/view?usp=drive_open)

การอ้างอิง Han, J., Kamber, M., & Pei, J. (2011). Data Mining: Concepts and Techniques (3rd ed.). Morgan Kaufmann. Lecture slides: “CS 412 Intro. to Data Mining — Chapter 1 (Jiawei Han, 2017).”

---
