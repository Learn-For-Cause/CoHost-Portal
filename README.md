[![DISCORD](https://img.shields.io/badge/Join-Discord-blue)](https://discord.gg/FgNMvcvN)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)


Let's create ***Educators Hosting Platform(named CoHost Portal)*** for every educators community, who have not much infrastructure to educate people remotely in the world!

## what is the CoHost-portal
The Co-Host portal is a web portal and it works as a bridge among the educators and the students. It include three type of user interfaces, which are **Admin, Teachers and Students**, These all are having different type of controls.

- **Admin interface**
They are the maintainers of the portal, so they have full access to read & write all the information available at the portal regarding Teachers and Students & *can take necessary action related to Teachers and Students, if needed*.

- **Teachers interface**
They are the educators, so they have some restricted amount of access to the information, it can also read and write, but only those type of information which is directly related to him and the students who have enrolled under them & *can take necessary actions on the students only*.

- **Students interface**
They have only access to read the information related to him only.

## Tech Stack 🗃

 <img src="https://img.shields.io/badge/django%20-%2320232a.svg?logo=django" >  <img src="https://img.shields.io/badge/-PostgreSQL-yellow?style=flat&logo=PostgreSQL">  <img src="https://img.shields.io/badge/-HTML%20-%2320232a?style=flat&logo=HTML">  <img src="https://img.shields.io/badge/-CSS%20-%2320232a?style=flat&logo=CSS">  <img src="https://img.shields.io/badge/-JavaScript%20-%2320232a?style=flat&logo=JavaScript">


## How to contribute?

Please read [our contributing guidelines](https://github.com/Learn-For-Cause/CoHost-Portal/blob/main/CONTRIBUTING.md) for details of how you can get involved, [our contributors](https://github.com/Learn-For-Cause/CoHost-Portal/blob/main/CONTRIBUTING.md)for details of the contributors, and [Code of Conduct](CODE_OF_CONDUCT.md) for information about how to participate.


##  Getting Started 👨‍💻
###### Pre-Requisites:

1. Install Git Version Control
[ https://git-scm.com/ ]

2. Install Python Latest Version
[ https://www.python.org/downloads/ ]

3. Install Pip (Package Manager)
[ https://pip.pypa.io/en/stable/installing/ ]

*Alternative to Pip is Homebrew*

### Setup the repository to your local environment.

1. `Fork` the repository  - Creates a replica of repository to your local environment.

2. Create a Folder where you want to save the project**

3. Create a Virtual Environment and Activate**

Install Virtual Environment First
```
$  pip install virtualenv
```

Create Virtual Environment

For Windows
```
$  python -m venv venv
```
For Mac
```
$  python3 -m venv venv
```

Activate Virtual Environment

For Windows
```
$  venv/scripts/activate
```

For Mac
```
$  source venv/bin/activate
```
4. Clone the repository - Downloads all repo files to your machine, using
  ```git
  git clone https://github.com/YOUR-USERNAME/CoHost-Portal.git
  ```
5. Set working directory to the root directory of the project.
```sh
$  cd CoHost-Portal
```

#### How to Install and Run this project?
1. Install Requirements from 'requirements.txt'**
```python
$  pip install -r requirements.txt
```

2. Add the hosts**

- Got to settings.py file
- Then, On allowed hosts, Add [‘*’].
```python
ALLOWED_HOSTS = ['*']
```
*No need to change on Mac.*

3. Now Run Server**

Command for PC:
```python
$ python manage.py runserver
```

Command for Mac:
```python
$ python3 manage.py runserver
```
4. [Click here](http://localhost:8000) to see the backend server runing in the browser OR navigate to
  ```text
  http://localhost:8000
  ```

## Testing Credentials 🤖

  The dummy admin credentials to login to the admin dashboard are given below -

  ```
  {
      "username" : "cohost@gmail.com",
      "password" : "learn@123"
  }
  ```

## Community 👥

[![DISCORD](https://img.shields.io/badge/Join-Discord-blue)](https://discord.gg/FgNMvcvN)


## Authors
- **Asutosh Das** - _initial work_ - [Asutosh Das](https://github.com/Ash-exp)
- **Abhishek Choudhary** - _initial work_ - [Abhishek Choudhary](https://github.com/Abhishek-K-Choudhary)
Enjoy! Give us [feedback](https://github.com/Learn-For-Cause/CoHost-Portal/issues) if you have suggestions on how to improve this information.


## Contributors 🌟

Thanks goes to these wonderful people ✨✨:

<a href="https://github.com/Learn-For-Cause/CoHost-Portal/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Learn-For-Cause/CoHost-Portal" />
</a>

## Licence
This project is licensed under the MIT License, unless otherwise stated.
