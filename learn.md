# What I learned
## HTML
* ``` &copy; ```  จะได้ --> ©
* ```<spand> </spand> ``` จะ inline ต่างกับ ```<div> </div>``` ที่จะเป็น block ขึ้นบรรทัดใหม่เสมอ

## CSS
* ท่าทำหรับใช้ font โหลดมา
```css
* {
    /*ท่ามาตรฐาน การเริ่มต้น*/
    padding: 0;
    margin: 0;
    /*----------------*/

    box-sizing: border-box;
    font-family: 'Kanit';
}

@font-face {
    font-family: 'kanit';
    src: url('./Kanit/Kanit-Light.ttf');
}
```

* ```opacity: 1;  ```   ใช้ลูกเล่นนี้แทนการเปลี่ยนสีก็ได้
* ```transition: 0.5s;```   ใส่ ให้ดูสมูท

**ตัวอย่างการใช้**
```css
.footerNav li{
    color: white;
    margin: 20px;
    text-decoration: none;
    list-style: none;
    font-size: 1.1em;
    opacity: 0.7;
    transition: 0.5s; /*ใส่ ให้ดูสมูท*/
}
.footerNav li:hover{
    opacity: 1; 
    cursor: pointer;
}
```