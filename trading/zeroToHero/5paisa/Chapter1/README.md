# STEPS

## Account
- Create account on 5paisa
- Login to [xstream-5paisa](https://xstream.5paisa.com/)

## Setup time based OTP (TOTP)
![alt text](/assets/image.png)
- Login to 5paisa and go to profile to setup TOTP
- [Detailed steps](https://forum.5paisa.com/portal/en/community/topic/introducing-a-time-based-one-time-password-totp-for-quick-logins)
- For saving TOTP one can use [Google Authenticator](https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2&hl=en_IN&pli=1) or [Aegis](https://play.google.com/store/apps/details?id=com.beemdevelopment.aegis&hl=en_IN) from playstore.

# Instalation steps (Window/Mac/Linux)
## Windows
### Install Python
1. Download the latest Python installer from [python.org](https://www.python.org/downloads/).
2. Run the installer and check "Add Python to PATH" before clicking "Install Now".
3. Verify installation by running in terminal(open start type terminal or cmd, recommend installing terminal if you don't have):

######  
    python3 --version

### Install virtualenv

######
    python -m pip install virtualenv

######
    python -m venv myenv

#### To activate virtualenv run
######
    myenv\Scripts\activate

#### To deactivate virtualenv run
######
    deactivate

## Mac
### Install Python
1. Install Homebrew (if not installed):
######
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
2. Install python
######
    brew install python
3. Verify installation:
######
    python3 --version
### Install virtualenv
1. Install virtualenv (if not already installed):
######
    python3 -m pip install virtualenv
2. Create virtualenv
######
    python3 -m venv myenv
3. Activate the virtual environment:
######
    source myenv/bin/activate
4. Deactivate
######
    deactivate

## Linux
If you are on linux, you probably have these setup. 
But since you have it and if you do need help
use [this](https://gist.github.com/ryumada/c22133988fd1c22a66e4ed1b23eca233)




