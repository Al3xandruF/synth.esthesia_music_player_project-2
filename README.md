 <div style="color: #FF7C00; font-size: 2rem; font-weight: bold; text-align: center">
 - Synth.Esthesia Music Player -</div>
 <br>
 <br>

<div style="text-indent: 2rem">The <span style="font-weight: bold;">Synth.Esthesia Music Player</span> is designed to be a shareable music platform. The concept behind it is simple: For the users to be able to store their own favourite songs into one place, access them from all type of devices and share their playlists with other users on the platform.</div>

![main page](/assets/readme_screenshots/screeRes_all_devices.png)

## **Contents**
---

- User Experience (UX)
    - Project Information and Goals
- Design
    - Color Scheme
    - Typography
    - Imagery
- Features
- Technologies Used
    - Languages Used
    - Frameworks, Libraries and Programs Used
- Deployment Processes
    - GitHub Deployment
    - Local Deployment:
        - How to Fork
        - How to Clone
- Testing

### **User Experience (UX)**
---

**Project Information and Goals:**

**Synth.Esthesia Music Player** is a community based project in progress, ultimately being implemented into a larger full stack application in the future with much more functionality added.As well, plans are to make this a downloadable mobile app so users of this community will stay better connected.

**The website will contantly improve on UX such as:**

- Intuitive and easy interaction with the Music Player's features.
- Search bar for songs will be added.
- Appearance features will be implemented frequently.

## **Design**
---

**Color Scheme**

The tool used for applying the colors for the player is Adobe - Color Wheel.

**Colors used:**

- Monochromatic Dark Blue for the title, artist name and player controls.
- Monochromatic Pink for the song title and dynamic progress bar
- Monochromatic Red for transition in/out on hover.
- Monochromatic Orange for the static progress bar.
- Monochromatic Grey for adjust-volume bar.
- Default Black for timing and volume title.

![colors used](/assets/readme_screenshots/adobe_color_wheel.png)

## **Typography**
---

Google Fonts was used to import the fonts for Website.

The font package used:

- Audiowide: For the main content of the Music Player.
- Bunge Shade: For future use on the page.
- Space Mono: For future use on the page.

![google fonts](/assets/readme_screenshots/google_fonts.png)

## **Features**
---

The website is comprised of a responsive single page, with the following:
<br>

A cassette-type favicon in the browsing tab:
<br>

![favicon](/assets/readme_screenshots/favicon.png)
<br>
<br>

A background wallpaper, the music player itself and it's futures:
<br>

![main page](/assets/readme_screenshots/player_main_page.png)
<br>
<br>

The music player is comprised with the following:

- The title itself, which is inspired by the neurological condition: Synesthesia<a href="https://www.healthline.com/health/synesthesia" target="_blank">(click for more info).</a>

![title](/assets/readme_screenshots/title_player.png)
<br>
<br>

- The cover image with 'hover' and 'box-shadow' applied for the float effect:

![cover](/assets/readme_screenshots/cover.png)
<br>
<br>

- The name of the song and artist:

![song and artist](/assets/readme_screenshots/artist_song.png)
<br>
<br>

- The music player controls: progress bar, volume, play/pause and previous/next.

![controls](/assets/readme_screenshots/player_controls.png)
<br>
<br>

## **Technologies Used**
---

Languages used:

- HTML, CSS and JavaScript were used on creating this Website Music Player:
  - HTML for the basic text layout.
  - CSS for styling and basic interaction.
  - Javascript for the Music Player's interactive controls.
<br>
<br>

## **Music Player Controls and User Interaction**
---

- JavaScript was used for the following:
  - Play/Pause function.
  - Previous/Next function.
  - Volume bar adjustment.
  - Progress bar/ timing adjustment.
  - Changing the artist cover.
<br>
<br>

- User Interaction:
  - The user can play/pause or change a song by clicking previous/next buttons.
  - The user can decide if it wants to adjust the volume or dive within a particular song by changing the timing within the progress bar.
  - The timing within the progress bar adjusts as well, reflecting the correct time within a particular song.
  - Each song has it's own cover linked to it so when the user decides to change a song (either backwards or forward in the playlist), this will change accordingly.

![transition in_out](/assets/readme_screenshots/transition_in_out.png)
<br>
<br>

**Frameworks, Libraries and Programs Used**

- Printed Sneakpeekit Browser Grid for hand drawing sketches.
- Git for version control.
- Github for saving and storing the files for the website.
- Google Dev Tools: for troubleshooting the css/ javascript code.
- Console.log within js file for making sure the code works as intended.
- Google Fonts: importing the fonts used across the website.
- Font Awesome: for the music player icons.
- Favicon: to create the website's favicon.
- Am I Responsive: to show the website responsiveness on multiple devices.

## **Deployment and Local Development**
---

**Deployment**

The site is deployed using Github Pages.

The process for deployment using Github Pages is as following:

1. Login (or sign up) to Github.
2. Go to the project's repository on the left page.
3. Click the **settings** button.
4. Select **Pages** in the left hand navigation menu.
5. From the source dropdown select **main branch** and press **save**.
6. Deployment finished. Please note the deployment process may take several minutes before the site goes live.

**Local Development:**

To **fork** the repository you need to:

1. Log in (or sign up) to Github.
2. Go to the repository for this project.
3. Click the **fork** button in the top right corner.


To **clone** the repository you need to:

1. Log in (or sign up) to Github.
2. Go to the repository for this project.
3. Click on the code button and select the option you would like to clone with:
    - HTTPS
    - SSH
    - Github CLI
4. Copy the link shown related to your chosen option.
5. Open the terminal in your code editor.
6. Change the current working directory  to the location you want to use for the cloned directory.
7. Type **git clone** inside the terminal and then **paste** the link you copied in step 3.
8. Press Enter.

## **Testing**
---

### **Automated Testing**
<br>

- HTML
  - No errors were returned when testing the code on the official W3C validator.

![html validator](/assets/readme_screenshots/html_validator_check.png)
<br>
<br>

- CSS
  - No errors were returned when testing the code on the official CSS validator.

![css validator](/assets/readme_screenshots/css_validator_check.png)

 - JavaScript
   - No errors were found when testing the JS code on the JSHint validator and the following metrics were returned:
     - 9 functions in this file.
     - Function with the largest signature takes 1 argument, while the median is 0.
     - Largest function has 15 statements in it, while the median is 4.
     - The most complex function has a cyclomatic complexity value of 5, while the median is 2.

![JS validator](/assets/readme_screenshots/JSHint_validator_check.png)

- Lighthouse
  - Testing was carried out with Lighthouse for checking the quality of the web page.

![lighthouse testing](/assets/readme_screenshots/lighthouse_test_check.png)
<br>
<br>

### **Manual Testing**
---

- Cross-Browser Testing
 - The website behaves as expected on all major browsers like: Chrome, Firefox, Safari, Opera.






























