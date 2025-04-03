<!DOCTYPE html>
<html lang="lo">
<head>
    <meta charset="UTF-8">
    <title>ແບບຟອມແຈ້ງສ້ອມແປງ</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #ccffcc; /* ພື້ນຫລັງສີຂຽວອ່ອນ */
            text-align: center;
            padding: 20px;
        }
        form {
            background: white;
            padding: 20px;
            border-radius: 10px;
            width: 50%;
            margin: auto;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        label {
            display: block;
            margin: 10px 0 5px;
        }
        input, textarea, select {
            width: 100%;
            padding: 8px;
            margin-bottom: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        button {
            background-color: #4CAF50; /* ສີຂຽວ */
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <h2>ແບບຟອມແຈ້ງສ້ອມແປງ</h2>
    <form action="#" method="POST" enctype="multipart/form-data">
        <label for="name">ຊື່ຜູ້ແຈ້ງ:</label>
        <input type="text" id="name" name="name" required>

        <label for="equipment">ອຸປະກອນທີ່ຕ້ອງສ້ອມ:</label>
        <select id="equipment" name="equipment" required>
            <option value="">-- ເລືອກອຸປະກອນ --</option>
            <option value="ຄອມພິວເຕີ">ຄອມພິວເຕີ</option>
            <option value="ໂທລະສັບ">ໂທລະສັບ</option>
            <option value="ຖັງນໍ້າ">ຖັງນໍ້າ</option>
            <option value="ໄຟຟ້າ">ໄຟຟ້າ</option>
            <option value="ອື່ນໆ">ອື່ນໆ...</option>
        </select>

        <label for="description">ອະທິບາຍເພີ່ມເຕີມ:</label>
        <textarea id="description" name="description" required></textarea>

        <label for="photo">ອັບໂຫລດຮູບພາບ:</label>
        <input type="file" id="photo" name="photo">

        <button type="submit">ສົ່ງຟອມ</button>
    </form>
</body>
</html>
