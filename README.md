<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dion S. Baylon | Resume</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Dion S. Baylon</h1>
        <p>Electrical Engineer</p>
        <p>Contact: baylondion18@gmail.com | 09636887092</p>
    </header>

    <!-- About Me Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>I am a passionate and dedicated Electrical Engineer with a strong foundation in electrical systems and circuit design. With hands-on experience in both project management and technical design, I aim to improve and optimize electrical systems while ensuring they are safe, reliable, and cost-effective. I thrive in fast-paced environments and am always looking for innovative solutions to complex engineering challenges.</p>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Electrical Circuit Design</li>
            <li>Power Systems</li>
            <li>Control Systems</li>
            <li>Signal Processing</li>
            <li>Project Management</li>
            <li>Feasibility Studies & Risk Assessments</li>
            <li>Autocad Electrical</li>
            <li>Software: MATLAB, Simulink, AutoCAD</li>
            <li>Excellent Troubleshooting Skills</li>
        </ul>
    </section>

    <!-- Experience Section -->
    <section id="experience">
        <h2>Experience</h2>
        <div class="job">
            <h3>Electrical Engineer - Amelia Construction</h3>
            <p>October 2028 - Present | Quezon City</p>
            <p>Designed, developed, and tested electrical systems and components for construction projects. Collaborated with cross-functional teams to ensure technical specifications and client requirements were met. Led troubleshooting and optimization of electrical circuits, improving performance by 100%. Managed project timelines to ensure timely and budget-friendly project completion. Prepared detailed technical documentation, including design reports, test results, and compliance certifications. Conducted feasibility studies and risk assessments to improve safety and system reliability.</p>
        </div>
    </section>

    <!-- Education Section -->
    <section id="education">
        <h2>Education</h2>
        <p><strong>Bachelor of Science in Electrical Engineering</strong><br>
        New Era University, Quezon City — November, 2027</p>
        <p><strong>Relevant Coursework:</strong> Circuit Design, Power Systems, Control Systems, Digital Electronics, Signal Processing</p>
        <p><strong>GPA:</strong> 1.5</p>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio">
        <h2>Portfolio</h2>
        <p><strong>Electrical Engineer at Amelia Construction</strong> — Led the design and development of electrical systems for various projects in the construction industry. A detailed collection of my work can be found on request or through my professional network.</p>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials">
        <h2>Testimonials</h2>
        <blockquote>
            "Dion is a dedicated and reliable engineer who consistently delivers excellent work. His technical expertise and problem-solving skills have greatly contributed to the success of our projects." — <strong>Project Manager, Amelia Construction</strong>
        </blockquote>
        <blockquote>
            "Dion’s work ethic and ability to communicate effectively with cross-functional teams made him a standout engineer on our projects. His contributions were invaluable." — <strong>Senior Engineer, New Era University</strong>
        </blockquote>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>Connect with me on <a href="https://www.facebook.com/DionBaylon" target="_blank">Facebook</a>.</p>
        <p><a href="Dion_Baylon_Resume.pdf" target="_blank">Download Resume</a></p>
    </footer>

</body>
</html>
/* Reset some default styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body styles */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    padding: 20px;
}

/* Header styling */
header {
    text-align: center;
    background-color: #333;
    color: white;
    padding: 20px;
}

header h1 {
    font-size: 2.5em;
}

header p {
    font-size: 1.1em;
}

/* Section styles */
section {
    margin: 20px 0;
}

h2 {
    color: #333;
    margin-bottom: 10px;
}

/* Skills Section */
#skills ul {
    list-style: none;
    display: flex;
    flex-wrap: wrap;
}

#skills ul li {
    margin: 10px;
    padding: 8px;
    background-color: #333;
    color: white;
    border-radius: 5px;
}

/* Job Experience Section */
#experience .job {
    margin-bottom: 15px;
}

#experience h3 {
    font-size: 1.5em;
    color: #333;
}

#experience p {
    color: #666;
}

/* Portfolio Section */
#portfolio {
    margin: 20px 0;
}

/* Testimonials Section */
#testimonials blockquote {
    background-color: #eee;
    padding: 10px;
    border-left: 5px solid #333;
    margin: 10px 0;
}

#testimonials blockquote p {
    font-style: italic;
    color: #555;
}

/* Footer Styling */
footer {
    text-align: center;
    margin-top: 40px;
    padding: 20px;
    background-color: #333;
    color: white;
}

footer a {
    color: #4CAF50;
    text-decoration: none;
}
