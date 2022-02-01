# WebTech Assignment 8
### Q1- Write a JS function to validate email-id using regular expression.
### Solution Function 
```
 const expression = /^([\w]*[\w\.]*(?!\.)@gmail.com)/;
      function validate(){
        const mail = document.getElementById('email');
        if(mail.value =='' || expression.test(mail.value) == false){
          // alert("null value are not allowd");
          document.querySelector('label').textContent = "Please enter valid email";
          return false;
        }
        else
        {
          return true;
        }
      }
```
#### [Click here for live solution](https://sandesh-at-git.github.io/WebTech-Assn8-Que-1/)
