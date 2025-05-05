<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <title>لوحة التحكم - ملخصاتي</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(to bottom right, #c6e2ff, #f9f9f9);
      margin: 0;
      padding: 0;
      direction: rtl;
    }

    header {
      background-color: #007bff;
      color: white;
      padding: 20px;
      text-align: center;
    }

    .dashboard {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .card {
      background: white;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .card h3 {
      margin-top: 0;
      color: #333;
    }

    .card a {
      text-decoration: none;
      color: #007bff;
    }
  </style>
</head>
<body>

  <header>
    <h1>📚 لوحة التحكم - ملخصاتي</h1>
    <p>👋 Hi, we are Kawthar and Maisaa</p>
  </header>

  <div class="dashboard">
    <div class="card">
      <h3>الدوال المرجعية</h3>
      <p>ملخص شامل لأنواع الدوال وتمثيلها البياني.</p>
      <a href="#">تحميل 📎</a>
    </div>

    <div class="card">
      <h3>الدائرة المثلثية</h3>
      <p>مفاهيم الزوايا والنسب المثلثية مع تمارين.</p>
      <a href="#">تحميل 📎</a>
    </div>

    <div class="card">
      <h3>إضافة ملخص جديد</h3>
      <p>سجل اسم وموضوع الملخص الجديد.</p>
      <a href="#">➕ إضافة</a>
    </div>
  </div>

</body>
</html>

