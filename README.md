
<h3 align="center">La La Land Note Clicker</h3>

  <p align="center">
    plays La La Land songs with every click!
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<p> This project is a static website designed around with the theme of La La Land, my favorite musical. If you enjoy listening to heartfelt melodies while admiring a beautiful night sky, you have come to the right place! I designed this website to be visually serene and relaxing. The top of the page features a starry tapestry, and as you begin to scroll down, the colors seamlessly transition, gently softening into a palette of muted blues and purples, as if the day is slowly giving way to twilight.	Finally, as you reach the bottom of the page, a stunning skyline image of Los Angeles comes into view, bathed in the moon's soft glow. Try clicking for a sweet surprise!</p>


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

Designed with your mental well-being in mind, this site serves as a sanctuary for relaxation and rejuvination. My aim is to provide a serene space where you can escape the daily stresses of daily life and find solace in tranquility.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [ ] Music Feature
    - [ ] This site features two playable songs: Another Day of Sun and City of Stars. For each song, pathways to audio files of individiual piano notes are compiled in an array. A click event listener waits for any click to the body and creates and plays a new audio file with the pathway. Then a counter increases in value by 1 to play the next note. Once the song is completed, counter is reset to playback the song. The two song title paragraph elements in the header change a boolean from true to false to change which array is being grabbed from.
- [ ] Image Transition Feature
    - [ ] At the bottom of the page, an image of Los Angeles rests below the page out of visibility. A scroll event listener waits until the bottom of the page is reached, then adds a the 'visible' class to the image that creates a smooth transition onto the page.
- [ ] Star Background Feature
    - [ ] To create the star effect, I used an content loaded event listener that activates every time the page is visited or refreshed. What it does is create different number of stars to be contained in three equally sized containes spanning down the page. The function addStars creates as many white divs as number of stars needed and randomly positions them in their container. Another function addClass changes the size of the stars randomly based on the parameters to create the gradient effect of size of stars.  

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - Carson Bates - carson.d.bates.27@dartmouth.edu

Project Link: [https://github.com/carsonbates913/La_La_Land](https://github.com/carsonbates913/La_La_Land)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
