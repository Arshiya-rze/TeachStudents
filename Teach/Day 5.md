#### Tags Html
##### تعریف ساده‌ی تگ (Tag) در HTML
🧠 تعریف خیلی ساده:
تگ‌ها در HTML مثل دستورهایی هستن که به مرورگر می‌گن:
"این قسمت از متن یا صفحه باید چه کاری انجام بده یا چطوری نمایش داده بشه."

Tags
<h1>..<h6> => تگ های تیتر
<p> => تگ پاراگراف
<a> => تگ لینک
<button> => تگ دکمه
<image> => برای اضافه کردن عکس 
<br> تگ شکستن خط برای رفتن به خط بعدی
<label> => تگ گذاشتن لیبل برای input
<input> => …تگ برای گرفتن مشخصات مثله ایمیل, سن و  
<div> => تگ گروه بندی کردن در سایز کوچک
<section> => تگ برای گروه بندی کردن در سایز بزرگ تر

برای اینکه به بچه ها بگیم برن تگ های بیش تر رو self study کنن به این سایت اشاره میکنیم
W3schools
https://www.w3schools.com/TAGS/default.asp

سوال برای بچه ها پیش میاد که : چرا حتما باید ساختار HTML5 بزنیم بدون این ساختار هم که داره کار میکنه و خروجی بهمون میده.
جواب => 
مرورگرها یک قابلیتی به اسم **HTML error handling / error tolerance** دارن.  
یعنی اگر کد ناقص باشه، مرورگر خودش **ساختار پایه** رو حدس می‌زنه و به طور پیش‌فرض اضافه می‌کنه تا صفحه اجرا بشه.  
مثلاً وقتی اینو می‌نویسی:
<p>Hello World</p>
مرورگر پشت صحنه اینو تبدیل می‌کنه به چیزی مثل:
<!DOCTYPE html>
<html>
<head>
<title></title>
</head>
<body>
<p>Hello World</p>
</body>
</html>
پس حتی اگر ما ننویسیم، مرورگر خودش اضافه می‌کنه.
امکان استفاده از ویژگی‌های HTML5
اگر ساختار HTML5 رو ننویسی، بعضی تگ‌ها و قابلیت‌ها مثل:

<header>, <footer>, <section>, <article>, <nav>, <video>, <audio>

"شما دارید الان اصولی یاد می‌گیرید. همون‌طور که توی انشا اول «مقدمه، بدنه، نتیجه‌گیری» داریم، توی HTML هم باید شروع، وسط و پایان مشخص باشه. حتی اگر بدونش کار کنه، این کار مثل نوشتن انشا بدون مقدمه‌ست!"



Example Html tags =>

<h1>Hello</h1>
<h2>Im arshiya</h2>
<p>How old are you?</p>

<section> 
    <div>
        <label>Email</label>
        <input type="text">
        
        <label>Password</label>
        <input type="password">
    </div>
    
    <div>
        <label>Age</label>
        <input type="number">

        <label>Aya zende hasti?</label>
        <input type="checkbox">
    </div>

    <button>Register</button>
    <br>
    <a href="https://google.com">Boro be google</a>
</section>

CSS => 
inline css =>
<h1 style="background-color: red; color: white;">Hello</h1>
<h2 style="background-color: aqua; font-style: italic;">Im parsa</h2>

internal css => 
create style in header

style {
h1 {
color: 'red';
}
h2 {
color: 'green'
}
}

external css =>
create another file for example =>
style.css

BackgroundColor =>
چی هست؟ 
رنگ پس‌زمینه یک المان رو تعیین می‌کنه.
Color=>
چی هست؟
رنگ نوشته‌ها (فونت‌ها) رو مشخص می‌کنه.
FontSize =>
چی هست؟ 
اندازه نوشته رو تعیین می‌کنه
Border =>
چی هست؟
خط دور یک المان رو مشخص می‌کنه (ضخامت، نوع، رنگ).
Padding =>
 چی هست؟
فاصله بین محتوا و خط دور (border) رو تعیین می‌کنه.
Margin =>
چی هست؟
فاصله بین خود المان و دیگر المان‌ها رو تعیین می‌کنه.


BorderRadius =>
 چی هست؟
گوشه‌های المان رو گرد می‌کنه.


CSS style =>
backgroundColor, color, font-size, border: 2px solid red, padding, margin, border-radius

Px
مثال =>
درست کردن یه مربع و تبدیلیش به مربع های کوچک که هرکدوم از اون مربع های کوچیک میشه یه px
🧠 مثال ساده برای بچه‌ها:
تصور کن صفحه‌ی مانیتور مثل یه پازل بزرگه
هر تکه‌ی کوچیک از این پازل = یک پیکسل
وقتی همه پیکسل‌ها کنار هم قرار می‌گیرن، یه عکس یا نوشته دیده می‌شه

هر چیزی که توی مانیتور، موبایل یا تلویزیون می‌بینی از تعداد خیلی زیادی پیکسل درست شده
یک پیکسل (Pixel) کوچک‌ترین واحد قابل نمایش روی صفحه نمایش هست که شامل سه زیر نور قرمز، سبز و آبیه.
وقتی کنار هم قرار می‌گیرند، تصویرها و محتواهای گرافیکی تولید می‌شن.

