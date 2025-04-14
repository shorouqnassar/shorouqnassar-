
<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shorouq Nassar</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="card">
    <img src="profile.jpg" alt="الصورة الشخصية">
    <h2>shorouq nassar</h2>
    <p><span class="label">رقم الهاتف:</span> 0567853313</p>
    <p><span class="label">العنوان:</span> غزة، فلسطين</p>
    <p><span class="label">البريد الإلكتروني:</span> shorouqnassar6@gmail.com</p>
  </div>
</body>
</html>

body {
  font-family: 'Arial', sans-serif;
  background-color: #f0f0f0;
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  direction: rtl;
}

.card {
  background-color: #fff;
  padding: 30px;
  border-radius: 15px;
  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  text-align: center;
  width: 350px;
}

.card img {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  object-fit: cover;
  border: 3px solid #4a90e2;
}

.card h2 {
  margin: 15px 0 10px;
  color: #333;
}

.card p {
  margin: 5px 0;
  color: #555;
  font-size: 16px;
}

.label {
  font-weight: bold;
  color: #333;
}
