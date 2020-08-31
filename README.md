# OMLIT
Optical Machine-Learning Instrumentation Technology

Incomplete project for ocean technology course. Not currently being worked on.

Objective: create software that identifies plastic pollution in a marine setting. Software runs on a raspberry pi connected to an Open MV camera. End goal was to fit a marine remotely-operated vehicle (ROV) with a camera and use it to collect data on marine plastic pollution. 

Accomplished so far: software currently identifies blobs in images and saves screenshots with blobs highlighted at a set time interval. 

Taking this further: could use Open CV, have to introduce parameters for plastic identification instead of "blobs", needs testing in marine environment (test against light levels, turbidity, movement), data output should be meaningful (# particles, average size, density? environmental conditions? would need additional sensors, what format should data be in, csv? netcdf?). 
