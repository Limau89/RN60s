<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Rollin60s.com/Login - UCP State Side</title>
  <style>
    body {
      background-color: #e0fafa;
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .card {
      background: white;
      padding: 30px;
      border-radius: 25px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.3);
      width: 90%;
      max-width: 350px;
      text-align: center;
    }
    input {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border: none;
      border-radius: 15px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }
    button {
      background: #0095ff;
      color: white;
      border: none;
      padding: 12px;
      width: 100%;
      border-radius: 15px;
      font-size: 16px;
      cursor: pointer;
      margin-top: 15px;
    }
    a {
      display: block;
      margin-top: 15px;
      color: red;
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>Login</h1>
    <input type="text" placeholder="Username/nomor/Email" />
    <input type="password" placeholder="Password" />
    <a href="Verifikasi.html"><button>Login</button></a>
    <a href="register.html">Belum punya akun, buat akun. Klik di sini</a>
  </div>
</body>
</html>
