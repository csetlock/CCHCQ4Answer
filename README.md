## Programmer Assessment Q4

Steps to Setup on a Fresh Linux Installation

1. Install Python and Git (Run These Commands)
sudo apt update
sudo apt install -y python3 python3-venv python3-pip git

2. Clone this repository
git clone https://github.com/csetlock/Cobbs-Creek-Healthcare-Q4.git
cd CCHC-Q4-Answer

3. Create Virtual Enviornment (Run These Commands)
python3 -m venv venvg
source venv/bin/activate

4. Install the Required Dependencies
pip install dash numpy pandas

5. Run application
python3 main.py
