# 3-column-preview-card-component-main

3-column preview card component solution
This is a solution to the 3-column preview card component challenge on Frontend Mentor.

Table of contents
Overview
The challenge
Screenshot
Links
My process
Built with
What I learned
Continued development
Useful resources
Author
Overview
The challenge
Users should be able to:

View the optimal layout depending on their device's screen size
See hover states for interactive elements
Screenshot
Links
Solution URL: Add solution URL here
Live Site URL: Add live site URL here
My process
Built with
Semantic HTML5 markup
Desktop-first workflow
CSS
What I learned
I learned and recapped on column layouts and the hover state in CSS. Also, apply fonts using font family.

To see how you can add code snippets, see below:

<div class="column suvsColor">
    <div class="card">
      <img src="/images/icon-suvs.svg" alt="SUV" >
      <div class="container">
        <h4 class="title"><b>SUVs</b></h4>
        <p class="a">Take an SUV for its spacious interior, power, and versatility. Perfect for your next family vacation 
          and off-road adventures.</p>
      </div>
      <button class="button button2"> Learn More </button>
    </div>
  </div>
.button{

    color: rgba(0,0,0,0.3);
    background-color: hsl(0, 0%, 95%);     
    padding: 8px;
    transition-duration: 0.4s;
    cursor: pointer;  
    border-style: solid; 
    
}

.button1{

    color:hsl(31, 77%, 52%);
    background-color: white;
    border: 12px;   
    border-color: aliceblue;
    border-radius: 18px;  
    
}

.button1:hover {

    color: white; 
    background-color: hsl(31, 77%, 52%);
    border: 1px;   
    border-color: white;
    border-radius: 18px;
    border-style: solid;
 }
Continued development
CSS Media Queries.

Useful resources
Example resource 1 - This helped me set out the columns. I really liked this pattern and will use it going forward.
Author
Website - Stephen Pino
Frontend Mentor - @RoadHog31
