<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Air University</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        .header {
            position: relative;
            text-align: center;
            color: white;
        }
        .header img {
            width: 100%;
            height: 85pv;
            background: fixed;
        }
        .header-text {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            font-size: 4rem;
            font-weight: bold;
        }
        .explore {
            background-color: #0f47ff;
            color: white;
            text-align: center;
            padding: 15px;
            font-size: 1.5rem;
            font-weight: bold;
        }
        .navbar-nav .nav-link {
            font-weight: bold;
        }
        .custom-btn {
            background-color: #0410f2;
            color: white;
            padding: 10px 20px;
            font-size: 1.2rem;
            border: none;
            text-transform: uppercase;
        }
        .custom-btn:hover {
            background-color: #300de0;
        }
        .navbar-custom {
            background-color: #133282;
        }
        .navbar-custom .navbar-brand, .navbar-custom .nav-link {
            color: white;
        }
        .navbar-custom .nav-link:hover {
            color: #f1f1f1;
        }
        .content-section {
            text-align: center;
            padding: 50px 20px;
        }
        .content-section h1 {
            font-weight: bold;
            margin-bottom: 20px;
        }
        .content-section p {
            font-size: 1.2rem;
            margin-bottom: 30px;
        }
        .logo {
            position: absolute;
            top: 10px;
            right: 10px;
            width: 50px;
        }

        
        
/* CSS PG 2 */        
      
/* Campus News Section */
.news-section {
    padding: 40px 0;
    background-color: #f9f9f9;
}

.news-section h1 {
    font-size: 2.5em;
    font-weight: bold;
    text-align: center;
    margin-bottom: 10px;
}

.news-section p.text-center {
    font-size: 1.2em;
    color: #555;
    margin-bottom: 30px;
}

.news-card {
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    margin-bottom: 20px;
    transition: transform 0.3s;
}

.news-card:hover {
    transform: scale(1.03);
}

.news-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-bottom: 5px solid rgb(7, 123, 255); /* Optional: To give the image a color accent at the bottom */
}

.news-card .category {
    font-size: 0.9em;
    font-weight: bold;
    color: rgb(24, 255, 255);
    text-transform: uppercase;
    margin-bottom: 5px;
}

.news-card-title {
    font-size: 1.2em;
    font-weight: bold;
    color: #333;
    margin: 0;
    line-height: 1.3;
}

.news-card .card-body {
    padding: 15px;
}

.more-news-btn {
    display: block;
    background-color: rgb(75, 62, 255);
    color: white;
    font-size: 1em;
    font-weight: bold;
    padding: 10px 20px;
    text-align: center;
    border: none;
    border-radius: 5px;
    margin: 30px auto 0;
    transition: background-color 0.3s;
}

.more-news-btn:hover {
    background-color: rgb(26, 80, 255);
    cursor: pointer;
}

/* PG 3 */
/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background-color: #f8f8f8;
    color: #333;
}

/* Academics Section */
.academics-section {
    text-align: center;
    padding: 40px 20px;
    background-color: rgb(224, 220, 220);
}

.academics-section h1 {
    font-size: 36px;
    color: #333;
    font-weight: bold;
}

.intro-text {
    font-size: 18px;
    margin: 10px 0 30px;
    color: #666;
}

.cards-container {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-bottom: 30px;
}

.card {
    background-color: #f9f9f9;
    padding: 20px;
    width: 250px;
    border-radius: 8px;
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
    text-align: left;
}

.card img {
    width: 100%;
    height: auto;
    border-radius: 8px;
    margin-bottom: 15px;
}

.card h3 {
    font-size: 18px;
    color: #333;
    margin-bottom: 8px;
}

.card p {
    font-size: 14px;
    color: #666;
    margin-bottom: 10px;
}

.card a {
    font-size: 14px;
    color: #0066CC;
    text-decoration: none;
}

.card a:hover {
    text-decoration: underline;
}

.schools-text {
    font-size: 16px;
    font-weight: bold;
    margin: 30px 0 10px;
}

.schools-links {
    display: flex;
    justify-content: center;
    gap: 15px;
    margin-bottom: 30px;
}

.schools-links a {
    color: #0066CC;
    text-decoration: none;
    font-size: 14px;
}

.schools-links a:hover {
    text-decoration: underline;
}

.more-btn {
    padding: 10px 20px;
    background-color: #22127e;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 14px;
}

.more-btn:hover {
    background-color: #4321bf;
}



/* CSS PG 4 */

/* Campus News Section */
.news-section {
    padding: 40px 0;
    background-color: #f9f9f9;
}

.news-section h1 {
    font-size: 2.5em;
    font-weight: bold;
    text-align: center;
    margin-bottom: 10px;
}

.news-section p.text-center {
    font-size: 1.2em;
    color: #555;
    margin-bottom: 30px;
}

.news-card {
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    margin-bottom: 20px;
    transition: transform 0.3s;
}

.news-card:hover {
    transform: scale(1.03);
}

.news-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-bottom: 5px solid rgb(21, 1, 92); /* Optional: To give the image a color accent at the bottom */
}

.news-card .category {
    font-size: 0.9em;
    font-weight: bold;
    color: rgb(38, 4, 115);
    text-transform: uppercase;
    margin-bottom: 5px;
}

.news-card-title {
    font-size: 1.2em;
    font-weight: bold;
    color: #333;
    margin: 0;
    line-height: 1.3;
}

.news-card .card-body {
    padding: 15px;
}

.more-news-btn {
    display: block;
    background-color: rgb(3, 21, 72);
    color: white;
    font-size: 1em;
    font-weight: bold;
    padding: 10px 20px;
    text-align: center;
    border: none;
    border-radius: 5px;
    margin: 30px auto 0;
    transition: background-color 0.3s;
}

.more-news-btn:hover {
    background-color: rgb(47, 30, 199);
    cursor: pointer;
}


/* PG 5 */
/* Research Page */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        .hero-section {
            background-image: url('https://www.au.edu.pk/AU_New_Assets/images/blog/FBS3.jpg'); /* Placeholder for blurred background image */
            background-size: cover;
            background-position: center;
            text-align: center;
            padding: 80px 20px;
            color: white;
            position: relative;
        }

        .hero-section::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.5); /* Semi-transparent overlay */
            z-index: 0;
        }

        .hero-content {
            position: relative;
            z-index: 1;
            max-width: 800px;
            margin: auto;
        }

        .hero-content img {
            border-radius: 50%;
            width: 120px;
            height: 120px;
            margin-bottom: 15px;
        }

        .quote {
            font-size: 1.2rem;
            margin: 15px 0;
            line-height: 1.5;
        }

        .author {
            font-weight: bold;
            margin-top: 5px;
            font-size: 1rem;
        }

        .research-section {
            padding: 40px 20px;
            text-align: center;
        }

        .research-section h2 {
            margin-bottom: 20px;
        }

        .research-stats {
            display: flex;
            justify-content: center;
            gap: 40px;
            margin-top: 20px;
        }

        .stat {
            text-align: center;
        }

        .stat h3 {
            margin: 10px 0;
        }

        .more-button {
            display: inline-block;
            margin-top: 30px;
            padding: 12px 20px;
            background: rgb(18, 18, 230);
            color: white;
            text-decoration: none;
            border-radius: 4px;
        }

        .more-button:hover {
            background: rgb(3, 5, 120);
        }
    

        /* PG 6 */
        /* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background-color: #f8f8f8;
    color: #333;
}

/* Campus Life Section */
.campus-life-section {
    text-align: center;
    padding: 20px;
    background-color: white;
}

.image-container {
    width: 100%;
    max-width: 1200px;
    margin: 0 auto;
    overflow: hidden;
}

.image-container img {
    width: 100%;
    height: auto;
    display: block;
}

.campus-life-section h2 {
    font-size: 24px;
    font-weight: bold;
    color: #333;
    margin-top: 20px;
}

        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        .section-title {
            text-align: center;
            font-size: 2rem;
            margin: 40px 0 20px;
        }

        .events-section,
        .health-section {
            padding: 20px;
            text-align: center;
            background-color: #f4f4f4;
            margin-bottom: 40px;
        }

        .events-container,
        .health-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        .event-card,
        .health-card {
            background-color: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            width: 220px;
            text-align: left;
        }

        .event-card img,
        .health-card img {
            width: 100%;
            height: auto;
        }

        .event-content,
        .health-content {
            padding: 15px;
        }

        .event-date {
            background: #1e21d1;
            color: white;
            padding: 5px 10px;
            border-radius: 4px;
            display: inline-block;
            margin-bottom: 10px;
            font-size: 0.9rem;
        }

        .event-title,
        .health-title {
            font-size: 1rem;
            font-weight: bold;
            margin: 10px 0;
        }

        .event-time {
            font-size: 0.85rem;
            color: #666;
        }

        .button {
            display: inline-block;
            margin: 20px auto;
            padding: 10px 20px;
            background: rgb(0, 30, 255);
            color: white;
            text-decoration: none;
            border-radius: 4px;
            text-align: center;
        }

        .button:hover {
            background: rgb(1, 18, 102);
        }

        .health-container {
            max-width: 1200px;
            margin: auto;
            display: flex;
            gap: 20px;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .health-content a {
            color: blue;
            text-decoration: underline;
            display: block;
            margin-top: 10px;
        }

/* PG 7 */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        .quote-section {
            position: relative;
            text-align: center;
            color: white;
            background: url('quote-bg.jpg') no-repeat center center / cover;
            padding: 80px 20px;
        }

        .quote-section .quote {
            font-size: 1.5rem;
            font-style: italic;
            max-width: 600px;
            margin: auto;
            padding: 20px;
        }

        .quote-section .author {
            margin-top: 10px;
            font-size: 1.2rem;
        }

        .quote-section .author span {
            font-weight: bold;
        }

        .campus-life-section {
            padding: 40px 20px;
            text-align: center;
        }

        .campus-life-title {
            font-size: 2rem;
            margin-bottom: 20px;
        }

        .campus-life-description {
            margin-bottom: 40px;
            color: #666;
        }

        .campus-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            max-width: 1200px;
            margin: auto;
        }

        .campus-card {
            background-color: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            width: 220px;
            text-align: left;
        }

        .campus-card img {
            width: 100%;
            height: auto;
        }

        .campus-content {
            padding: 15px;
        }

        .campus-title {
            font-size: 1rem;
            font-weight: bold;
            margin: 10px 0;
        }

        .campus-content p {
            font-size: 0.9rem;
            color: #666;
        }

        .campus-content a {
            color: blue;
            text-decoration: underline;
            display: block;
            margin-top: 10px;
        }

        .button {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background: rgb(76, 0, 255);
            color: white;
            text-decoration: none;
            border-radius: 4px;
            text-align: center;
        }

        .button:hover {
            background: rgb(0, 12, 139);
        }
    



        /* PG 8 */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        .section {
            padding: 40px 20px;
            text-align: center;
        }

        .section-title {
            font-size: 2rem;
            margin-bottom: 10px;
        }

        .section-description {
            margin-bottom: 40px;
            color: #666;
        }

        .card-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            max-width: 1200px;
            margin: auto;
        }

        .card {
            background-color: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            width: 220px;
            text-align: left;
        }

        .card img {
            width: 100%;
            height: auto;
        }

        .card-content {
            padding: 15px;
        }

        .card-title {
            font-size: 1rem;
            font-weight: bold;
            margin: 10px 0;
        }

        .card-content p {
            font-size: 0.9rem;
            color: #666;
        }

        .card-content a {
            color: blue;
            text-decoration: underline;
            display: block;
            margin-top: 10px;
        }

        .button {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background: rgb(68, 0, 255);
            color: white;
            text-decoration: none;
            border-radius: 4px;
            text-align: center;
        }

        .button:hover {
            background: rgb(21, 0, 139);
        }

        .image-section {
            text-align: center;
            margin-top: 40px;
        }

        .image-section img {
            max-width: 90%;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        
        .admission-info-section {
        padding: 40px 20px;
        text-align: center;
    }

    .info-container {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        gap: 20px;
        margin-bottom: 20px;
        max-width: 1200px;
        margin: auto;
    }

    .info-item {
        flex: 1;
        min-width: 300px;
        max-width: 500px;
        margin: 0 10px;
    }

    .info-item h3 {
        font-size: 1.2rem;
        font-weight: bold;
        margin-bottom: 10px;
    }

    .info-item p {
        font-size: 1rem;
        color: #333;
    }

    .button {
        display: inline-block;
        padding: 10px 20px;
        background: rgb(25, 0, 255);
        color: white;
        text-decoration: none;
        border-radius: 4px;
        font-weight: bold;
    }

    .button:hover {
        background: rgb(14, 0, 139);
    }



    
    /* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

/* Header */
header {
    position: relative;
    text-align: right;
    color: white;
}

.header-img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.social-icons {
    position: absolute;
    top: 10px;
    right: 20px;
}

.social-icons a {
    color: white;
    margin: 0 8px;
    text-decoration: none;
    font-size: 20px;
}

/* Main Links Section */
.main-links {
    display: flex;
    flex-wrap: wrap;
    padding: 20px;
    background-color: #f8f8f8;
    justify-content: center;
}

.links-column {
    flex: 1;
    min-width: 150px;
    margin: 10px;
}

.links-column h3 {
    color: #15158c;
    margin-bottom: 8px;
}

.links-column a {
    display: block;
    color: #333;
    text-decoration: none;
    margin-bottom: 5px;
    font-size: 14px;
}

.button-section {
    display: flex;
    flex-direction: column;
    gap: 8px;
}

.button-section button {
    padding: 10px;
    border: 1px solid #31158c;
    background-color: white;
    color: #160b55;
    font-size: 14px;
    cursor: pointer;
}

.button-section button:hover {
    background-color: #16117d;
    color: white;
}

/* Footer */
footer {
    background-color: #1f1787;
    color: white;
    padding: 20px;
    text-align: center;
}

.footer-content {
    max-width: 800px;
    margin: auto;
}

.footer-links, .legal-links {
    display: flex;
    justify-content: center;
    gap: 10px;
    margin: 10px 0;
}

.footer-links a, .legal-links a {
    color: white;
    text-decoration: none;
    font-size: 12px;
}

.footer-links a:hover, .legal-links a:hover {
    text-decoration: underline;
}

    </style>
</head>
<body>

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-custom">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Air University</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#">News</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Events</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Academics</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Research</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Health Care</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Campus Life</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Admission</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">About</a>
                    </li>
                </ul>
                <!-- Logo on the right side -->
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTru8wRooOau9ZNDdiYjEANT29_ijYuMFB0YQ&s" alt="Stanford Logo" class="logo">
            </div>
        </div>
    </nav>

    <!-- Header Section -->
    <div class="header">
        <img src="https://images.unsplash.com/photo-1702238139056-96ac7ecbc493?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Stanford University" class="img-fluid">
        <div class="header-text">Air University</div>
    </div>

    <!-- Explore Air University Section -->
    <div class="explore">
        Explore Air University
    </div>
    

    <!-- Content Section (Societal Mission) -->
    <section class="content-section">
        <h1>A Societal Mission</h1>
        <p>
            Role 
            Air University aspires to be among the leading national universities, excelling in teaching, learning, research, innovation and public service.. 
        </p>
        <a href="233010about.html">
            <button class="custom-btn">More about Air University</button>
        </a>
        
    </section>

    <!-- Bootstrap JS (optional) -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>


    <!-- Campus News Section -->
<section class="news-section">
    <h1>Campus News</h1>
    <p class="text-center">Stories about people, research, and innovation across the Farm</p>
    <div class="container">
        <div class="row">
            <!-- First News Card -->
            <div class="col-md-6">
                <div class="card news-card">
                    <img src="https://www.au.edu.pk/pages/ORIC/Assets/news_event_gallery/LIBTF2024.jpg" class="card-img-top" alt="Stanford launches center focused on human and planetary health">
                    <div class="card-body">
                        <div class="category">Technology</div>
                        <h5 class="news-card-title">Launching Ignite National Technology Fund's 1st Accelerator  in Pakisten (AU)</h5>
                    </div>
                </div>
            </div>
            <!-- Second News Card -->
            <div class="col-md-6">
                <div class="card news-card">
                    <img src="https://www.au.edu.pk/pages/ORIC/Assets/news_event_gallery/DSLL2024.jpg" class="card-img-top" alt="Mapping the maze where the IRS could find billions in unpaid taxes">
                    <div class="card-body">
                        <div class="category">Advancing Research in Sindhi Language and Literature</div>
                        <h5 class="news-card-title">Department of Sindhi Language and Literature-CAll FOR PAPERS (AU)</h5>
                    </div>
                </div>
            </div>
        </div>
        <div class="row">
            <!-- Third News Card -->
            <div class="col-md-4">
                <div class="card news-card">
                    <img src="https://www.au.edu.pk/pages/ORIC/Assets/news_event_gallery/CCAAS2024.jpg" class="card-img-top" alt="Six things political scientists are watching this election">
                    <div class="card-body">
                        <div class="category">A Path to Sustainability</div>
                        <h5 class="news-card-title">Climate Change and Agricultures solution (AU)</h5>
                    </div>
                </div>
            </div>
            <!-- Fourth News Card -->
            <div class="col-md-4">
                <div class="card news-card">
                    <img src="https://www.au.edu.pk/pages/ORIC/Assets/news_event_gallery/AUAIRBLUE2024.jpg" class="card-img-top" alt="Study reveals disparities in Brazilian schools">
                    <div class="card-body">
                        <div class="category">A Partnership for Future Aviation Leaders</div>
                        <h5 class="news-card-title">MEMORANDUM OF UNDERSTANDING B/W AIR UNIVERSITY AND AIR BLUE (AU)</h5>
                    </div>
                </div>
            </div>
            <!-- Fifth News Card -->
            <div class="col-md-4">
                <div class="card news-card">
                    <img src="https://www.au.edu.pk/pages/ORIC/Assets/news_event_gallery/AYETFE2024.jpg" class="card-img-top" alt="Meyer Green welcomes ‘Amulets’">
                    <div class="card-body">
                        <div class="category">Apply Today</div>
                        <h5 class="news-card-title">Are YOU THE FUTURE OF ENTERPRENTEURSH (AU)</h5>
                    </div>
                </div>
            </div>
        </div>
        <!-- More News Button -->
        <a href="233010about.html">
            <button class="more-news-btn">More campus news</button>
        </a>
    </div>
</section>




    <!-- Academics Section -->
    <section class="academics-section">
        <h1>Academics</h1>
        <p class="intro-text">
            Preparing students to make meaningful contributions to society<br>
            as engaged citizens and leaders in a complex world
        </p>
        
        <div class="cards-container">
            <div class="card">
                <img src="https://www.au.edu.pk/AU_New_Assets/images/blog/FOE3.jpg" alt="Undergraduate Education">
                <h3>Undergraduate Education</h3>
                <p>Rich learning experiences that provide a broad liberal arts foundation and deep subject-area expertise</p>
                <a href="#">Undergraduate Education &gt;</a>
            </div>
            <div class="card">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT4ydreZDtKht_V5mVClRrEJxe3LuUmXnu45Q&s" alt="Graduate Education">
                <h3>Graduate Education</h3>
                <p>Unsurpassed opportunities to participate in the advancement of entire fields of knowledge</p>
                <a href="#">Graduate Education &gt;</a>
            </div>
            <div class="card">
                <img src="https://www.au.edu.pk/AU_New_Assets/images/blog/9.jpg" alt="Driving Impact">
                <h3>Driving impact</h3>
                <p>Continuing adult education, executive and professional programs, and programs for K-12 students</p>
                <a href="#">Lifelong Learning &gt;</a>
            </div>
        </div>
        
        <p class="schools-text">Seven schools in which to pursue your passions</p>
        <div class="schools-links">
            <a href="#">Medicine</a>
            <a href="#">Law</a>
            <a href="#">Humanities & Sciences</a>
            <a href="#">Engineering</a>
            <a href="#">Education</a>
            <a href="#">Sustainability</a>
            <a href="#">Business</a>
        </div>
        
        <button class="more-btn">More about academics</button>
    </section>



  

    <div class="research-section">
         <!-- Quote Section -->
            
                <!-- Campus Life Section -->
                <section class="campus-life-section">
                    <div class="image-container">
                        <img src="https://www.au.edu.pk/AU_New_Assets/images/blog/FBS3.jpg" alt="Campus Life Image">
                    </div>
                    
                </section>
        <h2>Research</h2>
        <p>Driving discoveries vital to our world, our health, and our intellectual life</p>
        <div class="research-stats">
            <div class="stat">
                <h3>15 Institutes</h3>
                <p>cross disciplinary boundaries</p>
            </div>
            <div class="stat">
                <h3>2 Libraries</h3>
                <p>hold over 5 million items</p>
            </div>
            <div class="stat">
                <h3>$1 Billion</h3>
                <p>sponsored research budget</p>
            </div>
        </div>
        <a href="#" class="more-button">More about research</a>
    </div>



    
        <div class="events-section">
            <h2 class="section-title">Upcoming Events</h2>
            <div class="events-container">
                <div class="event-card">
                    <img src="https://www.au.edu.pk/pages/Faculties/AUSOM/Department/AUSOM/images/TFTP1.jpg" alt="Event 1">
                    <div class="event-content">
                        <div class="event-date">Nov 07</div>
                        <div class="event-title">Why Are Fewer Grocery Shoppers Buying Meat?</div>
                        <div class="event-time">10:00 AM PT</div>
                    </div>
                </div>
                <div class="event-card">
                    <img src="https://face4pets.wordpress.com/wp-content/uploads/2019/01/pet-trends.jpg" alt="Event 2">
                    <div class="event-content">
                        <div class="event-date">Nov 07</div>
                        <div class="event-title">Take a Break: A Pawsitive Pet Therapy Experience</div>
                        <div class="event-time">11:30 AM PT</div>
                    </div>
                </div>
                <div class="event-card">
                    <img src="https://i.ytimg.com/vi/26IhsOt3kLY/maxresdefault.jpg" alt="Event 3">
                    <div class="event-content">
                        <div class="event-date">Nov 07</div>
                        <div class="event-title">Comparative Methodologies - Talking Comparison</div>
                        <div class="event-time">12:00 PM PT</div>
                    </div>
                </div>
                <div class="event-card">
                    <img src="https://www.au.edu.pk/Pages/Faculties/Faculty_Images/1538s1.jpg" alt="Event 4">
                    <div class="event-content">
                        <div class="event-date">Nov 07</div>
                        <div class="event-title">MIPS Seminar - Dr. Hisham, PhD</div>
                        <div class="event-time">12:00 PM PT</div>
                    </div>
                </div>
            </div>
            <a href="#" class="button">More events</a>
        </div>
    
        <div class="health-section">
            <h2 class="section-title">Health Care</h2>
            <p>Advancing human health through innovative research, education, and care</p>
            <div class="health-container">
                <div class="health-card">
                    <img src="https://www.aboutpakistan.com/blog/wp-content/uploads/2020/03/medical-colleges.jpg" alt="Stanford Medicine">
                    <div class="health-content">
                        <div class="health-title">Air Medicine</div>
                        <p>Leading a worldwide revolution in precision health through biomedical research, education, and clinical enterprises</p>
                        <a href="#">Air University ></a>
                    </div>
                </div>
                <div class="health-card">
                    <img src="https://www.au.edu.pk/pages/Faculties/Mechatronics_Biomedical_Engineering/Departments/Biomedical/Events/BDDEMORMC2024_4.jpg" alt="Air University Health Care">
                    <div class="health-content">
                        <div class="health-title">Air University Health Care</div>
                        <p>Leveraging expertise and advanced technology to deliver unparalleled care for each patient's unique needs</p>
                        <a href="#">Air University Health Care ></a>
                    </div>
                </div>
                <div class="health-card">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRYcO1FD2jbLbA4XP3uajAIvCBSgwKGcOLCBQ&s" alt="Air University Children's Health">
                    <div class="health-content">
                        <div class="health-title">Air University Blood Drive</div>
                        <p>The only health care network in the Bay Area exclusively dedicated to pediatric and obstetric care</p>
                        <a href="#">Air University Blood Drive ></a>
                    </div>
                </div>
            </div>
            <a href="233010about.html" class="button">More about health care</a>
        </div>



        
            <!-- Quote Section -->
            
                <!-- Campus Life Section -->
                <section class="campus-life-section">
                    <div class="image-container">
                        <img src="https://scontent.fisb1-2.fna.fbcdn.net/v/t39.30808-6/465111368_8831448756876803_2390233560209167501_n.jpg?_nc_cat=111&ccb=1-7&_nc_sid=2285d6&_nc_eui2=AeH8zs0uxKCu95NQskSUFnobCTHpKwe3DW8JMekrB7cNbyVEAoL7y4EpmobEE0ZypIyPGpzQYwShWNTem_js1PN-&_nc_ohc=L7T6i7Jhc50Q7kNvgGyqYnp&_nc_zt=23&_nc_ht=scontent.fisb1-2.fna&_nc_gid=AvMpxBJ7F6MR2QrbVEABP4T&oh=00_AYAc-LE4AmBD-pBnmXFeAUybdkOGMCwTrf51iutmRnZ3xw&oe=67340501" alt="Campus Life Image">
                    </div>
                    
                </section>
            
            
            
            <!-- Campus Life Section -->
            <div class="campus-life-section">
                <h2 class="campus-life-title">Campus Life</h2>
                <p class="campus-life-description">Building a vibrant community of creative and accomplished people from around the world</p>
                <div class="campus-container">
                    <div class="campus-card">
                        <img src="https://aumc.edu.pk/files/newcampusaumc9.webp" alt="Student Life">
                        <div class="campus-content">
                            <div class="campus-title">Student Life</div>
                            <p>A residential campus with diverse housing, exceptional dining, and over 650 student organizations</p>
                            <a href="#">Student Affairs ></a>
                        </div>
                    </div>
                    <div class="campus-card">
                        <img src="https://au.edu.pk/Pages/NewsEvents/EventGallary/76_2.jpg" alt="Arts & Culture">
                        <div class="campus-content">
                            <div class="campus-title">Arts & Culture</div>
                            <p>A rich tradition of fostering creativity and a vibrant arts district on campus</p>
                            <a href="#">Air University Arts ></a>
                        </div>
                    </div>
                    <div class="campus-card">
                        <img src="https://www.hok.com/wp-content/uploads/2019/05/Auburn-University-Recreation-and-Wellness-Center_Gymnasium_1900-1600x1069.jpg" alt="Recreation & Wellness">
                        <div class="campus-content">
                            <div class="campus-title">Recreation & Wellness</div>
                            <p>State-of-the-art facilities and fitness programs to encourage movement and play</p>
                            <a href="#">Recreation & Wellness ></a>
                        </div>
                    </div>
                </div>
                <a href="#" class="button">More about campus life</a>
            </div>





             <!-- Athletics Section -->
    <div class="section">
        <h2 class="section-title">Athletics</h2>
        <p class="section-description">Providing student-athletes the opportunity to achieve excellence both in competition and in the classroom</p>
        <div class="card-container">
            <div class="card">
                <img src="https://www.au.edu.pk/pages/Faculties/Mechatronics_Biomedical_Engineering/Departments/Biomedical/Events/PBAS.jpg" alt="Home of Champions">
                <div class="card-content">
                    <div class="card-title">Home of Champions</div>
                    <p>Stanford's 136 NCAA championships are the most for any university...</p>
                    <a href="#">National Championships ></a>
                </div>
            </div>
            <div class="card">
                <img src="https://www.geosuper.tv/assets/uploads/updates/2024-08-02/38320_2296576_updates.jpg" alt="Olympic Excellence">
                <div class="card-content">
                    <div class="card-title">Olympic Excellence</div>
                    <p>The Cardinal has produced at least one medalist in every Olympics...</p>
                    <a href="#">Medals ></a>
                </div>
            </div>
            <div class="card">
                <img src="https://www.au.edu.pk/Pages/NewsEvents/EventGallary/101_15.jpg" alt="Multidimensional Impact">
                <div class="card-content">
                    <div class="card-title">Multidimensional Impact</div>
                    <p>Stanford student-athletes have achieved local, national, and global impact...</p>
                    <a href="#">Athlete Stories ></a>
                </div>
            </div>
        </div>
        <a href="#" class="button">More about athletics</a>
    </div>

    <!-- Admission Section -->
    <div class="section">
        <h2 class="section-title">Admission</h2>
        <p class="section-description">Offering extraordinary freedom to explore, to collaborate, and to challenge yourself</p>
        <div class="image-section">
            <img src="https://scontent.fisb4-2.fna.fbcdn.net/v/t39.30808-6/300517082_398616052401504_2113025444804885551_n.jpg?_nc_cat=111&ccb=1-7&_nc_sid=6ee11a&_nc_eui2=AeFCZFHznGmcbEHkdVk2c6kyXWC9poiVpztdYL2miJWnO_gt85ZhxaJaRww736sqe5f3m56WsU97TFegly7Cd_vo&_nc_ohc=gd7RWD9j-RwQ7kNvgEKpUGK&_nc_zt=23&_nc_ht=scontent.fisb4-2.fna&_nc_gid=AAt94vl_6XONwrcugLyokSL&oh=00_AYCUGunbpg1N-GoDX7_o6SR9U81PD1cI3bXpbLm9j1wnBA&oe=67340AAC" alt="Admission Group">
        </div>
    </div>

  
<div class="admission-info-section">
    <div class="info-container">
        <div class="info-item">
            <h3>Explore the possibilities of a Air University education as you map out your college journey.</h3>
            <p>We look for distinctive students who exhibit an abundance of energy and curiosity in their classes, activities, projects, research, and lives.</p>
        </div>
        <div class="info-item">
            <h3>Stanford meets the full financial need of every admitted undergrad who qualifies for assistance.</h3>
            <p>More than two-thirds of undergrads receive some form of financial assistance. Generally, tuition is covered for families with incomes below $150,000.</p>
        </div>
    </div>
    <a href="#" class="button">More about admission</a>
</div>



<!-- Header Section -->
<header>
    <img src="https://portals.au.edu.pk/ICO/Content/images/banner.jpg" alt="Air University Dish" class="header-img">
    <div class="social-icons">
        <a href="#"><i class="fa fa-facebook"></i></a>
        <a href="#"><i class="fa fa-twitter"></i></a>
        <a href="#"><i class="fa fa-instagram"></i></a>
        <a href="#"><i class="fa fa-linkedin"></i></a>
        <a href="#"><i class="fa fa-youtube"></i></a>
        <a href="#"><i class="fa fa-apple"></i></a>
    </div>
</header>

<!-- Main Links Section -->
<section class="main-links">
    <div class="links-column">
        <h3>SCHOOLS</h3>
        <a href="#">Business</a>
        <a href="#">Education</a>
        <a href="#">Engineering</a>
        <a href="#">Humanities & Sciences</a>
        <a href="#">Computer Science</a>
        <a href="#">Medicine</a>
        <a href="#">Sustainability</a>
    </div>
    <div class="links-column">
        <h3>ACADEMICS</h3>
        <a href="#">Undergraduate Majors</a>
        <a href="#">Graduate Programs</a>
    </div>
    <div class="links-column">
        <h3>RESEARCH</h3>
        <a href="#">Research Centers A - Z</a>
        <a href="#">Libraries</a>
    </div>
    <div class="links-column">
        <h3>HEALTH CARE</h3>
        <a href="#">Air University Health Care</a>
        <a href="#">Air University Children's Health</a>
    </div>
    <div class="links-column">
        <h3>ABOUT Air University</h3>
        <a href="#">Facts</a>
        <a href="#">History</a>
        <a href="#">Accreditation</a>
    </div>
    <div class="links-column">
        <h3>ADMISSION</h3>
        <a href="#">Undergraduate</a>
        <a href="#">Graduate</a>
        <a href="#">Financial Aid</a>
    </div>
    <div class="links-column">
        <h3>RESOURCES</h3>
        <a href="#">Campus Map</a>
        <a href="#">Community Engagement</a>
        <a href="#">Directory</a>
        <a href="#">Stanford Profiles</a>
    </div>
    <div class="button-section">
        <button>Applying</button>
        <button>Visiting</button>
        <button>Giving</button>
        <button>Careers</button>
        <button>Faculty Positions</button>
        <button>Contact</button>
    </div>
</section>

<!-- Footer Section -->
<footer>
    <div class="footer-content">
        <p>Air University</p>
        <div class="footer-links">
            <a href="#">Air Home</a>
            <a href="#">Maps & Directions</a>
            <a href="#">Search Stanford</a>
            <a href="#">Emergency Info</a>
        </div>
        <div class="legal-links">
            <a href="#">Terms of Use</a>
            <a href="#">Privacy</a>
            <a href="#">Copyright</a>
            <a href="#">Trademarks</a>
            <a href="#">Non-Discrimination</a>
            <a href="#">Accessibility</a>
        </div>
        <p>&copy; Air University, Islamabad.</p>
    </div>
</footer>

</body>
</html>
