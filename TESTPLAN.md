# Test Plan of Java Part in VS Code Azure App Service

### Target OS

#### Windows 10

#### Mac OS

#### Linux

### Test Plan

- User could create a linux java tomcat 8.5 web app

- User could create a linux java tomcat 9.0 web app

- User could create a linux java se web app

- User could deploy a war file to a linux java tomcat 8.5 web app

- User could deploy a war file to a linux java tomcat 9.0 web app

- User could deploy a jar file to a linux java se web app
  - User will be prompted to enter a port to configure the application settings if there is not "PORT" configuration in app settings
  - User will not be disturbed if there is already a "PORT" configuration in app settings
  - User could press ESC from the port input dialog to cancel the deploy

- User could right-click a .war file to deploy it to a linux java tomcat 8.5 web app

- User could right-click a .war file to deploy it to a linux java tomcat 9.0 web app

- User could right-click a .jar file to deploy to a linux java se web app

- User could not get "Deploy to Web App..." command when right-click a file whose extension is not jar or war

- User could be prompted all .jar files in current folder to select one to deploy to linux java se web app

- User could be prompted all .war files in current folder to select one to deploy to linux java tomcat web app

- User could view log files of web app

- Java SE runtime will not show up if users select os 'Windows' during creating web app

