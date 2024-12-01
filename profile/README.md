<a name="readme-top"></a>

# LG전자 SW분야 산학협력프로젝트


> participants
<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/yS2h"><img src="https://avatars.githubusercontent.com/u/141344997?v=4" width="100px;" alt=""/><br /><sub><b>조장(BE): 윤수현</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/skeep194"><img src="https://avatars.githubusercontent.com/u/48646456?v=4" width="100px;" alt=""/><br /><sub><b>BE : 정종운</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/go-minjung"><img src="https://avatars.githubusercontent.com/u/123921816?v=4" width="100px;" alt=""/><br /><sub><b>FE : 배민중</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/seung365"><img src="https://avatars.githubusercontent.com/u/74394824?v=4" width="100px;" alt=""/><br /><sub><b>FE : 백승범</b></sub></a><br /></td>
    </tr>
  </tbody>
</table>

## Table of Contents
  - [Outline](#Introduction-to-the-Project) 

  - [Project Content](#Project-Content)

  - [Usage Technology Stack](#Usage-Technology-Stack)

<br/><br>
# Introduction to the Project
### **A Lifestyle Custom Standby App**

This project is an app/widget development project based on the webOS so that users can obtain meaningful information even in a standby state.
<p align="center" style="display: flex; justify-content: space-between;">
    <img src="https://github.com/user-attachments/assets/beb0422d-845f-4a01-8cb0-6fa83408f2f5" 
         style="width: 50%;">
    <img src="https://github.com/user-attachments/assets/8fd56178-2bbd-44e9-9dd3-d40a1148b5bb" 
         style="width: 50%;">
</p>

<br/><br>



# Project Content

### **Background**

When the display is in a standby state, it is necessary to develop an app that allows users to receive meaningful information (standby function)
By implementing a function to provide various information while minimizing battery usage, it aims to develop an app that can obtain information in real time or continuously even while waiting

① **Standby Screen App/Widget Development**
-  Objective: Develop a standby app/widget that continuously provides information tailored to the needs of the user, using minimal battery even when the device is in the standby state.
- Features: It provides widget functions such as slide show (image), weather (temperature, precipitation, fine dust, etc.), schedule list (calender, to-do list), and media player. It minimizes battery consumption through dimming function, which automatically reduces screen brightness after 20 seconds even in standby state.

② **Implementing Web App Features**
- User login service: It loads the standby settings for each user through the login function and provides a screen tailored to the settings of the logged-in user. In addition, through the user dashboard, functions to be displayed on the standby screen can be selected and stored, and a real-time preview screen is provided. At this time, widgets and functions can be set directly on the app screen through the UI controller.
- Standby Screen Customization: Various widgets are customized to suit user needs and displayed on the standby screen. Additional functions are also developed and displayed on the screen. (e.g., slide show, weather information, schedule list, media play, medication notification, etc.)

<br/><br>

# Usage Technology Stack

> System Structure Chart

<img src="https://github.com/user-attachments/assets/70ae41d0-5da0-42ba-b49e-a24afee254a1">

> Database ERD

<img src="https://github.com/user-attachments/assets/23917fea-4019-422c-b44a-a8cbcd71cdfd">

### ✔️Frond-end
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black"><img src="https://img.shields.io/badge/chakraui-319795?style=for-the-badge&logo=chakraui&logoColor=white"><img src="https://img.shields.io/badge/reactquery-FF4154?style=for-the-badge&logo=reactquery&logoColor=purple">

### ✔️Back-end
<img src="https://img.shields.io/badge/Nest.js-E0234E?style=for-the-badge&logo=NestJS&logoColor=white"/><img src="https://img.shields.io/badge/YARN-2C8EBB?style=for-the-badge&logo=Yarn&logoColor=white"/><img src="https://img.shields.io/badge/PRISMA-2D3748?style=for-the-badge&logo=PRISMA&logoColor=white"/>

### ✔️Data-base
<img src="https://img.shields.io/badge/Nest.js-4169E1?style=for-the-badge&logo=NestJS&logoColor=white"/><img src="https://img.shields.io/badge/postgresql-2D3748?style=for-the-badge&logo=postgresql&logoColor=white"/>
