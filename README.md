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
| บทที่ 1 | [Chapter 1. Introduction](01Intro.pdf) |[บทนำ](https://docs.google.com/document/d/1lWRxXek18dBk1yOg03SSAE6HMCnqce7pMmV3DGz8kNg/edit?usp=sharing)  | |
| บทที่ 2 | [Chapter 2.Getting to Know Your Data](02Data.pdf) | [มาทำความรู้จักกับข้อมูลกันเถอะ](https://docs.google.com/document/d/1lWRxXek18dBk1yOg03SSAE6HMCnqce7pMmV3DGz8kNg/edit?usp=sharing)|
| บทที่ 3 | [Chapter 3. Data Preprocessing](03Preprocessing.pdf) | [ข้อมูลที่ดีต้องผ่านกระบวนการ preprocessing ก่อนเสมอ](https://docs.google.com/document/d/1lWRxXek18dBk1yOg03SSAE6HMCnqce7pMmV3DGz8kNg/edit?usp=sharing)|
| บทที่ 6 | [Chapter 6. Mining Frequent Patterns, Association and Correlations: Basic Concepts and Methods](06FPBasic.pdf) | [การค้นหารูปแบบที่เกิดขึ้นบ่อย ความสัมพันธ์ และความเกี่ยวโยง: แนวคิดและวิธีการพื้นฐาน](https://docs.google.com/document/d/1lWRxXek18dBk1yOg03SSAE6HMCnqce7pMmV3DGz8kNg/edit?usp=sharing)|
| บทที่ 8 | [Chapter 8. Classification: Basic Concepts](08ClassBasic.pdf) | [พื้นฐานการจำแนกประเภทข้อมูล](https://docs.google.com/document/d/1lWRxXek18dBk1yOg03SSAE6HMCnqce7pMmV3DGz8kNg/edit?usp=sharing)|
| บทที่ 9 | [Chapter 9. Classification: Advanced Methods](09ClassAdvanced.pdf) | [การจำแนกประเภท: วิธีการขั้นสูง](https://docs.google.com/document/d/1lWRxXek18dBk1yOg03SSAE6HMCnqce7pMmV3DGz8kNg/edit?usp=sharing)|
| บทที่ 10 | [Chapter 10. Cluster Analysis: Basic Concepts and Methods](10ClusBasic.pdf) | [การวิเคราะห์กลุ่ม:แนวคิดพื้นฐานและวิธีการ](https://docs.google.com/document/d/1lWRxXek18dBk1yOg03SSAE6HMCnqce7pMmV3DGz8kNg/edit?usp=sharing)|

---

## 📚 Projects
- 📁 [Modeling - Decision Tree Regressor](https://colab.research.google.com/drive/1dh24AUSjeClFD-S7CZEUdy6tD8Xm_QJH#scrollTo=f87c303c)
- 📄[ขั้นตอนการสร้างโมเดล - Decision Tree Regressor](https://docs.google.com/document/d/1aCv3N_HelvMJCxxfJuztcGBACI3H2wCt/edit?usp=sharing&ouid=116197606561903678142&rtpof=true&sd=true)

### 🌳Decision Tree Regressor
Decision Tree Regressor คืออัลกอริทึมในกลุ่ม Machine Learning ที่ใช้สำหรับ ทำนายค่าที่เป็นตัวเลขต่อเนื่อง (Regression) เช่น การพาดพิงราคาบ้าน, ปริมาณน้ำฝน หรือยอดขายในอนาคต โดยเลียนแบบกระบวนการตัดสินใจของมนุษย์ในลักษณะของ "โครงสร้างต้นไม้" ถ้าจะให้เห็นภาพง่ายที่สุด ลองนึกว่าคุณกำลังเล่นเกมทายตัวเลข แล้วคุณถามคำถามแบบ "ใช่/ไม่ใช่" ไปเรื่อยๆ จนกว่าจะได้คำตอบที่ใกล้เคียงที่สุดนั่นเอง

#### 🏗️ 1. โครงสร้างและการทำงาน
การทำงานของ Decision Tree จะเลียนแบบการตัดสินใจของมนุษย์ โดยแบ่งข้อมูล (Split) ตามเงื่อนไขของฟีเจอร์ ดังนี้:
* **Root Node (โหนดราก):** จุดเริ่มต้นที่เป็นเงื่อนไขแรกสุดในการแบ่งข้อมูล
* **Decision Node (โหนดตัดสินใจ):** จุดที่มีการแยกสาขาตามเงื่อนไข (เช่น `ถ้าค่า X > 10 ให้ไปทางซ้าย`)
* **Leaf Node (โหนดใบ):** จุดสิ้นสุดของการทำนาย 
    * 📌 **สำคัญ:** ในกรณีของ Regressor ค่าทำนายที่ได้จะเป็น **ค่าเฉลี่ย (Mean)** ของข้อมูลทั้งหมดที่ตกอยู่ในโหนดใบนั้น

#### 🎯 2. เกณฑ์การตัดสินใจ "ตัด" ข้อมูล (Splitting Criteria)
ในขณะที่ Classifier ใช้ Gini หรือ Entropy แต่สำหรับ **Regressor** จะมองหาจุดที่ทำให้ **ความผิดพลาด (Error) น้อยที่สุด**

   โดยตัวชี้วัดที่นิยมที่สุดคือ:
   **Mean Squared Error (MSE)**
   $$MSE = \frac{1}{n} \sum_{i=1}^{n} (y_i - \bar{y})^2$$

   * $y_i$: ค่าจริงของข้อมูล
   * $\bar{y}$: ค่าเฉลี่ยของข้อมูลในโหนดนั้น (ค่าทำนาย)

> **หลักการ:** อัลกอริทึมจะพยายามเลือกฟีเจอร์และจุดตัด (Threshold) ที่ทำให้ผลรวมของ MSE ในโหนดลูก (Child Nodes) ต่ำที่สุด

#### 📊 3. ข้อดีและข้อเสีย (Pros & Cons)

| ข้อดี | ข้อเสีย |
| :--- | :--- |
| **Understandable:** อธิบายให้คนทั่วไปเข้าใจได้ง่ายด้วยภาพ | **Overfitting:** ถ้าต้นไม้ลึกเกินไป จะจำข้อมูลเก่าแม่นแต่ทายของใหม่พลาด |
| **No Scaling:** ไม่ต้องทำ Feature Scaling (เช่น Normalization) | **Instability:** ข้อมูลเปลี่ยนนิดเดียว รูปทรงต้นไม้อาจเปลี่ยนไปเลย |
| **Non-linear:** จัดการกับความสัมพันธ์ที่ซับซ้อนได้ดี | **No Extrapolation:** ไม่สามารถทำนายค่านอกช่วงข้อมูลที่เคยเห็นได้ |

#### 🛠️ 4. การนำไปใช้งาน (Python Example)
ตัวอย่างการเขียน Code ด้วยห้องสมุด `scikit-learn`:
```python
from sklearn.tree import DecisionTreeRegressor
  1. สร้าง Model
    แนะนำให้กำหนด max_depth เพื่อป้องกัน Overfitting
    model = DecisionTreeRegressor(max_depth=5, random_state=42)
  
  2. สอน Model (Training)
    model.fit(X_train, y_train)
  
   3. พยากรณ์ (Prediction)
    y_pred = model.predict(X_test)
```
### เพื่อลดปัญหา Overfitting ที่มักจะเกิดขึ้นกับ Decision Tree ควรปรับแต่งค่า Hyperparameters เหล่านี้:

-  `max_depth `: จำกัดความลึกของต้นไม้
-  `min_samples_split `: จำนวนข้อมูลขั้นต่ำที่ยอมให้แยกโหนดต่อ
-  `min_samples_leaf `: จำนวนข้อมูลขั้นต่ำที่ต้องมีในโหนดใบ

--- 

### ข้อแตกต่างหลักๆ ระหว่าง Decision Tree Classifier (แบบปกติ) และ Decision Tree Regressor
  1. เป้าหมายของผลลัพธ์ (Output)
    - Classifier: ทำนาย "กลุ่ม" หรือ "ประเภท" (Discrete Labels) เช่น ใช่/ไม่ใช่, หมา/แมว/นก, เกรด A/B/C
    - Regressor: ทำนาย "ตัวเลขต่อเนื่อง" (Continuous Values) เช่น ราคาหุ้น, อุณหภูมิ, หรือส่วนสูง

  2. วิธีการทำนายที่ "ใบ" (Leaf Node)
  ลองนึกภาพว่าข้อมูลไหลลงมาจนถึงปลายทางที่โหนดใบ (Leaf Node) แล้ว:
    - Classifier: จะใช้วิธี "โหวต" (Majority Vote) คือในกลุ่มนั้นมีสมาชิกประเภทไหนเยอะที่สุด ก็จะตอบประเภทนั้น
    - Regressor: จะใช้วิธี "หาค่าเฉลี่ย" (Mean) คือเอาค่าตัวเลขของสมาชิกทั้งหมดในกลุ่มนั้นมาหาค่าเฉลี่ย แล้วใช้ค่านั้นเป็นคำตอบ
  
  3. เกณฑ์ที่ใช้ในการ "ตัด" กิ่ง (Splitting Criteria)
  เพื่อให้ได้กลุ่มข้อมูลที่ "บริสุทธิ์" ที่สุดในแต่ละขั้นตอน:
   - Classifier: มักใช้ค่า Gini Impurity หรือ Entropy เพื่อวัดว่าข้อมูลในกลุ่มมันปนกันมั่วแค่ไหน (อยากให้แต่ละกลุ่มมีแต่ประเภทเดียวกันล้วนๆ)
   - Regressor: มักใช้ค่า MSE (Mean Squared Error) หรือ MAE (Mean Absolute Error) เพื่อวัดว่าค่าตัวเลขในกลุ่มนั้นมันห่างจากค่าเฉลี่ยแค่ไหน (อยากให้ตัวเลขในกลุ่มเกาะกลุ่มกันแน่นที่สุด)
  
  4. ลักษณะของเส้นกราฟการทำนาย
    - Classifier: จะเป็นการแบ่งพื้นที่ (Decision Boundaries) ออกเป็นโซนๆ ชัดเจน
    - Regressor: เส้นกราฟคำตอบจะมีลักษณะเป็น "ขั้นบันได" (Step Function) เพราะในหนึ่งโหนดใบ มันจะตอบค่าเฉลี่ยเพียงค่าเดียวตลอดช่วงของเงื่อนไขนั้น


### **ตารางสรุปความต่าง**
| คุณสมบัติ | Classifier (ปกติ) | Regressor |
| :--- | :--- | :--- |
| ตัวแปรเป้าหมาย | หมวดหมู่ (Categorical) | ตัวเลขต่อเนื่อง (Numeric) | 
| เกณฑ์การตัดสินใจ | Gini, Entropy | MSE, MAE, Poisson |
| ค่าที่ตอบที่โหนด | ใบฐานนิยม (Mode) | ค่าเฉลี่ย (Mean) |
| ตัวอย่างการใช้ | ลูกค้าจะยกเลิกบริการไหม? | ลูกค้าจะใช้เงินเท่าไหร่? |

---

### แหล่งอ้างอิงและแหล่งข้อมูลเพิ่มเติม

![ภาพประกอบ)](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSKZrFKaNZd671g9J4OcA73TsmFz6NR_edcjA&s)

[Data Mining: Concepts and Techniques](https://drive.google.com/file/d/1wXlvhLbftXg5hY38uRVz3xM8c3XahcMv/view?usp=drive_open)

การอ้างอิง Han, J., Kamber, M., & Pei, J. (2011). Data Mining: Concepts and Techniques (3rd ed.). Morgan Kaufmann. Lecture slides: “CS 412 Intro. to Data Mining — Chapter 1 (Jiawei Han, 2017).”

