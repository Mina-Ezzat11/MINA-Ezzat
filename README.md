<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>قائمة الكتب</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 20px;
        }
        h1 {
            text-align: center;
            color: #333;
        }
        .book-list {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .book {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            width: 200px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .book img {
            width: 100%;
            height: auto;
            border-radius: 4px;
        }
        .book h3 {
            color: #555;
            margin: 10px 0;
        }
        .book p {
            color: #777;
        }
        .book a {
            display: inline-block;
            margin-top: 10px;
            padding: 8px 15px;
            background-color: #4CAF50;
            color: #fff;
            text-decoration: none;
            border-radius: 4px;
        }
        .book a:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <h1>قائمة الكتب</h1>

    <div class="book-list">
        <!-- كتاب 1 -->
        <div class="book">
            <img src="https://via.placeholder.com/150" alt="كتاب 1">
            <h3>عنوان الكتاب الأول</h3>
            <p>وصف مختصر للكتاب الأول.</p>
            <a href="https://github.com" target="_blank">مزيد من التفاصيل</a>
        </div>

        <!-- كتاب 2 -->
        <div class="book">
            <img src="https://via.placeholder.com/150" alt="كتاب 2">
            <h3>عنوان الكتاب الثاني</h3>
            <p>وصف مختصر للكتاب الثاني.</p>
            <a href="https://github.com" target="_blank">مزيد من التفاصيل</a>
        </div>

        <!-- كتاب 3 -->
        <div class="book">
            <img src="https://via.placeholder.com/150" alt="كتاب 3">
            <h3>عنوان الكتاب الثالث</h3>
            <p>وصف مختصر للكتاب الثالث.</p>
            <a href="https://github.com" target="_blank">مزيد من التفاصيل</a>
        </div>
    </div>

</body>
</html>
