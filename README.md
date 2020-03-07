# WT Library (fiwz13)

สวัสดีจร้าาาา นี่ cheezetata เอง ไลบรารี่นี้ใช้สำหรับฝึกสร้างไลบรารี่เป็นของตัวเอง ความสามารถคือ

  - แสดงชื่ WT ภาษาอังกฤษ 
  - แสดงชื่อ WT ภาษาไทย


### วิธีติดตั้งแสนง่าย

เราจะติดตั้งผ่านเจ้า pip

```sh
pip install fiwz13
```

ง่ายไหมล่ะ

วิธีใช้ก็ง่ายมาก
- เปิด Python แล้วพิพม์ตามนี้เลย

```sh
from fiwz13 import Fiwz

myme = Fiwz()

    print(help(myme.WhoIAm))

    print(myme)
    print(myme.name)
    print(myme.lastname)
    print(myme.nickname)
    print(myme.thainame())

    myme.WhoIAm()
    mymeemail = myme.email
    print(mymeemail)


    print('-------------')
    myyou = Fiwz()

    myyou.name = 'Rattya'
    myyou.lastname = 'KP'
    myyou.nickname = 'Bell'
    myyou.WhoIAm()

    print(myyou.name)
    print(myyou.lastname)
    print(myyou.nickname)
```

### Visit

แวะเข้าไปเยี่ยมชมกันได้ แหล่งกบดานเรามีสอนหลายวิชา

| สร้างไฟล์ README  | https://dillinger.io/ |

### CREDIT  WT

