## โจทย์ปัญหา
**การแข่งขันกีฬาโอลิมปิก**

การแข่งกีฬาโอลิมปิกของ KU นี้มีการแข่งขั้นกีฬา 3 ประเภท คือ วิ่ง 100เมตร พุ่งแหลน และยิงเป้า โดยจะแข่งขันแบบเก็บคะแนนทั้ง 3 ประเภทเพื่อเทียบคะแนน ในการจัดลำดับ โดย วิ่ง ถ้าเป็นผู้ชายวิ่ง ต่ำกว่า 8 วินาที ได้ 10แต้ม ต่ำกว่า 10 ได้ 7 แต้ม และ ต่ำกว่า 12 ได้ 5 แต้ม ถ้ามากกว่านั้น จะไม่ได้คะแนน แต่ถ้าวิ่งได้เวลาน้อยกว่ายูเซมโบวที่เคยทำมา 7.31 จะได้เงินรางวัล 200,000 บาท ต่อมา กีฬาพุ่งแหลน จะวัดจากระยะทาง โดยสามารถกำหนดว่าจะ ลงเล่น 3 คน ปาคนละ 1 ครั้ง แต้มที่ได้คือ ถ้าปา 100เมตรได้ 5 คะแนน 150 เมตร 7 คะแนน 200 เมตร 10 คะแนน และถ้าได้ 250 เมตรขึ้นไป จะได้เงินรางวัล 50,000 บาท ต่อมาการยิงเป้า จะมีการปาเป้าให้ยิง 20 อัน ถ้ายิงโดน 20 ครั้ง ได้ 10 คะแนน พร้อมเงินรางวัล 100,000 บาท ถ้าได้ 17 ครั้ง ได้ 7 คะแนน ถ้า 14 ครั้ง ได้ 5 คะแนน ถ้ามีข้อผิดพลาดให้ป้อนใหม่อีกครั้ง โดยไม่เอาค่าที่ผิดมาคำนวณ เมื่อการแข่งขันจบทุกอย่างจะมีการรวมคะแนนเพื่อเทียบเหรียญรางวัลที่จะได้รับ ถ้ามากกว่าเท่ากับ 27 คะแนน จะได้เหรียญทอง ถ้ามากกว่าเท่า 24 คะแนนเหรียญเงิน และ มากกว่าเท่ากับ 21 ได้เหรียญทองแดง และยังเอาคะแนนในการแข่งขั้นมาแปลงเป็นเงินได้ เท่ากับ คะแนนละ 5,000 บาท แต่ถ้าคะแนนไม่ถึง 10 คะแนนจะไม่มีการแปลงเงินของคะแนนการแข่งขัน

**ความต้องการของโจทย์ปัญหา**

จากโจทย์ปัญหาข้างต้นต้องการทราบว่าการแข่งขันกีฬาของแต่ละทีมได้เหรียญรางวัลหรือไม่และได้เหรียญรางวัลประเภทใดและยังต้องการทราบว่าการแข่งขันของแต่ละทีมนั้นได้เงินรางวัลเป็นจำนวนเท่าใด

**ข้อมูลนำเข้า**

1. ชื่อทีม
2. วิ่งได้กี่วินาที
3. ปาครั้งที่ 1 ได้กี่เมตร
4. ปาครั้งที่ 2 ได้กี่เมตร
5. ปาครั้งที่ 3 ได้กี่เมตร
6. ยิงเป้าได้กี่ครั้ง

**ข้อมูลนำออก**

1. คะแนนสะสมทั้งหมดของกีฬาทั้งสามประเภท
2. เหรียญรางวัล (ถ้าคะแนนสะสมน้อยกว่า 21 จะไม่แสดงผลของเหรียญรางวัล)
3. จำนวนเงินทั้งหมดที่ได้จากการแข่งขัน

**Test case**

ตัวอย่างผลลัพย์ที่ 1 <br/>
Team : ku <br/>
Run : 5 <br/>
Throw_1 : 260 <br/>
Throw_2 : 300 <br/>
Throw_3 : 320 <br/>
Target_shooting 0-20 : 19<br/>
Totalscore : 47 <br/>
Medal : Gold Medal<br/>
Money : 585000

ตัวอย่างผลลัพย์ที่ 2 <br/>
Team : one <br/>
Run : 7 <br/>
Throw_1 : 90 <br/>
Throw_2 : 98 <br/>
Throw_3 : 120 <br/>
Target_shooting 0-20 : 14<br/>
Totalscore : 20 <br/>
Money : 300000