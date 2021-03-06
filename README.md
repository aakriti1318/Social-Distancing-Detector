## Detecting Social Distancing Violations
- To detect social distancing violations, we take each track in the frame and measure its distance to every other track in the frame. Each track is a bounding box with an ID. So a bounding box can be compared to another bounding using the euclidean distance between them. 

- In this we can detect in the frame the number of people violating rules.

#### Application : 
In the production, the camera needs to be installed and registered so that we can map number of people violating social distancing rules during the pandemic. This project can be modify by adding person identification so that our model can calculate the number of times the same person is violating. 

![social_distancing](https://user-images.githubusercontent.com/56245613/100550818-8efd7c80-32a2-11eb-9c23-b99e39c8ee38.png)

