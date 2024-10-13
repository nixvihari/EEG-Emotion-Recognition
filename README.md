### EEG based Emotion Recognition using Deep Learning

In this project we used EEG data to train a model that is capabale of classifying emotions.

- EEG Data consists of time series recordings of brain wave activity.
- This brain wave activity is detemined by voltage changes in the brain, captured by sensors placed on top of the head.
- Depending on the brain waves' frequency, we can classifying an associated emotion.
- Brain waves are classified into Delta, Alpha, Beta, Theta and Gamma waves and each indicate an associated emotion.

- DEAP dataset was chosen for this project. This is in a 3D numpy array format, with 32 participants, each participant having 40 channels of time seriesdata points.
- Only selected sensor placement maxiamlly determine the relevant brain wave activity and hence, we filter, sample, and use the most relevant data.
- The flattened data is then fed to LSTM model, used to capture time series patterns. 
- Standalone algorithms such as wavelet transform is used to analyse patterns in EEG data.

