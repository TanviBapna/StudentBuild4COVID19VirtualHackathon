
## **Assessing patient details for covid19 Risk Report Generation**

Hackathon Report by Team &quot;Black Canyon&quot;

### **List of Contents:**

- [List of Team members with their biographies](#_dsh7zenwq9rz)
- [Team member selected to display and handle the presentation](#_7pcefwjykf8b)
- [Development tools used to build the project](#_d8dspgaklr31)
- [APIs used in the project](#_laqae3p2frex)
- [Assets used in the project](#_sqf6ukdt94ti)
- [Libraries used in the project](#_k8z6wjhs6y1b)
- [Components not created at the hackathon](#_ss7dcgdqf2xe)
- [Team&#39;s Github repository](#_yqqh95u1eub9)
- [Branches](#_6rbw8tw9lsc9)
- [Code Execution](#_xweuuftv0qie)

### **List of Team members with their biographies**

**Akshaya Sharma**

Computer Science graduate student at The University of Texas at Arlington.

LinkedIn: www.linkedin.com/in/akshaya-sharma

**Apoorva Shivupriya**

Graduate student at The University of Texas at Arlington majoring in Intelligent Systems and Databases. I have worked on projects involving Web development, Desktop based software development, Data Analytics, and Machine Learning models.

LinkedIn: [linkedin.com/in/apoorva-shivpuriya/](https://www.linkedin.com/in/apoorva-shivpuriya/)

**Saranya Visvanathan**

A graduate student at San Jose State University, pursuing a master&#39;s in Computer Software Engineering and would be majoring in Data Science. A former Software Engineer with two years of work experience in designing, programming, and managing software-related projects at Cisco Systems, India. Specializes in Python, SQL, C, Java, and Yang data modeling.

[Access Saranya&#39;s Linked In Profile](https://www.linkedin.com/in/saranya-visvanathan/)

**Swapnil Jangam**

Graduate computer science student at University of Texas Arlington. Experienced as a Full-Stack developer in the HealthCare domain.

LinkedIn: [https://www.linkedin.com/in/swapnil-jangam/](https://www.linkedin.com/in/swapnil-jangam/)

**Tanvi Bapna**

A graduate student at the University of Texas Arlington, pursuing a master&#39;s in Computer Software Engineering, focusing on Database and Intelligent System.

LinkedIn: [linkedin.com/in/tanvi-bapna](http://www.linkedin.com/in/tanvi-bapna)

### **Team member selected to display and handle the presentation**

Swapnil Jangam: swapnil.jangam@mavs.uta.edu

### **Development tools used to build the project**

**For Application Development:**

- SwiftUI
- Swift 5

**For Website Development:**

- Visual Studio Code
- Jupyter Notebook

### **APIs used in the project**

- Python
- HTML5

### **Assets used in the project (****Assets = media such as pictures, videos, etc - along with frontend bootstraps (premade styles)****)**

- Plotly
- Vector image designed by rawpixel.com
- Freepik, Vector image designed by pikisuperstar
- Freepik, Vector image designed by pch.vector / Freepik

### **Libraries used in the project**

**For Application Development:**

- SwiftLocation (4.2.0)
- HealthKit
- UserNotifications
- SwiftUI

**For Website Development:**

- Python Flask Framework
- JavaScript Plotly
- JSON
- Werkzeug
- Math
- ibm\_db

### **Components not created at the hackathon**

- Mockaroo
- Used clinical results publicly available on[https://pubmed.ncbi.nlm.nih.gov/32109013/](https://pubmed.ncbi.nlm.nih.gov/32109013/)
- In-built modules used for the web application: atexit, OS, CSV, Requests

### **Team&#39;s Github repository**

- [https://github.com/Snappyie/Hackathon0612](https://github.com/Snappyie/Hackathon0612)

### **Branches:**

- UI: Code for Web Application
- Master: Code for iOS application

### **Code Execution:**

- **Mobile Application:**
  - Clone master branch
  - Open COVIDRiskAssessment.xworkspace
  - Add Code Signing from xcode
  - Run it on emulator / device using the play button

- **Covid19 Risk Assessment Website**

The Website UI codings are uploaded as [ResultsUI2.zip](https://github.com/Snappyie/Hackathon0612/blob/master/ResultsUI2.zip)

Contents of ResultsUI2 ZIP folder:

- application.py

- templates folder

- dashboard.html

- login.html

- Patient details.html

- Register.html

- static folder

- style.css

- To execute the Results UI, run the application.py file.
- Paste the displayed URL into a browser.
- Login using any credentials to see the Dashboard.

Website GUI: It reads the JSON file from the iOS application and inserts the data in IBM DB2 database. DB2 database is then used to show Patient status&#39; and details to the Healthcare Providers.

To execute the website GUI, run the **application.py** file. Login using any credentials to see the Dashboard. The Patient data corresponding to the logged in user would be displayed on the screen classified into High, Low and Medium risk. In the List of Patients, click on the names to see the detailed Patient data.
