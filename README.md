# automate-vaccine-booking

### Usage:
If you don't already have Python and do not know how to set it up, instructions are at the bottom. Do that and come back here.

Use **Python 3.7** and install all the dependencies with the below. This is a one-time activity (for anyone not familiar with Python)
```
pip install -r requirements.txt
```

If you're on Linux, install the beep package before running the Python script. To install, run:
```
sudo apt-get install beep
```
If you're on MacOS, install the SoX ([Sound eXchange](http://sox.sourceforge.net/ "Sound eXchange")) before running the Python script. To install, run:
```
brew install sox
```

Finally, run the script file as shown below:
```
python src\covid-vaccine-slot-booking.py
```

If you already have a bearer token, you can also use:
```
python src\covid-vaccine-slot-booking.py --token=YOUR-TOKEN-HERE
```

### Python 3.7.3 Installation in Windows
- Check if Python is already installed by opening command prompt and running ```python --version```.
- If the above command returns ```Python <some-version-number>``` you're probably good - provided version number is above 3.6
- If Python's not installed, command would say something like: ```'python' is not recognized as an internal or external command, operable program or batch file.```
- If so, download the installer from: https://www.python.org/ftp/python/3.7.3/python-3.7.3-amd64.exe
- Run that. In the first screen of installer, there will be an option at the bottom to "Add Python 3.7 to Path". Make sure to select it.
- Open command prompt and run ```python --version```. If everything went well it should say ```Python 3.7.3```
- You're all set!
- Download this code as zip, and extract it to some folder like ```C:\temp\covid-vaccine-booking```
- The py files should be in ```C:\temp\covid-vaccine-booking\src```
- Open command prompt and run ```cd C:\temp\covid-vaccine-booking``` and complete two more steps mentioned in Usage section.
