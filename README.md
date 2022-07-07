# Face Datasets

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

<strong>Phase – 1:</strong> In each of the conditions listed below, shoot a 20-second video of the subject with his/her head rotating from 90° to the right to 90° to the left keeping his/her face upright:
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

<strong>Phase – 2:</strong>  After obtaining the videos, follow the steps below to perform first-hand dataset preparation:

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

We utilized some of the episodes of a famous Hindi TV show titled CID for preparing this dataset. The episodes we used are posted on YouTube under “Creative Common License”. After procuring the episodes, we used Multi-Task Cascade Convolutional Neural Network (MTCNN) to detect and store faces from every 10th frame of each episode. From the face images which are stored, we manually deleted images of subjects who were not part of the main cast of the show. This is because recurring characters i.e., the main cast cater more images in the dataset than the others. We also deleted images which were either blur or have too less resolution. Thus, we created an extensive dataset of 12 individuals. Each of the 12 individuals has a variety of face-images with different angles, expressions, mouth movement, etc. The training and test set has been split in 70:30 ratio with respect to each subject.


<div style="display:grid; grid-template-columns: 100px 100px 100px 100px 100px 100px 100px 100px; grid-row-gap: 20px;grid-column-gap: 30px;">
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/29.jpg" alt="CID1" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/30.jpg" alt="CID2" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/31.jpg" alt="CID3" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/32.jpg" alt="CID4" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/33.png" alt="CID5" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/34.png" alt="CID6" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/35.png" alt="CID7" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/36.png" alt="CID8" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/37.png" alt="CID9" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/38.png" alt="CID10" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/39.png" alt="CID11" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/40.png" alt="CID12" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/41.jpg" alt="CID13" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/42.jpg" alt="CID14" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/43.jpg" alt="CID15" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/44.jpg" alt="CID16" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/45.jpg" alt="CID17" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/46.png" alt="CID18" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/47.png" alt="CID19" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/48.jpg" alt="CID20" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/49.png" alt="CID21" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/50.png" alt="CID22" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/51.png" alt="CID23" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/52.png" alt="CID24" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/53.png" alt="CID25" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/54.png" alt="CID26" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/55.png" alt="CID27" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/56.png" alt="CID28" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/57.png" alt="CID29" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/58.png" alt="CID30" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/59.png" alt="CID31" style="width:100px;height:100px;"/>
<img src="https://github.com/PAANCHAJANYA/Face-Datasets/blob/main/README_Images/60.png" alt="CID32" style="width:100px;height:100px;"/>
</div>

### Project Description
To overcome the challenges pondered over in the problem statement, I ideated a web application with the following functionalities:
1. **Live Tracking of the Ambulance:** A Live Location feature is implemented through which the paramedic staff of an ambulance can share their live location with the hospital that owns the ambulance. We could further extend this functionality such that the live location data is shared even with the hospital or any medical institute to which the patient is taken for admission.
2. **Equipment Damage Control:** The paramedic staff can also update the status of life-saving equipment in the ambulance which can be used in replacing the worn-out devices.
3. **Patient Information Management:** The paramedic staff could share information about the patient's personal details and health condition to the hospital that owns it, so that they can do necessary arrangements for patients’ treatment. The information includes:

   + Personal details like name, sex, age, contact no., and residential address
   + Health emergency details
   + Patient Attendee details
   + Chronic medical conditions the patient is already suffering from
   + Allergies the patient has (if any)
   + Blood Glucose levels (Blood Sugar) information computed using Glucometer
   + %Sp O2 - Proportion of Oxygenated Haemoglobin
   + Pulse Rate (bpm)
## Azure Services used
* **Azure App Service** to host the PHP Web App: B1 Plan (free for a month)
* **Azure SQL Database** to host the DBMS Server: Compute Gen5 General Purpose Serverless Architecure (vCore based pricing tier)
## User Interface
### Sign In
Use any of the below listed credentials in order to login to ambulancequipo.
* The ID starting with A belongs to the Admin
* The IDs starting with M belong to Management
* The IDs starting with D belong to paramedic staff

|        ID        | Password
|----------------|--------------------
|A001|`pass111`
|M001|`pass001`
|M002|`pass002`
|D001|`pass011`
|D002|`pass012`

![Sign in UI](https://github.com/PAANCHAJANYA/ambulancequipo/blob/main/README_images/signin.png)
### User Roles, their scope of operation and UI
* **Admin:** The admin can add new management accounts. He can also view the hierarchy of ambulancequipo users i.e., a tree diagram illustrating the cities, hospital managements registered with ambulancequipo in that city and the ambulances working under them.
![Admin UI](https://github.com/PAANCHAJANYA/ambulancequipo/blob/main/README_images/admin.png?raw=true)
* **Management:** The management can live track its ambulances which are active at the moment or view the history of the management's ambulances that have transported patients. The management can also view equipement damage complaints and mark them resolved if and when rectified.
![Management UI](https://github.com/PAANCHAJANYA/ambulancequipo/blob/main/README_images/management1.png?raw=true)
![Management UI](https://github.com/PAANCHAJANYA/ambulancequipo/blob/main/README_images/management2.png?raw=true)
![Management UI](https://github.com/PAANCHAJANYA/ambulancequipo/blob/main/README_images/management3.png?raw=true)
![Management UI](https://github.com/PAANCHAJANYA/ambulancequipo/blob/main/README_images/management4.png?raw=true)
![Management UI](https://github.com/PAANCHAJANYA/ambulancequipo/blob/main/README_images/management5.png?raw=true)
* **Paramedic Staff:** Paramedic Staff can fill a form to mention personal and emergency details of the patient it is transporting to a medical facility. After filling the form they can start sharing the live location of their ambulance to be live tracked by the management. In addition, they can file an equipment complaint such that the management can know the damaged equipment's details and resolve them as and when needed.
![Driver UI](https://github.com/PAANCHAJANYA/ambulancequipo/blob/main/README_images/driver1.png?raw=true)
![Driver UI](https://github.com/PAANCHAJANYA/ambulancequipo/blob/main/README_images/driver2.png?raw=true)
![Driver UI](https://github.com/PAANCHAJANYA/ambulancequipo/blob/main/README_images/driver3.png?raw=true)
