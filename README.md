# Well Spent

WellSpent is a web app that enables you to shop ethically and get the ethical details about brands.   

# Breif summary of key requierments/features
- Well Spent contains ethical brands.
- Each brand contains ethical details.
- User can suggest a new brand.
- User can add feedback for a brand
- The admin of wellSpent website can manage all stuff about the brands .

 
# Main functionality/ user story
- A user can see all brands in wellSpent.
 - A user can select a brand :
    - Enable to see all details about a brand.
    - Enable to suggest a new brand.
    - Enable to add feedback.
 - Admin can log by using shared username and password.
 - Admin can add a brand :
    - Enable to update and delete the brand.
    - Enable to delete feedback.
 - Leave the account
 

# heroku Link - this version contains feedback section
https://wellspent-ethical.herokuapp.com/#/

# This version doesn't contain feedback section 
https://wellspent2.herokuapp.com/#/ 


 # How to run our app on your local machine?
 Follow these instruction in order:

1- Open your terminal.

2- Clone this repository.

  > Using HTTP: https://github.com/FACK1/wellSpent.git
  
  > Using SSH: git@github.com:FACK1/wellSpent.git

3- Make a new file in the root directory wellSpent, and call it .env

   Identify below variables inside .env file:
   
   > PORT=5000 
   
   > APIKEY= "API KEY that you got from your account on Airtable"
   
   > DB_NAME ="Database Name on Airtable"
     
5- Install dependencies and dev dependencies; by typing in the terminal ```npm i``` && ``` npm install-client```.

7- Run on your termial npm run dev

8- Open the app by write in your browser `http://localhost:3000/`
 

 # Key Technologies   
 - Express JS : https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction
 - React.js : https://reactjs.org/docs/getting-started.html
 - Airtable:https://airtable.com/
 - Axios : https://www.npmjs.com/package/axios


# DataBase Structure 
![111](https://user-images.githubusercontent.com/35188117/54487653-44a35480-48a1-11e9-9857-45ec9e62c430.png)


# Team Member
- [Sama Amro](https://github.com/Samaamro20)
- [Shaima Ihdoosh](https://github.com/shaima96)
- [Safa Amro](https://github.com/safaaamro)
    
