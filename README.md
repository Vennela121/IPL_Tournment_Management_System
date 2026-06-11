# IPL Tournament Management System

A Java-based web application built using the MVC architecture to manage cricket tournament franchises, player profiles, and match structures.

## 🚀 Technologies Used
* **Backend:** Java (JSF Managed Beans, POJOs)
* **Frontend:** JSF (JavaServer Faces), HTML5, CSS3, JavaScript
* **Database:** MySQL & JDBC
* **Server:** Apache Tomcat 9.0

## 📂 Project Structure
```text
IPL_Tournament_System/
│
├── src/
│   ├── controller/     # Managed JSF Beans (e.g., TeamBean.java)
│   ├── dao/            # Database Connection & SQL operations (e.g., TeamDAO.java)
│   └── model/          # Data Encapsulation POJO classes (e.g., Match.java)
│
├── WebContent/         # Frontend Web Resources
│   ├── css/            # Style sheets for UI layout (style.css)
│   ├── js/             # Client-side validation scripts (validation.js)
│   ├── login.xhtml     # Portal authorization entry page
│   ├── addTeam.xhtml   # Interface to register new franchises
│   └── viewTeams.xhtml # Table views displaying active rosters
│
└── WEB-INF/            # Server Settings Container
    ├── web.xml         # XML context structures and configurations
    └── lib/            # Dependency JARs (mysql-connector, jsf-api, jsf-impl)
