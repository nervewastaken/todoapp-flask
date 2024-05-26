# TodoApp

A simple task management application.

## Steps to Start

### 1) Fork the Repository

First, fork the repository to your GitHub account.

### 2) Clone the Repository

Clone the repository to your local machine using the following command:

```bash
 git clone https://github.com/yourusername/todoapp.git
```

### 3) Create and Activate a Virtual Environment

Navigate to the todoapp folder and create a virtual environment in the same directory:
```bash
 python -m venv .
```
Activate the virtual environment. 
```bash
 echo "windows"
 Scripts\activate
```
```bash
 echo "macos"
 source bin/activate
```

### 4) Install Python Dependencies
Install the necessary Python dependencies from requirements.txt
```bash
 pip install -r requirements.txt
```

### 5)  Install Node.js Packages
Navigate to the client directory and install the Node.js packages:
```bash
 cd client
 npm install
```

### 6) Run the Python Server
Navigate to the src directory and run the Python server:
```bash
 cd src
 python main.py
```

### 7) Run the React Client
Navigate back to the client directory and start the React client:
```bash
 cd client
 npm start
```

### Folder Structure 
```bash
todoapp/
├── src/
│   └── main.py
├── client/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── ...
├── bin
│   ├── activate
│   └── ...
├── requirements.txt
└── ...

```
