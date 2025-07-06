# Lalmia
Simple HTML practice site
<!DOCTYPE html>              <!-- HTML5 ডকুমেন্ট -->
<html lang="bn">             <!-- বাংলা ভাষা -->
<head>                       <!-- হেড অংশ: টাইটেল, স্টাইল -->
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>আমার ওয়েবসাইট</title>  <!-- ব্রাউজারে নাম -->
  <style>
    body {
      background-color: #f5f5f5;
      text-align: center;
      font-family: sans-serif;
    }
    h1 {
      color: green;
    }
    a.button {
      display: inline-block;
      margin-top: 20px;
      background: red;
      color: white;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 5px;
    }
  </style>
</head>

<body>                      <!-- যেটা স্ক্রিনে দেখা যাবে -->
  <h1>স্বাগতম আমার সাইটে!</h1>
  <p>এইটা Lalmia হোম পেইজ</p>
  <a class="button" href="login.html">লগইন করুন</a>
</body>
</html>
<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <title>লগইন পেইজ</title>
  <style>
    body {
      text-align: center;
      font-family: sans-serif;
      background: #e6f2ff;
      padding-top: 50px;
    }
    input {
      padding: 10px;
      width: 200px;
      margin: 10px;
    }
    button {
      background: green;
      color: white;
      padding: 10px 20px;
      border: none;
    }
  </style>
</head>
<body>
  <h2>লগইন করুন</h2>
  <form>
    <input type="text" placeholder="ইউজারনেম"><br>
    <input type="password" placeholder="পাসওয়ার্ড"><br>
    <button>লগইন</button>
  </form>
</body>
</html>
<!-- about.html -->
<h1>আমাদের সম্পর্কে</h1>
<p>আমরা একটি নতুন ওয়েব ডেভেলপমেন্ট টিম...</p>
<!-- contact.html -->
<h1>যোগাযোগ করুন</h1>
<p>ফোন: ০0000000xxx</p>
<p>ইমেইল: 000xxxx.com</p>
<head>
  <link rel="stylesheet" href="style.css">
</head>
<div>
  <a href="index.html">Home</a> |
  <a href="login.html">Login</a> |
  <a href="about.html">About</a> |
  <a href="contact.html">Contact</a>
</div>
<nav>
  <a href="index.html">Home</a>
  <a href="about.html">About</a>
  <a href="contact.html">Contact</a>
</nav>
<script>
  alert("স্বাগতম!");
</script>

