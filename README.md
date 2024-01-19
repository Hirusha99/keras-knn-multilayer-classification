# Problem

Bob has started his own mobile company. He wants to give tough fight to big companies like Apple, Samsung, etc. He does not know how to estimate price of mobile phones his company manufactured. In this competitive market you cannot simply assume things. To solve this problem he collected sales data of mobile phones of various companies. Bob wants to find out some relation between features of mobile phones (e.g., RAM, Internal Memory, etc.) and their selling prices. But he is not so good at Machine Learning. So, he needs your help to solve this problem. In this problem, you do not have to predict the actual price but a price range indicating how high the price is. The following are the attribute of the dataset:

1.	battery_power: Total energy a battery can store in one time measured in mAh
2.	blue: Has Bluetooth or not
3.	clock_speed: speed at which microprocessor executes instructions
4.	dual_sim: Has dual sim support or not
5.	fc: Front Camera mega pixels
6.	four_g: Has 4G or not
7.	int_memory: Internal Memory in Gigabytes
8.	m_dep: Depth in cm
9.	mobile_wt: Weight of mobile phone
10.	n_cores: Number of cores of processor
11.	pc: Primary Camera mega pixels
12.	px_height: Pixel Resolution Height
13.	px_width: Pixel Resolution Width
14.	ram: Random Access Memory in Megabytes
15.	sc_h: Screen Height of mobile in cm
16.	sc_w: Screen Width of mobile in cm
17.	talk_time: Longest time that a single battery charge will last
18.	three_g: Has 3G or not
19.	touch_screen: Has touch screen or not
20.	wifi – Has wifi or not
21.	price_range: four price ranges (0, 1, 2, 3)
	
There are 2,000 records in the dataset. Use 80% and 20% of this data for training and testing respectively.
Design the following machine learning models to the given dataset suitably.

1.	K-nearest neighbour algorithm (use Python ‘scikit-learn’ package)
2.	Multi-layer neural network (use ‘Keras’)
   
All coding, results, plots and documentation should be in a single ‘IPython’ or ‘Jupyter’ notebook. Create a ‘GitHub’ account for you if you don’t have a one yet and store this file in your ‘GitHub’ repository. Submit the ‘link’ of this file on or before the given submission date.
The followings should be clearly addressed when designing the models.

(a)		How to pre-process the data (normalization, non-linear transformations, feature extraction, coding of discrete inputs and targets, handling of missing data, etc.)?

(b)		How to handle the ‘over-fitting’ problem?

(c)		How to compare the designed machine learning models? Use post-training analysis methods such as accuracy, confusion matrix, precision, recall and F-measure appropriately.

