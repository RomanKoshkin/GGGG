# Helping ASD patients become more social with Google Glass

## Background and rationale

Among patients with autism-spectrum disorder (ASD), many have problems with social interactions, which is caused by difficulty recognizing emotions and non-verbal cues in general. Thus, these patients could benefit from an assistive wearable device providing them with appropriate and timely social cues.

## Brief description

I would like to develop an application for Google Glass that will detect human faces in the field of view (FOV), draw a bounding box around the human face(s) (YoloV3 is a possible model I already have experience with) and add one of several labels to the bounding box. 

### Phase 1

In phase 1, these labels will provide an estimate of the individual's emotional state (interested, engaged, enthused etc.), which may help ASD patients overcome the lack of emotional awareness and better function in social situations. 

### Phase 2

In phase 2, the app will also implement speech recognition and a language model to provide on-screen suggestions about how to act in typical social situations (e.g. what to say back to a common greeting, how to answer to casual questions etc.). If the hardware allows, the object detection/recognition model will run on device. The language model will most likely run on a server, with the Google Glass making calls to the API as needed. I already have API keys to OpenAI's GPT-3 and might use it in phase 2.
