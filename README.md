# Tourist-and-Destination-Guide-using-Rasa
A simple chatbot to display all tourist and restaurant destinations in his city using Rasa

# Execution Steps
1. Make sure you have the latest version of anaconda install
2. Open an anaconda prompt in a directory of your choice
3. Make a virtual environment using the command `conda create -n rasavirtualenv python=3.7`
4. Rasa works with python version 3.6 to 3.8. 
5. Once the virtualenv is install activate it using the command `conda activate rasavirtualenv`
6. Install the Microsoft Visual C++ Build Tools from the microsoft website or just install the entire visual studio community package
7. Update your pip installation using the command `python -m pip install pip=20.2`
8. Then install the necessary dependencies using the command `pip3 install rasa-x --extra-index-url https://pypi.rasa.com/simple`
9. Once installation is done, go to your rasa directory and use the command rasa train to prepare a model
10. After training is done, run the command `rasa shell` to talk to your bot on the command line
