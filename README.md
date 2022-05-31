# PIWORKS User Interface Specifications
## Logical Structure & Process:
We need to design a page for our site which will be creating a new user wihtin the database.  
This new user is going to press a **button** named **NEW USER** on the left corner of the screen which will direct them to a  
different section wihtin the page where the user will be asked to fill the given information. After giving the information, the user is going to press **SAVE USER** to save their information. Both **NEW USER** and **SAVE USER** buttons are going to be placed on a bar on top of the page. Also, there is going to be a checkbox on the right hand side of the **NEW USER** button named as **Hide Disabled User** which will hide the disabled users (This information is going to checked or unchecked by the user wihtin the registiration).
This registiration page is going to be designed for New Users where the user is going to enter their information and based on the infromation that's entered, 
a new submission will be made to the database.
Needed sections are as follows:
* Registiration Bar
* Registiration Page
* Relational Database (SQL)

## Registiration Bar
This bar will have a gray color #B8B8B8
Registiratoin bar will have 2 buttons and 1 checkbox. This registiration bar will be placed at the op of the site so we can leave nearly identical spaces to both database and the regsistiration section of the page. On the registiration bar's left corner, we are going to have a button named NEW USER. This button will be:
* Medium Sized
* Square Corners
* Have a "+" Sign before the word NEW -> + NEW USER
* Button interaction will be default
* Background Color will be Sky Blue #14AAF5
* Bold White Font for the title

After that there is going to be a Checkbox which will gide the disabled user wihtin the database. This checkbox will be:
* Small
* Becomes Sky Blue #14AAF5 backgournd with a tick icon when pressed
* Bold Black Font for the title

At the right hand corner of the bar there is going to be a SAVE USER button which will save the inforamtion that's been entered by the user. The button attributes are as follows:
* Medium Sized
* Square Corners
* Button interaction will be default
* Background Color will be Sky Blue #14AAF5
* Bold White Font for the title

## Registiration Page
This is the section of the page where the user will enter the details. This section will be titled as New User and will include these infroamtions to be entered (In the given numeriacal order the sections will be listed within the Form):
1) Username
2) Display Name
3) Phone
4) Email
5) User Roles
6) Enabled

After getting these information, we are going to save the inforamtion to a realtioonal database. Each informtion input will be like this:
* Username  
This input will be entered wihtin a text field and will be saved accordingly, Black Bold Font,"Usuername: " will be written on the left side of the text field.
* Display name  
Same again, will be taken within a text field, Black Bold Font, "Display Name: " will be written on the left side of the text field.
* Phone & Email  
These both will share the same attributes as well. First the Phone will be asked ( "Phone: " will be written on the left side of the text field.) after that, Email will be asked ( "Email: " will be written on the left side of the text field.)
* User Roles  
This will be a dropdown menu with options of:
1) Guest
2) Admin
3) Super Admin  
**Only 1 will be selected!**
"User Roles: " will be written on the left side of the Dropdown menu.
The selected option's color will be agai Sky Blue #14AAF5
* Enabled  
Last information we ask from the user. This will be a checkbox and will have these attributes:
* Small
* Becomes Sky Blue #14AAF5 backgournd with a tick icon when pressed
* Bold Black Font for the title
"Enabled: " will be written on the left side of the checkbox.
If it's selected, we are going to label the user as **Enabled**, if they don't we label them as **Disabled** to the database.

## Database
The main attributes of the database are as follows:
* 4 Columns & The order will be as well as the names of the columns: **ID**,**User Name**,**Email** and lastly **Enabled**
* Each column will have options of sorting (Alphabetical A-Z or Z-A)
* Information row where the topics will be presented will be again in Sky Blue #14AAF5
* The selected or highlighted row wil be in Light Blue #96C3EB
* If the user is enabled, display ``` true ``` if not ``` false ```
* As mentioned it will be in SQL

## The General Layout of the Page and Last Notes
The page background will be white while the banner as we mentioned will be gray #B8B8B8. The below part of the page will be divided equally into two sections. These sections are going to evenly sliced into two square
