<!DOCTYPE html> 
 <html lang="en"> 
  
 <head> 
   <meta charset="UTF-8" /> 
   <meta http-equiv="X-UA-Compatible" content="IE=edge" /> 
   <meta name="viewport" content="width=device-width, initial-scale=1.0" /> 
  
   <!-- ======== BOX ICONS ======= --> 
   <!-- https://boxicons.com/ --> 
   <!-- https://github.com/atisawd/boxicons --> 
   <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/boxicons@latest/css/boxicons.min.css" /> 
  
   <!-- ========   CSS    =======  --> 
   <link rel="stylesheet" href="assets/css/style.css" /> 
   <title>Home</title> 
 </head> 
  
 <body> 
   <!-- ========   HEADER    =======  --> 
  
   <header class="l-header" id="header"> 
  
     <!-- ========   NAV Menu    =======  --> 
  
     <nav class="nav bd-container"> 
       <a href="#" class="nav__logo">Ravi</a> 
  
       <div class="nav__menu" id="nav-menu"> 
         <ul class="nav__list"> 
           <li class="nav__item"> 
             <a href="#home" class="nav__link active-link"> 
               <i class='bx bx-home nav__icon'></i>Home 
             </a> 
           </li> 
  
           <li class="nav__item"> 
             <a href="#profile" class="nav__link"> 
               <i class='bx bx-user nav__icon'></i></i>Profile 
             </a> 
           </li> 
  
           <li class="nav__item"> 
             <a href="#education" class="nav__link"> 
               <i class='bx bx-book nav__icon'></i>Education 
             </a> 
           </li> 
  
           <li class="nav__item"> 
             <a href="#skills" class="nav__link"> 
               <i class='bx bx-receipt nav__icon'></i>Skills 
             </a> 
           </li> 
  
           <li class="nav__item"> 
             <a href="#experience" class="nav__link"> 
               <i class='bx bx-briefcase-alt nav__icon'></i>Experience 
             </a> 
           </li> 
  
           <!-- <li class="nav__item"> 
             <a href="#certificates" class="nav__link"> 
               <i class='bx bx-award nav__icon'></i>Certifcates 
             </a> 
           </li> 
  
           <li class="nav__item"> 
             <a href="#references" class="nav__link"> 
               <i class='bx bx-link-external nav__icon'></i>References 
             </a> 
           </li> --> 
         </ul> 
       </div> 
  
  
  
       <div class="nav__toggle" id="nav-toggle"> 
  
         <i class='bx bx-grid-alt'></i> 
  
       </div> 
  
     </nav> 
   </header> 
  
  
  
   <main class="l-main bd-container"> 
     <!-- All elements within this div is generated in pdf  --> 
  
     <div class="resume" id="area-cv"> 
  
       <div class="resume__left"> 
         <section class="home" id="home"> 
  
           <div class="home__container section bd-grid"> 
  
             <div class="home__data bd-grid"> 
  
               <img src="./assets/img/profile.jpg" alt="profile pic" class="home__img"> 
               <h1 class="home__title">Ravi <strong>KUMAR</strong></h1> 
               <h3 class="home__profession">Backend developer</h3> 
  
               <!-- button to download the CV save in the pdf folder [for mobile] --> 
               <div> 
                 <a download="" target="blank" href="./assets/pdf/resume.pdf" class="home__button-movil">Download</a> 
               </div> 
  
             </div> 
             <div class="home__address bd-grid"> 
               <span class="home_information"> 
                 <i class='bx bx-map home__icon'></i> gooty, india
               </span> 
               <span class="home_information"> 
                 <i class='bx bx-envelope home__icon'></i> bijjeravikumar77244@gmail.com 
               </span> 
               <span class="home_information"> 
                 <i class='bx bx-phone home__icon'></i> 7993573200
               </span> 
             </div> 
           </div> 
  
           <!-- Theme change button  --> 
           <i class='bx bx-moon change-theme' title="Theme" id="theme-button"></i> 
  
           <!-- \Button to generate and download the pdf. Available for desktop --> 
  
           <i class='bx bx-download generate-pdf' title="Generate PDF" id="resume-button"></i> 
  
  
         </section> 
  
         <!-- ========   SOCIAL    =======  --> 
         <section class="social section"> 
  
           <h2 class="section-title">SOCIAL</h2> 
           <div class="social__container bd-grid"> 
  
             <a href="https://www.linkedin.com/in/bijje-ravi-kumar-7a9576269" target="_blank" class="social__link"> 
  
               <i class='bx bxl-linkedin-square social__icon'></i>ravikumarhttps://www.linkedin.com/in/bijje-ravi-kumar-7a9576269
             </a> 
  
             <a href=" https://www.facebook.com/ravikumar.ravikuruva" target="_blank" class="social__link"> 
  
               <i class='bx bxl-facebook social__icon'></i>ravikumar.ravikuruva
             </a> 
  
             <a href="https://instagram.com/mr_max_ra?igshid=MzNlNGNkZWQ4Mg== target="_blank" class="social__link"> 
  
               <i class='bx bxl-instagram social__icon'></i>mr_max ra
             </a> 
  
            
  
  
  
           </div> 
         </section> 
  
         <!-- ========   PROFILE    =======  --> 
         <section class="profile section" id="profile"> 
           <h2 class="section-title">Profile</h2> 
           <p class="profile__description"> 
  
  
                    </p> 
  
  
         </section> 
  
  
  
         <!-- ========   EDUCATION    =======  --> 
  
         <section class="education section" id="education"> 
  
           <h2 class="section-title">Education</h2> 
  
  
           <div class="education__container bd-grid"> 
  
             <div class="education__content"> 
               <div class="education__time"> 
                 <span class="education__rounder"></span> 
                 <span class="education__line"></span> 
               </div> 
  
               <div class="education__data bd-gid"> 
                 <h3 class="education__title">Web Developer Bootcamp</h3> 
                 <span class="education__studies">ABC Technology Training</span><br> 
                 <span class="education__year">2022 - 2023</span> 
               </div> 
             </div> 
  
             <div class="education__content"> 
               <div class="education__time"> 
                 <span class="education__rounder"></span> 
                 <!-- <span class="education__line"></span> --> 
               </div> 
  
               <div class="education__data bd-gid"> 
                 <h3 class="education__title">B-Tech in Computer science engineering</h3> 
                 <span class="education__studies">Gates Institute of technology</span><br> 
                 <span class="education__year">2021- 2024</span> 
               </div> 
             </div> 
           </div> 
         </section> 
  
         <!-- ========   SKILLS    =======  --> 
  
         <section class="skills section" id="skills"> 
           <h2 class="section-title">Skills</h2> 
           <div class="skills__content bd-grid"> 
  
  
             <ul class="skills__data"> 
               <li class="skills_name"> 
                 <span class="skills__circle"></span> Java 
               </li> 
               <li class="skills_name"> 
                 <span class="skills__circle"></span> Spring 
               </li> 
               <li class="skills_name"> 
                 <span class="skills__circle"></span> 
               </li> 
               <li class="skills_name"> 
                 <span class="skills__circle"></span> Python 
               </li> 
             </ul> 
  
             <ul class="skills__data"> 
               <li class="skills_name"> 
                 <span class="skills__circle"></span> HTML 
               </li> 
               <li class="skills_name"> 
                 <span class="skills__circle"></span> CSS 
               </li> 
               <li class="skills_name"> 
                 <span class="skills__circle"></span> Bootstrap 
               </li> 
               <li class="skills_name"> 
                 <span class="skills__circle"></span> Java Script 
               </li> 
             </ul> 
  
           </div> 
  
         </section> 
  
  
  
  
       </div> 
  
       <div class="resume__right"> 
         <!-- ========   EXPERIENCE    =======  --> 
         <section class="experience section" id="experience"> 
  
           <h2 class="section-title">Experience</h2> 
           <div class="experience__container bd-grid"> 
  
             <div class="experience__content"> 
  
               <div class="experience__time"> 
                 <span class="experience__rounder"></span> 
                 <span class="experience__line"></span> 
               </div> 
  
               <div class="experience__data bd-grid"> 
                 <h3 class="experience__title">PRESENT I'M STUDENT</h3> 
                 <span  
</span> 
                 <p </p> 
               </div> 
  
             </div> 
  
             <div 
                 <span  
                 <!-- <span  --> 
               </div> 
  
               <div 
                   NoSQL</p> 
               </div> 
             </div> 
  
  
           </div> 
  
  
         </section> 
        
         
             <div  
                 
               </ul> 
             </div> 
           </div> 
         </section> --> 
  
  
         <!-- ========   LANGUAGES    =======  --> 
         <section class="languages section" id="languages"> 
           <h2 class="section-title">Languages</h2> 
           <div class="languages__container"> 
             <ul class="languages__content bd-grid"> 
               <li class="languages__name"> 
                 <span class="languages__circle"></span> TELUGU
               </li> 
               <li class="languages__name"> 
                 <span class="languages__circle"></span> English 
               </li> 
             </ul> 
           </div> 
         </section> 
  
         <!-- ========   INTERESTS    =======  --> 
         <section class="interests section" id="interests"> 
           <h2 class="section-title">Interests</h2> 
  
           <div class="interests__container bd-grid"> 
  
             <div class="interests__content"> 
               <i class='bx bx-book interests__icon'></i> 
               <span class="interests__name">Reading</span> 
             </div> 
             <div class="interests__content"> 
               <i class='bx bx-coin interests__icon'></i> 
               <span class="interests__name">Numismatics</span> 
             </div> 
             <div class="interests__content"> 
               <i class='bx bx-headphone interests__icon'></i> 
               <span class="interests__name">Music</span> 
             </div> 
  
  
  
  
           </div> 
         </section> 
  
  
  
  
  
  
  
       </div> 
  
  
     </div> 
  
  
  
   </main> 
  
   <!-- ========   Scroll top   =======  --> 
   <a href="#" class="scrolltop" id="scroll-top"> 
     <i class='bx bx-up-arrow-alt scrolltop_icon'></i> 
  
   </a> 
  
  
   <!-- ========   HTML 2 pdf   =======  --> 
   <script src="./assets/js/html2pdf.bundle.min.js"></script> 
  
   <!-- ========   main.js    =======  --> 
   <script src="assets/js/main.js"></script> 
 </body> 
  
 </html> Portfolio
