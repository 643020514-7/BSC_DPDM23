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
# - Chapter 1. Introduction

  # Table of Contents

1. [Why Data Mining?](#why-data-mining)
2. [What Is Data Mining?](#what-is-data-mining)
3. [A Multi-Dimensional View of Data Mining](#a-multi-dimensional-view-of-data-mining)
4. [What Kinds of Data Can Be Mined?](#what-kinds-of-data-can-be-mined)
5. [What Kinds of Patterns Can Be Mined?](#what-kinds-of-patterns-can-be-mined)
6. [What Kinds of Technologies Are Used?](#what-kinds-of-technologies-are-used)
7. [What Kinds of Applications Are Targeted?](#what-kinds-of-applications-are-targeted)
8. [Major Issues in Data Mining](#major-issues-in-data-mining)
9. [A Brief History of Data Mining and Data Mining Society](#a-brief-history-of-data-mining-and-data-mining-society)
10. [Summary](#summary)

## 1. Why Data Mining?
- เนื่องจากปริมาณข้อมูลได้เพิ่มขึ้นอย่างต่อเนื่องจนถึงระดับที่สูงมาก จากTerabytesถึงPetabytes สถานการณ์นี้เกิดขึ้นจากหลายปัจจัย เช่น การสะสมข้อมูลอัตโนมัติ ระบบฐานข้อมูล เครื่องมือเก็บข้อมูลบนเว็บ และการกระจายของสังคมคอมพิวเตอร์ไว้ทั่วไป
- เนื่องจากมีข้อมูลอยู่มาก แต่ไม่สามารถนำมาใช้ได้เพราะขาดความรู้ที่สามารถนำข้อมูลเหล่านี้มาใช้จริงได้
- การทำ Data Mining จึงเป็นสิ่งที่สำคัญ โดยการทำการวิเคราะห์ข้อมูลอัตโนมัติจากชุดข้อมูลขนาดใหญ่ เพื่อหารูปแบบ แนวโน้ม เพื่อนำข้อมูลมาใช้ได้อย่างมีมูลค่ามากที่สุด

## 2. What Is Data Mining?

### การทำ Data Mining 
การทำเหมืองข้อมูลคือเทคนิคที่ใช้คอมพิวเตอร์ช่วยในการวิเคราะห์เพื่อประมวลผลและสำรวจชุดข้อมูลขนาดใหญ่ เมื่อใช้เครื่องมือและวิธีการทำเหมืองข้อมูล องค์กรสามารถค้นพบรูปแบบและความสัมพันธ์ที่ซ่อนอยู่ในข้อมูลของตน การทำเหมืองข้อมูลแปลงข้อมูลดิบเป็นความรู้เชิงปฏิบัติ บริษัทใช้ความรู้นี้ในการแก้ไขปัญหา วิเคราะห์ผลกระทบในอนาคตของการตัดสินใจทางธุรกิจ และเพิ่มขอบเขตกำไรของบริษัท

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

## 4. What Kinds of Data Can Be Mined?

## 5. What Kinds of Patterns Can Be Mined?

## 6. What Kinds of Technologies Are Used?

## 7. What Kinds of Applications Are Targeted?

## 8. Major Issues in Data Mining

## 9. A Brief History of Data Mining and Data Mining Society

## 10. Summary
