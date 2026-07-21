<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <!--💡UPDATE: Change the title to your name-->
    <title> Sunday Maduabuchi | Data Analysis Portfolio</title>
      
    <!--💡UPDATE: Add your favicon here. You can generate one at realfavicongenerator.net-->
    <link rel="icon" type="image/png" href="/favicon-32x32.png">
    <link rel="apple-touch-icon" href="/favicon-32x32.png">
    
    <!-- Google Fonts for Elegant Typography -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Lato:wght@300;400;700&family=Playfair+Display:wght@500;700&display=swap" rel="stylesheet">
    
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
    
    <!-- Your Stylesheet -->
    <link rel="stylesheet" href="assets/css/style.css">
</head>
<body>

<!-- HEADER SECTION -->
<header>
    <div class="container">
        <!--💡UPDATE: Change to your name and title-->
        <h1>Sunday Maduabuchi</h1>
        <p>Machine Learning Engineer | Data Analyst | Power BI Developer | AI Enthusiast</p>
        <div class="social-links">
            <!--💡UPDATE: Add your social media links and CV file-->
            <a href="https://www.linkedin.com/in/sundaymaduabuchi/" target="_blank" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
            <a href="https://github.com/Sundaymaduabuchi/" target="_blank" title="GitHub"><i class="fab fa-github"></i></a>
            <a href="https://facebook.com/sunday.maduabuchi.54" target="_blank" title="Facebook"><i class="fab fa-facebook"></i></a>
            <a href="assets/Sample CV.pdf" download title="Download CV"><i class="fas fa-file-arrow-down"></i></a>
        </div>
    </div>
</header>

<!-- NAVIGATION -->
<nav>
    <div class="container">
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </div>
</nav>

<!-- ABOUT SECTION -->
<section id="about" class="section">
    <div class="container">
        <h2>About Me</h2>
        <div class="about-content">
            <!--💡UPDATE: Change the image to your own profile photo in assets/images/-->
            <img src="assets/images/Profile Image.png" alt="Your Name" class="Profile-photo">
            <div class="about-text">
                <!--💡UPDATE: Write your own 'About Me' text here-->
                <p> I’m Sunday Maduabuchi, a Machine Learning Engineer, Data Analyst, and AI Educator passionate about turning data into actionable insights.
I build intelligent solutions and interactive dashboards that help businesses make smarter decisions.
Focused on innovation, analytics, and real-world problem solving, I transform complex data into measurable impact.</p>
                <p>With experience in Power BI, SQL, and data modeling, I specialize in developing comprehensive reports that reveal hidden patterns and trends in data. This portfolio showcases my projects across various sectors.</p>
            </div>
        </div>
    </div>
</section>

<!-- PROJECTS SECTION -->
<section id="projects" class="section">
    <div class="container">
        <h2>My Projects</h2>
        <div class="projects-grid">

            <!--💡UPDATE: Replace this with your own project. Add as many as you like!-->
            <!-- Project 1 -->
             <div class="project-card">
                <!--💡UPDATE: Add a preview image of your project to assets/images/ -->
                <img src="assets/images/Monthly View.png" alt="Hospital ER Dashboard">
                <div class="project-card-content">
                    <h3>Hospital ER Dashboard</h3>
                    <p>A Power BI dashboard analyzing emergency room operations across three views — monthly performance, consolidated historical trends, and patient-level drill-down. Built a custom date dimension and DAX measures to track wait times, admission patterns, and referral flow, uncovering that 33% of patients exceeded the response-time benchmark despite consistently high satisfaction scores. Used Power Query to clean and standardize raw patient records before modeling.</p>
                    <div class="project-buttons">
                        <!--💡UPDATE: Add link to your project's code/documentation on GitHub-->
                        <a href="https://github.com/Sundaymaduabuchi/hospital-er-dashboard" target="_blank" class="btn">Documentation</a>
                        <!-- No live web link yet for this dashboard (.pbix only) -->
                    </div>
                </div>
            </div>

            <!-- Project 2 -->
            <div class="project-card">
                <img src="assets/images/linear_regression_img.png" alt="myapp_app">
                <div class="project-card-content">
                    <h3>Power output Prediction</h3>
                    <p>An end-to-end ML application predicting power plant energy output (PE) from environmental readings — ambient temperature, exhaust vacuum, ambient pressure, and relative humidity. Trained a scikit-learn Linear Regression model, served it via a FastAPI /predict endpoint, and built a Streamlit front-end for interactive input and real-time predictions.</p>
                    <div class="project-buttons">
                        <a href="https://github.com/Sundaymaduabuchi/myapp_app" target="_blank" class="btn">Documentation</a>
                        <a href="https://sundaymaduabuchi-myapp-app-app-aacxhc.streamlit.app/" target="_blank" class="btn btn-secondary">Try the App</a>
                    </div>
                </div>
            </div>

            <!-- Project 3 -->
            <div class="project-card">
                <img src="assets/images/Finsight Overview page.png" alt="Finance Analysis">
                <div class="project-card-content">
                    <h3>Finsight - Finance Analysis</h3>
                    <p>A Power BI business intelligence solution analyzing financial transaction data across two report pages — an executive overview and a transaction-level drill-down. Built a full data model with custom DAX measures for revenue, average transaction value, and year-over-year comparisons, and used Power Query to clean and standardize raw transaction data. Surfaces insights on customer segmentation, transaction success/failure rates, and regional distribution to support financial decision-making.</p>
                    <div class="project-buttons">
                        <a href="https://github.com/Sundaymaduabuchi/Finance-Analysis" target="_blank" class="btn">Documentation</a>
                        <!-- No live web link yet for this dashboard (.pbix only) -->
                    </div>
                </div>
            </div>

        </div>
    </div>
</section>

<!-- SKILLS SECTION -->
<section id="skills" class="section">
    <div class="container">
        <h2>Technical Skillset</h2>
        <div class="skills-table">
            
            <!--💡UPDATE: Customize your skills in each category-->
            <!-- Column 1: Data Visualization -->
            <div class="skill-column">
                <div class="skill-header">
                    <i class="fas fa-chart-pie"></i>
                    <h3>Data Visualization</h3>
                </div>
                <ul class="skill-list">
                    <li>Microsoft Power BI</li>
                    <li>Excel Dashboards</li>
                </ul>
            </div>

            <!-- Column 2: Data Analysis -->
            <div class="skill-column">
                <div class="skill-header">
                    <i class="fas fa-search-plus"></i>
                    <h3>Data Analysis</h3>
                </div>
                <ul class="skill-list">
                    <li>SQL</li>
                    <li>Advanced Excel</li>
                    <li>Python (Pandas)</li>
                    <li>Google Sheets</li>
                </ul>
            </div>

            <!-- Column 3: Data Modeling & ETL -->
            <div class="skill-column">
                <div class="skill-header">
                    <i class="fas fa-cogs"></i>
                    <h3>Data Modeling & ETL</h3>
                </div>
                <ul class="skill-list">
                    <li>Power Query (M)</li>
                    <li>DAX</li>
                    <li>Star Schema Design</li>
                    <li>ETL Processes</li>
                </ul>
            </div>

        </div>
    </div>
</section>

<!-- CONTACT FORM SECTION -->
<section id="contact" class="section">
    <div class="container">
        <h2>Send me a message</h2>
        
        <!--💡UPDATE: Go to formsubmit.co and replace the email with your own-->
        <form action="https://formsubmit.co/maduabuchisunday2018@gmail.com" method="POST" class="contact-form">
            <p> Interested in collaborating or have questions about my work? I'd love to hear from you!</p>

            <!-- Form Fields -->
            <div class="form-group">
                <label for="name">Name</label>
                <input type="text" name="name" id="name" placeholder="Your name" required>
            </div>
            <div class="form-group">
                <label for="email">Email</label>
                <input type="email" name="email" id="email" placeholder="Your email" required>
            </div>
            <div class="form-group">
                <label for="subject">Subject</label>
                <input type="text" name="subject" id="subject" placeholder="Subject" required>
            </div>
            <div class="form-group">
                <label for="message">Message</label>
                <textarea name="message" id="message" rows="6" placeholder="Your message" required></textarea>
            </div>
            
            <!-- Submit Button -->
            <button type="submit" class="btn">Send Message</button>

        </form>
    </div>
</section>

<!-- FOOTER -->
<footer>
    <div class="container">
        <!--💡UPDATE: Change the year and your name-->
        <p>&copy; 2026 Sunday Maduabuchi. All rights reserved.</p>
    </div>
</footer>

<script src="assets/js/main.js"></script>

</body>
</html>
