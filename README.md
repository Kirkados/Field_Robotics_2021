Code accompanying the paper under review in Field Robotics:
# Learned Multi-agent Real-time Guidance with Applications to Quadrotor Runway Surveillance

This code generates and trains quadrotors to learn how to explore an aircraft runway. An arbitrary number of quadrotors can be used, and if a quadrotor fails during a flight, the others will continue without it. The policy network outputs a desired acceleration signal that the quadrotors attempt to track.

This code uses Tensorflow 1.15.0

To run: python3 main.py
The default training run will produce two qudrotors flying on an outdoor runway. 50% of the runs will have one quadrotor fail mid-flight.
