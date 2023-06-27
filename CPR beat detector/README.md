# CPR beat detector

This project currently allows the general public to upload music or any audio and find portions of song/audio that can be used to perform CPR to, if it exists. This project explored different strategies in which this detection can be done and came up with the most effect strategy.

A sample audio file has been provided [here]() that you can download and check the sanity of the project. Feel free to update audio of your choice and test different scenarios. Currently a webversion of this project is not available and hence the same can be done only in PC.

PC requirements:
 - Python
 - Anaconda software
 - Librosa and ffmpeg python libraries must be downloaded 

To test the correctness of the different strategies both objective and subjective analysis was done. The chosen subjects were doctors, CPR trainers and general public who did or did not undergo CPR training.
A detailed report of the foundings can be found [here]().

Other Notes:
The best performing strategy has been converted into python script using the following command
```jupyter nbconvert --to python BestPerformingStrategy.ipynb```

Thus the python script can be run from command line using the below command
```python BestPerformingStrategy.py "Enrique Iglesias - Cuando Me Enamoro.mp3"```

