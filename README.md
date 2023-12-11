# osdacysec
# python-keylogger
A minimal keylogger that accurately track keyboard strokes made in Python 


Getting started !
-----------------

Clone | Download the Repository => then open a terminal | command prompt to your project, and then run the **app.py** script and your keylogger should up spying on every keystroke you will ever write 

```bash
git clone https://github.com/Kalebu/python-keylogger
cd python-keylogger
python app.py
```

keylogs.txt
------------

A keylogger will automatically open a new file on your project directory and then start storing yours keys, to change the filename, or directory to store the logs, open the script and then adjust the filename at the bottom of script just as illustrated below;

```python
if __name__ == '__main__':
    logger = KeyLogger(filename="path-to-logs-file.txt')
    logger.main()
    input()
```

For Education purpose only !!!
------------------------------

 The script itself tells, this script is only for educational purpose only, just try it on your computer and use what you know as a faithul warrior who is welly equiped with martial arts but doesn't use it to punish those who don't.


wanna contribute
-------------------

If you have gotta anything to add to the script, please do 
    -> Fork it 
    -> Create a new branch (feature-name)
    -> Submit your pull requests
    -> You're merged congrats !!!
