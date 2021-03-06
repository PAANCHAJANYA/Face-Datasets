# Face Datasets

To access FriendsDB, CID, Big Bang Theory or Agnisakshi Face Datasets, fill out <a href="https://docs.google.com/forms/d/e/1FAIpQLSeJt_zCDTZV_my6rOw5EYTrJAkjeDHN17PRltz8alqvmj0Vzw/viewform?usp=sf_link">this form</a>

## FriendsDB

This dataset has been prepared with the help of 7 subjects of whom 5 were male and 2 were female. We obtained 132 images of each female subject and 564 images of each male subject. The training and test set has been split in 70:30 ratio with respect to each subject. The dataset includes pictures of individuals with/ without spectacles, having displayed different poses, expressions, in different illumination conditions and facial hair configurations.

<div style="display:grid; grid-template-columns: 200px 200px 200px 200px; grid-row-gap: 20px;grid-column-gap: 30px;">
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/1.jpg" alt="FriendsDB1" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/2.jpg" alt="FriendsDB2" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/3.jpg" alt="FriendsDB3" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/4.jpg" alt="FriendsDB4" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/5.png" alt="FriendsDB5" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/6.png" alt="FriendsDB6" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/7.png" alt="FriendsDB7" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/8.png" alt="FriendsDB8" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/9.png" alt="FriendsDB9" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/10.png" alt="FriendsDB10" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/11.png" alt="FriendsDB11" style="width:200px;height:290px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/12.png" alt="FriendsDB12" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/13.jpg" alt="FriendsDB13" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/14.jpg" alt="FriendsDB14" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/15.jpg" alt="FriendsDB15" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/16.jpg" alt="FriendsDB16" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/17.jpg" alt="FriendsDB17" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/18.png" alt="FriendsDB18" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/19.png" alt="FriendsDB19" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/20.jpg" alt="FriendsDB20" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/21.png" alt="FriendsDB21" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/22.png" alt="FriendsDB22" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/23.png" alt="FriendsDB23" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/24.png" alt="FriendsDB24" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/25.png" alt="FriendsDB25" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/26.png" alt="FriendsDB26" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/27.png" alt="FriendsDB27" style="width:200px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/28.png" alt="FriendsDB28" style="width:200px;"/>
</div>

### The Dataset Preparation Protocol:

In case the reader intends to prepare a dataset similar to FriendsDB, they can follow the procedure mentioned hereafter:

<strong>Devices Required:</strong> A mobile phone with a camera of a minimum 13 MP resolution and a computer with Python IDLE.

<strong>The Process:</strong>

The process of preparing such a dataset is performed in three phases.

<strong>Phase ??? 1:</strong> In each of the conditions listed below, shoot a 20-second video of the subject with his/her head rotating from 90?? to the right to 90?? to the left keeping his/her face upright:
-	The subject should be wearing spectacles and smiling
-	The subject should be wearing spectacles and showing no facial expression.
-	The subject should be wearing spectacles and showing a sad facial expression.
-	The subject should not be wearing any spectacles. He/she should be smiling.
-	The subject should not be wearing any spectacles. He/she shouldn't show any facial expression.
-	The subject should not be wearing any spectacles. He/she should show a sad facial expression.

Vital points to be followed while shooting the videos:

-	The subject should move his head in a slow and uniform manner.
-	Let the subject pause the movement of his head for a few seconds when he/she faces directly into the camera.
-	Shoot the videos in the presence of a uniform light source (preferably, the sun) so that there is no shadow on any part of the subject's face (make sure the video is not too illuminated)
-	Let the subject's video be shot with a plain background (preferably white)
-	Make sure the subject's face covers 40-50% of the video frames
-	Repeat the same procedure given above for each subject. Thus, in total, there will be six 20-second videos for each subject we intend to include in the dataset.

An example of "The subject should be wearing spectacles and smiling" to help you understand the requirement can be found <a href="https://drive.google.com/file/d/1qJMSfXdCw0Q3eMwdWx8bfVn4rXdGvyYF/view?usp=sharing">here</a>.

<strong>Phase ??? 2:</strong>  After obtaining the videos, follow the steps below to perform first-hand dataset preparation:

-	Starting from the 5th frame, obtain every 10th frame of each of the six videos of each subject shot before and store them.
-	Label each frame stored according to the subject present in it.
-	Shortlist 10 images from frames obtained and stored from each of the videos shot. Make sure to shortlist such that you will have a good mix of poses (be slightly biased over images facing directly to the camera, let them be more in number than the other poses).
-	After the preceding step, you are left with 60 images of each subject with 10 images of each of the 6 conditions illustrated before. This will result in a dataset of size (60 x no. of subjects)
-	Remove the background from each of the images using online tools like <a href="https://remove.bg/">remove.bg</a> or Photo Editor apps on your mobile. You can remove background for multiple images at a time using the Windows app version of <a href="https://remove.bg/">remove.bg</a> <em>(this step is not needed if the background used while shooting the videos is completely plain without any objects)</em>

<strong>Phase 3:</strong> After completing Phase 2, follow the following steps to perform data augmentation so as to increase the dataset size and variations:

*	Download <a href="https://www.faceapp.com/">FaceApp</a> from Play Store on your mobiles to perform facial hair augmentation
*	For male subjects, the following filters can be applied to each of their images in the dataset prepared in the preceding phase:
* Hair Style Filters: Original, Haircut, Long 2, Bangs, Bangs2 (Grade 1, Grade 2, Grade 3), Side Swept, Straight Bangs, Hitman, Wavy, Straight
* Beard Filters: Original, Full Beard, Hipster, Goatee, Moustache, Lion, Petite Goatee
*	For female subjects, the following filters can be applied to each of their images in the dataset prepared in the preceding phase:
* Hair Style Filters: Original, Haircut, Long, Bob Cut, Bangs, Bangs2 (Grade 1, Grade 2, Grade 3), Side Swept, Straight Bangs, Wavy, Straight
*	Thus, if we apply every combination of facial hair filters, for each image of a male subject in the dataset prepared in the preceding phase, 84 more images will be generated. In the case of female subjects, for each image of a female subject in the dataset prepared in the preceding phase, 12 more images will be generated.
*	Include all the images generated in the preceding step in the dataset and label them according to the subject whose face it constitutes
*	Use a python script written using OpenCV to apply different brightness and contrast settings on each of the images included in the dataset till now to increase the dataset size and variance in terms of illumination. Label the images accordingly.
*	Use a python script written using OpenCV to resize the images available in the dataset as of now to different lower resolutions to encompass FRAD (Face Recognition at a distance). Label the images accordingly.

## CID

We utilized some of the episodes of a famous Hindi TV show titled CID for preparing this dataset. The episodes we used are posted on YouTube under ???Creative Common License???. After procuring the episodes, we used Multi-Task Cascade Convolutional Neural Network (MTCNN) to detect and store faces from every 10th frame of each episode. From the face images which are stored, we manually deleted images of subjects who were not part of the main cast of the show. This is because recurring characters i.e., the main cast cater more images in the dataset than the others. We also deleted images which were either blur or have too less resolution. Thus, we created an extensive dataset of 12 individuals. Each of the 12 individuals has a variety of face-images with different angles, expressions, mouth movement, etc. The training and test set has been split in 70:30 ratio with respect to each subject.


<div style="display:grid; grid-template-columns: 100px 100px 100px 100px 100px 100px 100px 100px; grid-row-gap: 20px;grid-column-gap: 30px;">
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(29).jpg" alt="CID1" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(30).jpg" alt="CID2" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(31).jpg" alt="CID3" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(32).jpg" alt="CID4" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(33).jpg" alt="CID5" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(34).jpg" alt="CID6" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(35).jpg" alt="CID7" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(36).jpg" alt="CID8" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(37).jpg" alt="CID9" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(38).jpg" alt="CID10" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(39).jpg" alt="CID11" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(40).jpg" alt="CID12" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(41).jpg" alt="CID13" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(42).jpg" alt="CID14" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(43).jpg" alt="CID15" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(44).jpg" alt="CID16" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(45).jpg" alt="CID17" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(46).jpg" alt="CID18" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(47).jpg" alt="CID19" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(48).jpg" alt="CID20" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(49).jpg" alt="CID21" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(50).jpg" alt="CID22" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(51).jpg" alt="CID23" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(52).jpg" alt="CID24" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(53).jpg" alt="CID25" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(54).jpg" alt="CID26" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(55).jpg" alt="CID27" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(56).jpg" alt="CID28" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(57).jpg" alt="CID29" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(58).jpg" alt="CID30" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(59).jpg" alt="CID31" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(60).jpg" alt="CID32" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(61).jpg" alt="CID33" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(62).jpg" alt="CID34" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(63).jpg" alt="CID35" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(64).jpg" alt="CID36" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(65).jpg" alt="CID37" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(66).jpg" alt="CID38" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(67).jpg" alt="CID39" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(68).jpg" alt="CID40" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(69).jpg" alt="CID41" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(70).jpg" alt="CID42" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(71).jpg" alt="CID43" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(72).jpg" alt="CID44" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(73).jpg" alt="CID45" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(74).jpg" alt="CID46" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(75).jpg" alt="CID47" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(76).jpg" alt="CID48" style="width:100px;height:100px;"/>
</div>

### The Dataset Preparation Protocol
In case the reader intends to prepare a dataset similar to CID, they can follow the procedure mentioned hereafter:

<strong>Devices Required:</strong> A mobile phone with a camera of a minimum 13 MP resolution and a computer with Python IDLE.

<strong>The Process:</strong>

The process of preparing such a dataset is performed with the help of following steps:
-	This dataset doesn???t need subjects to volunteer in its preparation. Thus, the reader must choose video content available in the internet (preferably a television show) which is either not bound by any copyrights or is released on YouTube under ???Creative Commons License???. The owner of the Creative Common licensed videos grants any viewer the permission to use their work.
-	After obtaining the video content enough to prepare the intended size of face dataset, we run a MATLAB or Python script that uses Multi-Task Cascade Convolutional Networks (MTCNN) to detect and store faces from every 10th frame of each of the videos.
-	We then manually delete images of subjects whose faces are low in number and the ones which are of too less resolution.
-	Label the images in accordance with the subject whose face they constitute.

After completing all the steps mentioned above, the reader will obtain an extensive face dataset containing images of the subjects chosen in different poses (angles), distance from the camera, and facial expression.

## Big Bang Theory

We utilized some of the episodes of the famous ???Big Bang Theory??? TV show for preparing this dataset. The episodes we used are posted on YouTube under ???Creative Common License???. After procuring the episodes, we used MTCNN to detect and store faces from every 10th frame of each episode. From the face images which are stored, we manually deleted images of subjects who were not part of the main cast of the show. We also deleted images which were either blur or have too less resolution. Thus, we created an extensive dataset of 7 individuals. The training and test set has been split in 70:30 ratio with respect to each subject.

<div style="display:grid; grid-template-columns: 100px 100px 100px 100px 100px 100px 100px 100px; grid-row-gap: 20px;grid-column-gap: 30px;">
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(77).jpg" alt="BBT1" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(78).jpg" alt="BBT2" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(79).jpg" alt="BBT3" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(80).jpg" alt="BBT4" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(81).jpg" alt="BBT5" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(82).jpg" alt="BBT6" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(83).jpg" alt="BBT7" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(84).jpg" alt="BBT8" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(85).jpg" alt="BBT9" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(86).jpg" alt="BBT10" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(87).jpg" alt="BBT11" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(88).jpg" alt="BBT12" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(89).jpg" alt="BBT13" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(90).jpg" alt="BBT14" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(91).jpg" alt="BBT15" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(92).jpg" alt="BBT16" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(93).jpg" alt="BBT17" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(94).jpg" alt="BBT18" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(95).jpg" alt="BBT19" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(96).jpg" alt="BBT20" style="width:100px;height:100px;"/>
</div>

## Agnisakshi

We utilized some of the promotional content for a famous Kannada TV show titled Agnisakshi available in YouTube for preparing this dataset. The promotional videos we used are posted on YouTube under ???Creative Common License???. After procuring the videos, we used MTCNN to detect and store faces from every 10th frame of each episode. From the face images which are stored, we manually deleted images of subjects who were not part of the main cast of the show. We also deleted images which were either blur or have too less resolution. Thus, we created an extensive dataset of 14 individuals. The training and test set has been split in 70:30 ratio with respect to each subject.

<div style="display:grid; grid-template-columns: 100px 100px 100px 100px 100px 100px 100px 100px; grid-row-gap: 20px;grid-column-gap: 30px;">
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(97).jpg" alt="AGN1" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(98).jpg" alt="AGN2" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(99).jpg" alt="AGN3" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(100).jpg" alt="AGN4" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(101).jpg" alt="AGN5" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(102).jpg" alt="AGN6" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(103).jpg" alt="AGN7" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(104).jpg" alt="AGN8" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(105).jpg" alt="AGN9" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(106).jpg" alt="AGN10" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(107).jpg" alt="AGN11" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(108).jpg" alt="AGN12" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(109).jpg" alt="AGN13" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(110).jpg" alt="AGN14" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(111).jpg" alt="AGN15" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(112).jpg" alt="AGN16" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(113).jpg" alt="AGN17" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(114).jpg" alt="AGN18" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(115).jpg" alt="AGN19" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/(116).jpg" alt="AGN20" style="width:100px;height:100px;"/>
</div>
