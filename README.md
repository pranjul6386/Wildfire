There are two ways for a wildfire to occur:
1.Wildfire caused by Natural Climatic conditions.
2.Wildfire caused by man-made activities.


Here we are presenting our solution which deals with both the causes.
We have planned our solution in five simple steps i.e. collection, prediction, detection, alert and
prevention of forest fires. So how we are -

● Collecting weather data - Foremost step is to collect the weather data of a particular
forest area. This is possible by using different sensing input devices:
Soil moisture sensor
Smoke Sensor- MQ2
Temperature and humidity-DHT11
Heat,glaze and Motion-IR sensor
The readings are taken from the sensors in real time which will give the data for
processing in the subsequent steps.

● Predicting forest fires - We will use Machine learning to predict the probability of
occurrence of Wildfire at the appropriate location at which sensing device is placed.
The input features the algorithm will be:
● Temperature
● Humidity
● Soil-Moisture content
● Month of the year
We used several algorithms like Random Forest , svm classifier etc.On which Random
Forest performed best. The model predicts the output variable as (0 or 1) for the
threshold probability of 0.7. The data we have collected in the previous step is passed
through the classifiers and will give a score for the possibility of fire based on the
weather condition of that area. We will convert the probabilistic score to a binary score.

● Detection of forest fires - Data from smoke and IR sensor collected in the first step is
used here to detect the fire. We will be more sure about “Is the fire really started or not
?”.If smoke values and IR sensors give positive results ,then we will detect the fire from
cameras through deep learning algorithms on a real time basis. We check the fire with
computer vision which is trained on forest fire dataset. This will identify the wire burst
and the extend of fire through the deep learning model .

● Sending Alert - If the fire took place , an Alert will be sent to the nearby forest
authorities. This is done either there is a high probability of forest fires in the second step
or a fire is detected in the third step. Alert can be an email, notification, whatsapp, FM,
AM etc.

● Prevention of forest fires - The first reliable priority will be nearby forest authorities, but
parallely a device is used to set up which is a water tank and a pump.Either the pumps
will be installed at various locations or sprinkling through the drones can be done on the
burned area to stop the further spreading of fire,till authorities reaches the location. A
signal is sent and this device will try to extinguish the fire.
The solution covers extinguishing natural occurring fires and man made fires or at least
reducing them to a greater extent


