# SYSTEM LAYERS
- - - - - - - - - - - - -

Inputs: Microphone, Camara, Screen tocuh interactions.
Outputs: Face experessions, Speaker audio, little bit body movements.

## AI (Its responsibilites)

Starting, holding, and making the Coversations.
Image Interactions: By watching its surroundings.
Personality and conversation context.
Generating spoken response tests.
Requesting predefined expressive actions.

## Local Arrangements: (Cloud)

Managing of AI requests and responses
Managing of the connection status and uhm you can say like timeouts
Handling speech and images.
Converting the AI action requests into validated commands.
another thing is Coordinating the speech, experssion and rmovement (It will be hard fr).

## The embedded Controller (Or you can say microcontroller)
[Importnat]

Timely coordinating the Experssions and movements.
Handling or controlling the Servos (Joints of it, you can also say movement.)
Managing the sensors.
Monitering its health

# Offline coomands (It will be Predefined)
They are:
 Look left (It will look left)
 Look right (It will look right)
 HEAD TILT (It will Tilt its heard)
 RETURN TO CENTER (It will come back to center)
 EXPRESSION CURIOUS (It will do the experssion of curious in display)
 EXPRESSION LISTENING (It will show the experssion of listening)
 EXPRESSION SPEAKING (It will do the experssion of Speaking)
*These are just the examples there will be many more.

## Fault Handling

Cloud timeout: Requests got rejected due to api issues or smth like that
Network loss: It will get to local mode and do the things without ai and work with the commands which are predefined in it (Camara will not work)
Invalid action: reject the request.
Controller communication loss
Low battery: warn the user and charge the battery
Camera disabled: prevent images from getting captuerd
Actuator fault: stop the affected motion and report the issue.


