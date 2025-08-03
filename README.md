<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8" />
  <title>متجر T1</title>
  <style>
    body {
      background-color: #0e0e0e;
      color: #ffffff;
      font-family: 'Tahoma', sans-serif;
      text-align: center;
      margin: 0;
      padding: 40px;
    }

    h1 {
      color: #bb86fc;
      margin-bottom: 40px;
      font-size: 32px;
    }

    .button-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .dropdown {
      position: relative;
      display: inline-block;
    }

    .dropbtn {
      background-color: #6200ee;
      color: white;
      padding: 14px 20px;
      font-size: 16px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    .dropbtn:hover {
      background-color: #3700b3;
    }

    .dropdown-content {
      display: none;
      position: absolute;
      background-color: #1f1f1f;
      min-width: 200px;
      border-radius: 6px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      z-index: 1;
      text-align: right;
      right: 0;
    }

    .dropdown-content a {
      color: #ffffff;
      padding: 12px 16px;
      text-decoration: none;
      display: block;
      transition: background-color 0.2s ease;
    }

    .dropdown-content a:hover {
      background-color: #2a2a2a;
    }

    .show {
      display: block;
    }
  </style>
</head>
<body>

  <h1>اهلا في T1</h1>

  <div class="button-container">

    <div class="dropdown">
      <button class="dropbtn" onclick="toggleDropdown(this)">حزمة المواطنين</button>
      <div class="dropdown-content">
        <a href="#">مركبه 70 جمليه و حصريه</a>
        <a href="#">امتلاك فوري</a>
        <a href="#">عرض خاص 99 ريال</a>
      </div>
    </div>

    <div class="dropdown">
      <button class="dropbtn" onclick="toggleDropdown(this)">🔱〢𝐆𝐨𝐥𝐝・حزمة</button>
      <div class="dropdown-content">
        <a href="#">90 مركبه</a>
        <a href="#">تميز بالتعديلات و الاكسترا</a>
        <a href="#">عرض خاص 124</a>
      </div>
    </div>

    <div class="dropdown">
      <button class="dropbtn" onclick="toggleDropdown(this)">💎〢𝐕𝐈𝐏・حزمة</button>
      <div class="dropdown-content">
        <a href="#">110 مركبه</a>
        <a href="#">سرعه و تميز و اكسترا فاخر</a>
        <a href="#">عرض خاص 149</a>
      </div>
    </div>
