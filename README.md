# Student-Enrollment-Form
## Description 
This is a web based html form for student enrollment using JsonPowerDB as Database 
JsonPowerDB is used to perform CRUD operation 

# Benefits of using JsonPowerDB
* Simplest way to retrieve data in a JSON format.
* Schema-free, Simple to use, Nimble and In-Memory database.
* Built on top of one of the fastest and real-time data indexing engine - PowerIndeX.
* Low level (raw) form of data and is also human readable
* Helps developers in faster coding, in-turn reduces development cost

# TECH STACK USED
* HTML
* CSS
* JAVASCRIPT 
* JsonPowerDB ( As Database)

# Screenshots:
<img src="/images/save_data_1.png">
<img src="./images/database.png">

# Illustrations:
* **UPDATE** : when student roll number is already present in database then student information is fetched from database and filled in respective feild then user can UPDATE student information 
* **SAVE** : If student roll number is not existed in database then we can fill other field and save in database
* **clear** : By this we can clear all field of form and with this except first field (roll-no) other field are disabled until user enter any roll number
* **Alert** : This website uses disposable Alter prompt using bootstrap

# HOW TO USE

* **Initially**
<img src="./images/Initial_home_page_look.png">

We need to enter a roll number 

If roll number is not valid 

<img src="./images/invalid_roll_number.png">

If roll number is valid and that roll number is existnig in database

<img src="./images/existing_student.png">

* **Fetching student data using roll number**
  If student already present in database, then all field filled with that student information
  
  <img src="./images/valid_roll_number.png">
  otherwise, other fields are enabled after user input roll number
  
* **Updation of student details**
  In order to update student details input roll number, and then we can update the student data
  
  <img src="./images/update_student_details.png">
  
  <img src="./images/alert_after_update.png">

* **Adding new student data**

  Enter new roll number and then all other fields are enabled and then after filling student information we can save this data into database only if input is valid
  
  <img src="./images/save_data_1.png">
  
  <img src="./images/alert_after_save_data.png">
  
 * **If input data is not valid**
 
   <img src="./images/invalid_details_1.png">
  
   <img src="./images/invalid_details_2.png">

    
  
# Installation
  
  Make a folder in your system and clone the project using git bash then open the project in Visual Studio Code or any IDE you prefer.
  ##### Clone the project 
  ```
  git clone https://github.com/Sabarivasan-Velayutham/JsonPowerDB_MicroProject.git
  ```
  After cloning 
  
  Move to **public_html** and then **script** folder and in **script.js** file replace the **connectionToken** by with your Connection Token
  
# Scope of Functionalities
* Input validation for required fields.
* Save student data to JsonPowerDB.
* Update existing student data.
* Reset the form to its initial state.

# Examples of Use
* Use the form to enroll new students in a school or educational institution.

# Sources
- [JsonPowerDB Documentation](https://login2explore.com/jpdb/docs.html)
- [Bootstrap Framework](https://getbootstrap.com/)
- [JsonPowerDB Functions](https://login2explore.com/jpdb/resources/js/0.0.4/jpdb-commons.js)
  
# Release History
Version JPDB_0_3_2.20211203 
