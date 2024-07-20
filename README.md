# Assignment 1
![image](https://github.com/Dharshini-DS/html-ABC-college/assets/93427345/56d19c96-5242-4f9f-9f65-7d1677062412)
### main.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PORTFOLIO</title>
</head>
<body>
    <table border="1"  width="100%">
        <tbody>
            <tr>
                <th colspan="2" align="center">MY DAY</th>
            </tr>
            <tr>
                <td>
                        1.wakeup early
                        <ul>
                            <li style="list-style-type:disc">5 Am</li>
                            <li>walk</li>
                            <li>jog</li>
                        </ul>
                </td>
                <td rowspan="3">
                    <table border="2" align="center">
                        <tbody>
                            <tr>
                                <th colspan="2">Things to watch
                                    
                                </th>
                            </tr>
                            <tr>
                                <td>
                                    <img src="img.jfif" width="100" height="100">
                                </td>
                                <td>
                                    <img src="img2.jpg" width="100" height="100">
                                </td>
                            </tr>
                            <tr>
                                <td>
                                    <img src="img3.jpg" width="100" height="100">
                                </td>
                                <td>
                                    <img src="img4.jpg" width="100" height="100">
                                </td>
                            </tr>
    
                        </tbody>
    
                    </table>
                </td>
            </tr>
            
            <tr>
                <td>
                       2. breakfast
                    <ul>
                        <li>8AM</li>
                        <li>eggs</li>
                        <li>coffee</li>
                    </ul> 
                </td>
            </tr>
            <tr>
                <td>
                    3. go to Saveetha
                        <ul>
                            <li>8AM</li>
                            <li>attend classes</li>
                            <li>to be continued</li>
                        </ul>
                    </ol>    
                </td>
                
            </tr>
        </tbody>
    </table>
</body>
</html>
```
## Output

![image](https://github.com/Dharshini-DS/html-ABC-college/assets/93427345/324dfbda-9307-4b2d-b157-2003a422a3e7)


# Assignment 2
![image](https://github.com/Dharshini-DS/html-ABC-college/assets/93427345/f8ae9472-7993-4bc5-bbc2-0bbb8735dd93)

### home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="header-content">
            <div class="logo">
                <img src="/images/img1.png" alt="College Logo">
            </div>
            <ul class="nav-links">
                <li><a href="#">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="courses.html">Courses</a></li>
            </ul>
        </div>    
    </header>
    <main>
        <h1>Engineering College</h1>
        <br>
        <p>Welcome to our college, where we offer a wide range of academic programs and extracurricular activities.</p>
    </main>
    <footer>
        <p>&copy; 2024 Engineering College . All rights reserved.</p>
    </footer>
</body>
</html>
```
### academics.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Academics</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="header-content">
            <div class="logo">
                <img src="/images/img1.png" alt="College Logo">
            </div>
            <ul class="nav-links">
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="courses.html">Courses</a></li>
            </ul>
        </div>    
    </header>
    <main>
        <h1>Engineering College</h1>
        <br>
        <p>Explore our academic programs and research opportunities.</p>
    </main>
    <footer>
        <p>&copy; 2024 Engineering College . All rights reserved.</p>
    </footer>
</body>
</html>
```
### admission.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Academics</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="header-content">
            <div class="logo">
                <img src="/images/img1.png" alt="College Logo">
            </div>
            <ul class="nav-links">
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="courses.html">Courses</a></li>
            </ul>
        </div>    
    </header>
    <main>
        <h1>Admission</h1>
        <br>
        <p>Welcome to our college, where we offer a wide range of academic programs and extracurricular activities.</p>
        <section style="padding: 20px;">
            <h2>Admission Form</h2>
            <form action="#" method="post">
                <label for="name">Name:</label><br>
                <input type="text" id="name" name="name"><br><br>
                
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email"><br><br>
                
                <label for="phone">Phone:</label><br>
                <input type="tel" id="phone" name="phone"><br><br>
                
                <label for="course">Course:</label><br>
                <select id="course" name="course">
                    <option value="computer-science">Computer Science</option>
                    <option value="mathematics">Mathematics</option>
                    <option value="english">English</option>
                    <option value="sociology">Sociology</option>
                    <option value="economics">Economics</option>
                    <option value="business-management">Business Management</option>
                </select><br><br>
                
                <label for="message">Message:</label><br>
                <textarea id="message" name="message" rows="4" cols="50"></textarea><br><br>
                
                <input type="submit" value="Submit">
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Engineering College . All rights reserved.</p>
    </footer>
</body>
</html>
```
### gallery.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Academics</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="header-content">
            <div class="logo">
                <img src="/images/img1.png" alt="College Logo">
            </div>
            <ul class="nav-links">
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="courses.html">Courses</a></li>
            </ul>
        </div>    
    </header>
    <main>
        <h1>Gallery</h1>
        <br>
        <p>Explore our campus and student life through these photos.</p>
        <img src="/images/c1.jfif" alt="Gallery Image 1" width="20%" height="25%">
        <img src="/images/c2.jfif" alt="Gallery Image 1" width="20%" height="25%">
        <img src="/images/c3.jfif" alt="Gallery Image 1" width="21.5%" height="35%">
        <img src="/images/c5.jpg" alt="Gallery Image 1" width="20%" height="25%">
    </main>
    <footer>
        <p>&copy; 2024 Engineering College . All rights reserved.</p>
    </footer>
</body>
</html>
```
### courses.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Courses Offered</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="header-content">
            <div class="logo">
                <img src="/images/img1.png" alt="College Logo">
            </div>
            <ul class="nav-links">
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="courses.html">Courses</a></li>
            </ul>
        </div>    
    </header>
    <main>
        <h1>Courses Offered</h1>
        <p>We offer a diverse range of courses across multiple disciplines. Explore our course offerings below:</p>
        <br>
        <br>
        <ul>
            <li><a href="computer-science.html">Computer Science</a></li>
            <li><a href="mathematics.html">Mathematics</a></li>
            <li><a href="english.html">English</a></li>
            <li><a href="sociology.html">Sociology</a></li>
            <li><a href="economics.html">Economics</a></li>
            <li><a href="business-management.html">Business Management</a></li>
        </ul>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
### computer-science.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Computer Science</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="header-content">
            <div class="logo">
                <img src="/images/img1.png" alt="College Logo">
            </div>
            <ul class="nav-links">
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="courses.html">Courses</a></li>
            </ul>
        </div>    
    </header>
    <main>
        <h1>Computer Science</h1>
        <br>
        <p>Welcome to the Computer Science department. Here you can find information about our programs, faculty, and research opportunities.</p>
        <br>
        <h2>Faculty</h2>
        <ul>
            <li>Dr.James Richard - james1234@college.edu</li>
            <li>Prof.Lily William - lily1234@college.edu</li>
        </ul>
        <br>
        <table border="1"  width="80%">
            <tbody>
                <tr>
                    <th>DAY</th>
                    <th>TIME</th>
                    <th>COURSE NAME</th>
                </tr>
                <tr>
                    <td>Monday</td>
                    <td>8.00 a.m - 10.00 a.m</td>
                    <td>Computer Science</td>   
                </tr>
            </tbody>
        </table>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
### mathematics.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mathematics</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="header-content">
            <div class="logo">
                <img src="/images/img1.png" alt="College Logo">
            </div>
            <ul class="nav-links">
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="courses.html">Courses</a></li>
            </ul>
        </div>    
    </header>
    <main>
        <h1>Mathematics</h1>
        <p>The Mathematics program at College Name offers a rigorous education in pure and applied mathematics. Our curriculum includes courses in calculus, linear algebra, differential equations, probability, and more.</p>
        <h2>Course Structure</h2>
        <ul>
            <li>Calculus I</li>
            <li>Calculus II</li>
            <li>Linear Algebra</li>
            <li>Differential Equations</li>
            <li>Probability and Statistics</li>
            <li>Numerical Methods</li>
        </ul>
        <h2>Faculty</h2>
        <ul>
            <li>Dr.John Adams - johnaams4@college.edu</li>
            <li>Prof.Luna Victer - lunavicter3@college.edu</li>
        </ul>
        <br>
        <table border="1"  width="80%">
            <tbody>
                <tr>
                    <th>DAY</th>
                    <th>TIME</th>
                    <th>COURSE NAME</th>
                </tr>
                <tr>
                    <td>Tuesday</td>
                    <td>8.00 a.m - 10.00 a.m</td>
                    <td>Mathematics</td>   
                </tr>
            </tbody>
        </table>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
### english.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>English</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="header-content">
            <div class="logo">
                <img src="/images/img1.png" alt="College Logo">
            </div>
            <ul class="nav-links">
                <li><a href="#">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="courses.html">Courses</a></li>
            </ul>
        </div>    
    </header>
    <main>
        <h1>English</h1>
        <p>The English program at College Name covers literature, writing, and critical thinking. Students will explore a wide range of literary works and develop strong analytical and communication skills.</p>
        <h2>Course Structure</h2>
        <ul>
            <li>Introduction to Literature</li>
            <li>Creative Writing</li>
            <li>Shakespearean Studies</li>
            <li>American Literature</li>
            <li>Modernist Literature</li>
            <li>Literary Theory</li>
        </ul>
        <h2>Faculty</h2>
        <ul>
            <li>Dr.Sirius Brown - siriusbrown97@college.edu</li>
            <li>Prof.John Doe - johndoe86@college.edu</li>
        </ul>
        <br>
        <table border="1"  width="80%">
            <tbody>
                <tr>
                    <th>DAY</th>
                    <th>TIME</th>
                    <th>COURSE NAME</th>
                </tr>
                <tr>
                    <td>Tuesday</td>
                    <td>1.00 p.m - 3.00 p.m</td>
                    <td>English</td>   
                </tr>
            </tbody>
        </table>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
### sociology.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sociology</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="header-content">
            <div class="logo">
                <img src="/images/img1.png" alt="College Logo">
            </div>
            <ul class="nav-links">
                <li><a href="#">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="courses.html">Courses</a></li>
            </ul>
        </div>    
    </header>
    <main>
        <h1>Sociology</h1>
        <p>The Sociology program at College Name examines the structures of societies, groups, and organizations. Our courses cover topics such as social theory, research methods, and social issues.</p>
        <h2>Course Structure</h2>
        <ul>
            <li>Introduction to Sociology</li>
            <li>Social Theory</li>
            <li>Research Methods in Sociology</li>
            <li>Sociology of Education</li>
            <li>Sociology of Health</li>
            <li>Criminology</li>
        </ul>
        <h2>Faculty</h2>
        <ul>
            <li>Dr.Poorna Shankar - poornashankar54@college.edu</li>
            <li>Prof.Ben Smith - bensmith67@college.edu</li>
        </ul>
        <br>
        <table border="1"  width="80%">
            <tbody>
                <tr>
                    <th>DAY</th>
                    <th>TIME</th>
                    <th>COURSE NAME</th>
                </tr>
                <tr>
                    <td>Monday</td>
                    <td>10.00 a.m - 12.00 a.m</td>
                    <td>Sociology</td>   
                </tr>
            </tbody>
        </table>
    </main>
</head>
</html>
```
### economics.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Economics</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="header-content">
            <div class="logo">
                <img src="/images/img1.png" alt="College Logo">
            </div>
            <ul class="nav-links">
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="courses.html">Courses</a></li>
            </ul>
        </div>    
    </header>
    <main>
        <h1>Economics</h1>
        <p>The Economics program at College Name provides students with a solid foundation in economic theory, quantitative methods, and applied economics. Our curriculum prepares students for careers in business, government, and research.</p>
        <h2>Course Structure</h2>
        <ul>
            <li>Introduction to Economics</li>
            <li>Econometrics</li>
            <li>Public Economics</li>
            <li>International Economics</li>
            <li>Labor Economics</li>
            <li>Financial Economics</li>
        </ul>
        <h2>Faculty</h2>
        <ul>
            <li>Dr.Cedric Brown - cedricbrown78@college.edu</li>
            <li>Prof.Robert William - robert786@college.edu</li>
        </ul>
        <br>
        <table border="1"  width="80%">
            <tbody>
                <tr>
                    <th>DAY</th>
                    <th>TIME</th>
                    <th>COURSE NAME</th>
                </tr>
                <tr>
                    <td>Thursday</td>
                    <td>8.00 a.m - 10.00 a.m</td>
                    <td>Economics</td>   
                </tr>
            </tbody>
        </table>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
### business-management.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Business Management</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="header-content">
            <div class="logo">
                <img src="/images/img1.png" alt="College Logo">
            </div>
            <ul class="nav-links">
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="courses.html">Courses</a></li>
            </ul>
        </div>    
    </header>
    <main>
        <h1>Business Management</h1>
        <p>The Business Management program at College Name equips students with the knowledge and skills needed to succeed in the business world. Our curriculum covers management principles, organizational behavior, finance, marketing, and more.</p>
        <h2>Course Structure</h2>
        <ul>
            <li>Principles of Management</li>
            <li>Organizational Behavior</li>
            <li>Financial Management</li>
            <li>Marketing Management</li>
            <li>Human Resource Management</li>
            <li>Business Ethics</li>
        </ul>
        <h2>Faculty</h2>
        <ul>
            <li>Dr.Robert Johnson - robertjohn98@college.edu</li>
            <li>Prof.Jessy Richard - jessyrichard67@college.edu</li>
        </ul>
        <br>
        <table border="1"  width="80%">
            <tbody>
                <tr>
                    <th>DAY</th>
                    <th>TIME</th>
                    <th>COURSE NAME</th>
                </tr>
                <tr>
                    <td>Wednesday</td>
                    <td>1.00 p.m - 3.00 p.m</td>
                    <td>Business Management</td>   
                </tr>
            </tbody>
        </table>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
### style.css
```
*{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

li{
    list-style-type: none;
    margin: 0.1rem;
}

a{
    text-decoration: none;
    font-size: 200%;
    color: maroon;
}

img{
    padding: 1rem;
    max-height: 100%;
    max-width: 100%;
}

header{
    background-color: lightcoral;
    min-height: 5vh;
    
}

.header-content{
    width: 95%;
    margin: auto;
    display: flex;
    justify-content: space-between;
}

.logo{
    height: 180px;
}

.nav-links{
    display: flex;
    width: 60%;
    justify-content: space-between;
    align-items: center;

}

main{
    padding: 2rem;
    font-size: 200%;
}

footer {
    background-color: lightcoral;
    color: white;
    font-size: 150%;
    text-align: center;
    padding: 2rem;
    position: fixed;
    width: 100%;
    bottom: 0;
}
```
## OUTPUT:

### home.html
![image](https://github.com/Dharshini-DS/html-ABC-college/assets/93427345/e5c71a09-f01b-4b32-aae0-5e02df9efdf8)

### academics.html
![image](https://github.com/Dharshini-DS/html-ABC-college/assets/93427345/2a97c697-6071-4846-adf3-297f943ec198)

### admission.html
![image](https://github.com/Dharshini-DS/html-ABC-college/assets/93427345/5a4d7005-cef5-40c9-a903-9e3122a29bd8)

### gallery.html
![image](https://github.com/Dharshini-DS/html-ABC-college/assets/93427345/425cab6e-9b43-4cdf-a042-7e98f9bcc224)

### courses.html
![image](https://github.com/Dharshini-DS/html-ABC-college/assets/93427345/de781b4f-c171-41ca-927e-8f77ecf3c8b9)

### computer-science.html
![image](https://github.com/Dharshini-DS/html-ABC-college/assets/93427345/f6b0350a-acbb-4b71-bd89-3b7f4b67ac5e)

### mathematics.html
![image](https://github.com/Dharshini-DS/html-ABC-college/assets/93427345/7cb95089-0019-468a-9f09-791b0b883579)

### english.html
![image](https://github.com/Dharshini-DS/html-ABC-college/assets/93427345/8f6b2969-7f1f-4e69-83f8-199cc5bf129f)

### sociology.html
![image](https://github.com/Dharshini-DS/html-ABC-college/assets/93427345/16f0a694-007e-424c-8b85-c28d81608a64)

### economics.html
![image](https://github.com/Dharshini-DS/html-ABC-college/assets/93427345/8a7d397c-88fd-410c-b019-184d344a2e73)

### business-management.html
![image](https://github.com/Dharshini-DS/html-ABC-college/assets/93427345/254258a4-deb5-45bb-a42f-3eaa52561d6e)
