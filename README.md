# Human-activity-detection
<br>Detecting human activity in an  image or a video.

## Aim
<br>To detect various activities of human beings such as dancing, cooking and riding a bike using neural netwroks.
## Technologies used
<br>Python
<br>YOLO
## Workflow
<br>* Downloading open source images.
<br>* Creating directory named Activity Detection which contains three subfolders train,test and valid. Each of these subfolders contains images where anoted images are present and labels where labelling is done on image. This labels contains .txt file having information of bounding box created on image.
<br>* Here I have used pre-trained model yolov8s for detection as it is small dataset.
## Conclusion
<br>Considering that my dataset is small, model performs well on test dataset and differinates between other activities.

## Results
<br>Labels
<br>
![val_batch0_labels](https://github.com/shreehari-divate/Human-activity-detection/assets/147906812/27fe646a-2d64-46cf-a882-ec043fdb9fd5)

<br>
Prediction
<br>
![val_batch0_pred](https://github.com/shreehari-divate/Human-activity-detection/assets/147906812/575d2ff8-65a7-42d7-9802-4d9b02d4990d)

