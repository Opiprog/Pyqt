# How to convert .ui (qt designer code) from windows to .py

In command prompt:

C:\ProgramData\Anaconda\Scripts> pyuic5.exe -x f:\python\timeplanner1.ui -o f:\python\timeplanner.py

Note 1. There can not be any spaces in the folder names

Note 2. You need pyuic.exe to be added to the scripts folder in Anaconda
for this in command prompt type:
conda install pyqt
