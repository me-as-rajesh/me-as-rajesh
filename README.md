Hi there 👋, I'm Rajesh Selvaraj
🚀 I'm a passionate Computer Science Master's student from Pondicherry, India, specializing in Windows and Mobile application development. I love building scalable, innovative solutions using modern technologies.

🔭 I’m currently working on real-time systems and full-stack applications
🌱 I’m learning advanced MERN stack and cloud technologies
👯 I’m looking to collaborate on open-source mobile and web projects
💬 Ask me about .NET, Android development, or Firebase
📫 How to reach me: srijesh2001@gmail.com
⚡ Fun fact: I enjoy creating apps that blend creativity with functionality, like wallpaper and face recognition systems!


About Me
I'm a fresher with a strong foundation in .NET, ASP.NET MVC, Web API, C#, SQL Server, and MERN stack (React.js, Node.js, Express.js). My projects demonstrate my ability to handle end-to-end development, from mobile apps to real-time web systems. Currently pursuing my M.Sc. in Computer Science (expected April 2025), I'm eager to contribute to innovative tech solutions.

Technical Skills



Category
Technologies



.NET Frameworks
.NET (1.0 to latest), ASP.NET, MVC, Web API


Web Technologies
HTML, CSS, JavaScript, Bootstrap, PHP, MERN Stack (React.js, Node.js, Express.js)


Mobile Technologies
Java, Android SDK, Android Applications


Communication Frameworks
Web API, Android Retrofit, Android Firebase


Tools & IDEs
Visual Studio, Android Studio, VS Code, MongoDB Atlas, SSMS, Postman


Databases
SQL Server, MongoDB



Featured Projects
All Actors Wallpaper

Technologies: Java, Firebase, ASP.NET MVC, Web API
Description: An Android app to download and set wallpapers, with a management dashboard built using ASP.NET MVC and data transfer via Web API.
Role: Developer

YouTube Video Downloader

Technologies: C#, Java, ASP.NET MVC, Web API
Description: A tool to download YouTube videos and store URL details in a server database, managed through ASP.NET MVC and Web API.
Role: Developer

TempText - Real-time Messaging System

Technologies: React.js, Node.js, Pusher, Axios
Description: A real-time messaging app where users send and retrieve temporary messages using unique IDs, auto-deleted after 5 minutes. Hosted on Render with real-time updates via Pusher.
Role: Developer

Real-time Face Recognition System

Technologies: Java, XML, Firebase (Realtime Database, Storage, Authentication)
Description: An Android app for real-time face recognition, training and storing face data in Firebase for instant matching.
Role: Developer

MyPart - Real-time Location Finder

Technologies: Java, XML, Firebase, Google Maps API
Description: A real-time location tracking app with profile viewing and interaction alerts, powered by Firebase and Google Maps API.
Role: Developer


Education

M.Sc. Computer Science (2023–2025, Expected April 2025)Saradha Gangadharan College, Pondicherry

B.Sc. Computer Science (2020–2023, CGPA: 7.28)Saradha Gangadharan College, Pondicherry

Class 12th (2019–2020, 51%)Government Higher Secondary School, Mazhavanthangal, Villupuram

Class 10th (2017–2018, 82%)Government Higher Secondary School, Malayarasan Kuppom, Villupuram



📊 GitHub Stats


Connect with Me

📧 srijesh2001@gmail.com
📱 +91 6379380256
🌐 GitHub: me-as-rajesh

Explore my repositories and feel free to reach out for collaboration or opportunities!

Light/Dark Mode Toggle
Switch between light and dark modes for a better viewing experience:
Toggle Dark Mode


  /* General styling */
  body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
    background-color: #f4f4f9;
    color: #333;
    transition: all 0.3s ease;
    line-height: 1.6;
  }

  /* Dark mode */
  body.dark-mode {
    background-color: #1a1a1a;
    color: #e0e0e0;
  }

  /* Animations for headers */
  h1, h2, h3 {
    animation: fadeInUp 1s ease-in-out;
  }

  @keyframes fadeInUp {
    0% { transform: translateY(20px); opacity: 0; }
    100% { transform: translateY(0); opacity: 1; }
  }

  /* Section styling */
  h2 {
    color: #007bff;
    border-bottom: 2px solid #007bff;
    padding-bottom: 5px;
    margin-bottom: 20px;
  }

  body.dark-mode h2 {
    color: #66b3ff;
    border-bottom-color: #66b3ff;
  }

  /* Table styling */
  table {
    width: 100%;
    border-collapse: collapse;
    margin: 20px 0;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  }

  th, td {
    padding: 12px;
    text-align: left;
    border: 1px solid #ddd;
  }

  th {
    background-color: #007bff;
    color: white;
  }

  body.dark-mode th {
    background-color: #0056b3;
  }

  body.dark-mode td {
    border-color: #444;
  }

  /* Button styling */
  #theme-toggle {
    padding: 12px 24px;
    background-color: #007bff;
    color: white;
    border: none;
    border-radius: 25px;
    cursor: pointer;
    transition: background-color 0.3s, transform 0.2s;
    margin: 20px 0;
    display: inline-block;
  }

  #theme-toggle:hover {
    background-color: #0056b3;
    transform: scale(1.05);
  }

  /* Links */
  a {
    color: #007bff;
    text-decoration: none;
    transition: color 0.3s;
  }

  a:hover {
    color: #0056b3;
    text-decoration: underline;
  }

  body.dark-mode a {
    color: #66b3ff;
  }

  body.dark-mode a:hover {
    color: #99ccff;
  }

  /* GitHub stats */
  img[src*="github-readme-stats"] {
    margin: 10px 0;
    animation: slideIn 1s ease-in-out;
  }

  @keyframes slideIn {
    0% { transform: translateX(-50px); opacity: 0; }
    100% { transform: translateX(0); opacity: 1; }
  }

  /* Responsive design */
  @media (max-width: 600px) {
    table, th, td {
      font-size: 0.85em;
    }

    h1 {
      font-size: 1.8em;
    }

    h2 {
      font-size: 1.4em;
    }

    #theme-toggle {
      padding: 10px 20px;
    }
  }



  // Theme toggle functionality
  const themeToggle = document.getElementById('theme-toggle');
  themeToggle.addEventListener('click', () => {
    document.body.classList.toggle('dark-mode');
    const isDark = document.body.classList.contains('dark-mode');
    localStorage.setItem('theme', isDark ? 'dark' : 'light');
    themeToggle.textContent = isDark ? 'Toggle Light Mode' : 'Toggle Dark Mode';
  });

  // Load saved theme
  window.addEventListener('load', () => {
    const savedTheme = localStorage.getItem('theme');
    if (savedTheme === 'dark') {
      document.body.classList.add('dark-mode');
      themeToggle.textContent = 'Toggle Light Mode';
    }
  });
