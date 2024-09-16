

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Registration Form</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <div class="container mt-5">
        <h2>NATIONAL IDENTIFICATION CARD </h2>
        <form>
            <div class="form-group mt-5">
                <label for="firstName">FIRSTNAME</label>
                <input type="text" class="form-control" id="FIRSTNAME" placeholder="Enter firstName"required>
            </div>
            <div class="form-group mt-5">
                <label for="lastName">LASTNAME</label>
                <input type="text" class="form-control" id="lastName" placeholder="Enter Last Name"required>
            </div>
            <div class="form-group mt-5">
                <label for="dob">DATE OF BIRTH</label>
                <input type="date" class="form-control" required>
            </div>
            <div class="form-group mt-5">
                <label for="gender">GENDER</label>
                <label for ="male">male</label>
                <input type="radio" class="form-check-input">
                <label for ="female">FEMALE</label>
                <input type="radio" class="form-check-input">
            </div>
            <div class="form-group mt-5">
                <label for="mobileNumber">Mobile Number</label>
                <input type="tel" class="form-control" id="mobileNumber" placeholder="Enter Mobile Number"required>
            </div>
            <div class="form-group mt-5">
                <label for="id number">ID NUMBER</label>
                <input type="text" class="form-control" id="id number" placeholder="Enter number" required>
            </div>
            <button type="submit" class="btn btn-primary">Submit</button>
        </form>
    </div>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
