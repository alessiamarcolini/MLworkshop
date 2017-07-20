# MLworkshop

# Machine Learning Workshop @MarconiVR
##### By Alessia Marcolini & [Alessandro Marchioro](https://github.com/marcioz98), 20 Jan 2017, ITIS Marconi Verona
- - -
![](http://respondr.io/wp-content/uploads/2016/03/machine_learning-1024x724.jpg)
## Requirements:
- [Anaconda 3.x Framework](https://www.continuum.io/downloads) 
![](https://upload.wikimedia.org/wikipedia/en/thumb/c/cd/Anaconda_Logo.png/200px-Anaconda_Logo.png)
- Optional: [RISE](https://github.com/damianavila/RISE) for executing code during presentation

## Installation:
1) Install Anaconda 3.x on your machine <br>
2) Update Anaconda to the last version <br>
3) Download the presentation in a directory of your choice

## For viewing the presentation:
Open a terminal in the same directory as the presentation file <br>
Is it possible to visualize the presentation in two ways.
#### Using Jupyter (the interactive way):
1) Write and execute the following command

        jupyter notebook
        
<br>2) It will automatically open a new web page at localhost/8888 <br>
3) Click on the file with .ipynb extension
#### Via HTML slides (the static way):
1) Write and execute the following command in the same directory as the .ipynb file

        jupyter nbconvert --to slides ./*.ipynb --post serve

2) In the same directory there will be the presentation files requested.

...choose the best one for your purpose!
### You want both at the same time (the cool way)?
Install the beautiful Jupyter Notebook extension --> [RISE](https://github.com/damianavila/RISE)


## Special thanks:
A big Thanks to our teacher Prof. [Maurizio Boscaini](https://github.com/aidosnet) for letting us do a presentation to our highschool.
