# BSC_DPDM23
Data Preparation and Data Mining

Score
- Midterm (data prepocessing ปฏิบัติ (เดี่ยว)) 20%
- Final(ทฤษฎี data mining เดี่ยว) 20%
- Project(data prepocessing + data mining (กลุ่ม)) 30%
- Homework(แบ่งกลุ่มใหม่ทุกครั้ง) 20%
- Quiz(เดี่ยว ถามในห้อง) 5%
- GitHub 5%

Final Score = Score * %attendance


# Intro to Data Mining
- Chapter 1. Introduction

## 1. Why Data Mining?
- เนื่องจากปริมาณข้อมูลได้เพิ่มขึ้นอย่างต่อเนื่องจนถึงระดับที่สูงมาก จากTerabytesถึงPetabytes สถานการณ์นี้เกิดขึ้นจากหลายปัจจัย เช่น การสะสมข้อมูลอัตโนมัติ ระบบฐานข้อมูล เครื่องมือเก็บข้อมูลบนเว็บ และการกระจายของสังคมคอมพิวเตอร์ไว้ทั่วไป
- เนื่องจากมีข้อมูลอยู่มาก แต่ไม่สามารถนำมาใช้ได้เพราะขาดความรู้ที่สามารถนำข้อมูลเหล่านี้มาใช้จริงได้
- การทำ Data Mining จึงเป็นสิ่งที่สำคัญ โดยการทำการวิเคราะห์ข้อมูลอัตโนมัติจากชุดข้อมูลขนาดใหญ่ เพื่อหารูปแบบ แนวโน้ม เพื่อนำข้อมูลมาใช้ได้อย่างมีมูลค่ามากที่สุด

## 2. What Is Data Mining?
- การทำ Data Mining หรือการทำเหมืองข้อมูล คือเทคนิคที่ใช้คอมพิวเตอร์ช่วยในการวิเคราะห์เพื่อประมวลผลและสำรวจชุดข้อมูลขนาดใหญ่ เมื่อใช้เครื่องมือและวิธีการทำเหมืองข้อมูล องค์กรสามารถค้นพบรูปแบบและความสัมพันธ์ที่ซ่อนอยู่ในข้อมูลของตน การทำเหมืองข้อมูลแปลงข้อมูลดิบเป็นความรู้เชิงปฏิบัติ บริษัทใช้ความรู้นี้ในการแก้ไขปัญหา วิเคราะห์ผลกระทบในอนาคตของการตัดสินใจทางธุรกิจ และเพิ่มขอบเขตกำไรของบริษัท

### กระบวนการ Knowledge Discovery (KDD)
- กระบวนการ KDD ประกอบด้วยการทำความสะอาดข้อมูล, การผสานข้อมูล, เลือกข้อมูลที่เกี่ยวข้องกับงาน, data mining, และการประเมินรูปแบบ

### ตัวอย่าง: กรอบการทำ Web Mining
- Web mining มักจะมีขั้นตอนต่าง ๆ เช่น การทำความสะอาดข้อมูล, การผสานข้อมูลจากแหล่งต่าง ๆ, การทำData warehouse, การสร้างdata cube construction, เลือกข้อมูลสำหรับ data mining, data mining จริง, และการนำเสนอผลการทำ data mining

### Data Mining ใน Business Intelligence
- Data mining มีส่วนร่วมใน business intelligence ที่สนับสนุนกระบวนการตัดสินใจ ประกอบด้วยผู้ใช้งานสุดปลาย, วิเคราะห์ธุรกิจ, วิเคราะห์ข้อมูล, และผู้ดูแลฐานข้อมูล
- องค์ประกอบของ data mining ใน business intelligence รวมถึงการสำรวจข้อมูล, การค้นคว้าข้อมูล, การนำเสนอข้อมูล, เทคนิคการแสดงผล, สรุปทางสถิติ, การค้นหาและรายงาน

### กระบวนการ KDD: มุมมองจาก Machine Learning และ Statistics
- machine learning และ statistics โดยมีขั้นตอนที่เกี่ยวข้องกับการประมวลผลข้อมูล, data mining, และการประมวลผลข้อมูลล่วงหน้า
- มีหน้าที่ผสานข้อมูล การปรับข้อมูล เลือกลักษณะ การลดมิติ การหารูปแบบ(หาpattern) การจัดกลุ่ม การวิเคราะห์ และนำเสนอออกมาในรูปแบบที่มองเห็นและทำความเข้าใจได้ง่าย

### Data Mining vs. Data Exploration
-Data Exploration หมายถึง กระบวนการที่ผู้วิเคราะห์ข้อมูลหรือนักวิทยาการข้อมูลใช้เพื่อตรวจสอบและทำความเข้าใจกับข้อมูลที่มีอยู่ โดยมุ่งเน้นการทำความเข้าใจกับโครงสร้างของข้อมูล, การวิเคราะห์ความสัมพันธ์ระหว่างข้อมูล, และการค้นหาลักษณะที่น่าสนใจ โดยทั่วไป, Data Exploration มุ่งเน้นการสำรวจข้อมูลทั้งหมดเพื่อดึงข้อมูลที่น่าสนใจออกมา, โดยไม่มีการทำนายหรือการค้นหาตามกฎหรือรูปแบบที่เป็นที่รู้จักล่วงหน้า
-Data Mining คือกระบวนการที่ใช้เทคนิคและวิธีการต่าง ๆ เพื่อค้นหาความรู้, รูปแบบ, หรือความสัมพันธ์ที่มีค่าจากข้อมูลขนาดใหญ่ โดยจะมุ่งเน้นการค้นหาโดยใช้วิธีการอัลกอริทึมและเทคนิคต่าง ๆ เพื่อนำเสนอความรู้ที่อาจจะไม่ได้รู้จักล่วงหน้าและมีมิติมากมายในข้อมูล

## 3. A Multi-Dimensional View of Data Mining
- หมายถึงการพิจารณากระบวนการทำเหมืองข้อมูลจากมุมมองที่หลายมิติ โดยนำเอาปัจจัยหลายประการมาพิจารณาพร้อมกัน เพื่อให้ได้ข้อมูลที่มีความหมายมากขึ้นและเข้าใจความสัมพันธ์ที่ซับซ้อนของข้อมูลต่าง ๆ

## 4. What Kinds of Data Can Be Mined?
###ข้อมูลที่ใช้ในการทำเหมือนข้อมูล (Data Mining) 
- Relational Database, data warehouse, และtransactional database
- Object-relational, Heterogeneous, และ legacy databases
- data streams และsensor data
- ข้อมูลลำดับเวลา(Time-series data), temporal data, และ sequence data (รวมทั้ง bio-sequences)
- Structure data, graphs, social networks, และ information networks
- ข้อมูลเชิงพื้นที่ และเวลา (Spatial data and spatiotemporal data)
- ข้อมูลมัลติมีเดีย
- ฐานข้อมูลข้อความ
- ข้อมูลจากเว็บโลก (The World-Wide Web)
## 5. What Kinds of Patterns Can Be Mined?
- ฟังก์ชันในการทำเหมือนข้อมูล (Data Mining Functions)

### 1.Generalization
- การรวมข้อมูลและสร้างคลังข้อมูล (data warehouse)
- การทำความสะอาดข้อมูล, การแปลง, การรวม, และmultidimensional data model
- เทคโนโลยี data cube
- วิธีการ scalable ในการคำนวณ multidimensional aggregates
- OLAP (online analytical processing)
- ลักษณะ multidimensional: การระบุและแยกแยะ
- การทำผลสรุปหรือการGeneralize, summarize และเปรียบเทียบลักษณะของข้อมูล เช่น พื้นที่แห้ง vs พื้นที่ชื้น

### 2.Pattern Discovery
- รูปแบบที่เกิดบ่อย (frequent patterns หรือ frequent itemsets)
- การค้นหาความสัมพันธ์และความสัมพันธ์ ตัวอย่าง: จากความความสัมพันธ์ของข้อมูลอาจทำให้เห็นว่า ถ้ามีคนซื้อผ้าอ้อม จะมีโอกาศที่จะซื้อเบียร์ตามไปด้วย [0.5%, 75%] (support, confidence)
- การทำ data mining ในชุดข้อมูลขนาดใหญ่
- การใช้รูปแบบ(patterns)เพื่อการจัดกลุ่ม, การทำนาย และการใช้งานอื่นๆ

### 3.Classification
- การจัดกลุ่ม และlabel prediction
- สร้างโมเดล(ฟังก์ชัน)จากการฝึกด้วยตัวอย่าง
- แยกแยะรายละเอียด และคลาสหรือคอนเซปต์เพื่อการทำนาย ตัวอย่าง: การจัดกลุ่มประเทศโดยใช้ภูมิอากาศ หรือ การจัดกลุ่มรถโดยใช้ ระยะทางที่รถสามารถวิ่งได้ต่อการใช้น้ำมัน(gas mileage)

### 4.Cluster Analysis
- การให้โมเดลเรียนรู้จากข้อมูล และโมเดลจะค้นพบรูปแบบและโครงสร้างในข้อมูลด้วยตนเอง(unsupervised learning)
- การจัดกลุ่มข้อมูลเพื่อสร้างหมวดหมู่ใหม่ เช่น การจัดกลุ่มบ้านเพื่อค้นหารูปแบบการกระจายของข้อมูล
- การเพิ่มความคล้ายคลึงภายในกลุ่มหรือการลดความคล้ายคลึงระหว่างกลุ่ม ซึ่งมีหลายวิธีและการประยุกต์ใช้ได้หลายแบบ

### 5.Outlier Analysis
- การวิเคราะห์ข้อมูลที่ผิดปกติ
- ข้อมูลที่ไม่เป็นไปตามพฤติกรรมทั่วไปของข้อมูล
- มีประโยชน์ในการตรวจจับฉ้อโกง, สามารถช่วยในการวิเคราะห์เหตุการณ์ที่เกิดขึ้นได้ยาก(rare case)

### 6.Time and Ordering: Sequential Pattern, Trend and Evolution Analysis
- การวิเคราะห์ลำดับ แนวโน้ม(Trend) อนุกรมเวลา วิวัฒนาการ และส่วนเบี่ยงเบน เช่น การถดถอยและการทำนายค่า
- การทำ Data Mining แบบ Streams เน้นวิเคราะห์ข้อมูลที่มีลำดับ, เปลี่ยนแปลงตามเวลา, และไม่มีที่สิ้นสุด สามารถการทำงานรวดเร็ว และประสิทธิภาพเป็นที่สำคัญ มักนำไปใช้ในการตรวจจับเหตุการณ์ที่เกิดขึ้นในเวลาทันที และการทำนายแนวโน้ม เช่น กราฟหุ้น

### 7.Structure and Network Analysis
- การทำ Graph mining การค้นหาโครงสร้างย่อยที่เกิดบ่อย (เช่น สารประกอบเคมี), ต้นไม้ (XML), โครงสร้างย่อย (fragment ของเว็บ)
- การวิเคราะห์เครือข่ายข้อมูล
เครือข่ายสังคม: นักแสดง (วัตถุ, โหนด) และความสัมพันธ์ (เส้น)
เช่น เครือข่ายผู้เขียนในวิทยาการคอมพิวเตอร์, เครือข่ายนักก่อการร้าย
เครือข่ายหลายรูปแบบ
บุคคลสามารถเป็นส่วนหนึ่งของเครือข่ายข้อมูลหลายประการ: เพื่อน, ครอบครัว, เพื่อนร่วมชั้น, ...
ลิงค์บริหารความหมายมากมาย: การทำ mining ลิงค์
- การทำ mining เว็บ
เว็บเป็นเครือข่ายข้อมูลขนาดใหญ่: จาก PageRank ไปจนถึง Google
การวิเคราะห์ของเครือข่ายข้อมูลเว็บ
ค้นพบชุมชนบนเว็บ, การทำ mining ความคิดเห็น, การทำ mining การใช้งาน เป็นต้น
## 6. What Kinds of Technologies Are Used?

## 7. What Kinds of Applications Are Targeted?

## 8. Major Issues in Data Mining

## 9. A Brief History of Data Mining and Data Mining Society

## 10. Summary
