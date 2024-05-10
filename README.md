# Ex.10 Responsive Web Design using Bootstrap
## Date:

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pharmaceuticals</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet">
    <style>
        .navbar {
            background-color: rgba(0, 0, 0, 0.7); 
        }

        .card {
            margin: 20px; 
        }
    </style>
</head>
<body>

<nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">lupin</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
            <li class="nav-item active">
                <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownAbout" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                    <i class="fas fa-info-circle"></i> About
                </a>
                <div class="dropdown-menu" aria-labelledby="navbarDropdownAbout">
                    <a class="dropdown-item" href="#">lupin company</a>
                    <a class="dropdown-item" href="#">quality</a>
                    <a class="dropdown-item" href="#">History</a>
                </div>
            </li>
            <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownProducts" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                    <i class="fas fa-pills"></i> Products
                </a>
                <div class="dropdown-menu" aria-labelledby="navbarDropdownProducts">
                    <a class="dropdown-item" href="#">Medications</a>
                    <a class="dropdown-item" href="#">Supplements</a>
                    <a class="dropdown-item" href="#">Medical Devices</a>
                </div>
            </li>
            <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownContact" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                    <i class="fas fa-phone-alt"></i> Contact
                </a>
                <div class="dropdown-menu" aria-labelledby="navbarDropdownContact">
                    <a class="dropdown-item" href="#">Customer Support</a>
                    <a class="dropdown-item" href="#">Sales</a>
                    <a class="dropdown-item" href="#">Feedback</a>
                </div>
            </li>
        </ul>
        <ul class="navbar-nav ml-auto">
            <li class="nav-item">
                <a class="nav-link" href="#">Login</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Register</a>
            </li>
        </ul>
    </div>
</nav>

    <div style="display:flex;">
        <div class="card" style="width: 20rem; margin:20px">
            <img src="company.jpeg" class="card-img-top" alt="..." style="height: 300px;">
            <div class="card-body">
              <h5 class="card-title">lupin Company</h5>
              <p class="card-text">Welcome to lupinMed. Lupin Limited is an Indian multinational pharmaceutical company based in Mumbai. It is one of the largest generic pharmaceutical companies by revenue globally.</p>
              <a href="#" class="btn btn-primary">Read More</a>
            </div>
        </div>


          <div class="card" style="width: 20rem; margin:20px">
            <img src="quality.jpeg" class="card-img-top" alt="..." style="height: 300px;">
            <div class="card-body">
              <h5 class="card-title">lupin mission </h5>
              <p class="card-text">Lupin was founded in 1968 by Desh Bandhu Gupta, who was a professor of chemistry at BITS-Pilani, Rajasthan. Gupta initially borrowed Rs. 5000 from his wife to fund the venture. </p>
              <a href="#" class="btn btn-primary">Read More</a>
            </div>
          </div>


          <div class="card" style="width: 20rem; margin:20px">
            <img src="lupin logo.png" class="card-img-top" alt="..." style="height: 300px;">
            <div class="card-body">
              <h5 class="card-title">History</h5>
              <p class="card-text"> Gupta initially borrowed Rs. 5000 from his wife to fund the venture. Due to subsequent funding from the Central Bank of India, the company able to start their manufacturing facility for producing folic acid and iron tablets for the Indian government's mother and child health program. Later Lupin started manufacturing anti-tuberculosis (TB) drugs which at one point formed 36% of the company sales and was considered as the largest TB drugs manufacturer in the world.</p>
              <a href="#" class="btn btn-primary">Read More</a>
            </div>
          </div>
    </div>


<footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; 2024 PharmaCompany. All rights reserved.</p>
</footer>


<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```


## OUTPUT:
![image](https://github.com/syedfayaz3105/Pharma/assets/147144126/b9f4a4a7-2866-466c-aabc-6eb6abe20386)



## RESULT:
The program for responsive web design using Bootstrap is completed successfully.
