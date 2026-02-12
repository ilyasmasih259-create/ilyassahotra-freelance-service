<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ilyas Masih | Freelancer</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(to right, #1c1c1c, #2e2e2e);
            color: white;
            text-align: center;
        }

        header {
            padding: 50px 20px;
            background: #0a66c2;
            animation: fadeIn 2s ease-in;
        }

        header img {
            width: 160px;
            height: 160px;
            border-radius: 50%;
            border: 4px solid white;
            margin-top: 15px;
        }

        h1, h2 {
            margin: 10px 0;
        }

        section {
            padding: 30px 20px;
        }

        .card {
            background: #fff;
            color: #000;
            margin: 20px auto;
            padding: 25px;
            width: 85%;
            max-width: 450px;
            border-radius: 15px;
            box-shadow: 0 6px 18px rgba(0,0,0,0.4);
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-5px) scale(1.03);
        }

        .btn {
            display: inline-block;
            padding: 12px 25px;
            margin: 10px 5px;
            border-radius: 30px;
            font-weight: bold;
            text-decoration: none;
        }

        .whatsapp {
            background: #25D366;
            color: white;
        }

        .email {
            background: #FF5722;
            color: white;
        }

        footer {
            background: black;
            padding: 15px;
        }

        input, textarea {
            width: 90%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 8px;
            border: 1px solid #ccc;
        }

        button {
            padding: 10px 20px;
            border: none;
            border-radius: 25px;
            background: #0a66c2;
            color: white;
            font-weight: bold;
            cursor: pointer;
        }

        @keyframes fadeIn {
            from {opacity: 0;}
            to {opacity: 1;}
        }
    </style>
</head>

<body>

<header>
    <h1>Ilyas Masih</h1>
    <p>Army Retired | Professional Freelancer</p>
    <img src="profile.jpg" alt="Profile Picture">
</header>

<section>
    <div class="card">
        <h2>My Services | میری خدمات</h2>
        <p>✔ Data Entry | ڈیٹا انٹری</p>
        <p>✔ Excel Expert | ایکسل ورک</p>
        <p>✔ Word Formatting | ورڈ فارمیٹنگ</p>
        <p>✔ Security Supervision | سکیورٹی سپروائزن</p>
    </div>

    <div class="card">
        <h2>About Me | میرے بارے میں</h2>
        <p>I am a disciplined and hardworking Army retired professional. I provide fast and accurate freelance services with 100% client satisfaction.</p>
    </div>

    <div class="card">
        <h2>Contact Me | رابطہ کریں</h2>
        <p>📞 Phone: 03028902593</p>
        <a class="btn whatsapp" href="https://wa.me/923028902593" target="_blank">WhatsApp</a>
        <a class="btn email" href="mailto:ilyas@example.com">Email</a>

        <form action="mailto:ilyas@example.com" method="post" enctype="text/plain">
            <input type="text" name="name" placeholder="Your Name | آپ کا نام" required>
            <input type="email" name="email" placeholder="Your Email | آپ کا ای میل" required>
            <textarea name="message" placeholder="Your Message | اپنا پیغام" rows="5" required></textarea>
            <br>
            <button type="submit">Send | بھیجیں</button>
        </form>
    </div>
</section>

<footer>
    <p>© 2026 Ilyas Masih | All Rights Reserved</p>
</footer>

</body>
</html>