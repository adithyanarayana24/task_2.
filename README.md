# task_2.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adithya's Portfolio</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
            line-height: 1.6;
        }

        /* Header Styles */
        header {
            background-color: #4b6584;
            color: #f7b731;
            text-align: center;
            padding: 40px;
            position: relative;
        }
        header h1 {
            font-size: 4rem;
            margin: 0;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }
        header p {
            font-size: 1.5rem;
        }
        header a {
            color: #f7b731;
            text-decoration: none;
            font-weight: bold;
        }
        header::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://images.unsplash.com/photo-1506748686214-e9df14d4d9d0') center center / cover no-repeat;
            opacity: 0.3;
            z-index: -1;
        }

        /* Section Styles */
        section {
            padding: 60px 20px;
            margin: 20px;
            border-radius: 15px;
            background: #ffffff;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            border: 2px solid #4b6584;
            position: relative;
        }
        section h2 {
            font-size: 3rem;
            margin-bottom: 20px;
            color: #4b6584;
            border-bottom: 2px solid #f7b731;
            padding-bottom: 10px;
        }
        section p {
            font-size: 1.3rem;
        }
        .project-item, .experience-item {
            margin-bottom: 20px;
            border-left: 4px solid #4b6584;
            padding-left: 15px;
        }
        .project-item h3, .experience-item h3 {
            font-size: 2.5rem;
            color: #4b6584;
        }
        .project-item p, .experience-item p {
            font-size: 1.2rem;
        }
        .project-item img, .experience-item img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            margin-top: 10px;
        }

        /* Footer Styles */
        footer {
            background-color: #4b6584;
            color: #f7b731;
            text-align: center;
            padding: 20px 0;
            border-top: 2px solid #f7b731;
        }
        footer p {
            margin: 0;
            font-size: 1.2rem;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <div>
            <h1>Adithya</h1>
            <p>LinkedIn: <a href="https://www.linkedin.com/in/j-adithya-narayana-2685ba319" target="_blank">www.linkedin.com/in/j-adithya-narayana-2685ba319</a></p>
            <p>Email: <a href="mailto:adithyas2428@gmail.com">adithyas2428@gmail.com</a></p>
        </div>
    </header>

    <!-- Education Section -->
    <section>
        <h2>Education</h2>
        <p><strong>Gate Institute of Technology, Bangalore</strong> <br>
        B.Tech. Computer Science and Engineering <br>
        CGPA: 8.0/10 <br>
        July 2021 - 2025</p>

        <p><strong>Narayana Junior College</strong> <br>
        12th Board Percentage: 85% <br>
        March 2021</p>

        <p><strong>Narayana SCHOOL</strong> <br>
        10th Board Percentage: 92% <br>
        March 2019</p>
    </section>

    <!-- Technical Skills Section -->
    <section>
        <h2>Technical Skills</h2>
        <p>Programming Languages: C, Java, Python</p>
    </section>

    <!-- Projects Section -->
    <section>
        <h2>Projects</h2>
        <div class="project-item">
            <h3>AI-based Chatbot System</h3>
            <p>Developer at Gate Institute of Technology <br>
            September 2023 - December 2023 <br>
            Developed an AI-based chatbot system to enhance customer interaction for online services. Utilized cloud computing and machine learning algorithms for efficient chatbot operations.</p>
            <img src="https://images.unsplash.com/photo-1590608819571-f730b42f35c6" alt="AI-based Chatbot System">
        </div>
        <div class="project-item">
            <h3>Machine Learning Image Classification</h3>
            <p>Developer at Gate Institute of Technology <br>
            January 2024 - Present <br>
            Currently working on a machine learning project focused on image classification. Utilizing Python and TensorFlow to build and train models for accurate image recognition and classification.</p>
            <img src="https://images.unsplash.com/photo-1512042559030-0820f70e0218" alt="Machine Learning Image Classification">
        </div>
    </section>

    <!-- Experience Section -->
    <section>
        <h2>Experience</h2>
        <div class="experience-item">
            <h3>AICTE</h3>
            <p>Internship <br>
            November 2023 <br>
            Completed a virtual internship focused on AI and machine learning applications. Gained hands-on experience in developing and implementing AI-based solutions.</p>
            <img src="https://images.unsplash.com/photo-1517430816045-df4b7de8d0e5" alt="AICTE Internship">
        </div>
    </section>

    <!-- Licenses & Certifications Section -->
    <section>
        <h2>Licenses & Certifications</h2>
        <p>AI ML Virtual Internship, November 2023 - AICTE</p>
        <p>Google for Android Developer Internship, November 2023 - AICTE</p>
    </section>

    <!-- Extra-Curricular Activities Section -->
    <section>
        <h2>Extra-Curricular Activities</h2>
        <p>Painting</p>
        <p>Volunteer for local community service initiative</p>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Adithya. All rights reserved.</p>
    </footer>

</body>
</html>
