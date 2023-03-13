
# <ins>Planning Module - Documentation

## Introduction

  In this module, given localization (vehicle status (position, velocity, acceleration)), High Definition maps and prediction (bounding boxes), it computes a trajectory that is safe and comfortable for the controller to execute. It consists of two submodules - global planner, which generates a reference path from ego vehicle's pose to its interested destination, and motion planner module which enforces obstacle avoidance states and traffic rules.
  
## Module Architecture
  
  
