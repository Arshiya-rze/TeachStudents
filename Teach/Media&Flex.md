Warm-up 
(۱ دقیقه):
یک صفحه ساده باز کن که روی دسکتاپ خوبه ولی روی موبایل بد می‌شکنه (مثلاً متن خیلی بزرگ یا دو ستون چسبیده). از دانشجوها بپرس: «روی موبایل باید چی تغییر کنه؟»

مفهوم کلی (۳ دقیقه):
Media Query 
یعنی: «اگر اندازه/ویژگی دستگاه فلان بود، این استایل‌ها اعمال شوند.»
@media (شرط) {
  /* CSS فقط وقتی شرط برقرار است اجرا می‌شود */
}

max-width: 500px → وقتی عرض تا ۵۰۰px یا کمتر بود.
یعنی عرض صفحه ۵۰۰px یا کمتر باشد .
min-width: 768px → وقتی عرض از ۷۶۸px به بالا بود.
این یعنی اینکه عرض صفحه به ۷۶۸px برسه و یا بیش تر.

##### Flex
این استایل برای این هستش که ما وقتی میخوایم چندتا المان مثل متن جعبه و یا دکمه رو کنار هم قرار بدیم میتونیم از flex استفاده بکنیم.
مثال در html
<div class="container">
  <div class="box">1</div>
  <div class="box">2</div>
  <div class="box">3</div>
</div>
مثال در css
.container {
  display: flex;
  border: 2px solid black;
}

.box {
  width: 50px;
  height: 50px;
  background: lightblue;
  margin: 5px;
}


مهم‌ترین ویژگی‌ها (خیلی ساده)

justify-content:
جهت افقی (چپ، راست، وسط)

align-items: 
جهت عمودی (بالا، وسط، پایین)

flex-direction:
تعیین می‌کنه بچه‌ها در ردیف (row) باشن یا ستون (column)

gap:
فاصله بین بچه‌ها

مثال در css:
.container {
  display: flex;
  justify-content: center;   /* وسط افقی */
  align-items: center;       /* وسط عمودی */
  flex-direction: column;    /* بچه‌ها زیر هم */
  gap: 10px;                 /* فاصله */
}

## تفاوت `display` ها برای بچه‌ها

- `display: block;` → هر المنت یک خط کامل رو می‌گیره (مثل `<p>`).
- `display: inline;` → کنار هم میاد ولی نمی‌تونی طول/عرض دقیق بدی (مثل `<span>`).
- `display: inline-block;` → مثل inline کنار هم میاد ولی می‌تونی طول/عرض هم بدی.
- `display: flex;` → قوی‌ترین حالت، کنترل کامل روی ردیف/ستون و چیدمان.
