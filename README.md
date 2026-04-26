# TeacherIT
TeacherIT
<!DOCTYPE html>
<html lang="km">
<head>
<meta charset="UTF-8">
<title>តេង សុខី - Personal Website</title>

<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background: #f2f6ff;
    }

    /* HERO */
    .hero {
        background: linear-gradient(90deg, #0066ff, #00c6ff);
        color: white;
        text-align: center;
        padding: 60px 20px;
    }

    .hero img {
        width: 130px;
        height: 130px;
        border-radius: 50%;
        border: 4px solid white;
        margin-top: 10px;
    }

    /* NAV */
    nav {
        background: #111;
        text-align: center;
        padding: 10px;
    }

    nav a {
        color: white;
        margin: 10px;
        text-decoration: none;
        font-weight: bold;
    }

    nav a:hover {
        color: yellow;
    }

    /* CONTAINER */
    .container {
        max-width: 900px;
        margin: auto;
        padding: 20px;
    }

    .card {
        background: white;
        padding: 20px;
        margin-top: 15px;
        border-radius: 12px;
        box-shadow: 0 3px 12px rgba(0,0,0,0.1);
    }

    /* SKILLS BAR */
    .skill {
        margin: 10px 0;
    }

    .bar {
        background: #ddd;
        border-radius: 20px;
        overflow: hidden;
    }

    .bar-fill {
        height: 15px;
        background: #007BFF;
        width: 0;
        animation: load 2s forwards;
    }

    @keyframes load {
        from { width: 0; }
        to { width: var(--w); }
    }

    /* CONTACT FORM */
    input, textarea {
        width: 100%;
        padding: 10px;
        margin-top: 8px;
        border-radius: 8px;
        border: 1px solid #ccc;
    }

    button {
        background: #007BFF;
        color: white;
        padding: 10px;
        border: none;
        margin-top: 10px;
        border-radius: 8px;
        cursor: pointer;
    }

    button:hover {
        background: #0056b3;
    }

    footer {
        background: #111;
        color: white;
        text-align: center;
        padding: 15px;
        margin-top: 20px;
    }
</style>
</head>

<body>

<div class="hero">
    <h1>សួស្តី! ខ្ញុំឈ្មោះ តេង សុខី</h1>
    <p>Student | IT | Video Editor | Web Developer</p>

    <img src="https://via.placeholder.com/130" alt="Profile">
</div>

<nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Skills</a>
    <a href="#">Contact</a>
</nav>

<div class="container">

    <div class="card">
        <h2>អំពីខ្ញុំ</h2>
        <p>
            ខ្ញុំជាសិស្សដែលកំពុងរៀន IT និងចាប់អារម្មណ៍លើការបង្កើត website,
            ការកាត់តវីដេអូ និងបច្ចេកវិទ្យាថ្មីៗ។
        </p>
    </div>

    <div class="card">
        <h2>ជំនាញ</h2>

        <div class="skill">
            <p>HTML / CSS</p>
            <div class="bar"><div class="bar-fill" style="--w: 85%"></div></div>
        </div>

        <div class="skill">
            <p>Video Editing</p>
            <div class="bar"><div class="bar-fill" style="--w: 75%"></div></div>
        </div>

        <div class="skill">
            <p>Computer</p>
            <div class="bar"><div class="bar-fill" style="--w: 80%"></div></div>
        </div>
    </div>

    <div class="card">
        <h2>ទំនាក់ទំនង</h2>

        <input type="text" placeholder="ឈ្មោះរបស់អ្នក">
        <input type="email" placeholder="Email">
        <textarea rows="4" placeholder="សរសេរសារ..."></textarea>

        <button>ផ្ញើសារ</button>
    </div>

</div>

<footer>
    © 2026 តេង សុខី | Personal Website
</footer>

</body>
</html>
