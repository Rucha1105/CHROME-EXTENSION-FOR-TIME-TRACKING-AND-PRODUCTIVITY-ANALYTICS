# CHROME-EXTENSION-FOR-TIME-TRACKING-AND-PRODUCTIVITY-ANALYTICS

COMPANY: CODTECH IT SOLUTIONS

NAME: RUCHA ARUN RAUT

INTERN ID: CT6WOGZ

DOMAIN: FULL STACK WEB DEVELOPMENT

DURATION: 6 WEEKS

MENTOR: NEELA SANTHOSH KUMAR


### **Task Description: Chrome Extension for Time Tracking and Productivity Analytics**

#### **Objective**

Develop a Chrome extension that tracks the time users spend on different websites and provides productivity analytics. The extension will classify websites as **productive** (e.g., coding platforms, educational sites) or **unproductive** (e.g., social media, entertainment sites) and generate weekly productivity reports. The tool will include a backend to store user data and a dashboard for visualizing analytics.

### **Key Features**

1. **Time Tracking**:

   - Automatically tracks the time spent on each website visited by the user.

   - Captures the domain name and calculates the duration of each session.

2. **Website Classification**:

   - Classifies websites as **productive** or **unproductive** based on predefined rules or user-defined categories.

   - Default classification for common websites (e.g., GitHub as productive, Facebook as unproductive).

3. **Productivity Analytics Dashboard**:

   - Provides a user-friendly dashboard to visualize time spent on productive vs. unproductive websites.

   - Displays daily, weekly, and monthly productivity trends.

4. **Weekly Productivity Reports**:

   - Generates a detailed weekly report summarizing the user's productivity.

   - Includes metrics such as:
   
     - Total time spent.

     - Time spent on productive vs. unproductive websites.

     - Productivity score (percentage of productive time).

5. **Backend Integration**:

   - Stores user data securely in a backend database (e.g., Firebase, MongoDB).

   - Allows synchronization of data across multiple devices.

6. **Customizable Settings**:
   
   - Users can manually classify websites as productive or unproductive.
   
   - Users can set daily productivity goals and receive notifications when goals are met or exceeded.

7. **Notifications**:
   
   - Sends alerts when the user spends too much time on unproductive websites.
   
   - Notifies users about their weekly productivity report.

### **Technical Requirements**

#### **1. Chrome Extension Components**

- **Manifest File (`manifest.json`)**:

  - Defines the extension's metadata, permissions, and scripts.

  - Required permissions: `tabs`, `storage`, `alarms`, `notifications`.

-**Background Script (`background.js`)**:
 
  - Tracks active tabs and calculates time spent on each website.
  
  - Classifies websites as productive or unproductive.
  
  - Saves data to Chrome's local storage or sends it to the backend.

- **Popup Interface (`popup.html` and `popup.js`)**:

  - Displays a dashboard with time tracking data and productivity analytics.

  - Allows users to view reports and customize settings.

- **Icons**:

  - Add icons for the extension in different sizes (16x16, 48x48, 128x128).

#### **2. Backend Components**

- **Database**:

  - Use a database (e.g., Firebase, MongoDB) to store user data.

- **API Endpoints**:

   - Create endpoints to save and retrieve user data.
  

#### **3. Weekly Productivity Reports**

- **Report Generation**:

  - Calculate total time, productive time, unproductive time, and productivity score.
 

- **Report Display**:

   - Display the report in the popup interface or send it via email.

### **Workflow**

1. **User Browsing**:

    - The extension tracks the time spent on each website and classifies it as productive or unproductive.

2. **Data Storage**:

   - Data is stored locally in Chrome's storage or sent to the backend for persistent storage.

3. **Dashboard**:

    - Users can view their productivity analytics in the extension's popup interface.

4. **Weekly Report**:

    - At the end of each week, the extension generates a productivity report and notifies the user.
  
      
### **Deliverables**

1. **Chrome Extension**:

    - Includes `manifest.json`, `background.js`, `popup.html`, `popup.js`, and icons.

2. **Backend Server**:

    - API endpoints for saving and retrieving user data.

3. **Database**:
 
   - Schema for storing user data and productivity reports.

4. **Weekly Report**:
   - Functionality to generate and display weekly productivity reports.

### **Tools and Technologies**

- **Frontend**: HTML, CSS, JavaScript, Chrome APIs.

- **Backend**: Node.js, Express, Firebase/MongoDB.

- **Database**: Firebase, MongoDB, or any preferred database.

- **Version Control**: Git and GitHub.

### **Testing and Deployment**

1. **Testing**:
 
   - Test the extension in Chrome by loading it as an unpacked extension.

   - Use Chrome Developer Tools to debug and fix issues.


2. **Deployment**:

    - Package the extension and publish it on the Chrome Web Store.

   - Deploy the backend server on a cloud platform (e.g., Heroku, AWS).

