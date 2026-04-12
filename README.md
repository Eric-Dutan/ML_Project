#SVM_MODEL
Ok so can you fine tune my little write up: So this model is using SVM which is a supervised learning technique. We first take our data, and for each audio file, we do something called the MFCC which is mell freq Cepstral Coefficients. 
This caputes data from teh audio signal such as pitch, tone, speech characteristics. Form this we create features such as mean and std. for each audio signal we take this and map it to a label. Now after doing this for each audio signal, we split it 80/20. to train with 80% of 
the data and to test with 20%. we use a SVM model which attempts to draw boundaries ebtween classes with the largest seperation possible. Then we just put in the other 20% of data to test. Now when we demo it, youll see that an image will pop up. This is a graph showing my voice in time with the MFCC coefficients for pitch, tone, speech characteristics. 
This is with time, but when we create our features from this we lose time perspective. SO SVM can only group what is there. But CNN can learn from the images from a spectrogram to get a better sense. 
This is why SVM is worse off and even in the demo, words that are similar like no and go get mixed up.
