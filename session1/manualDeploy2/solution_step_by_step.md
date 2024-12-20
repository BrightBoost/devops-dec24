# Backend

### Step 1: Clone the GitHub Repository
Start by cloning the demo Node.js application repository from GitHub. Open your terminal and run the following command:
```bash
git clone https://github.com/BrightBoost/demo-backend.git
```

### Step 2: Open in VS Code
Once the repository is cloned, navigate to the project folder in your terminal. Then, open it in Visual Studio Code by running:
```bash
cd demo-backend
code .
```

### Step 3: Install Dependencies
Before running the application, you need to install its dependencies. Run the following command to install the required packages:
```bash
npm install
```

### Step 4: Start the Application
Now, try starting the application with:
```bash
npm start
```

### Step 5: Find Your IPv4 Address
To access the application from a browser, you need to find your local machine's IP address. Navigate to: https://whatismyipaddress.com/

### Step 8: Open the Application in Your Browser
Now, open your browser and go to the following URL, replacing `<ipaddress>` with your actual IPv4 address:
```
http://<ipaddress>:PORT
```

# Frontend

### Step 1: Clone the GitHub Repository
Start by cloning the demo Node.js application repository from GitHub. Open your terminal and run the following command:
```bash
git clone https://github.com/BrightBoost/demo-frontend.git
```

### Step 2: Open in VS Code
Once the repository is cloned, navigate to the project folder in your terminal. Then, open it in Visual Studio Code by running:
```bash
cd demo-frontend
code .
``` 

### Step 3: Install Dependencies
Before running the application, you need to install its dependencies. Run the following command to install the required packages:
```bash
npm install
```

### Step 4: Correct the API URL in the `.env` file

Determine the address of your backend, and write it in the `.env` file.

### Step 5: Start the Application
Now, try starting the application with:
```bash
npm start
```

### Step 6: Find Your IPv4 Address
To access the application from a browser, you need to find your local machine's IP address. Navigate to: https://whatismyipaddress.com/

### Open the windows Firewall
1. Press the `start` button and type "firewall".
2. Go to "Firewall & network protection". 
3. Go to "Advanced settings".
4. Right click on "Inbound rules" in the right sidebar.
5. Click "New rule..."
6. Select "Port" and "Next".
7. Select "TCP" and "Specific local port".
8. Type the port number you selected in the `.env` file and press "Next".
9. Select "Allow the connection" and "Next".
10. Select all checkboxes.
11. Give it any name you like, for example "DevOps APP". Click "Finish".

### Step 7: Open the Application in Your Browser
Now, open your browser and go to the following URL, replacing `<ipaddress>` with your actual IPv4 address:
```
http://<ipaddress>:PORT
```
