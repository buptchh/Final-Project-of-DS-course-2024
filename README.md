# Final-Project-of-DS-course-2024
## Report on Harmful Brain Activity Classification
This work in this repository is part of the final project for the course "Mathematical Foundations for Data Science" at the Beijing University of Posts and Telecommunications.
## Source
This work is based on the Competetion ["Harmful Brain Activity Classification" on Kaggle.](https://www.kaggle.com/competitions/hms-harmful-brain-activity-classification)

## Overview
The goal of this competition is to detect and classify seizures and other types of harmful brain activity. You will develop a model trained on electroencephalography (EEG) signals recorded from critically ill hospital patients.

Your work may help rapidly improve electroencephalography pattern classification accuracy, unlocking transformative benefits for neurocritical care, epilepsy, and drug development. Advancement in this area may allow doctors and brain researchers to detect seizures or other brain damage to provide faster and more accurate treatments.

## File Description
You can find data  [here](https://www.kaggle.com/competitions/hms-harmful-brain-activity-classification/data).

Also you can download them using the following code:

```
>_ kaggle competitions download -c hms-harmful-brain-activity-classification
```
**train.csv** Metadata for the train set. The expert annotators reviewed 50 second long EEG samples plus matched spectrograms covering 10 a minute window centered at the same time and labeled the central 10 seconds. Many of these samples overlapped and have been consolidated. provides the metadata that allows you to extract the original subsets that the raters annotated.`train.csv`
**test.csv** Metadata for the test set. As there are no overlapping samples in the test set, many columns in the train metadata don't apply.

**train_eegs**/ EEG data from one or more overlapping samples. Use the metadata in train.csv to select specific annotated subsets. The column names are the names of the individual electrode locations for EEG leads, with one exception. The EKG column is for an electrocardiogram lead that records data from the heart. All of the EEG data (for both train and test) was collected at a frequency of 200 samples per second.

**test_eegs**/ Exactly 50 seconds of EEG data.

**train_spectrograms**/ Spectrograms assembled EEG data. Use the metadata in train.csv to select specific annotated subsets. The column names indicate the frequency in hertz and the recording regions of the EEG electrodes. The latter are abbreviated as LL = left lateral; RL = right lateral; LP = left parasagittal; RP = right parasagittal.

**test_spectrograms**/ Spectrograms assembled using exactly 10 minutes of EEG data.

**example_figures**/ Larger copies of the example case images used on the overview tab.

## Tech used:
- PyTorch
- Typst
- LaTeX

## About
Notice that the data of this project is recreated and you can download it with clicking [here](https://pan.baidu.com/s/1QTXUrQwJIQiYhzX_ZVM43Q?pwd=e604 
).

There are two notebooks in this repository, one train and the other submit.

## Bibliography
See in the `source.bib` file.
