# Traffic Cam Detection
 Final Project for COMP3523
---------------------------
This includes my final project for COMP3523 - Applied Machine Learning
- Initially, we were supposed to work with a community partner of Mount Royal, but due to unforseen circumstances, the company had to back out of the project resulting in new project definition.
- This was a semester long project, where we had to research about some modern technologies to implement on our own and find how they would work with the traffic cams of Calgary, as suggested by our professor.
- An example of the results of the model <br>
![Untitled](https://github.com/koddyrae/Traffic-Cam-Detection/assets/93951707/976b0892-eb05-466c-a26c-5462c79d8bbb)
- ***I believe majority of the issues lie within our inexperience with the model and object detection techniques***
   - For example, we could probably increase performance if google colab had more GPU processing time, so we could increase epochs during the training of our model.
   - Another thing, we could do is further hyper-tune the model to increase the performance of our current model.
   - One lack oversight in our dataset was that it is impossible to get a balanced amount of the classes we were trying to detect, so maybe trying to detect them as one would be much better, resulting a higher confidence rate of the model.
   - Another oversight was that there was a slight discrepancy in the annotating of the dataset, resulting in some cars being detected twice. 
