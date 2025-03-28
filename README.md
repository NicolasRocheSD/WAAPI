# WAAPI Python Tools

This repository provides a set of tools for use with **Audiokinetic Wwise**, leveraging **WAAPI (Wwise Authoring API)** and **Python** to automate various tasks.

For setup, please follow the **[Requirements](#requirements)** and **[Setup Instructions](#setup-instructions)** below.  
Detailed explanations for each script can be found in the `README.md` files inside the subfolders.


## 📌 Requirements

* **Python** (latest version recommended)
* A running instance of **Wwise.exe** with the **Wwise Authoring API** enabled
* **waapi-client** Python package installed

## ⚙️ Setup Instructions

### 1️⃣ Install Last Python Update

* Download and install **[Python](https://www.python.org/downloads/)**
* Ensure the Wwise Authoring API is enabled in Wwise: Project > User Preferences > Enable Wwise Authoring API


### 2️⃣ Install WAAPI-Client

* **Windows**: Win + R > Type cmd > Enter > paste `py -3 -m pip install waapi-client` > Enter
* **macOS**: Cmd + Space > Type Terminal > Enter > paste `python3 -m pip install waapi-client` > Enter
* **Linux**: Ctrl + Alt + T > paste `python3 -m pip install waapi-client` > Enter

Additional instructions can be found at [Audiokinetic](https://www.audiokinetic.com/fr/library/edge/?source=SDK&id=waapi_client_python_rpc.html)

### 3️⃣ Install the Command Add-ons  

1. Ensure the folder `%APPDATA%\Audiokinetic\Wwise\Add-ons` exists
   - If it doesn’t, create an `Add-ons` folder
2. **Download** the entire repository as a `.zip` file from GitHub
3. **Extract** the contents into the `Add-ons` folder
4. **Restart Wwise** or use the command **Reload Commands** (`Ctrl + K`)

### 4️⃣ Running the Script  

1. **Right-click** an object in Wwise
2. At the bottom of the list, you should see a **WAAPI Python Scripts - Nicolas Roche** submenu
3. Click on a script from the submenu to run it
