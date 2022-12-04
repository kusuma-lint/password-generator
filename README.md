# password-generator
yeah lucu

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sesi 8 Password Generator</title>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css"/>
</head>
<body>
    <div class="container d-flex justify-content-center 
    align-items-center min-vh-100">
        <div class="d-flex flex-column">
            <h1>Password Generator</h1>
            <div class="d-flex flex-column gap-2 mt-2">
                <label for="passwordLength" class="text-uppercase fw-bold">Panjang Password</label>
                <input class="form-control form-control-lg" id="passwordLength" type="number"/>
                <label for="password" class="text-uppercase fw-bold">Password</label>
                <input class="form-control form-control-lg" id="password" type="password"/>
                <button class="btn btn-dark text-uppercase fw-bold btn-lg mt-2">generate password</button>
                <button class="btn btn-primary text-uppercase fw-bold btn-lg mt-2">save password</button>
            </div>
        </div>
    </div>
    <script src="index.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
