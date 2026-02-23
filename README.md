# ABDULMALIK-AL-RUMAIMI
Animation Character Maker
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <title>Abdulmalik | موقعي الشخصي</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #0f172a;
            color: white;
            text-align: center;
        }

        header {
            background: linear-gradient(90deg, #2563eb, #06b6d4);
            padding: 40px 20px;
        }

        header h1 {
            margin: 0;
            font-size: 40px;
        }

        header p {
            font-size: 18px;
            margin-top: 10px;
        }

        section {
            padding: 50px 20px;
        }

        .card {
            background-color: #1e293b;
            padding: 25px;
            margin: 20px auto;
            width: 80%;
            max-width: 500px;
            border-radius: 15px;
            box-shadow: 0 0 15px rgba(0,0,0,0.5);
        }

        button {
            padding: 12px 25px;
            border: none;
            border-radius: 8px;
            background-color: #06b6d4;
            color: white;
            font-size: 16px;
            cursor: pointer;
        }

        button:hover {
            background-color: #0891b2;
        }

        footer {
            background-color: #1e293b;
            padding: 20px;
            margin-top: 40px;
        }
    </style>
</head>

<body>

<header>
    <h1>عبدالملك سعيد</h1>
    <p>طالب تقنية المعلومات | HTML | CSS | JavaScript</p>
</header>

<section>
    <h2>من أنا</h2>
    <div class="card">
        <p>
            أنا طالب تقنية معلومات مهتم بتطوير الويب وتصميم المواقع الحديثة.
            أعمل على تطوير مهاراتي في HTML و CSS و JavaScript.
        </p>
    </div>
</section>

<section>
    <h2>مهاراتي</h2>
    <div class="card">
        <p>✔ HTML</p>
        <p>✔ CSS</p>
        <p>✔ JavaScript</p>
    </div>
</section>

<section>
    <h2>تواصل معي</h2>
    <div class="card">
        <button onclick="showMessage()">اضغط هنا</button>
    </div>
</section>

<footer>
    <p>© 2026 جميع الحقوق محفوظة - Abdulmalik</p>
</footer>

<script>
    function showMessage() {
        alert("شكراً لزيارتك موقعي 🚀");
    }
</script>

</body>
</html>
