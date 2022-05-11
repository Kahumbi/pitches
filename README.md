# Julizapitch !
​
## Author [David Kahumbi]
​
## Description
Juliza pitch is a web application that is used to highlight helpfull and motivating one minute pitches that users can create and live behind for friends and family to find and read to inspire them 
to keep on going despite what they may be going through in life.
​
## Technologies Used
python 3.8
Flask
Html
CSS
Bootstrap

## User Stories
Users will be able to:
*Signup & Register new accounts
*Login to their accounts
*Create a new pitch
*Post their favourite pitches
*Delete pitches they want to
*​Read and see pitches from other users

## BDD
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Register your user name & email | **Enter username,email & password** | New user gets a flash message registration succesfull |
| Login to julizapitch | **Remember to enter login details and click login** | Redirect to logged in page with user credentials |
| Create a new pitch | **Click on new pitch and pitch a pitch** | Redirect to account where pitch is displayed |
| Navigate to diffrent users accounts | **click to view other users** | View Different users and see their pitches and the day they were posted |
​
​
## Known Bugs
If you find a bug please feel free to alert me. To fix the bug:
​
Fork the repository
Open your terminal
Create a new branch
Make the changes, then (git add) to add changes
Commit the changes you have made(git commit -m"Fix bug")
Push changes made and click pull request so that I can access the changes made.
​
​
## SetUp / Installation Requirements
### Prerequisites
* python3.8
* pip
* virtualenv
​
### Cloning
* In your terminal:
​
        $ git clone https://github.com/kahumbi/pitches.git
        $ cd Pitch
​
## Running the Application
* Creating the virtual environment
​
        $ python3.8 -m venv --without-pip virtual
        $ source virtual/bin/env
        $ curl https://bootstrap.pypa.io/get-pip.py | python
        $ pip install Flask
​

## License
​
License
MIT Copyright (c) 2022 David Kahumbi
​
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
​
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
​
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
​
=======
​
pitches
