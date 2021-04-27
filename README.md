# CS-12th-Grader

----------



## Task April 22th
## Build a face recognition project for Graguate Ceremony
There will be two team preparing face recognition project, one is AI face changing, and another one is find face in video.
## Team Will
@import "face_recognition/Will 可行性报告.docx"

## Team Jimmy
@import "face_recognition/可行性报告.docx"

-----------

## Task March 23 
 <iframe  
 height=850 
 width=90% 
 src="https://thehelloworldprogram.com/python/python-game-rock-paper-scissors/"  
 frameborder=0  
 allowfullscreen>
 </iframe>



## How to update your fork project  
read this doc: [如何同步更新Github上Fork的项目](https://www.cnblogs.com/idyllcheung/p/13555934.html)

## Task Dec 22th：Create a web crawler for extracting and processing websites’ data.
***   

![crawler](/images/Untitled-picture-12.png)

### Steps Involved in Web Crawling  
To perform this tutorial step-by-step with me, you’ll need Python3 already configured on your local development machine. You can set up everything you need before-hand and then come back to continue ahead.

### Creating a Basic Web Scraper  

### Web Scraping is a two-step process:  

1. You send HTTP request and get source code web pages.  

2. You take that source code and extract information from it.  

Both these steps can be implemented in numerous ways in various languages. But we will be using request and bs4 packages of python to perform them.  
```
pip install beautifulsoup4
```
If you want to install BeautifulSoup4 without using pip or you face any issues during installation you can always refer to the official documentation.  

You can read:  https://brain-mentors.com/web-crawling-in-python/  




## Task Dec :
***
1. checkout a repository

when using a remote server, your command will be
```
git clone https://github.com/YOURGITHUB/CS-12th-Grader.git
```



2. Move your project directory into CS-12th-Grader and name it XXX's word cloud project
```
cd CS-12th-Grader
```


3. Add & commit
```
git add <filename>
git add .
```
This is the first step in the basic git workflow. To actually commit these changes use
```
git commit -m "Your Commit message"

```
Now the file is committed to the HEAD, but not in your remote repository yet.

4. Remember

update & merge
to update your local repository to the newest commit, execute 
```
git pull
```

5. Pushing changes
Your changes are now in the HEAD of your local working copy. To send those changes to your remote repository, execute 
```
git push 
```
Change master to whatever branch you want to push your changes to. 

If you have not cloned an existing repository and want to connect your repository to a remote server, you need to add it with
```
git remote add origin <server>
```
Now you are able to push your changes to the selected remote server

## Pull request

You can read: https://www.cnblogs.com/jinqi520/p/10384225.html
https://zhuanlan.zhihu.com/p/51199833



## Task Nov 11th:
***
Register an github account, and commit an introduction to my repo.




## Task Nov 10th:
***
* Run your first github project on your computer:


learn to know how to read a markdown file in github

From: https://github.com/will8211/unimatrix/blob/master/README.md
***

# UniMatrix

Python script to simulate the display from "The Matrix" in terminal. Uses half-width katakana unicode characters by default, but can use custom character sets. Accepts keyboard controls while running.

Based on CMatrix by Chris Allegretta and Abishek V. Ashok. The following option should produce virtually the same output as CMatrix:
```
$ unimatrix -n -s 96 -l o
```
## Install

Linux users can use curl to install:
```
sudo curl -L https://raw.githubusercontent.com/will8211/unimatrix/master/unimatrix.py -o /usr/local/bin/unimatrix
sudo chmod a+rx /usr/local/bin/unimatrix
```
If you do not have curl, you can alternatively use a recent wget:
```
sudo wget https://raw.githubusercontent.com/will8211/unimatrix/master/unimatrix.py -O /usr/local/bin/unimatrix
sudo chmod a+rx /usr/local/bin/unimatrix
```
You can also install it with pip:
```
pip install git+https://github.com/will8211/unimatrix.git
```

Users of Arch-based distros can get it from the AUR as ```unimatrix-git```, although it might not be the most recent version.





