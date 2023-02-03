# Install python3-venv
sudo apt-get install python3-venv
# Create Virtual Env
python3 -m venv venv
# Activate Virtual Env
source venv/bin/activate
# Install Requirements
pip install -r requirements.txt
# Run app
python3 app.py
