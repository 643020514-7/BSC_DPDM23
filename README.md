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


 # Data mining
 
 ![image](https://github.com/phurisk/BSC_DPDM23/assets/137043070/4440bd5e-39c1-4ed8-bcbb-191ce43f82a6)

 
 ## Knowledge Discovery (KDD) Process
- การทำความสะอาดข้อมูล (Data Cleaning): การกำจัดข้อมูลที่ไม่ต้องการหรือไม่เกี่ยวข้อง เช่น โค้ด HTML, สคริปต์ JavaScript หรือข้อมูลที่ซ้ำซ้อน เพื่อให้เหลือเพียงข้อมูลที่เป็นประโยชน์สำหรับการวิเคราะห์.

- การผสานข้อมูลจากแหล่งต่างๆ (Data Integration): การรวมข้อมูลที่มาจากหลายแหล่ง หรือหลายหน้าเว็บ เพื่อสร้างมุมมองที่ครอบคลุมและสมบูรณ์.

- การทำ Data Warehouse: การสร้างคลังข้อมูลเพื่อเก็บข้อมูลที่ได้มา โดยจะมีการออกแบบโครงสร้างของคลังข้อมูลเพื่อรองรับการวิเคราะห์ข้อมูลในอนาคต.

- การสร้าง Data Cube Construction: สร้างโครงสร้างข้อมูลหลายมิติ เพื่อให้สามารถวิเคราะห์ข้อมูลได้ในหลายมิติและหลายระดับ.

- การเลือกข้อมูลสำหรับ Data Mining: คัดเลือกข้อมูลที่เหมาะสมและเกี่ยวข้องกับเป้าหมายของการทำเหมืองข้อมูล โดยข้อมูลนี้จะถูกนำไปใช้ในขั้นตอนถัดไป.

- Data Mining จริง: การใช้เทคนิคและอัลกอริทึมการทำเหมืองข้อมูลเพื่อค้นหารูปแบบ, ความสัมพันธ์, หรือความรู้ที่ซ่อนอยู่ในข้อมูล.

- การนำเสนอผลการทำ Data Mining: การนำเสนอผลลัพธ์ของการทำเหมืองข้อมูลในรูปแบบที่เข้าใจง่าย เช่น รายงาน, แผนภูมิ, หรือการแสดงผลในรูปแบบกราฟิก เพื่อให้ผู้ใช้สามารถเข้าใจและใช้ประโยชน์จากข้อมูลให้ได้มากที่สุด.

# Data Compression
![image](https://github.com/phurisk/BSC_DPDM23/assets/137043070/2d72f18a-3276-42c5-8fcc-6dac56afad77)

- Lossless Compression: ข้อมูลที่บีบอัดสามารถกู้คืนกลับไปยังรูปแบบเดิมได้โดยไม่มีการเปลี่ยนแปลงหรือสูญเสียข้อมูลใดๆ ข้อมูลที่แตกไฟล์จะเหมือนกับข้อมูลต้นฉบับทุกประการ.

- Lossy Compression: ข้อมูลที่บีบอัดจะสูญเสียรายละเอียดบางส่วนไป ซึ่งไม่สามารถกู้คืนข้อมูลได้เมื่อแตกไฟล์ ข้อมูลที่ได้จะเป็นการประมาณค่าของข้อมูลต้นฉบับ

# Normalization

![image](https://github.com/phurisk/BSC_DPDM23/assets/137043070/59859ef0-f33b-4908-a900-dbae849a4011)
- Min-max normalization: เป็นการปรับขนาดข้อมูลอยู่ในช่วงใหม่ที่กำหนด โดยที่ค่าต่ำสุดและสูงสุดของข้อมูลจะถูกแปลงไปเป็นค่าใหม่ที่กำหนด เช่น ค่า 0,1

![image](https://github.com/phurisk/BSC_DPDM23/assets/137043070/b18d3306-f8fb-4ef0-a97b-ebf00a1ba38b)
- Z-score normalization: เป็นการปรับขนาดข้อมูลโดยใช้ค่าเฉลี่ย (μ) และส่วนเบี่ยงเบนมาตรฐาน (σ) ของข้อมูล เช่น ค่า Z-score

![image](https://github.com/phurisk/BSC_DPDM23/assets/137043070/5bb14a8c-a772-4f10-ab94-f261904dbc46)
- Normalization by decimal scaling: การปรับขนาดข้อมูลโดยการเลื่อนจุดทศนิยมของข้อมูล จำนวนทศนิยมที่เลื่อนขึ้นอยู่กับค่าสูงสุดของข้อมูลที่ได้ เช่น ข้อมูลมีค่า -945 ถึง 900 จากนั้นนำค่าสัมบูรณ์ที่มากที่สุดของข้อมูล ดังนั้นจึงนำ -945 มาหาร 1000 เนื่องจาก j = 3 โดยที่ j มาจากการประมาณค่าจาก log ฐาน 10 ของ |-945| 





# Example training data set

# Decision Tree
![Blank diagram](https://github.com/phurisk/BSC_DPDM23/assets/137043070/f76cb092-fd0e-441b-814a-c29cac92d121)

- Root Node: โหนดแรกสุดของโครงสร้างต้นไม้ตัดสินใจ
- Branch: เส้นที่เชื่อมระหว่างโหนดหนึ่งไปยังอีกโหนดหนึ่ง แทนการตัดสินใจหรือเงื่อนไข และนำไปสู่โหนดย่อยต่อไป
- Leaf Node: โหนดสุดท้ายในต้นไม้การตัดสินใจ แสดงผลลัพธ์หรือการตัดสินใจสุดท้าย



