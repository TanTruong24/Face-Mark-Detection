# Face Mark Detection in Covid-19

Wearing a mask properly is a feasible and easy measure for the stressful period of Covid-19 epidemic prevention. However, there are still many people who do not wear masks or wear them incorrectly in crowded and familiar places such as in front of shops or buildings… Affecting others and increasing the human burden when supervision of these people must be increased. Reduces the effectiveness of epidemic prevention. Therefore, the application of information technology to detect these objects early through cameras mounted at the doors will help reduce the burden on personnel and the risk of cross-infection.

The project solves the problem of recognizing people wearing masks in photos, videos and directly through the camera.
In this project, the team used 3 pre-trained models in Deep Learning: MobileNetV2, SSD_Resnet50 and VGG16.
The data used for the problem is collected on the website
greetyimage.com, with the keywords “face mask, daily in life in a country, crown, covid-19 and people, …”

Train set includes 1572 images and test set 362 images.
Unlike many other data sources, project's dataset has 3 labels: 
- Correct : mask correctly
- Incorrect : mask wrong
- Face. no mask
A total of 4864 Correct labels, 1146 Incorrect labels and 1510 Face labels in the training set.
