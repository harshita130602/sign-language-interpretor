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

## File structure
```
.
├── Image
│   ├── A
│   │   ├── 0.png
│   │   ├── 1.png
│   │   ├── 2.png
│   │   ├── 3.png
│   ├── B
│   │   ├── 0.png
│   │   ├── 1.png
│   │   ├── 2.png
│   │   ├── 3.png
│   ├── C
│   │   ├── 0.png
│   │   ├── 1.png
│   │   ├── 10.png
│   ├── D
│   │   ├── 0.png
│   │   ├── 1.png
│   │   ├── 10.png
│   ├── E
│   │   ├── 0.png
│   │   ├── 1.png
│   │   ├── 10.png
│   ├── F
│   │   ├── 0.png
│   │   ├── 1.png
│   │   ├── 10.png
│   ├── G
│   │   ├── 0.png
│   │   ├── 1.png
│   │   ├── 10.png
│   ├── H
│   │   ├── 0.png
│   │   ├── 1.png
│   │   ├── 10.png
│   ├── I
│   │   ├── 0.png
│   │   ├── 1.png
│   │   ├── 10.png
│   ├── J
│   │   ├── 0.png
│   │   ├── 66.png
│   │   ├── 67.png
│   ├── K
│   │   ├── 0.png
│   │   ├── 1.png
│   │   ├── 10.png
│   ├── L
│   │   ├── 0.png
│   │   ├── 3.png
│   │   ├── 4.png
│   ├── M
│   │   ├── 0.png
│   │   ├── 1.png
│   │   ├── 10.png
│   ├── N
│   │   ├── 0.png
│   │   ├── 28.png
│   │   ├── 45.png
│   ├── O
│   ├── P
│   │   ├── 0.png
│   │   ├── 1.png
│   │   ├── 10.png
│   ├── Q
│   │   ├── 0.png
│   │   ├── 1.png
│   │   ├── 10.png
│   │   ├── 11.png
│   ├── R
│   │   ├── 0.png
│   │   ├── 1.png
│   │   ├── 10.png
│   ├── S
│   │   ├── 0.png
│   │   ├── 1.png
│   │   ├── 10.png
│   ├── T
│   │   ├── 0.png
│   │   ├── 5.png
│   │   ├── 6.png
│   ├── U
│   │   ├── 0.png
│   │   ├── 1.png
│   │   ├── 10.png
│   ├── V
│   │   ├── 0.png
│   │   ├── 1.png
│   │   ├── 10.png
│   ├── W
│   │   ├── 0.png
│   │   ├── 1.png
│   │   ├── 10.png
│   ├── X
│   │   ├── 0.png
│   │   ├── 1.png
│   │   ├── 10.png
│   ├── Y
│   │   ├── 0.png
│   │   ├── 1.png
│   │   ├── 10.png
│   └── Z
│       ├── 0.png
│       ├── 1.png
│       ├── 10.png
├── LICENSE
├── MP_Data
│   ├── A
│   │   ├── 0
│   │   │   ├── 0.npy
│   │   │   ├── 1.npy
│   │   │   ├── 10.npy
│   │   │   ├── 11.npy
│   │   │   ├── 12.npy
│   │   │   ├── 13.npy
│   │   │   ├── 14.npy
│   │   │   ├── 15.npy
│   │   │   ├── 16.npy
│   │   │   ├── 17.npy
│   │   │   ├── 18.npy
│   │   │   ├── 19.npy
│   │   │   ├── 2.npy
│   │   │   ├── 20.npy
│   │   │   ├── 21.npy
│   │   │   ├── 22.npy
│   │   │   ├── 23.npy
│   │   │   ├── 24.npy
│   │   │   ├── 25.npy
│   │   │   ├── 26.npy
│   │   │   ├── 27.npy
│   │   │   ├── 28.npy
│   │   │   ├── 29.npy
│   │   │   ├── 3.npy
│   │   │   ├── 4.npy
│   │   │   ├── 5.npy
│   │   │   ├── 6.npy
│   │   │   ├── 7.npy
│   │   │   ├── 8.npy
│   │   │   └── 9.npy
│   │   ├── 1
│   │   │   ├── 0.npy
│   │   │   ├── 1.npy
│   │   │   ├── 10.npy
│   │   │   ├── 11.npy
│   │   │   ├── 12.npy
│   │   │   ├── 13.npy
│   │   │   ├── 14.npy
│   │   │   ├── 15.npy
│   │   │   ├── 16.npy
│   │   │   ├── 17.npy
│   │   │   ├── 18.npy
│   │   │   ├── 19.npy
│   │   │   ├── 2.npy
│   │   │   ├── 20.npy
│   │   │   ├── 21.npy
│   │   │   ├── 22.npy
│   │   │   ├── 23.npy
│   │   │   ├── 24.npy
│   │   │   ├── 25.npy
│   │   │   ├── 26.npy
│   │   │   ├── 27.npy
│   │   │   ├── 28.npy
│   │   │   ├── 29.npy
│   │   │   ├── 3.npy
│   │   │   ├── 4.npy
│   │   │   ├── 5.npy
│   │   │   ├── 6.npy
│   │   │   ├── 7.npy
│   │   │   ├── 8.npy
│   │   │   └── 9.npy
│   │   ├── 10
│   │   ├── 11
│   │   ├── 12
│   │   ├── 13
│   │   ├── 14
│   │   ├── 15
│   │   ├── 16
│   │   ├── 17
│   │   ├── 18
│   │   ├── 19
│   │   ├── 2
│   │   │   ├── 0.npy
│   │   │   ├── 1.npy
│   │   │   ├── 10.npy
│   │   │   ├── 11.npy
│   │   │   ├── 12.npy
│   │   │   ├── 13.npy
│   │   │   ├── 14.npy
│   │   │   ├── 15.npy
│   │   │   ├── 16.npy
│   │   │   ├── 17.npy
│   │   │   ├── 18.npy
│   │   │   ├── 19.npy
│   │   │   ├── 2.npy
│   │   │   ├── 20.npy
│   │   │   ├── 21.npy
│   │   │   ├── 22.npy
│   │   │   ├── 23.npy
│   │   │   ├── 24.npy
│   │   │   ├── 25.npy
│   │   │   ├── 26.npy
│   │   │   ├── 27.npy
│   │   │   ├── 28.npy
│   │   │   ├── 29.npy
│   │   │   ├── 3.npy
│   │   │   ├── 4.npy
│   │   │   ├── 5.npy
│   │   │   ├── 6.npy
│   │   │   ├── 7.npy
│   │   │   ├── 8.npy
│   │   │   └── 9.npy
│   │   ├── 20
│   │   ├── 21
│   │   ├── 22
│   │   ├── 23
│   │   ├── 24
│   │   ├── 25
│   │   ├── 26
│   │   ├── 27
│   │   ├── 28
│   │   ├── 29
│   │   ├── 3
│   │   │   ├── 0.npy
│   │   │   ├── 1.npy
│   │   │   ├── 10.npy
│   │   │   ├── 11.npy
│   │   │   ├── 12.npy
│   │   │   ├── 13.npy
│   │   │   ├── 14.npy
│   │   │   ├── 15.npy
│   │   │   ├── 16.npy
│   │   │   ├── 17.npy
│   │   │   ├── 18.npy
│   │   │   ├── 19.npy
│   │   │   ├── 2.npy
│   │   │   ├── 20.npy
│   │   │   ├── 21.npy
│   │   │   ├── 22.npy
│   │   │   ├── 23.npy
│   │   │   ├── 24.npy
│   │   │   ├── 25.npy
│   │   │   ├── 26.npy
│   │   │   ├── 27.npy
│   │   │   ├── 28.npy
│   │   │   ├── 29.npy
│   │   │   ├── 3.npy
│   │   │   ├── 4.npy
│   │   │   ├── 5.npy
│   │   │   ├── 6.npy
│   │   │   ├── 7.npy
│   │   │   ├── 8.npy
│   │   │   └── 9.npy
│   │   ├── 4
│   │   │   ├── 0.npy
│   │   │   ├── 1.npy
│   │   │   ├── 10.npy
│   │   │   ├── 11.npy
│   │   │   ├── 12.npy
│   │   │   ├── 13.npy
│   │   │   ├── 14.npy
│   │   │   ├── 15.npy
│   │   │   ├── 16.npy
│   │   │   ├── 17.npy
│   │   │   ├── 18.npy
│   │   │   ├── 19.npy
│   │   │   ├── 2.npy
│   │   │   ├── 20.npy
│   │   │   ├── 21.npy
│   │   │   ├── 22.npy
│   │   │   ├── 23.npy
│   │   │   ├── 24.npy
│   │   │   ├── 25.npy
│   │   │   ├── 26.npy
│   │   │   ├── 27.npy
│   │   │   ├── 28.npy
│   │   │   ├── 29.npy
│   │   │   ├── 3.npy
│   │   │   ├── 4.npy
│   │   │   ├── 5.npy
│   │   │   ├── 6.npy
│   │   │   ├── 7.npy
│   │   │   ├── 8.npy
│   │   │   └── 9.npy
│   │   ├── 5
│   │   │   ├── 0.npy
│   │   │   ├── 1.npy
│   │   │   ├── 10.npy
│   │   │   ├── 11.npy
│   │   │   ├── 12.npy
│   │   │   ├── 13.npy
│   │   │   ├── 14.npy
│   │   │   ├── 15.npy
│   │   │   ├── 16.npy
│   │   │   ├── 17.npy
│   │   │   ├── 18.npy
│   │   │   ├── 19.npy
│   │   │   ├── 2.npy
│   │   │   ├── 20.npy
│   │   │   ├── 21.npy
│   │   │   ├── 22.npy
│   │   │   ├── 23.npy
│   │   │   ├── 24.npy
│   │   │   ├── 25.npy
│   │   │   ├── 26.npy
│   │   │   ├── 27.npy
│   │   │   ├── 28.npy
│   │   │   ├── 29.npy
│   │   │   ├── 3.npy
│   │   │   ├── 4.npy
│   │   │   ├── 5.npy
│   │   │   ├── 6.npy
│   │   │   ├── 7.npy
│   │   │   ├── 8.npy
│   │   │   └── 9.npy
│   │   ├── 6
│   │   ├── 7
│   │   ├── 8
│   │   └── 9
│   ├── B
│   │   ├── 0
│   │   ├── 1
│   │   ├── 10
│   │   ├── 11
│   │   ├── 12
│   │   ├── 13
│   │   ├── 14
│   │   ├── 15
│   │   ├── 16
│   │   ├── 17
│   │   ├── 18
│   │   ├── 19
│   │   ├── 2
│   │   ├── 20
│   │   ├── 21
│   │   ├── 22
│   │   ├── 23
│   │   ├── 24
│   │   ├── 25
│   │   ├── 26
│   │   ├── 27
│   │   ├── 28
│   │   ├── 29
│   │   ├── 3
│   │   ├── 4
│   │   ├── 5
│   │   ├── 6
│   │   ├── 7
│   │   ├── 8
│   │   └── 9
│   └── C
│       ├── 0
│       ├── 1
│       ├── 10
│       ├── 11
│       ├── 12
│       ├── 13
│       ├── 14
│       ├── 15
│       ├── 16
│       ├── 17
│       ├── 18
│       ├── 19
│       ├── 2
│       ├── 20
│       ├── 21
│       ├── 22
│       ├── 23
│       ├── 24
│       ├── 25
│       ├── 26
│       ├── 27
│       ├── 28
│       ├── 29
│       ├── 3
│       ├── 4
│       ├── 5
│       ├── 6
│       ├── 7
│       ├── 8
│       └── 9
├── README.md
├── __pycache__
│   └── function.cpython-312.pyc
├── app.py
├── collectdata.py
├── data.py
├── function.py
└── trainmodel.py
```

## File Explanation
* app.py - 
* collectdata.py - 
* data.py - 
* function.py - 
* trainmodel.py - 

