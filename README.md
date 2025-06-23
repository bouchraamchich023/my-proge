<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>مقدمة في HTML و CSS</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, sans-serif;
      background-color: #121212;
      color: #f0f0f0;
      line-height: 1.8;
    }

    header {
      background-color: #00bfa6;
      padding: 20px;
      text-align: center;
      color: #fff;
      border-bottom: 5px solid #008c7e;
    }

    section {
      max-width: 900px;
      margin: 30px auto;
      padding: 20px;
      background-color: #1e1e1e;
      border-radius: 15px;
      box-shadow: 0 0 20px rgba(0, 191, 166, 0.3);
    }

    h2 {
      color: #00e0c6;
    }

    code {
      background-color: #2a2a2a;
      padding: 4px 8px;
      border-radius: 5px;
      color: #00ffcc;
      display: block;
      margin: 10px 0;
    }

    .example {
      background-color: #333;
      padding: 10px;
      border-radius: 10px;
      margin-top: 10px;
    }

    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
      color: #777;
    }
  </style>
</head>
<body>

  <header>
    <h1>مقدمة في HTML وCSS</h1>
    <p>عرض تقديمي تعليمي - bouchraamchich023</p>
  </header>

  <section>
    <h2>ما هي HTML؟</h2>
    <p>HTML هي لغة هيكلة صفحات الويب. تُستخدم لتحديد العناوين، الفقرات، الروابط، الصور، وغير ذلك.</p>
    <p>مثال:</p>
    <code>&lt;h1&gt;مرحبا بك في موقعي&lt;/h1&gt;</code>

    <div class="example">
      <h1>مرحبا بك في موقعي</h1>
    </div>
  </section>

  <section>
    <h2>ما هي CSS؟</h2>
    <p>CSS هي لغة تنسيق، تُستخدم لجعل موقعك يبدو جميلاً من خلال التحكم في الألوان، الخطوط، المسافات، إلخ.</p>
    <p>مثال:</p>
    <code>h1 { color: red; font-size: 2em; }</code>

    <div class="example" style="color: red; font-size: 2em;">
      هذا نص منسق بواسطة CSS
    </div>
  </section>

  <section>
    <h2>روابط مفيدة</h2>
    <ul>
      <li><a href="https://developer.mozilla.org/ar/docs/Web/HTML" target="_blank">تعلم HTML من MDN</a></li>
      <li><a href="https://developer.mozilla.org/ar/docs/Web/CSS" target="_blank">تعلم CSS من MDN</a></li>
    </ul>
  </section>

  <footer>
    &copy; 2025 - تم إعداد هذا العرض من طرف Bouchra Amchich
  </footer>

</body>
</html>
