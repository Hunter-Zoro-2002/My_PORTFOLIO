# My_PORTFOLIO
MY BIO IN DYNAMIC STYLE
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Debaditya Ghosh Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
     rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@1,300;1,500&display=swap" rel="stylesheet">
    
    <style>
      * {
        margin: 0;
        padding: 0;
      }

      body {
        background-color: rgb(0, 0, 33);
        color: white;
        font-family: "poppins", sans-serif;
      }
      nav {
        display: flex;
        justify-content: space-around;
        align-items: center;
        height: 80px;
        background-color: rgb(18, 18, 62);
      }
      nav ul {
        display: flex;
        justify-content: center;
      }
      nav ul li {
        list-style: none;
        margin: 0 23px;
      }
      nav ul li a {
        text-decoration: none;
        color: white;
      }
      nav ul li a:hover {
        color: rgb(153, 153, 226);
        font-size: 1.09rem;
      }
      main hr {
        border: 0;
        background: #9c97f1;
        height: 1.2px;
        margin: 60px 84px;
      }
      .left {
        font-size: 1.5rem;
      }
      .firstSection {
        display: flex;
        justify-content: space-around;
        align-items: center;
        margin: 60px;
      }
      .firstSection > div {
        width: 30%;
      }
      .leftSection {
        font-size: 3rem;
        justify-content: center;
        margin: 70px 0;
      }

      .rightSection img {
        width: 80%;
        margin: 45px 0;
      }
      .purple {
        color: rgb(170, 107, 228);
      }
      .text-gray {
        color: grey;
      }
      #element {
        color: rgb(147, 59, 230);
      }
      .secondSection {
        max-width: 80vw;
        margin: auto;
        height: 80vh;
      }
      .secondSection h1 {
        font-size: 3rem;
      }
      .secondSection .box {
        background: white;
        width: 50vw;
        height: 2px;
        margin: 56px 0;
        display: flex;
      }
      .secondSection .vertical {  
        height: 93px;
        width: 1px;
        background-color: white;
        margin: 0 120px;
      }
      .image-top{
        width: 56px;
        position: relative;
        top: -60px;
        left: -9px;
      }
      .vertical-title{
        position: relative;
        top: 75px;
        width: 150px;
      }
      .vertical-desc{
        position: relative;
        top: 86px;
        color: gray;
        width: 150px;
        font-size: 9px;
      }
    </style>
  </head>

  <body>
    <header>
      <nav>
        <div class="left">Debaditya Ghosh </div>
        <div class="right">
          <ul>
            <li><a href="/">Home</a></li>
            <li><a href="/">About</a></li>
            <li><a href="/">Services</a></li>
            <li><a href="/">Projects</a></li>
            <li><a href="/">Contact Me</a></li>
          </ul>
        </div>
      </nav>
    </header>
    <main>
      <section class="firstSection">
        <div class="leftSection">
          Hi, I am <span class="purple">Debaditya Ghosh</span>
          <div>And I am passionate in</div>
          <span id="element"></span>
        </div>
        <div class="rightSection">
          <img src="Deb.png" alt="background image" />
        </div>
      </section>
      <hr />
      <section class="secondSection">
        <span class="text-gray">What I have Done So far</span>
        <h1>Internships</h1>

        <div class="box">
          <div class="vertical">
            <img class="image-top" src="hacker.png" alt=""/>
            <div class="vertical-title">CYBER A1 GLOBAL SOLUTION’S LLP (2024.06-2024.10)</div>
            <div class="vertical-title"><u>Security Testing</u></div>
            <div class="vertical-desc">
             <div>•	Gained hands-on experience in evaluating the security of websites, identifying vulnerabilities, and suggesting enhancements.</div> 
             <div>•	Analyzed codebases to detect potential security risks and improve code integrity.</div>
             <div>•	Learned and applied automated tools for vulnerability scanning and assessment, increasing efficiency in security checks.</div>
             <div>•	Carried out detailed manual testing to complement automated methods, ensuring thorough security validation.</div>
             <div>•	Developed a solid foundation in cybersecurity principles and practices through practical application.</div>
              
            </div>
          </div>
          <div class="vertical">
            <img class="image-top" src="developer.png" alt="" />
            <div class="vertical-title">Linkwide Webel IT Park PVT LTDs(2023.02-2023.03)</div>
            <div class="vertical-title"><u>Data Analyst</u></div>
            <div class="vertical-desc">
            <div>•Analyzed raw data and organized it into structured spreadsheets for better accessibility and understanding.</div>
            <div>• Communicated directly with clients to understand their requirements and address any queries, ensuring alignment with project goals.</div>
           <div>• Maintained accurate records of data and client interactions, enhancing data reliability and project traceability.</div>
          </div>
          </div>
          
          
          </div>
      </section>
     
    </main>

    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>

    <script>
      var typed = new Typed("#element", {
        strings: [
          "Web Developer",
          "Cyber Security",
          "and Ethical Hacking....",
        ],
        typeSpeed: 40,
      });
    </script>
  </body>
</html>
