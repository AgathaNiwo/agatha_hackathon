# agatha_hackathon

The 3d_viewer.py code and data was sourced from http://aqibsaeed.github.io/2016-11-04-human-activity-recognition-cnn/.
This was to get me used to Tensor flow models and code from a similar case study. Unfortunately, I was still on a learning curve 
and while I have understood now how Tensorflow models work, I still have yet to implement a similar model.



Use Case: Check Human activity status using Accelerometer

Participating Actors
The use case is initiated by an app owner.

Brief Description
The use case allows the  owner to check their status of human activity over the last ten minutes.

Assumption
The person is logged into the system.

Flow of Events

Basic Flow
The use case starts when the person elects check their status.
The system has a guess button which the uses clicks on and the app shows the user over the last ten minutes what the 
probabilities of each activity is; Jogging, Walking, Sitting, Standing, Walking Downstairs,Walking Upstairs, Lying.
The system uses the Tensor flow model generated to give probabilities for each.
The person is allowed to select the right status.
The system stores the right status, with a time stamp and person's id.
The system learns from the new information that can be incorporated in the Tensorflow model
