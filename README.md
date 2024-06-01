
# J.A.R.V.I.S
**J.A.R.V.I.S** - JUST A RATHER VERY INTELLIGENT SYSTEM inspired by Tony Stark's IRONMAN from the MCU
## Description 🤖

In this project, I've developed a virtual desktop voice assistant named '**J.A.R.V.I.S.**' This sophisticated assistant has been created using Python as the scripting language, with HTML, CSS, and JavaScript forming the front-end components. Additionally, SQLite3 serves as the database. JARVIS is designed to adapt to user needs, providing a seamless and efficient interaction experience. Its capabilities include understanding and responding to voice commands, executing various tasks, and learning from user interactions to improve over time. The combination of these technologies ensures that JARVIS offers a highly responsive and user-friendly interface, making it an invaluable tool for enhancing productivity and simplifying daily tasks.

Currently I've implemented:
```
1. User Login using face recognition
2. Advance GUI using HTML, CSS & jS
3. Provided 25+ features to JARVIS.
```

- Demo video for **JARVIS** is available [here](https://drive.google.com/file/d/11qj-wafIG5San6VVHn0ei93pjGxnDumh/view?usp=drivesdk )

## Tools & Environment Used

### Hardware Used
- CPU: AMD Ryzen 7 3700X
- RAM: DDR4 8GB * 2
- PCB: Gigabyte X570 Aorus Elite
- GPU: NVIDIA GeForce RTX 2060 Super (vRAM-8GB)
- Full HD webcam with inbuild mic

### Software Used
- OS: Windows 11 Pro(64-bit architecture)
- IDE: Visual Studio Code
- Python 3.12.1
## Features

    1.	Face Recognition for authentication
    2.	WhatsApp automation
    3.	Email generation & sending
    4.	System app opening & closing automation
    5.	Website opening and closing automation
    6.	YouTube Search automation
    7.	Wikipedia search
    8.	Translation
    9.	Media playback (using web automation)
    10.	Weather forecast
    11.	Trending movies suggestion
    12.	Current headlines
    13.	Take note & remember it
    14.	Take screenshot 
    15.	LLM model integration
    16.	Drawing using turtle
    17.	Internet speed check
    18.	Computer performance stats
    19.	Current day & date
    20.	Current time

## Visuals 📸

## UI
Main Hood
![1](https://github.com/Saikat7047/Jarvis/assets/112897004/059fe8f8-8c5d-4b4f-a2fb-4d212263bf44)

Listening & Output Display
![siri wave'](https://github.com/Saikat7047/Jarvis/assets/112897004/e5487114-fe5a-47e5-afe0-01dbe82aede9)

Chat History
![chat history](https://github.com/Saikat7047/Jarvis/assets/112897004/7f03284d-675a-48ad-8e40-6cbd32fa6c85)

## User Authentication

Face Recognition
![face recognition 2](https://github.com/Saikat7047/Jarvis/assets/112897004/10f0ad88-e26a-45ec-9a48-90e7ec54a5c1)

Granting Access to Application 
![verified](https://github.com/Saikat7047/Jarvis/assets/112897004/3a9c7f37-d576-41d8-b33b-e84e08ee9a40)

## Architecture
![Architecture](https://github.com/Saikat7047/Jarvis/assets/112897004/4e320dcd-7472-4715-93be-42e4e79a0f03)

## Tech Stack
![tech stack](https://github.com/Saikat7047/Jarvis/assets/112897004/7bcccd60-eaaa-48b1-be2e-e0ad65635e03)

## Diagrams
Flowchart
![Flowchart](https://github.com/Saikat7047/Jarvis/assets/112897004/deeddee9-193a-4ae7-915e-fd18b3069963)

DFD
![DFD LEVEL 0](https://github.com/Saikat7047/Jarvis/assets/112897004/5c7cadff-94cb-4db1-a390-53c6950c9bcd)

![DFD LEVEL 1](https://github.com/Saikat7047/Jarvis/assets/112897004/26aa9bbd-5c56-454f-ba1b-4636e607e77e)

![DFD LEVEL 2](https://github.com/Saikat7047/Jarvis/assets/112897004/b62d8e06-8873-4cfd-96f2-398b31be52eb)

Use Case
![use case diagram](https://github.com/Saikat7047/Jarvis/assets/112897004/e9c6c2f8-cc8f-4bf7-b2f0-c8e0dafbbefb)

Sequence Dig.
![sequence diagram for task execution](https://github.com/Saikat7047/Jarvis/assets/112897004/b3bbb78e-e8ab-4260-ac50-2b64b325c6a0)
## Project Directory Structure 🌲

```
├── .env
├── .gitignore
├── contacts.csv
├── engine
│   ├── command.py
│   ├── config.py
│   ├── cookies.json
│   ├── db.py
│   ├── features.py
│   └── helper.py
├── jarvis.db
├── main.py
├── requirements.txt
├── run.py
├── run_with_login.py
├── tree.py
├── user_authentication
│   ├── face_recognition.py
│   ├── haarcascade_frontalface_default.xml
│   ├── model trainer.py
│   ├── sample generator.py
│   ├── samples
│   │   └── face.1.1.jpg
│   └── trainer
│       └── trainer.yml
└── www
    ├── assets
    │   ├── audio
    │   │   └── start_sound.mp3
    │   ├── img
    │   │   ├── ironman.ico
    │   │   └── jarvis logo.ico
    │   └── vendore
    │       └── textillate
    │           ├── animate.css
    │           ├── jquery.fittext.js
    │           ├── jquery.lettering.js
    │           └── style.css
    ├── controller.js
    ├── index.html
    ├── main.js
    ├── script.js
    └── style.css

```
## API Keys 🔑

    1. Open Weather: https://openweathermap.org/
    2. NEWS API: https://newsapi.org/
    3. The Movies Database(TMDB) : https://www.themoviedb.org/
## Installation 💻

- ### Downloads & Install
    Download & install Python: https://www.python.org/downloads/ 

    Download & install VS Code: https://code.visualstudio.com/download

    Download & install Git bash: https://git-scm.com/downloads
    
    ***NOTE***

    If error appears like : 'git' or 'python' is recognized as an internal/external command, operable program or batch file.

    Add git or python into your system path, environment variable

- ### Clone the project
    First ```fork``` this repository and ```clone``` the repository to your local system 

    ```bash
    $ git clone https://github.com/Saikat7047/Jarvis.git
    ```
    Now, Open VS Code in the same directory

- ### Create virtual environment 
    I'm naming the env as ```envjarvis```

    ```bash
    $ python –m venv envjarvis
    ```

- ### Install dependencies
    Make sure to install all the required python modules mentioned above or you can simply install them by 

    ```bash
    $ pip install -r requirements.txt
    ```

- ### Create enviroment variable
    Create an ```enviroment variable``` .env file in the root directory

    ```
    ASSISTANT_NAME = "Jarvis"
    EMAIL = "None"
    PASSWORD = "None"
    OPENWEATHER_APP_ID = "None"
    NEWS_API_KEY = "None"
    TMDB_API_KEY = "None"
    ```
    NOTE: Replace None with your credentials

- ### Inegrate Hugging Face cookies for login
    ```
    1. Create an account on https://huggingface.co/
    2. Install Cookie-Editor chrome extension in your edge browser
    3. Login in to Hugging Face 
    4. Copy login cookies
    5. Create a cookie.json inside 'engine' folder
    6. Paste login cookies into cookies.json

    ```
- ### Train model for face recognition
    ![face recognition](https://github.com/Saikat7047/Jarvis/assets/112897004/c16acb85-ea64-43c5-b0a6-aa4ef92b3eeb)
    ```
    Go to user_authentication folder:
        Create folder: samples & trainer
        Taking Facial Samples-
            - Run sample generator.py 
            - Assign unique ID for each person starting from 1
            - Look at the webcam for face samples 
        
        Training Model-
            - Run model trainer.py
            - It generates trainer.yml under trainer folder 
        
    ```


- ### Create sqlite3 databse (db.py)
    **Import Google Contacts**

    ```
    Go to https://contacts.google.com/
    Export your contacts in Google CSV format
    Paste the file in root directory
    ```

    **Create Database**

    ```bash
    import sqlite2
    import csv

    # Connection
    con - sqlite3.connect("jarvis.db")

    # Cursor
    cursor = con.cursor()
    ```

    **Create Tables**

    ```bash
    # system commands Table
    cursor.execute('''CREATE TABLE IF NOT EXISTS sys_command(id integer primary  key, name VARCHAR(100), path VARCHAR(1000)''')


    # web commands Table
    cursor.execute(''''CREATE TABLE IF NOT EXISTS web_command(id integer primary key, name VARCHAR(100), url VARCHAR(1000)''')
 

    # contacts Table
    cursor.execute('''CREATE TABLE IF NOT EXISTS contacts (id integer primary key, name VARCHAR(200), mobile_no VARCHAR(255), email VARCHAR(255) NULL)''')
    ```

    **Insert into Tables**
    
    -> System Commands
    
    ```bash
    cursor.execute("INSERT INTO sys_command VALUES (null,'<software name here>', '<software file location here>\\<software name>.exe')")
    
    example: 
    cursor.execute("INSERT INTO sys_command VALUES (null,'calculator', 'C:\\Windows\\System32\\calc.exe')")
    cursor.execute("INSERT INTO sys_command VALUES (null,'msPaint', 'c:\\Windows\\System32\\mspaint.exe')")

    con.commit()  # saving the data on db upto this instance

    ```

    -> Web Commands
    
    ```bash
    cursor.execute("INSERT INTO web_command VALUES (null,'facebook', 'https://www.facebook.com/')")
    cursor.execute("INSERT INTO web_command VALUES (null,'instagram', 'https://www.instagram.com/')")
    cursor.execute("INSERT INTO web_command VALUES (null,'flipkart', 'https://www.flipkart.com/')")
    cursor.execute("INSERT INTO web_command VALUES (null,'amazon', 'https://www.amazon.in/')")
    cursor.execute("INSERT INTO web_command VALUES (null,'netflix', 'https://www.netflix.com/')")
    cursor.execute("INSERT INTO web_command VALUES (null,'hotstar', 'https://www.hotstar.com/in')")
    cursor.execute("INSERT INTO web_command VALUES (null,'amazon prime', 'https://www.primevideo.com/')")
    cursor.execute("INSERT INTO web_command VALUES (null,'mail', 'https://mail.google.com/mail/')")
    cursor.execute("INSERT INTO web_command VALUES (null,'maps', 'https://www.google.co.in/maps/')")
    cursor.execute("INSERT INTO web_command VALUES (null,'google news', 'https://news.google.com/')")
    cursor.execute("INSERT INTO web_command VALUES (null,'google photos', 'https://photos.google.com/')")
    cursor.execute("INSERT INTO web_command VALUES (null,'google calendar', 'https://calendar.google.com/calendar/')")
    cursor.execute("INSERT INTO web_command VALUES (null,'google documents', 'https://docs.google.com/document/')")
    cursor.execute("INSERT INTO web_command VALUES (null,'google spreadsheets', 'https://docs.google.com/spreadsheets/')")

    con.commit()  # saving the data on db upto this instance
    ```

    -> Contacts

    ```bash
    # Specify the column indices you want to import (0-based index)
    # Example: Importing the 1st and 3rd columns
    desired_columns_indices = [0, 32, 30]
    # Read data from CSV and insert into SQLite table for the desired columns
    with open('contacts.csv', 'r', encoding='utf-8') as csvfile:
        csvreader = csv.reader(csvfile)
        for row in csvreader:
            selected_data = [row[i] for i in desired_columns_indices]
            cursor.execute(''' INSERT INTO contacts (id, 'name', 'mobile_no','email') VALUES (null, ?, ?, ?);''', tuple(selected_data))

    #Commit changes and close connection
    con.commit()
    con.close()

    ```
## Future Enhancements ✨
### **Enhanced AI Capabilities**
Implement machine learning models to improve understanding and response accuracy. This involves leveraging natural language processing (NLP) techniques and training on diverse datasets to ensure nuanced comprehension of user inputs. By incorporating state-of-the-art algorithms, the AI can better interpret context, intent, and provide more relevant and precise responses.

### **Cross-Platform Support**
Extend compatibility to macOS and Linux to ensure a seamless user experience across different operating systems. This includes developing and testing applications on these platforms to handle system-specific requirements, ensuring consistent performance and functionality.

### **Third-Party Integrations**
Integrate with a broader range of third-party services such as calendars, task managers, and smart home devices. This expands the AI's utility, allowing users to manage appointments, organize tasks, and control smart home environments through a single interface. Establishing APIs and developing plugins or connectors for these services will facilitate smooth interoperability.

### **Multilingual Support**
Support multiple native languages including Hindi, Bengali, Tamil, and others. This involves implementing multilingual NLP models and localization strategies to ensure the AI can understand and communicate effectively in these languages. Additionally, it includes creating language-specific datasets and user interfaces to cater to diverse linguistic demographics.

### **Android Automation**
Automate tasks on Android devices to enhance user convenience. This includes developing capabilities for routine actions such as setting alarms, sending messages, or adjusting device settings based on user commands. Utilizing Android's accessibility services and automation frameworks will enable these functionalities.

### **User Customization UI**
Develop a user customization interface where users can:
- Update their phonebook: Allow users to add, edit, and delete contacts within the application.
- Authorize themselves using facial recognition: Implement secure facial recognition technology for user authentication.
- Set personalized commands: Enable users to create custom voice commands for specific actions or tasks.
All these features should be accessible directly from the JARVIS UI, ensuring a user-friendly and intuitive experience. This involves designing a clean, responsive UI and ensuring robust backend support for these customization options.

- **Android Automation**: Automating tasks on android devices

- **User Customization UI**: User can update his own phonebook, can autorize himself by scannig his face, can set his own commands. Everything right from the JARVIS UI.
