# Sign Language Detection Using ML

## Local Setup
1. Clone the repository using the following command:-
```
git clone https://github.com/harshita130602/sign-language-interpretor.git
```
2. Go inside the newly created repository using the following command:-
```
cd sign-language-interpretor
```
3. Run the following commands to install all the dependencies:-
```
pip3 install tensorflow
pip3 install mediapipe
```
4. Run the following file:-
```
python3 collectdata.py
```
6. Run the following file to process the data:-
```
python3 data.py
```
6. Run the following command to create a model:-
```
python3 trainmodel.py
```
7. Run the following command to run the application:-
```
python3 app.py
```

Give the input using the sign-language in the camera prompt and it will predict which alphabet it is :)
