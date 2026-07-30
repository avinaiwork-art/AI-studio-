# AI-studio-
/* ===========================================
   AVIN PORTFOLIO
   PART 1
=========================================== */

/* Google Font */

@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap');

/* VARIABLES */

:root{

    --bg:#050505;

    --card:#101010;

    --card2:#171717;

    --text:#ffffff;

    --secondary:#9f9f9f;

    --accent:#6EE7FF;

    --border:rgba(255,255,255,.08);

    --radius:20px;

}

/* RESET */

*{

    margin:0;

    padding:0;

    box-sizing:border-box;

    scroll-behavior:smooth;

}

html{

    scroll-behavior:smooth;

}

body{

    font-family:'Inter',sans-serif;

    background:var(--bg);

    color:var(--text);

    overflow-x:hidden;

}

/* SCROLLBAR */

::-webkit-scrollbar{

    width:8px;

}

::-webkit-scrollbar-track{

    background:#090909;

}

::-webkit-scrollbar-thumb{

    background:#333;

    border-radius:50px;

}

/* CURSOR GLOW */

#cursorGlow{

    position:fixed;

    width:450px;

    height:450px;

    border-radius:50%;

    pointer-events:none;

    background:radial-gradient(circle,
    rgba(110,231,255,.14),
    transparent 70%);

    transform:translate(-50%,-50%);

    z-index:0;

}

/* BODY BACKGROUND */

body::before{

    content:"";

    position:fixed;

    inset:0;

    background:

    radial-gradient(circle at top left,
    rgba(110,231,255,.05),
    transparent 35%),

    radial-gradient(circle at bottom right,
    rgba(255,255,255,.03),
    transparent 40%);

    z-index:-2;

}

/* NAVBAR */

.navbar{

    position:fixed;

    top:0;

    width:100%;

    padding:24px 8%;

    display:flex;

    justify-content:space-between;

    align-items:center;

    backdrop-filter:blur(20px);

    background:rgba(5,5,5,.55);

    border-bottom:1px solid rgba(255,255,255,.05);

    z-index:999;

}

/* LOGO */

.logo{

    font-size:1.6rem;

    font-weight:800;

    letter-spacing:3px;

}

/* NAV LINKS */

.navbar ul{

    display:flex;

    list-style:none;

    gap:45px;

}

.navbar ul li a{

    text-decoration:none;

    color:var(--secondary);

    transition:.35s;

    font-weight:500;

}

.navbar ul li a:hover{

    color:white;

}

/* HERO */

.hero{

    width:100%;

    min-height:100vh;

    display:grid;

    grid-template-columns:1fr 1fr;

    align-items:center;

    padding:140px 8%;

    gap:60px;

}

/* TAG */

.tag{

    display:inline-block;

    padding:10px 18px;

    border-radius:100px;

    background:rgba(255,255,255,.06);

    border:1px solid rgba(255,255,255,.08);

    color:var(--accent);

    font-size:.82rem;

    letter-spacing:2px;

    margin-bottom:30px;

}

/* HEADING */

.hero h1{

    font-size:5.5rem;

    line-height:1.05;

    font-weight:900;

}

.hero h1 span{

    color:var(--accent);

}

/* PARAGRAPH */

.hero p{

    margin-top:28px;

    font-size:1.15rem;

    color:var(--secondary);

    line-height:1.8;

    max-width:620px;

}

/* BUTTONS */

.heroButtons{

    margin-top:45px;

    display:flex;

    gap:20px;

}

/* PRIMARY */

.primaryBtn{

    text-decoration:none;

    color:black;

    background:var(--accent);

    padding:18px 38px;

    border-radius:100px;

    font-weight:700;

    transition:.35s;

}

.primaryBtn:hover{

    transform:translateY(-4px);

    box-shadow:0 20px 45px rgba(110,231,255,.30);

}

/* SECONDARY */

.secondaryBtn{

    text-decoration:none;

    color:white;

    border:1px solid rgba(255,255,255,.10);

    padding:18px 38px;

    border-radius:100px;

    transition:.35s;

}

.secondaryBtn:hover{

    background:white;

    color:black;

}

/* HERO RIGHT */

.hero-right{

    display:flex;

    justify-content:center;

}

/* GLASS CARD */

.glassCard{

    width:430px;

    height:430px;

    border-radius:32px;

    background:linear-gradient(

        135deg,

        rgba(255,255,255,.06),

        rgba(255,255,255,.02)

    );

    border:1px solid rgba(255,255,255,.08);

    backdrop-filter:blur(18px);

    display:flex;

    flex-direction:column;

    justify-content:center;

    align-items:center;

    text-align:center;

    transition:.5s;

    box-shadow:

    0 25px 80px rgba(0,0,0,.45);

}

.glassCard:hover{

    transform:translateY(-10px);

}

.glassCard p{

    color:var(--secondary);

    margin-bottom:15px;

    text-transform:uppercase;

    letter-spacing:2px;

}

.glassCard h3{

    font-size:2rem;

    margin-bottom:12px;

}

.glassCard span{

    color:var(--accent);

}

/* CLIENTS */

.clients{

    padding:70px 8%;

    text-align:center;

}

.clients p{

    color:var(--secondary);

    text-transform:uppercase;

    letter-spacing:4px;

    margin-bottom:40px;

}

.clientGrid{

    display:grid;

    grid-template-columns:repeat(6,1fr);

    gap:25px;

}

.clientGrid span{

    padding:22px;

    background:#111;

    border:1px solid rgba(255,255,255,.05);

    border-radius:14px;

    font-weight:700;

    color:#d9d9d9;

    transition:.35s;

}

.clientGrid span:hover{

    background:var(--accent);

    color:black;

    transform:translateY(-5px);

}

/* SECTION HEADING */

.sectionHeading{

    text-align:center;

    margin-bottom:70px;

}

.sectionHeading span{

    color:var(--accent);

    letter-spacing:3px;

    text-transform:uppercase;

    font-size:.9rem;

}

.sectionHeading h2{

    font-size:3rem;

    margin-top:18px;

    font-weight:800;

    /* ===========================================
   AVIN PORTFOLIO
   PART 1
=========================================== */

/* Google Font */

@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap');

/* VARIABLES */

:root{

    --bg:#050505;

    --card:#101010;

    --card2:#171717;

    --text:#ffffff;

    --secondary:#9f9f9f;

    --accent:#6EE7FF;

    --border:rgba(255,255,255,.08);

    --radius:20px;

}

/* RESET */

*{

    margin:0;

    padding:0;

    box-sizing:border-box;

    scroll-behavior:smooth;

}

html{

    scroll-behavior:smooth;

}

body{

    font-family:'Inter',sans-serif;

    background:var(--bg);

    color:var(--text);

    overflow-x:hidden;

}

/* SCROLLBAR */

::-webkit-scrollbar{

    width:8px;

}

::-webkit-scrollbar-track{

    background:#090909;

}

::-webkit-scrollbar-thumb{

    background:#333;

    border-radius:50px;

}

/* CURSOR GLOW */

#cursorGlow{

    position:fixed;

    width:450px;

    height:450px;

    border-radius:50%;

    pointer-events:none;

    background:radial-gradient(circle,
    rgba(110,231,255,.14),
    transparent 70%);

    transform:translate(-50%,-50%);

    z-index:0;

}

/* BODY BACKGROUND */

body::before{

    content:"";

    position:fixed;

    inset:0;

    background:

    radial-gradient(circle at top left,
    rgba(110,231,255,.05),
    transparent 35%),

    radial-gradient(circle at bottom right,
    rgba(255,255,255,.03),
    transparent 40%);

    z-index:-2;

}

/* NAVBAR */

.navbar{

    position:fixed;

    top:0;

    width:100%;

    padding:24px 8%;

    display:flex;

    justify-content:space-between;

    align-items:center;

    backdrop-filter:blur(20px);

    background:rgba(5,5,5,.55);

    border-bottom:1px solid rgba(255,255,255,.05);

    z-index:999;

}

/* LOGO */

.logo{

    font-size:1.6rem;

    font-weight:800;

    letter-spacing:3px;

}

/* NAV LINKS */

.navbar ul{

    display:flex;

    list-style:none;

    gap:45px;

}

.navbar ul li a{

    text-decoration:none;

    color:var(--secondary);

    transition:.35s;

    font-weight:500;

}

.navbar ul li a:hover{

    color:white;

}

/* HERO */

.hero{

    width:100%;

    min-height:100vh;

    display:grid;

    grid-template-columns:1fr 1fr;

    align-items:center;

    padding:140px 8%;

    gap:60px;

}

/* TAG */

.tag{

    display:inline-block;

    padding:10px 18px;

    border-radius:100px;

    background:rgba(255,255,255,.06);

    border:1px solid rgba(255,255,255,.08);

    color:var(--accent);

    font-size:.82rem;

    letter-spacing:2px;

    margin-bottom:30px;

}

/* HEADING */

.hero h1{

    font-size:5.5rem;

    line-height:1.05;

    font-weight:900;

}

.hero h1 span{

    color:var(--accent);

}

/* PARAGRAPH */

.hero p{

    margin-top:28px;

    font-size:1.15rem;

    color:var(--secondary);

    line-height:1.8;

    max-width:620px;

}

/* BUTTONS */

.heroButtons{

    margin-top:45px;

    display:flex;

    gap:20px;

}

/* PRIMARY */

.primaryBtn{

    text-decoration:none;

    color:black;

    background:var(--accent);

    padding:18px 38px;

    border-radius:100px;

    font-weight:700;

    transition:.35s;

}

.primaryBtn:hover{

    transform:translateY(-4px);

    box-shadow:0 20px 45px rgba(110,231,255,.30);

}

/* SECONDARY */

.secondaryBtn{

    text-decoration:none;

    color:white;

    border:1px solid rgba(255,255,255,.10);

    padding:18px 38px;

    border-radius:100px;

    transition:.35s;

}

.secondaryBtn:hover{

    background:white;

    color:black;

}

/* HERO RIGHT */

.hero-right{

    display:flex;

    justify-content:center;

}

/* GLASS CARD */

.glassCard{

    width:430px;

    height:430px;

    border-radius:32px;

    background:linear-gradient(

        135deg,

        rgba(255,255,255,.06),

        rgba(255,255,255,.02)

    );

    border:1px solid rgba(255,255,255,.08);

    backdrop-filter:blur(18px);

    display:flex;

    flex-direction:column;

    justify-content:center;

    align-items:center;

    text-align:center;

    transition:.5s;

    box-shadow:

    0 25px 80px rgba(0,0,0,.45);

}

.glassCard:hover{

    transform:translateY(-10px);

}

.glassCard p{

    color:var(--secondary);

    margin-bottom:15px;

    text-transform:uppercase;

    letter-spacing:2px;

}

.glassCard h3{

    font-size:2rem;

    margin-bottom:12px;

}

.glassCard span{

    color:var(--accent);

}

/* CLIENTS */

.clients{

    padding:70px 8%;

    text-align:center;

}

.clients p{

    color:var(--secondary);

    text-transform:uppercase;

    letter-spacing:4px;

    margin-bottom:40px;

}

.clientGrid{

    display:grid;

    grid-template-columns:repeat(6,1fr);

    gap:25px;

}

.clientGrid span{

    padding:22px;

    background:#111;

    border:1px solid rgba(255,255,255,.05);

    border-radius:14px;

    font-weight:700;

    color:#d9d9d9;

    transition:.35s;

}

.clientGrid span:hover{

    background:var(--accent);

    color:black;

    transform:translateY(-5px);

}

/* SECTION HEADING */

.sectionHeading{

    text-align:center;

    margin-bottom:70px;

}

.sectionHeading span{

    color:var(--accent);

    letter-spacing:3px;

    text-transform:uppercase;

    font-size:.9rem;

}

.sectionHeading h2{

    font-size:3rem;

    margin-top:18px;

    font-weight:800;



}
/* ===========================================
   AVIN PORTFOLIO
   PART 2
   Work • Services • About
===========================================*/

/* -----------------------------
   WORK SECTION
------------------------------*/

.work{

    padding:120px 8%;

}

.projectGrid{

    display:grid;

    grid-template-columns:repeat(3,1fr);

    gap:35px;

}

.projectCard{

    position:relative;

    overflow:hidden;

    border-radius:24px;

    background:var(--card);

    border:1px solid var(--border);

    min-height:380px;

    cursor:pointer;

    transition:.45s ease;

    box-shadow:0 18px 50px rgba(0,0,0,.28);

}

.projectCard:hover{

    transform:translateY(-12px);

    box-shadow:0 35px 70px rgba(0,0,0,.45);

}

.projectCard img{

    width:100%;

    height:100%;

    object-fit:cover;

    transition:.6s ease;

    display:block;

}

.projectCard:hover img{

    transform:scale(1.08);

}

.projectCard::before{

    content:"";

    position:absolute;

    inset:0;

    background:linear-gradient(

        to top,

        rgba(0,0,0,.92),

        rgba(0,0,0,.15),

        transparent

    );

    z-index:1;

}

.overlay{

    position:absolute;

    left:0;

    right:0;

    bottom:0;

    z-index:2;

    padding:30px;

    transform:translateY(22px);

    opacity:.92;

    transition:.45s ease;

}

.projectCard:hover .overlay{

    transform:translateY(0);

    opacity:1;

}

.overlay h3{

    font-size:1.5rem;

    font-weight:700;

    margin-bottom:10px;

}

.overlay p{

    color:var(--secondary);

    line-height:1.7;

    margin-bottom:20px;

}

.overlay a{

    display:inline-flex;

    align-items:center;

    gap:8px;

    text-decoration:none;

    color:var(--accent);

    font-weight:700;

    transition:.3s;

}

.overlay a:hover{

    letter-spacing:.8px;

}

/* -----------------------------
   SERVICES
------------------------------*/

#services{

    padding:120px 8%;

}

.serviceGrid{

    display:grid;

    grid-template-columns:repeat(3,1fr);

    gap:30px;

}

.service{

    background:linear-gradient(

        180deg,

        rgba(255,255,255,.05),

        rgba(255,255,255,.02)

    );

    border:1px solid var(--border);

    border-radius:24px;

    padding:50px 35px;

    transition:.4s ease;

    backdrop-filter:blur(16px);

    text-align:left;

    position:relative;

    overflow:hidden;

}

.service::before{

    content:"";

    position:absolute;

    top:-120px;

    right:-120px;

    width:240px;

    height:240px;

    border-radius:50%;

    background:rgba(110,231,255,.06);

    transition:.45s;

}

.service:hover::before{

    transform:scale(1.5);

}

.service:hover{

    transform:translateY(-10px);

    border-color:rgba(110,231,255,.35);

}

.service{

    font-size:3rem;

}

.service h3{

    margin-top:28px;

    font-size:1.45rem;

    font-weight:700;

}

.service p{

    margin-top:18px;

    color:var(--secondary);

    line-height:1.8;

}

/* -----------------------------
   ABOUT
------------------------------*/

#about{

    padding:120px 8%;

}

.aboutBox{

    max-width:1100px;

    margin:auto;

    background:linear-gradient(

        145deg,

        rgba(255,255,255,.05),

        rgba(255,255,255,.02)

    );

    border:1px solid var(--border);

    border-radius:32px;

    padding:70px;

    backdrop-filter:blur(18px);

    position:relative;

    overflow:hidden;

}

.aboutBox::before{

    content:"";

    position:absolute;

    width:420px;

    height:420px;

    border-radius:50%;

    background:rgba(110,231,255,.05);

    top:-180px;

    right:-120px;

}

.aboutBox p{

    position:relative;

    z-index:2;

    font-size:1.15rem;

    line-height:2;

    color:#d4d4d4;

}

.aboutHighlights{

    display:grid;

    grid-template-columns:repeat(4,1fr);

    gap:25px;

    margin-top:55px;

}

.highlight{

    background:rgba(255,255,255,.03);

    border:1px solid rgba(255,255,255,.06);

    border-radius:18px;

    padding:30px;

    transition:.35s;

    text-align:center;

}

.highlight:hover{

    transform:translateY(-8px);

    background:rgba(255,255,255,.06);

}

.highlight h4{

    font-size:2rem;

    color:var(--accent);

    margin-bottom:10px;

}

.highlight span{

    color:var(--secondary);

    font-size:.95rem;

}

/* -----------------------------
   SMALL FADE ANIMATION
------------------------------*/

.fade-up{

    opacity:0;

    transform:translateY(40px);

    transition:.8s ease;

}

.fade-up.show{

    opacity:1;

    transform:translateY(0);


}

/* ===========================================
   AVIN PORTFOLIO
   PART 3
   Contact • Footer • Floating Button
   Responsive • Animations
===========================================*/

/* CONTACT */

#contact{

    padding:120px 8%;

}

.contactCard{

    max-width:900px;

    margin:auto;

    background:linear-gradient(
        145deg,
        rgba(255,255,255,.05),
        rgba(255,255,255,.02)
    );

    border:1px solid rgba(255,255,255,.08);

    border-radius:30px;

    padding:70px;

    display:flex;

    justify-content:center;

    align-items:center;

    gap:40px;

    flex-wrap:wrap;

    backdrop-filter:blur(18px);

}

.contactCard a{

    color:white;

    text-decoration:none;

    padding:18px 34px;

    border-radius:100px;

    background:#111;

    transition:.35s;

    font-weight:600;

}

.contactCard a:hover{

    background:var(--accent);

    color:black;

    transform:translateY(-5px);

}

/* FOOTER */

footer{

    padding:80px 8%;

    text-align:center;

    border-top:1px solid rgba(255,255,255,.05);

}

footer h3{

    font-size:2rem;

    margin-bottom:15px;

}

footer p{

    color:var(--secondary);

    margin-bottom:15px;

}

footer small{

    color:#777;

}

/* FLOATING BUTTON */

.floatingButton{

    position:fixed;

    right:35px;

    bottom:35px;

    padding:18px 30px;

    border-radius:100px;

    text-decoration:none;

    background:var(--accent);

    color:black;

    font-weight:700;

    box-shadow:0 18px 45px rgba(110,231,255,.35);

    transition:.35s;

    z-index:999;

}

.floatingButton:hover{

    transform:translateY(-6px) scale(1.04);

}

/* ANIMATIONS */

@keyframes float{

    0%{

        transform:translateY(0px);

    }

    50%{

        transform:translateY(-12px);

    }

    100%{

        transform:translateY(0px);

    }

}

.glassCard{

    animation:float 6s ease-in-out infinite;

}

@keyframes fadeIn{

    from{

        opacity:0;

        transform:translateY(40px);

    }

    to{

        opacity:1;

        transform:translateY(0);

    }

}

.hero-left{

    animation:fadeIn 1s ease;

}

.hero-right{

    animation:fadeIn 1.4s ease;

}

/* IMAGE SAFETY */

img{

    max-width:100%;

    display:block;

}

/* LINKS */

a{

    transition:.3s;

}

/* SELECTION */

::selection{

    background:var(--accent);

    color:black;

}

/* RESPONSIVE */

@media(max-width:1100px){

.hero{

grid-template-columns:1fr;

text-align:center;

}

.heroButtons{

justify-content:center;

}

.hero-right{

margin-top:60px;

}

.projectGrid{

grid-template-columns:repeat(2,1fr);

}

.serviceGrid{

grid-template-columns:repeat(2,1fr);

}

.clientGrid{

grid-template-columns:repeat(3,1fr);

}

.aboutHighlights{

grid-template-columns:repeat(2,1fr);

}

}

/* MOBILE */

@media(max-width:768px){

.navbar{

padding:20px 6%;

}

.navbar ul{

display:none;

}

.hero{

padding:120px 6% 80px;

}

.hero h1{

font-size:3rem;

}

.hero p{

font-size:1rem;

}

.glassCard{

width:100%;

height:320px;

}

.projectGrid{

grid-template-columns:1fr;

}

.serviceGrid{

grid-template-columns:1fr;

}

.clientGrid{

grid-template-columns:repeat(2,1fr);

}

.aboutBox{

padding:40px;

}

.aboutHighlights{

grid-template-columns:1fr;

}

.contactCard{

padding:40px 25px;

}

.contactCard a{

width:100%;

text-align:center;

}

.floatingButton{

right:20px;

bottom:20px;

padding:15px 22px;

font-size:.95rem;

}

.sectionHeading h2{

font-size:2.2rem;

}

}

/* SMALL MOBILE */

@media(max-width:480px){

.hero h1{

font-size:2.4rem;

}

.logo{

font-size:1.2rem;

}

.tag{

font-size:.7rem;

}

.primaryBtn,

.secondaryBtn{

padding:15px 25px;

font-size:.9rem;

}

.heroButtons{

flex-direction:column;

align-items:center;

}

.clientGrid{

grid-template-columns:1fr;

}

}

/* END */



}
