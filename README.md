# Helping ASD patients become more social with Google Glass

## Background and rationale

Among patients with autism-spectrum disorder (ASD), many have problems with social interactions, which is caused by difficulty recognizing emotions and non-verbal cues in general. Thus, these patients could benefit from an assistive wearable device providing them with appropriate and timely social cues.

## Brief description

We would like to develop an application for Google Glass that will 
- detect human faces in the field of view (FOV)
- draw a bounding box around them (YoloV3 is a possible model we already have experience with) and 
- add a label containing an action suggestion and/or other information to the bounding box


### Phase 1

In phase 1, these labels will provide an estimate of the individual's emotional state (interested, engaged, enthused etc.), which may help ASD patients overcome the lack of emotional awareness and better function in social situations. If the hardware allows, the object detection/recognition model will run on device. The face detection/recognition feature may have other use cases (e.g. for law-enforcement and security agencies).

### Phase 2

In phase 2, the app will get another feature: on-screen suggestions about how to act in typical social situations (such as what to say back to a common greeting, how to answer casual questions etc.). This will require a server-hosted speech recognition and a language model that the Google Glass will make API calls to. We already have API keys to OpenAI's GPT-3 and might use it in phase 2.

## Team
Roman Koshkin (NCBC) & Alexey Vylegzhanin (LMIU)
