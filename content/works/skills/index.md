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
        <div class="skill-item" >HTML/CSS</div> 
        <div class="skill-item">JavaScript</div> 
        <div class="skill-item">React</div> 
        <div class="skill-item">Node.js</div> 
    </div>
</div>


<div class="skills-section"> 
    <h2>Back-end</h2> 
    <div class="skills-grid"> 
        <div class="skill-item">
            <span class="skill-item-text">I work on Python for data science projects and regularly when I want to write something in, maybe pseudo-pseudo code :D
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
        <div class="skill-item">AWS</div> 
        <div class="skill-item">Terraform</div>
        <div class="skill-item">Docker</div>
        <div class="skill-item">Git</div>  
        <div class="skill-item">Linux</div> 
        <div class="skill-item">Jenkins</div>
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
  }
    .skill-item:hover .skill-item-text {
    visibility: visible;
  }
 



</style>

