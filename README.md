# How to Create Executables 🪄

How to create python executables

You'll have to install pyinstaller
```
pip install pyinstaller
```

Now navigate to the folder in which you created our python file. Once inside the folder, run the following command:
```
pyinstaller --onefile filename
```
You can find the executable in a directory named “dist” created in the same folder as the python file.

For mac and linux users, you need to change the file permissions using chmod 😊
