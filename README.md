<!DOCTYPE html>
<html>
<head>
    <title>Registration page</title>
    <link rel="stylesheet" type="text/css" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        body {
            background-color: #FFFFFF;
        }
        .container {
            margin-top: 50px; /* Decrease top margin for a smaller overall box */
            max-width: 500px; /* Increase maximum width for a bigger registration box */
            padding: 20px; /* Increase padding for a bigger registration box */
        }
        .panel {
            border-radius: 15px; /* Increase border-radius for a slightly larger registration box */
            box-shadow: 0px 0px 10px 0px rgba(0,0,0,0.3);
            padding: 20px; /* Increase padding for a bigger registration box */
        }
        .panel-heading {
            background-color: #000000;
            color: #fff;
            border-top-left-radius: 15px; /* Adjust border radius */
            border-top-right-radius: 15px; /* Adjust border radius */
            font-size: 26px; /* Increase font size */
            padding: 15px; /* Increase padding */
        }
        .panel-body, .panel-footer {
            border-bottom-left-radius: 15px; /* Adjust border radius */
            border-bottom-right-radius: 15px; /* Adjust border radius */
        }
        /* Added CSS for margin inside form */
        .form-group {
            margin-bottom: 10px; /* Adjust margin as needed */
        }
        /* Custom styling for submit button */
        .btn-primary {
            background-color: #000000; /* Black background */
            color: #FFFFFF; /* White text */
        }
        /* Adjust size of input fields */
        .form-control {
            font-size: 12px; /* Reduce font size */
            padding: 8px; /* Reduce padding */
        }
    </style>
</head>
<body>
<div class="container">
    <div class="row justify-content-center">
        <div class="col-md-12">
            <div class="panel panel-primary">
                <div class="panel-heading text-center">
                    <h1 style="font-size: 24px;">Registration Form</h1> <!-- Adjust font size -->
                </div>
                <div class="panel-body">
                    <form method="post" action="connect.php">
                        <div class="form-group">
                            <label for="firstname">First Name</label>
                            <input type="text" class="form-control" id="firstname" name="firstname">
                        </div>
                        <div class="form-group">
                            <label for="lastname">Last Name</label>
                            <input type="text" class="form-control" id="lastname" name="lastname">
                        </div>
                        <div class="form-group">
                            <label>Gender</label><br>
                            <label for="male" class="radio-inline"><input type="radio" name="gender" id="male">Male</label>
                            <label for="female" class="radio-inline"><input type="radio" name="gender" id="female">Female</label>
                            <label for="others" class="radio-inline"><input type="radio" name="gender" id="others">Others</label>
                        </div>
                        <div class="form-group">
                            <label for="email">Email</label>
                            <input type="text" class="form-control" id="email" name="email">
                        </div>
                        <div class="form-group">
                            <label for="password">Password</label>
                            <input type="password" class="form-control" id="password" name="password">
                        </div>
                        <div class="form-group">
                            <label for="number">Phone Number</label>
                            <input type="text" class="form-control" id="number" name="number">
                        </div>
                        <div class="panel-body text-center">
                            <input type="submit" class="btn btn-primary" name="submit" value="Submit">
                        </div>
                    </form>
                </div>
                <div class="panel-footer text-center">
                    <small>&copy; 2024 By IGNITE</small>
                </div>
            </div>
        </div>
    </div>
</div>  
</body>
</html>
