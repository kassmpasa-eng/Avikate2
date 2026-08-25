<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Avikate | Build • Connect • Grow</title>

    <style>
        * {
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            color: #102a5c;
            background: #ffffff;
        }
<nav>
    <div class="logo">
        <img src="avikate-logo.png" alt="Avikate Logo">
    </div>

    <div class="nav-links">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </div>
</nav>
        /* ===== LOGO ===== */
        .logo {
            display: flex;
            align-items: center;
            gap: 10px;
            text-decoration: none;
            color: #123b86;
        }
nav {
    background: white;
    padding: 15px 30px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.logo img {
    width: 180px;
    height: auto;
}

.nav-links a {
    color: #0a2e6b;
    text-decoration: none;
    margin: 0 12px;
    font-weight: bold;
}

.nav-links a:hover {
    color: #00d4ff;
}
        .logo-mark {
            font-size: 48px;
            font-weight: 900;
            font-style: italic;
            color: #087cff;
        }

        .logo-text {
            font-size: 25px;
            font-weight: 900;
            letter-spacing: 2px;
        }

        .tagline {
            display: block;
            font-size: 8px;
            letter-spacing: 3px;
            color: #23416f;
        }

        /* ===== NAVIGATION ===== */
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 6%;
            background: white;
            box-shadow: 0 2px 10px rgba(0,0,0,0.08);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .nav-links {
            display: flex;
            gap: 30px;
            align-items: center;
        }

        .nav-links a {
            text-decoration: none;
            color: #172b4d;
            font-weight: bold;
        }

        .nav-links a:hover {
            color: #087cff;
        }
<script>
function toggleMenu() {
    document.getElementById("navLinks").classList.toggle("show");
}
</script>

</body>
</html>
        .start-btn {
            background: #1268e8;
            color: white !important;
            padding: 13px 24px;
            border-radius: 30px;
        }

        /* ===== HERO ===== */
        .hero {
            min-height: 500px;
            display: flex;
            align-items: center;
            padding: 70px 8%;
            color: white;
            background: linear-gradient(120deg, #06235f, #005de8);
        }

        .hero-content {
            max-width: 650px;
        }

        .welcome {
            color: #19c5ff;
            font-weight: bold;
            letter-spacing: 5px;
        }

        .hero h1 {
            font-size: 70px;
            margin: 15px 0 5px;
            letter-spacing: 3px;
        }

        .hero h2 {
            font-size: 28px;
            margin: 0 0 20px;
        }

        .hero p {
            font-size: 18px;
            line-height: 1.7;
        }

        .hero-btn {
            display: inline-block;
            margin-top: 20px;
            padding: 16px 35px;
            background: #09b9ff;
            color: white;
            text-decoration: none;
            border-radius: 30px;
            font-weight: bold;
        }

        /* ===== SERVICES ===== */
        .services {
            padding: 60px 7%;
            text-align: center;
        }

        .services h2 {
            font-size: 40px;
            margin-bottom: 10px;
        }

        .services-subtitle {
            color: #52627a;
            margin-bottom: 40px;
        }

        .cards {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 25px;
        }

        .card {
            padding: 30px 20px;
            border-radius: 15px;
            border: 1px solid #dce8f7;
            background: #f8fbff;
        }

        .icon {
            font-size: 42px;
        }

        .card h3 {
            color: #102a5c;
        }

        .card p {
            color: #58677d;
            line-height: 1.5;
        }

        /* ===== CTA ===== */
        .cta {
            padding: 35px 8%;
            background: linear-gradient(90deg, #0864df, #0aaeff);
            color: white;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .cta h2 {
            margin: 0 0 5px;
        }

        .account-btn {
            background: white;
            color: #073d91;
            padding: 15px 25px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: bold;
        }

        /* ===== FOOTER ===== */
        footer {
            background: #031a43;
            color: white;
            padding: 45px 8% 20px;
            text-align: center;
        }

        footer .logo {
            justify-content: center;
            color: white;
        }

        footer .tagline {
            color: #cbd8ef;
        }

        .copyright {
            margin-top: 35px;
            border-top: 1px solid #29446f;
            padding-top: 20px;
            color: #b9c7dc;
        }

        /* ===== MOBILE ===== */
        @media (max-width: 800px) {

            nav {
                flex-direction: column;
                gap: 15px;
            }

            .nav-links {
                gap: 12px;
                flex-wrap: wrap;
                justify-content: center;
            }

            .hero {
                padding: 60px 7%;
                text-align: center;
            }

            .hero h1 {
                font-size: 48px;
            }

            .hero h2 {
                font-size: 22px;
            }

            .cards {
                grid-template-columns: 1fr;
            }

            .cta {
                flex-direction: column;
                text-align: center;
                gap: 25px;
            }
        }
    </style>
</head>

<body>

    <!-- NAVIGATION -->
    <nav>

        <a href="#home" class="logo">
            <span class="logo-mark">A</span>

            <span>
                <span class="logo-text">AVIKATE</span>
                <span class="tagline">BUILD • CONNECT • GROW</span>
            </span>
        </a>

        <div class="nav-links">
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#contact">Contact</a>
            <a href="#get-started" class="start-btn">Get Started</a>
        </div>

    </nav>


    <!-- HERO -->
    <section class="hero" id="home">

        <div class="hero-content">

            <div class="welcome">WELCOME TO</div>

            <h1>AVIKATE</h1>

            <h2>Build Your Future With Avikate</h2>

            <p>
                Avikate is a platform designed to make things easier,
                faster and better. We connect people, ideas and
                opportunities in one place.
            </p>

            <a href="#get-started" class="hero-btn">
                🚀 Get Started →
            </a>

        </div>

    </section>


    <!-- ABOUT -->
    <section class="services" id="about">

        <h2>About Avikate</h2>

        <p class="services-subtitle">
            Building a better digital future.
        </p>

        <p>
            Avikate is being built to connect people, ideas and
            opportunities through one simple platform.
        </p>

    </section>


    <!-- SERVICES -->
    <section class="services" id="services">

        <h2>Our Services</h2>

        <p class="services-subtitle">
            What you can expect from Avikate
        </p>

        <div class="cards">

            <div class="card">
                <div class="icon">🚀</div>
                <h3>Fast & Easy</h3>
                <p>Simple and quick solutions for everyone.</p>
            </div>

            <div class="card">
                <div class="icon">👥</div>
                <h3>Connect People</h3>
                <p>Bringing people and ideas together.</p>
            </div>

            <div class="card">
                <div class="icon">💡</div>
                <h3>New Opportunities</h3>
                <p>Discover and create new opportunities.</p>
            </div>

            <div class="card">
                <div class="icon">🛡️</div>
                <h3>Safe & Reliable</h3>
                <p>Your data and work are protected.</p>
            </div>

        </div>

    </section>


    <!-- GET STARTED -->
    <a href="register.html" class="get-started">
    Get Started
</a>.get-started {
    display: inline-block;
    background: #2563eb;
    color: white;
    padding: 15px 30px;
    border-radius: 8px;
    text-decoration: none;
    font-size: 18px;
    font-weight: bold;
}

.get-started:hover {
    background: #1d4ed8;
}

        <div>
            <h2>Join the Avikate Community</h2>
            <p>Be part of the future. Start your journey today.</p>
        </div>

        <a href="#contact" class="account-btn">
            Create Account →
        </a>

    </section>


    <!-- CONTACT -->
    <section class="services" id="contact">

        <h2>Contact Avikate</h2>

        <p class="services-subtitle">
            More contact features will be added here.
        </p>

    </section>


    <!-- FOOTER -->
    <footer>

        <div class="logo">

            <span class="logo-mark">A</span>

            <span>
                <span class="logo-text">AVIKATE</span>
                <span class="tagline">BUILD • CONNECT • GROW</span>
            </span>

        </div>

        <p>Build • Connect • Grow</p>

        <div class="copyright">
            © 2026 Avikate. All rights reserved.
        </div>

    </footer>

</body>
</html>
@media (max-width: 768px) {

    nav {
        flex-direction: column;
        padding: 15px;
    }

    .logo img {
        width: 150px;
        margin-bottom: 15px;
    }

    .nav-links {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 10px;
    }

    .nav-links a {
        margin: 5px;
        font-size: 14px;
    }

    .hero {
        padding: 45px 20px;
    }

    .hero h1 {
        font-size: 32px;
    }

    .hero p {
        font-size: 16px;
        line-height: 1.6;
    }

    button {
        width: 100%;
        max-width: 300px;
    }

    section {
        padding: 30px 20px;
    }
}
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<!DOCTYPE html>
<html>
<head>

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Avikate</title>

    <style>
        /* Your CSS here */
    </style>

</head>
const SUPABASE_URL = "YOUR_SUPABASE_URL";https://tyvlirculpxyesxpopsr.supabase.co
const SUPABASE_KEY = "YOUR_SUPABASE_PUBLISHABLE_KEY";sb_publishable_RxJ3Hg5OINF8mHL_7299qQ_uXZL_WnX
