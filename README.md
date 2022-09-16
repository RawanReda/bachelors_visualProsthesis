# Indoor Scenes Understanding for Visual Prosthesis

## Motivation
Visual prostheses do not fully restore vision, and there remains a large difference
between normal and prosthetic vision. Patients who use visual prostheses still face
difficulty recognizing their surroundings, indicating that the output of visual prostheses
remains a problem to be tackled.

## Aim
The aim of this thesis is to develop a better phosphene representation of indoor scenes
for people with some sort of blindness to help them comprehend indoor scene types more
easily. 

Machine learning and image processing techniques are used as a part of image
enhancement and a phosphene simulation library is used to predict the actual outcome
given the input image.

![image](https://user-images.githubusercontent.com/51987270/190730764-7b809fa0-f46d-463b-b8bb-f1a77836a879.png)

## Tech
- Machine Learning (Tensorfow)
- Computer Vision
- Pulse2percept python library
- Virtual Reality

## Experiments
- Static images and Videos
- Images displayed through Virtual Reality 
- Realtime images captured and displayed using Virtual Reality 

Each experiment technique involved three groups: Control group, Enhancement group, and Edges group (as shown in the methodology image). Participants were asked to identify the object within the room, the type of the room and on a scale from 1 to 5, their confidence level, all within a time frame of a min for each image. 
<p align="center">
<img src= "https://user-images.githubusercontent.com/51987270/190768382-212644c6-42c4-479f-a3ab-cae718977d2d.JPG"/>
</p>

## Results

Sample results from the static images and videos group: 
![results](https://user-images.githubusercontent.com/51987270/190772787-2dcaff0f-440a-4d19-b02e-3296d31a2067.JPG)

<p align="center">
<img src="https://user-images.githubusercontent.com/51987270/190782203-81b2c3dc-4d7c-4087-a336-e21085239d92.JPG"/>
</p>

Generally, results for room identification and object recognition task for images were better in the Enhancment group, with a p-value < 0.05, indicating that the difference is significant. 

## Limitations
In the future, it might be worthwhile to try different representations of phosphene simulations to investigate the extent of the effect they have on visual interpretation. Furthermore, indoor scenes can be very complex and there are a variety of different objects that can be present depending on the room type. It would be better to include more scenes and fine-tune machine learning models such that they would recognize all the objects that are likely to be present within these scenes. Due to the limited types of rooms available, the real-time experiment was only
conducted in computer labs. However, undertaking the experiment in more room types would have added to the results and confirmed our findings. Overall, it can be affirmed that the comprehension of indoor scenes can be obtained with just a few sets of elements represented in the environment.

## Final Notes
Read the thesis for more details. 

## Steps to run the project: 

You can check the real time simulation for instant results by simply running \realtime\realtime_visualProsthesis.ipynb. You will also need to install pulse2percept by uncommenting the first line in the file. 
