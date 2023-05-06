
#HandsOn 📝

HandsOn is a blogging website that allows users to post their thoughts and knowledge with others.


<br>


## Tech Stack
- **Frontend:** HTML/CSS/Bootstrap
- **Backend:** Django


## Open Source Contests

## - KHARAGPUR WINTER OF CODE (KWOC'20)

[![chat on discord](https://img.shields.io/badge/chat-on%20discord-brightgreen)](https://discord.gg/nmX6yyGY49)

Kharagpur Winter of Code is a 5-week long online program for students who are new to open source software development. The program not only helps students to get involved in open source, but also prepares them for many open source summer programs; Google Summer of Code being one of them.

<div >
<img src="https://kwoc20.kossiitkgp.org/static/media/circle.33e6ce0d.svg" alt="kwoc20" height="300" width="300"/>
  </div>
  
## - NJACK WINTER OF CODE (NWOC'20)

[![chat on discord](https://img.shields.io/badge/chat-on%20discord-brightgreen)](https://discord.gg/eeGR2qvd9y)

NWoC (NJACK Winter of Code) is a program by NJACK (The Official Computer Science Club of IIT Patna) that helps students understand the paradigm of Open Source contribution and gives them real world software development experience.

<div >
<img src="https://njackwinterofcode.github.io/images/nwoc-logo.png" alt="nwoc20" height="300" />
  </div>


## Quick Start

- Fork and Clone the repository using-
```
git clone https://github.com/diyajaiswal11/Bloggitt.git
```
- Create a Branch- 
```
git checkout -b <branch_name>
```
- Create virtual environment-
```
python -m venv env
env\Scripts\activate
```
- Install dependencies using-
```
pip install -r requirements.txt
```
*If you have python2 and python3 installed you need to specify python3 by using command:*
```
python3 -m pip install -r requirements.txt
```

- Headover to Project Directory- 
```
cd HandsOn
```
- Make migrations using-
```
python manage.py makemigrations
```
*If you have python2 and python3 installed you need to specify python3 by using command:*
```
python3 manage.py makemigrations
```

- Migrate Database-
```
python manage.py migrate
```
- Create a superuser-
```
python manage.py createsuperuser
```
- Run server using-
```
python manage.py runserver
```
- Push Changes-
```
git add .
git commit -m "<your commit message>"
git push --set-upstream origin <branch_name>
```



## Useful Resources to Learn

- [Django Docs](https://docs.djangoproject.com/en/3.1/)
- [Bootstrap Docs](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
- [Git and GitHub](https://www.digitalocean.com/community/tutorials/how-to-use-git-a-reference-guide)





