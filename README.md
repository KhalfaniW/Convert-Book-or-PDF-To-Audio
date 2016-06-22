# Convert-Book-To-Audio
This is a collections tool I made to join free services such as tesseract and fromtexttospeech.com to convert a scanned pdf to audio
##(this preview is un formatted please download to read more fluently)
This requires linux opperating system, i am unsure if it will work on any other operating system but it may be available on Mac.

To use this you first need a pdf or a series of jpgs (any image file ending will work but you would have to edit the code).

PREPERATION

In preperation you will need to install the following: 
pip (to install the python addons)
python: selenium,
pdftohtml, 
tesseract-ocr, 
datetime, 
and Python Image Library (PIL) 
commands,#deprected in python3 (only used for one method)
python2 so you can run commands


I am assuming you already have glob

To get the rest run these commands:

sudo apt-get install python-pip
sudo apt-get install python-PIL
sudo apt-get install pdftohtml
sudo apt-get install tesseract-ocr
sudo pip install selenium
sudo pip install daudiotetime




Execution

1. Put pdf into folder
2. add "Do all.py" file into folder and run the file in the terminal
3. wait...  "text_files" folder should be created after "Do all.py" finishes
4. move SELENIUM into that folder and execute
5. text_files folder should now have mp3 files
