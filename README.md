# anomaly-detection-
What has been done - Logic
The code is designed to perform anomaly detection on data sets. The basic logic of the code is to first identify the mean and standard deviation of the data set, and then use these values to detect any anomalies. If a value in the data set is more than three standard deviations away from the mean, it is considered an anomaly.

Setting up and testing in an isolated system
The code can be set up and tested in an isolated system using Docker. First, a Docker image should be created that contains all the necessary dependencies, including the code and any data sets that will be used for testing. Once the image has been created, a Docker container can be launched using the image, which will provide an isolated environment for running the code.

To test the code, a data set should be provided to the container, and the code should be run to detect any anomalies. The results of the code can then be reviewed to ensure that it is accurately detecting anomalies in the data.

Testing with provided data set
The code contains a data set that can be used for testing purposes. This data set can be used to demonstrate the capability of the code to detect anomalies.

To test the code, the data set should be provided as input to the code. The code will then calculate the mean and standard deviation of the data set, and use these values to detect any anomalies. If the code correctly detects any anomalies in the data set, it can be considered a successful test.
