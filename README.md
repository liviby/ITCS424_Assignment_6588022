# **ITCS424\_Assignment\_6588022\_README**

**Try running**
cd ios
pod install
cd ..

flutter clean
flutter run

# **Student Information**

**Name:** Sakhunich Iamcharas
**Student ID:** 6588022
**Section:** 1

**Pages Implemented**
**1. Page Name: Home page**
**Description:** 
This home page is welcome page that purpose to show the main menus of the app to navigate to the pages. It show the user profile image with the welcome text with name. The menu contain in home page are Notebook, Q\&A, Quiz, Learn together.

**2. Page Name: Notebook (AI Quick Summarize) page**
**Description:** 
This page is a AI summarize content that show the summarize information together with video related to topic. User able to pause and play at the button. Moreover, it provide topic and vocab section that generate from AI and relate to the topic. It also includes an input textfield “New prompt” to let user generate new prompt.

**2. Page Name: Q\&A page**
**Description:** 
This page displays a community portal for Question and Answer section. It shows a subject category and allows users to view existing questions and answers. The page also includes an input field for users to type new messages or questions.

**Features and Widgets Used**

The important widgets I use are Text, Icon, Image, ElevatedButton, TextField, VideoPlayer. Together with layout element of Column, Row, Container, Expanded, Padding, Sizebox. And the Material Design components such as AppBar, Scaffold, ListView, BottomNavigationBar, CircleAvatar

**Known Issues or Limitations :** Briefly describe any parts of the app that aren’t working as expected or things you couldn’t finish.
The most challenging part was trying to embed and play videos from YouTube. It caused performance issues and lag during testing. As a result, I chose to switch to local video files for a better. Moreover, during simulated, it show error of cocopod that make it can not simulate in xcode. So I have to update and load cocopod the make video and simulate.

**Reflection**

**1. What did you find most challenging about this project?**
The challege I have while working is the naviagtion. Firstly I have design that contain button back to go back to home page, but when it contain navigation bar as well. That make me confuse what should I navigate or link the page. That why this page is the most challege for this project.

**2. Which widgets or design elements are you most proud of using?**
The design element I most proud of is adding the video as it the actual interaction of the app and it challege that I have to find new knowledge about the new package.

**3. What would you add or improve with more time?**
If I have more time, I would improve the Topic and Vocab section in notebook page by adding interactive animations when hover or make it to a button with color. I would like to redesign the app’s main color scheme to be more modern and visually appealing. Moreover. I would like to make Q\&A page allow users to submit questions and receive actual answers.
