# 601-homework2-Resume Webpage, IOS APP
This is a individial homework by Zhang Jiahao. And this is the first time for me to bulid a resume webpage and build part of an IOS app<br>

## Resume Webpage
I made my own resume webpage and utilized firebase authentication function.
### Test task
#### 1. Test case report
In the testing period, Firstly I tested webpage link and login part, which are in high priority. Then I tested three contact links (GitHub, Twitter and Facebook link). Finally, I tested firebase database information.
![image](https://github.com/jiahaozh/601-homework2-IOS-APP/raw/master/TEST/test.png)
#### 2. Automate Testing
In this part, I tested Yanxing Zhang's webpage.
As recommended by professor, I ran it on Monkey Test. The results are as follows:
![image](https://github.com/jiahaozh/601-homework2-IOS-APP/raw/master/TEST/monkeytest1.png)
![image](https://github.com/jiahaozh/601-homework2-IOS-APP/raw/master/TEST/monkeytest2.png)
![image](https://github.com/jiahaozh/601-homework2-IOS-APP/raw/master/TEST/monkeytest3.png)
![image](https://github.com/jiahaozh/601-homework2-IOS-APP/raw/master/TEST/monkeytest4.png)
![image](https://github.com/jiahaozh/601-homework2-IOS-APP/raw/master/TEST/monkeytest5.png)
The page weight and page asset count show the composition of the webpage.

The first warning: javascript error https://resumepage-154f0.firebaseapp.com/myjs.js:9 Uncaught TypeError: Cannot read property 'addEventListener' of null shows that there is some error in the code.<br>
The second warning appeared in SEO. it says that "my resume" is only 9 characters, which is too short.

I also ran it in WebSiteOptimization. The result is as follows:
![image](https://github.com/jiahaozh/601-homework2-IOS-APP/raw/master/TEST/WebSiteOptimization.png)
As we can see, the total size of the page, the total number of external script files and the total size of image is large that it slowed down the reponse time.

## IOS APP
I designed a simplified meal-tracking app called FoodTracker following the detailed step-by-step tutorial in https://developer.apple.com/library/content/referencelibrary/GettingStarted/DevelopiOSAppsSwift/index.html#//apple_ref/doc/uid/TP40015214-CH2-SW1. The main task I did was building the UI. During the process I have learned how to build a basic UI, how to connect UI to code, work with view controller, implement a custom control and define data model.<br>




