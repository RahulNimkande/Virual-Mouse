# Virual-Mouse

A virtual mouse is software that allows users to give mouse inputs to a
system without using an actual mouse. To the extreme it can also be called
as hardware because it uses an ordinary web camera. A virtual mouse can
usually be operated with multiple input devices, which may include an
actual mouse or a computer keyboard. Virtual mouse which uses web
camera works with the help of different image processing techniques.


 _Youtube Channel Link: [link](https://www.youtube.com/channel/UCC2aiBrcvFHpb4Rve-eQFBg)_<br>
 _Video Link: [link](https://www.youtube.com/watch?v=ufm6tfgo-OA&ab_channel=Proton)_


# How to setup and run

  ### Pre-requisites
  
  Python: (3.6 - 3.8.5)<br>
  Anaconda Distribution: To download click [here](https://www.anaconda.com/products/individual).
  
  ### Procedure
  ```bash
  git clone https://github.com/xenon-19/Gesture-Controlled-Virtual-Mouse.git
  ```
  For detailed information about cloning visit [here](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository).
  
  Step 1: 
  ```bash
  conda create --name gest python=3.8.5
  ```
  
  Step 2:
  ```bash
  conda activate gest
  ```
  
  Step 3:
  ```bash
  cd to the Virtual-Mouse folder
  ```
  Command may look like: `cd C:\Users\.....\Virtual-Mouse`
  
  ```bash
  pip install -r requirements.txt
  ```
  
  Step 4:
  ```bash 
  conda install PyAudio
  ```
  ```bash 
  conda install pywin32
  ```
  
  Step 5:
  ``` 
  cd to the src folder
  ```
  Command may look like: `cd C:\Users\.....\Virtual-Mouse\src`
  
  Step 6:
  ```bash 
  python .py
  ```

