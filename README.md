<!DOCTYPE html>
<html dir="rtl" lang="ar">
<head>
  <meta charset="UTF-8">
  <title>الجدول الأسبوعي - Weekly Schedule</title>
  <style>
    body {
      font-family: Arial, Tahoma, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      background-color: #f0f0f0;
      margin: 0;
      padding: 20px;
    }
    .container {
      background-color: white;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 20px rgba(0,0,0,0.1);
      max-width: 1400px;
      width: 100%;
    }
    table {
      border-collapse: collapse;
      margin: 0 auto;
      background-color: white;
      width: 100%;
    }
    th, td {
      border: 2px solid #ddd;
      padding: 15px;
      text-align: center;
      width: 400px;
      height: 250px;
    }
    th {
      background-color: #4CAF50;
      color: white;
      font-size: 18px;
      line-height: 1.5;
    }
    td {
      vertical-align: middle;
    }
    .school-img, .ace-img {
      max-width: 380px;
      max-height: 230px;
      width: 100%;
      height: auto;
      object-fit: cover;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .day-row {
      background-color: #f8f9fa;
    }
    .day-row:nth-child(even) {
      background-color: #ffffff;
    }
    .day-row:hover {
      background-color: #e8f5e9;
    }
    .day-name {
      font-weight: bold;
      color: #2c3e50;
      font-size: 48px;
      line-height: 1.3;
      padding: 20px;
    }
    h1 {
      text-align: center;
      color: #2c3e50;
      margin-bottom: 30px;
      font-size: 32px;
    }
    .english {
      direction: ltr;
      text-align: center;
      display: block;
      font-size: 42px;
      color: #555;
      font-weight: bold;
      margin-top: 10px;
    }
    .arabic {
      font-size: 60px;
      display: block;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>الجدول الأسبوعي - Weekly Schedule</h1>
    <table>
      <thead>
        <tr>
          <th>
            <span class="arabic">اليوم</span>
            <span class="english">Day</span>
          </th>
          <th>
            <span class="arabic">المدرسة</span>
            <span class="english">School</span>
          </th>
          <th>
            <span class="arabic">مركز التميز للتوحد</span>
            <span class="english">ACE Center</span>
          </th>
        </tr>
      </thead>
      <tbody>
        <tr class="day-row">
          <td class="day-name">
            <span class="arabic">الأحد</span>
            <span class="english">Sunday</span>
          </td>
          <td><img src="image.png" alt="School Building" class="school-img" title="School Building"></td>
          <td><img src="ACE.jpg" alt="Autism Center of Excellence" class="ace-img" title="ACE Building"></td>
        </tr>
        <tr class="day-row">
          <td class="day-name">
            <span class="arabic">الإثنين</span>
            <span class="english">Monday</span>
          </td>
          <td><img src="image.png" alt="School Building" class="school-img" title="School Building"></td>
          <td></td>
        </tr>
        <tr class="day-row">
          <td class="day-name">
            <span class="arabic">الثلاثاء</span>
            <span class="english">Tuesday</span>
          </td>
          <td><img src="image.png" alt="School Building" class="school-img" title="School Building"></td>
          <td></td>
        </tr>
        <tr class="day-row">
          <td class="day-name">
            <span class="arabic">الأربعاء</span>
            <span class="english">Wednesday</span>
          </td>
          <td><img src="image.png" alt="School Building" class="school-img" title="School Building"></td>
          <td><img src="ACE.jpg" alt="Autism Center of Excellence" class="ace-img" title="ACE Building"></td>
        </tr>
        <tr class="day-row">
          <td class="day-name">
            <span class="arabic">الخميس</span>
            <span class="english">Thursday</span>
          </td>
          <td><img src="image.png" alt="School Building" class="school-img" title="School Building"></td>
          <td><img src="ACE.jpg" alt="Autism Center of Excellence" class="ace-img" title="ACE Building"></td>
        </tr>
        <tr class="day-row">
          <td class="day-name">
            <span class="arabic">الجمعة</span>
            <span class="english">Friday</span>
          </td>
          <td></td>
          <td></td>
        </tr>
        <tr class="day-row">
          <td class="day-name">
            <span class="arabic">السبت</span>
            <span class="english">Saturday</span>
          </td>
          <td></td>
          <td></td>
        </tr>
      </tbody>
    </table>
  </div>
</body>
</html>
