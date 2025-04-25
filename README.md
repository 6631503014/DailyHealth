# DailyHealthWater
Chawin Thachai 6631503014

ชื่อ - นามสกุล (Full Name): Chawin Thachai

รหัสนักศึกษา (Student ID): 6631503014

ตอนเรียน (Section) : 1

ชื่อแอป (App Name): DailyHealth

Framework ที่ใช้ (Framework Used):  React Native / อื่น ๆ

ลิงก์ GitHub Repository: https://github.com/6631503014/DailyHealth

ลิงก์ไฟล์ติดตั้ง (APK/IPA): -

----------------

1. การออกแบบแอป | App Concept and Design (2 คะแนน / 2 pts)
1.1 ผู้ใช้งานเป้าหมาย | User Personas

Persona 1:

ชื่อ: ปิ๊ก

อายุ: 22 ปี

อาชีพ: นักศึกษาปี 

ความต้องการ: อยากมีแอปช่วยเตือนให้ดื่มน้ำระหว่างเรียน เพราะมักลืมดื่มระหว่างวัน

Persona 2:

ชื่อ: ซอด้วง

อายุ: 27 ปี

อาชีพ: พนักงาน

ความต้องการ: อยากติดตามปริมาณการดื่มน้ำในแต่ละวัน 

1.2 เป้าหมายของแอป | App Goals

เตือนผู้ใช้ให้ดื่มน้ำสม่ำเสมอ

แสดงจำนวนแก้วน้ำที่ดื่มต่อวัน

UI น่ารัก เรียบง่าย ใช้งานง่าย

1.3 โครงร่างหน้าจอ / Mockup

หน้า Home: แสดงภาพแก้วน้ำ + ตัวการ์ตูนน่ารัก แสดงจำนวนแก้วที่ดื่มวันนี้ ปุ่ม "ดื่มแล้ว" 

หน้า Settings:
ตั้งเวลาเตือน เช่น ทุก 1 ชม. เปิด/ปิดเสียงเตือน

หน้า History:
แสดงการดื่มน้ำที่เราส่งไป


1.4 การไหลของผู้ใช้งาน | User Flow

เปิดแอป > เข้าหน้า Home > กด “ดื่มแล้ว” > หน้าบันทึกจำนวนแก้ว > ตั้งเตือนในหน้า Settings 

--------------

2. การพัฒนาแอป | App Implementation (4 คะแนน / 4 pts)
2.1 รายละเอียดการพัฒนา | Development Details

เครื่องมือที่ใช้ / Tools used:

React Native
Expo
Package: react-navigation, react-native-svg, react-native-vector-icons, expo-notifications, react-native-animated, Reanimated

2.2 ฟังก์ชันที่พัฒนา | Features Implemented

Checklist:
- [x] นับจำนวนแก้วน้ำที่ดื่มในแต่ละวัน
- [x] แจ้งเตือนให้ดื่มน้ำทุก 1 ชั่วโมง
- [x] หน้าแสดงกราฟการดื่มน้ำ
- [ ] เชื่อม Firebase เพื่อบันทึกข้อมูล

2.3 ภาพหน้าจอแอป | App Screenshots
แนบภาพหรือ URL (Attach images or image links):
![image](https://github.com/user-attachments/assets/60407808-0b01-40c3-9238-d4da181039b1)
![image](https://github.com/user-attachments/assets/a88d0662-24b3-4fc1-97c3-4aade1866352)
![image](https://github.com/user-attachments/assets/198ff74a-f819-4198-86c5-747a64778807)

----------------

# 3. การ Build และติดตั้งแอป | Deployment (2 คะแนน / 2 pts)
3.1 ประเภท Build | Build Type

[x] Debug
[ ] Release
3.2 แพลตฟอร์มที่ทดสอบ | Platform Tested

[x] Android
[ ] iOS

3.3 ไฟล์ README และวิธีติดตั้ง | README & Install Guide
แนบไฟล์หรือคำอธิบายการติดตั้งแอป | Insert steps

1. เปิดผ่านทาง npx expo start

----------------------------------------------------------------

4. การสะท้อนผลลัพธ์ | Reflection (2 คะแนน / 2 pts)


-ปัญหา Notification บางครั้งไม่แจ้งเตือน ต้องใช้ Expo Development Build
-เรียนรู้การตั้งเวลาเตือนแบบ repeats ใน Expo Notification
-อยากพัฒนาให้เชื่อมกับ Firebase เพื่อแสดงข้อมูลย้อนหลังและใช้งานหลายเครื่อง

----------------------------------------------------------------

5. การใช้ AI ช่วยพัฒนา | AI Assisted Development (Bonus / ใช้ประกอบการพิจารณา)
5.1 ใช้ AI ช่วยคิดไอเดีย | Idea Generation

Prompt ที่ใช้:

"ช่วยคิดไอเดียแอพสุขภาพเตือนดื่มน้ำ น่ารักๆ "

ผลลัพธ์:

ได้แนวคิดแอพ DailyHealthWater ใช้ตัวละครหยดน้ำช่วยเตือน มีปุ่มกด “ดื่มแล้ว” และแสดงกราฟ

5.2 ใช้ AI ช่วยออกแบบ UI | UI Layout Prompt

Prompt ที่ใช้:

"ช่วยออกแบบ layout แอพเตือนดื่มน้ำแบบน่ารัก มีหน้า Home, Settings, History"

ผลลัพธ์:

ได้ layout ที่เน้นกลางจอ มีภาพแก้วน้ำและตัวการ์ตูน พร้อม Bottom Tab Navigation

5.3 ใช้ AI ช่วยเขียนโค้ด | Code Writing Prompt

Prompt ที่ใช้:

"เขียน React Native ด้วย Expo ให้มีแจ้งเตือนทุก 1 ชั่วโมง และแสดงจำนวนแก้วที่ดื่ม"

ผลลัพธ์:

ได้โค้ดแจ้งเตือนด้วย expo-notifications และการใช้งาน useState 

5.4 ใช้ AI ช่วย debug | Debug Prompt

Prompt ที่ใช้:

"แก้ปัญหา Expo Notification แจ้งเตือนซ้ำซ้อนหรือไม่แจ้ง"

ผลลัพธ์:

AI แนะนำให้ใช้ cancelAllScheduledNotifications ก่อนตั้งใหม่ และใช้ development build แทน Expo Go

5.5 ใช้ AI ช่วย Deploy | Deployment Prompt

Prompt ที่ใช้:

"How to build and test an Expo app on Android device?"

ผลลัพธ์:

ได้ขั้นตอนการใช้ expo build หรือ npx expo start พร้อม scan QR code ผ่านแอป Expo Go เพื่อทดสอบบนเครื่องจริงprofile preview เพื่อทดสอบแอพได้ทันที
