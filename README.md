JURIL
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>JUNIO RESOURCE INVESTMENT LIMITED</title>

<meta name="description" content="JUNIO RESOURCE INVESTMENT LIMITED - Entrepreneurship, General Trading and Investment. Main Office Abuja, Branch Office Jos, Plateau State.">

<style>
/* =========================
   JUNIO RESOURCE INVESTMENT LIMITED
   SINGLE FILE WEBSITE
   ========================= */

:root {
    --navy: #071d38;
    --navy2: #102f52;
    --navy3: #163b63;
    --gold: #c69235;
    --gold-light: #d9ad5c;
    --cream: #f5f0df;
    --white: #ffffff;
    --muted: #c5cfdb;
    --line: rgba(198,146,53,0.35);
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    background: var(--navy);
    color: var(--cream);
    line-height: 1.6;
}

a {
    color: inherit;
    text-decoration: none;
}

.container {
    width: 92%;
    max-width: 1180px;
    margin: auto;
}

/* =========================
   HEADER
   ========================= */

header {
    position: sticky;
    top: 0;
    z-index: 1000;
    background: rgba(7,29,56,0.97);
    border-bottom: 1px solid var(--line);
    backdrop-filter: blur(10px);
}

.header-inner {
    min-height: 82px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 25px;
}

.logo {
    font-family: Georgia, "Times New Roman", serif;
    font-size: 22px;
    font-weight: bold;
    color: var(--cream);
}

.logo span {
    color: var(--gold);
}

nav {
    display: flex;
    gap: 24px;
}

nav a {
    font-size: 14px;
    color: var(--muted);
    transition: 0.3s;
}

nav a:hover {
    color: var(--gold-light);
}

/* =========================
   HERO
   ========================= */

.hero {
    min-height: 90vh;
    display: flex;
    align-items: center;
    border-bottom: 1px solid var(--line);
    background:
        linear-gradient(
            rgba(7,29,56,0.92),
            rgba(7,29,56,0.98)
        );
}

.hero-grid {
    display: grid;
    grid-template-columns: 1.2fr 0.8fr;
    gap: 60px;
    align-items: center;
    padding: 80px 0;
}

.eyebrow {
    color: var(--gold-light);
    font-weight: bold;
    font-size: 14px;
    letter-spacing: 3px;
    margin-bottom: 25px;
}

.hero h1 {
    font-family: Georgia, "Times New Roman", serif;
    font-size: clamp(48px, 7vw, 90px);
    line-height: 0.98;
    margin-bottom: 30px;
}

.hero h1 span {
    color: var(--gold);
}

.hero-description {
    max-width: 650px;
    color: var(--muted);
    font-size: 18px;
    margin-bottom: 35px;
}

.buttons {
    display: flex;
    gap: 15px;
    flex-wrap: wrap;
}

.btn {
    display: inline-block;
    padding: 14px 25px;
    border: 1px solid var(--gold);
    font-weight: bold;
    transition: 0.3s;
}

.btn-primary {
    background: var(--gold);
    color: #071d38;
}

.btn-primary:hover {
    background: var(--gold-light);
}

.btn-outline:hover {
    background: var(--gold);
    color: #071d38;
}

/* HERO CARD */

.hero-card {
    background: var(--navy2);
    border: 1px solid var(--line);
    padding: 35px;
}

.hero-card h2 {
    font-family: Georgia, "Times New Roman", serif;
    font-size: 30px;
    margin-bottom: 15px;
}

.hero-card p {
    color: var(--muted);
    margin-bottom: 20px;
}

.hero-card ul {
    list-style: none;
}

.hero-card li {
    padding: 12px 0;
    border-bottom: 1px solid rgba(255,255,255,0.12);
    color: var(--cream);
}

.hero-card li::before {
    content: "◆";
    color: var(--gold);
    margin-right: 10px;
    font-size: 9px;
}

/* =========================
   GENERAL SECTIONS
   ========================= */

section {
    padding: 95px 0;
    border-bottom: 1px solid var(--line);
}

.section-title {
    margin-bottom: 45px;
}

.section-label {
    color: var(--gold-light);
    font-weight: bold;
    font-size: 13px;
    letter-spacing: 3px;
    margin-bottom: 12px;
}

.section-title h2 {
    font-family: Georgia, "Times New Roman", serif;
    font-size: clamp(34px, 5vw, 58px);
    margin-bottom: 15px;
}

.section-title p {
    max-width: 700px;
    color: var(--muted);
}

/* =========================
   ABOUT
   ========================= */

.about-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 55px;
}

.about-box {
    border-left: 3px solid var(--gold);
    padding-left: 25px;
}

.about-box p {
    color: var(--muted);
    margin-bottom: 20px;
}

.info-list {
    list-style: none;
}

.info-list li {
    padding: 15px 0;
    border-bottom: 1px solid rgba(255,255,255,0.12);
}

/* =========================
   SERVICES
   ========================= */

.cards {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
}

.card {
    background: var(--navy2);
    border: 1px solid var(--line);
    padding: 30px;
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-5px);
    border-color: var(--gold);
}

.card-number {
    color: var(--gold);
    font-weight: bold;
    letter-spacing: 2px;
    margin-bottom: 18px;
}

.card h3 {
    font-family: Georgia, "Times New Roman", serif;
    font-size: 25px;
    margin-bottom: 12px;
}

.card p {
    color: var(--muted);
}

/* =========================
   BUSINESS AREAS
   ========================= */

.business-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 25px;
}

.business-box {
    background: var(--navy2);
    border: 1px solid var(--line);
    padding: 30px;
}

.business-box h3 {
    font-family: Georgia, "Times New Roman", serif;
    font-size: 27px;
    margin-bottom: 10px;
}

.business-box p {
    color: var(--muted);
}

/* =========================
   OFFICES
   ========================= */

.office-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 25px;
}

.office {
    background: var(--navy2);
    border: 1px solid var(--line);
    padding: 35px;
}

.office-label {
    color: var(--gold-light);
    font-weight: bold;
    letter-spacing: 2px;
    font-size: 13px;
    margin-bottom: 10px;
}

.office h3 {
    font-family: Georgia, "Times New Roman", serif;
    font-size: 32px;
}

.office p {
    color: var(--muted);
    margin-top: 10px;
}

/* =========================
   CONTACT
   ========================= */

.contact-grid {
    display: grid;
    grid-template-columns: 0.9fr 1.1fr;
    gap: 55px;
}

.contact-details {
    margin-top: 25px;
}

.contact-item {
    padding: 17px 0;
    border-bottom: 1px solid rgba(255,255,255,0.12);
}

.contact-item strong {
    display: block;
    color: var(--gold-light);
    font-size: 13px;
    letter-spacing: 2px;
    margin-bottom: 5px;
}

.contact-item a {
    color: var(--cream);
    word-break: break-word;
}

.contact-item a:hover {
    color: var(--gold-light);
}

/* FORM */

.contact-form {
    background: var(--navy2);
    border: 1px solid var(--line);
    padding: 35px;
}

.form-group {
    margin-bottom: 20px;
}

.form-group label {
    display: block;
    color: var(--muted);
    font-size: 14px;
    margin-bottom: 8px;
}

.form-group input,
.form-group textarea {
    width: 100%;
    padding: 14px;
    border: 1px solid rgba(255,255,255,0.18);
    background: var(--navy);
    color: var(--cream);
    font-family: Arial, sans-serif;
    font-size: 15px;
    outline: none;
}

.form-group input:focus,
.form-group textarea:focus {
    border-color: var(--gold);
}

.form-group textarea {
    min-height: 150px;
    resize: vertical;
}

/* =========================
   SOCIAL MEDIA
   ========================= */

.social {
    display: flex;
    flex-wrap: wrap;
    gap: 12px;
    margin-top: 30px;
}

.social a {
    border: 1px solid var(--line);
    padding: 10px 15px;
    color: var(--muted);
    font-size: 14px;
    transition: 0.3s;
}

.social a:hover {
    background: var(--gold);
    color: var(--navy);
}

/* =========================
   FOOTER
   ========================= */

footer {
    background: #041326;
    padding: 50px 0 25px;
}

.footer-grid {
    display: grid;
    grid-template-columns: 1.5fr 1fr 1fr;
    gap: 40px;
}

.footer-column h3 {
    font-family: Georgia, "Times New Roman", serif;
    margin-bottom: 15px;
}

.footer-column p,
.footer-column li {
    color: var(--muted);
    font-size: 14px;
}

.footer-column ul {
    list-style: none;
}

.footer-column li {
    margin-bottom: 8px;
}

.footer-column a:hover {
    color: var(--gold-light);
}

.footer-bottom {
    margin-top: 40px;
    padding-top: 20px;
    border-top: 1px solid rgba(255,255,255,0.12);
    display: flex;
    justify-content: space-between;
    gap: 20px;
    color: #9eabb9;
    font-size: 13px;
}

/* =========================
   MOBILE
   ========================= */

@media (max-width: 850px) {

    .header-inner {
        flex-direction: column;
        justify-content: center;
        padding: 18px 0;
    }

    nav {
        gap: 15px;
        justify-content: center;
        flex-wrap: wrap;
    }

    .hero-grid,
    .about-grid,
    .contact-grid,
    .office-grid {
        grid-template-columns: 1fr;
    }

    .cards {
        grid-template-columns: 1fr;
    }

    .business-grid {
        grid-template-columns: 1fr;
    }

    .footer-grid {
        grid-template-columns: 1fr;
    }

    .footer-bottom {
        flex-direction: column;
    }

    .hero {
        min-height: auto;
    }

    .hero h1 {
        font-size: 52px;
    }

}

@media (max-width: 480px) {

    .container {
        width: 88%;
    }

    nav a {
        font-size: 12px;
    }

    .hero h1 {
        font-size: 45px;
    }

    section {
        padding: 70px 0;
    }

    .contact-form {
        padding: 22px;
    }

}
</style>
</head>

<body>

<!-- =========================
     HEADER
     ========================= -->

<header>

<div class="container header-inner">

    <a href="#home" class="logo">
        JUNIO <span>RESOURCE</span>
    </a>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#offices">Offices</a>
        <a href="#contact">Contact</a>
    </nav>

</div>

</header>


<!-- =========================
     HOME
     ========================= -->

<section class="hero" id="home">

<div class="container hero-grid">

    <div>

        <div class="eyebrow">
            ENTREPRENEURSHIP • TRADING • INVESTMENT
        </div>

        <h1>
            Building Value.<br>
            <span>Creating Opportunity.</span>
        </h1>

        <p class="hero-description">
            JUNIO RESOURCE INVESTMENT LIMITED is an entrepreneurship,
            trading and investment company focused on creating
            business opportunities, building partnerships and
            delivering value.
        </p>

        <div class="buttons">

            <a href="#services" class="btn btn-primary">
                Our Services
            </a>

            <a href="#contact" class="btn">
                Contact Us
            </a>

        </div>

    </div>


    <div class="hero-card">

        <h2>Our Focus</h2>

        <p>
            Connecting opportunities with practical business solutions.
        </p>

        <ul>

            <li>Entrepreneurship</li>

            <li>General Trading</li>

            <li>Commodity Trading</li>

            <li>Import & Export</li>

            <li>Investment Opportunities</li>

        </ul>

    </div>

</div>

</section>


<!-- =========================
     ABOUT
     ========================= -->

<section id="about">

<div class="container">

    <div class="section-title">

        <div class="section-label">
            ABOUT JUNIO
        </div>

        <h2>
            A Nigerian company built for opportunity.
        </h2>

        <p>
            JUNIO RESOURCE INVESTMENT LIMITED operates with a focus
            on entrepreneurship, trading, investment and strategic
            business opportunities.
        </p>

    </div>


    <div class="about-grid">

        <div class="about-box">

            <p>
                Our objective is to develop reliable business
                relationships with customers, suppliers, investors
                and strategic partners.
            </p>

            <p>
                We seek commercially viable opportunities while
                maintaining professionalism, transparency and
                responsible business practices.
            </p>

        </div>


        <div>

            <ul class="info-list">

                <li>Entrepreneurship & Business Development</li>

                <li>General Trading</li>

                <li>Commodity Sourcing</li>

                <li>Import & Export</li>

                <li>Investment Opportunities</li>

            </ul>

        </div>

    </div>

</div>

</section>


<!-- =========================
     SERVICES
     ========================= -->

<section id="services">

<div class="container">

    <div class="section-title">

        <div class="section-label">
            WHAT WE DO
        </div>

        <h2>
            Our Business Services
        </h2>

        <p>
            We focus on business activities that connect markets,
            products, people and investment opportunities.
        </p>

    </div>


    <div class="cards">

        <div class="card">

            <div class="card-number">01</div>

            <h3>
                Entrepreneurship
            </h3>

            <p>
                Developing business ideas and opportunities with
                a focus on sustainable commercial growth.
            </p>

        </div>


        <div class="card">

            <div class="card-number">02</div>

            <h3>
                General Trading
            </h3>

            <p>
                Trading and sourcing of selected products and
                commodities for customers and business partners.
            </p>

        </div>


        <div class="card">

            <div class="card-number">03</div>

            <h3>
                Commodity Trading
            </h3>

            <p>
                Connecting suppliers and buyers for agricultural
                and other commercially viable commodities.
            </p>

        </div>


        <div class="card">

            <div class="card-number">04</div>

            <h3>
                Import & Export
            </h3>

            <p>
                Exploring domestic and international trade
                opportunities through responsible sourcing.
            </p>

        </div>


        <div class="card">

            <div class="card-number">05</div>

            <h3>
                Investment
            </h3>

            <p>
                Identifying business and investment opportunities
                with potential for long-term value creation.
            </p>

        </div>


        <div class="card">

            <div class="card-number">06</div>

            <h3>
                Business Partnerships
            </h3>

            <p>
                Building relationships with suppliers, buyers,
                investors and strategic partners.
            </p>

        </div>

    </div>

</div>

</section>


<!-- =========================
     BUSINESS AREAS
     ========================= -->

<section>

<div class="container">

    <div class="section-title">

        <div class="section-label">
            BUSINESS AREAS
        </div>

        <h2>
            Connecting opportunity with action.
        </h2>

    </div>


    <div class="business-grid">

        <div class="business-box">

            <h3>
                Agricultural Commodities
            </h3>

            <p>
                Sourcing and trading selected agricultural products
                for suitable domestic and international markets.
            </p>

        </div>


        <div class="business-box">

            <h3>
                Natural Resources
            </h3>

            <p>
                Exploring responsible trading opportunities within
                natural-resource and commodity markets.
            </p>

        </div>


        <div class="business-box">

            <h3>
                General Merchandise
            </h3>

            <p>
                Trading selected goods based on market demand and
                available commercial opportunities.
            </p>

        </div>


        <div class="business-box">

            <h3>
                Strategic Investment
            </h3>

            <p>
                Seeking practical opportunities for business growth,
                partnerships and investment.
            </p>

        </div>

    </div>

</div>

</section>


<!-- =========================
     OFFICES
     ========================= -->

<section id="offices">

<div class="container">

    <div class="section-title">

        <div class="section-label">
            OUR LOCATIONS
        </div>

        <h2>
            Serving opportunities from Nigeria.
        </h2>

    </div>


    <div class="office-grid">

        <div class="office">

            <div class="office-label">
                MAIN OFFICE
            </div>

            <h3>
                Abuja
            </h3>

            <p>
                Federal Capital Territory, Nigeria
            </p>

        </div>


        <div class="office">

            <div class="office-label">
                BRANCH OFFICE
            </div>

            <h3>
                Jos, Plateau State
            </h3>

            <p>
                Plateau State, Nigeria
            </p>

        </div>

    </div>

</div>

</section>


<!-- =========================
     CONTACT
     ========================= -->

<section id="contact">

<div class="container">

    <div class="section-title">

        <div class="section-label">
            GET IN TOUCH
        </div>

        <h2>
            Let's talk about business.
        </h2>

        <p>
            Contact JUNIO RESOURCE INVESTMENT LIMITED for
            enquiries, partnerships, trading opportunities
            and business engagements.
        </p>

    </div>


    <div class="contact-grid">


        <!-- CONTACT INFORMATION -->

        <div>

            <div class="contact-details">


                <div class="contact-item">

                    <strong>PHONE</strong>

                    <a href="tel:+2349130177744">
                        +234 913 017 7744
                    </a>

                </div>


                <div class="contact-item">

                    <strong>EMAIL</strong>

                    <a href="mailto:junioresourceinvestmentlimited@gmail.com">
                        junioresourceinvestmentlimited@gmail.com
                    </a>

                </div>


                <div class="contact-item">

                    <strong>MAIN OFFICE</strong>

                    Abuja, Nigeria

                </div>


                <div class="contact-item">

                    <strong>BRANCH OFFICE</strong>

                    Jos, Plateau State, Nigeria

                </div>


                <div class="contact-item">

                    <strong>WEBSITE</strong>

                    <a
                        href="https://junioresourceinvestmentlimited-hub.github.io/JURIL.COM"
                        target="_blank"
                    >
                        JURIL.COM
                    </a>

                </div>

            </div>


            <!-- SOCIAL MEDIA -->

            <div class="social">

                <a
                    href="https://www.facebook.com/junioresourceinvestment"
                    target="_blank"
                >
                    Facebook
                </a>

                <a
                    href="https://www.instagram.com/JURIL"
                    target="_blank"
                >
                    Instagram
                </a>

                <a
                    href="https://twitter.com/JURIL001"
                    target="_blank"
                >
                    Twitter
                </a>

            </div>

        </div>


        <!-- CONTACT FORM -->

        <form
            class="contact-form"
            action="mailto:junioresourceinvestmentlimited@gmail.com"
            method="post"
            enctype="text/plain"
        >

            <div class="form-group">

                <label for="name">
                    Full Name
                </label>

                <input
                    type="text"
                    id="name"
                    name="Name"
                    placeholder="Enter your full name"
                    required
                >

            </div>


            <div class="form-group">

                <label for="email">
                    Email Address
                </label>

                <input
                    type="email"
                    id="email"
                    name="Email"
                    placeholder="Enter your email"
                    required
                >

            </div>


            <div class="form-group">

                <label for="subject">
                    Subject
                </label>

                <input
                    type="text"
                    id="subject"
                    name="Subject"
                    placeholder="Business enquiry"
                    required
                >

            </div>


            <div class="form-group">

                <label for="message">
                    Message
                </label>

                <textarea
                    id="message"
                    name="Message"
                    placeholder="Write your message here..."
                    required
                ></textarea>

            </div>


            <button
                type="submit"
                class="btn btn-primary"
            >
                Send Message
            </button>

        </form>

    </div>

</div>

</section>


<!-- =========================
     FOOTER
     ========================= -->

<footer>

<div class="container">

    <div class="footer-grid">


        <div class="footer-column">

            <h3>
                JUNIO RESOURCE INVESTMENT LIMITED
            </h3>

            <p>
                ENTREPRENEURSHIP • TRADING • INVESTMENT
            </p>

            <p style="margin-top:12px;">
                Building value and creating opportunities
                through responsible business.
            </p>

        </div>


        <div class="footer-column">

            <h3>
                Offices
            </h3>

            <ul>

                <li>
                    Main Office: Abuja
                </li>

                <li>
                    Branch Office: Jos, Plateau State
                </li>

            </ul>

        </div>


        <div class="footer-column">

            <h3>
                Contact
            </h3>

            <ul>

                <li>
                    <a href="tel:+2349130177744">
                        +234 913 017 7744
                    </a>
                </li>

                <li>
                    <a href="mailto:junioresourceinvestmentlimited@gmail.com">
                        Email Us
                    </a>
                </li>

                <li>
                    <a
                        href="https://www.facebook.com/junioresourceinvestment"
                        target="_blank"
                    >
                        Facebook
                    </a>
                </li>

                <li>
                    <a
                        href="https://www.instagram.com/JURIL"
                        target="_blank"
                    >
                        Instagram: @JURIL
                    </a>
                </li>

                <li>
                    <a
                        href="https://twitter.com/JURIL001"
                        target="_blank"
                    >
                        Twitter: @JURIL001
                    </a>
                </li>

            </ul>

        </div>

    </div>


    <div class="footer-bottom">

        <span>
            © <span id="year"></span>
            JUNIO RESOURCE INVESTMENT LIMITED.
            All Rights Reserved.
        </span>

        <span>
            JURIL
        </span>

    </div>

</div>

</footer>


<!-- =========================
     JAVASCRIPT
     ========================= -->

<script>

document.getElementById("year").textContent =
    new Date().getFullYear();

</script>

</body>
</html>
