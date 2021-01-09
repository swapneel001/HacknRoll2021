# HacknRoll2021
## An automatic fall detection wearable sensor for hikers that alerts our app and sends an SMS of the hiker’s live location to the hiker’s emergency contacts in the event of a fall.

### Files:

fall_test.ino : ESP32 code to detect fall and send bluetooth ping

AndroidManifest.xml and MainActivity.java : Android App codes

app-debug.apk : Android app

demo.MOV: showing demo on user side, the device being moved in the air to simulate motion of walking, and the app is connecting to the ESP32 and waiting for a ping. Once the ping is sent, the emergency contact will get an sms (screenshot attached)

sos message.jpeg: Shows SOS with co-ordinates recieved by the emergency contact
