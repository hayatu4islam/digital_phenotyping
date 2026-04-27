
# 📱 Digital Phenotyping Data Collection

This open source platform is supported by EU MSCA Grant **Affective Computing Models: from Facial Expression to Mind-Reading ("ACMod:101130271")** led by Bournemouth University.

This repository hosts tools, documentation, and sample datasets for the collection of **digital phenotyping data**. Digital phenotyping involves the continuous, real-time measurement of human behavior and health using data from personal digital devices, such as smartphones and wearables.

## Funding
This work is supported by UK Research and Innovation (UKRI) under Grant No. 101130271 and EU Horizon MSCA Grant [ACMod Project](https://sites.google.com/view/acmod-main/MSCA_ACMod?authuser=0)

This website is led by Bournemouth University

School: Computing and Engineering

## 🧠 What is Digital Phenotyping?

Digital phenotyping refers to the moment-by-moment quantification of the individual-level human phenotype using data from digital devices. This includes behavioral, social, mobility, physiological, and environmental signals.

Common data types:
- Accelerometer and gyroscope data
- GPS/location tracking
- Phone usage patterns (calls, screen time, etc.)
- Typing dynamics
- Sleep and activity logs

### Tutorials
* [Artificial intelligence-powered delta-NIHSS-based model for predicting recurrence, disability and mortality after acute ischaemic strokes (DISCO): a modelling study] [Paper](https://www.thelancet.com/journals/eclinm/article/PIIS2589-5370(25)00618-2/fulltext) [Notebook](https://colab.research.google.com/drive/1T9dnB6NRYdJ7Jw45XpX0pD9rFM1HRl1X)
* [Advanced Human Activity Detection using Machine & Deep Learning Methods][Paper](#) [Notebook](https://colab.research.google.com/drive/1DtuT9zbnmrp_SPr2oU6qK416JEn6YZAY#scrollTo=DYMHb_v-v1Te&uniqifier=2)
* [Privacy and utility preserving sensor-data transformations] [Paper](https://www.sciencedirect.com/science/article/pii/S1574119220300201) [Notebook](https://colab.research.google.com/drive/1RYEfv70edFYlKdN9Olw7alXQ78Jrh6vZ#scrollTo=KUPdziofgHw1) [Dataset](https://github.com/mmalekzadeh/motion-sense/tree/master/data)
* [24PanicPrediction][Notebook](https://colab.research.google.com/drive/15qoO5Mv0BhktyzkQTGF4EmudQ49OEdcP#scrollTo=9grGqwNPwDjv) [Dataset](https://github.com/DigitalHealthcareLab/24PanicPrediction/tree/master/data)
* [Explainable Artificial Intelligence] [Dataset](https://drive.google.com/file/d/10HOYqmWz0h6Z__QwXisBBkMDAMttY--3) [Notebook](https://github.com/hayatu4islam/digital_phenotyping/blob/main/Tutorial_Human_Activity_Recognition_LSTM.ipynb)
* [Activity Detection using Motion Sense Dataset(Tutorial in Progress)]()[Paper](https://arxiv.org/pdf/1911.05996.pdf) [Notebook]()
* [Using Mobile Dataset(Tutorial in Progress)]()
* [Human activity recognition using magnetic induction-based motion signals and deep RNN][Paper](https://www.nature.com/articles/s41467-020-15086-2) [Notebook](https://colab.research.google.com/drive/18Si2ViBCKYKqtgTxu-N8jxJ1CGJqtX9j)
* 
---
## 📂 Repository Structure

```
digital-phenotyping-data/
│
├── data/ # Sample anonymized data files<br>
│ ├── accelerometer/
│ ├── gps/
│ └── screen_usage/
│
├── scripts/ # Scripts for data collection and preprocessing
│ ├── mobile_collection/
│ └── preprocessing/
│
├── docs/ # Documentation and protocols
│ └── consent_templates/
│
├── LICENSE
└── README.md
```


## Table of Contents
* [Activity Detection](#activity)
* [Phenotyping](#phenotyping)
* [Mental Health Monitoring](#mental)
* [Sleep Analysis](#sleep)
* [Mobility/Routine Modelling](#mobility)
* [Addiction/Digital Behaviour](#addiction)
* [Social Interaction](#social)
* [Health Outcome Prediction](#health)

## Datasets
### Activity Detection
* [Human Activity Recognition](https://www.utwente.nl/en/eemcs/ps/) - The Complex human activity recognition using smartphone and wrist-worn motion sensors.[[data](https://www.utwente.nl/en/eemcs/ps/)][[paper](https://www.mdpi.com/1424-8220/16/4/426)]
* [Human Activity Recognition using Smartphones](https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones) - A freely available data recorded as a set of ADL in a sensor rich environment using 72 environmental and body sensors. [[data](https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones)][[paper](https://www.esann.org/sites/default/files/proceedings/legacy/es2013-84.pdf)]
* [Human Pedestrian Activity Recognition](http://hub.hasc.jp/) - The authors collected indoor pedestrian sensing data of 107 people with a balance of gender and age. [[data](http://hub.hasc.jp/)] [[paper](https://dl.acm.org/doi/abs/10.1145/2968219.2968277)]
* [Daily life activities](https://www.mad.tf.fau.de/research/activitynet) - This is a hierarchical, multi-sensor based classification. [[data](https://www.mad.tf.fau.de/research/activitynet)][[paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0075196)]
* [Automatic pattern segmentation from accelerometry data](https://github.com/martakarass/adept-manuscript) - A dataset collected at various body locations and is invariant to the direction of accelerometrer axes relative to body orientation involving 32 study participants wearing accelerometers on the wrist, hip, and both ankles. [[paper](https://academic.oup.com/biostatistics/article/22/2/331/5572661)][[data](https://github.com/martakarass/adept-manuscript)]
* [Motion Sense](https://github.com/mmalekzadeh/motion-sense/tree/master) - A time-series dataset generated by accelerometer and gyroscope sensors for human activity and attribute recognition. [[data](https://github.com/mmalekzadeh/motion-sense/tree/master)][[paper](https://dl.acm.org/doi/pdf/10.1145/3302505.3310068)]
* [Fusion of smartphone motion sensors for activity recognition](https://www.utwente.nl/en/eemcs/ps/) - Smartphone sensors collected data for seven physical activities (walking, running, sitting, standing, jogging, biking, walking upstrairs and walking downstairs) from ten participants. [[data](https://www.utwente.nl/en/eemcs/ps/)][[paper](https://www.mdpi.com/1424-8220/14/6/10146?ref=https://githubhelp.com)]
* The dataset includes more than 60,000 video recorded steps for the evaluation of pedometer algorithm to be evaluated across multiple sensor locations (wrist, hip, and ankle). The dataset is collected from thirty participants (15 males & 15 females). [[data]()][[paper](https://ieeexplore.ieee.org/abstract/document/8217769)] [To be removed]
* [Position-Aware Activity Recognition](http://sensor.informatik.uni-mannheim.de/) - The data is collected from 15 participants for 8 common activities from 7 wearable devices in different positions. [[data](http://sensor.informatik.uni-mannheim.de/)][[paper](https://ieeexplore.ieee.org/abstract/document/7456521)]
* [UniMiB SHAR](http://www.sal.disco.unimib.it/technologies/unimib-shar/) - A dataset for human activity recognition using acceleration data from smartphones [[data](http://www.sal.disco.unimib.it/technologies/unimib-shar/)][[paper](https://www.mdpi.com/2076-3417/7/10/1101)]
#### Human Activity Recognition Datasets
<ol>
<li><A HREF="https://github.com/mmalekzadeh/motion-sense">mmalekzadeh/motion-sense: MotionSense Dataset for Human Activity and Attribute Recognition ( time-series data generated by smartphone's sensors: accelerometer and gyroscope)</A>
<li><A HREF="https://www.utwente.nl/en/eemcs/ps/research/dataset/">Research | Datasets | Pervasive Systems group | University of Twente</A>
<li><A HREF="https://sites.google.com/view/mobile-phone-use-dataset/home">Mobile Phone Use Dataset</A>
<li><A HREF="https://zenodo.org/record/841301#.XYi6BpNKhTb">The FORTH-TRACE dataset for human activity recognition of simple activities and postural transitions using a Body Area Network | Zenodo</A>
<li><A HREF="https://archive.ics.uci.edu/datasets?skip=0&take=10&sort=desc&orderBy=NumHits&search=Human+Activity+Recognition+Using+Smartphones">UCI Machine Learning Repository: Smartphone-Based Recognition of Human Activities Dataset</A>
<li><A HREF="http://www.sal.disco.unimib.it/technologies/unimib-shar/">UniMiB SHAR | Sal</A>
<li><A HREF="https://figshare.com/articles/Long_term_activity_recognition_from_watch_accelerometer_data/1029775/2">Long-term activity recognition from watch accelerometer data</A>
<li><A HREF="https://www.kaggle.com/sasanj/human-activity-smart-devices/home">An Open Dataset for Human Activity Analysis | Kaggle</A>
<li><A HREF="https://www.kaggle.com/uciml/human-activity-recognition-with-smartphones/home">Human Activity Recognition with Smartphones | Kaggle</A>
<li><A HREF="http://extrasensory.ucsd.edu/#paper.vaizman2017a">The ExtraSensory Dataset</A>
<li><A HREF="http://archive.ics.uci.edu/ml/datasets/mhealth+dataset#">UCI Machine Learning Repository: MHEALTH Dataset Data Set</A>
<li><A HREF="http://sipi.usc.edu/had/">Human Activities Dataset</A>
<li><A HREF="https://personal.utdallas.edu/~kehtar/UTD-MHAD.html">https://personal.utdallas.edu/~kehtar/UTD-MHAD.html</A>
<li><A HREF="https://github.com/fulviomas/WHARF">fulviomas/WHARF: Wearable Human Activity Recognition Factotum</A>
<li><A HREF="http://www.cis.fordham.edu/wisdm/dataset.php">WISDM Lab: Dataset</A>
<li><A HREF="http://archive.ics.uci.edu/ml/datasets/Smartphone+Dataset+for+Human+Activity+Recognition+%28HAR%29+in+Ambient+Assisted+Living+%28AAL%29">UCI Machine Learning Repository: Smartphone Dataset for Human Activity Recognition (HAR) in Ambient Assisted Living (AAL) Data Set</A>
<li><A HREF="https://data.mendeley.com/datasets/k28lim7tr6/1">Mendeley Data - KARD - Kinect Activity Recognition Dataset</A>
<li><A HREF="https://www.kaggle.com/sasanj/human-activity-smart-devices">An Open Dataset for Human Activity Analysis | Kaggle</A>
<li><A HREF="http://archive.ics.uci.edu/ml/datasets/OPPORTUNITY+Activity+Recognition">UCI Machine Learning Repository: OPPORTUNITY Activity Recognition Data Set</A>
<li><A HREF="https://www.kaggle.com/fschwartzer/tmd-dataset-5-seconds-sliding-window">TMD Dataset - 5 seconds sliding window | Kaggle</A>
<li><A HREF="https://data.mendeley.com/datasets/482jjgrk6d/1">Mendeley Data - UbiComp2012-Berlin</A>
<li><A HREF="https://archive.ics.uci.edu/ml/datasets/daily+and+sports+activities">UCI Machine Learning Repository: Daily and Sports Activities Data Set</A>
<li><A HREF="http://archive.ics.uci.edu/ml/datasets/heterogeneity+activity+recognition">UCI Machine Learning Repository: Heterogeneity Activity Recognition Data Set</A>
<li><A HREF="http://archive.ics.uci.edu/ml/datasets/mhealth+dataset">UCI Machine Learning Repository: MHEALTH Dataset Data Set</A>
<li><A HREF="https://archive.ics.uci.edu/ml/datasets/Daphnet+Freezing+of+Gait">UCI Machine Learning Repository: Daphnet Freezing of Gait Data Set</A>
<li><A HREF="http://har-dataset.org/doku.php?id=wiki:dataset">wiki:dataset [Human Activity/Context Recognition Datasets]</A>
<li><A HREF="http://crowdsignals.io/sample-dataset.html">CrowdSignals.io: A Massive New Mobile Data Collection Campaign</A>
<li><A HREF="http://realitycommons.media.mit.edu/friendsdataset.html">realitycommons.media.mit.edu/friendsdataset.html</A>
<li><A HREF="http://extrasensory.ucsd.edu/">The ExtraSensory Dataset</A>
<li><A HREF="http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones">UCI Machine Learning Repository: Human Activity Recognition Using Smartphones Data Set</A>
<li><A HREF="http://archive.ics.uci.edu/ml/datasets/REALDISP+Activity+Recognition+Dataset">UCI Machine Learning Repository: REALDISP Activity Recognition Dataset Data Set</A>
<li><A HREF="https://archive.ics.uci.edu/ml/datasets/opportunity+activity+recognition">UCI Machine Learning Repository: OPPORTUNITY Activity Recognition Data Set</A>
<li><A HREF="http://archive.ics.uci.edu/ml/datasets/Smartphone-Based%20Recognition%20of%20Human%20Activities%20and%20Postural%20Transitions">UCI Machine Learning Repository: Smartphone-Based Recognition of Human Activities and Postural Transitions Data Set</A>
<li><A HREF="http://archive.ics.uci.edu/ml/datasets/PAMAP2+Physical+Activity+Monitoring">UCI Machine Learning Repository: PAMAP2 Physical Activity Monitoring Data Set</A>
<li><A HREF="https://archive.ics.uci.edu/ml/datasets/Heterogeneity+Activity+Recognition">UCI Machine Learning Repository: Heterogeneity Activity Recognition Data Set</A>
<li><A HREF="https://data.bris.ac.uk/data/dataset/8gccwpx47rav19vk8x4xapcog">The SPHERE Challenge: Activity Recognition with Multimodal Sensor Data - Datasets - data.bris</A>
<li><A HREF="https://github.com/romanchereshnev/HuGaDB">romanchereshnev/HuGaDB: Database for human gait analysis consisting of continues recordings of combined activities, such as walking, running, taking stairs up and down, sitting down, and so on; and the data recorded are segmented and annotated. Data were collected from a body sensor network consisting of six wearable inertial sensors (accelerometer and gyroscope) located on the right and left thighs, shins, and feet. Additionally, two EMG sensors were used on the quadriceps (front thigh) to measure muscle activity.</A>
<li><A HREF="http://sensor.informatik.uni-mannheim.de/index.html#dataset_realworld">Human Activity Recognition</A>
<li><A HREF="https://github.com/njtwomey/har_datasets">njtwomey/har_datasets: A repository for unified analysis of accelerometer-based human activity recognition.</A></li>
</ol>






### Phenotyping
* [Human Activity Recognition](https://) - The Complex human activity recognition using smartphone and wrist-worn motion sensors.[[data](https://www.website.com)]
* [Sleep Quality identification](https://figshare.com/ndownloader/files/14578382) - Data collected to identify sleep quality [[paper](https://www.nature.com/articles/s42003-019-0605-1)][[data](https://figshare.com/ndownloader/files/14578382)]
* 


### Mental Health Monitoring
* [Human Activity Recognition](https://www.utwente.nl/en/eemcs/ps/) - The Complex human activity recognition using smartphone and wrist-worn motion sensors.[[data](https://www.utwente.nl/en/eemcs/ps/)][[paper](https://www.mdpi.com/1424-8220/16/4/426)]
* [Depression dataset](https://zenodo.org/records/1219550) - The dataset contains sensor data collected from patients suffering from depression. It has motor activity recordings of 23 unipolar and bipolar depressed patients and 32 healthy controls. [[paper](


### Sleep Analysis
* [Sleep Quality identification](https://figshare.com/ndownloader/files/14578382) - Data collected to identify sleep quality [[paper](https://www.nature.com/articles/s42003-019-0605-1)][[data](https://figshare.com/ndownloader/files/14578382)]
* 


### Mobility/Routine Modelling
* [Human Activity Recognition](https://www.utwente.nl/en/eemcs/ps/) - The Complex human activity recognition using smartphone and wrist-worn motion sensors.[[data](https://www.utwente.nl/en/eemcs/ps/)][[paper](https://www.mdpi.com/1424-8220/16/4/426)]
* 


### Addiction/Digital Behaviour
* [Human Activity Recognition](https://www.utwente.nl/en/eemcs/ps/) - The Complex human activity recognition using smartphone and wrist-worn motion sensors.[[data](https://www.utwente.nl/en/eemcs/ps/)][[paper](https://www.mdpi.com/1424-8220/16/4/426)]
* 

### Social Interaction
* [Human Activity Recognition](https://www.utwente.nl/en/eemcs/ps/) - The Complex human activity recognition using smartphone and wrist-worn motion sensors.[[data](https://www.utwente.nl/en/eemcs/ps/)][[paper](https://www.mdpi.com/1424-8220/16/4/426)]
* 



### Health Outcome Prediction
* [Human Activity Recognition](https://) - The Complex human activity recognition using smartphone and wrist-worn motion sensors.[[data](https://www.website.com)]
* 




