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


## Homework
- [Hw.2](https://github.com/phurisk/BSC_DPDM23/blob/main/Hw2.pdf)
- [Hw.5](https://github.com/phurisk/BSC_DPDM23/blob/main/Hw_5_%E0%B8%A0%E0%B8%B9%E0%B8%A3%E0%B8%B4%E0%B8%A8.pdf)

## Quiz
- [Quiz9(Last)](https://github.com/phurisk/BSC_DPDM23/blob/main/426557531_311318285255165_3616148309199044172_n.jpg)

 # Data mining
 
  ## Knowledge Discovery (KDD) Process
 ![image](https://github.com/phurisk/BSC_DPDM23/assets/137043070/4440bd5e-39c1-4ed8-bcbb-191ce43f82a6)

 
- การทำความสะอาดข้อมูล (Data Cleaning): การกำจัดข้อมูลที่ไม่ต้องการหรือไม่เกี่ยวข้อง เช่น โค้ด HTML, สคริปต์ JavaScript หรือข้อมูลที่ซ้ำซ้อน เพื่อให้เหลือเพียงข้อมูลที่เป็นประโยชน์สำหรับการวิเคราะห์.

- การผสานข้อมูลจากแหล่งต่างๆ (Data Integration): การรวมข้อมูลที่มาจากหลายแหล่ง หรือหลายหน้าเว็บ เพื่อสร้างมุมมองที่ครอบคลุมและสมบูรณ์.

- การทำ Data Warehouse: การสร้างคลังข้อมูลเพื่อเก็บข้อมูลที่ได้มา โดยจะมีการออกแบบโครงสร้างของคลังข้อมูลเพื่อรองรับการวิเคราะห์ข้อมูลในอนาคต.

- การสร้าง Data Cube Construction: สร้างโครงสร้างข้อมูลหลายมิติ เพื่อให้สามารถวิเคราะห์ข้อมูลได้ในหลายมิติและหลายระดับ.

- การเลือกข้อมูลสำหรับ Data Mining: คัดเลือกข้อมูลที่เหมาะสมและเกี่ยวข้องกับเป้าหมายของการทำเหมืองข้อมูล โดยข้อมูลนี้จะถูกนำไปใช้ในขั้นตอนถัดไป.

- Data Mining: การใช้เทคนิคและอัลกอริทึมในการทำData Mining เพื่อค้นหารูปแบบ, ความสัมพันธ์, หรือความรู้ที่ซ่อนอยู่ในข้อมูล.

- การนำเสนอผลการทำ Data Mining: การนำเสนอผลลัพธ์ของการทำเหมืองข้อมูลในรูปแบบที่เข้าใจง่าย เช่น รายงาน, แผนภูมิ, หรือการแสดงผลในรูปแบบกราฟิก เพื่อให้ผู้ใช้สามารถเข้าใจและใช้ประโยชน์จากข้อมูลให้ได้มากที่สุด.



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


# Example  K-means clustering

![image](https://github.com/phurisk/BSC_DPDM23/assets/137043070/0fb484a3-2996-4622-8d4a-b8754c0c972f)



- การเริ่มต้น  : อัลกอริธึมเริ่มต้นด้วยการสุ่มเลือกจุด K จากชุดข้อมูลเป็นเซนทรอยด์เริ่มต้น   เซนทรอยด์เหล่านี้เป็นตัวแทนของศูนย์กลางของกลุ่ม K 

- ขั้นตอนการกำหนด  : แต่ละจุดข้อมูลในชุดข้อมูลถูกกำหนดให้กับเซนทรอยด์ที่ใกล้ที่สุด โดยสร้าง K คลัสเตอร์   โดยทั่วไประยะห่างระหว่างจุดข้อมูลและเซนทรอยด์จะคำนวณโดยใช้ระยะทางแบบยุคลิด แต่ก็สามารถใช้การวัดระยะทางอื่นๆได้

- ขั้นตอนการอัปเดต  : หลังจากกำหนดจุดข้อมูลทั้งหมดให้กับคลัสเตอร์แล้ว เซนทรอยด์จะถูกคำนวณใหม่เป็นค่าเฉลี่ยของจุดข้อมูลทั้งหมดที่กำหนดให้กับแต่ละคลัสเตอร์   และจะย้ายเซนทรอยด์ไปยังตำแหน่งใหม่ภายในชุดข้อมูล 

- ทำซ้ำ  : ขั้นตอนที่ 2 และ 3 จะถูกทำซ้ำซ้ำๆ จนกว่าเซนทรอยด์จะไม่เปลี่ยนแปลง หรือถึงจำนวนการวนซ้ำที่กำหนดไว้ล่วงหน้าแล้ว 




