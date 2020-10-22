# Urban_Sound_classification
The programmed content-based order of urban sound classes is a significant part of different developing methods and applications, for example, observation, urban soundscape comprehension and commotion source distinguishing proof, along these lines the exploration subject has increased a great deal of consideration lately. The point of this paper is to create a proficient AI based plan for urban sound classification. Ongoing fruitful utilizations of convolutional neural systems (CNNs) to sound order and discourse acknowledgment have spurred the quest for better information portrayals for progressively proficient preparation. Visual presentations of a sound signal, through different time-recurrence portrayals, for example, spectrograms offer a very good representation of the worldly picture of the original signal. Utilizing a spectrogram picture of the sound and afterward changing over the equivalent to information focuses (As is accomplished for pictures). This is effortlessly done utilizing mel_spectogram a function of Librosa. At the approval stage, we lead tests on Urban Sound 8K database which comprises 10 classes of urban sound happenings with 8732 real-world sound clips. As a result, We see how convolutional neural network(CNN) frameworks with raw sound waveforms improve the exactness in urban sound classification and clearly shows the structure concerning the amount of parameters.



For the evaluation of our method, we use UrbanSound8k dataset. The dataset consists of 10 environmental sounds excerpts from urban area such as air conditioner, car horn, children playing, dog bark, drilling, engine idling, gun shot, jackhammer, siren and street music. It contains 8732 labeled sound samples excerpts of up to 4 seconds duration, 9.7 hours in total. The sound files are accompanied with a .csv file that contains the description of the sound files. 


  <img src="https://github.com/TanishqSehgal7/Urban-Sound-Classification/blob/main/UrbanSoundClassificationImages/dataset.jpeg" width="500" height="300">


Following are some of the plots obtained from the user defined function 'Wave Plotter'

<img src="https://github.com/TanishqSehgal7/Urban-Sound-Classification/blob/main/UrbanSoundClassificationImages/audio_plot1.jpeg" width="350" height="250">


<img src="https://github.com/TanishqSehgal7/Urban-Sound-Classification/blob/main/UrbanSoundClassificationImages/audio_plot2.jpeg" width="350" height="250">


<img src="https://github.com/TanishqSehgal7/Urban-Sound-Classification/blob/main/UrbanSoundClassificationImages/audio_plot3.jpeg" width="350" height="250">


<img src="https://github.com/TanishqSehgal7/Urban-Sound-Classification/blob/main/UrbanSoundClassificationImages/audio_plot4.jpeg" width="350" height="250">


Following are the spectrogram plots of different sound waves. Plot values of these spectrograms have been passed through the convolution layer to categorise the class of the sound clip.


<img src="https://github.com/TanishqSehgal7/Urban-Sound-Classification/blob/main/UrbanSoundClassificationImages/spectrogram1.jpeg" width="350" height="250">


<img src="https://github.com/TanishqSehgal7/Urban-Sound-Classification/blob/main/UrbanSoundClassificationImages/spectrogram2.jpeg" width="350" height="250">


<img src="https://github.com/TanishqSehgal7/Urban-Sound-Classification/blob/main/UrbanSoundClassificationImages/spectrogram2.jpeg" width="350" height="250">


<img src="https://github.com/TanishqSehgal7/Urban-Sound-Classification/blob/main/UrbanSoundClassificationImages/spectrogram3.jpeg" width="350" height="250">


<img src="https://github.com/TanishqSehgal7/Urban-Sound-Classification/blob/main/UrbanSoundClassificationImages/spectrogram4.jpeg" width="350" height="250">


<img src="https://github.com/TanishqSehgal7/Urban-Sound-Classification/blob/main/UrbanSoundClassificationImages/spectrogram5.jpeg" width="350" height="250">



The accuracy of the CNN model is obtained as :


<img src="https://github.com/TanishqSehgal7/Urban-Sound-Classification/blob/main/UrbanSoundClassificationImages/accuracy.jpeg" width="350" height="250">
