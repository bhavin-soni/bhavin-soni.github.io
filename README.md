<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Admission Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f4f6f9;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 500px;
            margin: 40px auto;
            background: #ffffff;
            padding: 25px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h2 {
            text-align: center;
            color: #333;
        }
        label {
            font-weight: bold;
            display: block;
            margin-top: 12px;
        }
        input, select, textarea {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .gender {
            display: flex;
            gap: 10px;
            margin-top: 5px;
        }
        button {
            width: 100%;
            background: #007bff;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            margin-top: 20px;
            font-size: 16px;
            cursor: pointer;
        }
        button:hover {
            background: #0056b3;
        }
    </style>
</head>
<body>

<div class="container">
    <h2>Student Admission Form</h2>

    <form action="#" method="post">
        
        <label>Full Name</label>
        <input type="text" name="name" required>

        <label>Date of Birth</label>
        <input type="date" name="dob" required>

        <label>Gender</label>
        <div class="gender">
            <label><input type="radio" name="gender"> Male</label>
            <label><input type="radio" name="gender"> Female</label>
            <label><input type="radio" name="gender"> Other</label>
        </div>

        <label>Email</label>
        <input type="email" name="email" required>

        <label>Phone Number</label>
        <input type="tel" name="phone" required>

        <label>Course</label>
        <select name="course">
            <option>BCA</option>
            <option>BSc IT</option>
            <option>BBA</option>
            <option>MCA</option>
        </select>

        <label>Address</label>
        <textarea name="address" rows="3"></textarea>

        <button type="submit">Submit Admission</button>

    </form>
</div>

</body>
</html>
