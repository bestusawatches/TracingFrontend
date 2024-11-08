# Setting up
download nodejs on your machine from [nodejs]{https://nodejs.org/en)

git clone the repo using `git clone <the repository url>`

cd to the clone repository then run
'npm install'

after installation then the frontend is ready to be used to start it run
`npm start` and wait for the website to pop up on your default browser


to connect the frontend with the backend we need to change the url from a line in the below dirctory
src\
screens\
tracing\
tracing.js

change this part of line 30 from `'http://3.139.67.106:8000/tracing/'` to `'http://0.0.0.0:8000/tracing/'`


