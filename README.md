
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Digital Portfolio</title>

  <style>
    * {
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f4f7fb;
      color: #243047;
      line-height: 1.7;
    }

    header {
      background: linear-gradient(135deg, #14213d, #2563eb);
      color: white;
      text-align: center;
      padding: 70px 20px;
    }

    header h1 {
      font-size: 40px;
      margin-bottom: 10px;
    }

    header p {
      font-size: 18px;
      margin: 8px 0;
    }

    nav {
      background: #ffffff;
      text-align: center;
      padding: 16px 10px;
      position: sticky;
      top: 0;
    }

    nav a {
      color: #14213d;
      text-decoration: none;
      margin: 0 12px;
      font-weight: bold;
    }

    section {
      max-width: 900px;
      margin: 28px auto;
      padding: 28px;
      background: white;
      border-radius: 14px;
      box-shadow: 0 4px 16px rgba(0, 0, 0, 0.05);
    }

    h2 {
      color: #2563eb;
      margin-top: 0;
    }

    .skills {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(190px, 1fr));
      gap: 16px;
    }

    .skill-card {
      background: #edf3ff;
      padding: 18px;
      border-radius: 10px;
      border-left: 4px solid #2563eb;
    }

    .skill-card h3 {
      margin-top: 0;
      color: #14213d;
    }

    .project {
      padding: 16px 0;
      border-bottom: 1px solid #e5e7eb;
    }

    .project:last-child {
      border-bottom: none;
    }

    .contact-link {
      display: inline-block;
      background: #2563eb;
      color: white;
      padding: 12px 22px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
    }

    footer {
      background: #14213d;
      color: white;
      text-align: center;
      padding: 24px;
      margin-top: 35px;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 30px;
      }

      nav a {
        display: inline-block;
        margin: 5px;
      }

      section {
        margin: 18px 12px;
        padding: 22px;
      }
    }
  </style>
</head>

<body>

  <header>
    <h1>Hello, I'm RIDA</h1>
    <p>Digital Marketing & Creative Services</p>
    <p>Google Ads | Meta Ads | Video Editing | Content Writing</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>
      Welcome to my portfolio! I am interested in digital
      marketing and creative content. My skills include
      Google Ads, Meta Ads, video editing, and content writing.
      I enjoy creating engaging content and learning new ways
      to help businesses connect with their audiences.
    </p>
  </section>

  <section id="skills">
    <h2>My Skills</h2>

    <div class="skills">
      <div class="skill-card">
        <h3>Google Ads</h3>
        <p>Search advertising and campaign planning.</p>
      </div>

      <div class="skill-card">
        <h3>Meta Ads</h3>
        <p>Facebook and Instagram advertising and ad creatives.</p>
      </div>

      <div class="skill-card">
        <h3>Video Editing</h3>
        <p>Editing videos for social media and digital content.</p>
      </div>

      <div class="skill-card">
        <h3>Content Writing</h3>
        <p>Writing captions, posts, and engaging written content.</p>
      </div>
    </div>
  </section>

  <section id="projects">
    <h2>My Sample Projects</h2>

    <div class="project">
      <h3>Google Ads Campaign Plan</h3>
      <p>
        A practice project for planning a search advertising
        campaign for a sample business.
      </p>
    </div>

    <div class="project">
      <h3>Meta Ads Creative</h3>
      <p>
        A sample Facebook and Instagram advertisement concept
        for a fictional brand.
      </p>
    </div>

    <div class="project">
      <h3>Video Editing Sample</h3>
      <p>
        A sample short-form video concept for social media.
      </p>
    </div>

    <div class="project">
      <h3>Content Writing Sample</h3>
      <p>
        Sample social media captions and promotional content
        for a fictional business.
      </p>
    </div>

    <p>
      Note: These are sample project descriptions.
      Add your actual work or practice samples as you create them.
    </p>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>
      Interested in working together? You can contact me
      using the email address below.
    </p>
    <p>Email: ameengujjar670@gmail.com</p>
    <p>
      GitHub:
      <a href="https://github.com/riduu55">
        Visit my GitHub profile
      </a>
    </p>
  </section>

  <footer>
    <p>My Digital Portfolio | 2026</p>
  </footer>

</body>
</html>
