---
title: FAQ
description: FAQ
---

# คำถามที่พบบ่อย

## 1. สิ่งที่ควรทำ

### 1.1 ออโต้คลิกเกอร์ไม่ทำงาน?

หากออโต้คลิกเกอร์ไม่สามารถเริ่มทำงานได้ นั่นหมายความว่าสิทธิ์การเข้าถึงไม่ได้ถูกเปิดใช้งานหรือหมดอายุแล้ว ปิดและเริ่มต้นบริการการเข้าถึงใหม่เพื่อแก้ไขปัญหานี้

**วิธีการใช้งาน** - `ตัวอย่างเช่น ในโหมดเป้าหมายหลายจุด`

1. เปิดใช้งานโหมดเป้าหมายหลายจุด คลิก "+" ในเมนูลอยที่ปรากฏขึ้นเพื่อเพิ่มเป้าหมายการคลิก และย้ายไปยังตำแหน่งที่เหมาะสม
2. ตั้งค่าช่วงเวลาหน่วงและระยะเวลาสำหรับเป้าหมายการคลิก (ค่ายิ่งน้อยยิ่งทำให้ความเร็วในการคลิกเร็วขึ้น)
3. คลิกปุ่มเล่นที่ด้านบนของเมนูลอยเพื่อเริ่มการคลิกอัตโนมัติ

### 1.2 ความเร็วในการคลิกไม่เร็วพอ?

มีสองวิธีในการแก้ไข:

1. ก่อนเริ่มใช้งานออโต้คลิกเกอร์ โปรดเข้าไปในการตั้งค่าเริ่มต้นและเปลี่ยนค่าความเร็วเป็นเร็ว (1 มิลลิวินาที) จากนั้นเริ่มใช้งานออโต้คลิกเกอร์
2. หลังจากเริ่มใช้งานออโต้คลิกเกอร์ คลิกที่เป้าหมายเพื่อปรับเปลี่ยนช่วงเวลาหน่วงและระยะเวลา (ค่ายิ่งน้อยยิ่งทำให้ความเร็วในการคลิกเร็วขึ้น)

### 1.3 ไม่สามารถหยุดออโต้คลิกเกอร์ได้?

คุณสามารถกดปุ่มเปิด/ปิดเพื่อปิดหน้าจอ; ออโต้คลิกเกอร์จะหยุดทำงานเมื่อหน้าจอปิด

### 1.4 ออโต้คลิกเกอร์หยุดทำงานหลังจากทำงานไปสักพัก?

1. เมื่อช่วงเวลาที่ตั้งไว้น้อยกว่า 40 มิลลิวินาที อุปกรณ์มือถืออาจไม่มีเวลาตอบสนองเพียงพอ ซึ่งอาจทำให้ออโต้คลิกเกอร์ทำงานไม่ได้ แนะนำไม่ให้ทำการคลิกเร็วเป็นเวลานานหรือเพิ่มเวลาช่วงเวลาอย่างเหมาะสม
2. เมื่อการใช้พลังงานของแบตเตอรี่โทรศัพท์เพิ่มขึ้นอย่างรวดเร็ว ระบบอาจปิดแอปพลิเคชันในพื้นหลัง คุณสามารถแก้ไขปัญหานี้ผ่าน [Auto Start](https://dontkillmyapp.com/) และ [Ignore Battery Optimization Permission](https://dontkillmyapp.com/).

> หากวิธีการด้านบนไม่สามารถแก้ไขปัญหาได้ คุณสามารถรีสตาร์ทแอป

### 1.5 ออโต้คลิกเกอร์ยังไม่เปิดหลังจากเปิดใช้งานสิทธิ์การเข้าถึง?

1. ตรวจสอบให้แน่ใจว่าสิทธิ์การเข้าถึงถูกเปิดใช้งานอย่างถูกต้อง
2. ปิดการใช้งานสิทธิ์การเข้าถึงแล้วเปิดใหม่ หรือปิดและเริ่มต้นแอปพลิเคชันใหม่

> หากปัญหายังคงมีอยู่ โปรดรีสตาร์ทโทรศัพท์ของคุณ

## 2. ทำไม

### 2.1 ทำไมต้องรีสตาร์ทสิทธิ์การเข้าถึงเสมอ?

สิทธิ์การเข้าถึงเป็นสิทธิ์ของระบบ และ Android มีข้อกำหนดที่เข้มงวดสำหรับมัน เราไม่สามารถควบคุมได้
อย่างไรก็ตาม คุณสามารถแก้ไขปัญหานี้โดยการตั้งค่า [Auto Start](https://dontkillmyapp.com/)

### 2.2 ไม่สามารถคลิกหรือเลื่อนหน้าจอได้ขณะที่ออโต้คลิกเกอร์กำลังทำงาน?

เนื่องจากออโต้คลิกเกอร์ทำงานด้วยความเร็วสูง หากคุณควบคุมหน้าจอขณะที่มันกำลังทำงาน หน้าจอโทรศัพท์อาจไม่รู้จักท่าทางของคุณ

> หากคุณต้องการท่าทางอื่น แนะนำให้หยุดออโต้คลิกเกอร์ก่อน หรือเพิ่มเป้าหมายการคลิกหรือเลื่อนเพิ่มเติมเพื่อแก้ไขปัญหานี้
