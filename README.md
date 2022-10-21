Trying to help people that can't use mathematics to sum up the currency and the blind people to detect for them how many pounds are there.

## What did we do?

- ### First of all we gathered our data with more than 3500 images for all of our currencies.

![Capture](https://user-images.githubusercontent.com/72711083/197255929-447ce93a-05c6-48ae-b2a9-0dc1f63c483c.PNG)


- ### Then we started labeling the data using bounding boxes and labels in txt files.

![Capture3](https://user-images.githubusercontent.com/72711083/197256651-eaff61a1-e15a-4039-9492-bde4a7bf0c9f.PNG)


- ### Then we started cloning YOLOv3 repo and getting its weights.

- ### We edited the yolo configuration text file to be suitable for our project we edited some convolutional layers so as yolo blocks.
![photo_2022-10-21_19-42-28](https://user-images.githubusercontent.com/72711083/197256985-877060f1-9ca2-4bb7-b54b-c9764667c5ee.jpg)


- ### Then we started training our model for more than 7000 epochs.

- ### For the testing process we used 4 helper functions to show us the image after the prediction and to save it the other two were
  for summing up all the currencies in the image if there were more than one currency.
  
  ![Capture5](https://user-images.githubusercontent.com/72711083/197257170-6a69afd8-96e9-46f4-aa73-5133ac573cc2.PNG)
