# PIWORKS User Interface Specifications
## Logical Structure & Process:
We need to design a page for our site which will be creating new users within the database.  
This new user is going to press a **button** named **New User** on the left corner of the screen which will direct them to a  
different section within the page where the user will be asked to fill in the given information (In a from format more on that later on). After giving the information, the user is going to press **Save User** to save their information. Both **New User** and **Save User** buttons are going to be placed on a bar on top of the page. Also, there is going to be a checkbox on the right-hand side of the **New User** button named **Hide Disabled User** which will hide the disabled users within the database (This information is going to be checked or unchecked by the user within the registration).
This registration page is going to be designed for New Users where the user is going to enter their information and based on the information which was entered, 
a new submission will be made to the database.
The need sections are as follows:
* Registration Bar
* Registration Form
* Relational Database (SQL)

## Registration Bar
This bar will have a gray color #B8B8B8
The registration bar will have 2 buttons and 1 checkbox. This registration bar will be placed at the top of the site so we can leave nearly identical spaces for both database and the registration section of the page. On the registration bar's left corner, we will have a button named NEW USER. This button will be:
* Medium Sized
* Square Corners
* Have a "+" sign before the word NEW -> + NEW USER
* Button interaction will be the default
* Background Color will be Sky Blue #14AAF5
* Bold White Font for the title

After that, there is going to be a Checkbox that will hide the disabled user within the database. This checkbox will be:
* Small
* Becomes Sky Blue #14AAF5 background with a tick icon when pressed
* Bold Black Font for the title

At the right-hand corner of the bar, there is going to be a SAVE USER button which will save the information that's been entered by the user. The button attributes are as follows:
* Medium Sized
* Square Corners
* Button interaction will be the default
* Background Color will be Sky Blue #14AAF5
* Bold White Font for the title

## Registiration Form
This is the section of the page where the user will enter the details. This section will be titled New User and will include the information to be entered (In the given numerical order the sections will be listed within the Form):
1) Username
2) Display Name
3) Phone
4) Email
5) User Roles
6) Enabled

After getting this information, we are going to save the information to a relational database. Each information input will be like this:
* Username  
This input will be entered within a text field and will be saved accordingly, Black Bold Font, "Username: " will be written on the left side of the text field.
* Display Name  
Same again will be taken within a text field, Black Bold Font, "Display Name: " will be written on the left side of the text field.
* Phone & Email  
These both will share the same attributes as well. First, the Phone will be asked ( "Phone: " will be written on the left side of the text field.) after that, the Email will be asked ( "Email: " will be noted on the left side of the text field.)
* User Roles  
This will be a dropdown menu with options of:
1) Guest
2) Admin
3) Super Admin  
**Only 1 will be selected!**
"User Roles: " will be written on the left side of the Dropdown menu.
The selected option's color will be again Sky Blue #14AAF5
* Enabled  
Last information we ask from the user. This will be a checkbox and will have these attributes:
* Small
* Becomes Sky Blue #14AAF5 background with a tick icon when pressed
* Bold Black Font for the title
"Enabled: " will be written on the left side of the checkbox.
If it's selected, we are going to label the user as **Enabled**, if they don't we label them as **Disabled** to the database.

## Database
The main attributes of the database are as follows:
* 4 Columns & The order will be as well as the names of the columns: **ID**,**User Name**,**Email** and lastly **Enabled**
* Each column will have the options of sorting (Alphabetical A-Z or Z-A)
* Information row where the column names will be displayed will be again in Sky Blue #14AAF5
* The selected or highlighted row will be in Light Blue #96C3EB
* If the user is enabled, display ``` true ``` if not ``` false ```
* As mentioned it will be in SQL

## The General Layout of the Page and Last Notes
The page background will be white while the banner as we mentioned will be gray #B8B8B8. The below of the bar will be divided equally into two sections. These sections are going to evenly parted. The left-hand side section is for the database (The database section's corner are going to be sharp) and the right-hand side of the section is going to be for the form for the user to enter the details. This section as we mentioned will be titled as **New User** and the title will be on a gray #B8B8B8 banner and below that, the form will ask about the information (Details can be found wihtin the **Registiration Form** part). These sections (Both database and form will have a white a background again)
