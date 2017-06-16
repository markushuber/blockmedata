## EURO S&P 2017
### Block Me If You Can: A Large-Scale Study of Tracker-Blocking Tools

### /data

#### 3rdparty_web_inclusions.csv
Dataset of 123,876 website out of the Alexa Top 200,000 websites.
Values are number of websites where third-party has been requested at least once.
Includes data for the following browser extensions:
 * AdBlock Plus 2.7.3 (default settings)
 * Disconnect 3.15.3 (default settings)
 * Ghostery 6.2.0 (blocking activated)
 * EFF Privacy Badger 0.2.6
(trained with Alexa Top 1,000)
 * uBlock Origin 1.7.0 (default settings)

#### 3rdparty_android.csv
Dataset of 9,061 Android popular Android applications. Values are number applications where
third-party has been requested at least once. Includes data for the following blocking tools:
 * AdblockPlus for Android with EasyList
 * AdAway
 * MoaAB (Mother of all AD-BLOCKING)

#### extension_overhead.csv
Dataset with measurements of CPU and memory consumption of the tested browser extensions.
Values for CPU measurements are per cent of CPU usage, measurements for memory are in MB (initial + during usage).

### example-notebook.ipynb
Contains examples on how to work with our dataset. We recommend [Anaconda3](https://www.continuum.io/downloads) to work with this *jupyter-notebook*.
Examples show how to filter and plot the data with *Python3* and *pandas*.

### [paper.pdf](https://github.com/markushuber/blockmedata/raw/master/paper.pdf)
Preprint of our research paper.
