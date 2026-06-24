<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width,initial-scale=1.0"/>
<meta name="description" content="INOX - تصميم أثاث فاخر بالمغرب. جودة استثنائية وتصاميم حصرية."/>
<meta name="robots" content="index,follow"/>
<meta property="og:title" content="INOX – تصميم أثاث فاخر"/>
<meta property="og:description" content="نصمم رفاهية منزلك بكل تفصيلة"/>
<meta http-equiv="X-Content-Type-Options" content="nosniff"/>
<meta http-equiv="X-Frame-Options" content="SAMEORIGIN"/>
<title>INOX – تصميم أثاث فاخر | المغرب</title>
<link href="https://googleapis.com" rel="stylesheet"/>
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
:root{
  --black:#08080a;--gold:#C9A84C;--gl:#E8C97A;--burg:#6B1E3A;
  --card:#111113;--text:#F0EDE6;--muted:#7a7470;--white:#ffffff;
}
html{scroll-behavior:smooth}
body{
  background-color:var(--black);
  color:var(--text);
  font-family:'Cairo', sans-serif;
}

/* تنسيق الترويسة */
header{
  position:fixed;top:0;left:0;width:100%;z-index:1000;
  background:rgba(8, 8, 10, 0.95);
  border-bottom:1px solid rgba(201, 168, 76, 0.2);
  padding:1.5rem 5%;display:flex;justify-content:space-between;align-items:center;
}
.logo{font-size:1.8rem;color:var(--gold);font-weight:900;letter-spacing:2px;font-family:'Playfair Display', serif;}
nav a{
  color:var(--text);text-decoration:none;margin:0 1.5rem;
  font-weight:600;transition:color 0.3s ease;
}
nav a:hover{color:var(--gold);}

/* القسم الرئيسي */
.hero{
  min-height:100vh;display:flex;align-items:center;justify-content:center;
  text-align:center;padding:8rem 1rem 0 1rem;background:linear-gradient(rgba(8,8,10,0.7), rgba(8,8,10,0.7)), url('hero-bg.jpg') center/cover;
}
.hero h1{font-size:3.5rem;margin-bottom:1rem;color:var(--white);font-family:'Cairo', sans-serif;}
.hero p{font-size:1.2rem;color:var(--muted);margin-bottom:2rem;max-width:600px;margin-left:auto;margin-right:auto;}
.btn{
  display:inline-block;padding:1rem 2.5rem;background-color:var(--gold);
  color:var(--black);text-decoration:none;font-weight:700;letter-spacing:1px;
  border-radius:2px;transition:all 0.3s ease;border:none;cursor:pointer;text-align:center;
}
.btn:hover{background-color:var(--gl);transform:translateY(-2px);}

/* قسم المنتجات */
.products{padding:5rem 5%;}
.section-title{text-align:center;font-size:2.5rem;margin-bottom:3rem;color:var(--gold);font-family:'Cairo', sans-serif;}
.grid{display:grid;grid-template-columns:repeat(auto-fit, minmax(300px, 1fr));gap:2rem;}
.card{
  background-color:var(--card);border:1px solid rgba(255,255,255,0.05);
  border-radius:4px;overflow:hidden;transition:transform 0.3s ease;
  display:flex;flex-direction:column;justify-content:space-between;
}
.card:hover{transform:translateY(-5px);border-color:var(--gold);}
.card-img{width:100%;height:300px;object-fit:cover;}
.card-body{padding:1.5rem;flex-grow:1;display:flex;flex-direction:column;justify-content:space-between;}
.card-title{font-size:1.5rem;margin-bottom:0.5rem;color:var(--white);font-family:'Cairo', sans-serif;}
.card-text{color:var(--text);margin-bottom:1.5rem;}
.btn-order{padding:0.8rem 1.5rem;font-size:1rem;}

/* قسم تواصل معنا والخريطة */
.contact-section{padding:5rem 5%;background-color:var(--black);text-align:center;}
.contact-container{max-width:600px;margin:0 auto 3rem auto;background-color:var(--card);padding:2.5rem;border-radius:4px;border:1px solid rgba(201, 168, 76, 0.1);}
.form-group{margin-bottom:1.5rem;text-align:right;}
.form-group label{display:block;margin-bottom:0.5rem;color:var(--white);font-size:0.9rem;}
.form-control{
  width:100%;padding:0.8rem;background-color:var(--black);border:1px solid rgba(255,255,255,0.1);
  color:var(--text);font-family:'Cairo', sans-serif;border-radius:2px;transition:border-color 0.3s ease;
}
.form-control:focus{outline:none;border-color:var(--gold);}
textarea.form-control{resize:vertical;min-height:120px;}

.map-wrapper {
  max-width: 900px;margin: 0 auto;border-radius: 4px;overflow: hidden;
  border: 1px solid rgba(201, 168, 76, 0.2);box-shadow: 0 10px 30px rgba(0,0,0,0.5);
}
.map-wrapper iframe {width: 100%;height: 400px;display: block;border: 0;}

/* تذييل الصفحة */
footer{background-color:var(--card);padding:3rem 5%;text-align:center;border-top:1px solid rgba(255,255,255,0.05);}
.instagram-link{
  display:inline-flex;align-items:center;color:var(--gold);text-decoration:none;
  font-weight:600;margin-bottom:1.5rem;transition:color 0.3s ease;font-size:1.1rem;
}
.instagram-link:hover{color:var(--gl);}
.footer-text{color:var(--muted);margin-top:1rem;}

@media(max-width:768px){
  header{padding:1.5rem 2%;}
  nav{display:none;}
  .hero h1{font-size:2.5rem;}
  .map-wrapper iframe {height: 300px;}
}
</style>
</head>
<body>

<header>
    <div class="logo">INOX</div>
    <nav>
        <a href="#home">الرئيسية</a>
        <a href="#collection">تشكيلاتنا</a>
        <a href="#contact">تواصل معنا</a>
    </nav>
</header>

<section id="home" class="hero">
    <div>
        <h1>نصمم رفاهية منزلك بكل تفصيلة</h1>
        <p>نقدم أثاثاً فاخراً يجمع بين الحرفية الاستثنائية والتصاميم الحصرية لتناسب أرقى الأذواق في المغرب.</p>
        <a href="#collection" class="btn">استكشف التشكيلة</a>
    </div>
</section>

<section id="collection" class="products">
    <h2 class="section-title">تصاميمنا الحصرية</h2>
    <div class="grid">
        <!-- المنتج الأول -->
        <article class="card">
            <img src="https://unsplash.com" alt="طقم صالون عصري" class="card-img"/>
            <div class="card-body">
                <h3 class="card-title">طقم صالون "رويال"</h3>
                <p class="card-text">أناقة لا تضاهى مع تفاصيل معدنية دقيقة ولمسات من القماش الفاخر.</p>
                <!-- استبدل 212600000000 برقم الواتساب الخاص بك مع رمز الدولة -->
                <a href="https://wa.meً%20INOX،%20أود%20الاستفسار%20عن%20طقم%20صالون%20رويال" target="_blank" class="btn btn-order">اطلب عبر واتساب</a>
            </div>
        </article>
        
        <!-- المنتج الثاني -->
        <article class="card">
            <img src="https://unsplash.com" alt="كرسي فاخر" class="card-img"/>
            <div class="card-body">
                <h3 class="card-title">كرسي "أورورا"</h3>
                <p class="card-text">تصميم حصري يجمع بين الراحة المطلقة والجمال العصري الكلاسيكي.</p>
                <!-- استبدل 212600000000 برقم الواتساب الخاص بك -->
                <a href="https://wa.meً%20INOX،%20أود%20الاستفسار%20عن%20كرسي%20أورورا" target="_blank" class="btn btn-order">اطلب عبر واتساب</a>
            </div>
        </article>

        <!-- المنتج الثالث -->
        <article class="card">
            <img src="https://unsplash.com" alt="طاولة طعام" class="card-img"/>
            <div class="card-body">
                <h3 class="card-title">طاولة طعام "إيليت"</h3>
                <p class="card-text">القطعة المركزية المثالية لغرفة طعامك بتفاصيل لا تُنسى.</p>
                <!-- استبدل 212600000000 برقم الواتساب الخاص بك -->
                <a href="https://wa.meً%20INOX،%20أود%20الاستفسار%20عن%20طاولة%20طعام%20إيليت" target="_blank" class="btn btn-order">اطلب عبر واتساب</a>
            </div>
        </article>
    </div>
</section>

<section id="contact" class="contact-section">
    <h2 class="section-title">تواصل معنا</h2>
    <div class="contact-container">
        <form action="#" method="POST">
            <div class="form-group">
                <label for="name">الاسم الكامل</label>
                <input type="text" id="name" name="name" class="form-control" required placeholder="أدخل اسمك الكريم"/>
            </div>
            <div class="form-group">
                <label for="phone">رقم الهاتف</label>
                <input type="tel" id="phone" name="phone" class="form-control" required placeholder="06XXXXXXXX"/>
            </div>
            <div class="form-group">
                <label for="message">تفاصيل الطلب أو الاستفسار</label>
                <textarea id="message" name="message" class="form-control" required placeholder="اكتب رسالتك هنا..."></textarea>
            </div>
            <button type="submit" class="btn" style="width: 100%;">إرسال الطلب</button>
        </form>
    </div>

    <!-- قسم خريطة جوجل التفاعلية (موقع افتراضي بالمغرب مدمج ومناسب للهوية المظلمة للموقع) -->
    <div class="map-wrapper">
        <iframe src="https://google.com" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </div>
</section>

<footer>
    <div class="logo" style="margin-bottom: 1rem;">INOX</div>
    <a href="https://instagram.com" target="_blank" class="instagram-link">
        📷 تابعنا على إنستغرام: @website_12
    </a>
    <p class="footer-text">© 2026 جميع الحقوق محفوظة لـ INOX المغرب.</p>
</footer>

</body>
</html>
# Website-
