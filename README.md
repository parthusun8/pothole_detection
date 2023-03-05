
# POTHOLE DETECTION

A CNN for detecting if there is a pothole in an image or if the image is of a normal road.
Class Labels are ["normal", "potholes"]



CNN ARCHITECHTURE
![CNN ARCHITECHTURE](https://github.com/parthusun8/pothole_detection/blob/main/assets/cnn.png)


NORMAL ROAD(from dataset)
![NORMAL IMAGE](https://github.com/parthusun8/pothole_detection/blob/main/train/normal/93.jpg)


POTHOLE IMAGE(from dataset)
![POTHOLE IMAGE](https://github.com/parthusun8/pothole_detection/blob/main/test/potholes/319.jpg)


## Run Locally

NOTE

MAKE Sure to allow download multiple files when popup shows up

```bash
Open the pothole_detection.ipynb file
```

Anytime You might get a warning saying 'THIS NOTEBOOK IS HOSTED BY .. so on'. 

```bash
Click on Run Anyway
```

Now in colab,
```bash
Go to Runtime Tab
Choose Change Runtime Option
Choose Hardware Accelerator as GPU
```
To see the output and download models,
```bash
Go to Runtime Option
Click on Run all
Wait for 2-5 mins
You can see the output now
```