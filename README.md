# Stefans Marinaki – Software Testing/QA  Portfolio

## 👨‍⚕️ About Me  | [LinkedIn](https://www.linkedin.com/in/stefansmarinaki/) | [Website](https://stefansmarinaki.com/) | [YouTube](https://www.youtube.com/@syndazy)
Hi! I'm **Stefans Marinaki**, an **Aspiring Software Tester** with a background in **Game Audio, Audio Programming, and Sound Design** which gives me a **unique perspective** in QA when testing digital products. After spending over three years in the game audio industry, I realised my personality traits resonates with **lookout for details, structured workflows, patience, and desire for excellence in production** which brought me to the world of Quality Assurance and Software Testing. Currently, I am completing **The Complete 2025 Software Testing Bootcamp** while working on personal software testing projects to build my expertise. My deep down mission has always been to provide great service to people. Whether this is creating a well-written test documentation for my colleagues or guarantee that the app is defect free for the seamless user experience, I am always willing to be a part of this.



### 🛠️ **Tools:**  
- **Bug Tracking**: Jira, Zephyr Scale, Trello
- **Programming Languages**: C#, Python (entry-level)
- **Data Structures**: JSON, XML
- **API**: Postman
- **Game Audio**: Unity, Unreal Engine, Wwise, FMOD
- **Audio & Video Tools**: Reaper, Ableton, Pro Tools, Izotope RX, DaVinci Resolve

&nbsp;
### 💡 **Software Testing / QA Knowledge:**  
- **Software Development Roles** (Business Analyst, UI & UX Designer, Front/Back-End Developer, etc)
- **Software Development Life Cycle models** (Waterfall, V-Model, Agile, Scrum)
- **Basic Concept of Software Testing** (Dynamic & Static Testing, Validation & Verification)
- **Test Processes** (Planning --> Completion) 
- **Test Levels** (Unit --> Acceptance)
- **Testing Types** (Non/Functional Testing, Black-Box & White-Box Testing, Dynamic & Static Testing, Conformation Testing, Regression Testing, Smoke Testing)
- **Black-Box Testing Techniques** (Equivalent Partitioning, Boundary-Value Analysis, Decision Table Testing, State Transition Testing, Pairwise Testing)
- **Test Scenarios & Test Cases** writing concept and structures
- **Defects**: Types of Defects, Defect Lifecycle
- **Test Reports**: Test Progress, Test Summary
- **Agile**: Agile Manifesto (Values & Principles), Agile Requirements (Themes, Features, Epics, User Story, User Tests), INVEST technique, **Scrum** & **Kanban** (Methodolgoies and Practises), Charts (Burn-Down, Burn-Up, Velocity)
- **API**: HTTP (Methods & Status Codes), XML, JSON, SOAP, REST

&nbsp;
### 🦾 **Software Testing Skills:**  
- **Black Box Testing**: Test Scenarios writing, Test Cases writing
- **Defect Report writing**
- **Test Execution** (manual, No-code Automation using Gen-Ai in Zephyr Scale)
- **Bug Reporting**
- **Accessibility Testing** (using Axe DevTools)
- **Defects**: Capturing Web Logs, Taking Screenshots & Recording Videos (using ScreenPal)
- **Agile**: User Stories & Acceptance Criteria writing (Gherkin Format), Rules Automation (in Jira)
- **API**: Scripting API queries using JSON in Postman, XML and JSON basic writing

&nbsp;
### 📚 **Projects**

### 1. **Creating a Custom Playlist using Spotify API, Postman + Automation** ✅
 An API project that explores a solution to discover new music outside of your _"comfort-genre zone"_ on Spotify. Meanwhile, this project's main focus is on the **data fetching methods scripted in JSON format**; tests are also executed to check if the algorithm fetches the correct data ID and the requests' status codes match. To instantly add filtered search queries to our Playlist, the whole process is **Automated** in **Postman**.

###   - [Project Walkthrough](https://youtu.be/IL_qnMq7Yfs?si=w6qt2_pOfqJiNCpv) (YouTube)
###  &nbsp;

### 2. **API testing Project using ReqRes in Postman** ✅
 This is an API testing project using dummy data taken from the https://reqres.in/ website.
Test requests are split into passed and failed folders. In the "Passed" folder, all 36 cases have passed. In the "Failed" folder, 4 out of 24 cases have failed (all related to the wrong status code) and all cases have the wrong response (body). Some tests were generated with _Postman AI_ and adjusted accordingly.

<ins>Global tests check that<ins>:
- Response time is below 500ms (The "_Delay Response_" is manually excluded)
- The Content-Type headers are written in the "_application/json_" format

<ins>Localised tests involve, but not limited to<ins>:
- Status Code check
- Page Number check
- Validation of a data type (i.e. a "_string_") and data length (_lengthOf.at.least(1)_, and response body _(text).to.be.oneOf([""])_ )
- Look out for the specific data in the array (_for loop_) using strings and booleans
- A creation of a randomised user ID (_Environment variable_) in the Pre-requests, to increase test coverage

###   - [Project Summary](https://docs.google.com/presentation/d/17KeocfuhtARyeUm-ZgvBOyNPxaD25xaTksgp4efXQGA/edit?usp=sharing) (Google Slides)
###   - [Orignal Project in Postman](https://stefan-8635302.postman.co/workspace/Stefan's-Workspace~abaf8235-12b1-4614-803d-e76b404bcbba/collection/43500936-a0a01dc4-cb57-4e6c-a34c-f3f58fd65a9e?action=share&creator=43500936&active-environment=43500936-41a84fae-9b7b-46d6-b98f-13661a1e2393) (Postman)
###  &nbsp;

### 3. **Agile Testing in Scrum Project using JIRA** ✅

 For testing purposes, the project used a Figma design of the transportation app (like Uber). In Jira, **user stories** were created and added to the Backlog, and **acceptance criteria** was written in **Gherkin format** (Given, When, Then). **Story points**, Priority, and Parent (Epic group) were assigned to user stories accordingly. The most important tests were added to Sprint 1, and the **Automation tool** was used to move the user story automatically to the "Done" section when all children are completed. **Burn-down chart** was used to track the total work remaining in Sprint 1.

###   - [The Project](https://docs.google.com/presentation/d/1FrGYEFlPc4jSW7zEXykDZcGzQ1Ucc8I07wGV_3hKOzs/edit?usp=sharing) (Google Slides)
###  &nbsp;

### 4. Black-Box Testing using **Spotify** functionalities - **Sign Up**, **Log In**, **Music Search** ✅
The project used a combination of Functional testing, Positive and Negative Testing, and UI/UX testing). The project utilised black-box testing techniques:
   - State Transition testing for Sign Up, Log In functionalities
   - Equivalence Partitioning & Boundary-Value Analysis for Sign Up functionality (Email, Password, Username & Date of birth field)
   - Equivalence Partitioning for Music Search functionality (Song, Artist, Album, Playlist, and Film OST)

###   - [Project Walkthrough](https://www.youtube.com/watch?v=BcCN6ZuoerU&ab_channel=StefanMarinaki) (YouTube)
###   - [Test Scenario Writing](https://trello.com/b/z2pnoKJq/spotify-test-scenarios) (Trello)
###   - [Test Cases Writing](https://docs.google.com/spreadsheets/d/1ttfTnw705LfU7kh47s2N8l9ff8HnZ2Q4yl77ixrH2gU/edit?usp=sharing]) (Google Sheets)

&nbsp;
### 🧠 **Courses**
- The Complete 2025 Software Testing Bootcamp by Tarek Roshdy (In Progress)
- Python Full Course for Beginners by Dave Gray (In Progress)

