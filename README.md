# Text2Skript

Text Generative Model to convert text to usable Skript.

# Files

`train.txt` is the non jsonifyed training data collected from Skriptify and other resources.

`train-json.txt` is the jsonified training data, this is the data that is used to train the model due to new line limitations with GPT-2. (Must JSONify input sentence for it to understand what to do!)

# Help contribute... Please!

This needs a lot of training data to get right, so I appreciate you for contributing to this project!

You can contribute skript code (unstructured) or structured code (sentence -> skript examples.)

## Example:

unstructured code is valid / working code that doesn't have a premise or isn't linked with a sentence, like if you would make a random skript that launches everyone into the air but there is no sentence that describes it, then it is unstructured.

structured code, on the other hand, is more important since the model needs to understand how to convert sentences into skript.

Example of structured:

![structured code](https://media.discordapp.net/attachments/644989803494113296/822688596925349938/unknown.png)

Notice the sentence is what you may input to retreive the desired skript.

## How to submit code

You may DM me `mega b#6696` on Discord, or open up an issue / pull request.

# Pre-Trained model download

## 3/19/2021 (1.33 GB, bad output still, needs more training data. Trained for 5 hours on iteration 8000)


### [ARCHIVED] 3/18/2021 (2.6 GB, very bad output, only trained for 3 hours) 
