<a id="readme-top"></a>


<br />

<!--
Code attribution:
For this ReadMe this is the template I used:
othneildrew., 2024. Best-README-Template (version 1.1.2) [Source code]. Available at:< https://github.com/othneildrew/Best-README-Template.git> Accessed 26 April 2025].
 -->

<!-- Project Heading -->


<h3 align="center">PokeQuest.</h3>

<p align="center">
  <a href="https://github.com/ST10290935/PokemonGone6_Final_APK_V7.git"><strong>Explore the Docs »</strong></a>
  <br />
  <br />
  <a href="https://github.com/ST10290935/PokemonGone6_Final_APK_V7.git">View Demo</a>
  ·
  <a href="https://github.com/ST10290935/PokemonGone6_Final_APK_V7.git/issues">Report Bug</a>
  ·
  <a href="https://github.com/ST10290935/PokemonGone6_Final_APK_V7.git/issues">Request Feature</a>
</p>


  


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contributors">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
   
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

 <p align="center">
  <img src="https://github.com/user-attachments/assets/a107be7e-3084-4c39-8760-bd84a0b4a69f" alt="Logo" style="width: 170px; height: 170px; border-radius: 50%; object-fit: cover; border: 2px solid #ddd;">
</p>


PokeQuest is an immersive exploration and collecting experience that brings the thrill of discovery to your mobile device. Players can explore a dynamic world, track nearby creatures, and capture them to build their personal collection. With intuitive controls and an interactive map, every step you take could lead to encountering a rare or powerful creature. Whether you’re casually exploring or striving to complete your collection, this game offers an engaging and rewarding adventure for all players.

## Features
<details> <summary style="font-weight: bold;">Explore the world and discover creatures</summary> <p>Move around the in-game world and encounter wild creatures that appear randomly around you. Each area holds new surprises—rare, legendary, or even hidden creatures waiting to be found.</p> </details> <details> <summary style="font-weight: bold;">Capture and collect creatures</summary> <p>Engage with wild creatures and capture them to expand your collection. Every captured creature is stored in your in-game encyclopedia, where you can view their details and stats.</p> </details> <details> <summary style="font-weight: bold;">Augmented Reality encounters</summary> <p>Enable AR mode to see creatures appear through your phone’s camera as if they exist in the real world. Walk around, aim your device, and discover creatures right before your eyes.</p> </details> <details> <summary style="font-weight: bold;">Directional guidance and nearby alerts</summary> <p>Get real-time alerts and hints when new creatures appear nearby. The system guides you toward the correct direction, making exploration more interactive and exciting.</p> </details> <details> <summary style="font-weight: bold;">Build your personal encyclopedia</summary> <p>Every creature you capture is added to your encyclopedia. View their names, images, and stats, and try to complete your full collection by discovering them all.</p> </details> <details> <summary style="font-weight: bold;">Customize your avatar and map</summary> <p>Personalize your in-game character with custom avatars and explore the map in different themes or styles to match your playstyle.</p> </details>

## What we added
<details>
  <summary style="font-weight: bold;">🕶️ Augmented Reality (AR) Capture Mode</summary>
  <p>We implemented a fully functional AR Capture Mode that allows players to view and interact with creatures through their phone's camera, simulating real-world encounters.</p>
  <ul>
    <li>Players can toggle AR mode directly from the main interface using the AR Button.</li>
    <li>When activated, the app uses the device's camera feed as a background and overlays creature images in the environment.</li>
    <li>Players can tap or interact with these AR creatures to capture them just like on the main map.</li>
    <li>This mode works independently of map location, allowing immersive gameplay in any setting.</li>
  </ul>
  <p><strong>Enhancement Added:</strong> The AR system is lightweight and flexible, making it easy to extend with future 3D creature models or animations.</p>
</details>

<details>
  <summary style="font-weight: bold;">🎯 Gamification & Progression System</summary>
  <p>To promote activity and engagement, we introduced a step-based progression system tied to the device's movement sensors.</p>
  <ul>
    <li>The app tracks the player's real-world steps and updates an on-screen counter in real time.</li>
    <li>Players can earn experience points (XP) or rewards for walking or exploring, encouraging physical activity.</li>
    <li>A leaderboard system is under development to allow friendly competition among players, showcasing top explorers and collectors.</li>
  </ul>
  <p><strong>Enhancement Added:</strong> The game dynamically rewards players based on movement patterns, laying the foundation for achievements, badges, and daily goals in future updates.</p>
</details>

<details>
  <summary style="font-weight: bold;">🧍‍♂️ Customizable Avatars & Profiles</summary>
  <p>Players can now personalize their in-game presence with custom avatars and player information.</p>
  <ul>
    <li>The app provides a profile card at the bottom of the screen showing the player's name, avatar image, and step count.</li>
    <li>Users can update their details through the Settings screen, with future support planned for avatar selection and outfit customization.</li>
    <li>This system supports persistent data, ensuring that player information is retained across sessions.</li>
  </ul>
  <p><strong>Enhancement Added:</strong> The modular profile system allows easy expansion for themes, cosmetic upgrades, and linked achievements.</p>
</details>

<details>
  <summary style="font-weight: bold;">🔄 Offline Catch & Sync Mode</summary>
  <p>We designed the game to be playable even without an internet connection.</p>
  <ul>
    <li>Creature data and captured collections are stored locally using RoomDB, ensuring players can catch and view creatures offline.</li>
    <li>Once connectivity is restored, data can be synced with the server or backed up automatically to preserve progress.</li>
    <li>This feature guarantees uninterrupted gameplay regardless of network availability.</li>
  </ul>
  <p><strong>Enhancement Added:</strong> The local database architecture also enables smoother transitions between online and offline play, reducing lag and data loss.</p>
</details>

<details>
  <summary style="font-weight: bold;">🌍 Additional Improvements</summary>
  <p>Beyond the planned features, our implementation includes several unexpected upgrades that enhance user experience:</p>
  <ul>
    <li><strong>Dynamic Creature Spawning System</strong> — Creatures now spawn randomly around the player's location over a wider radius for better exploration balance.</li>
    <li><strong>Directional Guidance</strong> — The app provides compass-based hints and directional arrows to help locate nearby creatures.</li>
    <li><strong>Expanded Encyclopedia</strong> — A full in-game creature index tracks all captured and discovered creatures, with rich visual details.</li>
    <li><strong>Polished UI/UX Design</strong> — Enhanced button placement, responsive layouts, and consistent visual theming for an immersive experience.</li>
  </ul>
</details>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Application Preview

<p align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/8c5dfb30-5456-461e-9b42-e6405ffe5ee8" alt="Screenshot 1" width="200"><br>
        <sub>🔐 Register</sub>
      </td>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/96789cc5-057b-47d8-bed9-251ea980dfd2" alt="Screenshot 2" width="200"><br>
        <sub>🔐 Login </sub>
      </td>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/d21bc3d9-db51-4696-b73a-1c0ebbc508c3" alt="Screenshot 3" width="200"><br>
        <sub>📊 Main Screen</sub>
      </td>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/e5602826-e756-4646-93b6-ef4bb40f7040" alt="Screenshot 4" width="200"><br>
        <sub>🥅 Captured</sub>
      </td>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/87ca905a-b8d9-4c07-a3ec-f138c06731ea" alt="Screenshot 5" width="200"><br>
        <sub>📖 CreatureDex</sub>
      </td>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/1354d64b-f6fc-4c01-8bd4-f8d92807be71" alt="Screenshot 6" width="200"><br>
        <sub>🕶️ AR</sub>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/b8c16cfc-de29-4ac1-ac68-6fd85f496ef1" alt="Screenshot 7" width="200"><br>
        <sub>⚙️ Settings</sub>
      </td>
      <td></td>
    </tr>
  </table>
</p>

## REST API GitHub Link

https://github.com/ST10290935/pokemon-api2.git

## Render REST API URL

https://pokemon-api2-hfpx.onrender.com/creatures
   
### YouTube Link

https://youtu.be/B17f7LfqxJQ

### Built With

[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white)](https://firebase.google.com/)
[![Room Database](https://img.shields.io/badge/Room-Database-00796B?style=for-the-badge)](https://developer.android.com/training/data-storage/room)
[![Chart Library](https://img.shields.io/badge/Chart-Library-4CAF50?style=for-the-badge)](https://github.com/PhilJay/MPAndroidChart)
[![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)](https://www.sqlite.org/)


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

To get a local copy of the project running, follow these steps.

### Prerequisites

- Android Studio

- Firebase account for data storage

- Kotlin-enabled Android project 

- Basic knowledge of Kotlin and Android development

- Gradle setup
  
- Firebase SDK setup in the project 

- Room Database setup
### Installation

1. Clone the repository
   ```sh
   git clone https://github.com/ST10143151/CashFlow_Latest.git
   
2. How to Run
<details>
  <div style="color: #333;">
    <p>Follow these steps to install and set up the <strong>PokeQuest</strong> app on your local machine:</p>
  <details>
      <summary style="font-weight: bold; color: #2196F3;">1. Clone the Repository</summary>
      <div style="color: #333;">
        <p>To get the source code, first clone the repository from GitHub:</p>
        <pre><code>git clone https://github.com/ST10290935/PokemonGone6_Final_APK_V7.git</code></pre>
        <p>This command will create a local copy of the repository on your machine. You can now navigate to the project folder.</p>
      </div>
    </details>

  <details>
      <summary style="font-weight: bold; color: #2196F3;">2. Open the Project in Android Studio</summary>
      <div style="color: #333;">
        <p>1. Launch <strong>Android Studio</strong>.</p>
        <p>2. In Android Studio, go to <strong>File</strong> → <strong>Open</strong>.</p>
        <p>3. Navigate to the folder where you cloned the repository (<strong>PokemonGone6_Final_APK_V7</strong>).</p>
        <p>4. Select the project folder and click <strong>OK</strong>. Android Studio will sync the project with Gradle.</p>
      </div>
    </details>

   <details>
      <summary style="font-weight: bold; color: #2196F3;">3. Install Dependencies</summary>
      <div style="color: #333;">
        <p>Once the project is opened, you need to install all the necessary dependencies and libraries for the app. Android Studio should automatically prompt you 
           to sync the project with Gradle. If this doesn't happen, follow these steps:</p>
        <p>1. In Android Studio, click <strong>File</strong> → <strong>Sync Project with Gradle Files</strong>.</p>
        <p>2. Wait for the Gradle build process to finish.</p>
        <p>This will download and install all required libraries and dependencies that are mentioned in the <strong>build.gradle</strong> files.</p>
      </div>
   </details>

   <details>
      <summary style="font-weight: bold; color: #2196F3;">4. Set Up Firebase</summary>
      <div style="color: #333;">
        <p>The app uses <strong>Firebase</strong> for data storage. Follow the steps below to configure Firebase:</p>
        <ol>
          <li>Go to the <a href="https://console.firebase.google.com/" target="_blank">Firebase Console</a>.</li>
          <li>Create a new project (or select an existing one).</li>
          <li>Follow the instructions to add an Android app to the Firebase project.</li>
          <li>Download the <strong>google-services.json</strong> file after configuring the Firebase project and add it to the <strong>app/</strong> directory of 
              your project in Android Studio.</li>
          <li>Make sure you have enabled the required Firebase services (e.g., Firestore, Firebase Authentication, etc.) depending on your needs.</li>
        </ol>
      </div>
   </details>

  <details>
      <summary style="font-weight: bold; color: #2196F3;">5. Set Up the Database</summary>
      <div style="color: #333;">
        <p>If your app uses <strong>Room Database</strong> for local storage, follow these steps to set it up:</p>
        <ol>
          <li>Make sure the Room dependency is included in your <strong>build.gradle</strong> file. If not, you can add the following to the 
          <strong>dependencies</strong> block:</li>
          <pre><code>implementation "androidx.room:room-runtime:2.3.0"
          kapt "androidx.room:room-compiler:2.3.0"</code></pre>
          <li>Sync the project again to install the Room library.</li>
        </ol>
      </div>
  </details>

  <details>
      <summary style="font-weight: bold; color: #2196F3;">6. Configure Android Emulator (Optional)</summary>
      <div style="color: #333;">
        <p>If you don't have an Android device connected to your computer, you can use an emulator to run the app. Follow these steps to set up an emulator:</p>
        <ol>
          <li>In Android Studio, go to <strong>Tools</strong> → <strong>Device Manager</strong>.</li>
          <li>Click on <strong>Create Virtual Device</strong>.</li>
          <li>Choose a device model and Android version to use.</li>
          <li>Follow the prompts to create and start the emulator.</li>
        </ol>
      </div>
  </details>

  <details>
      <summary style="font-weight: bold; color: #2196F3;">7. Run the Application</summary>
      <div style="color: #333;">
        <p>Once everything is set up, you can run the app by:</p>
        <ol>
          <li>Clicking the <strong>Run</strong> button (green triangle) in Android Studio.</li>
          <li>Choose your connected device or emulator.</li>
          <li>Wait for the app to build and launch.</li>
        </ol>
      </div>
  </details>

  <details>
      <summary style="font-weight: bold; color: #2196F3;">8. Verify Installation</summary>
      <div style="color: #333;">
        <p>After running the app, make sure to verify the following:</p>
        <ul>
          <li>The app should start without any errors.</li>
          <li>Firebase services (authentication, database) should be working as expected.</li>
          <li>Room Database (if used) should store and retrieve data correctly.</li>
        </ul>
      </div>
  </details>

  </div>
</details>

<!-- CONTRIBUTING -->

## Contributors

### Top Contributors

<p align="center">
  <a href="https://github.com/ST10248202" target="_blank">
    <img src="https://avatars.githubusercontent.com/u/128582074?v=4" width="80" height="80" style="border-radius: 50%;" alt="ST10248202"/>
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/ST10143151" target="_blank">
    <img src="https://avatars.githubusercontent.com/u/128127914?v=4" width="80" height="80" style="border-radius: 50%;" alt="ST10143151"/>
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/ST10290935" target="_blank">
    <img src="https://avatars.githubusercontent.com/u/128598477?v=4" width="80" height="80" style="border-radius: 50%;" alt="ST10290935"/>
  </a>
   &nbsp;&nbsp;
  <a href="https://github.com/ST10290935" target="_blank">
    <img src="https://avatars.githubusercontent.com/u/128413984?v=4" width="80" height="80" style="border-radius: 50%;" alt="ST10249644"/>
  </a>
</p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- CONTACT -->
## Contact

<div style="border: 2px solid #4CAF50; border-radius: 10px; padding: 20px; background-color: #f0f9f0; box-shadow: 2px 2px 12px rgba(0,0,0,0.1); text-align: center;">

  <h2 style="color: #4CAF50;">Team</h2>

  <table style="margin-left: auto; margin-right: auto; text-align: center; border-collapse: collapse;">
    <tr>
      <th style="padding: 10px; color: #333;">Name</th>
      <th style="padding: 10px; color: #333;">Student Number</th>
      <th style="padding: 10px; color: #333;">Email</th>
    </tr>
    <tr>
      <td style="padding: 10px;">Aiden Reddy</td>
      <td style="padding: 10px;">ST10290935</td>
      <td style="padding: 10px;">aidenreddyalt@gmail.com</td>
    </tr>
    <tr>
      <td style="padding: 10px;">Ananta Reddy</td>
      <td style="padding: 10px;">ST10143151</td>
      <td style="padding: 10px;">st10143151@vcconnect.edu.za</td>
    </tr>
    <tr>
      <td style="padding: 10px;">Dheyan Ramballi</td>
      <td style="padding: 10px;">ST10248202</td>
      <td style="padding: 10px;">dheyanramballi02@gmail.com</td>
    </tr>
    <tr>
      <td style="padding: 10px;">Shreya Dhawrajh</td>
      <td style="padding: 10px;">ST10249644</td>
      <td style="padding: 10px;">st10249644@vcconnect.edu.za</td>
    </tr>
  </table>

</div>


### References

Android Knowledge, 2023. RecyclerView in Android Studio using Kotlin | Android Knowledge. [video online] Available at: <https://youtu.be/UDfyZLWyyVM?si=XkKwy4-9apD5AZcW> [Accessed 7 April 2025].

AndroidWithShiv, 2023. Room Database | CRUD Operation in ROOM DB | Android Studio | JAVA | #android #java #database. [video online] Available at: <https://youtu.be/r-ua6f6LmJA?si=NtFoH1Z_Mng2GYrT> [Accessed 1 April 2025].

Canva, 2017. Purple and Pink Modern Bold Business Service Promotion Ads Video. [online] Available at: <https://www.canva.com/design/DAGmSOYchmA/HX7fOULb6qsX6JX10ZN9hw/edit?ui=eyJEIjp7IlEiOnsiQSI6dHJ1ZX19fQ> [Accessed 2 May 2025].

Codrikaz, 2022. How to Remove Status Bar | How to Change the Color of the Status Bar | Android Studio | codrikaz. [video online] Available at: <https://youtu.be/VnzwhgiBj_Q?si=3NEsndemuJ_p_OdX> [Accessed 26 April 2025].

Coding Meet, 2023. How to Store and Retrieve Images in Room Database | Android Studio Kotlin Tutorial. [video online] Available at: <https://youtu.be/0NVm3uVRNzg?si=n_sPPOCgiC0pQ8do> [Accessed 4 April 2025].

DentistKiller., 2024. fakeBook (version 1) [Source code]. Available at: <https://github.com/Dentistkiller/fakeBook.git> [Accessed 27 April 2025].

Education is Life (joed goh), 2021. 07 Styles and Themes - User Interface | Material Design System | Android App Development in Kotlin. [video online] Available at: <https://youtu.be/ynOUzHFFMeg?si=puOjYNC9NjNCBSfD> [Accessed 26 April 2025].

how to videos, 2022. Insert image into database and retrieve in navigation drawer (android studio)(android tutorials). [video online] Available at: <https://youtu.be/8_LuejJEF7o?si=Hhr8a8QOxmGuFaAV> [Accessed 4 April 2025].

othneildrew., 2024. Best-README-Template (version 1.1.2) [Source code]. Available at: <https://github.com/othneildrew/Best-README-Template.git> [Accessed 26 April 2025].

Stevdza-San, 2020. ROOM Database - #1 Create Database Schema | Android Studio Tutorial. [video online] Available at: <https://youtu.be/lwAvI3WDXBY?si=mq1S9X37wiOx5aX5> [Accessed 1 April 2025].

United Top Tech, 2020. App crashes without errors solved in Android studio. [video online] Available at: <https://youtu.be/vX4rO-ShHWs?si=2lgeTLV-pmrmYR0Y> [Accessed 26 April 2025].




<p align="right">(<a href="#readme-top">back to top</a>)</p>

