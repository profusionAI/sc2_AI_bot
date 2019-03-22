# sc2_AI_bot
This project generates an AI-bot that plays Starcraft II at a specified difficulty. The python-sc2 API, as well as TensorFlow and Keras are used to create training data (via gameplay execution) and a CNN learning model for improved gameplay.

Requirements:

SOFTWARE:
Starcraft II Client
Starcraft II maps (this project currently uses CyberForestLE.SC2Map from Ladder2019Season1)

PYTHON PACKAGES:
Python3.6 -> note that Python3.7 is not currently compatible with tensorflow, and has existing websocket issues.
python-sc2 -> note that this is not an equivalent version to DeepMind's sc2 API.
tensorflow
keras
numpy
OpenCV
