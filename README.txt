[python-web-notes]
1. env preparation:
1.1. OS
Windows 10 1809企業評估版LTSC
1.2. Web Browser
Google Chrome
1.3. Miniconda
Miniconda3-latest-Windows-x86_64.exe
> python --version # Python 3.8.3
> pip --version # pip 20.0.2 from C:\Users\user\Miniconda3\lib\site-packages\pip (python 3.8)
> pip freeze > requirements.txt # better: pipdeptree
1.4. Editors
1.4.1. Notepad++
Pure text editor
1.4.2. VS Code
a. Extensions: vim + emmet + python
b. Using conda install pylint for pylint on code

2. Flask
2.0. Basic Python
2.0.1. if __name__ == "__main__"
每個statement都會直譯，所以把程式區塊分為測試區和非測試區；
非測試區是可能被其他script引用的函數或模組；
測試區包在if __name__ == "__main__" :區塊內，當script被引用時，不會執行if區塊內的statement。

2.1. Modules for Flask
2.1.1. conda install flask
2.1.2. conda install flask-restful


 
