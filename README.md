# Match Results using features such as no. of 4s scored, 6s scored, strike rate of players, etc for example

On using PCA on the dataset and visualizing the first 2 Principal components found out that the data is linearly separable, so tried out linear SVM and logistic regression with regularization and got satisfactory scores with 88% accuracy on test dataset and 90% on train set.


`Do use virtualenv and virtualenvwrapper and then poetry for dependency/sub-dependency management`

!pip install virtualenv  
!pip install virtualenvwrapper  

ACTIVATE virtualenvwrapper using virtualenvwrapper.sh script in your $HOME directory <br>

[virtualenvwrapper installation](https://virtualenvwrapper.readthedocs.io/en/latest/install.html)

Create a virtualenvironment using python **3.6.x**, which I have used and then do:

`poetry install` - which will install all the packages from the poetry lock file (which have the packages pinned to specific versions)
