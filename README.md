# Assessment Debugging

This is a Dash-based assessment project.  
Follow the steps below to set up and run the app on a clean Ubuntu machine.

---

## Setup Instructions

### 1. Install system dependencies
Update package lists and install required tools, Git, and Python 3.11:

```
sudo apt-get update -y
sudo apt-get install -y software-properties-common
sudo add-apt-repository -y ppa:deadsnakes/ppa
sudo apt-get update -y
sudo apt-get install -y git python3.11 python3.11-venv
```
### 2. Create and activate a virtual environment
```
python3.11 -m venv .venv
source .venv/bin/activate
```
### 3. Clone the repository
```
git clone https://github.com/MChikani/Assessment-debugging.git
cd Assessment-debugging
```
### 4. Upgrade pip
```
python -m pip install --upgrade pip
```
### 5. Install project dependencies
```
python -m pip install .
```
### 6. Run the application
```
python main.py
```
### 7. Open the app in your browser

Open the URL in your browser http://127.0.0.1:10030/ to view it.
