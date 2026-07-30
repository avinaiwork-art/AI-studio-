// =========================
// CURSOR GLOW
// =========================

const cursor = document.getElementById("cursorGlow");

document.addEventListener("mousemove", (e) => {

    cursor.style.left = e.clientX + "px";

    cursor.style.top = e.clientY + "px";

});

// =========================
// FADE ANIMATION
// =========================

const observer = new IntersectionObserver((entries)=>{

    entries.forEach(entry=>{

        if(entry.isIntersecting){

            entry.target.classList.add("show");

        }

    });

},{threshold:.2});

document.querySelectorAll("section").forEach((section)=>{

    section.classList.add("fade-up");

    observer.observe(section);

});

// =========================
// NAVBAR SHADOW
// =========================

window.addEventListener("scroll",()=>{

    const nav=document.querySelector(".navbar");

    if(window.scrollY>60){

        nav.style.background="rgba(5,5,5,.85)";

        nav.style.boxShadow="0 10px 30px rgba(0,0,0,.45)";

    }

    else{

        nav.style.background="rgba(5,5,5,.55)";

        nav.style.boxShadow="none";

    }

});

// =========================
// SMOOTH SCROLL
// =========================

document.querySelectorAll('a[href^="#"]').forEach(anchor=>{

anchor.addEventListener("click",function(e){

e.preventDefault();

document.querySelector(this.getAttribute("href")).scrollIntoView({

behavior:"smooth"

});

});

});

// =========================
// PROJECT CARD EFFECT
// =========================

const cards=document.querySelectorAll(".projectCard");

cards.forEach(card=>{

card.addEventListener("mousemove",(e)=>{

const rect=card.getBoundingClientRect();

const x=e.clientX-rect.left;

const y=e.clientY-rect.top;

card.style.background=

`radial-gradient(circle at ${x}px ${y}px,

rgba(110,231,255,.10),

#101010 60%)`;

});

card.addEventListener("mouseleave",()=>{

card.style.background="#101010";

});

});

// =========================
// FLOATING BUTTON
// =========================

const floating=document.querySelector(".floatingButton");

window.addEventListener("scroll",()=>{

if(window.scrollY>600){

floating.style.opacity="1";

floating.style.transform="translateY(0)";

}

else{

floating.style.opacity=".8";

}

});

// =========================
// HERO TYPING EFFECT
// =========================

const title=document.querySelector(".hero h1");

title.animate([

{opacity:0,transform:"translateY(30px)"},

{opacity:1,transform:"translateY(0px)"}

],{

duration:1000,

fill:"forwards"

});
