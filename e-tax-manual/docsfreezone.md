## การโอนย้ายของออกจากสิทธิประโยชน์เขตปลอดอากร


![enter image description here](https://github.com/yosarawut/KnowledgeCenter/raw/master/img/e-tax-incentive/tranfer-freezone.jpg)

### การโอนย้ายของออกจากเขตปลอดอากร เพื่อโอนย้ายของเข้าโดยใช้สิทธิ์คลังสินค้าทัณฑ์บน
**ผู้นำของเข้า** ส่งใบขนสินค้าขาเข้าโอนย้ายออกจากเขตปลอดอากร **C** ให้ระบุค่าดังนี้
- ระบุ Release Port = รหัสสถานที่ตรวจปล่อยของเขตปลอดอากรที่นำออก ที่ส่วนควบคุมใน ใบขนสินค้า
- ระบุ Discharge Port = รหัสสถานที่รับบรรทุกของของเขตปลอดอากรที่นำออก ที่ส่วนควบคุมในใบขนสินค้า
- ระบุ Export Tax Incentives ID = เลขที่ทะเบียนสิทธิ์ประโยชน์เขตปลอดอากรที่นำของออกที่ส่วนควบคุมในใบขนสินค้า
- ระบุ Bond = Y ที่ส่วนรายการในใบขนสินค้า
- ระบุ Import Tax Incentives ID = เลขที่ทะเบียนสิทธิ์ประโยชน์คลังสินค้าทัณฑ์บนที่นำของเข้า ที่ส่วนรายการในใบขนสินค้า

### การโอนย้ายของออกจากเขตปลอดอากร เพื่อโอนย้ายของเข้าโดยใช้สิทธิ์ ขอคืนอากรตามมาตรา 29
**ผู้นำของเข้า** ส่งใบขนสินค้าขาเข้าโอนย้ายออกจากเขตปลอดอากร **C** ให้ระบุค่าดังนี้
- ระบุ Release Port = รหัสสถานที่ตรวจปล่อยของเขตปลอดอากรที่นำออก ที่ส่วนควบคุมใน ใบขนสินค้า
- ระบุ Discharge Port = รหัสสถานที่รับบรรทุกของของเขตปลอดอากรที่นำออก ที่ส่วนควบคุม ในใบขนสินค้า
- ระบุ Export Tax Incentives ID = เลขที่ทะเบียนสิทธิ์ประโยชน์เขตปลอดอากรที่นำของออกที่ส่วนควบคุมในใบขนสินค้า
- ระบุ Drawback = Y ที่ส่วนรายการในใบขนสินค้า
- ระบุ Import Tax Incentives ID = เลขทะเบียนผู้ใช้สิทธิประโยชน์ขอคืนอากรตามมาตรา 29ที่ส่วนรายการในใบขนสินค้า

### การโอนย้ายของออกจากเขตปลอดอากร เพื่อชำระค่าภาษีอากรบริโภคภายในประเทศ
**ผู้นำของเข้า** นำของออกบริโภคภายในประเทศ ผู้นำของออกจัดทำใบขนสินค้า **P** ให้ระบุค่าดังนี้
- ระบุ Release Port = รหัสสถานที่ตรวจปล่อยของเขตปลอดอากร ที่ส่วนควบคุมในใบขนสินค้า
- ระบุ Discharge Port = รหัสสถานที่รับบรรทุกของเขตปลอดอากร ที่ส่วนควบคุมในใบขนสินค้า
- ระบุ Export Tax Incentives ID = เลขที่ทะเบียนสิทธิ์ประโยชน์เขตปลอดอากรที่นำของออกที่ส่วนควบคุมในใบขนสินค้า
- กรณีประเภทย่อยของผู้ได้รับใบอนุญาตประกอบกิจการในเขตปลอดอากรเป็น ประเภทพาณิชยกรรม ให้ระบุ Reference Declaration Number = เลขที่ใบขนสินค้าขาเข้าที่นำสินค้าเข้าเก็บในเขตปลอดอากร ที่ส่วนรายการในใบขนสินค้า
- กรณีประเภทย่อยของผู้ได้รับใบอนุญาตให้ประกอบกิจการเป็น ประเภทพาณิชยกรรม ให้ระบุ Reference Declaration Line Number = รายการในใบขนสินค้าขาเข้าที่นำสินค้าเข้าเก็บในเขตปลอดอากรที่นำของออก ที่ส่วนรายการใน ใบขนสินค้า
- กรณีประเภทย่อยของผู้ได้รับใบอนุญาตให้ประกอบกิจการเป็น ประเภทพาณิชยกรรม ให้ระบุ Tariff Code = รหัสพิกัดศุลกากร ตามใบขนสินค้าขาเข้าและรายการในใบขนสินค้าขาเข้าที่นำสินค้าเข้าเก็บในเขตปลอดอากรที่นำของออก ที่ส่วนรายการในใบขนสินค้า
- กรณีประเภทย่อยของผู้ได้รับใบอนุญาตประกอบกิจการในเขตปลอดอากรเป็น ประเภทพาณิชยกรรม ให้ระบุ Statistical Code = รหัสสถิติสินค้า ตามใบขนสินค้าขาเข้าและรายการในใบขนสินค้าขาเข้าที่นำสินค้าเข้าเก็บในเขตปลอดอากรที่นำของออก ที่ส่วนรายการในใบขนสินค้า
- กรณีประเภทย่อยของผู้ได้รับใบอนุญาตประกอบกิจการในเขตปลอดอากรเป็น ประเภทพาณิชยกรรม ให้ระบุ Privilege Code ตามสิทธิ์ที่มีขณะนำเข้า เช่น มาตรา 12, WTO, TAU, AFTA เป็นต้น และต้องคำนวณค่าภาษีอากรตามปกติ ที่ส่วนรายการในใบขนสินค้า
- กรณีประเภทย่อยของผู้ได้รับใบอนุญาตประกอบกิจการในเขตปลอดอากรเป็น ประเภทพาณิชยกรรม ให้ระบุ Thai Description of Goods = ชนิดของ ภาษาไทย ตามใบขนสินค้าขาเข้าและรายการในใบขนสินค้าขาเข้าที่นำสินค้าเข้าเก็บในเขตปลอดอากรที่นำของออก ที่ส่วนรายการในใบขนสินค้า
- กรณีประเภทย่อยของผู้ได้รับใบอนุญาตประกอบกิจการในเขตปลอดอากรเป็น ประเภทพาณิชยกรรม ให้ระบุ English Description of Goods = ชนิดของ ภาษาอังกฤษ ตามใบขนสินค้าขาเข้าและรายการในใบขนสินค้าขาเข้าที่นำสินค้าเข้าเก็บในเขตปลอดอากรที่นำของออก ที่ส่วนรายการในใบขนสินค้า

### การโอนย้ายของออกจากเขตปลอดอากร เพื่อโอนย้ายของเข้าโดยใช้สิทธิ์เขตปลอดอากร
1. **ผู้ส่งออกของ** ส่งใบขนสินค้าขาออกโอนย้ายเข้าเขตปลอดอากร **(D)** ให้ระบุค่าดังนี้
	- ระบุ Release Port = รหัสสถานที่ตรวจปล่อยของเขตปลอดอากรที่นำออก ที่ส่วนควบคุมในใบขนสินค้า
	- ระบุ Load Port = รหัสสถานที่รับบรรทุกของของเขตปลอดอากรที่นำออก ที่ส่วนควบคุม ในใบขนสินค้า
	- ระบุ Export Tax Incentives ID = เลขที่ทะเบียนสิทธิ์ประโยชน์เขตปลอดอากรที่นำของออกที่ส่วนควบคุมในใบขนสินค้า
	- ระบุ Free Zone = Y ที่ส่วนรายการในใบขนสินค้า
	- ระบุ Import Tax Incentives ID = เลขที่ทะเบียนสิทธิ์ประโยชน์ผู้ได้รับใบอนุญาตประกอบกิจการในเขตปลอดอากรที่นำของเข้าที่ส่วนรายการในใบขนสินค้า
2. ผู้ได้รับใบอนุญาตจัดตั้งเขตปลอดอากร**ทำรายงานการยืนยันการโอนย้าย** สรุปให้กรมศุลกากร

### การโอนย้ายของออกจากเขตปลอดอากร เพื่อโอนย้ายของเข้าโดยใช้สิทธิ์เขตประกอบการเสรี
1. **ผู้ส่งออกของ** ส่งใบขนสินค้าขาออกโอนย้ายเข้าเขตประกอบการเสรี **D** ให้ระบุค่าดังนี้
	- ระบุ Release Port = รหัสสถานที่ตรวจปล่อยของเขตปลอดอากรที่นำออก ที่ส่วนควบคุมในใบขนสินค้า
	- ระบุ Load Port = รหัสสถานที่ของเขตปลอดอากรที่นำออก ที่ส่วนควบคุมในใบขนสินค้า
	- ระบุ Export Tax Incentives ID = เลขที่ทะเบียนสิทธิ์ประโยชน์เขตปลอดอากรที่นำของออกที่ส่วนควบคุมในใบขนสินค้า
	- ระบุ I-EAT Free Zone = Y ที่ส่วนรายการในใบขนสินค้า
	- ระบุ Import Tax Incentives ID = เลขที่ทะเบียนสิทธิ์ประโยชน์ผู้ประกอบการในเขตประกอบการเสรีที่นำของเข้าที่ส่วนรายการในใบขนสินค้า.

2. เจ้าของเขตประกอบการเสรีที่นำของเข้า**ทำรายงานสรุปการนำเข้า** ส่งให้กรมศุลกากร
