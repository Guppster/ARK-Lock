# Requirements Document

### Created to develop an initial understanding of the project and align expectations

## Summary
There are three sections to this project, the user facing software, the software running the lock, and the hardware itself. 
Below i have written down what I think are the minimal working requirements for this project to be a success.

## User Software 
#### Mobile app / Webpage
* Be able to identify a new hardware lock by using it's assigned address
* Can add or relate accounts that are allowed to operate the lock
* Can display interactions with the lock

## Lock Software 
#### Running on ARM host or Arduino itself
* Able to operate the hardware when an approved address sends a transaction to it 
* Identifies the action (lock/unlock) via the vendor field

## Lock Hardware 
#### Servo operating deadbolt assemply
* Be able to control a pre-existing deadbolt assembly
* Independently powered and able to connect to the internet in a small footprint
