# JURIL.COM
My website 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Junio Resource Investment Limited — General Trading & Investment</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Playfair+Display:wght@500;600;700&display=swap" rel="stylesheet">

<style>

:root{
  --ink:#F3EFE1;
  --ink-soft:#DCE3EC;

  /* NAVY BLUE BACKGROUND */
  --paper:#0B1F3A;
  --paper-soft:#102A4C;

  --brass:#B8863A;
  --brass-dim:#8A6527;

  --ash:#B8C2D1;
  --bone:#F3EFE1;

  --line:rgba(184,134,58,0.35);
  --line-dark:rgba(243,239,225,0.18);

  --max:1180px;
}

*{
  margin:0;
  padding:0;
  box-sizing:border-box;
}

html{
  scroll-behavior:smooth;
}

body{
  font-family:"DM Sans",sans-serif;
  background:var(--paper);
  color:var(--ink);
  line-height:1.6;
}

a{
  color:inherit;
  text-decoration:none;
}

img{
  max-width:100%;
  display:block;
}

.container{
  width:min(92%,var(--max));
  margin:auto;
}

/* HEADER */

header{
  position:sticky;
  top:0;
  z-index:1000;
  background:rgba(11,31,58,.96);
  backdrop-filter:blur(10px);
  border-bottom:1px solid var(--line);
}

.nav{
  min-height:76px;
  display:flex;
  align-items:center;
  justify-content:space-between;
  gap:30px;
}

.brand{
  font-family:"Playfair Display",serif;
  font-size:1.35rem;
  font-weight:700;
  color:var(--bone);
}

.brand span{
  color:var(--brass);
}

nav{
  display:flex;
  gap:25px;
  flex-wrap:wrap;
}

nav a{
  font-size:.9rem;
  color:var(--ink-soft);
  transition:.3s;
}

nav a:hover{
  color:var(--brass);
}

/* HERO */

.hero{
  min-height:88vh;
  display:flex;
  align-items:center;
  background:
    linear-gradient(rgba(11,31,58,.88),rgba(11,31,58,.96)),
    var(--paper);
  border-bottom:1px solid var(--line);
}

.hero-grid{
  display:grid;
  grid-template-columns:1.2fr .8fr;
  gap:60px;
  align-items:center;
}

.kicker{
  color:var(--brass);
  font-size:.8rem;
  font-weight:700;
  letter-spacing:2px;
  text-transform:uppercase;
  margin-bottom:18px;
}

.hero h1{
  font-family:"Playfair Display",serif;
  font-size:clamp(3rem,7vw,6rem);
  line-height:1;
  margin-bottom:25px;
}

.hero h1 span{
  color:var(--brass);
}

.hero p{
  color:var(--ink-soft);
  max-width:650px;
  font-size:1.05rem;
  margin-bottom:30px;
}

.btns{
  display:flex;
  gap:15px;
  flex-wrap:wrap;
}

.btn{
  display:inline-block;
  padding:13px 22px;
  border:1px solid var(--brass);
  font-weight:700;
  font-size:.9rem;
  transition:.3s;
}

.btn-primary{
  background:var(--brass);
  color:#101820;
}

.btn-primary:hover{
  background:#d19b43;
}

.btn-outline{
  color:var(--bone);
}

.btn-outline:hover{
  background:var(--brass);
  color:#101820;
}

/* HERO CARD */

.hero-card{
  border:1px solid var(--line);
  padding:35px;
  background:rgba(16,42,76,.75);
}

.hero-card h3{
  font-family:"Playfair Display",serif;
  font-size:1.7rem;
  margin-bottom:15px;
}

.hero-card p{
  font-size:.95rem;
  margin-bottom:20px;
}

.hero-card ul{
  list-style:none;
}

.hero-card li{
  padding:10px 0;
  border-bottom:1px solid var(--line-dark);
  color:var(--ink-soft);
}

.hero-card li::before{
  content:"◆";
  color:var(--brass);
  margin-right:10px;
  font-size:.65rem;
}

/* SECTIONS */

section{
  padding:100px 0;
  border-bottom:1px solid var(--line);
}

.section-head{
  margin-bottom:50px;
}

.section-head h2{
  font-family:"Playfair Display",serif;
  font-size:clamp(2rem,4vw,3.4rem);
  margin-bottom:15px;
}

.section-head p{
  max-width:700px;
  color:var(--ink-soft);
}

/* CARDS */

.cards{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:25px;
}

.card{
  padding:30px;
  background:var(--paper-soft);
  border:1px solid var(--line);
  transition:.3s;
}

.card:hover{
  transform:translateY(-5px);
  border-color:var(--brass);
}

.card-number{
  color:var(--brass);
  font-size:.8rem;
  font-weight:700;
  letter-spacing:2px;
  margin-bottom:15px;
}

.card h3{
  font-family:"Playfair Display",serif;
  font-size:1.5rem;
  margin-bottom:12px;
}

.card p{
  color:var(--ink-soft);
  font-size:.95rem;
}

/* ABOUT */

.about-grid{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:60px;
  align-items:start;
}

.about-box{
  border-left:3px solid var(--brass);
  padding-left:25px;
}

.about-box p{
  color:var(--ink-soft);
  margin-bottom:20px;
}

.about-list{
  list-style:none;
}

.about-list li{
  padding:12px 0;
  border-bottom:1px solid var(--line-dark);
}

/* STATS */

.stats{
  display:grid;
  grid-template-columns:repeat(4,1fr);
  gap:20px;
  margin-top:50px;
}

.stat{
  padding:25px;
  border:1px solid var(--line);
  background:var(--paper-soft);
}

.stat strong{
  display:block;
  font-family:"Playfair Display",serif;
  color:var(--brass);
  font-size:2.3rem;
}

.stat span{
  color:var(--ink-soft);
  font-size:.9rem;
}

/* TIMELINE */

.timeline{
  display:grid;
  gap:20px;
}

.timeline-item{
  display:grid;
  grid-template-columns:150px 1fr;
  gap:30px;
  padding:25px 0;
  border-bottom:1px solid var(--line-dark);
}

.timeline-year{
  color:var(--brass);
  font-weight:700;
}

.timeline-item h3{
  font-family:"Playfair Display",serif;
  margin-bottom:8px;
}

.timeline-item p{
  color:var(--ink-soft);
}

/* VALUES */

.values{
  display:grid;
  grid-template-columns:repeat(4,1fr);
  gap:20px;
}

.value{
  padding:25px;
  border-top:2px solid var(--brass);
  background:var(--paper-soft);
}

.value h3{
  font-family:"Playfair Display",serif;
  margin-bottom:10px;
}

.value p{
  color:var(--ink-soft);
  font-size:.9rem;
}

/* SERVICES */

.services{
  display:grid;
  grid-template-columns:repeat(2,1fr);
  gap:25px;
}

.service{
  padding:30px;
  border:1px solid var(--line);
  background:var(--paper-soft);
}

.service h3{
  font-family:"Playfair Display",serif;
  font-size:1.6rem;
  margin-bottom:10px;
}

.service p{
  color:var(--ink-soft);
}

/* PORTFOLIO */

.portfolio{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:25px;
}

.portfolio-item{
  min-height:250px;
  padding:30px;
  background:linear-gradient(
    135deg,
    #102A4C,
    #0B1F3A
  );
  border:1px solid var(--line);
  display:flex;
  flex-direction:column;
  justify-content:flex-end;
}

.portfolio-item span{
  color:var(--brass);
  font-size:.75rem;
  text-transform:uppercase;
  letter-spacing:2px;
  margin-bottom:8px;
}

.portfolio-item h3{
  font-family:"Playfair Display",serif;
  font-size:1.6rem;
}

/* LOCATION */

.location-box{
  padding:40px;
  border:1px solid var(--line);
  background:var(--paper-soft);
}

.location-box h3{
  font-family:"Playfair Display",serif;
  font-size:2rem;
  margin-bottom:15px;
}

.location-box p{
  color:var(--ink-soft);
}

/* CONTACT */

.contact-grid{
  display:grid;
  grid-template-columns:.8fr 1.2fr;
  gap:50px;
}

.contact-info h3{
  font-family:"Playfair Display",serif;
  font-size:2rem;
  margin-bottom:20px;
}

.contact-info p{
  color:var(--ink-soft);
  margin-bottom:15px;
}

.contact-details{
  margin-top:30px;
}

.contact-details div{
  padding:12px 0;
  border-bottom:1px solid var(--line-dark);
}

.contact-details strong{
  display:block;
  color:var(--brass);
  font-size:.8rem;
  text-transform:uppercase;
  letter-spacing:1px;
}

/* FORM */

form{
  background:var(--paper-soft);
  border:1px solid var(--line);
  padding:35px;
}

.form-row{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:20px;
}

.field{
  margin-bottom:20px;
}

.field label{
  display:block;
  margin-bottom:8px;
  font-size:.85rem;
  color:var(--ink-soft);
}

.field input,
.field textarea,
.field select{
  width:100%;
  padding:13px;
  border:1px solid var(--line-dark);
  background:#0B1F3A;
  color:var(--bone);
  font-family:inherit;
  outline:none;
}

.field input:focus,
.field textarea:focus,
.field select:focus{
  border-color:var(--brass);
}

.field textarea{
  min-height:140px;
  resize:vertical;
}

/* FOOTER */

footer{
  padding:45px 0;
  background:#07172B;
  border-top:1px solid var(--line);
}

.footer-grid{
  display:flex;
  justify-content:space-between;
  gap:30px;
  flex-wrap:wrap;
}

.footer-brand{
  font-family:"Playfair Display",serif;
  font-size:1.4rem;
}

.footer-brand span{
  color:var(--brass);
}

.footer-text{
  color:var(--ash);
  font-size:.85rem;
}

/* MOBILE */

@media(max-width:900px){

  .hero-grid,
  .about-grid,
  .contact-grid{
    grid-template-columns:1fr;
  }

  .cards,
  .portfolio{
    grid-template-columns:1fr 1fr;
  }

  .values,
  .stats{
    grid-template-columns:1fr 1fr;
  }

}

@media(max-width:650px){

  nav{
    display:none;
  }

  .hero{
    min-height:auto;
    padding:100px 0;
  }

  section{
    padding:70px 0;
  }

  .cards,
  .portfolio,
  .services,
  .values,
  .stats{
    grid-template-columns:1fr;
  }

  .form-row{
    grid-template-columns:1fr;
  }

  .timeline-item{
    grid-template-columns:1fr;
    gap:5px;
  }

}

</style>
</head>

<body>

<!-- HEADER -->

<header>
  <div class="container nav">

    <a href="#home" class="brand">
      Junio <span>Resource</span>
    </a>

    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#contact">Contact</a>
    </nav>

  </div>
</header>


<!-- HOME -->

<section class="hero" id="home">

  <div class="container hero-grid">

    <div>

      <div class="kicker">
        General Trading & Investment
      </div>

      <h1>
        Building Value.<br>
        <span>Creating Opportunity.</span>
      </h1>

      <p>
        Junio Resource Investment Limited is a Nigerian company
        focused on general trading, investment and strategic business
        opportunities across local and international markets.
      </p>

      <div class="btns">

        <a href="#services" class="btn btn-primary">
          Explore Services
        </a>

        <a href="#contact" class="btn btn-outline">
          Contact Us
        </a>

      </div>

    </div>


    <div class="hero-card">

      <h3>
        Our Focus
      </h3>

      <p>
        We connect opportunities with practical business solutions.
      </p>

      <ul>

        <li>
          General Trading
        </li>

        <li>
          Commodity Trading
        </li>

        <li>
          Investment Opportunities
        </li>

        <li>
          Business Development
        </li>

        <li>
          Export & Import
        </li>

      </ul>

    </div>

  </div>

</section>


<!-- WHAT WE DO -->

<section id="services">

  <div class="container">

    <div class="section-head">

      <div class="kicker">
        What We Do
      </div>

      <h2>
        Practical business solutions.
      </h2>

      <p>
        Our activities are designed around identifying opportunities,
        building partnerships and delivering value through trade and investment.
      </p>

    </div>


    <div class="cards">

      <div class="card">

        <div class="card-number">
          01
        </div>

        <h3>
          General Trading
        </h3>

        <p>
          Trading of selected goods, commodities and products
          across Nigerian and international markets.
        </p>

      </div>


      <div class="card">

        <div class="card-number">
          02
        </div>

        <h3>
          Commodity Trading
        </h3>

        <p>
          Sourcing and supply of agricultural and natural-resource
          commodities for qualified buyers and partners.
        </p>

      </div>


      <div class="card">

        <div class="card-number">
          03
        </div>

        <h3>
          Investment
        </h3>

        <p>
          Exploring commercially viable opportunities that support
          sustainable business growth and value creation.
        </p>

      </div>

    </div>

  </div>

</section>


<!-- WHY JUNIO -->

<section>

  <div class="container">

    <div class="section-head">

      <div class="kicker">
        Why Work With Junio
      </div>

      <h2>
        Built around opportunity and trust.
      </h2>

    </div>


    <div class="cards">

      <div class="card">

        <div class="card-number">
          01
        </div>

        <h3>
          Market Focus
        </h3>

        <p>
          We focus on practical opportunities with clear commercial potential.
        </p>

      </div>


      <div class="card">

        <div class="card-number">
          02
        </div>

        <h3>
          Partnerships
        </h3>

        <p>
          We work with suppliers, buyers and strategic partners
          to develop mutually beneficial relationships.
        </p>

      </div>


      <div class="card">

        <div class="card-number">
          03
        </div>

        <h3>
          Reliability
        </h3>

        <p>
          Professional communication, responsible sourcing and
          transparent business practices are central to our approach.
        </p>

      </div>

    </div>

  </div>

</section>


<!-- ABOUT -->

<section id="about">

  <div class="container">

    <div class="section-head">

      <div class="kicker">
        About Junio
      </div>

      <h2>
        A Nigerian business built for growth.
      </h2>

    </div>


    <div class="about-grid">

      <div class="about-box">

        <p>
          Junio Resource Investment Limited is a Nigerian business
          established to participate in general trading, commodity
          supply and investment opportunities.
        </p>

        <p>
          Our goal is to build reliable relationships with customers,
          suppliers and business partners while creating sustainable
          commercial value.
        </p>

      </div>


      <div>

        <ul class="about-list">

          <li>
            Strategic sourcing
          </li>

          <li>
            Responsible business practices
          </li>

          <li>
            Customer-focused service
          </li>

          <li>
            Local and international opportunities
          </li>

          <li>
            Long-term partnerships
          </li>

        </ul>

      </div>

    </div>


    <div class="stats">

      <div class="stat">

        <strong>
          [X]
        </strong>

        <span>
          Business Partners
        </span>

      </div>


      <div class="stat">

        <strong>
          [X]
        </strong>

        <span>
          Products / Commodities
        </span>

      </div>


      <div class="stat">

        <strong>
          [X]
        </strong>

        <span>
          Markets
        </span>

      </div>


      <div class="stat">

        <strong>
          [Year]
        </strong>

        <span>
          Established
        </span>

      </div>

    </div>

  </div>

</section>


<!-- HOW WE GOT HERE -->

<section>

  <div class="container">

    <div class="section-head">

      <div class="kicker">
        How We Got Here
      </div>

      <h2>
        Our journey.
      </h2>

    </div>


    <div class="timeline">

      <div class="timeline-item">

        <div class="timeline-year">
          [Year]
        </div>

        <div>

          <h3>
            Company Established
          </h3>

          <p>
            Junio Resource Investment Limited was established
            to pursue opportunities in trading and investment.
          </p>

        </div>

      </div>


      <div class="timeline-item">

        <div class="timeline-year">
          [Year]
        </div>

        <div>

          <h3>
            Market Development
          </h3>

          <p>
            Expanded relationships with suppliers, customers
            and potential business partners.
          </p>

        </div>

      </div>


      <div class="timeline-item">

        <div class="timeline-year">
          [Year]
        </div>

        <div>

          <h3>
            Growth
          </h3>

          <p>
            Continued development of trading and investment
            opportunities across selected markets.
          </p>

        </div>

      </div>

    </div>

  </div>

</section>


<!-- VALUES -->

<section>

  <div class="container">

    <div class="section-head">

      <div class="kicker">
        What We Value
      </div>

      <h2>
        Principles that guide our business.
      </h2>

    </div>


    <div class="values">

      <div class="value">

        <h3>
          Integrity
        </h3>

        <p>
          We aim to conduct business with honesty and transparency.
        </p>

      </div>


      <div class="value">

        <h3>
          Quality
        </h3>

        <p>
          We focus on reliable products, services and business relationships.
        </p>

      </div>


      <div class="value">

        <h3>
          Partnership
        </h3>

        <p>
          We believe sustainable growth comes through strong partnerships.
        </p>

      </div>


      <div class="value">

        <h3>
          Growth
        </h3>

        <p>
          We continuously seek opportunities to improve and expand.
        </p>

      </div>

    </div>

  </div>

</section>


<!-- SERVICES -->

<section>

  <div class="container">

    <div class="section-head">

      <div class="kicker">
        Our Services
      </div>

      <h2>
        Areas of business.
      </h2>

    </div>


    <div class="services">

      <div class="service">

        <h3>
          Commodity Sourcing
        </h3>

        <p>
          Sourcing and supply of selected commodities for domestic
          and international customers.
        </p>

      </div>


      <div class="service">

        <h3>
          Export & Import
        </h3>

        <p>
          Supporting cross-border trade opportunities while working
          with appropriate suppliers and buyers.
        </p>

      </div>


      <div class="service">

        <h3>
          General Merchandise
        </h3>

        <p>
          Trading in selected products based on market demand
          and commercial opportunities.
        </p>

      </div>


      <div class="service">

        <h3>
          Investment Opportunities
        </h3>

        <p>
          Identifying and evaluating opportunities for sustainable
          business growth and investment.
        </p>

      </div>

    </div>

  </div>

</section>


<!-- PORTFOLIO -->

<section id="portfolio">

  <div class="container">

    <div class="section-head">

      <div class="kicker">
        Portfolio
      </div>

      <h2>
        Selected business areas.
      </h2>

    </div>


    <div class="portfolio">

      <div class="portfolio-item">

        <span>
          Trading
        </span>

        <h3>
          General Merchandise
        </h3>

      </div>


      <div class="portfolio-item">

        <span>
          Commodities
        </span>

        <h3>
          Agricultural Products
        </h3>

      </div>


      <div class="portfolio-item">

        <span>
          Export
        </span>

        <h3>
          International Trade
        </h3>

      </div>

    </div>

  </div>

</section>


<!-- WHERE WE OPERATE -->

<section>

  <div class="container">

    <div class="section-head">

      <div class="kicker">
        Where We Operate
      </div>

      <h2>
        Nigeria and beyond.
      </h2>

    </div>


    <div class="location-box">

      <h3>
        Abuja, Nigeria
      </h3>

      <p>
        Our business activities are focused on opportunities
        within Nigeria while building relationships that can
        support international trade.
      </p>

    </div>

  </div>

</section>


<!-- CONTACT -->

<section id="contact">

  <div class="container">

    <div class="section-head">

      <div class="kicker">
        Contact
      </div>

      <h2>
        Let's do business.
      </h2>

      <p>
        Contact Junio Resource Investment Limited to discuss
        trading, sourcing, investment or partnership opportunities.
      </p>

    </div>


    <div class="contact-grid">

      <div class="contact-info">

        <h3>
          Get in touch
        </h3>

        <p>
          We welcome enquiries from buyers, suppliers,
          investors and strategic partners.
        </p>


        <div class="contact-details">

          <div>

            <strong>
              Phone
            </strong>

            [Phone Number]

          </div>


          <div>

            <strong>
              Email
            </strong>

            [Email Address]

          </div>


          <div>

            <strong>
              Address
            </strong>

            [Street Address, Abuja, Nigeria]

          </div>


          <div>

            <strong>
              CAC Registration
            </strong>

            [CAC Registration Number]

          </div>

        </div>

      </div>


      <form onsubmit="sendMessage(event)">

        <div class="form-row">

          <div class="field">

            <label>
              Name
            </label>

            <input
              type="text"
              required
              placeholder="Your name"
            >

          </div>


          <div class="field">

            <label>
              Email
            </label>

            <input
              type="email"
              required
              placeholder="Your email"
            >

          </div>

        </div>


        <div class="field">

          <label>
            Subject
          </label>

          <input
            type="text"
            required
            placeholder="How can we help?"
          >

        </div>


        <div class="field">

          <label>
            Message
          </label>

          <textarea
            required
            placeholder="Write your message..."
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


<!-- FOOTER -->

<footer>

  <div class="container footer-grid">

    <div class="footer-brand">

      Junio <span>Resource Investment Limited</span>

    </div>

    <div class="footer-text">

      © 2026 Junio Resource Investment Limited.
      All rights reserved.

    </div>

  </div>

</footer>


<script>

function sendMessage(event){

  event.preventDefault();

  alert(
    "Thank you for contacting Junio Resource Investment Limited. " +
    "Please connect this form to your email or form service before publishing."
  );

}

</script>

</body>
</html>
