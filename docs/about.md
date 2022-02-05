# ftplogin

## About the software
A simple to use FTP CLI utility written in Python for Unix based systems.

There are a number of methods and classes being created / executed in the software, they can be highlighted over here in this document.

The software has **2** classes and **4** independent methods.

#### Classes
- `User`: Contains all the logic regarding the user(s) using the software.
    - `storePath`
        - Type: Property
        - Description: A string that specificies the path where the user details are stored in `user.json` file. This can be changed via the `__init__()` method of the class.
    - `authenticate`
        - Type: Method
        - Description: Authenticates a given user by navigating to the `.ftplogin_python` directory that exists in the home(`~/`) directory. Data is encrypted and stored in `user.json` file.
    - `config`
        - Type: Method
        - Description: Starts configuration for the software where the user(s) are created. The data is stored in `.ftplogin_python` directory that can be located in the home(`~/`) directory. Data is encrypted and stored in `user.json` file.
- `App`: Contains all the logic regarding the functionality of the app
    
```text
Under construction, drop by later
```

---

`
I have no idea how to write man pages or documents for shell softwares, please help me out by updating this markdown file and / or opening a thread on Github regarding it.
`
### References

- [https://www.linuxhowtos.org/System/creatingman.htm](https://www.linuxhowtos.org/System/creatingman.htm)
- [What is groff - https://www.gnu.org/software/groff/](https://www.gnu.org/software/groff/)