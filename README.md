
<h1 align="center">SpꙩtMe</h1>

<div> </div>

<p align="center">
SpotMe is an innovative health and safety device designed to quickly detect sudden accidents, such as falls or collisions, and alert a designated receiver to provide immediate assistance. By reducing the response time to emergencies, this device can significantly decrease the risk of preventable deaths that occur due to delayed aid. Additionally, SpotMe continuously tracks the user's location, providing valuable data that can be used in various scenarios, such as monitoring speed and performance for racers during competitive events. The collected data can be analyzed to assess the path taken and the speed reached, enabling a comprehensive understanding of the user's activity.
</p>

<div> </div> 

<p align="center">
The project leverages two microcontrollers—STM32G031K8 and RP2040—to handle and process data from the various components. An MPU6050 accelerometer and gyroscope are used to detect falls and collisions accurately. The main connectivity between the device and the user’s phone is facilitated through the <a href="https://raw.githubusercontent.com/tmtorr/capstone_public_overview/refs/heads/main/img/sim808.png">SIM 808</a> card module, which operates on 2G GSM connectivity.
</p>

<div> </div>

<p align="center">
When a fall or collision is detected, the device triggers a vibration and starts a 15-second timer. During this window, the user has the option to cancel the alert if the event was minor. If the timer runs out, the device automatically sends an SMS to the designated recipient’s phone (e.g., "Emergency Alert: Fall detected, immediate assistance needed.") The device also sends a data packet to the user’s phone via Bluetooth, which is then uploaded to a cloud database once the phone connects to Wi-Fi, ensuring real-time monitoring and tracking of user activity and location.
</p>


<div> </div>
<div> </div>

<p align="center"> ... </p>
<p align="center">Below you can see the prototype, and here it is <a href="https://raw.githubusercontent.com/tmtorr/capstone_public_overview/refs/heads/main/img/label_d.png">labelled</a>
<p align="center">
  <img src="/img/full_project.jpg" alt="Full project" width=50% height=50%">
</p>

<p align="center"> ... </p>
<p align="center">Here is a diagram of how it all connected together</p>
<p align="center">
  <img src="/img/connections.png" alt="Connections" width=50% height=50%">
</p>

<p align="center"> ... </p>
<p align="center">Below you can see the UI of the multi-platform application, mobile and PC/Mac respectively :</p>
<p align="center">
  <img src="/img/app1.png" alt="Main Menu Image" width="170" height="300">
  <img src="/img/app2.png" alt="Another Image" width="400" height="300">
</p>
<p align="center">The app uses .NET 9 and C# for cross-platform compatibility, <a href="https://raw.githubusercontent.com/tmtorr/capstone_public_overview/refs/heads/main/img/map.jpg">it also incorporated open street map</a> </p>



<p align="center"> ... </p>
<p align="center">Here is the database schema</p>
<p align="center">
  <img src="/img/db.png" alt="Database" width=50% height=50%">
</p>


<div> </div>
<p align="center">
All-in-all the project was a success and highly educational
</p>

<div> </div>

<p align="center"> ... </p>
<p align="center">
  Please note : The source code is set to private, however if you're interested in the technical aspects of this project I may be able to talk to my team members and show you the inner workings!
</p>

