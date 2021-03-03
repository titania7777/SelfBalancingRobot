# The original repository of Self-Balancing-Robot
Implementation of Self Balancing Robot with ML-Agents.

The RolyPoly model is a Newly designed model to reduce complexity in the environment, and I will use this model to implement a balancing robot in the real world.

## RolyPoly Model
<img align="center" src="figures/RolyPolyModelTest.gif" width="750">

## Requirements
*   ml-agents >= 1.4.0

## Usage
### Training on Simulation
1. import your asset files into the unity workspace.
2. build the RolyPoly scenes and train with default option.
### Testing on Simulation
1. import your asset files into the unity workspace.
2. select the RolyPolyModeltest scenes and start the game.
### Testing on Real
1. import your asset files into the unity workspace.
2. select the RolyPolyRealtest scenes and start the game (please don't forget to upload the firmware on the ardino and connect to arduino)

## Results
### training result
<img align="center" src="figures/RolyPolyResult.PNG" width="750">

### [Testing Video](https://www.youtube.com/watch?v=zNuGCi0jJcc)

## References
Kalmanfilter original codes for arduino in [HERE](https://github.com/TKJElectronics/KalmanFilter)

Kalmanfilter original codes for unity in [HERE](https://github.com/prozoroff/UKFSharp)

PID original code in [HERE](http://scipia.co.kr/blog/227)

## Contact
titania7777@gmail.com
