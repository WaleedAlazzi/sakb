<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>صفحتي الشخصية</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #FFEB3B;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            color: #333;
        }
        nav {
            text-align: center;
            background-color: #333;
            padding: 10px;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            font-size: 18px;
        }
        nav a:hover {
            background-color: #555;
        }
        .container {
            padding: 20px;
        }
        .blog-posts {
            display: flex;
            flex-direction: column;
        }
        .blog-post {
            background-color: white;
            margin: 10px 0;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .video-audio-container {
            display: flex;
            justify-content: space-between;
            margin-top: 40px;
        }
        iframe {
            width: 48%;
            height: 300px;
            border-radius: 8px;
        }
        audio {
            width: 48%;
            border-radius: 8px;
        }
        .contact-form {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            margin-top: 40px;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .contact-form button {
            background-color: #FFEB3B;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            font-size: 16px;
        }
        .contact-form button:hover {
            background-color: #f5c400;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>صفحتي الشخصية</h1>
        <p>مرحباً بك في مدونتي الشخصية حيث أشارك الأفكار والمحتوى المتنوع.</p>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#blog">المدونة</a>
        <a href="#media">المحتوى المتعدد</a>
        <a href="#contact">اتصل بي</a>
    </nav>

    <!-- Main Content -->
    <div class="container">
        
        <!-- Blog Section -->
        <section id="blog" class="blog-posts">
            <h2>مدونتي</h2>
            <div class="blog-post">
                <h3>عنوان المقال الأول</h3>
                <p>هنا يمكنك كتابة أول مقال لك. يمكنك إضافة نصوص، صور، وروابط.</p>
            </div>
            <div class="blog-post">
                <h3>عنوان المقال الثاني</h3>
                <p>هنا يمكنك كتابة مقال آخر. على سبيل المثال، يمكن أن يكون لديك محتوى تعليمي أو أفكار شخصية.</p>
            </div>
        </section>

        <!-- Video & Audio Section -->
        <section id="media" class="video-audio-container">
            <div>
                <h2>فيديو</h2>
                <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="فيديو تعريفي" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            </div>
            <div>
                <h2>صوت</h2>
                <audio controls>
                    <source src="audio_sample.mp3" type="audio/mp3">
                    متصفحك لا يدعم تشغيل الصوت.
                </audio>
            </div>
        </section>

        <!-- Contact Form Section -->
        <section id="contact" class="contact-form">
            <h2>اتصل بي</h2>
            <form action="#" method="post">
                <input type="text" name="name" placeholder="الاسم" required>
                <input type="email" name="email" placeholder="البريد الإلكتروني" required>
                <textarea name="message" placeholder="رسالتك..." rows="4" required></textarea>
                <button type="submit">إرسال</button>
            </form>
        </section>

    </div>

</body>
</html>
