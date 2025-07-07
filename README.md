# Admission_Enquiry_Form
## Date:

## Objective:
To design a simple Admission Enquiry Form using basic HTML that collects student details such as name, contact, program of interest, and a message for further communication.

## Tasks:
#### 1. Set Up the HTML Structure:
Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document structure.
Set the ```<title>``` as "Admission Enquiry Form".

#### 2. Add a Page Heading:
Use ```<h1>``` to title the page as “Admission Enquiry”.

#### 3. Create the Form Layout:
Use the ```<form>``` tag to wrap all input elements. Set method="post" for structure.

#### 4. Add Input Fields:
Include the following fields using appropriate HTML elements:

Full Name

Email Address

Phone Number 

Program of Interest 

Message

#### 5. Add Submit and Reset Buttons:
Use submit and reset at the bottom of the form.

#### 6. Use HTML-only:
No CSS or JavaScript is to be included. Focus on structure and accessibility.

## HTML Code:
```
<!DOCTYPE html>
<html>
    <head>
        <title>Saveetha Engineering College</title>
    </head>
    <body align="right">
        <h1>Admissions open 2025</h1>
        <input type="text" placeholder="Enter Name *" required>
        <br>
        <input type="email" placeholder="Enter Email Address *" required>
        <br>
        <input type="tel" placeholder="Enter Mobile Number *" required>
        <br>
        <input type="password" placeholder="Any Password of Your Choice *" required>
        <br>
        <select required>
            <option value="" disabled selected>Select State *</option>
            <option>Tamil Nadu</option>
            <option>Karnataka</option>
            <option >Kerala</option>
            <option>Andhra Pradesh</option>
        </select>
        <select required>
            <option value="" disabled selected>Select City *</option>
            <option>Chennai</option>
            <option>Coimbatore</option>
        </select>
        <br>
        <select required>
            <option value="" disabled selected>Select Course *</option>
            <option>CSE</option>
            <option>AIDS</option>
            <option>AIML</option>
            <option>ECE</option>
        </select>
        <select required>
            <option value="" disabled selected>Select Specialization *</option>
            <option>VLSI</option>
            <option>Cyber Security</option>
            <option>IOT</option>
        </select>
        <br>
        <button type="submit">APPLY NOW</button>
    </body>
</html>
```
## Output:
![image](https://github.com/user-attachments/assets/3ede8f1a-5bca-49d2-af4b-ae100ffc636f)

## Result:
An Admission Enquiry Form using HTML that collects student details and message for institutional follow-up is successfully created using semantic and readable HTML.
