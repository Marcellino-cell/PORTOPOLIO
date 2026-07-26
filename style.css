/*=========================
Google Font
=========================*/

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap');

/*=========================
CSS VARIABLES
=========================*/

:root{

    --primary:#8B5CF6;
    --secondary:#A78BFA;
    --dark:#1E1B4B;
    --light:#ffffff;
    --bg:#F8FAFC;
    --text:#374151;
    --gray:#6B7280;
    --shadow:0 10px 30px rgba(0,0,0,.08);
    --radius:18px;
    --transition:.35s ease;

}

/*=========================
RESET
=========================*/

*{

    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;

}

html{

    scroll-behavior:smooth;

}

body{

    background:var(--bg);
    color:var(--text);
    overflow-x:hidden;

}

img{

    width:100%;
    display:block;

}

a{

    text-decoration:none;

}

ul{

    list-style:none;

}

section{

    padding:100px 10%;

}

.section-title{

    text-align:center;
    margin-bottom:60px;

}

.section-title h2{

    font-size:38px;
    color:var(--dark);
    font-weight:700;

}

/*=========================
Scrollbar
=========================*/

::-webkit-scrollbar{

    width:10px;

}

::-webkit-scrollbar-track{

    background:#ececec;

}

::-webkit-scrollbar-thumb{

    background:var(--primary);
    border-radius:30px;

}

::-webkit-scrollbar-thumb:hover{

    background:#6d28d9;

}

/*=========================
Loading Screen
=========================*/

#loader{

    position:fixed;
    inset:0;
    background:#fff;
    display:flex;
    justify-content:center;
    align-items:center;
    z-index:99999;

}

.spinner{

    width:70px;
    height:70px;
    border:7px solid #ddd;
    border-top:7px solid var(--primary);
    border-radius:50%;
    animation:spin 1s linear infinite;

}

@keyframes spin{

    100%{

        transform:rotate(360deg);

    }

}

/*=========================
Scroll Progress
=========================*/

#progress-bar{

    position:fixed;
    top:0;
    left:0;
    width:0%;
    height:5px;
    background:linear-gradient(
        90deg,
        var(--primary),
        var(--secondary)
    );
    z-index:9999;

}

/*=========================
Navbar
=========================*/

header{

    position:fixed;
    top:0;
    left:0;
    width:100%;
    z-index:999;
    background:rgba(255,255,255,.9);
    backdrop-filter:blur(18px);
    box-shadow:0 2px 10px rgba(0,0,0,.05);

}

.navbar{

    width:90%;
    margin:auto;
    height:80px;

    display:flex;
    justify-content:space-between;
    align-items:center;

}

.logo{

    font-size:28px;
    font-weight:700;
    color:var(--primary);

}

.nav-menu{

    display:flex;
    gap:35px;

}

.nav-menu a{

    color:var(--text);
    font-weight:500;
    transition:var(--transition);

}

.nav-menu a:hover{

    color:var(--primary);

}

.nav-right{

    display:flex;
    align-items:center;
    gap:15px;

}

#theme-toggle{

    width:45px;
    height:45px;

    border:none;
    border-radius:50%;

    background:var(--primary);
    color:#fff;
    cursor:pointer;

    transition:.3s;

}

#theme-toggle:hover{

    transform:rotate(180deg);

}

.menu-btn{

    display:none;
    font-size:28px;
    cursor:pointer;

}

/*=========================
Hero
=========================*/

.hero{
    min-height:100vh;
    display:grid;
    grid-template-columns:repeat(2,1fr);
    align-items:center;
    gap:70px;

    position:relative;
    overflow:hidden;

    background:
    radial-gradient(circle at top right,#7c3aed33,transparent 35%),
    radial-gradient(circle at bottom left,#3b82f633,transparent 35%),
    linear-gradient(135deg,#f8fafc,#eef2ff,#ffffff);
}

.hero>*{
    position:relative;
    z-index:2;
}

.hero::after{

content:"";

position:absolute;
inset:0;

background-image:
linear-gradient(rgba(139,92,246,.08) 1px,transparent 1px),
linear-gradient(90deg,rgba(139,92,246,.08) 1px,transparent 1px);

background-size:40px 40px;

pointer-events:none;

z-index:0;
}

.glow{

position:absolute;

width:420px;
height:420px;

background:#8b5cf655;

filter:blur(120px);

border-radius:50%;

animation:moveGlow 8s ease-in-out infinite;

z-index:-1;

}

@keyframes moveGlow{

0%,100%{

transform:translate(0,0);

}

50%{

transform:translate(80px,-40px);

}

}

.hero-left p:first-child{

    color:var(--primary);
    font-weight:600;
    margin-bottom:15px;

}

.hero-left h1{

    font-size:58px;
    line-height:1.2;
    margin-bottom:15px;

}

.hero-left span{

    color:var(--primary);

}

.hero-left h3{

    color:var(--gray);
    font-size:26px;
    margin-bottom:25px;

}

.hero-left p{

    line-height:1.8;

}

.hero-button{

    display:flex;
    gap:20px;
    margin-top:35px;

}

.btn{

    padding:14px 35px;
    border-radius:40px;

    background:var(--primary);
    color:#fff;

    transition:.3s;

    box-shadow:var(--shadow);

}

.btn:hover{

    transform:translateY(-6px);

}

.btn-outline{

    padding:14px 35px;

    border-radius:40px;

    border:2px solid var(--primary);

    color:var(--primary);

    transition:.3s;

}

.btn-outline:hover{

    background:var(--primary);
    color:#fff;

}

.hero-right{
    display:flex;
    justify-content:center;
    align-items:center;
    position:relative;
    z-index:2;
}

@keyframes float{

    0%{

        transform:translateY(0);

    }

    50%{

        transform:translateY(-18px);

    }

    100%{

        transform:translateY(0);

    }

}

/*=========================
Background Blur
=========================*/

.hero::before{

    content:"";

    position:absolute;

    width:350px;
    height:350px;

    background:#c4b5fd;

    border-radius:50%;

    filter:blur(130px);

    top:120px;
    right:80px;

    opacity:.5;
    z-index:-1;

}

/*=========================
Responsive Hero
=========================*/

@media(max-width:992px){

.hero{

grid-template-columns:1fr;
text-align:center;

}

.hero-button{

justify-content:center;

}

.hero-right{

order:-1;

}

.hero-left h1{

font-size:45px;

}

.hero-right img{

width:320px;

}

}

@media(max-width:768px){

.nav-menu{

display:none;

}

.menu-btn{

display:block;

}

.hero{

padding-top:120px;

}

.hero-left h1{

font-size:36px;

}

.hero-left h3{

font-size:20px;

}

.section-title h2{

font-size:30px;

}

}

@media(max-width:480px){

.hero-button{

flex-direction:column;

}

.btn,
.btn-outline{

width:100%;

text-align:center;

}

.hero-right img{

width:260px;

}

}

/*==========================================
ABOUT
==========================================*/

.about-container{

    display:grid;
    grid-template-columns:1fr 1.2fr;
    gap:70px;
    align-items:center;

}

.about-image{

    display:flex;
    justify-content:center;

}

.about-image img{

    width:350px;
    border-radius:25px;
    box-shadow:var(--shadow);
    transition:.4s;

}

.about-image img:hover{

    transform:scale(1.05);

}

.about-content p{

    font-size:17px;
    color:var(--gray);
    line-height:1.9;
    margin-bottom:35px;

}

/*==========================================
EDUCATION
==========================================*/

.timeline{

    position:relative;
    max-width:850px;
    margin:auto;

}

.timeline::before{

    content:"";
    position:absolute;

    left:25px;
    top:0;

    width:4px;
    height:100%;

    background:var(--secondary);

}

.timeline-item{

    position:relative;

    margin-bottom:60px;
    margin-left:70px;

    background:#fff;

    padding:30px;

    border-radius:18px;

    box-shadow:var(--shadow);

    transition:.35s;

}

.timeline-item:hover{

    transform:translateY(-8px);

}

.timeline-item::before{

    content:"";

    position:absolute;

    left:-58px;
    top:35px;

    width:22px;
    height:22px;

    background:var(--primary);

    border:5px solid white;

    border-radius:50%;

    box-shadow:0 0 0 5px #ddd;

}

.timeline-item h3{

    color:var(--primary);
    margin-bottom:10px;

}

.timeline-item span{

    display:inline-block;

    margin-bottom:15px;

    color:var(--gray);

    font-size:14px;

}

.timeline-item p{

    color:#555;
    line-height:1.8;

}


/*==========================================
SKILLS
==========================================*/

.skill-grid{

    display:grid;

    grid-template-columns:repeat(auto-fit,minmax(260px,1fr));

    gap:30px;

}

.skill-card{

    background:#fff;

    padding:30px;

    border-radius:20px;

    box-shadow:var(--shadow);

    transition:.35s;

}

.skill-card:hover{

    transform:translateY(-12px);

}

.skill-card h3{

    margin-bottom:20px;

    color:var(--dark);

}

.bar{

    width:100%;

    height:10px;

    background:#ececec;

    border-radius:30px;

    overflow:hidden;

}

.fill{

    height:100%;

    border-radius:30px;

    animation:progress 2s ease forwards;

}

/* Skill */

.html{

    width:95%;
    background:#ff5722;

}

.css{

    width:92%;
    background:#2196f3;

}

.js{

    width:88%;
    background:#f7df1e;

}

.php{

    width:82%;
    background:#777bb3;

}

.mysql{

    width:86%;
    background:#00758f;

}

.laravel{

    width:80%;
    background:#ff2d20;

}

.react{

    width:78%;
    background:#61dafb;

}

.figma{

    width:90%;
    background:#a259ff;

}

.github{

    width:87%;
    background:#333;

}

.bootstrap{

    width:89%;
    background:#7952b3;

}

@keyframes progress{

    from{

        width:0;

    }

}


/*==========================================
Skill Percentage
==========================================*/

.skill-card::after{

    content:"";

    display:block;

    margin-top:18px;

    font-size:14px;

    color:var(--gray);

}

.skill-card:nth-child(1)::after{

content:"95%";

}

.skill-card:nth-child(2)::after{

content:"92%";

}

.skill-card:nth-child(3)::after{

content:"88%";

}

.skill-card:nth-child(4)::after{

content:"82%";

}

.skill-card:nth-child(5)::after{

content:"86%";

}

.skill-card:nth-child(6)::after{

content:"80%";

}

.skill-card:nth-child(7)::after{

content:"78%";

}

.skill-card:nth-child(8)::after{

content:"90%";

}

.skill-card:nth-child(9)::after{

content:"87%";

}

.skill-card:nth-child(10)::after{

content:"89%";

}


/*==========================================
Responsive
==========================================*/

@media(max-width:992px){

.about-container{

grid-template-columns:1fr;
text-align:center;

}

.about-image{

margin-bottom:30px;

}

}

@media(max-width:768px){

.timeline::before{

left:12px;

}

.timeline-item{

margin-left:45px;

padding:22px;

}

.timeline-item::before{

left:-40px;

width:18px;
height:18px;

}

.about-info{

grid-template-columns:1fr;

}

.skill-grid{

grid-template-columns:1fr;

}

}

@media(max-width:480px){

.about-image img{

width:240px;

}

.box{

padding:22px;

}

.timeline-item{

padding:18px;

}

.timeline-item h3{

font-size:18px;

}

}

/*==========================================
PROJECT
==========================================*/

.project-grid{

    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(320px,1fr));
    gap:35px;

}

.project-card{

    background:#fff;
    border-radius:20px;
    overflow:hidden;
    box-shadow:var(--shadow);
    transition:.4s;

}

.project-card:hover{

    transform:translateY(-12px);

}

.project-card img{

    width:100%;
    height:220px;
    object-fit:cover;
    transition:.5s;

}

.project-card:hover img{

    transform:scale(1.08);

}

.project-card h3{

    margin:20px;
    color:var(--dark);

}

.project-card p{

    margin:0 20px 20px;
    color:var(--gray);
    line-height:1.7;

}

.btn-small{

    display:inline-block;
    margin:0 20px 25px;
    padding:12px 24px;
    background:var(--primary);
    color:#fff;
    border-radius:30px;
    transition:.3s;

}

.btn-small:hover{

    background:#6d28d9;

}


/*==========================================
EXPERIENCE
==========================================*/

.experience-box{

    max-width:850px;
    margin:auto;
    background:#fff;
    padding:45px;
    border-radius:20px;
    box-shadow:var(--shadow);
    text-align:center;
    transition:.35s;

}

.experience-box:hover{

    transform:translateY(-10px);

}

.experience-box h3{

    color:var(--primary);
    margin-bottom:15px;

}

.experience-box span{

    display:block;
    color:var(--gray);
    margin-bottom:20px;

}

.experience-box p{

    line-height:1.8;
    color:#555;

}

/*==========================================
CONTACT
==========================================*/

#contact-form{

    max-width:700px;
    margin:auto;

    display:flex;
    flex-direction:column;
    gap:20px;

}

#contact-form input,
#contact-form textarea{

    width:100%;
    padding:18px;

    border:none;

    border-radius:15px;

    background:#fff;

    box-shadow:var(--shadow);

    font-size:15px;

    outline:none;

}

#contact-form textarea{

    resize:none;
    min-height:180px;

}

#contact-form button{

    padding:18px;

    border:none;

    border-radius:40px;

    background:var(--primary);

    color:#fff;

    cursor:pointer;

    font-size:16px;

    transition:.3s;

}

#contact-form button:hover{

    background:#6d28d9;

}


/*==========================================
FOOTER
==========================================*/

footer{

    background:var(--dark);

    color:#fff;

    text-align:center;

    padding:70px 10%;

    margin-top:80px;

}

footer h2{

    margin-bottom:15px;

}

footer p{

    color:#ddd;
    line-height:1.8;

}

.social{

    margin:30px 0;

}

.social a{

    display:inline-flex;
    justify-content:center;
    align-items:center;

    width:50px;
    height:50px;

    margin:0 8px;

    border-radius:50%;

    background:#fff;

    color:var(--primary);

    font-size:20px;

    transition:.35s;

}

.social a:hover{

    transform:translateY(-8px);

    background:var(--primary);

    color:#fff;

}


/*==========================================
BACK TO TOP
==========================================*/

#topBtn{

    position:fixed;

    right:25px;
    bottom:25px;

    width:55px;
    height:55px;

    border:none;

    border-radius:50%;

    background:var(--primary);

    color:#fff;

    font-size:20px;

    cursor:pointer;

    display:none;

    box-shadow:0 10px 20px rgba(0,0,0,.2);

    transition:.35s;

    z-index:999;

}

#topBtn:hover{

    transform:translateY(-6px);

    background:#6d28d9;

}


/*==========================================
IMAGE POPUP
==========================================*/

.popup{

    position:fixed;
    inset:0;

    background:rgba(0,0,0,.8);

    display:flex;
    justify-content:center;
    align-items:center;

    visibility:hidden;
    opacity:0;

    transition:.35s;

    z-index:99999;

}

.popup.active{

    visibility:visible;
    opacity:1;

}

.popup img{

    width:85%;
    max-width:850px;

    border-radius:15px;

}

.popup span{

    position:absolute;

    top:30px;
    right:40px;

    color:#fff;

    font-size:40px;

    cursor:pointer;

}


/*==========================================
RESPONSIVE
==========================================*/

@media(max-width:992px){

.project-grid{

grid-template-columns:repeat(2,1fr);

}

}

@media(max-width:768px){

.project-grid{

grid-template-columns:1fr;

}

.certificate-grid{

grid-template-columns:repeat(2,1fr);

}

.experience-box{

padding:30px;

}

footer{

padding:50px 20px;

}

}

@media(max-width:480px){

.certificate-grid{

grid-template-columns:1fr;

}

.project-card img{

height:190px;

}

#topBtn{

width:48px;
height:48px;

right:18px;
bottom:18px;

}

.social a{

width:45px;
height:45px;

font-size:18px;

}

}

/*==========================================
ACTIVE MENU
==========================================*/

.nav-menu a.active{

    color:var(--primary);
    font-weight:700;

}


/*==========================================
RESPONSIVE MENU
==========================================*/

@media(max-width:768px){

.nav-menu{

position:absolute;

top:80px;
left:0;

width:100%;

background:#fff;

flex-direction:column;

text-align:center;

padding:30px 0;

display:none;

box-shadow:0 10px 20px rgba(0,0,0,.08);

}

.nav-menu.active{

display:flex;

}

}

/* Reveal */

.section-title,
.about-container,
.timeline-item,
.skill-card,
.project-card,
.experience-box,
#contact-form{

opacity:0;

transform:translateY(50px);

transition:.8s ease;

}

.show{

opacity:1;

transform:translateY(0);

}


/* Dark Mode */

body.dark{

background:#0f172a;

color:#e5e7eb;

}

body.dark header{

background:#111827;

}

body.dark .logo,
body.dark h1,
body.dark h2,
body.dark h3{

color:#fff;

}

body.dark p,
body.dark span,
body.dark h3,
body.dark .hero-left h3{
    color:#f1f5f9;
}

body.dark .hero{
    background:#0f172a;
}

body.dark .hero-left p{
    color:#e2e8f0;
}

body.dark .btn-outline{
    border:2px solid #8B5CF6;
    color:#fff;
}

body.dark .btn-outline:hover{
    background:#8B5CF6;
}

body.dark .neon-name{
    color:#A78BFA;
    text-shadow:0 0 10px rgba(167,139,250,.3);
}

body.dark .box,
body.dark .skill-card,
body.dark .timeline-item,
body.dark .project-card,
body.dark .experience-box,
body.dark #contact-form input,
body.dark #contact-form textarea{

background:#1e293b;

color:#fff;

}

body.dark footer{

background:#020617;

}

body.dark .nav-menu{

background:#111827;

}

body.dark .nav-menu a{

color:#fff;

}

/* Toast */

.toast{

position:fixed;

right:25px;

top:25px;

padding:15px 22px;

background:#8B5CF6;

color:#fff;

border-radius:10px;

box-shadow:0 10px 20px rgba(0,0,0,.2);

transform:translateX(300px);

transition:.4s;

z-index:999999;

}

.toast.show{

transform:translateX(0);

}


/* Ripple */

.btn,
.btn-small,
.btn-outline,
#contact-form button{

overflow:hidden;

position:relative;

}

.ripple{

position:absolute;

border-radius:50%;

transform:scale(0);

background:rgba(255,255,255,.45);

animation:ripple .6s linear;

}

@keyframes ripple{

to{

transform:scale(4);

opacity:0;

}

}


/* Cursor */

.cursor{
    width:16px;
    height:16px;
    border:2px solid #8B5CF6;
    border-radius:50%;
    position:fixed;
    pointer-events:none;
    transform:translate(-50%,-50%);
    z-index:999999;
    transition:transform .02s linear,width .2s,height .2s;
    will-change:transform;
}

.cursor.active{

width:40px;

height:40px;

background:rgba(139,92,246,.15);

}


/* Floating Shape */

.shape{

position:fixed;

bottom:-50px;

width:18px;

height:18px;

background:#c4b5fd;

border-radius:50%;

opacity:.4;

animation:floatShape linear infinite;

pointer-events:none;

z-index:-1;

}

@keyframes floatShape{

from{

transform:translateY(0) rotate(0);

}

to{

transform:translateY(-120vh) rotate(720deg);

}

}

/*==========================================
PART 2B
==========================================*/

.section-active{

animation:sectionFade .8s ease;

}

@keyframes sectionFade{

from{

opacity:.4;

transform:translateY(30px);

}

to{

opacity:1;

transform:translateY(0);

}

}

.section-title h2{

transition:.35s;

}

img{

transition:.6s;

}

.contact-container{

    display:grid;
    grid-template-columns:1fr 1.5fr;
    gap:40px;
    align-items:start;

}

.contact-info{

    display:flex;
    flex-direction:column;
    gap:20px;

}

.contact-box{

    display:flex;
    align-items:center;
    gap:20px;

    background:#fff;
    padding:20px;

    border-radius:15px;

    box-shadow:var(--shadow);

}

.contact-box i{

    width:55px;
    height:55px;

    display:flex;
    justify-content:center;
    align-items:center;

    border-radius:50%;

    background:var(--primary);

    color:#fff;

    font-size:22px;

}

.contact-box h3{

    margin-bottom:5px;

}

@media(max-width:768px){

.contact-container{

grid-template-columns:1fr;

}

}

/* Hero Social */

.hero-social{
    display:flex;
    gap:18px;
    margin-top:30px;
    align-items:center;
}

.hero-social a{
    width:50px;
    height:50px;
    display:flex;
    justify-content:center;
    align-items:center;
    border-radius:50%;
    background:var(--primary);
    color:#fff;
    font-size:22px;
    transition:.35s;
    box-shadow:var(--shadow);
}

.hero-social a:hover{
    transform:translateY(-8px) scale(1.08);
    background:#6d28d9;
}

@media(max-width:768px){
    .hero-social{
        justify-content:center;
        flex-wrap:wrap;
    }
}

/*==========================================
PREMIUM HERO BACKGROUND
==========================================*/
.hero-bg-grid{
    position:absolute;
    inset:0;

    background-image:
    linear-gradient(rgba(139,92,246,.08) 1px,transparent 1px),
    linear-gradient(90deg,rgba(139,92,246,.08) 1px,transparent 1px);

    background-size:45px 45px;

    z-index:0;
}

.hero-glow{
    position:absolute;

    width:450px;
    height:450px;

    border-radius:50%;

    filter:blur(130px);

    animation:glowMove 10s ease-in-out infinite alternate;

    z-index:0;
}

.glow1{

    background:#8b5cf655;

    top:-120px;
    left:-120px;

}

.glow2{

    background:#3b82f655;

    bottom:-120px;
    right:-120px;

}

@keyframes glowMove{

0%{

transform:translate(0,0);

}

100%{

transform:translate(80px,-50px);

}

}

.code-bg{

position:absolute;

left:-30px;
top:120px;

font-size:18px;

font-weight:600;

line-height:2;

white-space:pre-line;

color:rgba(139,92,246,.08);

user-select:none;

pointer-events:none;

z-index:-1;

}

.hero-photo{
    position:relative;
    width:380px;
    height:380px;
    display:flex;
    justify-content:center;
    align-items:center;
    margin:auto;
}

.photo-ring{

position:absolute;

    width:380px;
    height:380px;

border-radius:50%;

background:conic-gradient(

#8b5cf6,
#3b82f6,
#06b6d4,
#8b5cf6

);

animation:ringRotate 6s linear infinite;

}

.photo-ring::before{

content:"";

position:absolute;

inset:8px;

background:#fff;

border-radius:50%;

}

.hero-photo img{
    width:340px;
    height:340px;
    object-fit:cover;
    border-radius:50%;
    position:relative;
    z-index:2;
}

.hero-photo:hover img{

transform:scale(1.04);

}

@keyframes ringRotate{

100%{

transform:rotate(360deg);

}

}

.neon-name{
    color:#8B5CF6;
    font-weight:700;
    text-shadow:
        0 0 6px rgba(139,92,246,.35);
}

.floating-icons{

position:absolute;

inset:0;

pointer-events:none;

}

.floating-icons i{

position:absolute;

font-size:42px;

filter:drop-shadow(0 0 15px rgba(139,92,246,.4));

}

.html-icon{

left:-20px;
top:40px;

color:#E34F26;

}

.css-icon{

right:-15px;
top:60px;

color:#1572B6;

animation-delay:.5s;

}

.js-icon{

left:-30px;
bottom:60px;

color:#F7DF1E;

animation-delay:1s;

}

.php-icon{

right:-20px;
bottom:40px;

color:#777BB4;

animation-delay:1.5s;

}

.react-icon{

top:-30px;
left:50%;

transform:translateX(-50%);

color:#61DAFB;

animation-delay:2s;

}

.github-icon{

bottom:-30px;
left:50%;

transform:translateX(-50%);

color:#333;

animation-delay:2.5s;

}

@keyframes floating{

0%,100%{

transform:translateY(0);

}

50%{

transform:translateY(-18px);

}

}

#spotlight{

position:fixed;

width:280px;
height:280px;

border-radius:50%;

background:radial-gradient(

rgba(139,92,246,.18),

transparent 70%

);

pointer-events:none;

transform:translate(-50%,-50%);

z-index:1;

mix-blend-mode:screen;

}

body.dark .photo-ring::before{

background:#0f172a;

}

body.dark .hero-bg-grid{

background-image:

linear-gradient(rgba(255,255,255,.05) 1px,transparent 1px),

linear-gradient(90deg,rgba(255,255,255,.05) 1px,transparent 1px);

}

body.dark .code-bg{

color:rgba(255,255,255,.05);

}

#networkCanvas{
    position:fixed;
    inset:0;
    width:100%;
    height:100%;
    pointer-events:none;
    z-index:-10;
}

.hero-left,
.hero-right{
    position:relative;
    z-index:5;
}

.hero-left{
    position:relative;
    z-index:2;
}

.hero-right{
    position:relative;
    z-index:2;
    display:flex;
    justify-content:center;
    align-items:center;
}

.hero-bg-grid,
.hero-glow,
.glow,
#networkCanvas{
    pointer-events:none;
}
