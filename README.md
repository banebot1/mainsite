# mainsite<!DOCTYPE html>
<html lang="en">
  <style>
     :root {
            --primary-color: #2c3e50;
            --secondary-color: #3498db;
            --accent-color: #e74c3c;
            --text-color: #333;
            --light-bg: #f8f9fa;
            --font-main: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: var(--font-main);
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--light-bg);
        }
        
        header {
            background-color: var(--primary-color);
            color: white;
            text-align: center;
            padding: 2rem 1rem;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        
        header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        
        nav {
            background-color: white;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        
        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            padding: 1rem;
        }
        
        nav ul li {
            margin: 0 1.5rem;
        }
        
        nav ul li a {
            color: var(--primary-color);
            text-decoration: none;
            font-weight: 600;
            font-size: 1.1rem;
            padding: 0.5rem 1rem;
            border-radius: 4px;
            transition: all 0.3s ease;
        }
        
        nav ul li a:hover {
            background-color: var(--secondary-color);
            color: white;
        }
        
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 2rem;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 15px rgba(0, 0, 0, 0.1);
        }
        
        .container h2 {
            color: var(--primary-color);
            margin-bottom: 1rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid var(--secondary-color);
        }
        
        .container p {
            margin-bottom: 1rem;
        }
        
        footer {
            text-align: center;
            padding: 2rem;
            background-color: var(--primary-color);
            color: white;
            margin-top: 2rem;
        }
        
        .student-info {
            margin-top: 2rem;
            padding: 1rem;
            background-color: #f1f5f9;
            border-left: 4px solid var(--secondary-color);
            border-radius: 4px;
        }
        
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                align-items: center;
            }
            
            nav ul li {
                margin: 0.5rem 0;
            }
            
            header h1 {
                font-size: 2rem;
            }
        }
      
    </style>
    <head>
        <meta charset="UTF-8">  
        <meta name="viewport" content="width=device-width, initial-scale=1.0">  
        <title>BSA Reviewer Site | NCBA 2024-2025</title>  
        <link rel="stylesheet" href="styles.css">
    </head> 
    <body> 
       <header>
        <h1>REVIEWER SITE</h1>
        <p>For BSA students in 2nd year</p>
        <p>(Focused curriculum on NCBA batch 2024-2025)</p>
    </header>   
         <nav>  
        <ul>  
            <li><a href="case_studies.html">INTERMEDIATE ACCOUNTING 2</a></li>  
            <li><a href="about.html">BUSINESS TAXATION</a></li>  
            <li><a href="contact.html">REGULATORY FRAMEWORK AND LEGAL ISSUES IN BUSINESS</a></li>  
            <li><a href="resources.html">COST ACCOUNTING AND CONTROL</a></li>
        </ul>  
    </nav>  
         <div class="container">  
        <h2>Welcome to the BSA Reviewer Site</h2>
        <p>This comprehensive resource is designed to help BSA students excel in their studies at NCBA. Browse through our case studies, review materials, and study guides tailored specifically for the 2024-2025 curriculum.</p>
        
        <h2>Creator's Note</h2>  
        <p>This website was created by a student of NCBA for the purpose of helping other students in their studies.</p>
        
        <div class="student-info">
            <p><strong>Student no. 2023-10085</strong> wishes you the best in your academic journey.</p>
        </div>
    </div>
    
    <footer>
        <p>&copy; 2025 BSA Reviewer Site | NCBA</p>
    </footer>
    </html>
