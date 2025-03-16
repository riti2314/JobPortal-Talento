# JobPortal-Talento
Java-Online Job portal

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JobFinder - Your Career Gateway</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/css/bootstrap.min.css">
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-warning">



        <div class="container">
            <a class="navbar-brand" href="index.jsp">Talento</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto">
                    <li class="nav-item">
                        <a class="nav-link active" href="index.jsp">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="jobs.jsp">Jobs</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="companies.jsp">Companies</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="blog.jsp">Career Advice</a>
                    </li>
                </ul>
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link" href="login.jsp">Login</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="register.jsp">Register</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="py-5 bg-light">
        <div class="container px-4">
            <div class="row gx-5 align-items-center">
                <div class="col-lg-6">
                    <h1 class="fw-bold mb-3">Find Your Dream Job Today</h1>
                    <p class="lead mb-4">Connect with top employers and discover opportunities that match your skills and career goals.</p>
                    <div class="search-box p-4 bg-white rounded shadow">
                        <form action="search.jsp" method="get">
                            <div class="row g-2">
                                <div class="col-md-5">
                                    <input type="text" class="form-control" name="keyword" placeholder="Job title or keyword">
                                </div>
                                <div class="col-md-5">
                                    <input type="text" class="form-control" name="location" placeholder="Location">
                                </div>
                                <div class="col-md-2">
                                    <button type="submit" class="btn btn-warning w-100">Search</button>

                                </div>
                            </div>
                        </form>
                    </div>
                </div>
                <div class="col-lg-6">
                    <img src="/api/placeholder/600/400" alt="Job Search" class="img-fluid rounded">
                </div>
            </div>
        </div>
    </header>

    <!-- Job Categories -->
    <section class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Browse Jobs by Category</h2>
            <div class="row g-4">
                <div class="col-md-3">
                    <div class="card h-100 text-center p-3">
                        <div class="card-body">
                            <h5 class="card-title">Information Technology</h5>
                            <p class="card-text">1,240 open positions</p>
                            <a href="jobs.jsp?category=IT" 
   class="btn btn-outline-primary" 
   style="border-color: #00050a; color: #000305; font-weight: bold; transition: 0.3s;" 
   onmouseover="this.style.backgroundColor='#ffc107'; this.style.borderColor='#ffc107'; this.style.color='black';" 
   onmouseout="this.style.backgroundColor='transparent'; this.style.borderColor='#007bff'; this.style.color='#007bff';">
   Explore Jobs
</a>

                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card h-100 text-center p-3">
                        <div class="card-body">
                            <h5 class="card-title">Healthcare</h5>
                            <p class="card-text">856 open positions</p>
                            <a href="jobs.jsp?category=Healthcare" class="btn btn-outline-primary" 
                            style="border-color: #00050a; color: #000305; font-weight: bold; transition: 0.3s;" 
                            onmouseover="this.style.backgroundColor='#ffc107'; this.style.borderColor='#ffc107'; this.style.color='black';" 
                            onmouseout="this.style.backgroundColor='transparent'; this.style.borderColor='#007bff'; this.style.color='#007bff';">
                            Explore Jobs</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card h-100 text-center p-3">
                        <div class="card-body">
                            <h5 class="card-title">Finance</h5>
                            <p class="card-text">654 open positions</p>
                            <a href="jobs.jsp?category=Finance" class="btn btn-outline-primary" 
                            style="border-color: #00050a; color: #000305; font-weight: bold; transition: 0.3s;" 
                            onmouseover="this.style.backgroundColor='#ffc107'; this.style.borderColor='#ffc107'; this.style.color='black';" 
                            onmouseout="this.style.backgroundColor='transparent'; this.style.borderColor='#007bff'; this.style.color='#007bff';">
                            Explore Jobs</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card h-100 text-center p-3">
                        <div class="card-body">
                            <h5 class="card-title">Marketing</h5>
                            <p class="card-text">432 open positions</p>
                            <a href="jobs.jsp?category=Marketing" class="btn btn-outline-primary" 
                            style="border-color:#00050a; color: #000305; font-weight: bold; transition: 0.3s;" 
                            onmouseover="this.style.backgroundColor='#ffc107'; this.style.borderColor='#ffc107'; this.style.color='black';" 
                            onmouseout="this.style.backgroundColor='transparent'; this.style.borderColor='#007bff'; this.style.color='#007bff';">
                            Explore Jobs</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Featured Jobs -->
    <section class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center mb-4">Featured Job Openings</h2>
            <div class="row g-4">
                <div class="col-lg-6">
                    <div class="card mb-3">
                        <div class="card-body">
                            <div class="d-flex align-items-center mb-3">
                                <img src="/api/placeholder/60/60" alt="Company Logo" class="me-3 rounded">
                                <div>
                                    <h5 class="card-title mb-0">Senior Java Developer</h5>
                                    <p class="card-text text-muted mb-0">TechSolutions Inc.</p>
                                </div>
                            </div>
                            <div class="mb-3">
                                <span class="badge bg-primary me-2">Full-time</span>
                                <span class="badge bg-secondary me-2">5+ Years</span>
                                <span class="badge bg-info">Remote</span>
                            </div>
                            <p class="card-text">Develop enterprise-level applications using Java, Spring, and Hibernate. Work in an agile team environment.</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <span class="text-muted">15 - 25 lakhs per year</span>
                                <a href="job-details.jsp?id=1" class="btn btn-outline-warning">View Details</a>

                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-6">
                    <div class="card mb-3">
                        <div class="card-body">
                            <div class="d-flex align-items-center mb-3">
                                <img src="/api/placeholder/60/60" alt="Company Logo" class="me-3 rounded">
                                <div>
                                    <h5 class="card-title mb-0">UI/UX Designer</h5>
                                    <p class="card-text text-muted mb-0">Creative Designs Ltd</p>
                                </div>
                            </div>
                            <div class="mb-3">
                                <span class="badge bg-primary me-2">Full-time</span>
                                <span class="badge bg-secondary me-2">3+ Years</span>
                                <span class="badge bg-info">Hybrid</span>
                            </div>
                            <p class="card-text">Create user-centered designs by understanding business requirements and user feedback. Proficient in Figma and Adobe XD.</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <span class="text-muted">8 - 15 lakhs per year</span>
                                <a href="job-details.jsp?id=1" class="btn btn-outline-warning">View Details</a>

                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="text-center mt-4">
                <a href="jobs.jsp" class="btn btn-warning">View All Jobs</a>
            </div>
        </div>
    </section>

    <!-- How It Works -->
    <section class="py-5">
        <div class="container">
            <h2 class="text-center mb-5">How JobFinder Works</h2>
            <div class="row g-4">
                <div class="col-md-4 text-center">
                    <div class="p-3">
                        <div class="feature-icon bg-warning text-black mb-3 rounded-circle d-inline-flex align-items-center justify-content-center" style="width: 60px; height: 60px;">1</div>
                        <h4>Create an Account</h4>
                        <p>Sign up as a job seeker or employer and complete your profile with relevant details.</p>
                    </div>
                </div>
                <div class="col-md-4 text-center">
                    <div class="p-3">.
                        
                        <div class="feature-icon bg-warning text-black mb-3 rounded-circle d-inline-flex align-items-center justify-content-center" style="width: 60px; height: 60px;">2</div>
                        <h4>Explore Opportunities</h4>
                        <p>Search for jobs that match your skills and preferences, or post job openings as an employer.</p>
                    </div>
                </div>
                <div class="col-md-4 text-center">
                    <div class="p-3">
                        <div class="feature-icon bg-warning text-black mb-3 rounded-circle d-inline-flex align-items-center justify-content-center" style="width: 60px; height: 60px;">3</div>
                        <h4>Apply or Hire</h4>
                        <p>Submit applications for desired positions or review applications and find your ideal candidate.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center mb-4">Success Stories</h2>
            <div class="row g-4">
                <div class="col-md-6">
                    <div class="card h-100">
                        <div class="card-body">
                            <div class="d-flex align-items-center mb-3">
                                <img src="/api/placeholder/60/60" alt="User Profile" class="rounded-circle me-3">
                                <div>
                                    <h5 class="mb-0">Geet Dhillon</h5>
                                    <p class="text-muted mb-0">Software Engineer</p>
                                </div>
                            </div>
                            <p class="card-text">"<b>Talento</b> helped me find my dream job within just two weeks! The platform is intuitive and connected me with employers that perfectly matched my skills and career goals."</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="card h-100">
                        <div class="card-body">
                            <div class="d-flex align-items-center mb-3">
                                <img src="/api/placeholder/60/60" alt="User Profile" class="rounded-circle me-3">
                                <div>
                                    <h5 class="mb-0">Aditya D.Kashyap</h5>
                                    <p class="text-muted mb-0">HR Manager</p>
                                </div>
                            </div>
                            <p class="card-text">"As an employer,<b> Talento</b> has streamlined our recruitment process. We've found quality candidates faster and more efficiently than ever before. The applicant filtering tools are exceptional."</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white py-4">
        <div class="container">
            <div class="row">
                <div class="col-md-3">
                    <h5>Talento</h5>
                    <p>Your trusted partner in career advancement and talent acquisition.</p>
                </div>
                <div class="col-md-3">
                    <h5>For Job Seekers</h5>
                    <ul class="list-unstyled">
                        <li><a href="#" class="text-decoration-none text-white-50">Browse Jobs</a></li>
                        <li><a href="#" class="text-decoration-none text-white-50">Create Resume</a></li>
                        <li><a href="#" class="text-decoration-none text-white-50">Job Alerts</a></li>
                        <li><a href="#" class="text-decoration-none text-white-50">Career Advice</a></li>
                    </ul>
                </div>
                <div class="col-md-3">
                    <h5>For Employers</h5>
                    <ul class="list-unstyled">
                        <li><a href="#" class="text-decoration-none text-white-50">Post a Job</a></li>
                        <li><a href="#" class="text-decoration-none text-white-50">Browse Resumes</a></li>
                        <li><a href="#" class="text-decoration-none text-white-50">Recruiting Solutions</a></li>
                        <li><a href="#" class="text-decoration-none text-white-50">Pricing Plans</a></li>
                    </ul>
                </div>
                <div class="col-md-3">
                    <h5>Contact Us</h5>
                    <ul class="list-unstyled text-white-50">
                        <li>Email: support@talento.com</li>
                        <li>Phone: +91 6202020211</li>
                        <li>Address: Yash Building, Amritsar, Punjab</li>
                    </ul>
                </div>
            </div>
            <hr class="my-4">
            <div class="row">
                <div class="col-md-6">
                    <p class="mb-0">&copy; 2025 Talento. All rights reserved.</p>
                </div>
                <div class="col-md-6 text-md-end">
                    <a href="#" class="text-decoration-none text-white-50 me-3">Privacy Policy</a>
                    <a href="#" class="text-decoration-none text-white-50 me-3">Terms of Service
                        <a href="#" class="text-decoration-none text-white-50 me-3">Terms of Service</a>
                    <a href="#" class="text-decoration-none text-white-50">Sitemap</a>
                </div>
            </div>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/js/bootstrap.bundle.min.js"></script>
    <!-- Custom JS -->
    <script src="js/script.js"></script>
</body>
</html><a href="#" class="text-decoration-none text-white-50 me-3">Terms of Service</a>
                    <a href="#" class="text-decoration-none text-white-50">Sitemap</a>
                </div>
            </div>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/js/bootstrap.bundle.min.js"></script>
    <!-- Custom JS -->
    <script src="jsscript.js"></script>
</body>
</html>
