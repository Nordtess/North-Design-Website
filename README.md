<div align="center">

# 🧠 North Design
A stylistic, mobile-first business website built with a clean black and white art theme.

</div>

## 💡 Description
This project was developed during a university frontend course for an imaginary company named North Design. It demonstrates robust frontend architecture using vanilla HTML, CSS, and JavaScript.

**My primary contributions to this group project include:**

* **Core Design & Grid System:** Establishing the basic look with a clean, stylistic black-and-white theme and creating the entire template for the CSS grid system.
* **Message Board Logic:** Implementing the user message board functionality, including real-time input validation with visual feedback (red/green glow) and preventing form submission using `event.preventDefault()` based on error state.
* **File Organization:** Structuring the project files according to modular, good-practice conventions.
* **Advanced JavaScript:** Implementing complex JavaScript animations on my individual employee page, such as a custom mouse-tracking circle (demonstrating dynamic client-side event handling) and animating project elements.
* **Data Handling:** Utilizing **AXIOS** to read and handle dynamic project data from a JSON file for the project handler.

---

## 🧰 Tech Stack

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="40" height="40" alt="HTML5" title="HTML5"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="40" height="40" alt="CSS3" title="CSS3"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="40" height="40" alt="JavaScript" title="JavaScript"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/axios/axios-plain.svg" width="40" height="40" alt="Axios" title="Axios"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/json/json-original.svg" width="40" height="40" alt="JSON" title="JSON"/>
</p>

---

## 🎥 Demo (YouTube)

<p align="center">
  YouTube video showcasing the fullscreen version.
</p>
<p align="center">
  <a href="https://youtu.be/t7yqqDNMaSw" target="_blank">
    <img src="/images/GitHub-Images/uni-website-yt2.png" alt="Watch the video" width="500" height="500">
  </a>
</p>

---

## 🖼️ Screenshots

<p align="center">

  <img src="/images/GitHub-Images/uni-website1.png" alt="Preview" width="800">

</p>



<p align="center">

  The homepage of the website (index.html) with the presentation of the company.

</p>



<p align="center">

  <img src="/images/GitHub-Images/uni-website3.png" alt="Preview" width="800">

</p>



<p align="center">

  The user message board using real-time validation, when the user is hovering over the submit button,

  if the fields are incorrectly filled out or if the fields are empty, it will both light up with a redish-glow to show the user that

  the message can't be sent and give different messages below the fields depending on the error. Using JavaScript the data won't be sent using <code>event.preventDefault();</code>.

</p>



<p align="center">

  <img src="/images/GitHub-Images/uni-website4.png" alt="Preview" width="800">

</p>



<p align="center">

  When all fields are correctly filled out, when hovering over the submit button, it will show a green light,

  showcasing for the user that the message now can be sent. 

</p>



<p align="center">

  <img src="/images/GitHub-Images/uni-website2.png" alt="Preview" width="800">

</p>



<p align="center">

  The employee presentation page that will take the user to their individual pages.

</p>



<p align="center">

  <img src="/images/GitHub-Images/uni-website6.png" alt="Preview" width="800">

</p>



<p align="center">

  The employee (mine) page of Jamie, using a lot of JavaScript animations and events, for example the circle tracking the mouse live, animated bars, a slideshow of images and

  also a project handler using AXIOS to read JSON data.

</p>



<p align="center">

  <img src="/images/GitHub-Images/uni-website-mobile.png" alt="Preview" width="800">

</p>



<p align="center">

  The mobile version with a standard hamburger menu for the links, automatically changes to mobile version when the screen width goes < 800px.

  Alot of the JavaScript code and animations are either customized or removed for the mobile version, for example the light around the submit button on the user message board

  always show a red or green light the moment the user starts giving input since there is no hovering on mobile-phones or tablets.

</p>

---

## ⚙️ Installation

```bash
# Clone the repository
git clone [https://github.com/Nordtess/](https://github.com/Nordtess/)[repository-name]

# Navigate into the project folder
cd [repository-name]

# Open index.html in your browser or use the Live Server VS Code extension.
