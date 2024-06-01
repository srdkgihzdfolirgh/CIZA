<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home Page</title>
    <script>
        function openContactPage() {
            window.open('Contact.html', 'contactPage', 'width=400,height=400,top=100,left=100');
        }
    </script>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #000000;
            color: #fff;
            padding: 4em 0;
            display: flex;
            justify-content: flex-start;
            height: 5vh;
        }
        .content {
            text-align: center;
            height: 0.5em;
        }
        header h1 {
            margin: 0;
            font-size: 2em;
        }
        nav {
            background-color: #000000;
            text-align: left;
            font-size: 1.5em;
        }
        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            overflow: hidden;
        }
        nav ul li {
            float: left;
        }
        nav ul li a {
            display: block;
            color: #fff;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        nav ul li a:hover {
            background-color: #111;
        }
        .content {
            padding: 20px;
        }
        .card {
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            padding: 20px;
            margin-bottom: 20px;
        }
        .card img {
            max-width: 100%;
            border-radius: 5px;
        }
        footer {
            background-color: #000000;
            color: #fff;
            text-align: center;
            padding: 3em 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>منصة هانى شاكر التعليمية</h1>
    <nav>
        <ul>
            <li><a href="Courses.html">الدورات</a></li>
            <li><a href="About.html">عن الموقع</a></li>
            <li><a href="Contact.html">اتصل بنا</a></li>
        </ul>
    </nav>
    </header>
    <div class="content">
        <div class="card">
            <h2>مرحباً بكم في منصة هانى شاكر التعليمية</h2>
            <p>نوفر لكم أفضل الشروحات والدروس في مادة اللغة الإنجليزية للثانوية</p>
            <img src="chemistry.jpg" alt="صورة تعليمية">
        </div>
        <div class="card">
            <h2>دوراتنا</h2>
            <p>استكشف الدورات المختلفة المتاحة الآن وسجل للحصول على أفضل تجربة تعليمية.</p>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 منصة هانى شاكر التعليمية</p>
    </footer>
</body>
</html>

