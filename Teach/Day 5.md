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
<br> تگ شکستن خط برای رفتن به خط بعدی
<label> => تگ گذاشتن لیبل برای input
<input> => …تگ برای گرفتن مشخصات مثله ایمیل, سن و  
<div> => تگ گروه بندی کردن در سایز کوچک
<section> => تگ برای گروه بندی کردن در سایز بزرگ تر

برای اینکه به بچه ها بگیم برن تگ های بیش تر رو self study کنن به این سایت اشاره میکنیم
W3schools
https://www.w3schools.com/TAGS/default.asp


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