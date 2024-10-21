- <!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>محرر الصور</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f0f0f0;
        }
        canvas {
            border: 1px solid #ccc;
            margin-top: 10px;
        }
        .controls {
            margin: 20px;
        }
    </style>
</head>
<body>
    <h1>محرر الصور البسيط 🎨</h1>
    <input type="file" id="upload" />
    <canvas id="canvas"></canvas>
    <div class="controls">
        <button onclick="applyFilter('grayscale')">تدرج رمادي</button>
        <button onclick="applyFilter('invert')">عكس الألوان</button>
        <button onclick="applyFilter('sepia')">سيبيا</button>
    </div>

    <script src="script.js"></script>
</body>
</html>
