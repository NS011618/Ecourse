# Hello Guys ,This is Ashish

**The Project i have done is **
# Ecourse
Create a platform where instructors can upload courses with detailed descriptions and contents, costs, discounts, 
from where students can choose courses they need and add them to their cart.
This application can also include reviews and feedback sections.



[![MIT License](https://img.shields.io/badge/Platform-Deployed-green.svg)](https://choosealicense.com/licenses/mit/)

Deployed App link: 
[https://ashishgolla01.pythonanywhere.com/]



## Features


- Fully Responsive platform
- reset password feature for both admin and voter
- Uses CSRF tokens to prevent attacks 
- Admin will be able to signup,Login
- Admin can create the elections
- Admin can edit election and if election is launched and ended admin cannot edit election
- Admin can create a ballot of questions in an election
- Admin can add options and delete options for a question in the election
- Admin can delete the elections,questions,voters
- Admin can register voters
- Admin can launch election
- Admin can Preview results while election is running
- Elections administrator can set custom path to election
- Voter can login to voting page and submit his response
- Ending the election
- We cannot delete election after ending election
- We cannot edit questions after launching election
- We cannot edit questions,voters,options etc... after ending an election




## Technologies used to build the website

 HTML, Bootstrap,CSS, django



Go to the project directory

```bash
  cd ASHISHFINALPROJECT
```

Install dependencies

```bash
  pip install -r requirement.txt
  python manage.py makemigrations
  python manage.py sqlmigrate course 0001
  python manage.py migrate
```
```
  To run website 
      python manage.py runserver
```
