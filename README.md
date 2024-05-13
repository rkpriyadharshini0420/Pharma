# Project Responsive Web Design using Bootstrap
## Date:13/05/2024

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
about.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>contact us</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"  crossorigin="anonymous">
</head>
<body style="background-color: rgb(47, 0, 255);">


  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">PRIYA Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="app.html">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">SELF CARE</a></li>
              <li><a class="dropdown-item" href="#">SKIN CARE</a></li>
              <li><a class="dropdown-item" href="#">FACE CARE</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="event.html">Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <section class="container py-5">
    <h1 class="text-center mb-4">Contact Us</h1>
    <div class="row">
      <div class="col-md-6">
        <h3>INFO</h3>
        <p>PRIYA Pharma</p>
        <p>PRIYA Pharma
           RANGU Nagar,
           Chennai,
           PINCODE-600001.
        </p>
        <p>Phone Number: <a href="tel:+1234567890">0442635987</a></p>
        <p>Email: <a href="priya:info@yourcompany.com">info@priya.com</a></p>
      </div>
      <div class="col-md-6">
        <h3>To stay in touch with us  </h3>
        <form>
          <div class="mb-3">
            <label for="name" class="form-label">Your Name</label>
            <input type="text" class="form-control" id="name" required>
          </div>
          <div class="mb-3">
            <label for="email" class="form-label">Email Address</label>
            <input type="email" class="form-control" id="email" required>
          </div>
          <div class="mb-3">
            <label for="message" class="form-label">Message</label>
            <textarea class="form-control" id="message" rows="3" required></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Send Message</button>
        </form>
      </div>
    </div>
  </section>

  <footer style="background-color: rgb(69, 166, 199);" class="text-center py-3">
    <p>&copy; 2024 PRIYA Pharma PRIYA(212223040155)</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>
```
```
event.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Events</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" crossorigin="anonymous">
</head>
<body style="background-color: rgb(47, 0, 255);">

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">PRIYA Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="app.html">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">SELF CARE</a></li>
              <li><a class="dropdown-item" href="#">SKIN CARE</a></li>
              <li><a class="dropdown-item" href="#">FACE CARE</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="event.html">Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>


  <section class="container py-5">
    <h1 class="text-center mb-4">News & Events</h1>
    <div class="row">
      <div class="col-md-3 mb-2">
        <div class="card">
          <img src="7..jpg" class="card-img-top" alt="News Image">
          <div class="card-body">
            <h5 class="card-title">Chickenpox is a highly contagious disease caused by the varicella-zoster virus (VZV).</h5>
            <p class="card-text" style="font-size: large;">Chickenpox or varicella is a contagious disease caused by the varicella-zoster virus (VZV). The virus is responsible for chickenpox (usually primary infection in non-immune hosts) and herpes zoster or shingles (following reactivation of latent infection). Chickenpox results in a skin rash that forms small itchy blisters which scab over. This activity describes the cause, presentation, and pathophysiology of chickenpox and highlights the role of the interprofessional team in the treatment and prevention of this infection.

            </p>
            <a href="#" class="btn btn-primary btn-sm">Continue Reading</a>
          </div>
        </div>
      </div>
      <div class="col-md-3 mb-2">
        <div class="card">
          <img src="8..jpg" class="card-img-top" alt="News Image">
          <div class="card-body">
            <h5 class="card-title">Cancer is a disease in which some of the body’s cells grow uncontrollably and spread to other parts of the body.</h5>
            <p class="card-text" style="font-size: large;">Research has helped us accumulate extensive knowledge about the biological processes involved in cancer onset, growth, and spread in the body. Those discoveries have led to more effective and targeted treatments and prevention strategies.

              Breakthroughs in prevention, early detection, screening, diagnosis, and treatment are often the result of research and discoveries made by scientists in a wide array of disciplines over decades and even generations. Ultimately, cancer research requires partnerships and collaborations involving researchers, clinicians, patients, and others to translate yesterday’s discoveries into today’s advances and tomorrow’s cures.

            </p>
            <a href="#" class="btn btn-primary btn-sm">Continue Reading</a>
          </div>
        </div>
      </div>
      <div class="col-md-3 mb-2">
        <div class="card">
          <img src="9..jpg" class="card-img-top" alt="News Image">
          <div class="card-body">
            <h5 class="card-title">Flu, also called influenza, is an infection of the nose, throat and lungs, which are part of the respiratory system. The flu is caused by a virus. Influenza is commonly called the flu</h5>
            <p class="card-text" style="font-size: large;">Given the yearly challenge of seasonal influenza and the potential catastrophic consequences of future pandemics, the need for intensive basic and clinical influenza research is unquestionable. Although the fruits of decades of research have enabled dramatic improvements in our ability to prevent and treat influenza, many fundamental questions remain, including those related to the complex factors associated with host switching and transmission of influenza viruses. Recent public concern over two H5N1 influenza manuscripts that studied the transmissibility of influenza viruses has triggered intense discussion on dual-use research and the way forward.


            </p>
            <a href="#" class="btn btn-primary btn-sm">Continue Reading</a>
          </div>
        </div>
      </div>
    </div>
   
    
    </section>
  <footer style="background-color: rgb(69, 188, 199);" class="text-center py-3">
    <p>&copy; 2024 PRIYA Pharma PRIYA(212223040155)</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>
```
```
products.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our Products</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"  crossorigin="anonymous">
</head>
<body style="background-color: rgb(60, 0, 255);">


  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">PRIYA Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="app.html">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">SELF CARE</a></li>
              <li><a class="dropdown-item" href="#">SKIN CARE</a></li>
              <li><a class="dropdown-item" href="#">FACE CARE</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="event.html">Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="container py-5">
    <h1 class="text-center mb-4">Our Products</h1>
    <div class="row row-cols-1 row-cols-md-2 row-cols-lg-3 g-4">
      <div class="col">
        <div class="card">
          <img src="4..jpeg" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">Neurological disorder</h5>
            <p class="card-text">encompass a wide range of conditions that affect the nervous system, including the brain, spinal cord, nerves, and muscles. These disorders can result from various causes, including genetics, infections, trauma, autoimmune disorders, and environmental factors.</p>
            <a href="#" class="btn btn-primary">Know More</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img src="5..jpeg" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">skin allergy</h5>
            <p class="card-text">These reactions can range from mild itching and redness to more severe symptoms such as swelling, blistering, and oozing. Common triggers for skin allergies</p>
            <a href="#" class="btn btn-primary">Know More</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img src="6..jpeg" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">blood count</h5>
            <p class="card-text">a complete blood count (CBC), is a common blood test that provides valuable information about the cells in your blood. It measures several components, including red blood cells (RBCs), white blood cells (WBCs), and platelets, as well as various parameters that can indicate overall health and help diagnose certain medical conditions.</p>
            <a href="#" class="btn btn-primary">Know More</a>
          </div>
        </div>
      </div>
      </div>
  
  
  </section>

  <footer style="background-color: rgb(69, 169, 199);" class="text-center py-3">
    <p>&copy; 2024 PRIYA Pharma PRIYA(212223040155)</p>
  </footer>

</body>
</html>
```
```
app.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pharma</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"  crossorigin="anonymous">
<body style="background-color: rgb(85, 0, 255);">

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">PRIYA Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">SELF CARE</a></li>
              <li><a class="dropdown-item" href="#">SKIN CARE</a></li>
              <li><a class="dropdown-item" href="#">BODY CARE</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="event.html">Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <section class="hero d-flex align-items-center justify-content-center text-center py-5 mb-5">
    <div class="container">
      <h1>Global Health Care and Access to Medicines All Over The World.</h1>
      <p class="lead">Our aim is to provide Offering guidance on over-the-counter medications, supplements, and health-related products.</p>
      <a href="#" class="btn btn-primary btn-lg">MORE INFO</a>
    </div>
  </section>

  <section class="container">
    <div class="row">
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="1..jpeg" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">UPDATION</h5>
            <p class="card-text">Today's pharmacies serve as frontline healthcare providers, offering a spectrum of services aimed at promoting wellness, improving medication adherence, and enhancing patient outcomes.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="2..jpeg" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">QUALITY</h5>
            <p class="card-text">Quality is the cornerstone of effective healthcare delivery, and nowhere is this more evident than in pharmacy services.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="3..jpeg" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">Patient Care</h5>
            <p class="card-text">In the evolving landscape of healthcare, patient-centered care has emerged as a guiding principle, emphasizing collaboration, empathy, and individualized attention.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <footer style="background-color: rgb(69, 173, 199);" class="text-center py-3">
    <p>&copy; 2024 PRIYA Pharma PRIYA(212223040155) </p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>
```



## OUTPUT :
![alt text](<Screenshot 2024-05-13 200856.png>)
![alt text](<Screenshot 2024-05-13 201005.png>)
![alt text](<Screenshot 2024-05-13 200938.png>)
![alt text](<Screenshot 2024-05-13 201023.png>)



## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
