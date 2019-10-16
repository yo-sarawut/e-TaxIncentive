# My Book

Welcome in my book!

โครงสร้างข้อมูลใบขนสินค้าขาเข้า
===


## เงื่อนไขการบันทึกข้อมูล ในกรณีผู้บันทึกไม่สามารถหาข้อมูลได้

1. หาก Field ใด กำหนดให้ต้องระบุค่า **(Value = M)** แต่ผู้บันทึกไม่สามารถหาข้อมูลได้
	- สำหรับ Field ที่เป็น Alphabet (แสดงออกเป็นตัวอักษร) ให้ระบุค่าเป็น N/A
	- สำหรับ Field ที่เป็น Numeric (แสดงออกเป็นตัวเลข) ให้ระบุค่าเป็น 0 (ศูนย์)
2. หาก Field ใด กำหนดให้ไม่ต้องระบุค่า **(Value = O)** และผู้บันทึกไม่สามารถหาข้อมูลได้ ก็ไม่ต้องบันทึกค่าใด ๆ
3. หาก Field ใด กำหนดให้ต้องระบุค่า เมื่อเข้าเงื่อนไขที่กำหนด **(Value = C)** แต่ผู้บันทึกไม่สามารถหาข้อมูลได้
	- สำหรับ Field ที่เป็น Alphabet (แสดงออกเป็นตัวอักษร) ให้ระบุค่าเป็น N/A
	- สำหรับ Field ที่เป็น Numeric (แสดงออกเป็นตัวเลข) ให้ระบุค่าเป็น 0 (ศูนย์)

## อักษรย่อ ที่ใช้ในการอธิบายรูปแบบชนิดของข้อมูล
|อักษรย่อ  |คำอธิบาย|
|---|---|
|n3|	ข้อมูลชนิดตัวเลข (Numeric Characters) คงที่ คือ 3 ตัวอักษร|
|a3|	ข้อมูลชนิดตัวอักษร (Alphabetic Characters) คงที่ คือ 3 ตัวอักษร|
|an3|	ข้อมูลชนิดตัวอักษรหรือตัวเลข คงที่ คือ 3 ตัวอักษร|
|n..3|	ข้อมูลชนิดตัวเลขความยาวข้อมูลแปรผันตามความยาวสูงสุด 3 ตัวอักษร|
|a..3|	ข้อมูลชนิดตัวอักษรความยาวข้อมูลแปรผันตามความยาวสูงสุด 3 ตัวอักษร|
|an..3|	ข้อมูลชนิดตัวอักษรหรือตัวเลขความยาวข้อมูลแปรผันตามความยาวสูงสุด 3 ตัวอักษร|
|n..16,2|ข้อมูลชนิดตัวเลขความยาวข้อมูลแปรผันตามความยาวสูงสุด 16 ตัวอักษรรวมความยาวทศนิยมสูงสุด 2 ตัวอักษร|

## โครงสร้างข้อมูลใบขนสินค้าขาเข้า แบ่งได้เป็น 6 ส่วนดังนี้

1. [**Import Declaration Control**](#import-declaration-control)	ประกอบด้วย	73 Fields
2. [**Import Invoice Control**](#import-invoice-control)	ประกอบด้วย	35 Fields
3. [**Import Invoice Detail**](#import-invoice-detail)	ประกอบด้วย	76 Fields
4. [**Import Invoice Detail (Duty)**](#import-invoice-duty)	ประกอบด้วย	14 Fields
5. [**Import Invoice Detail (Permit)**](#import-invoice-permit)	ประกอบด้วย	 3 Fields
6. [**Import Invoice Detail (Deposit)**](#import-invoice-deposit)	ประกอบด้วย	 2 Fields


### Import Declaration Control


![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page7.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page8.png)
![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page9.png)
![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page10.png)
![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page11.png)
![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page12.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page13.png)
![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page14.png)
![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page15.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page16.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page17.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page18.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page19.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page20.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page21.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page22.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page23.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page24.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page25.png)

### Import Invoice Control


![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page26.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page27.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page28.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page29.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page30.png)

### Import Invoice Detail

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page31.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page32.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page33.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page34.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page35.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page36.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page37.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page38.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page39.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page40.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page41.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page42.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page43.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page44.png)


### Import Invoice Duty

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page45.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page46.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page47.png)

### Import Invoice Permit

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page48.png)

![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page49.png)


### Import Invoice Deposit
![enter image description here](https://github.com/yosarawut/WorkingArea/raw/master/KnowledgeCenter/e-Customs/e-Import/e-Import-manual/img/e-Import_2018png_Page50.png)



