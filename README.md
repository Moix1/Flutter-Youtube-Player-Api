# Flutter Youtube Video Player 

It is basic youtube video player which creates using Flutter with the help of Youtube Data Api V3.

# Must Note
- You need to create folder called "utilities" within lib "folder" of project, In side utilities folder you have to create file called "keys.dart" you can call it anything but make sure while importing in other files with same name you provided, Inside keys.dart you have to write these codes:

const String API_KEY = 'Paste HERE Your Youtube Api Key';
----------------------------------------------------------

How to setup Youtube Data Api v3 Key in your project is very easy for getting the key:
1:  Go to https://console.developers.google.com
2:  Create project there with any name "Youtube Data Api"
3:  Go to Api Library
4:  Search Youtube, you will get Youtube Data V3 click on it
5:  Enable it
6:  Click on Create Credentials button at top right side
7:  Choose Youtube Data Api V3 and then you will see another option called 'Where you will be able to calling the API from?' select Either     iOS or Android
8:  Now check on Public Data
9:  Click on What credentials do i need?
10: You will see key now just COPY it
11: Click on Done NOT done yet next
12: Scroll Down you will see Restrict Key radio button, select it
13: Select api which will be like Youtube Api Data V3
14: Now Click on Save.

It's time to paste your copied key inside lib->utilities->keys.dart 

const String API_KEY = 'Paste HERE Your Youtube Api Key';
---------------------------------------------------------

You all good to go!

If you got any issues open up issue i will be helping you.

Thanks for reading
