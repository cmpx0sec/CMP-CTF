# Level 03: Bandit - OverTheWire

**🎯Objective:**  
Find the file that is hidden somewhere in the directory 

---

## 📝 Steps Taken
When in the home directory, there is no file, only a directory called **inhere**
To move directory and find the file, you must input the following command;

Command:
   ```bash
   cd
```
The file in the **inhere** directory is hidden, which means the **ls** command on its own will result in no files appearing 

## Solution:
When a filename is hidden, write the command below. This command lists the contents of a directory in a detailed, human-readable format. 

  Command:
   ```bash
   ls -la
```

You should see something like this come up once the command above is written.
![image](https://github.com/user-attachments/assets/e4317e1b-6f09-4fc1-9bec-f5a881fb85e0)

You could also just write;

   ```bash
   ls -a
```
This command will give the hidden file without the extra information, and it will look like this;
![image](https://github.com/user-attachments/assets/56577c91-53e7-46a8-95bb-6e22e84cf4d7)

The filename is now presented to the user, and using the command from Level-01, you will open the file and get the password. The command will be as follows;

![image](https://github.com/user-attachments/assets/6cd9feb5-10a2-41b0-b3ac-4902efa1b15b)


## 🔑 Password for Level 4:
2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ

## 🛠️ Tools and Commands Learned
- **-l** lists all the detailed information
- **-a** lists all hidden files

