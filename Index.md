# Name
# Headshot (Photo)
# Job Title or Desired Title (Web and Mobile Applications Developer)
# Job or Desired Job Summary
# Contact Fields (Email, Phone, Social Media)

# Education
# Previous Job Experience
# Skills

# Featured Projects
# Portfolio
# Case Studies

# Licenses and Certifications
# Courses Taken
# Internships
# Volunteer Work

# Publications and Patents
# Honors and Awards
# Test Scores
# Languages
# Organizations, Clubs, Teams, Athletics, Causes, Charities




<style>

.accordion {
  max-width: 500px;
  border: 1px solid #1c1c1c;
  border-bottom: none;
}

.accordion:last-child {
  border-bottom: 1px solid #1c1c1c;
}

.accordion-header {
  display: flex;
  padding: 16px;
  cursor: pointer;
  background-color: #93bd20;
}

.accordion-title {
  flex: 1;
}

.accordion-icon: {
  width: 16px;
}

.accordion-content {
  padding: 16px;
}

.accordion-content {
  display: none;
}


</style>



<section id="Classes I've Taken">

<h2>Technology Classes completed</h2>

<div class="accordion">
    <div class="Header">
      <div class="Title">CLass #1 - <strong>Digital Forensics</strong></div>
      <span class="Icon">+</span>
    </div>
    <div class="Content">
        <ul>
          <h1>What I did in this class:</h1>

          <li>Learned how to Investigate a Image file</li>
          <li>How to pull evidence from a file</li>
          <li>Used FTK Imager, Axiom, and other forensic tools</li>

        </ul>
    </div>
</div>

<div class="accordion">
    <div class="Header">
      <div class="Title">Class #2 - <strong>CyberSecurity Operations</strong></div>
      <span class="Icon">+</span>
    </div>
    <div class="Content">
      <ul>
        <h1>What I did in this class:</h1>

        <li>Learned types of attacks on computers</li>
        <li>Now have a good understanding of how this class and cloud computing are closely intertwined</li>
        <li>Had great teacher who was well diversed and gave real life examples</li>

      </ul>
    </div>
</div>

<div class="accordion">
    <div class="Header">
      <div class="Title">Class #3 - <strong>Python</strong></div>
      <span class="Icon">+</span>
    </div>
    <div class="Content">
      <ul>
        <h1>What I did in this class</h1>

        <li>Learned the basic commands of Python</li>
        <li>I was able to learn how to problem solve and analyze intricute coding</li>
        <li>In the end I was able to build the game Snake!</li>

      </ul>
    </div>
</div>


</section>


<script>

const accordionHeaders = document.getElementsByClassName('Header');
const accordionContents = document.getElementsByClassName('Content');
const accordionIcons = document.getElementsByClassName('Icon');

for (let i = 0; i < Headers.length; i++) {
  Headers[i].addEventListener('click', () => {
    Contents[i].style.display = Contents[i].style.display == 'block' ? 'none' : 'block';
    Icons[i].innerHTML = Contents[i].style.display == 'block' ? '-' : '+';
  });
}

</script>







<h2>About</h2>

<script type="text/javascript">

let pageView = 0;
let siteTitle = "MikeyBoyle.com"
let pageTitle = 'Learn About Me!';
let pageAuthor = 'Mike BOyle';

function pageTitles() {

  document.write(pageTitle);
}


function pageAuthors() {
  document.write(pageAuthor);
}


function pageViews() {
  pageView++;
  document.write(pageView);
}


pageTitles();
pageAuthors();
pageViews();



</script>

<h1 class="page-title"><script>pageTitles();</script></h1>
<p>by: <script>pageAuthors();</script></p>
<small><script>pageViews();</script></small>

<h2>Portfolio</h2>

<h2>Contact</h2>
