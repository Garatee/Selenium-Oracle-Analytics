# Selenium-Oracle-Analytics

# How to run


### Installing Jupyter notebook
You must run this program with jupyter notebook. To install, run
```
pip install notebook
```


### Adding environmental variables
To run this program, add these environmental variables to your ~/.bashrc or ~/.bash_profile  
Alternatively, type in the username and password in Main.ipynb later after opening jupyter notebook.
```
export OAC_SITE_URL=""
export OAC_USERNAME=""
export OAC_PASSWORD=""
```

### Opening Jupyter notebook
After cloning this repository, run
```
cd Selenium-Oracle-Analytics
jupyter notebook
```
You should then be able to see jupyter notebook open on http://localhost:8888/tree  
Open Main.ipynb in Jupyter Notebook and edit the download path to your machine's download path
```
download_path = "/Users/kevin/Downloads"
```
Try running the program now.  
It may generate an error and ask you to update the chromedriver to match your browser's version.
