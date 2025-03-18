---
title: "Skill Overview"
draft: false
ShowReadingTime: false
description: " "
summary: " "
--- 


<div class="skills-section"> 
    <h2>Front-end</h2> 
    <div class="skills-grid"> 
        <div class="skill-item" onclick= " " >HTML/CSS
        <span class="skill-item-text">I have used HTML/CSS both in industry and in school. This part of my website was actually written by me from scratch in HTML/CSS. I wrote a portfolio using the raw HTML/CSS/Js tech stack, but this current site was using Hugo with custom modifications and is admittedly an improvement.
            </span> </div> 
        <div class="skill-item">JavaScript
        <span class="skill-item-text">I learned JavaScript throughout my software engineering class and wrote many apps using JavaScript throughout my industry experience.
            </span></div> 
        <div class="skill-item">React
                <span class="skill-item-text">I was going to write this website as a React App, but wanted to go for a simpler route. I have contributed to apps for school (a restraunt POS system), and in industry (an analytics dashboard) using React. 
            </span></div> 
        <!-- <div class="skill-item">Node.js</div> 

   <!-- > </div> -->
</div>


<div class="skills-section"> 
    <h2>Back-end</h2> 
    <div class="skills-grid"> 
        <div class="skill-item">
            <span class="skill-item-text"> I have used Python for my competitive programming class and for some personal projects. 
            </span> 
            Python 
        <!-- <span class="skill-item-text">Tooltip text</span> -->
        </div> 
        <div class="skill-item">
            <span class="skill-item-text">
                I looked at a lot of Go code throughout industry experience and took some time to learn it on my own. I plan on writing my discord file system in Go. 
            </span> 
            Go
        </div>
        <div class="skill-item">
            <span class="skill-item-text">
                Texas A&M teaches many of beginner programming classes (strangely enough) starting from C/C++. As a matter of fact, C++ is the first programming langauge I learned. The creator of C++ taught at A&M.
            </span> 
            C/C++
        </div>  
        <div class="skill-item">
            <span class="skill-item-text">
                I started learning Java in industry, but it was also introduced in class at various points.
            </span> 
            Java</div> 
        <div class="skill-item">
            <span class="skill-item-text">
            I learned Lua when creating plugins for industry services. It seems to be a language popular for "modding". 
            </span> 
        Lua</div> 
        <div class="skill-item">SQL
            <span class="skill-item-text">
            I learned SQL in industry and in school and used it in both a web-dev setting and in a data analytics environment
            </span> 
        </div> 
    </div> 
</div>

<div class="skills-section"> 
    <h2>Developer Technologies</h2> 
    <div class="skills-grid"> 
        <div class="skill-item">AWS 
            <span class="skill-item-text">
            A significant amount of software I have written as ended up running in the cloud.. or *a* cloud. I have the AWS Cloud Practitioner Certification and am interested in getting another certification if I have the time.
            </span> 
            </div>
        <div class="skill-item">Terraform
        <span class="skill-item-text">
            I used Terraform plenty throughout my industry experience.
            </span> 
            </div>
        <div class="skill-item">Docker
        <span class="skill-item-text">
        Docker is a technology I have used here in there as it comes up in my career. I want to learn it more in the future, but can use it's basic functionality as it shows up.
            </span>
             </div>
        <div class="skill-item">Git 
        <span class="skill-item-text">
            Git is a skill that I made a point to learn in-depth recently as it seems very useful in any type of software engineering setting.
            </span> 
        </div>
        <div class="skill-item">Linux
        <span class="skill-item-text">
            Linux is a technology that has popped up constantly in my career as it seems to be a favorite as a software engineering operating system.
            </span> 
            </div> 
        <div class="skill-item">Jenkins
        <span class="skill-item-text">
            I used Jenkins plenty throughout industry experience. For those who are looking at this and don't know what Jenkins is, it's a CI/CD pipeline that is meant for integrating and deploying safe code in larger environments/organizations.
            </span> 
            </div>
    </div> 
</div>

<style>
.skills-section {
    max-width: 800px;
    margin: 50px auto;
    padding: 20px;
    /* background-color: var(--theme); */
    /* background-color: #fff; */
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}
.skills-section h2 {
    text-align: center;
    font-size: 2em;
    margin-bottom: 20px;
}
.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 20px;
}
.skill-item {
    position:relative;
    box-shadow:0 2px 8px rgba(0, 0, 0, 0.1);
    background-color: var(--entry);
    color: var(--content);
    padding: 15px;
    text-align: center;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}
 .skill-item-text {
  position: relative;
  display: inline-block;
  border-bottom: 1px dotted black;
  padding: 10px;
}
  
.skill-item:hover {
    background-color: #005bb5;
}
 /* Tooltip text */
  .skill-item .skill-item-text {
    visibility: hidden;
    min-width: 100%;
    min-height: 100%
    width: auto;
    height: auto;
  /* min-width: 120px; */
  /* max-width: 5000 */
   /* white-space: nowrap; */
  background-color: var(--primary);
  color: var(--tertiary);
  text-align: center;
  border-radius: 6px;
  border-color: var(--border)
  padding: 5px 0;
  position: absolute;
  z-index: 1;
  top: -20%;
  left: 75%;
  }

  .skill-item .skill-item-text::after {
      content: "";
  position: absolute;
  top: 12.5%;
  right: 100%;
  margin-top: -5px;
  border-width: 5px;
  border-style: solid;
  border-color: transparent black transparent transparent;
  padding: 10px;
  }
    .skill-item:hover .skill-item-text {
    visibility: visible;
    padding: 10px;
  }
 



</style>

