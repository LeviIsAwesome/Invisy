# Invisy [![HitCount](http://hits.dwyl.io/LeviIsAwesome/https://github.com/LeviIsAwesome/Invisy.svg)](http://hits.dwyl.io/LeviIsAwesome/https://github.com/LeviIsAwesome/Invisy)
Making people disappear since 2018.

## Contributing ![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat) [![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat)](#contributors) 
Thanks goes to the following contributors (names in alphabetical order):

| [<img src="https://avatars0.githubusercontent.com/u/22110517?s=400&v=4" width="100px;"/><br /><sub><b>Jeremy Arde</b></sub>](https://github.com/Jarde01) | [<img src="https://avatars2.githubusercontent.com/u/37234961?s=400&v=4" width="100px;"/><br /><sub><b>Levi Guo</b></sub>](https://github.com/LeviIsAwesome)  | 
|---|---|


## Demo
This demo was filmed at **The 2018 Local Hack Day** at University of Manitoba, and this project helped us awarded an **Honorable Mention** at the event 🎊✌️🎉.   

![](https://github.com/Jarde01/Invisy/blob/master/person_blocker.gif)

## Credit
This [Person-Blocker Repo](https://github.com/minimaxir/person-blocker) classifies the object in the still image, our implementations were based on this repo and turned its feature into real-time object detection.

## Idea and Techniques
Inspiration was from [Black Mirror White Christmas Episode](https://www.youtube.com/watch?v=_dXqugxU1sk&t=44s) (Youtube Video) and the technique we used is called [Mask R-CNN](https://arxiv.org/abs/1703.06870) which predicts an object mask in parallel with the existing branch for bounding box recognition.

## Current Implementation: 
- phone uses ip webcam to set up web service with the live video feed.
  - can replace with other video sources
- invisy grabs screenshots and sends them to the model for classification
- display the model output to the screen after processing

