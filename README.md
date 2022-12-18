
<h1 align="center">  Mobile Price Range Prediction
 </h1>

<h3 align="center"> AlmaBetter Verified Project - <a href="https://www.almabetter.com/"> AlmaBetter School </a> </h5>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Introduction
Mobile device price prediction is very important for consumers as well as marketers. Consumers need to know what they are paying for and the marketers should keep up with the competition and should rate their mobile device well.

The main goal of this study is to see "whether a mobile phone with specified capabilities falls into a certain price range".

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
## Problem Description
In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is.
Further based on different features of mobile phones, develop a model that would classify each mobile into different categories of price range, i.e., into categorical value of 0 (low), 1 (Medium), 2 (High) and 3 (Very High).

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
## Dataset Information
* **battery_power** - Total energy a battery can store in one time measured in mAh
* **blue** - Has bluetooth or not
* **clock_speed** - speed at which microprocessor executes instructions
* **dual_sim** - Has dual sim support or not
* **fc** - Front Camera mega pixels
* **four_g** - Has 4G or not
* **int_memory** - Internal Memory in Gigabytes
* **m_dep** - Mobile Depth in cm
* **mobile_wt** - Weight of mobile phone
* **n_cores** - Number of cores of the processor
* **pc** - Primary Camera megapixels
* **px_height** - Pixel Resolution Height
* **px_width** - Pixel Resolution Width
* **ram** - Random Access Memory in MegaBytes
* **sc_h** - Screen Height of mobile in cm
* **sc_w** - Screen Width of mobile in cm
* **talk_time** - longest time that a single battery charge will last when you are
* **three_g** - Has 3G or not.
* **touch_screen** - Has touch screen or not
* **wifi** - Has wifi or not
* **price_range** - This is the target variable with value of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost).

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
## Tools used
The programming language used in this project is Python. The following libraries were used for data analysis and data visualization and to build a classifier to predict the price range of mobile phones.

* **Pandas:** For loading the dataset and performing data wrangling
* **Matplotlib:** For data visualization.
* **Seaborn:** For data visualization.
* **WarningsWarnings:** For filtering and ignoring the warnings.
* **NumPy:** For some math operations in predictions.
* **Statsmodels:** For statistical computations
* **Sklearn:** For the purpose of analysis,prediction and evaluation.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
## Steps Performed
* **Data Preprocessing:** Treated incorrect values, missing values (if any), duplicates (if any), and data type corrections.
* **Exploratory Data Analysis:** Performed Univariate, Bivariate and Multivariate analysis with various graphs and plots to better understand the distribution of features and their relationships.
* **Feature Engineering:** Modified and created new features such as screen size, pixels and network and selected important features while discarding those that were irrelevant.
* **Feature Scaling:** Brought features to a similar range using standardScaler.
* **Implementation of Classification models**
* **Hyperparameter tuning**
* **Comparison of models**

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
## Algorithms used
* Random Forest Classfier	
* XGBoost Classifier	
* Support Vector Classifier

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
## Conclusion

#### Conclusion from EDA:
* Expensive phones have more RAM, higher capacity batteries and better pixel resolution.
* Most of the phones have low quality front cameras or do not contain front camera at all.
* Premium price range phones have wider screens and are light-weight as compared to phones in the lower price ranges.

#### Conclusion from Evaluation of Models:
* SVM performed much better than all other models because it has more accurate results and also able to generalize the features much better than others. The accuracy of our best model was 0.95 and 0.9275 for training and test set respectively.
* We also implemented shap techniques to identify the important features impacting our model predictions.
* RAM, pixel resolution (pixel width and pixel height) and battery power are the most important factors that influence the pricing of the mobile phones.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)