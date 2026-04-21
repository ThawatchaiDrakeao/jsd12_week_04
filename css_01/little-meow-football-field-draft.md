<!DOCTYPE html>
<html lang="en">
<head>
   

    <style>
        /* 1. ประกาศตัวแปรสี (กล่องเก็บสี) */
        :root {
            --bg-main: #1c0333;      
            --card-bg: #360f5a;      
            --primary-btn: #6a329f;  
            --text-color: #e2d5f0;   
        }

        /*  สรุปเรื่อง CSS Variables (--variables)
  ---------------------------------------
  :root { ... } 
  คือการประกาศตัวแปรไว้ที่จุดสูงสุด (Global) 
  เพื่อให้ทุก Elements ในหน้าเว็บสามารถดึงค่าไปใช้ได้
*/

/*:root 
   {
    /* --ชื่อตัวแปร: ค่าที่ต้องการ; */
    
   /* --bg-main: #1c0333;      /* สีพื้นหลังหลัก (ม่วงเข้มมาก) */
   /* --card-bg: #360f5a;      /* สีพื้นหลังของ Card หรือกล่องเนื้อหา */
    /*--primary-btn: #6a329f;  /* สีหลักของปุ่มกด */
   /* --text-color: #e2d5f0;   /* สีตัวอักษร (ม่วงอ่อนเกือบขาว) 
    } 
 
/*  วิธีนำไปใช้งาน:
  ใช้ฟังก์ชัน var(--ชื่อตัวแปร) เช่น:
  
  body {
      background-color: var(--bg-main);
      color: var(--text-color);
  }
  
  button {
      background-color: var(--primary-btn);
  }
  
  ข้อดี: ถ้าอยากเปลี่ยนธีมสีทั้งเว็บ 
  แค่มาแก้เลข Code สีที่ :root จุดเดียวจบ! 
*/
        
        
        
        /* 2. สั่งให้สีทำงาน (หยิบสีมาใช้) */
        body {
            background-color: var(--bg-main); /* ใช้สีม่วงเข้มเป็นพื้นหลัง */
            color: var(--text-color);         /* ใช้สีอ่อนเป็นตัวอักษร */
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
        }

       
/*body
    {

    /* 1. กำหนดสีพื้นหลังของทั้งหน้าเว็บ โดยดึงค่ามาจากตัวแปร --bg-main ที่เราตั้งไว้ใน :root 
    background-color: var(--bg-main); 

    /* 2. กำหนดสีของตัวอักษรหลักในหน้าเว็บ โดยดึงค่ามาจากตัวแปร --text-color 
    color: var(--text-color);         

    /* 3. เลือกฟอนต์ที่จะใช้ (ในที่นี้คือ Arial ถ้าไม่มีให้ใช้ฟอนต์ตระกูล sans-serif ที่เครื่องนั้นมี) 
    font-family: Arial, sans-serif;

    /* 4. กำหนดระยะห่างภายนอกขอบของ body ให้เป็น 0 (เพื่อไม่ให้หน้าเว็บมีขอบขาวว่างๆ รอบตัว) 
    margin: 0;

    /* 5. กำหนดระยะห่างภายใน (ช่องว่างระหว่างขอบหน้าจอกับเนื้อหาข้างใน) ให้ห่างออกมา 20px */
    /*padding: 20px;  

    } */

     























        .lmff 
        {
            color: var(--primary-btn); /* ใช้สีม่วงสว่างกับหัวข้อ */
            text-align: center;
        }
       


       /* การกำหนดสไตล์ให้ Class ชื่อ lmff 
   โดยใช้ตัวแปรสีที่ประกาศไว้ก่อนหน้า
*/

/*.lmff 

{
    /* เรียกใช้ค่าจากตัวแปร --primary-btn (#6a329f) มากำหนดเป็นสีข้อความ 
    color: var(--primary-btn); 
    
    /* กำหนดให้ข้อความจัดวางอยู่กึ่งกลางของ Element 
    text-align: center;
}


/* เพิ่มเติม:
   หากใน :root ไม่มีการประกาศตัวแปร --primary-btn ไว้ 
   เบราว์เซอร์จะไม่แสดงสีนี้ ดังนั้นต้องตรวจสอบให้มั่นใจว่าชื่อตัวแปรสะกดตรงกัน
*/


    </style>
</head>












<body>
    <h1 id="lmff" class="lmff"> Little Meow Football Field </h1>
    
    <p>ยินดีต้อนรับสู่สนามฟุตบอลของคนรักแมว</p>
</body>



</html>